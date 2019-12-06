---
TOCTitle: 'MS09-MAR'
Title: 2009 년 3 월 Microsoft 보안 공지 요약
ms:assetid: 'ms09-mar'
ms:contentKeyID: 61230715
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms09-mar(v=Security.10)'
---


2009 년 3 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2009년 3월 11일 수요일 | 업데이트된 날짜: 2009년 3월 12일 목요일

**버전:** 1.1

이 공지 요약 목록에는 2009년 3월 발표된 보안 공지가 포함되어 있습니다.

2009년 3월 공지 발표와 함께 이 공지 요약이 2009년 3월 5일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2009년 3월 12일 오전 3시(한국 표준시)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [3월 보안 공지 웹캐스트에 지금 등록하십시오.(영문)](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395124) 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-006">MS09-006</a></td>
<td style="border:1px solid black;"><strong>Windows 커널의 취약점으로 인한 원격 코드 실행 문제점 (958690)</strong><br />
<br />
이 보안 업데이트는 Windows 커널에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 가장 심각한 취약점의 경우 사용자가 영향을 받는 시스템에서 특수하게 조작된 EMF 또는 WMF 이미지 파일을 보면 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-007">MS09-007</a></td>
<td style="border:1px solid black;"><strong>SChannel의 취약점으로 인한 스푸핑 허용 문제점(960225)</strong><br />
<br />
이 보안 업데이트는 Windows의 Secure Channel(SChannel) 보안 패키지에서 비공개적으로 보고된 취약점을 해결합니다. 공격자가 최종 사용자가 인증에 사용한 인증서에 액세스할 수 있는 경우 이 취약점으로 인해 스푸핑이 허용됩니다. 고객은 공격자가 다른 방법을 통해 인증에 사용된 인증서의 공개 키 구성 요소를 획득한 경우에만 영향을 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
스푸핑</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-008">MS09-008</a></td>
<td style="border:1px solid black;"><strong>DNS 및 WINS 서버의 취약점으로 인한 스푸핑 허용 문제점 (962238)</strong><br />
<br />
이 보안 업데이트는 Windows DNS 서버 및 Windows WINS 서버에 대해 비공개적으로 보고된 취약점 2건 및 일반에 공개된 취약점 2건을 해결합니다. 이러한 취약점을 통해 원격 공격자가 인터넷을 통해 시스템에 대한 네트워크 트래픽을 공격자 자신의 시스템으로 리디렉션할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
스푸핑</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](http://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 공지 제목                                                      | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                                                         |  
|---------------------------------------------------------------------|----------------------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|  
| [MS09-006](http://technet.microsoft.com/security/bulletin/ms09-006) | Windows 커널의 취약점으로 인한 원격 코드 실행 문제점 (958690)  | [CVE-2009-0081 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0081) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 일관적인 서비스 거부 가능(일관적인 기능 코드 실행 제외)                                           |  
| [MS09-006](http://technet.microsoft.com/security/bulletin/ms09-006) | Windows 커널의 취약점으로 인한 원격 코드 실행 문제점 (958690)  | [CVE-2009-0082 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0082) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 일관적인 서비스 거부 가능(일관적인 기능 코드 실행 제외)                                           |  
| [MS09-006](http://technet.microsoft.com/security/bulletin/ms09-006) | Windows 커널의 취약점으로 인한 원격 코드 실행 문제점 (958690)  | [CVE-2009-0083 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0083) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 일관적인 서비스 거부 또는 정보 유출에 대한 로컬 위협 존재(일관적인 기능 코드 실행 제외)           |  
| [MS09-007](http://technet.microsoft.com/security/bulletin/ms09-007) | SChannel의 취약점으로 인한 스푸핑 허용 문제점 (960225)         | [CVE-2009-0085 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0085) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 일관적인 악용 가능성에 대한 요구 사항이 높으며 유효한 고객 시나리오의 수가 낮음                   |  
| [MS09-008](http://technet.microsoft.com/security/bulletin/ms09-008) | DNS 및 WINS 서버의 취약점으로 인한 스푸핑 허용 문제점 (962238) | [CVE-2009-0093 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0093) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 일관적인 개념 증명 스푸핑은 가능하지만 악의적인 코드 실행을 유발하는 기능 악용 코드는 거의 불가능 |  
| [MS09-008](http://technet.microsoft.com/security/bulletin/ms09-008) | DNS 및 WINS 서버의 취약점으로 인한 스푸핑 허용 문제점 (962238) | [CVE-2009-0094 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0094) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 일관적인 개념 증명 스푸핑은 가능하지만 악의적인 코드 실행을 유발하는 기능 악용 코드는 거의 불가능 |  
| [MS09-008](http://technet.microsoft.com/security/bulletin/ms09-008) | DNS 및 WINS 서버의 취약점으로 인한 스푸핑 허용 문제점 (962238) | [CVE-2009-0233 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0233) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 일관적인 개념 증명 스푸핑은 가능하지만 악의적인 코드 실행을 유발하는 기능 악용 코드는 거의 불가능 |  
| [MS09-008](http://technet.microsoft.com/security/bulletin/ms09-008) | DNS 및 WINS 서버의 취약점으로 인한 스푸핑 허용 문제점(962238)  | [CVE-2009-0234 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0234) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 일관적인 개념 증명 스푸핑은 가능하지만 악의적인 코드 실행을 유발하는 기능 악용 코드는 거의 불가능 |
  
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
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-006**](http://technet.microsoft.com/security/bulletin/ms09-006)
</td>
<td style="border:1px solid black;">
[**MS09-007**](http://technet.microsoft.com/security/bulletin/ms09-007)
</td>
<td style="border:1px solid black;">
[**MS09-008**](http://technet.microsoft.com/security/bulletin/ms09-008)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=98bb7d40-89a0-470a-8eb7-06f15072a635&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=bf7065bc-c183-4a78-8d46-72fe7385c07c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server 서비스 팩 4의 DNS 서버](https://www.microsoft.com/download/details.aspx?familyid=110354f7-5ece-4c4d-b563-3adba6ac0116&displaylang=ko)  
(961063)  
(중요)  
[Microsoft Windows 2000 Server 서비스 팩 4의 WINS 서버](https://www.microsoft.com/download/details.aspx?familyid=4319abb3-1ea2-466a-a815-c0b3b86b4462&displaylang=ko)  
(961064)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-006**](http://technet.microsoft.com/security/bulletin/ms09-006)
</td>
<td style="border:1px solid black;">
[**MS09-007**](http://technet.microsoft.com/security/bulletin/ms09-007)
</td>
<td style="border:1px solid black;">
[**MS09-008**](http://technet.microsoft.com/security/bulletin/ms09-008)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=e09641ba-6cbe-4095-82b5-703d3a7dc33b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=942d87f6-3cb1-4d36-a70a-70d9c34488f3&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d0d704c6-48c2-4907-b6c3-2455d7cf21c8)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6d02306e-9e2e-4ae8-bd21-8a2c1a229472)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-006**](http://technet.microsoft.com/security/bulletin/ms09-006)
</td>
<td style="border:1px solid black;">
[**MS09-007**](http://technet.microsoft.com/security/bulletin/ms09-007)
</td>
<td style="border:1px solid black;">
[**MS09-008**](http://technet.microsoft.com/security/bulletin/ms09-008)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f5cfb8da-e7cc-4183-8631-507c2a406500&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0b3f6fdd-276e-4267-99d8-8f00d91ad6a2&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2의 DNS 서버](https://www.microsoft.com/download/details.aspx?familyid=6cc42c9e-c34e-4577-8b23-9e07e2369878&displaylang=ko)  
(중요)  
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2의 WINS 서버](https://www.microsoft.com/download/details.aspx?familyid=049e5db5-7315-4188-99fd-4a54833e6bf2&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ecf75c70-8489-41ad-9759-3a07e13957be&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ce98ff55-f565-469d-bbd2-32b681faf908&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2의 DNS 서버](https://www.microsoft.com/download/details.aspx?familyid=b1f81fd2-0099-4450-8543-0459561d22d0&displaylang=ko)  
(중요)  
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2의 WINS 서버](https://www.microsoft.com/download/details.aspx?familyid=4a393c63-eff5-4c8c-9c3f-33ce45c32428&displaylang=ko)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=04be3d7e-7dda-4dca-887a-e7a8156ede1c)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=5ca3c72c-cadb-4b0a-b3a3-fb81d0bfd7b3)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)의 DNS 서버](https://www.microsoft.com/download/details.aspx?familyid=d3ed7d9a-d652-4bd0-aecc-5a415bec6c59)  
(961063)  
(중요)  
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)의 WINS 서버](https://www.microsoft.com/download/details.aspx?familyid=37e3a75e-0a5d-4df0-881f-cdb87efa4dcf)  
(961064)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-006**](http://technet.microsoft.com/security/bulletin/ms09-006)
</td>
<td style="border:1px solid black;">
[**MS09-007**](http://technet.microsoft.com/security/bulletin/ms09-007)
</td>
<td style="border:1px solid black;">
[**MS09-008**](http://technet.microsoft.com/security/bulletin/ms09-008)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 및 Windows Vista 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Vista 및 Windows Vista 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=4b1aaaba-f355-4265-83c0-50b901856ced&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 및 Windows Vista 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=21086a04-402a-4940-8358-7fa63508102b&displaylang=ko)  
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
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=0fcac480-d6db-4a94-8c7d-b7319282cf56&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=c75a2ea9-b42f-457b-be09-5c8fa0339388&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-006**](http://technet.microsoft.com/security/bulletin/ms09-006)
</td>
<td style="border:1px solid black;">
[**MS09-007**](http://technet.microsoft.com/security/bulletin/ms09-007)
</td>
<td style="border:1px solid black;">
[**MS09-008**](http://technet.microsoft.com/security/bulletin/ms09-008)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 (32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 (32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=38851df2-4fb5-4d28-9d15-181c260cf8cf&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 (32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=47b361ce-624b-466c-b5c5-8703f6532615&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 (32비트 시스템용)의 DNS 서버](https://www.microsoft.com/download/details.aspx?familyid=92e89882-d656-4b61-a05c-3afb44895f08&displaylang=ko)\*  
(961063)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 (x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 (x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=ec15acc4-3e0f-4414-9383-61c122ff1382&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 (x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=5c81ac45-60e6-4121-ab6b-d3b3179aacc4&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 (x64 기반 시스템용)의 DNS 서버](https://www.microsoft.com/download/details.aspx?familyid=be068d06-5939-4ad8-8191-e85931ed610f&displaylang=ko)\*  
(961063)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 (Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 (Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=eead6f93-10fd-4492-8137-481d9876a5fe)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 (Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=bf8f5a86-1757-4f9b-b632-d4aa7005a9f8)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**Windows Server 2008 참고 사항**

**\*Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** 지원 대상인 Windows Server 2008 에디션에 대해 이 업데이트의 심각도는 Windows Server 2008에 Server Core 설치 옵션의 사용 여부와 상관없이 동일하게 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://technet.microsoft.com/ko-kr/updatemanagement/default.aspx)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://www.microsoft.com/korea/protect/default.mspx)을 방문하거나 “최신 보안 업데이트”를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 및 [Office 업데이트](http://go.microsoft.com/fwlink/?linkid=21135)에서 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security%20update)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 이 달의 보안 업데이트를 위한 검색 및 배포 지침을 제공하였습니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), ESUIT(Extended Security Update Inventory Tool) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](http://support.microsoft.com/kb/910723)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](http://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.mspx)를 참조하십시오. SMS 2.0 사용자는[Software Updates Service Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=33340)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer와 Microsoft Office 검색 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit) 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트 (영문)](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](http://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security%20update)에서 다운로드할 수 있으며"security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://technet.microsoft.com/security/bulletin/policy)드립니다.

-   MS09-006에서 설명한 문제점을 보고해 주신 Helmut Buhler([http://home.arcor.de/clipboarder/ (영문)](http://home.arcor.de/clipboarder/))
-   MS09-006에서 설명한 문제점을 보고해 주신 [SkyRecon (영문)](http://www.skyrecon.com/)의 Thomas Garnier
-   MS09-007에서 설명한 문제점을 보고해 주신 [Secretaria da Fazenda do Estado do Rio Grande do Sul (포르투칼)](http://www.sefaz.rs.gov.br/)
-   MS09-007에서 설명한 문제점을 보고해 주신 [Cia de Processamento de Dados do Estado do Rio Grande do Sul (포르투칼)](http://www.procergs.rs.gov.br/)
-   MS09-008에서 설명한 두 가지 문제점을 해결하기 위해 협력해 주신 Kevin Day
-   MS09-008에서 설명한 두 가지 문제점을 해결하기 위해 협력해 주신 [Georgia Tech Information Security Center (영문)](http://www.gtisc.gatech.edu/)의 Dave Dagon

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 1577-9700을 통해 [Microsoft 고객 지원 센터](http://go.microsoft.com/fwlink/?linkid=21131)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2009년 3월 11일): 공지 요약이 게시되었습니다.
-   V1.1(2009년 3월 12일): MS09-008의 발견자 정보가 업데이트되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
