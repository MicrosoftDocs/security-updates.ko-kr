---
TOCTitle: Windows Server 2003 IIS 서버 강화
Title: Windows Server 2003 IIS 서버 강화
ms:assetid: '6f1179f2-d368-4e99-bdc4-e2c834b73151'
ms:contentKeyID: 20214069
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547914(v=TechNet.10)'
---

Windows Server 2003 IIS 서버 강화
=================================

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

이 모듈에서는 IIS(인터넷 정보 서비스) 서버에 특정한 보안 템플릿의 구성에 대해 설명합니다. 이 모듈에서는 서버에 이미 구성원 서버 기준이 적용된 것으로 가정합니다. 또한 보안 템플릿에 정의된 설정 외에 적용해야 하는 추가 보안 구성 설정도 다룹니다. 이러한 추가 설정은 완전하게 강화된 IIS 서버를 만드는 데 필요합니다.

이 모듈에서는 Microsoft Windows Server™ 2003 운영 체제에 설치된 IIS의 기본 구성에 대해 설명합니다. 또한 IIS 특징과 기능에 대해 설명하고 권장 사용법을 알려 줍니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection122121120120"></span>
목표
----

이 모듈을 사용하여 다음을 할 수 있습니다.
-   

    IIS 서버 강화

-   

    IIS 서버에 대한 적절한 보안 구성 조사

