---
TOCTitle: 'MS04-NOV'
Title: 2004 년 11 월 Microsoft 보안 공지 요약
ms:assetid: 'ms04-nov'
ms:contentKeyID: 61230659
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms04-nov(v=Security.10)'
---

2004 년 11 월 Microsoft 보안 공지 요약
======================================

게시된 날짜: 2004년 11월 10일 수요일

**버전:** 1.0

**게시된 날짜:** 2004년 11월 10일
**버전 번호:** 1.0

이 정보의 최종 사용자 버전은 [여기](https://www.microsoft.com/korea/security/security_bulletins/200411_isa.asp)를 참조하십시오.

**PC 보호:** Microsoft는 PC 보호 방법에 대한 정보를 제공합니다.

-   최종 사용자의 경우 [PC 보호 웹 사이트](https://www.microsoft.com/korea/security/protect/default.asp)를 방문하십시오.
-   IT 전문가인 경우 [Security Guidance Center](https://www.microsoft.com/korea/security/guidance/default.mspx) 웹 사이트를 방문하십시오.

**업데이트 관리 전략:** [패치 관리, 보안 업데이트 및 다운로드](https://www.microsoft.com/korea/technet/security/topics/patch/default.asp) 웹 사이트에서는 보안 업데이트를 적용하기 위한 최선의 권장 사항과 관련된 자세한 내용을 볼 수 있습니다.

**IT 전문가 보안 영역 커뮤니티:** [IT 전문가 보안 영역 웹 사이트](https://www.microsoft.com/korea/technet/security/community/default.asp)는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

**Microsoft 보안 알림 서비스:** [Microsoft 보안 알림 서비스](https://www.microsoft.com/korea/technet/security/bulletin/notify.asp)에 가입하면 Microsoft 보안 게시판이 업데이트될 때마다 자동 전자 메일 알림을 받을 수 있습니다.

#### 요약

여기에는 새로 발견된 취약점에 대한 업데이트가 들어 있으며 이들 취약점은 다음의 위험 등급으로 분류됩니다.

중요(1)
-------

<span></span>
| 게시판 ID                  | Microsoft Security Bulletin MS04-039                                                                                                                    |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| **게시판 제목**            | ISA Server 2000 및 Proxy Server 2.0의 취약점으로 인한 인터넷 콘텐츠 스푸핑 허용 문제(888258)                                                            |
| **요약**                   | 이 취약점으로 인해 침입자가 신뢰할 수 있는 인터넷 콘텐츠를 스푸핑할 수 있습니다.                                                                        |
| **최대 위험 등급**         | [중요](https://www.microsoft.com/korea/technet/security/policy/rating.asp)                                                                               |
| **취약점으로 인한 영향**   | 스푸핑                                                                                                                                                  |
| **영향을 받는 소프트웨어** | 자세한 내용은 [전문가용 게시판](https://technet.microsoft.com/security/bulletin/ms04-039)에서 영향을 받는 소프트웨어 및 다운로드 위치 절을 참조하십시오. |

배포
----

<span></span>
**Systems Management Server:**

Microsoft Systems Management Server(SMS)는 업데이트 관리를 위해 효율적으로 구성할 수 있는 엔터프라이즈 솔루션을 제공합니다. SMS를 사용하면 관리자는 보안 업데이트가 필요한 Windows 기반 시스템을 식별하고, 사용자의 업무 중단을 최소화하면서 엔터프라이즈 전체에 해당 업데이트를 효율적으로 배포할 수 있습니다. 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리 웹 사이트](https://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.asp)를 참조하십시오. SMS 2.0 사용자는 [Software Updates Service 기능 팩 (US)](https://go.microsoft.com/fwlink/?linkid=33340)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 내용은 [SMS 웹 사이트](https://www.microsoft.com/korea/smserver/default.asp)를 참조하십시오.

**참고** SMS에서는 Microsoft Baseline Security Analyzer와 Microsoft Office Detection Tool을 사용하여 보안 게시판 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 이러한 도구로 일부 소프트웨어 업데이트를 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [여기 (US)](https://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업에는 시스템을 다시 시작한 후에 관리자 권한이 필요합니다. 관리자는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있으며, 이 도구는 [SMS 2003 Administration 기능 팩 (US)](https://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration 기능 팩 (US)](https://go.microsoft.com/fwlink/?linkid=21161)에서 구할 수 있습니다.

#### 기타 정보:

**감사의 말**

고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://www.microsoft.com/korea/technet/security/bulletin/policy.asp)드립니다.

-   스푸핑 취약점을 발견해 주신 Info Support의 Martijn de Vries님과 스푸핑 취약점(CAN-2004-0892)을 보고해 주신 Info Support의 Thomas de Klerk님

**기타 보안 관련 업데이트 입수:**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터 (US)](https://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security\_patch"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   각 사용자 플랫폼에 맞는 업데이트는 [Windows Update 웹 사이트](https://windowsupdate.microsoft.com/)에서 구할 수 있습니다.

**지원:**

-   기술 지원은 02-3468-7200을 통해 [Microsoft 고객기술지원부](https://support.microsoft.com/directory/question.asp?sd=gn&fr=0)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 기술 지원 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

**보안 관련 자료:**

-   [Microsoft TechNet Security](https://www.microsoft.com/korea/security/default.asp) 웹 사이트에서 Microsoft 제품의 보안에 관한 추가 정보를 제공합니다.
-   [Microsoft Software Update Services](https://www.microsoft.com/technet/security/bulletin/korea/windowsserversystem/sus/default.asp)
-   [MBSA(Microsoft Baseline Security Analyzer)](https://www.microsoft.com/korea/technet/security/tools/mbsahome.asp)
-   [Windows Update](https://windowsupdate.microsoft.com/)
-   Windows Update 카탈로그: Windows Update 카탈로그에 대한 자세한 내용은 Microsoft 기술 자료 문서 [323166](https://support.microsoft.com/default.aspx?scid=kb;en-us;323166)을 참조하십시오.
-   [Office 업데이트](https://go.microsoft.com/fwlink/?linkid=21135)

**알림:**

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실이나 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제나 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

**개정판:**

-   V1.0(2004년 11월 10일): 게시판에 게시

*Built at 2014-04-18T12:27:44Z-07:00*
