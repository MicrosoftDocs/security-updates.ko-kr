---
TOCTitle: 'MS07-JUL'
Title: 2007 년 7 월 Microsoft 보안 공지 요약
ms:assetid: 'ms07-jul'
ms:contentKeyID: 61230689
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms07-jul(v=Security.10)'
---

2007 년 7 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2007년 7월 11일 수요일 | 업데이트된 날짜: 2008년 3월 26일 수요일

**버전:** 2.0

이 공지 요약 목록에는 2007년 7월 릴리스된 보안 공지가 포함되어 있습니다.

2007년 7월 공지 릴리스와 함께 이 공지 요약이 2007년 7월 5일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2007년 7월 12일 목요일(대한민국 표준시)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [7월 보안 공지 웹캐스트에 지금 등록하십시오](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032343783&eventcategory=4&culture=ko-kr&countrycode=kr). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

#### 요약

이번 달의 보안 공지는 다음과 같습니다(심각도 순).

긴급(3)
-------


| 공지 번호                  | Microsoft 보안 공지 MS07-036                                                                                                                                                                                                                                                                                                                                      |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft Excel의 취약점으로 인한 원격 코드 실행 문제점(936542)**](http://technet.microsoft.com/security/bulletin/ms07-036)                                                                                                                                                                                                                                    |
| **요약**                   | 이 긴급 업데이트는 일반에 공개된 취약점 1건, 비공개적으로 보고된 취약점 2건 및 조사 과정에서 확인된 기타 보안 문제점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 Excel 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                     |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                    |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 적용하기 위해 다시 시작할 필요는 없습니다.                                                                                                                                                                                                      |
| **영향을 받는 소프트웨어** | **Office, Excel**. 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                     |

| 공지 번호                  | Microsoft 보안 공지 MS07-039                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Windows Active Directory의 취약점으로 인한 원격 코드 실행 문제점(926122)**](http://technet.microsoft.com/security/bulletin/ms07-039)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **요약**                   | 이 긴급 보안 업데이트는 비공개적으로 보고된 취약점을 해결합니다. 이 취약점은 Windows 2000 Server 및 Windows Server 2003에 구현된 Active Directory에서 발견되었으며 원격 코드 실행 또는 서비스 거부 조건을 허용할 수 있습니다. 이 취약점을 악용하려는 공격은 대부분 서비스 거부 상태를 유발합니다. 그러나 원격 코드 실행은 가능합니다. Windows Server 2003의 경우 공격자가 이 취약점을 악용하려면 유효한 로그온 자격 증명을 갖고 있어야 합니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 새 계정을 만들 수도 있습니다. |
| **최대 심각도**            | [긴급](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 합니다.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **영향을 받는 소프트웨어** | **Windows** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |

| 공지 번호                  | Microsoft 보안 공지 MS07-040                                                                                                                                                                                                                                                                                                                                                       |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**.NET Framework의 취약점으로 인한 원격 코드 실행 문제점(931212)**](http://technet.microsoft.com/security/bulletin/ms07-040)                                                                                                                                                                                                                                                      |
| **요약**                   | 이 업데이트는 비공개적으로 보고된 취약점 3건을 해결합니다. 이 취약점 중 2건은 .NET Framework가 설치된 클라이언트 시스템에서 원격 코드 실행을 허용할 수 있고, 1건은 ASP.NET을 실행하는 웹 서버에서 정보 유출을 허용할 수 있습니다. 모든 원격 코드 실행의 경우, 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                      |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                     |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 합니다.                                                                                                                                                                                                                          |
| **영향을 받는 소프트웨어** | **.NET Framework**. 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                     |

중요(2)
-------



| 공지 번호                  | Microsoft 보안 공지 MS07-037                                                                                                                                                                                                                                                                                                                             |
|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft Office Publisher의 취약점으로 인한 원격 코드 실행 문제점(936548)**](http://technet.microsoft.com/security/bulletin/ms07-037)                                                                                                                                                                                                                |
| **요약**                   | 이 중요 보안 업데이트는 일반에 공개된 취약점 1건을 해결합니다. 이 취약점은 사용자가 특수하게 조작된 Microsoft Office Publisher 파일을 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 이 취약점을 악용하려면 사용자 개입이 필요합니다. |
| **최대 심각도**            | [중요](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                            |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                           |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 적용하기 위해 다시 시작할 필요는 없습니다.                                                                                                                                                                                             |
| **영향을 받는 소프트웨어** | **Office, Publisher**. 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                        |

| 공지 번호                  | Microsoft 보안 공지 MS07-041                                                                                                                                                                                                                                                                                                                                                                                                          |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft IIS(인터넷 정보 서비스)의 취약점으로 인한 원격 코드 실행 문제점(939373)**](http://technet.microsoft.com/security/bulletin/ms07-041)                                                                                                                                                                                                                                                                                      |
| **요약**                   | 이 중요 보안 업데이트는 비공개적으로 보고된 취약점 1건을 해결합니다. 공격자가 Windows XP Professional 서비스 팩 2의 IIS(인터넷 정보 서비스) 5.1에서 호스팅하는 웹 페이지에 특수하게 조작된 URL 요청을 보낼 경우 이 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. IIS 5.1은 Windows XP Professional 서비스 팩 2의 기본 설치에 속하지 않습니다. 이 취약점 악용에 성공한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. |
| **최대 심각도**            | [중요](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                         |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 합니다.                                                                                                                                                                                                                                                                             |
| **영향을 받는 소프트웨어** | **Windows XP Professional**. 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                               |

보통(1)
-------


| 공지 번호                  | Microsoft 보안 공지 MS07-038                                                                                                                                                                                                              |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Windows Vista 방화벽의 취약점으로 인한 정보 유출 문제점(935807)**](http://technet.microsoft.com/security/bulletin/ms07-038)                                                                                                            |
| **요약**                   | 이 보통 보안 업데이트는 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 네트워크 인터페이스에 대한 액세스를 수신되는 무단 네트워크 트래픽에 허용할 수 있습니다. 공격자는 영향을 받는 호스트에 대해 정보를 수집할 수 있습니다. |
| **최대 심각도**            | [보통](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                             |
| **취약점으로 인한 영향**   | 정보 유출                                                                                                                                                                                                                                 |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 합니다.                                                                                 |
| **영향을 받는 소프트웨어** | **Windows** **Vista**. 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                         |

검색, 배포 도구 및 지침
-----------------------


**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://technet.microsoft.com/ko-kr/updatemanagement/default.aspx)를 참조하십시오. [TechNet Security Center](http://www.microsoft.com/korea/technet/security/default.mspx)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://www.microsoft.com/korea/athome/security/default.mspx)을 방문하거나 “최신 보안 업데이트”를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://update.microsoft.com/microsoftupdate/), [Windows Update](http://update.microsoft.com/) 및 [Office 업데이트](http://office.microsoft.com/ko-kr/downloads/)에서 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서도 다운로드할 수 있으며 "security\_patch"라는 키워드를 사용하여 쉽게 찾을 수 있습니다. 마지막으로, 보안 업데이트는 Windows Update 카탈로그에서 다운로드할 수 있습니다. Windows Update 카탈로그에 대한 자세한 내용은 [Microsoft 기술 자료 문서 323166](http://support.microsoft.com/kb/323166)을 참조하십시오.

**검색 및 배포 지침**

Microsoft는 이 달의 보안 업데이트를 위한 검색 및 배포 지침을 제공하였습니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), Extended Security Update Inventory Tool 및 Enterprise Update Scan Tool(EST) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](http://support.microsoft.com/kb/910723)을 참조하십시오.

**Microsoft Baseline Security Analyzer 및** **Update** **Update Scan Tool)**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer (영문)](http://www.microsoft.com/technet/security/tools/mbsahome.mspx)를 방문하십시오.

MBSA 1.2.1에서 보안 업데이트 검색을 지원할 수 없는 경우 해당 보안 업데이트 검색에 사용할 수 있도록 EST(Enterprise Update Scan Tool)가 발표되었습니다. EST에 대한 자세한 내용은 [Enterprise Update Scan Tool](http://support.microsoft.com/default.aspx?id=894193)을 참조하십시오.

**참고** 2007년 10월 9일 이후부터 MBSA 1.2.1에서 사용되는 MSSecure.XML 파일이 더 이상 업데이트되지 않습니다. 이 날짜 이후부터는 MBSA 1.2.1에서 사용되는 MSSecure.XML 파일에 새 보안 업데이트가 추가되지 않으며 EST(Enterprise Scan Tool)의 새 버전도 발표되지 않습니다. 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer (영문)](http://www.microsoft.com/technet/security/tools/mbsahome.mspx)를 방문하십시오.

**Software Update Services**

관리자는 Microsoft Software Update Services(SUS)를 사용하여 Windows 2000 및 Windows Server 2003 기반 서버 그리고 Windows 2000 Professional 또는 Windows XP Professional을 실행하는 데스크톱 시스템에 최신 중요 업데이트와 보안 업데이트를 신속하고 안전하게 배포할 수 있습니다.

Software Update Services를 통해 이 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Software Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/previous/default.mspx)를 참조하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.mspx)를 참조하십시오. SMS 2.0 사용자는[Software Updates Service Feature Pack](http://technet.microsoft.com/ko-kr/sms/bb676802(en-us).aspx)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer와 Microsoft Office 검색 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://www.microsoft.com/technet/sms/2003/patchupdate.mspx)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://technet.microsoft.com/ko-kr/sms/bb676767(en-us).aspx) 및 [SMS 2.0 Administration Feature Pack](http://technet.microsoft.com/ko-kr/sms/bb676800(en-us).aspx)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

이 도구는 Software Update Services(SUS)를 통해****배포되지 않습니다.

#### MU, WU, WSUS 및 SUS의 비보안 중요 업데이트

이달의 업데이트:

-   Microsoft는 Microsoft Update(MU) 및 Windows Server Update Services(WSUS)를 통해 4개의 **비보안**, 중요 업데이트를 릴리스했습니다.
-   Microsoft는 Windows Update(WU) 및 Software Update Services(SUS)를 통해 1개의 Windows용 **비보안**, 중요 업데이트를 릴리스했습니다.

이 정보는 보안 공지 요약과 같은 날짜에 Microsoft Update, Windows Update, Windows Server Update Services, Software Update Services를 통해 릴리스된 **비보안**, 중요 업데이트에만****해당됩니다. 다른 날짜에 발표된 **비보안** 업데이트 관련 정보는 제공되지****않습니다.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[패치 관리를 위한 보안 가이드](http://www.microsoft.com/korea/technet/security/topics/patchmanagement.mspx)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서 다운로드할 수 있으며 "security\_patch"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://update.microsoft.com/microsoftupdate/)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://www.microsoft.com/korea/communities/default.mspx)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://technet.microsoft.com/security/bulletin/policy)드립니다.

-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040)에서 설명한 문제점을 보고해 주신 [OWASP (영문)](http://www.owasp.org/)의 Dinis Cruz
-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040)에서 설명한 문제점을 보고해 주신 [Security Assessment (영문)](http://www.smsiinc.com/)의 Paul Craig
-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040)에서 설명한 문제점을 보고해 주신 [Sumatra (영문)](http://www.sumatra.nl/)의 Jeroen Frijters
-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040)에서 설명한 문제점을 최초로 보고해 주신 [UK CPNI (영문)](http://www.cpni.gov.uk/)와 협력해 주신 [ProCheckUp (영문)](http://www.procheckup.com/)
-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040)에서 설명한 문제점에 대한 추가 정보를 제공하여 Microsoft와 협력해 주신 [Portcullis Computer Security Ltd. (영문)](http://www.portcullis-security.com/)의 Ferruh T. Mavituna
-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040)에서 설명한 문제점에 대한 추가 정보를 제공하여 Microsoft와 협력해 주신 [TrueSec (영문)](http://www.truesec.com/)의 Johannes Gumbel
-   [MS07-039](http://technet.microsoft.com/security/bulletin/ms07-039)에서 설명한 문제점을 보고해 주신 [NGSSoftware (영문)](http://www.nextgenss.com/)의 Peter Winter-Smith
-   [MS07-039](http://technet.microsoft.com/security/bulletin/ms07-039)에서 설명한 문제점을 보고해 주신 [IBM Internet Security Systems x-Force (영문)](http://xforce.iss.net/)의 Neel Mehta
-   [MS07-037](http://go.microsoft.com/fwlink/?linkid=93488)에서 설명한 문제점을 보고해 주신 [eEye (영문)](http://www.eeye.com/)
-   [MS07-038](http://technet.microsoft.com/security/bulletin/ms07-038)에서 설명한 문제점을 보고해 주신 [Symantec (영문)](http://www.symantec.com/)의 Jim Hoagland 및 Ollie Whitehouse
-   [MS07-041](http://technet.microsoft.com/security/bulletin/ms07-041)에서 설명한 문제점에 대한 추가 정보를 제공하여 Microsoft와 협력해 주신 [Watchfire (영문)](http://www.watchfire.com/)의 Jonathan Afek 및 Adi Sharabani
-   [MS07-041](http://technet.microsoft.com/security/bulletin/ms07-041)에서 설명한 문제점에 대한 추가 정보를 제공하여 Microsoft와 협력해 주신 [NGSSoftware (영문)](http://www.nextgenss.com/)의 Peter Winter-Smith

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle)를 참조하십시오.
-   기술 지원은 1577-9700을 통해 [Microsoft 고객 지원 센터](http://support.microsoft.com/)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://support.microsoft.com/common/international.aspx)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0 (2007년 7월 11일): 공지 요약이 게시되었습니다.
-   V2.0 (2008년 3월 26일): Windows Vista 서비스 팩 1, Windows Vista x64 Edition 서비스 팩 1, Windows Server 2008, Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008 x64 Edition이 영향을 받는 소프트웨어에 추가되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
