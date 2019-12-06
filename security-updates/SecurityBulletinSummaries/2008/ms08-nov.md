---
TOCTitle: 'MS08-NOV'
Title: 2008 년 11 월 Microsoft 보안 공지 요약
ms:assetid: 'ms08-nov'
ms:contentKeyID: 61230705
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms08-nov(v=Security.10)'
---

2008 년 11 월 Microsoft 보안 공지 요약
======================================

게시된 날짜: 2008년 11월 12일 수요일 | 업데이트된 날짜: 2011년 7월 13일 수요일

**버전:** 4.0

이 공지 요약 목록에는 2008년 11월 발표된 보안 공지가 포함되어 있습니다.

2008년 11월 공지 발표와 함께 이 공지 요약이 2008년 11월 6일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2008년 11월 12일 수요일(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [11월 보안 공지 웹캐스트에 지금 등록하십시오. (영문)](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374642) 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](https://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

#### 요약

이번 달의 보안 공지는 다음과 같습니다(심각도 순).

긴급(1)
-------



| 공지 번호                  | Microsoft 보안 공지 MS08-069                                                                                                                                                                                                                                                                                                             |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft XML Core Services의 취약점으로 인한 원격 코드 실행 문제점 (955218)**](https://technet.microsoft.com/security/bulletin/ms08-069)                                                                                                                                                                                              |
| **요약**                   | 이 보안 업데이트는 Microsoft XML Core Services의 여러 가지 취약점을 해결합니다. 가장 심각한 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                            |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                           |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 할 수 있습니다.                                                                                                                                                                        |
| **영향을 받는 소프트웨어** | **Microsoft Windows.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                        |

중요(1)
-------



| 공지 번호                  | Microsoft 보안 공지 MS08-068                                                                                                                                                                                                                                                                                                                                                                                                       |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**SMB의 취약점으로 인한 원격 코드 실행 문제점 (957097)**](https://technet.microsoft.com/security/bulletin/ms08-068)                                                                                                                                                                                                                                                                                                                |
| **요약**                   | 이 보안 업데이트는 공개된 Microsoft SMB(Server Message Block)의 취약점을 해결합니다. 이 취약점으로 인해 영향을 받는 시스템에서 원격 코드 실행이 발생할 수 있습니다. 취약점 악용에 성공한 공격자는 프로그램을 설치하거나 데이터를 보고 변경하거나 삭제하고 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [중요](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                      |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 설치하려면 다시 시작해야 합니다.                                                                                                                                                                                                                                                                                 |
| **영향을 받는 소프트웨어** | **Microsoft Windows.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                  |

악용 가능성 인덱스
------------------


**이 표를 어떻게 사용합니까?**  

이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](https://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.

| 공지 번호                                                           | 공지 제목                                                                                                                               | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                           | 주요 정보                                                                                                              |
|---------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| [MS08-068](https://technet.microsoft.com/security/bulletin/ms08-068) | [SMB의 취약점으로 인한 원격 코드 실행 문제점 (957097)](https://technet.microsoft.com/security/bulletin/ms08-068)                         | [CVE-2008-4037 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4037) | [1 - 일관적인 악용 코드 가능](https://technet.microsoft.com/en-us/security/cc998259.aspx)          | Windows XP에 대한 이 취약점의 악용 코드가 현재 공개되었습니다.                                                         |
| [MS08-069](https://technet.microsoft.com/security/bulletin/ms08-069) | [Microsoft XML Core Services의 취약점으로 인한 원격 코드 실행 문제점 (955218)](https://technet.microsoft.com/security/bulletin/ms08-069) | [CVE-2008-4029 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4029) | [1 - 일관적인 악용 코드 가능 (영문)](https://technet.microsoft.com/en-us/security/cc998259.aspx)   | 이와 같은 정보 유출 악용 코드가 도메인 간 공격에 사용될 수 있습니다.                                                   |
| [MS08-069](https://technet.microsoft.com/security/bulletin/ms08-069) | [Microsoft XML Core Services의 취약점으로 인한 원격 코드 실행 문제점 (955218)](https://technet.microsoft.com/security/bulletin/ms08-069) | [CVE-2007-0099 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2007-0099) | [2 - 비일관적인 악용 코드 가능 (영문)](https://technet.microsoft.com/en-us/security/cc998259.aspx) | 이 취약점은 XML 파일을 로드하는 중 경쟁 조건에 관련되어 있습니다. 그러므로 이 취약점은 일관적으로 악용하기 어렵습니다. |
| [MS08-069](https://technet.microsoft.com/security/bulletin/ms08-069) | [Microsoft XML Core Services의 취약점으로 인한 원격 코드 실행 문제점 (955218)](https://technet.microsoft.com/security/bulletin/ms08-069) | [CVE-2008-4033](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4033)        | [2 - 비일관적인 악용 코드 가능 (영문)](https://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                        |

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
</tr>
<tr>
<th colspan="3">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-069**](https://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](https://technet.microsoft.com/security/bulletin/ms08-068)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=559cd4b6-24b7-4e60-8749-37d9b833d3eb&displaylang=ko)  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ko)  
(KB954430)  
(중요)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3&displaylang=ko)  
(KB954459)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=44c971e6-96fc-4bba-8f4a-f9d46bda2b6c&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<th colspan="3">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-069**](https://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](https://technet.microsoft.com/security/bulletin/ms08-068)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08&displaylang=ko)  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ko)  
(KB954430)  
(중요)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3&displaylang=ko)  
(KB954459)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/technet/security/bulletin/http//www.microsoft.com/downloads/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08&displaylang=ko)  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ko)  
(KB954430)  
(중요)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=7493fa37-2cbf-4d66-8690-d50d63da4096&displaylang=ko)  
(KB954459)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c&displaylang=ko)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=1b79f220-ebfc-49c1-963b-58bbda21b6e7)  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(중요)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9501b33b-d639-43e7-ad5a-9e76ed66effd)  
(중요)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-069**](https://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](https://technet.microsoft.com/security/bulletin/ms08-068)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=0a0f8385-e908-4b5f-b9bf-80b7dabfcafd&displaylang=ko)  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ko)  
(KB954430)  
(낮음)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3&displaylang=ko)  
(KB954459)  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=57a0606d-ea7a-4e5b-8b8b-7b77a444ef75&displaylang=ko)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=347c8c83-4269-4a0e-af6f-4be2e824d22b&displaylang=ko)  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ko)  
(KB954430)  
(낮음)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3&displaylang=ko)  
(KB954459)  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=915e001f-9aa0-4fb0-9c2a-0f0c72b4f056&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1 (Itanium 기반 시스템용) 및 Windows Server 2003 SP2 (Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=3a65e1cd-eb4e-44b6-8868-a5a84be2cb32)  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(낮음)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=6abf7ba9-825f-4ee2-a2fe-6b1cd9fab622)  
(중요)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-069**](https://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](https://technet.microsoft.com/security/bulletin/ms08-068)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 및 Windows Vista 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=affbc957-1867-4bbe-924d-6f0696ae0895&displaylang=ko)  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ko)  
(KB954430)  
(중요)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=cb6c4315-8c6d-43af-978b-b190b1a1577a&displaylang=ko)  
(KB954459)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 및 Windows Vista 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5612815f-8685-45d2-af4a-164c298a0869&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=b01a5f31-8c57-4c5c-909e-b37caf0439b0&displaylang=ko)  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ko)  
(KB954430)  
(중요)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=39443046-2093-4c87-ac7b-679deab96414&displaylang=ko)  
(KB954459)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=727ce9b6-827f-4350-b4ff-c08e8ac541a6&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-069**](https://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](https://technet.microsoft.com/security/bulletin/ms08-068)
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
[**보통**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 (32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=90a04164-4d02-4ce9-b3d8-bddb1ec27618&displaylang=ko)\*\*  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ko)\*\*  
(KB954430)  
(낮음)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=dea9f227-967f-47c7-bb2a-ed68f13645d9&displaylang=ko)\*\*  
(KB954459)  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=b305e894-61ec-46b4-91ee-4c9ac59bc47e&displaylang=ko)\*  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=b7bfe3f4-835f-402c-95b5-6d49b6935308&displaylang=ko)\*\*  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ko)\*\*  
(KB954430)  
(낮음)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=f16e2a5f-37fd-4ee1-aef0-597214323dc4&displaylang=ko)\*\*  
(KB954459)  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=e8d26dfd-b347-4f10-b5b6-27dfff5e4f47&displaylang=ko)\*  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=4e0d1efe-70ac-459b-b330-c0149b74f520)  
(KB955069)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(낮음)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=d4ae74e2-1b09-4a99-8cf5-8a8ca8ac6f7f)  
(KB954459)  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d565467d-e10f-4ddc-a278-3f81a3798686)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-069**](https://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](https://technet.microsoft.com/security/bulletin/ms08-068)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-069**](https://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](https://technet.microsoft.com/security/bulletin/ms08-068)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**낮음**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**\*Server Core 설치가 영향을 받습니다.** 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오

**\*\*Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오

#### Microsoft Office 제품군 및 소프트웨어

 
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
Microsoft Office 제품군, 시스템 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-069**](https://technet.microsoft.com/security/bulletin/ms08-069)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3&displaylang=ko)  
(KB951535)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office 시스템 및 2007 Microsoft Office 시스템 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245&displaylang=ko)  
(KB951550)  
(중요)
</td>
</tr>
<tr>
<th colspan="2">
기타 Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-069**](https://technet.microsoft.com/security/bulletin/ms08-069)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3&displaylang=ko)  
(KB951535)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245&displaylang=ko)  
(KB951550)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web 및 Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245&displaylang=ko)  
(KB951550)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 및 Microsoft Office SharePoint Server 2007 서비스 팩 1 (32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=a208f2b5-2b0d-43bb-8f8a-58d4a3fc64f5&displaylang=ko)  
(KB951597)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 및 Microsoft Office SharePoint Server 2007 서비스 팩 1 (64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c&displaylang=ko)  
(KB951597)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Groove Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c&displaylang=ko)  
(KB951597)  
(중요)
</td>
</tr>
</table>
 

