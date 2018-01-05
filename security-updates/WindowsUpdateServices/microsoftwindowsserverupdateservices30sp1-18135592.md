---
TOCTitle: 'Microsoft Windows Server Update Services 3.0 SP1 릴리스 정보'
Title: 'Microsoft Windows Server Update Services 3.0 SP1 릴리스 정보'
ms:assetid: 'a5aa93bf-842b-4ad4-ab0f-fe867843cb02'
ms:contentKeyID: 18135592
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc708525(v=WS.10)'
---

Microsoft Windows Server Update Services 3.0 SP1 릴리스 정보
============================================================

이러한 릴리스 정보는 Microsoft® Windows® Server Update Services(WSUS) 3.0 서비스 팩 1에 영향을 주는 알려진 문제에 대해 설명하고 응용 프로그램 설치와 관련된 권장 사항 및 요구 사항을 설명합니다. 이러한 정보에는 다음과 같은 섹션이 포함되어 있습니다.

-   WSUS 3.0 SP1 서버 설치를 위한 시스템 요구 사항
-   WSUS 3.0 SP1 서버 설치를 위한 구성 요구 사항
-   WSUS 3.0 SP1 원격 콘솔 설치를 위한 시스템 요구 사항
-   클라이언트 설치를 위한 시스템 요구 사항
-   WSUS SP1 서버 설치를 위한 소프트웨어 요구 사항
-   WSUS 3.0 SP1 서버 설치를 위한 최소 디스크 공간 요구 사항
-   WSUS 3.0 SP1 업그레이드 요구 사항
-   설치 명령줄 매개 변수
-   설치 문제
-   업그레이드 문제
-   알려진 문제
-   Windows Server® 2008의 WSUS 3.0 SP1
-   Windows Small Business Server 2003의 WSUS 3.0 SP1

WSUS 3.0 SP1 서버 설치를 위한 시스템 요구 사항
----------------------------------------------

#### Windows Server 2008 및 Windows Server 2003 서비스 팩 1에서 WSUS 3.0 SP1 서버 지원

Windows Server 2008 및 Windows Server 2003 서비스 팩 1에서 WSUS 3.0 SP1 서버가 지원됩니다.

#### WSUS 3.0 SP1 서버에 대해 Windows 2000 Server가 지원되지 않음

Microsoft Windows® 2000 Server는 WSUS 3.0 SP1 서버에 대해 지원되는 운영 체제가 아닙니다.

#### 터미널 서비스를 실행하는 서버에서 WSUS 3.0 SP1이 지원되지 않음

터미널 서비스를 실행하는 서버에서 WSUS 3.0 SP1을 실행할 수는 있지만 이는 지원되거나 권장되는 사항이 아닙니다. 원격 SQL Server 구현을 사용하도록 구성된 터미널 서비스를 실행하는 서버에서는 WSUS 3.0 SP1이 실행되지 않습니다. 터미널 서비스 라이선스 서버에서 설치를 비롯한 모든 원격 사용자 지정 작업은 시스템 계정으로 실행되며 서버의 시스템 계정에 원격 SQL Server에 대한 사용 권한이 없을 수 있으므로 설치에 실패할 수 있습니다.

WSUS 3.0 SP1 서버 설치를 위한 구성 요구 사항
--------------------------------------------

#### IIS가 설치되어야 함

WSUS 3.0 SP1에는 IIS(인터넷 정보 서비스)가 필요한데, 이는 Windows Server 2008 또는 Microsoft Windows Server 2003에는 기본적으로 설치되어 있지 않습니다. IIS 없이 WSUS 3.0 SP1을 설치하려고 하면 Windows Server Update Services 설치 시 IIS가 설치되어 있지 않다는 오류 메시지가 표시됩니다.

#### IIS가 IIS 5.0 격리 모드에서 실행 중인 경우 설치에 실패함

Windows 2000 Server에서 Windows Server 2003으로 서버를 업그레이드한 경우 IIS는 IIS 5.0 호환 모드에서 실행될 수 있습니다. IIS 관리자에서 IIS 5.0 격리 모드를 사용하도록 설정되어 있을 수 있습니다. 이 경우 설치에 실패합니다. WSUS 3.0 SP1을 설치하기 전에 IIS 5.0 격리 모드가 사용되지 않도록 설정해야 합니다.

#### 64비트 플랫폼의 32비트 호환 모드에 IIS 구성 요소가 설치되어 있으면 WSUS 3.0 SP1 설치에 실패할 수 있음

모든 IIS 구성 요소는 64비트 플랫폼의 기본 모드에서 설치되어야 합니다. IIS 구성 요소가 32비트 호환 모드에 있는 경우 설치에 실패할 수 있습니다.

#### 프록시 서버는 HTTP만 지원할 수도 있고, HTTP와 HTTPS를 지원할 수도 있음

WSUS 3.0 SP1에서는 프록시 서버가 HTTP만 지원할 수 있습니다. 구성 마법사 또는 관리 콘솔에서 WSUS 서버를 구성하기 전에 명령줄(**wsusutil configuresslproxy**)을 사용하여 HTTPS를 실행하는 두 번째 프록시 서버를 구성해야 합니다.

#### 두 개 이상의 웹 사이트가 이미 포트 80에서 실행 중인 경우 WSUS를 설치하기 전에 하나만 제외하고 모두 삭제

두 개 이상의 웹 사이트가 포트 80(예: Windows® SharePoint® Services)에서 실행 중인 경우 WSUS를 설치하기 전에 하나만 제외하고 모두 삭제해야 합니다. 이렇게 하지 않으면 서버의 클라이언트가 자동 업데이트에 실패할 수 있습니다.

#### WSUS 3.0 SP1 설치 시 바이러스 백신 프로그램을 사용하지 않도록 설정해야 할 수 있음

WSUS 3.0 SP1을 설치할 때 설치를 제대로 수행할 수 있으려면 바이러스 백신 프로그램을 사용하지 않도록 설정해야 할 수 있습니다. 바이러스 백신 프로그램을 사용하지 않도록 설정하고 컴퓨터를 다시 시작한 후 WSUS를 설치하십시오. 컴퓨터를 다시 시작해야 설치 프로세스 시 액세스해야 하는 파일이 잠기지 않도록 할 수 있습니다. 설치가 완료되면 바이러스 백신 프로그램을 다시 사용하도록 설정해야 합니다. 바이러스 백신 프로그램을 사용하지 않도록 설정했다가 다시 사용하도록 설정하는 정확한 단계와 버전에 대해 알아보려면 바이러스 백신 프로그램 공급업체 웹 사이트를 방문하십시오.

