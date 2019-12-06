---
TOCTitle: 'MS13-JAN'
Title: 2013 년 1 월 Microsoft 보안 공지 요약
ms:assetid: 'ms13-jan'
ms:contentKeyID: 61230761
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms13-jan(v=Security.10)'
---

2013 년 1 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2013년 1월 8일 화요일 | 업데이트된 날짜: 2013년 3월 13일 수요일

**버전:** 4.0

이 공지 요약 목록에는 2013년 1월 발표된 보안 공지가 포함되어 있습니다.

2013년 1월 보안 공지 발표와 함께 이 공지 요약이 2013년 1월 3일에 게시된 공지 사전 알림과 2013년 1월 13일에 게시된 부정기 공지 사전 알림을 대체합니다. 공지 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2013년 1월 9일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [1월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538623&culture=ko-kr). 이 날짜 이후 이 웹캐스트는 [주문형](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538623&culture=ko-kr)으로 제공됩니다.

Microsoft는 2013년 1월 14일 오후 1:00(태평양 표준시, 미국 및 캐나다)에 부정기 보안 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [2013년 1월 14일에 진행되는 부정기 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032541648&culture=ko-kr). 이 날짜 이후 이 웹캐스트는 [주문형](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032541648&culture=ko-kr)으로 제공됩니다.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. 기타 정보 섹션을 참조하십시오.

### 공지 정보

#### 요약

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 영향을 받는 소프트웨어 및 다운로드 위치를 참조하십시오.

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275222">MS13-008</a></td>
<td style="border:1px solid black;">Internet Explorer 보안 업데이트(2799329)  <br />
<br />
이 보안 업데이트는 Internet Explorer의 공개된 취약점 1건을 해결합니다. 이 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273848">MS13-001</a></td>
<td style="border:1px solid black;">Windows 인쇄 스풀러 구성 요소의 취약점으로 인한 원격 코드 실행 문제점(2769369)  <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점 1건을 해결합니다. 이 취약점으로 인해 인쇄 서버에서 특수하게 조작된 인쇄 요청을 받을 경우 원격 코드가 실행될 수 있습니다. 최선의 방화벽 구성 방법과 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 들어오는 공격으로부터 네트워크를 보호할 수 있습니다. 인터넷과 직접 연결되는 시스템의 경우 필요한 포트만 최소한으로 열어 두는 것이 안전합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">Microsoft XML Core Services의 취약점으로 인한 원격 코드 실행 문제점(2756145) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft XML Core Services의 취약점 2건을 해결합니다. 이 취약점들은 모두 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 공격자는 강제로 사용자가 이러한 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Microsoft Office, <br />
Microsoft 개발자 도구,  <br />
Microsoft Server 소프트웨어</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">System Center Operations Manager의 취약점으로 인한 권한 상승 문제점(2748552)  <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft System Center Operations Manager의 취약점 2건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 URL을 통해 영향을 받는 웹 사이트를 방문할 경우 권한 상승이 허용될 수 있습니다. 공격자는 강제로 사용자가 이러한 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 영향을 받는 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft Server 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">.NET Framework의 취약점으로 인한 권한 상승 문제점(2769324)  <br />
<br />
이 보안 업데이트는 .NET Framework에서 발견되어 비공개적으로 보고된 취약점4건을 해결합니다. 이 중 가장 심각한 취약점은 사용자가 XAML 브라우저 응용 프로그램(XBAP)을 실행하는 웹 브라우저에서 특수하게 조작된 웹 페이지를 보는 경우 유발되는 권한 상승입니다. 이 취약점은 CAS(코드 액세스 보안) 제한을 우회하기 위해 Windows .NET 응용 프로그램에서 사용될 수도 있습니다. 이러한 취약점을 성공적으로 악용한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273826">MS13-005</a></td>
<td style="border:1px solid black;">Windows 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점 (2778930)  <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점 1건을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 응용 프로그램을 사용할 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273872">MS13-006</a></td>
<td style="border:1px solid black;">Microsoft Windows의 취약점으로 인한 보안 기능 우회 (2785220)  <br />
<br />
이 보안 업데이트는 Microsoft Windows의 SSL 및 TLS 구현에서 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 공격자가 암호화된 웹 트래픽 핸드셰이크를 가로챌 경우 보안 기능을 우회할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268284">MS13-007</a></td>
<td style="border:1px solid black;">Open Data 프로토콜의 취약점으로 인한 서비스 거부 (2769327)  <br />
<br />
이 보안 업데이트는 OData(Open Data) 프로토콜의 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 인증되지 않은 공격자가 특수하게 조작된 HTTP 요청을 영향을 받는 사이트에 전송할 경우 서비스 거부가 발생할 수 있습니다. 최선의 방화벽 구성 방법과 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 들어오는 공격으로부터 네트워크를 보호할 수 있습니다. 인터넷과 연결되는 시스템의 경우, 필요한 포트만 최소한으로 열어 두는 것이 안전합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273848">MS13-001</a></td>
<td style="border:1px solid black;">Windows 인쇄 스풀러 구성 요소 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0011">CVE-2013-0011</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">MSXML 정수 잘림 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0006">CVE-2013-0006</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">MSXML XSLT 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0007">CVE-2013-0007</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">System Center Operations Manager 웹 콘솔 XSS 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0009">CVE-2013-0009</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">System Center Operations Manager 웹 콘솔 XSS 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0010">CVE-2013-0010</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">WinForms 버퍼 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0002">CVE-2013-0002</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">S.DS.P 버퍼 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0003">CVE-2013-0003</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">이중 구성 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0004">CVE-2013-0004</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273826">MS13-005</a></td>
<td style="border:1px solid black;">Win32k 부적절한 메시지 처리 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0008">CVE-2013-0008</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273872">MS13-006</a></td>
<td style="border:1px solid black;">Microsoft SSL 버전 3 및 TLS 프로토콜 보안 기능 우회 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0013">CVE-2013-0013</a>(영문)</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 보안 기능 우회 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268284">MS13-007</a></td>
<td style="border:1px solid black;">교체 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0005">CVE-2013-0005</a>(영문)</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275222">MS13-008</a></td>
<td style="border:1px solid black;">Internet Explorer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4792">CVE-2012-4792</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
Microsoft는 Internet Explorer 8을 통해 이 취약점을 악용하려는 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
</tbody>
</table>
 

