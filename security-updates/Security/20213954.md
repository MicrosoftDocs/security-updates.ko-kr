---
TOCTitle: Windows Server 2003 보안 가이드 개요
Title: Windows Server 2003 보안 가이드 개요
ms:assetid: '9911b568-c474-465f-998f-4f0fa31bebc6'
ms:contentKeyID: 20213954
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc163140(v=TechNet.10)'
---

Windows Server 2003 보안 가이드
===============================

개요

업데이트 날짜: 2005년 12월 27일

업데이트된 Windows Server 2003 보안 가이드는 세 가지 다른 환경에서 Microsoft® Windows Server™ 2003 SP1(서비스 팩 1)이 실행되는 컴퓨터의 보안을 강화하는 방법에 대한 권장 사항을 제공합니다. 여기서 말하는 세 가지 환경은 Windows NT® 4.0 및 Windows® 98과 같은 이전 운영 체제가 지원되어야 하는 환경, Windows 운영 체제가 모두 Windows 2000 버전 이상인 환경, 보안에 대한 필요성이 매우 높아 최대한의 보안을 달성하기 위해 클라이언트 기능이나 관리 효율 등이 상당 부분 손실되는 환경입니다. 이러한 세 가지 환경은 이 가이드 전체에서 각각 LC(레거시 클라이언트), EC(엔터프라이즈 클라이언트) 및 SSLF(특수 보안 - 기능 제한 환경으로 지칭됩니다.

이러한 세 가지 환경에서 컴퓨터의 보안을 강화하는 방법이 개별 서버 역할 그룹에 대해 제공됩니다. 설명된 보안 대책과 제공된 도구는 각 서버가 단일 역할을 갖는다고 가정합니다. 작업 환경의 서버 중 일부에 대한 역할을 조합해야 하는 경우 이 가이드의 다운로드 가능 버전에 포함되어 있는 보안 템플릿을 사용자 지정하여 서비스 및 보안 옵션을 적절히 조합할 수 있습니다. 이 가이드에 설명된 서버 역할에는 다음이 포함됩니다.

-   DNS 서비스를 제공하는 도메인 컨트롤러

-   WINS 및 DHCP 서비스를 제공하는 인프라 서버

-   파일 서버

-   인쇄 서버

-   Microsoft IIS(인터넷 정보 서비스)를 실행하는 웹 서버

-   IAS(인터넷 인증 서비스) 서버

-   인증서 서비스 서버

-   요새 호스트

이 가이드는 사용자가 필요한 정보를 빠르게 찾고 조직의 컴퓨터에 적합한 설정을 쉽게 결정할 수 있도록 체계적이며 찾아보기 쉽게 구성되었습니다. 이 가이드는 엔터프라이즈 고객을 위해 작성되었지만 대부분의 정보는 모든 규모의 조직에 적절합니다.

이 자료를 최대한 활용하려면 전체 가이드를 모두 읽어 보아야 합니다. 또한 관련 가이드인 [위협 및 대책 - Windows Server 2003 및 Windows XP용 보안 설정](http://www.microsoft.com/korea/technet/security/topics/serversecurity/tcg/tcgch00.mspx)을 참조하십시오. 이 가이드는 http://www.microsoft.com/korea/technet/security/topics/serversecurity/tcg/tcgch00.mspx 사이트에서 다운로드할 수 있습니다.

##### 이 페이지에서

[](#eeaa)[이 가이드의 대상](#eeaa)  
[](#edaa)[가이드 개요](#edaa)  
[](#ecaa)[관련 리소스](#ecaa)  
[](#ebaa)[의견 보내기](#ebaa)  
[](#eaaa)[컨설팅 및 지원 서비스](#eaaa)

### 이 가이드의 대상

이 가이드는 주로 Windows Server 2003의 응용 프로그램 또는 인프라의 개발 및 배포의 계획 단계를 담당하는 컨설턴트, 보안 전문가, 시스템 설계자, IT 전문가 등을 대상으로 하며 개인 사용자를 대상으로 하지 않습니다.

보안 전문가와 IT 설계자는 이 가이드에 논의된 보안 설정에 대한 보다 자세한 정보를 원할 수 있습니다. 이러한 추가 정보는 관련 가이드인 [위협 및 대책 - Windows Server 2003 및 Windows XP용 보안 설정](http://www.microsoft.com/korea/technet/security/topics/serversecurity/tcg/tcgch00.mspx)(http://www.microsoft.com/korea/technet/security/topics/serversecurity/tcg/tcgch00.mspx)을 참조하십시오.

[](#mainsection)[페이지 위쪽](#mainsection)

### 가이드 개요

#### 1장: Windows Server 2003 보안 가이드 소개

이 장에서는 Windows Server 2003 보안 가이드의 개요를 제공하며 각 장에 대해 간단히 소개합니다. 또한 레거시 클라이언트, 엔터프라이즈 클라이언트 및 특수 보안 – 기능 제한 환경과 이러한 환경에서 실행되는 컴퓨터에 대해 설명합니다.

#### 2장: Windows Server 2003 보안 강화 메커니즘

이 장에서는 이 가이드에서 Windows Server 2003 SP1의 보안 강화를 위해 사용되는 주요 메커니즘인 SCW(보안 구성 마법사)와 Active Directory 그룹 정책에 대해 간략하게 설명합니다. 또한 SCW가 어떤 방식으로 여러 다른 서버 역할을 제공하는 Windows Server 2003의 보안 정책을 만들고 관리하고 테스트하기 위한 대화형 프레임워크를 제공하는지 설명합니다. 그런 다음 1장에 설명된 세 가지 환경의 컨텍스트 내에서 SCW의 기능을 평가합니다.

이 장의 두 번째 부분에서는 Active Directory 디자인, OU(조직 구성 단위) 디자인, GPO(그룹 정책 개체), 관리 그룹 디자인 및 도메인 정책에 대해 자세히 설명합니다. 이러한 내용은 이상적인 보안 환경에 대한 비전을 제시하기 위해 1장에 설명된 세 가지 환경의 컨텍스트에서 논의됩니다.

마지막으로 이 가이드를 통해 SCW 및 전형적인 GPO 기반 방식의 최상의 기능들을 조합하여 Windows Server 2003 SP1 보안을 강화하는 방법을 자세히 설명합니다.

#### 3장: 도메인 정책

이 장에서는 1장에 설명된 세 가지 환경에서 사용되는 도메인 수준 정책에 대한 보안 템플릿 설정과 추가 대책에 대해 설명합니다. 여기서는 특정 서버 역할을 중점적으로 다루지 않으며 최상위 수준 도메인 정책에 유용한 특정 정책 및 설정에 대해 주로 설명합니다.

#### 4장: 구성원 서버 기준 정책

이 장에서는 가이드 뒷부분에 나오는 서버 역할에 대해 MSBP(구성원 서버 기준 정책)를 설정하는 방법을 중점적으로 소개합니다.

#### 5장: 도메인 컨트롤러 기준 정책

도메인 컨트롤러 서버 역할은 Windows Server 2003 SP1을 실행하는 컴퓨터가 있는 Active Directory 환경에서는 보안 유지에 가장 중요한 역할 중 하나입니다. 도메인 컨트롤러가 없거나 손상되면 인증, 그룹 정책 및 중앙의 LDAP(Lightweight Directory Access Protocol) 디렉터리를 이용하기 위해 도메인 컨트롤러에 의존하는 클라이언트, 서버 및 응용 프로그램 모두에 심각한 영향을 미칠 수 있습니다. 가이드에 정의된 세 가지 환경에서 도메인 컨트롤러는 또한 DNS 서비스를 제공합니다.

#### 6장: 인프라 서버 역할

이 장에서 인프라 서버 역할은 DHCP 또는 WINS 서비스를 제공합니다. 작업 환경의 Windows Server 2003 SP1 인프라 서버에서 MSBP(구성원 서버 기준 정책)를 통해서는 적용할 수 없는 보안 설정을 활용하는 방법을 자세히 설명합니다.

#### 7장: 파일 서버 역할

이 장은 파일 서버의 역할을 하는 컴퓨터의 보안을 강화하는 방법과 이러한 서버의 보안 강화 시 어려운 점에 대해 중점적으로 설명합니다. 파일 서버가 제공하는 필수 서비스 대부분을 사용하려면 Windows NetBIOS 관련 프로토콜과 SMB(서비스 메시지 블록) 및 CIFS(Common Internet File System) 프로토콜이 필요합니다. SMB 및 CIFS 프로토콜은 일반적으로 인증된 사용자에게 액세스 권한을 부여하는 데 사용되지만 보안이 제대로 유지되지 않으면 인증되지 않은 사용자나 공격자에게 중요한 정보를 노출할 수 있습니다. 이와 같은 위협 때문에 이러한 프로토콜은 높은 보안 환경에서는 주로 비활성화됩니다. 이 장에서는 Windows Server 2003 SP1이 실행되는 파일 서버에서 MSBP를 통해서는 적용할 수 없는 보안 설정을 활용하는 방법을 설명합니다.

#### 8장: 인쇄 서버 역할

이 장에서는 인쇄 서버를 중점적으로 소개합니다. 파일 서버와 마찬가지로 인쇄 서버의 필수 서비스 대부분을 사용하려면 Windows NetBIOS 관련 프로토콜과 SMB 및 CIFS 프로토콜이 필요합니다. 앞서 설명한 것처럼 SMB 및 CIFS 프로토콜은 높은 보안 환경에서는 주로 비활성화됩니다. 이 장에서는 MSBP를 통해서는 가능하지 않은 방법으로 Windows Server 2003 SP1 인쇄 서버 보안 설정을 강화하는 방법을 설명합니다.

#### 9장: 웹 서버 역할

이 장에서는 웹 사이트와 응용 프로그램의 전반적인 보안을 위해 IIS 서버에서 실행되는 각 웹 사이트와 응용 프로그램을 포함하는 전체 IIS 서버를 사용자 환경의 클라이언트 컴퓨터로부터 잘 보호해야 하는 이유에 대해 설명합니다. 웹 사이트와 응용 프로그램 또한 동일한 IIS 서버에서 실행되는 다른 웹 사이트와 응용 프로그램으로부터 보호되어야 합니다. 이 장에서는 사용자 환경에서 Windows Server 2003 SP1이 실행되는 IIS 서버를 통해 이러한 보안 대책을 수행하는 방법을 설명합니다.

#### 10장: IAS 서버 역할

IAS(인터넷 인증 서버)는 네트워크에 원격으로 액세스하는 클라이언트를 식별하도록 디자인된 표준 기반 인증 프로토콜인 RADIUS(Remote Authentication Dial-In User Service)를 제공합니다. 이 장에서는 Windows Server 2003 SP1이 실행되는 IAS 서버에서 MSBP를 통해서는 적용할 수 없는 보안 설정을 활용하는 방법을 설명합니다.

#### 11장: 인증서 서비스 서버 역할

인증서 서비스는 사용자 서버 환경에서 PKI(공개 키 구조)를 만드는 데 필요한 암호화 및 인증서 관리 서비스를 제공합니다. 이 장에서는 Windows Server 2003 SP1이 실행되는 인증서 서비스 서버에서 MSBP를 통해서는 적용할 수 없는 보안 설정을 활용하는 방법을 설명합니다.

#### 12장: 요새 호스트 역할

인터넷의 클라이언트 컴퓨터에서는 요새 호스트 서버에 액세스할 수 있습니다. 이 장에서 대중에게 노출된 이러한 시스템이 대부분의 경우 완전히 익명을 가장한 많은 사용자로부터 얼마나 쉽게 공격을 받을 수 있는지에 대해 설명합니다. 많은 조직에서는 도메인 인프라를 인터넷으로 확장하지 않으므로 이 장에서는 Windows Server 2003 SP1이 실행되지만 Active Directory 기반 도메인에 속하지 않는 독립 실행형 컴퓨터의 보안을 강화하는 방법을 중점적으로 소개합니다.

#### 13장: 결론

이 가이드의 결론 장에서는 이전 장에서 소개된 내용들은 간단히 요약해서 설명합니다.

#### 부록 A: 보안 도구 및 형식

Windows Server 2003 보안 가이드에서는 SCW를 사용하여 정책을 만든 후 보안 템플릿 및 그룹 정책 개체로 변환하는 방법을 중점적으로 다루고 있지만 이 방법을 확장하거나 대체하는 데 사용할 수 있는 다양한 도구 및 데이터 형식이 있습니다. 이 부록에서는 이러한 도구 및 형식을 간단한 목록으로 제공합니다.

#### 부록 B: 고려해야 할 중요한 설정

Windows Server 2003 보안 가이드에서는 여러 가지 보안 대책과 보안 설정을 다루지만 몇 가지 핵심 사항이 특히 중요하다는 사실을 이해해야 합니다. 이 부록에서는 Windows Server 2003 SP1이 실행되는 컴퓨터의 보안에 가장 큰 영향을 주는 설정에 대해 설명합니다.

#### 부록 C: 보안 템플릿 설정 요약

이 부록에서는 Microsoft Excel® 스프레드시트 "[Windows Server 2003 Security Guide Settings (영문)](http://go.microsoft.com/fwlink/?linkid=14846)"를 소개합니다. 이 통합 문서는 http://go.microsoft.com/fwlink/?LinkId=14846 사이트에 제공되는 이 가이드의 [다운로드 가능 버전 (영문)](http://go.microsoft.com/fwlink/?linkid=14846)에 도구 및 템플릿과 함께 제공됩니다. 이 스프레드시트는 포괄적인 마스터 참조서로, 이 가이드에 정의된 세 가지 환경에 권장되는 모든 설정을 편리하고 간단한 형식으로 보여 줍니다.

#### 부록 D: Windows Server 2003 보안 가이드 테스트

Windows Server 2003 보안 가이드에는 Windows Server 2003 SP1 실행 서버의 보안을 강화하는 방법에 대한 방대한 정보가 포함되어 있지만 가이드 사용자는 모든 설정을 주의해서 테스트 및 검사한 후에 프로덕션 환경에서 구현하도록 해야 합니다.

이 부록은 프로덕션 환경에서 권장 설정을 성공적으로 구현하기 위해 활용할 수 있는 적절한 테스트 랩 환경을 만드는 방법을 설명합니다. 또한 필요한 검사를 수행하고 이러한 작업에 필요한 리소스 양을 최소화하는 데 도움이 되는 정보도 제공합니다.

#### 도구 및 템플릿

이 가이드에는 조직에서 권장 대책을 보다 쉽게 평가, 테스트 및 구현할 수 있도록 하기 위한 보안 템플릿, 스크립트 및 추가 파일 모음이 포함되어 있습니다. 보안 템플릿은 도메인 기반 그룹 정책으로 가져올 수 있거나 MMC(Microsoft Management Console) 보안 구성 및 분석 스냅인을 사용하여 로컬로 적용할 수 있는 텍스트 파일입니다. 이러한 절차는 2장 "Windows Server 2003 보안 강화 메커니즘"에 자세히 설명되어 있습니다. 이 가이드에는 그룹 정책 개체를 만들어 연결하기 위한 스크립트와 권장 대책을 테스트하는 데 사용되는 테스트 스크립트가 포함되어 있습니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 관련 리소스

이 가이드에 설명된 보안 설정에 대한 자세한 내용은 관련 가이드 [위협 및 대책 - Windows Server 2003 및 Windows XP용 보안 설정 (영문)](http://go.microsoft.com/fwlink/?linkid=15160)(http://go.microsoft.com/fwlink/?LinkId=15160)과 [Windows XP 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=14840)(http://go.microsoft.com/fwlink/?LinkId=14840)를 참조하십시오. MSSC(Microsoft Solutions for Security and Compliance) 팀에서 제공하는 [기타 보안 솔루션 (영문)](http://www.microsoft.com/technet/community/columns/sectip/st0805.mspx)은 www.microsoft.com/technet/community/columns/sectip/st0805.mspx 사이트에서 사용할 수 있습니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 의견 보내기

MSSC(Microsoft Solutions for Security and Compliance) 팀에서는 이 가이드 및 기타 보안 솔루션에 대한 여러분의 의견을 기다립니다.

의견이 있으면 [IT 전문가를 위한 보안 솔루션 블로그 (영문)](http://blogs.technet.com/secguide)에 올려 주십시오.

메일 주소 [SecWish@microsoft.com](mailto:secwish@microsoft.com?subject=windows%20server%202003%20security%20guide)으로 의견을 보내주셔도 됩니다. 성심 성의껏 답변해 드리겠습니다.

Microsoft는 여러분의 의견을 기다리고 있습니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 컨설팅 및 지원 서비스

조직의 보안 노력을 지원하는 여러 가지 서비스가 제공되고 있습니다. 귀사에 필요한 서비스를 알아보려면 다음 링크를 사용하십시오.

Microsoft Gold Certified Partners, Microsoft Certified Technical Education Centers, Microsoft Certified Partners 및 Microsoft 기술을 사용하여 ISV(Independent Software Vendor)에서 배포한 제품에 대해서는 [Microsoft 리소스 디렉터리](http://go.microsoft.com/fwlink/?linkid=43094)(http://go.microsoft.com/fwlink/?LinkId=43094)를 검색하십시오.

조직의 요건에 적합한 컨설팅 및 지원 서비스를 찾으려면 [Microsoft Services](http://support.microsoft.com/msservices)(http://support.microsoft.com/msservices)를 방문하십시오.

**다운로드**

[Windows Server 2003 보안 가이드 받기 (영문)](http://go.microsoft.com/fwlink/?linkid=14846)

**업데이트 알림**

[업데이트 및 최신 릴리스 정보 수신 등록 (영문)](http://go.microsoft.com/fwlink/?linkid=54982)

**사용자 의견 보내기**

[의견 및 제안 보내기](mailto:secwish@microsoft.com?subject=windows%20server%202003%20security%20guide)

[](#mainsection)[페이지 위쪽](#mainsection)
