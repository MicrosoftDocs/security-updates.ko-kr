---
TOCTitle: 'MS14-MAY'
Title: 2014년 5월 Microsoft 보안 공지 요약
ms:assetid: 'ms14-may'
ms:contentKeyID: 62246741
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms14-may(v=Security.10)'
---

2014년 5월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2014년 5월 2일 | 업데이트된 날짜: 2014년 5월 14일

**버전:** 2.0

이 공지 요약 목록에는 2014년 5월 발표된 보안 공지가 포함되어 있습니다.

2014년 5월 보안 공지 발표와 함께 이 공지 요약이 2014년 5월 8일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2014년 5월 14일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [5월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572979&culture=en-us).

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향을 받는 소프트웨어**를 참조하십시오.

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=397669"><strong>MS14-021</strong></a><br />
(2014년 5월 1일 부정기 릴리스)</td>
<td style="border:1px solid black;"><strong>Internet Explorer 보안 업데이트(2965111)<br />
<br />
</strong>이 보안 업데이트는 Internet Explorer의 공개된 취약점을 해결합니다. 이 취약점은 사용자가 영향을 받는 버전의 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=395261"><strong>MS14-029</strong></a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 보안 업데이트(2962482)</strong><br />
<br />
이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점들은 모두 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server의 취약점으로 인한 원격 코드 실행 문제점(2952166)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office 서버 및 생산성 소프트웨어에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 인증된 공격자가 대상 SharePoint 서버에 특수하게 조작된 페이지를 보내는 경우 이러한 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Server 소프트웨어,<br />
생산성 소프트웨어</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393745"><strong>MS14-023</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점(2961037)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 특수하게 조작된 라이브러리 파일과 동일한 네트워크 디렉터리에 있는 Office 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396820"><strong>MS14-025</strong></a></td>
<td style="border:1px solid black;"><strong>그룹 정책 기본 설정 취약점으로 인한 권한 상승 문제점(2962486)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점을 해결합니다. Active Directory 그룹 정책 기본 설정을 사용하여 도메인 전체에서 암호를 배포하는 경우 이 취약점으로 인해 권한 상승이 허용되어 공격자가 그룹 정책 기본 설정에 저장된 암호를 검색하고 해독할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396825"><strong>MS14-026</strong></a></td>
<td style="border:1px solid black;"><strong>.NET Framework의 취약점으로 인한 권한 상승 문제점(2958732)<br />
</strong><br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft .NET Framework의 취약점을 해결합니다. 이 취약점으로 인해 인증되지 않은 공격자가 특수하게 조작한 데이터를 .NET Remoting을 사용하는 영향을 받는 워크스테이션 또는 서버로 전송할 경우 권한 상승이 허용될 수 있습니다. .NET Remoting은 응용 프로그램에서 광범위하게 사용되고 있습니다. .NET Remoting을 사용하도록 특수하게 설계된 사용자 지정 응용 프로그램만 시스템을 이 취약점에 노출시킬 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396823"><strong>MS14-027</strong></a></td>
<td style="border:1px solid black;"><strong>Windows 셸 처리기의 취약점으로 인한 권한 상승 문제점(2962488)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 ShellExecute를 사용하는 특수하게 조작된 응용 프로그램을 사용할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온 할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393744"><strong>MS14-028</strong></a></td>
<td style="border:1px solid black;"><strong>iSCSI의 취약점으로 인한 서비스 거부 문제점(2962485)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점으로 인해 공격자가 대량의 특수하게 조작된 iSCSI 패킷을 대상 네트워크로 보낼 경우 서비스 거부가 발생할 수 있습니다. 이 취약점은 iSCSI 대상 역할이 사용된 서버에만 영향을 줍니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396835"><strong>MS14-024</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft 공용 컨트롤의 취약점으로 인한 보안 기능 우회(2961033)</strong><br />
<br />
이 보안 업데이트는 MSCOMCTL 공용 컨트롤 라이브러리의 구현에서 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 Internet Explorer와 같이 COM 구성 요소를 인스턴스화 할 수 있는 웹 브라우저에서 특수하게 조작된 웹 페이지를 볼 경우 보안 기능 우회가 허용될 수 있습니다. 웹 검색을 통한 공격의 경우, 이 취약점 악용에 성공한 공격자는 다양한 취약점 클래스로부터 사용자를 보호해 주는 ASLR(Address Space Layout Randomization) 보안 기능을 우회할 수 있습니다. 보안 기능을 우회하는 것만으로는 임의의 코드 실행이 허용되지 않지만 공격자는 이 ASLR 우회 취약점을 다른 취약점 즉, ASLR 우회를 통해 임의의 코드를 실행할 수 있는 원격 코드 실행 취약점 등과 함께 사용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
 
  
악용 가능성 인덱스  
------------------
  
