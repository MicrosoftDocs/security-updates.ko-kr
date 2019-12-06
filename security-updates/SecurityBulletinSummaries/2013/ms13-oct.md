---
TOCTitle: 'MS13-OCT'
Title: 2013 년 10 월 Microsoft 보안 공지 요약
ms:assetid: 'ms13-oct'
ms:contentKeyID: 61230767
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms13-oct(v=Security.10)'
---

2013 년 10 월 Microsoft 보안 공지 요약
======================================

게시된 날짜: 2013년 10월 9일 수요일 | 업데이트된 날짜: 2013년 11월 7일 목요일

**버전:** 1.2

이 공지 요약 목록에는 2013년 10월에 발표된 보안 공지가 포함되어 있습니다.

2013년 10월 보안 공지 발표와 함께 이 공지 요약이 2013년 10월 3일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2013년 10월 9일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [10월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557381&culture=en-us).

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. 기타 정보 섹션을 참조하십시오.

### 공지 정보

#### 요약

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 영향을 받는 소프트웨어를 참조하십시오.

<p> </p>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2879017)<br />
<br />
이 보안 업데이트는 Internet Explorer의 공개된 취약점 1건과 비공개로 보고된 취약점 8건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 가장 위험한 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Windows 커널 모드 드라이버의 취약점으로 인한 원격 코드 실행 문제점(2870008)<br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 7건을 해결합니다. 이 중 가장 심각한 취약점으로 인해 사용자가 OpenType 또는 TrueType 글꼴 파일이 포함된 공유 콘텐츠를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템에 대해 완벽히 제어할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">.NET Framework의 취약점으로 인한 원격 코드 실행 문제점(2878890)<br />
<br />
이 보안 업데이트는 Microsoft .NET Framework에 대해 비공개적으로 보고된 취약점 2건과 공개된 취약점 1건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 XBAP 응용 프로그램을 인스턴스화할 수 있는 브라우저를 통해 특수하게 조작된 OpenType 글꼴(OTF)이 포함된 웹 사이트를 방문하는 경우 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314045">MS13-083</a></td>
<td style="border:1px solid black;">Windows 공용 컨트롤 라이브러리의 취약점으로 인한 원격 코드 실행 문제점(2864058)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 영향을 받는 시스템에서 실행되는 ASP.NET 웹 응용 프로그램으로 특수하게 조작된 웹 요청을 보내는 경우 원격 코드 실행이 허용될 수 있습니다. 공격자는 인증 없이 이 취약점을 악용하여 임의 코드를 실행할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">Microsoft SharePoint Server의 취약점으로 인한 원격 코드 실행 문제점(2885089)<br />
<br />
이 보안 업데이트는 Microsoft Office 서버 소프트웨어에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 영향을 받는 버전의 Microsoft SharePoint Server, Microsoft Office Services 또는 Web Apps에서 특수하게 조작된 Office 파일을 여는 경우 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server 소프트웨어</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Microsoft Excel의 취약점으로 인한 원격 코드 실행 문제점(2885080)<br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 취약점으로 인해 사용자가 영향을 받는 Microsoft Excel 버전 또는 영향을 받는 기타 Microsoft Office 소프트웨어에서 특수하게 조작된 Office 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">Microsoft Word의 취약점으로 인한 원격 코드 실행 문제점(2885084)<br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 취약점으로 인해 영향을 받는 Microsoft Word 또는 영향을 받는 기타 Microsoft Office 소프트웨어에서 특수하게 조작된 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324590">MS13-087</a></td>
<td style="border:1px solid black;">Silverlight의 취약점으로 인한 정보 유출 문제점(2890788)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Silverlight의 취약점을 해결합니다. 공격자가 취약점을 악용할 수 있는 특수하게 조작된 Silverlight 응용 프로그램을 포함한 웹 사이트를 호스팅하고 사용자가 웹 사이트를 보도록 유도하는 경우 이 취약점으로 인해 정보가 유출될 수 있습니다. 공격자는 사용자가 제공한 콘텐츠가 광고를 허용하거나 호스팅하는 웹 사이트와 공격에 노출된 웹 사이트를 이용할 수도 있습니다. 이러한 웹 사이트에는 이 취약점을 악용할 수 있도록 특수하게 조작된 콘텐츠가 포함될 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다. 배너 광고에서 특수하게 조작된 웹 콘텐츠를 표시하거나 웹 콘텐츠를 전달하는 다른 방법을 사용하여 영향을 받는 시스템에 대한 공격을 시도할 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------

