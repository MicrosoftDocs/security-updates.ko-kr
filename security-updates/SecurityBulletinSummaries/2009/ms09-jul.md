---
TOCTitle: 'MS09-JUL'
Title: 2009 년 7 월 Microsoft 보안 공지 요약
ms:assetid: 'ms09-jul'
ms:contentKeyID: 61230713
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms09-jul(v=Security.10)'
---


2009 년 7 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2009년 7월 15일 수요일 | 업데이트된 날짜: 2010년 3월 10일 수요일

**버전:** 8.0

이 공지 요약 목록에는 2009년 7월 발표된 보안 공지가 포함되어 있습니다.

2009년 7월 공지 발표와 함께 이 공지 요약이 2009년 7월 9일 게시된 공지 사전 알림과 2009년 7월 24일에 게시된 부정기 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2009년 7월 15일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 정기 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행했습니다. 현재 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 2009년 7월 28일 오후 1:00(태평양 표준시, 미국 및 캐나다)와 오후 4:00(태평양 표준시, 미국 및 캐나다)에 이 공지 요약의 버전 2.0에 추가된 부정기 보안 공지인 MS09-034 및 MS09-035에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. 지금 [7월 28일 오후 1:00 웹캐스트](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422339&culture=en-us)와 [7월 28일 오후 4:00 웹캐스트](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422341&culture=en-us)에 등록하십시오. 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-029">MS09-029</a></td>
<td style="border:1px solid black;"><strong>Embedded OpenType 글꼴 엔진의 취약점으로 인한 원격 코드 실행 문제점 (961371)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows 구성 요소인 EOT(Embedded OpenType) 글꼴 엔진에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점으로 인해 원격 코드 실행이 발생할 수 있습니다. 이러한 취약점 두 가지 중 하나를 성공적으로 악용한 공격자는 영향을 받는 시스템을 원격으로 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-028">MS09-028</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow의 취약점으로 인한 원격 코드 실행 문제점 (971633)</strong><br />
<br />
이 보안 업데이트는 Microsoft DirectShow의 공개된 취약점 1건과 비공개로 보고된 취약점 2건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 QuickTime 미디어 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-032">MS09-032</a></td>
<td style="border:1px solid black;"><strong>ActiveX 킬(Kill) 비트 누적 보안 업데이트 (973346)</strong><br />
<br />
이 보안 업데이트는 현재 악용되고 있는 비공개적으로 보고된 취약점 1건을 해결합니다. 사용자가 Internet Explorer로 ActiveX 컨트롤을 인스턴스화하는 특수하게 조작된 웹 페이지를 볼 경우 Microsoft 비디오 ActiveX 컨트롤의 취약점으로 인해 원격 코드 실행이 발생할 수 있습니다. 이 ActiveX 컨트롤은 Internet Explorer에서 인스턴스화하지 않도록 설계되었습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-034">MS09-034</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트 (972260)</strong><br />
<br />
이 보안 업데이트는 취약한 Microsoft ATL(액티브 템플릿 라이브러리) 버전을 사용하여 개발된 구성 요소와 컨트롤의 취약점에 대해 설명하는 Microsoft 보안 공지 MS09-035와 함께 릴리스되었습니다. 심층적인 보안 대응책으로써, 이 Internet Explorer 보안 업데이트는 Microsoft 보안 권고(973882) 및 Microsoft 보안 공지 MS09-035에 설명되어 있는 취약한 버전의 ATL로 개발된 구성 요소와 컨트롤을 이용하는 Internet Explorer의 알려진 공격 방법을 완화할 뿐만 아니라<br />
<br />
비공개적으로 보고된 Internet Explorer의 세 가지 취약점을 해결합니다. 이 취약점들은 모두 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-033">MS09-033</a></td>
<td style="border:1px solid black;"><strong>Virtual PC 및 Virtual Server의 취약점으로 인한 권한 상승 문제점 (969856)</strong><br />
<br />
이 보안 업데이트는 Microsoft Virtual PC 및 Microsoft Virtual Server의 비공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점 악용에 성공한 공격자는 임의 코드를 실행하여 영향을 받는 게스트 운영 체제를 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Virtual PC, Virtual Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-031">MS09-031</a></td>
<td style="border:1px solid black;"><strong>Microsoft ISA Server 2006의 취약점으로 인한 권한 상승 문제점 (970953)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft ISA(Internet Security and Acceleration) Server 2006의 취약점 1건을 해결합니다. 이 취약점으로 인해 공격자가 Kerberos 제한 위임과 함께 Radius OTP(일회용 암호) 인증 및 인증 위임을 사용하도록 구성된 ISA 서버의 관리 사용자 계정을 성공적으로 가장할 경우 권한 상승이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft ISA Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-030">MS09-030</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Publisher의 취약점으로 인한 원격 코드 실행 문제점(969516)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 취약점 1건을 해결합니다. 사용자가 특수하게 조작된 Publisher 파일을 열면 이 Microsoft Office Publisher 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-035">MS09-035</a></td>
<td style="border:1px solid black;"><strong>Visual Studio ATL(액티브 템플릿 라이브러리)의 취약점으로 인한 원격 코드 실행 문제점 (969706)</strong><br />
<br />
이 보안 업데이트는 Visual Studio에 포함되어 있는 Microsoft ATL(액티브 템플릿 라이브러리)의 공개 버전에서 비공개적으로 보고된 몇 가지 취약점을 해결합니다. 이 보안 업데이트는 구성 요소와 컨트롤을 개발하는 개발자를 위해 특별히 개발된 것입니다. ATL을 사용하여 구성 요소와 컨트롤을 만들고 재배포하는 개발자는 이 보안 공지에 제공된 업데이트를 설치하고, 함께 제공된 지침에 따라 이 보안 공지에서 설명하는 취약점을 갖지 않는 구성 요소와 컨트롤을 만들어 자신의 고객에게 배포해야 합니다.<br />
<br />
이 보안 공지에서는 사용자가 취약한 버전의 ATL로 작성된 구성 요소나 컨트롤을 로드할 경우 원격 코드가 실행될 수 있는 취약점에 대해 설명합니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">보통</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](http://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 공지 제목                                                                                    | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                 |  
|---------------------------------------------------------------------|----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|  
| [MS09-028](http://technet.microsoft.com/security/bulletin/ms09-028) | Microsoft DirectShow의 취약점으로 인한 원격 코드 실행 문제점 (971633)                        | [CVE-2009-1537 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1537) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.** |  
| [MS09-028](http://technet.microsoft.com/security/bulletin/ms09-028) | Microsoft DirectShow의 취약점으로 인한 원격 코드 실행 문제점 (971633)                        | [CVE-2009-1538 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1538) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS09-028](http://technet.microsoft.com/security/bulletin/ms09-028) | Microsoft DirectShow의 취약점으로 인한 원격 코드 실행 문제점 (971633)                        | [CVE-2009-1539 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1539) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS09-029](http://technet.microsoft.com/security/bulletin/ms09-029) | Embedded OpenType 글꼴 엔진의 취약점으로 인한 원격 코드 실행 문제점 (961371)                 | [CVE-2009-0231 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0231) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS09-029](http://technet.microsoft.com/security/bulletin/ms09-029) | Embedded OpenType 글꼴 엔진의 취약점으로 인한 원격 코드 실행 문제점 (961371)                 | [CVE-2009-0232 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0232) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS09-030](http://technet.microsoft.com/security/bulletin/ms09-030) | Microsoft Office Publisher의 취약점으로 인한 원격 코드 실행 문제점 (969516)                  | [CVE-2009-0566 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0566) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS09-031](http://technet.microsoft.com/security/bulletin/ms09-031) | Microsoft ISA Server 2006의 취약점으로 인한 권한 상승 문제점 (970953)                        | [CVE-2009-1135 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1135) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS09-032](http://technet.microsoft.com/security/bulletin/ms09-032) | ActiveX 킬(Kill) 비트 누적 보안 업데이트 (973346)                                            | [CVE-2008-0015 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.** |  
| [MS09-033](http://technet.microsoft.com/security/bulletin/ms09-033) | Virtual PC 및 Virtual Server의 취약점으로 인한 권한 상승 문제점 (969856)                     | [CVE-2009-1542 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1542) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 악용 결과가 비일관적인 기능 코드 실행이 가능합니다.       |  
| [MS09-034](http://technet.microsoft.com/security/bulletin/ms09-034) | Internet Explorer 누적 보안 업데이트 (972260)                                                | [CVE-2009-1917 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1917) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 기능 코드 실행은 쉽고 안전합니다.                         |  
| [MS09-034](http://technet.microsoft.com/security/bulletin/ms09-034) | Internet Explorer 누적 보안 업데이트 (972260)                                                | [CVE-2009-1918 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1918) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 악용 결과가 비일관적인 기능 코드 실행이 가능합니다.       |  
| [MS09-034](http://technet.microsoft.com/security/bulletin/ms09-034) | Internet Explorer 누적 보안 업데이트 (972260)                                                | [CVE-2009-1919 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1919) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 악용 결과가 비일관적인 기능 코드 실행이 가능합니다.       |  
| [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035) | Visual Studio ATL(액티브 템플릿 라이브러리)의 취약점으로 인한 원격 코드 실행 문제점 (969706) | [CVE-2009-0901 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 기능 코드 실행은 쉽고 안전합니다.                         |  
| [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035) | Visual Studio ATL(액티브 템플릿 라이브러리)의 취약점으로 인한 원격 코드 실행 문제점 (969706) | [CVE-2009-2493 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 기능 코드 실행은 쉽고 안전합니다.                         |  
| [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035) | Visual Studio ATL(액티브 템플릿 라이브러리)의 취약점으로 인한 원격 코드 실행 문제점 (969706) | [CVE-2009-2495 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 코드 실행 위험은 없으며 정보 누출 위험만 있습니다.        |
  
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
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://technet.microsoft.com/security/bulletin/ms09-034)
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
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=1efbbd95-cd72-43df-b1ce-7e2b0c0cb9e2&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 7.0](https://www.microsoft.com/download/details.aspx?familyid=e3e54348-6548-4162-b4c0-9910ec6e18b3&displaylang=ko)  
(긴급)  
[DirectX 8.1](https://www.microsoft.com/download/details.aspx?familyid=ce297c3e-8122-4276-a9c2-d1a404f8028d&displaylang=ko)  
(긴급)  
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=862db2ad-3c1f-4a26-af70-d8c4f5a69dda&displaylang=ko)\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=89d941f0-3f71-46e3-8096-716561396b72&displaylang=ko)  
(심각도 없음\*\*)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=50ffc8f4-7ab7-4e64-9965-5767db5f53cd&displaylang=ko)  
(긴급)  
[Microsoft Internet Explorer 6 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=93bd1baa-e2fb-4e8c-9dd7-738efef32282&displaylang=ko)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://technet.microsoft.com/security/bulletin/ms09-034)
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
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=6914167b-6961-480c-a4d4-808cd58a035b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=09d585cb-481d-4767-875e-9c6ebe456b80&displaylang=ko)\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=24701af8-b87e-4e85-9463-f50755a1b6ad&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=22bed634-5227-4a22-8df5-801f3e2e232a&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c874c8f8-0449-42b1-8d8b-901040069568&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0acc8aaa-0ae1-412a-9f2b-dc7c707cae00&displaylang=ko)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3b8b019e-e6d8-4ce2-8f1f-3a6399b252d1)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=f8cd4803-82da-467c-8cb1-520f5a6021d4)\*\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2cbf3699-7f79-4006-99e9-0a4c0d394c48)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=35ab0c5e-df3d-4873-8139-d1d98b3ac350)  
(긴급)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=113cc76a-c434-42ff-b594-4834989ad5ba)  
(긴급)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=29c8d9e6-2cb8-42b6-b0a6-2510fdb49eab)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://technet.microsoft.com/security/bulletin/ms09-034)
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
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=018ef53d-f78e-4084-940d-7c86bf59d83c&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=571d57c5-1ef8-4dc4-a1e5-2211a805f0cc&displaylang=ko)\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b0a458d6-c34c-41c7-964a-c130cfcb0d01&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=44852619-58ad-48f2-bc55-e8e1c72b1ba9&displaylang=ko)  
(보통)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f4112c25-9e6f-473a-bdbc-3df6dd66e6af&displaylang=ko)  
(보통)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=f4ae65a7-142f-4953-a542-315dac2ac606&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7f5fc902-f5d8-4a87-a73f-68632f9a0935&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=1779cbc0-0c29-4fac-a3a6-8b335ffcb98e&displaylang=ko)\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8b7a7bb0-80ef-4f25-bc70-3d0ac06007c5&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=bd7f36c6-c5c5-4f19-ab59-39f1aaba7fe2&displaylang=ko)  
(보통)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a594ee0d-ec8f-47df-9125-89d0bbf2115d&displaylang=ko)  
(보통)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3bc0e17b-898b-4f29-aa29-607527e1c1cd&displaylang=ko)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=7df0fce2-543c-4e82-85e6-012bfc8bf130)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=48282a89-f849-405a-a31e-2676f45b5042)\*\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=7be36edf-02af-402f-983a-f9ca8128b6b5)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=cdb70acf-77c3-40a4-b6a3-0fbc0fc0d7fc)  
(보통)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=adb6bad2-9931-4ede-856e-bb43bb0f6071)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://technet.microsoft.com/security/bulletin/ms09-034)
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
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c67d85c4-25c5-4821-8db9-91764888f893&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6c90240e-c201-4dad-9835-ea71e3527b45&displaylang=ko)  
(심각도 없음\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d3be9a13-1a5b-4b74-9649-449df923f573&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b05a19f7-7412-4c2b-ad11-34396e54ca43&displaylang=ko)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3f8ae651-59f7-48e1-9e8c-8e07c6806964&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d2084e8d-212b-4c39-9163-a71ec6d1b1c7&displaylang=ko)  
(심각도 없음\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2b23cd74-6cf1-413b-82a7-b602347e3ce6&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=900e9a05-2f71-42de-b603-47e4ac061bcb&displaylang=ko)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://technet.microsoft.com/security/bulletin/ms09-034)
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
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=91f6ee68-0e39-4ec3-b4cd-45f05404e2fb&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0194f994-5821-4fb9-b9e1-ed6af248c995&displaylang=ko)\*  
(심각도 없음\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=92e3af41-71b0-4a28-afc7-123733180ead&displaylang=ko)\*  
(보통)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=30f99bda-9107-4969-90af-2a30e12acdae&displaylang=ko)\*  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5cdc3014-97b3-47b5-a6b7-cd0e12ec60e4&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4127b125-fdaa-489a-a80c-14b5647ac7e0&displaylang=ko)\*  
(심각도 없음\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1958ec40-3b7b-43a9-9fdc-742735dcf516&displaylang=ko)\*  
(보통)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=acd3667b-6676-4010-b23b-e8372dd55f93&displaylang=ko)\*  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=03330a14-9cfa-4146-a3d3-4b7a76975d2d)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4082c776-318c-4e0c-83fc-2f3f472c039a)  
(심각도 없음\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=470387ac-6d75-4b7e-8ca5-376b67a8bd4d)  
(보통)
</td>
</tr>
</table>
 
