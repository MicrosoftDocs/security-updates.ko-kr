---
TOCTitle: 'MS08-APR'
Title: 2008 년 4 월 Microsoft 보안 공지 요약
ms:assetid: 'ms08-apr'
ms:contentKeyID: 61230696
ms:mtpsurl: '   '
---

2008 년 4 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2008년 4월 9일 수요일 | 업데이트된 날짜: 2009년 2월 19일 목요일

**버전:** 1.3

이 공지 요약 목록에는 2008년 4월 릴리스된 보안 공지가 포함되어 있습니다.

2008년 4월 공지 발표와 함께 이 공지 요약이 2008년 4월 3일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2008년 3월 10일 목요일(대한민국 표준시)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [4월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357219&eventcategory=4&culture=ko-kr&countrycode=kr). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](https://www.microsoft.com/korea/technet/security/current.aspx) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

#### 요약

이번 달의 보안 공지는 다음과 같습니다(심각도 순).

긴급 (5)
--------



| 공지 번호                  | Microsoft 보안 공지 MS08-018                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft Project의 취약점으로 인한 원격 코드 실행 문제점(950183)**](https://technet.microsoft.com/security/bulletin/ms08-018)                                                                                                                                                                                                                                                                                                                                                                              |
| **요약**                   | 이 보안 업데이트는 비공개적으로 보고된 취약점 1건을 해결합니다. 사용자가 특수하게 조작된 Project 파일을 열면 이 Microsoft Project 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 공격자가 프로그램을 설치하거나 데이터를 보고, 변경하거나 삭제하고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 적용하기 위해 다시 시작할 필요는 없습니다.                                                                                                                                                                                                                                                                                                                                                  |
| **영향을 받는 소프트웨어** | **Microsoft Office.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                                                                                              |

| 공지 번호                  | Microsoft 보안 공지 MS08-021                                                                                                                                                                                                                                                                                                                                                                                        |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**GDI의 취약점으로 인한 원격 코드 실행 문제점(948590)**](https://technet.microsoft.com/security/bulletin/ms08-021)                                                                                                                                                                                                                                                                                                  |
| **요약**                   | 이 보안 업데이트는 GDI에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이러한 취약점을 악용하면 사용자가 특수하게 조작된 EMF 또는 WMF 이미지 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템에 대해 완벽히 제어할 수 있습니다. 공격자가 프로그램을 설치하거나 데이터를 보고, 변경하거나 삭제하고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. |
| **최대 심각도**            | [긴급](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                       |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                      |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 설치하려면 다시 시작해야 합니다.                                                                                                                                                                                                                                                                  |
| **영향을 받는 소프트웨어** | **Microsoft Windows.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                   |

| 공지 번호                  | Microsoft 보안 공지 MS08-022                                                                                                                                                                                                                                                                                           |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**VBScript 및 JScript 스크립팅 엔진의 취약점으로 인한 원격 코드 실행 취약점(944338)**](https://technet.microsoft.com/security/bulletin/ms08-022)                                                                                                                                                                       |
| **요약**                   | 이 보안 업데이트는 Windows의 VBScript 및 JScript 스크립팅 엔진에 대해 비공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 공격자가 프로그램을 설치하거나 데이터를 보고, 변경하거나 삭제하고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. |
| **최대 심각도**            | [긴급](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                          |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                         |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 설치하려면 다시 시작해야 합니다.                                                                                                                                                                     |
| **영향을 받는 소프트웨어** | **Microsoft Windows.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                      |

| 공지 번호                  | Microsoft 보안 공지 MS08-023                                                                                                                                                                                                                                                                                                                                                                                              |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**ActiveX 킬(Kill) 비트 보안 업데이트(948881)**](https://technet.microsoft.com/security/bulletin/ms08-023)                                                                                                                                                                                                                                                                                                                |
| **요약**                   | 이 보안 업데이트는 Microsoft 제품에 대해 비공개적으로 보고된 취약점 1건을 해결합니다. 이 업데이트에는 Yahoo! Music Jukebox 제품에 대한 킬(kill) 비트도 포함되어 있습니다. 이 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                             |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                            |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 할 수 있습니다.                                                                                                                                                                                                                                                         |
| **영향을 받는 소프트웨어** | **Microsoft Windows, Internet Explorer.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                      |

| 공지 번호                  | Microsoft 보안 공지 MS08-024                                                                                                                                                                                                                                                                                    |
|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Internet Explorer 누적 보안 업데이트(947864)**](https://technet.microsoft.com/security/bulletin/ms08-024)                                                                                                                                                                                                     |
| **요약**                   | 이 보안 업데이트는 비공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                   |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                  |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 설치하려면 다시 시작해야 합니다.                                                                                                                                                              |
| **영향을 받는 소프트웨어** | **Microsoft Windows, Internet Explorer.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                            |

중요 (3)
--------



| 공지 번호                  | Microsoft 보안 공지 MS08-020                                                                                                                                                                                                                    |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**DNS 클라이언트의 취약점으로 인한 스푸핑 허용 문제점(945553)**](https://technet.microsoft.com/security/bulletin/ms08-020)                                                                                                                      |
| **요약**                   | 이 보안 업데이트는 비공개적으로 보고된 취약점 1건을 해결합니다. 이 스푸핑 취약점은 Windows DNS 클라이언트에 존재하며, 공격자가 특수하게 조작된 DNS 요청을 전송하여 적법한 위치에서 보낸 인터넷 트래픽을 스푸핑하거나 리디렉션하도록 허용합니다. |
| **최대 심각도**            | [중요](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                   |
| **취약점으로 인한 영향**   | 스푸핑                                                                                                                                                                                                                                          |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 설치하려면 다시 시작해야 합니다.                                                                                              |
| **영향을 받는 소프트웨어** | **Microsoft Windows.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                               |

| 공지 번호                  | Microsoft 보안 공지 MS08-025                                                                                                                                                                                                                                                             |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Windows 커널의 취약점으로 인한 권한 상승 문제점(941693)**](https://technet.microsoft.com/security/bulletin/ms08-025)                                                                                                                                                                   |
| **요약**                   | 이 보안 업데이트는 비공개적으로 보고된, Windows 커널의 취약점을 해결합니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 새 계정을 만들 수도 있습니다. |
| **최대 심각도**            | [중요](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                            |
| **취약점으로 인한 영향**   | 권한 상승                                                                                                                                                                                                                                                                                |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 설치하려면 다시 시작해야 합니다.                                                                                                                                       |
| **영향을 받는 소프트웨어** | **Microsoft Windows.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                        |

| 공지 번호                  | Microsoft 보안 공지 MS08-019                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft Visio의 취약점으로 인한 원격 코드 실행 문제점(949032)**](https://technet.microsoft.com/security/bulletin/ms08-019)                                                                                                                                                                                                                                                                                                                                                                               |
| **요약**                   | 이 보안 업데이트는 비공개적으로 보고된 취약점을 해결합니다. 사용자가 특수하게 조작된 Visio 파일을 열면 이 Microsoft Office Visio 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 공격자가 프로그램을 설치하거나 데이터를 보고, 변경하거나 삭제하고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [중요](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 적용하기 위해 다시 시작할 필요는 없습니다.                                                                                                                                                                                                                                                                                                                                                 |
| **영향을 받는 소프트웨어** | **Microsoft Office.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                                                                                             |

영향을 받는 소프트웨어 및 다운로드 위치
---------------------------------------


**이 표를 어떻게 사용합니까?**  

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 필요한 보안 업데이트가 있는지 확인합니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.

**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

#### Windows 운영 체제 및 구성 요소

 
<p></p>
<table style="border:1px solid black;">
<caption>Microsoft Windows 2000</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>최대 심각도</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows 2000 서비스 팩 4</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=caac000a-22b6-48cb-aa00-1a0bfe886de2">Microsoft Windows 2000 서비스 팩 4</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.1 및 JScript 5.1</a><br />
(긴급)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.6 및 JScript 5.6</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0395451f-b719-4f71-a7b4-403d0c7e8fcc">Microsoft Internet Explorer 5.01 서비스 팩 4</a><br />
(긴급)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=ba6d3aeb-e35a-47cc-bace-7bd9d58a9d3f">Microsoft Internet Explorer 6 서비스 팩 1</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=b051ae04-fe81-440d-9136-d6b239ca954e">Microsoft Internet Explorer 5.01 서비스 팩 4</a><br />
(긴급)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=75d2dc78-e3a4-4ff6-9e2d-bf1935003e8e">Microsoft Internet Explorer 6 서비스 팩 1</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=41326ade-96b6-47ce-9291-d4e3039471c4">Microsoft Windows 2000 서비스 팩 4</a><br />
(중요)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8db9f328-da0e-4fb8-96c4-6d368b47c224">Microsoft Windows 2000 서비스 팩 4</a><br />
(중요)</td>
</tr>
</tbody>
</table>
 

 
<p></p>
<table style="border:1px solid black;">
<caption>Windows XP</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>최대 심각도</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP 서비스 팩 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=c2763dd8-a03e-4a48-aa86-a7ec00250a7a">Windows XP 서비스 팩 2</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=c0124698-3b94-4474-9473-22a2f39a4a56">VBScript 5.6 및 JScript 5.6</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=9dbf002f-fe53-4cc7-a430-35f45c520d10">Windows XP 서비스 팩 2</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=36c641ad-953f-4b09-ba1c-9c383295e180">Microsoft Internet Explorer 6</a><br />
(긴급)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=e771efe8-8881-4f23-b5b0-15651a390ba9">Windows Internet Explorer 7</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=893f4cef-0395-4c44-ba28-7a10b6e7dd48">Windows XP 서비스 팩 2</a><br />
(중요)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0e937f65-abd0-46dd-8883-5bfd70ea1178">Windows XP 서비스 팩 2</a><br />
(중요)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=166f2ab5-913c-47a9-86fe-b814797b751e">Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=87b80ae3-e299-4d15-a135-3b1bcf943652">VBScript 5.6 및 JScript 5.6</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=01400970-df68-4daf-aa39-2fc4f969974c">Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=85beacc0-8ca2-4ded-9c24-23348d05c735">Microsoft Internet Explorer 6</a><br />
(긴급)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=9364bf81-6505-4788-958d-a4bd29dc98ad">Windows Internet Explorer 7</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8fdd1207-6e93-4c43-bacc-fe3623a6ebe7">Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2</a><br />
(중요)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=a29bbd13-761f-44fa-8948-e1a8c244bd7a">Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2</a><br />
(중요)</td>
</tr>
</tbody>
</table>
 

 
<p></p>
<table style="border:1px solid black;">
<caption>Windows Server 2003</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>최대 심각도</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=bee91d80-d49a-4d3d-82d6-d5aa63f54979">Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=88518aa6-e334-4529-aa63-0bf2ef417ce3">VBScript 5.6 및 JScript 5.6</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=ad384fea-53be-4be3-8acb-1cd23a7f5405">Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2</a><br />
(보통)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0444b76e-93fa-43c2-b1bc-a5c054529eb5">Microsoft Internet Explorer 6</a><br />
(긴급)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=9acd2a03-5530-49c8-9ea1-0bfaf259700d">Windows Internet Explorer 7</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=214bd8f5-6eb2-414c-b013-c516a306d692">Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2</a><br />
(중요)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=d3b855a6-4648-4771-826d-11a151828eac">Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2</a><br />
(중요)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=e3dde449-e062-4ce0-a9f4-433bff23e224">Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=12cefefc-8553-4dca-9850-c653371de61e">VBScript 5.6 및 JScript 5.6</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=ffc5c893-cb24-4875-b0a7-6d5c7aa4d642">Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2</a><br />
(보통)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=5ebb5ef9-615f-4cab-bac5-6f45f1b94952">Microsoft Internet Explorer 6</a><br />
(긴급)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=a9e406aa-33e2-49b8-ab54-4a7328e46147">Windows Internet Explorer 7</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=fd123394-a5d6-4b55-be74-2938f52ce922">Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2</a><br />
(중요)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=320fd100-35e1-4345-9399-796393235cbc">Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2</a><br />
(중요)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=7886a802-f2b5-489c-b14b-631f4c4c0742">Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=fe22a828-cca4-4b51-bbd5-995c65fead21">VBScript 5.6 및 JScript 5.6</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=94cf78d3-b6c3-41bc-993e-3af3be0d70f1">Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)</a><br />
(보통)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=63da8040-fda2-42c7-8543-26ad6f9811f2">Microsoft Internet Explorer 6</a><br />
(긴급)<br />
<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=75a05d3a-92a0-4a00-95d4-e2b2f6755180">Windows Internet Explorer 7</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=e0e63f03-904d-47ee-94fc-51a8dea668eb">Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)</a><br />
(중요)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=126426a7-be38-4327-89db-02d99d76589d">Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)</a><br />
(중요)</td>
</tr>
</tbody>
</table>
 

 
<p></p>
<table style="border:1px solid black;">
<caption>Windows Vista</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>최대 심각도</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Vista 및 Windows Vista 서비스 팩 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=9b51deb8-3873-4146-977f-7e3d0840a4c5">Windows Vista 및 Windows Vista 서비스 팩 1</a><br />
(긴급)</td>
<td style="border:1px solid black;">없음</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=d7f14001-7f42-4ca0-9193-cdf061179b59">Windows Vista 및 Windows Vista 서비스 팩 1</a><br />
(중요)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=d4e24966-6530-463a-9ee2-f6a9d000f998">Windows Internet Explorer 7</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8203d303-c855-4579-9bbf-b06ddf5c1b87">Windows Vista</a><br />
(중요)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=9640cd8b-d749-4ddd-8af9-b298cebed969">Windows Vista 및 Windows Vista 서비스 팩 1</a><br />
(중요)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=4ad6dcd1-6ea5-43bf-8bee-a5f507beadc6">Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1</a><br />
(긴급)</td>
<td style="border:1px solid black;">없음</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=d33462b6-7391-482d-babe-fb4cd0beaa21">Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1</a><br />
(중요)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=295cf8f2-265e-4570-b708-21033337fe05">Windows Internet Explorer 7</a><br />
(긴급)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=73f3a234-3973-4467-be7e-69efa7ee978c">Windows Vista x64 Edition</a><br />
(중요)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=d56bb4fe-304e-45e0-95f2-fde2f47b2a04">Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1</a><br />
(중요)</td>
</tr>
</tbody>
</table>
 

 
<p></p>
<table style="border:1px solid black;">
<caption>Windows Server 2008</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>최대 심각도</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008(32비트 시스템용)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=006d5c47-53e6-4ee1-932c-497611804938">Windows Server 2008(32비트 시스템용)</a><br />
(긴급)</td>
<td style="border:1px solid black;">없음</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=95691924-2813-4a86-9e11-99d853f8e606">Windows Server 2008(32비트 시스템용)</a><br />
(낮음)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=e57b4d94-19ad-4818-8311-a3f94be01a4b">Windows Internet Explorer 7</a>\*<br />
(긴급)</td>
<td style="border:1px solid black;">없음</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=4497333c-9418-4b91-83dc-0155735421c0">Windows Server 2008(32비트 시스템용)</a><br />
(중요)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2008(x64 기반 시스템용)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8909f144-655b-4f07-916f-fd967f1efb2b">Windows Server 2008(x64 기반 시스템용)</a><br />
(긴급)</td>
<td style="border:1px solid black;">없음</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=920ae29b-19d0-4089-ac79-f2da824a2256">Windows Server 2008(x64 기반 시스템용)</a><br />
(낮음)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=93e9f52a-c7d0-4033-9c12-740665a219af">Windows Internet Explorer 7</a>\*<br />
(긴급)</td>
<td style="border:1px solid black;">없음</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=5aefc7a6-79a4-45a2-b534-35d0ec400dda">Windows Server 2008(x64 기반 시스템용)</a><br />
(중요)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008(Itanium 기반 시스템용)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=b7771a4a-4e4f-48d1-8551-bb8b778ca5a7">Windows Server 2008(Itanium 기반 시스템용)</a><br />
(긴급)</td>
<td style="border:1px solid black;">없음</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=66df79ac-8364-4922-9688-ebc7ec76d89f">Windows Server 2008(Itanium 기반 시스템용)</a><br />
(낮음)</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=acf948e8-c4a9-40da-b282-f5e584e77b05">Windows Internet Explorer 7</a><br />
(긴급)</td>
<td style="border:1px solid black;">없음</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=3080c26b-7456-41ef-8668-28f15bc7b8ce">Windows Server 2008(Itanium 기반 시스템용)</a><br />
(중요)</td>
</tr>
</tbody>
</table>
 

**\*\*Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 Windows Server 2008이 설치된 경우, 비록 이 취약점의 영향을 받는 파일이 시스템에 존재해도 이 업데이트에서 해결하는 취약점은 지원되는 Windows Server 2008 에디션에 영향을 주지 않습니다. 그러나 현재 시스템에 있는 파일보다 업데이트 파일이 최신이므로(버전 번호가 높음) 영향을 받는 파일을 가진 사용자에게 이 업데이트가 제공됩니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<caption>Microsoft Project</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-018"><strong>MS08-018</strong></a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>최대 심각도</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>긴급</strong></a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Project 2000 서비스 버전 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=fbe46241-b9da-40c6-803d-42eb6234be77">Project 2000 서비스 버전 1</a><br />
(KB949043)<br />
(긴급)</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Project 2002 서비스 팩 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=07a90718-6597-426d-9dca-a336d60c01b8">Project 2002 서비스 팩 1</a><br />
(KB949005)<br />
(중요)</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Project 2003 서비스 팩 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=aaba07d6-e972-4e85-bccd-406aa2c4a4f4">Project 2003 서비스 팩 2</a><br />
(KB948962)<br />
(중요)</td>
<td style="border:1px solid black;"></td>
</tr>
</tbody>
</table>

 
<p></p>
<table style="border:1px solid black;">
<caption>Microsoft Visio</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-019"><strong>MS08-019</strong></a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>최대 심각도</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Visio 2002 서비스 팩 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0056a936-def5-40fa-bcfc-0ab0dd5c3964">Visio 2002 서비스 팩 2</a><br />
(KB947896)<br />
(중요)</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Visio 2003 서비스 팩 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 서비스 팩 2</a><br />
(KB947650)<br />
(중요)</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Visio 2003 서비스 팩 3</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 서비스 팩 3</a><br />
(KB947650)<br />
(중요)</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Visio 2007</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007</a><br />
(KB947590)<br />
(중요)</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Visio 2007 서비스 팩 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007 서비스 팩 1</a><br />
(KB947590)<br />
(중요)</td>
<td style="border:1px solid black;"></td>
</tr>
</tbody>
</table>
  
검색, 배포 도구 및 지침  
-----------------------
  

**보안 센터**
  
해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center (영문)](https://technet.microsoft.com/ko-kr/updatemanagement/default(en-us).aspx)를 참조하십시오. [TechNet Security Center](https://www.microsoft.com/korea/technet/security/default.mspx)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](https://www.microsoft.com/korea/athome/security/default.mspx)을 방문하거나 “최신 보안 업데이트”를 클릭하여 이 정보를 볼 수도 있습니다.
  
보안 업데이트는 [Microsoft Update](https://update.microsoft.com/microsoftupdate/), [Windows Update](https://update.microsoft.com/) 및 [Office 업데이트](https://office.microsoft.com/ko-kr/downloads/)에서 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
  
마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](https://catalog.update.microsoft.com/)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](https://catalog.update.microsoft.com/v7/site/faq.aspx)를 참조하십시오.
  
**검색 및 배포 지침**
  
Microsoft는 이 달의 보안 업데이트를 위한 검색 및 배포 지침을 제공하였습니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), ESUIT(Extended Security Update Inventory Tool) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](https://support.microsoft.com/kb/910723)을 참조하십시오.
  
**Microsoft Baseline Security Analyzer**
  
관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer (영문)](https://www.microsoft.com/technet/security/tools/mbsahome.mspx)를 방문하십시오.
  
**Windows Server Update Services**
  
관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.
  
Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](https://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)를 참조하십시오.
  
**Systems Management Server**
  
Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](https://technet.microsoft.com/ko-kr/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](https://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.mspx)를 참조하십시오. SMS 2.0 사용자는[Software Updates Service Feature Pack (영문)](https://technet.microsoft.com/ko-kr/sms/bb676802(en-us).aspx)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](https://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.
  
**참고** SMS는 Microsoft Baseline Security Analyzer와 Microsoft Office 검색 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](https://www.microsoft.com/technet/sms/2003/patchupdate.mspx)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](https://technet.microsoft.com/ko-kr/sms/bb676767(en-us).aspx) 및 [SMS 2.0 Administration Feature Pack (영문)](https://technet.microsoft.com/ko-kr/sms/bb676800(en-us).aspx)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.
  
### 기타 정보
  
#### Microsoft Windows 악성 소프트웨어 제거 도구
  
Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.
  
#### MU, WU 및 WSUS의 비보안 중요 업데이트
  
Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.
  
-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 2008년에 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명  
-   [Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트 (영문)](https://technet.microsoft.com/ko-kr/wsus/bb466214.aspx)
  
#### 보안 전략 및 커뮤니티
  
**업데이트 관리 전략**
  
[업데이트 관리를 위한 보안 가이드](https://www.microsoft.com/korea/technet/security/topics/patchmanagement.mspx)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.
  
**기타 보안 관련 업데이트 받기**
  
기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.
  
-   보안 업데이트는 [Microsoft 다운로드 센터](https://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서 다운로드할 수 있으며"security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.  
-   일반 사용자용 업데이트는 [Microsoft Update](https://update.microsoft.com/microsoftupdate/)에서 사용할 수 있습니다.  
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.
  
**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**
  
[IT Pro Security Community(IT 전문가 보안 커뮤니티)](https://www.microsoft.com/korea/communities/default.mspx)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.
  
#### 감사의 말
  
고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://technet.microsoft.com/security/bulletin/policy)드립니다.
  
-   MS08-018에서 설명한 문제점을 보고해 주신 대한민국 [국가사이버안전센터](https://www.ncsc.go.kr/)  
-   MS08-019에서 설명한 문제점을 보고해 주신 익명 발견자  
-   MS08-019에서 설명한 다른 문제점을 보고해 주신 익명 발견자  
-   MS07-020에서 설명한 문제점을 보고해 주신 [Trusteer (영문)](https://www.trusteer.com/)의 Amit Klein  
-   MS07-020에서 설명한 문제점을 보고해 주신 [Scanit (영문)](https://www.scanit.be/)의 Alla Berzroutchko  
-   MS08-020에서 설명한 문제점을 보고해 주신 [Nominet UK (영문)](https://www.nominet.org.uk/)의 Roy Arends  
-   MS08-021에서 설명한 문제점을 보고해 주신 [iDefense Labs (영문)](https://labs.idefense.com/)의 Jun Mao  
-   MS08-021에서 설명한 문제점을 보고해 주신 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)의 Sebastian Apelt  
-   MS08-021에서 설명한 문제점을 보고해 주신 [SkyRecon (영문)](https://www.skyrecon.com/)의 Thomas Garnier  
-   MS08-021에서 설명한 문제점을 보고해 주신 [Palo Alto Networks (영문)](https://www.paloaltonetworks.com/)의 Yamata Li  
-   MS08-022에서 설명된 문제점을 보고해 주신 [Symantec (영문)](https://www.symantec.com/)의 Peter Ferrie  
-   MS07-023에서 설명한 문제점을 보고해 주신 [iDefense VCP (영문)](https://labs.idefense.com/)와 협력해 주신 익명 연구자  
-   MS07-024에서 설명한 문제점을 보고해 주신 [Secunia (영문)](https://secunia.com/)의 Carsten Eiram  
-   MS08-025에서 설명한 문제점을 보고해 주신 [SkyRecon (영문)](https://www.skyrecon.com/)의 Thomas Garnier
  
#### 지원
  
-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle)를 참조하십시오.  
-   기술 지원은 1577-9700을 통해 [Microsoft 고객 지원 센터](https://support.microsoft.com/)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.  
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](https://support.microsoft.com/common/international.aspx)에 나와 있습니다.
  
#### 부인
  
Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.
  
#### 개정 내역
  
-   V1.0 (2008년 4월 9일): 공지 요약이 게시되었습니다.  
-   V1.1 (2008년 4월 10일): Microsoft 보안 공지 MS08-018의 요약이 업데이트되었습니다.  
-   V1.2 (2008년 4월 17일): MS08-021의 발견자 정보가 업데이트되었으며, Microsoft Office 제품군 및 소프트웨어에 대해 영향을 받는 소프트웨어가 설명되어 있습니다.  
-   V1.3(2009년 2월 19일): Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(x64 기반 시스템용)에 영향을 받지 않는 Server Core 표시가 추가되었습니다(MS08-024).
  
*Built at 2014-04-18T12:27:44Z-07:00*
