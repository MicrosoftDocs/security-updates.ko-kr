---
TOCTitle: '계획 설명서 — 무선 LAN 보안을 위한 RADIUS 인프라 디자인'
Title: '계획 설명서 — 무선 LAN 보안을 위한 RADIUS 인프라 디자인'
ms:assetid: 'f3173f46-7234-42e3-a883-4819f7952c93'
ms:contentKeyID: 20214054
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547899(v=TechNet.10)'
---

5장: 무선 LAN 보안을 위한 RADIUS 인프라 디자인
==============================================

게시 날짜: 2004년 11월 20일 | 업데이트 날짜: 2004년 11월 24일

##### 이 페이지의 내용

[](#efaa)[소개](#efaa)
[](#eeaa)[네트워크 액세스 관리에 IAS 사용](#eeaa)
[](#edaa)[솔루션의 전제 조건 확인](#edaa)
[](#ecaa)[RADIUS 인프라 디자인](#ecaa)
[](#ebaa)[관리 계획 작성](#ebaa)
[](#eaaa)[요약](#eaaa)

### 소개

이 장은 이 WLAN(wireless local area network) 솔루션에서 사용하는 RADIUS(Remote Authentication Dial-In User Service) 인프라의 아키텍처 및 디자인을 다룹니다. RADIUS 인프라는 Microsoft RADIUS 구현인 Microsoft® IAS(Internet Authentication Service)를 사용합니다.

이 장의 첫 번째 목적은 솔루션의 IAS 인프라에 관련된 디자인 결정을 다루고 이러한 결정을 하게 된 이유를 논의합니다.

이 장에 "이 솔루션은 옵션 ...를 사용합니다" 또는 "이 디자인은...를 사용합니다" 등의 표현이 나타나면 이는 솔루션 설명서 뒷부분인 구축 및 운영 장에서 구현한, 솔루션 디자인에 대해 내린 결정을 가리키는 것입니다.

이 장의 두 번째 목표는 디자인이 조직에 적합한지 결정하는 것입니다. 따라서 "이 ...를 결정해야 합니다" 등의 표현이 나오면 이는 사용자의 요구 사항을 기준으로 선택해야 하는 결정 시점을 나타냅니다. 이 결정 시점은 보통 조직의 광범위한 보안 요구에 맞게 솔루션을 확장하는 방법을 논의할 때 발생합니다. 이런 이유로 사용자가 단계의 의미를 이해하고 다른 문서를 참조할 필요가 없도록 하기 위해 주제에 따라 상세한 논의를 하기도 합니다.

#### 장 전제 조건

이 장에 들어가기 전에 RADIUS 개념과 IAS 배포 옵션을 익히는 것이 좋습니다. 이 장 마지막의 "추가 정보" 절에 이 주제에 관한 유용한 참고 자료가 있습니다. 또한 *Microsoft Windows Server*™ *2003 Resource Kit* 및 *Microsoft Windows Server*™ *2003 Deployment Kit*의 IAS 관련 장에서 유용한 정보를 찾을 수 있습니다.

#### 장 개요

이 장은 RADIUS 인프라 디자인을 다루는 여러 주제로 나뉩니다. 이 장의 목표는 다음과 같습니다.

-   IAS를 사용하여 광범위한 네트워크 액세스 관리 솔루션을 제공하는 법의 개요를 설명하고 특히 WLAN에 적용하는 법을 설명합니다.

-   솔루션의 IT 환경 전제 조건을 식별하고 기존 인프라를 논의합니다.

-   IAS 기반 RADIUS 인프라용 아키텍처를 만들 때 직면하는 디자인 결정 사항, 특히 802.1X 기반 무선 네트워킹과 관련된 결정을 상세하게 다룹니다.

-   IAS 서버 인프라를 유지하기 위한 관리 전략을 찾습니다.

-   개념, 제품 상세 정보 및 배포 계획에 관한 자세한 정보의 참고 자료를 제공합니다.

다음 순서도는 장 구성을 보여줍니다.

![](images/Dd547899.05fig5-1(ko-kr,TechNet.10).gif)

**그림 5.1 IAS 인프라 계획**

[](#mainsection)[페이지 위쪽](#mainsection)

### 네트워크 액세스 관리에 IAS 사용

Microsoft Windows Server™ 2003의 인터넷 인증 서비스는 Microsoft가 구현한 RADIUS 서버 및 프록시 서버입니다. IAS는 RADIUS 서버로서 다양한 종류의 네트워크 연결에 대해 중앙 AAA(인증(Authentication), 권한 부여(Authorization) 및 계정(Accounting)을 수행합니다. IAS는 RADIUS 프록시 서버로서 AAA에 대한 RADIUS 요청을 다른 RADIUS 서버로 전달할 수 있습니다. IAS는 Microsoft Windows® 기반 RRAS(라우팅 및 원격 액세스 서비스) 등의 VPN(가상 사설망) 서버 또는 무선 AP(액세스 지점) 및 인증 이더넷 스위치 등의 다른 네트워크 액세스 인프라와 함께 사용할 수 있습니다.

IAS 기반 RADIUS 인프라의 가치를 극대화하려면 네트워크 액세스 관리를 위해 중앙 집중식 서비스를 사용하기 위한 전 회사 차원의 결정이 필요합니다. 여기에는 Microsoft Active Directory® 디렉터리 서비스와 같은 중앙 집중식 계정 데이터베이스 사용 및 IAS 서버에 대한 중앙 집중식 네트워크 액세스 정책 관리가 포함됩니다. 중앙 집중식 관리를 강화하면 배포된 네트워크 액세스 장비에 대한 네트워크 액세스 제어 정보의 유지 관리 비용이 대폭 감소합니다. 또한 중앙 집중식 계정 및 네트워크 액세스 정책을 사용하면 배포된 장비의 구성 및 관리에 관련된 보안 위험을 줄일 수 있습니다.

조직의 현재 및 미래의 요구 사항을 만족시키는 IAS 인프라를 계획하고 배포하려면 신중한 검토가 필요합니다. IAS는 분리된 단일 네트워크 액세스를 제공하기 위한 것이 아닙니다. 대신 IAS는 다양한 네트워크 액세스 시나리오에 전략적인 네트워크 액세스 관리를 제공하도록 배포해야 합니다.

#### 조직 구성 단위 네트워크 액세스 관리 요구 사항 확인

Windows Server 2003 IAS는 다음 내용을 포함하여 수많은 네트워크 액세스 시나리오를 지원합니다.

-   **무선 액세스**. 802.11 기반 WLAN 액세스 제어용 IAS AAA 서비스를 사용하고 키 관리를 제공하도록 802.1X 기능의 무선 액세스 지점을 구성합니다.

-   **유선 액세스**. 802.1X 기능의 이더넷 스위치는 유선 LAN에 대한 포트별 액세스 제어에 IAS AAA 서비스를 사용합니다.

-   **VPN 액세스**. Windows 기반 RRAS 등의 VPN 서버는 키 관리뿐 아니라 회사 네트워크 액세스 제어를 위해 IAS AAA 서비스를 사용합니다.

-   **전화 접속 액세스**. Windows 기반 RRAS 등의 전화 접속 서버는 회사 네트워크의 네트워크 액세스 제어를 위해 IAS AAA를 사용합니다.

-   **이더넷 액세스**. 익스트라넷 액세스 서버는 업무 파트너에게 공유 리소스에 대해 제한적으로 액세스를 허용할 때 IAS AAA 서비스를 사용합니다.

-   **아웃소싱한 회사 네트워크 액세스**. 네트워크 솔루션 공급자는 IAS AAA 서비스를 사용하여 아웃소싱된 네트워크 인프라와 고객의 계정 데이터베이스 및 액세스 제어 정책을 통합합니다. IAS는 고객에게 이 서비스 대금을 청구하는 데 필요한 계정 정보를 제공합니다.

-   **인터넷 액세스**. ISP(인터넷 서비스 공급자)는 IAS AAA 서비스를 사용하여 개별 조직 구성 단위 계정 데이터베이스 및 액세스 제어 정책을 사용하면서 전화 접속 및 고속 인터넷 액세스를 제공합니다. IAS는 이 서비스의 고객에게 청구하는 데 필요한 계정 정보를 제공할 수 있습니다.

IAS에 대한 투자를 극대화하고 IAS 인프라에 대한 변경을 최소화하려면 자신의 조직에 이러한 시나리오가 맞는지 각각 평가해야 합니다. 이 솔루션의 IAS는 무선 네트워크 액세스에만 사용되지만 솔루션을 확장하면 다른 시나리오도 지원할 수 있습니다. 다른 시나리오를 지원하기 위해 RADIUS 인프라를 확장하는 법에 대한 자세한 내용은 3장 "무선 LAN 보안 솔루션 아키텍처"에 나와 있습니다.

#### 무선 네트워크 액세스 관리에 IAS 사용

WLAN은 IEEE(Institute of Electrical and Electronics Engineers) 802.11 표준 등의 산업 표준의 등장으로 점점 확산되는 추세입니다. WLAN을 사용하면 무선 AP에 근접해 있기만 하면 빌딩이나 캠퍼스 주변을 이동할 때 자동으로 네트워크에 연결됩니다.

WLAN이 편리하지만 다음과 같은 보안 위험이 발생할 수 있습니다.

-   호환 가능한 WLAN 어댑터를 사용하는 사람이면 누구나 네트워크에 액세스할 수 있습니다.

-   무선 네트워킹 신호는 전파를 사용하여 정보를 주고 받습니다. 따라서 무선 AP 거리 내에 있는 사람이면 누구나 무선 AP에서 주고 받는 모든 데이터를 감지하고 받을 수 있습니다.

첫 번째 보안 위험을 방지하려면 무선 AP를 RADIUS 클라이언트로 설정한 다음 이 클라이언트가 IAS를 실행하는 중앙 RADIUS 서버에게 액세스 요청 및 계정 메시지를 보내도록 구성할 수 있습니다. 두 번째 보안 위험을 방지하려면 무선 장치 및 무선 AP 간에 전송되는 데이터를 암호화할 수 있습니다.

IAS는 두 가지 방법으로 WLAN 보안을 강화합니다. IEEE 802.1X 무선 AP 및 클라이언트 장치의 RADIUS 서버 역할을 하고 EAP–TLS(확장할 수 있는 인증 프로토콜 – 전송 계층 보안) 프로토콜과 같은 인증서 기반 인증 프로토콜을 사용하여 동적 암호화 키를 제공합니다.

**참고**: 이 설명서 전체에서 무선 AP는 RADIUS 클라이언트로 간주됩니다. 무선 AP만 RADIUS 클라이언트가 되는 것은 아니지만 이 설명서에서는 RADIUS 클라이언트 형식만 다룹니다. 따라서 두 용어는 같은 의미로 사용됩니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 솔루션의 전제 조건 확인

IAS를 사용한 무선 액세스 관리 솔루션을 디자인하려면 먼저 사용 환경에 필요한 전제 조건을 확실히 이해해야 합니다.

#### Active Directory 고려 사항

이 솔루션은 도메인 컨트롤러에 Active Directory를 배포하고 Microsoft Windows 2000 Server 이상을 실행하는 조직을 위한 제품입니다. Windows 2000 기본 모드 이상을 사용하는 도메인에서만 사용할 수 있는 기능이 필요한 여러 RADIUS 디자인 결정이 이루어졌고 다음은 거기에 따른 솔루션 전제 조건입니다. 다음 표는 이 솔루션에 사용되는 일부 기능과 이러한 기능에 대한 지원을 여러 가지 도메인 기능 수준과 함께 보여 줍니다.

**표 5.1 솔루션에 사용되는 Windows 도메인 기능**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >기능</th>
<th style="border:1px solid black;" >Windows Server 2003 기본 모드</th>
<th style="border:1px solid black;" >Windows 2000 기본 모드</th>
<th style="border:1px solid black;" >혼합 모드-또는-Microsoft Windows NT® 4.0</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">유니버설 및 중첩 그룹</td>
<td style="border:1px solid black;">필요함</td>
<td style="border:1px solid black;">필요함</td>
<td style="border:1px solid black;">필요 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">UPN(사용자 이름)</td>
<td style="border:1px solid black;">필요함</td>
<td style="border:1px solid black;">필요함</td>
<td style="border:1px solid black;">필요 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">사용자 계정에 사용할 수 있는 RAP(원격 액세스 정책) 권한을 통해 액세스 제어</td>
<td style="border:1px solid black;">필요함</td>
<td style="border:1px solid black;">필요함</td>
<td style="border:1px solid black;">필요 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">EAP–TLS 지원</td>
<td style="border:1px solid black;">필요함</td>
<td style="border:1px solid black;">필요함</td>
<td style="border:1px solid black;">필요 없음</td>
</tr>
</tbody>
</table>
  
**참고:** 이 솔루션의 인증서 서비스 구현에도 Active Directory에만 해당되는 요구 사항이 있습니다. 자세한 정보는 4장 "공용 키 구조 디자인"을 참조하십시오.
  
필수 사항은 아니지만 이 장을 읽은 후 도메인 컨트롤러에 IAS를 배포하기로 결정할 수 있습니다. 이 솔루션은 Window Server 2003의 IAS를 기반으로 하고 있으므로 대상 도메인 컨트롤러를 이 운영 체제 버전으로 업그레이드해야 합니다. 도메인 컨트롤러를 ISA와 함께 사용하는 방법에 대한 자세한 내용은 이 장 뒷부분에서 다룹니다.
  
#### 기존 RADIUS 인프라
  
이 솔루션은 사용자 환경의 기존 RADIUS 서버와의 통합은 다루지 않습니다. 하지만 기존의 IAS 기반 및 타사 RADIUS 서버를 이 솔루션과 통합할 수 있습니다. 대부분의 경우 WLAN 액세스 관련 기능 때문에 Windows Server 2003 IAS를 사용하려 합니다.
  
Windows RADIUS 서버 이전 버전을 Windows Server 2003으로 업그레이드하여 이 솔루션의 핵심 RADIUS 서버 역할을 하도록 합니다. 또한 기존 RADIUS 서버를 새로운 Windows Server 2003 기반 RADIUS 서버와 연결되는 프록시 RADIUS로 개조할 수 있습니다.
  
기존 RADIUS 인프라를 Windows Server 2003 IAS로 마이그레이션하는 방법에 대한 자세한 계획 지침은 Microsoft 협력업체에 문의하거나 해당 협력업체나 Microsoft 컨설팅 서비스 전문가와 연결해 줄 수 있는 Microsoft 고객 담당자에게 문의하십시오.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### RADIUS 인프라 디자인
  
IAS를 사용하여 802.1X 기반 WLAN 액세스를 지원할 때 수많은 디자인 결정을 해야 합니다. 이 절에서는 몇 가지 결정에 대해 설명하고 이 솔루션에 선택된 옵션을 논의합니다. 각 결정을 사용자 본인의 환경에 어떻게 적용할지의 관점에서 평가하는 것이 좋습니다.
  
#### RADIUS 서버로서 IAS의 역할 결정
  
IAS 서버는 세 가지 개념적인 RADIUS 역할 중 하나로 동작하도록 배포합니다.
  
-   RADIUS 서버
  
-   RADIUS 프록시 서버
  
-   RADIUS 서버 및 프록시 서버
  
    **참고**: 이 설명서 전체에서 RADIUS 서버 및 RADIUS 프록시 서버라는 용어는 이 역할을 수행하도록 구성된 IAS 서버를 설명하는 데 사용됩니다.
  
다음 표는 이러한 역할을 수행하기 위해 구성된 일부 서버 기능을 자세히 설명하고 이러한 기능이 실제 시나리오에서 사용되는 방법을 확인합니다.
  
**표 5.2 IAS RADIUS 역할**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >IAS RADIUS 역할</th>
<th style="border:1px solid black;" >기능</th>
<th style="border:1px solid black;" >시나리오</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">RADIUS 서버</td>
<td style="border:1px solid black;">– Active Directory 또는 기타 권한 있는 데이터 출처에 대해 자격 증명을 직접 대조합니다.<br />
– RAP를 사용하여 네트워크 액세스를 결정합니다.</td>
<td style="border:1px solid black;">모든 네트워크 액세스 관리 시나리오에 필요합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RADIUS 프록시 서버</td>
<td style="border:1px solid black;">– 요청 우선 순위를 기준으로 요청을 라우팅합니다.<br />
– 전송 중 요청의 RADIUS 속성을 수정할 수 있습니다.<br />
– RADIUS 서버 그룹에 전달되는 RADIUS 요청의 로드 균형 조정을 수행합니다.</td>
<td style="border:1px solid black;">– 네트워크 액세스 장비를 공유하는 다중 포리스트 시나리오에 유용합니다.<br />
– 프런트 엔드 및 백 엔드 네트워크 AAA 아키텍처를 배포하는 데 유용합니다.<br />
– 인증을 외부 조직과 연합하는 데 유용합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RADIUS 서버 및 프록시 서버</td>
<td style="border:1px solid black;">이전 두 기능의 조합입니다.</td>
<td style="border:1px solid black;">두 시나리오의 조합입니다.</td>
</tr>
</tbody>
</table>
  
모든 RADIUS 역할이 모든 네트워크 액세스 관리 시나리오에 필요한 것은 아닙니다. 예를 들어 WLAN 액세스 관리는 많은 조직에서 RADIUS 서버 역할만 필요로 합니다. 그러나 조직이 무선 네트워크 인프라를 사용하여 여러 Active Directory 포리스트의 사용자 및 장치에 서비스를 제공할 계획이면 요청을 각 포리스트의 분리된 RADIUS 서버로 라우팅하기 위한 RADIUS 프록시 서버 역할도 필요합니다.
  
단순함 및 비용상의 이유로 이 솔루션은 RADIUS 서버로 구성된 IAS 서버만 다룹니다. IAS를 RADIUS 프록시 서버로 구현하지 않습니다.
  
#### 서버 장애 조치 및 로드 균형 조정 이해
  
RADIUS는 모든 802.1X 기반 WLAN 액세스 관리 솔루션의 중요한 구성 요소입니다. 무선 AP의 IAS 서버 가용성이 최종 사용자의 WLAN 가용성을 결정합니다. 따라서 RADIUS 인프라를 구축할 때는 항상 무선 AP가 둘 이상의 IAS 서버를 사용하도록 만들어야 합니다. 대부분의 현대 무선 AP에는 인증을 위한 두 개의 RADIUS 서버 및 계정 관리를 위한 두 개의 RADIUS 서버를 구성하는 기능이 들어 있습니다. 이렇게 하면 단일 RADIUS 서버의 연결이 끊겨도 WLAN 클라이언트 서비스에 영향을 주지 않습니다.
  
복원성을 위해 여러 서버를 구현할 때 대부분의 조직이 RADIUS 클라이언트로 구성되어 있는 무선 AP의 요청을 RADIUS 서버에 로드 균형 조정하여 요청이 폭주하는 서버가 없도록 하는 기법을 선택하려 합니다.
  
로드 균형 조정 전략을 선택하기 전에 802.1X가 무선 AP 및 RADIUS 서버 사이에 RADIUS 내 EAP(EAP-RADIUS)를 구현한다는 점을 이해해야 합니다. RADIUS는 연결 없는 UDP(사용자 데이터그램 프로토콜)를 사용하지만 EAP는 RADIUS 안을 터널링하는 세션 지향 프로토콜입니다. 이는 사실상 하나의 인증 작업을 구성하는 여러 EAP–RADIUS 패킷이 동일한 RADIUS 서버에 반환되어야 하고 그렇지 않으면 인증이 실패한다는 뜻입니다.
  
다음 표는 RADIUS 클라이언트가 복원성 및 RADIUS 요청의 로드 균형 조정을 위해 여러 대의 RADIUS 서버를 사용하는 몇 가지 옵션을 보여 줍니다.
  
**표 5.3 EAP-RADIUS 장애 조치 및 로드 균형 조정 옵션**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >장애 조치 및 로드 균형 조정 방법</th>
<th style="border:1px solid black;" >장점</th>
<th style="border:1px solid black;" >단점</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">RADIUS 서버 그룹을 사용한 IAS 프록시</td>
<td style="border:1px solid black;">- 장애 조치 및 장애 복구를 사용한 RADIUS 서비스 장애 검색을 수행합니다.<br />
– 트래픽 우선 순위에 따라 트래픽 부하를 분배합니다.<br />
– 로드 균형 조정 시 EAP 세션 상태를 유지합니다.<br />
– 우선 순위 및 가중치 설정에 따라 서버에 구성 가능한 요청을 분배합니다.</td>
<td style="border:1px solid black;">- 추가 IAS 서버가 필요합니다.<br />
– 여전히 AP를 주 및 보조 프록시 RADIUS IP로 구성해야 합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">무선 AP의 주 및 보조 RADIUS 서버 설정</td>
<td style="border:1px solid black;">– 규모가 작은 환경은 구성이 더 단순합니다.<br />
– 무선 AP가 트래픽 실패를 탐지하고 장애 조치를 수행합니다.<br />
– 기본 무선 AP 기능을 사용합니다.</td>
<td style="border:1px solid black;">- 주 및 보조 RADIUS 서버를 선택할 때 신중한 계획 및 모니터링이 필요합니다.<br />
- 많은 무선 AP는 서버 로드 균형 조정에 차질을 유발하는 장애 복구 기능을 지원하지 않습니다.</td>
</tr>
</tbody>
</table>
 

엔터프라이즈 조직 및 대규모 네트워크 서비스 공급자는 RADIUS 클라이언트의 요청을 수락하고 이 로드를 RADIUS 서버로 분산하기 위해 RADIUS 서버 그룹으로 구성할 수 있는 RADIUS 프록시 사용을 고려해야 합니다. 네트워크 트래픽을 RADIUS 서버 그룹의 RADIUS 서버에 분배하는 것은 구성 가능한 수많은 항목을 기반으로 합니다. 이 항목에는 우선 순위와 가중치 외에도 RADIUS 트래픽 형식 및 RADIUS 특성이 포함됩니다. 그런 다음 각 RADIUS 서버 그룹의 RADIUS 서버는 도메인 또는 전체 포리스트 내의 사용자 및 장치에 대해 핵심 인증 및 권한 부여를 수행합니다. 이는 RADIUS 요청을 처리하기 위한 프런트 엔드/백 엔드 아키텍처를 만들고 로드 균형 조정 및 옵션 조정에 최상의 유연성을 제공합니다.

![](images/Dd547899.05fig5-2(ko-kr,TechNet.10).gif)

**그림 5.2 RADIUS 프록시를 사용한 장애 조치 및 로드 균형 조정**

하지만 최신 무선 AP의 간단한 RADIUS 서버 장애 조치 기능도 대부분의 조직에 적합한 수준의 복원성은 제공합니다. 이 기능이 원하는 만큼 정교하지 않다면 이를 RADIUS 프록시 서버 기반 장애 조치 및 로드 균형 조정으로 어렵지 않게 마이그레이션할 수 있습니다. 무선 AP 기반 장애 조치 및 로드 균현 조정 전략의 단점은 무선 AP와 RADIUS 서버 쌍을 만들고 RADIUS 서버의 서비스 부하 분배에 불균형이 생기지 않는지 모니터링하고 필요한 수정 작업을 하는 데 드는 관리 오버헤드입니다. 또 다른 단점은 일부 무선 AP 모델이 장애 복구를 지원하지 않는다는 점입니다. 장애 복구는 보조 RADIUS 서버를 사용하도록 장애 조치된 AP가 지정된 주 RADIUS 서버가 복구되자마자 자동으로 다시 주 서버로 전환하는 것입니다. 장애 복구가 없으면 모든 무선 AP는 보조 RADIUS 서버로 장애 조치되었다가 지정된 주 서버로 다시 돌아오는 데 관리자 개입이 필요합니다.

여러 RADIUS 서버를 로컬로 사용할 수 있는 경우 무선 AP 기반 장애 조치 전략을 사용하여 로드 균형 조정을 수행하려면 다음을 수행합니다.

-   각 위치의 무선 AP 중 절반이 먼저 주 RADIUS 서버를 사용하고 주 서버에 장애가 발생하면 보조 RADIUS 서버를 사용하도록 구성합니다.

-   각 위치의 나머지 무선 AP는 보조 RADIUS 서버를 먼저 사용하고 보조 서버에 장애가 발생하면 주 RADIUS 서버를 사용하도록 구성합니다.

    **참고:** 용어 "주" 및 "보조"는 서버 기능에 차이가 있음을 의미하는 것은 아닙니다. 두 서버는 피어 관계입니다. 여기서 두 용어는 장애 조치를 설명할 때 서버를 구분하기 위해 사용합니다.

    ![](images/Dd547899.05fig5-3(ko-kr,TechNet.10).gif)

    **그림 5.3 무선 AP 기반 장애 조치 및 로드 균형 조정**

지점의 한 RADIUS 서버를 로컬로 사용할 수 있고 원격 RADIUS 서버도 사용할 수 있는 상황에서 무선 AP 기반 장애 조치 전략을 사용하여 로드 균형 조정을 수행하려면 지점 내 모든 무선 AP가 로컬 RADIUS 서버를 주 서버로 사용하도록 구성해야 합니다. 그런 다음 주 서버에 장애가 발생하는 경우 원격 RADIUS 서버를 보조 서버로 사용하도록 구성합니다.

[![](images/Dd547899.05fig5-4(ko-kr,TechNet.10).gif)](https://technet.microsoft.com/ko-kr/dd547899.05fig5-4_big(ko-kr,technet.10).gif)

**그림 5.4 로컬 및 원격 RADIUS 서버를 사용한 무선 AP 기반 장애 조치 및 로드 균현 조정**

지점 시나리오에서 주 RADIUS 서버가 정상 서비스 상태로 돌아오는 경우 무선 AP가 주 RADIUS 서버로의 장애 복구 기능이 있어야 합니다. 그렇지 않으면 RADIUS 서비스를 받기 위한 불필요한 WAN(광역 네트워크) 통과를 막기 위해 수동으로 무선 AP를 재구성해야 합니다.

**참고:** 하드웨어 제품의 장애 복구 지원에 대해서는 하드웨어 제조업체에 문의하십시오.

지점 RADIUS 서버는 옵션입니다. WAN에 중앙 집중식 RADIUS 서버를 사용할 수도 있습니다. 하지만 로컬 RADIUS 서버와 도메인 컨트롤러가 없는 경우 지점의 원격 사용자는 WAN이 실패하면 로컬 WLAN을 액세스할 수 없습니다.

이 솔루션은 무선 AP 기반 서버 장애 조치 및 로드 균형 조정을 위한 수동 구성을 사용하도록 디자인되었습니다. 서버 장애 조치 및 로드 균형 조정을 위해 RADIUS 프록시를 사용하는 RADIUS 인프라를 계획하는 방법에 대한 자세한 내용은 *Microsoft Windows Server* *2003 Deployment Kit*의 "Deploying* *IAS"* *를 참조하십시오. 이 장 마지막에 이 참고 자료의 참조가 나와 있습니다.

#### 로깅 요구 사항 만들기

IAS 서버가 옵션인 두 가지 유형의 정보를 로깅하도록 구성할 수 있습니다.

-   성공 및 거부 인증 이벤트

-   RADIUS 인증 및 계정 정보

WLAN에 액세스하려는 사용자 및 장치에서 생성된 인증 성공 및 거부 이벤트는 기본적으로 IAS가 Windows Server 2003 시스템 이벤트 로그에 기록합니다. 인증 이벤트 로그 정보는 보안 감사 및 경고 목적으로 사용될 수도 있지만 인증 문제를 해결하는 데 가장 유용합니다.

처음에는 **성공** 및 **거부** 이벤트 로깅 옵션을 사용함으로 해야 하지만 시스템이 안정되면 **성공** 옵션을 사용 안 함으로 설정해야 합니다. 이는 성공한 WLAN 액세스 이벤트로 인해 시스템 이벤트 로그가 급속히 채워지고 이 옵션을 사용하는 것이 RADIUS 인증 요청 로깅 옵션을 사용하는 경우 보안상 불필요하기 때문입니다.

기업 수준의 조직은 사용자 지정 스크립트를 사용하여 시스템 이벤트 로그의 IAS 이벤트에 조치를 취할 수 있도록 MOM(Microsoft Operations Manager) 등의 엔터프라이즈 모니터링 도구 사용을 고려해야 합니다. 예를 들어 사용자 지정 MOM 스크립트는 거부된 인증 시도와 관련된 IAS 이벤트 증가를 검색하여 관리자에게 조치를 취하도록 알립니다.

또한 IAS는 인증 및 네트워크 액세스 세션 정보를 RADIUS 요청 로그의 형식으로 저장하는 기능을 제공할 수도 있습니다. 다음과 같은 RADIUS 요청 로그의 정보를 제공하기 위한 옵션을 선별적으로 사용함 또는 사용 안 함으로 설정할 수 있습니다.

-   계정 요청 - 예를 들어 네트워크 액세스 세션의 시작 및 끝을 나타내는 계정 시작 및 중지 메시지입니다.

-   인증 요청 - 예를 들어 인증 시도의 성공 또는 실패를 나타내는 액세스 허용 또는 액세스 거부 메시지입니다.

-   정기 상태 - 예를 들어 일부 네트워크 액세스 장치에서 보내는 중간 계정 요청입니다.

RADIUS 요청 로그는 네트워크 사용량에 따라 고객에게 요금을 청구하는 네트워크 서비스 공급자 등의 조직에 가장 유용합니다. 하지만 보안 모니터링 및 감사에도 RADIUS 요청 로그를 사용할 수 있습니다. 특히 RADIUS 인증 및 계정 로그를 사용하면 보안 감사자가 다음과 같은 사항을 결정할 수 있습니다.

-   WLAN의 무단 인증 시도에 대한 자세한 정보

-   허용된 WLAN 연결 기간

IAS는 텍스트 로그 또는 Microsoft SQL Server™ 2000 데이터베이스에 로깅할 수 있습니다. IAS에서 RADIUS 인증 및 계정 정보의 텍스트 기반 로깅은 기본적으로 비활성화되어 있습니다. RADIUS 텍스트 기반 로깅을 활성화하기 전에 다음을 수행해야 합니다.

-   보안 담당자에게 WLAN 액세스 정보를 추적하기 위한 요구 사항과 필요한 세부 사항을 문의합니다.

-   WLAN 사용자의 로드 균형 조정 중에 RADIUS 텍스트 로깅을 랩 테스트하여 서버 하드웨어 요구 사항(디스크 및 CPU)을 이해합니다. WLAN 액세스는 다른 네트워크 액세스 유형보다 상당히 많은 정보를 생성합니다.

-   RADIUS 요청 정보(인증, 계정 및 정기 상태) 중 필수적인 것과 옵션인 것을 구분합니다. WLAN 액세스는 상당한 양의 정보를 생성하여 디스크 공간을 빠른 속도로 소비할 수 있습니다.

-   RADIUS 요청 로그 정보를 액세스, 저장 및 보관하기 위한 전략을 결정합니다. RADIUS 요청 로그 정보를 각 IAS 서버의 하드 디스크에 텍스트 파일로 또는 SQL Server 데이터베이스로 저장합니다.

RADIUS 계정 로그를 사용해야 하는 기업 수준 조직은 IAS의 SQL Server 로깅 기능 사용을 고려하는 것이 좋습니다. RADIUS 계정 정보를 각 IAS 서버의 SQL Server Desktop Engine(MSDE)에 로깅한 다음 중앙 SQL Server 클러스터에 정보를 복제합니다. 이 전략은 RADIUS 계정 데이터의 중앙화 및 구조화된 저장소를 제공하여 쿼리, 보고 및 보관을 쉽게 합니다. 또한 로컬 MSDE 데이터베이스에 SQL Server 로깅을 수행하면 IAS가 이 정보를 로깅하지 못하게 만드는 네트워크 문제 및 계정 정보에 의존하는 네트워크 액세스 요청이 거부되는 가능성을 없애 줍니다.

SQL Server 2000이 없는 조직 또는 RADIUS 요청 로그의 정기적인 쿼리, 보고 및 보관을 수행할 담당자는 보안 사고 조사를 쉽게 할 수 있도록 이 정보를 기록해야 합니다. 이 솔루션에서 RADIUS 로깅과 관련한 여러 디자인 결정이 이루어졌는데 다음 표에 나와 있습니다. 이 정보를 검토하여 어떤 것이 사용 환경의 요구 사항에 맞는지 결정합니다.

**표 5.4 IAS 로깅 디자인 결정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >IAS 로깅 디자인 결정</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><em>Windows Server</em> <em>2003 Security Guide</em>에 있는 IAS 그룹 정책 템플릿의 시스템 이벤트 로그 크기가 기본값에서 IAS 이벤트를 수용할 수 있을 정도로 증가했습니다.</td>
<td style="border:1px solid black;">RADIUS 인증 요청 로깅을 활성화하지 않으면 시스템 이벤트 로그는 기본 설정에 따라 WLAN 액세스 보안 이벤트의 주 기록이 됩니다. <strong>필요한 경우 이벤트 덮어쓰기</strong> 기본 설정과 같은 설정은 로그가 꽉 차면 감사 데이터를 덮어쓸 수 있기 때문에 신중하게 판단해야 합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">텍스트 파일에 대한 RADIUS 인증 및 계정 요청 로깅이 활성화되었습니다.</td>
<td style="border:1px solid black;">이는 IAS 서버의 CPU 로드 및 디스크 공간이 필요합니다.<br />
IAS는 로깅을 수행할 수 없는 경우 인증 및 계정 요청 허가를 중단합니다. 이런 이유로 DoS(서비스 거부) 공격으로 로그 파일 디스크가 꽉 찰 가능성을 고려해야 합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">이 설명서의 IAS 서버 하드웨어 사양은 별도의 실제 디스크에 로그 파일 디스크 볼륨을 별도로 사용합니다.</td>
<td style="border:1px solid black;">이는 RADIUS 요청 로그 파일의 쓰기 성능이 RADIUS 네트워크 액세스 관리 성능에 미치는 영향을 최소화합니다. 또한 로깅이 디스크 볼륨을 채우는 이벤트는 서버 복구 능력에 영향을 주지 않습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RADIUS 인증 및 계정 항목 옵션은 사용하고 정기 상태 옵션은 사용하지 않았습니다.</td>
<td style="border:1px solid black;">이는 인증 상태 및 세션 기간을 결정하는 데 필요한 필수 정보만 기록하도록 합니다. 로그 파일 요구 사항을 줄이기 위해 정기 상태 옵션은 생략했습니다. 환경에서 사용자 세션 기간 기록이 중요한 경우 정기 상태 로깅 사용을 고려해야 합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RADIUS 인증 및 계정 로그 파일로 ODBC(Open Database Connectivity) 호환 데이터베이스 형식을 선택했습니다.</td>
<td style="border:1px solid black;">이 결정을 통해 관리자는 쉽게 로그 파일을 ODBC 호환 데이터베이스로 가져와 분석할 수 있으며 이 결정은 일반적으로 최적의 결정으로 간주됩니다. 또한 Windows Server 2003 지원 도구의 IASPARSE.EXE를 사용하여 파일을 검색할 수 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">새 로그 파일을 만드는 간격은 <strong>매월</strong>로 설정되어 있습니다.</td>
<td style="border:1px solid black;">적은 수의 로그 파일을 생성하도록 간격을 설정하면 SQL Server 로깅을 사용하지 않는 경우 로그 파일을 데이터베이스에 가져오거나 IASPARSE.exe를 사용하여 로그 파일을 검색하는 일이 수월합니다. 이 옵션은 단일 로그 파일로 하드 디스크가 차는 위험을 고려해야 합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RADIUS 요청 로깅의 옵션은 디스크가 꽉 찰 때 가장 오래된 로그 파일을 삭제하도록 설정되었습니다.</td>
<td style="border:1px solid black;">이 기본 설정의 위험은 로그 파일 디스크가 꽉 차는 경우 보안 정보가 손실될 수 있다는 점입니다. 이 설정은 로그 파일이 꽉 찰 때 IAS 서버가 중단되는 것을 막기 위해 선택했습니다.<br />
보안 로그 유지가 서비스 가용성보다 더 중요하면 이 설정을 사용 안 함으로 설정합니다.</td>
</tr>
</tbody>
</table>
 

#### 서버 중앙 집중화 또는 분산 선택

중앙 집중화되거나 분산된 IAS 서버를 사용하기 위한 결정은 부분적으로 조직의 지리적인 배치와 조직의 IT(정보 기술) 인프라 배포 전략을 기준으로 합니다. 다음 세 가지 IT 인프라 전략 유형 중 조직에 가장 근접한 것을 고려해야 합니다.

-   중앙 집중화된 IT 인프라

-   분산된 IT 인프라

-   혼합형 IT 인프라

현대의 수많은 IT 조직은 보다 적은 수로 보다 나은 결함 복원성(fault-resilient)을 가지고 더욱 중앙 집중화된 IT 인프라 구성 요소를 제공하기 위해 노력합니다. 이 목표를 달성하려면 지점 사용자가 중앙에 위치한 사용자와 같은 수준의 IT 서비스를 받을 수 있도록 고속 및 결함 복원성(fault-resilient) WAN 인프라에 상당한 투자가 필요합니다. 이 전략의 장점 중 하나는 분산 서버 인프라 비용을 네트워크 인프라 및 대역폭으로 전환할 수 있다는 점입니다. 또한 서버 인프라는 숙련된 데이터 센터 운영 및 엔지니어링 담당자와 가장 가까운 곳에 위치하므로 높은 수준의 가용성을 확보할 수 있습니다.

복원성이 뛰어난 고속 WAN을 보유한 조직에서 IAS 서버를 중앙 집중화하면 802.1X WLAN 솔루션 비용을 줄일 수 있습니다. 이 형식의 IT 인프라 전략은 기업 수준 조직의 RADIUS 서버 디자인의 출발점으로 간주해야 합니다. RADIUS 프로토콜은 많은 네트워크 대역을 소모하지 않고 WAN 연결에서 잘 동작합니다. 또한 DHCP(Dynamic Host Configuration Protocol)와 같은 프로토콜에서 802.1X 인증이 완료되기를 기다리다 시간 제한에 걸릴 가능성도 고려해야 합니다. 또한 사용 환경에서 네트워크 액세스를 결정할 때 사용하는 사용자 및 그룹이 있는 도메인 컨트롤러와 IAS 서버 사이의 뛰어난 연결 성능에 핵심적입니다. IAS 서버와 Active Directory 간에 고속 통신을 유지할 수 있도록 802.1X 네트워킹의 많은 잠재적 문제를 피할 수 있습니다.

하지만 일부 IT 조직의 경우 대역, 정교한 네트워크 장비 및 중복 WAN 연결의 비용 때문에 중앙 집중식 IT 인프라 모델을 사용하기 어렵습니다. 이런 조직은 대신 서버 인프라가 지점에 분산되어 있는 분산 IT 인프라 모델을 따릅니다. 이 모델은 WAN 실패가 발생할 경우에도 IT 서비스를 계속할 수 있습니다.

IT 인프라 전략의 세 번째 유형은 조직이 가능하면 IT 인프라를 중앙 집중화하고 필요에 따라 IT 인프라를 분산하도록 선택하는 것입니다. 이 전략을 사용하면 대부분의 IT 인프라를 허브 위치에 그룹화하여 허브 위치 사용자 및 허브에 연결된 지점 사용자에게 서비스를 제공할 수 있습니다. 동시에 이 모델로 서버 인프라를 최종 사용자가 많은 지점에 분산할 수 있습니다. 다음 다이어그램은 그런 혼합형 IT 인프라 조직의 예를 보여 줍니다.

[![](images/Dd547899.05fig5-5(ko-kr,TechNet.10).gif)](https://technet.microsoft.com/ko-kr/dd547899.05fig5-5_big(ko-kr,technet.10).gif)

**그림 5.5 중앙 집중식 및 분산식이 혼재된 혼합형 IT 인프라 조직**

본 설명서의 솔루션은 다음을 제공하여 중앙 집중식, 분산식 및 혼합형 서버 인프라 배포 모델을 수용할 수 있도록 디자인되었습니다.

-   서버 인프라 없는 사무실의 요청 및 로컬 요청에 서비스를 제공할 수 있는 두 대의 RADIUS 서버가 있는 대규모 허브 사무실을 구성하기 위한 지침

-   선택적인 지점 RADIUS 서버가 있는 대규모 지점을 구성하기 위한 지침

    **참고:** 서버 인프라가 없는 소규모 지점의 경우 WLAN 액세스는 WAN 가용성에 따라 결정됩니다.

#### 서버 수 및 위치 결정

최소한 독립 Active Directory 포리스트 각각은 포리스트 사용자 및 장치에 대해 RADIUS 서버로 작동하는 두 대 이상의 IAS 서버를 가지고 있어야 합니다. 이로써 RADIUS 서버 중 한 대를 사용할 수 없을 경우에도 네트워크 액세스 요청을 계속 서비스할 수 있습니다.

많은 사용자가 있는 본사는 두 대 이상의 RADIUS 서버를 설치하는 것이 좋습니다. RADIUS 서버가 있는 여러 허브 간에 고속 대역을 사용할 수 있는 경우 무선 AP는 WAN에 있는 RADIUS 서버로 장애 조치되도록 구성할 수 있습니다. 하지만 WAN으로 RADIUS 서버를 사용할 계획인 경우 RADIUS 서버와 서버가 사용하는 도메인 컨트롤러 간에 적절한 네트워크 링크가 있는지 평가해야 합니다. 또한 무선 AP와 클라이언트 컴퓨터의 시간 제한 값을 테스트해야 하고 AP 매개 변수를 필요에 따라 수정해야 합니다. 마지막으로 포리스트의 루트 도메인에 RADIUS 서버를 위치시켜 Kerberos 작업을 최적화합니다.

도메인 컨트롤러를 설치할 정도의 규모지만 허브에 대해 복원성 있는 WAN 연결이 되지 않는 지점은 한 대의 로컬 RADIUS 서버가 적합합니다. 조직이 WAN 복원성이 없는 경우 WAN에 문제가 발생할 때 무선 사용자가 무선 네트워크에 액세스할 수 없을 때의 비용과 지점 IAS 서버의 초기 및 진행 비용을 비교해야 합니다.

#### 다른 서비스와 IAS를 함께 배치하는 결정

IAS와 Active Directory 도메인 컨트롤러 간에 통신이 과다한 경우 도메인 컨트롤러와 동일한 서버에 IAS를 실행하여 성능을 높일 수 있습니다. 이 방법은 네트워크 통신 관련 지연 문제를 피할 수 있습니다. 하지만 IAS를 도메인 컨트롤러에 함께 배치할 때의 결과에 대해 신중하게 생각해야 합니다. 다음 표는 이러한 고려 사항 중 일부를 자세히 보여 줍니다.

**표 5.5 IAS 및 도메인 컨트롤러 공동 배치 고려 사항**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >IAS 위치</th>
<th style="border:1px solid black;" >장점</th>
<th style="border:1px solid black;" >단점</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">도메인 컨트롤러에 배치</td>
<td style="border:1px solid black;">– 사용자 및 컴퓨터 인증 및 권한 부여의 성능이 높아집니다.
– 서버 하드웨어가 많이 필요하지 않습니다.</td>
<td style="border:1px solid black;">- IAS 관리자와 도메인 관리자를 분리할 수 없습니다.
– 함께 배치한 서비스의 오류 또는 성능 문제를 구분할 수 없습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">도메인 컨트롤러와 분리</td>
<td style="border:1px solid black;">- IAS 관리자와 도메인 관리자를 분리할 수 있습니다.
– IAS 부하 및 작업이 Active Directory 서비스에 영향을 주지 않습니다.</td>
<td style="border:1px solid black;">추가 서버 하드웨어가 필요합니다.</td>
</tr>
</tbody>
</table>
  
Active Directory 도메인 컨트롤러는 매우 신중히 다루어야 하는 중요한 IT 인프라입니다. 많은 엔터프라이즈 조직은 최상의 서비스 안정성을 유지하기 위해 도메인 컨트롤러에 소프트웨어 또는 서비스 추가를 제한하는 정책을 가지고 있습니다.
  
많은 기업 수준의 조직에서 RADIUS 관리자는 Active Directory 관리자와는 별도의 역할이 있습니다. IAS는 Windows 운영 체제의 옵션 구성 요소이므로 IAS 관리를 Windows 로컬 관리자가 담당하는 일과 분리할 수 없습니다. 이런 이유로 도메인 컨트롤러에 IAS를 설치한 경우 IAS 관리자는 도메인 관리자 보안 그룹의 구성원입니다.
  
이 솔루션은 Windows Server 2003 버전 IAS가 필요합니다. 따라서 도메인 컨트롤러를 Windows Server 2003으로 업그레이드해야 합니다(아직 업그레이드하지 않은 경우). Windows 2000 서버를 실행하는 환경에서 도메인 컨트롤러를 Windows Server 2003으로 업그레이드하기 전에 다음 전제 조건을 고려합니다.
  
**표 5.6 Windows Server 2003 도메인 컨트롤러의 전제 조건**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >문제</th>
<th style="border:1px solid black;" >전제 조건</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 도메인 컨트롤러는 기본적으로 SMB(서버 메시지 블록) 서명 및 보안 채널 통신 암호화 또는 서명이 필요합니다. 이 요구 사항은 일부 Windows 기반 클라이언트 초기 버전에서 문제가 발생할 수 있습니다.</td>
<td style="border:1px solid black;">사용 환경의 모든 클라이언트 컴퓨터를 최소한 Active Directory 클라이언트가 포함된 Microsoft Windows® 95 또는 Windows NT 4.0 서비스 팩 4(SP 4) 이상으로 업그레이드합니다.</td>
<td style="border:1px solid black;">이 장 마지막의 추가 정보 절에서 참조하는 자세한 정보는 <em>Windows</em> <em>Server</em> <em>2003 도움말 및 지원 센터</em>를 참조하십시오.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 도메인 컨트롤러는 기본 설정으로 보안 채널 서명 및 암호화가 필요합니다. 이 요구 사항은 SP4 이전의 Windows NT 4.0을 실행하는 도메인에서 서버에 대한 도메인 트러스트에 영향을 줍니다.</td>
<td style="border:1px solid black;">레거시 도메인의 모든 도메인 컨트롤러를 SP4 이상의 Windows NT Server 4.0으로 업그레이드합니다.</td>
<td style="border:1px solid black;">이 장 마지막의 추가 정보 절에서 참조하는 자세한 정보는 <em>Windows Server</em> <em>2003 도움말 및 지원 센터</em>를 참조하십시오.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 도메인 컨트롤러는 설치 전에 Active Directory 포리스트 및 도메인 준비가 필요합니다.</td>
<td style="border:1px solid black;">도메인 컨트롤러를 Windows Server 2003으로 업그레이드하기 전에 ADPrep 유틸리티를 사용하여 새 포리스트를 준비합니다.</td>
<td style="border:1px solid black;">이 작업은 PAS(부분 특성 세트)에 영향을 주지 않으므로 글로벌 카탈로그 서버가 다시 빌드되지 않습니다.</td>
</tr>
</tbody>
</table>
  
이 솔루션은 필요한 경우 도메인 컨트롤러에 IAS와 Active Directory를 함께 배치할 수 있도록 설계되었습니다. 이 솔루션은 허브에서 ISA를 Windows Server 2003 도메인 컨트롤러와 분리하고 지점에서 Windows Server 2003 도메인 컨트롤러와 함께 배치하여 테스트를 마쳤습니다.
  
#### RADIUS 서버 로그 예상
  
IAS는 복잡하지 않은 서버 하드웨어에서 순조롭게 수행되며 추가 하드웨어를 사용하여 확장하거나 RADIUS 서버 그룹을 사용하여 확대할 수 있습니다. 그러나 서비스 가용성에 영향을 줄 수 있는 서버 리소스 제약을 방지하려면 WLAN 클라이언트가 IAS 서버 하드웨어에 가하는 부하를 미리 예상하는 것이 최상입니다.
  
최적의 디자인은 복원성에 필요한 서버 수를 최소한으로 함과 동시에 미래에 확장할 경우를 대비한 여유도 남겨둬야 합니다. 성장에 대비한 여유 공간을 확보하는 것은 무선 AP 기반 로드 균형 조정 모델에 사용할 서버 하드웨어를 선택할 때 특히 중요합니다. 무선 AP 기반 로드 균형 조정에서 RADIUS 프록시 서버 기반 로드 균형 조정으로 이동하면 필요한 서버 수가 두 대에서 다섯 대로 급증합니다(기존 RADIUS 서버가 최대 용량에 도달했다고 가정할 때).
  
IAS 서버 로드 고려 사항은 다음과 같습니다.
  
-   인증 및 계정에 필요한 사용자와 장치 수
  
-   EAP(확장할 수 있는 인증 프로토콜) 종류 및 재인증 빈도 등의 인증 옵션
  
-   로깅 및 IAS 소프트웨어 추적 등의 RADIUS 옵션
  
IAS 서버 부하를 예상하려면 WLAN 액세스가 필요한 사용자 및 장치 수를 예상해야 합니다. 일부 조직은 WLAN 사용을 임원 등 사용자 일부분으로 제한하는 반면 다른 조직은 모든 사용자에게 WLAN 액세스를 제공할 수도 있습니다. 조직이 선택하는 전략과 상관없이 WLAN을 사용하는 모든 사용자 및 장치가 짧은 시간 내에 인증 및 권한 부여를 요구하는 "최악의 경우" 시나리오를 예상해야 합니다. 이렇게 하면 IAS 서버는 사무실의 사용량이 최대인 시간 또는 네트워크 정전 직후와 같이 높은 부하가 발생하는 경우도 수용할 정도로 크기를 조정할 수 있습니다.
  
WLAN 인증 옵션 선택이 IAS 서버 부하에 큰 영향을 줍니다. EAP-TLS 등의 인증서 기반 프로토콜은 초기 로그온에 대해 CPU를 많이 사용하는 공용 키 작업을 수행하지만 후속 로그온에 대해서는 빠른 다시 연결이라는 캐시된 자격 증명 전략을 캐시가 만료될 때까지(기본 8시간) 사용합니다. 무선 클라이언트가 한 IAS 서버의 인증을 받는 AP에서 다른 AIS 서버의 인증을 받는 AP로 전환할 때 언제나 완전한 재인증이 일어납니다(예: 클라이언트가 건물 내에서 이동할 때). 이 로밍 재인증은 각 클라이언트와 IAS 서버 간에 한 번만 발생하며 EAP-TLS를 사용하는 경우 최종 사용자에게 투명합니다.
  
또한 무선 클라이언트는 802.11 WEP 세션 암호화 키를 새로 고치기 위한 방법으로 RADIUS 서버에 재인증을 받아야 할 수도 있습니다. 일부 무선 AP 모델은 RADIUS 서버에서 클라이언트가 주기적인 재인증을 받도록 할 필요 없이 정기적인 WEP 세션 키 새로 고침을 수행하는 기능이 있습니다. 이 형식의 기능은 제조업체별로 고유합니다. WPA(WiFi Protected Access) 표준에는 세션 키를 새로 고치기 위한 재인증 요구를 줄이는 향상된 암호화 및 키 관리 기능이 들어 있습니다.
  
따라서 각 IAS 서버가 얼마나 많은 인증 서비스를 제공할 것인지에 관한 모델을 설계할 때 다음 표의 다양한 형식의 인증을 고려해야 합니다.
  
**표 5.7 EAP–TLS 인증 작업**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >인증 유형</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">초기 컴퓨터 인증</td>
<td style="border:1px solid black;">클라이언트는 IAS에 대해 전체 인증을 수행합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">초기 사용자 인증</td>
<td style="border:1px solid black;">클라이언트는 IAS에 대해 전체 인증을 수행합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">무선 AP 간에 로밍할 때 사용자 재인증</td>
<td style="border:1px solid black;">클라이언트는 일단 각 IAS 서버에 대해 전체 인증을 수행한 후 추가 인증에 대해 빠른 다시 연결을 사용합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">무선 AP 간에 로밍할 때 장치 재인증</td>
<td style="border:1px solid black;">클라이언트는 일단 각 IAS 서버에 대해 전체 인증을 수행한 후 추가 인증에 대해 빠른 다시 연결을 사용합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">정기적인 컴퓨터 재인증</td>
<td style="border:1px solid black;">클라이언트는 IAS에 대해 캐시 인증을 수행합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">정기적인 사용자 재인증</td>
<td style="border:1px solid black;">클라이언트는 IAS에 대해 캐시 인증을 수행합니다.</td>
</tr>
</tbody>
</table>
  
IAS가 서비스할 수 있는 인증 수에 대한 예상은 초당 인증으로 가장 잘 나타낼 수 있습니다. IAS는 Intel Pentium 4.2GHz CPU를 사용하고 Active Directory가 있는 Windows Server 2003을 실행하는 컴퓨터에서 다음 수치를 보였습니다.
  
**중요**: 다음 표의 정보는 어떠한 형태의 보증도 하지 않으며 성능 비교가 아닌 용량 계획을 위한 지침으로만 사용되어야 합니다.
  
**표 5.8 초당 인증**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >인증 유형</th>
<th style="border:1px solid black;" >초당 인증 수</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">새로운 EAP–TLS 인증</td>
<td style="border:1px solid black;">36</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">오프로드 카드 지원이 포함된 새 EAP-TLS 인증</td>
<td style="border:1px solid black;">50</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">빠른 다시 연결을 사용한 인증</td>
<td style="border:1px solid black;">166</td>
</tr>
</tbody>
</table>
  
IAS는 다양한 용량의 RADIUS 요청 정보가 들어 있는 디스크 기반 텍스트 로그를 생성하도록 구성할 수 있습니다. RADIUS 로깅으로 RADIUS 서버에 가해지는 오버헤드 때문에 RADIUS 로그를 저장하기 위한 고성능 디스크 사용 계획을 세워야 합니다. 디스크 하위 시스템 속도가 느리면 무선 AP에 대한 IAS RADIUS 응답을 지연시켜 프로토콜 시간 제한에 도달하거나 무선 AP가 불필요하게 보조 RADIUS 서버로 장애 조치되는 일이 발생합니다.
  
또한 Windows  2003 Server 소프트웨어 추적 기능을 사용하면 IAS 서버에 추가로 부하를 주게 됩니다. 그러나 이 기능은 종종 네트워크 액세스 문제를 해결하는 데 필요할 수 있습니다. 이런 이유로 지속적으로 프로덕션 부하를 처리하면서 제한된 시간 동안 추적 기능을 사용하면서 실행할 수 있는 용량이 되도록 IAS 서버를 확장합니다.
  
#### 서버 하드웨어 요구 사항 예상
  
[Windows Server 2003 HCL(하드웨어 호환성 목록)](http://www.microsoft.com/hwdq/hcl/scnet.asp)에서 IAS의 서버 하드웨어를 선택합니다. Windows Server 2003 HCL에서 서버 하드웨어를 선택하면 테스트되지 않은 하드웨어 및 장치 드라이버로 인해 발생할 수 있는 안정성 및 호환성 문제를 피할 수 있습니다.
  
IAS 서버가 Windows Server 2003 권장 하드웨어 요구 사항을 만족하는지 확인합니다. Active Directory 등 시스템에서 실행할 수 있는 다른 서비스도 고려해야 합니다. 예상 서버당 인증 부하를 두 배로 늘이기 위한 IAS 서버 하드웨어 사용 확장을 고려합니다. 서버 용량을 이런 식으로 확장하면 해당 서버 리소스를 서버 장애 조치 시나리오 및 예기치 못한 네트워크 상태를 처리하는 데 이용할 수 있습니다.
  
다음 그림은 가상의 회사인 Woodgrove 은행의 서버 레이아웃을 사용하여 IAS-기반 RADIUS 서버 디자인의 예를 보여 줍니다. 그림은 Woodgrove 은행의 예상 사용자 분포 및 부하에 따른 IAS 서버의 위치 및 수를 표시합니다. 하지만 본 설명서에서는 이 인프라의 일부만 테스트했습니다(런던 허브 및 요하네스버그 지점 사용).
  
**참고:** Woodgrove 은행은 중대형 조직을 대표하는 가상의 회사입니다. 이 은행의 네트워크 아키텍처 및 특성은 이 솔루션 구현의 다양한 디자인 결정의 토대로 사용되었습니다.
  
[![](images/Dd547899.05fig5-6(ko-kr,TechNet.10).gif)](https://technet.microsoft.com/ko-kr/dd547899.05fig5-6_big(ko-kr,technet.10).gif)
  
**그림 5.6 Woodgrove 은행의 사용자, 무선 AP 및 IAS 서버 배포**
  
이 솔루션은 6,742명의 사용자가 있는 본사에 두 대의 RADIUS 서버가 있는 경우를 기준으로 디자인되었습니다. 사용자 중 50퍼센트만 무선을 사용할 수 있으므로 로드 부하가 최대인 동안에는 3,371명의 사용자와 이들에게 할당된 3,371개의 장치가 EAP-TLS를 사용하여 두 대의 RADIUS 서버에 인증할 수 있습니다. 각 서버는 최대 로그온 기간 30분 동안 3,371 인증 서비스를 하도록 확장됩니다. 로그온이 최고조에 달하는 기간의 부하는 서버 장애 조치 시 초당 네 개의 새로운 인증을 수행할 수 있는 용량일 때 대략 초당 두 개의 새로운 EAP–TLS 인증을 수행하는 것과 같습니다.
  
서버는 RADIUS 인증 및 계정 요청을 텍스트 파일에 로깅하도록 구성되었습니다. 이 서버는 RADIUS 전용 서버입니다. 도메인 컨트롤러 서비스는 다른 서버에 있습니다.  의도적으로 RADIUS 서버 하드웨어 사양에 초과 용량을 구현하여 VPN, 유선 네트워크 및 전화 접속 액세스 등의 응용 프로그램의 향후 네트워크 액세스 제어 요구 사항을  수용하도록 했습니다.
  
다음 표는 솔루션 테스트 중에 사용된 IAS 서버 하드웨어를 상세하게 소개합니다.
  
**표 5.9. 테스트한 서버 하드웨어**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >리소스</th>
<th style="border:1px solid black;" >구성</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">CPU</td>
<td style="border:1px solid black;">듀얼 CPU Pentium III 850 MHz</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RAM</td>
<td style="border:1px solid black;">512MB(메가바이트)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">NIC(네트워크 인터페이스 카드)</td>
<td style="border:1px solid black;">복원성을 위해 팀으로 구성된 두 개의 NIC</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">하드 디스크</td>
<td style="border:1px solid black;">– 운영 체제용 RAID – 1 구성(볼륨 C)의 9GB 하드 디스크 2대<br />
– 로그 파일 및 구성 데이터용 RAID – 1 구성(볼륨 D)의 18GB 하드 디스크 2대</td>
</tr>
</tbody>
</table>
 

IAS 서버의 하드웨어 요구 사항은 다를 가능성이 큽니다. 조직의 특정 변수를 기준으로 요구 사항을 평가합니다.

#### 서버 소프트웨어 요구 사항 결정

해당 환경의 IAS 서버에 Windows Server 2003 Standard Edition 또는 Enterprise Edition이 필요한지 결정해야 합니다. Windows Server 2003 Standard Edition은 50대의 RADIUS 클라이언트(예: 무선 AP) 및 2대의 서버 라우팅 그룹만 지원할 수 있습니다.

이 솔루…˜은 허브 사무실 RADIUS 서버에 대해서는 Windows Server 2003 Enterprise Edition으로 테스트했고 지점 RADIUS 서버에 대해서는 Windows Server 2003 Standard Edition으로 테스트했습니다. 하지만 솔루션은 앞에서 언급한 두 소프트웨어 버전의 제한점에도 불구하고 똑같이 잘 작동합니다.

조직 기준에 따라 사용 환경에 필요한 다른 소프트웨어 구성 요소가 있으며 그 예는 다음과 같습니다.

-   백업 에이전트

-   MOM 또는 Microsoft SMS(Systems Management Server) 클라이언트 구성 요소 등의 관리 에이전트

-   바이러스 백신 소프트웨어

-   침입 감지 에이전트

[](#mainsection)[페이지 위쪽](#mainsection)

### 관리 계획 작성

IAS 기반 RADIUS 서버는 지속적인 서비스 가용성 및 네트워크 보안에 대한 진행 유지 관리가 비교적 덜 필요합니다. 하지만 WLAN 프로젝트를 시작할 때 IAS 관리 전략을 결정하여 담당 직원이 RADIUS 인프라 관리에 필요한 교육을 받고 준비하도록 합니다.

#### 관리 변경 및 구성

IAS 서버의 알려진 상태를 유지하는 것은 서비스 가용성 및 네트워크 보안을 유지하는 데 필수적입니다. IAS는 기본적으로 **netsh** 명령을 통해 다양한 서버 구성 요소의 트랜잭션 변경을 쉽게 수행할 수 있습니다. 따라서 변경으로 인해 예상치 못한 동작이 발생하는 경우 쉽게 롤백할 수 있습니다.

**netsh** 명령으로 IAS 구성 전부 또는 일부를 텍스트 파일에 내보내고 가져올 수 있습니다. 이 파일을 사용하여 IAS 서버 간에 설정을 복제합니다. 이 기능으로 대규모 환경에서 구성 변경을 빨리 배포할 수 있습니다.

해당 변경 및 구성 관리에 필요한 작업이 12장 "RADIUS 및 무선 LAN 보안 인프라 관리"에 나와 있습니다.

#### 서비스 복구 계획

재해가 발생할 때 RADIUS 서비스를 빠르게 복구하려면 문제가 발생하기 전에 철저한 계획을 세워야 합니다. 이 설명서와 함께 제공되는 설치 스크립트를 사용하여 IAS의 설치 및 구성을 단순화하고 **netsh** 스크립트를 사용하여 IAS 구성 상태를 신속하게 복구하는 데 필요한 단계를 쉽게 자동화할 수 있습니다. 서비스 복구 작업에 관한 자세한 정보는 12장 ""RADIUS 및 무선 LAN 보안 인프라 관리"를 참조하십시오.

#### 관리자 권한 계획

IAS는 Windows Server 2003 운영 체제의 옵션 구성 요소이므로 로컬 서버의 관리 보안 모델 외 별도의 관리 보안 모델이 필요하지 않습니다. IAS 관리를 로컬 서버 관리자로부터 완전히 분리하는 것은 불가능합니다. 사용자 지정 개발 없이 로컬 서버 관리 권한이 있는 계정을 사용하여 IAS 구성을 변경하는 보안 웹 응용 프로그램을 작성하는 등 어느 정도의 분리는 가능합니다.

그러나 필요한 관리 유형과 다양한 IAS 리소스에 대한 액세스 요구 사항을 계획하여 최소 권한 모델을 만드는 작업도 중요합니다. 다음 표는 IAS 서버와 관련된 역할 및 작업 예를 보여 줍니다.

**표 5.10. IAS 역할 설명 및 작업**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >담당자 역할</th>
<th style="border:1px solid black;" >역할 설명</th>
<th style="border:1px solid black;" >작업</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">IAS Administrators</td>
<td style="border:1px solid black;">이 역할은 IAS 서비스 및 IAS 구성 제어와 같은 일상적인 IAS 관리 작업을 수행합니다.</td>
<td style="border:1px solid black;">IAS 서비스를 시작, 중지, 쿼리 및 구성하고 IAS 구성 데이터베이스를 수정합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS Security Auditors</td>
<td style="border:1px solid black;">이 역할을 가지면 보안 감사자가 관리 권한 없이 보안 정보에 액세스할 수 있습니다.</td>
<td style="border:1px solid black;">RADIUS 계정 및 인증 로그 파일에 보안 이벤트가 있는지 검사합니다.
RADIUS 인증 요청 로그를 사용할 수 없는 경우 IAS 보안 감사자는 시스템 이벤트 로그 항목에 IAS 관련 보안 이벤트가 있는지 검토하고 저장해야 합니다. 이 작업에는 추가 사용 권한이 필요할 수 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS Backup Operators</td>
<td style="border:1px solid black;">이 역할을 가지면 Backup Operator가 IAS 서버의 정기적인 백업을 수행할 수 있습니다. 백업에는 IAS 구성 상태 및 기록 데이터가 들어 있습니다.</td>
<td style="border:1px solid black;">IAS 서버의 매일/매주/매월 백업을 관리합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">WLAN 지원 부서 직원</td>
<td style="border:1px solid black;">사용자가 WLAN 액세스 관련 문제를 해결하도록 지원하는 담당자</td>
<td style="border:1px solid black;">시스템 이벤트 로그에서 사용자 및 장치 인증 관련 IAS 이벤트를 검토하거나 이벤트가 다른 시스템으로 복제될 때 이벤트를 확인합니다.</td>
</tr>
</tbody>
</table>
  
다음 표는 여러 가지 IAS 서버 작업을 수행하는 데 필요한 리소스 사용 권한을 상세하게 소개합니다.
  
**표 5.11 IAS 서버 작업에 필요한 사용 권한**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >작업</th>
<th style="border:1px solid black;" >그룹 구성원</th>
<th style="border:1px solid black;" >필요한 사용 권한 또는 권한</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">IAS 서비스를 중지/시작/쿼리/구성합니다.</td>
<td style="border:1px solid black;">IAS 서버의 로컬 관리자 그룹 구성원인 IAS Admins 도메인 글로벌 그룹</td>
<td style="border:1px solid black;">SC 명령을 사용하여  Windows Server 2003의 서비스 권한을 수정할 수 있습니다. 운영 체제 구성 요소의 기본 사용 권한을 수정하기 전에 Microsoft 고객 지원 담당자에게 문의합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS 구성 수정</td>
<td style="border:1px solid black;">IAS 서버의 로컬 Administrators 그룹의 구성원인 IAS Admins 도메인 글로벌 그룹</td>
<td style="border:1px solid black;">C:\WINDOWS\system32\ias directory에 있는 IAS 데이터베이스 파일 및 <strong>HKLM\System\CurrentControlSet\Services</strong>에 있는 다양한 레지스트리 키에 권한이 필요합니다.
기본적으로 이 권한은 로컬/기본 제공 관리자 보안 그룹의 구성원에게 부여됩니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS 서버에 있는 RADIUS 요청 로그 액세스</td>
<td style="border:1px solid black;">IAS 보안 감사자 도메인 글로벌 그룹</td>
<td style="border:1px solid black;">IAS 감사자는 D:\IASLogs 디렉터리에 있는 RADIUS 요청 로그 파일을 읽고 삭제할 수 있어야 합니다. 이 솔루션의 빌드 지침은 이 디렉터리의 IAS 보안 감사자 보안 그룹에 NTFS 변경 권한을 부여하며 IAS 보안 감사자 보안 그룹에 부여된 변경 공유 권한으로 공유 이름 IASLogs를 만듭니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">시스템 이벤트 로그에서 IAS 보안 이벤트를 읽고 저장합니다.</td>
<td style="border:1px solid black;">IAS 서버의 Local Administrators<br />
또는<br />
Backup Operators</td>
<td style="border:1px solid black;">이 솔루션은 디스크의 텍스트 파일에 대한 RADIUS 인증 로깅을 활성화하는 지침을 제공합니다. 따라서 IAS 감사자는 일반적으로 RADIUS 인증 보안 이벤트의 IAS 시스템 이벤트 로그에 액세스할 필요가 없습니다.<br />
그러나 RADIUS 인증 로깅을 비활성화하는 경우 IAS 보안 감사자는 시스템 이벤트 로그의 IAS 이벤트를 읽고 저장할 수 있어야 합니다. 시스템 이벤트 로그를 보관하려면 Administrator 또는 Backup Operators 구성원이어야 합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS 서버의 매일/매주/매월 백업을 수행합니다.</td>
<td style="border:1px solid black;">Backup Operators</td>
<td style="border:1px solid black;">RADIUS 요청 로그와 같은 IAS 구성 상태 및 기록 데이터를 포함하여 IAS 서버를 백업합니다. Backup Operators 보안 그룹에 등록하면 %systemroot%\system32\ias 디렉터리의 IAS 데이터베이스 파일, <strong>HKLM\System\CurrentControlSet\Services</strong> 아래의 여러 레지스트리 키, D:\IASLogs의 RADIUS 요청 로그 파일 및 D:\IASConfig의 IAS <strong>NETSH</strong> 구성 텍스트 파일에 액세스할 수 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">문제를 해결하기 위해 시스템 이벤트 로그의 IAS 인증 이벤트를 검토합니다.</td>
<td style="border:1px solid black;">시스템 이벤트 로그에 대해 읽기 권한이 있는 그룹 구성원 자격</td>
<td style="border:1px solid black;">수석 문제 해결 담당자는 IAS 인증 거부 이벤트를 보고 해석할 수 있도록 Windows Server 2003 시스템 이벤트 로그에 대해 읽기 권한이 있어야 합니다.</td>
</tr>
</tbody>
</table>
  
#### 보안 모니터링 및 감사
  
IAS는 보안 인프라의 구성 요소이며 사전에 모니터링해야 합니다. 보안 업계 조사에 따르면 일반적으로 성공적인 공격은 수많은 실패 이후 이루어집니다. 네트워크가 공격 받는 경우를 이해하려면 IAS 서버 및 관련 로그의 비정상적인 동작에 대한 사전 보안 모니터링이 필요합니다.
  
다음 표에 IAS 서버 인프라에서 모니터링해야 하는 위협이 나와 있습니다.
  
**표 5.12 IAS 서버 인프라 위협**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >위협/취약점</th>
<th style="border:1px solid black;" >증상</th>
<th style="border:1px solid black;" >모니터링 도구</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">분실하거나 훔친 휴대용 컴퓨터에서 발견한 자격 증명 등을 사용한 권한 부여 시도</td>
<td style="border:1px solid black;">해지된 인증서 사용 시도를 나타내는 시스템 이벤트 로그 또는 RADIUS 인증 요청 로그의 인증 성공/거부 이벤트(원본: IAS, ID 1 및 2)</td>
<td style="border:1px solid black;">– 이벤트 로그 항목에서 해지된 인증서 사용을 구문 분석하도록 작성된 사용자 지정 스크립트가 있는 MOM<br />
– 해지된 인증서 사용을 검색하는 파일 구문 분석 스크립트 또는 SQL Server 도구</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">악의적인 무선 AP를 사용하여 수행되는 중간자(man-in-the-middle) 공격 시도</td>
<td style="border:1px solid black;">IAS 서버에 시스템 모니터 카운터를 사용하여 잘못된 인증자(잘못된 메시지 인증자 특성) 또는 잘못된 요청(알 수 없는 RADIUS 클라이언트 또는 서버로부터 받은)의 과도한 인스턴스 표시</td>
<td style="border:1px solid black;">이러한 시스템 모니터 카운터를 검색하고 경고를 내보내기 위한 사용자 지정 스크립트가 들어 있는 MOM</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS 서버 서비스에 대해 DoS 또는 버퍼 오버플로 시도</td>
<td style="border:1px solid black;">IAS 서버에 시스템 모니터 카운터를 사용하여 손상된 패킷(손상된 데이터가 들어 있는 패킷), 알 수 없는 형식(비 RADIUS 패킷 수신) 또는 손실된 패킷(잘못된 MAC/손상된/알 수 없는 패킷이 아닌 잃어버린 패킷)의 과도한 인스턴스 표시</td>
<td style="border:1px solid black;">이러한 시스템 모니터 카운터를 검색하고 경고를 내보내기 위한 사용자 지정 스크립트가 들어 있는 MOM</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">무단 인증 시도</td>
<td style="border:1px solid black;">시스템 이벤트 로그의 반복되는 인증 실패 이벤트(원본: IAS, ID 2)</td>
<td style="border:1px solid black;">– 이벤트 로그 항목을 구문 분석하여 과도한 인증 거부 패턴을 검색하는 MOM 사용자 지정 스크립트<br />
– 과도한 인증 거부 패턴을 식별하기 위한 파일 구문 분석 스크립트 또는 SQL Server 도구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">훔친 자격 증명을 사용하여 성공한 무단 인증</td>
<td style="border:1px solid black;">RADIUS 계정 로그가 비정상적인 네트워크 동작을 표시합니다.</td>
<td style="border:1px solid black;">– 로그를 가져와 사용자 지정 쿼리를 수행하는 Microsoft Access<br />
– SQL Server 데이터베이스에 저장된 비정상적인 네트워크 액세스 정보를 식별하는 보고서</td>
</tr>
</tbody>
</table>
 

기본 보안 모니터링 외에도 Microsoft는 IAS 서버를 정기적으로 감사하여 잠재적인 보안 문제를 찾고 모니터링 기술을 사용하여 네트워크 인프라에서 발견한 취약점을 분명하게 정의하고 해결할 것을 권장합니다.

다음 표는 IAS 서버 인프라에 대한 잠재적 위협 및 IAS 인프라를 감사하여 보안 문제를 발견하는 데 사용하는 기술을 상세하게 소개합니다.

**표 5.13 사전 감사 대상 IAS 서버 인프라 위협**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >위협/취약점</th>
<th style="border:1px solid black;" >증상</th>
<th style="border:1px solid black;" >감사 도구</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">IAS 구성 및 기록 데이터에 대한 약한 사용 권한</td>
<td style="border:1px solid black;">IAS Admins 그룹, IAS 보안 감사 또는 로컬 관리자 그룹의 허가 받지 않은 구성원</td>
<td style="border:1px solid black;">SomarSoft의 DumpSec 등 Active Directory 및 로컬 보안 그룹 감사 도구</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">실패한 인증 시도를 숨기려는 시도</td>
<td style="border:1px solid black;">시스템 이벤트 로그가 갑자기 삭제됩니다.</td>
<td style="border:1px solid black;">– <em>Windows Server</em> <em>2003 Resource Kit</em>의 EventcombMT 등의 도구를 사용하는 Windows 이벤트 로그 감사
– MOM 등의 이벤트 로그 모니터링 및 경고 도구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RADIUS 계정 감사 및 인증 로그에 대한 무단 수정</td>
<td style="border:1px solid black;">예기치 않은 사용자 ID가 폴더 감사 로그에 쓰기 성공을 표시합니다.</td>
<td style="border:1px solid black;">Windows 파일 감사 및 MOM 등의 모니터링 도구 무단 파일 수정을 찾아내려면 파일 감사를 사용해야 합니다.</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 요약
  
이 장에서는 802.1X 기반 무선 네트워크 보안을 지원하기 위해 RADIUS 인프라를 디자인하는 과정을 다루었습니다. 이 장에서 상세하게 설명한 RADIUS 인프라 디자인은 사용자가 향후 광범위한 요구 사항을 충족하기 위해 확장할 수 있도록 유연합니다. 또한 다른 네트워크 액세스 관리에도 인프라 디자인을 사용할 수 있습니다.
  
이 장에서 설명한 디자인은 뒷장에서 RADIUS 인프라를 구현하는 데 사용됩니다. 다음 장은 일반적인 RADIUS 디자인을 확장하여 WLAN 보안 인프라의 나머지 구성 요소를 구현하는 데 필요한 802.1X 설정 및 WLAN 인프라를 설명합니다.
  
#### 추가 정보
  
IAS에 대한 자세한 내용은 다음을 참조하십시오.
  
-   http://www.microsoft.com/korea/technet/prodtechnol/windowsserver2003/proddocs/  
    entserver/default.mspx의 [Windows Server 2003 지원 센터](http://www.microsoft.com/technet/prodtechnol/windowsserver2003/proddocs/entserver/default.mspx)(영문) 웹 사이트
  
-   제품 설명서에서는 IAS 기능 개요, 기본 구성 지침, 유용한 배포 정보 등을 제공합니다.
  
-   http://www.microsoft.com/windows/reskits/  
    default.asp의 [*Microsoft Windows Server 2003 Technical Reference*](http://www.microsoft.com/windows/reskits/default.asp) (영문) 및 [*Microsoft Windows Server 2003 Deployment Kit*](http://www.microsoft.com/windows/reskits/default.asp) (영문)
  
-   http://www.microsoft.com/resources/documentation/windowsServ/2003/all/  
    techref/en-us/W2K3TR\_ias\_intro.asp의 *Microsoft Windows Server* *2003 Technical Reference*의 "[IAS 기술 참조](http://www.microsoft.com/technet/prodtechnol/windowsserver2003/library/techref/8f5c89d5-fdaf-430c-9ef4-318f8c15baf1.mspx) (영문)"
  
-   IAS 기술 참조는 제품 설명서보다 포괄적인, IAS에 관한 기술 정보를 제공하며 자세한 정보가 필요할 때 이를  참고 자료로 사용할 수 있습니다.
  
-   http://www.microsoft.com/windowsserver2003/techinfo/reskit/deploykit.mspx의 [*Microsoft Windows Server 2003 Deployment Kit*](http://www.microsoft.com/windows/reskits/default.asp) (영문)의 *Deploying Network Services* 설명서의 "Deploying IAS" 장
  
-   이 Depolyment Kit 장은 현재 무선 네트워킹 보안 설명서에는 포함되지 않지만 설계 결정 사항에 영향을 주는, 다양한 시나리오의 IAS 사용을 위한 배포 지침을 제공합니다.
  
802.1X WLAN 기술에 대한 자세한 내용은 다음을 참조하십시오.
  
-   http://www.microsoft.com/korea/technet/prodtechnol/winxppro/maintain/wificomp.mspx의 Microsoft TechNet 백서 "[Windows XP Wireless Deployment Technology and Component Overview](http://www.microsoft.com/technet/prodtechnol/winxppro/maintain/wificomp.mspx) (영문)"
  
[](#mainsection)[페이지 위쪽](#mainsection)