---
TOCTitle: 'Windows Server Update Services 3.0 SP2 릴리스 정보'
Title: 'Windows Server Update Services 3.0 SP2 릴리스 정보'
ms:assetid: 'b3723422-489d-47b7-abfa-663353647da0'
ms:contentKeyID: 21743478
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd939886(v=WS.10)'
---

Windows Server Update Services 3.0 SP2 릴리스 정보
==================================================

이 릴리스 정보에서는 WSUS 3.0 SP2(Windows Server Update Services 3.0 서비스 팩 2) 릴리스에 대해 설명합니다. 이 문서에는 다음 섹션이 포함됩니다.

1.  이 릴리스의 새로운 기능
2.  WSUS 3.0 SP2 서버 설치를 위한 시스템 요구 사항
3.  WSUS 서버에 대한 필수 구성 요소 및 모범 사례 권장 사항
4.  Windows Small Business Server 필수 구성 요소
5.  WSUS 3.0 SP2 원격 콘솔 설치를 위한 시스템 요구 사항
6.  클라이언트 설치를 위한 시스템 요구 사항
7.  업그레이드 요구 사항 및 권장 사항
8.  WSUS 3.0 SP2 설치
9.  WSUS 3.0 SP2 무인 설치를 위한 설치 프로그램 명령줄 매개 변수
10. 알려진 문제

이 릴리스의 새로운 기능
-----------------------