다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](https://technet.microsoft.com/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.

<p> </p>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3872">CVE-2013-3872</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3873">CVE-2013-3873</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3874">CVE-2013-3874</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3875">CVE-2013-3875</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3882">CVE-2013-3882</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3885">CVE-2013-3885</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3886">CVE-2013-3886</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3893">CVE-2013-3893</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
Microsoft는 Internet Explorer 8 및 Internet Explorer 9에서 이 취약점을 악용하려는 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3897">CVE-2013-3897</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">Microsoft는 Internet Explorer 8에서 이 취약점을 악용하려는 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">OpenType 글꼴 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 <a href="https://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a><a href="https://go.microsoft.com/fwlink/?linkid=293350"></a>에도 영향을 미칩니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Windows USB 설명자 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3200">CVE-2013-3200</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3879">CVE-2013-3879</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">앱 컨테이너 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3880">CVE-2013-3880</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">이 취약점은 권한 상승을 허용할 수 있는 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Win32k NULL 페이지 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3881">CVE-2013-3881</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">DirectX 그래픽 커널 하위 시스템 이중 페치 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3888">CVE-2013-3888</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">TrueType 글꼴 CMAP 테이블 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3894">CVE-2013-3894</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">OpenType 글꼴 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 <a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a><a href="https://go.microsoft.com/fwlink/?linkid=293350"></a>에도 영향을 미칩니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">엔터티 확장 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3860">CVE-2013-3860</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">JSON 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3861">CVE-2013-3861</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314045">MS13-083</a></td>
<td style="border:1px solid black;">Comctl32 정수 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3195">CVE-2013-3195</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">Microsoft Excel 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 <a href="https://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a><a href="https://go.microsoft.com/fwlink/?linkid=293350"></a>에도 영향을 미칩니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">매개 변수 주입 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3895">CVE-2013-3895</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Microsoft Excel 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 <a href="https://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a><a href="https://go.microsoft.com/fwlink/?linkid=293350"></a>에도 영향을 미칩니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Microsoft Excel 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3890">CVE-2013-3890</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3891">CVE-2013-3891</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3892">CVE-2013-3892</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324590">MS13-087</a></td>
<td style="border:1px solid black;">Silverlight 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3896">CVE-2013-3896</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 보안 기능 우회를 허용할 수 있는 정보 유출 취약점입니다.</td>
</tr>
</tbody>
</table>
  
영향을 받는 소프트웨어  
----------------------

다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.
  
참고 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="5">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(긴급)  
Internet Explorer 7   
(2879017)  
(긴급)  
Internet Explorer 8   
(2879017)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(2847311)  
(긴급)  
Windows XP 서비스 팩 3  
(2862330)  
(중요)  
Windows XP 서비스 팩 3  
(2862335)  
(중요)  
Windows XP 서비스 팩 3  
(2868038)  
(중요)  
Windows XP 서비스 팩 3  
(2883150)  
(긴급)  
Windows XP 서비스 팩 3  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2863239)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2861189)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2861697)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4  
(2861188)  
(긴급)
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
Internet Explorer 6   
(2879017)  
(긴급)  
Internet Explorer 7   
(2879017)  
(긴급)  
Internet Explorer 8   
(2879017)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2847311)  
(긴급)  
Windows XP Professional x64 Edition 서비스 팩 2  
(2862330)  
(중요)  
Windows XP Professional x64 Edition 서비스 팩 2  
(2862335)  
(중요)  
Windows XP Professional x64 Edition 서비스 팩 2  
(2868038)  
(중요)  
Windows XP Professional x64 Edition 서비스 팩 2  
(2883150)  
(긴급)  
Windows XP Professional x64 Edition 서비스 팩 2  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2863239)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2861189)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2861697)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4  
(2861188)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2864058)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(보통)  
Internet Explorer 7  
(2879017)  
(보통)  
Internet Explorer 8  
(2879017)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2847311)  
(긴급)  
Windows Server 2003 서비스 팩 2  
(2862330)  
(중요)  
Windows Server 2003 서비스 팩 2  
(2862335)  
(중요)  
Windows Server 2003 서비스 팩 2  
(2868038)  
(중요)  
Windows Server 2003 서비스 팩 2  
(2883150)  
(긴급)  
Windows Server 2003 서비스 팩 2  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2863239)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2861189)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2861697)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4  
(2861188)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2864058)  
(심각도 없음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(보통)  
Internet Explorer 7  
(2879017)  
(보통)  
Internet Explorer 8  
(2879017)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2847311)  
(긴급)  
Windows Server 2003 x64 Edition 서비스 팩 2  
(2862330)  
(중요)  
Windows Server 2003 x64 Edition 서비스 팩 2  
(2862335)  
(중요)  
Windows Server 2003 x64 Edition 서비스 팩 2  
(2868038)  
(중요)  
Windows Server 2003 x64 Edition 서비스 팩 2  
(2883150)  
(긴급)  
Windows Server 2003 x64 Edition 서비스 팩 2  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2863239)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2861189)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2861697)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4  
(2861188)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2864058)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(보통)  
Internet Explorer 7  
(2879017)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2847311)  
(긴급)  
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2862330)  
(중요)  
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2862335)  
(중요)  
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2868038)  
(중요)  
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2883150)  
(긴급)  
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2863239)  
(중요)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2861697)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2864058)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(긴급)  
Internet Explorer 8  
(2879017)  
(긴급)  
Internet Explorer 9   
(2879017)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2847311)  
(긴급)  
Windows Vista 서비스 팩 2  
(2855844)  
(긴급)  
Windows Vista 서비스 팩 2  
(2862330)  
(중요)  
Windows Vista 서비스 팩 2  
(2862335)  
(중요)  
Windows Vista 서비스 팩 2  
(2864202)  
(중요)  
Windows Vista 서비스 팩 2  
(2868038)  
(중요)  
Windows Vista 서비스 팩 2  
(2876284)  
(중요)  
Windows Vista 서비스 팩 2  
(2883150)  
(긴급)  
Windows Vista 서비스 팩 2  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2863253)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2861190)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2861697)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4  
(2861188)  
(긴급)  
Microsoft .NET Framework 4.5  
(2861193)  
(긴급)  
Microsoft .NET Framework 4.5  
(2861208)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2864058)  
(심각도 없음)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(긴급)  
Internet Explorer 8  
(2879017)  
(긴급)  
Internet Explorer 9   
(2879017)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2847311)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(2855844)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(2862330)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(2862335)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(2864202)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(2868038)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(2876284)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(2883150)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2863253)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2861190)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2861697)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4  
(2861188)  
(긴급)  
Microsoft .NET Framework 4.5  
(2861193)  
(긴급)  
Microsoft .NET Framework 4.5  
(2861208)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2864058)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(보통)  
Internet Explorer 8  
(2879017)  
(보통)  
Internet Explorer 9   
(2879017)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2847311)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2855844)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2862330)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2862335)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2864202)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2868038)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2876284)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2883150)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2863253)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2861190)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2861697)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4  
(2861188)  
(긴급)  
Microsoft .NET Framework 4.5  
(2861193)  
(긴급)  
Microsoft .NET Framework 4.5  
(2861208)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2864058)  
(심각도 없음)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(보통)  
Internet Explorer 8  
(2879017)  
(보통)  
Internet Explorer 9   
(2879017)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2847311)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2855844)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2862330)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2862335)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2864202)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2868038)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2876284)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2883150)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2863253)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2861190)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2861697)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4  
(2861188)  
(긴급)  
Microsoft .NET Framework 4.5  
(2861193)  
(긴급)  
Microsoft .NET Framework 4.5  
(2861208)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2864058)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2847311)  
(긴급)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2862330)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2862335)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2864202)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2868038)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2876284)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2883150)  
(긴급)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2863253)  
(중요)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2861697)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2864058)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(긴급)  
Internet Explorer 9   
(2879017)  
(긴급)  
Internet Explorer 10   
(2879017)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2847311)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(2855844)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(2862330)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(2862335)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(2864202)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(2868038)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(2876284)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(2883150)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4.5  
(2861208)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2864058)  
(심각도 없음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(긴급)  
Internet Explorer 9   
(2879017)  
(긴급)  
Internet Explorer 10   
(2879017)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2847311)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2855844)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2862330)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2862335)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2864202)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2868038)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2876284)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2883150)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4.5  
(2861208)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2864058)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(보통)  
Internet Explorer 9   
(2879017)  
(보통)  
Internet Explorer 10   
(2879017)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2847311)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2855844)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2862330)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2862335)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2864202)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2868038)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2876284)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2883150)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4.5  
(2861208)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2864058)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2847311)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2855844)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2862330)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2862335)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2864202)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2868038)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2876284)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2883150)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2864058)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2847311)  
(긴급)  
Windows 8(32비트 시스템용)  
(2862330)  
(중요)  
Windows 8(32비트 시스템용)  
(2862335)  
(중요)  
Windows 8(32비트 시스템용)  
(2863725)  
(중요)  
Windows 8(32비트 시스템용)  
(2864202)  
(중요)  
Windows 8(32비트 시스템용)  
(2868038)  
(중요)  
Windows 8(32비트 시스템용)  
(2883150)  
(긴급)  
Windows 8(32비트 시스템용)  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(긴급)  
Microsoft .NET Framework 3.5  
(2861704)  
(중요)  
Microsoft .NET Framework 3.5  
(2863243)  
(중요)  
Microsoft .NET Framework 4.5  
(2861702)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2864058)  
(심각도 없음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)  
(2847311)  
(긴급)  
Windows 8(64비트 시스템용)  
(2862330)  
(중요)  
Windows 8(64비트 시스템용)  
(2862335)  
(중요)  
Windows 8(64비트 시스템용)  
(2863725)  
(중요)  
Windows 8(64비트 시스템용)  
(2864202)  
(중요)  
Windows 8(64비트 시스템용)  
(2868038)  
(중요)  
Windows 8(64비트 시스템용)  
(2883150)  
(긴급)  
Windows 8(64비트 시스템용)  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(긴급)  
Microsoft .NET Framework 3.5  
(2861704)  
(중요)  
Microsoft .NET Framework 3.5  
(2863243)  
(중요)  
Microsoft .NET Framework 4.5  
(2861702)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)  
(2864058)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2847311)  
(긴급)  
Windows Server 2012  
(2862330)  
(중요)  
Windows Server 2012  
(2862335)  
(중요)  
Windows Server 2012  
(2863725)  
(중요)  
Windows Server 2012  
(2864202)  
(중요)  
Windows Server 2012  
(2868038)  
(중요)  
Windows Server 2012  
(2883150)  
(긴급)  
Windows Server 2012  
(2884256)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(긴급)  
Microsoft .NET Framework 3.5  
(2861704)  
(중요)  
Microsoft .NET Framework 3.5  
(2863243)  
(중요)  
Microsoft .NET Framework 4.5  
(2861702)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2864058)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows RT  
(2847311)  
(긴급)  
Windows RT  
(2862330)  
(중요)  
Windows RT  
(2862335)  
(중요)  
Windows RT  
(2863725)  
(중요)  
Windows RT  
(2864202)  
(중요)  
Windows RT  
(2868038)  
(중요)  
Windows RT  
(2883150)  
(긴급)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2861702)  
(중요)
</td>
<td style="border:1px solid black;">
Windows RT  
(2864058)  
(심각도 없음)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 8.1(32비트 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
Windows 8.1(64비트 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
<th style="border:1px solid black;" colspan="5">
Windows Server 2012 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
<th style="border:1px solid black;" colspan="5">
Windows RT 8.1
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
<th style="border:1px solid black;" colspan="5">
Server Core 설치 옵션
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2847311)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2862330)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2862335)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2864202)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2876284)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2883150)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2864058)  
(심각도 없음)
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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2847311)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2862330)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2862335)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2864202)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2876284)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2883150)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2864058)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2847311)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2862330)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2862335)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2864202)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2876284)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2883150)  
(긴급)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(중요)  
Microsoft .NET Framework 4  
(2858302)  
(중요)  
Microsoft .NET Framework 4.5  
(2861208)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2864058)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2847311)  
(긴급)  
Windows Server 2012(Server Core 설치)  
(2862330)  
(중요)  
Windows Server 2012(Server Core 설치)  
(2862335)  
(중요)  
Windows Server 2012(Server Core 설치)  
(2863725)  
(중요)  
Windows Server 2012(Server Core 설치)  
(2864202)  
(중요)  
Windows Server 2012(Server Core 설치)  
(2883150)  
(긴급)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(긴급)  
Microsoft .NET Framework 3.5  
(2861704)  
(중요)  
Microsoft .NET Framework 3.5  
(2863243)  
(중요)  
Microsoft .NET Framework 4.5  
(2861702)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2864058)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)
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
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
MS13-080 참고 사항