<span id="sectionToggle1"></span>
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.
  
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
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><strong>취약점 제목</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>최신 소프트웨어 버전에 대한 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>이전 소프트웨어 버전에 대한 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>서비스 거부 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>주요 정보</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=397669"><strong>MS14-021</strong></a><br />
(2014년 5월 1일 부정기 릴리스)</td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1776">CVE-2014-1776</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다. 이 취약점은 <a href="https://technet.microsoft.com/library/security/2963983">Microsoft 보안 권고 2963983</a>에서 처음 설명되었습니다.<br />
<br />
Microsoft는 Internet Explorer에서 이 취약점을 악용하려는 제한적이며 대상이 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></td>
<td style="border:1px solid black;">SharePoint 페이지 콘텐츠 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0251">CVE-2014-0251</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></td>
<td style="border:1px solid black;">SharePoint XSS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1754">CVE-2014-1754</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></td>
<td style="border:1px solid black;">Web Applications 페이지 콘텐츠 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1813">CVE-2014-1813</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393745"><strong>MS14-023</strong></a></td>
<td style="border:1px solid black;">Microsoft Office 중국어 문법 검사 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1756">CVE-2014-1756</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393745"><strong>MS14-023</strong></a></td>
<td style="border:1px solid black;">토큰 재사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1808">CVE-2014-1808</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396835"><strong>MS14-024</strong></a></td>
<td style="border:1px solid black;">MSCOMCTL ASLR 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1809">CVE-2014-1809</a></td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 보안 기능 우회 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396820"><strong>MS14-025</strong></a></td>
<td style="border:1px solid black;">그룹 정책 기본 설정 암호 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1812">CVE-2014-1812</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396825"><strong>MS14-026</strong></a></td>
<td style="border:1px solid black;">TypeFilterLevel 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1806">CVE-2014-1806</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396823"><strong>MS14-027</strong></a></td>
<td style="border:1px solid black;">Windows 셸 파일 연결 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1807">CVE-2014-1807</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">Microsoft는 이 취약점을 악용하려는 제한적인 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393744"><strong>MS14-028</strong></a></td>
<td style="border:1px solid black;">iSCSI 대상 원격 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0255">CVE-2014-0255</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393744"><strong>MS14-028</strong></a></td>
<td style="border:1px solid black;">iSCSI 대상 원격 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0256">CVE-2014-0256</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=395261"><strong>MS14-029</strong></a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0310">CVE-2014-0310</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=395261"><strong>MS14-029</strong></a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1815">CVE-2014-1815</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">Microsoft는 Internet Explorer에서 이 취약점을 악용하려는 제한적인 공격에 대한 보고를 받았습니다.</td>
</tr>
</tbody>
</table>
  
영향을 받는 소프트웨어  
----------------------
  
