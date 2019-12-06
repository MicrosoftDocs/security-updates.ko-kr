---
TOCTitle: 'MS13-FEB'
Title: 2013 년 2 월 Microsoft 보안 공지 요약
ms:assetid: 'ms13-feb'
ms:contentKeyID: 61230760
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms13-feb(v=Security.10)'
---

2013 년 2 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2013년 2월 13일 수요일 | 업데이트된 날짜: 2013년 2월 14일 목요일

**버전:** 1.2

이 공지 요약 목록에는 2013년 2월 발표된 보안 공지가 포함되어 있습니다.

2013년 2월 보안 공지 발표와 함께 이 공지 요약이 2013년 2월 7일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2013년 2월 13일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [2월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538626&culture=en-us). 이 날짜 이후 이 웹캐스트는 [주문형](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538626&culture=en-us)으로 제공됩니다.

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2792100)  <br />
<br />
이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 13건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275837">MS13-010</a></td>
<td style="border:1px solid black;">벡터 표시 언어의 취약점으로 인한 원격 코드 실행 문제점(2797052) <br />
<br />
이 보안 업데이트는 Microsoft의 VML(벡터 표시 언어) 구현에 대해 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=271307">MS13-011</a></td>
<td style="border:1px solid black;">미디어 압축 해제의 취약점으로 인한 원격 코드 실행 문제점(2780091)  <br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점 1건을 해결합니다. 이 취약점은 사용자가 특수하게 조작된 내장 미디어 파일을 포함하거나 특수하게 조작된 스트리밍 컨텐츠를 수신한 특수하게 조작된 미디어 파일(예: .mpg 파일), Microsoft Office 문서(예: .ppt 파일)를 열 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=279801">MS13-012</a></td>
<td style="border:1px solid black;">Microsoft Exchange Server의 취약점으로 인한 원격 코드 실행 문제점(2809279)  <br />
<br />
이 보안 업데이트는 Microsoft Exchange Server에서 발견되어 공개적으로 보고된 취약점을 해결합니다. 가장 심각한 취약점은 Microsoft Exchange Server WebReady 문서 보기에 있으며, 사용자가 OWA(Outlook Web App)를 사용하여 특수하게 조작된 파일을 미리보는 경우 Exchange 서버에 있는 코드 변환 서비스의 보안 컨텍스트에서 원격 코드를 실행하도록 허용할 수 있습니다. WebReady 문서 보기에 사용되는 Exchange에 있는 코드 변환 서비스는 LocalService 계정에서 실행되고 있습니다. LocalService 계정에는 로컬 컴퓨터의 최소 권한이 있으며 네트워크에서 익명 자격 증명을 제시합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Server 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=279005">MS13-020</a></td>
<td style="border:1px solid black;">OLE 자동화의 취약점으로 인한 원격 코드 실행 문제점(2802968)  <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows OLE(Object Linking and Embedding) 자동화의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=272434">MS13-013</a></td>
<td style="border:1px solid black;">FAST Search Server 2010 for SharePoint의 구문 분석 취약점으로 인한 원격 코드 실행 (2784242)  <br />
<br />
이 보안 업데이트는 Microsoft FAST Search Server 2010 for SharePoint의 공개된 취약점을 해결합니다. 이 취약점은 사용자 계정의 보안 컨텍스트에서 제한된 토큰으로 원격 코드를 실행하도록 허용할 수 있습니다. FAST Search Server for SharePoint는 Advanced Filter Pack을 사용하는 경우에만 이 문제의 영향을 받습니다. 기본적으로 Advanced Filter Pack은 사용되지 않습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office, <br />
Microsoft Server 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=276948">MS13-014</a></td>
<td style="border:1px solid black;">NFS 서버의 취약점으로 인한 서비스 거부 문제점 (2790978)  <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 공격자가 읽기 전용 공유에서 파일 작업을 수행하려고 하면 취약점으로 인해 서비스 거부 문제가 발생할 수 있습니다. 이 취약점을 악용하는 공격자는 영향을 받는 시스템에서 응답을 중지하거나 다시 시작하도록 만들 수 있습니다. 이 취약점은 NFS 역할이 활성화된 Windows 서버에만 영향을 줍니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275736">MS13-015</a></td>
<td style="border:1px solid black;">.NET Framework의 취약점으로 인한 권한 상승 문제점(2800277)  <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 .NET Framework의취약점 한 가지를 해결합니다. 이 취약점은 사용자가 XBAP(XAML 브라우저 응용 프로그램)를 실행할 수 있는 웹 브라우저를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 권한을 상승시킬 수 있습니다. 이 취약점은 CAS(코드 액세스 보안) 제한을 우회하기 위해 Windows .NET 응용 프로그램에서 사용될 수도 있습니다. 이 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Windows 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2778344) <br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 30건을 해결합니다. 공격자가 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">Windows 커널의 취약점으로 인한 권한 상승 문제점(2799494) <br />
이 보안 업데이트는 지원 대상인 모든 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 3건을 해결합니다. 공격자가 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278912">MS13-018</a></td>
<td style="border:1px solid black;">TCP/IP의 취약점으로 인한 서비스 거부 문제점(2790655)  <br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 인증되지 않은 공격자가 특수하게 조작된 연결 종료 패킷을 서버에 보낼 경우 서비스 거부가 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278896">MS13-019</a></td>
<td style="border:1px solid black;">Windows CSRSS(Client/Server Runtime Subsystem)의 취약점으로 인한 권한 상승 문제점(2790113)  <br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점을 해결합니다. 공격자가 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Shift JIS 문자 인코딩 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0015">CVE-2013-0015</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer SetCapture 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0018">CVE-2013-0018</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer COmWindowProxy 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0019">CVE-2013-0019</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer CMarkup 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0020">CVE-2013-0020</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer vtable 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0021">CVE-2013-0021</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer LsGetTrailInfo 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0022">CVE-2013-0022</a></td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer CDispNode 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0023">CVE-2013-0023</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer pasteHTML 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0024">CVE-2013-0024</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer SLayoutRun 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0025">CVE-2013-0025</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer InsertElement 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0026">CVE-2013-0026</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer CPasteCommand 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0027">CVE-2013-0027</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer CObjectElement 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0028">CVE-2013-0028</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer CHTML 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0029">CVE-2013-0029</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275837">MS13-010</a></td>
<td style="border:1px solid black;">VML 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0030">CVE-2013-0030</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">Microsoft는 이 취약점이 정보 유출 취약점으로, 제한적이며 대상이 일정한 공격에 악용되고 있다는 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=271307">MS13-011</a></td>
<td style="border:1px solid black;">미디어 압축 해제 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0077">CVE-2013-0077</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=279801">MS13-012</a></td>
<td style="border:1px solid black;">Oracle Outside In에 포함되어 있는 악용 가능한 여러 취약점</td>
<td style="border:1px solid black;">다수*</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">*여러 취약점에 대한 자세한 내용은 MS13-012 공지를 참조하십시오.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=272434">MS13-013</a></td>
<td style="border:1px solid black;">Oracle Outside In에 포함되어 있는 악용 가능한 여러 취약점</td>
<td style="border:1px solid black;">다수*</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">*여러 취약점에 대한 자세한 내용은 MS13-013 공지를 참조하십시오.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=276948">MS13-014</a></td>
<td style="border:1px solid black;">NULL 역참조 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1281">CVE-2013-1281</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275736">MS13-015</a></td>
<td style="border:1px solid black;">WinForms 콜백 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0073">CVE-2013-0073</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1248">CVE-2013-1248</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이는 최신 소프트웨어의 심층 보안 대응책입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1249">CVE-2013-1249</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이는 최신 소프트웨어의 심층 보안 대응책입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1250">CVE-2013-1250</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1251">CVE-2013-1251</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1252">CVE-2013-1252</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1253">CVE-2013-1253</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1254">CVE-2013-1254</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1255">CVE-2013-1255</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1256">CVE-2013-1256</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1257">CVE-2013-1257</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1258">CVE-2013-1258</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1259">CVE-2013-1259</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1260">CVE-2013-1260</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1261">CVE-2013-1261</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1262">CVE-2013-1262</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1263">CVE-2013-1263</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1264">CVE-2013-1264</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1265">CVE-2013-1265</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1266">CVE-2013-1266</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1267">CVE-2013-1267</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1268">CVE-2013-1268</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1269">CVE-2013-1269</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1270">CVE-2013-1270</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1271">CVE-2013-1271</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1272">CVE-2013-1272</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1273">CVE-2013-1273</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1274">CVE-2013-1274</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1275">CVE-2013-1275</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1276">CVE-2013-1276</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1277">CVE-2013-1277</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">커널 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1278">CVE-2013-1278</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">커널 경쟁 조건 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1279">CVE-2013-1279</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">Windows 커널 참조 수 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1280">CVE-2013-1280</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278912">MS13-018</a></td>
<td style="border:1px solid black;">TCP FIN WAIT 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0075">CVE-2013-0075</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278896">MS13-019</a></td>
<td style="border:1px solid black;">참조 수 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0076">CVE-2013-0076</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=279005">MS13-020</a></td>
<td style="border:1px solid black;">OLE 자동화 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1313">CVE-2013-1313</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
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
<th style="border:1px solid black;" colspan="11">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-009](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[MS13-010](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[MS13-011](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[MS13-020](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[MS13-014](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[MS13-015](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[MS13-016](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[MS13-017](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[MS13-018](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[MS13-019](https://go.microsoft.com/fwlink/?linkid=278896)
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
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=9bf087e7-4487-48bf-84e9-04b816411a0f&displaylang=ko)   
(KB2792100)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4501ef62-7d06-49b7-af86-c84e399e6275&displaylang=ko)  
(KB2792100)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2ab64eac-8ecf-4178-9a01-5f10fc2f049e&displaylang=ko)  
(KB2792100)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=daed0c2e-bd9a-4685-a5f9-1c01f7fdeccf&displaylang=ko)   
(KB2797052)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=fd693211-bcc8-4267-9aa1-86bac45e25bf&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e8924d23-f6e2-41bf-9542-f8991d084db9&displaylang=ko)  
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=95f5acea-32a0-42a5-a14d-837edf313984&displaylang=ko)   
(KB2780091)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=3a8ddbab-5999-48b7-9de8-423954f345b6)  
(KB2802968)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36&displaylang=ko)  
(KB2789643)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=cdaa7282-c354-4d70-938a-a025631205a2&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=9100bf70-8723-4635-9b78-f7c3048a950f&displaylang=ko)  
(KB2799494)    
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
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=c42347dd-5ec8-4760-a685-2cd7b6bb7bb2)   
(KB2792100)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6513176c-e9cb-4863-a228-5bc369135996)  
(KB2792100)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=25e15457-ffd2-4466-aff9-1d0830e967d7)  
(KB2792100)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=dd9383b9-a6df-44a7-bea9-8f7d088bc488)   
(KB2797052)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b042e717-bf4e-44a1-a1ba-6359bf551e8e)  
(KB2797052)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c8618c96-25c0-415b-b147-5713ec5ab5b1)  
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=06ef35a1-f76f-4e99-a8b2-6b086c7e51be)   
(KB2780091)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)   
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f72228df-8379-4bd9-b446-cb9505e9d228)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9a945336-b037-4ee6-9ea2-dfb885747b97)  
(KB2799494)    
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
<th style="border:1px solid black;" colspan="11">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-009](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[MS13-010](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[MS13-011](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[MS13-020](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[MS13-014](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[MS13-015](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[MS13-016](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[MS13-017](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[MS13-018](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[MS13-019](https://go.microsoft.com/fwlink/?linkid=278896)
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
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=35b58c7a-aae3-4445-957a-42ee708d77a5&displaylang=ko)   
(KB2792100)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3ee73b80-b8f6-4843-afba-41c7b55faf17&displaylang=ko)  
(KB2792100)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d67754e2-7ebd-484d-a008-ed8719e0c72d&displaylang=ko)  
(KB2792100)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=9b96ebfc-93e9-41bb-81f9-35c433ca5479&displaylang=ko)   
(KB2797052)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b902617d-1f35-4b17-9a44-235c0d3c27d2&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=47ca5d22-b957-4ac9-91e9-c440b0614728&displaylang=ko)  
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=e3b0b928-0f76-4b51-871a-aeda2ee3b7d5&displaylang=ko)   
(KB2780091)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36&displaylang=ko)  
(KB2789643)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8daebdb5-eba2-4685-b781-ead5c2185548&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c005c0a0-4025-4a07-a76d-c57ed5afbd68&displaylang=ko)  
(KB2799494)    
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
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=075de724-b996-413f-8ff3-74f435d94b9b&displaylang=ko)   
(KB2792100)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a90d6861-7ff6-4501-9200-f72b5a9f1817&displaylang=ko)  
(KB2792100)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=319a7a93-c03e-4c0b-a5c4-6a4f379d781e&displaylang=ko)  
(KB2792100)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=b3ca28b1-9d3c-4df5-b8d7-f31d70f6e714&displaylang=ko)   
(KB2797052)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e13c9366-9cb6-4e62-bf6c-a09fe7842463&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=80aab9c7-4511-4d44-b570-c77cdb50e542&displaylang=ko)  
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=493377a4-4ce2-4dd9-ba84-090466248669&displaylang=ko)   
(KB2780091)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36&displaylang=ko)  
(KB2789643)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e7d03ef2-517b-4442-a968-5aaa300dd2ba&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dc004424-61f9-49ed-9cb3-b89ed9e98aef&displaylang=ko)  
(KB2799494)    
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
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=92ce1fa1-4b12-4fd5-9a02-21fc9b119fb9)   
(KB2792100)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5965ce09-c5d7-4072-bad3-df46f9b76478)  
(KB2792100)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=63791740-00e2-4569-967e-36086efe6ca6)   
(KB2797052)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d1a9b2b2-191c-4ffe-9c8a-8ef641a45eb7)  
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=8e9a09fd-f360-4471-ac89-481dc2935cec)   
(KB2780091)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=2a3039a4-9b46-4db8-a539-07d52bbf1b92)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=3cad66f1-6651-4948-9579-9df050fdaa1b)  
(KB2799494)    
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
<th style="border:1px solid black;" colspan="11">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-009](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[MS13-010](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[MS13-011](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[MS13-020](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[MS13-014](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[MS13-015](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[MS13-016](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[MS13-017](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[MS13-018](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[MS13-019](https://go.microsoft.com/fwlink/?linkid=278896)
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
<td style="border:1px solid black;">
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=eea43429-2691-4a31-a640-d74035145d2d&displaylang=ko)  
(KB2792100)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5c195229-8e63-4fff-a304-13c13b2fa132&displaylang=ko)  
(KB2792100)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7f7ce868-28ce-497e-882f-3abfdd9b89e8&displaylang=ko)   
(KB2792100)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4f946407-cd81-48b5-a279-1ab81388b70b&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e0cfc24f-293c-4817-a69c-f9cfd514e1c1&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=4fab0417-5c9a-4e5d-864d-b1b3bee6fc89&displaylang=ko)   
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=d730eacf-e30a-45aa-89da-dfec5e87906a&displaylang=ko)   
(KB2780091)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477&displaylang=ko)  
(KB2789646)   
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)    
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139&displaylang=ko)  
(KB2789648)   
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0ff0475c-cc1b-4886-971e-1a71e6b311c3&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4de1249f-012e-47cb-ad08-4fd5bddb0879&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=80b766e7-3b7f-4d04-9a80-71864a13df8c&displaylang=ko)  
(KB2790655)    
(보통)
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=308d99ff-7575-4d70-958f-0d57fd6bffab&displaylang=ko)  
(KB2792100)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d9d4987e-95ad-4246-a52b-7ac859a40e67&displaylang=ko)  
(KB2792100)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=74b370c0-29f5-4acb-a3cd-bd2c2b708bb7&displaylang=ko)   
(KB2792100)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6ffb3215-1c90-4eb2-9143-0866efc98374&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=649dbf4e-654b-48a2-bd35-2df7f34fbb56&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=44fbe00c-eeb4-4a80-a934-7ce58c02d6ec&displaylang=ko)   
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=4cd6b10c-b310-4aee-bbca-f23049c14455&displaylang=ko)   
(KB2780091)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477&displaylang=ko)  
(KB2789646)   
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)    
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139&displaylang=ko)  
(KB2789648)   
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e5043a08-a9e4-422b-8455-80a5091d38b9&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=448ac43a-0a6f-4049-be2b-c853b5dbfab3&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=92bad797-5b66-422c-a096-8070d02bb8b2&displaylang=ko)  
(KB2790655)    
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="11">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-009](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[MS13-010](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[MS13-011](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[MS13-020](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[MS13-014](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[MS13-015](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[MS13-016](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[MS13-017](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[MS13-018](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[MS13-019](https://go.microsoft.com/fwlink/?linkid=278896)
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
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=71c805ed-a68b-4d3e-97ca-922557cfbf67&displaylang=ko)  
(KB2792100)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=775ea105-4a71-4b7b-9dc0-50f1eecab96d&displaylang=ko)  
(KB2792100)  
(보통)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=ccdf8abc-9657-4aff-8d73-4824a558c168&displaylang=ko)   
(KB2792100)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d432acb3-10a0-4f4c-a793-381aedd4bdd1&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b91ce04a-a464-4388-9386-54dd2815b8dd&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=58f0810c-f253-4740-ac9f-75b8a4506b06&displaylang=ko)   
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=86cc3b51-818a-49a6-abab-488ac316e021&displaylang=ko)   
(KB2780091)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477&displaylang=ko)  
(KB2789646)   
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)    
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139&displaylang=ko)  
(KB2789648)   
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=850e319f-dd6e-4480-86c3-a5129f084817&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6d7a74c8-de4b-4bcb-8b3f-581858d0776b&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c24aa6f3-82a5-4b1f-adc8-4aece948161c&displaylang=ko)  
(KB2790655)    
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=de1b96b7-a5ac-4a39-9808-c00c6b1a4325&displaylang=ko)  
(KB2792100)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e5775802-e529-4894-b1cf-2839948706c2&displaylang=ko)  
(KB2792100)  
(보통)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=51df1e78-f014-4492-8a3d-83b3c821458b&displaylang=ko)   
(KB2792100)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=152f90b3-efae-42e6-a845-59052383a8a0&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=304ac41e-b4e5-4bf8-94d2-f2bd9a07bcff&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7b85336a-d3f7-4077-b6eb-55b3042f5335&displaylang=ko)   
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=fe239f9b-d986-4828-a01d-8abd494037ec&displaylang=ko)   
(KB2780091)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477&displaylang=ko)  
(KB2789646)   
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)    
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139&displaylang=ko)  
(KB2789648)   
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8978769b-447b-4b01-848a-cbcdf692f17a&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c9fbb7cc-c33b-4af9-8416-9d16015e79c1&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2738fbe4-2163-4e77-82e6-208a7a08a70c&displaylang=ko)  
(KB2790655)    
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=61c1964f-9307-4128-9470-bcb20e07856b)  
(KB2792100)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1a2af9dc-e9a7-477e-9943-8132eb7fea81)  
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=4b3e48e3-0dbe-449b-9bca-0ba8bbdcbab0)   
(KB2780091)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)   
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0f84e24c-43f4-4851-932c-8849171b2505)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f3e18038-b8a1-4eba-9542-8396903a3709)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c269c175-f47c-456a-9360-f38bbdfd7ed0)  
(KB2790655)    
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="11">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-009](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[MS13-010](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[MS13-011](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[MS13-020](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[MS13-014](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[MS13-015](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[MS13-016](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[MS13-017](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[MS13-018](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[MS13-019](https://go.microsoft.com/fwlink/?linkid=278896)
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
<td style="border:1px solid black;">
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4df9414b-02da-4254-ab29-5091151e2900&displaylang=ko)  
(KB2792100)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b21bd7b3-2eb8-433a-b6c2-8243c5128038&displaylang=ko)   
(KB2792100)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d7d64177-deec-4fd3-9716-b7816fe3c623&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=04a101c6-d553-426f-b3cd-412eefeec580&displaylang=ko)   
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9&displaylang=ko)  
(KB2789644)    
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=631adede-ba0f-461f-85e1-82b60a7efec1&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=912ac2e1-e737-43fb-acc8-a01a918a8475&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=cb4270c4-cec5-49e0-a56b-97539d6352a0&displaylang=ko)  
(KB2790655)    
(보통)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d4d02ef9-b0a4-46a3-ad92-7508aa26ad3b&displaylang=ko)  
(KB2790113)    
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4df9414b-02da-4254-ab29-5091151e2900&displaylang=ko)  
(KB2792100)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b21bd7b3-2eb8-433a-b6c2-8243c5128038&displaylang=ko)   
(KB2792100)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d7d64177-deec-4fd3-9716-b7816fe3c623&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=04a101c6-d553-426f-b3cd-412eefeec580&displaylang=ko)   
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062&displaylang=ko)  
(KB2789645)    
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)    
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139&displaylang=ko)  
(KB2789648)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=631adede-ba0f-461f-85e1-82b60a7efec1&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=912ac2e1-e737-43fb-acc8-a01a918a8475&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=cb4270c4-cec5-49e0-a56b-97539d6352a0&displaylang=ko)  
(KB2790655)    
(보통)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=d4d02ef9-b0a4-46a3-ad92-7508aa26ad3b&displaylang=ko)  
(KB2790113)    
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6ef9cbf9-d131-420d-b566-6b0f94f2e1c1&displaylang=ko)  
(KB2792100)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=4b2402ff-035a-47c4-b982-00d428eab379&displaylang=ko)   
(KB2792100)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d503795a-b1a3-48dc-b1e6-27628aeb150a&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=36eb59be-6703-40c0-b01c-0fffb1456719&displaylang=ko)   
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9&displaylang=ko)  
(KB2789644)    
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=8dab3aca-fde1-4bd9-b82a-e4805a2e8d39&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=0d1601cc-fb76-4276-bf0b-a46b7f8055ae&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=5d93cb19-7854-4b49-9743-8d6a11be2dd6&displaylang=ko)  
(KB2790655)    
(보통)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=77277398-c5b4-4ba4-8425-465710b0bef2&displaylang=ko)  
(KB2790113)    
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6ef9cbf9-d131-420d-b566-6b0f94f2e1c1&displaylang=ko)  
(KB2792100)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=4b2402ff-035a-47c4-b982-00d428eab379&displaylang=ko)   
(KB2792100)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d503795a-b1a3-48dc-b1e6-27628aeb150a&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=36eb59be-6703-40c0-b01c-0fffb1456719&displaylang=ko)   
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062&displaylang=ko)  
(KB2789645)    
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)    
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139&displaylang=ko)  
(KB2789648)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=8dab3aca-fde1-4bd9-b82a-e4805a2e8d39&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=0d1601cc-fb76-4276-bf0b-a46b7f8055ae&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5d93cb19-7854-4b49-9743-8d6a11be2dd6&displaylang=ko)  
(KB2790655)    
(보통)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=77277398-c5b4-4ba4-8425-465710b0bef2&displaylang=ko)  
(KB2790113)    
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="11">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-009](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[MS13-010](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[MS13-011](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[MS13-020](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[MS13-014](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[MS13-015](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[MS13-016](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[MS13-017](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[MS13-018](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[MS13-019](https://go.microsoft.com/fwlink/?linkid=278896)
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
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e7b455a3-6a44-430c-a7d1-30c03ef7f141&displaylang=ko)  
(KB2792100)  
(보통)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7e9d97f2-c006-4e5a-bc80-10450069b8c5&displaylang=ko)   
(KB2792100)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7a36109b-f1e2-4cde-9ede-9f7449c5412c&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=be2fd20a-4c37-47a6-a322-e16acd99db2c&displaylang=ko)   
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4&displaylang=ko)  
(KB2790978)   
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9&displaylang=ko)  
(KB2789644)    
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01&displaylang=ko)  
(KB2790655)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab&displaylang=ko)  
(KB2790113)    
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e7b455a3-6a44-430c-a7d1-30c03ef7f141&displaylang=ko)  
(KB2792100)  
(보통)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7e9d97f2-c006-4e5a-bc80-10450069b8c5&displaylang=ko)   
(KB2792100)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7a36109b-f1e2-4cde-9ede-9f7449c5412c&displaylang=ko)  
(KB2797052)  
(긴급)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=be2fd20a-4c37-47a6-a322-e16acd99db2c&displaylang=ko)   
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4&displaylang=ko)  
(KB2790978)    
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062&displaylang=ko)  
(KB2789645)    
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(KB2789642)    
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139&displaylang=ko)  
(KB2789648)   
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036&displaylang=ko)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01&displaylang=ko)  
(KB2790655)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab&displaylang=ko)  
(KB2790113)    
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c1eb941e-833d-46f0-bf65-d9701d67bc20)  
(KB2792100)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c2e1c1b3-5b75-47cf-91d5-82d413b358e6)  
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=8e37196c-2f43-457d-8d87-336d8775c0bf)  
(KB2790978)    
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)    
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=99320f36-1481-446c-bc3e-d33fcfd1f2c1)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=9f0b132a-8616-49cd-8927-393f35d0cf21)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=e1be5dea-dd13-42b5-a37f-4bcd828cc65f)  
(KB2790655)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=9fbc37dd-53ec-4de1-b1c1-9761a8f83ab8)  
(KB2790113)    
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c1eb941e-833d-46f0-bf65-d9701d67bc20)  
(KB2792100)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c2e1c1b3-5b75-47cf-91d5-82d413b358e6)  
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=8e37196c-2f43-457d-8d87-336d8775c0bf)  
(KB2790978)    
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)    
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=99320f36-1481-446c-bc3e-d33fcfd1f2c1)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=9f0b132a-8616-49cd-8927-393f35d0cf21)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=e1be5dea-dd13-42b5-a37f-4bcd828cc65f)  
(KB2790655)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=9fbc37dd-53ec-4de1-b1c1-9761a8f83ab8)  
(KB2790113)    
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="11">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-009](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[MS13-010](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[MS13-011](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[MS13-020](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[MS13-014](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[MS13-015](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[MS13-016](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[MS13-017](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[MS13-018](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[MS13-019](https://go.microsoft.com/fwlink/?linkid=278896)
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
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=7966de38-c6a6-4137-8b7e-8ccd3306521a&displaylang=ko)   
(KB2792100)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=0389b515-59bf-4733-aab4-ffb822efdbea&displaylang=ko)   
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014&displaylang=ko)  
(KB2789650)    
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0&displaylang=ko)  
(KB2789649)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 8(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d5395864-1822-4151-a10c-f6a036f8853f&displaylang=ko)  
(KB2778344)    
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 8(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=5b74e5b3-7b8d-4669-b403-c776e70bf072&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 8(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=e7739ba6-9c62-4180-a095-47fdb6c741e9&displaylang=ko)  
(KB2790655)    
(보통)
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
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=d6720d21-269b-4605-b95e-573bc327afd9&displaylang=ko)   
(KB2792100)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=c1859853-d43f-4497-b212-e6a4daa43485&displaylang=ko)   
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014&displaylang=ko)  
(KB2789650)    
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0&displaylang=ko)  
(KB2789649)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 8(64비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=79aaaa3a-747a-4320-9fd2-5f4a6de3d13c&displaylang=ko)  
(KB2778344)    
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 8(64비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=a41a2b38-5e5c-48bc-8727-e19402519f12&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows 8(64비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=dd2042b8-c784-4dfc-8fca-61905693cda5&displaylang=ko)  
(KB2790655)    
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="11">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-009](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[MS13-010](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[MS13-011](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[MS13-020](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[MS13-014](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[MS13-015](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[MS13-016](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[MS13-017](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[MS13-018](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[MS13-019](https://go.microsoft.com/fwlink/?linkid=278896)
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
없음
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
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=8e3fdcd0-ab75-4500-aac7-7ecb4f39fca7&displaylang=ko)   
(KB2792100)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=3b39813e-5ee2-412e-b1f1-a16617a70f43&displaylang=ko)   
(KB2797052)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=b284296a-1db5-47dc-af2c-bf55d0ad09e6&displaylang=ko)  
(KB2790978)   
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014&displaylang=ko)  
(KB2789650)    
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0&displaylang=ko)  
(KB2789649)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=aac38d33-fad6-4060-bad4-61cf7c059af9&displaylang=ko)  
(KB2778344)    
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=4e427f56-436e-43d0-b4f8-eee8427b3741&displaylang=ko)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=f74a104d-4749-4dd5-b144-2e4ce9c284a2&displaylang=ko)  
(KB2790655)    
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="11">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-009](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[MS13-010](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[MS13-011](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[MS13-020](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[MS13-014](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[MS13-015](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[MS13-016](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[MS13-017](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[MS13-018](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[MS13-019](https://go.microsoft.com/fwlink/?linkid=278896)
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
없음
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
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](https://go.microsoft.com/fwlink/?linkid=21140)
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
Internet Explorer 10<sup>[1]</sup>   
(KB2792100)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[1]</sup>   
(KB2797052)  
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
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2778344)  
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2799494)  
(중요)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2790655)   
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="11">
Server Core 설치 옵션
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-009](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[MS13-010](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[MS13-011](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[MS13-020](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[MS13-014](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[MS13-015](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[MS13-016](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[MS13-017](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[MS13-018](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[MS13-019](https://go.microsoft.com/fwlink/?linkid=278896)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=850e319f-dd6e-4480-86c3-a5129f084817&displaylang=ko)(Server Core 설치)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6d7a74c8-de4b-4bcb-8b3f-581858d0776b&displaylang=ko)(Server Core 설치)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c24aa6f3-82a5-4b1f-adc8-4aece948161c&displaylang=ko)(Server Core 설치)  
(KB2790655)    
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
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8978769b-447b-4b01-848a-cbcdf692f17a&displaylang=ko)(Server Core 설치)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c9fbb7cc-c33b-4af9-8416-9d16015e79c1&displaylang=ko)(Server Core 설치)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2738fbe4-2163-4e77-82e6-208a7a08a70c&displaylang=ko)(Server Core 설치)  
(KB2790655)    
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4&displaylang=ko)(Server Core 설치)  
(KB2790978)    
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9&displaylang=ko)(Server Core 설치)  
(KB2789644)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036&displaylang=ko)(Server Core 설치)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb&displaylang=ko)(Server Core 설치)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01&displaylang=ko)(Server Core 설치)  
(KB2790655)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab&displaylang=ko)(Server Core 설치)  
(KB2790113)    
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4&displaylang=ko)(Server Core 설치)  
(KB2790978)    
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062&displaylang=ko)(Server Core 설치)  
(KB2789645)    
(중요)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05&displaylang=ko)<sup>[1]</sup>
(Server Core 설치)(KB2789642)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139&displaylang=ko)(Server Core 설치)  
(KB2789648)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036&displaylang=ko)(Server Core 설치)  
(KB2778344)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb&displaylang=ko)(Server Core 설치)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01&displaylang=ko)(Server Core 설치)  
(KB2790655)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab&displaylang=ko)(Server Core 설치)  
(KB2790113)    
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=b284296a-1db5-47dc-af2c-bf55d0ad09e6&displaylang=ko)(Server Core 설치)  
(KB2790978)   
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014&displaylang=ko)(Server Core 설치)  
(KB2789650)    
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0&displaylang=ko)(Server Core 설치)  
(KB2789649)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=aac38d33-fad6-4060-bad4-61cf7c059af9&displaylang=ko)(Server Core 설치)  
(KB2778344)    
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=4e427f56-436e-43d0-b4f8-eee8427b3741&displaylang=ko)(Server Core 설치)  
(KB2799494)    
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=f74a104d-4749-4dd5-b144-2e4ce9c284a2&displaylang=ko)(Server Core 설치)  
(KB2790655)    
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
MS13-009, MS13-010, MS13-017, MS13-018 참고 사항

