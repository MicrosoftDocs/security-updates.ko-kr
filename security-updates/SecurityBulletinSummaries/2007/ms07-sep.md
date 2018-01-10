---
TOCTitle: 'MS07-SEP'
Title: 2007 년 9 월 Microsoft 보안 공지 요약
ms:assetid: 'ms07-sep'
ms:contentKeyID: 61230695
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms07-sep(v=Security.10)'
---

2007 년 9 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2007년 9월 11일 화요일 | 업데이트된 날짜: 2007년 9월 12일 수요일

**버전:** 1.1

이 공지 요약 목록에는 2007년 9월 발표된 보안 공지가 포함되어 있습니다.

2007년 9월 공지 발표와 함께 이 공지 요약이 2007년 9월 6일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2007년 9월 12일 수요일(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [9월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344690&eventcategory=4&culture=en-us&countrycode=us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

#### 요약

이번 달의 보안 공지는 다음과 같습니다(심각도 순).

긴급(1)
-------


| 공지 번호                  | Microsoft 보안 공지 MS07-051                                                                                                                                                                                                                                                                                                                                             |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft Agent의 취약점으로 인한 원격 코드 실행 문제점(938827)**](http://technet.microsoft.com/security/bulletin/ms07-051)                                                                                                                                                                                                                                           |
| **요약**                   | 이 긴급 보안 업데이트는 비공개적으로 보고된 취약점을 해결합니다. Microsoft Agent에서 특수하게 조작된 특정 URL을 처리하는 방식에 원격 코드 실행 취약점이 존재합니다. 취약점을 통해 공격자는 영향 받는 시스템에서 코드를 원격으로 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                            |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                           |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 합니다.                                                                                                                                                                                                                |
| **영향을 받는 소프트웨어** | **Windows** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                   |

중요 (3)
--------


| 공지 번호                  | Microsoft 보안 공지 MS07-052                                                                                                                                                                                                                                                                |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Visual Studio용 Crystal Reports의 취약점으로 인한 원격 코드 실행 문제점(941522)**](http://technet.microsoft.com/security/bulletin/ms07-052)                                                                                                                                              |
| **요약**                   | 이 중요 보안 업데이트는 일반에 공개된 취약점 1건을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 RPT 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [중요](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                               |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                              |
| **검색**                   | Microsoft Baseline Security Analyzer 및 EST(Enterprise Update Scan Tool)로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 할 수 있습니다.                                                                                       |
| **영향을 받는 소프트웨어** | **Visual Studio.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                               |

| 공지 번호                  | Microsoft 보안 공지 MS07-053                                                                                                                                                                                                                                           |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**UNIX용 Windows 서비스의 취약점으로 인한 권한 상승 문제점(939778)**](http://technet.microsoft.com/security/bulletin/ms07-053)                                                                                                                                        |
| **요약**                   | 이 중요 보안 업데이트는 공개적으로 보고된 취약점 1건을 해결합니다. UNIX용 Windows 서비스 3.0, UNIX용 Windows 서비스 3.5 및 UNIX 기반 응용 프로그램용 하위 시스템에 취약점이 존재하며, 특정 setuid 바이너리 파일을 실행하는 경우 공격자 권한 상승이 발생할 수 있습니다. |
| **최대 심각도**            | [중요](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                          |
| **취약점으로 인한 영향**   | 권한 상승                                                                                                                                                                                                                                                              |
| **검색**                   | Microsoft Baseline Security Analyzer 및 EST(Enterprise Update Scan Tool)로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 합니다.                                                                          |
| **영향을 받는 소프트웨어** | **UNIX용 Windows 서비스, UNIX 기반 응용 프로그램용 하위 시스템.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                           |

| 공지 번호                  | Microsoft 보안 공지 MS07-054                                                                                                                                                                                                                                                                                                                                                                                                   |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**MSN Messenger 및 Windows Live Messenger의 취약점으로 인한 원격 코드 실행 문제점(942099)**](http://technet.microsoft.com/security/bulletin/ms07-054)                                                                                                                                                                                                                                                                         |
| **요약**                   | 이 보안 업데이트는 일반에 공개된 MSN Messenger 및 Windows Live Messenger의 취약점을 해결합니다. 공격자가 보낸 웹캠 또는 화상 채팅 초대를 사용자가 수락하면 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 성공적으로 악용한 경우 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [중요](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                  |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **검색**                   | 이러한 제품은 업데이트의 자동 검색 및 배포 메커니즘이 포함되어 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 할 수 있습니다.                                                                                                                                                                                                                                                                                         |
| **영향을 받는 소프트웨어** | **MSN Messenger, Windows Live Messenger.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                          |

검색, 배포 도구 및 지침
-----------------------


**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center (영문)](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://www.microsoft.com/korea/technet/security/default.mspx)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안 (영문)](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 “최신 보안 업데이트”를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 및 [Office 업데이트](http://go.microsoft.com/fwlink/?linkid=21135)에서 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서도 다운로드할 수 있으며 "security\_patch"라는 키워드를 사용하여 쉽게 찾을 수 있습니다. 마지막으로, 보안 업데이트는 Windows Update 카탈로그에서 다운로드할 수 있습니다. Windows Update 카탈로그에 대한 자세한 내용은 [Microsoft 기술 자료 문서 323166](http://support.microsoft.com/kb/323166)을 참조하십시오.

**검색 및 배포 지침**

Microsoft는 이 달의 보안 업데이트를 위한 검색 및 배포 지침을 제공하였습니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), Extended Security Update Inventory Tool 및 Enterprise Update Scan Tool(EST) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](http://support.microsoft.com/kb/910723)을 참조하십시오.

**Microsoft Baseline Security Analyzer 및** **Update** **Update Scan Tool)**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer (영문)](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

MBSA 1.2.1에서 보안 업데이트 검색을 지원할 수 없는 경우 해당 보안 업데이트 검색에 사용할 수 있도록 EST(Enterprise Update Scan Tool)가 발표되었습니다. EST에 대한 자세한 내용은 [Enterprise Update Scan Tool](http://support.microsoft.com/default.aspx?id=894193)을 참조하십시오.

**참고** 2007년 10월 9일 이후부터 MBSA 1.2.1에서 사용되는 MSSecure.XML 파일이 더 이상 업데이트되지 않습니다. 이 날짜 이후부터는 MBSA 1.2.1에서 사용되는 MSSecure.XML 파일에 새 보안 업데이트가 추가되지 않으며 EST(Enterprise Scan Tool)의 새 버전도 발표되지 않습니다. 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer (영문)](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services (영문)](http://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.mspx)를 참조하십시오. SMS 2.0 사용자는[Software Updates Service Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=33340)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer와 Microsoft Office 검색 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack(영문)](http://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack(영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

이달의 업데이트:

-   Microsoft는 Microsoft Update(MU) 및 Windows Server Update Services(WSUS)를 통해 **비보안**, 중요 업데이트를 0건 발표했습니다.
-   Microsoft는 Windows Update(WU)를 통해 Windows용 **비보안**, 중요 업데이트를 0건 발표했습니다.

이 정보는 보안 공지 요약과 같은 날짜에 Microsoft Update, Windows Update, Windows Server Update Services를 통해 발표된 **비보안**, 중요 업데이트에만****해당됩니다. 다른 날짜에 발표된 **비보안** 업데이트 관련 정보는 제공되지****않습니다.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[패치 관리를 위한 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서 다운로드할 수 있으며 "security\_patch"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티) (영문)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://technet.microsoft.com/security/bulletin/policy)드립니다.

-   [MS07-051](http://technet.microsoft.com/security/bulletin/ms07-051)에서 설명한 문제점을 보고해 주신 [Assurent Secure Technologies (영문)](http://www.assurent.com/)의 Vulnerability Research 팀
-   [MS07-051](http://technet.microsoft.com/security/bulletin/ms07-051)에서 설명한 문제점을 보고해 주신 [Palo Alto Networks (영문)](http://www.paloaltonetworks.com/)의 Yamata Li
-   [MS07-051](http://technet.microsoft.com/security/bulletin/ms07-051)에서 설명한 문제점을 보고해 주신 [iDefense VCP (영문)](http://labs.idefense.com/)의 익명 연구자
-   [MS07-053](http://technet.microsoft.com/security/bulletin/ms07-053)에서 보고된 문제점을 해결하기 위해 협력해 주신 WolfeReiter의 Brian A. Reiter
-   [MS07-054](http://technet.microsoft.com/security/bulletin/ms07-054)에서 설명한 문제점을 보고해 주신 [team 509 (중문)](http://www.team509.com/)의 Woo Shi

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 1577-9700을 통해 [Microsoft 고객 지원 센터](http://go.microsoft.com/fwlink/?linkid=21131)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정판

-   V1.0 (2007년 9월 11일): 공지 요약이 게시되었습니다.
-   V1.1 (2007년 9월 12일): MS07-045에 대해 다시 시작 요구 사항이 변경되고 다운로드 링크가 추가되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
