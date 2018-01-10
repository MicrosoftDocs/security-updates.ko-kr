---
TOCTitle: 'MS14-DEC'
Title: 2014년 12월 Microsoft 보안 공지 요약
ms:assetid: 'ms14-dec'
ms:contentKeyID: 63745963
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms14-dec(v=Security.10)'
---

2014년 12월 Microsoft 보안 공지 요약
====================================

게시된 날짜: 2014년 12월 10일

**버전:** 1.0

이 공지 요약에는 2014년 12월에 발표된 보안 공지가 나와 있습니다.

2014년 12월 보안 공지 발표와 함께 이 공지 요약이 2014년 12월 4일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/ko-kr/security/gg309152.aspx)(영문)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/ko-kr/security/dd252948.aspx)을 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향받는 소프트웨어**를 참조하십시오.

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 ID</strong></td>
<td style="border:1px solid black;"><strong>공지 제목 및 요약</strong></td>
<td style="border:1px solid black;"><strong>최대 심각도 및 취약성 영향</strong></td>
<td style="border:1px solid black;"><strong>다시 시작 요구 사항</strong></td>
<td style="border:1px solid black;"><strong>영향받는 소프트웨어</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server의 취약성으로 인한 권한 상승 문제(3009712)<br />
<br />
</strong>이 보안 업데이트는 Microsoft Exchange Server에서 발견되어 비공개적으로 보고된 취약성 4건을 해결합니다. 이 중에서 가장 심각한 취약성으로 인해 사용자가 특수 제작된 URL을 클릭하여 대상 Outlook Web App 사이트로 유인되는 경우 권한 상승 문제가 발생할 수 있습니다. 공격자는 강제로 사용자가 특수 제작된 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하고 특수 제작된 URL을 클릭하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3008923)<br />
<br />
</strong>이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약성 14건을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-081">MS14-081</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word 및 Microsoft Office Web Apps의 취약성으로 인한 원격 코드 실행 문제(3017301)<br />
<br />
</strong>이 보안 업데이트는 Microsoft Word 및 Microsoft Office Web Apps의 비공개적으로 보고된 취약성 2건을 해결합니다. 공격자가 사용자에게 특수 제작된 Microsoft Word 파일을 영향받는 버전의 Microsoft Office 소프트웨어에서 열거나 미리 보도록 유도할 경우 이러한 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다. 이 취약성을 악용한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그인한 경우 공격자는 프로그램을 설치하여 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-082">MS14-082</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office의 취약성으로 인한 원격 코드 실행 문제(3017349)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약성을 해결합니다. 이 취약성으로 인해 영향을 받는 Microsoft Office 버전에서 특수 제작된 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약성을 성공적으로 악용한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-083">MS14-083</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel의 취약성으로 인한 원격 코드 실행 문제(3017347)<br />
<br />
</strong>이 보안 업데이트는 Microsoft Excel에서 발견되어 비공개적으로 보고된 취약성 2건을 해결합니다. 공격자가 사용자에게 특수 제작된 Microsoft Excel 파일을 영향받는 버전의 Microsoft Office 소프트웨어에서 열거나 미리 보도록 유도할 경우 이러한 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다. 이 취약성을 악용한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그인한 경우 공격자는 프로그램을 설치하여 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-084">MS14-084</a></td>
<td style="border:1px solid black;"><strong>VBScript 스크립팅 엔진의 취약성으로 인한 원격 코드 실행 문제(3016711)<br />
<br />
</strong>이 보안 업데이트는 Microsoft Windows의 VBScript 스크립팅 엔진에서 비공개적으로 보고된 취약성을 해결합니다. 이 취약성으로 인해 사용자가 특수 제작된 웹 사이트를 방문할 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약성을 성공적으로 악용한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우, 이 취약성을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-085">MS14-085</a></td>
<td style="border:1px solid black;"><strong>Microsoft 그래픽 구성 요소의 취약성으로 인한 정보 유출 문제(3013126)<br />
<br />
</strong>이 보안 업데이트는 Microsoft Windows의 공개적으로 보고된 취약성을 해결합니다. 이 취약성으로 인해 사용자가 특수 제작된 JPEG 콘텐츠가 포함된 웹 사이트로 이동할 경우 정보가 공개될 수 있습니다. 공격자는 이 정보 유출 취약성을 이용하여 시스템에 대한 정보를 얻은 후 해당 시스템을 손상시키기 위해 다른 공격과 이 정보를 결합할 수 있습니다. 이 정보 유출 취약성만으로는 임의의 코드 실행이 허용되지 않지만 공격자는 다른 취약성과 함께 이 정보 유출 취약성을 이용하여 ASLR(Address Space Layout Randomization)과 같은 보안 기능을 우회할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
악용 가능성 인덱스  
------------------
  
