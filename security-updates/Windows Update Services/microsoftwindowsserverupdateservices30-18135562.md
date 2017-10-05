---
TOCTitle: 'Microsoft Windows Server Update Services 3.0 릴리스 정보'
Title: 'Microsoft Windows Server Update Services 3.0 릴리스 정보'
ms:assetid: '94d1385f-4872-4c29-8822-3a4ec5e45ae4'
ms:contentKeyID: 18135562
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc708491(v=WS.10)'
---

Microsoft Windows Server Update Services 3.0 릴리스 정보
========================================================

이 릴리스 정보에서는 Microsoft® Windows® Server Update Services(WSUS) 3.0에 영향을 미치는 알려진 문제에 대해 설명하고 응용 프로그램 설치 권장 사항과 요구 사항을 제공합니다. 이 정보는 다음 섹션으로 이루어집니다.

-   WSUS 3.0 서버 설치의 시스템 요구 사항
-   WSUS 3.0 서버 설치의 구성 요구 사항
-   WSUS 3.0 원격 콘솔 설치의 시스템 요구 사항
-   WSUS 3.0 원격 콘솔의 구성 요구 사항
-   클라이언트 설치 시스템 요구 사항
-   WSUS 3.0 서버 설치의 소프트웨어 요구 사항
-   WSUS 3.0 서버 설치의 최소 디스크 공간 요구 사항
-   WSUS 3.0 업그레이드 요구 사항
-   설치 명령줄 매개 변수
-   설치 및 업그레이드 문제
-   알려진 문제
-   Windows Server® 2008의 WSUS 3.0
-   Windows Small Business Server 2003의 WSUS 3.0