<sup>[1]</sup>Windows RT 보안 업데이트는 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다.

MS13-015 참고 사항

<sup>[1]</sup>.NET Framework 4 및 .NET Framework 4 Client Profile이 영향을 받습니다. .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4 및 .NET Framework 4 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4 Client Profile은 .NET Framework 4의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4 및 .NET Framework 4 Client Profile에 모두 영향을 줍니다. 자세한 내용은 MSDN 문서, [.NET Framework 설치](https://msdn.microsoft.com/ko-kr/library/5a4x27ek.aspx)를 참조하십시오.

MS13-016 참고 사항

<sup>[1]</sup>Windows RT 보안 업데이트는 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다.

<sup>[2]</sup>지정된 소프트웨어에 대한 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 심층적인 보안 대응책으로써 이 소프트웨어를 사용하는 고객은 이 보안 업데이트를 적용하는 것이 좋습니다.

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
[MS13-012](https://go.microsoft.com/fwlink/?linkid=279801)
</td>
<td style="border:1px solid black;">
[MS13-013](https://go.microsoft.com/fwlink/?linkid=272434)
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
Microsoft Exchange Server 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=316a1aff-b72d-4d96-8ee5-bd86b0e29e6f&displaylang=ko)   
(KB2788321)   
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=498e7612-73b5-4e28-99a4-b3157ac69932&displaylang=ko)   
(KB2746164)   
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft FAST Search Server 2010 for SharePoint
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-012](https://go.microsoft.com/fwlink/?linkid=279801)
</td>
<td style="border:1px solid black;">
[MS13-013](https://go.microsoft.com/fwlink/?linkid=272434)
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
Microsoft FAST Search Server 2010 for SharePoint 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Advanced Filter Pack](https://www.microsoft.com/download/details.aspx?familyid=0ae86754-69a8-4c82-855c-2ee2b7887fa5&displaylang=ko)<sup>[1]</sup>   
(KB2553234)  
(중요)
</td>
</tr>
</table>
 
MS13-013 참고 사항

<sup>[1]</sup>이 업데이트는 Microsoft 다운로드 센터에서만 다운로드할 수 있습니다

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

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)(영문)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/systemcenter/bb545936)(영문)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](https://go.microsoft.com/fwlink/?linkid=33341)(영문)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)(영문)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971)(영문)에 포함된 [UCE(Update Compatibility Evaluator)](https://technet.microsoft.com/library/cc749197)(영문) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

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

-   MS13-009에서 설명한 문제점을 보고해 주신 Masato Kinugawa
-   MS13-009에서 설명한 문제점을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Omair](https://krash.in/)(영문)
-   MS13-009에서 설명한 문제점을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 SkyLined
-   MS13-009에서 설명한 문제점을 Exodus Intelligence와 협력하여 보고해 주신 Arthur Gerkis
-   MS13-009에서 설명한 문제점 2건을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하며 보고해 주신 [Harmony Security](https://www.harmonysecurity.com)(영문)의 Stephen Fewer
-   MS13-009에서 설명한 문제점을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com)
-   MS13-009에서 설명한 문제점을 보고해 주신 Tencent PC Manager
-   MS13-009에서 설명한 문제점을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Arthur Gerkis
-   MS13-009에서 설명한 문제점을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   MS13-009에서 설명한 문제점 2개를 보고해 주신 [Security-Assessment.com](https://www.security-assessment.com)(영문)의 Scott Bell
-   MS13-009에서 설명한 문제점을 Exodus Intelligence와 협력하여 보고해 주신 Yenteasy Security Research의 Jose A Vazquez
-   MS13-009에서 설명한 문제점을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Yenteasy Security Research의 Jose A Vazquez
-   MS13-009에 설명되어 있는 문제점을 보고해 주신 IBM X-Force의 Mark Yason
-   MS13-009에 포함된 심층 보안 변경 사항에 대해 협력해 주신 [NCC Group](https://www.nccgroup.com/)(영문)의 Ollie Whitehouse
-   MS13-011에 설명된 문제점을 보고해 주신 [Tencent Security Team](https://security.tencent.com/)(영문)
-   MS13-015에서 설명한 문제점을 보고해 주신 [Context Information Security](https://www.contextis.com/)(영문)의 James Forshaw
-   MS13-016에서 설명한 문제점 2개를 보고해 주신 [Google Inc](https://www.google.com) 및 [Tencent Security Team](https://security.tencent.com/)(영문)의 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/)(영문)
-   MS13-016에서 설명한 문제점 25개를 보고해 주신 Google Inc의 [Gynvael Coldwind](https://j00ru.vexillium.org/)(영문)와 [Mateusz "j00ru" Jurczyk](https://www.google.com/)(영문)
-   MS13-016에서 설명한 문제점 3개를 보고해 주신 [Google Inc](https://www.google.com)의 [Gynvael Coldwind](https://gynvael.coldwind.pl/)(영문)와 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/)(영문)
-   MS13-017에서 설명한 문제점 2개를 보고해 주신 [Google Inc](https://www.google.com)의 [Gynvael Coldwind](https://gynvael.coldwind.pl/)(영문)와 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/)(영문)
-   MS13-019에서 설명한 문제점을 해결하기 위해 협력해 주신 Max DeLiso
-   MS13-020에서 설명한 문제점을 [HP](https://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](https://technet.microsoft.com/security/bb980617.aspx)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](https://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2013년 2월 13일): 공지 요약이 게시되었습니다.
-   V1.1(2013년 2월 13일): MS13-009에서 CVE-2013-0022의 악용 가능성 인덱스의 최신 소프트웨어 버전에 대한 악용 가능성 평가를 수정했습니다.
-   V1.2(2013년 2월 14일): MS13-014에서 CVE-2013-1281의 악용 가능성 인덱스의 최신 소프트웨어 버전에 대한 악용 가능성 평가를 수정했습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
