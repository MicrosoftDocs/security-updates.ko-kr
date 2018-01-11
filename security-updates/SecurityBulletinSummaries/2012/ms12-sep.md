---
TOCTitle: 'MS12-SEP'
Title: 2012 년 9 월 Microsoft 보안 공지 요약
ms:assetid: 'ms12-sep'
ms:contentKeyID: 61230756
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms12-sep(v=Security.10)'
---


2012 년 9 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2012년 9월 11일 화요일 | 업데이트된 날짜: 2012년 9월 22일 토요일

**버전:** 2.0

이 공지 요약 목록에는 2012년 9월에 발표된 보안 공지가 포함되어 있습니다.

2012년 9월 보안 공지 발표와 함께 이 공지 요약이 2012년 9월 19일 수요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2012년 9월 12일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [9월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522555&culture=en-us). 이 날짜 이후 이 웹캐스트는 [주문형](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522555&culture=en-us)으로 제공됩니다.

Microsoft는 2012년 9월 21일 오후 12:00(태평양 표준시, 미국 및 캐나다)에 부정기 보안 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [9월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032529852&culture=en-us). 이 날짜 이후 이 웹캐스트는 [주문형](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032529852&culture=en-us)으로 제공됩니다.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. 기타 정보 섹션을 참조하십시오.

### 공지 정보

요약
----

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 영향을 받는 소프트웨어 및 다운로드 위치를 참조하십시오.

 
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2744842) <br />
<br />
이 보안 업데이트는 Internet Explorer의 공개된 취약점 1건과 비공개로 보고된 취약점 4건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254184">MS12-061</a></td>
<td style="border:1px solid black;">Visual Studio Team Foundation Server의 취약점으로 인한 권한 상승 문제점(2719584) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Visual Studio Team Foundation Server의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 전자 메일 메시지의 특수하게 조작된 링크를 클릭하거나 이 취약점을 악용하는 데 사용된 웹 페이지로 이동할 경우 권한 상승이 허용될 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 이러한 작업을 수행하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft 개발자 도구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=261858">MS12-062</a></td>
<td style="border:1px solid black;">System Center Configuration Manager의 취약점 으로 인한 권한 상승 문제점(2741528) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft System Center Configuration Manager의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 URL을 통해 영향을 받는 웹 사이트를 방문할 경우 권한 상승이 허용될 수 있습니다. 공격자는 강제로 사용자가 이러한 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft Server 소프트웨어</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/security/cc998259.aspx)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >공지 번호</th>
<th style="border:1px solid black;" >취약점 제목</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >최신 소프트웨어 버전에 대한 악용 가능성 평가</th>
<th style="border:1px solid black;" >이전 소프트웨어 버전에 대한 악용 가능성 평가</th>
<th style="border:1px solid black;" >서비스 거부 악용 가능성 평가</th>
<th style="border:1px solid black;" >주요 정보</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254184">MS12-061</a></td>
<td style="border:1px solid black;">XSS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1892">CVE-2012-1892</a>(영문)</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=261858">MS12-062</a></td>
<td style="border:1px solid black;">변형 XSS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2536">CVE-2012-2536</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;">OnMove 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1529">CVE-2012-1529</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;">이벤트 수신기 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2546">CVE-2012-2546</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;">레이아웃 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2548">CVE-2012-2548</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;">cloneNode 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2557">CVE-2012-2557</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;">execCommand 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4969">CVE-2012-4969</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
Microsoft는 이 취약점을 악용하려는 제한된 공격에 대한 보고를 받았습니다.</td>
</tr>
</tbody>
</table>
 

<sup>[1]</sup>Internet Explorer 10는 이 취약점의 영향을 받지 않습니다.

영향을 받는 소프트웨어 및 다운로드 위치
---------------------------------------

다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.

이 표를 어떻게 사용합니까?

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.

참고 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

