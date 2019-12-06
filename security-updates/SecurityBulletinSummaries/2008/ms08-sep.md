---
TOCTitle: 'MS08-SEP'
Title: 2008 년 9 월 Microsoft 보안 공지 요약
ms:assetid: 'ms08-sep'
ms:contentKeyID: 61230707
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms08-sep(v=Security.10)'
---

2008 년 9 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2008년 9월 10일 수요일 | 업데이트된 날짜: 2008년 12월 10일 수요일

**버전:** 3.0

이 공지 요약 목록에는 2008년 9월 발표된 보안 공지가 포함되어 있습니다.

2008년 9월 공지 발표와 함께 이 공지 요약이 2008년 9월 4일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2008년 9월 10일 수요일(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [9월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374633&eventcategory=4&culture=en-us&countrycode=us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](https://www.microsoft.com/korea/technet/security/current.mspx) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

#### 요약

이번 달의 보안 공지는 다음과 같습니다(심각도 순).

긴급 (4)
--------



| 공지 번호                  | Microsoft 보안 공지 MS08-054                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Windows Media Player의 취약점으로 인한 원격 코드 실행 문제점 (954154)**](https://technet.microsoft.com/security/bulletin/ms08-054)                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **요약**                   | 이 보안 업데이트는 Windows Media Player의 비공개적으로 보고된 취약점, 즉 특수하게 조작된 오디오 파일이 Windows Media 서버로부터 스트리밍될 때 원격 코드의 실행이 가능하다는 문제점을 해결합니다. 사용자가 관리자 권한으로 로그온한 경우, 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 적용하기 위해 다시 시작할 필요는 없습니다.                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **영향을 받는 소프트웨어** | **Microsoft Windows.**자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

| 공지 번호                  | Microsoft 보안 공지 MS08-052                                                                                                                                                                                                                                                                                                                                                                                        |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**GDI+의 취약점으로 인한 원격 코드 실행 문제점 (954593)**](https://technet.microsoft.com/security/bulletin/ms08-052)                                                                                                                                                                                                                                                                                                |
| **요약**                   | 이 보안 업데이트는 Microsoft Windows GDI+에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 이 취약점으로 인해 사용자가 영향을 받는 소프트웨어를 사용하여 특수하게 조작된 이미지를 보거나 특수하게 조작된 콘텐츠가 포함된 웹사이트를 탐색할 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                       |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                      |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 설치하려면 다시 시작해야 합니다.                                                                                                                                                                                                                                                                  |
| **영향을 받는 소프트웨어** | **Microsoft Windows, Internet Explorer, .NET Framework, Office, SQL Server, Visual Studio.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                             |

| 공지 번호                  | Microsoft 보안 공지 MS08-053                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Windows Media 인코더 9의 취약점으로 인한 원격 코드 실행 문제점 (954156)**](https://technet.microsoft.com/security/bulletin/ms08-053)                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **요약**                   | 이 보안 업데이트는 비공개적으로 보고된 Windows Media 인코더 9 시리즈의 취약점을 해결합니다. 이 취약점은 사용자가 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 사용자가 관리자 권한으로 로그온한 경우, 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 할 수 있습니다.                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **영향을 받는 소프트웨어** | **Microsoft Windows.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

| 공지 번호                  | Microsoft 보안 공지 MS08-055                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점 (955047)**](https://technet.microsoft.com/security/bulletin/ms08-055)                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **요약**                   | 이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 OneNote URL을 클릭할 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 적용하기 위해 다시 시작할 필요는 없습니다.                                                                                                                                                                                                                                                                                                                                                                                        |
| **영향을 받는 소프트웨어** | **Microsoft Office.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                                                                                                                                    |

영향을 받는 소프트웨어 및 다운로드 위치
---------------------------------------


**이 표를 어떻게 사용합니까?**  

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 필요한 보안 업데이트가 있는지 확인합니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.

**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

#### Windows 운영 체제 및 구성 요소

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="4">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-054**](https://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](https://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](https://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a860d2d9-653d-4ddb-bbff-323d3ccdb866)  
(KB938464)  
(긴급)  
[Microsoft .NET Framework 1.0 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=c7cbcd19-acc1-4a89-adfa-99b2f431510d)  
(KB947739)  
(심각도 없음)  
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=6013f866-3ea1-4672-b1bf-e516204c3a7a)  
(KB947742)  
(심각도 없음)  
[Microsoft .NET Framework 2.0](https://www.microsoft.com/download/details.aspx?familyid=7f1cd013-2c4b-4582-9114-cb840a96124a)  
(KB947746)  
(심각도 없음)  
[Microsoft .NET Framework 2.0 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=215b73a3-46ab-44a8-a0fb-6d37bd1c39b8)  
(KB947748)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
[Windows Media 인코더 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=0cabfbc0-db5d-4a6a-a4cd-e6df89ac2b25)  
(긴급)
</td>
</tr>
<tr>
<th colspan="4">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-054**](https://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](https://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](https://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=d5891180-5dd1-49ec-bcc6-3030a544202c)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=e0bd6fbe-f46e-4961-9a79-49ec77d39439)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 인코더 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=57bcb3c2-49d3-4f18-8d03-36abd03d7403)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=caf8a45e-a9f8-4e91-98fd-87eddbeae64c)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c5d26771-1f49-4bbf-902c-bf92e527cadb)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 인코더 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=18efea9e-b103-46de-90d9-5e295854cec3)  
(긴급)  
[Windows Media 인코더 9 시리즈 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=ebc1737c-6e78-4244-a1b2-a56d031f16e9)  
(긴급)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-054**](https://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](https://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](https://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ac03f138-eca4-46e1-9782-e811820e547f)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 인코더 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=54ce1080-94cf-4e4f-8e09-a7dbab2757c5)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=93f1451b-5b62-47e5-8f0c-b720b957999a)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 인코더 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=c83011cd-90b8-494c-9cad-fa055e101992)  
(보통)  
[Windows Media 인코더 9 시리즈 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=d8f1b782-136b-443f-b5f2-63aa4d1fd94a)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=14e99f8a-cdd4-40d7-8cfc-73ae6bd6dfad)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-054**](https://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](https://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](https://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 및 Windows Vista 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=2f4118fd-1ffb-46da-b922-cd4ca4f9d84e)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 및 Windows Vista 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=16f3ad21-ed77-4c32-93df-3b650b2b32a5)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 인코더 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=334352e7-d41f-494f-866d-f1f1745ffd17)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=aa47d016-f5c9-4586-8876-f1f4f255f54d)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 인코더 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
(긴급)  
[Windows Media 인코더 9 시리즈 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=54d1279a-7f26-4727-a39d-5505bcd4fc53)  
(긴급)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-054**](https://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](https://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](https://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=72fc6028-6af4-44ec-8d2a-28c53807d6bc)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=23bd3be5-cc66-46f8-9420-49d65d8afe1d)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 인코더 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=3906512b-26db-473e-b522-3883ff34a21c)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=7f1e0f05-6c9d-4ad1-9b19-50ee4fa7bd7e)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 인코더 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
(보통)  
[Windows Media 인코더 9 시리즈 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=e30f9427-26d0-4e86-b9b8-bc637c3b5734)\*  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=5159bdba-3825-4816-a2be-ab035332b9e2)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**\*\*Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 Windows Server 2008이 설치된 경우, 비록 이 취약점의 영향을 받는 파일이 시스템에 존재해도 이 업데이트에서 해결하는 취약점은 지원되는 Windows Server 2008 에디션에 영향을 주지 않습니다. 그러나 현재 시스템에 있는 파일보다 업데이트 파일이 최신이므로(버전 번호가 높음) 영향을 받는 파일을 가진 사용자에게 이 업데이트가 제공됩니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Office 제품군, 시스템 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-052**](https://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-055**](https://technet.microsoft.com/security/bulletin/ms08-055)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 2 및 Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)  
(중요)  
[Microsoft Office 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?displaylang=ko&familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
(중요)  
[Microsoft Office 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office 시스템 및 2007 Microsoft Office 시스템 서비스 팩 1
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System](https://www.microsoft.com/download/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)  
(중요)  
[2007 Microsoft Office System 서비스 팩 1](https://www.microsoft.com/download/details.aspx?displaylang=ko&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)  
(중요)
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System](https://www.microsoft.com/download/details.aspx?familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
(중요)  
[2007 Microsoft Office System 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
(중요)
</td>
</tr>
<tr>
<th colspan="3">
기타 Office 소프트웨어
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-052**](https://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-055**](https://technet.microsoft.com/security/bulletin/ms08-055)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project 2002 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2002 서비스 팩 1](https://www.microsoft.com/download/details.aspx?displaylang=ko&familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2002 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a6d9d3ef-f087-4f61-9ec1-522b7d4b9c48)  
(KB954479)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word Viewer, Microsoft Word Viewer 2003, Microsoft Word Viewer 2003 서비스 팩 3, Microsoft Office Excel Viewer 2003, Microsoft Office Excel Viewer 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer, Microsoft Word Viewer 2003, Microsoft Word Viewer 2003 서비스 팩 3, Microsoft Office Excel Viewer 2003, Microsoft Office Excel Viewer 2003 서비스 팩 3, Microsoft Visio 2003 Viewer](https://www.microsoft.com/download/details.aspx?displaylang=ko&familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office PowerPoint Viewer 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint Viewer 2003](https://www.microsoft.com/download/details.aspx?displaylang=ko&familyid=cd503f08-1831-45ff-bdf4-dd918ca40505)  
(KB956500)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer, Microsoft Office PowerPoint Viewer 2007, Microsoft Office PowerPoint Viewer 2007 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer, Microsoft Office PowerPoint Viewer 2007, Microsoft Office PowerPoint Viewer 2007 서비스 팩 1](https://www.microsoft.com/download/details.aspx?displaylang=ko&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web 및 Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft Expression Web 및 Microsoft Expression Web 2](https://www.microsoft.com/download/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Groove 2007 및 Microsoft Office Groove 2007 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove 2007 및 Microsoft Office Groove 2007 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
[Microsoft Works 8](https://www.microsoft.com/download/details.aspx?familyid=eb0d224e-a517-40d9-9fc6-2345fa12a841)  
(KB956483)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Digital Image Suite 2006
</td>
<td style="border:1px solid black;">
[Microsoft Digital Image Suite 2006](https://www.microsoft.com/download/details.aspx?familyid=04afd760-8173-4069-9e82-d3bf053d9eae)  
(KB955992)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office OneNote 2007
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office OneNote 2007](https://www.microsoft.com/download/details.aspx?familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
(긴급)  
[Microsoft Office OneNote 2007 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
(긴급)
</td>
</tr>
</table>
 
\*영향을 받는 이 소프트웨어의 업데이트는 Microsoft Office XP 서비스 팩 3 업데이트와 동일합니다.

\*\*영향을 받는 이 소프트웨어의 업데이트는 Microsoft Office 2003 서비스 팩 2 및 Microsoft Office 2003 서비스 팩 3 업데이트와 동일합니다.

\*\*\*영향을 받는 이 소프트웨어의 업데이트는 2007 Microsoft Office System 및 2007 Microsoft Office System 서비스 팩 1 업데이트와 동일합니다.

#### Microsoft Server 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-052**](https://technet.microsoft.com/security/bulletin/ms08-052)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2000 Reporting Services 서비스 팩 2
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
해당 사항 없음  
QFE 업데이트:  
[SQL Server 2000 Reporting Services 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5f9e7f78-7439-414b-a9dc-a779b89427db)  
(KB954609)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 서비스 팩 2
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(긴급)  
QFE 업데이트:  
[SQL Server 2005 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(긴급)  
QFE 업데이트:  
[SQL Server 2005 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 서비스 팩 2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 서비스 팩 2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(긴급)  
QFE 업데이트:  
[SQL Server 2005 서비스 팩 2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(긴급)
</td>
</tr>
</table>
 

#### Microsoft 개발자 도구 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-052**](https://technet.microsoft.com/security/bulletin/ms08-052)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2002 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2002 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=7848a652-4025-44bb-9c98-37a078b56d01)  
(KB947736)  
(심각도 없음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=9bc1e8f8-6c30-4aa0-90f5-fbb0ad5fd90e)  
(KB947737)  
(심각도 없음)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a7bf790b-3249-4ee8-9440-fa911ebbc08a)  
(KB947738)  
(심각도 없음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](https://www.microsoft.com/download/details.aspx?familyid=a8c80b29-6d00-4949-a005-5d706122919a)  
(KB952241)  
(심각도 없음)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 서비스 팩 1 재배포 가능 패키지
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 서비스 팩 1 재배포 가능 패키지](https://www.microsoft.com/download/details.aspx?familyid=82833f27-081d-4b72-83ef-2836360a904d)  
(KB954765)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 재배포 가능 패키지
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 재배포 가능 패키지](https://www.microsoft.com/download/details.aspx?familyid=6ae0aa19-3e6c-474c-9d57-05b2347456b1)  
(KB954766)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 8.0 서비스 팩 1
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4에 설치된 [Microsoft Visual FoxPro 8.0 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1f4371b9-b8be-4455-94d2-2304ee340543)  
(KB955368)  
(심각도 없음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 서비스 팩 1
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4에 설치된 [Microsoft Visual FoxPro 9.0 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=49b21e30-722d-446e-9020-aceb3870db69)  
(KB955369)  
(심각도 없음)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 서비스 팩 2
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4에 설치된 [Microsoft Visual FoxPro 9.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=36957f47-9d8b-477d-bd60-5959e5a2eafa)  
(KB955370)  
(심각도 없음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Platform SDK 재배포 가능 파일: GDI+
</td>
<td style="border:1px solid black;">
[Microsoft Platform SDK 재배포 가능 파일: GDI+](https://www.microsoft.com/download/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a)  
(심각도 없음)
</td>
</tr>
</table>
 

#### Microsoft 보안 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Forefront Security
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-052**](https://technet.microsoft.com/security/bulletin/ms08-052)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Client Security 1.0
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4에 설치된 [Microsoft Forefront Client Security 1.0](https://www.microsoft.com/download/details.aspx?familyid=1eb1a79f-44ca-499e-90bb-ac51894e9d1e)  
(KB957177)  
(중요)
</td>
</tr>
</table>
 

검색, 배포 도구 및 지침
-----------------------


**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](https://technet.microsoft.com/ko-kr/updatemanagement/default.aspx)를 참조하십시오. [TechNet Security Center (영문)](https://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](https://www.microsoft.com/korea/protect/default.mspx)을 방문하거나 “최신 보안 업데이트”를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 및 [Office 업데이트](https://go.microsoft.com/fwlink/?linkid=21135)에서 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security%20update)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](https://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](https://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 이 달의 보안 업데이트를 위한 검색 및 배포 지침을 제공하였습니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), ESUIT(Extended Security Update Inventory Tool) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](https://support.microsoft.com/kb/910723)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer (영문)](https://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services (영문)](https://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](https://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](https://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.mspx)를 참조하십시오. SMS 2.0 사용자는[Software Updates Service Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=33340)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](https://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer와 Microsoft Office 검색 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](https://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit) 5.0 (영문)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 2008년에 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명
-   [Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트 (영문)](https://technet.microsoft.com/en-us/wsus/bb466214.aspx)

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](https://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security%20update)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티) (영문)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티) (영문)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://technet.microsoft.com/security/bulletin/policy)드립니다.

-   MS08-052에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](https://labs.idefense.com/)의 Greg MacManus
-   MS08-052에서 설명한 문제점을 보고해 주신 Fortinet, [FortiGuard Global Security Research Team (영문)](https://www.fortiguardcenter.com/)의 Bing Liu
-   MS08-052에서 설명한 문제점을 보고하기 위해 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)와 협력해 주신 [NGSSoftware (영문)](https://www.ngssoftware.com/)의 Peter Winter-Smith와 Ivan Fratric
-   MS08-052에서 설명한 문제점을 보고해 주신 [Vulnerability Research Team, Assurent Secure Technologies (영문)](https://www.assurent.com/)
-   MS08-052에서 설명한 문제점을 보고하기 위해 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)와 협력해 주신 익명 연구자
-   MS08-053에서 설명한 문제점을 보고해 주신 [Bach Khoa Internetwork Security Center (BKIS) Hanoi University of Technology(베트남) (영어)](https://security.bkis.vn/)의 Nguyen Minh Duc 및 Le Manh Tung
-   MS08-055에서 설명한 문제점을 보고해 주신 [Insomnia Security (영문)](https://www.insomniasec.com/)의 Brett Moore

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 1577-9700을 통해 [Microsoft 고객 지원 센터](https://go.microsoft.com/fwlink/?linkid=21131)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](https://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2008년 9월 10일): 공지 요약이 게시되었습니다.
-   V2.0(2008년 9월 13일): Microsoft Office Project 2002 서비스 팩 2, Microsoft Office 2003의 모든 Office Viewer 소프트웨어, 2007 Microsoft Office System의 모든 Office Viewer 소프트웨어가 MS08-052의 영향을 받는 소프트웨어로 추가되어 공지 요약이 업데이트되었습니다.
-   V2.1(2008년 9월 18일): 보안공지 요약에 영향을 받는 프로그램이 Microsoft Office Project 2002 Service Pack 1에서 Microsoft Office Project 2002 Service Pack 2로 변경 되었습니다. 이름만 변경 되었습니다. 다른 변화는 감지 되지 않았습니다.
-   V2.2(2008년 10월 30일): Microsoft Visio 2003 Viewer, Microsoft Visio 2007 Viewer 및 Microsoft Visio 2007 Viewer 서비스 팩 1이 MS08-052의 영향을 받는 소프트웨어에서 제거되어 공지 요약이 업데이트되었습니다.
-   V3.0(2008년 12월 10일): Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩, Microsoft Expression Web 및 Microsoft Expression Web 2, Microsoft Office Groove 2007 및 Microsoft Office Groove 2007 서비스 팩 1을 MS08-052의 영향을 받는 소프트웨어로 추가하기 위해 이 공지 요약을 개정하였습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