<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
### Windows 운영 체제 및 구성 요소

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

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
**없음**

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
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
(긴급)  
Internet Explorer 7  
(2964358)  
(긴급)  
Internet Explorer 8  
(2964358)  
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
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
(긴급)  
Internet Explorer 7  
(2964358)  
(긴급)  
Internet Explorer 8  
(2964358)  
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
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

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
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
(보통)  
Internet Explorer 7  
(2964358)  
(보통)  
Internet Explorer 8  
(2964358)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2953522)  
(보통)  
Internet Explorer 7   
(2953522)  
(보통)  
Internet Explorer 8   
(2953522)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2931352)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2932079)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
(보통)  
Internet Explorer 7  
(2964358)  
(보통)  
Internet Explorer 8  
(2964358)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2953522)  
(보통)  
Internet Explorer 7   
(2953522)  
(보통)  
Internet Explorer 8   
(2953522)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2932079)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2926765)  
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
Internet Explorer 6  
(2964358)  
(보통)  
Internet Explorer 7  
(2964358)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2953522)  
(보통)  
Internet Explorer 7   
(2953522)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2932079)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
(긴급)  
Internet Explorer 8  
(2964358)  
(긴급)  
Internet Explorer 9  
(2964358)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
(긴급)  
Internet Explorer 8  
(2953522)  
(긴급)  
Internet Explorer 9  
(2953522)  
(긴급)

</td>
<td style="border:1px solid black;">
원격 서버 관리 도구  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2931354)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)  
Microsoft .NET Framework 4.5  
(2931368)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2926765)  
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
Internet Explorer 7  
(2964358)  
(긴급)  
Internet Explorer 8  
(2964358)  
(긴급)  
Internet Explorer 9  
(2964358)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
(긴급)  
Internet Explorer 8  
(2953522)  
(긴급)  
Internet Explorer 9  
(2953522)  
(긴급)

</td>
<td style="border:1px solid black;">
원격 서버 관리 도구  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2931354)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)  
Microsoft .NET Framework 4.5  
(2931368)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
(보통)  
Internet Explorer 8  
(2964358)  
(보통)  
Internet Explorer 9  
(2964358)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
(보통)  
Internet Explorer 8  
(2953522)  
(보통)  
Internet Explorer 9  
(2953522)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2931354)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)  
Microsoft .NET Framework 4.5  
(2931368)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
(보통)  
Internet Explorer 8  
(2964358)  
(보통)  
Internet Explorer 9  
(2964358)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
(보통)  
Internet Explorer 8  
(2953522)  
(보통)  
Internet Explorer 9  
(2953522)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2931354)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)  
Microsoft .NET Framework 4.5  
(2931368)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2931354)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2964358)  
(긴급)  
Internet Explorer 9  
(2964358)  
(긴급)  
Internet Explorer 10  
(2964358)  
(긴급)  
Internet Explorer 11  
(2964358)  
(긴급)  
Internet Explorer 11  
(2964444)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
(긴급)  
Internet Explorer 9  
(2953522)  
(긴급)  
Internet Explorer 10  
(2953522)  
(긴급)  
Internet Explorer 11  
(2953522)  
(긴급)  
Internet Explorer 11  
(2961851)  
(긴급)

</td>
<td style="border:1px solid black;">
원격 서버 관리 도구  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)  
Microsoft .NET Framework 4.5  
(2931368)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2964358)  
(긴급)  
Internet Explorer 9  
(2964358)  
(긴급)  
Internet Explorer 10  
(2964358)  
(긴급)  
Internet Explorer 11  
(2964358)  
(긴급)  
Internet Explorer 11  
(2964444)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
(긴급)  
Internet Explorer 9  
(2953522)  
(긴급)  
Internet Explorer 10  
(2953522)  
(긴급)  
Internet Explorer 11  
(2953522)  
(긴급)  
Internet Explorer 11  
(2961851)  
(긴급)

</td>
<td style="border:1px solid black;">
원격 서버 관리 도구  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)  
Microsoft .NET Framework 4.5  
(2931368)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2964358)  
(보통)  
Internet Explorer 9  
(2964358)  
(보통)  
Internet Explorer 10  
(2964358)  
(보통)  
Internet Explorer 11  
(2964358)  
(보통)  
Internet Explorer 11  
(2964444)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
(보통)  
Internet Explorer 9  
(2953522)  
(보통)  
Internet Explorer 10  
(2953522)  
(보통)  
Internet Explorer 11  
(2953522)  
(보통)  
Internet Explorer 11  
(2961851)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)  
Microsoft .NET Framework 4.5  
(2931368)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
iSCSI Software Target 3.3  
(2933826)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2964358)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 10  
(2964358)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
(긴급)

