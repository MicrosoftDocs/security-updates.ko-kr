---
TOCTitle: 'MS12-DEC'
Title: 2012년 12월 Microsoft 보안 공지 요약
ms:assetid: 'ms12-dec'
ms:contentKeyID: 61230747
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms12-dec(v=Security.10)'
---


2012년 12월 Microsoft 보안 공지 요약
====================================

게시된 날짜: 2012년 12월 11일 화요일 | 업데이트된 날짜: 2012년 12월 20일 목요일

**버전:** 2.0

이 공지 요약 목록에는 2012년 12월 발표된 보안 공지가 포함되어 있습니다.

2012년 12월 보안 공지 발표와 함께 이 공지 요약이 2012년 12월 6일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2012년 12월 12일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [12월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522564&culture=en-us). 이 날짜 이후 이 웹캐스트는 [주문형](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522564&culture=en-us)으로 제공됩니다.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

#### 요약

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(2761465)<br />
<br />
</strong>이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 3건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271624">MS12-078</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버의 취약점으로 인한 원격 코드 실행 문제점<br />
(2783534)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점의 더욱 위험한 점은 사용자가 특수하게 조작된 문서를 열거나 TrueType 또는 OpenType 글꼴 파일을 포함하는 악의적인 웹페이지를 방문할 경우 원격 코드 실행을 허용할 수 있다는 점입니다. 공격자는 사용자가 전자 메일 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271609">MS12-079</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word의 취약점으로 인한 원격 코드 실행 문제점(2780642)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 취약점으로 인해 사용자가 영향을 받는 버전의 Microsoft Office 소프트웨어를 사용하여 특수하게 조작된 RTF 파일을 열거나, 전자 메일 뷰어로 Word를 사용하면서 특수하게 조작된 RTF 전자 메일 메시지를 Outlook에서 미리 보거나 열 경우 원격 코드 실행이 발생할 수 있습니다. 이 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272389">MS12-080</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server의 취약점으로 인한 원격 코드 실행 문제점(2784126)<br />
<br />
</strong>이 보안 업데이트는 MMicrosoft Exchange Server의 공개된 취약점과 비공개적으로 보고된 취약점 1건을 해결합니다. 가장 심각한 취약점은 Microsoft Exchange Server WebReady 문서 보기에 있으며, 사용자가 OWA(Outlook Web App)를 사용하여 특수하게 조작된 파일을 미리보는 경우 Exchange 서버에 있는 코드 변환 서비스의 보안 컨텍스트에서 원격 코드를 실행하도록 허용할 수 있습니다. WebReady 문서 보기에 사용되는 Exchange에 있는 코드 변환 서비스는 LocalService 계정에서 실행되고 있습니다. LocalService 계정에는 로컬 컴퓨터의 최소 권한이 있으며 네트워크에서 익명 자격 증명을 제시합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Server 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=266541">MS12-081</a></td>
<td style="border:1px solid black;"><strong>Windows 파일 처리 구성 요소의 취약점으로 인한 원격 코드 실행 문제점(2758857)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 이름의 파일 또는 하위 폴더가 있는 폴더를 찾아볼 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271751">MS12-082</a></td>
<td style="border:1px solid black;"><strong>DirectPlay의 취약점으로 인한 원격 코드 실행 문제점(2770660)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 공격자가 사용자를 특수하게 조작된 콘텐츠를 내장한 Office 문서를 보도록 유도할 경우 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263950">MS12-083</a></td>
<td style="border:1px solid black;"><strong>IP-HTTPS 구성 요소의 취약점으로 인한 보안 기능 우회(2765809)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 공격자가 해지된 인증서를 Microsoft DirectAccess 배포에서 일반적으로 사용되는 IP-HTTPS 서버에 제출할 경우 취약점으로 인해 보안 기능 우회가 허용될 수 있습니다. 취약점을 악용하려면 공격자는 IP-HTTPS 서버 인증을 위해 도메인에서 발급된 인증서를 사용해야 합니다. 조직 내부의 시스템에 로그온하려면 시스템 또는 도메인 자격 증명이 필요합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
보안 기능 우회</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/security/cc998259)를 참조하십시오.
  
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;">InjectHTMLStream 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4781">CVE-2012-4781</a></td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;">CMarkup 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4782">CVE-2012-4782</a></td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;">잘못된 Ref 셈 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4787">CVE-2012-4787</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271624">MS12-078</a></td>
<td style="border:1px solid black;">OpenType 글꼴 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2556">CVE-2012-2556</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271624">MS12-078</a></td>
<td style="border:1px solid black;">TrueType 글꼴 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4786">CVE-2012-4786</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271609">MS12-079</a></td>
<td style="border:1px solid black;">Word RTF 'listoverridecount' 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2539">CVE-2012-2539</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272389">MS12-080</a></td>
<td style="border:1px solid black;">Oracle Outside In에 포함되어 있는 악용 가능한 여러 취약점</td>
<td style="border:1px solid black;">다수*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">*여러 취약점에 대한 자세한 내용은 MS12-080 공지를 참조하십시오.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272389">MS12-080</a></td>
<td style="border:1px solid black;">RSS 피드로 발생하는 Exchange DoS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4791">CVE-2012-4791</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=266541">MS12-081</a></td>
<td style="border:1px solid black;">Windows 파일 이름 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4774">CVE-2012-4774</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271751">MS12-082</a></td>
<td style="border:1px solid black;">DirectPlay 힙 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1537">CVE-2012-1537</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263950">MS12-083</a></td>
<td style="border:1px solid black;">해지된 인증서 우회 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2549">CVE-2012-2549</a></td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 보안 기능 우회 취약점입니다.</td>
</tr>
</tbody>
</table>
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=e39c8368-9cd3-4f29-8c9c-aa784122bef0)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d1881d12-2a40-4cb1-9428-31d6633746be)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=8359ec5a-07f8-4b29-8576-7356a84daf82)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=e4a2cd3b-598b-4cf4-8b42-2582d369bab5)  
(KB2753842)  
(긴급)  
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=7a7a68cf-42a2-49a4-bf0c-88dd582ddd0d)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=f189ee1c-1457-4d50-87cd-5be268b04f16)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=98ceaf36-ef87-4ea3-8b73-bb0a1a624fe0)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=ed2d3c6e-b90a-49a7-867e-9549b14eb0bf)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=18e165e9-346b-4337-81d2-77f3bf5f5f3f)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5d0a76e1-80d3-4f81-be5e-8d235babaa61)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=27e6c4df-7988-4d03-b2f6-bc9ce37483f9)  
(KB2753842)  
(긴급)  
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d2a59846-74fd-4166-9d65-1cc98cb7d934)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2bf25fc8-6458-4807-bb7d-1c07ec424638)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=421b0c02-e572-4362-b690-73ad63b028de)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=478f4789-0f5e-4bfb-9536-94314f84f12c)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5ca71c15-0add-45cd-991f-e5810791c434)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0157c9ee-58c5-419f-ba97-6c4334318b75)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=efe4755b-3bc4-4a65-9826-7ecaa3856093)  
(KB2753842)  
(긴급)  
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=74847cb5-a092-4818-bf7a-912ccaed7a12)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2242a927-cafb-41eb-8bf2-01302b5a5d94)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1b487137-8b5a-4f22-8395-f3fc4f25f00b)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=66b552b4-8b55-45de-ba0a-940dc24e6f56)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e9fb2cf9-3acb-48ac-80ac-f61f1a47a188)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=23c4962c-8526-4e18-9b8d-50f3c3a2bf6d)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=019d80e2-7622-4951-9437-5d613c5fb2fb)  
(KB2753842)  
(긴급)  
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b0c9df15-857f-490a-96df-3883a11c3234)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4d97b0a5-1ba7-44f0-88b6-1e0a8039b9b1)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=39d79b5b-f11c-465a-8ddd-aecb571c711f)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=890d1149-7bb3-4d6e-a4ce-f9116c658eda)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d8025298-be72-4ef2-8914-7698494f4368)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=419b9fd2-dbe6-45b5-b025-9712bb9319d6)  
(KB2753842)  
(긴급)  
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=323c122b-be77-45e9-805d-ab14f5cc76f9)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=e74713fd-e1bc-4a63-9a00-2f33000eac27)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=312975f6-2269-4c6f-996b-8fb04e8c08d6)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3701a40d-e423-4204-9527-26e527f47fb0)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=394963e9-edd6-4b5d-b9d4-e6fb86d7eb54)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=bd3a6f9b-7bfd-40e1-9393-a125030f2964)  
(KB2761465)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0cadef72-625f-4c91-8289-c10a96bb3423)  
(KB2753842)  
(긴급)  
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f2854a4e-2597-49ab-8a85-715ea9194208)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ebd25f89-e6d9-4c48-a673-f665d189905c)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=cd60c749-bb24-4147-9699-a1a75939a28f)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2856c7b8-d5c0-444d-8273-5bd116f8898b)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7a0c6dbd-e537-43d7-97cc-0d3df354e46a)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=482fadb3-0974-40f3-af35-f29210913c81)  
(KB2761465)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dd5eb06a-c805-4518-a784-5e29d7636037)  
(KB2753842)  
(긴급)  
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b6baf170-65b0-4068-b2a0-196c3e4b3aed)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e7629d85-5c18-4979-a8e2-054a6175cf21)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[](https://www.microsoft.com/download/details.aspx?familyid=?...?)[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d6f2c1d9-b775-48a0-b154-cf61b1e2674c)</a>
(KB2770660)  
(중요)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a4824a10-4011-4ce5-9454-693d42acddf3)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e3d584f5-fc25-4e66-a911-4595018c51e3)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=ffff647e-8d05-4c77-aea6-542ab8d76c57)  
(KB2761465)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9a51b84d-2200-42c5-a6ab-4d570fa20609)  
(KB2753842)  
(긴급)  
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=bdad28e8-987e-492e-a405-b3be552d2d7a)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ced1ffc6-7d30-480a-a3e0-8071981d1863)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=20ffdbfd-c786-41ca-9367-d7499108d711)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=750797e5-1da7-49a9-8c27-ff35fe7516a1)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ca4a5972-faec-412a-b51a-130253cebcab)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=8f22603d-3a0d-49da-9691-671c0c950867)  
(KB2761465)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9c60014b-133e-455e-b03f-d73f6e36d3de)  
(KB2753842)  
(긴급)  
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6298d55c-2ed2-4a90-9dfe-43bae0932e27)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b9a687e6-9ab7-4dae-9771-5f7bb3123e06)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=cfeb7a06-5812-4a49-b69b-88be06d63d71)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4d49cd73-feea-44c7-86f2-048dd69233a4)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=68e6d5c4-cb20-4291-8864-4270db36ead0)  
(KB2753842)  
(긴급)  
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2293a5fb-4a1c-41d9-ab67-b89e00078029)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=202b3919-0075-4c54-a189-123de852fc7b)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0345e31f-6d0d-4d46-8f02-8b2ffbf795f0)  
(KB2770660)  
(중요)
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
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5b461a22-6ca4-4ab9-8874-84d7928cc668)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=38b15264-1a1d-41a6-8803-2d3facdb2dc3)  
(KB2761465)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d1894fc3-603a-4a94-9e27-e1c564688294)  
(KB2753842)  
(긴급)  
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=48f7d41e-f1c4-428d-9889-543fcb1e272b)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=cdaae723-6287-4607-9dc2-c23e1fb31f80)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=27e57b08-8616-4eb3-9724-3647e6841296)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5b461a22-6ca4-4ab9-8874-84d7928cc668)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=38b15264-1a1d-41a6-8803-2d3facdb2dc3)  
(KB2761465)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=d1894fc3-603a-4a94-9e27-e1c564688294)  
(KB2753842)  
(긴급)  
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=48f7d41e-f1c4-428d-9889-543fcb1e272b)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=cdaae723-6287-4607-9dc2-c23e1fb31f80)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=27e57b08-8616-4eb3-9724-3647e6841296)  
(KB2770660)  
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
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d19dfe38-77ef-4479-b3d9-8f6385ddee80)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7accb5a9-98a1-4358-90ba-534d197885c1)  
(KB2761465)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d7b5c43d-b659-4843-8944-62bf52738bbc)  
(KB2753842)  
(긴급)  
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=ae9f0c19-169b-4bcd-92f7-654b84bab01f)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=4a389411-bf52-4cb2-9051-ba7344b58474)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=5f7c21b9-7dd3-4b9f-84af-1450af6c7ee3)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d19dfe38-77ef-4479-b3d9-8f6385ddee80)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7accb5a9-98a1-4358-90ba-534d197885c1)  
(KB2761465)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=d7b5c43d-b659-4843-8944-62bf52738bbc)  
(KB2753842)  
(긴급)  
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ae9f0c19-169b-4bcd-92f7-654b84bab01f)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=4a389411-bf52-4cb2-9051-ba7344b58474)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5f7c21b9-7dd3-4b9f-84af-1450af6c7ee3)  
(KB2770660)  
(중요)
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
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체** **심각도**
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=8968122d-d3b9-404e-ba23-846be9041e3f)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=14bd26c2-b006-4465-88cc-4ecdc5de540f)  
(KB2761465)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099)  
(KB2753842)  
(긴급)  
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=efe0d293-9cfb-46cb-b52e-0b90bde3f8e9)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f)  
(KB2765809)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=8968122d-d3b9-404e-ba23-846be9041e3f)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=14bd26c2-b006-4465-88cc-4ecdc5de540f)  
(KB2761465)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099)  
(KB2753842)  
(긴급)  
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=efe0d293-9cfb-46cb-b52e-0b90bde3f8e9)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f)  
(KB2765809)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9191365d-5541-4277-9079-f4e72e98fd19)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=f26098f5-6b6c-48f9-8737-345ad4956cb0)  
(KB2753842)  
(긴급)  
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=51b562f4-8b1a-416e-88dc-93b561ad850a)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=2a0a6f92-c4bf-45a3-b103-b7937121b675)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=33096b07-bfa3-4879-b214-dfa81cd73cae)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=88a3452c-b416-41cf-867a-fdc64666c0a6)  
(KB2765809)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9191365d-5541-4277-9079-f4e72e98fd19)  
(KB2761465)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=f26098f5-6b6c-48f9-8737-345ad4956cb0)  
(KB2753842)  
(긴급)  
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=51b562f4-8b1a-416e-88dc-93b561ad850a)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=2a0a6f92-c4bf-45a3-b103-b7937121b675)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=33096b07-bfa3-4879-b214-dfa81cd73cae)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=88a3452c-b416-41cf-867a-fdc64666c0a6)  
(KB2765809)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=28fb32a1-12fd-420d-94ff-570742a02b8d)  
(KB2761465)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 8(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=385265c4-f920-4ac1-b474-a166b3d3ab42)  
(KB2753842)  
(긴급)  
[Windows 8(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=75969782-d3f8-40dd-8922-4408eefad6f3)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 8(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=15f86dbf-d8db-445c-8996-cc789c8a894d)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=ad0ee30f-b550-434b-9fe0-ff418e052d3f)  
(KB2761465)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 8(64비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=543af274-d6cf-4f85-a120-b7f3936d7fc2)  
(KB2753842)  
(긴급)  
[Windows 8(64비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=2332059d-30d3-4b44-b172-f054e26d8971)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 8(64비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=dfdda0c8-a440-49ab-832b-cdd343c57770)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=96fda694-876a-45e9-911a-b68b3bd03290)  
(KB2761465)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=15298129-8f1c-47d7-a7e9-efb40823d91a)  
(KB2753842)  
(긴급)  
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=f8e84ff9-a9c0-4363-b5a6-1b90254edd73)  
(KB2779030)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=59be5ec7-df5a-4f01-8e27-ad76f1fe76bb)  
(KB2770660)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=d6654bf1-1ab9-4691-8729-793eb6d0e563)  
(KB2765809)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
**없음**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[2]</sup>
(KB2761465)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2753842)  
(긴급)  
Windows RT<sup>[1]</sup>
(KB2779030)  
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
Server Core 설치 옵션
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9a51b84d-2200-42c5-a6ab-4d570fa20609)(Server Core 설치)  
(KB2753842)  
(중요)  
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=bdad28e8-987e-492e-a405-b3be552d2d7a)(Server Core 설치)  
(KB2779030)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ced1ffc6-7d30-480a-a3e0-8071981d1863)(Server Core 설치)  
(KB2758857)  
(긴급)
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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9c60014b-133e-455e-b03f-d73f6e36d3de)(Server Core 설치)  
(KB2753842)  
(중요)  
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6298d55c-2ed2-4a90-9dfe-43bae0932e27)(Server Core 설치)  
(KB2779030)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b9a687e6-9ab7-4dae-9771-5f7bb3123e06)(Server Core 설치)  
(KB2758857)  
(긴급)
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
Windows Server 2008 R2(x64 기반 시스템용)(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099)(Server Core 설치)  
(KB2753842)  
(중요)  
[Windows Server 2008(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c)(Server Core 설치)  
(KB2779030)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817)(Server Core 설치)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f)(Server Core 설치)  
(KB2765809)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099)(Server Core 설치)  
(KB2753842)  
(중요)  
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c)(Server Core 설치)  
(KB2779030)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817)(Server Core 설치)  
(KB2758857)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f)(Server Core 설치)  
(KB2765809)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=15298129-8f1c-47d7-a7e9-efb40823d91a)(Server Core 설치)  
(KB2753842)  
(중요)  
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=f8e84ff9-a9c0-4363-b5a6-1b90254edd73)(Server Core 설치)  
(KB2779030)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=d6654bf1-1ab9-4691-8729-793eb6d0e563)(Server Core 설치)  
(KB2765809)  
(중요)
</td>
</tr>
</table>
 