#### Windows 운영 체제 및 구성 요소

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-063](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=967c9ef3-db48-4c2f-9a67-87851fd54962&displaylang=ko)  
(KB2744842)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6ba78d4c-3657-4963-b2da-7a3763c6b5c9&displaylang=ko)  
(KB2744842)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ac71ffe3-f077-4753-a238-47a2e9623363&displaylang=ko)  
(KB2744842)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=020b36c6-7050-4458-8762-bae35eb713cd)  
(KB2744842)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1e2e412a-be97-407e-9f02-fc074db3bb07)  
(KB2744842)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c727d956-be3e-4cd2-913c-f26cb6c33227)  
(KB2744842)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-063](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7aaaa15b-87d8-4afc-b183-8ce5becda026&displaylang=ko)  
(KB2744842)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=aef34ce4-a6ce-4f5e-9892-0a7fbd90c3b4&displaylang=ko)  
(KB2744842)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d63e25ad-ab8c-425f-89cd-29cd2b7b69d6&displaylang=ko)  
(KB2744842)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=366feacb-16ad-455c-b2ad-5038f998c432&displaylang=ko)  
(KB2744842)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=baa47c53-2724-43ef-8590-d3733b47e75b&displaylang=ko)  
(KB2744842)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=84144e56-f653-4c92-bf49-d44d9ba10489&displaylang=ko)  
(KB2744842)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=c28d6dc3-c2f0-4505-a545-85b7a0e3e2dc)  
(KB2744842)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=86c28695-86a5-4c17-82d6-7f98b3162aa6)  
(KB2744842)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-063](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=053546fc-ed41-43c2-b4f2-b76334314f5c&displaylang=ko)  
(KB2744842)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0a5a446d-0a48-4eec-b424-87339b34a3be&displaylang=ko)  
(KB2744842)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=daba1ef1-62db-43db-9d5b-495aa2d3550f&displaylang=ko)  
(KB2744842)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=cbe5681b-c28e-4a6a-9b97-0bfe44acf077&displaylang=ko)  
(KB2744842)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5642136e-68f6-42e8-b48e-1549733c6e7d&displaylang=ko)  
(KB2744842)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=aae496ef-fca2-4632-9a8f-2108722d2b28&displaylang=ko)  
(KB2744842)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-063](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=df861b42-bcf2-4f7a-9019-f49e6725f5dc&displaylang=ko)  
(KB2744842)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1d4f0f25-9539-4c38-babb-4af7f0f4c6cf&displaylang=ko)  
(KB2744842)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=0b2965d7-e0b2-4035-a9e4-f6badb389098&displaylang=ko)  
(KB2744842)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fa9878c0-b7e5-43ac-b1eb-679e62cf62fc&displaylang=ko)  
(KB2744842)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=10bab7d4-0dd8-4fa7-b26c-715a68553707&displaylang=ko)  
(KB2744842)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=612a94ef-0950-41e8-9875-a8f0e71eba6f&displaylang=ko)  
(KB2744842)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ded887a4-a06d-4447-b19d-19d0f4928523)  
(KB2744842)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-063](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=93591461-39ff-4cbd-8df3-88cb80ed6255&displaylang=ko)  
(KB2744842)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b303f86a-df17-4961-b677-0c38bd6a86d3&displaylang=ko)  
(KB2744842)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=93591461-39ff-4cbd-8df3-88cb80ed6255&displaylang=ko)  
(KB2744842)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b303f86a-df17-4961-b677-0c38bd6a86d3&displaylang=ko)  
(KB2744842)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e2083388-19a9-4754-9449-1dad2a7f7543&displaylang=ko)  
(KB2744842)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=01045ee2-c7c4-4078-969f-905fd7e8774f&displaylang=ko)  
(KB2744842)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e2083388-19a9-4754-9449-1dad2a7f7543&displaylang=ko)  
(KB2744842)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=01045ee2-c7c4-4078-969f-905fd7e8774f&displaylang=ko)  
(KB2744842)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-063](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d46ec8ea-b8c8-42d9-a201-f36eb97b91b8&displaylang=ko)  
(KB2744842)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c44a0253-fefc-4ce6-9cfd-396fdea71f8d&displaylang=ko)  
(KB2744842)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d46ec8ea-b8c8-42d9-a201-f36eb97b91b8&displaylang=ko)  
(KB2744842)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c44a0253-fefc-4ce6-9cfd-396fdea71f8d&displaylang=ko)  
(KB2744842)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c132173b-f869-47ec-bb70-6307081473fe)  
(KB2744842)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c132173b-f869-47ec-bb70-6307081473fe)  
(KB2744842)  
(보통)
</td>
</tr>
</table>
 

