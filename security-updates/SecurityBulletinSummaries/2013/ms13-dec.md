---
TOCTitle: 'MS13-DEC'
Title: 2013년 12월 Microsoft 보안 공지 요약
ms:assetid: 'ms13-dec'
ms:contentKeyID: 61230759
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms13-dec(v=Security.10)'
---

2013년 12월 Microsoft 보안 공지 요약
====================================

게시된 날짜: 2013년 12월 10일

**버전:** 1.0

이 공지 요약 목록에는 2013년 12월에 발표된 보안 공지가 포함되어 있습니다.

2013년 12월 보안 공지 발표와 함께 이 공지 요약이 2013년 12월 5일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2013년 12월 11일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [12월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557386&culture=en-us).

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
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><strong>공지 제목 및 용약</strong></td>
<td style="border:1px solid black;"><strong>최대 심각도 및 취약점 영향</strong></td>
<td style="border:1px solid black;"><strong>다시 시작 요구 사항</strong></td>
<td style="border:1px solid black;"><strong>영향을 받는 소프트웨어</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344108">MS13-096</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics Component의 취약점으로 인한 원격 코드 실행 문제점(2908005)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows, Microsoft Office, Microsoft Lync의 공개된 취약점을 해결합니다. 취약점으로 인해 사용자가 특수하게 조작된 TIFF 파일이 포함된 공유 콘텐츠를 볼 경우 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office,<br />
Microsoft Lync</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(2898785)</strong><br />
<br />
이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 7건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 가장 위험한 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325389">MS13-098</a></td>
<td style="border:1px solid black;"><strong>Windows의 취약점으로 인한 원격 코드 실행 문제점(2893294)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 사용자나 응용 프로그램이 영향을 받는 시스템에서 특수하게 조작되고 서명된 이식 가능한 실행(PE) 파일을 실행 또는 설치할 경우 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344112">MS13-099</a></td>
<td style="border:1px solid black;"><strong>Microsoft Scripting Runtime 개체 라이브러리의 취약점으로 인한 원격 코드 실행 문제점(2909158)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 사용자를 특수하게 조작된 웹 사이트나 특수하게 조작된 콘텐츠를 호스팅하는 웹 사이트를 방문하도록 유도할 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server의 취약점으로 인한 원격 코드 실행 문제점(2915705)</strong><br />
<br />
이 보안 업데이트는 Microsoft Exchange Server의 공개된 취약점 3건과 비공개적으로 보고된 취약점 1건을 해결합니다. Microsoft Exchange Server의 WebReady 문서 보기 및 데이터 손실 방지 기능에 이 중 가장 심각한 취약점이 있습니다. 공격자가 영향을 받는 Exchange 서버 사용자에게 특수하게 조작된 파일이 포함된 전자 메일 메시지를 보낸 경우 이러한 취약점은 LocalService 계정의 보안 컨텍스트에서 원격 코드 실행을 허용할 수 있습니다. LocalService 계정에는 로컬 시스템의 최소 권한이 있으며 네트워크에서 익명 자격 증명을 제시합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329771">MS13-100</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server의 취약점으로 인한 원격 코드 실행 문제점(2904244)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office 서버 소프트웨어에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 인증된 공격자가 SharePoint 서버에 특수하게 조작된 페이지를 보내는 경우 이러한 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 성공적으로 악용한 공격자는 대상 SharePoint 사이트의 W3WP 서비스 계정의 보안 컨텍스트에서 임의의 코드를 실행할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft SharePoint</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2880430)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 5건을 해결합니다. 가장 위험한 취약점으로 인해 공격자가 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344110">MS13-102</a></td>
<td style="border:1px solid black;"><strong>LRPC 클라이언트의 취약점으로 인한 권한 상승 문제점(2898715)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 공격자가 LRPC 서버를 스푸핑하여 특수하게 조작된 LPC 포트 메시지를 LRPC 클라이언트로 보내는 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 프로그램을 설치하거나 데이터를 보고 변경하거나 삭제하고 모든 관리자 권한이 있는 새 계정을 만들 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329969">MS13-103</a></td>
<td style="border:1px solid black;"><strong>ASP.NET SignalR의 취약점으로 인한 권한 상승 문제점(2905244)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 ASP.NET SignalR의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 JavaScript를 대상 사용자의 브라우저에 리플렉션할 경우 권한을 상승시킬 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft 개발자 도구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=330934">MS13-104</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office의 취약점으로 인한 정보 유출 문제점(2909976)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 악의적인 웹 사이트에서 호스팅되는 Office 파일을 열 경우 정보 유출이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 대상 SharePoint 사이트 또는 다른 Microsoft Office 서버 사이트에서 현재 사용자 인증에 사용되는 액세스 토큰을 확인할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329967">MS13-106</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 공유 구성 요소의 취약점으로 인한 보안 기능 우회<br />
(2905238)</strong><br />
<br />
이 보안 업데이트는 현재 악용되고 있는 Microsoft Office의 공유 구성 요소의 공개된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 Internet Explorer와 같이 COM 구성 요소를 인스턴스화할 수 있는 웹 브라우저에서 특수하게 조작된 웹 페이지를 볼 경우 보안 기능 우회가 허용될 수 있습니다. 웹 검색을 통한 공격의 경우, 이 취약점 악용에 성공한 공격자는 다양한 취약점 클래스로부터 사용자를 보호해 주는 ASLR(Address Space Layout Randomization) 보안 기능을 우회할 수 있습니다. 보안 기능을 우회하는 것만으로는 임의의 코드 실행이 허용되지 않지만 공격자는 이 ASLR 우회 취약점을 다른 취약점 즉, ASLR 우회를 통해 임의의 코드를 실행할 수 있는 원격 코드 실행 취약점 등과 함께 사용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
 
  
악용 가능성 인덱스  
------------------
  