영향을 받는 소프트웨어 및 다운로드 위치
---------------------------------------


다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.

이 표를 어떻게 사용합니까?

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.

참고 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

#### Windows 운영 체제 및 구성 요소

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="8">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=20d8d873-a709-4834-a956-f3d9d82dbb73&displaylang=ko)   
(KB2799329)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=dcdcf814-e39d-4515-bc5d-12e11f214d08&displaylang=ko)  
(KB2799329)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4e0d584a-c684-408c-bc47-6bd4ecaa9b8a&displaylang=ko)  
(KB2799329)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b&displaylang=ko)  
(KB2758694)  
(긴급)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=137cc5ee-abf0-4a10-b1c4-d464331cbcfd&displaylang=ko)  
(KB2757638)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=155a2984-2cd9-40a4-abaa-c1ea21e76062&displaylang=ko)  
(KB2742607)  
(Media Center Edition 2005 서비스 팩 3 및 Tablet PC Edition 2005 서비스 팩 3만 해당)  
(중요)  
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5&displaylang=ko)  
(KB2742597)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610&displaylang=ko)  
(KB2742596)  
(중요)  
[Microsoft .NET Framework 3.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21&displaylang=ko)  
(KB2756918)  
(심각도 없음<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d&displaylang=ko)  
(KB2736416)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=f35f2ea5-d60e-405a-9ed3-248e0d733c2b)   
(KB2799329)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=36c9d6a9-d939-4e19-b9f5-576fee048764)  
(KB2799329)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=396f26bd-8c8b-459d-9467-6ec17a11c9d4)  
(KB2799329)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=d147f865-6a56-4db2-8d78-14f2bee6da18)  
(KB2757638)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(긴급)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=0b13a83c-1e51-4604-a09d-afb2e25646f9)  
(KB2758696)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(중요)  
[Microsoft .NET Framework 3.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(심각도 없음<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=1a7cfc5a-2872-4516-a371-f42d4d3969a6&displaylang=ko)   
(KB2799329)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4b7c2bcd-a732-46ba-9d09-cc192efd4755&displaylang=ko)  
(KB2799329)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7f134d1c-670d-4528-b755-22124aa4d8c9&displaylang=ko)  
(KB2799329)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b&displaylang=ko)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=6a12de5f-de80-48e4-8276-6c420f5a2948&displaylang=ko)  
(KB2758696)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=f1a2eb6e-0290-4a53-b93c-017a48b19973&displaylang=ko)  
(KB2742604)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610&displaylang=ko)  
(KB2742596)  
(중요)  
[Microsoft .NET Framework 3.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21&displaylang=ko)  
(KB2756918)  
(심각도 없음<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d&displaylang=ko)  
(KB2736416)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=00304f3b-069f-49dc-a416-b0b5fb97aa4b&displaylang=ko)   
(KB2799329)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4911899c-863f-4499-9477-340ef8daad29&displaylang=ko)  
(KB2799329)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b0cf6516-aea6-4879-9a6e-171d4825ae20&displaylang=ko)  
(KB2799329)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=29985fdc-8aba-44b2-9420-970ca475052e&displaylang=ko)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=0b13a83c-1e51-4604-a09d-afb2e25646f9&displaylang=ko)  
(KB2758696)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5&displaylang=ko)  
(KB2742597)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610&displaylang=ko)  
(KB2742596)  
(중요)  
[Microsoft .NET Framework 3.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21&displaylang=ko)  
(KB2756918)  
(심각도 없음<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d&displaylang=ko)  
(KB2736416)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=b2c635b7-56ad-426b-8bd6-4aee9deadb69)   
(KB2799329)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b33197ab-f489-4c11-a229-044b186d7dda)  
(KB2799329)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=bca95077-a28f-406c-9fe4-51dbcf6adee8)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=fb834cf7-d1fe-4291-8a0d-c866fdbdf0e6)  
(KB2758696)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=95d603e8-9440-4aa6-9765-20c77a55966a&displaylang=ko)  
(KB2799329)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=64b498a6-54fc-4b88-bcc3-2cc15a16abb5&displaylang=ko)  
(KB2799329)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b&displaylang=ko)  
(KB2758694)  
(긴급)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=d477235d-60f4-420d-8161-82194b4e62e7&displaylang=ko)  
(KB2757638)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5&displaylang=ko)  
(KB2742597)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b&displaylang=ko)  
(KB2742601)  
(중요)  
[Microsoft .NET Framework 3.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791&displaylang=ko)  
(KB2756919)  
(심각도 없음<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0&displaylang=ko)  
(KB2742613)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8b1aef73-cfb2-4998-bca6-35cccfbb2078&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3107fadf-5ba8-48f6-bb23-0c0003b4ba76&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d&displaylang=ko)  
(KB2736416)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a35ccbff-c476-4ee2-be9c-5b6a4b1664e9&displaylang=ko)  
(KB2799329)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b427bace-5297-4593-9dd2-66847ae506c6&displaylang=ko)  
(KB2799329)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=873eba5d-5a8f-410e-bad8-e9d538acf1b3&displaylang=ko)  
(KB2757638)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)  
(KB2758694)  
(긴급)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=873eba5d-5a8f-410e-bad8-e9d538acf1b3&displaylang=ko)  
(KB2757638)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5&displaylang=ko)  
(KB2742597)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b&displaylang=ko)  
(KB2742601)  
(중요)  
[Microsoft .NET Framework 3.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791&displaylang=ko)  
(KB2756919)  
(심각도 없음<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0&displaylang=ko)  
(KB2742613)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4287381f-6f23-4a36-a7dc-f79c44bac124&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=098958e5-83cd-4ed2-b758-e970cef33325&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d&displaylang=ko)  
(KB2736416)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3ce450f1-f71f-4d5d-bf1c-db4742522d18&displaylang=ko)  
(KB2799329)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2d1266fc-f6b0-4062-9799-7b3721c2cf52&displaylang=ko)  
(KB2799329)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b&displaylang=ko)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=e6439fef-e5e7-479b-8fc4-daacf3a39f3a&displaylang=ko)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5&displaylang=ko)  
(KB2742597)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b&displaylang=ko)  
(KB2742601)  
(중요)  
[Microsoft .NET Framework 3.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791&displaylang=ko)  
(KB2756919)  
(심각도 없음<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0&displaylang=ko)  
(KB2742613)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c635ad51-4e15-461c-8927-a86d79f90b45&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b3ed781e-b740-4153-aaf3-daafdeb91004&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d&displaylang=ko)  
(KB2736416)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0f87dd60-92c2-444c-a9ea-dfeb106c88fa&displaylang=ko)  
(KB2799329)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2f71f8e6-309c-4bea-abde-d91040c46611&displaylang=ko)  
(KB2799329)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735&displaylang=ko)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735&displaylang=ko)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5&displaylang=ko)  
(KB2742597)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b&displaylang=ko)  
(KB2742601)  
(중요)  
[Microsoft .NET Framework 3.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791&displaylang=ko)  
(KB2756919)  
(심각도 없음<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0&displaylang=ko)  
(KB2742613)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eff3a82e-f3db-4733-95aa-a68621e27068&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4aa3e3a7-3ebc-4b47-ab62-c22243a4edcc&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d&displaylang=ko)  
(KB2736416)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e47425e9-f53e-4e20-a7ec-b4c552bd66eb)  
(KB2799329)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=c11ec9cd-1a85-4514-a1b9-9da5cdd0926b)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=c11ec9cd-1a85-4514-a1b9-9da5cdd0926b)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(중요)  
[Microsoft .NET Framework 3.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(심각도 없음<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d949fde9-31e7-4553-a34c-b41625a8cdc8)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ab117984-c4cb-473b-8c20-2b0d0409d8d6)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d20f50ed-89c3-48cb-a78d-a44470fa1285&displaylang=ko)  
(KB2799329)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=abbc3f31-e940-4750-acb6-5af477bc8390&displaylang=ko)  
(KB2769369)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b&displaylang=ko)  
(KB2758694)  
(긴급)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=3a160fc4-1bf0-4db2-aa8d-6ba4f07d196b&displaylang=ko)  
(KB2757638)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a&displaylang=ko)  
(KB2742598)  
(중요)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127&displaylang=ko)  
(KB2756920)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=057726d1-cdb4-4488-8cd8-822dabfc62a6&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=6120322b-7e04-4eeb-a9a4-11fe563a9f27&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4&displaylang=ko)  
(KB2736418)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d20f50ed-89c3-48cb-a78d-a44470fa1285&displaylang=ko)  
(KB2799329)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=abbc3f31-e940-4750-acb6-5af477bc8390&displaylang=ko)  
(KB2769369)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b&displaylang=ko)  
(KB2758694)  
(긴급)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=3a160fc4-1bf0-4db2-aa8d-6ba4f07d196b&displaylang=ko)  
(KB2757638)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0&displaylang=ko)  
(KB2742599)  
(중요)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3&displaylang=ko)  
(KB2756921)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0&displaylang=ko)  
(KB2742613)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=057726d1-cdb4-4488-8cd8-822dabfc62a6&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=6120322b-7e04-4eeb-a9a4-11fe563a9f27&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97&displaylang=ko)  
(KB2736422)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c113b67f-42ca-4fea-ba45-aba6f94de154&displaylang=ko)  
(KB2799329)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=1868c2ca-a184-494e-8eb3-82db45b08e32&displaylang=ko)  
(KB2769369)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23&displaylang=ko)  
(KB2757638)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)  
(KB2758694)  
(긴급)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23&displaylang=ko)  
(KB2757638)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a&displaylang=ko)  
(KB2742598)  
(중요)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127&displaylang=ko)  
(KB2756920)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=64249562-1fc3-436d-a9e1-4c9378b632d7&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=c9e2a55e-170f-4fe1-a306-eda676fd0fdb&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4&displaylang=ko)  
(KB2736418)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c113b67f-42ca-4fea-ba45-aba6f94de154&displaylang=ko)  
(KB2799329)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1868c2ca-a184-494e-8eb3-82db45b08e32&displaylang=ko)  
(KB2769369)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23&displaylang=ko)  
(KB2757638)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)  
(KB2758694)  
(긴급)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23&displaylang=ko)  
(KB2757638)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0&displaylang=ko)  
(KB2742599)  
(중요)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3&displaylang=ko)  
(KB2756921)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0&displaylang=ko)  
(KB2742613)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=64249562-1fc3-436d-a9e1-4c9378b632d7&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=c9e2a55e-170f-4fe1-a306-eda676fd0fdb&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97&displaylang=ko)  
(KB2736422)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d2fffc43-a88f-4fe5-9b24-5677258011b8&displaylang=ko)  
(KB2799329)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19&displaylang=ko)  
(KB2769369)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3&displaylang=ko)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3&displaylang=ko)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a&displaylang=ko)  
(KB2742598)  
(중요)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127&displaylang=ko)  
(KB2756920)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4&displaylang=ko)  
(KB2736418)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d2fffc43-a88f-4fe5-9b24-5677258011b8&displaylang=ko)  
(KB2799329)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19&displaylang=ko)  
(KB2769369)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3&displaylang=ko)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3&displaylang=ko)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0&displaylang=ko)  
(KB2742599)  
(중요)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3&displaylang=ko)  
(KB2756921)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>
(KB2742595)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0&displaylang=ko)  
(KB2742613)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97&displaylang=ko)  
(KB2736422)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=fbcee22b-9801-4c9e-ba0c-eb4a54526d38)  
(KB2799329)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=18070321-8635-4c2e-b9f9-0fc58c924136)  
(KB2769369)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(중요)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=12917b84-1f91-4c19-9197-a7d1e7adcdfc)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=86e5b2fc-f530-4259-af90-259b64fcdd73)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=fbcee22b-9801-4c9e-ba0c-eb4a54526d38)  
(KB2799329)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=18070321-8635-4c2e-b9f9-0fc58c924136)  
(KB2769369)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(중요)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=12917b84-1f91-4c19-9197-a7d1e7adcdfc)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=86e5b2fc-f530-4259-af90-259b64fcdd73)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b&displaylang=ko)  
(KB2758694)  
(긴급)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=e19d1373-a3f3-4f60-9142-c2484726aac8&displaylang=ko)  
(KB2757638)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998&displaylang=ko)  
(KB2742616)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e&displaylang=ko)  
(KB2756923)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a&displaylang=ko)  
(KB2742614)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 8(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=1f5441f1-a66d-42c0-bf0e-2f6867d4d43a&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 8(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=9f40864f-5347-44ef-bb08-afea45b5351b&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb&displaylang=ko)  
(KB2736693)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=c669190d-964c-42d3-b09d-40a397ae3a9c&displaylang=ko)  
(KB2757638)  
(긴급)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)  
(KB2758694)  
(긴급)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=c669190d-964c-42d3-b09d-40a397ae3a9c&displaylang=ko)  
(KB2757638)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998&displaylang=ko)  
(KB2742616)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e&displaylang=ko)  
(KB2756923)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a&displaylang=ko)  
(KB2742614)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 8(64비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=9d71dc77-9c01-4a1f-b403-8a18ca10979d&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 8(64비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=1b40baad-784a-4eba-a4ef-703250248057&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb&displaylang=ko)  
(KB2736693)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528&displaylang=ko)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528&displaylang=ko)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998&displaylang=ko)  
(KB2742616)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e&displaylang=ko)  
(KB2756923)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a&displaylang=ko)  
(KB2742614)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=2ad7872c-a387-41a1-8606-732a6ff0701d&displaylang=ko)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=4f0b9fb1-f1c4-4773-a956-94c8983c008a&displaylang=ko)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb&displaylang=ko)  
(KB2736693)  
(중요)  
[관리 OData IIS 확장](https://www.microsoft.com/download/details.aspx?familyid=77b6fb5f-10b8-4bc2-a5c3-97055c92acf1&displaylang=ko)  
(KB2753596)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
</td>
</tr>
<tr>
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
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0<sup>[1]</sup>
(KB2758694)  
(긴급)  
Microsoft XML Core Services 6.0<sup>[1]</sup>
(KB2757638)  
(긴급)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5<sup>[3]</sup>
(KB2742614)  
(중요)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Server Core 설치 옵션
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b&displaylang=ko)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=e6439fef-e5e7-479b-8fc4-daacf3a39f3a&displaylang=ko)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c635ad51-4e15-461c-8927-a86d79f90b45&displaylang=ko)(Server Core 설치)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b3ed781e-b740-4153-aaf3-daafdeb91004&displaylang=ko)(Server Core 설치)  
(KB2785220)  
(중요)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735&displaylang=ko)(Server Core 설치)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)(Server Core 설치)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735&displaylang=ko)(Server Core 설치)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eff3a82e-f3db-4733-95aa-a68621e27068&displaylang=ko)(Server Core 설치)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4aa3e3a7-3ebc-4b47-ab62-c22243a4edcc&displaylang=ko)(Server Core 설치)  
(KB2785220)  
(중요)
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
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19&displaylang=ko)(Server Core 설치)  
(KB2769369)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3&displaylang=ko)(Server Core 설치)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)(Server Core 설치)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3&displaylang=ko)(Server Core 설치)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a&displaylang=ko)(Server Core 설치)  
(KB2742598)  
(중요)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127&displaylang=ko)(Server Core 설치)  
(KB2756920)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5&displaylang=ko)(Server Core 설치)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e&displaylang=ko)(Server Core 설치)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4&displaylang=ko)(Server Core 설치)  
(KB2736418)  
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
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19&displaylang=ko)(Server Core 설치)  
(KB2769369)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3&displaylang=ko)(Server Core 설치)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)(Server Core 설치)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3&displaylang=ko)(Server Core 설치)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0&displaylang=ko)(Server Core 설치)  
(KB2742599)  
(중요)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3&displaylang=ko)(Server Core 설치)  
(KB2756921)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5&displaylang=ko)<sup>[1]</sup>(Server Core 설치)  
(KB2742595)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0&displaylang=ko)(Server Core 설치)  
(KB2742613)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5&displaylang=ko)(Server Core 설치)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e&displaylang=ko)(Server Core 설치)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97&displaylang=ko)(Server Core 설치)  
(KB2736422)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7&displaylang=ko)<sup>[1]</sup>(Server Core 설치)  
(KB2736428)  
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528&displaylang=ko)(Server Core 설치)  
(KB2757638)  
(보통)  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04&displaylang=ko)(Server Core 설치)  
(KB2758694)  
(보통)  
[Microsoft XML Core Services 6.0](https://www.microsoft.com/download/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528&displaylang=ko)(Server Core 설치)  
(KB2757638)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998&displaylang=ko)(Server Core 설치)  
(KB2742616)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e&displaylang=ko)(Server Core 설치)  
(KB2756923)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a&displaylang=ko)(Server Core 설치)  
(KB2742614)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=2ad7872c-a387-41a1-8606-732a6ff0701d&displaylang=ko)(Server Core 설치)  
(KB2778930)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=4f0b9fb1-f1c4-4773-a956-94c8983c008a&displaylang=ko)(Server Core 설치)  
(KB2785220)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb&displaylang=ko)(Server Core 설치)  
(KB2736693)  
(중요)  
[관리 OData IIS 확장](https://www.microsoft.com/download/details.aspx?familyid=77b6fb5f-10b8-4bc2-a5c3-97055c92acf1&displaylang=ko)(Server Core 설치)  
(KB2753596)  
(중요)
</td>
</tr>
</table>
 
MS13-002 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

<sup>[1]</sup>Windows RT 보안 업데이트는 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다.

MS13-004 참고 사항

<sup>[1]</sup>.NET Framework 4 and .NET Framework 4 Client Profile이 영향을 받습니다. .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4 및 .NET Framework 4 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4 Client Profile은 .NET Framework 4의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4 및 .NET Framework 4 Client Profile에 모두 영향을 줍니다. 자세한 내용은 MSDN 문서, [.NET Framework 설치](https://msdn.microsoft.com/ko-kr/library/5a4x27ek.aspx)를 참조하십시오.

<sup>[2]</sup>이 공지에서 설명한 취약점에 대해 알려진 공격 경로가 기본 구성으로 차단되므로 지정된 소프트웨어에 대한 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 심층적인 보안 대응책으로써 이 소프트웨어를 사용하는 고객은 이 보안 업데이트를 적용하는 것이 좋습니다.

<sup>[3]</sup>Windows RT 보안 업데이트는 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다.

MS13-005 참고 사항

<sup>[1]</sup>Windows RT 보안 업데이트는 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다.

MS13-006 참고 사항

<sup>[1]</sup>Windows RT 보안 업데이트는 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다.

MS13-007 참고 사항

<sup>[1]</sup>.NET Framework 4 and .NET Framework 4 Client Profile이 영향을 받습니다. .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4 및 .NET Framework 4 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4 Client Profile은 .NET Framework 4의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4 및 .NET Framework 4 Client Profile에 모두 영향을 줍니다. 자세한 내용은 MSDN 문서, [.NET Framework 설치](https://msdn.microsoft.com/ko-kr/library/5a4x27ek.aspx)를 참조하십시오.

#### Microsoft Office 제품군 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Office 제품군 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=d108d56c-f9fb-4823-b38e-3d2f838592de&displaylang=ko)  
(KB2760574)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11&displaylang=ko)  
(KB2687499)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11&displaylang=ko)  
(KB2687499)  
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
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11&displaylang=ko)  
(KB2687499)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11&displaylang=ko)  
(KB2687499)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11&displaylang=ko)  
(KB2687499)  
(긴급)
</td>
</tr>
</table>
 