<span id="sectionToggle1"></span>
다음 표는 이달에 해결한 각 취약성의 악용 가능성 평가입니다. 취약성은 공지 ID 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약성만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/ko-kr/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 릴리스를 나타냅니다.
  
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 ID</strong></td>
<td style="border:1px solid black;"><strong>취약성 제목</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>최신 소프트웨어 릴리스에 대한 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>이전 소프트웨어 릴리스에 대한 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>서비스 거부 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>주요 정보</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">Outlook Web App 토큰 스푸핑 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6319">CVE-2014-6319</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 정보 공개 취약성입니다. 이 취약성은 소셜 엔지니어링 공격의 스푸핑에 사용할 수 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">OWA XSS 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6325">CVE-2014-6325</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약성입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">OWA XSS 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6326">CVE-2014-6326</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">Exchange URL 리디렉션 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6336">CVE-2014-6336</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 정보 공개 취약성입니다. 이 취약성은 소셜 엔지니어링 공격의 스푸핑에 사용할 수 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6327">CVE-2014-6327</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer XSS 필터 우회 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6328">CVE-2014-6328</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 보안 기능 우회 취약성입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6329">CVE-2014-6329</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6330">CVE-2014-6330</a></td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">VBScript 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6363">CVE-2014-6363</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer XSS 필터 우회 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6365">CVE-2014-6365</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 보안 기능 우회 취약성입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6366">CVE-2014-6366</a></td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR 우회 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6368">CVE-2014-6368</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 보안 기능 우회 취약성입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6369">CVE-2014-6369</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6373">CVE-2014-6373</a></td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6374">CVE-2014-6374</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6375">CVE-2014-6375</a></td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6376">CVE-2014-6376</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-080">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-8966">CVE-2014-8966</a></td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-081">MS14-081</a></td>
<td style="border:1px solid black;">잘못된 인덱스 원격 코드 실행 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6356">CVE-2014-6356</a></td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-081">MS14-081</a></td>
<td style="border:1px solid black;">Word 원격 코드 실행 해제 후 사용 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6357">CVE-2014-6357</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-082">MS14-082</a></td>
<td style="border:1px solid black;">Microsoft Office 구성 요소 해제 후 사용 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6364">CVE-2014-6364</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-083">MS14-083</a></td>
<td style="border:1px solid black;">Excel의 원격 코드 실행 글로벌 해제 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6360">CVE-2014-6360</a></td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-083">MS14-083</a></td>
<td style="border:1px solid black;">Excel의 잘못된 포인터 원격 코드 실행 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6361">CVE-2014-6361</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-084">MS14-084</a></td>
<td style="border:1px solid black;">VBScript 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6363">CVE-2014-6363</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 원격 코드 실행 취약성입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms14-085">MS14-085</a></td>
<td style="border:1px solid black;">그래픽 구성 요소 정보 유출 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6355">CVE-2014-6355</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약성입니다.</td>
</tr>
</tbody>
</table>
  
 
  
영향받는 소프트웨어  
-------------------
  
<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.
  