**Windows Server 2008 참고 사항**

**\*\*Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 Windows Server 2008이 설치된 경우 이 업데이트에서 해결하는 취약점은 지원되는 모든 Windows Server 2008 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

**MS09-032 참고 사항**

**\*\*** 이 공지에서 설명한 취약점이 이 소프트웨어에 영향을 미치지 않으므로 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 나중에 발생 가능한 새로운 경로를 방지하기 위한 심층적인 보안 대응책으로써 이 소프트웨어를 사용하는 고객은 이 보안 업데이트를 적용하는 것이 좋습니다.

**MS09-028 참고 사항**

**\*\*\*** DirectX 8.1의 업데이트는 DirectX 8.1b에도 적용됩니다.

**\*\*\*\*** DirectX 9.0의 업데이트는 DirectX 9.0a, DirectX 9.0b, DirectX 9.0c에도 적용됩니다.

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
<th style="border:1px solid black;" colspan="2">
Microsoft Office 제품군, 시스템 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-030**](http://technet.microsoft.com/security/bulletin/ms09-030)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=d4b0665d-5744-49c7-a3c0-f231fd08d3b8&displaylang=ko)  
(KB969516)  
(중요)
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
<th style="border:1px solid black;" colspan="2">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-035**](http://technet.microsoft.com/security/bulletin/ms09-035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=63ce454e-f69c-44e3-89fb-eb23c2e2154e&displaylang=ko)  
(KB971089)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=7c8729dc-06a2-4538-a90d-ff9464dc0197&displaylang=ko)  
(KB971090)  
(보통)  
[Microsoft Visual Studio 2005 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=9d7ee45b-9892-41b5-ac08-5fde9cde1b42&displaylang=ko)\*  
(KB973673)  
(보통)  
[Microsoft Visual Studio 2005 서비스 팩 1(64비트 호스팅 Visual C++ 도구)](https://www.microsoft.com/download/details.aspx?familyid=43f96f2a-69c6-4c5e-b72c-0edfa35f4fc2&displaylang=ko)  
(KB973830)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Embedded CE 6.0
</td>
<td style="border:1px solid black;">
[Windows Embedded CE 6.0](https://www.microsoft.com/download/details.aspx?familyid=99d114f8-4d95-4075-a0f1-45f498f0ade8)\*\*  
(KB974616)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](https://www.microsoft.com/download/details.aspx?familyid=8f9da646-94dd-469d-baea-a4306270462c&displaylang=ko)  
(KB971091)  
(보통)  
[Microsoft Visual Studio 2008](https://www.microsoft.com/download/details.aspx?familyid=e3bb6602-b7f4-4614-9999-77f5c6f66ccd&displaylang=ko)\*  
(KB973674)  
(보통)  
[Microsoft Visual Studio 2008 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=294de390-3c94-49fb-a014-9a38580e64cb&displaylang=ko)  
(KB971092)  
(보통)  
[Microsoft Visual Studio 2008 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=75fbf397-5140-4961-92a9-78a88ba7228f&displaylang=ko)\*  
(KB973675)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2005 서비스 팩 1 재배포 가능 패키지](https://www.microsoft.com/download/details.aspx?familyid=766a6af7-ec73-40ff-b072-9112bab119c2&displaylang=ko)  
(KB973544)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual C++ 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2008 재배포 가능 패키지](https://www.microsoft.com/download/details.aspx?familyid=8b29655e-9da4-4b6b-9ac5-687ca0770f93&displaylang=ko)  
(KB973551)  
(보통)  
[Microsoft Visual C++ 2008 서비스 팩 1 재배포 가능 패키지](https://www.microsoft.com/download/details.aspx?familyid=2051a0c1-c9b5-4b0a-a8f5-770a549fd78c&displaylang=ko)  
(KB973552)  
(보통)
</td>
</tr>
</table>
 
**MS09-035 참고 사항**

\*스마트 장치용 ATL을 사용하는 모바일 응용 프로그램용

\*\*Windows Embedded CE 6.0 월별 업데이트(2009년 12월)를 설치하십시오. 이 업데이트 패키지는 Microsoft 다운로드 센터에서만 다운로드할 수 있습니다.

#### Microsoft Server and Security Software

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Internet Security and Acceleration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-031**](http://technet.microsoft.com/security/bulletin/ms09-031)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](https://www.microsoft.com/download/details.aspx?familyid=c4e9b1dd-526d-407b-bc23-ebc2738b1b19&displaylang=ko)  
(KB970811)  
(중요)  
[Microsoft Internet Security and Acceleration Server 2006 지원 업데이트](https://www.microsoft.com/download/details.aspx?familyid=e8ccd770-a925-411c-b994-78e4cf5c3476&displaylang=ko)  
(KB970811)  
(중요)  
[Microsoft Internet Security and Acceleration Server 2006 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=e536cfed-c1af-4868-b2ac-79178d6355a5&displaylang=ko)  
(KB970811)  
(중요)
</td>
</tr>
</table>
 

#### Microsoft 가상화 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Virtual PC
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-033**](http://technet.microsoft.com/security/bulletin/ms09-033)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2004
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2004 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=56a160e1-59b5-45bc-aecf-dfe614a7efad)  
(KB969856)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual PC 2007
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007](https://www.microsoft.com/download/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
(중요)  
[Microsoft Virtual PC 2007 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2007 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
(중요)  
[Microsoft Virtual PC 2007 x64 Edition 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Virtual Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-033**](http://technet.microsoft.com/security/bulletin/ms09-033)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005](https://www.microsoft.com/download/details.aspx?familyid=85d4f910-4c13-4229-aba7-b9d6181d78c8)  
(KB969856)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57&displaylang=ko)  
(KB969856)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 x64 Edition 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57&displaylang=ko)  
(KB969856)  
(중요)
</td>
</tr>
</table>
 

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://technet.microsoft.com/ko-kr/updatemanagement/default.aspx)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://www.microsoft.com/korea/protect/default.mspx)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**참고** 2009년 8월 1일부터 Microsoft는 Office 업데이트와 Office 업데이트 인벤토리 도구에 대한 지원을 중단합니다. 계속해서 Microsoft Office 제품에 필요한 최신 업데이트를 받으려면 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)를 사용하십시오. 자세한 내용은 [Microsoft Office 업데이트 정보: 자주 제기되는 질문 사항(FAQ) (영문)](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx)을 참조하십시오.

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
-   [Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트 (영문)](http://technet.microsoft.com/en-us/wsus/dd573344.aspx)

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](http://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://technet.microsoft.com/security/bulletin/policy)드립니다.

-   MS09-028에서 설명한 문제점을 보고해 주신 [SkyRecon (영문)](http://www.skyrecon.com/)의 Thomas Garnier 및 [Qihoo 360 Security Center (영문)](http://www.360.cn/)의 Zheng Wenbin, Liu Qi 및 Song Shenlei
-   MS09-028에서 설명한 문제점을 보고해 주신 [Palo Alto Networks (영문)](http://www.paloaltonetworks.com/)의 Yamata Li
-   MS09-028에서 설명한 문제점을 TippingPoint의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/), [SkyRecon (영문)](http://www.skyrecon.com/)의 Thomas Garnier 및 [Palo Alto Networks (영문)](http://www.paloaltonetworks.com/)의 Yamata Li와 협력하여 보고해 주신 [TippingPoint DVLabs (영문)](http://dvlabs.tippingpoint.com/)의 Aaron Portnoy 및 익명 연구자
-   MS09-029에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)
-   MS09-029에서 설명한 문제점을 보고해 주신 Thomas Garnier
-   MS09-030에서 설명한 문제점을 [VeriSign iDefense Labs (영문)](http://www.idefense.com/)와 협력하여 보고해 주신 [Labo Skopia (영문)](http://www.laboskopia.com/)의 Lionel d'Hauenens
-   MS09-032에서 설명한 문제점을 처음 보고해 주신 [IBM IIS X-Force (영문)](http://www.iss.net/)의 Ryan Smith 및 Alex Wheeler
-   MS09-033에서 설명한 문제점을 보고해 주신 [Google Inc. (영문)](http://www.google.com/)의 Julien Tinnes 및 Tavis Ormandy
-   MS09-034에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Peter Vreugdenhil
-   MS09-034에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 [team509 (영문)](http://www.team509.com/)의 Wushi 및 Ling
-   MS09-034에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Peter Vreugdenhil
-   MS09-035에서 설명한 문제점을 보고해 주신 [IBM ISS X-Force (영문)](http://www.iss.net/)의 David Dewey
-   MS09-035에서 설명한 두 가지 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Ryan Smith

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2009년 7월 15일): 공지 요약이 게시되었습니다.
-   V1.1(2009년 7월 15일): MS09-032의 요약이 업데이트되고, MS09-029의 다시 시작 요구 사항이 수정되었으며 기타 내용이 편집되었습니다.
-   V2.0(2009년 7월 29일): Microsoft 보안 공지 MS09-034, Internet Explorer 누적 보안 업데이트(972260) 및 MS09-035, Visual Studio ATL(액티브 템플릿 라이브러리)의 취약점으로 인한 원격 코드 실행 문제점(969706)이 추가되었습니다. 또한 이 부정기 보안 업데이트에 대한 공지 웹캐스트 링크가 추가되었습니다.
-   V3.0 (2009년 8월 5일): Microsoft Windows 2000 서비스 팩 4에 설치된 Microsoft Internet Explorer 6 서비스 팩 1의 업데이트가 다시 발행되었음을 알리도록 개정되었습니다. 이미 Microsoft Windows 2000 서비스 팩 4의 Internet Explorer 6 서비스 팩 1의 원본 업데이트를 설치한 모든 고객은 이미 보호되고 있습니다. 그러나 Internet Explorer 6 서비스 팩 1의 한국어 버전을 사용하는 고객은 동일한 보호 기능을 보유하고 인쇄 문제도 해결하기 위해 Windows 2000 시스템의 Internet Explorer 6 서비스 팩 1의 업데이트를 다시 설치할 수 있습니다. Microsoft 보안 공지 MS09-034를 검토하십시오.
-   V4.0(2009년 8월 12일): Visual Studio를 사용하여 스마트 장치용 ATL을 사용하는 모바일 응용 프로그램에 대한 구성 요소 및 컨트롤을 만드는 개발자에게 Microsoft Visual Studio 2005 서비스 팩 1(KB973673), Microsoft Visual Studio 2008(KB973674) 및 Microsoft Visual Studio 2008 서비스 팩 1(KB973675)에 대한 신규 업데이트를 제공하기 위해 MS09-035가 다시 릴리스되었으며 이를 알리기 위해 공지가 개정되었습니다.
-   V4.1(2009년 8월 14일): MS09-035의 다시 시작 요구 사항이 수정되었습니다.
-   V5.0(2009년 8월 20일): DirectX 8.1의 영향을 받는 소프트웨어를 설명하기 위해 공지 MS09-028에 대한 각주가 추가되었습니다.
-   V6.0(2009년 8월 26일): Windows XP 서비스 팩 2, Windows XP 서비스 팩 3 및 Windows XP Professional x64 Edition 서비스 팩 2에 대한 일본어 업데이트가 다시 발표되었음을 알리기 위해 개정되었습니다. 원본 업데이트를 설치한 고객은 이미 보호되고 있습니다. 그러나 일본어 버전의 Windows XP 서비스 팩 2, Windows XP 서비스 팩 3 또는 Windows XP Professional x64 Edition 서비스 팩 2를 사용하는 고객은 동일한 보호 기능을 보유하고 인쇄 문제를 해결하기 위해 업데이트를 다시 설치해야 합니다. Microsoft 보안 공지 MS09-029를 검토하십시오.
-   7.0(2010년 1월 13일): MS09-035의 영향을 받는 소프트웨어에 Windows Embedded CE 6.0을 추가하기 위해 개정되었습니다. Windows Embedded CE 6.0(KB974616)에 대한 업데이트는 Microsoft 다운로드 센터에서만 다운로드할 수 있는 누적 업데이트입니다. Windows Embedded CE 6.0 플랫폼을 사용하는 고객은 누적 업데이트 적용을 고려해야 합니다.
-   V8.0(2010년 3월 10일): MS09-033의 영향을 받는 소프트웨어에 Microsoft Virtual Server 2005를 추가하기 위해 개정되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
