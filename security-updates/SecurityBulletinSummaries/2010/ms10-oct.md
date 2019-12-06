---
TOCTitle: 'MS10-OCT'
Title: Microsoft Security Bulletin Summary for 10월 2010
ms:assetid: 'ms10-oct'
ms:contentKeyID: 61230730
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms10-oct(v=Security.10)'
---


Microsoft Security Bulletin Summary for 10월 2010
=================================================

게시된 날짜: 2010년 10월 12일 화요일 | 업데이트된 날짜: 2011년 10월 27일 목요일

**버전:** 4.1

이 공지 요약 목록에는 2010년 10월 발표된 보안 공지가 포함되어 있습니다.

2010년 10월 공지 발표와 함께 이 공지 요약이 2010년 10월 7일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/ko-kr/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2010년 10월 13일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [10월 보안 공지 웹캐스트에 지금 등록하십시오(영문)](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032454437&culture=ko-kr). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약(영문)](http://technet.microsoft.com/ko-kr/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. 기타 정보 섹션을 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-071">MS10-071</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2360131)<br />
<br />
이 보안 업데이트는 Internet Explorer의 비공개적으로 보고된 취약점 7건과 일반에 공개된 취약점 3건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-075">MS10-075</a></td>
<td style="border:1px solid black;">Media Player 네트워크 공유 서비스의 취약점으로 인한 원격 코드 실행 문제점(2281679)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows Media Player 네트워크 공유 서비스의 취약점을 해결합니다. 공격자가 영향을 받는 시스템에 특수하게 조작된 RTSP 패킷을 보낼 경우 이 취약점으로 인해 원격 코드 실행이 발생할 수 있습니다. 그러나 홈 미디어에 대한 인터넷 액세스는 기본적으로 사용되지 않습니다. 이 기본 구성에서 공격자는 동일한 서브넷 내에서만 이 취약점을 악용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-076">MS10-076</a></td>
<td style="border:1px solid black;">Embedded OpenType 글꼴 엔진의 취약점으로 인한 원격 코드 실행 문제점(982132)<br />
<br />
이 보안 업데이트는 Microsoft Windows 구성 요소인 EOT(Embedded OpenType) 글꼴 엔진에서 발견되어 비공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점을 악용하면 원격 코드 실행이 가능합니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 원격으로 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-077">MS10-077</a></td>
<td style="border:1px solid black;">.NET Framew ork의 취약점으로 인한 원격 코드 실행 문제점(2160841)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft .NET Framework의 취약점을 해결합니다. 사용자가 XBAP(XAML 브라우저 응용 프로그램)을 실행할 수 있는 웹 브라우저를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 이 취약점으로 인해 클라이언트 시스템에서 원격 코드가 실행될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 서버에서 ASP.NET 페이지 처리를 허용하고 공격자가 해당 서버에 특수하게 조작한 ASP.NET 페이지를 성공적으로 업로드하여 실행할 경우 이 취약점으로 인해 IIS를 실행하는 서버 시스템에서 원격 코드 실행이 허용될 수 있습니다. 이러한 경우는 웹 호스팅 시나리오에서 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-072">MS10-072</a></td>
<td style="border:1px solid black;">SafeHTML의 취약점으로 인한 정보 유출 문제점(2412048)<br />
<br />
이 보안 업데이트는 Microsoft SharePoint 및 Windows SharePoint Services에서 발견되어 공개적으로 보고된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 공격자가 SafeHTML을 사용하여 특수하게 조작된 스크립트를 대상 사이트에 제출할 경우 이 취약점으로 인해 정보 유출이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Server 소프트웨어</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-073">MS10-073</a></td>
<td style="border:1px solid black;">Windo ws 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(981957)<br />
<br />
이 보안 업데이트는 Windows 커널 모드 드라이버의 공개된 여러 취약점을 해결합니다. 가장 위험한 취약점으로 인해 공격자가 영향을 받는 시스템에 로그온하여 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다.이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-078">MS10-078</a></td>
<td style="border:1px solid black;">OTF(OpenType Font) 드라이버의 취약점으로 인한 권한 상승 문제점(2279986)<br />
<br />
이 보안 업데이트는 Windows OTF(OpenType 글꼴) 서식 드라이버에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 보안 업데이트의 심각도는 지원 대상인 모든 Windows XP 및 Windows Server 2003 에디션에 대해 중요입니다. 지원 대상인 모든 Windows Vista, Windows Server 2008, Windows 7 및 Windows Server 2008 R2 에디션은 이 취약점의 영향을 받지 않습니다.<br />
<br />
이 취약점으로 인해 사용자가 특수하게 조작된 OpenType 글꼴로 렌더링된 콘텐츠를 볼 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-079">MS10-079</a></td>
<td style="border:1px solid black;">Microsoft Word의 취약점으로 인한 원격 코드 실행 문제점(2293194)<br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 11건을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 Word 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-080">MS10-080</a></td>
<td style="border:1px solid black;">Microsoft Excel의 취약점으로 인한 원격 코드 실행 문제점(2293211)<br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 13건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 Excel 파일이나 특수하게 조작된 Lotus 1-2-3 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-081">MS10-081</a></td>
<td style="border:1px solid black;">Windows 공용 컨트롤 라이브러리의 취약점으로 인한 원격 코드 실행 문제점(2296011)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows 공용 컨트롤 라이브러리의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 웹 페이지를 방문할 경우 원격 코드 실행이 허용될 수 있습니다. 사용자가 관리자 권한으로 로그온한 경우, 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-082">MS10-082</a></td>
<td style="border:1px solid black;">WindowsMedia Player의 취약점으로 인한 원격 코드 실행 문제점(2378111)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows Media Player의 취약점을 해결합니다. 이 취약점으로 인해 Windows Media Player에서 악의적인 웹 사이트에서 호스팅하는 특수하게 조작된 미디어 콘텐츠를 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-083">MS10-083</a></td>
<td style="border:1px solid black;">Windows 셸 및 WordPad의 COM 유효성 검사 취약점으로 인한 원격 코드 실행 문제점(2405882)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 WordPad를 사용하여 특수하게 조작된 파일을 열거나 네트워크 또는 WebDAV 공유에 있는 바로 가기 파일을 선택하거나 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-084">MS10-084</a></td>
<td style="border:1px solid black;">Windows 로컬 프로시저 호출의 취약점으로 인한 권한 상승 문제점(2360937)<br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점을 해결합니다. 이 보안 업데이트의 심각도는 지원 대상인 모든 Windows XP 및 Windows Server 2003 에디션에 대해 중요입니다. 지원 대상인 모든 Windows Vista, Windows Server 2008, Windows 7 및 Windows Server 2008 R2 에디션은 이 취약점의 영향을 받지 않습니다.<br />
<br />
취약점으로 인해 공격자가 영향을 받는 시스템에 로그온하여 LPC 메시지를 로컬 LRPC 서버로 보내는 특수하게 조작된 코드를 실행할 경우 권한 상승이 허용될 수 있습니다. 그러면 이 메시지는 인증된 사용자가 NetworkService 계정 컨텍스트에서 실행되는 리소스에 액세스할 수 있도록 합니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-085">MS10-085</a></td>
<td style="border:1px solid black;">SChannel의 취약점으로 인한 서비스 거부 문제점(2207566)<br />
<br />
이 보안 업데이트는 Windows의 Secure Channel(SChannel) 보안 패키지에서 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 영향을 받는 서버에서 SSL(Secure Sockets Layer)을 통해 특수하게 조작된 패킷 메시지를 수신할 경우 서비스 거부가 허용될 수 있습니다. 기본적으로 지원 대상인 모든 Windows Vista, Windows Server 2008, Windows 7 및 Windows Server 2008 R2 에디션은 SSL 네트워크 트래픽을 수신하도록 구성되어 있지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-084">MS10-074</a></td>
<td style="border:1px solid black;">MFC(Microsoft Foundation Class)의 취약점으로 인한 원격 코드 실행 문제점(2387149)<br />
<br />
이 보안 업데이트는 일반에 공개된 MFC(Microsoft Foundation Class) 라이브러리의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 관리 사용자 권한으로 로그온하고 MFC 라이브러리로 만들어진 응용 프로그램을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 사용자가 관리자 권한의 사용자 권한으로 로그온한 경우 공격자가 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">보통</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-086">MS10-086</a></td>
<td style="border:1px solid black;">Windows 공유 클러스터 디스크의 취약점으로 인한 변조 문제점(2294255)<br />
<br />
이 보안 업데이트는 공유 장애 조치(Failover) 클러스터로 사용되는 Windows Server 2008 R2에서 발견되어 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 장애 조치(Failover) 클러스터 디스크의 관리 공유에서 데이터 변조가 발생할 수 있습니다. 기본적으로 Windows Server 2008 R2 서버는 이 취약점의 영향을 받지 않습니다. 이 취약점은 장애 조치(Failover) 클러스터에 사용된 클러스터 디스크에만 적용됩니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">보통</a><br />
변조</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 악용 가능성 평가 수준 내림차순 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 취약점 제목                                 | CVE ID                                                                           | 악용 가능성 인덱스 평가                                                                    | 주요 정보                                                                                                                                                   |  
|---------------------------------------------------------------------|---------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-083](http://technet.microsoft.com/security/bulletin/ms10-083) | COM 유효성 검사 취약점                      | [CVE-2010-1263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-076](http://technet.microsoft.com/security/bulletin/ms10-076) | Embedded OpenType 글꼴 정수 오버플로 취약점 | [CVE-2010-1883](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1883) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 최신 운영 체제에서는 ASLR로 인해 취약점 악용이 어렵습니다.                                                                                                  |  
| [MS10-078](http://technet.microsoft.com/security/bulletin/ms10-078) | OpenType 글꼴 구문 분석 취약점              | [CVE-2010-2740](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2740) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-078](http://technet.microsoft.com/security/bulletin/ms10-078) | OpenType 글꼴 유효성 검사 취약점            | [CVE-2010-2741](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2741) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-073](http://technet.microsoft.com/security/bulletin/ms10-073) | Win32k 키보드 레이아웃 취약점               | [CVE-2010-2743](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2743) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점은 공개되었으며 현재 인터넷 생태계에서 악용되고 있습니다.                                                                                          |  
| [MS10-073](http://technet.microsoft.com/security/bulletin/ms10-073) | Win32k 창 클래스 취약점                     | [CVE-2010-2744](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2744) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점은 공개되었습니다.                                                                                                                                 |  
| [MS10-082](http://technet.microsoft.com/security/bulletin/ms10-082) | Windows Media Player 메모리 손상 취약점     | [CVE-2010-2745](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2745) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-081](http://technet.microsoft.com/security/bulletin/ms10-081) | Comctl32 힙 오버플로 취약점                 | [CVE-2010-2746](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2746) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079) | Word 스택 오버플로 취약점                   | [CVE-2010-3214](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3214) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079) | Word 책갈피 취약점                          | [CVE-2010-3216](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3216) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-084](http://technet.microsoft.com/security/bulletin/ms10-084) | LPC 메시지 버퍼 오버런 취약점               | [CVE-2010-3222](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3222) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점은 공개되었습니다.                                                                                                                                 |  
| [MS10-075](http://technet.microsoft.com/security/bulletin/ms10-075) | RTSP 해제 후 사용 취약점                    | [CVE-2010-3225](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3225) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-077](http://technet.microsoft.com/security/bulletin/ms10-077) | .NET Framework x64 JIT 컴파일러 취약점      | [CVE-2010-3228](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3228) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | Excel 파일 형식 구문 분석 취약점            | [CVE-2010-3232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3232) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | 수식 하위 스트림 메모리 손상 취약점         | [CVE-2010-3234](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3234) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | 수식 BIFF 레코드 취약점                     | [CVE-2010-3235](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3235) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | 범위 초과 배열 취약점                       | [CVE-2010-3236](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3236) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | 음수 미래 함수 취약점                       | [CVE-2010-3238](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3238) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | 추가 범위 초과 레코드 구문 분석 취약점      | [CVE-2010-3239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3239) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071) | 초기화되지 않은 메모리 손상 취약점          | [CVE-2010-3326](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3326) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071) | 초기화되지 않은 메모리 손상 취약점          | [CVE-2010-3328](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3328) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071) | 초기화되지 않은 메모리 손상 취약점          | [CVE-2010-3329](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3329) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071) | 초기화되지 않은 메모리 손상 취약점          | [CVE-2010-3331](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3331) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                      |  
| [MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079) | Word 초기화되지 않은 포인터 취약점          | [CVE-2010-2747](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2747) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079) | Word 경계 검사 취약점                       | [CVE-2010-2748](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2748) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079) | Word 인덱스 취약점                          | [CVE-2010-2750](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2750) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079) | Word 반환 값 취약점                         | [CVE-2010-3215](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3215) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079) | Word 포인터 취약점                          | [CVE-2010-3217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3217) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079) | Word 힙 오버플로 취약점                     | [CVE-2010-3218](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3218) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079) | Word 인덱스 구문 분석 취약점                | [CVE-2010-3219](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3219) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079) | Word 구문 분석 취약점                       | [CVE-2010-3220](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3220) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079) | Word 구문 분석 취약점                       | [CVE-2010-3221](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3221) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | Excel 레코드 구문 분석 정수 오버플로 취약점 | [CVE-2010-3230](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3230) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | Excel 레코드 분석 메모리 손상 취약점        | [CVE-2010-3231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3231) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | Lotus 1-2-3 통합 문서 구문 분석 취약점      | [CVE-2010-3233](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3233) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | 셀 병합 레코드 포인터 취약점                | [CVE-2010-3237](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3237) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | 실시간 데이터 배열 레코드 취약점            | [CVE-2010-3240](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3240) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | 구문 분석 시 범위 초과 메모리 쓰기 취약점   | [CVE-2010-3241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3241) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080) | 삭제할 레코드 유형 구문 분석 취약점         | [CVE-2010-3242](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3242) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                      |  
| [MS10-073](http://technet.microsoft.com/security/bulletin/ms10-073) | Win32k 참조 수 취약점                       | [CVE-2010-2549](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2549) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점은 공개되었습니다.                                                                                                                                 |  
| [MS10-085](http://technet.microsoft.com/security/bulletin/ms10-085) | TLSv1 서비스 거부 취약점                    | [CVE-2010-3229](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3229) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 최대 보안 영향은 서비스 거부입니다.                                                                                                                         |  
| [MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071) | HTML 삭제 취약점                            | [CVE-2010-3243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3243) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | [MS10-072](http://technet.microsoft.com/security/bulletin/ms10-072)도 이 취약점을 해결합니다. 최대 보안 영향은 정보 유출입니다.                             |  
| [MS10-072](http://technet.microsoft.com/security/bulletin/ms10-072) | HTML 삭제 취약점                            | [CVE-2010-3243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3243) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | [MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071)도 이 취약점을 해결합니다. 최대 보안 영향은 정보 유출입니다.                             |  
| [MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071) | HTML 삭제 취약점                            | [CVE-2010-3324](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3324) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | [MS10-072](http://technet.microsoft.com/security/bulletin/ms10-072)도 이 취약점을 해결합니다. 이 취약점은 공개되었습니다. 최대 보안 영향은 정보 유출입니다. |  
| [MS10-072](http://technet.microsoft.com/security/bulletin/ms10-072) | HTML 삭제 취약점                            | [CVE-2010-3324](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3324) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | [MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071)도 이 취약점을 해결합니다. 이 취약점은 공개되었습니다. 최대 보안 영향은 정보 유출입니다. |  
| [MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071) | CSS 특수 문자 정보 유출 취약점              | [CVE-2010-3325](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3325) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점은 공개되었습니다. 최대 보안 영향은 정보 유출입니다.                                                                                               |  
| [MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071) | 도메인 간 정보 유출 취약점 취약점           | [CVE-2010-3330](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3330) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 최대 보안 영향은 정보 유출입니다.                                                                                                                           |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
참고 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
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
<th style="border:1px solid black;" colspan="14">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](http://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](http://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](http://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](http://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](http://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](http://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](http://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](http://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](http://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](http://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](http://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](http://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=3b029696-cf98-4935-b3d6-846110aaa4bb&displaylang=ko)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c77ee103-7e97-44b2-bbf3-ee9f0de37fed&displaylang=ko)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=93580299-d764-417f-a7fa-ee441fea2bb3&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=c3799399-ca72-4dec-a2a2-3571ad0b2f63&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=3966d754-d298-4e4a-9ce6-8205accd2215&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=0553fc7c-deed-4594-a133-d621551310dc&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=912a7c20-8177-4f65-b986-43fca6375ec1&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Player 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=bbf153e7-e764-46a0-a33b-81b7288d346c&displaylang=ko)  
(중요)  
[Windows Media Player 10](https://www.microsoft.com/download/details.aspx?familyid=bbf153e7-e764-46a0-a33b-81b7288d346c&displaylang=ko)  
(중요)  
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=bbf153e7-e764-46a0-a33b-81b7288d346c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=211d95be-5630-4af5-85a7-c50268c475a9&displaylang=ko)  
(KB979687)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=6049c879-b81a-4d10-b96b-b2837cb24834&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=22f46b3b-9be6-45ea-a639-9974324ce4bd&displaylang=ko)  
(보통)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=d494535a-b68e-4242-af85-5fa62f631ffc)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ff9c65fe-437c-426d-9096-dd89ff7927fd)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=05413f6c-b4be-4892-b4b3-c54dd01fd95d)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=860ff738-205d-430e-b223-b333813fc590)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ko)<sup>[1]</sup>
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7fd7c675-0675-4a87-a709-edc47a30f1e2)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1ad30596-bac6-4d48-8b15-0245960c443b)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6c651bca-adb1-4172-9714-cd5a6e5d2c2a)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Player 10](https://www.microsoft.com/download/details.aspx?familyid=0663e0e8-c5d1-4cd2-b6d3-ff78fb56bba1)  
(중요)  
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=474b5618-dfe6-40de-b59b-1fd61a05749e)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4b6f0898-8f77-4ce1-9c96-2b17c496230b)  
(KB979687)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d690846c-5e0b-4216-84cd-d17e366dd16d)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=285627b9-242d-4247-a4c8-55dc89386b62)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="14">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](http://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](http://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](http://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](http://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](http://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](http://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](http://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](http://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](http://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](http://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](http://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](http://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=f64af3cd-591d-4212-94a0-3bc9a4d9782a&displaylang=ko)  
(중요)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=fbcf0e65-c9f4-47f8-b4fc-ae46a66ab339&displaylang=ko)  
(중요)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9af37f62-5585-4ff5-9dd3-3fa0b148ae08&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7b240b65-f3ca-465c-a606-b561999c1977&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8ef4378e-21ff-4290-96ba-e00a60f372d1&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f94763e7-b1db-4043-aa79-d5be1a42307d&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3b2eb449-ad55-4dfb-a3c5-aac767de6f45&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Player 10](https://www.microsoft.com/download/details.aspx?familyid=5479fd20-50d1-447a-8555-a98ce0723f71&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=13c08ec0-53ae-4b85-b669-8c88f6089259&displaylang=ko)  
(KB979687)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b31e18b0-da9f-4b3b-82c6-603e08b3b241&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d220f04e-9dbb-4b6d-924a-23065b48b8b6&displaylang=ko)  
(보통)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=12c3b950-b955-4820-9b4c-5206deb0cd3e&displaylang=ko)  
(중요)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=59a715a5-10ff-40e6-88e0-096c9b640799&displaylang=ko)  
(중요)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c8052f0c-e62c-46c4-bb59-d515fa388ea8&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=70c9e826-b80b-4a20-82d2-8e52e5cca839&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ko)<sup>[1]</sup>
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4a95c74b-cfd8-45b5-8887-777429d21745&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6fca5cab-7e11-4911-a6a8-f73f113b2963&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=54fc4bc6-f46c-447c-8307-afd8338e7ffb&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Player 10](https://www.microsoft.com/download/details.aspx?familyid=a9515e69-c147-4810-8c5a-6cb94c398a95&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=02519f9e-e1c5-48a1-8420-01898c45ec01&displaylang=ko)  
(KB979687)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1d73f0f1-6ec8-4304-a20e-345d8b6c225a&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=de908137-33e0-4f23-b32b-cc1bdbcb349c&displaylang=ko)  
(보통)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=97b3f6dc-8df5-4c93-aaee-f191498c7ce4)  
(중요)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ba194be9-24f9-4c62-9aa9-9e98c81ddba1)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=bd5878bb-f565-4303-afed-4e17b44a02f2)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ko)<sup>[1]</sup>
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=21637cd8-c75c-43b4-9948-be7be54af6bf)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=e8f297e2-0dfd-421a-b598-a78199ad6baa)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=64f5c311-d74a-4665-9775-ac91c6885ed3)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=1064bccb-3ce6-4a72-8788-56d8021bca91)  
(KB979687)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=8fad4f77-7c89-4684-b957-9c00ced248d3)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=873dea9d-44cc-4e16-8a6d-dca678ce3a80)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="14">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](http://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](http://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](http://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](http://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](http://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](http://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](http://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](http://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](http://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](http://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](http://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](http://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4f656d16-2a7e-4d18-8a5a-ebf8a1a10e2b&displaylang=ko)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=191c8388-f1ef-45b6-9f07-d5654a973abe&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4a481825-d9ad-4a7c-aa89-f40fb9651961&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=29c4afb1-227d-4572-b136-a78ef7e1df77&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e9f735ab-d995-4209-b2dc-197f53fdee0f&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=95ceafc6-e37a-4c77-b16e-c9c94a7d89bd&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=95e24a63-d21a-4756-a16e-17a977595396&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=80c99d69-4b97-4af2-8f8e-f3b300a89a5a&displaylang=ko)<sup>[1]</sup>
(KB979687)  
(중요)  
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dff92449-22ad-49a8-8b28-5295a8af5b8b&displaylang=ko)<sup>[1]</sup>
(KB979688)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4af2f6e6-6905-498c-bfba-a565976b3365&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=75ca4e2c-b0ae-46f4-a0fc-616510c41a55&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=02c6260c-8e21-401a-992d-884c6ff7141d&displaylang=ko)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=adeb3036-62fa-4a29-b82f-ff4a50c05996&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=15d8f81b-97b0-43d9-b218-1cdd759cb2ec&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=880ad9a0-6ddd-41f4-a608-171d59a31b6a&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ko)<sup>[1]</sup>
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=738c8f70-b46a-4a59-bea6-078074a9c4db&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dfe7cd18-53a3-433e-9a33-bd96b04b4deb&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=277151a2-b74f-4da6-8203-e774af75e44c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b73951f2-a7eb-4c7c-bf60-fdcfee83574f&displaylang=ko)<sup>[1]</sup>
(KB979687)  
(중요)  
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c9d2261f-bd9a-4495-a2f1-3c3b2208b01e&displaylang=ko)<sup>[1]</sup>
(KB979688)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8c56ba29-b2a8-47a8-a605-4c54c0a7fa7c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0a12ff95-ea5c-4c48-96c5-9494eb8f9f0d&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="14">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](http://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](http://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](http://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](http://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](http://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](http://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](http://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](http://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](http://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](http://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](http://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](http://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0107dd61-7b3e-4fcf-9743-d9ae594b2278&displaylang=ko)\*\*  
(중요)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ea5b7c86-3878-43a9-a4bc-12e04bfbd06e&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=50386655-982e-4126-8261-2c972d695bbd&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4dff0ebe-ccba-4675-98ca-9903f1cb6763&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d5f079b0-d8e1-47fe-b9dd-41eeb463a93c&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=67eb3a70-9ca7-4184-b9fe-cc3e66b1bf36&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=fd507e7a-4516-474b-8f33-7fa8fd2afa6d&displaylang=ko)\*\*<sup>[1]</sup>
(KB979687)  
(중요)  
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4a8c2358-36ea-4757-abfc-5bffcad0a872&displaylang=ko)\*\*<sup>[1]</sup>
(KB979688)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0566915f-2a1b-474b-b5f1-e1a9cedd836a&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=952b3594-d980-45b1-8fa3-49403784afbf&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=139f3bb2-eefc-4cf4-9c15-de78f5a736c1&displaylang=ko)\*\*  
(중요)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=71ecdb27-46aa-4db1-b86a-3268cda88632&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a6b2ae1d-9225-4495-8560-97860f87d7b4&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ko)\*\*<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=da7905a9-9587-4184-8fca-ecc636a3b67e&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8e88d9c5-eb57-4d39-a880-a478c5f286da&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=33a06f0e-81ab-445a-bc89-14350ebfe688&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b5f53faf-61e2-4b4e-8b85-c5e8f38e5c30&displaylang=ko)\*\*<sup>[1]</sup>
(KB979687)  
(중요)  
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=612ab78c-1ff1-45d2-96cc-ae831fb0a563&displaylang=ko)\*\*<sup>[1]</sup>
(KB979688)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=74ac2233-02ec-454c-8aa0-64b18071e16a&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=21128031-d935-4e2d-b001-c502a2d6022c&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1a971fb2-7dc4-43bf-ae25-3a420bb1acf9)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a4e38a77-3835-47b3-bd86-6c039169abf5)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b9096046-8c7a-450c-b8c5-6e9fb001e6cd)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=76e46d08-22d9-4a0c-82cd-d2753d07efe6)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5efe55b0-d34d-4f00-98b2-cc0e9807a8b9)<sup>[1]</sup>
(KB979687)  
(중요)  
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d30368cb-c6e8-403e-aaf6-425f96b6211e)<sup>[1]</sup>
(KB979688)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2fff281a-2221-42a3-a2b7-07b5c5e66ae7)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2eca0c38-73f5-4f83-ab62-97f979716a1d)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="14">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](http://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](http://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](http://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](http://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](http://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](http://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](http://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](http://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](http://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](http://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](http://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](http://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[없음](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6595770f-e580-4613-a83a-3b8ee4cc30f1&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=1a3953fe-ba48-4980-a65d-74e3b756d53c&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=f6cae091-e9f1-48e9-a035-4346b9c6fec6&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=b5b31499-d242-42bf-ac78-b787ffb4d602&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=bdff9057-381a-44e8-b093-84f07d8d7e3c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Player 12](https://www.microsoft.com/download/details.aspx?familyid=59a2ef36-9c32-488b-b5b1-30b5bcd83358&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=b0d46bc3-24db-4207-b6fc-46b8cc64f075&displaylang=ko)<sup>[1]</sup>
(KB979687)  
(중요)  
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=4a422192-d7fa-47e5-9661-2c65eaefaf62)<sup>[1]</sup>
(KB979688)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d7a08a66-08b4-421c-afad-f2f367d4a9f0&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=f09fbc23-cb6b-4525-8e41-8c14e8d03de9&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ffe364ee-e2ae-466c-b727-14b1a976a860&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=5759d2a3-7f35-4fa1-8ab4-17145839fa26&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=35882477-4e0a-4783-a4b4-0f1ea3398360&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ko)<sup>[1]</sup>
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=c47e8b74-8cfe-42d9-9362-8786687c88ad&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=35a2b1a9-6dd6-4a7e-bc0a-b4fcffa06b28&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Player 12](https://www.microsoft.com/download/details.aspx?familyid=00176d56-8a93-4780-96fc-a7ab715e7291&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=2de197c0-6d9e-460e-9509-f337fac8ee85&displaylang=ko)<sup>[1]</sup>
(KB979687)  
(중요)  
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=03665687-8fd4-4afd-ac33-5f6824f51df8&displaylang=ko)<sup>[1]</sup>
(KB979688)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=50d27c23-5f69-40fa-b517-32c245009467&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=abc24826-b83a-4e01-be68-8e3a73c10494&displaylang=ko)  
(보통)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ko)<sup>[1]</sup>
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
<th style="border:1px solid black;" colspan="14">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-071](http://technet.microsoft.com/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](http://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](http://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](http://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](http://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](http://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](http://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](http://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](http://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](http://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](http://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](http://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](http://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d8b563ce-5db1-4490-8a63-44833d55152b&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=b060c516-233a-4e1e-9237-698420e97b2f&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=98e0c6ac-c30b-4d39-8ed9-1fe69e7644e5&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=25fff010-3abc-45e6-979e-21d2bae49418&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Player 12](https://www.microsoft.com/download/details.aspx?familyid=4cf0e3b1-4b72-4f99-b716-2489ea42ed72&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=70622d35-4877-4cbb-bdbf-7648dc1ea8ed&displaylang=ko)\*\*<sup>[1]</sup>
(KB979687)  
(중요)  
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=1c2ff242-65e3-4d47-bfca-4db30f809ed8&displaylang=ko)\*\*<sup>[1]</sup>
(KB979688)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d356af2f-eadf-4bf2-82d1-efa0d01ac92d&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=e4d27aa6-9739-4e41-9536-5f0b8d26503c&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=1de12fdf-b439-4020-9313-a193d47dcfb2&displaylang=ko)\*  
(보통)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)\*\*<sup>[1]</sup>
(중요)
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
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=bbaa9f46-8fc7-4c44-b38c-dc3d5210f63d)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=0ead2ed9-8b2f-496e-b7d1-3ad2b04be5cc)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=44080c75-036e-4bd0-914a-74ab72189ee3)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d0742526-b5ec-4658-82f1-c3680f33a790)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=3cec2b70-f694-4c0d-bf82-96a4fd50675d)<sup>[1]</sup>
(KB979687)  
(중요)  
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=f478020b-0305-47d5-bcb2-0758f292db29)<sup>[1]</sup>
(KB979688)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=334d39e6-8e4c-4e83-94c1-1db3d636e865)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=c1634278-5598-45e0-81c6-f18fb5ba54cf)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=1c607c7d-6144-4a39-beea-a31b62085047)  
(보통)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f)<sup>[1]</sup>
(중요)
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
 