**참고** 단일 취약성에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
### Windows 운영 체제 및 구성 요소

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://technet.microsoft.com/ko-kr/library/security/ms14-080)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://technet.microsoft.com/ko-kr/library/security/ms14-084)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://technet.microsoft.com/ko-kr/library/security/ms14-085)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(보통)  
Internet Explorer 7  
(3008923)  
(보통)  
Internet Explorer 8  
(3008923)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3012168)  
(보통)  
VBScript 5.7   
(3012172)  
(보통)  
VBScript 5.8   
(3012176)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(보통)  
Internet Explorer 7  
(3008923)  
(보통)  
Internet Explorer 8  
(3008923)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3012168)  
(보통)  
VBScript 5.7   
(3012172)  
(보통)  
VBScript 5.8   
(3012176)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(보통)  
Internet Explorer 7  
(3008923)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3012168)  
(보통)  
VBScript 5.7   
(3012172)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://technet.microsoft.com/ko-kr/library/security/ms14-080)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://technet.microsoft.com/ko-kr/library/security/ms14-084)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://technet.microsoft.com/ko-kr/library/security/ms14-085)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(긴급)  
Internet Explorer 8  
(3008923)  
(긴급)  
Internet Explorer 9  
(3008923)  
(긴급)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(긴급)  
VBScript 5.8   
(IE8 포함 시스템만)<sup>[1]</sup>
(3012176)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(긴급)  
Internet Explorer 8  
(3008923)  
(긴급)  
Internet Explorer 9  
(3008923)  
(긴급)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(긴급)  
VBScript 5.8   
(IE8 포함 시스템만)<sup>[1]</sup>
(3012176)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://technet.microsoft.com/ko-kr/library/security/ms14-080)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://technet.microsoft.com/ko-kr/library/security/ms14-084)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://technet.microsoft.com/ko-kr/library/security/ms14-085)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(보통)  
Internet Explorer 8  
(3008923)  
(보통)  
Internet Explorer 9  
(3008923)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(보통)  
VBScript 5.8   
(IE8 포함 시스템만)<sup>[1]</sup>
(3012176)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(보통)  
Internet Explorer 8  
(3008923)  
(보통)  
Internet Explorer 9  
(3008923)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(보통)  
VBScript 5.8   
(IE8 포함 시스템만)<sup>[1]</sup>
(3012176)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://technet.microsoft.com/ko-kr/library/security/ms14-080)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://technet.microsoft.com/ko-kr/library/security/ms14-084)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://technet.microsoft.com/ko-kr/library/security/ms14-085)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(긴급)  
Internet Explorer 9  
(3008923)  
(긴급)  
Internet Explorer 10  
(3008923)  
(긴급)  
Internet Explorer 11  
(3008923)  
(긴급)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(IE8 포함 시스템만)<sup>[1]</sup>
(3012176)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(긴급)  
Internet Explorer 9  
(3008923)  
(긴급)  
Internet Explorer 10  
(3008923)  
(긴급)  
Internet Explorer 11  
(3008923)  
(긴급)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(IE8 포함 시스템만)<sup>[1]</sup>
(3012176)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://technet.microsoft.com/ko-kr/library/security/ms14-080)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://technet.microsoft.com/ko-kr/library/security/ms14-084)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://technet.microsoft.com/ko-kr/library/security/ms14-085)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(보통)  
Internet Explorer 9  
(3008923)  
(보통)  
Internet Explorer 10  
(3008923)  
(보통)  
Internet Explorer 11  
(3008923)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(IE8 포함 시스템만)<sup>[1]</sup>
(3012176)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(IE8 포함 시스템만)<sup>[1]</sup>
(3012176)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://technet.microsoft.com/ko-kr/library/security/ms14-080)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://technet.microsoft.com/ko-kr/library/security/ms14-084)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://technet.microsoft.com/ko-kr/library/security/ms14-085)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://technet.microsoft.com/ko-kr/library/security/ms14-080)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://technet.microsoft.com/ko-kr/library/security/ms14-084)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://technet.microsoft.com/ko-kr/library/security/ms14-085)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://technet.microsoft.com/ko-kr/library/security/ms14-080)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://technet.microsoft.com/ko-kr/library/security/ms14-084)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://technet.microsoft.com/ko-kr/library/security/ms14-085)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](https://technet.microsoft.com/ko-kr/library/security/ms14-080)