<sup>[1]</sup>Internet Explorer 11의 경우 고객은 Windows RT 8.1, Windows 8.1 및 Windows Server 2012 R2 업데이트 롤업을 적용해야 합니다. 2013년 10월(2883200) 2883200 업데이트 롤업에는 보안 및 비보안 업데이트가 포함되어 있습니다. 자세한 내용 및 사용 가능한 다운로드 링크는 [Microsoft 기술 자료 문서 2883200](https://support.microsoft.com/kb/2883200)을 참조하십시오.

#### Microsoft Office 제품군 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft Word 2003 서비스 팩 3  
(2826020)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 서비스 팩 3  
(2827324)  
(중요)  
Microsoft Office 2007 서비스 팩 3  
(2760585)  
(중요)  
Microsoft Office 2007 서비스 팩 3  
(2760591)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft Word 2007 서비스 팩 3  
(2827330)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 서비스 팩 1(32비트 에디션)  
(2826033)  
(중요)  
Microsoft Office 2010 서비스 팩 1(32비트 에디션)  
(2826023)  
(중요)  
Microsoft Office 2010 서비스 팩 1(32비트 에디션)  
(2826035)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 서비스 팩 1(64비트 에디션)  
(2826033)  
(중요)  
Microsoft Office 2010 서비스 팩 1(64비트 에디션)  
(2826023)  
(중요)  
Microsoft Office 2010 서비스 팩 1(64비트 에디션)  
(2826035)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 서비스 팩 2(32비트 에디션)  
(2826033)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 에디션)  
(2826023)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 에디션)  
(2826035)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 서비스 팩 2(64비트 에디션)  
(2826033)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 에디션)  
(2826023)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 에디션)  
(2826035)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013(32비트 에디션)  
(2827238)  
(중요)  
Microsoft Office 2013(32비트 에디션)  
(2817623)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013(64비트 에디션)  
(2827238)  
(중요)  
Microsoft Office 2013(64비트 에디션)  
(2817623)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2827238)  
(중요)  
Microsoft Office 2013 RT  
(2817623)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(2889496)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
기타 Microsoft Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3
</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(2827326)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(2827329)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2827328)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 