<span id="sectionToggle1"></span>
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](https://technet.microsoft.com/security/cc998259)를 참조하십시오.
  
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344108">MS13-096</a></td>
<td style="border:1px solid black;">Microsoft 그래픽 구성 요소 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3906">CVE-2013-3906</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
Microsoft는 Microsoft Office 제품에서 이 취약점을 악용하려는 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5045">CVE-2013-5045</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5046">CVE-2013-5046</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5047">CVE-2013-5047</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5048">CVE-2013-5048</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5049">CVE-2013-5049</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5051">CVE-2013-5051</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5052">CVE-2013-5052</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325389">MS13-098</a></td>
<td style="border:1px solid black;">WinVerifyTrust 서명 유효성 검사 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3900">CVE-2013-3900</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">Microsoft는 이 취약점을 악용하려는 대상이 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344112">MS13-099</a></td>
<td style="border:1px solid black;">Microsoft Scripting Runtime 개체 라이브러리의 메모리 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5056">CVE-2013-5056</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329771">MS13-100</a></td>
<td style="border:1px solid black;">SharePoint 페이지 콘텐츠 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5059">CVE-2013-5059</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3899">CVE-2013-3899</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3902">CVE-2013-3902</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">TrueType 글꼴 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3903">CVE-2013-3903</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">포트 클래스 드라이버 이중 페치 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3907">CVE-2013-3907</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k 정수 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5058">CVE-2013-5058</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344110">MS13-102</a></td>
<td style="border:1px solid black;">LRPC 클라이언트 버퍼 오버런 취약점 </td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3878">CVE-2013-3878</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329969">MS13-103</a></td>
<td style="border:1px solid black;">SignalR XSS 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5042">CVE-2013-5042</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=330934">MS13-104</a></td>
<td style="border:1px solid black;">토큰 가로채기 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5054">CVE-2013-5054</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.<br />
<br />
Microsoft는 이 취약점을 악용하려는 제한적이며 대상이 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">MAC 비활성화 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1330">CVE-2013-1330</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">Oracle Outside In에 포함되어 있는 악용 가능한 여러 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5763">CVE-2013-5763</a><br />
<br />
및<br />
<br />
<a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5791">CVE-2013-5791</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">OWA XSS 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5072">CVE-2013-5072</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329967">MS13-106</a></td>
<td style="border:1px solid black;">HXDS ASLR 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5057">CVE-2013-5057</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 보안 기능 우회 취약점입니다.<br />
<br />
이 취약점은 공개되었습니다.<br />
<br />
Microsoft는 이 취약점을 악용하려는 제한적이며 대상이 일정한 공격에 대한 보고를 받았습니다.</td>
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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(긴급)  
Internet Explorer 7   
(2898785)  
(긴급)  
Internet Explorer 8   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.7  
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(2893984)  
(중요)

</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(2898715)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(긴급)  
Internet Explorer 7   
(2898785)  
(긴급)  
Internet Explorer 8   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.6  
(2892076)  
(긴급)  
Windows Script 5.7   
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2893984)  
(중요)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2898715)  
(중요)

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(보통)  
Internet Explorer 7  
(2898785)  
(중요)  
Internet Explorer 8  
(2898785)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(긴급)  
Windows Script 5.7   
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2893984)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2898715)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(보통)  
Internet Explorer 7  
(2898785)  
(중요)  
Internet Explorer 8  
(2898785)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(긴급)  
Windows Script 5.7   
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2893984)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2898715)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(보통)  
Internet Explorer 7  
(2898785)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(긴급)  
Windows Script 5.7   
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2893984)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2898715)  
(중요)

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista 서비스 팩 2  
(2901674)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(긴급)  
Internet Explorer 8  
(2898785)  
(긴급)  
Internet Explorer 9   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2893984)  
(보통)  
Windows Vista 서비스 팩 2  
(2887069)  
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
Windows Vista x64 Edition 서비스 팩 2  
(2901674)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(긴급)  
Internet Explorer 8  
(2898785)  
(긴급)  
Internet Explorer 9   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2893984)  
(보통)  
Windows Vista x64 Edition 서비스 팩 2  
(2887069)  
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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2901674)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(중요)  
Internet Explorer 8  
(2898785)  
(중요)  
Internet Explorer 9   
(2898785)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2893984)  
(보통)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2887069)  
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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2901674)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(중요)  
Internet Explorer 8  
(2898785)  
(중요)  
Internet Explorer 9   
(2898785)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2893984)  
(보통)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2887069)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2901674)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2893984)  
(보통)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2887069)  
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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

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
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(긴급)  
Internet Explorer 9   
(2898785)  
(긴급)  
Internet Explorer 10   
(2898785)  
(긴급)  
Internet Explorer 11   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2893984)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(2887069)  
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
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(긴급)  
Internet Explorer 9   
(2898785)  
(긴급)  
Internet Explorer 10   
(2898785)  
(긴급)  
Internet Explorer 11   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2893984)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2887069)  
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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(중요)  
Internet Explorer 9   
(2898785)  
(중요)  
Internet Explorer 10   
(2898785)  
(중요)  
Internet Explorer 11   
(2898785)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2893984)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2887069)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2893984)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2887069)  
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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

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
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2893984)  
(보통)  
Windows 8(32비트 시스템용)  
(2887069)  
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
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2893984)  
(보통)  
Windows 8(x64 기반 시스템용)  
(2887069)  
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
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2893984)  
(보통)

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
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2893984)  
(보통)

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

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
Internet Explorer 10   
(2898785)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2893984)  
(보통)  
Windows Server 2012  
(2887069)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2893984)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

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
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(2893984)  
(보통)  
Windows RT  
(2887069)  
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
해당 사항 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2893984)  
(보통)

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2901674)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2893984)  
(보통)

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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2901674)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2893984)  
(보통)

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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2893984)  
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
Windows Server 2012(Server Core 설치)  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2893984)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

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
Windows Server 2012 R2(Server Core 설치)  
(2893294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(2893984)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
</table>
 
**MS13-096 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

### Microsoft Office 제품군 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Office 2003 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3(2850047)  
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
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(2817641)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(2850022)  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)  
(2817670)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)  
(2850016)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)  
(2817670)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)  
(2850016)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)  
(2817670)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)  
(2850016)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)  
(2817670)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)  
(2850016)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

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
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 에디션)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 에디션)  
(2850064)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 에디션)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 에디션)  
(2850064)  
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
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2850064)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**기타 Office 소프트웨어**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(2817641)  
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
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2850047)  
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
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2817641)  
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
Microsoft PowerPoint 2010 Viewer 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer 서비스 팩 1  
(2817670)  
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
Microsoft PowerPoint 2010 Viewer 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer 서비스 팩 2  
(2817670)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
</table>
 
