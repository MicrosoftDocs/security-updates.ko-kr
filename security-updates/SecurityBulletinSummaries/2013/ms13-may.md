---
TOCTitle: 'MS13-MAY'
Title: 2013 년 5 월 Microsoft 보안 공지 요약
ms:assetid: 'ms13-may'
ms:contentKeyID: 61230765
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms13-may(v=Security.10)'
---

2013 년 5 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2013년 5월 15일 수요일 | 업데이트된 날짜: 2013년 5월 23일 목요일

**버전:** 1.1

이 공지 요약 목록에는 2013년 5월 발표된 보안 공지가 포함되어 있습니다.

2013년 5월 보안 공지 발표와 함께 이 공지 요약이 2013년 5월 9일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2013년 5월 15일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [5월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538728&culture=ko-kr)(영문). 이 날짜 이후 이 웹캐스트는 [주문형](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538728&culture=ko-kr)(영문)으로 제공됩니다.

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2829530)  <br />
<br />
이 보안 업데이트는 Internet Explorer의 비공개적으로 보고된 취약점 11건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 가장 위험한 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299892">MS13-038</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2847204) <br />
<br />
이 보안 업데이트는 Internet Explorer의 공개된 취약점 1건을 해결합니다. 이 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=293363">MS13-039</a></td>
<td style="border:1px solid black;">HTTP.sys 취약점으로 인한 서비스 거부 문제점(2829254)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 영향을 받는 Windows 서버나 클라이언트에 특수하게 조작된 HTTP 패킷을 보낼 경우 서비스 거부가 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=296485">MS13-040</a></td>
<td style="border:1px solid black;">.NET Framework의 취약점으로 인한 스푸핑 문제점(2836440)  <br />
<br />
이 보안 업데이트는 .NET Framework의비공개적으로 보고된 취약점 1건과 공개적으로 보고된 취약점 1건을 해결합니다. 가장 위험한 취약점으로 인해 .NET 응용 프로그램에서 특수하게 조작된 XML 파일을 수신할 경우 스푸핑을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 파일의 서명을 무효화하지 않으면서 XML 파일의 내용을 수정하고 인증된 사용자인 것처럼 종점 기능에 대한 액세스 권한을 얻을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
스푸핑</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=293445">MS13-041</a></td>
<td style="border:1px solid black;">Lync의 취약점으로 인한 원격 코드 실행 문제점(2834695) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Lync의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 콘텐츠(파일 또는 프로그램 등)를 Lync 또는 Communicator에서 프레젠테이션으로 공유한 다음 사용자가 초대를 수락하여 프레젠테이션 가능한 콘텐츠를 보거나 공유하도록 유도할 경우 원격 코드 실행이 허용될 수 있습니다. 어떠한 경우에도 공격자는 강제로 사용자가 공격자 제어 파일 또는 프로그램을 보거나 공유하도록 만들 수는 없습니다. 대신 공격자는 사용자가 Lync 또는 Communicator에서 초대를 수락하여 프레젠테이션 가능한 콘텐츠를 보거나 공유하게 하는 등의 조치를 취하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Microsoft Publisher의 취약점으로 인한 원격 코드 실행 문제점(2830397)  <br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 11건을 해결합니다. 이러한 취약점으로 인해 사용자가 영향을 받는 버전의 Microsoft Publisher로 특수하게 조작된 Publisher 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287107">MS13-043</a></td>
<td style="border:1px solid black;">Microsoft Word의 취약점으로 인한 원격 코드 실행 문제점(2830399)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 영향을 받는 Microsoft Office 소프트웨어에서 특수하게 조작된 파일을 열거나 특수하게 조작된 전자 메일 메시지를 미리 볼 경우 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=293446">MS13-044</a></td>
<td style="border:1px solid black;">Microsoft Visio의 취약점으로 인한 정보 유출 문제점(2834692)  <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 Visio 파일을 열 경우 정보 유출이 발생할 수 있습니다. 이 취약점으로 인해 공격자가 직접 코드를 실행하거나 해당 사용자 권한을 상승시킬 수는 없지만 영향을 받는 시스템의 손상을 악화시키는 데 사용할 수 있는 정보를 생성할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=280675">MS13-045</a></td>
<td style="border:1px solid black;">Windows Essentials의 취약점으로 인한 정보 유출 문제점(2813707)  <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows Essentials의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 URL을 사용하여 Windows Writer를 열 경우 정보 유출이 발생할 수 있습니다. 취약점 악용에 성공한 공격자는 Windows Writer 프록시 설정을 무시하고 대상 시스템에서 사용자가 액세스할 수 있는 파일을 덮어쓸 수 있습니다. 웹 기반의 공격 시나리오에서 웹 사이트는 이 취약점을 악용하는 데 사용되는 특수하게 조작된 링크를 포함하고 있을 수 있습니다. 공격자는 사용자가 웹 사이트를 방문하고 특수하게 조작된 링크를 열도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows Essentials</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;">커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2840221) <br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 3건을 해결합니다. 공격자가 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0811">CVE-2013-0811</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">JSON 배열 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1297">CVE-2013-1297</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1306">CVE-2013-1306</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1307">CVE-2013-1307</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1308">CVE-2013-1308</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1309">CVE-2013-1309</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1310">CVE-2013-1310</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1311">CVE-2013-1311</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1312">CVE-2013-1312</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-2551">CVE-2013-2551</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3140">CVE-2013-3140</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299892">MS13-038</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1347">CVE-2013-1347</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
Microsoft는 Internet Explorer 8을 통해 이 취약점을 악용하려는 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=293363">MS13-039</a></td>
<td style="border:1px solid black;">HTTP.sys 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1305">CVE-2013-1305</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=296485">MS13-040</a></td>
<td style="border:1px solid black;">XML 디지털 서명 스푸핑 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1336">CVE-2013-1336</a>(영문)</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 스푸핑 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=296485">MS13-040</a></td>
<td style="border:1px solid black;">인증 우회 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1337">CVE-2013-1337</a>(영문)</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
이 취약점은 보안 기능 우회 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=293445">MS13-041</a></td>
<td style="border:1px solid black;">Lync RCE 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1302">CVE-2013-1302</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 음수 값 할당 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1316">CVE-2013-1316</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 정수 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1317">CVE-2013-1317</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 손상된 인터페이스 포인터 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1318">CVE-2013-1318</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 반환 값 처리 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1319">CVE-2013-1319</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 버퍼 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1320">CVE-2013-1320</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 반환 값 유효성 검사 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1321">CVE-2013-1321</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 잘못된 범위 확인 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1322">CVE-2013-1322</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 잘못된 NULL 값 처리 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1323">CVE-2013-1323</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 부호가 있는 정수 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1327">CVE-2013-1327</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 포인터 처리 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1328">CVE-2013-1328</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 버퍼 언더플로 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1329">CVE-2013-1329</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=287107">MS13-043</a></td>
<td style="border:1px solid black;">Word 도형 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1335">CVE-2013-1335</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=293446">MS13-044</a></td>
<td style="border:1px solid black;">XML 외부 엔터티 확인 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1301">CVE-2013-1301</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=280675">MS13-045</a></td>
<td style="border:1px solid black;">Windows Essentials 잘못된 URI 처리 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0096">CVE-2013-0096</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;">DirectX 그래픽 커널 하위 시스템 이중 페치 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1332">CVE-2013-1332</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;">Win32k 버퍼 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1333">CVE-2013-1333</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;">Win32k 창 처리 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1334">CVE-2013-1334</a>(영문)</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
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
<th style="border:1px solid black;" colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-037](https://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[MS13-038](https://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[MS13-039](https://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[MS13-040](https://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[MS13-046](https://go.microsoft.com/fwlink/?linkid=296427)
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
없음
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
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2829530)  
(긴급)  
Internet Explorer 7   
(2829530)  
(긴급)  
Internet Explorer 8   
(2829530)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 8   
(2847204)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2804577)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)
</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(2829361)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2829530)  
(긴급)  
Internet Explorer 7   
(2829530)  
(긴급)  
Internet Explorer 8   
(2829530)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 8   
(2847204)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2804577)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2829361)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-037](https://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[MS13-038](https://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[MS13-039](https://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[MS13-040](https://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[MS13-046](https://go.microsoft.com/fwlink/?linkid=296427)
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
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2829530)  
(보통)  
Internet Explorer 7  
(2829530)  
(보통)  
Internet Explorer 8  
(2829530)  
(보통)
</td>
<td style="border:1px solid black;">
Internet Explorer 8   
(2847204)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2804577)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2829530)  
(보통)  
Internet Explorer 7  
(2829530)  
(보통)  
Internet Explorer 8  
(2829530)  
(보통)
</td>
<td style="border:1px solid black;">
Internet Explorer 8   
(2847204)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2804577)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2829530)  
(보통)  
Internet Explorer 7  
(2829530)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2804577)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-037](https://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[MS13-038](https://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[MS13-039](https://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[MS13-040](https://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[MS13-046](https://go.microsoft.com/fwlink/?linkid=296427)
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
없음
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
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(긴급)  
Internet Explorer 8  
(2829530)  
(긴급)  
Internet Explorer 9   
(2829530)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(긴급)  
Internet Explorer 9   
(2847204)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2804580)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)  
Microsoft .NET Framework 4.5  
(2804582)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2830290)  
(중요)  
Windows Vista 서비스 팩 2  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(긴급)  
Internet Explorer 8  
(2829530)  
(긴급)  
Internet Explorer 9   
(2829530)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(긴급)  
Internet Explorer 9   
(2847204)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2804580)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)  
Microsoft .NET Framework 4.5  
(2804582)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2830290)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-037](https://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[MS13-038](https://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[MS13-039](https://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[MS13-040](https://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[MS13-046](https://go.microsoft.com/fwlink/?linkid=296427)
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
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(보통)  
Internet Explorer 8  
(2829530)  
(보통)  
Internet Explorer 9   
(2829530)  
(보통)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(보통)  
Internet Explorer 9   
(2847204)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2804580)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)  
Microsoft .NET Framework 4.5  
(2804582)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2830290)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(보통)  
Internet Explorer 8  
(2829530)  
(보통)  
Internet Explorer 9   
(2829530)  
(보통)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(보통)  
Internet Explorer 9   
(2847204)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2804580)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)  
Microsoft .NET Framework 4.5  
(2804582)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2830290)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2804580)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2830290)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-037](https://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[MS13-038](https://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[MS13-039](https://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[MS13-040](https://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[MS13-046](https://go.microsoft.com/fwlink/?linkid=296427)
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
없음
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
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(긴급)  
Internet Explorer 9   
(2829530)  
(긴급)  
Internet Explorer 10   
(2829530)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(긴급)  
Internet Explorer 9   
(2847204)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)  
Microsoft .NET Framework 4.5  
(2804582)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2830290)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(2829361)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(긴급)  
Internet Explorer 9   
(2829530)  
(긴급)  
Internet Explorer 10   
(2829530)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(긴급)  
Internet Explorer 9   
(2847204)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)  
Microsoft .NET Framework 4.5  
(2804582)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2830290)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2829361)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-037](https://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[MS13-038](https://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[MS13-039](https://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[MS13-040](https://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[MS13-046](https://go.microsoft.com/fwlink/?linkid=296427)
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
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(보통)  
Internet Explorer 9   
(2829530)  
(보통)  
Internet Explorer 10   
(2829530)  
(보통)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(보통)  
Internet Explorer 9   
(2847204)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)  
Microsoft .NET Framework 4.5  
(2804582)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2830290)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(보통)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2830290)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-037](https://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[MS13-038](https://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[MS13-039](https://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[MS13-040](https://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[MS13-046](https://go.microsoft.com/fwlink/?linkid=296427)
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
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 8(32비트 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2829530)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2829254)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(중요)  
Microsoft .NET Framework 4.5  
(2804583)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2830290)  
(중요)  
Windows 8(32비트 시스템용)  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2829530)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)  
(2829254)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(중요)  
Microsoft .NET Framework 4.5  
(2804583)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)  
(2830290)  
(중요)  
Windows 8(64비트 시스템용)  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-037](https://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[MS13-038](https://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[MS13-039](https://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[MS13-040](https://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[MS13-046](https://go.microsoft.com/fwlink/?linkid=296427)
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
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2829530)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2829254)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(중요)  
Microsoft .NET Framework 4.5  
(2804583)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2830290)  
(중요)  
Windows Server 2012  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-037](https://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[MS13-038](https://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[MS13-039](https://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[MS13-040](https://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[MS13-046](https://go.microsoft.com/fwlink/?linkid=296427)
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
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2829530)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows RT  
(2829254)  
(보통)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2804583)  
(중요)
</td>
<td style="border:1px solid black;">
Windows RT  
(2830290)  
(중요)  
Windows RT  
(2829361)  
(심각도 없음)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Server Core 설치 옵션
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-037](https://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[MS13-038](https://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[MS13-039](https://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[MS13-040](https://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[MS13-046](https://go.microsoft.com/fwlink/?linkid=296427)
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
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)
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
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2830290)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2829361)  
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2830290)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2829361)  
(심각도 없음)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(중요)  
Microsoft .NET Framework 4.5  
(2804582)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2830290)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2829361)  
(심각도 없음)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2829254)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(중요)  
Microsoft .NET Framework 4.5  
(2804583)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2830290)  
(중요)  
Windows Server 2012(Server Core 설치)  
(2829361)  
(심각도 없음)
</td>
</tr>
</table>
 