</td>
<td style="border:1px solid black;">
원격 서버 관리 도구  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931357)  
(중요)  
Microsoft .NET Framework 4.5  
(2931367)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931367)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2964358)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
(긴급)

</td>
<td style="border:1px solid black;">
원격 서버 관리 도구  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931357)  
(중요)  
Microsoft .NET Framework 4.5  
(2931367)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931367)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2964358)  
(긴급)  
Internet Explorer 11  
(2964444)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
(긴급)  
Internet Explorer 11  
(2961851)  
(긴급)

</td>
<td style="border:1px solid black;">
원격 서버 관리 도구  
(2928120)  
(중요)  
원격 서버 관리 도구  
(2961899)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931358)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931366)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2926765)  
(중요)  
Windows 8.1(32비트 시스템용)  
(2962123)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2964358)  
(긴급)  
Internet Explorer 11  
(2964444)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
(긴급)  
Internet Explorer 11  
(2961851)  
(긴급)

</td>
<td style="border:1px solid black;">
원격 서버 관리 도구  
(2928120)  
(중요)  
원격 서버 관리 도구  
(2961899)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931358)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931366)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2926765)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(2962123)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 10  
(2964358)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2928120)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931357)  
(중요)  
Microsoft .NET Framework 4.5  
(2931367)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931367)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2933826)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2964358)  
(보통)  
Internet Explorer 11  
(2964444)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
(보통)  
Internet Explorer 11  
(2961851)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2928120)  
(중요)  
Windows Server 2012 R2  
(2961899)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931358)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931366)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2926765)  
(중요)  
Windows Server 2012 R2  
(2962123)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2933826)  
(중요)  
Windows Server 2012 R2  
(2962073)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2964358)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2931367)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931367)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2964358)  
(긴급)  
Internet Explorer 11  
(2964444)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
(긴급)  
Internet Explorer 11  
(2961851)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1  
(2931366)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2926765)  
(중요)  
Windows RT 8.1  
(2962123)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

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
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
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
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

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
(2931356)  
(중요)  
Microsoft .NET Framework 4  
(2931365)  
(중요)  
Microsoft .NET Framework 4.5  
(2931368)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

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
Microsoft .NET Framework 3.5  
(2931357)  
(중요)  
Microsoft .NET Framework 4.5  
(2931367)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931367)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2926765)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2933826)  
(중요)

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
Microsoft .NET Framework 3.5  
(2931358)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2931366)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(2926765)  
(중요)  
Windows Server 2012 R2(Server Core 설치)  
(2962123)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(2933826)  
(중요)  
Windows Server 2012 R2(Server Core 설치)  
(2962073)  
(중요)

</td>
</tr>
</table>
 
 