| ![](images/Cc708525.Caution(WS.10).gif)주의                                                                                                                                                                                                     |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 이 해결 방법은 컴퓨터나 네트워크를 악의적인 사용자나 바이러스 같은 악성 소프트웨어의 공격에 더 취약하게 만들 수 있습니다. 권장 방법은 아니지만 이 정보를 제공하는 것은 사용자의 재량에 따라 이 해결 방법을 구현할 수 있도록 하기 위해서입니다. 따라서 주의하여 사용하십시오. |

| ![](images/Cc708525.note(WS.10).gif)참고                                                                                                                                                                                                              |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 바이러스 백신 프로그램은 컴퓨터를 바이러스로부터 보호하도록 설계되었습니다. 바이러스 백신 프로그램을 사용하지 않도록 설정한 상태에서는 신뢰할 수 없는 출처에서 파일을 다운로드하거나 이를 열거나, 신뢰할 수 없는 웹 사이트를 방문하거나, 전자 메일 첨부 파일을 열어서는 안 됩니다. |

#### WSUS 3.0 SP1을 설치하려면 SQL Server에서 중첩 트리거 옵션이 설정되어야 함

중첩 트리거 옵션은 기본적으로 설정되어 있지만 SQL Server 관리자에 의해 해제되어 있을 수 있습니다.

SQL Server 데이터베이스를 Windows Server Update Services 데이터 저장소로 사용할 계획이라면, WSUS 3.0 SP1 관리자가 WSUS 3.0 SP1을 설치하고 설치 중 데이터베이스를 지정하기 전에, SQL Server 관리자는 서버에서 중첩 트리거 옵션이 설정되어 있는지 확인해야 합니다.

WSUS 3.0 SP1 설치 프로그램은 데이터베이스 특정 옵션인 RECURSIVE\_TRIGGERS 옵션은 설정하지만 서버 전역 옵션인 중첩 트리거 옵션은 설정하지 않습니다.

중첩 트리거 옵션이 설정되어 있는지 확인하려면 다음을 사용하십시오.

**sp\_configure 'nested triggers'**

SQL Server에서 중첩 트리거 옵션을 설정하려면 SQL Server를 실행하는 컴퓨터의 배치 파일로부터 다음을 실행하십시오.

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

서버에 SQL Server Management Studio가 없는 경우 명령줄에서 SQL 스크립트를 실행할 수 있습니다. [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=70728)(http://go.microsoft.com/fwlink/?LinkId=70728)에서 Microsoft SQL Server 2005 명령줄 쿼리 유틸리티를 얻을 수 있습니다. 시작하려면 **sqlcmd**를 실행하십시오.

Windows 내부 데이터베이스에 대해 SQL 스크립트를 실행하려면 같은 다운로드 페이지에서 SQL Server Native Client도 다운로드해야 합니다.

#### 원격 SQL 제한 사항 및 요구 사항

WSUS 3.0 SP1은 한 컴퓨터에서 데이터베이스 소프트웨어를 실행하고 다른 컴퓨터에서 WSUS 3.0 SP1 응용 프로그램의 나머지를 실행하는 것을 지원합니다. 원격 SQL 설치를 구성하기 위한 몇 가지 요구 사항이 있습니다.

-   원격 SQL 쌍의 백 엔드에 대해서는 도메인 컨트롤러로 구성된 서버를 사용할 수 없습니다.
-   원격 SQL 설치의 프런트 엔드 서버가 될 컴퓨터에서 터미널 서버를 실행해서는 안 됩니다.
-   백 엔드 컴퓨터에서 Windows Server 2003을 실행 중인 경우 해당 백 엔드 컴퓨터의 데이터베이스 소프트웨어에 대해 적어도 Microsoft SQL Server 2005 서비스 팩 1([Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=66143)(http://go.microsoft.com/fwlink/?LinkId=66143)에서 사용 가능)을 사용해야 하며, 백 엔드 컴퓨터에서 Windows Server® 2008을(를) 실행 중인 경우 SQL Server 2005 서비스 팩 2를 사용해야 합니다.
-   프런트 엔드 컴퓨터와 백 엔드 컴퓨터 모두 Active Directory 도메인에 가입되어야 합니다. 이들이 서로 다른 도메인에 있을 경우에는 WSUS 설치 프로그램을 실행하기 전에 두 도메인 사이에 도메인 간 트러스트를 설정해야 합니다.
-   원격 SQL 구성에 WSUS 2.0이 이미 설치되어 있는 상태에서 WSUS 3.0 SP1로 업그레이드하려는 경우, 기존 데이터베이스가 유지되는지 확인하는 한편 백 엔드 컴퓨터의 제어판에서 **프로그램 추가/제거**를 사용하여 WSUS 2.0을 제거해야 합니다. 그런 다음 SQL Server 2005 SP1 또는 SP2를 설치하고 기존 데이터베이스를 업그레이드해야 합니다. 마지막으로 프런트 엔드 컴퓨터에서 WSUS 3.0 SP1을 설치해야 합니다.

WSUS 3.0 SP1 원격 콘솔 설치를 위한 시스템 요구 사항
---------------------------------------------------

WSUS 3.0 SP1 원격 콘솔을 다음 플랫폼에 설치할 수 있습니다.

-   Windows Server 2008
-   Windows Vista® 이상
-   Windows Server 2003 SP1 이상
-   Windows XP SP2 이상

클라이언트 설치를 위한 시스템 요구 사항
---------------------------------------

자동 업데이트는 WSUS 클라이언트 소프트웨어로서, 다음 운영 체제에서 WSUS와 함께 사용할 수 있습니다.

-   Windows Vista 이상
-   Windows Server 2008 이상
-   Microsoft Windows Server 2003 모든 버전
-   Microsoft Windows XP Professional SP2 이상
-   Microsoft Windows 2000 Professional SP4, Windows 2000 Server SP4 또는 Windows 2000 Advanced Server SP4

WSUS 3.0 SP1 서버 설치를 위한 소프트웨어 요구 사항
--------------------------------------------------

다음 표에서는 Windows Server 2003 SP1 플랫폼에 필요한 소프트웨어를 보여줍니다. Windows Server 2008에 필요한 소프트웨어는 Windows Server 2008에서의 WSUS 3.0 SP1에 대해 다루는 섹션에서 설명합니다.

WSUS 3.0 SP1 설치를 실행하기 전에 WSUS 3.0 SP1 서버가 여기에 나열된 요구 사항을 충족하는지 확인하십시오. 이러한 업데이트 중에서 설치 완료 시 컴퓨터를 다시 시작하도록 요구하는 것이 있다면 WSUS 3.0 SP1을 설치하기 전에 컴퓨터를 다시 시작해야 합니다.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >요구 사항</th>
<th style="border:1px solid black;" >세부 정보</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft IIS(인터넷 정보 서비스)</td>
<td style="border:1px solid black;">운영 체제에서 설치합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft .NET Framework 버전 2.0 재배포 가능 패키지</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=68935">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=68935)의 Microsoft .NET Framework 버전 2.0 재배포 가능 패키지(x86)를 참조하십시오. 64비트 플랫폼의 경우 <a href="http://go.microsoft.com/fwlink/?linkid=70637">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=70637)의 Microsoft .NET Framework 버전 2.0 재배포 가능 패키지(x64)를 참조하십시오.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003용 Microsoft Management Console 3.0</td>
<td style="border:1px solid black;">WSUS 3.0 SP1 사용자 인터페이스를 사용하기 위한 필수 구성 요소입니다. <a href="http://go.microsoft.com/fwlink/?linkid=70412">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=70412)의 Windows Server 2003용 Microsoft Management Console 3.0(KB907265)을 참조하십시오. 64비트 플랫폼의 경우 <a href="http://go.microsoft.com/fwlink/?linkid=70638">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=70638)의 Microsoft Management Console 3.0 for Windows Server 2003 x64 Edition (KB907265)을 참조하십시오.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">WSUS 3.0 SP1 사용자 인터페이스를 사용하기 위한 필수 구성 요소입니다. <a href="http://go.microsoft.com/fwlink/?linkid=70410">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=70410)의 Microsoft Report Viewer 재배포 가능 패키지 2005를 참조하십시오.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2005(옵션)</td>
<td style="border:1px solid black;">WSUS 3.0 SP1은 SQL Server의 호환 버전이 아직 설치되어 있지 않은 경우에 Windows 내부 데이터베이스을(를) 설치합니다. 전체 SQL Server 데이터베이스를 사용하려면 Windows Server 2003에서 적어도 SQL Server 2005 SP1(<a href="http://go.microsoft.com/fwlink/?linkid=66143">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=66143)에서 사용 가능)을 사용하거나 Windows Server 2008에서 SQL Server 2005 SP2(<a href="http://go.microsoft.com/fwlink/?linkid=84823">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=84823)에서 사용 가능)를 사용해야 합니다.</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc708525.note(WS.10).gif)참고                                                                                                                                                                                                                                                                         |  
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| WSUS 2.0이 이전에 설치되었고 WSUS 2.0에서 SQL Server 2000, SQL Server Desktop Engine 2000 또는 SQL Server 2005 SP1(Windows Server 2008의 경우 SQL Server 2005 SP2)보다 이전 버전의 SQL Server 데이터베이스를 사용 중인 경우, WSUS 3.0 SP1 설치 프로그램은 Windows® 내부 데이터베이스을(를) 설치하고 여기로 데이터베이스를 마이그레이션합니다. |
  