MS10-077 참고 사항

<sup>[1]</sup>.NET Framework 4.0 및 .NET Framework 4.0 Client Profile이 영향을 받습니다. .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4.0 및 .NET Framework 4.0 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4.0 Client Profile은 .NET Framework 4.0의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4.0 및 .NET Framework 4.0 Client Profile에 모두 영향을 줍니다. 자세한 내용은 MSDN 문서, .NET Framework 설치를 참조하십시오.

MS10-083 참고 사항

<sup>[1]</sup>KB979687 및 KB979688의 두 보안 업데이트 패키지가 동일 운영 체제에 제공되는 경우 MS10-083에 설명된 취약점으로부터 보호하려면 둘 다 설치해야 합니다.

Windows Server 2008 및 Windows Server 2008 R2 참고 사항

\*Server Core 설치가 영향을 받습니다. 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](http://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](http://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

\*\*Server Core 설치는 영향을 받지 않습니다. Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](http://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](http://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 제품군 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079)
</td>
<td style="border:1px solid black;">
[MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=f22d10fd-cb12-43e8-88d5-2116cf4317c4&displaylang=ko)  
(KB2328360)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=ea859881-2cc5-407b-a394-5d00c5d9fd97&displaylang=ko)  
(KB2345017)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=172f3743-cdfa-42d7-aeb4-27ba0e4139f7&displaylang=ko)  
(KB2344911)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=3d9a00b8-0f80-4d36-b92a-89b61350fb36&displaylang=ko)  
(KB2344893)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ccad4871-32f2-4982-a23e-9b5824397615&displaylang=ko)<sup>[1]</sup>
(KB2344993)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dc9b9af5-50b0-4a07-8923-a30fd5548760&displaylang=ko)<sup>[1]</sup>
(KB2345035)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=6c3b8690-e568-42ed-a858-0cbdd5ea3669&displaylang=ko)  
(KB2345000)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=f31a1f9b-02df-4a85-a7d1-7d1e31baa30f&displaylang=ko)  
(KB2345000)  
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
[MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079)
</td>
<td style="border:1px solid black;">
[MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Mac용 Microsoft Office 2004
</td>
<td style="border:1px solid black;">
[Mac용 Microsoft Office 2004](https://www.microsoft.com/download/details.aspx?familyid=464965fa-971a-49dd-bcee-c4d91fac86a9)  
(KB2422343)  
(중요)
</td>
<td style="border:1px solid black;">
[Mac용 Microsoft Office 2004](https://www.microsoft.com/download/details.aspx?familyid=464965fa-971a-49dd-bcee-c4d91fac86a9)  
(KB2422343)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=abd05074-8ffc-41a4-a2f3-1d8047574552)  
(KB2422352)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=abd05074-8ffc-41a4-a2f3-1d8047574552)  
(KB2422352)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=5c759c46-ead3-44ea-b7c8-a308b3140d2e)  
(KB2422398)  
(중요)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=5c759c46-ead3-44ea-b7c8-a308b3140d2e)  
(KB2422398)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
기타 Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079)
</td>
<td style="border:1px solid black;">
[MS10-080](http://technet.microsoft.com/security/bulletin/ms10-080)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer](https://www.microsoft.com/download/details.aspx?familyid=1cb5ab02-074d-4877-b378-7058959705ae&displaylang=ko)  
(KB2345009)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a833a94a-2dc0-4864-9c14-e196dc54c5a7&displaylang=ko)  
(KB2345088)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=553d28ae-c352-4985-97c3-e5038414be45&displaylang=ko)  
(KB2345043)  
(중요)
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=7391ec2f-12c9-483c-91d8-e3ec5754da1c&displaylang=ko)  
(KB2344875)  
(중요)
</td>
</tr>
</table>
 