**MS12-077 참고 사항**

<sup>[1]</sup>이 공지에서 설명한 취약점에 대해 알려진 공격 경로가 기본 구성으로 차단되므로 지정된 소프트웨어에 대한 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 심층적인 보안 대응책으로써 이 소프트웨어를 사용하는 고객은 이 보안 업데이트를 적용하는 것이 좋습니다.

<sup>[2]</sup>이 업데이트는 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해서만 제공됩니다.

**MS12-078** **참고 사항**

<sup>[1]</sup>이 업데이트는 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해서만 제공됩니다.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Office 제품군 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=6947d500-f197-4001-bb39-1c4221af1b36)  
(KB2760497)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=52aad8a5-14d9-4c02-828a-5c1164a01f27)<sup>[1]</sup>
(KB2760421)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=52aad8a5-14d9-4c02-828a-5c1164a01f27)<sup>[1]</sup>
(KB2760421)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 서비스 팩 1(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=68c69b37-c544-4f24-8589-4212b868dd69)  
(KB2760410)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 서비스 팩 1(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=9d776c2b-1a9a-4ccb-9e76-dd2cb0f9a80d)  
(KB2760410)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
기타 Microsoft Office 소프트웨어
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer](https://www.microsoft.com/download/details.aspx?familyid=4ccaabd9-5128-4505-ba2f-20bcf02b97ec)  
(KB2760498)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 호환 기능 팩 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c82de87d-3457-423e-9bfc-ec3f950049e7)  
(KB2760416)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 호환 기능 팩 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=c82de87d-3457-423e-9bfc-ec3f950049e7)  
(KB2760416)  
(중요)
</td>
</tr>
</table>
 