#### Microsoft Server 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 서비스 팩 3(wssloc)(32비트 버전)  
(2596741)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 서비스 팩 3(wssloc)(64비트 버전)  
(2596741)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 서비스 팩 1(wssloc)  
(2589365)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 서비스 팩 2(wssloc)  
(2589365)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013(pptserver)  
(2760561)  
(중요)
</td>
</tr>
</table>
 
MS13-084 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Office Services 및 Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 에디션)
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 에디션)
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
(중요)  
Word Automation Services  
(2826022)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
(중요)  
Word Automation Services  
(2826022)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Excel Services  
(2752002)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Word Automation Services  
(2826036)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Office Web Apps 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 서비스 팩 1  
(2826030)  
(중요)  
Microsoft Excel Web App 2010 서비스 팩 1  
(2826028)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 서비스 팩 2  
(2826030)  
(중요)  
Microsoft Excel Web App 2010 서비스 팩 2  
(2826028)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Office Web Apps 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2827222)  
(중요)
</td>
</tr>
</table>
 
MS13-084 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft 개발자 도구 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-087](https://go.microsoft.com/fwlink/?linkid=324590)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
Mac에 설치된 Microsoft Silverlight 5  
(2890788)  
(중요)  
Mac에 설치된 Microsoft Silverlight 5 Developer 런타임  
(2890788)  
(중요)  
지원 대상인 모든 Microsoft Windows 클라이언트 릴리스에 설치된 Microsoft Silverlight 5  
(2890788)  
(중요)  
지원 대상인 모든 Microsoft Windows 클라이언트 릴리스에 설치된 Microsoft Silverlight 5 Developer 런타임  
(2890788)  
(중요)  
지원 대상인 모든 Microsoft Windows 서버 릴리스에 설치된 Microsoft Silverlight 5  
(2890788)  
(중요)  
지원 대상인 모든 Microsoft Windows 서버 릴리스에 설치된 Microsoft Silverlight 5 Developer 런타임  
(2890788)  
(중요)
</td>
</tr>
</table>
 

검색, 배포 도구 및 지침
-----------------------

관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 존재합니다.

-   관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 구성 오류를 검색할 수 있습니다.
-   WSUS(Windows Server Update Services), SMS(Systems Management Server), System Center Configuration Manager는 관리자가 보안 업데이트를 배포하는 데 도움이 됩니다.
-   ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](https://technet.microsoft.com/security/cc297183)를 참조하십시오.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 버전에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 발표에서 사용할 수 없습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199)
-   : 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](https://technet.microsoft.com/wsus/bb456965)
-   . Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](https://go.microsoft.com/fwlink/?linkid=215201)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

업데이트 관리 전략

[업데이트 관리를 위한 보안 가이드](https://go.microsoft.com/fwlink/?linkid=21168)(영문)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

기타 보안 관련 업데이트 받기

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://go.microsoft.com/fwlink/?linkid=21127)드립니다.

MS13-080

-   Internet Explorer 메모리 손상 취약점(CVE-2013-3872)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com)
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3873)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Yenteasy - Security Research의 Jose A. Vazquez
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3874)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Amol Naik
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3874)을 [VeriSign iDefense Labs](https://labs.idefense.com)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3875)을 [VeriSign iDefense Labs](https://labs.idefense.com)(영문)와 협력하여 보고해 주신 Yenteasy - Security Research의 Jose A. Vazquez
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3882)을 보고해 주신 [Google Security Team](https://www.google.com/)의 Ivan Fratric
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3882)을 보고해 주신 Yenteasy - Security Research의 Jose A. Vazquez
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3885)을 보고해 주신 Yenteasy - Security Research의 Jose A. Vazquez
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3886)을 [VeriSign iDefense Labs](https://labs.idefense.com)(영문)와 협력하여 보고해 주신 Yenteasy - Security Research의 Jose A. Vazquez
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3893)에 대해 Microsoft와 협력해 주신 [LAC Co.](https://www.lac.co.jp/)(일문)의 Yoshihiro Ishikawa
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3897)에 대해 Microsoft와 협력해 주신 네덜란드의 국가 사이버 안전 센터와 협력하시는 Hoodie22
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3897)에 대해 Microsoft와 협력해 주신 Trustwave SpiderLabs Team의 Daniel Chechik
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3897)에 대해 Microsoft와 협력해 주신 [IOprotect GmbH](https://ioprotect.ch/)(영문)의 Renato Ettisberger

MS13-081

-   OpenType 글꼴 구문 분석 취약점(CVE-2013- 3128)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Windows USB 설명자 취약점(CVE-2013-3200)을 보고해 주신 [NCC Group](https://www.nccgroup.com/)(영문)의 Andy Davis
-   Windows USB 설명자 취약점(CVE-2013-3200)을 보고해 주신 ANSSI의 Lucas Bouillot
-   Win32k NULL 페이지 취약점(CVE-2013-3881)을 보고해 주신 [Endgame](https://www.endgame.com/)(영문)의 Seth Gibson 및 Dan Zentner
-   TrueType 글꼴 CMAP 테이블 취약점(CVE-2013-3895)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 ZombiE

MS13-082

-   OpenType 글꼴 구문 분석 취약점(CVE-2013- 3128)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   엔터티 확장 취약점(CVE-2013-3860)을 보고해 주신 [Context Information Security](https://www.contextis.com/)(영문)의 James Forshaw

MS13-083

-   Comctl32 정수 오버플로 취약점(CVE-2013-3195)을 보고해 주신 孙晓山

MS13-084

-   Microsoft Excel 메모리 손상 취약점(CVE-2013-3889)을 보고해 주신 [Google Security Team](https://www.google.com/)의 Mateusz Jurczyk, Ivan Fratric 및 Ben Hawkes
-   매개 변수 주입 취약점(CVE-2013-3895)을 보고해 주신 Nutan kumar panda
-   이 공지에 포함된 심층 보안 변경 사항에 대해 협력해 주신 [National Institutes of Health](https://nih.gov/)의 Ari Elias-Bachrach 및 Angela Kelso

MS13-085

-   Microsoft Excel 메모리 손상 취약점(CVE-2013-3889)을 보고해 주신 [Google Security Team](https://www.google.com/)의 Mateusz Jurczyk, Ivan Fratric 및 Ben Hawkes
-   Microsoft Excel 메모리 손상 취약점(CVE-2013-3890)을 보고해 주신 [Google Security Team](https://www.google.com/)의 Mateusz Jurczyk, Ivan Fratric 및 Ben Hawkes

MS13-086

-   메모리 손상 취약점(CVE-2013-3891)을 보고해 주신 Yuhong Bao
-   메모리 손상 취약점(CVE-2013-3892)을 보고해 주신 [Google Security Team](https://www.google.com/)의 Mateusz Jurczyk, Ivan Fratric 및 Ben Hawkes

MS13-087

-   Silverlight 취약점(CVE-2013-3896)을 보고해 주신 Vitaliy Toropov

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](https://technet.microsoft.com/security/bb980617)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](https://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2013년 10월 9일): 공지 요약이 게시되었습니다.
-   V1.1(2013년 10월 11일): MS13-080에서 CVE-2013-3871에 대한 악용 가능성 인덱스의 악용 가능성 평가를 제거했습니다. 기존 악용 가능성 인덱스에 포함된 이 CVE는 문서상 오류였습니다. CVE-2013-3871은 추후 보안 업데이트에서 해결될 예정입니다. 이 변경 사항은 정보에만 해당됩니다. MS13-082에서 Windows Server 2012의 Server Core 설치가 2861194 업데이트에서 해결된 취약점의 영향을 받는다는 사실을 표시하기 위해 공지를 개정했습니다. 검색 로직이나 보안 업데이트 파일에 대한 변경 사항은 없습니다. 이미 시스템을 성공적으로 업데이트한 고객은 추가 조치를 취할 필요가 없습니다.
-   V1.2 (2013년 11월 7일): MS13-084에서 Microsoft Office Web Apps Server 2013(2827222) 업데이트의 제품 이름을 수정하였습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