MS13-002 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft 개발자 도구 및 소프트웨어

<p> </p>
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
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11&displaylang=ko)  
(KB2687499)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11&displaylang=ko)  
(KB2687499)  
(긴급)
</td>
</tr>
</table>
 
MS13-002 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Server 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-003](https://go.microsoft.com/fwlink/?linkid=261863)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 2(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6&displaylang=ko)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 2(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689&displaylang=ko)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6&displaylang=ko)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689&displaylang=ko)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-003](https://go.microsoft.com/fwlink/?linkid=261863)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689&displaylang=ko)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689&displaylang=ko)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft System Center Operations Manager
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-003](https://go.microsoft.com/fwlink/?linkid=261863)
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
Microsoft System Center Operations Manager 2007 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft System Center Operations Manager 2007 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=f848d74d-fdae-4a19-a0f5-12d2d4389db9&displaylang=ko)<sup>[1]</sup>
(KB2809182)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft System Center Operations Manager 2007 R2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft System Center Operations Manager 2007 R2](https://www.microsoft.com/download/details.aspx?familyid=4e1ab3bd-af0c-41f8-8ebc-1cdc68a3ee37&displaylang=ko)<sup>[1]</sup><sup>[2]</sup>
(KB2783850)  
(중요)
</td>
</tr>
</table>
 
MS13-002 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

MS13-003 참고 사항

<sup>[1]</sup>이 업데이트는 Microsoft 다운로드 센터에서만 다운로드할 수 있습니다.

<sup>[2]</sup>이 업데이트는 누적 업데이트로서 지정된 소프트웨어에 대한 이전의 누적 업데이트를 대체합니다.

검색, 배포 도구 및 지침
-----------------------


보안 센터

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](https://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security TechCenter](https://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [Microsoft 안전 및 보안 센터](https://go.microsoft.com/fwlink/?linkid=85102)를 방문하거나 "보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)을 참조하십시오.

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

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/systemcenter/bb545936)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](https://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) (영문)에 포함된 [UCE(Update Compatibility Evaluator)](https://technet.microsoft.com/library/cc749197) (영문)구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 버전에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 발표에서 사용할 수 없습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](https://technet.microsoft.com/wsus/bb456965). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](https://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

업데이트 관리 전략

[업데이트 관리를 위한 보안 가이드](https://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

기타 보안 관련 업데이트 받기

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS13-002에서 설명한 문제점을 보고해 주신 [Agarri](https://www.agarri.fr/)(영문)의 Nicolas Gregoire
-   MS13-003에서 설명한 문제점을 보고해주신 BAE Systems Detica의 Andy Yang
-   MS13-004에서 설명한 문제점을 보고해 주신 [iSIGHT Partners Labs](https://www.isightpartners.com/)(영문)의 Jon Erickson
-   MS13-004에서 설명한 두 가지 문제점을 [Tipping Point](https://www.tippingpoint.com/)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Vitaliy Toropov
-   MS13-004에서 설명한 문제점을 보고해 주신 Context Information Security의 James Forshaw
-   MS13-006에서 설명한 문제점을 보고해 주신 [Kenichiro Katayama](https://twitter.com/pin_ptr)(영문)
-   MS13-008에서 설명한 문제점을 해결하기 위해 협력해 주신 [Exodus Intelligence](https://www.exodusintel.com)(영문)

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](https://technet.microsoft.com/security/bb980617.aspx)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](https://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2013년 1월 8일): 공지 요약이 게시되었습니다.
-   V1.1(2013년 1월 8일): MS13-002에서 Windows Server 2008(32비트 시스템용) 서비스 팩 2에 설치된 Microsoft XML Core Services 4.0 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2의 Microsoft XML Core Services 6.0에 대한 영향을 받는 소프트웨어에 Server Core 설치 항목을 추가했습니다. 이 변경 사항은 정보에만 해당됩니다. 이미 시스템을 성공적으로 업데이트한 고객은 추가 조치를 취할 필요가 없습니다.
-   V2.0(2013년 1월 14일): Microsoft 보안 공지 MS13-008, Internet Explorer 보안 업데이트(2799329)가 추가되었으며, 이 부정기 보안 업데이트에 대한 공지 웹캐스트 링크가 추가되었습니다.
-   V3.0(2013년 1월 22일): MS13-004에서는 Microsoft는 잠재적인 호환성 문제를 가질 수 있다고 알려진 특정 구성을 실행하는 Windows 7 및 Windows Server 2008 R2 시스템에 대한 KB2756920 업데이트를 다시 제공하기 위해 이 공지를 다시 릴리스했습니다. 자세한 정보를 보려면 공지를 확인하십시오.
-   V4.0(2013년 3월 13일): MS13-003에서는 Microsoft System Center Operations Manager 2007 서비스 팩 1을 위한 업데이트를 알리기 위해 이 공지를 릴리스하였습니다. 다른 업데이트 패키지는 이 발표의 영향을 받지 않습니다. 자세한 정보를 보려면 공지를 확인하십시오.

*Built at 2014-04-18T12:27:44Z-07:00*