**MS12-079참고 사항**

<sup>[1]</sup>Microsoft Office Word 2007을 사용하는 고객의 경우 이 공지에서 설명한 취약점으로부터 보호하기 위해 보안 업데이트 패키지 KB2760421 이외에도 Microsoft Office 호환 기능 팩용 보안 업데이트(KB2760416)를 설치해야 합니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Server 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=605fc9bc-a05c-4466-ace6-9c2af087d797)  
(KB2746157)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=e43b1164-d768-4152-b9a3-d1491e2f3cba)  
(KB2787763)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2a49ed58-9dab-4d48-ae8a-c7139e3b34ba)  
(KB2785908)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft SharePoint Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Word Automation Services](https://www.microsoft.com/download/details.aspx?familyid=62007dcd-80db-42e4-8478-9e81f89cab98)  
(KB2760405)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=c98d8ef3-e9a8-4e7c-9e0a-02e192bab39c)  
(KB2687412)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**MS12-079** **참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security TechCenter](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [Microsoft 안전 및 보안 센터](http://go.microsoft.com/fwlink/?linkid=85102)를 방문하거나 "보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)을 참조하십시오.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS12-001")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 참조하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://technet.microsoft.com/wsus/default)를 참조하십시오.

**SystemCenter Configuration Manager**

System Center Configuration Manager 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. System Center Configuration Manager를 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

System Center Configuration Manager의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. System Center Configuration Manager의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. System Center Configuration Manager에 대한 자세한 내용은 [System Center 기술 리소스](http://technet.microsoft.com/systemcenter/bb980621)를 참조하십시오.

**Systems Management Server 2003**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

**참고** System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](http://go.microsoft.com/fwlink/?linkid=21742) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager를 지금 사용할 수 있습니다(이전 섹션의 **System** Center Configuration Manager 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936)를 방문하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet.microsoft.com/library/cc749197) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/wsus/bb456965). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS12-077에서 설명한 두 가지 문제점을 보고해 주신 [Rosario Valotta](https://sites.google.com/site/tentacoloviola)
-   MS12-077에서 설명한 문제점을 보고해 주신 [Google Inc](http://www.google.com)의 Fermin J. Serna
-   MS12-078에서 설명한 문제점을 Chromium Security Rewards Program과 협력하여 보고해 주신 [Documill](http://www.documill.com)의 Eetu Luodemaa와 Joni Vähämäki
-   MS12-079에서 설명한 문제점을 Beyond Security의 [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) 프로그램과 협력하여 보고해 주신 익명의 기고자
-   MS12-081에서 설명한 문제점을 보고해 주신 [IOActive](http://ioactive.co.uk/)의 Lucas Apa
-   MS12-082에서 설명한 문제점을 [VeriSign iDefense Labs](http://labs.idefense.com/)와 협력하여 보고해 주신 [Aniway](mailto:aniway.anyway@gmail.com)

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617.aspx)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2012년 12월 11일): 공지 요약이 게시되었습니다.
-   V1.1(2012년 12월 12일): MS12-082에 대한 "다시 시작 요구 사항" 항목을 수정했습니다. 이 변경 사항은 정보에만 해당됩니다. 보안 업데이트 파일에 대한 변경 사항은 없습니다.
-   V2.0(2012년 12월 20일): MS12-078의 경우 기존의 업데이트가 설치된 이후 OpenType 글꼴이 올바르게 렌더링되지 않는 문제를 해결하기 위해 업데이트(KB2753842)가 다시 릴리스되었습니다. 기존의 KB2753842 업데이트를 성공적으로 설치한 고객은 다시 릴리스된 업데이트를 설치할 필요가 없습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
