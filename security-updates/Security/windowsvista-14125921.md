---
TOCTitle: Windows Vista 보안 가이드 개요
Title: Windows Vista 보안 가이드 개요
ms:assetid: '4d8207c2-c2a2-4503-b602-b1dba08fe8c4'
ms:contentKeyID: 14125921
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Bb629420(v=MSDN.10)'
---

Windows Vista 보안 가이드
=========================

### 개요

게시 날짜: 2006년 11월 8일

*Windows Vista 보안 가이드*에 오신 것을 환영합니다. 이 가이드에서는 Active Directory® 디렉터리 서비스를 사용하는 도메인에서 Windows Vista™가 실행되는 데스크톱 및 랩톱 컴퓨터의 보안을 강화하는 데 도움이 되는 지침과 권장 사항을 설명합니다.

*Windows Vista 보안 가이드*에서는 보안 문제와 관련된 솔루션 이외에도 배포 프로세스를 크게 간소화할 수 있는 방법, 권장 사항, 단계별 절차, 도구 등도 설명합니다. 이 가이드에서는 효과적인 보안 설정 지침을 제공할 뿐만 아니라 테스트 환경과 프로덕션 환경 모두에 지침을 적용하는 데 사용할 수 있는 정형화된 방법도 제공합니다.

*Windows Vista 보안 가이드*에서 제공하는 주요 도구로는 GPOAccelerator.wsf 스크립트가 있습니다. 이 도구를 사용하여 스크립트를 실행하면 이 보안 지침을 적용하는 데 필요한 모든 GPO(그룹 정책 개체)를 자동으로 만들 수 있습니다. 이 가이드와 함께 제공되는 Windows Vista Security Guide Settings.xls 파일에서는 설정 값을 비교하는 데 사용할 수 있는 다른 리소스를 제공합니다.

Microsoft 엔지니어 팀, 컨설턴트, 지원 엔지니어, 파트너 업체 및 고객들은 다음과 같은 면에서 이 규범적 지침을 검토하고 승인했습니다.

-   **검증**. 현장 경험을 기반으로 검증되었습니다.

-   **신뢰성**. 적용 가능한 최상의 조언을 제공합니다.

-   **정확성**. 기술적인 검증과 테스트를 거쳤습니다.

-   **실용성**. 성공적인 작업 수행을 위한 단계를 제공합니다.

-   **적합성**. 실제 보안 문제를 해결해줍니다.