-   Windows Server 2008 R2와 통합
-   Windows Server 2008 R2에서 BranchCache 기능 지원.
-   Windows 7 클라이언트 지원.
-   WUA(Windows Update Agent) 클라이언트 고급 기능. 새로운 WUA 클라이언트에서는 성능 향상, 사용자 경험 개선 및 고객 의견을 기반으로 한 일련의 버그 수정 모음을 제공합니다.
    -   클라이언트 스캔 속도가 이전 버전보다 빠릅니다.
    -   이제 WSUS 서버가 관리하는 컴퓨터가 전체 스캔을 수행하는 대신 동일한 WSUS 서버에 대해 '범위' 스캔을 실행할 수 있습니다. 이로 인해 Windows Defender와 같은 Microsoft Update API를 사용하는 응용 프로그램에 대한 스캔이 훨씬 더 빨라집니다.
    -   WUA(Windows Update Agent) 사용자 경험 고급 기능은 업데이트를 더 잘 구성하고 업데이트 값 및 동작을 더 명확히 이해하는 데 도움이 됩니다.
    -   이미지로 만들어진 시스템이 WSUS 콘솔에서 더 선명하게 표시됩니다. 자세한 내용은 문서 [Windows 2000, Windows Server 2003 또는 Windows XP 이미지를 사용하여 설정된 Windows 2000 기반 Windows Server 2003 기반 또는 Windows XP 기반 컴퓨터가 WSUS 콘솔에서 나타나지 않습니다](http://go.microsoft.com/fwlink/?linkid=159749)를 참조하십시오.
-   새로운 기능:
    -   자동 승인 규칙에 모든 컴퓨터 또는 특정 컴퓨터 그룹에 대한 승인 마감 날짜 및 시간을 지정하는 기능이 포함되어 있습니다.
    -   다운스트림 서버에 대한 언어 선택 처리가 향상되어 지정된 언어에 대해서만 업데이트를 다운로드할 경우 새 경고 대화 상자가 표시됩니다.
    -   새 업데이트 및 컴퓨터 상태 보고서를 사용하면 설치를 위해 승인된 업데이트를 필터링할 수 있습니다. WSUS 콘솔에서 이러한 보고서를 실행하거나 API(응용 프로그래밍 인터페이스)를 사용하여 이 기능을 사용자의 보고서에 통합할 수 있습니다.
-   클라이언트와 서버 모두에서 WSUS 3.0 서비스 팩 1과 서비스 팩 2의 사용자 인터페이스가 호환됩니다.
-   소프트웨어 업데이트
-   이 릴리스에서 해결된 Windows Update 에이전트 관련 알려진 문제:
    1.  WSUS 3.0 SP2 및 Windows 7에는 Windows Update 에이전트의 새 릴리스(Windows XP, Windows Vista, Windows Server 2000, Windows Server 2003 및 Windows Server 2008용)가 포함되어 있습니다. 이 릴리스에서는 비대화형 세션에서 로컬이 아닌 시스템 호출자가 호출한 API가 실패하는 문제가 해결되었습니다.
    2.  Windows Update 에이전트 7.2.6001.788 버전에서 해결된 문제. 이 업데이트에서는 Windows Update 웹 페이지 또는 Microsoft Update 웹 페이지에서 80개 이상의 업데이트를 동시에 설치할 경우 0x80070057 오류 코드가 표시되는 문제가 해결되었습니다.
    3.  Windows Update 에이전트 7.2.6001.784 버전에서 해결된 문제 및 향상된 기능. 이 업데이트에 포함된 내용은 다음과 같습니다. Windows Update의 검색 시간 단축, 서명 업데이트 제공 속도 향상, Windows Installer 다시 설치 기능 사용 및 오류 메시지 개선

<span id="BKMK_SysReqWSUS30SP2"></span>
WSUS 3.0 SP2 서버 설치를 위한 시스템 요구 사항
----------------------------------------------

이 섹션에서는 WSUS 3.0 SP2 설치에 필요한 소프트웨어 및 하드웨어 요구 사항에 대해 설명합니다.

### WSUS 서버 소프트웨어 요구 사항

-   다음의 지원되는 운영 체제 중 하나가 설치되어 있어야 합니다.
    -   Windows Server 2008 R2
    -   Windows Server 2008 SP1 이상 버전
 
        <table style="border:1px solid black;">
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><img src="images/Dd939886.Warning(WS.10).gif" />경고</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td style="border:1px solid black;">Windows Server 2008 R2로 업그레이드하기 전에 WSUS 3.0 SP2가 Windows Server 2008에 설치되어 있으면 Windows Server 2008 R2으로 업그레이드할 수 없습니다. 자세한 내용은 <a href="#bkmk_knownissues">알려진 문제</a> 섹션을 참조하십시오.
        </td>
        </tr>
        </tbody>
        </table>
 

    -   Windows Server 2003 SP1 이상 버전
    -   Windows Small Business Server 2008
    -   Windows Small Business Server 2003

    Windows Small Business Server에는 추가 필수 구성 요소가 적용됩니다. 자세한 내용은 "Windows Small Business Server 필수 구성 요소" 섹션을 참조하십시오.
-   IIS(인터넷 정보 서비스) 6.0 이상 버전
-   Microsoft .NET Framework 2.0 이상 버전
-   다음의 지원되는 데이터베이스 중 하나가 설치되어 있어야 합니다.
    -   Microsoft SQL Server 2008 Standard 또는 Enterprise Edition
    -   Microsoft SQL Server 2005 SP3 이상 버전
    -   Windows 내부 데이터베이스

    지원되는 SQL Server 버전이 설치되어 있지 않은 경우 WSUS 3.0 SP2 설치 마법사가 Windows 내부 데이터베이스를 설치합니다.
-   Microsoft Management Console 3.0
-   Microsoft Report Viewer 재배포 가능 패키지 2008

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><img src="images/Dd939886.Important(WS.10).gif" />중요</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 R2에는 WSUS 3.0 SP2가 필요합니다. 따라서 Windows Server 2008 R2를 설치할 경우 WSUS 3.0 SP2를 설치해야 합니다. Windows Server 2008 R2에 WSUS 3.0 SP1을 설치하지 마십시오.

WSUS 3.0 SP2는 원격 SQL 구성의 프런트 엔드 서버에서 터미널 서비스와 사용할 수 없습니다.
</td>
</tr>
</tbody>
</table>
 

### WSUS 관리 콘솔 소프트웨어 필수 구성 요소

-   지원되는 운영 체제: Windows Server 2008 R2, Windows Server 2008, Windows Server 2003 SP2 이상 버전, Windows Small Business Server 2008 또는 Windows Small Business Server 2003, Windows Vista 또는 Windows XP SP2
-   Microsoft .NET Framework 2.0 이상 버전
-   Microsoft Management Console 3.0
-   Microsoft Report Viewer 재배포 가능 패키지 2008

### WSUS 서버 하드웨어 최소 요구 사항

다음 목록에는 기본 서버 설치에 필요한 최소 하드웨어 요구 사항이 포함되어 있습니다. 지원되는 하드웨어 구성의 전체 목록을 보려면 WSUS 3.0 SP2 배포 안내서([http://go.microsoft.com/fwlink/?LinkId=139832](http://go.microsoft.com/fwlink/?linkid=139832)(영문))를 참조하십시오.

-   시스템 파티션과 WSUS 3.0 SP2를 설치할 파티션 모두 NTFS 파일 시스템으로 포맷해야 합니다.
-   시스템 파티션에 최소 1GB의 사용 가능한 공간이 있어야 합니다.
-   데이터베이스 파일을 저장할 볼륨에 최소 2GB의 사용 가능한 공간이 있어야 합니다.
-   콘텐츠를 저장할 볼륨에 최소 20GB(30GB 권장)의 사용 가능한 공간이 있어야 합니다.

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><img src="images/Dd939886.Important(WS.10).gif" />중요</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">압축 드라이브에는 WSUS 3.0 SP2를 설치할 수 없습니다.
</td>
</tr>
</tbody>
</table>
 

WSUS 서버에 대한 필수 구성 요소 및 모범 사례 권장 사항
------------------------------------------------------

WSUS 3.0 SP2를 설치하기 전에 이 섹션의 해당 작업을 완료해야 합니다.

### IIS

-   서버 관리자 웹 서버(IIS) 역할 서비스 페이지에서 필요한 기능, 모든 기본 IIS 역할 서비스 및 다음 역할 서비스를 설치하십시오. **ASP.NET**, **Windows 인증**, **동적 콘텐츠 압축** 및 **IIS 6 관리 호환성**.
-   IIS가 IIS 5.0 격리 모드에서 실행되는 경우 설치에 실패합니다. WSUS 3.0 SP2를 설치하기 전에 IIS 5.0 격리 모드를 비활성화하십시오.
-   IIS 구성 요소가 64비트 플랫폼에서 32비트 호환 모드로 설치되어 있으면 WSUS 3.0 SP2 설치에 실패할 수 있습니다. 모든 IIS 구성 요소는 64비트 플랫폼에서 기본 모드로 설치해야 합니다.

### 프록시 서버

WSUS 3.0 SP2를 사용하면 프록시 서버에서 HTTP만 지원할 수 있습니다. 구성 마법사 또는 관리 콘솔에서 WSUS 서버를 구성하기 전에 명령줄(**wsusutil configuresslproxy**)을 사용하여 HTTPS를 실행하는 보조 프록시 서버를 구성하는 것이 가장 좋습니다.

### 포트 80에서 실행 중인 웹 사이트

포트 80에서 두 개 이상의 웹 사이트가 실행 중인 경우(예: Windows SharePoint Services) WSUS를 설치하기 전에 하나의 웹 사이트를 제외한 모든 웹 사이트를 삭제합니다. 그렇지 않으면 서버의 클라이언트가 자동으로 업데이트되지 않을 수 있습니다.

### 바이러스 백신 프로그램

WSUS 3.0 SP2를 설치할 때 성공적으로 설치를 완료하려면 바이러스 백신 프로그램을 사용하지 않도록 설정해야 할 수 있습니다. 바이러스 백신 프로그램을 사용하지 않도록 설정하는 경우 컴퓨터를 다시 시작한 다음 WSUS를 설치하십시오. 컴퓨터를 다시 시작하면 설치 과정에서 액세스해야 하는 파일이 잠기지 않습니다. 설치가 완료되면 바이러스 백신 소프트웨어를 다시 사용하도록 설정해야 합니다. 바이러스 백신 소프트웨어와 버전을 사용하지 않도록 설정했다가 다시 사용하도록 설정하는 정확한 단계를 알아보려면 바이러스 백신 소프트웨어 공급업체의 웹 사이트를 방문하십시오.

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><img src="images/Dd939886.Caution(WS.10).gif" />주의</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">이 방법을 사용하면 컴퓨터나 네트워크가 악의적인 사용자나 바이러스 같은 악의적인 소프트웨어의 공격에 더 취약해질 수 있습니다. Microsoft는 이 방법을 권장하지 않지만 사용자 자신이 판단하여 이 해결 방법을 구현할 수 있도록 하기 위해 이 정보를 제공합니다. 이 해결 방법의 사용에 따른 모든 문제는 사용자의 책임입니다.

바이러스 백신 소프트웨어를 사용하여 바이러스로부터 컴퓨터를 보호할 수 있습니다. 신뢰하지 않는 출처의 파일을 다운로드하거나 열지 말고 신뢰하지 않는 웹 사이트를 방문하지 마십시오. 또는 바이러스 백신 프로그램을 사용하지 않도록 설정한 경우 전자 메일 첨부 파일을 열지 마십시오.
</td>
</tr>
</tbody>
</table>
 

### SQL Server의 중첩 트리거 옵션

SQL Server 데이터베이스를 Windows Server Update Services 데이터 저장소로 사용하려면 WSUS 관리자가 WSUS 3.0 SP2를 설치하기 전에 SQL Server 관리자가 서버에 중첩 트리거 옵션이 설정되어 있는지 확인해야 합니다. 중첩 트리거 옵션은 기본적으로 설정되어 있습니다. 그러나 SQL Server 관리자가 이 옵션을 해제할 수 있습니다. WSUS 3.0 SP2 설치 프로그램에서는 데이터베이스 고유 옵션인 RECURSIVE\_TRIGGERS 옵션을 사용합니다. 그러나 서버 전역 옵션인 중첩 트리거 옵션은 사용하지 않습니다.

### 원격 SQL 제한 사항 및 요구 사항

WSUS 3.0 SP2에서는 WSUS 3.0 SP2 응용 프로그램을 실행 중인 컴퓨터와 별도인 컴퓨터에서 SQL Server 소프트웨어 호환 버전을 실행할 수 있습니다. 원격 SQL 설치에 적용되는 요구 사항은 다음과 같습니다.

-   원격 SQL 쌍의 백엔드를 위한 도메인 컨트롤러로 구성된 서버는 사용할 수 없습니다.
-   원격 SQL 설치의 프런트 엔드 서버로 사용할 컴퓨터에서 터미널 서비스를 실행할 수 없습니다.
-   프런트 엔드 컴퓨터와 백엔드 컴퓨터를 모두 Active Directory 도메인에 연결해야 합니다. 프런트 엔드 컴퓨터와 백엔드 컴퓨터가 서로 다른 도메인에 있는 경우 도메인 간에 상호 도메인 트러스트를 설정한 다음 WSUS 설치 프로그램을 실행합니다.
-   원격 SQL 구성에 WSUS 2.0이 이미 설치된 경우 WSUS 3.0 SP2로 업그레이드하려면 WSUS를 설치하기 전에 다음을 수행합니다.
    1.  기존 데이터베이스는 그대로 유지하면서 제어판의 **프로그램 추가/제거**를 사용하여 WSUS 2.0을 제거합니다.
    2.  SQL Server 2005 SP2 또는 SQL Server 2008을 설치하고 기존 데이터베이스를 업그레이드합니다.

### IIS가 WSUS 3.0 SP2 설치 중에 다시 시작됨

WSUS 3.0 SP2를 설치하면 알림 없이 IIS가 다시 시작됩니다. 이로 인해 조직에 있는 기존 웹 사이트가 영향을 받을 수 있습니다. 이 설치를 실행하기 전에 영향을 받는 대상에게 알리는 것이 가장 좋습니다. IIS가 실행되고 있지 않으면 WSUS 3.0 SP2 설치 프로그램이 설치 중에 IIS를 시작합니다.

Windows Small Business Server 필수 구성 요소
--------------------------------------------

Windows Small Business Server에 WSUS 3.0 SP2를 설치하는 경우 다음과 같은 필수 조건이 적용됩니다.

### IIS 가상 루트가 특정 IP 주소나 도메인 이름으로 제한되는 경우

Windows Small Business Server의 일부 설치에 **IP 주소 및 도메인 이름 제한**을 사용하도록 구성된 기본 IIS 웹 사이트가 있을 수 있습니다. 이 경우 서버의 Windows Update Client에서 자동으로 업데이트할 수 없습니다. 제한 사항을 제거한 다음 WSUS 3.0 SP2를 설치하십시오.

### ISA 프록시 서버를 사용 중인 경우

-   Windows Small Business Server에서 ISA 프록시 서버를 사용하여 인터넷에 액세스하는 경우 **설정** UI(사용자 인터페이스)에 **프록시 서버 설정,프록시 서버 이름, 포트**를 입력합니다.
-   ISA에서 Windows 인증을 사용하는 경우 프록시 서버 자격 증명을 *DOMAIN*\\*user* 형식으로 입력합니다. 사용자가 인터넷 사용자 그룹의 구성원이어야 합니다.

### Windows Small Business Server 마법사를 사용하지 않고 네트워크에 서브넷을 추가한 경우

WSUS 서버 설치 과정 중에 서버에 두 개의 IIS vroot인 SelfUpdate와 ClientWebService가 설치됩니다. 또한 클라이언트 컴퓨터가 기본 웹 사이트를 통해 자동으로 업데이트할 수 있는 기본 웹 사이트(80 포트)의 루트 디렉터리 아래에 일부 파일이 배치됩니다. 기본적으로 기본 웹 사이트는 localhost 이외의 모든 IP 주소 또는 서버에 연결된 특정 서브넷에 대한 액세스를 거부하도록 구성되어 있습니다. 따라서 localhost에 없거나 해당하는 특정 서브넷에 있는 클라이언트 컴퓨터는 자동으로 업데이트할 수 없습니다. Microsoft Windows Small Business Server 마법사를 사용하지 않고 네트워크에 서브넷을 추가한 경우 다음 절차를 수행해야 합니다.

1.  서버 관리에서 **고급 관리**, **인터넷 정보 서비스**, **웹 사이트**, **기본 웹 사이트**를 차례로 확장하고 **Selfupdate** 가상 디렉터리를 마우스 오른쪽 단추로 클릭한 다음 **속성**을 클릭합니다.
2.  **디렉터리 보안**을 클릭합니다.
3.  **IP 주소 및 도메인 이름 제한**에서 **편집**을 클릭한 다음 **액세스 허가**를 클릭합니다.
4.  **확인**을 클릭하고 **ClientWebService** 가상 디렉터리를 마우스 오른쪽 단추로 클릭한 다음 **속성**을 클릭합니다.
5.  **디렉터리 보안**을 클릭합니다.
6.  **IP 주소 및 도메인 이름 제한**에서 **편집**을 클릭한 다음 **액세스 허가**를 클릭합니다.

WSUS 3.0 SP2 원격 콘솔 설치를 위한 시스템 요구 사항
---------------------------------------------------

WSUS 3.0 SP2 원격 콘솔을 설치할 수 있는 운영 체제:

-   Windows Server 2008 R2, Windows Server 2008 SP1 이상 버전, Windows Server 2003 SP2 이상 버전, Windows Small Business Server 2003, Windows Small Business Server 2005 또는 Windows Small Business Server 2008, Windows Vista 또는 Windows XP Professional SP3 이상 버전.

WSUS 클라이언트 설치를 위한 시스템 요구 사항
--------------------------------------------

WSUS 클라이언트 소프트웨어인 자동 업데이트를 설치할 수 있는 운영 체제:

-   Windows Server 2008 R2, Windows Server 2008 SP1 이상 버전, Windows Server 2003 SP2 이상 버전, Windows Small Business Server 2003, Windows Small Business Server 2005 또는 Windows Small Business Server 2008, Windows Vista 또는 Windows XP Professional RTM, Windows XP Professional SP1, Windows XP Professional SP2, Windows XP Professional SP3 이상 버전, Windows 2000 SP4 또는 Windows 7 클라이언트.

업그레이드 요구 사항 및 권장 사항
---------------------------------

다음 WSUS 버전을 WSUS 3.0 SP2로 업그레이드할 수 있으며 이전 버전을 제거할 필요가 없습니다.

-   WSUS 2.0, 2.0 SP1, 3.0 및 3.0 SP1

WSUS 1.0에서 WSUS 3.0 SP2로 업그레이드할 수 없습니다. SUS(Software Update Services) 1.0을 제거한 후에 WSUS 3.0 SP2를 설치하십시오.

Windows Server 2008 R2에는 WSUS 3.0 SP2가 필요합니다. 따라서 Windows Server 2008 R2를 설치할 경우 WSUS 3.0 SP2를 설치해야 합니다. Windows Server 2008 R2에 WSUS 3.0 SP1을 설치하지 마십시오.

#### WSUS 3.0 SP2로 업그레이드하기 전에

1.  이벤트 로그에서 최근에 발생한 오류가 있는지 확인하고 다운스트림 서버와 업스트림 서버 간의 동기화 문제 및 클라이언트 보고 문제가 있는지 확인합니다. 업그레이드하기 전에 이러한 문제를 해결합니다.

2.  선택적으로 DBCC CHECKDB를 실행하여 WSUS 데이터베이스가 제대로 인덱싱되는지 확인할 수 있습니다. DBCC CHECKDB에 대한 자세한 내용은 [DBCC CHECKDB](http://go.microsoft.com/fwlink/?linkid=86948)(영문)를 참조하십시오.

3.  WSUS 데이터베이스를 백업합니다. WSUS 3.0 SP2 설치 프로그램은 새 데이터베이스를 기본 디렉터리(*drive*\\WSUS)에 추가합니다. 여기서 *drive*는 사용 가능한 공간이 가장 많은 로컬 NTFS 드라이브입니다. 이 디렉터리에 데이터베이스 백업이 이미 있는 경우 해당 백업을 덮어쓸 수 있습니다. WSUS 3.0 SP2로 업그레이드하기 전에 현재 버전의 WSUS 데이터베이스 백업을 다른 위치에 저장하는 것이 좋습니다.

4.  WSUS에 사용되는 포트를 수동으로 변경하고(즉, Wsusutil 유틸리티를 사용하지 않음) 현재 SUS 1.0 또는 WSUS 2.0을 실행 중인 경우 SUS 1.0 또는 WSUS 2.0 64비트를 제거하기 전에 기본 웹 사이트를 시작합니다.

5.  기존 WSUS 데이터베이스에 대한 연결이 열려 있으면(예: SQL Server Management Studio가 열려 있는 경우) 설치에 실패할 수 있습니다. WSUS 3.0 SP2를 설치하기 전에 모든 연결을 닫으십시오.

### 실패한 업그레이드에서 복구

이전 버전의 WSUS에서 WSUS 3.0 SP2로 업그레이드할 때 SUS 1.0에서 지원되지 않는 업그레이드를 시도한 경우가 아닌 다른 이유로 업그레이드에 실패할 경우 다음 작업을 수행합니다.

1.  이전 버전의 WSUS를 다시 설치합니다.
2.  업그레이드를 시도하기 전에 만든 백업에서 데이터베이스를 복원합니다. 이전에 설치한 기존 WSUS 3.0 SP2 데이터베이스가 있는 경우 업그레이드를 완료할 수 없습니다. 대부분의 경우 WSUS에서 백업을 자동으로 만듭니다. 위치에 대한 정보는 WSUSSetup.log 파일을 참조하십시오.
3.  로그를 검토하여 실패의 원인을 확인하고 문제를 해결합니다.
4.  WSUS 3.0 SP2를 설치합니다.

### WSUS 3.0 SP2로 업그레이드하기 전에 컴퓨터 이름을 변경하면 업그레이드가 실패할 수 있음

WSUS 2.0을 설치한 후 WSUS 3.0 SP2로 업그레이드하기 전에 컴퓨터 이름을 변경하면 업그레이드가 실패할 수 있습니다.

다음 스크립트를 사용하여 ASPNET 및 WSUS Administrators 그룹을 제거했다가 다시 추가하십시오. 그런 다음 업그레이드를 다시 실행합니다.

        ```

### MSDE에서 WSUS 2.0의 SQL Server 2008 또는 SQL Server 2005로 마이그레이션한 경우 레지스트리 값을 변경해야 함

WSUS 2.0을 설치하고 SQL Server 2008 또는 SQL Server 2005로 마이그레이션한 경우 **HKLM\\SOFTWARE\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled** 값을 1에서 0으로 변경해야 합니다. 값을 변경하지 않고 WSUS 3.0 SP2로 업그레이드하면 업그레이드에 실패합니다.

### WSUS 3.0 SP2를 제거하고 로그 파일을 그대로 남겨 두면 다시 설치 후 올바른 사용 권한을 얻을 수 없음

WSUS 3.0 SP2를 제거할 때 설치 로그 파일을 유지할 수 있습니다. WSUS 3.0 SP2를 다시 설치하면 이전 로그 파일의 사용 권한(보통 WSUS Administrators만 해당)이 삭제될 수 있습니다. 설치 후 로그 파일에서 사용 권한을 확인하는 것이 좋습니다.

### WSUS 2.0 클라이언트에 "해당 없음" 상태의 업데이트가 있는 경우 WSUS 3.0 SP2로 업그레이드한 후 잠시 동안 업데이트가 "알 수 없음"으로 표시됨

기존 WSUS 2.0 서버에 **해당 없음** 상태의 업데이트가 있는 클라이언트가 있는 경우 WSUS 3.0 SP2로 업그레이드한 후 잠시 동안 해당 업데이트의 상태가 **알 수 없음**으로 표시될 수 있습니다. 다음에 클라이언트가 검색을 수행한 이후에 업데이트 상태가 **해당 없음**으로 되돌아갑니다.

WSUS 3.0 SP2 설치
-----------------

Windows 서버 관리자 또는 WSUSSetup.exe 파일을 사용하여 WSUS 3.0 SP2를 설치하는 방법에 대한 자세한 내용은 WSUS 단계별 설치 안내서([http://go.microsoft.com/fwlink/?LinkId=139836](http://go.microsoft.com/fwlink/?linkid=139836))를 참조하십시오.

WSUS를 설치 및 사용하는 방법에 대한 자세한 내용은 다음을 참조하십시오.

WSUS 배포 가이드([http://go.microsoft.com/fwlink/?LinkId=139832](http://go.microsoft.com/fwlink/?linkid=139832))

WSUS 운영 가이드([http://go.microsoft.com/fwlink/?LinkId=139838](http://go.microsoft.com/fwlink/?linkid=139838))

WSUS 3.0 SP2 무인 설치를 위한 설치 프로그램 명령줄 매개 변수
------------------------------------------------------------

WSUS 명령줄 설치 프로그램을 사용하여 WSUS 3.0 SP2를 무인 설치할 수 있습니다. 다음 표에는 WSUS 3.0 SP2 설치의 명령줄 매개 변수가 표시되어 있습니다.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>옵션</th>
<th>설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>/q</strong></td>
<td style="border:1px solid black;">자동 설치를 수행합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/u</strong></td>
<td style="border:1px solid black;">제거합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/p</strong></td>
<td style="border:1px solid black;">필수 구성 요소 검사. 시스템을 검사하고 누락된 필수 구성 요소를 보고합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/?, /h</strong></td>
<td style="border:1px solid black;">명령줄 매개 변수 및 해당 설명을 표시합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/g</strong></td>
<td style="border:1px solid black;">이전 버전의 WSUS에서 업그레이드합니다. SUS 1.0에서는 업그레이드할 수 없습니다. 이 옵션에는 /q(자동 설치) 매개 변수만 사용할 수 있습니다. 이 옵션에는 DEFAULT_WEBSITE 속성만 사용할 수 있습니다.</td>
</tr>
</tbody>
</table>
  
다음 표에는 WSUS 3.0 SP2의 명령줄 속성이 표시되어 있습니다.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>속성</th>
<th>설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">CONTENT_LOCAL</td>
<td style="border:1px solid black;">0=로컬로 호스팅되는 콘텐츠, 1=Microsoft Update에서 호스팅</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CONTENT_DIR</td>
<td style="border:1px solid black;">콘텐츠 디렉터리의 경로. 기본값은 <em>WSUSInstallationDrive\WSUS\WSUSContent</em>입니다. 여기서 <em>WSUSInstallationDrive</em>는 사용 가능한 공간이 가장 많은 로컬 드라이브입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WYUKON_DATA_DIR</td>
<td style="border:1px solid black;">Windows 내부 데이터베이스 데이터 디렉터리에 대한 경로.</td>
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
<td style="border:1px solid black;">0=로그 파일 유지, 1=로그 파일 제거(/u 설치 스위치와 함께 사용)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATE_DATABASE</td>
<td style="border:1px solid black;">0=현재 데이터베이스 사용, 1=데이터베이스 작성</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROGRESS_WINDOW_HANDLE</td>
<td style="border:1px solid black;">Windows Installer 진행률 메시지를 반환하는 창 핸들</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MU_ROLLUP</td>
<td style="border:1px solid black;">1=Microsoft Update 개선 프로그램 참여, 0=Microsoft Update 개선 프로그램 참여하지 않음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">FRONTEND_SETUP</td>
<td style="border:1px solid black;">1=데이터베이스에 콘텐츠 위치를 쓰지 않음, 0=데이터베이스에 콘텐츠 위치를 씀(NLB)</td>
</tr>
</tbody>
</table>
  
### 사용법 예제
  
```  
WSUSSetup.exe /q DEFAULT\_WEBSITE=0(포트 8530을 사용하여 자동 모드에서 설치) WSUSSetup.exe /q /u(WSUS 제거)  
```
 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><img src="images/Dd939886.Important(WS.10).gif" />중요</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">WSUS 3.0 SP2를 자동 모드(/q)로 설치하는 경우 컴퓨터에 모든 필수 구성 요소가 설치되어 있지 않으면 설치 시 WSUSPreReqCheck.xml이라는 파일이 생성되어 %TEMP% 디렉터리에 저장됩니다.
</td>
</tr>
</tbody>
</table>
 

<span id="BKMK_KnownIssues"></span>
알려진 문제
-----------

-   WSUS 설치 마법사를 완료하면 **마침**을 클릭하라는 지침이 나타납니다. 드물지만 "**서버와 통신하는 동안 오류가 발생했습니다. 이 마법사를 닫아야 합니다. WSUS 콘솔의 옵션 페이지에서 WSUS 서버 구성 마법사를 다시 시작할 수도 있습니다.**"라는 메시지가 포함된 오류 대화 상자가 표시되는 경우가 있습니다. 설치 선택 사항이 저장되었는지 확인하려면 WSUS 관리 콘솔에서 **옵션** 페이지를 열고 각 섹션의 설정을 확인하십시오.
-   **WUA(Windows Update Agent) 클라이언트의 지역화 버전은 WSUS 3.0 SP2 이후에 릴리스됩니다**. 이는 Windows 7 지역화 일정에 의존하기 때문입니다. WSUS 3.0 SP2 릴리스와 WUA 클라이언트의 지역화 릴리스 간의 시간 동안에는 WUA 클라이언트가 5개의 언어(영어, 독일어, 프랑스어, 스페인어 및 일본어)만 지원합니다.
-   **이 SP2 릴리스에서 도입된 새로운 업데이트 및 컴퓨터 상태 보고서는 다운스트림 WSUS 3.0 SP1 서버가 WSUS 3.0 SP2 서버에서 관리되는 환경에서는 제대로 작동하지 않습니다**. SP1 서버에 대해 새로운 보고서가 실행되는 경우 다음 오류 메시지가 나타납니다. “보고서를 생성하는 동안 오류가 발생했습니다. 보고서를 다시 실행하거나 문제가 계속되면 네트워크 관리자에게 문의하십시오.” 보고서를 다시 실행하면 문제가 해결되지 않고 네트워크와 관련한 이러한 문제도 해결되지 않습니다. 새 보고서는 SP1에 없는 API 기능에 따라 달라집니다. 하지만 SP2 관리 콘솔은 SP1 서버 관리 시 새 보고서를 차단하지 않습니다.
-   **SSL이 인증서 이름 없이 구성되어 있으면 WSUS 3.0 SP2로 업그레이드할 수 없습니다**. SSL을 구성하는 경우에는 인증서 이름이 필요합니다.
-   **WSUS 3.0 SP2가 Windows Server 2008에 설치된 Windows 내부 데이터베이스을 실행하는 경우 Windows Server 2008 R2**으로 업그레이드할 수 없습니다. Windows Server 2008 R2으로의 업그레이드를 계속하기 전에 Windows 내부 데이터베이스을 해제하라는 호환성 보고서 오류 메시지가 나타납니다. Windows Server 2008 R2으로의 업그레이드를 계속하려면 먼저 Windows 내부 데이터베이스을 업그레이드해야 합니다. Windows 내부 데이터베이스 업그레이드에 대한 자세한 지침 및 정보는 [Windows 내부 데이터베이스의 최신 서비스 팩을 구하는 방법](http://go.microsoft.com/fwlink/?linkid=162104)(http://go.microsoft.com/fwlink/?LinkId=162104)을 참조하십시오.

저작권 표시
-----------

URL 및 기타 인터넷 웹 사이트 참조를 포함하여, 이 설명서의 내용은 예고 없이 변경될 수 있습니다. 다른 설명이 없는 한, 용례에 사용된 회사, 조직, 제품, 도메인 이름, 전자 메일 주소, 로고, 사람, 장소 및 이벤트는 실제 데이터가 아닙니다. 어떠한 실제 회사, 조직, 제품, 도메인 이름, 전자 메일 주소, 로고, 사람, 장소 또는 이벤트와도 연관시킬 의도가 없으며 그렇게 유추해서도 안 됩니다. 해당 저작권법을 준수하는 것은 사용자의 책임입니다. 저작권에서의 권리와는 별도로, 이 설명서의 어떠한 부분도 Microsoft Corporation의 명시적인 서면 승인 없이는 어떠한 형식이나 수단(전기적, 기계적, 복사기에 의한 복사, 디스크 복사 또는 다른 방법) 또는 목적으로도 복제되거나, 검색 시스템에 저장 또는 도입되거나, 전송될 수 없습니다.

Microsoft가 이 설명서 본안에 관련된 특허권, 상표권, 저작권, 또는 기타 지적 재산권 등을 보유할 수도 있습니다. 서면 사용권 계약에 따라 Microsoft로부터 귀하에게 명시적으로 제공한 권리 이외에, 이 설명서의 제공은 귀하에게 이러한 특허권, 사용권, 저작권 또는 기타 지적 소유권 등에 대한 어떠한 사용 권한도 제공하지 않습니다.

ⓒ 2009 Microsoft Corporation. 모든 권리 보유.

Microsoft, Active Directory, ActiveX, Authenticode, Excel, InfoPath, Internet Explorer, MSDN, Outlook, Visual Studio, Win32, Windows, Windows Server 및 Windows Vista는 Microsoft 그룹사의 상표입니다.

다른 모든 상표는 해당 소유자의 소유입니다.