MS13-040 참고 사항

<sup>[1]</sup>.NET Framework 4 및 .NET Framework 4 Client Profile이 영향을 받습니다. .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4 및 .NET Framework 4 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4 Client Profile은 .NET Framework 4의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4 및 .NET Framework 4 Client Profile에 모두 영향을 줍니다. 자세한 내용은 MSDN 문서, [.NET Framework 설치](https://msdn.microsoft.com/ko-kr/library/5a4x27ek.aspx)를 참조하십시오.

#### Microsoft Office 제품군 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-042](https://go.microsoft.com/fwlink/?linkid=287106)
</td>
<td style="border:1px solid black;">
[MS13-043](https://go.microsoft.com/fwlink/?linkid=287107)
</td>
<td style="border:1px solid black;">
[MS13-044](https://go.microsoft.com/fwlink/?linkid=293446)
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
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2003 서비스 팩 3  
(2810047)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft Word 2003 서비스 팩 3  
(2810046)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2007 서비스 팩 3  
(2597971)  
(중요)
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
Microsoft Office 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2010 서비스 팩 1(32비트 에디션)  
(2553147)  
(중요)
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
Microsoft Office 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2010 서비스 팩 1(64비트 에디션)  
(2553147)  
(중요)
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
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2817361)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2003 서비스 팩 3 
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft Visio 2003 서비스 팩 3   
(2810062)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2007 서비스 팩 3 
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft Visio 2007 서비스 팩 3   
(2596595)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2010 서비스 팩 1(32비트 에디션) 
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft Visio 2010 서비스 팩 1(32비트 에디션)   
(2810068)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2010 서비스 팩 1(64비트 에디션) 
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft Visio 2010 서비스 팩 1(64비트 에디션)   
(2810068)  
(중요)
</td>
</tr>
</table>
 

#### Microsoft 통신 플랫폼 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Lync
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-041](https://go.microsoft.com/fwlink/?linkid=293445)
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
Microsoft Communicator 2007 R2
</td>
<td style="border:1px solid black;">
Microsoft Communicator 2007 R2  
(2827753)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)  
(2827750)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)  
(2827750)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)  
(2827752)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(사용자 수준 설치)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(사용자 수준 설치)  
(2827751)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Web Components Server)
</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Web Components Server)  
(2827754)  
(중요)
</td>
</tr>
</table>
 