컨설턴트와 시스템 엔지니어는 다양한 환경에서 Windows Vista, Microsoft® Windows® XP Professional, Windows Server® 2003 및 Windows 2000을 구현하기 위한 최상의 방법을 개발합니다. 자신의 환경을 대상으로 Windows Vista를 평가하려는 경우 [Windows VRA(Vista Readiness Assessment) (영문)](http://go.microsoft.com/fwlink/?linkid=74708)를 사용하면 중간 규모의 조직에서 컴퓨터가 Windows Vista 운영 체제를 실행할 준비가 되어 있는지 손쉽게 확인할 수 있습니다. VRA를 사용하면 컴퓨터 목록을 작성하고, 지원되는 Windows Vista 사용 환경을 확인하고, 필요한 경우 특정 하드웨어의 업그레이드를 제안하는 등과 같은 작업을 신속하게 수행할 수 있습니다.

Microsoft에서는 Windows XP SP1(서비스 팩 1)과 Windows XP SP2 모두에 대한 가이드를 발행했습니다. 여기서는 Windows Vista의 중요한 보안 강화 기능을 설명하면서 이들 가이드를 참조하기도 합니다. 이 가이드는 독립 실행형 컴퓨터로 사용되는 경우뿐 아니라 Active Directory를 사용하는 도메인에 가입한 Windows Vista 컴퓨터를 대상으로 개발 및 테스트를 마쳤습니다.

**참고**   이 가이드에 언급된 Windows XP는 별도의 설명이 없는 한 모두 Windows XP SP2를 가리킵니다.

##### 이 페이지에서

[](#egaa)[요약](#egaa)  
[](#efaa)[이 가이드의 대상](#efaa)  
[](#eeaa)[각 장의 내용 요약](#eeaa)  
[](#edaa)[지침 및 도구](#edaa)  
[](#ecaa)[스타일 규칙](#ecaa)  
[](#ebaa)[추가 정보](#ebaa)  
[](#eaaa)[감사의 말](#eaaa)

### 요약

보안은 어떤 환경에서건 진지하게 다뤄야 할 문제입니다. IT(정보 기술)의 가치를 저평가하는 조직이 많습니다. 조직의 서버에 심각한 공격이 가해지면 전체 조직이 엄청난 타격을 받을 수 있습니다. 예를 들어, 네트워크의 클라이언트 컴퓨터가 악성 프로그램에 감염되면 조직의 데이터 자산을 잃을 수도 있고, 이를 안전한 상태로 되돌리는 데 많은 추가 비용을 부담해야 할 수도 있습니다. 웹 사이트가 공격을 받아 사용할 수 없는 지경에 이르면 수익이 크게 감소할 수도 있고 고객의 신뢰를 잃을 수도 있습니다.

보안과 관련된 취약성, 위험 및 노출을 분석하면 네트워킹 환경의 모든 컴퓨터 시스템에 적용되는 보안과 기능 사이에서 균형을 유지할 수 있습니다. 이 가이드에서는 Windows Vista에 사용할 수 있는 보안 관련 주요 대응책, 이러한 대응책을 통해 해결할 수 있는 보안 취약점, 각 대응책을 구현하는 과정에서 부정적인 결과가 발생할 수 있는 경우 대응책에 수반하는 그와 같은 결과에 대해 설명합니다.

이 가이드는 Windows XP SP2가 실행되는 컴퓨터를 강화하기 위해 권장되는 방법을 설명하는 [*Windows XP 보안 가이드*](http://www.microsoft.com/korea/technet/security/guidance/secmod60.asp)를 기초로 작성되었습니다. *Windows Vista 보안 가이드*에서는 다음과 같은 두 가지 환경에서 특정 보안 기준을 사용하여 컴퓨터를 강화하기 위해 권장되는 방법을 제공합니다.

-   **EC(엔터프라이즈 클라이언트)**. 이 환경에서는 Active Directory를 사용하는 도메인에 클라이언트 컴퓨터가 배치되며 이러한 클라이언트 컴퓨터는 Windows Server 2003이 실행되는 시스템과만 통신하면 됩니다. 이 환경의 클라이언트 컴퓨터는 운영 체제가 혼합되어 있을 수도 있습니다. 즉, 일부 컴퓨터에서는 Windows Vista를 사용하는 반면 나머지 컴퓨터에서는 Windows XP를 실행할 수도 있습니다. EC 환경을 테스트하고 배포하는 방법에 대한 지침은 1장, "기본 보안 구현"을 참조하십시오. 이 환경에서 사용하는 기본 보안 설정에 대한 자세한 내용은 부록 A, "보안 그룹 정책 설정"을 참조하십시오.

-   **SSLF(특수 보안 - 기능 제한)**. 이 환경에서는 보안이 매우 중요하므로 기능 및 관리 효율성 측면을 상당 부분 포기해야 합니다. 예를 들어, 군 기관 및 정보 기관의 컴퓨터는 이러한 유형의 환경에서 사용됩니다. 이 환경의 클라이언트 컴퓨터에서는 Windows Vista만 사용합니다. SSLF 환경을 테스트하고 배포하는 방법에 대한 지침은 5장, "특수 보안 - 기능 제한"을 참조하십시오. 이 환경에서 사용하는 SSLF 설정에 대한 자세한 내용은 부록 A, "보안 그룹 정책 설정"을 참조하십시오.

    ![](images/bb629420.warning(ko-kr,MSDN.10).gif)**경고:**

    대부분의 엔터프라이즈 조직에서는 SSLF 보안 설정을 사용할 필요가 없습니다. 이러한 설정의 구성은 기능보다 보안이 더 중요한 조직을 위해 개발된 것입니다.

이 가이드는 필요한 정보를 쉽게 찾을 수 있도록 구성되어 있습니다. 이 가이드와 관련 도구를 통해 다음과 같은 도움을 얻을 수 있습니다.

-   네트워크 환경에 두 가지 보안 기준 중 하나를 배포하고 적용합니다.

-   일반적인 보안 시나리오에 적용되는 Windows Vista 보안 기능을 확인하고 사용합니다.

-   기본 보안 각각의 개별 설정이 무엇을 목적으로 하는지 확인하고 그 중요성을 이해합니다.

이 가이드는 엔터프라이즈 고객을 위해 작성된 것이지만 대부분의 지침은 그 규모와 상관없이 거의 모든 조직에 적용할 수 있습니다. 이 자료를 최대한 활용하려면 가이드 전체를 읽어 보아야 합니다. 그러나 구체적인 필요에 따라 가이드의 특정 부분만 읽을 수도 있습니다. 이 개요의 "각 장의 내용 요약" 섹션에서는 가이드의 내용을 간략하게 소개합니다. Windows XP와 관련된 보안 항목 및 설정에 대한 자세한 내용은 [*Windows XP 보안 가이드*](http://www.microsoft.com/korea/technet/security/guidance/secmod60.asp) 및 이와 함께 제공되는 [*위협 및 대책 (영문)*](http://go.microsoft.com/fwlink/?linkid=15159) 가이드를 참조하십시오.

[](#mainsection)[페이지 위쪽](#mainsection)

### 이 가이드의 대상

*Windows* *Vista 보안 가이드*는 주로 IT 관련 종사자, 보안 전문가, 네트워크 설계자를 비롯하여 엔터프라이즈 환경에서 데스크톱 및 랩톱 클라이언트 컴퓨터에 대한 Windows Vista의 응용 프로그램 또는 인프라 개발과 배포를 계획하고 있는 기타 IT 전문가 및 컨설턴트를 위한 것입니다. 이 가이드는 개인 사용자를 대상으로 하지 않습니다. 이 가이드의 대상이 되는 사용자의 작업 역할을 구체적으로 살펴보면 다음과 같습니다.

-   **IT** **관련 종사자**. 이 역할을 맡은 사용자들은 클라이언트 컴퓨터가 50대에서 500대 정도의 규모인 조직에서 모든 수준의 보안 업무를 처리합니다. IT 관련 종사자는 주로 자신이 관리하는 컴퓨터의 보안을 빠르고 간편하게 설정하는 데 초점을 맞춥니다.

-   **보안** **전문가**. 이 역할을 맡은 사용자들은 조직 내의 컴퓨팅 플랫폼 간에 보안을 어떻게 적용할지에 주된 관심을 갖습니다. 보안 전문가는 조직에서 발생하는 모든 수준의 보안 요구 사항을 처리하는 데 참조할 수 있고 보안 대응책을 구현하기 위한 검증된 방법을 제공하는 신뢰할 만한 참조 가이드를 필요로 합니다. 보안 전문가는 보안 기능과 설정을 확인한 후 많은 위험이 도사리고 있는 환경에서 고객이 어떻게 하면 이러한 기능과 설정을 가장 효율적으로 활용할 수 있는지 제안합니다.

-   **IT** **운영,** **지원 센터및 배포 담당자**. IT 운영 담당자는 배포 프로세스에서 보안을 통합하고 변경을 제어하는 데 많은 신경을 쓰는 반면, 배포 담당자는 보안 업데이트를 신속하게 관리하는 데 주로 초점을 맞춥니다. 이러한 역할을 맡은 담당자들은 소프트웨어를 설치하고 구성하는 방법과 이를 사용하고 관리하기 편하도록 개선하는 방법을 비롯하여 응용 프로그램과 관련된 보안 문제도 해결해야 합니다. 이들은 이러한 유형의 문제를 모니터링하여 보안의 측정 가능한 향상 정도를 정의하고 중요한 업무용 응용 프로그램에 보안 설정이 미치는 영향을 최소화합니다.

-   **네트워크 설계자 및 계획자**. 이 역할을 맡은 사용자들은 조직에 있는 컴퓨터들에 대한 네트워크 설계에 많은 노력을 기울입니다.

-   **컨설턴트**. 이 역할을 맡은 사용자들은 클라이언트 컴퓨터가 50대에서 5,000대 또는 그 이상 규모인 조직을 위해 일합니다. IT 컨설턴트는 조직의 모든 비즈니스 수준에 걸친 다양한 유형의 보안 시나리오를 잘 알고 있어야 합니다. IT 컨설턴트는 Microsoft 서비스 직원이건 다른 협력업체에 소속되어 있건 상관없이 엔터프라이즈 고객과 협력업체를 위한 지식 이전 도구를 잘 활용할 수 있어야 합니다.

-   **업무 분석가 및 BDM(비즈니스 의사 결정자)**. 이 역할을 맡은 사용자들은 IT 데스크톱 또는 랩톱 지원이 필요한 중요한 비즈니스 목표와 요구 사항을 처리합니다.

**참고**   이 가이드에서 제공하는 규범적 지침을 적용하려는 사용자는 적어도 1장, "기본 보안 구현"에서 설명하는 EC 환경 설정 단계를 읽고 실행해야 합니다.

#### 기술 및 준비

이 가이드의 대상에 속하는 사용자로서 엔터프라이즈 조직에서 Windows Vista가 실행되는 컴퓨터를 개발 및 배포하고 보안을 설정하려는 사용자는 다음과 같은 지식과 기술을 갖추고 있어야 합니다.

-   Windows Server 2003 이상에 대한 MCSE 인증 및 2년 이상의 보안 관련 실무 경험 또는 이에 준하는 지식

-   조직의 도메인 및 Active Directory 환경에 대한 해박한 지식

-   GPMC(그룹 정책 관리 콘솔) 사용 경험

-   모든 그룹 정책 관련 작업을 관리하기 위한 단일 솔루션을 제공하는 GPMC를 사용하여 그룹 정책을 관리해 본 경험

-   MMC(Microsoft Management Console), Gpupdate 및 Gpresult를 비롯한 관리 도구 사용 경험

-   엔터프라이즈 환경에서 응용 프로그램 및 클라이언트 컴퓨터를 배포해 본 경험

#### 가이드 목적

이 가이드의 주요 목적은 사용자가 다음과 같은 능력을 갖도록 하는 데 있습니다.

-   검증된 기본 보안 구성을 솔루션 지침에 따라 그룹 정책을 사용하여 효율적으로 작성 및 적용합니다.

-   가이드에 포함되어 있는 기본 구성의 보안 설정 권장 사항이 갖는 의미와 이유를 이해합니다.

-   일반적인 보안 시나리오를 확인 및 검토하고 사용자의 환경에서 Windows Vista의 특정 보안 기능을 사용하여 이를 손쉽게 관리할 수 있는 방법을 선택합니다.

이 가이드는 조직의 보안 요구 사항을 충족하는 데 필요한 관련 부분만 읽어도 큰 무리가 없도록 구성되어 있습니다. 그러나 가이드 전체를 읽으면 훨씬 더 많은 것을 얻을 수 있습니다.

#### 가이드 범위

이 가이드에서는 Windows Vista가 실행되는 데스크톱 및 랩톱 컴퓨터의 보안 환경을 만들고 유지 관리하는 데 도움이 되는 방법을 주로 설명합니다. 이 가이드에서는 서로 다른 두 환경을 안전하게 보호하는 방법을 단계별로 설명하고, 각 보안 설정을 통해 각 환경에 배포되어 있는 데스크톱 및 랩톱 컴퓨터의 어떠한 보안 문제를 처리할 수 있는지 설명합니다. 이 가이드에서는 규범적 정보와 보안 권장 사항을 제공합니다.

EC 환경의 클라이언트 컴퓨터에서는 Windows XP 또는 Windows Vista를 실행할 수 있습니다. 그러나 네트워크에서 이러한 클라이언트 컴퓨터를 관리하는 데 사용되는 컴퓨터에서는 Windows Server 2003 R2 또는 Windows Server 2003 SP1을 실행해야 합니다. SSLF 환경의 클라이언트 컴퓨터에서는 Windows Vista만 실행할 수 있습니다.

이 가이드에는 권장 운영 체제에 사용할 수 있는 보안 설정만 포함되어 있습니다. Windows Vista의 모든 보안 설정을 자세히 살펴보려면 관련 가이드인 [*위협 및 대책 (영문)*](http://go.microsoft.com/fwlink/?linkid=15159)을 참조하십시오.

[](#mainsection)[페이지 위쪽](#mainsection)

### 각 장의 내용 요약

*Windows* *Vista 보안 가이드*는 설정 설명, 고려 사항 및 값을 참조하는 데 사용할 수 있는 부록 하나와 다섯 개의 장으로 구성되어 있습니다. 이 가이드와 함께 제공되는 Windows Vista Security Guide Settings.xls 파일에서는 설정 값을 비교하는 데 사용할 수 있는 다른 리소스를 제공합니다. 다음 그림에 나와 있는 가이드 구조를 참조하면 규범적 지침을 구현하고 배포하는 최적의 방법을 쉽게 찾을 수 있습니다.

[![](images/bb629420.VSGOver(ko-kr,MSDN.10).gif)](https://technet.microsoft.com/ko-kr/bb629420.vsgover_big(ko-kr,msdn.10).gif)

#### 개요

이 개요 부분에서는 가이드의 목적과 범위를 설명하고, 가이드의 대상을 정의하고, 필요한 정보를 쉽게 찾을 수 있도록 이 가이드가 어떻게 구성되어 있는지 설명합니다. 또한 여기서는 가이드와 함께 제공되는 도구 및 템플릿에 대해 설명하고 지침을 실행에 옮기기 위해 사용자가 미리 갖춰야 할 조건도 설명합니다. 가이드의 각 장과 부록에 대한 간략한 소개가 이어집니다.

#### 1장: 기본 보안 구현

이 장에서는 기본 보안을 생성하고 배포할 경우 조직이 얻게 될 이점에 대해 설명합니다. 이 장에서는 EC 기본 설정 및 보안 지침을 구현하는 절차와 과정도 설명합니다.

이를 위해 이 장에서는 GPMC와 함께 GPOAccelerator.wsf 스크립트를 사용하여 이 환경을 설정하기 위한 GPO 및 OU(조직 구성 단위)를 작성, 테스트 및 배포하는 방법에 대한 지침을 설명합니다. 이 가이드와 함께 제공되는 Windows Vista Security Guide Settings.xls 파일에서는 설정 값을 비교하는 데 사용할 수 있는 다른 리소스를 제공합니다.

#### 2장: 악성 프로그램 방어

이 장에서는 Windows Vista에 새로 추가되었거나 향상된 보안 기능을 활용하여 바이러스, 웜, 트로이 목마 등을 비롯한 악성 프로그램으로부터 클라이언트 컴퓨터와 기업 자산을 안전하게 보호하기 위해 권장되는 방법을 소개합니다. 여기서는 운영 체제의 다음과 같은 기술을 가장 효율적으로 사용하는 방법에 대한 정보도 제공합니다.

-   UAC(사용자 계정 제어)

-   Windows Defender

-   Windows 방화벽

-   Windows 보안 센터

-   악성 소프트웨어 제거 도구

-   소프트웨어 제한 정책

또한 이 장에서는 Internet Explorer 7 보안 기술에 대한 다음 정보도 제공합니다.

-   Internet Explorer 보호 모드

-   ActiveX 선택

-   도메인 간 스크립팅 공격 방어

-   보안 상태 표시줄

-   피싱 필터

-   추가 보안 기능

#### 3장: 중요한 데이터 보호

이 장에서는 Windows Vista의 암호화 및 액세스 제어 기술을 사용하여 데이터를 보호하는 데 도움이 되는 권장 사항과 최상의 방법 정보를 제공합니다. 이러한 기술은 Windows Vista가 실행되는 장치를 분실하거나 도난 당할 위험이 상대적으로 더 높은 모바일 컴퓨팅 환경에 특히 중요합니다.

이 장의 내용 중에는 Windows Vista의 다음과 같은 기술을 가장 효율적으로 사용하는 방법에 대한 정보도 들어 있습니다.

-   BitLocker™ 드라이브 암호화

-   EFS(파일 시스템 암호화)

-   RMS(권한 관리 서비스)

-   장치 제어

#### 4장: 응용 프로그램 호환성

이 장에서는 사용자 환경의 기존 응용 프로그램 기능을 그대로 유지한 채 Windows Vista에 새로 추가되었거나 향상된 보안 기능과 설정을 사용하기 위해 권장되는 방법을 설명합니다. 이 장에서 다루는 내용은 다음과 같습니다.

-   발생할 수 있는 응용 프로그램 호환성 문제에 대해 간략하게 설명합니다.

-   Windows Vista와의 응용 프로그램 호환성을 테스트하는 데 사용할 수 있는 두 가지 간단한 절차를 설명합니다.

-   잠재적 완화 전략, 구성 및 지침을 제공합니다.

-   Windows Vista와의 응용 프로그램 호환성을 더 구체적으로 확인하기 위해 사용할 수 있는 다른 권장 리소스를 소개합니다.

#### 5장: 특수 보안 – 기능 제한

이 장에서는 SSLF 환경에 대해 설명하고 이 환경과 EC 환경 사이의 주요 차이점을 설명합니다. 이 장에서는 SSLF 기본 설정 및 보안 지침을 구현하는 절차와 과정도 설명합니다. 또한 이 장에서는 스크립트로 GPMC를 사용하여 이 환경을 설정하기 위한 GPO와 OU를 작성, 테스트 및 배포하는 방법에 관한 지침도 제공합니다.

![](images/bb629420.warning(ko-kr,MSDN.10).gif)**경고:**

이 장에 나와 있는 지침을 사용하면 1장, "기본 보안 구현"에서 설명하는 EC 환경과는 확연히 다른 SSLF 환경을 설정할 수 있습니다. 이 장의 지침은 매우 높은 보안이 필요한 환경에만 해당하며 1장의 지침을 보완하기 위한 내용이 아닙니다.

#### 부록 A: 보안 그룹 정책 설정

이 부록에는 가이드의 EC 및 SSLF 기본 보안에 대한 규범적 설정을 자세히 설명하는 내용과 표가 나와 있습니다. 이 부록에서는 각 설정을 비롯하여 설정의 구성 또는 값을 사용하는 이유를 설명합니다. 또한 이 부록에서는 Windows Vista와 Windows XP 사이의 설정이 어떻게 다른지도 설명합니다.

[](#mainsection)[페이지 맨 위로](#mainsection)

### 지침 및 도구

이 Solution Accelerator에는 Windows Vista Security Guide.doc, Appendix A of the Windows Vista Security Guide.doc, the Windows Vista Security Guide Settings.xls 같은 여러 파일들과 지침을 손쉽게 구현하는 데 도움이 되는 GPOAccelerator 도구가 포함되어 있습니다. \\Microsoft 다운로드 센터에서 [*Windows Vista 보안 가이드 (영문)*](http://go.microsoft.com/fwlink/?linkid=74028) Solution Accelerator를 다운로드한 후, Microsoft Windows Installer 파일(.msi)을 사용하여 컴퓨터의 원하는 위치에 이러한 리소스를 설치합니다.

**참고**   *Windows Vista 보안 가이드* 설치를 시작할 때 GPOAccelerator 도구는 기본적으로 선택되어, 이 도구에 수반되는 다른 지침과 함께 설치되도록 되어 있습니다. 이 도구를 사용하려면 관리자 권한이 있어야 합니다. 이 Solution Accelerator의 기본 설치 위치는 사용자의 문서 폴더입니다. 설치 과정에서 이 가이드에 대한 바로 가기가 생성됩니다. 이 바로 가기를 클릭하면 Windows Vista 보안 가이드 폴더가 열립니다.

GPMC(그룹 정책 관리 콘솔)를 사용하면 이 가이드에 정의되어 있는 기본 보안에 대한 도구와 템플릿을 적용할 수 있습니다. "기본 보안 구현" 장과 "특수 보안 - 기능 제한" 장에서는 이러한 작업을 수행하는 데 사용할 수 있는 절차를 설명합니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 스타일 규칙

이 가이드에서는 다음과 같은 스타일 규칙을 사용합니다.

**표 1.1 스타일 규칙**

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >요소</th>
<th style="border:1px solid black;" >의미</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>굵게</strong></td>
<td style="border:1px solid black;">명령, 스위치 및 파일 이름을 비롯하여 표시된 그대로 입력해야 할 문자를 나타냅니다. 사용자 인터페이스 요소도 굵게 표시됩니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>기울임꼴</em></td>
<td style="border:1px solid black;">책 및 기타 실제 발행물의 제목은 <em>기울임꼴</em>로 표시됩니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>&lt;기울임꼴&gt;</em></td>
<td style="border:1px solid black;">기울임꼴로 설정되고 꺾쇠 괄호로 묶인 자리 표시자 &lt;<em>filename</em>&gt;은 변수를 나타냅니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">고정 폭 글꼴</td>
<td style="border:1px solid black;">코드 및 스크립트 샘플을 정의합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>참고</strong></td>
<td style="border:1px solid black;">보충 정보를 알려 줍니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>중요</strong></td>
<td style="border:1px solid black;">작업을 완료하는 데 필수적인 정보를 제공하는 중요한 내용입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/bb629420.warning(ko-kr,MSDN.10).gif" /><strong>경고:</strong></td>
<td style="border:1px solid black;">유념해야 할 중요한 보충 정보를 알려 줍니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">‡</td>
<td style="border:1px solid black;">이 기호는 특정 그룹 정책 설정의 수정 또는 권장 사항을 가리킵니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">§</td>
<td style="border:1px solid black;">이 기호는 Windows Vista에 새로 도입된 그룹 정책 설정을 가리킵니다.</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 추가 정보
  
다음 링크에서는 이 가이드에 나와 있는 개념과 보안 조치에 대한 자세한 설명 및 보안 항목에 대한 추가 정보를 제공합니다.
  
-   [*Microsoft Windows Security Resource Kit (영문)*](http://www.microsoft.com/mspress/books/6815.asp) (Microsoft Learning 웹 사이트)
  
-   [*Microsoft Windows Server 2003 Resource Kit: Special Promotional Edition (영문)*](http://www.microsoft.com/mspress/books/5555.asp) (Microsoft Learning 웹 사이트)
  
-   [Security Guidance](http://www.microsoft.com/korea/technet/security/topics/default.mspx) 페이지 (Microsoft TechNet®)
  
-   [*Threats and Countermeasures (영문)*](http://go.microsoft.com/fwlink/?linkid=15159)**(TechNet)
  
-   [*Windows Server 2003 Security Guide*](http://www.microsoft.com/korea/technet/security/guidance/secmod117.asp) (TechNet)
  
-   [Windows Vista Readiness Assessment (영문)](http://go.microsoft.com/fwlink/?linkid=74708) (Microsoft.com)
  
-   [*Windows XP Professional Resource Kit (영문)*](http://www.microsoft.com/technet/prodtechnol/winxppro/reskit/default.mspx) (TechNet)
  
-   [*Windows XP Security Guide*](http://www.microsoft.com/korea/technet/security/guidance/secmod60.asp) (TechNet)
  
#### 지원 및 피드백
  
SASC(Solution Accelerators – Security and Compliance) 팀에서는 이 가이드 및 기타 Solution Accelerator에 대한 여러분의 의견을 기다립니다.
  
Windows Vista 도움말 및 지원 웹 사이트의 [Discussions in Security (영문)](http://windowshelp.microsoft.com/communities/newsgroups/en-us/default.mspx?dg=microsoft.public.windows.vista.security&lang=en&cr=us&r=9dcac6a3-b8e7-4ba3-aa06-4e38b8ee9f35) 뉴스 그룹에 여러분의 의견을 남겨 주십시오.
  
또는 전자 메일을 통해 다음 주소로 피드백을 보내셔도 됩니다. [secwish@microsoft.com](mailto:secwish@microsoft.com?subject=windows%20vista%20security%20guide).
  
Microsoft는 여러분의 의견을 기다리고 있습니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 감사의 말
  
SASC(Solution Accelerators – Security and Compliance) 팀에서는 *Windows Vista 보안 가이드* 제작 팀에 감사를 표합니다. 다음은 가이드 제작을 직접 담당한 분들과 이 솔루션의 작성, 개발 및 테스트에 많은 기여를 해주신 분들입니다.
  
#### 개발 팀
  
**작성자 및 전문가**
  
José Maldonado
  
Mike Danseglio
  
Michael Tan
  
Richard Harrison*(Content Master Ltd)*
  
David Coombes*(Content Master Ltd)*
  
Jim Captainino*(Content Master Ltd)*
  
Richard Hicks*(QinetiQ)*
  
**테스터**
  
Gaurav Bora
  
Vikrant Minhas*(Infosys Technologies Ltd)*
  
Sumit Parikh*(Infosys Technologies Ltd)*
  
Dharani Mohanam*(Infosys Technologies Ltd)*
  
Swapna Jagannathan*(Infosys Technologies Ltd)*
  
Prashant Japkar*(Infosys Technologies Ltd)*
  
**편집자**
  
John Cobb*(Wadeware LLC)*
  
Jennifer Kerns*(Wadeware LLC)*
  
Steve Wacker*(Wadeware LLC)*
  
**프로그램 관리자**
  
Kelly Hengesteg
  
Audrey Centola*(Volt Information Sciences)*
  
Neil Bufton*(Content Master Ltd)*
  
**제품 관리자**
  
Jim Stewart
  
Alain Meeus
  
Tony Bailey
  
Kevin Leo*(Excell Data Corporation)*
  
**릴리스 관리자**
  
Karina Larson
  
Gareth Jones
  
#### 기고자 및 검토자
  
**Microsoft**
  
Charles Denny, Ross Carter,
  
Derick Campbell, Chase Carpenter
  
Karl Grunwald, Mike Smith-Lonergan
  
Don Armstrong, Bob Drake
  
Eric Fitzgerald, Emily Hill
  
George Roussos, David Abzarian
  
Darren Canavor, Nils Dussart
  
Peter Waxman, Russ Humphries
  
Sarah Wahlert, Tariq Sharif
  
Ned Pyle, Bomani Siwatu
  
Kiyoshi Watanabe, Eric Lawrence
  
David Abzarian, Chas Jeffries
  
Vijay Bharadwaj, Marc Silbey
  
Sean Lyndersay, Chris Corio
  
Matt Clapham, Tom Daemen
  
Sanjay Pandit, Jeff Williams
  
Alex Heaton, Mike Chan
  
Bill Sisk, Jason Joyce
  
**외부 기관**
  
Mehul Mediwala*(Infosys Technologies Ltd)*
  
**참고**  
Microsoft의 요청에 따라 NSA(미국 국가 안전 보장국)의 정보 보증 본부에서 이 Microsoft 보안 가이드의 검토 작업에 참여했으며 정보 보증 본부의 의견은 이 가이드의 최종 발행 버전에 반영되었습니다.  
미국 상무부의 NIST(미국 표준 기술 연구소)에서도 이 Microsoft 보안 가이드의 검토 작업에 참여했으며 표준 기술 연구소의 의견은 이 가이드의 최종 발행 버전에 반영되었습니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
**다운로드**
  
[Windows Vista 보안 가이드 받기 (영문)](http://go.microsoft.com/fwlink/?linkid=74028)
  
**업데이트 알림**
  
[업데이트 및 최신 릴리스 정보 수신 등록 (영문)](http://go.microsoft.com/fwlink/?linkid=54982)
  
**사용자 의견**
  
[의견 및 제안 보내기](mailto:secwish@microsoft.com?subject=windows%20vista%20security%20guide)
  
[](#mainsection)[페이지 위쪽](#mainsection)
