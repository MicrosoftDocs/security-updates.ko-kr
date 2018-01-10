---
TOCTitle: '2장: Active Directory 도메인 인프라 구성'
Title: '2장: Active Directory 도메인 인프라 구성'
ms:assetid: '620c0004-41a8-4d13-9a61-e6d879f9cc65'
ms:contentKeyID: 20213970
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc163071(v=TechNet.10)'
---

Windows XP 보안 가이드
======================

### 2장: Active Directory 도메인 인프라 구성

업데이트 날짜: 2005년 10월 20일

##### 이 페이지에서

[](#elaa)[개요](#elaa)  
[](#ekaa)[보안 관리 지원을 위한 OU 디자인](#ekaa)  
[](#ejaa)[보안 관리 지원을 위한 GPO 디자인](#ejaa)  
[](#eiaa)[도메인 수준 그룹 정책](#eiaa)  
[](#ehaa)[암호 정책 설정](#ehaa)  
[](#egaa)[계정 잠금 정책 설정](#egaa)  
[](#efaa)[사용자 권한 할당 설정](#efaa)  
[](#eeaa)[보안 옵션 설정](#eeaa)  
[](#edaa)[Kerberos 정책](#edaa)  
[](#ecaa)[OU 수준 그룹 정책](#ecaa)  
[](#ebaa)[그룹 정책 도구](#ebaa)  
[](#eaaa)[요약](#eaaa)  

### 개요

그룹 정책은 Microsoft® Windows Server™ 2003 및 Microsoft Windows® 2000 Server 도메인에서 변경 및 구성 관리 작업을 편리하게 수행하도록 지원하는 Active Directory® 디렉터리 서비스의 기능입니다. 그러나 Microsoft Windows XP Professional SP2(서비스 팩 2) 환경의 클라이언트 컴퓨터에 그룹 정책을 적용하기 전에 도메인에서 몇 가지 준비 단계를 수행해야 합니다.

그룹 정책 설정은 Active Directory 데이터베이스의 GPO(그룹 정책 개체)에 저장됩니다. GPO는 Active Directory 사이트, 도메인 및 OU(조직 구성 단위)가 포함된 컨테이너에 연결됩니다. 그룹 정책은 Active Directory와 견고하게 통합되어 있으므로 Active Directory 구조 및 그 구조 내에서 구성한 여러 다른 디자인 옵션이 보안에 미치는 영향을 충분히 이해한 후 그룹 정책을 구현하는 것이 중요합니다. Active Directory 디자인에 대한 자세한 내용은 *Windows* *Server 2003 보안 가이드* 3장 "도메인 정책"을 참조하십시오.

그룹 정책은 Windows XP 보안 유지에 필요한 도구입니다. 이 장에서는 그룹 정책을 사용하여 중앙의 한 위치에서 네트워크에 일관된 보안 정책을 적용하고 유지하는 방법을 자세히 설명합니다.

이 가이드에서는 EC(엔터프라이즈 클라이언트) 및 SSLF(특수 보안 - 기능 제한) 환경에 대한 옵션을 제공합니다. 이 장에서 권장하는 설정은 데스크톱 및 랩톱 클라이언트 컴퓨터 둘 다에 동일하게 적용되며 특별한 설정이므로 OU 수준이 아닌 도메인 루트 수준에서 적용됩니다. 예를 들어 Windows Server 2003 및 Windows 2000 Server 도메인에 대한 암호 및 계정 잠금은 도메인 루트에 연결되어 있는 GPO를 통해 구성해야 합니다. 두 가지 다른 환경에 대한 기준 보안 템플릿 파일의 이름은 다음과 같습니다.

-   EC-Domain.inf

-   SSLF-Domain.inf

[](#mainsection)[페이지 위쪽](#mainsection)

### 보안 관리 지원을 위한 OU 디자인

OU는 Active Directory 도메인 내의 컨테이너입니다. OU에는 사용자, 그룹, 컴퓨터 및 기타 OU(자식 OU)가 포함될 수 있습니다. GPO를 OU에 연결할 수 있으며 이 경우 GPO 설정은 해당 OU 및 해당 자식 OU에 포함된 사용자 및 컴퓨터에 적용됩니다. 편리한 관리 작업을 위해 관리 권한을 각 OU에 위임할 수 있습니다. OU를 사용하여 사용자, 컴퓨터 및 기타 보안 사용자를 쉽게 그룹화할 수 있을 뿐 아니라 관리 범위를 효과적으로 구분할 수 있습니다. 조직에서는 사용자 및 컴퓨터를 별도의 OU에 할당하는 것이 좋습니다. 설정에 따라 사용자에게만 적용되는 경우도 있고 컴퓨터에만 적용되는 경우도 있기 때문입니다.

MMC(Microsoft Management Console) Active Directory 사용자 및 컴퓨터 스냅인 도구의 위임 마법사를 사용하여 그룹 또는 개별 OU에 제어 권한을 위임할 수 있습니다. 권한 위임 방법에 대한 설명서로 연결되는 링크를 보려면 이 장 끝에 나오는 "추가 정보" 섹션을 참조하십시오.

모든 환경에서 OU 구조 디자인의 주요 목표 중 하나는 Active Directory의 모든 워크스테이션에 적용되는 그룹 정책을 원활하게 구현할 수 있는 기반을 제공하고 조직의 보안 표준에 맞는 그룹 정책을 구현하도록 하는 것입니다. 또한 OU 구조는 조직에서 특정 유형의 사용자에게 적합한 보안 설정을 제공하도록 디자인되어야 합니다. 예를 들어 개발자는 일반 사용자에게 허용되지 않은 작업을 해당 워크스테이션에서 수행할 수 있습니다. 또한 랩톱 사용자에게는 데스크톱 사용자와는 약간 다른 보안 설정이 필요할 수 있습니다. 다음 그림에서는 이 장에서 논의하게 될 그룹 정책에 대한 개념을 잘 나타내는 간단한 OU 구조를 보여 줍니다. 이 OU의 구조는 사용자 환경의 조직 관련 요구 사항과 다를 수도 있습니다.

![](images/Cc163071.sgfg0201(ko-kr,TechNet.10).gif)

**그림 2.1 Windows XP 컴퓨터의 OU 구조**

#### 부서 OU

조직 내의 보안 요구 사항은 자주 바뀌므로 사용자 환경에 부서 OU를 만드는 것이 적합할 수도 있습니다. 부서의 보안 설정은 GPO를 통해 각 해당 부서 OU의 컴퓨터와 사용자에게 적용될 수 있습니다.

##### 보안 처리된 XP 사용자 OU

이 OU에는 EC 및 SSLF 환경의 사용자에 대한 계정이 포함됩니다. 이 OU에 적용되는 설정에 대해서는 4장 "Windows XP용 관리 템플릿"의 "사용자 구성" 섹션을 참조하십시오.

##### Windows XP OU

이 OU에는 사용자 환경에 있는 각 유형의 Windows XP 클라이언트 컴퓨터에 대한 자식 OU가 포함됩니다. 이 가이드에는 데스크톱 및 랩톱 컴퓨터에 대한 지침이 모두 포함되어 있습니다. 그렇기 때문에 데스크톱 OU와 랩톱 OU가 만들어진 것입니다.

-   **데스크톱 OU**. 이 OU에는 네트워크에 계속 연결된 상태를 유지하는 데스크톱 컴퓨터가 포함됩니다. 이 OU에 적용되는 설정에 대해서는 3장 "Windows XP 클라이언트용 보안 설정"과 4장 "Windows XP용 관리 템플릿"을 참조하십시오.

-   **랩톱 OU**. 이 OU에는 네트워크에 항상 연결되어 있지는 않은 이동이 잦은 사용자의 랩톱 컴퓨터가 포함됩니다. 3장 "Windows XP 클라이언트용 보안 설정"과 4장 "Windows XP용 관리 템플릿"에서는 이 OU에 적용되는 설정에 대해 자세히 설명합니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 보안 관리 지원을 위한 GPO 디자인

특정 정책 설정, 사용자 권한 및 동작이 OU 내의 모든 워크스테이션 또는 사용자에게 적용되는지 확인하려면 GPO를 사용합니다. 수동 구성 대신 그룹 정책을 사용하면 나중에 추가 변경이 발생했을 때 많은 수의 워크스테이션 또는 사용자를 간단히 업데이트할 수 있습니다. 수동 구성은 기술자가 각 클라이언트 컴퓨터를 방문해야 하므로 비효율적입니다. 또한 도메인 기반 GPO의 정책 설정이 로컬로 적용되는 정책 설정과 다를 경우 도메인 기반 GPO 정책 설정이 로컬로 적용되는 정책 설정을 덮어씁니다.

[![](images/Cc163071.sgfg0202(ko-kr,TechNet.10).gif)](https://technet.microsoft.com/ko-kr/cc163071.sgfg0202_big(ko-kr,technet.10).gif)

**그림 2.2 GPO 적용 순서**

이 그림은 자식 OU의 구성원인 컴퓨터에 GPO가 적용되는 순서를 보여 줍니다. 1이 가장 낮은 순서이고 5가 가장 높은 순서입니다. 각 Windows XP 워크스테이션의 로컬 정책으로부터 먼저 그룹 정책이 적용됩니다. 로컬 정책이 적용된 후 모든 GPO가 사이트 수준에서 적용된 다음 도메인 수준에서 적용됩니다.

여러 OU 계층에 중첩된 Windows XP 클라이언트 컴퓨터의 경우 계층 구조에서 가장 높은 OU 수준부터 가장 낮은 수준의 순서로 GPO가 적용됩니다. 마지막 GPO는 클라이언트 컴퓨터가 포함된 OU로부터 적용됩니다. 프로세스에서 나중에 적용되는 GPO가 먼저 적용되는 GPO를 덮어쓰므로 이러한 GPO 처리 순서(로컬 정책, 사이트, 도메인, 부모 OU 및 자식 OU)는 매우 중요합니다. 사용자 GPO도 같은 방식으로 적용됩니다.

그룹 정책을 디자인할 때는 다음 사항을 고려해야 합니다.

-   관리자는 사용자가 여러 GPO를 OU에 연결하는 순서를 설정해야 합니다. 그렇지 않을 경우 기본적으로 OU에 연결된 순서대로 정책이 적용됩니다. 여러 정책에 동일한 설정이 구성되면 해당 컨테이너의 정책 목록에서 가장 높은 수준의 정책이 우선적으로 적용됩니다.

-   **적용** 옵션을 사용하여 GPO를 구성할 수 있습니다. 이 옵션을 선택하면 다른 GPO가 이 GPO에 구성된 설정보다 우선적으로 적용될 수 없습니다.

    **참고**: Windows 2000에서 **적용** 옵션은 **무시 안 함** 옵션으로 제공됩니다.

-   **정책의 상속을 금지** 옵션을 사용하여 Active Directory, 사이트, 도메인 또는 OU를 구성할 수 있습니다. 이 옵션을 사용하면 **적용** 옵션을 선택하지 않은 경우 Active Directory 계층 구조에서 더 높은 수준의 GPO로부터 GPO가 설정되는 것이 차단됩니다. 즉, **적용** 옵션은 **정책의 상속을 금지** 옵션보다 우선적으로 적용됩니다.

-   그룹 정책 설정은 Active Directory에서 사용자 또는 컴퓨터 개체가 존재하는 위치에 따라 사용자 및 컴퓨터에 적용됩니다. 경우에 따라 사용자 개체의 위치가 아닌 컴퓨터 개체의 위치에 따라 정책이 적용되어야 하는 사용자 개체가 있을 수도 있습니다. 그룹 정책 루프백 기능을 통해 관리자는 사용자가 로그온한 컴퓨터에 따라 사용자 그룹 정책 설정을 적용할 수 있게 됩니다. 루프백 지원에 대한 자세한 내용은 이 장 뒷부분에 나오는 "추가 정보" 섹션의 그룹 정책 백서를 참조하십시오.

다음 그림에서는 임시 OU 구조를 확장하여 랩톱 OU 및 데스크톱 OU에 속하는 Windows XP 클라이언트 컴퓨터에 GPO가 적용될 수 있는 방법을 보여 줍니다.

[![](images/Cc163071.XPSG0203(ko-kr,TechNet.10).jpg)](https://technet.microsoft.com/ko-kr/cc163071.xpsg0203_big(ko-kr,technet.10).gif)

**그림 2.3 Windows XP 기반 데스크톱 및 랩톱 컴퓨터를 수용할 수 있는 확장된 OU 구조**

위 예에서 랩톱 컴퓨터는 랩톱 OU의 구성원입니다. 첫 번째로 적용된 정책은 랩톱 컴퓨터의 로컬 보안 정책입니다. 이 예에는 사이트가 한 개만 있으므로 사이트 수준에서는 GPO가 적용되지 않고 도메인 GPO가 다음에 적용될 정책으로 남겨집니다. 끝으로 랩톱 GPO가 적용됩니다.

**참고**:데스크톱 정책은 랩톱 OU가 포함된 계층 구조에 있는 어떤 OU에도 연결되지 않으므로 어떤 랩톱에도 적용되지 않습니다. 뿐만 아니라 보안 처리된 XP 사용자 OU에는 관리 템플릿의 설정만 포함되므로 해당 보안 템플릿(.inf 파일)이 없습니다.

우선 순위가 적용되는 방식을 확인하려면 **터미널 서비스를 통한 로그온 허용**에 대한 Windows XP OU 정책 설정이 **Administrators** 그룹으로 설정되고 **터미널 서비스를 통한 로그온 허용**에 대한 랩톱 GPO 설정이 **Power Users** 및 **Administrators** 그룹으로 설정된 시나리오 예를 참조하십시오. 이 예에서 계정이 **Power Users** 그룹에 속하는 사용자는 랩톱 OU가 Windows XP OU의 자식 OU이므로 터미널 서비스를 통해 랩톱에 로그온할 수 있습니다. Windows XP GPO에서 **무시 안 함** 정책 옵션을 사용하면 **Administrators** 그룹에 속하는 계정을 가진 사용자만 터미널 서비스를 사용하여 클라이언트 컴퓨터에 로그온할 수 있습니다.

#### 보안 템플릿

보안 템플릿은 보안 설정 값을 포함하는 텍스트 파일이며 GPO의 하위 구성 요소입니다. 또한 보안 템플릿에 포함되어 있는 정책 설정은 MMC 그룹 정책 개체 편집기 스냅인에서 수정할 수 있으며 **컴퓨터 구성\\Windows 설정\\보안 설정** 폴더에 있습니다. 이러한 보안 템플릿 파일을 MMC 보안 템플릿 스냅인이나 메모장과 같은 텍스트 편집기에서 수정할 수도 있습니다. GPO에 속하는 보안 템플릿의 정책 설정을 관리할 때는 그룹 정책 개체 편집기 스냅인을 사용하고 독립 실행형 보안 템플릿의 정책 설정을 관리할 때는 보안 템플릿 스냅인을 사용하는 것이 좋습니다.

템플릿 파일의 일부 섹션에는 SDDL(Security Descriptor Definition Language)로 정의되는 특정 ACL(액세스 제어 목록)이 포함됩니다. 보안 템플릿 및 SDDL을 편집하는 방법에 대한 자세한 내용은 이 장 뒷부분의 "추가 정보" 섹션을 참조하십시오.

##### 보안 템플릿 관리

프로덕션 환경의 보안 템플릿은 반드시 인프라의 안전한 위치에 저장해야 합니다. 보안 템플릿에 대한 액세스 권한은 그룹 정책 구현을 담당하는 관리자에게만 부여해야 합니다. Windows XP, Windows 2000 및 Windows Server 2003에 포함되어 있는 보안 템플릿은 기본적으로 **%SystemRoot%\\security\\templates** 폴더에 저장됩니다. 1장에 설명된 것처럼 이 가이드에 포함되어 있는 보안 템플릿은 가이드가 들어 있는 WinZip 보관 파일에 포함된 .msi 파일을 실행할 때 **\\Windows XP Security Guide Tools and Templates\\Security Templates** 폴더로 복사됩니다. 이 가이드의 다운로드 버전은 [http://go.microsoft.com/fwlink/?LinkId=14840 (영문)](http://go.microsoft.com/fwlink/?linkid=14840)에서 찾을 수 있습니다. 이 폴더의 보안 템플릿을 새 위치로 복사하거나 이동한 후 보안 설정을 평가하고 조직의 비즈니스 요구에 맞게 좀 더 수정할 수 있습니다. 테스트가 완료된 후에는 보안 템플릿의 최종 버전을 중앙의 한 위치(예: 기본 제공 보안 템플릿의 기본 위치)로 옮겨 두어야 합니다.

**%SystemRoot%\\security\\templates** 폴더는 도메인 컨트롤러 간에 복제되지 않습니다. 그러므로 템플릿에 대해 버전 관리 문제가 발생하지 않도록 보안 템플릿의 마스터 복사본을 보관할 도메인 컨트롤러를 선택해야 합니다. 이렇게 하면 항상 동일한 템플릿 복사본을 수정할 수 있습니다.

##### 보안 템플릿 가져오기

보안 템플릿을 가져오려면 다음 절차의 단계를 수행하십시오.

**보안 템플릿을 GPO로 가져오려면**

1.  그룹 정책 개체 편집기에서 **Windows 설정** 폴더로 이동합니다.

2.  **Windows 설정** 폴더를 확장하고 **보안 설정**을 선택합니다.

3.  **보안 설정** 폴더를 마우스 오른쪽 단추로 클릭한 다음 **정책 가져오기...** 를 클릭합니다.

4.  가져올 보안 템플릿을 선택한 다음 **열기**를 클릭합니다. 그러면 GPO에 해당 파일의 설정이 열립니다.

#### 관리 템플릿

관리 템플릿이라고 하는 유니코드 기반 파일의 추가 보안 설정을 사용할 수 있습니다. 이러한 파일에는 Windows XP 및 해당 구성 요소와 Microsoft Office 2003 같은 기타 응용 프로그램에 영향을 주는 레지스트리 설정이 포함되어 있습니다. 관리 템플릿에는 사용자 설정뿐만 아니라 컴퓨터 설정도 포함될 수 있습니다. 컴퓨터 설정은 HKEY\_LOCAL\_MACHINE 레지스트리 하이브에 저장되며 사용자 설정은 HKEY\_CURRENT\_USER 레지스트리 하이브에 저장됩니다.

##### 관리 템플릿 관리

보안 템플릿을 안전하게 저장하는 것이 중요한 것처럼 프로덕션 환경에 사용되는 관리 템플릿도 인프라의 안전한 위치에 저장해야 합니다. 그룹 정책 구현을 담당하는 관리자만 이 위치에 액세스할 수 있어야 합니다. Windows XP 및 Windows Server 2003과 함께 제공되는 관리 템플릿은 **%systemroot%\\inf** 디렉터리에 저장됩니다. Office 2003용 추가 템플릿은 *Office 2003 Resource Kit*에 포함되어 있습니다. Microsoft에서 제공하는 관리 템플릿은 서비스 팩이 출시될 때 변경될 수 있으므로 편집해서는 안 됩니다.

##### 정책에 관리 템플릿 추가

Windows XP와 함께 제공된 관리 템플릿 외에도 Office 2003 설정을 구성하려는 해당 GPO에 Office 2003 템플릿을 적용할 수 있습니다. 또는 조직에 고유하게 적용되는 사용자 지정 관리 템플릿을 만들 수 있습니다. GPO에 추가 템플릿을 추가하려면 다음 절차를 수행하십시오.

**GPO에 관리 템플릿을 추가하려면**

1.  그룹 정책 개체 편집기에서 관리 템플릿 폴더를 탐색합니다.

2.  **관리 템플릿** 폴더를 마우스 오른쪽 단추로 클릭한 다음 **템플릿 추가/제거**를 클릭합니다.

3.  **템플릿 추가/제거** 대화 상자에서 **추가**를 클릭합니다.

4.  관리 템플릿 파일이 들어 있는 폴더를 탐색합니다.

5.  추가할 템플릿을 선택하고 **열기**를 클릭한 다음 **닫기**를 클릭합니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 도메인 수준 그룹 정책

도메인 수준 그룹 정책에는 해당 도메인의 모든 컴퓨터와 사용자에게 적용되는 설정이 포함됩니다. 도메인 수준 설정은 기본 제공 기본 도메인 정책이 아닌 새 GPO에 구성하는 것이 좋습니다. 이렇게 하면 이 가이드에 따라 설정을 변경했을 때 문제가 발생해도 기본 설정을 쉽게 복원할 수 있습니다. 또한 일부 응용 프로그램이 기본 도메인 정책을 자동으로 구성하고 이러한 응용 프로그램에 의해 변경된 정책 설정이 이 가이드에 설명된 도메인 정책 GPO에 정의된 설정과 충돌할 수 있습니다. 그러나 도메인 수준에서는 일부 설정만 구성되므로 이러한 문제가 발생할 가능성은 많지 않습니다. 도메인 수준 설정은 [*Windows Server 2003 보안 가이드*](http://go.microsoft.com/fwlink/?linkid=14845)(http://go.microsoft.com/fwlink/?LinkId=14845)의 3장 "도메인 정책'에 자세히 설명되어 있습니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 암호 정책 설정

복잡한 암호를 정기적으로 바꿔서 사용하면 암호 공격의 가능성이 줄어듭니다. 암호 정책 설정은 암호의 복잡성 및 수명을 제어하며 도메인 수준의 그룹 정책을 통해서만 구성할 수 있습니다. 독립 실행형 컴퓨터에서 로컬 SAM(보안 계정 관리자)에서 직접 암호 정책을 설정하는 방법에 대한 자세한 내용은 5장 "독립 실행형 Windows XP 클라이언트 보안 설정"을 참조하십시오.

이 섹션에서는 EC 및 SSLF 환경의 암호 정책 설정에 대해 설명합니다.

그룹 정책 개체 편집기의 다음 위치에서 암호 정책 설정을 구성할 수 있습니다.

**컴퓨터 구성\\Windows 설정\\보안 설정\\계정 정책\\암호 정책**

다음 표는 이 가이드에 정의된 두 가지 유형의 보안 환경에 대한 암호 정책 설정 권장 사항을 요약해서 보여 줍니다. 각 설정에 대한 자세한 내용은 다음 하위 섹션에 제공됩니다.

**표 2.1 암호 정책 설정 권장 사항**

 
<p> </p><table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >설정</th>
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >EC</th>
<th style="border:1px solid black;" >SSLF</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">최근 암호 기억</td>
<td style="border:1px solid black;">24개 암호</td>
<td style="border:1px solid black;">24개 암호</td>
<td style="border:1px solid black;">24개 암호</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">최대 암호 사용 기간</td>
<td style="border:1px solid black;">42일</td>
<td style="border:1px solid black;">90일</td>
<td style="border:1px solid black;">90일</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">최소 암호 사용 기간</td>
<td style="border:1px solid black;">1일</td>
<td style="border:1px solid black;">1일</td>
<td style="border:1px solid black;">1일</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">최소 암호 길이</td>
<td style="border:1px solid black;">7자</td>
<td style="border:1px solid black;">8자</td>
<td style="border:1px solid black;">12자</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">암호는 복잡성을 만족해야 함</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">도메인 내의 모든 사용자에 대해 해독 가능한 암호화를 사용하여 암호 저장</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
#### 최근 암호 기억
  
이 정책 설정은 이전 암호를 다시 사용하기 전에 사용자 계정과 연결되어야 할 고유한 새 암호 수를 결정합니다. 이 정책 설정의 암호 수는 0부터 24개 사이여야 합니다. Windows XP의 기본 설정은 0개이지만 도메인의 기본 설정은 24개입니다. 이 정책 설정을 유효하게 하려면 **최소 암호 사용 기간** 설정을 사용하여 사용자가 암호를 반복해서 변경하지 못하도록 합니다.
  
이 가이드에 정의된 두 가지 보안 환경에 대해 **최근 암호 기억** 설정을 **24개 암호 기억됨**으로 구성합니다.
  
#### 최대 암호 사용 기간
  
이 정책 설정 값의 범위는 1일부터 999일까지입니다. 암호가 만료되지 않도록 지정하려면 이 값을 0으로 설정할 수도 있습니다. 이 정책 설정은 암호가 만료되기까지 암호를 사용할 수 있는 기간을 정의합니다. 이 정책 설정의 기본값은 42일입니다. 대부분의 암호는 해독될 수 있으므로 암호를 자주 변경할수록 공격자가 암호를 알아내어 사용할 수 있는 기회는 줄어듭니다. 그러나 이 값을 낮게 설정할수록 지원 부서로의 지원 요청이 늘어날 가능성은 높아집니다.
  
이 가이드에 정의된 두 가지 보안 환경에서는 **최대 암호 사용 기간** 설정을 **90일**로 구성합니다.
  
#### 최소 암호 사용 기간
  
이 정책 설정은 사용자가 암호를 변경하기 전에 암호를 사용해야 하는 일 수를 결정합니다. 이 정책 설정 값의 범위는 1일부터 998일까지입니다. 즉각적인 암호 변경을 허용하기 위해 이 값을 0으로 설정할 수도 있습니다. 이 정책 설정의 기본값은 0일입니다.
  
암호가 만료되지 않도록 **최대 암호 사용 기간** 설정 값이 0으로 구성되지 않은 이상, **최소 암호 사용 기간** 설정 값은 **최대 암호 사용 기간** 설정에 지정된 값보다 작아야 합니다. **최대 암호 사용 기간** 설정 값이 0으로 구성되어 있으면 이 정책 설정 값을 0에서 999 사이의 어떤 값으로든 구성할 수 있습니다.
  
**최근 암호 기억** 설정을 유효하게 하려면 이 값을 0보다 큰 값으로 구성합니다. **최소 암호 사용 기간** 설정 값이 0이면 사용자가 이전에 즐겨 쓰던 암호가 나올 때까지 반복해서 암호를 바꿀 수 있습니다.
  
이 가이드에 정의된 두 가지 보안 환경에서는 **최소 암호 사용 기간** 설정을 1일로 구성합니다. 이 값을 지정하면 암호를 변경하기 위해 하루를 꼬박 기다려야 하므로 같은 암호를 반복해서 다시 사용할 수 없습니다. 또한 암호를 다시 설정하기 전까지 적어도 하루 이상 해당 암호를 사용해야 하므로 새 암호를 기억하기 쉬워집니다. 뿐만 아니라 **최근 암호 기억** 설정에 따른 제한을 효과적으로 적용할 수 있습니다.
  
#### 최소 암호 길이
  
이 정책 설정은 사용자 계정의 암호를 구성하는 최소 문자 수를 결정합니다. 조직에 가장 적합한 암호 길이를 결정하는 방법에 대해서는 여러 가지 많은 이론이 있지만 "통과 구문"이 "암호"보다 더 좋은 용어가 될 수 있습니다. Microsoft Windows 2000 이상의 버전에서는 통과 구문이 아주 길 수 있으며 공백을 포함할 수도 있습니다. 따라서 "I want to drink a $5 milkshake"와 같은 구문도 유효한 통과 구문이 되며 임의의 숫자와 문자로 된 8자리 또는 10자리 문자열보다 매우 강력하면서도 더 쉽게 기억할 수 있는 암호가 됩니다. 사용자는 암호를 적절히 선택하고 유지 관리하는 방법을 잘 배워야 하며 암호 길이에 대한 지침도 잘 숙지해야 합니다.
  
EC 환경에서는 **최소 암호 길이** 설정 값이 **8문자**로 구성되어야 합니다. 이 정책 설정은 적절한 보안을 제공할만큼 길이가 충분하지만 사용자가 쉽게 기억하기 좋을 정도로 길이가 짧습니다. SSLF 환경에서는 이 값을 **12문자**로 구성합니다.
  
#### 암호는 복잡성을 만족해야 함
  
이 정책 설정은 모든 새 암호를 확인하여 강력한 암호에 대한 기본 요구 사항을 만족하는지 검사합니다. 기본적으로 Windows XP에서 이 정책 설정 값은 **사용 안 함**으로 구성되지만 Windows Server 2003 도메인에서는 이 설정이 **사용**입니다.
  
암호 길이가 한 자리씩 길어질 때마다 복잡성은 엄청나게 증가합니다. 예를 들어 모두 알파벳 소문자로 이루어진 7자리 암호로 만들 수 있는 조합은 267(약 8x109 또는 80억) 가지입니다. 일반적인 암호 해독 유틸리티의 성능을 가정하여 초당 1,000,000번 시도할 경우 133분이면 암호를 해독할 수 있습니다. 대/소문자를 구분하는 7자리 영문자 암호는 527 가지 조합을 갖습니다. 문장 부호를 사용하지 않는 7자리의 대/소문자를 구분하는 암호로는 627 가지의 조합이 가능합니다. 8자리 암호로는 268 또는 2 x 1011 가지 조합이 가능합니다. 이러한 조합의 수는 대단히 많은 것처럼 보이지만 초당 1,000,000번 시도할 경우 가능한 모든 암호를 검사하는 데 59시간이면 족합니다. Alt 문자와 그 밖의 특수 키보드 문자(예: ! 또는 @)를 사용하는 암호의 경우 해독하는 데 훨씬 많은 시간이 필요합니다.
  
암호 설정을 적절히 사용하면 암호를 해독하는 것이 완전히 불가능하다고는 볼 수 없지만 아주 어려워집니다.
  
#### 도메인 내의 모든 사용자에 대해 해독 가능한 암호화를 사용하여 암호 저장
  
이 정책 설정은 운영 체제에서 해독 가능한 암호화를 사용하여 암호를 저장할지를 결정합니다. 이 설정을 사용하면 인증을 위해 사용자 암호를 알아야 하는 응용 프로그램 프로토콜이 지원됩니다. 해독 가능한 암호화를 사용하여 저장한 암호는 기본적으로 암호의 일반 텍스트 버전과 동일합니다. 따라서 응용 프로그램 요구 사항이 암호 정보 보호의 필요성보다 더 중요한 경우가 아니라면 이 정책 설정을 사용해서는 안 됩니다. 이 정책 설정의 기본값은 **사용 안 함**입니다.
  
이 정책 설정은 원격 액세스 또는 IAS(Internet Authentication Service)를 통해 Challenge Handshake 인증 프로토콜(CHAP)을 사용할 때 사용해야 하며 Microsoft Internet Information Services(IIS)에서 다이제스트 인증을 사용할 때도 필요합니다.
  
**도메인 내의 모든 사용자에 대해 해독 가능한 암호화를 사용하여 암호 저장** 설정이 **사용 안 함**으로 구성되어 있는지 확인합니다. 이 설정은 Windows Server 2003의 기본 도메인 GPO와 워크스테이션 및 서버에 대한 로컬 보안 정책에 구성된 설정을 나타냅니다. 이 정책 설정은 이 가이드에 정의된 두 환경에서도 **사용 안 함**입니다.
  
#### 필요한 경우 외에는 사용자의 암호 변경 금지
  
일부 조직에서는 이 장 앞부분에 설명된 암호 정책 외에도 중앙에서 모든 사용자의 암호 사용을 제어해야 할 필요가 있습니다. 여기서는 필요한 경우 외에 사용자가 자신의 암호를 변경하지 못하도록 하는 방법을 설명합니다.
  
사용자 암호를 중앙에서 제어하는 시스템은 잘 만들어진 Windows XP 보안 구성의 기초가 됩니다. 그룹 정책을 사용하면 앞에서 살펴본 바와 같이 최소 및 최대 암호 기간을 설정할 수 있습니다. 그러나 암호를 자주 변경하도록 지정하면 작업 환경에 대한 **최근 암호 기억** 설정이 효과를 발휘할 수 없습니다. 너무 긴 암호를 지정하도록 하면 암호를 잊어버린 사람들이 지원 서비스에 문의하는 일이 많아질 수 있습니다.
  
사용자는 최소 및 최대 암호 사용 기간 설정 사이의 기간 중 자신의 암호를 변경할 수 있습니다. 그러나 특수 보안 - 기능 제한 환경의 보안 디자인에서는 암호가 최대 42일 기간에 도달한 후 운영 체제에서 암호를 변경하라는 메시지를 표시하는 경우에만 사용자가 암호를 변경해야 합니다. 이 수준의 제어 권한을 얻기 위해 관리자는 Ctrl+Alt+Delete를 누를 때 나타나는 **Windows 보안** 대화 상자에서 **암호 변경...** 단추를 비활성화할 수 있습니다.
  
그룹 정책을 사용하여 전체 도메인에 대해 이 구성을 구현하거나 레지스트리를 편집하여 한 명 이상의 특정 사용자에 대해 구현할 수 있습니다. 이 구성에 대한 자세한 내용은 Microsoft 기술 자료 문서 324744, "[Windows Server 2003에서 필요한 경우를 제외하고 사용자가 암호를 변경하지 못하게 하는 방법](http://support.microsoft.com/default.aspx?scid=324744)”(http://support.microsoft.com/default.aspx?scid=324744)을 참조하십시오. Windows 2000 도메인이 있는 경우에는 Microsoft 기술 자료 문서 309799, "[Windows 2000에서 필요한 경우를 제외하고 사용자가 암호를 변경하지 못하게 하는 방법](http://support.microsoft.com/default.aspx?scid=309799)"(http://support.microsoft.com/default.aspx?scid=309799)을 참조하십시오.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 계정 잠금 정책 설정
  
계정 잠금 정책은 지정한 기간 내에 지정한 횟수만큼 로그온 시도가 실패한 후 사용자 계정을 잠그고 로그온을 금지시키는 Active Directory 보안 기능입니다. 도메인 컨트롤러에서는 로그온 시도를 추적합니다. 허용되는 시도 수와 기간은 구성된 계정 잠금 설정 값을 기반으로 합니다. 잠금 기간도 지정할 수 있습니다.
  
이러한 정책 설정은 공격자가 사용자 암호를 알아내지 못하도록 막는 것을 도와 주며 네트워크 환경의 공격 가능성을 줄여 줍니다. 그러나 계정 잠금 정책을 설정하면 네트워크 사용자에 대한 지원 문제가 더 많이 발생할 수 있습니다. 다음 설정을 사용하기 전에 조직에서 이러한 추가 관리 오버헤드를 수용할 수 있는지 확인합니다. 많은 조직에서는 도메인 컨트롤러의 보안 이벤트 로그를 자동으로 검사하고 누군가가 사용자 계정의 암호를 추측하려고 시도할 때 관리 경고를 생성하는 저렴하고 뛰어난 솔루션을 필요로 합니다.
  
그룹 정책 개체 편집기의 다음 위치에서 계정 잠금 정책 설정을 구성할 수 있습니다.
  
**컴퓨터 구성\\Windows 설정\\보안 설정\\계정 정책\\계정 잠금 정책**
  
다음 표에는 이 가이드에 정의된 두 보안 환경에 대한 계정 잠금 정책 설정 권장 사항이 포함되어 있습니다. 각 설정에 대한 자세한 내용은 다음 하위 섹션에 제공됩니다.
  
**표 2.2 계정 잠금 정책 설정 권장 사항**

 
<p> </p><table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >설정</th>
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >EC</th>
<th style="border:1px solid black;" >SSLF</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">계정 잠금 기간</td>
<td style="border:1px solid black;">정의되지 않음</td>
<td style="border:1px solid black;">15분</td>
<td style="border:1px solid black;">15분</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">계정 잠금 임계값</td>
<td style="border:1px solid black;">0번의 잘못된 로그온 시도</td>
<td style="border:1px solid black;">50번의 잘못된 로그온 시도</td>
<td style="border:1px solid black;">10번의 잘못된 로그온 시도</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">다음 시간 후 계정 잠금 수를 원래대로 설정</td>
<td style="border:1px solid black;">정의되지 않음</td>
<td style="border:1px solid black;">15분</td>
<td style="border:1px solid black;">15분</td>
</tr>
</tbody>
</table>
  
#### 계정 잠금 기간
  
이 정책 설정은 계정의 잠금을 해제하고 사용자가 다시 로그온을 시도하기 전까지 경과해야 하는 기간을 결정합니다. 잠겨진 계정이 사용 불가능한 상태로 유지될 시간을 분으로 지정하여 이 설정이 이루어집니다. 이 정책 설정 값을 0으로 구성하면 잠긴 계정은 관리자가 해당 계정의 잠금을 해제할 때까지 잠긴 상태로 유지됩니다. 이 정책 설정에 대한 Windows XP 기본값은 **정의되지 않음**입니다.
  
지원 문의 횟수를 줄이고 보안 인프라를 제공하려면 이 가이드에 정의된 EC 및 SSLF 환경에 대한 **계정 잠금 기간** 설정 값을 **15**분으로 구성합니다.
  
계정 잠금을 자동으로 해제하지 않도록 이 정책 설정을 구성하는 것이 적절해 보일 수 있지만 이와 같이 구성하면 지원 부서에서는 실수로 잠근 계정에 대한 해제 요청을 많이 받을 수 있습니다. 15분이 권장되는 이유는 계정이 잠긴 경우 다시 로그온하기 위해 기다리기에 적절한 시간이 바로 15분이기 때문입니다. 또한 사용자들은 이 정책의 구성 방식을 제대로 이해하여 컴퓨터에 즉시 다시 액세스해야 할 경우에만 지원을 요청하도록 해야 합니다.
  
#### 계정 잠금 임계값
  
이 정책 설정은 계정이 잠기기 전에 시도할 수 있는 로그온 횟수를 결정합니다. 권한이 부여된 사용자의 경우 암호를 잘못 입력하거나 잊어버리거나 또는 다른 컴퓨터에 로그온된 상태에서 이 컴퓨터의 암호를 변경했을 때 계정이 잠길 수 있습니다. 잘못된 암호를 지정하여 계속 사용자를 인증하려고 시도할 경우 인증에 사용하는 암호가 틀리므로 결국에는 사용자 계정이 잠깁니다. 권한이 부여된 사용자의 계정이 잠기지 않도록 하려면 계정 잠금 임계값을 더 큰 값으로 설정하십시오. 이 정책 설정의 기본값은 0번의 잘못된 로그온 시도이며 이 경우 계정 잠금 기능이 해제됩니다.
  
**계정 잠금 임계값** 설정 값을 EC 환경에 대해서는 **50**번의 잘못된 로그온 시도로, SSLF 환경에 대해서는 **10**번의 잘못된 로그온 시도로 구성합니다.
  
공격자가 많은 수의 계정에 대한 잠금을 트리거하여 이 잠금 상태를 DoS(서비스 거부 공격)로 사용할 수 있으므로 조직에서는 식별된 위협과 완화시키고 싶은 위험 요소를 기반으로 이 정책 설정을 사용할지를 결정해야 합니다. 이 정책을 설정할 때는 두 가지 옵션을 고려해야 합니다.
  
-   계정이 잠기지 않도록 하려면 **계정 잠금 임계값**을 **0**으로 구성합니다. 이 설정 값은 조직의 계정을 잠그려고 시도하는 DoS 공격을 방지합니다. 또한 사용자들이 계정을 실수로 잠그는 경우는 없으므로 지원 부서 요청 횟수도 줄어듭니다. 그러나 이 값을 설정하면 암호 해독 공격을 효과적으로 방지할 수 없습니다. 다음과 같은 방어 대책도 고려해야 합니다.
  
    -   모든 사용자에게 8자 이상으로 구성된 복잡한 암호를 사용하도록 요구하는 암호 정책
  
    -   환경에서 일련의 계정 잠금이 발생할 때 관리자에게 경고하는 강력한 감사 메커니즘. 예를 들어 감사 솔루션은 로그온 실패를 나타내는 보안 이벤트 539를 모니터링해야 합니다. 이 이벤트는 로그온 시도가 이루어졌을 때 계정이 잠겼음을 의미합니다.
  
두 번째 옵션은 다음과 같습니다.
  
-   암호를 몇 차례 실수로 잘못 입력하는 것은 허용하지만 암호 해독 공격이 발생할 경우에는 계정이 잠기도록 **계정 잠금 임계값**을 구성합니다. 잘못된 로그온 시도 횟수를 EC 환경에서는 50번으로, SSLF 환경에서는 10번으로 설정하면 보안과 편리성을 어느 정도 만족시킬 수 있습니다. 이와 같이 구성하면 부주의로 인한 계정 잠금이 방지되고 지원 부서로의 지원 요청이 줄어들지만 위에 설명한 바와 같이 DoS 공격이 방지되지는 않습니다.
  
#### 다음 시간 후 계정 잠금 수를 원래대로 설정
  
이 정책 설정은 **계정 잠금 임계값**이 0으로 다시 설정되기까지의 시간을 결정합니다. 이 정책 설정의 기본값은 **정의되지 않음**입니다. **계정 잠금 임계값**을 정의한 경우 이 재설정 시간은 **계정 잠금 기간** 설정 값보다 작거나 같아야 합니다.
  
이 가이드에 정의된 EC 및 SSLF 환경 모두에 대해 **다음 시간 후 계정 잠금 수를 원래대로 설정** 값을 **15**분으로 구성합니다.
  
이 정책 설정을 기본값으로 두거나 너무 긴 간격으로 구성하면 DoS 공격을 받기 쉬워질 수 있습니다. 공격자는 악의적인 취지로 조직의 모든 사용자의 계정을 사용하여 로그온을 여러 번 실패할 수 있으며 이 경우 이 장 앞부분에 설명된 것처럼 계정이 잠깁니다. 계정 잠금을 다시 설정하도록 결정된 정책이 없으면 관리자가 모든 계정의 잠금을 직접 해제해야 합니다. 반대로, 이 정책 설정이 적당한 시간 값으로 구성되면 모든 계정의 잠금이 자동으로 해제될 때까지 정해진 기간 동안 사용자는 잠긴 상태가 됩니다. 권장되는 설정 값인 15분은 사용자가 수긍할 수 있는 타당한 시간이며 지원 부서에 대한 문의 횟수를 최소화하는 데도 도움이 됩니다. 또한 사용자들은 이 정책의 구성 방식을 제대로 이해하여 컴퓨터에 즉시 다시 액세스해야 할 경우에만 지원을 요청하도록 해야 합니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 사용자 권한 할당 설정
  
사용자 권한에 대해서는 3장 "Windows XP 클라이언트용 보안 설정"에 자세히 설명되어 있습니다. 그러나 **워크스테이션을 도메인에 추가** 사용자 권한은 모든 도메인 컨트롤러에 할당해야 하므로 이 장에서 설명됩니다. 구성원 서버 및 도메인 컨트롤러 설정에 대한 추가 정보는 *Windows* *Server 2003* *보안 가이드*의 4장 및 5장에서 찾을 수 있습니다.
  
#### 워크스테이션을 도메인에 추가
  
이 정책 설정을 사용하여 특정 도메인에 컴퓨터를 추가할 수 있습니다.
  
**표 2.3 사용자 권한 할당 설정 권장 사항**

 
<p> </p><table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >설정</th>
<th style="border:1px solid black;" >도메인 컨트롤러 기본값</th>
<th style="border:1px solid black;" >EC</th>
<th style="border:1px solid black;" >SSLF</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">워크스테이션을 도메인에 추가</td>
<td style="border:1px solid black;">Authenticated Users</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators</td>
</tr>
</tbody>
</table>
  
**워크스테이션을 도메인에 추가** 설정이 적용되려면 도메인의 모든 도메인 컨트롤러에 적용되는 GPO의 사용자에게 해당 권한이 할당되어야 합니다. 이 권한이 할당된 사용자는 최대 10개의 워크스테이션을 도메인에 추가할 수 있습니다. 특정 OU 또는 Active Directory의 컴퓨터 컨테이너에 대해 **컴퓨터 개체 만들기** 사용 권한이 할당된 사용자는 **워크스테이션을 도메인 추가** 사용자 권한이 할당되었는지 여부에 관계없이 컴퓨터를 도메인에 가입하고 도메인에 컴퓨터를 무제한 추가할 수 있습니다.
  
기본적으로 **Authenticated Users** 그룹의 모든 사용자는 Active Directory 도메인에 컴퓨터 계정을 최대 10개까지 추가할 수 있습니다. 이러한 새 컴퓨터 계정은 컴퓨터 컨테이너에 만들어집니다.
  
Active Directory 도메인에서 각 컴퓨터 계정은 도메인 리소스를 인증하고 액세스할 수 있는 완전한 보안 사용자가 됩니다. 일부 조직에서는 일관성 있는 조직의 관리와 구축을 위해 Active Directory 환경의 컴퓨터 수를 제한하려고 합니다. 사용자가 도메인에 워크스테이션을 추가하도록 허용될 경우 이러한 관리 노력은 소용이 없게 됩니다. 또한 이 사용자 권한이 있으면 허가되지 않은 도메인 컴퓨터를 추가로 만들 수 있으므로 추적하기가 훨씬 더 어려운 활동을 수행할 수 있습니다.
  
이러한 이유로 **워크스테이션을 도메인에 추가** 사용자 권한은 이 가이드에 정의된 두 가지 환경에서 **Administrators** 그룹에만 부여됩니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 보안 옵션 설정
  
계정 정책은 기본 도메인 정책의 정책 설정과 같이 도메인 수준에서 연결된 GPO에서 정의해야 합니다. 도메인 컨트롤러를 포함하는 OU에 적용된 GPO에 다른 계정 정책이 설정되어 있더라도 도메인 컨트롤러는 항상 도메인 수준 GPO에서 계정 정책을 가져옵니다.
  
계정 정책과 비슷한 세 가지 보안 옵션 설정을 도메인 수준에서 고려해야 합니다. 그룹 정책 개체 편집기의 다음 위치에서 이러한 보안 옵션 설정을 구성할 수 있습니다.
  
**컴퓨터 구성\\Windows 설정\\보안 설정\\로컬 정책\\보안 옵션**
  
다음 표는 이 가이드에 정의된 두 가지 유형의 보안 환경에 대한 보안 옵션 설정 권장 사항을 요약해서 보여 줍니다. 각 설정에 대한 자세한 내용은 다음 하위 섹션에 제공됩니다.
  
**표 2.4 보안 옵션 설정 권장 사항**

 
<p> </p><table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >설정</th>
<th style="border:1px solid black;" >도메인 구성원 기본값</th>
<th style="border:1px solid black;" >EC</th>
<th style="border:1px solid black;" >SSLF</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft 네트워크 서버: 로그온 시간이 만료되면 클라이언트 연결 끊기</td>
<td style="border:1px solid black;">정의되지 않음</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">네트워크 액세스: 익명 SID/이름 변환 허용</td>
<td style="border:1px solid black;">정의되지 않음</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">네트워크 보안: 로그온 시간이 만료되면 강제로 로그오프</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
#### Microsoft 네트워크 서버: 로그온 시간이 만료되면 클라이언트 연결 끊기
  
이 정책 설정은 사용자 계정의 유효한 로그온 시간을 초과하여 로컬 네트워크에 연결되어 있는 사용자의 연결을 끊을지를 결정합니다. 이 정책 설정은 SMB(서버 메시지 블록) 구성 요소에 영향을 미칩니다. 이 정책 설정을 사용하면 SMB 서비스를 사용하는 클라이언트의 로그온 시간이 만료될 경우 해당 클라이언트 컴퓨터 세션 연결이 강제로 끊어지게 됩니다. 이 정책을 사용하지 않으면 연결이 설정된 클라이언트의 로그온 시간이 만료된 후에도 해당 클라이언트 컴퓨터 세션이 계속될 수 있습니다. 이 정책 설정을 사용할 때는 반드시 **네트워크 보안: 로그온 시간이 만료되면 강제로 로그오프** 설정도 사용해야 합니다.
  
**참고**:서버 메시지 블록은 Windows 네트워크에서 공유되는 리소스의 기반이 됩니다. 따라서 SMB에 영향을 주는 설정은 폴더 및 프린터와 같은 공유 리소스에도 영향을 줍니다.
  
조직에서 사용자의 로그온 시간을 구성한 경우에는 **Microsoft 네트워크 서버: 로그온 시간이 만료되면 클라이언트 연결 끊기** 설정을 사용하는 것이 바람직합니다. 이 설정을 사용하지 않으면 자신의 로그온 시간을 초과하여 네트워크 리소스에 액세스할 수 없도록 지정된 사용자가 실제로는 허용된 시간 동안 설정된 세션을 통해 해당 리소스에 계속 액세스할 수도 있습니다.
  
조직에서 로그온 시간을 사용하지 않을 경우에는 이 정책 설정을 사용해도 아무런 영향을 주지 않습니다. 로그온 시간을 사용하면 해당 로그온 시간이 만료될 때 사용자 세션이 종료됩니다.
  
#### 네트워크 액세스: 익명 SID/이름 변환 허용
  
**네트워크 액세스: 익명 SID/이름 변환 허용** 설정은 익명 사용자가 다른 사용자의 SID를 요청할 수 있는지를 결정합니다. 도메인 컨트롤러에 대해 이 정책 설정을 사용하면 관리자의 SID 특성을 알고 있는 사용자가 이 정책 설정을 사용하는 컴퓨터에 연결하여 해당 SID로 관리자의 계정 정보를 알아낼 수 있습니다. 그런 다음 해당 계정을 사용하여 암호 추측 공격을 시작할 수 있습니다. *구성원 컴퓨터*의 기본 설정은 **사용 안 함**이지만 *도메인 컨트롤러*의 기본 설정은 **사용**입니다. 이 정책 설정을 사용하지 않으면 다음 시스템에서는 Windows Server 2003 기반 도메인과 통신하지 못할 수 있습니다.
  
-   Microsoft Windows NT® 4.0 기반의 원격 액세스 서비스 서버
  
-   Windows NT 3.*x* 또는 Windows NT 4.0 도메인에 위치한 Windows 2000 기반 컴퓨터에서 실행되는 원격 액세스 서비스 서버
  
-   Windows NT 3.*x* 기반 또는 Windows NT 4.0 기반 컴퓨터에서 실행되는 Microsoft SQL Server
  
-   Windows NT 3.*x* 또는 Windows NT 4.0 도메인에 위치한 Windows 2000 기반 컴퓨터에서 실행되는 SQL Server
  
-   파일, 공유 폴더 및 레지스트리 개체에 대한 액세스 권한을 Windows Server 2003 도메인 컨트롤러가 포함된 계정 도메인의 사용자 계정에 할당하려는 Windows NT 4.0 리소스 도메인의 사용자
  
#### 네트워크 보안: 로그온 시간이 만료되면 강제로 로그오프
  
**네트워크 보안: 로그온 시간이 만료되면 강제로 로그오프** 설정은 사용자 계정의 유효한 로그온 시간을 초과하여 로컬 네트워크에 연결되어 있는 사용자의 연결을 끊을지를 결정합니다. 이 정책 설정은 SMB 구성 요소에 영향을 미칩니다.
  
이 정책 설정을 사용하면 사용자의 로그온 시간이 만료되어 허용되는 다음 액세스 시간까지 시스템에 로그온할 수 없을 때 SMB 서버와의 클라이언트 컴퓨터 세션 연결이 끊어집니다. 이 정책 설정을 사용하지 않으면 설정된 클라이언트 컴퓨터 세션은 사용자의 로그온 시간이 만료된 후에도 유지됩니다. 이 정책 설정을 도메인 계정에 적용하려면 도메인 루트에 연결된 GPO에서 정의해야 합니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### Kerberos 정책
  
Kerberos 버전 5 인증 프로토콜을 위한 정책은 해당 도메인의 구성원 컴퓨터가 아니라 도메인 컨트롤러에 대해 구성됩니다. 이 정책은 티켓 수명 및 적용과 같은 Kerberos 프로토콜 관련 설정을 결정합니다. 로컬 컴퓨터 정책에는 Kerberos 설정이 없습니다. 대부분의 환경에서는 이러한 설정의 기본값을 변경하지 말아야 합니다. 이 설명서에서는 기본 Kerberos 정책을 변경하는 것에 대해서는 전혀 설명하지 않습니다. 이러한 설정에 대한 자세한 내용은 관련 가이드인 [*위협 및 대책: Windows Server 2003 및 Windows XP의 보안 설정*](http://go.microsoft.com/fwlink/?linkid=15159))을 참조하십시오. 이 가이드는 http://www.microsoft.com/korea/technet/security/topics/serversecurity/tcg/tcgch00.mspx에서 다운로드할 수 있습니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### OU 수준 그룹 정책
  
OU 수준 그룹 정책에 포함된 보안 설정은 해당 OU별로 고유해야 합니다. 이러한 설정에는 컴퓨터 설정과 사용자 설정이 모두 포함됩니다. 이 가이드에서는 관리 효율을 높이고 보안을 향상시키는 데 도움을 주기 위해 SRP(소프트웨어 제한 정책)에 대한 섹션을 다른 보안 설정과 분리해서 설명합니다. 6장 "Windows XP 클라이언트에 대한 소프트웨어 제한 정책"에서는 SRP에 대한 자세한 정보를 제공합니다.
  
#### 그룹 정책 보안 설정
  
작업 환경에서 Windows XP 컴퓨터의 각 범주에 대한 GPO를 만들어야 합니다. 이러한 컴퓨터 범주 각각에 대해 사용자 지정된 GPO를 적용하기 위해 이 가이드에서는 랩톱과 데스크톱을 별개의 OU로 나눕니다.
  
#### 소프트웨어 제한 정책 설정
  
작업 환경의 SRP 설정 구성을 위한 전용 GPO를 만듭니다. SRP 설정을 나머지 그룹 정책 설정과 별도로 유지해야만 하는 이유에는 두 가지가 있습니다. 한 가지는 SRP가 다른 그룹 정책 설정과 개념적으로 다르기 때문입니다. 옵션은 설정 또는 해제되고 값은 구성되지 않습니다. 대신 SRP를 사용할 경우 관리자는 제공될 응용 프로그램 집합, 적용될 제한 및 예외 처리 방식을 식별해야 합니다. 또 다른 이유는 프로덕션 환경에서 SRP 정책이 구현될 때 심각한 오류가 발생할 경우 빠르게 복구할 수 있다는 것입니다. 즉, 관리자는 다른 보안 설정에 영향을 주지 않으면서 SRP 설정이 정의된 GPO를 일시적으로 사용하지 않을 수 있습니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 그룹 정책 도구
  
Windows XP에 포함되어 있는 몇 가지 도구를 사용하면 GPO를 보다 쉽게 사용할 수 있습니다. 이 섹션에서는 이러한 도구 중 일부에 대한 간략히 설명합니다. 이러한 도구에 대한 자세한 내용은 Windows XP에서 온라인 도움말을 참조하십시오.
  
#### 그룹 정책 강제 업데이트
  
Active Directory에서 그룹 정책이 정기적으로 업데이트되긴 하지만 Windows XP Professional에 함께 제공되는 명령줄 도구인 Gpupdate를 사용하면 클라이언트 컴퓨터에서 해당 버전을 직접 업데이트할 수 있습니다. 이 도구는 클라이언트 컴퓨터에서 로컬로 실행해야 합니다.
  
이 도구를 사용하여 로컬 컴퓨터를 업데이트하려면 명령 프롬프트에서 다음을 실행합니다.
  
```  
gpupdate /force  
```  
Gpupdate를 실행하면 다음과 같은 확인 정보가 표시됩니다.
  
```  
C:\Documents and Settings\administrator.MSSLAB>gpupdate /force
Refreshing Policy...
User Policy Refresh has completed.
Computer Policy Refresh has completed.
To check for errors in policy processing, review the event log.
C:\Documents and Settings\administrator.MSSLAB> 
```  
사용자 기반 그룹 정책의 경우 로그오프했다가 정책 테스트를 위해 사용 중인 컴퓨터에 다시 로그온해야 합니다. 컴퓨터 정책은 즉시 업데이트되어야 합니다.
  
추가 Gpupdate 옵션을 보려면 명령 프롬프트에서 다음을 실행합니다.
  
```  
gpupdate /?  
```  
#### 정책 결과 집합 보기
  
Windows XP와 함께 제공되는 두 가지 도구를 사용하면 사용자 환경에서 컴퓨터에 적용된 정책과 그 정책이 적용된 시점 및 순서를 확인할 수 있습니다.
  
-   **RSoP 스냅인**. 이 도구(RSoP.msc)는 컴퓨터에 적용된 모든 정책의 집계 설정을 표시하는 MMC 스냅인입니다. 이 도구는 로컬로 또는 다른 컴퓨터에서 원격으로 실행할 수 있습니다. 각 정책 설정에 대해 RSoP 도구는 컴퓨터 설정과 원본 GPO를 보여 줍니다.
  
-   **Gpresult**. 그룹 정책이 최근에 컴퓨터에 적용된 시점과 컴퓨터에 적용된 GPO 및 그 순서에 대한 통계를 제공하는 명령줄 도구입니다. 이 도구는 필터링을 통해 적용된 모든 GPO에 대한 정보도 제공합니다. Gpesult 도구는 원격으로 또는 클라이언트 컴퓨터에서 로컬로 사용할 수 있습니다.
  
#### 그룹 정책 관리 콘솔
  
GPMC(그룹 정책 관리 콘솔)는 Windows Server 2003 SP1에서 선택적 구성 요소로 사용할 수 있는 MMC 스냅인입니다. 이 콘솔은 모든 그룹 정책 관련 작업을 관리하는 데 사용됩니다. GPMC는 GPO의 적용을 계획 및 준비하고 GPO를 배포하고 관련 보고서를 작성하고 스크립팅하고, 관련 문제를 해결하는 데 도움을 줍니다. 추가 정보는 [GPMC](http://www.microsoft.com/windowsserver2003/gpmc/default.mspx) 사이트(www.microsoft.com/windowsserver2003/gpmc/default.mspx)에서 찾을 수 있습니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 요약
  
그룹 정책은 Windows Server 2003 및 Windows 2000 도메인에서 사용자 및 컴퓨터 환경을 제어할 수 있는 Active Directory 기반 기능입니다. 작업 환경에서 Windows XP 데스크톱에 그룹 정책을 적용하려면 먼저 해당 도메인에서 특정 준비 작업을 수행해야 합니다.
  
작업 환경의 도메인 컨트롤러에 있는 GPO(그룹 정책 개체)에 저장된 그룹 정책 설정은 Active Directory 구조 안에 위치하는 사이트, 도메인 및 OU에 연결됩니다. 그룹 정책을 구현하기 전에 Active Directory 구조 및 그 구조 내에서 여러 가지 디자인 옵션을 구성하는 보안의 의미에 대해 알아야 합니다.
  
그룹 정책은 Windows XP 보안 유지에 필요한 도구입니다. 이 장에서는 그룹 정책을 사용하여 중앙에서 네트워크에 일관된 보안 정책을 적용하고 유지하는 방법을 자세히 설명했습니다.
  
또한 그룹 정책의 여러 다른 수준에 대한 정보와 환경에서 그룹 정책을 업데이트하는 데 사용할 수 있는 특수 도구에 대한 정보도 포함되어 있습니다.
  
#### 추가 정보
  
다음 링크에서는 Windows XP Professional 보안 관련 항목에 대한 추가 정보를 제공합니다.
  
-   Active Directory 관리 및 디자인에 대한 자세한 내용은 "[Active Directory의 관리 위임을 위한 디자인 고려 사항](http://www.microsoft.com/technet/prodtechnol/ad/windows2000/plan/addeladm.mspx)" 백서(www.microsoft.com/technet/prodtechnol/ad/windows2000/plan/addeladm.asp)를 참조하십시오.
  
-   Active Directory 디자인에 대한 자세한 내용은 "[Windows 네트워크를 관리하기 위한 최상의 Activie Directory 디자인](http://www.microsoft.com/technet/prodtechnol/ad/windows2000/plan/bpaddsgn.mspx)" 백서(www.microsoft.com/technet/prodtechnol/ad/windows2000/plan/bpaddsgn.asp)를 참조하십시오.
  
-   그룹 정책에 대한 자세한 내용은 "[그룹 정책 기능 집합을 이해하기 위한 단계별 지침](http://www.microsoft.com/technet/prodtechnol/windowsserver2003/technologies/directory/activedirectory/stepbystep/gpfeat.mspx)" 백서(www.microsoft.com/technet/prodtechnol/windowsserver2003/technologies/directory/  
    activedirectory/stepbystep/gpfeat.mspx)를 참조하고  
    Windows Server 2003 [그룹 정책](http://www.microsoft.com/windowsserver2003/technologies/management/grouppolicy/default.mspx) 홈 페이지(www.microsoft.com/windowsserver2003/technologies/management/grouppolicy/default.mspx)를 참조하십시오.
  
-   Windows XP 보안에 대한 자세한 내용은 "[Microsoft Windows XP Professional Resource Kit 설명서](http://www.microsoft.com/windowsxp/pro/techinfo/productdoc/resourcekit.asp)"(www.microsoft.com/WindowsXP/pro/techinfo/productdoc/resourcekit.asp)를 참조하십시오.
  
-   Windows XP의 보안 기능의 개요는 "[Windows XP Professional 및 Windows XP Home Edition의 새로운 보안 기능](http://www.microsoft.com/technet/prodtechnol/winxppro/evaluate/xpsec.mspx)" 백서(www.microsoft.com/technet/prodtechnol/winxppro/evaluate/xpsec.asp)를 참조하십시오.
  
-   관리 템플릿에 대한 자세한 내용은 "[레지스트리 기반 그룹 정책 구현](http://www.microsoft.com/windows2000/techinfo/howitworks/management/rbppaper.asp)" 백서(www.microsoft.com/windows2000/techinfo/howitworks/management/rbppaper.asp)를 참조하십시오.
  
-   GPMC(그룹 정책 관리 콘솔)에 대한 자세한 내용은 [GPMC](http://www.microsoft.com/windowsserver2003/gpmc/default.mspx) 사이트(www.microsoft.com/windowsserver2003/gpmc/default.mspx)를 참조하십시오.
  
-   그룹 업데이트 도구([Gpupdate](http://www.microsoft.com/technet/prodtechnol/winxppro/proddocs/refrgp.mspx))에 대한 자세한 내용은 www.microsoft.com/technet/prodtechnol/winxppro/proddocs/refrGP.asp를 참조하십시오.
  
-   RSoP([정책 결과 집합](http://www.microsoft.com/technet/prodtechnol/winxppro/proddocs/rspintro.mspx)) 도구에 대한 자세한 내용은 www.microsoft.com/technet/prodtechnol/winxppro/proddocs/RSPintro.asp를 참조하십시오.
  
-   그룹 정책 결과 도구([Gpresult](http://www.microsoft.com/technet/prodtechnol/winxppro/proddocs/gpresult.mspx))에 대한 자세한 내용은 www.microsoft.com/technet/prodtechnol/winxppro/proddocs/gpresult.asp를 참조하십시오.
  
-   Active Directory에서 권한을 위임하는 방법에 대한 자세한 내용은 사이트에서 *Windows 2000 Resource Kit*의 "[분산 보안](http://www.microsoft.com/resources/documentation/windows/2000/server/reskit/en-us/distrib/dsca_pt3_stbp.asp)" 계획 섹션(www.microsoft.com/resources/documentation/Windows/2000/server/reskit/en-us/distrib/  
    dsca\_pt3\_stbp.asp)을 참조하십시오.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
##### 다운로드
  
[Windows XP 보안 가이드 다운로드](http://go.microsoft.com/fwlink/?linkid=14840)
  
[](#mainsection)[페이지 위쪽](#mainsection)
