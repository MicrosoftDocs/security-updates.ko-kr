---
TOCTitle: 'MS06-MAR'
Title: 2006 년 3 월 Microsoft 보안 공지 요약
ms:assetid: 'ms06-mar'
ms:contentKeyID: 61230679
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms06-mar(v=Security.10)'
---

Security Bulletin Summary

2006 년 3 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2006년 3월 15일 수요일

**버전:** 1.0

[웹 사이트](http://www.microsoft.com/korea/security/)에서 제공됩니다.

**PC 보호:** 다음 사이트에서 PC를 보호하는 데 유용한 정보를 볼 수 있습니다.

-   [PC 보호 웹 사이트](http://www.microsoft.com/korea/athome/security/protect/)를 방문하십시오.
-   IT 전문가인 경우 [Security Guidance Center](http://www.microsoft.com/korea/technet/security/) 웹 사이트를 방문하십시오.

**업데이트 관리 전략:** [패치 관리, 보안 업데이트 및 다운로드](http://www.microsoft.com/korea/technet/security/topics/patchmanagement.mspx) 웹 사이트에서는 보안 업데이트를 적용하기 위한 최선의 권장 사항 및 자세한 관련 내용을 볼 수 있습니다.

**IT 전문가 보안 영역 커뮤니티:** [IT 전문가 보안 영역 웹 사이트](http://www.microsoft.com/korea/technet/community/default.asp)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

**Microsoft 보안 알림 서비스:** [Microsoft 보안 알림 서비스](http://www.microsoft.com/korea/technet/security/bulletin/notify.asp)에 가입하면 Microsoft 보안 공지가 업데이트될 때마다 전자 메일 알림을 자동으로 받을 수 있습니다.

#### 요약

여기에는 새로 발견된 취약점에 대한 업데이트가 들어 있으며 이러한 취약점은 다음 심각도로 분류됩니다.

긴급(1)
-------

<span></span>
| 공지 번호                  | Microsoft 보안 공지 MS06-012                                                                                                                                        |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점 (905413)**](http://technet.microsoft.com/security/bulletin/ms06-012)                                    |
| **요약**                   | Microsoft Office에 원격 코드 실행을 허용할 수 있는 취약점이 존재합니다.                                                                                             |
| **최대 심각도**            | [긴급](http://www.microsoft.com/korea/technet/security/policy/rating.asp)                                                                                           |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                      |
| **영향을 받는 소프트웨어** | **Office.** 자세한 내용은 [전문가용 게시판](http://technet.microsoft.com/security/bulletin/ms06-012)에서 영향을 받는 소프트웨어 및 다운로드 위치 절을 참조하십시오. |

중요(1)
-------

<span></span>
| 공지 번호                  | Microsoft 보안 공지 MS06-011                                                                                                                                         |
|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**필요 이상의 사용 권한을 허용하는 Windows 서비스 DACL로 인한 권한 상승 문제점 (914798)**](http://technet.microsoft.com/security/bulletin/ms06-011)                 |
| **요약**                   | 유효한 로그온 자격 증명을 가진 사용자가 시스템을 완전히 제어할 수 있는 권한 상승 취약점이 존재합니다.                                                                |
| **최대 심각도**            | [중요](http://www.microsoft.com/korea/technet/security/policy/rating.asp)                                                                                            |
| **취약점으로 인한 영향**   | 권한 상승                                                                                                                                                            |
| **영향을 받는 소프트웨어** | **Windows.** 자세한 내용은 [전문가용 게시판](http://technet.microsoft.com/security/bulletin/ms06-011)에서 영향을 받는 소프트웨어 및 다운로드 위치 절을 참조하십시오. |

배포
----

<span></span>
**Software Update Services:**

관리자는 Microsoft Software Update Services(SUS)를 사용하여 Windows 2000 및 Windows Server 2003 기반 서버 그리고 Windows 2000 Professional 또는 Windows XP Professional을 실행하는 데스크톱 시스템에 최신 중요 업데이트와 보안 업데이트를 신속하고 안전하게 배포할 수 있습니다.

Software Update Services에서 이 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Software Update Services 웹 사이트](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/previous/default.mspx)를 참조하십시오.

**Windows Server Update Services:**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services 웹 사이트](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)를 방문하십시오.

**Systems Management Server:**

Microsoft Systems Management Server(SMS)는 업데이트 관리를 위해 효율적으로 구성할 수 있는 기업용 솔루션을 제공합니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 해당 업데이트를 효율적으로 배포할 수 있습니다. 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리 웹 사이트 (영문)](http://go.microsoft.com/fwlink/?linkid=22939)를 참조하십시오. SMS 2.0 사용자는 [Software Updates Service 기능 팩 (영문)](http://go.microsoft.com/fwlink/?linkid=33340)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [SMS 웹 사이트](http://www.microsoft.com/korea/smserver/)를 참조하십시오.

**참고** SMS에서는 Microsoft Baseline Security Analyzer와 Microsoft Office 탐지 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 이러한 도구로 일부 소프트웨어 업데이트를 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [여기 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**QChain.exe 및 Update.exe:**

Microsoft에서 제공하는 명령 줄 도구인 QChain.exe를 사용하면 관리자는 보안 업데이트를 안전하게 체인화할 수 있습니다. *체인 작업*은 각 업데이트마다 다시 시작할 필요 없이 여러 개의 업데이트를 설치하는 것을 의미합니다. 여기에 설명되어 있는 업데이트에 사용되는 Update.exe는 체인 기능을 기본적으로 포함하고 있으므로 Windows 2000 서비스 팩 2 이상, Windows XP 또는 Windows Server 2003을 사용하는 고객은 Qchain.exe를 사용하여 이러한 업데이트를 체인화하지 않아도 됩니다. 그러나 Qchain.exe는 관리자가 모든 플랫폼에 대해 일관된 배포 스크립트를 만들 수 있도록 Windows Updates에 대한 체인화를 지원합니다. Qchain에 대한 자세한 내용은 이 [웹 사이트 (영문)](http://go.microsoft.com/fwlink/?linkid=21156)를 참조하십시오.

**Microsoft Baseline Security Analyzer:**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer 웹 사이트](http://www.microsoft.com/korea/technet/security/tools/mbsahome.asp)를 방문하십시오.

**검색 및 배포 지침:**

Microsoft는 이 달의 보안 업데이트를 위한 검색 및 배포 지침을 제공하였습니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), Extended Security Update Inventory Tool 및 Enterprise Update Scan Tool(EST) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](http://support.microsoft.com/kb/910723)을 참조하십시오.

#### 기타 정보:

**감사의 말**

[감사](http://www.microsoft.com/korea/technet/security/bulletin/policy.asp)드립니다.

-   [MS06-011](http://technet.microsoft.com/security/bulletin/ms06-011)에서 설명한 문제점을 해결하기 위해 협력해 주신 [SIA Group (영문)](http://www.siainternational.com/)의 Andres Tarasco.
-   [MS06-012](http://technet.microsoft.com/security/bulletin/ms06-012)에서 설명한 문제점을 보고해 주신 [Symantec (영문)](http://symantec.com/)의 Ollie Whitehouse.
-   [MS06-012](http://technet.microsoft.com/security/bulletin/ms06-012)에서 설명한 문제점을 해결하기 위해 협력해 주신 [FelicioX](mailto:feliciox@gmail.com).
-   [MS06-012](http://technet.microsoft.com/security/bulletin/ms06-012)에서 설명한 문제점을 보고해 주신 [NGS Software (영문)](http://www.ngssoftware.com/index.htm)의 Peter Winter-Smith.
-   [MS06-012](http://technet.microsoft.com/security/bulletin/ms06-012)에서 설명한 문제점을 보고해 주신 [Fortinet Security Response Team (영문)](http://www.fortinet.com/)의 Dejun.
-   [MS06-012](http://technet.microsoft.com/security/bulletin/ms06-012)에서 설명한 문제점을 보고해 주신 [TippingPoint (영문)](http://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/).
-   [MS06-012](http://technet.microsoft.com/security/bulletin/ms06-012)에서 설명한 문제점을 보고해 주신 [XFOCUS Security Team (영문)](http://www.xfocus.org/)의 Eyas.

**기타 보안 관련 업데이트 받기:**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서 다운로드할 수 있으며 "security\_patch"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   [Microsoft Update 웹 사이트](http://go.microsoft.com/fwlink/?linkid=40747)에서 구할 수 있습니다.

**지원:**

-   기술 지원은 1577-9700 (국내), 82-2-567-7881 (해외)을 통해 [고객지원센터](http://go.microsoft.com/fwlink/?linkid=21131)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 기술 지원 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

**보안 관련 자료:**

-   [Microsoft TechNet Security](http://www.microsoft.com/korea/technet/security/) 웹 사이트에서 Microsoft 제품의 보안에 관한 추가 정보를 제공합니다.
-   [Microsoft Software Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/previous/default.mspx)
-   [Microsoft Windows Server Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)
-   [MBSA(Microsoft Baseline Security Analyzer)](http://www.microsoft.com/korea/technet/security/tools/mbsahome.asp)
-   [Windows Update](http://update.microsoft.com/microsoftupdate/)
-   [Microsoft Update](http://update.microsoft.com/microsoftupdate)
-   Windows Update 카탈로그: Windows Update 카탈로그에 대한 자세한 내용은 Microsoft 기술 자료 문서 [323166](http://support.microsoft.com/?kbid=323166)을 참조하십시오.
-   [Office 업데이트](http://office.microsoft.com/ko-kr/officeupdate/default.aspx)

**부인:**

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

**개정판:**

-   V1.0(2006년 3월 15일): 공지가 게시되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
