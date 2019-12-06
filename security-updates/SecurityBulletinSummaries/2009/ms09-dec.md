---
TOCTitle: 'MS09-DEC'
Title: 2009 년 12 월 Microsoft 보안 공지 요약
ms:assetid: 'ms09-dec'
ms:contentKeyID: 61230710
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms09-dec(v=Security.10)'
---


2009 년 12 월 Microsoft 보안 공지 요약
======================================

게시된 날짜: 2009년 12월 9일 수요일 | 업데이트된 날짜: 2010년 1월 14일 목요일

**버전:** 2.0

이 공지 요약 목록에는 2009년 12월 발표된 보안 공지가 포함되어 있습니다.

2009년 12월 공지 발표와 함께 이 공지 요약이 2009년 12월 3일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2009년 12월 10일 목요일 오전 4시 (한국 시각)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [12월 보안 공지 웹캐스트 (영문)](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407802&culture=en-us)에 지금 등록하십시오. 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](https://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

요약
----

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향을 받는 소프트웨어 및 다운로드 위치**를 참조하십시오.

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >공지 번호</th>
<th style="border:1px solid black;" >공지 제목 및 용약</th>
<th style="border:1px solid black;" >최대 심각도 및 취약점 영향</th>
<th style="border:1px solid black;" >다시 시작 요구 사항</th>
<th style="border:1px solid black;" >영향을 받는 소프트웨어</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-071">MS09-071</a></td>
<td style="border:1px solid black;"><strong>IAS(Internet Authentication Service)의 취약점으로 인한 원격 코드 실행 문제점 (974318)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이러한 취약점으로 인해 IAS(Internet Authentication Service) 서버에서 받은 메시지가 메모리에 올바르지 않게 복사될 경우 PEAP 인증 시도를 처리할 때 원격 코드 실행이 발생할 수 있습니다. 이러한 취약점 두 가지 중 하나를 성공적으로 악용한 경우 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. IAS(Internet Authentication Service)를 사용하는 서버에서 PEAP 및 MS-CHAP v2 인증을 사용하는 경우에만 이 취약점의 영향을 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-074">MS09-074</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Project의 취약점으로 인한 원격 코드 실행 문제점 (967183)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office Project의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 Project 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-072">MS09-072</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트 (976325)</strong><br />
<br />
이 보안 업데이트는 Internet Explorer에 대해 비공개적으로 보고된 취약점 4건과 공개된 취약점 1건을 해결합니다. 이 취약점들은 모두 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. Microsoft ATL(액티브 템플릿 라이브러리) 헤더로 작성된 ActiveX 컨트롤이 원격 코드 실행을 허용할 수 있습니다. 이 취약점은 Microsoft 보안 권고 973882 및 Microsoft 보안 공지 MS09-035에 설명되어 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-069">MS09-069</a></td>
<td style="border:1px solid black;"><strong>로컬 보안 기관 하위 시스템 서비스의 취약점으로 인한 서비스 거부 문제 (974392)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 원격에서 인증된 공격자가 IPSec(인터넷 프로토콜 보안)을 통해 통신하는 동안 특수하게 조작된 ISAKMP 메시지를 영향을 받는 시스템의 로컬 보안 기관 하위 시스템 서비스(LSASS)에 보내는 경우 서비스 거부가 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-070">MS09-070</a></td>
<td style="border:1px solid black;"><strong>Active Directory Federation Services의 취약점으로 인한 원격 코드 실행 문제점 (971726)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 중 가장 심각한 취약점은 공격자가 ADFS 사용 웹 서버로 특수하게 조작된 HTTP 요청을 전송할 경우 원격 코드 실행을 허용할 수 있습니다. 공격자가 이러한 취약점을 악용하려면 인증을 받은 사용자여야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-073">MS09-073</a></td>
<td style="border:1px solid black;"><strong>WordPad 및 Office 텍스트 변환기의 취약점으로 인한 원격 코드 실행 문제점 (975539)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft WordPad 및 Microsoft Office 텍스트 변환기의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 WordPad 또는 Microsoft Office Word에서 특수하게 조작된 Word 97 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약점을 성공적으로 악용한 경우 공격자는 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 덜 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](https://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 취약점 제목                                             | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                                                                                                                                                                                                                     |  
|---------------------------------------------------------------------|---------------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-069](https://technet.microsoft.com/security/bulletin/ms09-069) | 로컬 보안 기관 하위 시스템 서비스 리소스 부족 취약점    | [CVE-2009-3675 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3675) | [**3 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점을 통해 원격 코드 실행은 불가능하며 원격에서 인증된 공격자는 서비스 거부만 악용할 수 있습니다.                                                                                                                                                       |  
| [MS09-070](https://technet.microsoft.com/security/bulletin/ms09-070) | ADFS의 단일 사인온 스푸핑 취약점                        | [CVE-2009-2508 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2508) | [**3 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점을 통해 원격 코드 실행은 불가능하며 스푸핑만 가능합니다.                                                                                                                                                                                             |  
| [MS09-070](https://technet.microsoft.com/security/bulletin/ms09-070) | ADFS의 원격 코드 실행 취약점                            | [CVE-2009-2509 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2509) | [**1 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 인증된 공격자만 이 취약점을 악용할 수 있습니다.                                                                                                                                                                                                               |  
| [MS09-071](https://technet.microsoft.com/security/bulletin/ms09-071) | IAS(Internet Authentication Service) 메모리 손상 취약점 | [CVE-2009-2505 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2505) | [**2 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 제한적인 원격 코드 실행이 가능합니다. 대부분 서비스 거부가 발생합니다.                                                                                                                                                                                        |  
| [MS09-071](https://technet.microsoft.com/security/bulletin/ms09-071) | MS-CHAP 인증 우회 취약점                                | [CVE-2009-3677 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3677) | [**3 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점을 통해 원격 코드 실행은 불가능하며 네트워크 인증 우회로 인한 권한 상승만 가능합니다.                                                                                                                                                                |  
| [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) | ATL COM 초기화 취약점                                   | [CVE-2009-2493 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | 없음                                                                                                  | (이 취약점은 이미 [7월 공지 요약](https://technet.microsoft.com/security/bulletin/ms09-jul)에서 악용 가능성 인덱스 평가가 제공되었습니다. [MS09-035](https://technet.microsoft.com/security/bulletin/ms09-035)에서 처음으로 이 취약점이 해결되었기 때문입니다.) |  
| [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) | 초기화되지 않은 메모리 손상 취약점                      | [CVE-2009-3671 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3671) | [**1 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                        |  
| [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) | HTML 개체 메모리 손상 취약점                            | [CVE-2009-3672 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3672) | [**1 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                        |  
| [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) | 초기화되지 않은 메모리 손상 취약점                      | [CVE-2009-3673 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3673) | [**1 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                        |  
| [MS09-072](https://technet.microsoft.com/security/bulletin/ms09-072) | 초기화되지 않은 메모리 손상 취약점                      | [CVE-2009-3674 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3674) | [**1 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                        |  
| [MS09-073](https://technet.microsoft.com/security/bulletin/ms09-073) | WordPad 및 Office 텍스트 변환기 메모리 손상 취약점      | [CVE-2009-2506 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2506) | [**2 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                        |  
| [MS09-074](https://technet.microsoft.com/security/bulletin/ms09-074) | Project 메모리 유효성 검사 취약점                       | [CVE-2009-0102 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0102) | [**2 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                        |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=5b02d10d-1abd-4d68-826b-71dad543657a&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=0cf37247-505a-4dc2-aad7-c8cb1a63b57a&displaylang=ko)  
(긴급)  
[Internet Explorer 6 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=7fb6261c-6895-4f79-be2c-bb110874a19c&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=560e01db-5f59-4ef1-9406-f5d7e0fd4128&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=50936f51-b0a9-4e94-85bf-93f9ad74fdd1&displaylang=ko)  
(KB973904)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=4d294be6-19d1-43b5-9c75-f9d30699a2e7&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=facab13f-ea31-4c71-be4c-24e44ded174f&displaylang=ko)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=def2c038-3b03-4162-a563-a6ebec756f37&displaylang=ko)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6c003629-77bf-4735-bd4a-c37c4386f869&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=5448b168-6bf7-4bae-9627-b88d76c4d5c5&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=c090c4c2-c277-4d8c-91e1-28286bc5443e&displaylang=ko)  
(KB973904)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=17b5206d-61e9-4663-afc7-80e98bf4d618)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=a253c19a-c808-4115-8bd0-cf312d396abd)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=98a56425-4f88-4f0f-963b-dada8dc0d8f8)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0c9af3b5-d015-4025-bbb4-1a5113e9113f)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c2bbf515-f81a-436b-947b-cbf2db85fdd9)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4b9bf156-cd34-460f-b4ad-571e37f54659)  
(KB973904)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
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
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3d49b386-133a-4d51-b6f0-cec0c70ef93e&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=6659fc40-71ee-44a9-9656-8d3ee02b5bc0&displaylang=ko)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7bdba030-e2c6-44ac-bb5f-24ae8ec372a2&displaylang=ko)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0dd50357-64f2-4286-86ba-c512e65eed2a&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a779aae1-7724-4458-94fb-a2343356ecae&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=31351b9e-b5bb-4618-990b-1089ea5a3bc2&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b9678229-2473-4aae-a814-eca9ea556d17&displaylang=ko)  
(KB973904)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5a273b47-8a18-4778-9b60-8b560a1ce089&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=287e7921-8aab-42a6-b647-551d0a9adc15&displaylang=ko)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4de4bbcd-b1b8-4482-8ef7-0d9b4a730e0c&displaylang=ko)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e62aba15-5eeb-46a2-a142-bfca94016c55&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a8a9bf12-4ad6-49fd-b2b7-f379dc3309d2&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b6eb9d9b-1a43-4b30-a033-19a1db786244&displaylang=ko)<sup>[2]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=257facf3-20a1-49e2-ab4c-c1ae67fe05a0&displaylang=ko)  
(KB973904)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=498f5eeb-d03e-42ee-ad6a-9d6f98c66acb)  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=9ce1a721-0c6a-4775-9407-9633d817d716)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=72d44de7-dfc5-4667-a59f-2ee73d0e3708)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=f5b003ad-af25-488a-91fb-98835a0bfeac)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=1a7784ef-5d25-4de1-a293-f742b5a3473d)  
(KB973904)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista 및 Windows Vista 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6&displaylang=ko)  
(보통)  
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=40d26d40-4203-4013-b3f9-912a5b209fbd&displaylang=ko)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=47d5ada1-1d60-4233-bdd3-64918b5e1245&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab&displaylang=ko)  
(보통)  
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3140527a-aa33-462b-b3a6-bfcd78b5aa0c&displaylang=ko)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=1e466b48-422f-4c80-8fdf-ba61111942b1&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968&displaylang=ko)\*  
(중요)  
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d0570536-756e-4fda-883d-f2a3c4ac5bbd&displaylang=ko)\*  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=43660133-43e1-41f3-8a82-98c4a739914f&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f6715abb-fd93-44ba-9854-2ecc672622da&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b&displaylang=ko)\*  
(중요)  
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0e72d0f1-2ce7-4650-b72c-bb303351aafc&displaylang=ko)\*  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=22972970-740f-4c50-93ec-f6d49dd1b360&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7d1f5e9e-a7de-4f96-89c8-510fd51f16e7&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=89defe77-7e82-4bfa-9693-66c93b930da1)  
(보통)  
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=89defe77-7e82-4bfa-9693-66c93b930da1)  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2c7765a2-3117-4dd8-94b4-0060ca16871b)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5af3be0b-2dd2-4039-90e1-2278e9c5aee5&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9d9a04c8-a019-4943-8e93-c6bfd77c8960&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-071**](https://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](https://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](https://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](https://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=bcb38127-787f-49b0-b3fb-62f6a8628d89&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2c1b96f2-b3c3-4711-a9ad-b2133ea7bf81&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**Windows Server 2008 및 Windows Server 2008 R2 참고 사항**

**\*Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교](https://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오

**MS09-070 참고 사항**

<sup>[1]</sup> ADFS(Active Directory Federation Services)를 배포하는 Windows Server 2003 R2가 업데이트된 경우에만 영향을 받습니다.

<sup>[2]</sup> ADFS(Active Directory Federation Services)를 배포하는 Windows Server 2003 R2 x64 Edition이 업데이트된 경우에만 영향을 받습니다.

**MS09-073 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

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
<th style="border:1px solid black;" colspan="3">
Microsoft Office 제품군, 시스템 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-074**](https://technet.microsoft.com/security/bulletin/ms09-074)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=bc3ec3ba-2cec-43ab-b184-c222794231f2&displaylang=ko)  
(KB975008)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=b4a4126c-b0b3-4db2-b6f5-0e67519c2a5f&displaylang=ko)  
(KB975051)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
기타 Microsoft Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-074**](https://technet.microsoft.com/security/bulletin/ms09-074)
</td>
<td style="border:1px solid black;">
[**MS09-073**](https://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Project 2000
</td>
<td style="border:1px solid black;">
[Microsoft Project 2000 서비스 버전 1](https://www.microsoft.com/download/details.aspx?familyid=135c010a-55f4-4385-b67d-96ea06ef881a&displaylang=ko)  
(KB961083)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Project 2002
</td>
<td style="border:1px solid black;">
[Microsoft Project 2002 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=c55ef8fe-8f66-42fc-a298-de6f8886b3e4&displaylang=ko)  
(KB961079)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Project 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=2ea8ca39-f130-439a-92d5-77e9ef050105&displaylang=ko)  
(KB961082)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 8.5
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](https://www.microsoft.com/download/details.aspx?familyid=807426a1-8b78-4681-a606-dc39f4d7b64a)  
(KB977304)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 변환 팩
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 변환 팩](https://www.microsoft.com/download/details.aspx?familyid=f3ff8bb6-d047-42f1-9331-b6df85fff9fd)  
(KB974882)  
(중요)
</td>
</tr>
</table>
 
**MS09-073 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](https://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](https://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](https://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](https://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](https://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**참고** 2009년 8월 1일부터 Microsoft는 Office 업데이트와 Office 업데이트 인벤토리 도구에 대한 지원을 중단합니다. 계속해서 Microsoft Office 제품에 필요한 최신 업데이트를 받으려면 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)를 사용하십시오. 자세한 내용은 [Microsoft Office 업데이트 정보: 자주 제기되는 질문 사항(FAQ)](https://office.microsoft.com/ko-kr/downloads/fx010402221042.aspx)을 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](https://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](https://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](https://go.microsoft.com/fwlink/?linkid=22939)를 참조하십시오. SMS 2.0 사용자는 SUIT(Security Update Inventory Tool)을 사용하여 보안 업데이트 배포를 지원할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](https://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트 (영문)](https://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](https://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](https://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS09-072에서 설명한 문제점을 보고해 주신 [Verisign iDefense Labs (영문)](https://labs.idefense.com/)의 Ryan Smith
-   MS09-072에서 설명한 문제점을 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/) 및 [TippingPoint (영문)](https://www.tippingpoint.com/)와 협력하여 보고해 주신 Sam Thomas(https://eshu.co.uk/)
-   MS09-072에서 설명한 문제점을 [Verisign iDefense Labs (영문)](https://labs.idefense.com/)와 협력하여 보고해 주신 [team509 (영문)](https://www.team509.com/)
-   MS09-072에서 설명한 문제점을 [TippingPoint (영문)](https://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS09-072에서 설명한 다른 문제점을 [TippingPoint (영문)](https://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS09-073에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](https://labs.idefense.com/)의 Sean Larsson 및 Jun Mao
-   MS09-074에서 설명한 문제점을 보고해 주신 [Fortinet's FortiGuard Labs (영문)](https://www.fortiguard.com/)의 Bing Liu

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](https://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](https://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](https://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2009년 12월 9일): 공지 요약이 게시되었습니다.
-   V1.1(2009년 12월 10일): 요약 표에서 MS09-071에 대한 설명이 업데이트되었습니다. MS09-073의 다시 시작 요구 사항이 수정되었습니다.
-   V2.0(2010년 1월 14일): MS09-073에서 이전에 **Microsoft Office Word 2002 서비스 팩 3(KB975008)** 및 **Microsoft Office Word 2003 서비스 팩 3(KB975051)**으로 나열된 업데이트 패키지의 이름이 각각 **Microsoft Office XP 서비스 팩 3(KB975008)** 및 **Microsoft Office 2003 서비스 팩 3(KB975051)**으로 변경되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