MS10-079 참고 사항

<sup>[1]</sup>Microsoft Word 2007 서비스 팩 2를 사용하는 고객의 경우 MS10-079에서 설명한 취약점으로부터 보호하기 위해 보안 업데이트 패키지 KB2344993 이외에도 Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 서비스 팩 2용 보안 업데이트(KB2345043)를 설치해야 합니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

MS10-080 참고 사항

<sup>[1]</sup>Microsoft Office Excel 2007 서비스 팩 2를 사용하는 고객의 경우 MS10-080에서 설명한 취약점으로부터 보호하기 위해 보안 업데이트 패키지 KB2345035 이외에도 Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 서비스 팩 2용 보안 업데이트(KB2344875)를 설치해야 합니다.

#### Microsoft Server 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft SharePoint Services 및 Microsoft SharePoint Foundation
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-072](http://technet.microsoft.com/security/bulletin/ms10-072)
</td>
<td style="border:1px solid black;">
[MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 서비스 팩 2(32비트 버전)](https://www.microsoft.com/download/details.aspx?familyid=12fd97a9-6fb8-4b65-a497-a56587f114e1&displaylang=ko)  
(KB2345304)  
(중요)  
[Microsoft Windows SharePoint Services 3.0 서비스 팩 2(64비트 버전)](https://www.microsoft.com/download/details.aspx?familyid=58d1e91d-a037-485d-a6d9-80fbf403b108&displaylang=ko)  
(KB2345304)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010](https://www.microsoft.com/download/details.aspx?familyid=fc146fcb-c2cb-4860-a0cd-4b09fa3f44eb&displaylang=ko)  
(KB2345322)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft SharePoint 및 Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-072](http://technet.microsoft.com/security/bulletin/ms10-072)
</td>
<td style="border:1px solid black;">
[MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 서비스 팩 2(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=aee3f2de-ccf3-4d32-b468-eede4e8afcd4)<sup>[1]</sup>
(KB2345212)  
(중요)  
[Microsoft Office SharePoint Server 2007 서비스 팩 2(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=e5e60751-242a-4fdb-9852-6d94050d3d0e)<sup>[1]</sup>
(KB2345212)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2010
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010](https://www.microsoft.com/download/details.aspx?familyid=e032aef8-dd30-41c6-99bb-8cf0491451cc&displaylang=ko)  
(KB2346298)  
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
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-072](http://technet.microsoft.com/security/bulletin/ms10-072)
</td>
<td style="border:1px solid black;">
[MS10-079](http://technet.microsoft.com/security/bulletin/ms10-079)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps](https://www.microsoft.com/download/details.aspx?familyid=8fb56eb9-9601-4c1e-905a-9fe4802b2c8d&displaylang=ko)  
(KB2346411)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps](https://www.microsoft.com/download/details.aspx?familyid=8fb56eb9-9601-4c1e-905a-9fe4802b2c8d&displaylang=ko)<sup>[2]</sup>
(KB2346411)  
(중요)  
[Microsoft Word Web App](https://www.microsoft.com/download/details.aspx?familyid=13b24264-ec3d-44e8-81e3-82ac767defd3&displaylang=ko)<sup>[2]</sup>
(KB2345015)  
(중요)
</td>
</tr>
</table>
 
MS10-072 참고 사항

\[1***\]***고객은 MS10-072에서 설명한 취약점으로부터 보호하기 위해 지원 대상인 Microsoft SharePoint Server 2007 에디션에 보안 업데이트 패키지 KB2345212와 함께 Microsoft Windows SharePoint Services 3.0용 보안 업데이트(KB2345304)를 설치해야 합니다.

MS10-079 참고 사항

<sup>[2]</sup>Microsoft Office Web Apps를 사용하는 고객의 경우 MS10-079에서 설명한 취약점으로부터 보호하기 위해 보안 업데이트 KB2346411 및 보안 업데이트 KB2345015를 모두 설치해야 합니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

검색, 배포 도구 및 지침
-----------------------

보안 센터

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

검색 및 배포 지침

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

Microsoft Baseline Security Analyzer

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

Windows Server Update Services

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

Systems Management Server

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007(영문)](http://technet.microsoft.com/ko-kr/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://go.microsoft.com/fwlink/?linkid=22939)를 참조하십시오. SMS 2.0 사용자는 SUIT(Security Update Inventory Tool)을 사용하여 보안 업데이트 배포를 지원할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)를 참조하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포(영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2.0 Administration Feature Pack(영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)(영문)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator)(영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199)
-   : 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트(영문)](http://technet.microsoft.com/ko-kr/wsus/bb456965.aspx)
-   . Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너(영문)](http://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

업데이트 관리 전략

[업데이트 관리를 위한 보안 가이드(영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

기타 보안 관련 업데이트 받기

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS10-071에서 설명한 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 [Sirdarckcat(영문)](http://www.sirdarckcat.net/)
-   MS10-071에서 설명한 문제점을 보고해 주신 Mario Heiderich
-   MS10-071에서 설명한 문제점을 보고해 주신 [IBM ISS X-Force(영문)](http://www.iss.net/)의 Takehiro Takahashi
-   MS10-071에서 설명한 문제점을 [TippingPoint(영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 [Peter Vreugdenhil(영문)](http://vreugdenhilresearch.nl)
-   MS10-071에서 설명한 문제점을 보고해 주신 [Core Security Technologies(영문)](http://www.coresecurity.com/)의 Damián Frizza
-   MS10-071에서 설명한 문제점을 보고해 주신 [Cigital(영문)](http://www.cigital.com/)의 Aldwin Saugere 및 Radoslav Vasilev
-   MS10-071에서 설명한 문제점을 보고해 주신 [Check Point(영문)](http://www.checkpoint.com/) IPS Research Center의 Rodrigo Rubira Branco
-   MS10-072에서 설명한 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 [Sirdarckcat(영문)](http://www.sirdarckcat.net/)
-   MS10-072에서 설명한 문제점을 보고해 주신 Mario Heiderich
-   MS10-073에서 설명한 문제점을 보고해 주신 [Kaspersky Lab(영문)](http://www.kaspersky.com)의 Sergey Golovanov, Alexander Gostev, Maxim Golovkin 및 Alexey Monastyrsky와 [Design and Test Lab(영문)](http://www.dnt-lab.com)의 Vitaly Kiktenko 및 Alexander Saprykin
-   MS10-073에서 설명한 문제점을 보고해 주신 [Symantec(영문)](http://www.symantec.com/index.jsp)의 Eric Chien
-   MS10-073에서 설명한 문제점을 해결하기 위해 협력해 주신 [Norman(영문)](http://www.norman.com)의 Tarjei Mandt
-   MS10-074에서 설명한 문제점을 해결하기 위해 협력해 주신 [Secunia(영문)](http://secunia.com/)의 Carsten H. Eiram
-   MS10-075에서 설명한 문제점을 [TippingPoint(영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Oleksandr Mirosh
-   MS10-076에서 설명한 문제점을 [TippingPoint(영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Sebastian Apelt
-   MS10-076에서 설명한 문제점을 [iSIGHT Partners Global Vulnerability Partnership(영문)](https://gvp.isightpartners.com/)을 통해 보고해 주신 Ivan Fratric
-   MS10-077에서 설명한 문제점을 보고해 주신 [Sumatra(영문)](http://www.sumatra.nl/)의 Jeroen Frijters
-   MS10-078에서 설명한 문제점을 보고해 주신 [Siberas(영문)](http://www.siberas.de/)의 Sebastian Apelt
-   MS10-078에서 설명한 문제점을 보고해 주신 [Core Security Technologies(영문)](http://www.coresecurity.com/)의 Diego Juarez
-   MS10-079에서 설명한 열 가지 문제점을 보고해 주신 [VUPEN Vulnerability Research Team(영문)](http://www.vupen.com/)의 Chaouki Bekrar
-   MS10-079에서 설명한 문제점을 보고해 주신 [VUPEN Vulnerability Research Team(영문)](http://www.vupen.com/)의 Nicolas Joly
-   MS10-079에서 설명한 문제점을 보고해주신 [Secunia Research(영문)](http://secunia.com/)의 Alin Rad Pop
-   MS10-080에서 설명한 두 가지 문제점을 보고해 주신 [Secunia(영문)](http://secunia.com/)의 Alin Rad Pop
-   MS10-080에서 설명한 열 가지 문제점을 보고해 주신 [VUPEN Vulnerability Research Team(영문)](http://www.vupen.com/)의 Chaouki Bekrar
-   MS10-080에서 설명한 문제점을 보고해 주신 Omair
-   MS10-080에서 설명한 두 가지 문제점을 보고해 주신 [Secunia(영문)](http://secunia.com/)의 Carsten H. Eiram
-   MS10-081에서 설명한 문제를 [Secunia(영문)](http://secunia.com/)와 협력하여 보고해 주신 Krystian Kloskowski(h07)
-   MS10-082에서 설명한 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 SkyLined
-   MS10-083에서 설명한 문제점을 보고해 주신 [Rapid7(영문)](http://www.rapid7.com/)의 HD Moore
-   MS10-083에서 해결한 심층 보안 변경 사항에 대해 협력해 주신 [IBM ISS X-Force(영문)](http://www.iss.net/)의 David Dewey 및 [Accuvant(영문)](http://www.accuvant.com/)(이전 [VeriSign iDefense Labs(영문)](http://labs.idefense.com/))의 Ryan Smith
-   MS10-085에서 설명한 문제점을 보고해 주신 [Mu Dynamics](http://www.mudynamics.com/)의 [Mu Test Suite Team(영문)](http://www.mudynamics.com/products/mu-test-suite.html)

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원(영문)](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/korea) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2010년 10월 12일): 공지 요약이 게시되었습니다.
-   V1.1(2010년 10월 13일): MS10-077에서 Windows Server 2008 및 Windows Server 2008 R2에 대한 취약점 심각도가 중요로 변경되었습니다. 또한 MS10-082에서 Windows XP Professional x64 Edition 서비스 팩 2의 Windows Media Player 11에 대한 다운로드 링크가 수정되었습니다.
-   V2.0(2010년 10월 18일): MS10-085에서 네트워크 트래픽을 수신하도록 구성된 영향을 받는 시스템에서 취약점이 악용될 수 있음을 설명하기 위해 요약 설명이 변경되었습니다. 이 변경 사항은 정보에만 해당됩니다. 자동 업데이트를 사용하는 고객을 포함하여 이미 시스템을 성공적으로 업데이트한 고객은 추가 조치를 취할 필요가 없습니다. 이전에 이 업데이트를 설치하지 않은 고객은 시스템에 이 업데이트가 필요한지 다시 평가해야 할 수 있습니다.
-   V3.0(2010년 12월 14일): 다음 사항을 알리기 위해 이 공지 요약을 개정하였습니다. MS10-077에서 다른 업데이트 및/또는 제품의 설공적인 설치를 방해할 수 있는 설정 문제점을 수정하는 .NET Framework 4.0에 대한 새 업데이트 패키지가 제공됩니다. 이미 시스템을 성공적으로 업데이트한 고객은 추가 조치를 취할 필요가 없습니다. MS10-083에서 Windows Vista 서비스 팩 1 또는 Windows Server 2008에 Windows Search 4.0을 설치한 후 KB2405882에서 제공되는 보안 업데이트를 설치하고 Windows Vista 서비스 팩 2 또는 Windows Server 2008 서비스 팩 2로 마이그레이션한 사용자를 위한 Windows Vista 서비스 팩 2(KB979688) 및 Windows Server 2008 서비스 팩 2(KB979688)용 추가 업데이트가 제공됩니다. 새 업데이트는 [Microsoft 기술 자료 문서 2405882](http://support.microsoft.com/kb/2405882)에서 다운로드할 수 있습니다.
-   V4.0(2011년 2월 22일): MS10-077에서 검색 변경 사항은 이제 Windows 7(x64 기반 시스템용) 서비스 팩 1, Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1 또는 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1을 설치한 후 Microsoft .NET Framework 4.0을 설치한 고객에게 Microsoft .NET Framework 4.0 업데이트 패키지를 제공합니다. 이미 시스템을 성공적으로 업데이트한 고객은 추가 조치를 취할 필요가 없습니다.
-   V4.1(2011년 10월 27일): MS10-077에서 설명한 Windows Server 2008 R2(x64 기반 시스템용)의 .NET Framework 4에 대한 Server Core 설치 적용 가능성이 수정되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
