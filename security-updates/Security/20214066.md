---
TOCTitle: Windows Server 2003 인프라 서버 강화
Title: Windows Server 2003 인프라 서버 강화
ms:assetid: 'a3235efd-a81d-4fee-8ea7-c2bd6b39f328'
ms:contentKeyID: 20214066
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547911(v=TechNet.10)'
---

Windows Server 2003 인프라 서버 강화
====================================

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
[](#xsltsection132121120120)[요약](#xsltsection132121120120)

<span id="XSLTsection121121120120"></span>
모듈 정보
---------

이 모듈에서는 Microsoft Windows Server™ 2003 운영 체제 기반 인프라 서버 전용 보안 템플릿의 구성에 대해 설명합니다. 모듈의 설명을 위해 인프라 서버는 DHCP(Dynamic Host Configuration Protocol) 서비스 또는 WINS(Windows Internet Name Services) 기능을 제공하는 서버입니다. 이 모듈에서는 서버에 이미 구성원 서버 기준이 적용된 것으로 가정합니다. 이 모듈에서는 보안 템플릿에 정의된 설정 외에 적용해야 하는 추가 보안 구성 설정도 다룹니다. 이 추가 설정은 완전하게 강화된 파일 서버를 만드는 데 필요합니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection122121120120"></span>
목표
----

이 모듈을 사용하여 다음을 할 수 있습니다.
-   

    Windows Server 2003 기반 인프라 서버를 강화합니다.

-   

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

이 모듈을 사용하여 Windows Server 2003 기반 인프라 서버에 적용해야 하는 보안 설정을 이해할 수 있습니다. 이 모듈에서는 역할 관련 보안 템플릿과 기준 보안 템플릿을 함께 사용합니다. 이러한 보안 템플릿은 [http://go.microsoft.com/fwlink/?LinkId=14846](http://go.microsoft.com/fwlink/?linkid=14846) ![](images/Dd547911.tous(ko-kr,TechNet.10).gif)에서 Windows Server 2003 Security Guide와 함께 다운로드할 수 있습니다.

이 모듈을 최대한 활용하려면 다음을 수행합니다.
-   

    **모듈 "Windows Server 2003 보안 소개"**를 참고하십시오. 여기에서는 Windows 2003 보안의 목적과 내용을 설명합니다.

-   

    **모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"**를 참고하십시오. 이 모듈에서는 조직 구성 단위 계층 구조와 그룹 정책을 사용하여 여러 서버에 구성원 서버 기준을 적용하는 방법을 보여 줍니다.

[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection125121120120"></span>
개요
----

이 모듈에서는 이 설명서에 정의된 세 가지 환경에서 인프라 서버를 보호하기 위한 서버 강화 설정에 대해 설명합니다. 이 설명서의 목적상, 인프라 서버는 DHCP(Dynamic Host Control Protocol) 서비스 또는 WINS(Windows Internet Name Service) 기능을 제공하는 서버를 나타냅니다.

여기에서 설명하는 대부분의 설정은 그룹 정책을 사용하여 구성되고 적용됩니다. MSBP(구성원 서버 기준 정책)를 보완하도록 설계된 GPO(그룹 정책 개체)는 이러한 서버가 제공하는 서비스를 기반으로 추가 보안을 제공하기 위해 인프라 서버가 포함된 해당 OU(조직 구성 단위)에 연결할 수 있습니다.

여기에서 설명하는 일부 설정은 그룹 정책을 사용하여 적용할 수 없습니다. 이 경우 이러한 설정을 수동으로 구성하는 방법이 자세히 설명되어 있습니다. 이 모듈에서 설명하는 두 종류의 인프라 서버와 통신할 수 있는 네트워크 종류를 제어하는 IPSec(Internet Protocol Security) 필터를 만들고 적용하는 자세한 방법도 제공합니다.

이 모듈의 유용성을 향상시키기 위해 여기서는 MSBP에서 수정된 설정만 설명합니다. MSBP의 설정에 대한 자세한 내용은 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"를 참고하십시오. 모든 기본 설정에 대한 자세한 내용은 관련 설명서인 Threats and Countermeasures: Security Settings in Windows Server 2003 and Windows XP를 참고하십시오.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection126121120120"></span>
감사 정책 설정
--------------

이 설명서에 정의된 세 가지 환경에서 인프라 서버의 감사 정책 설정은 MSBP를 통해 구성됩니다. MSBP에 대한 자세한 내용은 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"를 참고하십시오. MSBP 설정을 사용하면 모든 관련 보안 감사 정보를 모든 인프라 서버에 기록할 수 있습니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection127121120120"></span>
사용자 권한 할당
----------------

이 설명서에 정의된 세 가지 환경에서 인프라 서버의 사용자 권한 할당은 MSBP를 통해 구성됩니다. MSBP에 대한 자세한 내용은 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"를 참고하십시오. MSBP 설정을 사용하면 모든 해당 사용자 권한 할당이 인프라 서버에 일관되게 구성됩니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection128121120120"></span>
보안 옵션
---------

이 설명서에 정의된 세 가지 환경에서 인프라 서버의 보안 옵션 설정은 MSBP를 통해 구성됩니다. MSBP에 대한 자세한 내용은 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"를 참고하십시오. MSBP 설정을 사용하면 모든 관련 보안 옵션이 인프라 서버에 일관되게 구성됩니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection129121120120"></span>
이벤트 로그 설정
----------------

이 설명서에 정의된 세 가지 환경에서 인프라 서버의 이벤트 로그 설정은 MSBP를 통해 구성됩니다. MSBP에 대한 자세한 내용은 모듈 "Windows Server 2003 서버의 구성원 서버 기준 만들기"를 참고하십시오.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection130121120120"></span>
시스템 서비스
-------------

이 시스템 서비스 설정 섹션에서는 사용자 환경에 있는 인프라 서버에서 사용하거나 사용하지 말아야 하는 지정된 시스템에 대한 내용을 자세히 설명합니다. 이러한 서비스 설정은 인프라 서버 증분 정책에 지정되어 있습니다. DoS(서비스 거부) 공격 가능성을 최소화하기 위해 GPO는 이러한 서비스가 자동으로 시작되도록 구성됩니다. 이 섹션에 지정된 설정에 대한 요약은 [http://go.microsoft.com/fwlink/?LinkId=14846](http://go.microsoft.com/fwlink/?linkid=14846) ![](images/Dd547911.tous(ko-kr,TechNet.10).gif) 에서 Windows Server 2003 Security Guide와 함께 포함된 'Excel 통합 문서로 제공되는 Windows Server 2003 Security Guide Settings를 참조하십시오.
### DHCP 서버

**표 1: 설정**
<p> </p>
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
<th style="border:1px solid black;" >서비스 이름</th>
<th style="border:1px solid black;" >구성원 서버 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
DHCP</td>
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
 

DHCP 서비스는 IP(인터넷 프로토콜) 주소를 DHCP 클라이언트에 자동으로 할당하고 DNS 서버와 WINS 서버 같은 네트워크 설정의 고급 구성을 사용합니다. DHCP는 클라이언트/서버 모델을 사용합니다. 네트워크 관리자는 TCP/IP(Transmission Control Protocol/Internet Protocol) 구성 정보를 유지 관리하는 DHCP 서버를 하나 이상 설정하여 클라이언트에 제공합니다.

IP 주소 구성을 클라이언트에 할당하려면 DHCP 서버에서 DHCP 서버 서비스를 실행하고 있어야 합니다. 그룹 정책을 사용하여 서비스에 보안을 설정하고 서비스 시작 모드를 설정하면 서버 관리자에게만 액세스 권한이 부여되므로 권한이 없거나 악의적인 사용자는 서비스를 구성하거나 서비스에 대한 작업을 수행하지 못하게 됩니다. 또한 그룹 정책을 사용하면 관리자가 실수로 서비스를 사용하지 못하도록 설정하는 것을 방지할 수 있습니다.
### WINS

**표 2: 설정**
<p> </p>
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
<th style="border:1px solid black;" >서비스 이름</th>
<th style="border:1px solid black;" >구성원 서버 기본값</th>
<th style="border:1px solid black;" >레거시 클라이언트</th>
<th style="border:1px solid black;" >엔터프라이즈 클라이언트</th>
<th style="border:1px solid black;" >고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
WINS</td>
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
 

WINS는 NetBIOS(네트워크 기본 입/출력 시스템) 이름 확인을 사용합니다. NetBIOS 이름을 사용하여 확인된 네트워크 리소스를 찾으려면 WINS 서버가 있어야 합니다. 모든 도메인이 Microsoft Active Directory 디렉터리 서비스로 업그레이드되지 않고, 네트워크의 모든 컴퓨터가 Microsoft Windows 2000 이상의 운영 체제를 실행하지 않고, 응용 프로그램이 적절한 작동을 위해 WINS 이름 확인을 사용하지 않는 경우에는 WINS 서버가 필요합니다.

클라이언트에 이름 확인을 제공하려면 WINS 서버에서 WINS 서버 서비스를 실행하고 있어야 합니다. 그룹 정책을 사용하여 서비스에 보안을 설정하고 서비스 시작 모드를 설정하면 서버 관리자에게만 액세스 권한이 부여되므로 권한이 없거나 악의적인 사용자는 서비스를 구성하거나 서비스에 대한 작업을 수행하지 못하게 됩니다. 또한 그룹 정책을 사용하면 관리자가 실수로 서비스를 사용하지 못하도록 설정하는 것을 방지할 수 있습니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection131121120120"></span>
추가 보안 설정
--------------

MSBP를 통해 적용된 보안 설정은 인프라 서버의 여러 가지 향상된 보안을 제공합니다. 몇 가지 사항을 더 고려해야 합니다. 그룹 정책을 통해 이러한 단계를 완료할 수는 없고 모든 인프라 서버에서 수동으로 수행해야 합니다.
### DHCP 로깅 구성

DHCP 서비스는 기본적으로 이벤트 뷰어에 시작과 종료 이벤트만 기록합니다. 다음 단계를 수행하여 DHCP 서버에 보다 상세한 로그를 사용할 수 있습니다.
1.  

    DHCP 관리 도구에서 DHCP 서버를 마우스 오른쪽 단추로 클릭합니다.

2.  

    **속성**을 선택합니다.

3.  

    **속성** 대화 상자의 **일반** 탭에서 **DHCP 감사 로깅 사용**을 클릭합니다.

이러한 단계를 완료한 후에 DHCP 서버는 다음 위치에 로그 파일을 만듭니다.

%systemroot%\\system32\\dhcp\\

대부분의 이벤트 로그에 저장되는 유일한 정보는 대개 IP 주소가 아닌 컴퓨터 이름이기 때문에 DHCP 클라이언트는 로그 항목에서 찾기가 어렵습니다. DHCP 감사 로그는 내부 공격이나 부주의한 활동의 원인을 찾는 도구를 하나 이상 제공할 수 있습니다.

그러나 호스트 이름과 MAC(Media Access Control) 주소 둘 모두 위조나 위장할 수 있기 때문에 이러한 로그의 정보는 절대 간단하지는 않습니다. 스푸핑은 작업을 수행한 사용자가 아닌 다른 사용자로부터 전송되는 것처럼 보이게 만드는 방법입니다. 그러나 지금까지 DHCP 서버에서 로깅을 사용함으로써 발생되는 비용보다 이 정보를 수집하는 이점이 더 많습니다. IP 주소와 시스템 이름만 있으면 특정 IP 주소가 네트워크에서 어떻게 사용되는지 확인하는 데 큰 도움이 될 수 있습니다.

기본적으로 Server Operators 및 Authenticated Users에는 이러한 로그 파일에 대한 읽기 권한이 있습니다. DHCP 서버가 기록하는 정보의 무결성을 잘 유지하려면 이러한 로그에 대한 액세스를 서버 관리자로 제한하는 것이 좋습니다. Server Operators 및 Authenticated Users 그룹을 %systemroot%\\system32\\dhcp\\ 폴더의 ACL(액세스 제어 목록)에서 제거해야 합니다.

DHCP 감사 로그는 이론적으로 로그가 저장된 디스크를 채울 수 있습니다. 그러나 DHCP 감사 로깅 설정의 기본 구성을 사용하면 서버에 남아 있는 여유 디스크 공간이 20MB 미만일 경우 이 로깅이 중지됩니다. 대부분의 환경에서는 기본 설정이면 적당하지만 서버의 다른 응용 프로그램이 충분한 여유 디스크 공간을 사용할 수 있도록 이 설정을 수정할 수 있습니다. 이 설정을 수정하는 방법에 대한 자세한 내용은 Windows 2000 Server Resource Kit 의 "DhcpLogMinSpaceOnDisk" 항목을 참조하십시오. <http://www.microsoft.com/windows2000/techinfo/reskit/en-us/default.asp?url=/windows2000/techinfo/reskit/en-us/regentry/46692.asp> ![](images/Dd547911.tous(ko-kr,TechNet.10).gif).

이 문서에서 설명하는 레지스트리 설정은 Windows Server 2003에서 실행되는 DHCP에도 적용됩니다.
### DHCP 서비스 거부 공격으로부터 보호

DHCP 서버가 네트워크에 대한 클라이언트 액세스를 제공하는 중요한 리소스이기 때문에 DoS 공격의 주요 대상이 될 수 있습니다. DHCP 서버가 공격을 받고 서비스 DHCP 요청에 대해 더 이상 서비스를 제공할 수 없는 경우 결국 DHCP 클라이언트가 임대를 얻지 못할 수도 있습니다. 이러한 클라이언트는 기존 IP 임대 및 네트워크 리소스에 액세스하는 기능을 잃게 됩니다.

DHCP 서버에서 사용 가능한 모든 주소를 요청하는 공격 도구 스크립트는 쉽게 작성할 수 있습니다. 이렇게 하면 이후에 DHCP 클라이언트가 보내는 합법적인 요청에 대해 사용 가능한 IP 주소의 풀을 소모하게 됩니다. 또한 악의적인 사용자가 자신이 관리하는 컴퓨터의 네트워크 어댑터에 있는 모든 DHCP IP 주소를 구성할 수도 있습니다. 따라서 DHCP 서버가 모든 주소에 대한 IP 주소 충돌을 검색하고 DHCP 임대 할당을 거부하게 됩니다.

또한 다른 모든 네트워크 서비스와 마찬가지로 합법적인 트래픽에 응답하는 DHCP 서버의 기능을 소모하는 CPU 소모 또는 DHCP 수신기의 요청 버퍼 채우기 등의 DoS 공격으로 인해 클라이언트는 임대와 갱신을 요청하지 못할 수 있습니다. 환경에서 DHCP 서비스를 적절히 설계함으로써 이것을 피할 수 있습니다.

DHCP 서버를 쌍으로 구성하고 가장 좋은 방법인 80/20 규칙(예: 한 DHCP 서버가 배포하는 주소를 80%로 하고 다른 DHCP 서버가 배포하는 주소는 20%가 되도록 서버 간에 DHCP 서버 범위를 분할)을 준수하면 서버에 오류가 발생하더라도 해당 클라이언트가 IP 주소 구성을 계속 받을 수 있도록 함으로써 이러한 종류의 공격이 주는 영향을 완화할 수 있습니다. 80/20 규칙과 DHCP 프로토콜에 대한 자세한 내용은 Windows 2000 Server Resource Kit의 DHCP 프로토콜 항목을 참고하십시오. <http://www.microsoft.com/windows2000/techinfo/reskit/en-us/default.asp?url=/windows2000/techinfo/reskit/en-us/cnet/cncb_dhc_ogjw.asp> ![](images/Dd547911.tous(ko-kr,TechNet.10).gif).
### 잘 알려진 계정의 보안

Windows Server 2003에는 삭제할 수 없지만 이름을 변경할 수는 있는 기본 제공 사용자 계정이 여러 개 포함되어 있습니다. Windows 2003에서 가장 잘 알려진 기본 제공 계정 중 두 가지는 **Guest** 와 **Administrator**입니다.

기본적으로 구성원 서버와 도메인 컨트롤러에서는 **Guest** 계정이 사용되지 않습니다. 이 설정은 변경하면 안 됩니다. 공격자가 잘 알려진 계정을 사용하여 원격 서버를 손상시키지 못하도록 하려면 기본 제공 **Administrator** 계정의 이름과 설명을 변경해야 합니다.

변형된 대부분의 악성 코드는 서버를 손상시키려는 초기 시도에서 기본 제공 Administrator 계정을 사용합니다. 기본 제공 **Administrator** 계정의 SID(보안 식별자)를 지정하여 해당 계정의 이름을 확인함으로써 서버 침입을 시도하는 공격 도구가 등장한 이후 지난 몇 년 동안 이 구성 변경 값이 감소했습니다. SID는 네트워크의 각 사용자, 그룹, 컴퓨터 계정 및 로그온 세션을 고유하게 식별하는 값입니다. 이 기본 제공 계정의 SID는 변경할 수 없습니다. 로컬 관리자 계정의 이름을 고유한 이름으로 바꾸면 작업 그룹에서 이 계정에 대해 시도된 공격을 모니터링하기가 쉬워집니다.
-   

    **인프라 서버에서 잘 알려진 계정을 보호하려면:**

    1.  

        모든 도메인과 서버에서 **Administrator** 및 **Guest** 계정 이름을 변경하고 해당 암호를 길고 복잡한 값으로 변경하십시오.

    2.  

        각 서버에 서로 다른 이름과 암호를 사용합니다. 모든 도메인 및 서버에 사용된 계정 이름과 암호가 동일하면 하나의 구성원 서버에 액세스한 공격자가 계정 이름 및 암호가 같은 다른 모든 서버에도 액세스할 수 있게 됩니다.

    3.  

        계정을 쉽게 식별할 수 없도록 계정 설명을 기본값이 아닌 다른 값으로 변경합니다.

    4.  

        이러한 변경 내용을 안전한 위치에 기록합니다.

**참고:** 기본 제공 **Administrator** 계정의 이름은 그룹 정책을 통해 변경할 수 있습니다. 이 설정은 사용 환경에 고유한 이름을 사용자가 선택해야 하므로 이 설명서와 함께 제공되는 보안 템플릿에서는 구성되지 않았습니다. **계정: Administrator 계정 이름 바꾸기** 설정을 사용하면 이 설명서에 정의된 세 가지 환경에서 Administrator 계정의 이름을 바꿀 수 있습니다. 이 설정은 보안 옵션 설정 GPO에 포함됩니다.
### 서비스 계정 보안

꼭 필요한 경우가 아니면 서비스가 도메인 계정의 보안 컨텍스트에서 실행되도록 구성하지 않습니다. 서버가 물리적으로 손상되면 LSA(로컬 보안 기관) 기밀 정보를 덤프하여 도메인 계정 암호를 알아낼 수 있습니다.
### IPSec 필터를 사용한 포트 차단

IPSec(인터넷 프로토콜 보안) 필터를 사용하면 서버에 필요한 보안 수준을 효과적으로 높일 수 있습니다. 이 설명서에 정의된 고급 보안 환경에서는 서버의 공격 허점을 더 줄이기 위해 이 선택적 방법을 사용하는 것이 좋습니다.

IPSec 필터 사용에 대한 자세한 내용은 모듈 "추가 구성원 서버 강화 절차"를 참고하십시오.

다음 표는 이 설명서에 정의된 고급 보안 환경에서 DHCP 서버에 만들 수 있는 모든 IPSec 필터를 나열합니다.

**표 3: DHCP 서버 IPSec 네트워크 트래픽 맵**
<p> </p>
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
DHCP 서버</td>
<td style="border:1px solid black;">
UDP</td>
<td style="border:1px solid black;">
68</td>
<td style="border:1px solid black;">
67</td>
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
 

다음 표는 이 설명서에 정의된 고급 보안 환경에서 WINS 서버에 만들 수 있는 모든 IPSec 필터를 나열합니다.

**표 4: WINS 서버 IPSec 네트워크 트래픽 맵**
<p> </p>
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
WINS 이름 확인 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
1512</td>
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
1512</td>
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
WINS 복제 클라이언트</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
42</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
WINS 복제 파트너</td>
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
42</td>
<td style="border:1px solid black;">
ME</td>
<td style="border:1px solid black;">
WINS 복제 파트너</td>
<td style="border:1px solid black;">
허용</td>
<td style="border:1px solid black;">
예</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
WINS 복제 서버</td>
<td style="border:1px solid black;">
TCP</td>
<td style="border:1px solid black;">
임의</td>
<td style="border:1px solid black;">
42</td>
<td style="border:1px solid black;">
WINS 복제 파트너</td>
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
42</td>
<td style="border:1px solid black;">
WINS 복제 파트너</td>
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

위의 표는 서버에서 해당 역할 관련 기능을 수행하기 위해 열려야 하는 기준 포트를 나타냅니다. 서버가 정적 IP 주소를 갖고 있는 경우에는 이러한 포트로 충분합니다. 추가 기능을 제공하기 위해 추가 포트를 열어야 할 수도 있습니다. 추가 포트를 열면 사용자 환경의 인프라 서버를 쉽게 관리할 수 있지만 이러한 서버의 보안성이 크게 낮아질 수 있습니다.

특히 RPC와 인증 트래픽에서 도메인 구성원과 도메인 컨트롤러 사이의 상호 작용이 많기 때문에 인프라 서버와 모든 도메인 컨트롤러 간에 모든 통신이 허용됩니다. 트래픽을 더 제한할 수 있지만 대부분의 환경에서 필터가 서버를 효과적으로 보호하도록 하려면 수십 개의 추가 필터를 만들어야 합니다. 이 경우 IPSec 정책을 구현하고 관리하기가 매우 어려워집니다. 인프라 서버가 상호 작용할 각 도메인 컨트롤러에 대해 비슷한 규칙을 만들어야 합니다. 인프라 서버의 안정성과 가용성을 높이기 위해 환경에 있는 모든 도메인 컨트롤러에 대해 규칙을 추가하기도 합니다.

위에서 보여 준 것처럼 사용 중인 환경에 MOM(Microsoft Operations Manager)이 구현되어 있는 경우 IPSec 필터가 구현된 서버와 MOM 서버 사이에 모든 네트워크 트래픽이 이동할 수 있어야 합니다. 이는 MOM 서버와 OnePoint 클라이언트(MOM 콘솔에 보고하는 클라이언트 응용 프로그램) 사이에서 많은 양의 상호 작용이 수행되기 때문에 필요합니다. 다른 관리 패키지의 요구 사항은 이와 비슷할 수 있습니다. 훨씬 더 높은 수준의 보안이 필요할 경우 MOM 서버와 IPSec를 협상하도록 OnePoint 클라이언트에 대한 필터 동작을 구성할 수 있습니다.

이 IPSec 정책은 임의의 높은 포트를 통한 트래픽을 효과적으로 차단하므로 RPC(원격 프로시저 호출) 트래픽을 허용하지 않습니다. 따라서 서버 관리가 어려워질 수 있습니다. 대부분의 포트가 효과적으로 닫혀 있기 때문에 터미널 서비스를 사용할 수 있습니다. 이 경우 관리자는 원격 관리를 수행할 수 있습니다.

위의 네트워크 트래픽 맵에서는 사용 환경에 Active Directory를 사용할 수 있는 DNS 서버가 포함되어 있는 것으로 가정합니다. 독립 실행형 DNS 서버가 사용되는 경우에는 추가 규칙이 필요할 수 있습니다.

IPSec 정책을 구현할 때 서버 성능에 중대한 영향을 미쳐서는 안 됩니다. 그러나 이러한 필터를 구현하기 전에 테스트를 수행하여 필요한 서버 기능 및 성능이 유지되는지 확인해야 합니다. 다른 응용 프로그램을 지원하기 위해 규칙을 추가해야 할 수도 있습니다.

이 설명서에 포함된 .cmd 파일을 사용하면 인프라 서버에 대해 지정된 IPSec 필터를 쉽게 만들 수 있습니다. PacketFilters-DHCP.cmd 및 PacketFilters-WINS.cmd 파일은 NETSH 명령을 사용하여 적절한 필터를 만듭니다. 이러한 .cmd 파일을 수정하여 사용 환경에 있는 도메인 컨트롤러의 IP 주소를 포함해야 합니다. 이 스크립트에는 두 개의 도메인 컨트롤러를 추가하기 위한 자리 표시자가 포함되어 있습니다. 원한다면 이러한 스크립트에 추가 도메인 컨트롤러를 추가할 수 있습니다. 도메인 컨트롤러에 대한 이 IP 주소 목록은 항상 최신 상태를 유지해야 합니다. WINS 복제 파트너에 대해서만 자리 표시자가 포함됩니다. WINS 복제를 적용하려면 PacketFilters-WINS.cmd 파일에 적절한 WINS 복제 파트너도 지정해야 합니다.

사용 환경에 MOM이 있는 경우에는 스크립트에 해당 MOM 서버의 IP 주소도 지정되어 있어야 합니다. 이 스크립트는 영구 필터를 만들지 않습니다. 따라서 서버는 IPSec 정책 에이전트가 시작되어야만 보호됩니다. 영구 필터를 만들거나 보다 고급의 IPSec 필터 스크립트를 작성하는 방법에 대해서는 모듈 "추가 구성원 서버 강화 절차"를 참고하십시오. 마지막으로, 이 스크립트는 스크립트에서 만드는 IPSec 정책을 할당하지 않도록 구성되어 있습니다. IP 보안 정책 관리 스냅인을 사용하면 만든 IPSec 필터를 검사하고 이 IPSec 필터가 적용되도록 하기 위해 IPSec 정책을 할당할 수 있습니다.
[](#mainsection)[페이지 위쪽](#mainsection)

<span id="XSLTsection132121120120"></span>
요약
----

이 모듈에서는 이 설명서에 정의된 세 가지 환경에서 DHCP 및 WINS 서버를 보호하기 위한 서버 강화 설정에 대해 설명합니다. 이러한 역할에 대한 대부분의 설정은 MSBP를 통해 적용됩니다. DHCP 및 WINS 서버에 대한 증분 .inf 파일의 주요 목표는 보안을 유지하면서 이러한 역할이 완벽하게 작동하는 데 필요한 서비스를 사용하는 것입니다.

MSBP는 높은 수준의 보안을 제공하지만 인프라 역할에 대한 다른 몇 가지 다른 고려 사항도 설명했습니다. 주로 이러한 고려 사항에는 이러한 컴퓨터에 대한 승인받지 않은 네트워크 트래픽을 차단하기 위한 로깅 사용과 IPSec 필터의 선택적인 사용도 포함되었습니다.
### 추가 정보

다음은 Windows Server 2003의 출시 당시 Windows Server 2003을 실행하는 컴퓨터가 있는 환경에서 인프라 서버와 관련하여 작성된 최신 자료입니다.

DHCP 로깅에 대한 Windows Server 2003 변경 사항에 대한 최신 정보는 다음 페이지를 참고하십시오. <http://support.microsoft.com/default.aspx?scid=328891>.

Active Directory 도메인에서 DHCP 서버에 대한 자세한 내용은 <http://support.microsoft.com/default.aspx?scid=323360>에서 "HOWTO: Windows Server 2003 제품군의 Active Directory 도메인에서 DHCP 서버 설치 및 구성"을 참고하십시오.

DHCP에 대한 자세한 내용은 <http://www.microsoft.com/technet/treeview/default.asp?url=/technet/prodtechnol/windows2000serv/reskit/tcpip/part2/tcpch04.asp> ![](images/Dd547911.tous(ko-kr,TechNet.10).gif)를 참고하십시오.

WINS에 대한 자세한 내용은 <http://www.microsoft.com/technet/treeview/default.asp?url=/technet/prodtechnol/windows2000serv/evaluate/featfunc/nt5wins.asp> ![](images/Dd547911.tous(ko-kr,TechNet.10).gif)를 참고하십시오.

Windows Server 2003에 Wins를 설치하는 방법은 <http://support.microsoft.com/default.aspx?scid=323429>에서 "HOWTO: Windows Server 2003 제품군에서 WINS 설치"를 참고하십시오.
[](#mainsection)[페이지 위쪽](#mainsection)