**MS13-096 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

### Microsoft Server 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

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
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013(coreserverloc)  
(2850058)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 서비스 팩 3  
(2903911)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 서비스 팩 2  
(2903903)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 서비스 팩 3  
(2905616)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 2  
(2880833)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 3  
(2880833)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
</table>
 
**MS13-100 참고 사항**

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
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2553298)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2553298)  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2837629)  
(중요)  
Excel Services  
(2837631)  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2910228)  
(중요)

</td>
</tr>
</table>
 
**MS13-100 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

### Microsoft 통신 플랫폼 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)  
(2899397)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)  
(2899397)  
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
(2899393)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)  
(2899395)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013(32비트)  
(2850057)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013(32비트)  
(2850057)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013(64비트)  
(2850057)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013  
(64비트)  
(2850057)  
(중요)

</td>
</tr>
</table>
 
**MS13-096 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

### Microsoft 개발자 도구 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**ASP.NET**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-103**](https://go.microsoft.com/fwlink/?linkid=329969)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET SignalR

</td>
<td style="border:1px solid black;">
ASP.NET SignalR 1.1.x   
(2903919)  
(중요)  
ASP.NET SignalR 2.0.x   
(2903919)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Visual Studio Team Foundation Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS13-103**](https://go.microsoft.com/fwlink/?linkid=329969)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2013   
(2903566)  
(중요)

</td>
</tr>
</table>
 
 

검색, 배포 도구 및 지침
-----------------------

<span id="sectionToggle3"></span>
관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 존재합니다.

-   관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 구성 오류를 검색할 수 있습니다.
-   WSUS(Windows Server Update Services), SMS(Systems Management Server), System Center Configuration Manager는 관리자가 보안 업데이트를 배포하는 데 도움이 됩니다.
-   ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](https://technet.microsoft.com/security/cc297183)를 참조하십시오. 

감사의 말
---------

<span id="sectionToggle4"></span>
고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://go.microsoft.com/fwlink/?linkid=21127)드립니다.

**MS13-096**

-   Microsoft 그래픽 구성 요소 메모리 손상 취약점(CVE-2013-3906)을 보고해 주신 McAfee Labs IPS Team의 Haifei Li

**MS13-097**

-   Internet Explorer 권한 상승 취약점(CVE-2013-5045)을 보고해 주신 Context Information Security의 James Forshaw
-   Internet Explorer 권한 상승 취약점(CVE-2013-5046)을 보고해 주신 Context Information Security의 James Forshaw
-   Internet Explorer 메모리 손상 취약점(CVE-2013-5047)을 보고해 주신 [HP](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/)의 Abdul-Aziz Hariri
-   Internet Explorer 메모리 손상 취약점(CVE-2013-5048)을 [HP](https://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2013-5049)을 [HP](https://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Jose Antonio Vazquez Gonzalez
-   Internet Explorer 메모리 손상 취약점(CVE-2013-5051)을 보고해 주신 [OUSPG](https://www.ee.oulu.fi/research/ouspg/)의 Atte Kettunen
-   Internet Explorer 메모리 손상 취약점(CVE-2013-5052)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)의 Bo Qu
-   이 공지에 포함된 Internet Explorer XSS 필터 심층 보안 변경 사항에 대해 협력해 주신 Alex Inführ

**MS13-098**

-   WinVerifyTrust 서명 유효성 검사 취약점(CVE-2013-3900)을 보고해 주신 [Kingsoft Internet Security Software Co. Ltd](https://www.ijinshan.com/)의 Kingsoft Internet Security Center

**MS13-101**

-   Win32k 메모리 손상 취약점(CVE-2013-3899)을 보고해 주신 [Qihoo](https://www.360.cn/)의 Renguang Yuan
-   Win32k 메모리 손상 취약점(CVE-2013-3899)을 [VeriSign iDefense Labs](https://labs.idefense.com/)와 협력하여 보고해 주신 익명 연구자
-   TrueType 글꼴 분석 취약점(CVE-2013-3903)을 보고해 주신 [F13 Laboratory](https://www.f13-labs.net/)의 Ling Chuan Lee
-   Win32k 정수 오버플로 취약점(CVE-2013-5058)을 보고해 주신 [Core Security Technologies](https://www.coresecurity.com/)의 Nicolas Economou

**MS13-102**

-   LRPC 클라이언트 버퍼 오버런 취약점(CVE-2013-3878)을 보고해 주신 [Qihoo](https://www.360.cn/)의 Renguang Yuan

**MS13-104**

-   토큰 가로채기 취약점(CVE-2013-5054)을 보고해 주신 [Adallom](https://www.adallom.com/)의 Noam Liran

**MS13-105**

-   OWA XSS 취약점(CVE-2013-5072)을 [Criteo](https://www.criteo.com/) 대신 보고해 주신 [Minded Security](https://www.mindedsecurity.com/)

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 버전에서 Microsoft는 Windows 업데이트, Microsoft 업데이트, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 발표에서 사용할 수 없습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows 업데이트 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](https://technet.microsoft.com/wsus/bb456965). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](https://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](https://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft 업데이트](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows 업데이트를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.

IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](https://technet.microsoft.com/security/bb980617)

Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](https://support.microsoft.com/contactus/cu_sc_virsec_master)

국가별 현지 지원: [국가별 지원](https://support.microsoft.com/common/international.aspx)

### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 개정 내역

-   V1.0(2013년 12월 10일): 공지 요약이 게시되었습니다.

*2014년 5월 9일 17:27Z-07:00에 페이지가 생성되었습니다.*