WSUS 3.0 SP1 서버 설치를 위한 최소 디스크 공간 요구 사항  
--------------------------------------------------------
  
다음은 Windows Server Update Services 설치를 위한 최소 디스크 공간 요구 사항입니다.
  
-   시스템 파티션에 대해 1GB  
-   데이터베이스 파일을 저장할 볼륨으로 2GB  
-   콘텐츠를 저장할 볼륨으로 20GB
  
| ![](images/Cc708525.Important(WS.10).gif)중요                                  |  
|-------------------------------------------------------------------------------------------------------------|  
| 압축 드라이브에는 WSUS 3.0 SP1을 설치할 수 없습니다. 선택하는 드라이브가 압축되어 있지 않은지 확인하십시오. |
  
WSUS 3.0 SP1 업그레이드 요구 사항  
---------------------------------
  
#### WSUS 설치가 제대로 실행되고 있는지 확인하고 업그레이드 전에 WSUS 데이터베이스 백업
  
이전 버전에서 WSUS 3.0 SP1로 업그레이드하는 경우 현재 설치가 제대로 실행되고 있는지 확인하고 업그레이드 전에 WSUS 데이터베이스를 백업하십시오.
  
1.  이벤트 로그의 최근 오류, 다운스트림 서버와 업스트림 서버 간의 동기화 관련 문제 또는 보고되지 않은 클라이언트 관련 문제를 확인합니다. 계속하기 전에 이러한 문제가 해결되었는지 확인하십시오.  
2.  WSUS 데이터베이스가 제대로 인덱싱되는지 확인하기 위해 DBCC CHECKDB를 실행할 수 있습니다. DBCC CHECKDB에 대한 자세한 내용은 [DBCC CHECKDB](http://go.microsoft.com/fwlink/?linkid=86948)(http://go.microsoft.com/fwlink/?LinkId=86948)를 참조하십시오.  
3.  WSUS 데이터베이스를 백업합니다.
  
#### WSUS에서 사용되는 포트를 수동으로 수정한 경우 업그레이드 전에 제거
  
WSUS용 포트를 수정할 경우 포트를 수동으로 수정하기보다는 항상 wsusutil 유틸리티를 사용합니다. 포트를 수동으로 수정하고 이전에 Software Update Services 1.0에서 WSUS 2.0으로 업그레이드한 경우:
  
1.  아직 WSUS 3.0을 설치하지 않은 경우 데이터베이스와 콘텐츠는 유지한 상태로 WSUS 2.0을 제거합니다. 이미 WSUS 3.0을 설치한 경우 데이터베이스와 콘텐츠는 유지한 상태로 이를 제거합니다.  
2.  SUS 1.0을 일시적으로 다시 사용하도록 설정하되 제거 프로그램에 액세스할 수 있도록 한 상태에서 기본 웹 사이트를 시작합니다.  
3.  SUS 1.0을 제거합니다.  
4.  WSUS 3.0을 설치합니다.
  
#### Software Update Services 1.0을 제거해야 함
  
Software Update Services 1.0이 동일한 컴퓨터에 설치되어 있으면 WSUS 3.0 SP1이 설치되지 않습니다. WSUS 3.0 SP1을 설치하기 전에 Software Update Services 1.0을 제거해야 합니다.
  
#### 64비트 운영 체제에서는 WSUS 2.0에서 WSUS 3.0 SP1로 업그레이드할 수 없음
  
64비트 운영 체제에서는 WSUS 2.0이 지원되지 않습니다. 64비트 운영 체제에서는 WSUS 2.0에서 WSUS 3.0 SP1로 업그레이드할 수 없습니다.
  
설치 명령줄 매개 변수  
---------------------
  
WSUS 명령줄 설치 프로그램을 사용하여 WSUS 3.0 SP1의 무인 설치를 수행할 수 있습니다. 이 표에서는 WSUS 3.0 SP1 설치를 위한 명령줄 매개 변수를 보여줍니다.
  
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
<td style="border:1px solid black;">자동 설치를 수행합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/u</strong></td>
<td style="border:1px solid black;">제품을 제거합니다. Windows 내부 데이터베이스 인스턴스가 설치되어 있는 경우 해당 인스턴스도 제거합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/p</strong></td>
<td style="border:1px solid black;">필수 구성 요소만 검사합니다. 제품을 설치하는 것이 아니라 시스템을 검사하고 누락된 필수 구성 요소를 보고합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/?, /h</strong></td>
<td style="border:1px solid black;">명령줄 매개 변수 및 해당 설명을 표시합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/g</strong></td>
<td style="border:1px solid black;">이전 버전의 WSUS에서 업그레이드합니다. SUS 1.0에서는 업그레이드하지 마십시오. 이 옵션과 함께 사용할 수 있는 유효한 매개 변수는 /q(자동 설치)뿐입니다. 이 옵션과 함께 사용할 수 있는 유효한 속성은 DEFAULT_WEBSITE뿐입니다.</td>
</tr>
</tbody>
</table>
  
이 표에서는 WSUS 3.0 SP1의 명령줄 속성을 보여줍니다.
  
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
<td style="border:1px solid black;">콘텐츠 디렉터리의 경로입니다. 기본값은 <em>WSUS 설치 드라이브</em><strong>\WSUS\WSUSContent</strong>이며, 여기서 <em>WSUS 설치 드라이브</em>는 사용 가능한 공간이 가장 큰 로컬 드라이브를 가리킵니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WYUKON_DATA_DIR</td>
<td style="border:1px solid black;">Windows 내부 데이터베이스 데이터 디렉터리의 경로입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQLINSTANCE_NAME</td>
<td style="border:1px solid black;">이름은 <em>서버 이름</em>\<em>SQL 인스턴스 이름</em> 형식으로 표시해야 합니다. 데이터베이스 인스턴스가 로컬 컴퓨터에 있는 경우 %COMPUTERNAME% 환경 변수를 사용하십시오. 기존 인스턴스가 없는 경우 기본값은 %COMPUTERNAME%\WSUS입니다.</td>
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
<td style="border:1px solid black;">0=인벤토리 기능 설치하지 않음, 1=인벤토리 기능 설치</td>
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
<td style="border:1px solid black;">0=로그 파일 보존, 1=로그 파일 제거(/u 설치 스위치와 함께 사용됨)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATE_DATABASE</td>
<td style="border:1px solid black;">0=현재 데이터베이스 사용, 1=데이터베이스 만들기</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROGRESS_WINDOW_HANDLE</td>
<td style="border:1px solid black;">MSI 진행률 메시지를 반환하는 창 핸들</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MU_ROLLUP</td>
<td style="border:1px solid black;">1=Microsoft Update 개선 프로그램에 참여, 0=Microsoft Update 개선 프로그램에 참여 안 함</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">FRONTEND_SETUP</td>
<td style="border:1px solid black;">1=데이터베이스에 콘텐츠 위치 기록하지 않음, 0=데이터베이스에 콘텐츠 위치 기록(NLB용)</td>
</tr>
</tbody>
</table>
  
#### 사용법 예제
  
```  
WSUSSetup.exe /q DEFAULT\_WEBSITE=0 (install in quiet mode using port 8530) WSUSSetup.exe /q /u (uninstall WSUS)  
```  
| ![](images/Cc708525.Important(WS.10).gif)중요                                                                                                     |  
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| WSUS 3.0 SP1을 자동 모드(/q)에서 설치하고 컴퓨터에 일부 필수 구성 요소가 설치되지 않은 경우 설치 시 이름이 WSUSPreReqCheck.xml인 파일이 생성되고 %TEMP% 디렉터리에 저장됩니다. |
  
설치 문제  
---------
  
#### WSUS 3.0 SP1을 설치하는 동안 IIS가 다시 시작됨
  
WSUS 3.0 SP1 설치 시 알림 없이 IIS가 다시 시작되는데, 이는 조직 내의 기존 웹 사이트에 영향을 줄 수 있습니다. IIS가 실행되지 않고 있으면 WSUS 3.0 SP1 설치 프로그램이 이를 시작합니다.
  
#### 기존 WSUS 데이터베이스에 대해 연결이 열려 있으면 설치에 실패할 수 있음
  
기존 설치로부터 WSUS 3.0 SP1로 업그레이드 중이고 기존 WSUS 데이터베이스에 대해 아직 연결이 열려 있는 경우(예를 들어, SQL Server Management Studio가 열려 있는 경우) 설치에 실패할 수 있습니다. 모든 연결을 닫고 WSUS 3.0 SP1을 다시 설치하십시오.
  
#### WSUS 설치 시 데이터베이스 파일에 대한 잘못된 디렉터리를 보여줌
  
WSUS 설치 시 **설치 준비 완료** 화면에서는 데이터베이스 위치가 데이터베이스 위치의 상위 디렉터리로 잘못 보고됩니다. 예를 들어, 기본 위치는 %systemdrive%\\WSUS\\UpdateServicesDbFiles인데, 이 위치가 %systemdrive%\\WSUS로 잘못 표시됩니다.
  
#### WSUS가 영어가 아닌 기본 언어로 된 MUI(Multilingual User Interface) 언어 팩이 있는 컴퓨터에 설치되어 있으면 영어가 아닌 기본 언어로 도움말이 표시됨
  
영어가 아닌 기본 언어로 된 MUI 언어 팩이 있는 컴퓨터를 사용하는 경우 현재 사용자의 로캘이 영어이더라도 WSUS를 설치할 수 있습니다. UI는 영어로 표시되지만 도움말도 영어로 표시되도록 해결 방법을 사용해야 합니다. 영어 도움말 .chm 파일(*WSUS 설치 디렉터리*\\documentation\\mui\\0409\\WSUS30Help.chm)을 주 설명서 디렉터리(*WSUS 설치 디렉터리*\\documentation\\WSUS30Help.chm)로 복사하십시오. 여기서 도움말은 모든 언어로 제대로 표시되어야 합니다.
  
업그레이드 문제  
---------------
  
#### 실패한 업그레이드 복구
  
이전 버전의 WSUS(WSUS 3.0, WSUS 2.0 SP1 또는 WSUS 2.0)에서 WSUS 3.0 SP1로 업그레이드하는 경우 다음 이유로 인해 업그레이드는 실패합니다.
  
1.  이전 버전의 WSUS를 다시 설치합니다.  
2.  업그레이드를 시도하기 전에 만든 백업으로부터 데이터베이스를 복원합니다. 대부분의 경우 WSUS도 자동으로 백업을 만듭니다. 해당 위치에 대해서는 WSUSSetup.log 파일을 참조하십시오.  
3.  로그를 검토하여 실패의 원인을 판별하고 문제를 해결합니다.  
4.  WSUS의 업그레이드를 다시 시도합니다.
  
#### 이전에 설치한 WSUS 3.0 SP1 데이터베이스가 남아 있다면 WSUS 2.0에서 WSUS 3.0 SP1로 업그레이드할 수 없음
  
이전에 WSUS 3.0 SP1을 설치한 다음 WSUS 2.0을 다시 설치했다면 WSUS 3.0 SP1을 다시 설치하기 전에 컴퓨터에서 WSUS 3.0 SP1 데이터베이스를 삭제해야 합니다.
  
#### WSUS 3.0 SP1로 업그레이드하기 전에 컴퓨터 이름을 변경하면 업그레이드가 실패할 수 있음
  
WSUS 2.0을 설치하고 나서 WSUS 3.0 SP1로 업그레이드하기 전에 컴퓨터 이름을 변경할 경우 업그레이드가 실패할 수 있습니다.
  
ASPNET 및 WSUS Administrators 그룹을 제거하고 다시 추가하려면 다음 스크립트를 사용하십시오. 그런 다음 다시 업그레이드를 실행하십시오.
  
*&lt;DB 위치&gt;*를 데이터베이스가 설치된 폴더로, *&lt;콘텐츠 디렉터리&gt;*를 로컬 저장소 폴더로 바꿔야 합니다.
  
```  
sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=name from sysusers WHERE name like '%ASPNET' EXEC sp\_revokedbaccess @asplogin" sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=name from sysusers WHERE name like '%WSUS Administrators' EXEC sp\_revokedbaccess @wsusadminslogin"   sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=HOST\_NAME()+'\\ASPNET' EXEC sp\_grantlogin @asplogin EXEC sp\_grantdbaccess @asplogin EXEC sp\_addrolemember webService,@asplogin" sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=HOST\_NAME()+'\\WSUS Administrators' EXEC sp\_grantlogin @wsusadminslogin EXEC sp\_grantdbaccess @wsusadminslogin EXEC sp\_addrolemember webService,@wsusadminslogin"   sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "backup database SUSDB to disk=N'*&lt;ContentDirectory&gt;*\\SUSDB.Dat' with init"  
```
  
#### 설치 시 이전 데이터베이스 백업을 덮어씀
  
WSUS 3.0 SP1 설치 시 *드라이브*\\WSUS인 기본 디렉터리에 데이터베이스가 추가됩니다. 여기서 *드라이브*는 사용 가능한 공간이 가장 큰 로컬 NTFS 드라이브입니다. 이 디렉터리에 데이터베이스 백업이 있으면 이를 덮어씁니다. 관리자는 WSUS 3.0 SP1로 업그레이드하기 전에 현재 버전의 데이터베이스 백업을 다른 위치에 저장해야 합니다.
  
#### MSDE에서 WSUS 2.0의 SQL Server 2000 또는 SQL Server 2005로 마이그레이션한 경우 레지스트리 값을 변경해야 함
  
WSUS 2.0이 설치되어 있고 SQL Server 2000 또는 SQL Server 2005로 마이그레이션했다면 **HKLM\\SOFTWARE\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled** 값을 1에서 0으로 변경해야 합니다. WSUS 3.0 SP1을 업그레이드하기 전에 이렇게 하지 않을 경우 업그레이드는 실패합니다.
  
#### WSUS 2.0 설치가 시작되었다가 취소되는 경우 WSUS 레지스트리 키가 삭제됨
  
WSUS 2.0 설치를 시작한 다음 이를 취소하는 경우 WSUS 레지스트리 키가 삭제됩니다. 이렇게 되면 WSUS 3.0 SP1이 이미 설치된 경우 문제가 발생할 수 있습니다. WSUS 2.0을 제거하기 시작하다가 해당 제거 작업을 취소한 다음 WSUS 2.0에서 WSUS 3.0 SP1로 업그레이드를 시도하는 경우에도 동일한 문제가 발생합니다.
  
#### WSUS 3.0 SP1을 제거하고 로그 파일을 남겨둔 경우에는 다시 설치한 후에 올바른 사용 권한을 가질 수 없음
  
WSUS 3.0 SP1을 제거할 때 설치 로그 파일을 유지하도록 선택할 수 있습니다. WSUS 3.0 SP1을 다시 설치할 때는 기존 로그 파일이 사용 권한(보통 WSUS Administrators 전용)을 잃게 됩니다. 이러한 로그 파일의 사용 권한을 복원해야 합니다.
  
#### WSUS 2.0 클라이언트가 "적용할 수 없음" 상태로 업데이트된 경우 WSUS 3.0 SP1로 업그레이드한 후에 잠시 동안 업데이트가 "알 수 없음"으로 표시됨
  
WSUS 2.0 서버에 **적용할 수 없음** 업데이트를 포함하는 클라이언트가 있으면 이러한 업데이트는 서버가 WSUS 3.0 SP1로 업그레이드된 후에 잠시 동안 **알 수 없음** 상태로 표시됩니다. 다음 번에 클라이언트가 검색을 수행하고 나면 업데이트 상태가 **적용할 수 없음**으로 되돌아갑니다.
  
알려진 문제  
-----------
  
#### 여러 다운로드 오류 또는 반복되는 클라이언트 동기화 문제 해결이 실패함
  
WSUS 3.0 SP1 클라이언트가 여러 다운로드 오류를 보고하거나 클라이언트가 오랜 시간 동안 WSUS 3.0 SP1 서버와 동기화하는 데 실패하는 경우 손상된 클라이언트 다운로드 캐시가 발생할 수 있습니다. 이 상태를 복구하기 위해 파일 시스템에서 클라이언트 다운로드 캐시를 삭제할 수 있습니다.
  
클라이언트 다운로드 캐시를 삭제하려면 다음을 수행하십시오.
  
1.  클라이언트 컴퓨터의 다음 위치에서 모든 파일 및 하위 디렉터리를 삭제합니다. **%windir%\\SoftwareDistribution\\Download**  
2.  클라이언트 컴퓨터를 WSUS 3.0 SP1과 다시 동기화하여 업데이트를 설치합니다. 이 설치 시도는 다음 오류와 함께 실패하게 됩니다. **WU\_E\_DM\_NOTDOWNLOADED, "업데이트가 다운로드되지 않았습니다."**  
3.  이 실패 후에 클라이언트 컴퓨터는 자동으로 다운로드를 다시 시작하며 이제 설치가 진행될 수 있습니다.
  
#### 동기화가 실패하면 동기화를 다시 시도
  
동기화에 실패하면 서버 동기화를 다시 시도하기 전에 먼저 문제 해결 작업을 시도해야 합니다. 그 이후의 동기화에도 실패하면 [Windows Server Update Services 3.0 Operations Guide](http://go.microsoft.com/fwlink/?linkid=81072)(http://go.microsoft.com/fwlink/?LinkId=81072)의 문제 해결 정보를 사용하십시오.
  
#### WSUS 3.0 SP1 구성을 데이터베이스에서 직접 변경할 수 없음
  
Windows Server Update Services는 해당 구성 데이터를 SQL Server 데이터베이스에 저장합니다. 그러나 데이터베이스에 직접 액세스하여 구성 데이터를 변경할 수는 없습니다. 데이터베이스에 직접 액세스하여 WSUS 3.0 SP1 구성을 수정하지 마십시오. WSUS 3.0 SP1 콘솔을 사용하거나 WSUS 3.0 SP1 API를 호출하여 WSUS 3.0 SP1 구성을 변경해야 합니다.
  
#### 디스크 할당량이 설정되어 있으면 다운로드 실패가 신속하게 보고되지 않음
  
디스크 할당량이 설정되어 있는 상태에서 할당량에 다다르면 WSUS 서버에서의 업데이트 다운로드 실패가 적절한 시기에 보고되지 않을 수 있습니다. 아 문제를 피하려면 디스크 할당량을 사용하지 않도록 설정하거나 할당량을 늘리십시오.
  
#### WSUS 3.0 SP1이 SSL을 사용하여 배포되는 경우 클라이언트 컴퓨터가 0x8024400a 오류 코드와 함께 실패할 수 있음
  
클라이언트 컴퓨터는 SSL을 사용하여 WSUS 3.0 SP1 서버와 함께 통신할 경우 때때로 0x8024400a 오류 코드와 함께 실패할 수 있습니다. 이 문제를 해결하는 업데이트에 대해서는 [KB 905422](http://go.microsoft.com/fwlink/?linkid=70593)(http://go.microsoft.com/fwlink/?LinkId=70593)를 참조하십시오.
  
#### WSUS가 제거될 때 WSUS Administrators 도메인 계정이 삭제되지 않음
  
WSUS Administrators 그룹은 도메인 컨트롤러의 도메인 계정(로컬 계정 아님)으로 만들어집니다. 따라서 이 도메인 계정을 사용하는 모든 설치는 WSUS 제거 시 계정이 삭제된 경우 사용하지 않도록 설정될 수 있습니다. 그러므로 WSUS를 제거해도 WSUS Administrators 도메인 계정은 삭제되지 않습니다.
  
#### 다운스트림 서버가 업스트림 서버로 변환되면 카탈로그 사이트 업데이트를 다시 가져와야 함
  
다운스트림 서버를 업스트림 서버로 수준을 올릴 경우 모든 카탈로그 사이트 업데이트도 다시 가져와야 합니다. 그렇지 않으면 사이트가 새 카탈로그 사이트 업데이트 수정 버전을 이 서버로 동기화할 수 없습니다.
  
#### SSL과 함께 IIS를 사용할 경우 "보안 채널 필요"가 선택되어 있지 않는 한 암호화되지 않은 액세스도 가능
  
인증서를 설치하여 SSL을 사용하도록 IIS를 설정할 경우에도 **보안 채널 필요** 옵션이 선택되어 있지 않는 한 암호화되지 않은 HTTP를 통해 사이트에 액세스할 수 있습니다. 자세한 내용은 [IIS](http://go.microsoft.com/fwlink/?linkid=98084)(http://go.microsoft.com/fwlink/?LinkId=98084)의 설명서를 참조하십시오.
  
#### %windir%\\TEMP 폴더에 대한 읽기/쓰기 권한이 없으면 카탈로그 사이트 가져오기가 실패할 수 있음
  
카탈로그 사이트 가져오기를 수행할 때 네트워크 서비스 계정에 %windir%\\TEMP 폴더에 대한 읽기/쓰기 권한이 없으면, 가져오기는 다음과 같은 오류 메시지와 함께 실패할 수 있습니다. 서버에서 요청을 처리할 수 없습니다. ---&gt; "C:\\WINDOWS\\TEMP\\*임시 파일 이름*.dll" 파일을 찾을 수 없습니다.
  
#### WSUS 2.0을 실행하는 다운스트림 복제 서버와 WSUS 3.0 SP1 간의 동기화 시 성능이 느려질 수 있음
  
업스트림 서버에 WSUS 3.0 SP1을 설치하고 WSUS 2.0을 실행하는 다운스트림 복제 서버와 함께 동기화하려는 경우 성능 문제가 발생할 수 있습니다. 이 문제를 해결하려면 [KB 910847](http://go.microsoft.com/fwlink/?linkid=70669)(http://go.microsoft.com/fwlink/?LinkId=70669)을 참조하십시오.
  
#### 전자 메일 서버가 다운되었거나 연결할 수 없는 경우 사전 통지 없이 전자 메일 알림이 실패함
  
네트워크의 전자 메일 서버가 오프라인 상태인 경우 WSUS 3.0 SP1에서 전자 메일 알림을 보낼 수 없습니다. 그러나 이벤트 로그에 이벤트 10052(HealthCoreEmailNotificationRed)를 씁니다.
  
#### 업스트림 서버에서 변경된 설정이 다운스트림 서버로 즉시 적용되지 않음
  
업스트림 서버 구성이 변경되는 경우 이러한 구성 변경 사항이 실제로 적용되기까지는 다소 시간이 걸릴 수 있습니다. 예를 들어, 새 언어 선택과 같이 업스트림 서버에서 설정을 변경하고 다운스트림 서버에서 동기화를 즉시 트리거할 경우 변경 사항이 나타나지 않습니다. 대신 다음 번에 예약된 동기화 시 다운스트림 서버에 적용됩니다. 대기 시간은 업스트림 서버에 있는 업데이트 수에 따라 늘어날 수 있습니다.
  
#### WSUS 3.0 SP1을 제거해도 데이터베이스 인스턴스가 제거되지 않음
  
WSUS 3.0 SP1이 제거되더라도 데이터베이스 인스턴스는 제거되지 않습니다. 인스턴스는 두 개 이상의 응용 프로그램에서 공유할 수 있으므로 인스턴스를 제거할 경우 다른 응용 프로그램에 오류가 발생할 수 있습니다.
  
Windows 내부 데이터베이스을(를) 제거해야 할 경우 다음 명령이 응용 프로그램을 제거합니다.
  
(32비트 플랫폼에서)
  
```  
msiexec /x {CEB5780F-1A70-44A9-850F-DE6C4F6AA8FB} callerid=ocsetup.exe  
```  
(64비트 플랫폼에서)
  
```  
msiexec /x {BDD79957-5801-4A2D-B09E-852E7FA64D01} callerid=ocsetup.exe  
```  
Windows 내부 데이터베이스 서비스 팩 2를 Windows Server 2008에서 제거하려면 서버 관리자를 사용하여 제거할 수 있습니다.
  
그러나 응용 프로그램을 제거해도 기본 .mdf 및 .ldf 파일이 제거되지 않을 수 있으며, 이는 이후 WSUS 3.0 SP1 설치가 실패하는 원인이 됩니다. 이러한 파일은 %windir%\\SYSMSI\\SSEE 디렉터리에서 삭제될 수 있습니다.
  
#### 다운스트림 서버가 해당 업스트림 서버를 변경할 경우 "알 수 없음" 상태 업데이트는 "적용할 수 없음"으로 보고됨
  
다운스트림 서버가 다른 업스트림 서버에서 동기화를 시작할 경우 **알 수 없음** 상태인 업데이트는 **적용할 수 없음**으로 새 업스트림 서버에서 보고됩니다. 이 상태는 일시적이며 다운스트림 서버의 클라이언트가 다운스트림 서버와 동기화된 후에 해당 다운스트림 서버에서 상태를 보고하고 나면 수정됩니다.
  
#### 서버 정리 마법사가 원격 콘솔로부터 여러 서버에서 실행될 때 하나의 서버에서 시간이 초과되면 모든 서버에 대한 연결을 잃음
  
단일 원격 콘솔로부터 여러 서버에서 서버 정리 마법사를 실행할 수 있습니다. 그러나 정리 프로세스가 해당 서버 중 하나에서 시간이 초과되면 콘솔이 모든 서버에 대한 연결을 잃게 됩니다. 데이터는 손실되지 않지만 관리자는 각 서버에 대한 원격 연결을 다시 설정해야 합니다.
  
#### 연속적으로 연결을 시작하고 중지하면 구성 마법사에서 "동기화 오류가 없습니다."라는 오류 메시지가 생성될 수 있음
  
WSUS를 구성할 때 서버에 대한 기본 정보를 전송하려면 업스트림 서버(Microsoft Update 또는 인트라넷 업스트림 서버 중 하나)에 연결되어야 합니다. **연결 시작**을 클릭한 다음 바로 **연결 중지**를 클릭하면 “동기화 오류가 없습니다.”라는 잘못된 오류 메시지를 받게 됩니다.
  
Windows Server 2008의 WSUS 3.0 SP1  
----------------------------------
  
#### 지원되는 버전
  
WSUS 3.0 SP1은 32비트 버전과 64비트 버전 모두에서 Windows Server 2008을(를) 지원합니다.
  
#### 필수 구성 요소
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >요구 사항</th>
<th style="border:1px solid black;" >세부 정보</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft 인터넷 정보 서비스(IIS)</td>
<td style="border:1px solid black;">운영 체제에서 설치합니다. 다음 구성 요소를 사용하도록 설정되어 있는지 확인하십시오.
<ul>
<li>Windows 인증<br />
<br />
</li>
<li>정적 콘텐츠<br />
<br />
</li>
<li>ASP.NET<br />
<br />
</li>
<li>6.0 관리 호환성<br />
<br />
</li>
<li>6.0 IIS 메타베이스 호환성<br />
<br />
</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft .NET Framework 버전 2.0 재배포 가능 패키지(x86)</td>
<td style="border:1px solid black;">Windows Server 2008의 필수 구성 요소는 아니지만 이미 운영 체제의 일부로 설치되어 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Management Console 3.0</td>
<td style="border:1px solid black;">Windows Server 2008의 필수 구성 요소는 아니지만 이미 운영 체제의 일부로 설치되어 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">WSUS 사용자 인터페이스를 사용하기 위한 필수 구성 요소입니다. <a href="http://go.microsoft.com/fwlink/?linkid=70410">Microsoft 다운로드 센터</a>(http://go.microsoft.com/fwlink/?LinkId=70410)의 Microsoft Report Viewer 재배포 가능 패키지 2005를 참조하십시오.</td>
</tr>
</tbody>
</table>
  
#### 보안 구성 마법사 사용
  
Windows Server 2008에서 SCW(보안 구성 마법사)를 실행할 때 WSUS 역할을 선택하고 해당 역할의 종속성을 사용하도록 설정할 수 있습니다. SCW를 실행하려면 **시작**을 클릭하고 **관리 도구**를 가리킨 다음 **보안 구성 마법사**를 클릭하십시오.
  
SCW를 WSUS 역할과 함께 사용할 때 다음과 같은 알려진 문제가 발생합니다.
  
-   **WSUS에서 Windows 내부 데이터베이스 서비스를 사용할 수 없으나 Windows 내부 데이터베이스 서비스를 사용하도록 설정되어 있습니다.** 데이터베이스(Windows 내부 데이터베이스 또는 SQL Server 데이터베이스)를 사용하도록 WSUS를 구성합니다. WSUS가 SQL Server를 사용하여 설치되고 SCW에서 WSUS 역할을 선택하면 Windows 내부 데이터베이스 서비스가 컴퓨터에 설치되어 있는 경우 Windows 내부 데이터베이스 서비스가 사용되도록 설정되지만 WSUS에서는 사용되지 않습니다. Windows 내부 데이터베이스 대신 SQL Server 데이터베이스를 사용할 경우 Windows 내부 데이터베이스 서비스를 사용하지 않도록 설정해야 합니다.  
-   **사용자 지정 웹 사이트에서 WSUS에 대한 방화벽 규칙은 기본적으로 선택되어 있지 않습니다.** 사용자 지정 웹 사이트(포트 8530 또는 포트 8531)에 WSUS를 설치하는 경우 SCW에서 WSUS 역할을 선택하더라도 필수 방화벽 규칙이 자동으로 선택되지 않습니다. WSUS 서버에 대한 SSL(Secure Sockets Layer)의 구성 여부를 기반으로 WSUS에 적절한 방화벽 규칙을 사용하도록 설정해야 합니다.
  
Windows Small Business Server 2003의 WSUS 3.0 SP1  
-------------------------------------------------
  
#### IIS 가상 루트가 특정 IP 주소 또는 도메인 이름으로 제한되어 있다면 WSUS 3.0 SP1 서버는 자체 업데이트할 수 없음
  
일부 Windows Small Business Server가 설치되면 **IP 주소 및 도메인 이름 제한**에 대해 구성된 기본 IIS 웹 사이트를 가질 수 있습니다. 그럴 경우 서버의 Windows Update 클라이언트는 자체 업데이트하지 못할 수도 있습니다.
  
#### Small Business Server에 WSUS 3.0 SP1 설치 - 통합 문제
  
-   Windows Small Business Server 2003에서 ISA 프록시 서버를 사용하여 인터넷에 액세스하는 경우 **설정** 사용자 인터페이스에서 **프록시 서버 설정, 프록시 서버 이름, 포트**를 입력해야 합니다.  
-   ISA가 Windows 인증을 사용하는 경우 프록시 서버 자격 증명은 *도메인*\\*사용자* 형식으로 입력해야 하고 사용자는 Internet Users 그룹의 구성원이어야 합니다.
  
#### Windows SBS 마법사 없이 네트워크에 서브넷을 추가한 경우 이 절차를 수행해야 함
  
WSUS 서버 설치 프로세스는 서버에 두 개의 IIS vroot, 즉 SelfUpdate 및 ClientWebService를 설치합니다. 설치 시 포트 80의 기본 웹 사이트에 있는 홈 디렉터리에 일부 파일도 배치되며, 이로써 클라이언트 컴퓨터가 기본 웹 사이트를 통해 자동으로 업데이트할 수 있습니다. 기본적으로 기본 웹 사이트는 로컬 호스트를 제외한 모든 IP 주소 또는 서버에 연결된 특정 서브넷에 대한 액세스를 거부하도록 구성되어 있습니다. 따라서 로컬 호스트 또는 그러한 특정 서브넷에 있지 않은 클라이언트 컴퓨터는 자동으로 업데이트할 수 없습니다. Microsoft Windows Small Business Server 2003(Windows SBS) 마법사 없이 네트워크에 서브넷을 추가한 경우 이 절차를 수행해야 합니다.
  
1.  서버 관리에서 **고급 관리**, **인터넷 정보 서비스**, **웹 사이트**, **기본 웹 사이트**를 차례로 확장하고 **Selfupdate** 가상 디렉터리를 마우스 오른쪽 단추로 클릭한 다음 **속성**을 클릭합니다.  
2.  **디렉터리 보안**을 클릭합니다.  
3.  **IP 주소 및 도메인 이름 제한**에서 **편집**을 클릭한 다음 **액세스 허가**를 클릭합니다.  
4.  **확인**을 클릭하고 **ClientWebService** 가상 디렉터리를 마우스 오른쪽 단추로 클릭한 다음 **속성**을 클릭합니다.  
5.  **디렉터리 보안**을 클릭합니다.  
6.  **IP 주소 및 도메인 이름 제한**에서 **편집**을 클릭한 다음 **액세스 허가**를 클릭합니다.
  
저작권  
------
  
URL 및 기타 인터넷 웹 사이트 참조를 비롯한 본 문서의 정보는 사전 통지 없이 변경될 수 있습니다. 별도로 명시하지 않는 한 본 문서의 예제에 표현된 회사, 조직, 제품, 도메인 이름, 전자 메일 주소, 로고, 사람, 장소 및 이벤트는 실제 데이터가 아닙니다. 어떠한 실제 회사, 조직, 제품, 도메인 이름, 전자 메일 주소, 로고, 사람, 장소 또는 이벤트와도 연관시킬 의도가 없으며 그렇게 유추해서도 안 됩니다. 해당하는 모든 저작권 법을 준수하는 것은 사용자의 의무입니다. 저작권 하의 권한 제한 없이 본 문서의 어떠한 부분도 Microsoft Corporation에서 명시하는 사용 권한 없이는 전자적 방법, 기계적 방법, 사진 복사 또는 녹음 등 어떠한 형태나 방법으로 또는 어떠한 목적으로도 재생산되거나, 검색 시스템에 저장 또는 도입되거나 전송될 수 없습니다.
  
Microsoft는 본 문서에서 주요하게 다루는 특허권, 특허 응용 프로그램, 상표, 저작권 또는 기타 지적 재산권을 가집니다. Microsoft로부터 작성된 모든 사용권 계약에서 제공하는 내용을 제외하고는 본 문서의 어떠한 내용도 이러한 특허권, 상표, 저작권 또는 기타 지적 재산에 대한 사용권을 제공하지 않습니다.
  
© 2007 Microsoft Corporation. All rights reserved.
  
Microsoft, SQL Server, Windows 및 Windows Server는 미국 및/또는 기타 국가에서의 Microsoft Corporation 등록 상표 또는 상표입니다.
  
기타 모든 상표는 해당 소유자의 자산입니다.