[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection123121120120"></span>
적용 범위
---------

이 모듈은 다음과 같은 제품 및 기술에 적용됩니다.
-   

    Windows Server 2003

-   

    IIS 6.0

[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection124121120120"></span>
모듈 사용법
-----------

이 모듈을 사용하면 Windows Server 2003 IIS 서버에 적용해야 하는 보안 설정에 대해 파악하고 이런 유형의 서버를 강화할 수 있습니다. 이 모듈에서는 역할 관련 보안 템플릿과 기준 보안 템플릿을 함께 사용합니다. 이러한 보안 템플릿은 [http://go.microsoft.com/fwlink/?LinkId=14846](http://go.microsoft.com/fwlink/?linkid=14846) ![](images/Dd547914.tous(ko-kr,TechNet.10).gif)의 Windows Server 2003 보안 설명서에서 제공됩니다.

이 모듈을 최대한 활용하려면 다음을 수행합니다.
-   

    **모듈 "Windows 2003 보안 소개**"를 읽어 보십시오. 여기에서는 Windows Server 2003 보안 설명서의 목적과 내용을 설명합니다.

-   

    **모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기**"를 읽어 보십시오. 여기에서는 조직 구성 단위 계층 구조와 그룹 정책을 사용하여 여러 서버에 구성원 서버 기준을 적용하는 방법을 보여 줍니다.

-   

    **함께 제공된 작업 방법을 사용합니다**. 이 모듈에서 참조하는 다음 사용 안내서를 읽어 보십시오.

    -   

        "Windows Server 2003에서의 IIS 6.0 구성 요소 식별 방법"

[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection125121120120"></span>
개요
----

이 모듈에서는 사용자 환경에서 IIS 서버를 강화하는 데 필요한 지침과 절차에 대해 중점적으로 설명합니다. 조직의 인트라넷에 있는 웹 서버 및 응용 프로그램에 대한 종합적인 보안 기능을 제공하려면, 각각의 Microsoft IIS(인터넷 정보 서비스) 서버를 비롯하여 이러한 서버에서 실행되는 응용 프로그램과 웹 사이트 각각이 연결 가능한 클라이언트 컴퓨터로부터 보호되어야 합니다. 또한 이러한 IIS 서버 각각에서 실행되는 응용 프로그램과 웹 사이트는 회사 인트라넷 내의 다른 IIS 서버에서 실행되는 응용 프로그램과 웹 사이트로부터도 보호되어야 합니다.

악의적인 사용자와 공격자에 대한 더욱 확실한 예방 대책을 취하기 위해 IIS는 Windows Server 2003 제품군의 구성원에 기본적으로 설치되어 있지 않습니다. IIS는 고급 보안 설정인 "잠금" 모드로 처음 설치됩니다. 예를 들어 IIS는 처음에 기본적으로 정적 콘텐트만 제공합니다. ASP(Active Server Pages) 등의 기능과 ASP.NET, SSI(Server Side Includes), WebDAV(Web Distributed Authoring and Versioning) 게시 및 Microsoft FrontPage 서버 익스텐션은 관리자가 사용하도록 설정하기 전에는 작동되지 않습니다. IIS 관리자(인터넷 정보 서비스 관리자)의 웹 서비스 익스텐션 노드를 통해 이러한 기능과 서비스를 사용하도록 설정할 수 있습니다.

IIS 관리자는 IIS를 쉽게 관리할 수 있도록 설계된 GUI(그래픽 사용자 인터페이스)입니다. 또한 보안성, 효율성 및 안정성을 갖추고 있을 뿐 아니라 파일 및 디렉터리 관리 리소스와 응용 프로그램 풀 구성을 제공합니다.

다음 섹션에서는 회사의 인트라넷에서 HTML 콘텐트를 호스팅하는 IIS 서버의 보안성 향상을 위해 구현되어야 하는 다양한 보안 강화 설정에 대해 자세히 설명합니다. IIS 서버의 보안을 유지하기 위해서는 보안 모니터링, 감지 및 응답 절차도 구현되어야 합니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection126121120120"></span>
감사 정책 설정
--------------

본 설명서에 정의된 세 가지 환경에서의 IIS 서버에 대한 감사 정책 설정은 MSBP를 사용해 구성됩니다. MSBP에 대한 자세한 내용은 "Windows Server 2003 서버의 구성원 서버 기준 만들기" 모듈을 참고하십시오. MSBP 설정은 관련된 모든 보안 감사 정보가 모든 IIS 서버에 로그온되도록 합니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection127121120120"></span>
사용자 권한 할당
----------------

본 설명서에 정의된 세 가지 환경에서의 IIS 서버에 대한 사용자 권한 할당은 대부분 MSBP를 사용해 구성됩니다. MSBP에 대한 자세한 내용은 "Windows Server 2003 서버의 구성원 서버 기준 만들기" 모듈을 참고하십시오. 다음 섹션에서는 MSBP와 증분 IIS 그룹 정책 사이의 차이점에 대해 설명합니다.
### 네트워크에서 이 컴퓨터 액세스 거부

**표 1: 설정**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>구성원 서버 기본값</th>
<th>레거시 클라이언트</th>
<th>엔터프라이즈 클라이언트</th>
<th>고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
SUPPORT_388945a0</td>
<td style="border:1px solid black;">
ANONYMOUS LOGON; 기본 제공 Administrator; Support_388945a0;Guest; 모든 비 운영 체제 서비스 계정</td>
<td style="border:1px solid black;">
ANONYMOUS LOGON; 기본 제공 Administrator; Support_388945a0;Guest; 모든 비 운영 체제 서비스 계정</td>
<td style="border:1px solid black;">
ANONYMOUS LOGON; 기본 제공 Administrator; Support_388945a0;Guest; 모든 비 운영 체제 서비스 계정</td>
</tr>
</tbody>
</table>
 

**참고:** ANONYMOUS LOGON, 기본 제공 Administrator, Support\_388945a0, Guest 및 모든 비 운영 체제 서비스 계정은 보안 템플릿에 들어 있지 않습니다. 이러한 계정 및 그룹에는 조직 내 각 영역별로 고유한 SID(보안 식별자)가 부여됩니다. 따라서 수동으로 추가해야 합니다.

**네트워크에서 이 컴퓨터 액세스 거부** 설정은 네트워크를 통해 컴퓨터에 연결할 수 없는 사용자를 결정합니다. 이 설정은 SMB(서버 메시지 블록) 기반 프로토콜, NetBIOS(네트워크 기본 입/출력 시스템), CIFS(일반 인터넷 파일 시스템), HTTP(Hypertext Transfer Protocol) 및 COM+(Component Object Model Plus)를 비롯한 여러 네트워크 프로토콜을 거부합니다. 또한 사용자 계정이 두 가지 정책을 모두 따를 경우에는 **네트워크에서 이 컴퓨터 액세스** 설정이 무시됩니다. 다른 그룹에 대해 이 사용자 권한을 구성하면 사용자들이 현재 환경에서 위임 관리 작업을 수행할 수 있는 기능이 제한될 수 있습니다.

모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"에서는 가능한 한 가장 높은 수준의 보안을 제공하기 위해 이 권한이 할당된 사용자 및 그룹 목록에 **Guests** 그룹을 포함할 것을 권장합니다. 그러나 IIS에 익명으로 액세스하는 데 사용되는 IUSR 계정은 기본적으로 **Guests** 그룹의 구성원입니다. 본 설명서에서는 IIS 서버로의 익명 액세스를 필요에 따라 구성하도록 하기 위해 증분 IIS 그룹 정책에서 **Guests** 그룹을 제거하도록 권장합니다. 이러한 이유로 본 설명서에 정의된 세 가지 환경 모두에서의 IIS 서버에 대해 **ANONOYMOUS LOGON, 기본 제공 Administrator, Support\_388945a0, Guest 및 모든 비 운영 체제 서비스 계정**이 포함되도록 **네트워크에서 이 컴퓨터 액세스 거부** 설정이 구성됩니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection128121120120"></span>
보안 옵션
---------

본 설명서에 정의된 세 가지 환경에서의 IIS 서버에 대한 보안 옵션 설정은 MSBP를 사용해 구성됩니다. MSBP에 대한 자세한 내용은 "Windows Server 2003 서버의 구성원 서버 기준 만들기" 모듈을 참고하십시오. MSBP 설정은 연관된 모든 보안 옵션이 IIS 서버 전체에서 일관되게 구성되도록 합니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection129121120120"></span>
이벤트 로그 설정
----------------

본 설명서에 정의된 세 가지 환경에서의 IIS 서버에 대한 이벤트 로그 설정은 MSBP를 사용해 구성됩니다. MSBP에 대한 자세한 내용은 "Windows Server 2003 서버의 구성원 서버 기준 만들기" 모듈을 참고하십시오. MSBP 설정은 올바른 이벤트 로그 설정이 기업의 모든 IIS 서버에 일관되게 구성되도록 합니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection130121120120"></span>
시스템 서비스
-------------

IIS가 웹 서버 기능을 Windows Server 2003에 추가하려면 다음의 세 가지 서비스가 사용 가능하도록 설정되어야 합니다. 증분 IIS 그룹 정책을 사용하면 이러한 서비스가 자동으로 시작되도록 구성할 수 있습니다.

**참고:** MSBP는 IIS와 연관된 다른 몇몇 서비스를 사용하지 못하도록 설정합니다. FTP, SMTP 및 NNTP 등의 서비스가 MSBP에 의해 사용하지 못하도록 설정됩니다. 본 설명서에 정의된 임의의 세 가지 환경에서의 IIS 서버에 대해 이러한 서비스를 사용하도록 설정된 경우에는 증분 IIS 그룹 정책을 수정해야 합니다.
### HTTP SSL

**표 2: 설정**
 
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
<th>서비스 이름</th>
<th>구성원 서버 기본값</th>
<th>레거시 클라이언트</th>
<th>엔터프라이즈 클라이언트</th>
<th>고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
HTTPFilter</td>
<td style="border:1px solid black;">
수동</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
</tr>
</tbody>
</table>
 

**HTTP SSL** 서비스를 사용하면 IIS가 SSL(Secure Sockets Layer) 기능을 수행할 수 있습니다. SSL은 신용 카드 번호와 같이 중요한 정보의 도난을 방지하기 위해 보안 통신 채널을 구축하는 데 사용되는 개방형 표준입니다. 또한 이 기능은 다른 인터넷 서비스에 대해서도 사용할 수 있도록 설계되었지만 주로 World Wide Web 상의 전자 금융 트랜잭션을 안전하게 보호합니다.

If the HTTP SSL service is stopped, IIS will not perform SSL functions. 이 서비스를 해제하면 이 서비스에 명시적으로 의존하는 모든 서비스가 작동하지 않게 됩니다. 그룹 정책을 사용하여 서비스에 보안을 설정하고 서비스 시작 모드를 설정하면 서버 관리자에게만 액세스 권한이 부여되므로 권한이 없거나 악의적인 사용자는 서비스를 구성하거나 서비스에 대한 작업을 수행하지 못하게 됩니다. 또한 그룹 정책을 사용하면 관리자가 실수로 서비스를 사용하지 못하도록 설정하는 것을 방지할 수 있습니다. 이러한 이유로 **HTTP SSL** 설정은 본 설명서에 정의된 세 가지 환경에서의 IIS 서버에 대해**자동**으로 구성됩니다.
### IIS 관리 서비스

**표 3: 설정**
 
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
<th>서비스 이름</th>
<th>구성원 서버 기본값</th>
<th>레거시 클라이언트</th>
<th>엔터프라이즈 클라이언트</th>
<th>고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
IISADMIN</td>
<td style="border:1px solid black;">
설치되지 않음</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
</tr>
</tbody>
</table>
 

**IIS 관리 서비스**를 사용하면 FTP(File Transfer Protocol), 응응 프로그램 풀, 웹 사이트, 웹 서비스 익스텐션 등의 IIS 구성 요소를 비롯하여 NNTP(Network News Transfer Protocol)와 SMTP(Simple Mail Transport Protocol) 가상 서버 모두를 관리할 수 있습니다.

FTP, NNTP 및 SMTP 등의 웹 서비스를 제공하려면 **IIS 관리 서비스**가 IIS 서버에서 실행되고 있어야 합니다. 이 서비스를 사용할 수 없도록 설정된 경우에는 IIS를 구성할 수 없으며 모든 웹 서비스 요청이 실패합니다. 그룹 정책을 사용하여 서비스에 보안을 설정하고 서비스 시작 모드를 설정하면 서버 관리자에게만 액세스 권한이 부여되므로 권한이 없거나 악의적인 사용자는 서비스를 구성하거나 서비스에 대한 작업을 수행하지 못하게 됩니다. 또한 그룹 정책을 사용하면 관리자가 실수로 서비스를 사용하지 못하도록 설정하는 것을 방지할 수 있습니다. 이러한 이유로 본 설명서에 정의된 세 가지 환경에서의 IIS 서버에 대해 **IIS 관리 서비스** 설정이 **자동**으로 구성됩니다.
### World Wide Web 게시 서비스

**표 4: 설정**
 
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
<th>서비스 이름</th>
<th>구성원 서버 기본값</th>
<th>레거시 클라이언트</th>
<th>엔터프라이즈 클라이언트</th>
<th>고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
W3SVC</td>
<td style="border:1px solid black;">
설치되지 않음</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
<td style="border:1px solid black;">
자동</td>
</tr>
</tbody>
</table>
 

**World Wide Web 게시 서비스**는 IIS 스냅인을 통해 웹 사이트를 관리하고 웹 연결 기능을 제공합니다.

**World Wide Web 게시 서비스**가 IIS 서버에서 실행되어야 IIS 관리자를 통해 관리 기능과 웹 연결 기능을 제공할 수 있습니다. 그룹 정책을 사용하여 서비스에 보안을 설정하고 서비스 시작 모드를 설정하면 서버 관리자에게만 액세스 권한이 부여되므로 권한이 없거나 악의적인 사용자는 서비스를 구성하거나 서비스에 대한 작업을 수행하지 못하게 됩니다. 또한 그룹 정책을 사용하면 관리자가 실수로 서비스를 사용하지 못하도록 설정하는 것을 방지할 수 있습니다. 이러한 이유로 **World Wide Web 게시 서비스** 설정은 본 설명서에 정의된 세 가지 환경에서의 IIS 서버에 대해 **자동**으로 구성됩니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection131121120120"></span>
추가 보안 설정
--------------

Windows Server 2003과 IIS가 설치된 후 IIS는 기본적으로 정적 웹 콘텐트만 전송합니다. 웹 사이트와 응용 프로그램에 동적 콘텐트가 포함되어 있거나 하나 이상의 추가 IIS 구성 요소를 요구한 경우에는 각각의 추가 IIS 기능을 사용하도록 개별적으로 설정해야 합니다. 이러한 프로세스를 처리하는 동안에는 사용자 환경에서 IIS 서버 각각의 공격 허점을 최소화하도록 주의를 기울여야 합니다. 사용자 조직의 웹 사이트가 정적 콘텐트로 구성되어 있고 다른 IIS 구성 요소를 요구하지 않는다면 기본 IIS 구성만으로도 사용자 환경에서 IIS 서버의 공격 허점을 최소화하는 데 충분합니다.

MSBP를 통해 적용된 보안 설정은 IIS 서버에 대한 보안을 상당히 향상시켜 줍니다. 그러나 몇 가지 사항과 프로시저를 더 고려해야 합니다. 이와 같은 단계는 그룹 정책을 통해 완성할 수 없으며 모든 IIS 서버에 수동으로 수행해야 합니다.
### 필요 시에만 IIS 구성 요소 설치

IIS 6.0에는 **World Wide Web 게시 서비스** 이외에 FTP와 SMTP 서비스와 같은 기타 구성 요소와 서비스가 포함됩니다. IIS 구성 요소 및 서비스는 Windows Components Wizard Application Server를 사용하여 설치하고 사용하도록 설정하는데 이 프로그램은 **제어판**의 **프로그램 추가/제거**를 두 번 클릭하여 시작할 수 있습니다. IIS 설치 후 웹 사이트 및 응용 프로그램에서 요구하는 모든 필수 IIS 구성 요소와 서비스는 사용할 수 있도록 설정되어야 합니다.

웹 사이트 및 응용 프로그램에서 요구하는 핵심 IIS 구성 요소와 서비스만 사용할 수 있도록 설정하십시오. 불필요한 구성 요소와 서비스를 사용하도록 설정하면 IIS 서버의 공격 허점만 늘어납니다.

IIS 구성 요소에 대한 권장 설정과 위치에 대해 알아 보려면 "Windows Server 2003에서의 IIS 6.0 구성 요소 식별 방법"을 참고하십시오.
### 핵심 웹 서비스 익스텐션만 사용하도록 설정

IIS 서버에서 실행되는 여러 웹 사이트 및 응용 프로그램에는 동적 콘텐트 작성 기능을 포함하여 정적 페이지를 능가하는 확장된 기능이 있습니다. IIS 서버의 기능을 통해 제공되거나 확장되는 모든 동적 콘텐트는 웹 서비스 익스텐션을 사용하여 수행됩니다.

IIS 6.0의 향상된 보안 기능을 사용하면 개별 웹 서비스 익스텐션을 사용하거나 사용하지 않도록 설정할 수 있습니다. 처음 설치된 후 IIS 서버는 정적 콘텐트만 전송합니다. 동적 콘텐트 기능은 IIS 관리자의 웹 서비스 익스텐션 노드를 통해 사용하도록 설정할 수 있습니다. 이러한 익스텐션에는 ASP.NET, SSI, WebDAV 및 FrontPage 서버 익스텐션이 포함됩니다.

모든 웹 서비스 익스텐션을 사용할 수 있도록 설정하면 기존 응용 프로그램과 가능한 최고의 호환성이 보장되지만 사용자 환경의 IIS 서버에 불필요할 수도 있는 기능도 사용할 수 있게 됨으로써 IIS의 공격 허점이 증가되므로 이에 따른 보안 위험성도 발생합니다.

IIS 서버의 공격 허점을 줄이려면 본 설명서에 정의된 임의의 세 가지 환경에서의 IIS 서버에 대해 가능한 최대로 필요한 웹 서비스 익스텐션만 사용하도록 설정해야 합니다.

사용자 환경의 IIS 서버에서 실행되는 웹 사이트와 응용 프로그램이 요구하는 웹 서비스 익스텐션만 사용하도록 설정하면 서버 기능이 최소화되고 IIS 서버 각각의 공격 허점이 줄어들어 보안이 향상됩니다.

웹 서비스 익스텐션에 대한 설명은 Windows Server 2003에서의 IIS 6.0 구성 요소 식별 방법"을 참고하십시오.
### 전용 디스크 볼륨에 콘텐트 배치

IIS는 기본 웹 사이트의 파일을 &lt;systemroot&gt;\\inetpub\\wwwroot에 저장하는데, 여기서 &lt;systemroot&gt;는 Windows Server 2003 운영 체제가 설치된 드라이브입니다.

웹 사이트와 응용 프로그램을 구성하는 모든 파일과 폴더는 본 설명서에 정의된 세 가지 환경의 IIS 서버에서 전용 디스크 볼륨에 배치하십시오. 이러한 파일과 폴더를 IIS 서버의 전용 디스크 볼륨(운영 체제가 포함되어 있지 않은 볼륨)에 배치하면 디렉터리 순회 공격을 쉽게 방지할 수 있습니다. 디렉터리 순회 공격은 공격자가 IIS 서버의 디렉터리 구조 외부에 있는 파일을 요청할 때 사용됩니다.

예를 들어 cmd.exe가 &lt;systemroot&gt;\\System32 폴더에 있는 경우, 공격자는 명령 프롬프트를 호출하여 다음 위치로 요청할 수 있습니다.

..\\..\\Windows\\system\\cmd.exe

웹 사이트 콘텐트가 별도의 디스크 볼륨에 있다면 이런 유형의 디렉터리 순회 공격은 다음과 같은 두 가지 이유로 실패하게 됩니다. 첫 번째, cmd.exe에 대한 권한이 Windows Server 2003의 기본 구축 과정의 일부로서 재설정되어 그 액세스 권한이 휠씬 더 제한적인 사용자 그룹으로 한정됩니다. 두 번째, 이렇게 변경된 후 cmd.exe는 웹 루트와 같은 디스크 볼륨에 존재하지 않게 되는데 현재로서는 그런 공격을 사용해 다른 드라이브의 명령에 액세스할 수 있는 알려진 방법이 없습니다.

보안성 측면 이외에도 웹 사이트 및 응용 프로그램 파일과 폴더를 전용 디스크 볼륨에 배치하면 백업 및 복원 등의 관리 작업을 더욱 쉽게 수행할 수 있습니다. 또한 이런 유형의 콘텐트를 별도의 전용 드라이브에 배치하여 시스템 볼륨의 디스크 충돌 현상을 줄이고 전반적인 디스크 액세스 성능을 향상시킬 수 있습니다.
### NTFS 권한 설정

Windows Server 2003에서는 NTFS 파일 시스템 권한을 조사하여 사용자나 프로세스의 특정 파일 및 폴더에 대한 사용 권한을 결정합니다.

NTFS 권한은 본 설명서에 정의된 세 가지 환경에서의 IIS 서버에 있는 웹 사이트에 대해 특정 사용자에게 사용 권한을 부여하거나 거부하도록 지정되어야 합니다.

NTFS 권한은 웹 권한을 대신하는 것이 아니라 웹 권한과 연합하여 사용해야 합니다. NTFS 권한의 효력은 웹 사이트 및 응용 프로그램 콘텐트에 대한 사용 권한이 부여되었거나 거부된 계정에 대해서만 적용됩니다. 웹 사이트 권한은 웹 사이트나 응용 프로그램에 액세스하는 모든 사용자에게 영향을 줍니다. 디렉터리나 파일에 대해 웹 권한과 NTFS 권한에 충돌이 발생하면 더 제한적인 설정이 적용됩니다.

익명 계정에 대한 액세스는 익명 액세스가 필요 없는 웹 사이트 및 응용 프로그램에서 명시적으로 거부되어야 합니다. 익명 액세스는 인증된 자격 증명이 없는 사용자가 시스템 리소스를 액세스할 때 발생합니다. 익명 계정에는 기본 제공 **Guest** 계정, **Guests** 그룹 및 **IIS Anonymous** 계정 등이 포함됩니다. 또한 IIS 관리자를 제외한 모든 사용자의 쓰기 액세스 권한을 모두 제거합니다.

다음 표에서는 IIS 서버에 대해 서로 다른 파일 형식에 적용되는 몇 가지 NTFS 권장 권한을 제공합니다. 같은 부류에 속하는 다른 파일 형식들을 별도의 폴더에 그룹으로 모으면 NTFS 권한을 쉽게 적용할 수 있습니다.

**표 5: NTFS 권한**
 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>파일 형식</th>
<th>권장되는 NTFS 권한</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
CGI 파일(.exe, .dll, .cmd, .pl)</td>
<td style="border:1px solid black;">
Everyone(실행)<br />
Administrators(모든 권한)<br />
System(모든 권한)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
스크립트 파일(.asp)</td>
<td style="border:1px solid black;">
Everyone(실행)<br />
Administrators(모든 권한)<br />
System(모든 권한)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
포함 파일(.inc, .shtm, .shtml)</td>
<td style="border:1px solid black;">
Everyone(실행)<br />
Administrators(모든 권한)<br />
System(모든 권한)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
정적 콘텐트(.txt, .gif, .jpg, .htm, .html)</td>
<td style="border:1px solid black;">
Everyone(읽기 전용)<br />
Administrators(모든 권한)<br />
System(모든 권한)</td>
</tr>
</tbody>
</table>
 

### IIS 웹 사이트 권한 설정

IIS는 웹 사이트 권한을 조사하여 스크립트 소스 액세스나 디렉터리 검색을 허용하는 등 웹 사이트에서 어떤 조치를 발생시킬 지 결정합니다. 웹 사이트 권한은 본 설명서에 정의된 세 가지 환경에서 IIS 서버의 더욱 안전한 웹 사이트에 지정되어야 합니다.

웹 사이트 권한은 NTFS 권한과 연합하여 사용됩니다. 이 권한은 특정 사이트, 디렉터리 및 파일에 구성됩니다. NTFS 권한과 달리 웹 사이트 권한은 IIS 서버에서 실행되는 웹 사이트를 액세스하려고 하는 모든 사용자에게 영향을 줍니다. 웹 사이트 권한은 IIS 관리자 스냅인을 사용하여 적용됩니다.

다음 표에는 IIS 6.0에서 지원하는 웹 사이트 권한을 나열하고 해당 권한이 웹 사이트에 지정된 다음의 상황을 간단히 설명합니다.

**표 6: IIS 6.0 웹 사이트 권한**
 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>웹 사이트 권한:</th>
<th>권한 부여:</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
읽기</td>
<td style="border:1px solid black;">
사용자는 디렉터리나 파일의 내용과 특성을 볼 수 있습니다. 이 권한은 기본적으로 선택되어 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
쓰기</td>
<td style="border:1px solid black;">
사용자는 디렉터리나 파일의 내용과 특성을 변경할 수 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
스크립트 소스 액세스</td>
<td style="border:1px solid black;">
사용자는 소스 파일에 액세스할 수 있습니다. 읽기 권한을 사용하도록 설정한 경우에는 소스를 읽을 수 있으며 쓰기 권한을 사용하도록 설정하면 스크립트 소스 코드를 변경할 수 있습니다. 스크립트 소스 액세스에는 스크립트의 소스 코드가 포함됩니다. 읽기와 쓰기 권한을 모두 사용하도록 설정하지 않으면 이 옵션이 제공되지 않습니다.<br />
<strong>중요:</strong> 스크립트 소스 액세스를 사용하도록 설정하면 사용자는 사용자 이름과 암호 같은 기밀 정보를 볼 수 있습니다. 또한 IIS 서버에서 실행되는 소스 코드를 변경하여 서버의 보안성과 성능에 심각한 영향을 줄 수 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
디렉터리 검색</td>
<td style="border:1px solid black;">
사용자는 파일 목록과 집합을 볼 수 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
방문 기록</td>
<td style="border:1px solid black;">
웹 사이트를 방문할 때마다 로그 항목이 작성됩니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
이 리소스 색인화</td>
<td style="border:1px solid black;">
색인화 서비스를 사용하여 리소스를 색인화합니다. 리소스에 대한 검색 작업도 허용됩니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
실행</td>
<td style="border:1px solid black;">
다음 옵션에 따라 사용자의 스크립트 실행 단계가 결정됩니다.<br />
<strong>없음</strong> ? 스크립트와 실행 파일을 서버에서 실행할 수 없습니다.<br />
<strong>스크립트만</strong> ? 스크립트만 서버에서 실행할 수 있습니다.<br />
<strong>실행(스크립트 포함)</strong> ? 스크립트와 실행 파일을 모두 서버에서 실행할 수 있습니다.</td>
</tr>
</tbody>
</table>
 

### IIS 로깅 구성

본 설명서에서는 정의된 세 가지 환경의 IIS 서버에 대해 IIS 로깅 기능을 사용하도록 설정할 것을 권장합니다.

웹 사이트나 응용 프로그램 각각에 대해 별도의 로그가 작성됩니다. Microsoft Windows 운영 체제는 이벤트 로깅 범위 이상의 IIS 로그 정보나 성능 모니터링 기능을 제공합니다. IIS 로그에는 사이트 방문자, 방문자가 본 내용 및 정보를 마지막으로 본 시점 등의 정보가 포함됩니다. IIS 로그는 콘텐트의 인기를 평가하고 정보 병목 현상을 식별하는 데 사용하거나 공격 조사를 위한 리소스로 사용할 수 있습니다.

IIS 관리자 스냅인을 사용하면 로그 파일 형식, 로그 일정 및 로그할 정확한 정보 등을 구성할 수 있습니다. 로그 크기를 제한하려면 로그할 필드를 선택할 때 신중하게 계획해야 합니다.

IIS 로깅을 사용하도록 설정하면 IIS는 IIS 관리자를 통해 웹 사이트용으로 지정된 디렉터리로 저장될 매일의 작업 로그를 작성하는 데 W3C 확장형 로그 파일 형식을 사용합니다. 서버 성능을 향상시키려면 비 시스템 스트라이프 볼륨이나 스트라이프/미러 디스크 볼륨에 로그를 저장해야 합니다.

또한 로그는 완전한 UNC(Universal Naming Convention) 경로를 사용하여 네트워크 상의 원격 공유 파일에 기록됩니다. 원격 로깅을 사용하면 관리자가 중앙식 로그 파일 저장소와 백업을 설정할 수 있습니다. 그러나 네트워크 상의 로그 파일 기록은 서버 성능에 부정적인 영향을 줄 수 있습니다.

다른 ASCII 또는 ODBC(Open Database Connectivity) 로그 파일 형식을 사용하도록 IIS 로깅을 구성할 수 있습니다. ODBC 로깅을 사용하면 IIS가 작업 정보를 SQL 데이터베이스에 저장할 수 있습니다. 또한 ODBC 로깅을 사용하도록 설정된 시점을 알려야 IIS는 커널 모드 캐시를 사용하지 못하도록 설정합니다. 이러한 이유로 ODBC 로깅을 구현하면 전반적인 서버 성능이 저하됩니다.

수 많은 사이트를 호스트하는 IIS 서버는 이진 형식의 중앙식 로깅을 사용하여 로깅 성능을 향상시킬 수 있습니다. 이진 형식의 중앙식 로깅을 사용하면 IIS 서버의 모든 웹 사이트 작업 정보를 단일 로그 파일에 기록할 수 있습니다. 이렇게 함으로써 개별적으로 저장하여 분석해야 하는 로그 수가 줄어 들어 IIS 로깅 프로세스의 관리 기능 및 확장성이 크게 향상됩니다. 이진 형식의 중앙식 로깅에 대한 자세한 내용은 다음 사이트에서 Microsoft TechNet 항목인 "Centralized Binary Logging"을 참고하십시오. <http://www.microsoft.com/technet/prodtechnol/windowsserver2003/proddocs/standard/log_binary.asp> ![](images/Dd547914.tous(ko-kr,TechNet.10).gif).

IIS 로그가 IIS 서버에 저장되면 기본적으로 서버 관리자만 로그에 액세스할 수 있는 권한을 갖습니다. 로그 파일 디렉터리나 파일의 소유자가 **로컬 관리자** 그룹에 속해 있지 않다면 IIS 6.0의 커널 모드 드라이버인 HTTP.sys가 NT 이벤트 로그에 오류를 게시합니다. 이 오류는 **로컬 관리자** 그룹에 속해 있지 않은 디렉터리나 파일의 소유자를 알려 주며 해당 소유자가 **로컬 관리자** 그룹에 추가되거나 기존 디렉터리나 로그 파일이 삭제될 때까지 해당 사이트에 대한 로깅이 일시 중단됨을 나타냅니다.
### 사용자 권한 할당에 수동으로 고유 보안 그룹 추가

이 설명서와 함께 제공되는 보안 템플릿에는 MSBP를 통해 적용된 대부분의 사용자 권한 할당에 대해 적절한 보안 그룹이 지정되어 있습니다. 그러나 일부 계정 및 보안 그룹의 경우에는 해당 SID(보안 식별자)가 개별 Windows 2003 도메인에서 고유하므로 템플릿에 포함할 수 없습니다. 수동으로 구성해야 하는 사용자 권한 할당은 다음과 같이 지정됩니다.

**경고:** 다음 표에는 기본 제공 **Administrator** 계정에 대한 값이 들어 있습니다. **Administrator** 계정과 기본 제공 **Administrators** 보안 그룹을 혼돈하지 않도록 유의하십시오. **Administrators** 보안 그룹이 아래에 있는 임의의 거부 액세스 사용자 권한에 추가되면 오류를 바로 잡기 위해 로컬로 로그온하게 됩니다.

또한 기본 제공 **Administrator** 계정의 이름은 "Windows Server 2003 서버의 구성원 서버 기준 만들기" 모듈의 권장 사항에 따라 변경할 수 있습니다. **Administrator** 계정을 추가할 때 변경된 이름의 계정을 지정하도록 하십시오.

**표 7: 수동으로 추가된 사용자 권한 할당**
 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>구성원 서버 기본값</th>
<th>레거시 클라이언트</th>
<th>엔터프라이즈 클라이언트</th>
<th>고급 보안</th>
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
</tbody>
</table>
 

**경고:** 모든 비 운영 체제 서비스 계정에는 기업 전체에서 특정 응용 프로그램에 사용된 서비스 계정이 포함됩니다. 운영 체제가 사용하는 기본 제공 계정인 LOCAL SYSTEM, LOCAL SERVICE 또는 NETWORK SERVICE 계정은 여기에 해당되지 않습니다.

### 잘 알려진 계정의 보안

Windows Server 2003에는 삭제할 수 없지만 이름을 변경할 수는 있는 기본 제공 사용자 계정이 여러 개 포함되어 있습니다. Windows 2003에서 가장 잘 알려진 두 개의 기본 제공 계정은 **Guest**와 **Administrator**입니다.

**Guest** 계정은 구성원 서버와 도메인 컨트롤러에서 기본적으로 사용하지 않도록 설정됩니다. 이 설정은 변경하면 안 됩니다. 공격자가 잘 알려진 계정을 사용하여 원격 서버를 손상시키는 것을 방지하려면 기본 제공 **Administrator** 계정의 이름과 설명을 변경해야 합니다.

변형된 대부분의 악성 코드는 서버를 손상시키려는 초기 시도에서 기본 제공 Administrator 계정을 사용합니다. 기본 제공 Administrator 계정의 SID(보안 식별자)를 지정하여 해당 계정의 이름을 확인함으로써 서버 침입을 시도하는 공격 도구가 등장한 이후 지난 몇 년 동안 이 구성 변경 값은 감소했습니다. SID는 네트워크의 각 사용자, 그룹, 컴퓨터 계정 및 로그온 세션을 고유하게 식별하는 값입니다. 이 기본 제공 계정의 SID는 변경할 수 없습니다. 로컬 관리자 계정의 이름을 고유한 이름으로 바꾸면 작업 그룹에서 이 계정에 대해 시도된 공격을 모니터링하기가 쉬워집니다.
-   

    **IIS 서버의 잘 알려진 계정을 보호하려면**

    1.  

        **Administrator**와 **Guest** 계정의 이름을 변경한 다음 모든 도메인과 서버에서 암호를 길고 복잡한 것으로 변경합니다.

    2.  

        각 서버에 서로 다른 이름과 암호를 사용합니다. 모든 도메인 및 서버에 사용된 계정 이름과 암호가 동일하면 하나의 구성원 서버에 액세스한 공격자가 계정 이름 및 암호가 같은 다른 모든 서버에도 액세스할 수 있게 됩니다.

    3.  

        계정을 쉽게 식별할 수 없도록 계정 설명을 기본값이 아닌 다른 값으로 변경합니다.

    4.  

        이러한 변경 내용을 안전한 위치에 기록합니다.

**참고:**: 그룹 정책을 통해 기본 제공 Administrator 계정의 이름은 변경할 수 있습니다. 이 설정은 사용 환경에 고유한 이름을 사용자가 선택해야 하므로 이 설명서와 함께 제공되는 보안 템플릿에서는 구성되지 않았습니다. **계정: Administrator 계정 이름 변경** 설정은 본 설명서에 정의된 세 가지 환경에서 Administrator 계정의 이름을 변경하도록 구성될 수 있습니다. 이 설정은 그룹 정책의 보안 옵션 설정에 포함됩니다.
### 서비스 계정 보안

꼭 필요한 경우가 아니면 서비스가 도메인 계정의 보안 컨텍스트에서 실행되도록 구성하지 않습니다. 서버가 물리적으로 손상되면 LSA(로컬 보안 기관) 기밀 정보를 덤프하여 도메인 계정 암호를 알아낼 수 있습니다.
### IPSec 필터를 사용한 포트 차단

IPSec(인터넷 프로토콜 보안) 필터를 사용하면 서버에 필요한 보안 수준을 효과적으로 높일 수 있습니다. 이 설명서에 정의된 고급 보안 환경에서는 서버의 공격 허점을 더 줄이기 위해 이 선택적 방법을 사용하는 것이 좋습니다.

IPSec 필터 사용에 대한 자세한 내용은 모듈 "추가 구성원 서버 강화 절차"를 참고하십시오.

다음 표에는 본 설명서에 정의된 고급 보안 환경에서 IIS 서버에 작성할 수 있는 모든 IPSec 필터가 나열되어 있습니다.

**표 8: IIS 서버 IPSec 네트워크 트래픽 맵**
 
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
<th>서비스</th>
<th>프로토콜</th>
<th>원본 포트</th>
<th>대상 포트</th>
<th>원본 주소</th>
<th>대상 주소</th>
<th>동작</th>
<th>미러링</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
OnePoint 클라이언트</td>
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
터미널 서비스</td>
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
도메인 구성원</td>
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
<tr class="even">
<td style="border:1px solid black;">
도메인 구성원</td>
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
<tr class="odd">
<td style="border:1px solid black;">
HTTP 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
80</td>
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
HTTPS 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
443</td>
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

위의 표는 서버에서 해당 역할 관련 기능을 수행하기 위해 열려야 하는 기준 포트를 나타냅니다. 서버가 정적 IP 주소를 갖고 있는 경우에는 이러한 포트로 충분합니다. 추가 기능을 제공하기 위해 추가 포트를 열어야 할 수도 있습니다. 추가 포트를 열게 되면 사용자 환경에서 관리자가 IIS 서버를 더 쉽게 관리할 수 있지만 서버 보안성은 크게 약화됩니다.

도메인 구성원과 도메인 컨트롤러 사이의 수많은 상호 작용으로 인해, IIS 서버와 모든 도메인 컨트롤러 간에 모든 통신, 특히 RPC 및 인증 트래픽을 통한 통신을 수행할 수 있습니다. 트래픽을 더 제한할 수 있지만 대부분의 환경에서 필터가 서버를 효과적으로 보호하도록 하려면 수십 개의 추가 필터를 만들어야 합니다. 이 경우 IPSec 정책을 구현하고 관리하기가 매우 어려워집니다. 따라서 IIS 서버와 상호 작용하는 도메인 컨트롤러 각각에 대해 유사한 규칙을 만들어야 합니다. 대개 IIS 서버의 안정성과 가용성을 높이기 위해 사용자 환경의 모든 도메인 컨트롤러에 대한 규칙이 추가됩니다.

위에서 보여 준 것처럼 사용 중인 환경에 MOM(Microsoft Operations Manager)이 구현되어 있는 경우 IPSec 필터가 구현된 서버와 MOM 서버 사이에 모든 네트워크 트래픽이 이동할 수 있어야 합니다. 이는 MOM 서버와 OnePoint 클라이언트(MOM 콘솔에 보고하는 클라이언트 응용 프로그램) 사이에서 많은 양의 상호 작용이 수행되기 때문에 필요합니다. 다른 관리 패키지의 요구 사항은 이와 비슷할 수 있습니다. 훨씬 더 높은 수준의 보안이 필요할 경우 MOM 서버와 IPSec를 협상하도록 OnePoint 클라이언트에 대한 필터 동작을 구성할 수 있습니다.

이 IPSec 정책은 임의의 높은 포트를 통한 트래픽을 효과적으로 차단하므로 RPC(원격 프로시저 호출) 트래픽을 허용하지 않습니다. 따라서 서버 관리가 어려워질 수 있습니다. 대부분의 포트가 효과적으로 닫혀 있기 때문에 터미널 서비스를 사용할 수 있습니다. 이 경우 관리자는 원격 관리를 수행할 수 있습니다.

위의 네트워크 트래픽 맵에서는 사용 환경에 Active Directory를 사용할 수 있는 DNS 서버가 포함되어 있는 것으로 가정합니다. 독립 실행형 DNS 서버가 사용되는 경우에는 추가 규칙이 필요할 수 있습니다.

IPSec 정책을 구현할 때 서버 성능에 중대한 영향을 미쳐서는 안 됩니다. 그러나 이러한 필터를 구현하기 전에 테스트를 수행하여 필요한 서버 기능 및 성능이 유지되는지 확인해야 합니다. 다른 응용 프로그램을 지원하기 위해 규칙을 추가해야 할 수도 있습니다.

본 설명서에는 IIS 서버에 대해 규정된 IPSec 필터를 간단히 작성할 수 있는 .cmd 파일에 대한 내용이 포함되어 있습니다. **PacketFilters-IIS.cmd** 파일은 NETSH 명령을 사용하여 알맞은 필터를 작성합니다. 이 .cmd 파일을 수정하여 사용 환경에 있는 도메인 컨트롤러의 IP 주소를 포함해야 합니다. 이 스크립트에는 두 개의 도메인 컨트롤러를 추가하기 위한 자리 표시자가 포함되어 있습니다. 따라서 필요하면 도메인 컨트롤러를 추가할 수 있습니다. 도메인 컨트롤러에 대한 이 IP 주소 목록은 항상 최신 상태를 유지해야 합니다.

사용 환경에 MOM이 있는 경우에는 스크립트에 해당 MOM 서버의 IP 주소도 지정되어 있어야 합니다. 이 스크립트는 영구 필터를 만들지 않습니다. 따라서 서버는 IPSec 정책 에이전트가 시작되어야만 보호됩니다. 영구 필터를 만들거나 보다 고급의 IPSec 필터 스크립트를 작성하는 방법에 대해서는 모듈 "추가 구성원 서버 강화 절차"를 참고하십시오. 마지막으로, 이 스크립트는 스크립트에서 만드는 IPSec 정책을 할당하지 않도록 구성되어 있습니다. IP 보안 정책 관리 스냅인을 사용하면 만든 IPSec 필터를 검사하고 이 IPSec 필터가 적용되도록 하기 위해 IPSec 정책을 할당할 수 있습니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection132121120120"></span>
요약
----

이 모듈에서는 이 가이드에서 정의한 세 가지 환경에서 IIS 서버에 대해 보안을 설정하기 위한 서버 강화 설정을 설명했습니다. 여기에서 설명하는 대부분의 설정은 그룹 정책을 사용하여 구성되고 적용됩니다. MSBP를 따르도록 설계된 GPO(그룹 정책 개체)는 이러한 서버에서 제공하는 서비스를 기반으로 추가적인 보안 기능을 제공하기 위해 IIS 서버를 포함하여 적절한 OU(조직 구성 단위)에 링크됩니다.

여기에서 설명하는 일부 설정은 그룹 정책을 사용하여 적용할 수 없습니다. 이 경우 이러한 설정을 수동으로 구성하는 방법이 자세히 설명되어 있습니다. IIS 서버와 통신할 수 있는 네트워크 트래픽 유형을 조정하는 IPSec 필터를 작성하고 적용하는 방법에 대해서도 자세히 설명합니다.
### 추가 정보

다음은 이 제품의 출시 당시 Windows Server 2003이 실행되는 컴퓨터 환경에서의 IIS 서버와 관련하여 작성된 최신 자료입니다.

이 주제에 대한 자세한 내용은 다음 사이트에서 "Enable Logging"을 참고하십시오. <http://www.microsoft.com/technet/prodtechnol/windowsserver2003/proddocs/standard/log_enablelogging.asp> ![](images/Dd547914.tous(ko-kr,TechNet.10).gif)

사이트 작업 로깅에 대한 내용은 다음 사이트에서 "Logging Site Activity"를 참고하십시오. <http://www.microsoft.com/technet/prodtechnol/windowsserver2003/proddocs/standard/log_aboutlogging.asp> ![](images/Dd547914.tous(ko-kr,TechNet.10).gif)

확장된 로깅에 대한 내용은 다음 사이트에서 "Customizing W3C Extended Logging"을 참고하십시오. <http://www.microsoft.com/technet/prodtechnol/windowsserver2003/proddocs/standard/log_customw3c.asp> ![](images/Dd547914.tous(ko-kr,TechNet.10).gif)

이진 형식의 중앙식 로깅에 대한 내용은 다음 사이트에서 "Centralized Binary Logging"을 참고하십시오. <http://www.microsoft.com/technet/prodtechnol/windowsserver2003/proddocs/standard/log_binary.asp> ![](images/Dd547914.tous(ko-kr,TechNet.10).gif)

원격 로깅에 대한 내용은 다음 사이트에서 "Remote Logging"을 참고하십시오. <http://www.microsoft.com/technet/prodtechnol/windowsserver2003/proddocs/standard/log_remote.asp> ![](images/Dd547914.tous(ko-kr,TechNet.10).gif)

보안 로그(감사)를 생성하거나 보거나 이해하는 것과 관련한 내용은 다음 위치에 있는 Microsoft TechNet 보안 사이트를 방문하십시오. <http://www.microsoft.com/technet/prodtechnol/windowsserver2003/proddocs/standard/sec_security.asp> ![](images/Dd547914.tous(ko-kr,TechNet.10).gif)

IIS 6.0에 대한 추가 내용은 [www.microsoft.com/iis](http://www.microsoft.com/technet/prodtechnol/windowsnetserver/proddocs/standard/iiswelcome.asp) ![](images/Dd547914.tous(ko-kr,TechNet.10).gif)에 있는 TechNet 사이트를 방문하십시오.

IPSec 필터링에 대한 자세한 내용은 다음 위치에서 "How To: Use IPSec IP Filter Lists in Windows 2000"을 참조하십시오. <http://support.microsoft.com/default.aspx?scid=313190>
[](#mainsection)[페이지 위쪽](#mainsection)