</td>
<td style="border:1px solid black;">
[**MS14-084**](https://technet.microsoft.com/ko-kr/library/security/ms14-084)

</td>
<td style="border:1px solid black;">
[**MS14-085**](https://technet.microsoft.com/ko-kr/library/security/ms14-085)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(심각도 없음)<sup>[2]</sup>
VBScript 5.8   
(3012176)  
(심각도 없음)<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(심각도 없음)<sup>[2]</sup>
VBScript 5.8   
(3012176)  
(심각도 없음)<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(3012176)  
(심각도 없음)<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3013126)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3013126)  
(중요)

</td>
</tr>
</table>
 
**MS14-080 참고 사항**

Windows Technical Preview 및 Windows Server Technical Preview가 영향을 받습니다. 해당 운영 체제를 실행하는 고객은 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)에서 제공되는 이 업데이트를 적용하는 것이 좋습니다.

**MS14-084 참고 사항**

VBScript 5.8에 대한 업데이트는 Windows Technical Preview 및 Windows Server Technical Preview용으로 제공되며 Internet Explorer 누적 업데이트 3008923([MS14-080](https://technet.microsoft.com/ko-kr/library/security/ms14-080))으로 제공됩니다. Preview 버전을 실행하는 고객은 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)에서 제공되는 이 업데이트를 적용하는 것이 좋습니다.

<sup>[1]</sup>Internet Explorer 8이 설치되어 있는 시스템에 적용됩니다. 시스템에서 Internet Explorer 9 이상을 실행하는 고객은 Internet Explorer 누적 업데이트([MS14-080](https://technet.microsoft.com/ko-kr/library/security/ms14-080))를 적용해야 합니다. 이 업데이트는 MS14-084에 설명된 취약성을 해결합니다.

<sup>[2]</sup>MS14-084에서 설명한 취약성에 대해 알려진 Internet Explorer를 통한 공격 경로가 차단되므로 지정된 소프트웨어에 대한 심각도가 적용되지 않습니다. 그러나 나중에 발생 가능한 새로운 경로를 방지하기 위한 심층 보안 대응책으로 이 소프트웨어의 고객은 이 보안 업데이트를 적용하는 것이 좋습니다.

 

### Microsoft Server 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-075**](https://technet.microsoft.com/ko-kr/library/security/ms14-075)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 서비스 팩 3  
(2996150)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-075**](https://technet.microsoft.com/ko-kr/library/security/ms14-075)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 서비스 팩 3  
(2986475)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 서비스 팩 1  
(3011140)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 6  
(3011140)  
(중요)

</td>
</tr>
</table>
 
 

### Microsoft Office 제품군 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://technet.microsoft.com/ko-kr/library/security/ms14-081)

</td>
<td style="border:1px solid black;">
[**MS14-082**](https://technet.microsoft.com/ko-kr/library/security/ms14-082)

</td>
<td style="border:1px solid black;">
[**MS14-083**](https://technet.microsoft.com/ko-kr/library/security/ms14-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 서비스 팩 3  
(2920793)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(2596927)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 서비스 팩 3  
(2984942)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://technet.microsoft.com/ko-kr/library/security/ms14-081)

</td>
<td style="border:1px solid black;">
[**MS14-082**](https://technet.microsoft.com/ko-kr/library/security/ms14-082)

</td>
<td style="border:1px solid black;">
[**MS14-083**](https://technet.microsoft.com/ko-kr/library/security/ms14-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(2899518)  
(긴급)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(2899519)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(2553154)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 서비스 팩 2(32비트 버전)  
(2910902)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(2899518)  
(긴급)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(2899519)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(2553154)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 서비스 팩 2(64비트 버전)  
(2910902)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013 및 Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://technet.microsoft.com/ko-kr/library/security/ms14-081)

</td>
<td style="border:1px solid black;">
[**MS14-082**](https://technet.microsoft.com/ko-kr/library/security/ms14-082)

</td>
<td style="border:1px solid black;">
[**MS14-083**](https://technet.microsoft.com/ko-kr/library/security/ms14-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013(32비트 버전)  
(2910916)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 버전)  
(2726958)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013(32비트 버전)  
(2910929)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(2910916)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(2726958)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 서비스 팩 1(32비트 버전)  
(2910929)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013(64비트 버전)  
(2910916)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 버전)  
(2726958)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013(64비트 버전)  
(2910929)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(2910916)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)  
(2726958)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 서비스 팩 1(64비트 버전)  
(2910929)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT  
(2910916)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2726958)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2910929)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT 서비스 팩 1  
(2910916)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1  
(2726958)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT 서비스 팩 1  
(2910929)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://technet.microsoft.com/ko-kr/library/security/ms14-081)

</td>
<td style="border:1px solid black;">
[**MS14-082**](https://technet.microsoft.com/ko-kr/library/security/ms14-082)

</td>
<td style="border:1px solid black;">
[**MS14-083**](https://technet.microsoft.com/ko-kr/library/security/ms14-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3018888)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**기타 Office 소프트웨어**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://technet.microsoft.com/ko-kr/library/security/ms14-081)

</td>
<td style="border:1px solid black;">
[**MS14-082**](https://technet.microsoft.com/ko-kr/library/security/ms14-082)

</td>
<td style="border:1px solid black;">
[**MS14-083**](https://technet.microsoft.com/ko-kr/library/security/ms14-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2920729)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(2920792)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(2920790)  
(중요)

</td>
</tr>
</table>
 
**MS14-081 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오. 

 

### Microsoft Office Services 및 Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://technet.microsoft.com/ko-kr/library/security/ms14-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2899581)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://technet.microsoft.com/ko-kr/library/security/ms14-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883050)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883050)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://technet.microsoft.com/ko-kr/library/security/ms14-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 서비스 팩 2  
(2910892)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](https://technet.microsoft.com/ko-kr/library/security/ms14-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2889851)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1  
(2889851)  
(중요)

</td>
</tr>
</table>
 
**MS14-081 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

검색, 배포 도구 및 지침
-----------------------

<span id="sectionToggle3"></span>
관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 존재합니다.

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트와 일반적인 잘못된 구성을 검색할 수 있습니다.

WSUS(Windows Server Update Services), SMS(Systems Management Server) 및 System Center Configuration Manager를 통해 관리자가 보안 업데이트를 배포할 수 있습니다.

ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](http://technet.microsoft.com/ko-kr/security/cc297183)를 참조하십시오.

감사의 말
---------

<span id="sectionToggle4"></span>
Microsoft는 신뢰할 수 있는 취약성 공개를 통해 고객을 보호하는 데 도움을 주는 보안 커뮤니티의 이러한 공로를 기립니다. 자세한 내용은 [감사의 말](https://technet.microsoft.com/ko-kr/library/security/dn820091.aspx)(영문)을 참조하십시오.

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 릴리스에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 릴리스에서 사용할 수 없습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199/ko): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/ko-kr/windowsserver/bb332157.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객을 위한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약성 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://technet.microsoft.com/ko-kr/security/dn467918)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://technet.microsoft.com/ko-kr/library/bb466251.aspx)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/ko-kr/download/search.aspx?q=security%20update)에서 다운로드할 수 있으며 "보안 업데이트"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086/ko)을 참조하십시오.

**IT Pro Security Community(IT 전문가 보안 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://technet.microsoft.com/ko-kr/security/cc136632.aspx)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.

IT 전문가용 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/ko-kr/security/bb980617)

Windows 컴퓨터를 바이러스 및 맬웨어로부터 보호: [바이러스 솔루션 및 보안 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ko)

지역별 지원 정보: [국가별 지원](http://support.microsoft.com/common/international.aspx?ln=ko)

### 고지 사항

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성과 특정 목적에 대한 적합성의 보증을 포함하여 명시적이거나 묵시적인 모든 보증을 부인합니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 수정 내역

-   V1.0(2014년 12월 10일): 공지 요약이 게시되었습니다.

*2014-12-04 13:31Z-08:00에 페이지가 생성되었습니다.*
