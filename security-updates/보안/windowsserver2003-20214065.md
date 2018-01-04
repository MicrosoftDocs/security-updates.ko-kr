---
TOCTitle: Windows Server 2003 도메인 컨트롤러 강화
Title: Windows Server 2003 도메인 컨트롤러 강화
ms:assetid: '495f18d7-9e57-4c28-b9f9-e6ca1d60b2ca'
ms:contentKeyID: 20214065
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547910(v=TechNet.10)'
---

Windows Server 2003 도메인 컨트롤러 강화
========================================

##### 이 페이지에서

[](#xsltsection121121120120)[모듈 정보](#xsltsection121121120120)
[](#xsltsection122121120120)[목표](#xsltsection122121120120)
[](#xsltsection123121120120)[적용 범위](#xsltsection123121120120)
[](#xsltsection124121120120)[모듈 사용법](#xsltsection124121120120)
[](#xsltsection125121120120)[개요](#xsltsection125121120120)
[](#xsltsection126121120120)[감사 정책 설정](#xsltsection126121120120)
[](#xsltsection127121120120)[사용자 권한 할당](#xsltsection127121120120)
[](#xsltsection128121120120)[보안 옵션](#xsltsection128121120120)
[](#xsltsection129121120120)[이벤트 로그 설정](#xsltsection129121120120)
[](#xsltsection130121120120)[시스템 서비스](#xsltsection130121120120)
[](#xsltsection131121120120)[추가 보안 설정](#xsltsection131121120120)
[](#xsltsection132121120120)[요약](#xsltsection132121120120)<span id="XSLTsection121121120120"></span>
모듈 정보
---------

이 모듈에서는 Microsoft Windows Server™ 2003 운영 체제 기반 도메인 컨트롤러에 해당하며 그룹 정책을 사용하여 적용할 수 있는 보안 기본 구성에 대해 설명합니다. 이 모듈에서는 보안 템플릿에 정의된 설정 외에 적용해야 하는 추가 보안 구성 설정도 다룹니다. 이 추가 설정은 완전하게 강화된 도메인 컨트롤러를 만드는 데 필요합니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection122121120120"></span>
목표
----

이 모듈을 사용하여 다음을 할 수 있습니다.
-   

    Windows Server 2003 기반 도메인 컨트롤러를 강화합니다.

-   

    보안 도메인 컨트롤러에 사용되는 적절한 보안 템플릿 설정을 확인합니다.

[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection123121120120"></span>
적용 범위
---------

이 모듈은 다음과 같은 제품 및 기술에 적용됩니다.
-   

    Windows Server 2003

[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection124121120120"></span>
모듈 사용법
-----------

이 모듈을 사용하여 Windows Server 2003 기반 도메인 컨트롤러에 적용해야 하는 보안 설정을 이해할 수 있습니다. 이 모듈은 Windows 2003 보안 소개 도메인 컨트롤러 보안 템플릿에서 적용하는 보안 템플릿 설정에 관해 자세히 다루기 때문에 이 모듈을 사용하여 가능한 보안 구성을 확인할 수 있습니다. 모듈에는 각 설정에 대한 설명과 함께 도메인 및 서버 환경에 미치는 영향이 포함되어 있습니다.

이 모듈을 최대한 활용하려면 다음을 수행합니다.
-   

    **모듈** "**Windows 2003 보안 소개**"를 참고하십시오. 여기에서는 Windows 2003 보안 소개의 목적과 내용을 설명합니다.

-   

    **모듈** "**Windows Server 2003 환경에서 도메인 인프라 구성**"을 참고하십시오. 여기에서는 보안 도메인 인프라를 설계 및 구현하는 방법을 제시합니다.

[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection125121120120"></span>
개요
----

도메인 컨트롤러 서버 역할은 Microsoft Active Directory 디렉터리 서비스를 사용하는 Windows Server 2003 실행 컴퓨터가 있는 환경을 보호하는 가장 중요한 역할 중 하나입니다. 환경에 있는 도메인 컨트롤러가 손실되거나 손상되면 인증, 그룹 정책 및 중앙의 LDAP(Lightweight Directory Access Protocol)를 위해 도메인 컨트롤러를 사용하는 클라이언트, 서버 및 응용 프로그램이 큰 손상을 입을 수 있습니다.

그 중요성으로 인해 도메인 컨트롤러는 항상 자격 있는 관리 담당자만 액세스할 수 있는 실제로 안전한 위치에 보관해야 합니다. 도메인 컨트롤러를 지사와 같이 안전하지 않은 위치에 보관해야 하는 경우 여러 가지 보안 설정을 조정하여 물리적 위협으로부터 가능한 손상을 제한할 수 있습니다.
### 도메인 컨트롤러 기준 정책

이 설명서 뒷부분에서 자세하게 설명하는 다른 서버 역할 정책과 달리 도메인 컨트롤러 서버 역할에 대한 그룹 정책은 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"에 정의된 MSBP(구성원 서버 기준 정책)와 같은 클래스에 저장된 기준 정책입니다. DCBP(도메인 컨트롤러 기준 정책)는 도메인 컨트롤러 OU(조직 구성 단위)에 연결되며 기본 도메인 컨트롤러 정책보다 우선합니다. DCBP에 포함된 설정은 주어진 환경에서 도메인 컨트롤러의 전체 보안을 강화합니다.

대부분의 DCBP는 MSBP의 직접 복사본입니다. DCBP는 MSBP를 기반으로 하기 때문에 DCBP에도 포함된 여러 설정을 완벽하게 이해하려면 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"를 자세히 검토해야 합니다. 이 모듈에서는 MSBP의 설정과 다른 DCBP 설정만 설명합니다.

도메인 컨트롤러 템플릿은 이 설명서에 정의된 세 가지 환경의 보안 요구를 해결하도록 설계되었습니다. 다음 표는 이 설명서에 포함된 도메인 컨트롤러 .inf 파일과 이러한 환경 사이의 관계를 보여 줍니다. 예를 들어, Enterprise Client - Domain Controller.inf 파일은 엔터프라이즈 클라이언트 환경을 위한 보안 템플릿입니다.

**표 1: 도메인 컨트롤러 기준 보안 템플릿**
 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
Legacy Client - Domain Controller.inf</td>
<td style="border:1px solid black;">
Enterprise Client - Domain Controller.inf</td>
<td style="border:1px solid black;">
High Security - Domain Controller.inf</td>
</tr>
</tbody>
</table>
 

**참고:** 잘못 구성된 GPO(그룹 정책 개체)를 도메인 컨트롤러 OU에 연결하면 도메인의 올바른 작동에 심각한 영향을 줄 수 있습니다. 이러한 보안 템플릿을 가져올 때는 주의를 기울이고 GPO를 도메인 컨트롤러 OU에 연결하기 전에 가져온 모든 설정이 올바른지 확인하십시오.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection126121120120"></span>
감사 정책 설정
--------------

도메인 컨트롤러의 감사 정책 설정은 MSBP에 지정된 감사 정책 설정과 동일합니다. 자세한 내용은 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"를 참고하십시오. DCBP의 기준 정책 설정을 사용하면 모든 관련 보안 감사 정보가 도메인 컨트롤러에 기록됩니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection127121120120"></span>
사용자 권한 할당
----------------

DCBP는 도메인 컨트롤러에 대한 여러 가지 사용자 권한 할당을 지정합니다. 기본 설정 이외에 이 설명서에 정의된 세 가지 환경에서는 도메인 컨트롤러의 보안을 강화하기 위해 7가지 다른 사용자 권한이 수정되었습니다.

여기서는 MSBP의 사용자 권한 설정과는 다른, DCBP용으로 지정된 사용자 권한 설정에 대해 자세히 설명합니다. 이 섹션에 지정된 설정에 대한 요약은 [http://go.microsoft.com/fwlink/?LinkId=14846](http://go.microsoft.com/fwlink/?linkid=14846) ![](images/Dd547910.tous(ko-kr,TechNet.10).gif)에서 Windows Server 2003 보안 설명서와 함께 제공되는 Windows Server 2003 Security Guide Settings(Microsoft Excel 통합 문서로 제공)를 참조하십시오.
### 네트워크에서 이 컴퓨터 액세스

**표 2: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
Administrators, Authenticated Users, ENTERPRISE DOMAIN CONTROLLERS, Everyone, Pre-Windows 2000 Compatible Access</td>
<td style="border:1px solid black;">
정의되지 않음</td>
<td style="border:1px solid black;">
정의되지 않음</td>
<td style="border:1px solid black;">
Administrators, Authenticated Users, ENTERPRISE DOMAIN CONTROLLERS</td>
</tr>
</tbody>
</table>
 

**네트워크에서 이 컴퓨터 액세스** 사용자 권한은 네트워크를 통해 컴퓨터에 연결할 수 있는 사용자 및 그룹을 결정합니다. 이 사용자 권한은 SMB(서버 메시지 블록) 기반 프로토콜, NetBIOS(네트워크 기본 입/출력 시스템), CIFS(일반 인터넷 파일 시스템), HTTP(Hypertext Transfer Protocol) 및 COM+(Component Object Model Plus)를 비롯한 여러 네트워크 프로토콜에 필요합니다.

**Everyone** 보안 그룹에 부여된 권한을 Windows Server 2003에서는 더 이상 익명 사용자에게 액세스 권한을 부여하지 않지만 Guest 그룹과 계정에는 **Everyone** 보안 그룹을 통해 여전히 권한을 부여할 수 있습니다. 이런 이유로 고급 보안 환경에서는 도메인에 액세스하는 게스트를 대상으로 하는 공격으로부터 추가적인 보호를 제공하도록 **네트워크에서 이 컴퓨터 액세스** 사용자 권한에서 **Everyone** 보안 그룹을 제거하는 것이 좋습니다.
### 도메인에 워크스테이션 추가

**표 3: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
Authenticated Users</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
</tr>
</tbody>
</table>
 

**도메인에 워크스테이션 추가** 사용자 권한을 사용하면 특정 도메인에 컴퓨터를 추가할 수 있습니다. 이 권한을 적용하려면 해당 도메인의 기본 도메인 컨트롤러 정책의 일부로 사용자에게 할당해야 합니다. 이 권한이 부여된 사용자는 최대 10개의 워크스테이션을 도메인에 추가할 수 있습니다. Active Directory의 컴퓨터 컨테이너 또는 OU에 대한 **컴퓨터 개체 만들기** 사용 권한이 부여된 사용자는 컴퓨터를 도메인에 참가시킬 수도 있습니다. 이 사용 권한이 부여된 사용자는 **도메인에 워크스테이션 추가** 사용자 권한이 할당되었는지 여부에 관계 없이 도메인에 컴퓨터를 무제한적으로 추가할 수 있습니다.

기본적으로 **Authenticated Users** 그룹의 모든 사용자는 Active Directory 도메인에 컴퓨터 계정을 최대 10개까지 추가할 수 있습니다. 이러한 새 컴퓨터 계정은 컴퓨터 컨테이너에 만들어집니다.

Active Directory 도메인에서는 각 컴퓨터 계정이 도메인 리소스를 인증하고 액세스할 수 있는 완전한 보안 사용자가 됩니다. 일부 조직에서는 일관성 있는 조직의 관리와 구축을 위해 Active Directory 환경의 컴퓨터 수를 제한하려고 합니다.

도메인에 워크스테이션을 추가할 수 있도록 사용자를 허용하는 것은 이러한 노력에 방해가 될 수 있습니다. 또한 권한이 없는 도메인 컴퓨터를 추가로 만들 수 있기 때문에 추적하기가 더욱 어려운 작업을 사용자가 수행할 수 있는 방법을 제공하는 것이 되기도 합니다.

이러한 이유로 인해 **도메인에 워크스테이션 추가** 사용자 권한은 이 설명서에서 정의하는 두 가지 환경에서 **Administrators** 그룹에만 부여됩니다.
### 로컬 로그온 허용

**표 4: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
Administrators, Account Operators, Backup Operators, Print Operators 및 Server Operators</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
</tr>
</tbody>
</table>
 

**로컬 로그온 허용** 사용자 권한을 사용하면 컴퓨터에서 대화형 세션을 시작할 수 있습니다. **터미널 서비스를 통한 로그온 허용** 권한이 있으면 이 권한이 없는 사용자도 컴퓨터에서 원격 대화형 세션을 시작할 수 있습니다.

환경에서 도메인 컨트롤러 콘솔에 로그온하는 데 사용할 수 있는 계정을 제한하면 도메인 컨트롤러 파일 시스템과 시스템 서비스에 대한 무단 액세스가 방지됩니다. 도메인 컨트롤러의 콘솔에 로그온할 수 있는 사용자가 시스템을 악용하여 전체 도메인이나 포리스트의 보안을 손상시킬 수 있습니다.

기본적으로 **Account Operators**, **Backup Operators**, **Print Operators** 및 **Server Operators** 그룹에는 도메인 컨트롤러에 로컬로 로그온하는 권한이 부여됩니다. 이러한 그룹의 사용자는 관리 작업을 수행하기 위해 도메인 컨트롤러에 로그온할 필요가 없습니다. 대개 이러한 그룹의 사용자는 다른 워크스테이션에서 자신의 임무를 수행할 수 있습니다. 도메인 컨트롤러에서는 **Administrators** 그룹의 사용자만 유지 관리 작업을 수행해야 합니다.

**Administrators** 그룹에만 이 권한을 부여하면 확실히 신뢰할 수 있는 사용자만 도메인 컨트롤러에 실제 액세스하고 대화형 액세스하도록 제한하므로 보안이 향상됩니다. 이러한 이유로 인해 **로컬 로그온 허용** 사용자 권한은 이 설명서에 정의된 세 가지 환경에서 **Administrators** 그룹에만 부여됩니다.
### 터미널 서비스를 통한 로그온 허용

**표 5: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
정의되지 않음</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
</tr>
</tbody>
</table>
 

**터미널 서비스를 통한 로그온 허용** 사용자 권한을 사용하면 원격 데스크톱 연결을 사용하여 컴퓨터에 로그온할 수 있습니다.

터미널 서비스를 통해 도메인 컨트롤러 콘솔에 로그온하는 데 사용할 수 있는 계정을 제한하면 도메인 컨트롤러 파일 시스템과 시스템 서비스에 대한 무단 액세스가 방지됩니다. 터미널 서비스를 통해 도메인 컨트롤러의 콘솔에 로그온할 수 있는 사용자는 해당 시스템을 이용할 수 있으며 전체 도메인이나 포리스트의 보안을 손상시킬 수 있습니다.

**Administrators** 그룹에만 이 권한을 부여하면 확실히 신뢰할 수 있는 사용자만 도메인 컨트롤러에 대화형 액세스하도록 제한하므로 보안이 향상됩니다. 이러한 이유로 인해 **로컬 로그온 허용** 사용자 권한은 이 설명서에 정의된 세 가지 환경에서 **Administrators** 그룹에만 부여됩니다. 터미널 서비스를 통해 도메인 컨트롤러에 로그온하려면 기본적으로 관리자 권한이 필요하지만 이 사용자 권한을 구성하면 이 제한을 손상시킬 수 있는 부주의하거나 악의적인 작업을 방지할 수 있습니다.

추가 보안 조치로서 DCBP는 기본 **Administrator** 계정이 터미널 서비스를 통해 도메인 컨트롤러에 로그온하는 권한을 거부합니다. 또한 이 설정은 악의적인 사용자가 기본 **Administrator** 계정을 사용하여 도메인 컨트롤러에 원격으로 침입을 시도하지 못하도록 합니다. 이 설정에 대한 자세한 내용은 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"를 참고하십시오.
### 시스템 시간 변경

**표 6: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
Administrators, Server Operators</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
</tr>
</tbody>
</table>
 

**시스템 시간 변경** 사용자 권한을 사용하면 컴퓨터 내부 시계의 시간을 조정할 수 있습니다. 표준 시간대 또는 시스템 시간의 다른 디스플레이 특성을 변경하는 데는 이 권한이 필요하지 않습니다.

동기화된 시스템 시간은 Active Directory 작동에 중요합니다. Kerberos 버전 5 인증 프로토콜에서 사용하는 적절한 Active Directory 복제 및 인증 티켓 생성 프로세스를 사용하려면 모든 환경의 시간을 동기화해야 합니다.

환경에 있는 다른 도메인 컨트롤러의 시스템 시간과 동기화되지 않은 시스템 시간을 사용하여 구성된 도메인 컨트롤러는 도메인 서비스 작동을 방해할 수 있습니다. 관리자만 시스템 시간을 수정할 수 있도록 허용하면 도메인 컨트롤러가 잘못된 시스템 시간을 사용하여 구성될 가능성이 최소화됩니다.

기본적으로 **Server Operators** 그룹에는 도메인 컨트롤러에서 시스템 시간을 수정할 권한이 부여됩니다. 이 그룹의 구성원이 도메인 컨트롤러에서 시스템 시간을 잘못 수정하여 발생할 수 있는 영향 때문에 이 설명서에 정의된 세 가지 환경에서는 이 사용자 권한이 DCBP의 **Administrators** 그룹만 시스템 시간을 변경할 수 있도록 구성됩니다.

Windows 시간 서비스에 대한 자세한 내용은 [http://support.microsoft.com/default.aspx?scid=224799](http://support.microsoft.com/default.aspx?scid=224799%20)에 있는 기술 자료 문서 Q224799, "Windows Time 서비스의 기본 작업" 및 <http://support.microsoft.com/default.aspx?scid=216734>에 있는 기술 자료 문서 Q216734, "Windows 2000에서 권한을 보유한 시간 서버를 구성하는 방법"을 참조하십시오.
### 컴퓨터 및 사용자 계정을 위임용으로 트러스트할 수 있음

**표 7: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
정의되지 않음</td>
<td style="border:1px solid black;">
정의되지 않음</td>
<td style="border:1px solid black;">
관리자</td>
</tr>
</tbody>
</table>
 

**컴퓨터 및 사용자 계정을 위임용으로 트러스트할 수 있음** 사용자 권한을 사용하면 Active Directory에서 사용자나 컴퓨터 개체에 대한 위임용으로 트러스트 설정을 변경할 수 있습니다. 인증의 위임은 다계층 클라이언트/서버 응용 프로그램에서 사용하는 기능입니다. 이 기능을 사용하면 프런트 엔드 서비스가 백 엔드 서비스를 인증하는 데 클라이언트의 자격 증명을 사용할 수 있습니다. 이렇게 하려면 클라이언트와 서버가 모두 위임용으로 트러스트된 계정에서 실행 중이어야 합니다.

이 권한을 잘못 사용하면 권한이 없는 사용자가 네트워크의 다른 사용자를 가장할 수 있게 됩니다. 공격자는 이 권한으로 다른 사용자를 가장하여 네트워크 리소스에 액세스할 수 있으므로 보안 사고 후에 어떤 일이 발생했는지 파악하기가 더욱 어려워질 수 있습니다.

따라서 **컴퓨터 및 사용자 계정을 위임용으로 트러스트할 수 있음** 권한을 도메인 컨트롤러의 **Administrators** 그룹에 할당하는 것이 좋습니다.

**참고:** 기본 도메인 컨트롤러 정책은 Administrators 그룹에 이 권한을 할당하지만 DCBP는 원래 MSBP를 기반으로 하기 때문에 고급 보안 환경에서만 이 권한을 적용합니다. MSBP는 이 권한에 NULL 값을 할당합니다.
### 장치 드라이버 로드 및 언로드

**표 8: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
Administrators, Print Operators</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
</tr>
</tbody>
</table>
 

**장치 드라이버 로드 및 언로드** 사용자 권한은 장치 드라이버를 로드하고 언로드할 수 있는 사용자를 결정합니다. 플러그 앤 플레이 장치를 로드 및 언로드하려면 이 사용자 권한이 필요합니다.

도메인 컨트롤러에 악의적으로 장치 드라이버를 로드하거나 언로드하면 도메인 컨트롤러 작동에 부정적인 영향을 미칠 수 있습니다. 장치 드라이버를 로드 및 언로드할 수 있는 계정을 확실히 신뢰할 수 있는 사용자로만 제한하면 사용자 환경에서 장치 드라이버로 인해 도메인 컨트롤러가 손상될 가능성이 최소화됩니다.

기본적으로 **Print Operators** 그룹에 이 권한이 부여됩니다. 앞에서 설명한 것처럼 도메인 컨트롤러에는 프린터 공유를 만들지 않는 것이 좋습니다. 이렇게 하면 장치 드라이버를 로드 및 언로드할 경우 **Print Operators** 그룹에 해당 권한이 필요하지 않습니다. 따라서 이 설명서에 정의된 세 가지 환경에서는 **Administrators** 그룹에만 이 사용자 권한이 부여됩니다.
### 파일 및 디렉터리 복원

**표 9: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
Administrators, Backup Operators, Server Operators</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
</tr>
</tbody>
</table>
 

**파일 및 디렉터리 복원** 사용자 권한을 사용하면 백업 파일과 디렉터리를 복원할 때 파일과 디렉터리 권한을 사용하지 않고, 유효한 보안 사용자를 개체 소유자로 설정할 수 있습니다.

파일과 디렉터리를 도메인 컨트롤러의 파일 시스템에 복원할 수 있도록 사용자 계정을 설정하면 계정 소유자가 서비스 실행 파일을 쉽게 수정할 수 있습니다. 악의적인 사용자는 이 권한이 제공하는 액세스 권한을 이용하여 도메인 컨트롤러를 쓸모 없게 만들 뿐 아니라 도메인이나 전체 포리스트의 보안을 손상시킬 수 있습니다.

기본적으로 **Server Operators** 및 **Backup Operators** 그룹에 이 권한이 부여됩니다. 이러한 그룹에서 이 사용자 권한을 제거하고 **Administrators** 그룹에만 부여하면 파일 시스템을 부적절하게 수정함으로써 도메인 컨트롤러가 손상될 가능성이 줄어듭니다. 따라서 이 설명서에 정의된 세 가지 환경에서는 **Administrators** 그룹에만 이 사용자 권한이 부여됩니다.
### 시스템 종료

**표 10: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
Administrators, Server Operators, Print Operators, Backup Operators</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
<td style="border:1px solid black;">
관리자</td>
</tr>
</tbody>
</table>
 

**시스템 종료** 사용자 권한을 사용하면 로컬 컴퓨터를 종료할 수 있습니다.

도메인 컨트롤러를 종료할 수 있는 악의적인 사용자는 DoS(서비스 거부) 공격을 쉽게 시작하여 전체 도메인이나 포리스트에 심각한 영향을 미칠 수 있습니다. 또한 이 사용자 권한을 악용하면 서비스를 다시 시작할 때 도메인 컨트롤러의 시스템 계정에 대한 권한 상승 공격을 시작할 수 있습니다. 도메인 컨트롤러에 대한 권한 상승 공격이 성공하면 도메인이나 전체 포리스트의 보안이 손상됩니다.

기본적으로 **Administrators**, **Server Operators**, **Print Operators** 및 **Backup Operators** 그룹에 도메인 컨트롤러를 종료하는 이 권한이 부여됩니다. 보안 환경에서는 이러한 그룹 중 **Administrators**를 제외하면 관리 작업을 수행하는 데 이 권한이 필요하지 않습니다. 이런 이유로 이 설명서에 정의된 세 가지 환경에서는 이 사용자 권한이 **Administrators** 그룹에만 부여됩니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection128121120120"></span>
보안 옵션
---------

도메인 컨트롤러의 보안 옵션 설정 대부분은 MSBP에 지정된 보안 옵션 설정과 동일합니다. 자세한 내용은 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"를 참고하십시오. 다음 섹션에서는 MSBP와 DCBP 사이의 차이점에 대해 설명합니다.
### 네트워크 보안: 다음 암호 변경 시 Lan Manager 해시 값 저장 안 함

**표 11: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >구성원 서버 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
사용 안 함</td>
<td style="border:1px solid black;">
사용 안 함</td>
<td style="border:1px solid black;">
사용</td>
<td style="border:1px solid black;">
사용</td>
</tr>
</tbody>
</table>
 

**네트워크 보안: 다음 암호 변경 시 Lan Manager 해시 값 저장 안 함** 보안 옵션 설정은 암호를 변경할 때 새 암호의 LM(LAN Manager) 해시 값이 저장되는지를 결정합니다. LM 해시는 상대적으로 약하며 암호화되어 더욱 강력한 Windows NT 해시와 비교할 때 공격받기 쉽습니다. 이런 이유로 이 MSBP는 이 설명서에 정의된 세 가지 보안 환경에서 이 설정을 사용합니다.

DCBP는 엔터프라이즈 클라이언트와 고급 보안 환경의 도메인 컨트롤러에서 이 설정을 사용하며 레거시 클라이언트 환경의 도메인 컨트롤러에서는 사용하지 않습니다. 레거시 클라이언트 환경의 도메인 컨트롤러에서 이 설정을 사용한 경우 Windows 98 클라이언트는 해당 암호를 변경한 후에 로그인할 수 없게 됩니다.

**참고:** 이 설정을 사용하는 경우 이전 운영 체제 및 일부 타사 응용 프로그램이 실패할 수도 있습니다. 또한 이 설정을 사용하려면 모든 계정이 해당 암호를 변경해야 합니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection129121120120"></span>
이벤트 로그 설정
----------------

도메인 컨트롤러의 이벤트 로그 설정은 MSBP에 지정된 이벤트 로그 설정과 동일합니다. 자세한 내용은 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"를 참고하십시오. DCBP의 기준 그룹 정책 설정을 사용하면 모든 관련 보안 감사 정보가 디렉터리 서비스 액세스를 포함하여 도메인 컨트롤러에 기록됩니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection130121120120"></span>
시스템 서비스
-------------

모든 Windows Server 2003 도메인 컨트롤러에서 다음 시스템 서비스를 사용해야 합니다. DCBP의 기준 정책 설정을 사용하면 필요한 모든 시스템 서비스가 도메인 컨트롤러에 일관되게 구성됩니다.

여기에서는 MSBP의 시스템 서비스 설정과는 다른, DCBP용으로 지정된 시스템 서비스 설정에 대해 자세히 설명합니다. 이 섹션에 지정된 설정에 대한 요약은 [http://go.microsoft.com/fwlink/?LinkId=14846](http://go.microsoft.com/fwlink/?linkid=14846)에서 Microsoft Excel 통합 문서로 제공되는 Windows Server 2003 Security Guide Settings를 참조하십시오.

**참고:** Windows Server 2003 지원 도구에서 DCDiag.exe 유틸리티를 실행하면 사용자 환경의 도메인 컨트롤러에서 실행할 수 있는 모든 서비스가 확인됩니다. IISADMIN, SMTPSVC 및 TrkSvr을 포함한 도메인 컨트롤러 기준 정책에서 일부 서비스가 사용되지 않기 때문에 DCDiag.exe는 오류를 보고하게 됩니다. 이 정보는 구성 문제를 나타내는 것은 아닙니다.
### Distributed File System

**표 12: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >서비스 이름</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
Dfs</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
</tr>
</tbody>
</table>
 

**Distributed File System(DFS)** 서비스는 서로 다른 파일 공유를 단일 논리 네임스페이스로 통합하는 분산 서비스입니다. 이 서비스는 LAN 또는 WAN에 분산된 논리 볼륨을 관리하며 Active Directory SYSVOL(시스템 볼륨) 공유에 필요합니다. SYSVOL 복제는 DFS의 올바른 작동에 의해 좌우됩니다.

그룹 정책을 사용하여 서비스에 보안을 설정하고 서비스 시작 모드를 설정하면 서버 관리자에게만 액세스 권한이 부여되므로 권한이 없거나 악의적인 사용자는 서비스를 구성하거나 서비스에 대한 작업을 수행하지 못하게 됩니다. 또한 그룹 정책을 사용하면 관리자가 실수로 서비스를 사용하지 못하도록 설정하는 것을 방지할 수 있습니다. 따라서 이 설명서에 정의된 세 가지 환경에서 이 서비스는 DCBP에서 자동으로 시작되도록 구성되어 있습니다.
### DNS Server

**표 13: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >서비스 이름</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
Dns</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
</tr>
</tbody>
</table>
 

**DNS Server** 서비스는 DNS 이름에 대한 DNS(Domain Name System) 쿼리와 업데이트 요청을 확인합니다. **DNS Server**는 Active Directory에서 DNS 이름과 도메인 컨트롤러를 사용하여 식별되는 장치를 찾는 중요한 서비스입니다.

Active Directory의 안정성과 가용성은 **DNS Server** 서비스의 올바른 작동에 의해 크게 좌우됩니다. DNS가 없으면 도메인 컨트롤러는 디렉터리 정보를 복제하기 위해 서로를 찾을 수 없으며, 클라이언트는 도메인 컨트롤러에 인증을 요청할 수 없습니다.

그룹 정책을 사용하여 서비스에 보안을 설정하고 서비스 시작 모드를 설정하면 서버 관리자에게만 액세스 권한이 부여되므로 권한이 없거나 악의적인 사용자는 서비스를 구성하거나 서비스에 대한 작업을 수행하지 못하게 됩니다. 또한 그룹 정책을 사용하면 관리자가 실수로 서비스를 사용하지 못하도록 설정하는 것을 방지할 수 있습니다. 따라서 이 설명서에 정의된 세 가지 환경에서 이 서비스는 DCBP에서 자동으로 시작되도록 구성되어 있습니다.
### File Replication

**표 14: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >서비스 이름</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
NtFrs</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
</tr>
</tbody>
</table>
 

**File Replacation** 서비스를 사용하면 파일이 자동으로 복사되고 여러 서버에서 동시에 유지 관리됩니다. File Replication Service(FRS)는 Windows 2000 및 Windows Server™ 제품군의 자동 파일 복제 서비스입니다. 이 서비스는 모든 도메인 컨트롤러의 SYSVOL을 복제하며, 내결함성이 있는 DFS와 관련된 다른 대상에 파일을 복제하도록 구성할 수 있습니다. SYSVOL 복제도 **File Replication** 서비스의 올바른 작동에 의해 좌우됩니다.

그룹 정책을 사용하여 서비스에 보안을 설정하고 서비스 시작 모드를 설정하면 서버 관리자에게만 액세스 권한이 부여되므로 권한이 없거나 악의적인 사용자는 서비스를 구성하거나 서비스에 대한 작업을 수행하지 못하게 됩니다. 또한 그룹 정책을 사용하면 관리자가 실수로 서비스를 사용하지 못하도록 설정하는 것을 방지할 수 있습니다. 따라서 이 설명서에 정의된 세 가지 환경에서 이 서비스는 DCBP에서 자동으로 시작되도록 구성되어 있습니다.
### Intersite Messaging

**표 15: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >서비스 이름</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
IsmServ</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
</tr>
</tbody>
</table>
 

**Intersite Messaging**(ISM) 서비스를 사용하면 Windows Server 사이트를 실행하는 컴퓨터 간에 메시지를 교환할 수 있습니다. 이 서비스는 사이트 간의 메일 기반 복제에 사용됩니다. Active Directory는 IP(Internet Protocol) 전송을 통해 SMTP(Simple Mail Transfer Protocol)를 사용하는 사이트 간 복제를 지원합니다. Microsoft IIS(Internet Information Services)의 구성 요소인 SMTP 서비스가 SMTP 지원을 제공합니다.

사이트 간 통신에 사용되는 전송 집합은 확장 가능해야 합니다. 따라서 각 전송은 별도의 추가 기능 DLL(동적 연결 라이브러리)에 정의됩니다. 이러한 추가 기능 DLL은 사이트 간 통신을 수행할 수 있는 모든 도메인 컨트롤러에서 실행되는 ISM 서비스로 로드됩니다. ISM 서비스는 적절한 전송 추가 기능 DLL에 보내기와 받기 메시지 요청을 보낸 다음 메시지를 대상 컴퓨터의 ISM 서비스로 라우트합니다. Active Directory 복제는 **Intersite Messaging** 서비스의 올바른 실행에 의해 좌우됩니다.

그룹 정책을 사용하여 서비스에 보안을 설정하고 서비스 시작 모드를 설정하면 서버 관리자에게만 액세스 권한이 부여되므로 권한이 없거나 악의적인 사용자는 서비스를 구성하거나 서비스에 대한 작업을 수행하지 못하게 됩니다. 또한 그룹 정책을 사용하면 관리자가 실수로 서비스를 사용하지 못하도록 설정하는 것을 방지할 수 있습니다. 따라서 이 설명서에 정의된 세 가지 환경에서 이 서비스는 DCBP에서 자동으로 시작되도록 구성되어 있습니다.
### Kerberos Key Distribution Center

**표 16: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >서비스 이름</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
Kdc</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
</tr>
</tbody>
</table>
 

**Kerberos Key Distribution Center**(KDC) 서비스를 사용하면 Kerberos v5 인증 프로토콜을 사용하여 네트워크에 로그온할 수 있습니다.

사용자가 네트워크에 로그온하려면 KDC 서비스가 필요합니다. 이 서비스를 사용하지 않으면 사용자가 네트워크에 로그온하지 못하도록 차단됩니다.

그룹 정책을 사용하여 서비스에 보안을 설정하고 서비스 시작 모드를 설정하면 서버 관리자에게만 액세스 권한이 부여되므로 권한이 없거나 악의적인 사용자는 서비스를 구성하거나 서비스에 대한 작업을 수행하지 못하게 됩니다. 또한 그룹 정책을 사용하면 관리자가 실수로 서비스를 사용하지 못하도록 설정하는 것을 방지할 수 있습니다. 따라서 이 설명서에 정의된 세 가지 환경에서 이 서비스는 DCBP에서 자동으로 시작되도록 구성되어 있습니다.
### Remote Procedure Call(RPC) Locator

**표 17: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >서비스 이름</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
RpcLocator</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
</tr>
</tbody>
</table>
 

**Remote Procedure Call(RPC) Locator** 서비스를 사용하면 RpcNs\* 제품군 API(응용 프로그래밍 인터페이스)를 사용하는 RPC 클라이언트가 RPC 서버를 찾고 RPC 이름 서비스 데이터베이스를 관리할 수 있습니다.

이 서비스를 중지하거나 사용하지 않으면 RpcNs\* API를 사용하는 RPC 클라이언트가 서버를 찾지 못하거나 시작하지 못할 수 있습니다. 또한, 같은 컴퓨터의 RpcNs\* API를 사용하는 RPC 클라이언트가 해당 인터페이스를 지원하는 RPC 서버를 찾지 못할 수 있습니다. 도메인 컨트롤러에서 이 서비스를 중지하거나 사용하지 않으면 RpcNs\* API를 사용하는 RPC 클라이언트 및 도메인 컨트롤러의 서비스가 클라이언트를 찾으려고 시도할 때 서비스가 중단될 수 있습니다.

그룹 정책을 사용하여 서비스에 보안을 설정하고 서비스 시작 모드를 설정하면 서버 관리자에게만 액세스 권한이 부여되므로 권한이 없거나 악의적인 사용자는 서비스를 구성하거나 서비스에 대한 작업을 수행하지 못하게 됩니다. 또한 그룹 정책을 사용하면 관리자가 실수로 서비스를 사용하지 못하도록 설정하는 것을 방지할 수 있습니다. 따라서 이 설명서에 정의된 세 가지 환경에서 이 서비스는 DCBP에서 자동으로 시작되도록 구성되어 있습니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection131121120120"></span>
추가 보안 설정
--------------

이 섹션에서는 DCBP에서 수행해야 하는 수동 수정은 물론 그룹 정책을 통해 구현할 수 없는 추가 설정 및 대책에 대해 설명합니다.
### 사용자 권한 할당에 수동으로 고유 보안 그룹 추가

DCBP를 통해 적용되는 대부분의 사용자 권한 할당은 [http://go.microsoft.com/fwlink/?LinkId=14846](http://go.microsoft.com/fwlink/?linkid=14846) ![](images/Dd547910.tous(ko-kr,TechNet.10).gif)에 있는 Windows Server 2003 Security Guide의 일부로 제공되는 보안 템플릿에 적절히 지정되었습니다. 그러나 SID(보안 식별자)가 개별 Windows 2003 도메인과 관련이 있기 때문에 템플릿에 포함될 수 없는 몇 가지 계정과 보안 그룹이 있습니다. 수동으로 구성해야 하는 사용자 권한 할당은 다음과 같이 지정됩니다.

**경고:** 다음 표에는 기본 제공 Administrator 계정에 대한 값이 들어 있습니다. 이 계정을 기본 제공 Administrators 보안 그룹과 혼동하면 안됩니다. Administrators 보안 그룹을 아래의 액세스 거부 사용자 권한에 실수로 추가한 경우 이를 수정하려면 로컬로 로그온해야 합니다.

또한 기본 제공 Administrator 계정 이름이 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"에서 설명하는 몇 가지 권장 사항을 바탕으로 변경되었을 수 있습니다. Administrator 계정을 추가할 때는 이름이 변경된 계정을 지정했는지 확인하십시오.

**표 18: 수동으로 추가된 사용자 권한 할당**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
네트워크에서 이 컴퓨터 액세스 거부</td>
<td style="border:1px solid black;">
기본 제공 Administrator; Support_388945a0;Guest; 모든 비 운영 체제 서비스 계정</td>
<td style="border:1px solid black;">
기본 제공 Administrator; Support_388945a0;Guest; 모든 비 운영 체제 서비스 계정</td>
<td style="border:1px solid black;">
기본 제공 Administrator; Support_388945a0;Guest; 모든 비 운영 체제 서비스 계정</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
일괄 작업으로 로그온 거부</td>
<td style="border:1px solid black;">
Support_388945a0 및 Guest</td>
<td style="border:1px solid black;">
Support_388945a0 및 Guest</td>
<td style="border:1px solid black;">
Support_388945a0 및 Guest</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
터미널 서비스를 통한 로그온 거부</td>
<td style="border:1px solid black;">
기본 제공 Administrator; 모든 비 운영 체제 서비스 계정</td>
<td style="border:1px solid black;">
기본 제공 Administrator; 모든 비 운영 체제 서비스 계정</td>
<td style="border:1px solid black;">
기본 제공 Administrator; 모든 비 운영 체제 서비스 계정</td>
</tr>
</tbody>
</table>
 

**중요:** 모든 비 운영 체제 서비스 계정에는 엔터프라이즈 전체에서 특정 응용 프로그램에 사용되는 서비스 계정이 포함됩니다. 운영 체제에서 사용하는 기본 제공 계정인 LOCAL SYSTEM, LOCAL SERVICE 또는 NETWORK SERVICE 계정은 여기에 포함되지 않습니다.
### 디렉터리 서비스

Windows Server 2003을 실행하는 도메인 컨트롤러는 디렉터리 데이터를 저장하고 사용자 로그온 프로세스, 인증, 디렉터리 검색 같은 사용자와 도메인 상호 작용을 관리합니다.
#### 데이터 재배치 - Active Directory 데이터베이스 및 로그 파일

디렉터리 무결성과 안정성을 유지하려면 Active Directory 데이터베이스와 로그 파일을 보호하는 것이 중요합니다.

ntds.dit, edb.log 및 temp.edb 파일을 기본 위치에서 이동하면 도메인 컨트롤러가 손상되는 경우 공격자로부터 이러한 파일을 숨길 수 있습니다. 또한 시스템 볼륨의 파일을 별도의 실제 디스크로 이동하면 도메인 컨트롤러 성능도 개선됩니다.

이러한 이유로 이 설명서에 정의된 세 가지 환경에서는 도메인 컨트롤러의 Active Directory 데이터베이스와 로그 파일을 시스템 볼륨의 기본 위치에서 비 시스템 스트라이프 또는 스트라이프/미러 디스크 볼륨으로 이동하는 것이 좋습니다.
#### Active Directory 로그 파일 크기 조정

Active Directory의 무결성, 안정성 및 가용성을 효과적으로 모니터링하고 관리하려면 환경에서 도메인 컨트롤러에 대해 적당량의 정보가 기록되고 유지되도록 하는 것이 중요합니다.

이를 위해 로그 파일의 최대 크기를 늘리면 해커의 공격이 발생한 경우 관리자는 의미 있는 감사를 수행하는 데 필요한 적당량의 정보를 유지 관리할 수 있게 됩니다.

이런 이유로 이 설명서에 정의된 세 가지 환경에서는 도메인 컨트롤러의 디렉터리 서비스 및 파일 복제 서비스 로그 파일의 최대 크기를 기본값인 512KB에서 16MB로 늘리는 것이 좋습니다.
#### Syskey 사용

도메인 컨트롤러에서는 암호 정보가 디렉터리 서비스에 저장됩니다. 암호를 알아내는 소프트웨어가 사용자 계정 암호에 액세스하기 위해 SAM(보안 계정 관리자) 데이터베이스나 디렉터리 서비스를 대상으로 하는 것이 일반적입니다.

시스템 키 유틸리티(Syskey)는 오프라인으로 암호를 알아내는 소프트웨어로부터 방어하는 추가 보안 기능을 제공합니다. Syskey는 강력한 암호화 기술을 사용하여 디렉터리 서비스에 저장된 계정 암호 정보를 보호합니다.

**표 19: Syskey 모드**
 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >시스템 키 옵션</th>
<th style="border:1px solid black;" >보안 수준</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
<strong>모드 1</strong>: 시스템 생성 암호, 시작 키를 로컬에 저장</td>
<td style="border:1px solid black;">
안전</td>
<td style="border:1px solid black;">
컴퓨터에서 생성한 임의 키를 시스템 키로 사용하고 암호화된 버전의 키를 로컬 컴퓨터에 저장합니다. 이 옵션은 레지스트리에 있는 암호 정보의 강력한 암호화를 제공하며 관리자는 사용자가 암호를 입력하거나 디스크를 삽입할 필요 없이 컴퓨터를 다시 시작하도록 할 수 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
<strong>모드 2</strong>: 관리자 생성 암호, 시작 암호</td>
<td style="border:1px solid black;">
보다 안전</td>
<td style="border:1px solid black;">
컴퓨터에서 생성한 임의 키를 시스템 키로 사용하고 암호화된 버전의 키를 로컬 컴퓨터에 저장합니다. 키는 관리자가 선택한 암호로도 보호됩니다. 컴퓨터의 초기 시작 시퀀스에서 시스템 키 암호를 입력하라는 메시지가 사용자에게 표시됩니다. 시스템 키 암호는 컴퓨터의 어느 위치에나 저장되지 않습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
<strong>모드 3</strong>: 시스템 생성 암호, 시작 키를 플로피 디스크에 저장</td>
<td style="border:1px solid black;">
가장 안전</td>
<td style="border:1px solid black;">
컴퓨터에서 생성한 임의 키를 사용하고 키를 플로피 디스크에 저장합니다. 시스템을 시작하려면 시스템 키가 들어 있는 플로피 디스크가 필요하며 시작 시퀀스 동안 프롬프트가 나타날 때 삽입해야 합니다. 시스템 키는 컴퓨터의 어느 위치에나 저장되지 않습니다.</td>
</tr>
</tbody>
</table>
 

Syskey는 모드 1(난독 처리된(obfuscated) 키)의 모든 Windows Server 2003 서버에서 사용됩니다. 실제 보안 위협에 노출된 모든 도메인 컨트롤러의 경우 모드 2(콘솔 암호) 또는 모드 3(Syskey 암호를 플로피에 저장)에서 Syskey 사용을 권장하는 여러 가지 이유가 있습니다.

보안의 관점에서 공격자가 실제 액세스 권한을 사용하여 도메인 컨트롤러를 다시 시작하는 취약점이 있기 때문에 처음에는 이것이 적당해 보일 수 있습니다. 모드 1에서 Syskey를 사용하면 공격자는 디렉터리 내용을 읽고 변경할 수 있습니다.

그러나, 다시 시작하여 도메인 컨트롤러를 사용할 수 있도록 하는 작동 요구 사항은 Syskey 모드 2나 3을 지원하기 어렵게 만드는 경향이 있습니다. 이러한 Syskey 모드가 제공하는 추가 보호 기능을 이용하려면 도메인 컨트롤러의 특정 가용성 요구 사항을 충족시키도록 사용자 환경에서 적절한 작동 프로세스를 구현해야 합니다.

Syskey 암호의 배치나 플로피 디스크 관리는 특히 지사에서는 매우 복잡할 수 있습니다. 예를 들어, 다른 사용자가 시스템에 액세스할 수 있도록 지사 관리자나 로컬 관리 직원 중 한 명이 오전 3시에 사무실에 와서 암호를 입력하거나 플로피를 삽입하도록 하는 것은 비용이 많이 들고 높은 사용 가능성 SLA(Service Level Agreement)를 달성하기 매우 어렵게 만들 수 있습니다.

또한 중앙의 IT 운영 직원이 Syskey 암호를 원격으로 제공하도록 하려면 추가 하드웨어가 필요합니다. 일부 하드웨어 공급업체는 서버 콘솔에 원격으로 액세스할 수 있는 추가 솔루션을 갖추고 있습니다.

마지막으로, Syskey 암호를 잊거나 플로피 디스크가 손실되면 도메인 컨트롤러를 다시 시작할 수 없는 상태에 이르게 됩니다. Syskey 암호를 잊거나 플로피 디스크를 손실한 경우 도메인 컨트롤러를 복구할 방법이 없습니다. 이런 일이 발생하면 도메인 컨트롤러를 다시 구축해야 합니다.

그러나 적절한 작동 절차를 갖추고 있으면 Syskey는 도메인 컨트롤러에 있는 민감한 디렉터리 정보를 보호할 수 있는 향상된 보안 수준을 제공할 수 있습니다.

이런 이유로 강력한 실제 저장소 보안이 없는 위치의 도메인 컨트롤러에는 Syskey 모드 2 또는 모드 3을 사용하는 것이 좋습니다. 이 권장 사항은 이 설명서에 정의된 세 가지 환경에 있는 도메인 컨트롤러에도 적용됩니다.
-   

    **시스템 키를 만들거나 업데이트하려면:**

    1.  

        **시작**을 클릭하고 **실행**을 클릭하고 **syskey**를 입력한 후 **확인**을 클릭합니다.

    2.  

        **암호화 사용**을 클릭하고 **업데이트**를 클릭합니다.

    3.  

        원하는 옵션을 클릭하고 **확인**을 클릭합니다.

### Active Directory 통합 DNS

영역을 Active Directory에 통합하면 DNS 인프라를 보호하는 프로세스가 간단해지므로 이 설명서에 정의된 세 가지 환경에서는 Active Directory 통합 DNS를 사용하는 것이 좋습니다.
#### DNS 서버 보호

Active Directory가 있는 환경에서는 DNS 서버를 보호하는 것이 중요합니다. 다음 섹션에서는 이러한 작업을 수행하는 여러 가지 권장 사항과 설명을 제공합니다.

DNS 서버가 공격을 받을 때 공격자의 가능한 한 가지 목표는 DNS 클라이언트 쿼리에 응답하여 반환되는 DNS 정보를 제어하는 것입니다. 이런 방법을 통해 고의로 클라이언트를 승인받지 않은 컴퓨터로 보낼 수 있습니다. IP 스푸핑과 캐시 포이즈닝은 이런 종류의 공격 예입니다.

IP 스푸핑에서는 액세스 권한을 얻으려는 승인받지 않은 사용자의 IP 주소가 컴퓨터나 네트워크로 전송됩니다. 캐시 포이즈닝은 승인받지 않은 호스트가 다른 호스트에 관한 잘못된 정보를 DNS 서버의 캐시로 전송하는 공격입니다. 공격으로 인해 클라이언트는 승인받지 않은 컴퓨터로 리디렉션됩니다.

클라이언트가 승인받지 않은 컴퓨터와 실수로 통신하게 되면 이러한 컴퓨터는 클라이언트 컴퓨터에 저장된 정보에 대한 액세스 권한을 얻으려고 시도할 수 있습니다.

모든 공격이 DNS 서버에 스푸핑을 집중하는 것은 아닙니다. 일부 DoS 공격은 합법적인 DNS 서버에 있는 DNS 레코드를 변경하여 클라이언트 쿼리에 응답하여 잘못된 주소를 제공할 수 있습니다. 서버가 잘못된 주소를 응답하도록 함으로써 클라이언트와 서버는 도메인 컨트롤러, 웹 서버 또는 파일 공유 같은 기능에 필요한 리소스를 찾을 수 없습니다.

이런 이유로 이 설명서에 지정된 세 가지 환경에서는 사용되는 라우터가 위장된 IP 패킷을 제거하여 다른 컴퓨터가 DNS 서버의 IP 주소를 위장할 수 없도록 구성하는 것이 좋습니다.
#### 보안 동적 업데이트 구성

Windows Server 2003 DNS 클라이언트 서비스는 클라이언트 시스템이 DNS 레코드를 직접 데이터베이스에 추가할 수 있는 동적 DNS 업데이트를 지원합니다. 동적 DNS 서버는 안전하지 않은 업데이트를 받아들이도록 서버가 구성된 경우 DDNS 프로토콜을 지원하는 클라이언트를 사용하여 공격자로부터 악의적이거나 승인받지 않은 업데이트를 받을 수 있습니다.

최소한 공격자는 위조 항목을 DNS 데이터베이스에 추가할 수 있으며, 최악의 경우 공격자는 DNS 데이터베이스에 있는 합법적인 항목을 덮어쓰거나 삭제할 수 있습니다. 이러한 공격으로 인해 다음과 같은 조건이 발생할 수 있습니다.
-   

    클라이언트를 승인받지 않은 도메인 컨트롤러로 전송: 클라이언트가 도메인 컨트롤러의 주소를 찾는 DNS 쿼리를 제출하면 손상된 DNS 서버는 승인받지 않은 서버의 주소를 반환하도록 지시할 수 있습니다. 그런 다음 다른 비 DNS 관련 공격을 사용하여 클라이언트에 대해 안전한 정보를 위조 서버로 전달하는 속임수를 쓸 수 있습니다.

-   

    DNS 쿼리에 잘못된 주소를 응답: 이렇게 하면 클라이언트와 서버가 서로를 찾을 수 없습니다. 클라이언트가 서버를 찾을 수 없으면 디렉터리에 액세스할 수 없습니다. 도메인 컨트롤러가 다른 도메인 컨트롤러를 찾을 수 없으면 디렉터리 복제가 중지되고 포리스트 전체의 사용자에게 영향을 미칠 수 있는 DoS 조건이 생성됩니다.

-   

    상당한 파일 영역이 더미 레코드 또는 많은 수의 항목으로 채워짐으로써 서버의 디스크 공간이 고갈되어 복제 속도가 느려질 수 있는 DoS 조건이 생성

안전한 DDNS 업데이트를 사용하면 Active Directory 포리스트의 유효한 클라이언트에서 보낸 등록 요청만 처리됩니다. 이렇게 하면 공격자가 DNS 서버의 무결성을 손상시킬 기회가 크게 제한됩니다.

이런 이유로 이 설명서에 정의된 세 가지 환경에서는 보안 동적 업데이트만 받아들이도록 Active Directory DNS 서버를 구성하는 것이 좋습니다.
#### 권한 있는 시스템에 영역을 전송하도록 제한

DNS에서 영역이 수행하는 중요한 역할 때문에 이름 쿼리를 확인할 때 적절한 가용성과 내결함성을 제공하도록 네트워크에 있는 둘 이상의 DNS 서버에서 영역을 사용할 수 있어야 합니다. 그렇지 않으면, 영역에서 응답하지 않는 한 서버에만 보낸 이름 쿼리는 확인하지 못할 수 있습니다. 영역을 호스팅하는 추가 서버가 있을 경우 영역 서버를 호스팅하도록 구성된 각 서버에서 사용하는 영역의 모든 복사본을 복제하고 동기화하기 위해 영역을 전송해야 합니다.

또한, 영역 전송을 요청할 수 있는 사용자를 제한하도록 구성되지 않은 DNS 서버는 영역을 요청하는 모든 사람에게 전체 DNS 영역을 전송하는 취약점이 있습니다. 이것은 nslookup.exe 같은 도구를 사용하여 쉽게 수행할 수 있습니다. 이 도구는 호스트가 도메인 컨트롤러, 디렉터리(통합 웹 서버) 또는 Microsoft SQL Server™ 2000 데이터베이스의 역할을 하는 DNS를 비롯하여 전체 도메인의 DNS 데이터 집합을 노출할 수 있습니다.

이런 이유로 이 설명서에 정의된 세 가지 환경에서는 전송 요청을 할 수 있는 시스템을 제한하도록 Active Directory 통합 DNS 서버를 구성하는 것이 좋습니다.
#### 이벤트 로그 및 DNS 서비스 로그 크기 조정

DNS 서비스를 효과적으로 모니터링하려면 환경 내의 도메인 컨트롤러에 대해 적절한 양의 정보를 기록하고 관리하도록 하는 것이 중요합니다.

DNS 서비스 로그 파일의 최대 크기를 늘리면 공격이 발생한 경우 관리자는 의미 있는 감사를 수행하기에 적절한 양의 정보를 유지 관리할 수 있게 됩니다.

이런 이유로 이 설명서에 정의된 세 가지 환경에서는 도메인 컨트롤러의 DNS 서비스 로그 파일의 최대 크기를 최소 16MB로 구성하는 것이 좋으며 DNS 서비스에서 **필요한 경우 이벤트 덮어쓰기** 옵션을 선택하여 제공되는 로그 항목의 양을 최대화하도록 하십시오.
### 잘 알려진 계정의 보안

Windows Server 2003에는 삭제할 수 없지만 이름을 변경할 수는 있는 기본 제공 사용자 계정이 여러 개 포함되어 있습니다. Windows 2003에서 가장 잘 알려진 기본 제공 계정 중 두 가지가 **Guest** 및 **Administrator**입니다.

기본적으로 구성원 서버와 도메인 컨트롤러에서는 **Guest** 계정이 사용되지 않습니다. 이 설정은 변경하면 안 됩니다. 공격자가 잘 알려진 계정을 사용하여 원격 서버를 손상시키지 못하도록 하려면 기본 제공 **Administrator** 계정의 이름과 설명을 변경해야 합니다.

변형된 대부분의 악성 코드는 서버를 손상시키려는 초기 시도에서 기본 제공 Administrator 계정을 사용합니다. 기본 제공 Administrator 계정의 SID를 지정하여 해당 계정의 이름을 확인함으로써 서버 침입을 시도하는 공격 도구가 등장한 이후 지난 몇 년 동안 이 구성 변경 값은 감소했습니다. SID는 네트워크의 각 사용자, 그룹, 컴퓨터 계정 및 로그온 세션을 고유하게 식별하는 값입니다. 이 기본 제공 계정의 SID는 변경할 수 없습니다. 로컬 관리자 계정의 이름을 고유한 이름으로 바꾸면 작업 그룹에서 이 계정에 대해 시도된 공격을 모니터링하기가 쉬워집니다.

도메인 및 서버의 잘 알려진 계정에 보안을 설정하려면 다음 단계를 수행하십시오.
1.  

    모든 도메인과 서버에서 **Administrator** 및 **Guest** 계정 이름을 변경하고 해당 암호를 길고 복잡한 값으로 변경하십시오.

2.  

    각 서버에 서로 다른 이름과 암호를 사용합니다. 모든 도메인 및 서버에 사용된 계정 이름과 암호가 동일하면 하나의 구성원 서버에 액세스한 공격자가 계정 이름 및 암호가 같은 다른 모든 서버에도 액세스할 수 있게 됩니다.

3.  

    계정을 쉽게 식별할 수 없도록 계정 설명을 기본값이 아닌 다른 값으로 변경합니다.

4.  

    이러한 변경 내용을 안전한 위치에 기록합니다.

**참고:** 기본 제공 Administrator 계정의 이름은 그룹 정책을 통해 변경할 수 있습니다. 이 설정은 사용자 환경에 대해 고유한 이름을 선택해야 하기 때문에 DCBP에서 구성되지 않았습니다. 계정: Administrator 계정 이름 바꾸기를 사용하면 이 설명서에 정의된 세 가지 환경에서 Administrator 계정의 이름을 바꿀 수 있습니다. 이 설정은 GPO의 보안 옵션 설정에 포함됩니다.
### 서비스 계정 보안

꼭 필요한 경우가 아니면 서비스가 도메인 계정의 보안 컨텍스트에서 실행되도록 구성하지 않습니다. 서버가 물리적으로 손상되면 LSA(로컬 보안 기관) 기밀 정보를 덤프하여 도메인 계정 암호를 알아낼 수 있습니다.
### 터미널 서비스 설정

**표 20: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
클라이언트 연결 암호화 수준 설정</td>
<td style="border:1px solid black;">
고가</td>
<td style="border:1px solid black;">
고가</td>
<td style="border:1px solid black;">
고가</td>
</tr>
</tbody>
</table>
 

**클라이언트 연결 암호화 수준** 설정은 사용자 환경에서 터미널 서비스 클라이언트 연결의 암호화 수준을 결정합니다. 128비트 암호화를 사용하는 **높은 수준** 설정 옵션은 공격자가 패킷 분석기를 사용하여 터미널 서비스 세션을 도청하지 못하도록 합니다. 이전 버전의 터미널 서비스 클라이언트에서는 이 고급 수준의 암호화를 지원하지 않는 경우도 있습니다. 네트워크에 이러한 클라이언트가 포함된 경우에는 해당 클라이언트에서 지원하는 가장 높은 암호화 수준으로 데이터를 보내고 받도록 연결 암호화 수준을 설정합니다. 이런 이유로 이 설명서에 정의된 세 가지 보안 환경에서 **클라이언트 연결 암호화 수준** 설정을 **사용**으로 구성하고 DCBP에서 **높은 수준** 암호화 옵션을 선택하는 것이 좋습니다.

그룹 정책 개체 편집기에서 이 설정을 구성하는 경로는 다음과 같습니다.

Computer Configuration\\Administrative Templates\\Windows Components\\Terminal Services\\Encryption and Security.

사용할 수 있는 암호화 수준은 세 가지가 있습니다.

**표 21: 터미널 서비스 암호화 수준**
 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >암호화 수준</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
높은 수준</td>
<td style="border:1px solid black;">
이 수준은 강력한 128비트 암호화를 사용하여 클라이언트에서 서버로, 서버에서 클라이언트로 보낸 데이터를 암호화합니다. 원격 데스크톱 연결 클라이언트와 같은 128비트 클라이언트만이 포함된 환경에서 터미널 서버를 실행 중인 경우 이 수준을 사용합니다. 이 암호화 수준을 지원하지 않는 클라이언트는 연결할 수 없습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
클라이언트 호환</td>
<td style="border:1px solid black;">
이 수준에서는 클라이언트와 서버 간에 보내지는 데이터를 클라이언트가 지원하는 최대 키 강도에서 암호화합니다. 혼합 또는 레거시 클라이언트가 포함된 환경에서 터미널 서버를 실행 중인 경우 이 수준을 사용합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
낮은 수준</td>
<td style="border:1px solid black;">
이 수준은 56비트 암호화를 사용하여 클라이언트에서 서버로 보낸 데이터를 암호화합니다.<strong>중요:</strong> 서버에서 클라이언트로 보낸 데이터는 암호화하지 않습니다.</td>
</tr>
</tbody>
</table>
 

### 오류 보고

**표 22: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
오류 보고</td>
<td style="border:1px solid black;">
사용 안 함</td>
<td style="border:1px solid black;">
사용 안 함</td>
<td style="border:1px solid black;">
사용 안 함</td>
</tr>
</tbody>
</table>
 

**오류 보고** 서비스를 사용하면 Microsoft가 오류를 추적하고 해결하는 데 도움이 됩니다. 이 서비스에서 운영 체제 오류, Windows 구성 요소 오류 또는 프로그램 오류에 대한 보고서를 생성하도록 구성할 수 있습니다. **오류 보고** 서비스를 사용하면 이러한 오류를 인터넷을 통해 Microsoft에 보고하거나 내부 기업 공유 파일에 보고할 수 있습니다.

이 설정은 Microsoft Windows XP Professional 운영 체제 및 Windows Server 2003에서만 사용할 수 있습니다. 그룹 정책 개체 편집기에서 이 설정을 구성하는 경로는 다음과 같습니다.

Computer Configuration\\Administrative Templates\\System\\Error Reporting

오류 보고에는 중요하거나 기밀인 회사 데이터가 포함될 수 있습니다. 오류 보고와 관련된 Microsoft 개인 정보 보호 정책은 Microsoft에서 이러한 데이터를 올바르지 않게 사용하지 않을 것임을 보장하지만 데이터가 암호화되지 않은 텍스트로 HTTP(Hypertext Transfer Protocol)를 통해 전송되므로 인터넷에서 제3자가 가로채어 볼 수 있습니다. 이런 이유로 이 설명서에 정의된 세 가지 모든 보안 환경에서는 DCBP의 **오류 보고** 설정을 **사용 안 함**으로 구성하는 것이 좋습니다.
### IPSec 필터를 사용한 포트 차단

IPSec(인터넷 프로토콜 보안) 필터를 사용하면 서버에 필요한 보안 수준을 효과적으로 높일 수 있습니다. 이 설명서에 정의된 고급 보안 환경에서는 서버의 공격 허점을 더 줄이기 위해 이 선택적 방법을 사용하는 것이 좋습니다.

IPSec 필터 사용에 대한 자세한 내용은 모듈 "추가 구성원 서버 강화 절차"를 참고하십시오.

다음 표는 이 설명서에 정의된 고급 보안 환경에서 도메인 컨트롤러에 만들 수 있는 모든 IPSec 필터를 나열합니다.

다음 표는 이 설명서에 정의된 고급 보안 환경에서 도메인 컨트롤러에 만들어야 하는 모든 IPSec 필터를 나열합니다.

**표 23: 도메인 컨트롤러 IPSec 필터 네트워크 트래픽 맵**
 
<table style="border:1px solid black;">
<colgroup>
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >서비스</th>
<th style="border:1px solid black;" >프로토콜</th>
<th style="border:1px solid black;" >원본 포트</th>
<th style="border:1px solid black;" >대상 포트</th>
<th style="border:1px solid black;" >원본 주소</th>
<th style="border:1px solid black;" >대상 주소</th>
<th style="border:1px solid black;" >동작</th>
<th style="border:1px solid black;" >미러링</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
CIFS/SMB 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
445</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
UDP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
445</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
RPC 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
135</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
UDP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
135</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
NetBIOS 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
137</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
UDP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
137</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
UDP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
138</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
139</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
모니터링 클라이언트</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
MOM 서버</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
터미널 서비스 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
3389</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
글로벌 카탈로그 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
3268</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
3269</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
DNS 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
53</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
UDP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
53</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
Kerberos 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
88</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
UDP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
88</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
LDAP 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
389</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
UDP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
389</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
636</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
UDP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
636</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
NTP 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
123</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;">
UDP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
123</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
PredefinedRPC 범위</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
57901-57950</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
DC Comms</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
도메인 컨트롤러</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
DC Comms</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
도메인 컨트롤러 2</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
ICMP</td>
<td style="border:1px solid black;">
ICMP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
모든 인바운드 트래픽</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
차단</td>
<td style="border:1px solid black;">
예</td>
</tr>
</tbody>
</table>
 

위 표에 나열된 모든 규칙은 구현할 때 미러링되어야 합니다. 이렇게 하면 서버로 들어오는 모든 네트워크 트래픽을 원래 서버로 되돌려 보낼 수도 있습니다.

위의 표는 서버에서 해당 역할 관련 기능을 수행하기 위해 열려야 하는 기준 포트를 나타냅니다. 서버가 정적 IP 주소를 갖고 있는 경우에는 이러한 포트로 충분합니다. 추가 기능을 제공하기 위해 추가 포트를 열어야 할 수도 있습니다. 추가 포트를 열면 사용자 환경의 도메인 컨트롤러를 쉽게 관리할 수 있지만 이러한 서버의 보안은 크게 줄어들 수 있습니다

클라이언트 로그온 프로세스를 지원하려면 특히 RPC의 사용을 위한 포트 범위를 지정해야 합니다. 사용자 환경의 RPC 트래픽을 특정 개수의 포트로 제한할 때 선택한 포트 범위는 50,000개 이상의 포트를 포함해야 합니다. 이것은 다음 레지스트리 설정을 통해 구성할 수 있습니다.

HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\RPC\\Internet 키가 아직 없으면 만들어야 합니다.

열 포트 범위를 나타내는 값을 사용하여 HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\RPC\\Internet\\Ports를 REG\_MULTI\_SZ로 만들고 구성해야 합니다. 예를 들어, 값 57901-57950은 RPC 트래픽에 사용하기 위해 50개의 포트를 엽니다.

HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\RPC\\Internet\\PortsInternetAvailable은 Y 값을 사용하여 REG\_SZ로 만들고 구성해야 합니다.

HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\RPC\\Internet\\UseInternetPorts는 Y 값을 사용하여 REG\_SZ로 만들고 구성해야 합니다.

위와 같이 레지스트리를 변경한 후에 서버를 다시 시작해야 합니다.

**참고:** 이러한 변경은 성능에 영향을 미칠 수 있으며 프로덕션에 구현하기 전에 테스트해야 합니다. 열리는 정확한 포트 수는 환경 및 사용하는 서버와 그 기능에 따라 다릅니다. 클라이언트 로그온 시간을 모니터링해야 합니다. 로그온 성능이 저하되면 추가 포트를 열어야 합니다.

위에서 보여 준 것처럼 사용 중인 환경에 MOM(Microsoft Operations Manager)이 구현되어 있는 경우 IPSec 필터가 구현된 서버와 MOM 서버 사이에 모든 네트워크 트래픽이 이동할 수 있어야 합니다. 이는 MOM 서버와 OnePoint 클라이언트(MOM 콘솔에 보고하는 클라이언트 응용 프로그램) 사이에서 많은 양의 상호 작용이 수행되기 때문에 필요합니다. 다른 관리 패키지의 요구 사항은 이와 비슷할 수 있습니다. 훨씬 더 높은 수준의 보안이 필요할 경우 MOM 서버와 IPSec를 협상하도록 OnePoint 클라이언트에 대한 필터 동작을 구성할 수 있습니다.

위의 네트워크 트래픽 맵에서는 사용 환경에 Active Directory를 사용할 수 있는 DNS 서버가 포함되어 있는 것으로 가정합니다. 독립 실행형 DNS 서버가 사용되는 경우에는 추가 규칙이 필요할 수 있습니다.

IPSec 정책을 구현할 때 서버 성능에 중대한 영향을 미쳐서는 안 됩니다. 그러나 이러한 필터를 구현하기 전에 테스트를 수행하여 필요한 서버 기능 및 성능이 유지되는지 확인해야 합니다. 다른 응용 프로그램을 지원하기 위해 규칙을 추가해야 할 수도 있습니다.

**참고:** 도메인 컨트롤러는 매우 동적이며 여기에 IPSec 필터를 구현할 때는 신중하게 검토한 다음 랩 환경에서 철저하게 테스트해야 합니다. 도메인 컨트롤러 간의 많은 양의 상호 작용으로 인해 서로 정보를 복제하는 도메인 컨트롤러 사이에 모든 트래픽을 허용하려면 IPSec 필터를 추가해야 합니다. 많은 도메인 컨트롤러가 있는 복잡한 환경에서 이렇게 하려면 필터가 도메인 컨트롤러를 효과적으로 보호할 수 있도록 여러 개의 추가 필터를 만들어야 합니다. 따라서 IPSec 정책을 구현하고 관리하기가 매우 어려워질 수 있습니다. 그러나 도메인 컨트롤러 수가 적은 환경은 IPSec 필터를 구현함으로써 얻은 장점을 효율적으로 활용할 수 있습니다.

이 설명서에 포함된 .cmd 파일을 사용하면 도메인 컨트롤러에 지정된 IPSec 필터를 쉽게 만들 수 있습니다. PacketFilters-DC.cmd 파일은 NETSH 명령을 사용하여 적절한 필터를 만듭니다. 이 .cmd 파일을 수정하여 사용 환경에 있는 다른 도메인 컨트롤러의 IP 주소를 포함해야 합니다. 이 스크립트에는 두 개의 도메인 컨트롤러를 추가하기 위한 자리 표시자가 포함되어 있습니다. 따라서 필요하면 도메인 컨트롤러를 추가할 수 있습니다. 도메인 컨트롤러에 대한 이 IP 주소 목록은 항상 최신 상태를 유지해야 합니다.

사용 환경에 MOM이 있는 경우에는 스크립트에 해당 MOM 서버의 IP 주소도 지정되어 있어야 합니다. 이 스크립트는 영구 필터를 만들지 않습니다. 따라서 서버는 IPSec 정책 에이전트가 시작되어야만 보호됩니다. 영구 필터를 만들거나 보다 고급의 IPSec 필터 스크립트를 작성하는 방법에 대해서는 모듈 "추가 구성원 서버 강화 절차"를 참고하십시오. 마지막으로, 이 스크립트는 스크립트에서 만드는 IPSec 정책을 할당하지 않도록 구성되어 있습니다. IP 보안 정책 관리 스냅인을 사용하면 만든 IPSec 필터를 검사하고 이 IPSec 필터가 적용되도록 하기 위해 IPSec 정책을 할당할 수 있습니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection132121120120"></span>
요약
----

이 모듈에서는 이 설명서에 정의된 세 가지 환경에서 도메인 컨트롤러를 보호하는 데 필요한 서버 강화 설정에 대해 설명합니다. 여기에서 설명하는 대부분의 설정은 그룹 정책을 사용하여 구성되고 적용됩니다. 기본 도메인 컨트롤러 정책을 보완하도록 설계된 GPO(그룹 정책 개체)는 도메인 컨트롤러 OU(조직 구성 단위)에 연결되어 있습니다. DCBP(도메인 컨트롤러 기준 정책)에 포함된 설정은 주어진 환경에서 도메인 컨트롤러의 전체 보안을 강화합니다. 두 가지 GPO를 사용하여 도메인 컨트롤러를 보호하면 기본 환경을 보존하고 문제를 쉽게 해결할 수 있습니다.

그룹 정책을 통해서는 여러 가지 서버 강화 설정을 적용할 수 없습니다. 이 경우 이러한 설정을 수동으로 구성하는 방법이 자세히 설명되어 있습니다.

도메인 컨트롤러 보안을 강화했으므로 이 설명서의 다음 모듈은 여러 가지 다른 특정 서버 역할 보호를 중점적으로 설명합니다.
### 추가 정보

다음은 이 제품의 출시 당시 Windows Server 2003을 실행하는 컴퓨터가 있는 환경에서 도메인 컨트롤러의 보안과 관련하여 작성된 최신 자료입니다.

Microsoft 시스템 아키텍처: 엔터프라이즈 데이터 센터 규정 아키텍처 가이드에 대한 자세한 내용은 다음 페이지를 참고하십시오. <http://www.microsoft.com/technet/itsolutions/edc/default.asp> ![](images/Dd547910.tous(ko-kr,TechNet.10).gif)

Active Directory에 대한 익명 액세스를 사용하는 방법에 대한 자세한 내용은 다음 위치에서 기술 자료 문서 257988, "Description of Dcpromo Permissions Choices"를 참고하십시오.

<http://support.microsoft.com/default.aspx?scid=257988>

Windows 2000 DNS에 대한 자세한 내용은 다음 위치에서 "Windows 2000 DNS 백서"를 참고하십시오. [http://www.microsoft.com/korea/windows2000/techinfo/howitworks/communications/nameadrmgmt/w2kdns.asp](https://technet.microsoft.com/ko-kr/library//korea/windows2000/techinfo/howitworks/communications/nameadrmgmt/w2kdns.asp(v=TechNet.10))

Windows 2000 DNS에 대한 자세한 내용은 다음 위치에서 "TCP/IP Core Networking Guide"의 온라인 버전 모듈 6을 참고하십시오. <http://www.microsoft.com/windows2000/techinfo/reskit/en-us/default.asp> ![](images/Dd547910.tous(ko-kr,TechNet.10).gif)

Windows 2003 DNS에 대한 자세한 내용은 다음 위치에서 "Changes to DNS in Windows Server 2003"을 참고하십시오. <http://www.microsoft.com/windows2000/technologies/communications/dns/dns2003.asp> ![](images/Dd547910.tous(ko-kr,TechNet.10).gif)

IPSec 필터링에 대한 자세한 내용은 다음 위치에서 "How To: Use IPSec IP Filter Lists in Windows 2000"을 참고하십시오. <http://support.microsoft.com/default.aspx?scid=313190>

Active Directory를 제한하는 방법에 대한 자세한 내용은 <http://support.microsoft.com/default.aspx?scid=224196>에서 "Restricting Active Directory Replication Traffic to a Specific Port"를 참고하십시오.

FRS 복제 트래픽을 제한하는 방법에 대한 자세한 내용은 <http://support.microsoft.com/default.aspx?scid=319553>에서 "How to Restrict FRS Replication Traffic to a Specific Static Port"를 참고하십시오.

Windows 시간 서비스에 대한 자세한 내용은 다음 위치에서 "Windows Time 서비스의 기본 작업"을 참고하십시오. <http://support.microsoft.com/default.aspx?scid=224799>

Windows Time 서비스를 구성하는 방법에 대한 자세한 내용은 다음 위치에서 "Windows 2000에서 권한을 보유한 시간 서버를 구성하는 방법"을 참고하십시오. <http://support.microsoft.com/default.aspx?scid=216734>
[](#mainsection)[페이지 위쪽](#mainsection)