#### Microsoft 소비자 도구 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Windows Essentials
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-045](https://go.microsoft.com/fwlink/?linkid=280675)
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
Windows Essentials 2011
</td>
<td style="border:1px solid black;">
Windows Essentials 2011   
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Essentials 2012
</td>
<td style="border:1px solid black;">
Windows Essentials 2012   
(2813707)  
(중요)
</td>
</tr>
</table>
 

검색, 배포 도구 및 지침
-----------------------

<span></span>
보안 센터

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](https://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security TechCenter](https://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [Microsoft 안전 및 보안 센터](https://go.microsoft.com/fwlink/?linkid=85102)를 방문하거나 "보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)(영문)을 참조하십시오.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](https://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS13-001")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](https://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

검색 및 배포 지침

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](https://support.microsoft.com/kb/961747)을 참조하십시오.

Microsoft Baseline Security Analyzer

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)를 참조하십시오.

Windows Server Update Services

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](https://technet.microsoft.com/wsus/default)를 참조하십시오.

System Center Configuration Manager

System Center Configuration Manager 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. System Center Configuration Manager를 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

System Center Configuration Manager의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. System Center Configuration Manager의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. System Center Configuration Manager에 대한 자세한 내용은 [System Center 기술 리소스](https://technet.microsoft.com/systemcenter/bb980621)를 참조하십시오.

Systems Management Server 2003

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

참고 System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](https://go.microsoft.com/fwlink/?linkid=21742) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager를 지금 사용할 수 있습니다(이전 섹션의 System Center Configuration Manager 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)(영문)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/systemcenter/bb545936)(영문)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](https://go.microsoft.com/fwlink/?linkid=33341)(영문)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)(영문)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971)(영문)에 포함된 [UCE(Update Compatibility Evaluator)](https://technet.microsoft.com/library/cc749197) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

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

MS13-037

-   Internet Explorer 해제 후 사용 취약점(CVE-2013-0811) [VeriSign iDefense Labs](https://labs.idefense.com)(영문)와 협력하여 보고해 주신 Jose Antonio Vazquez Gonzalez
-   JSON 배열 정보 유출 취약점(CVE-2013-1297)을 보고해 주신 Yosuke Hasegawa 및 Masahiro Yamada
-   Internet Explorer 해제 후 사용 취약점(CVE-2013-1306)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 SkyLined
-   Internet Explorer 해제 후 사용 취약점(CVE-2013-1306)을 보고해 주신 [Security-Assessment.com](https://www.security-assessment.com/)(영문)의 Scott Bell
-   Internet Explorer 해제 후 사용 취약점(CVE-2013-1307)을 보고해 주신 [Google Security Team](https://www.google.com/)의 Ivan Fratric
-   Internet Explorer 해제 후 사용 취약점(CVE-2013-1308)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com)
-   Internet Explorer 해제 후 사용 취약점(CVE-2013-1309)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 SkyLined
-   Internet Explorer 해제 후 사용 취약점(CVE-2013-1310)을 보고해 주신 Yuhong Bao
-   Internet Explorer 해제 후 사용 취약점(CVE-2013-1311)을 보고해 주신 [Security-Assessment.com](https://www.security-assessment.com/)(영문)의 Scott Bell
-   Internet Explorer 해제 후 사용 취약점(CVE-2013-1312)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Harmony Security](https://www.harmonysecurity.com)(영문)의 Stephen Fewer
-   Internet Explorer 해제 후 사용 취약점(CVE-2013-2551)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [VUPEN Security](https://www.vupen.com)(Pwn2Own 2013)(영문)
-   Internet Explorer 해제 후 사용 취약점(CVE-2013-3140)을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   이 공지에 포함된 심층 보안 변경 사항에 대해 협력해 주신 Masato Kinugawa
-   이 공지에 포함된 심층 보안 변경을 위해 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력해 주신 [VUPEN Security](https://www.vupen.com)(Pwn2Own 2013)(영문)

MS13-038

-   Internet Explorer 해제 후 사용 취약점(CVE-2013-1347)을 보고해 주신 [FireEye](https://www.fireeye.com/)(영문)의 Daniel Caselden
-   Internet Explorer 해제 후 사용 취약점(CVE-2013-1347)을 해결하기 위해 협력해 주신 [iSIGHT Partners](https://www.isightpartners.com/)(영문)

MS13-039

-   HTTP.sys 서비스 거부 취약점(CVE-2013-1305)을 보고한 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력해 주신 Marek Kroemeke, 22733db72ab3ed94b5f8a1ffcde850251fe6f466, AKAT-1

MS13-040

-   XML 디지털 서명 스푸핑 취약점(CVE-2013-1336)을 보고해 주신 [Context Information Security](https://www.contextis.com/)(영문)의 James Forshaw

MS13-042

-   여러 Microsoft Publisher 원격 코드 실행 취약점(CVE-2013-1316, CVE-2013-1317, CVE-2013-1318, CVE-2013-1319, CVE-2013-1320, CVE-2013-1321, CVE-2013-1322, CVE-2013-1323, CVE-2013-1327, CVE-2013-1328 및 CVE-2013-1329)을 해결하기 위해 협력해 주신 [CERT/CC](https://www.cert.org/)(영문)의 Will Dormann

MS13-043

-   Word 도형 손상 취약점(CVE-2013-1335)을 보고해 주신 [CERT/CC](https://www.cert.org/)(영문)의 Will Dormann

MS13-044

-   XML 외부 엔터티 확인 취약점(CVE-2013-1301)을 보고해 주신 [Positive Technologies](https://www.ptsecurity.com/)(영문)의 Timur Yunusov

MS13-045

-   Windows Essentials 잘못된 URI 처리 취약점(CVE-2013-0096)을 Beyond Security의 [SecuriTeam Secure Disclosure](https://www.beyondsecurity.com/ssd.html)(영문)팀과 협력하여 보고해 주신 Andrea Micalizzi

MS13-046

-   DirectX 그래픽 커널 하위 시스템 이중 페치 취약점(CVE-2013-1332)을 보고해 주신 을 보고해 주신 [Google Inc](https://www.google.com/)의 [Gynvael Coldwind](https://gynvael.coldwind.pl/)(영문) 및 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/)(영문)
-   Win32k 버퍼 오버플로 취약점(CVE-2013-1333)을 보고해 주신 [Qihoo 360 Security Center](https://www.360.cn/)(중문)
-   Win32k 창 처리 취약점(CVE-2013-1334)을 [iDefense VCP](https://labs.idefense.com/)(영문)와 협력하여 보고해 주신 익명 연구자

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](https://technet.microsoft.com/security/bb980617)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](https://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2013년 5월 15일): 공지 요약이 게시되었습니다.
-   V1.1(2013년 5월 23일): MS13-037에서 CVE-2013-3140에 대한 CVE(Common Vulnerabilities and Exposures) 번호를 수정하였습니다. 이 변경 사항은 정보에만 해당됩니다.

*Built at 2014-04-18T12:27:44Z-07:00*
