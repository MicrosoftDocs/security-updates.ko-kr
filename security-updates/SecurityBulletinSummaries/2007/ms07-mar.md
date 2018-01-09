---
TOCTitle: 'MS07-MAR'
Title: 2007 년 3 월 Microsoft 보안 공지 요약
ms:assetid: 'ms07-mar'
ms:contentKeyID: 61230691
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms07-mar(v=Security.10)'
---

Security Bulletin Summary

2007 년 3 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2007년 3월 13일 화요일

**버전:** 1.0

이 공지 요약 목록에는 2007년 3월 릴리스된 보안 공지가 포함되어 있습니다.

**보안 센터:** 다음 웹 사이트에서 PC를 보호하는 데 유용한 정보를 볼 수 있습니다.

-   일반 사용자는 [가정의 보안](http://www.microsoft.com/korea/athome/security/default.mspx)을 방문하거나 “최신 보안 업데이트”를 클릭하여 이 정보를 볼 수도 있습니다.
-   IT 전문가는 [TechNet Security Center](http://www.microsoft.com/korea/technet/security/default.mspx)를 참조하십시오.

**업데이트 관리 전략:**  [패치 관리를 위한 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**IT 전문가 보안 영역 커뮤니티:** [IT 전문가 보안 커뮤니티 (영문)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

**Microsoft 보안 알림 서비스:** [Microsoft 기술 보안 알림](http://www.microsoft.com/korea/technet/security/bulletin/notify.asp)에 가입하면 Microsoft 보안 공지가 업데이트될 때마다 자동 메일 알림을 받을 수 있습니다.

#### 보안 업데이트

Microsoft는 2007년 3월 13일 보안 공지를 릴리스하지 않았습니다.

배포
----

<span></span>
**Software Update Services:**

관리자는 Microsoft Software Update Services(SUS)를 사용하여 Windows 2000 및 Windows Server 2003 기반 서버 그리고 Windows 2000 Professional 또는 Windows XP Professional을 실행하는 데스크톱 시스템에 최신 중요 업데이트와 보안 업데이트를 신속하고 안전하게 배포할 수 있습니다.

Software Update Services를 통해 이 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Software Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/previous/default.mspx)를 참조하십시오.

**Windows Server Update Services:**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)를 참조하십시오.

**Systems Management Server:**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.asp)를 참조하십시오. SMS 2.0 사용자는[Software Updates Service 기능 팩 (영문)](http://go.microsoft.com/fwlink/?linkid=33340)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://www.microsoft.com/korea/smserver/)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer와 Microsoft Office 검색 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**Microsoft Baseline Security Analyzer:**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://www.microsoft.com/korea/technet/security/tools/mbsahome.asp)를 방문하십시오.

**검색 및 배포 지침:**

Microsoft는 보안 업데이트에 대한 추가 탐지 및 배포 가이드를 제공합니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), Extended Security Update Inventory Tool 및 Enterprise Update Scan Tool(EST) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](http://support.microsoft.com/kb/910723/ko)을 참조하십시오.

#### 기타 정보:

**Microsoft Windows 악성 소프트웨어 제거 도구:**

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 릴리스했습니다.

이 도구는 Software Update Services(SUS)를 통해 배포되지 않습니다.

**MU, WU, WSUS 및 SUS의 비보안 중요 업데이트:**

-   Microsoft는 Microsoft Update(MU) 및 Windows Server Update Services(WSUS)를 통해 2개의 **비보안**, 중요 업데이트를 릴리스했습니다.
-   Microsoft는 Windows Update(WU) 및 Software Update Services(SUS)를 통해 4개의 Windows용 **비보안**, 중요 업데이트를 릴리스했습니다.

이 정보는 보안 공지 요약과 같은 날짜에 Microsoft Update, Windows Update, Windows Server Update Services, Software Update Services를 통해 릴리스된 **비보안**, 중요 업데이트에만 해당됩니다. 다른 날짜에 릴리스된 **비보안** 업데이트 관련 정보는 제공되지 않습니다.

**기타 보안 관련 업데이트 받기:**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서 다운로드할 수 있으며 "security\_patch"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.

**지원:**

-   기술 지원은 1577-9700을 통해 [Microsoft 고객지원센터](http://go.microsoft.com/fwlink/?linkid=21131)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://support.microsoft.com/common/international.aspx)에 나와 있습니다.

**보안 관련 자료:**

-   [TechNet Security Center](http://www.microsoft.com/korea/technet/security/)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다.
-   [Microsoft Software Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/previous/default.mspx)
-   [Microsoft Windows Server Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)
-   [MBSA(Microsoft Baseline Security Analyzer)](http://www.microsoft.com/korea/technet/security/tools/mbsahome.asp)
-   [Microsoft Update](http://update.microsoft.com/microsoftupdate/)
-   [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)
-   Windows Update 카탈로그: Windows Update 카탈로그에 대한 자세한 내용은 [Microsoft 기술 자료 문서 323166](http://support.microsoft.com/kb/323166/ko)을 참조하십시오.
-   [Office 업데이트](http://office.microsoft.com/ko-kr/officeupdate/default.aspx)

**부인:**

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

**개정판:**

-   V1.0 (2007년 3월 13일): 공지 요약이 게시되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