### Office 제품군 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-023**](http://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](http://go.microsoft.com/fwlink/?linkid=396835)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3(교정 도구)  
(2767772)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3(mscomct2)  
(2596804)  
(중요)  
Microsoft Office 2007 서비스 팩 3(mscomctlocx)  
(2817330)  
(중요)  
Microsoft Office 2007 서비스 팩 3(msaddndr)  
(2880508)  
(중요)  
Microsoft Office 2007 서비스 팩 3(msstdfmt)  
(2880507)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-023**](http://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](http://go.microsoft.com/fwlink/?linkid=396835)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)(교정 도구)  
(2878284)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)(mscomct2)  
(2589288)  
(중요)  
Microsoft Office 2010 서비스 팩 1(32비트 에디션)(mscomctlocx)  
(2810073)  
(중요)  
Microsoft Office 2010 서비스 팩 1(32비트 에디션)(msaddndr)  
(2880971)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)(교정 도구)  
(2878284)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)(mscomct2)  
(2589288)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 에디션)(mscomctlocx)  
(2810073)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 에디션)(msaddndr)  
(2880971)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)(교정 도구)  
(2878284)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)(mscomct2)  
(2589288)  
(중요)  
Microsoft Office 2010 서비스 팩 1(64비트 에디션)(msaddndr)  
(2880971)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)(교정 도구)  
(2878284)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)(mscomct2)  
(2589288)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 에디션)(msaddndr)  
(2880971)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 및 Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-023**](http://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](http://go.microsoft.com/fwlink/?linkid=396835)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 에디션)(교정 도구)  
(2880463)  
(중요)  
Microsoft Office 2013(32비트 에디션)(mso)  
(2878316)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 에디션)(mscomct2)  
(2760272)  
(중요)  
Microsoft Office 2013(32비트 에디션)(mscomctlocx)  
(2880502)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 에디션)(교정 도구)  
(2880463)  
(중요)  
Microsoft Office 2013 서비스 팩 1(32비트 에디션)(mso)(2878316)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 에디션)(mscomct2)  
(2760272)  
(중요)  
Microsoft Office 2013 서비스 팩 1(32비트 에디션)(mscomctlocx)  
(2880502)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 에디션)(교정 도구)  
(2880463)  
(중요)  
Microsoft Office 2013(64비트 에디션)(mso)  
(2878316)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 에디션)(mscomct2)  
(2760272)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 에디션)(교정 도구)  
(2880463)  
(중요)  
Microsoft Office 2013 서비스 팩 1(64비트 에디션)(mso)  
(2878316)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 에디션)(mscomct2)  
(2760272)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-023**](http://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](http://go.microsoft.com/fwlink/?linkid=396835)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT(교정 도구)  
(2880463)  
(중요)  
Microsoft Office 2013 RT(mso)  
(2878316)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT(mscomct2)  
(2760272)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(교정 도구)  
(2880463)  
(중요)  
Microsoft Office 2013 RT 서비스 팩 1(mso)  
(2878316)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1(mscomct2)  
(2760272)  
(중요)

</td>
</tr>
</table>
 
 

### Microsoft Server 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 서비스 팩 3(32비트 버전)  
(2837616)  
(긴급)  
SharePoint Server 2007(32비트 에디션)(dlcapp)  
(2596902)  
(긴급)  
SharePoint Server 2007(32비트 에디션)(dlc)  
(2596763)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 서비스 팩 3(64비트 버전)  
(2837616)  
(긴급)  
SharePoint Server 2007(64비트 에디션)(dlcapp)  
(2596902)  
(긴급)  
SharePoint Server 2007(64비트 에디션)(dlc)  
(2596763)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 서비스 팩 1(wss)  
(2837588)  
(긴급)  
Microsoft SharePoint Server 2010 서비스 팩 1(coreserver)  
(2837598)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 서비스 팩 2(wss)  
(2837588)  
(긴급)  
Microsoft SharePoint Server 2010 서비스 팩 2(coreserver)  
(2837598)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013(sts)  
(2863856)  
(긴급)  
Microsoft SharePoint Foundation 2013(wssloc)  
(2863863)  
(긴급)  
Microsoft SharePoint Server 2013(coreserverloc)  
(2863829)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 서비스 팩 1(sts)  
(2863856)  
(긴급)  
Microsoft SharePoint Foundation 2013 서비스 팩 1(wssloc)  
(2863863)  
(긴급)  
Microsoft SharePoint Server 2013 서비스 팩 1(coreserver)  
(2863829)  
(긴급)

</td>
</tr>
</table>
 
**MS14-022 참고 사항**

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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2010 서비스 팩 1  
(2863922)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2010 서비스 팩 2  
(2863922)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2013  
(2760236)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2013 서비스 팩 1  
(2760236)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 서비스 팩 1  
(2880536)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 서비스 팩 2  
(2880536)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2880453)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1  
(2880453)  
(긴급)

</td>
</tr>
</table>
 
**MS14-022 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

### 생산성 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SharePoint Server 2013 클라이언트 구성 요소 SDK**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
SharePoint Server 2013 클라이언트 구성 요소 SDK(32비트 버전)

</td>
<td style="border:1px solid black;">
SharePoint Server 2013 클라이언트 구성 요소 SDK(32비트 버전)  
(2863854)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
SharePoint Server 2013 클라이언트 구성 요소 SDK(64비트 버전)