#### Microsoft 개발자 도구 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Visual Studio Team Foundation Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-061](http://go.microsoft.com/fwlink/?linkid=254184)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio Team Foundation Server 2010 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=721c4a38-b255-4792-83a5-7526a680a79a&displaylang=ko)<sup>[1]</sup>   
(KB2719584)   
(중요)
</td>
</tr>
</table>
 
MS12-061 참고 사항

<sup>[1]</sup>이 업데이트는 누적 업데이트로서 지정된 소프트웨어에 대한 이전의 누적 업데이트를 대체합니다.

#### Microsoft Server 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft System Center Configuration Manager
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-062](http://go.microsoft.com/fwlink/?linkid=261858)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Systems Management Server 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Systems Management Server 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=f3a3d8e1-d551-43b4-9d54-9536f30c074d&displaylang=ko)<sup>[1]</sup>   
(KB2733631)   
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft System Center Configuration Manager 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft System Center Configuration Manager 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=89890c0e-118b-49ea-9fd1-6d23c674f9e8&displaylang=ko)<sup>[1]</sup>   
(KB2721642)   
(중요)
</td>
</tr>
</table>
 
MS12-062 참고 사항

<sup>[1]</sup>이 업데이트는 Microsoft 다운로드 센터에서만 다운로드할 수 있습니다

검색, 배포 도구 및 지침
-----------------------

보안 센터

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security TechCenter](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [Microsoft 안전 및 보안 센터](http://go.microsoft.com/fwlink/?linkid=85102)를 방문하거나 "보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)을 참조하십시오.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS12-001")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

검색 및 배포 지침

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

Microsoft Baseline Security Analyzer

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 참조하십시오.

Windows Server Update Services

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://technet.microsoft.com/wsus/default)(영문)를 참조하십시오.

System Center Configuration Manager

System Center Configuration Manager 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. System Center Configuration Manager를 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

System Center Configuration Manager의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. System Center Configuration Manager의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. System Center Configuration Manager에 대한 자세한 내용은 [System Center 기술 리소스](http://technet.microsoft.com/systemcenter/bb980621)를 참조하십시오.

Systems Management Server 2003

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

참고 System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](http://go.microsoft.com/fwlink/?linkid=21742) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager를 지금 사용할 수 있습니다(이전 섹션의 System Center Configuration Manager 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)(영문)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) (영문)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet.microsoft.com/library/cc749197) (영문)구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199)
-   : 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/wsus/bb456965)
-   . Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

업데이트 관리 전략

[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

기타 보안 관련 업데이트 받기

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS12-061에서 설명한 문제점을 보고해주신 INR Labs([Network Intelligence India](http://niiconsulting.com/)(영문))의 Sunil Yadav
-   MS12-062에서 설명한 문제점을 보고해주신 [Stratsec](http://www.stratsec.net)(영문)의 Andy Yang
-   MS12-063에서 설명한 문제점을 [VeriSign iDefense Labs](http://labs.idefense.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   MS12-063에서 설명한 문제점을 보고해 주신 [Rosario Valotta](https://sites.google.com/site/tentacoloviola)(영문)
-   MS12-063에서 설명한 문제점을 [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하며 보고해 주신 [Harmony Security](http://www.harmonysecurity.com/)(영문)의 Stephen Fewer
-   MS12-063에서 설명한 문제점을 [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   MS12-063에서 설명한 문제점을 [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   MS12-063에서 설명한 문제점을 해결하기 위해 협력해 주신 [Mitre](http://www.mitre.org/)(영문)

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617.aspx)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2012년 9월 11일): 공지 요약이 게시되었습니다.
-   V2.0(2012년 9월 22일): Microsoft 보안 공지 MS12-063, Internet Explorer 누적 보안 업데이트(2744842)가 추가되었습니다. 또한 이 부정기 보안 업데이트에 대한 공지 웹캐스트 링크가 추가되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