| ![](images/Cc708491.note(WS.10).gif)참고                                                                                                                                                        |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 이 설명서의 복사본은 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=71220)([http://go.microsoft.com/fwlink/?LinkId=71220](http://go.microsoft.com/fwlink/?linkid=71220))(영문)에서 다운로드할 수 있습니다. |

중요한 구성 문제: 구성 마법사에서 프록시 서버 암호를 덮어써야 합니다.
---------------------------------------------------------------------

사용자 이름/암호 인증이 필요한 프록시 서버를 사용하는 경우, WSUS 서버 구성 마법사를 실행할 때 프록시 서버 암호를 덮어쓰지 않으면 WSUS 서버가 업데이트를 동기화하지 못할 수도 있습니다. 구성 마법사는 설치 마지막 단계에 자동 실행되므로, 이전 버전의 WSUS에서 WSUS 3.0으로 업그레이드한 후 동기화 오류가 발생할 수 있습니다.

업그레이드한 후 구성 마법사를 취소하거나, 구성 마법사를 실행할 때 올바른 프록시 암호를 다시 입력하여 이러한 문제를 방지할 수 있습니다. 문제 발생 후 이 문제를 복구하려면, **옵션** 페이지에 있는 **업데이트 원본 및 프록시 서버**로 가서, 프록시 암호를 다시 입력한 다음 설정을 저장하십시오.

WSUS 3.0 서버 설치의 시스템 요구 사항
-------------------------------------

#### WSUS 3.0 서버는 Windows Server 2003 서비스 팩 1 및 Windows Server 2008에서 지원됩니다.

WSUS 3.0 서버는 Windows Server 2003 서비스 팩 1 및 Windows Server 2008에서 지원됩니다.

#### WSUS 3.0 서버는 Windows 2000 Server에서 지원되지 않습니다.

Microsoft Windows® 2000 Server는 WSUS 3.0 서버에서 지원되는 운영 체제가 아닙니다.

#### 터미널 서비스를 실행하는 서버에서 WSUS 3.0이 지원되지 않음

WSUS 3.0이 터미널 서비스를 실행하는 서버에서 여전히 작동될 수 있지만, 이를 지원하거나 권장하지는 않습니다. WSUS 3.0은 원격 SQL Server 구현을 사용하여 구성의 터미널 서비스를 실행하는 서버에서 작동되지 않을 것입니다. 터미널 서버 라이선스 서버의 모든 원격 사용자 지정 작업(설치 포함)이 시스템 계정으로 실행되고 서버의 시스템 계정에 원격 SQL Server에 대한 권한이 없을 수 있기 때문에 설치에 실패할 수 있습니다.

WSUS 3.0 서버 설치의 구성 요구 사항
-----------------------------------

#### IIS를 설치해야 함

Microsoft Windows Server Update Services 3.0을 설치하려면 Microsoft Windows Server 2003 또는 Windows Server 2008과 함께 기본적으로 설치되지 않는 인터넷 정보 서비스(IIS)가 필요합니다. IIS 없이 WSUS 3.0을 설치하려고 하면, Windows Server Update Services 설치 프로그램은 IIS가 설치되어 있지 않다는 오류 메시지를 표시합니다.

#### IIS가 IIS 5.0 격리 모드에서 실행 중일 경우 설치되지 않습니다.

Windows 2000 Server에서 Windows Server 2003로 서버를 업그레이드한 경우, IIS는 IIS 5.0 호환 모드로 실행될 수 있습니다. IIS 관리자에서 IIS 5.0 격리 모드를 사용할 수도 있습니다. 이는 설치 실패의 원인이 될 수 있습니다. WSUS 3.0 설치 전 IIS 5.0 격리 모드를 사용하지 않도록 설정해야 합니다.

#### IIS 구성 요소가 64비트 플랫폼에서 32비트 호환 모드로 설치되어 있으면 WSUS 3.0 설치에 실패할 수 있음

모든 IIS 구성 요소는 64비트 플랫폼에서 기본 모드로 설치되어야 합니다. IIS 구성 요소가 32비트 호환 모드로 설치되어 있으면 설치에 실패할 수 있습니다.

#### 프록시 서버가 HTTP 및 HTTPS를 모두 지원해야 함

루트 WSUS 서버(Microsoft Update에서 업데이트를 직접 가져오는 WSUS 서버)를 구성할 때 프록시 서버를 사용하여 WSUS 서버와 Internet 간을 연결하는 경우 이 프록시 서버는 HTTP 및 HTTPS 모두를 지원해야 합니다.

#### 둘 이상의 웹 사이트가 이미 포트 80에서 실행 중인 경우, 모두 삭제하되 그 중 한 개는 WSUS를 설치하기 전에 삭제해야 합니다.

둘 이상의 웹 사이트가 이미 포트 80에서 실행 중인 경우(예: Windows® SharePoint® Services), 모두 삭제하되 그 중 한 개는 WSUS를 설치하기 전에 삭제해야 합니다. 그러지 않으면, 서버의 클라이언트가 자동 업데이트에 실패할 수 있습니다.

#### WSUS 3.0을 설치할 때 바이러스 백신 프로그램을 사용할 수 없게 설정해야 할 수 있음

WSUS 3.0을 설치할 때 성공적으로 설치하려면 바이러스 백신 프로그램을 사용할 수 없게 설정해야 할 수 있습니다. 바이러스 백신 프로그램을 사용할 수 없게 설정한 경우, WSUS 설치 전에 컴퓨터를 다시 시작하십시오. 컴퓨터를 다시 시작하면 설치 작업에서 액세스해야 하는 파일이 잠기지 않습니다. 설치가 완료되면 바이러스 백신 프로그램을 다시 사용할 수 있게 설정해야 합니다. 바이러스 백신 프로그램과 버전을 사용 및 사용할 수 없게 설정하는 정확한 단계를 알아보려면 바이러스 백신 프로그램 공급업체의 웹 사이트를 방문하십시오.

| ![](images/Cc708491.Caution(WS.10).gif)주의                                                                                                                                                                                                                                                |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 이 방법을 사용하면 컴퓨터나 네트워크가 악의적인 사용자나 바이러스와 같은 악의적인 소프트웨어의 공격에 더 취약해질 수 있습니다. Microsoft는 이 방법을 권장하지 않지만 사용자 자신이 판단하여 이 해결 방법을 구현할 수 있도록 하기 위해 이 정보를 제공합니다. 이 해결 방법의 사용에 따른 모든 문제는 사용자의 책임입니다. |

| ![](images/Cc708491.note(WS.10).gif)참고                                                                                                                                                                                                                                |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 바이러스 백신 프로그램은 바이러스로부터 컴퓨터를 보호하기 위해 설계되었습니다. 신뢰하지 않는 출처의 파일을 다운로드하거나 열지 않아야 하며 신뢰하지 않는 웹 사이트를 방문하지 않아야 합니다. 또한 바이러스 백신 프로그램이 사용할 수 없게 설정되어 있을 때 전자 메일 첨부 파일을 열지 않아야 합니다. |

#### WSUS 3.0을 사용하려면 SQL Server에서 중첩 트리거 옵션을 설정해야 함

중첩 트리거 옵션은 기본적으로 설정되어 있습니다. 그러나 SQL Server 관리자가 이 옵션을 해제할 수 있습니다.

SQL Server 데이터베이스를 Windows Server Update Services 데이터 저장소로 사용할 계획이면 WSUS 3.0 관리자가 WSUS 3.0을 설치하고 설치 중에 데이터베이스를 지정하기 전에 SQL Server 관리자가 서버에 중첩 트리거 옵션이 설정되어 있는지 확인해야 합니다.

WSUS 3.0 설치 프로그램에서는 데이터베이스 고유 옵션인 RECURSIVE\_TRIGGERS 옵션을 설정합니다. 하지만 서버 전역 옵션인 중첩 트리거 옵션은 설정하지 않습니다.

중첩 트리거 옵션이 설정되어 있는지 확인하려면 다음을 사용하십시오.

**sp\_configure 'nested triggers'**

SQL Server에서 중첩 트리거 옵션을 설정하려면 SQL Server를 실행하는 컴퓨터의 배치 파일에서 다음을 실행하십시오.

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

서버에 SQL Server Management Studio가 없으면 명령줄에서 SQL 스크립트를 실행할 수 있습니다. [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=70728)(http://go.microsoft.com/fwlink/?LinkId=70728)에서 Microsoft SQL Server 2005 명령줄 쿼리 유틸리티를 다운로드할 수 있습니다. 이 페이지는 영문일 수 있습니다. 시작하려면 **sqlcmd**를 실행하십시오.

Windows 내부 데이터베이스에 대한 SQL 스크립트를 실행하려면, 동일한 다운로드 페이지에서 SQL Native Client를 다운로드해야 합니다.

#### 원격 SQL 제한 사항 및 요구 사항

WSUS 3.0은 나머지 WSUS 3.0 응용 프로그램이 있는 컴퓨터와 분리된 컴퓨터에서 데이터베이스 소프트웨어를 실행하는 작업을 지원합니다. 원격 SQL 설치 구성에 대한 몇 가지 요구 사항이 있습니다.

-   원격 SQL 쌍의 백 엔드에 대해 도메인 컨트롤러로 구성된 서버를 사용할 수 없습니다.
-   원격 SQL 설치의 프런트 엔드 서버가 될 컴퓨터에서 터미널 서비스를 실행하고 있지 않아야 합니다.
-   컴퓨터에서 Windows Server® 2008을 실행하고 있는 경우, 백 엔드 컴퓨터에서 Windows Server 2003 또는 SQL Server 2005 서비스 팩 2를 실행하고 있다면 데이터베이스 소프트웨어로 최소 Microsoft SQL Server 2005 서비스 팩 1 이상의 사양을 사용하여야 합니다(http://go.microsoft.com/fwlink/?LinkId=66143의 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=66143)에서 사용 가능) .
-   프런트 엔드와 백 엔드 컴퓨터 모두 Active Directory 도메인에 가입되어 있어야 합니다. 그렇지 않으면, 다른 도메인에 있는 경우, WSUS 설치 프로그램을 실행하기 전에 도메인 간 교차 도메인 트러스트를 설정해야 합니다.
-   원격 SQL 구성에 WSUS 2.0을 이미 설치한 경우 WSUS 3.0으로 업그레이드하려면 기존 데이터베이스는 그대로 유지하면서 백 엔드 컴퓨터에서 WSUS 2.0을 제거해야 합니다(제어판의 **프로그램 추가/제거** 사용). 그런 다음 SQL Server 2005 SP1 또는 SP2를 설치하고 기존 데이터베이스를 업그레이드해야 합니다. 마지막으로 프런트 엔드 컴퓨터에 WSUS 3.0을 설치합니다.

#### 특정 시험판 버전의 Internet Explorer 7과 Terminal Services가 설치되어 있는 경우 WSUS를 설치할 수 없음

특정 시험판 버전의 Internet Explorer 7이 Terminal Services와 함께 설치되어 있는 경우에는 WSUS 설치가 실패합니다.

WSUS 3.0 원격 콘솔 설치의 시스템 요구 사항
------------------------------------------

WSUS 3.0 원격 콘솔은 다음과 같은 플랫폼에 설치할 수 있습니다.

-   Windows Server 2008
-   Windows Vista®
-   Windows Server 2003 SP1
-   Windows XP SP2

WSUS 3.0 원격 콘솔의 구성 요구 사항
-----------------------------------

#### 원격 관리 콘솔과 WSUS 3.0 서버 간에 광대역 연결을 사용해야 합니다.

협대역 WAN 연결을 통해 원격 관리 콘솔로 WSUS 3.0 서버를 연결할 경우, 성능 문제가 발생할 수 있습니다. 업데이트와 컴퓨터 보기를 필터링하여 표시되는 업데이트와 컴퓨터 수를 제한할 수 있으나, 원격 관리 콘솔과 WSUS 3.0 서버 간에는 광대역 연결을 사용하는 것이 좋습니다. 원격 콘솔에 성능 문제가 발생하는 경우, 원격 관리를 위해 터미널 서버를 사용하여 서버에 연결하는 것이 좋습니다.

클라이언트 설치 시스템 요구 사항
--------------------------------

자동 업데이트는 WSUS 클라이언트 소프트웨어입니다. 다음 운영 체제 중 하나에서 WSUS와 함께 사용할 수 있습니다.

-   Windows Vista
-   Windows Server 2008
-   Microsoft Windows Server 2003, 모든 버전
-   Microsoft Windows XP Professional SP2
-   Microsoft Windows 2000 Professional SP4, Windows 2000 Server SP4, 또는 Windows 2000 Advanced Server SP4

WSUS 3.0 서버 설치의 소프트웨어 요구 사항
-----------------------------------------

다음 표에는 Windows Server 2003 SP1 플랫폼의 필수 소프트웨어가 나와 있습니다. Windows Server 2008에 대한 필수 소프트웨어는 Windows Server 2008의 WSUS 3.0을 다루는 섹션에서 함께 설명합니다.

WSUS 3.0 설치 프로그램을 실행하기 전에 WSUS 3.0 서버가 이 요구 사항 목록을 충족하는지 확인하십시오. 설치가 완료될 때 컴퓨터를 다시 시작해야 하는 업데이트가 있는 경우 WSUS 3.0을 설치하기 전에 컴퓨터를 다시 시작해야 합니다.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >요구 사항</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft 인터넷 정보 서비스(IIS)</td>
<td style="border:1px solid black;">운영 체제에서 설치합니다.
&quot;문제 1: IIS를 설치해야 함&quot;을 참조하십시오.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft .NET Framework 버전 2.0 재배포 가능 패키지(x86)</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=68935">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=68935)에서 Microsoft .NET Framework 버전 2.0 재배포 가능 패키지(x86)를 참조하십시오. 이 페이지는 영문일 수 있습니다. 64비트 플랫폼의 경우 <a href="http://go.microsoft.com/fwlink/?linkid=70637">Microsoft 다운로드 센터</a> (http://go.microsoft.com/fwlink/?LinkId=70637)에서 Microsoft .NET Framework 버전 2.0 재배포 가능 패키지(x64)를 참조하십시오. 이 페이지는 영문일 수 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003용 Microsoft Management Console 3.0</td>
<td style="border:1px solid black;">WSUS 3.0 UI를 사용하기 위한 필수 구성 요소입니다. <a href="http://go.microsoft.com/fwlink/?linkid=70412">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=70412)에서 Windows Server 2003용 Microsoft Management Console 3.0(KB907265)을 참조하십시오. 이 페이지는 영문일 수 있습니다. 64비트 플랫폼의 경우 <a href="http://go.microsoft.com/fwlink/?linkid=70638">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=70638)에서 Windows Server 2003 x64 Edition용 Microsoft Management Console 3.0(KB907265)을 참조하십시오. 이 페이지는 영문일 수 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">WSUS 3.0 UI를 사용하기 위한 필수 구성 요소입니다. <a href="http://go.microsoft.com/fwlink/?linkid=70410">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=70410)에서 Microsoft Report Viewer 재배포 가능 패키지 2005를 참조하십시오. 이 페이지는 영문일 수 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2005(옵션)</td>
<td style="border:1px solid black;">SQL Server와 호환되는 버전이 이미 설치되어 있지 않은 경우 WSUS 3.0에서 Windows 내부 데이터베이스를 설치합니다. 전체 SQL Server 데이터베이스를 사용할 계획이라면 Windows Server 2003의 경우에는 <a href="http://go.microsoft.com/fwlink/?linkid=66143">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=66143)에서 다운로드할 수 있는 SQL Server 2005 SP1 이상을 사용하거나(최소 사양), Windows Server 2008의 경우에는 <a href="http://go.microsoft.com/fwlink/?linkid=84823">Microsoft 다운로드 센터</a> (http://go.microsoft.com/fwlink/?LinkId=84823)에서 다운로드할 수 있는 SQL Server 2005 SP2를 사용해야 합니다.</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc708491.note(WS.10).gif)참고                                                                                                                                                                                                                                            |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 이전에 설치한 WSUS 2.0이 SQL Server 2000, SQL Server Desktop Engine 2000 또는 SQL Server 2005 SP1(또는 Windows Server 2008의 SQL Server 2005 SP2) 이전 버전의 SQL Server 데이터베이스를 사용하는 경우 WSUS 3.0 설치 프로그램을 실행하면 Windows® 내부 데이터베이스가 설치되고 데이터베이스가 마이그레이션됩니다. |
  
WSUS 3.0 서버 설치의 최소 디스크 공간 요구 사항  
-----------------------------------------------
  
다음은 Windows Server Update Services를 설치하기 위한 최소 디스크 공간 요구 사항입니다.
  
-   시스템 파티션 1GB  
-   데이터베이스 파일을 저장하기 위한 2GB  
-   콘텐츠를 저장하기 위한 볼륨 20GB
  
| ![](images/Cc708491.Important(WS.10).gif)중요                            |  
|-------------------------------------------------------------------------------------------------------|  
| 압축 드라이브에는 WSUS 3.0을 설치할 수 없습니다. 선택한 드라이브가 압축되어 있지 않은지 확인하십시오. |
  
WSUS 3.0 업그레이드 요구 사항  
-----------------------------
  
#### WSUS가 제대로 실행되고 있는지 확인하고 WSUS 데이터베이스를 백업한 후에 업그레이드
  
이전 버전에서 WSUS 3.0으로 업그레이드하는 경우 현재 설치가 올바르게 실행되고 있는지 확인하고 WSUS 데이터베이스를 백업한 후에 업그레이드하십시오.
  
1.  이벤트 로그에서 최근에 발생한 오류를 확인하고 다운스트림 서버와 업스트림 서버 간의 동기화 문제 또는 보고하지 않은 클라이언트 문제를 확인하십시오. 계속 진행하기 전에 이러한 문제가 해결되었는지 확인하십시오.  
2.  WSUS 데이터베이스가 올바르게 색인화되도록 DBCC CHECKDB를 실행할 수 있습니다. CHECKDB에 대한 자세한 내용은 [DBCC CHECKDB](http://go.microsoft.com/fwlink/?linkid=86948)(http://go.microsoft.com/fwlink/?LinkId=86948)(영문)를 참조하십시오.  
3.  WSUS 데이터베이스를 백업하십시오.
  
#### Software Update Services 1.0을 제거해야 함
  
Software Update Services 1.0이 동일한 컴퓨터에 설치되어 있으면 WSUS 3.0의 설치에 실패합니다. WSUS 3.0을 설치하기 전에 Software Update Services 1.0을 제거해야 합니다.
  
#### WSUS 3.0 베타 버전에서 WSUS 3.0 RTM 버전으로의 업그레이드는 지원되지 않지만 RC 버전에서 RTM 버전으로의 업그레이드는 지원됨
  
WSUS 3.0의 베타 버전을 이미 설치한 경우 WSUS 3.0의 RTM 버전을 설치하기 전에 베타 버전을 제거하고 데이터베이스를 삭제해야 합니다. RC 버전에서만 RTM 버전으로 업그레이드할 수 있습니다.
  
#### 64 비트 운영 체제에서 WSUS 2.0에서 WSUS 3.0으로 업그레이드할 수 없음
  
WSUS 2.0는 64비트 운영 체제에서 지원되지 않습니다. 따라서 64 비트 체제에서는 WSUS 2.0에서 WSUS 3.0으로 업그레이드할 수 없습니다.
  
설치 명령줄 매개 변수  
---------------------
  
WSUS 명령줄 매개 변수를 사용하여 WSUS 3.0을 무인 설치할 수 있습니다. 다음 표에는 WSUS 3.0의 명령줄 매개 변수가 표시되어 있습니다.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >옵션</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>/q</strong></td>
<td style="border:1px solid black;">자동으로 설치합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/u</strong></td>
<td style="border:1px solid black;">제품을 제거합니다. Windows 내부 데이터베이스 인스턴스가 설치되어 있는 경우 해당 인스턴스도 제거합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/p</strong></td>
<td style="border:1px solid black;">필수 구성 요소만 검사합니다. 제품을 설치하지 않지만 시스템을 검사하고 누락된 필수 구성 요소를 보고합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/?, /h</strong></td>
<td style="border:1px solid black;">명령줄 매개 변수와 해당 설명을 표시합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/g</strong></td>
<td style="border:1px solid black;">WSUS 2.0 버전에서 업그레이드합니다. 이 옵션에 사용할 수 있는 매개 변수는 /q(자동 설치)뿐입니다. 이 옵션에 사용할 수 있는 속성은 DEFAULT_WEBSITE뿐입니다.</td>
</tr>
</tbody>
</table>
  
다음 표에는 WSUS 3.0의 명령줄 속성이 표시되어 있습니다.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >속성</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">CONTENT_LOCAL</td>
<td style="border:1px solid black;">0=로컬로 호스팅되는 콘텐츠, 1=Microsoft Update에서 호스팅</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CONTENT_DIR</td>
<td style="border:1px solid black;">콘텐츠 디렉터리의 경로입니다. 기본 경로는 <em>WSUSInstallationDrive</em><strong>\WSUS\WSUSContent</strong>입니다. <em>WSUSInstallationDrive</em>는 사용 가능한 최대 공간을 가진 로컬 드라이브입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WYUKON_DATA_DIR</td>
<td style="border:1px solid black;">Windows 내부 데이터베이스 데이터 디렉터리 경로입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQLINSTANCE_NAME</td>
<td style="border:1px solid black;">이름은 <em>ServerName</em>\<em>SQLInstanceName</em> 형식이어야 합니다. 데이터베이스 인스턴스가 로컬 컴퓨터에 있는 경우에는 %COMPUTERNAME% 환경 변수를 사용합니다. 기존 인스턴트가 없는 경우 기본값은 %COMPUTERNAME%\WSUS입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DEFAULT_WEBSITE</td>
<td style="border:1px solid black;">0=포트 8530, 1=포트 80</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PREREQ_CHECK_LOG</td>
<td style="border:1px solid black;">로그 파일의 경로 및 파일 이름</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CONSOLE_INSTALL</td>
<td style="border:1px solid black;">0=WSUS 서버 설치, 1=콘솔만 설치</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ENABLE_INVENTORY</td>
<td style="border:1px solid black;">0=인벤토리 기능 설치 안 함, 1=인벤토리 기능 설치</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_DATABASE</td>
<td style="border:1px solid black;">0=데이터베이스 보존, 1=데이터베이스 제거</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DELETE_CONTENT</td>
<td style="border:1px solid black;">0=콘텐츠 파일 보존, 1=콘텐츠 파일 제거</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_LOGS</td>
<td style="border:1px solid black;">0=로그 파일 유지, 1=로그 파일 제거(/u 설치 스위치에 사용).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATE_DATABASE</td>
<td style="border:1px solid black;">0=현재 데이터베이스 사용, 1=데이터베이스 작성</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROGRESS_WINDOW_HANDLE</td>
<td style="border:1px solid black;">MSI 진행률 메시지를 반환하는 창 핸들</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MU_ROLLUP</td>
<td style="border:1px solid black;">1=Microsoft Update 개선 프로그램 참여, 0=참여하지 않음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">FRONTEND_SETUP</td>
<td style="border:1px solid black;">1=데이터베이스에 콘텐츠 위치를 쓰지 않음, 0=데이터베이스에 콘텐츠 위치를 씀(NLB)</td>
</tr>
</tbody>
</table>
  
#### 샘플 사용법
  
```  
WSUSSetup.exe /q DEFAULT\_WEBSITE=0 (install in quiet mode using port 8530) WSUSSetup.exe /q /u (uninstall WSUS)  
```  
| ![](images/Cc708491.Important(WS.10).gif)중요                                                                                                   |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| WSUS 3.0을 자동 모드(/q)로 설치하는 경우 컴퓨터에 모든 필수 구성 요소가 설치되어 있지 않으면 설치 시 WSUSPreReqCheck.xml이라는 파일이 생성되어 %TEMP% 디렉터리에 저장됩니다. |
  
설치 문제  
---------
  
#### IIS가 WSUS 3.0 설치 중에 다시 시작됨
  
WSUS 3.0 설치 중에 알림 없이 IIS가 다시 시작됩니다. 이 때문에 조직에 있는 기존 웹 사이트가 영향을 받을 수 있습니다. IIS가 실행되고 있지 않으면 WSUS 3.0 설치 프로그램이 IIS를 시작합니다.
  
#### 기존 WSUS 데이터베이스에 대한 연결이 열려 있으면 설치에 실패할 수 있음
  
기존 설치에서 WSUS 3.0으로 업그레이드하는 경우 기존 WSUS 데이터베이스에 대한 연결이 여전히 열려 있으면(예: SQL Server Management Studio가 열려 있으면) 설치에 실패할 수 있습니다. 이러한 경우 모든 연결을 닫고 WSUS 3.0을 다시 설치하십시오.
  
#### WSUS 설치 프로그램에서 지정하는 데이터베이스 파일용 디렉터리가 잘못됨
  
WSUS 설치 프로그램의 **설치 준비** 화면에서 데이터베이스 위치의 상위 디렉터리가 데이터베이스 위치라고 보고되지만 이는 잘못된 것입니다. 예를 들어 기본 위치는 %systemdrive%\\WSUS\\UpdateServicesDbFiles인데 %systemdrive%\\WSUS인 것으로 잘못 나타납니다.
  
#### WSUS가 설치된 시스템에 기본 언어가 영어가 아닌 MUI(Multilingual User Interface) 언어 팩이 있는 경우 도움말이 영어가 아닌 기본 언어로 표시됨
  
기본 언어가 영어가 아닌 MUI(Multilingual User Interface) 언어 팩이 있는 시스템에서는 현재 사용자의 로캘이 영어인 경우에도 WSUS를 설치할 수 있습니다. UI는 영어로 표시되지만 도움말을 영어로 표시하려면 별도의 해결 방법을 사용해야 합니다. 영문 도움말 .chm 파일(*WSUSInstallDir*\\documentation\\mui\\0409\\WSUS30Help.chm)을 기본 문서 디렉터리(*WSUSInstallDir*\\documentation\\WSUS30Help.chm)에 복사하십시오. 이제 도움말이 모든 언어로 올바르게 표시됩니다.
  
업그레이드 문제  
---------------
  
#### WSUS 3.0 RC에서 WSUS 3.0 RTM으로 업그레이드하면 SSL 인증서가 WSUS 웹 사이트에 할당되지 않음
  
WSUS 3.0 RC에서 WSUS 3.0 RTM으로 업그레이드하는 동안 WSUS 웹 사이트는 삭제되고 새 웹 사이트가 생성됩니다. 그에 따라 SSL 인증서는 더 이상 WSUS 웹 사이트에 할당되지 않습니다. 업그레이드한 후 인증서를 다시 할당해야 합니다.
  
#### 실패한 업그레이드에서 복구
  
WSUS 2.0에서 WSUS 3.0으로 업그레이드할 때 업그레이드에 실패하면 WSUS 2.0을 다시 설치하고 데이터베이스를 백업에서 복원해야 합니다.
  
#### 이전 설치에 WSUS 3.0 데이터베이스가 있으면 WSUS 2.0에서 WSUS 3.0으로 업그레이드할 수 없음
  
이전에 WSUS 3.0을 설치한 다음 WSUS 2.0을 다시 설치한 경우 WSUS 3.0을 다시 설치하기 전에 컴퓨터에서 WSUS 3.0 데이터베이스를 삭제해야 합니다.
  
#### WSUS 3.0으로 업그레이드하기 전에 컴퓨터 이름을 변경하면 업그레이드가 실패할 수 있음
  
WSUS 2.0을 설치하고 WSUS 3.0으로 업그레이드하기 전에 컴퓨터 이름을 변경하면 업그레이드가 실패할 수 있습니다.
  
다음 스크립트를 사용하여 ASPNET 및 WSUS Administrators 그룹을 제거했다가 다시 추가하십시오. 그런 다음 업그레이드를 다시 실행합니다.
  
여기에서 *&lt;DBLocation&gt;*은 데이터베이스가 설치된 폴더로 바꾸고 *&lt;ContentDirectory&gt;*는 로컬 저장소 폴더로 바꿉니다.
  
```  
sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=name from sysusers WHERE name like '%ASPNET' EXEC sp\_revokedbaccess @asplogin" sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=name from sysusers WHERE name like '%WSUS Administrators' EXEC sp\_revokedbaccess @wsusadminslogin"   sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=HOST\_NAME()+'\\ASPNET' EXEC sp\_grantlogin @asplogin EXEC sp\_grantdbaccess @asplogin EXEC sp\_addrolemember webService,@asplogin" sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=HOST\_NAME()+'\\WSUS Administrators' EXEC sp\_grantlogin @wsusadminslogin EXEC sp\_grantdbaccess @wsusadminslogin EXEC sp\_addrolemember webService,@wsusadminslogin"   sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "backup database SUSDB to disk=N'*&lt;ContentDirectory&gt;*\\SUSDB.Dat' with init"  
```
  
#### 설치 프로그램에서 이전 데이터베이스 백업을 덮어쓸 수 있음
  
WSUS 3.0 설치 프로그램은 설치 중 지정된 디렉터리에 데이터베이스를 추가합니다. 기본적으로 이 폴더는 *%systemdrive%*\\WSUS\\UpdateServicesDbFiles입니다. 이 디렉터리에 이전 데이터베이스 백업이 있으면 새 데이터베이스로 덮어쓰게 됩니다. 관리자는 데이터베이스가 있는 컴퓨터에 업데이트를 적용하기 전에 데이터베이스 파일을 백업해야 합니다.
  
#### WSUS 2.0에서 MSDE를 SQL Server 2000 또는 SQL Server 2005로 마이그레이션한 경우 레지스트리 값을 변경해야 함
  
WSUS 2.0이 설치된 상태에서 SQL Server 2000 또는 SQL Server 2005에서 마이그레이션한 경우 **HKLM\\SOFTWARE\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled** 값을 1에서 0으로 변경해야 합니다. WSUS 3.0으로 업그레이드하기 전에 해당 값을 변경하지 않으면 업그레이드에 실패합니다.
  
#### WSUS 2.0 설치 프로그램 시작 후 취소하면 WSUS 레지스트리 키가 삭제됨
  
WSUS 2.0 설치 프로그램을 시작했다가 취소하면 WSUS 레지스트리 키가 삭제됩니다. 따라서 WSUS 3.0이 이미 설치된 경우에는 문제가 발생할 수 있습니다. WSUS 2.0 을 제거하고 작업을 취소한 다음 WSUS 2.0에서 WSUS 3.0으로 업그레이드하는 경우에도 동일한 문제가 발생할 수 있습니다.
  
#### WSUS 3.0을 제거하고 로그 파일을 그대로 남겨 두면 다시 설치 후 올바른 사용 권한을 얻을 수 없음
  
WSUS 3.0을 제거할 때 설치 로그 파일을 유지할 수 있습니다. 그러나 WSUS 3.0을 다시 설치하면 이전 로그 파일의 사용 권한(보통 WSUS Administrators만 해당)이 삭제됩니다. 이러한 경우에는 로그 파일의 사용 권한을 복원해야 합니다.
  
#### WSUS 3.0 RC를 설치한 후 Windows SharePoint Services를 설치한 경우 해결 방법을 사용해야 WSUS 3.0 RTM으로 업그레이드할 수 있음
  
WSUS 3.0 RC를 설치한 다음 같은 컴퓨터에 Windows SharePoint Services를 설치한 경우 사용자 지정 포트(포트 8530)에서 설치하도록 선택하여야만 WSUS 3.0 RTM으로 업그레이드할 수 있습니다. 명령줄에서 이 설치를 실행하려면 명령 셸을 열고 다음 명령을 입력합니다. **WSUSSetup /q / g/ DEFAULT\_WEBSITE=0** UI를 사용하여 이 설치를 실행하려면 **WSUSSetup /g DEFAULT\_WEBSITE=0**을 입력합니다.
  
WSUS를 설치한 컴퓨터에 MUI(Multilingual User Interface) 언어 팩이 설치되어 있는 경우 도움말이 사용자의 현재 언어가 아닌 기본 언어로 표시됨
  
#### WSUS 2.0 클라이언트에 "적용할 수 없음" 상태의 업데이트가 있는 경우 해당 업데이트는 WSUS 3.0으로 업그레이드한 후 잠시 동안 "알 수 없음"으로 표시됩니다.
  
WSUS 2.0 서버의 클라이언트에 "적용할 수 없음" 상태의 업데이트가 있는 경우 해당 업데이트는 WSUS 3.0으로 서버를 업그레이드한 후 잠시 동안 "알 수 없음" 상태로 표시됩니다. 다음 번에 클라이언트가 검색을 완료하면 업데이트 상태는 "적용할 수 없음" 상태로 돌아옵니다.
  
알려진 문제  
-----------
  
#### 여러 다운로드 오류 또는 반복되는 클라이언트 동기화 실패 문제 해결
  
WSUS 3.0 클라이언트에서 여러 다운로드 오류를 보고하거나 클라이언트가 오랫 동안 WSUS 3.0 서버와 동기화하지 못하는 경우 클라이언트 다운로드 캐시가 손상되었을 수 있습니다. 이 상태에서 복구하기 위해 파일 시스템에서 클라이언트 다운로드 캐시를 삭제해볼 수 있습니다.
  
클라이언트 다운로드 캐시를 삭제하려면
  
1.  클라이언트 컴퓨터의 **%windir%\\SoftwareDistribution\\Download에 있는 모든 파일과 하위 디렉터리를 삭제합니다.**  
2.  다시 클라이언트 컴퓨터를 WSUS 3.0과 동기화하여 업데이트를 설치해봅니다. 이 설치 시도는 실패하고 **WU\_E\_DM\_NOTDOWNLOADED, "업데이트를 다운로드하지 못했습니다."라는 내용의 오류가 발생합니다.**  
3.  이 실패 후에 클라이언트 컴퓨터가 자동으로 다운로드를 다시 시작하고 설치가 진행될 수 있습니다.
  
#### 동기화에 실패할 경우 다시 시도
  
동기화에 실패하면 문제 해결의 첫 번째 단계로 서버를 다시 동기화해봐야 합니다. 이후 동기화에도 실패하면 [Windows Server Update Services 3.0 작업 가이드](http://go.microsoft.com/fwlink/?linkid=81072)(http://go.microsoft.com/fwlink/?LinkId=81072)에서 문제 해결 정보를 검토하십시오. 이 페이지는 영문일 수 있습니다.
  
#### 데이터베이스에서 WSUS 3.0 구성을 직접 변경하는 작업이 지원되지 않음
  
Windows Server Update Services는 구성 데이터를 SQL Server 데이터베이스에 저장합니다. 그러나 데이터베이스에 직접 액세스하여 구성 데이터를 변경하는 것은 지원되지 않습니다. 데이터베이스에 직접 액세스하여 WSUS 3.0 구성을 수정하려고 하지 마십시오. WSUS 3.0 콘솔을 사용하거나 WSUS 3.0 API를 호출하여 WSUS 3.0 구성을 변경해야 합니다.
  
#### 디스크 할당량이 설정되어 있으면 다운로드 실패가 빨리 보고되지 않음
  
디스크 할당량이 설정되어 있고 이 할당량에 도달하면 WSUS 서버에서 업데이트 다운로드 실패가 제때에 보고되지 않을 수 있습니다. 이 문제를 방지하려면 디스크 할당량을 해제하거나 할당량을 늘리십시오.
  
#### SSL을 사용하여 WSUS 3.0을 배포하면 클라이언트 컴퓨터에 0x8024400a 오류 코드를 포함하는 오류가 발생할 수 있음
  
SSL을 사용하여 WSUS 3.0 서버와 통신할 때 클라이언트 컴퓨터에 "0x8024400a" 오류 코드를 포함하는 오류가 발생하는 경우가 있습니다. 이 문제를 해결하는 업데이트에 대한 자세한 내용은 [KB 905422](http://go.microsoft.com/fwlink/?linkid=70593)(http://go.microsoft.com/fwlink/?LinkId=70593)를 참조하십시오. 이 페이지는 영문일 수 있습니다.
  
#### WSUS를 제거할 때 WSUS Administrators 도메인 계정이 삭제되지 않음
  
WSUS Administrators 그룹은 도메인 컨트롤러에서 로컬 계정이 아니라 도메인 계정으로 만들어지므로 WSUS를 제거할 때 이 도메인 계정이 삭제되면 이 계정을 사용하는 모든 설치를 수행할 수 없게 됩니다. 따라서 WSUS를 제거할 때 WSUS Administrators 도메인 계정이 삭제되지 않습니다.
  
#### 다운스트림 서버가 업스트림 서버로 변환되면 카탈로그 사이트 업데이트를 다시 가져와야 함
  
다운스트림 서버를 업스트림 서버로 승격하는 경우 모든 카탈로그 사이트의 업데이트도 다시 가져와야 합니다. 이렇게 하지 않으면 사이트에서 이 서버에 대해 새 카탈로그 사이트 업데이트 수정 버전을 동기화하지 못합니다.
  
#### SSL과 함께 IIS를 사용하는 경우 "보안 채널 필요"를 선택하지 않으면 암호화되지 않은 액세스가 여전히 가능함
  
인증서를 설치하여 SSL을 사용하도록 IIS를 설정하는 경우 "보안 채널 필요" 옵션을 선택하지 않으면 암호화되지 않은 HTTP를 통해 사이트에 여전히 액세스할 수 있습니다. 자세한 내용은 [암호화 사용](http://go.microsoft.com/fwlink/?linkid=70601)(http://go.microsoft.com/fwlink/?LinkId=70601)을 참조하십시오. 이 페이지는 영문일 수 있습니다.
  
#### %windir%\\TEMP 폴더에 대한 읽기/쓰기 권한이 없으면 카탈로그 사이트를 가져오지 못할 수 있음
  
카탈로그 사이트를 가져올 때 Network Service 계정에 %windir%\\TEMP 폴더에 대한 읽기/쓰기 권한이 없으면 "서버에서 요청을 처리할 수 없습니다. ---&gt;'C:\\WINDOWS\\TEMP\\*tempFileName*.dll' 파일을 찾을 수 없습니다."라는 내용의 오류 메시지가 나타나고 가져오기에 실패할 수 있습니다.
  
#### WSUS 2.0을 실행하는 다운스트림 복제 서버와 WSUS 3.0을 동기화할 때 성능이 저하될 수 있음
  
업스트림 서버에 WSUS 3.0을 설치하고 WSUS 2.0을 실행하는 다운스트림 복제 서버와 동기화하려고 하면 성능 문제가 발생할 수 있습니다. 이 문제를 해결하려면 [KB 910847](http://go.microsoft.com/fwlink/?linkid=70669)(http://go.microsoft.com/fwlink/?LinkId=70669)을 참조하십시오. 이 페이지는 영문일 수 있습니다.
  
#### 메일 서버가 작동하지 않거나 연결이 불가능하면 전자 메일 알림이 통지 없이 실패함
  
네트워크의 전자 메일 서버가 오프라인이면 별다른 통지 없이 WSUS 3.0에서 전자 메일 알림을 보내지 못합니다. 그러나 이벤트 로그에는 이벤트 10052(HealthCoreEmailNotificationRed)가 기록됩니다.
  
#### 업스트림 서버의 변경된 설정이 다운스트림 서버에 즉시 적용되지 않음
  
업스트림 서버 구성이 변경되면 이러한 구성 변경 사항이 실제로 적용될 때까지 시간이 걸릴 수 있습니다. 예를 들어, 업스트림 서버에서 새 언어를 선택하는 것과 같이 설정을 변경하고 다운스트림 서버에서 즉시 동기화를 트리거하면 변경 사항이 나타나지 않습니다. 대신, 예약된 다음 동기화에서 변경 사항이 다운스트림 서버에 적용됩니다. 대기 시간은 업스트림 서버에 있는 업데이트 수에 따라 증가합니다.
  
#### WSUS 3.0을 제거해도 데이터베이스 인스턴스가 제거되지 않음
  
WSUS 3.0을 제거해도 데이터베이스 인스턴스는 제거되지 않습니다. 둘 이상의 응용 프로그램에서 인스턴스를 공유할 수 있으므로 이를 제거할 경우 다른 응용 프로그램을 사용할 수 없을 수 있습니다.
  
Windows 내부 데이터베이스을 제거해야 하면 다음 명령을 사용하여 응용 프로그램을 제거하십시오.
  
(32비트 플랫폼)
  
```  
msiexec /x {CEB5780F-1A70-44A9-850F-DE6C4F6AA8FB} callerid=ocsetup.exe  
```  
(64비트 플랫폼)
  
```  
msiexec /x {BDD79957-5801-4A2D-B09E-852E7FA64D01} callerid=ocsetup.exe  
```  
Windows 내부 데이터베이스 서비스 팩 2를 Windows Server 2008에서 제거하려면 서버 관리자를 사용하여 제거하면 됩니다.
  
하지만 응용 프로그램을 제거하더라도 기본 .mdf 및 .ldf 파일은 제거되지 않을 수 있으므로 다음 번 WSUS 3.0 설치에 실패할 수 있습니다. 이러한 파일은 %windir%\\SYSMSI\\SSEE 디렉터리에서 삭제할 수 있습니다.
  
#### 다운스트림 서버에서 업스트림 서버를 변경하면 "알 수 없음" 상태의 업데이트가 "적용할 수 없음"으로 보고됨
  
다운스트림 서버가 다른 업스트림 서버에서 동기화를 시작하면 "알 수 없음" 상태의 업데이트가 새 업스트림 서버에서 "적용할 수 없음"으로 보고됩니다. 이 상태는 일시적이며 클라이언트가 다운스트림 서버와 동기화한 후 다음 번에 다운스트림 서버에서 상태를 보고할 때 올바르게 수정됩니다.
  
#### WSUS 3.0 복제 서버가 이름이 같은 컴퓨터를 두 대 이상 관리하는 경우 보고 롤업에 실패함
  
WSUS 3.0 복제 서버가 이름이 같은 컴퓨터를 두 대 이상 관리하는 경우 보고 롤업에 실패합니다. 이로 인해 루트 WSUS 서버에서 사용할 수 있는 보고서가 완료되지 않습니다. 이 문제를 해결하려면 복제 서버에서 중복 컴퓨터 항목 중 하나를 제외하고 모두 삭제하십시오.
  
#### 서버 정리 마법사가 원격 콘솔을 통해 여러 서버에서 실행될 때 한 서버에서 시간 제한이 초과되면 모든 서버의 연결이 끊어짐
  
단일 원격 콘솔을 통해 여러 서버에서 서버 정리 마법사를 실행할 수 있습니다. 그러나 서버 중 하나에서 정리 작업의 시간 제한이 초과되면 콘솔에서 모든 서버의 연결이 끊어집니다. 데이터는 손실되지 않지만 관리자가 각 서버의 원격 연결을 다시 설정해야 합니다.
  
#### 서버 정리 마법사는 3달 후가 아니라 30일 후 파일을 삭제함
  
서버 정리 마법사에 대한 일부 설명이 정확하지 않습니다. 설명 중에 만료되었으나 3달 동안 승인되지 않은 업데이트와, 3달 동안 승인되지 않은 이전 버전의 업데이트를 삭제한다는 내용이 있으나 3달이 아니라 30일이 맞습니다.
  
#### 연결을 시작했다가 즉시 중지하면 구성 마법사에서 오류가 없다는 오류 메시지가 나타날 수 있음
  
WSUS를 구성하려면 서버에 대한 기본 정보를 전송하기 위해 업스트림 서버(Microsoft Update 또는 인터넷 업스트림 서버)에 연결해야 합니다. **연결 시작**을 클릭하고 즉시 **연결 중지**를 클릭하면 "동기화 오류가 없습니다.."라는 오류 메시지가 나타나는데 이는 잘못된 것입니다.
  
#### Windows Vista RTM을 사용하는 WSUS 클라이언트가 Microsoft Update에서 업데이트를 검색할 수 있음
  
이전 버전의 WSUS의 경우 Windows Vista RTM을 사용하는 클라이언트는 WSUS 서버에서만 업데이트를 받을 수 있었습니다. 이제 WSUS 3.0 RTM의 경우 Vista 클라이언트는 Microsoft Update에서도 업데이트를 받을 수 있습니다. 제어판에서 Windows Update를 선택하고 **Microsoft Update Service에서 온라인 업데이트 확인** 하이퍼링크를 클릭하여 Vista 클라이언트를 Microsoft Update로 안내할 수 있습니다. **모든 Windows Update 기능을 액세스할 수 있는 권한 제거** 그룹 정책 옵션이 설정되어 있으면 Windows Update에 이 하이퍼링크가 표시되지 않습니다.
  
Windows Server 2008의 WSUS 3.0  
------------------------------
  
#### 지원 버전
  
WSUS 3.0은 32비트 및 64비트 버전에서 Windows Server 2008을 지원합니다.
  
#### 필수 조건
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >요구 사항</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft 인터넷 정보 서비스(IIS)</td>
<td style="border:1px solid black;">운영 체제에서 설치합니다. 다음 구성 요소를 사용할 수 있는지 확인합니다.
Windows 인증
정적 콘텐츠
ASP.NET
6.0 관리 호환성
IIS 메타베이스 호환성</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft .NET Framework 버전 2.0 재배포 가능 패키지(x86)</td>
<td style="border:1px solid black;">Windows Server 2008에는 필요하지 않음. 이미 운영 체제의 일부로 설치되어 있음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Management Console 3.0</td>
<td style="border:1px solid black;">Windows Server 2008에는 필요하지 않음. 이미 운영 체제의 일부로 설치되어 있음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">WSUS UI를 사용하기 위한 필수 구성 요소입니다. <a href="http://go.microsoft.com/fwlink/?linkid=70410">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=70410)에서 Microsoft Report Viewer 재배포 가능 패키지 2005를 참조하십시오.</td>
</tr>
</tbody>
</table>
  
#### 문제 1: WSUS 3.0을 실행하기 전에 IIS 7.0 구성 파일을 업데이트해야 함
  
Windows Server 2008에서 WSUS 3.0을 실행하기 전에 IIS 구성 파일을 업데이트해야 합니다. 다음 단계를 수행해야 합니다.
  
1. 다음 IIS 구성 파일을 엽니다. %WINDIR%\\system32\\inetsrv\\applicationhost.config
  
2. &lt;System.webServer&gt;&lt;modules&gt; 태그에서 &lt;add name="CustomErrorMode"&gt;가 있는 경우 제거합니다.
  
3. &lt;System.webServer&gt;&lt;modules&gt; 태그에서 &lt;remove name="CustomErrorMode"&gt;를 추가합니다.
  
결과 태그는 다음과 같습니다.
  
```  
 &lt;System.webServer&gt; &lt;modules&gt; &lt;remove name="CustomErrorMode"&gt; &lt;/modules&gt; &lt;/System.webServer&gt;  
```
  
#### 문제 2: Windows Server 2008 베타 3의 사용자 지정 포트에서 WSUS 3.0을 설치하려면 웹 사이트를 미리 생성해야 함
  
Windows Server 2008 베타 3에 WSUS 3.0을 설치하고 사용자 지정 포트 8530을 사용하도록 WSUS를 구성하려는 경우 WSUS 설치 프로그램을 시작하기 전에 포트 8530에 "WSUS Administration"이라는 웹 사이트를 생성해야 합니다.
  
Windows Small Business Server 2003의 WSUS 3.0  
---------------------------------------------
  
#### 문제 1: IIS 가상 루트가 특정 IP 주소나 도메인 이름으로 제한되는 경우 WSUS 3.0 서버에서 자동으로 업데이트할 수 없음
  
Windows Small Business Server의 일부 설치에 "IP 주소 및 도메인 이름 제한"을 사용하도록 구성된 기본 IIS 웹 사이트가 있을 수 있습니다. 이 경우 서버의 Windows Update Client에서 자동으로 업데이트할 수 없습니다.
  
#### 문제 2: Small Business Server에 WSUS 3.0 설치—통합 문제
  
-   Windows Small Business Server 2003에서 ISA 프록시 서버를 사용하여 인터넷에 액세스하는 경우 **설정** 사용자 인터페이스에서 프록시 서버 설정, 프록시 서버 이름 및 포트를 수동으로 입력해야 합니다.  
-   ISA에서 Windows 인증을 사용하는 경우 프록시 서버 자격 증명을 "DOMAIN\\user"(user는 인터넷 사용자 그룹에 속함) 형식으로 입력해야 합니다.
  
#### 문제 3: Windows SBS 마법사를 사용하지 않고 네트워크에 서브넷을 추가한 경우 다음 절차를 수행해야 함
  
WSUS 서버 설치 과정 중에 서버에 IIS vroot인 SelfUpdate와 ClientWebService가 설치됩니다. 또한 클라이언트 컴퓨터가 기본 웹 사이트를 통해 자동으로 업데이트할 수 있도록 하는 기본 웹 사이트(80 포트)의 홈 디렉터리 아래에 파일이 배치됩니다. 기본적으로 기본 웹 사이트는 localhost나 서버에 연결된 특정 서브넷이 아닌 IP 주소에 대한 액세스를 거부하도록 구성됩니다. 따라서 localhost나 특정 서브넷에 있지 않은 클라이언트 컴퓨터는 자동으로 업데이트할 수 없습니다. Microsoft Windows Small Business Server 2003(Windows SBS) 마법사를 사용하지 않고 네트워크에 서브넷을 추가한 경우 다음 절차를 수행해야 합니다.
  
1.  서버 관리에서 **고급 관리**, **인터넷 정보 서비스**, **웹 사이트**, **기본 웹 사이트**를 차례로 확장하고 **Selfupdate** 가상 디렉터리를 마우스 오른쪽 단추로 클릭한 다음 **속성**을 클릭합니다.  
2.  **디렉터리 보안**을 클릭합니다.  
3.  **IP 주소 및 도메인 이름 제한**에서 **편집**을 클릭한 다음 **액세스 허가**를 클릭합니다.  
4.  **확인**을 클릭하고 **ClientWebService** 가상 디렉터리를 마우스 오른쪽 단추로 클릭한 다음 **속성**을 클릭합니다.  
5.  **디렉터리 보안**을 클릭합니다.  
6.  **IP 주소 및 도메인 이름 제한**에서 **편집**을 클릭한 다음 **액세스 허가**를 클릭합니다.
  
#### 저작권
  
이 설명서는 발매 전에 대폭 변경될 수 있는 소프트웨어 제품의 임시 릴리스를 지원하며 Microsoft Corporation의 기밀 및 독점 정보입니다. 이 설명서는 수신자와 Microsoft 간의 비밀 유지 계약에 따라 공개됩니다. 이 설명서는 오직 정보를 제공하기 위한 것입니다. Microsoft는 이 설명서에서 어떠한 명시적이거나 묵시적인 보증도 하지 않습니다. URL 및 기타 인터넷 웹 사이트 참조를 비롯한 이 설명서의 내용은 예고 없이 변경될 수 있습니다. 이 설명서의 사용이나 사용 결과에 따른 책임은 전적으로 사용자에게 있습니다. 다른 설명이 없는 한, 용례에 사용된 회사, 기관, 제품, 도메인 이름, 전자 메일 주소, 로고, 사람, 장소 및 이벤트는 실제 데이터가 아닙니다. 어떠한 실제 회사, 기관, 제품, 도메인 이름, 전자 메일 주소, 로고, 사람, 장소 또는 이벤트와도 연관시킬 의도가 없으며 그렇게 유추해서도 안 됩니다. 해당 저작권법을 준수하는 것은 사용자의 책임입니다. 저작권에서의 권리와는 별도로, 이 설명서의 어떠한 부분도 Microsoft Corporation의 명시적인 서면 승인 없이는 어떠한 형식이나 수단(전기적, 기계적, 복사기에 의한 복사, 디스크 복사 또는 다른 방법) 또는 목적으로도 복제되거나, 검색 시스템에 저장 또는 도입되거나, 전송될 수 없습니다.
  
Microsoft가 이 설명서 본안에 관련된 특허권, 상표권, 저작권 또는 기타 지적 재산권 등을 보유할 수도 있습니다. 서면 사용권 계약에 따라 Microsoft로부터 귀하에게 명시적으로 제공된 권리 이외에, 이 설명서의 제공은 귀하에게 이러한 특허권, 상표권, 저작권 또는 기타 지적 재산권 등에 대한 어떠한 사용권도 허여하지 않습니다.
  
ⓒ 2007 Microsoft Corporation. All rights reserved.
  
Microsoft, SQL Server, Windows 및 Windows Server는 미국, 대한민국 및/또는 기타 국가에서의 Microsoft Corporation 등록 상표 또는 상표입니다.
  
다른 모든 상표는 해당 소유자의 재산입니다.