</td>
<td style="border:1px solid black;">
SharePoint Server 2013 클라이언트 구성 요소 SDK(64비트 버전)  
(2863854)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Designer 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2007 서비스 팩 3(ewd)  
(2596861)  
(긴급)  
Microsoft SharePoint Designer 2007 서비스 팩 3(spd)  
(2596810)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Designer 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 서비스 팩 1(32비트 버전)  
(2810069)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 서비스 팩 2(32비트 버전)  
(2810069)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 서비스 팩 1(64비트 버전)  
(2810069)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 서비스 팩 2(64비트 버전)  
(2810069)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft SharePoint Designer 2013**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013(32비트 버전)(spdcore)  
(2752096)  
(긴급)  
Microsoft SharePoint Designer 2013(32비트 버전)(spd)  
(2863836)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 서비스 팩1(32비트 버전)(spdcore)  
(2752096)  
(긴급)  
Microsoft SharePoint Designer 2013 서비스 팩1(32비트 버전)(spd)  
(2863836)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013(64비트 버전)(spdcore)  
(2752096)  
(긴급)  
Microsoft SharePoint Designer 2013(64비트 버전)(spd)  
(2863836)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 서비스 팩1(64비트 버전)(spdcore)  
(2752096)  
(긴급)  
Microsoft SharePoint Designer 2013 서비스 팩1(64비트 버전)(spd)  
(2863836)  
(긴급)

</td>
</tr>
</table>
 
**MS14-022 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

검색, 배포 도구 및 지침
-----------------------

<span id="sectionToggle3"></span>
관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 존재합니다.

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 구성 오류를 검색할 수 있습니다.

WSUS(Windows Server Update Services), SMS(Systems Management Server), System Center Configuration Manager는 관리자가 보안 업데이트를 배포하는 데 도움이 됩니다.

ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](http://technet.microsoft.com/security/cc297183)를 참조하십시오. 

감사의 말
---------

<span id="sectionToggle4"></span>
고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

**MS14-021**

-   Internet Explorer 메모리 손상 취약점(CVE-2014-1776)에 대해 Microsoft와 협력해 주신 [FireEye Inc.](http://www2.fireeye.com/)(영문)

     

**MS14-023**

-   Microsoft Office 중국어 문법 검사 취약점(CVE-2014-1756)에 대해 보고해 주신 [NSFOCUS Security Team](http://www.nsfocus.com/)(영문)
-   토큰 재사용 취약점(CVE-2014-1808)을 보고해 주신 [ANSSI](http://www.ssi.gouv.fr/en/)(영문)의 Arnaud Maillet

     

**MS14-026**

-   TypeFilterLevel 취약점(CVE-2014-1806)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw

     

**MS14-028**

-   iSCSI 대상 원격 서비스 거부 취약점(CVE-2014-0255)을 보고해 주신 Beyond Security의 [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html)(영문) 프로젝트와 협력하고 계신 익명의 연구자
-   iSCSI 대상 원격 서비스 거부 취약점(CVE-2014-0256)을 보고해 주신 Beyond Security의 [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html)(영문) 프로젝트와 협력하고 계신 익명의 연구자

     

**MS14-029**

-   Internet Explorer 메모리 손상 취약점(CVE-2014-0310)을 보고해 주신 [Google Security Team](http://www.google.com/)의 Fermin J. Serna
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0310)을 [HP(영문)](http://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1815)을 보고해 주신 [Google Security Team](http://www.google.com/)의 Clément Lecigne

     

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 버전에서 Microsoft는 Windows 업데이트, Microsoft 업데이트, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 발표에서 사용할 수 없습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows 업데이트 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/wsus/bb456965). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft 업데이트](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows 업데이트를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)(영문)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.

IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617)

Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)

국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 개정 내역

-   V1.0(2014년 5월 2일): 공지 요약이 게시되었습니다.
-   V2.0(2014년 5월 14일): Microsoft 보안 공지 MS13-022를 MS13-029를 통해 추가하였으며 5월 14일 웹캐스트의 공지 웹캐스트 링크를 추가했습니다.

*2014년 5월 9일 18:42Z-07:00에 페이지가 생성되었습니다.*