검색, 배포 도구 및 지침
-----------------------


**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center (영문)](https://technet.microsoft.com/ko-kr/updatemanagement/default.aspx)를 참조하십시오. [TechNet Security Center (영문)](https://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](https://www.microsoft.com/korea/protect/default.mspx)을 방문하거나 “최신 보안 업데이트”를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 및 [Office 업데이트](https://go.microsoft.com/fwlink/?linkid=21135)에서 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security%20update)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](https://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](https://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 이 달의 보안 업데이트를 위한 검색 및 배포 지침을 제공하였습니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), ESUIT(Extended Security Update Inventory Tool) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](https://support.microsoft.com/kb/910723)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer (영문)](https://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](https://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](https://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](https://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.mspx)를 참조하십시오. SMS 2.0 사용자는[Software Updates Service Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=33340)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](https://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer와 Microsoft Office 검색 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](https://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack](https://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

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

-   보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티) (영문)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://technet.microsoft.com/security/bulletin/policy)드립니다.

-   MS08-069에서 설명한 문제점을 보고해 주신 Gregory Fleischer
-   MS08-069에서 설명한 문제점을 보고해 주신 [Minded Security (영문)](https://www.mindedsecurity.com/)의 Stefano Di Paolafor

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 1577-9700을 통해 [Microsoft 고객 지원 센터](https://go.microsoft.com/fwlink/?linkid=21131)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](https://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2008년 11월 12일): 공지 요약이 게시되었습니다.
-   V2.0(2009년 4월 30일): Windows Vista(32비트 및 x64 기반 에디션) 서비스 팩 2 및 Windows Server 2008(32비트, x64 기반 및 Itanium 기반 에디션) 서비스 팩 2의 Microsoft XML Core Services 4.0(KB954430)이 MS08-069에 영향을 받는 소프트웨어로 추가되었습니다. 이 변경 사항은 검색에만 해당됩니다. 바이너리에 대한 변경 사항은 없습니다. 이미 KB954430을 성공적으로 설치한 고객은 다시 설치할 필요가 없습니다.
-   V3.0(2009년 10월 14일): Windows 7 32비트 및 x64 기반 에디션과 Windows Server 2008 R2 x64 기반 및 Itanium 기반 에디션에 설치된 Microsoft XML Core Services 4.0(KB954430)이 MS08-069에 영향을 받는 소프트웨어로 추가되었습니다. 이 변경 사항은 검색에만 해당됩니다. 바이너리에 대한 변경 사항은 없습니다. 이미 KB954430을 성공적으로 설치한 고객은 다시 설치할 필요가 없습니다.
-   V4.0(2011년 7월 13일): Windows 7 서비스 팩 1 32비트 및 x64 기반 에디션과 Windows Server 2008 R2 서비스 팩 1 x64 기반 및 Itanium 기반 에디션에 설치된 Microsoft XML Core Services 4.0(KB954430)이 MS08-069에 영향을 받는 소프트웨어로 추가되었습니다. 이 변경 사항은 검색에만 해당됩니다. 바이너리에 대한 변경 사항은 없습니다. 이미 KB954430을 성공적으로 설치한 고객은 다시 설치할 필요가 없습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
