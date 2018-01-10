---
TOCTitle: 'MS10-DEC'
Title: 2010 년 12 월 Microsoft 보안 공지 요약
ms:assetid: 'ms10-dec'
ms:contentKeyID: 61230722
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms10-dec(v=Security.10)'
---


2010 년 12 월 Microsoft 보안 공지 요약
======================================

게시된 날짜: 2010년 12월 15일 수요일 | 업데이트된 날짜: 2010년 12월 16일 목요일

**버전:** 1.1

이 공지 요약 목록에는 2010년 12월 발표된 보안 공지가 포함되어 있습니다.

2010년 12월 보안 공지 발표와 함께 이 공지 요약이 2010년 12월 9일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2010년 12월 14일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [12월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454444&eventcategory=4&culture=en-us&countrycode=us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

요약
----

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-090">MS10-090</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(2416400)</strong><br />
<br />
이 보안 업데이트는 Internet Explorer의 비공개적으로 보고된 취약점 4건과 일반에 공개된 취약점 3건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-091">MS10-091</a></td>
<td style="border:1px solid black;"><strong>OTF(OpenType 글꼴) 드라이버의 취약점으로 인한 원격 코드 실행 문제점(2296199)</strong><br />
<br />
이 보안 업데이트는 원격 코드 실행을 허용할 수 있는 비공개적으로 보고된 여러 건의 Windows OTF(Open Type Font) 드라이버 취약점을 해결합니다. 공격자는 네트워크 공유 위치에 특수하게 조작된 OpenType 글꼴을 호스팅할 수 있습니다. 그러면 사용자가 Windows 탐색기에서 공유 위치로 이동할 때 영향을 받는 제어 경로가 트리거되어 특수하게 조작된 글꼴이 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-092">MS10-092</a></td>
<td style="border:1px solid black;"><strong>작업 스케줄러의 취약점으로 인한 권한 상승 문제점(2305420)</strong><br />
<br />
이 보안 업데이트는 Windows 작업 스케줄러의 공개된 취약점을 해결합니다. 이 취약점으로 인해 공격자가 영향을 받는 시스템에 로그온한 후 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-093">MS10-093</a></td>
<td style="border:1px solid black;"><strong>Windows Movie Maker의 취약점으로 인한 원격 코드 실행 문제점(2424434)</strong><br />
<br />
이 보안 업데이트는 Windows Movie Maker의 공개된 취약점을 해결합니다. 이 취약점으로 인해 공격자가 사용자로 하여금 특수하게 조작된 라이브러리 파일과 동일한 네트워크 디렉터리에 있는 합법적인 Windows Movie Maker 파일을 열도록 유도할 경우 원격 코드 실행이 허용될 수 있습니다. 공격에 성공하려면, 사용자가 신뢰할 수 없는 원격 파일 시스템 위치 또는 WebDAV 공유를 방문하거나 이러한 위치에서 취약한 응용 프로그램이 로드되는 문서를 열어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-094">MS10-094</a></td>
<td style="border:1px solid black;"><strong>Windows Media Encoder의 취약점으로 인한 원격 코드 실행 문제점(2447961)</strong><br />
<br />
이 보안 업데이트는 Windows Media Encoder의 공개된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 라이브러리 파일과 동일한 네트워크 디렉터리에 있는 합법적인 Windows Media 프로필(.prx) 파일을 열도록 유도할 경우 원격 코드 실행이 허용될 수 있습니다. 공격에 성공하려면, 사용자가 신뢰할 수 없는 원격 파일 시스템 위치 또는 WebDAV 공유를 방문하거나 이러한 위치에서 취약한 응용 프로그램이 로드되는 문서를 열어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-095">MS10-095</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows의 취약점으로 인한 원격 코드 실행 문제점(2385678)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 라이브러리 파일과 동일한 네트워크 폴더에 있는 .eml 및 .rss(Windows Live 메일) 또는 .wpost(Microsoft Live Writer)와 같은 파일 형식을 열 경우 원격 코드 실행이 허용될 수 있습니다. 공격에 성공하려면, 사용자가 신뢰할 수 없는 원격 파일 시스템 위치 또는 WebDAV 공유를 방문하거나 이러한 위치에서 취약한 응용 프로그램이 로드되는 문서를 열어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-096">MS10-096</a></td>
<td style="border:1px solid black;"><strong>Windows 주소록의 취약점으로 인한 원격 코드 실행 문제점(2423089)</strong><br />
<br />
이 보안 업데이트는 Windows 주소록의 공개된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 라이브러리 파일과 동일한 네트워크 폴더에 있는 Windows 주소록 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 공격에 성공하려면, 사용자가 신뢰할 수 없는 원격 파일 시스템 위치 또는 WebDAV 공유를 방문하거나 이러한 위치에서 취약한 응용 프로그램이 로드되는 문서를 열어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-097">MS10-097</a></td>
<td style="border:1px solid black;"><strong>인터넷 연결 등록 마법사의 안전하지 않은 라이브러리 로드로 인한 원격 코드 실행 문제점(2443105)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows 인터넷 연결 등록 마법사의 공개된 취약점을 해결합니다. 이 보안 업데이트의 심각도는 지원 대상인 모든 Windows XP 및 Windows Server 2003 에디션에 대해 중요입니다. 지원 대상인 모든 Windows Vista, Windows Server 2008, Windows 7 및 Windows Server 2008 R2 에디션은 이 취약점의 영향을 받지 않습니다.<br />
<br />
이 취약점으로 인해 사용자가 특수하게 조작된 라이브러리 파일과 동일한 네트워크 폴더에 있는 .ins 또는 .isp 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 공격에 성공하려면, 사용자가 신뢰할 수 없는 원격 파일 시스템 위치 또는 WebDAV 공유를 방문하거나 이러한 위치에서 취약한 응용 프로그램이 로드되는 문서를 열어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-098">MS10-098</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2436673)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점 1건과 비공개적으로 보고된 여러 취약점을 해결합니다. 이 취약점으로 인해 공격자가 시스템에 로컬로 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-099">MS10-099</a></td>
<td style="border:1px solid black;"><strong>라우팅 및 원격 액세스의 취약점으로 인한 권한 상승 문제점(2440591)</strong><br />
<br />
이 보안 업데이트는 비공개로 보고된 Microsoft Windows의 라우팅 및 원격 액세스 NDProxy 구성 요소의 취약점을 해결합니다. 이 보안 업데이트의 심각도는 지원 대상인 모든 Windows XP 및 Windows Server 2003 에디션에 대해 중요입니다. 지원 대상인 모든 Windows Vista, Windows Server 2008, Windows 7 및 Windows Server 2008 R2 에디션은 이 취약점의 영향을 받지 않습니다.<br />
<br />
이 취약점으로 인해 공격자가 영향을 받는 시스템에 로그온한 후 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-100">MS10-100</a></td>
<td style="border:1px solid black;"><strong>동의 사용자 인터페이스의 취약점으로 인한 권한 상승 문제점(2442962)</strong><br />
<br />
이 보안 업데이트는 동의 사용자 인터페이스(UI)의 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 공격자가 영향을 받는 시스템에서 특수 조작된 응용 프로그램을 실행하면 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명 및 SeImpersonatePrivilege를 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-101">MS10-101</a></td>
<td style="border:1px solid black;"><strong>Windows Netlogon 서비스의 취약점으로 인한 서비스 거부 문제점(2207559)</strong><br />
<br />
이 보안 업데이트는 도메인 컨트롤러로 작동하도록 구성된 영향을 받는 Windows Server 버전에서 Netlogon RPC 서비스의 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 RPC 패킷을 영향을 받는 시스템의 Netlogon RPC 서비스 인터페이스로 보낼 경우 서비스 거부가 발생할 수 있습니다. 공격자는 이러한 취약점을 이용하기 위해 영향 받는 도메인 컨트롤러와 동일한 도메인에 가입된 시스템에 대한 관리자 권한이 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-102">MS10-102</a></td>
<td style="border:1px solid black;"><strong>Hyper-V의 취약점으로 인한 서비스 거부 문제점(2345316)</strong><br />
<br />
이 보안 업데이트는 Windows Server 2008 Hyper-V 및 Windows Server 2008 R2 Hyper-V에서 발견되어 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 Hyper-V 서버에서 호스팅하는 게스트 가상 컴퓨터 중 하나의 인증된 사용자가 특수하게 조작된 패킷을 VMBus로 보낼 경우 서비스 거부가 발생할 수 있습니다. 공격자는 이 취약점을 악용하기 위해 유효한 로그온 자격 증명이 있어야 하며 특수하게 조작된 콘텐츠를 게스트 가상 시스템에서 전송할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-103">MS10-103</a></td>
<td style="border:1px solid black;"><strong>Microsoft Publisher의 취약점으로 인한 원격 코드 실행 문제점(2292970)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 취약점 5건을 해결합니다. 사용자가 특수하게 조작된 Publisher 파일을 열면 이 Microsoft Publisher 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 어느 것이든 성공적으로 악용한 경우 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-104">MS10-104</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint의 취약점으로 인한 원격 코드 실행 문제점(2455005)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft SharePoint의 취약점을 해결합니다. 이 취약점으로 인해 문서 변환 부하 분산 서비스를 사용하는 SharePoint 서버 환경에서 공격자가 특수하게 조작된 SOAP 요청을 문서 변환 시작 관리자 서비스에 보낼 경우 게스트 사용자의 보안 컨텍스트에서 원격 코드 실행이 허용될 수 있습니다. 기본적으로 문서 변환 부하 분산 서비스 및 문서 변환 시작 관리자 서비스는 Microsoft Office SharePoint Server 2007에서 사용되지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft SharePoint</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-105">MS10-105</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 그래픽 필터의 취약점으로 인한 원격 코드 실행 문제점(968095)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 7건을 해결합니다. 이러한 취약점은 사용자가 Microsoft Office를 사용하여 특수하게 조작된 이미지 파일을 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-106">MS10-106</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server의 취약점으로 인한 서비스 거부 문제점(2407132)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Exchange Server의 취약점을 해결합니다. 이 취약점으로 인해 인증된 공격자가 Exchange 서비스를 실행하는 컴퓨터에 특수하게 조작된 네트워크 메시지를 보낼 경우 서비스 거부가 발생할 수 있습니다. 최선의 방화벽 구성 방법과 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 들어오는 공격으로부터 네트워크를 보호할 수 있습니다. 인터넷과 연결되는 시스템의 경우, 필요한 포트만 최소한으로 열어 두는 것이 안전합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">보통</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 악용 가능성 평가 수준 내림차순 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/ko-kr/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 취약점 제목                                                    | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                        | 주요 정보                                                 |  
|---------------------------------------------------------------------|----------------------------------------------------------------|-----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|-----------------------------------------------------------|  
| [MS10-103](http://technet.microsoft.com/security/bulletin/ms10-103) | pubconv.dll의 크기 값 힙 손상 취약점                           | [CVE-2010-2569 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2569) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-103](http://technet.microsoft.com/security/bulletin/ms10-103) | pubconv.dll의 힙 오버런 취약점                                 | [CVE-2010-2570 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2570) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-097](http://technet.microsoft.com/security/bulletin/ms10-097) | 인터넷 연결 등록 마법사의 안전하지 않은 라이브러리 로드 취약점 | [CVE-2010-3144 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3144) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 공개되었습니다.**                           |  
| [MS10-096](http://technet.microsoft.com/security/bulletin/ms10-096) | 안전하지 않은 라이브러리 로드 취약점                           | [CVE-2010-3147 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3147) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 공개되었습니다.**                           |  
| [MS10-092](http://technet.microsoft.com/security/bulletin/ms10-092) | 작업 스케줄러 취약점                                           | [CVE-2010-3338 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3338) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 인터넷 생태계에서 악용되고 있습니다.**      |  
| [MS10-090](http://technet.microsoft.com/security/bulletin/ms10-090) | HTML 개체 메모리 손상 취약점                                   | [CVE-2010-3340 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3340) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-090](http://technet.microsoft.com/security/bulletin/ms10-090) | HTML 개체 메모리 손상 취약점                                   | [CVE-2010-3343 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3343) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-090](http://technet.microsoft.com/security/bulletin/ms10-090) | HTML 요소 메모리 손상 취약점                                   | [CVE-2010-3345 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3345) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-090](http://technet.microsoft.com/security/bulletin/ms10-090) | HTML 요소 메모리 손상 취약점                                   | [CVE-2010-3346 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3346) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k 버퍼 오버플로 취약점                                    | [CVE-2010-3939 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3939) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 공개되었습니다.**                           |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k PFE 포인터 Double Free 취약점                           | [CVE-2010-3940 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3940) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k 커서 연결 취약점                                        | [CVE-2010-3943 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3943) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k 메모리 손상 취약점                                      | [CVE-2010-3944 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3944) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | FlashPix 이미지 변환기 버퍼 오버플로 취약점                    | [CVE-2010-3951 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3951) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-091](http://technet.microsoft.com/security/bulletin/ms10-091) | OpenType 글꼴 Double Free 취약점                               | [CVE-2010-3957 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3957) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-091](http://technet.microsoft.com/security/bulletin/ms10-091) | OpenType CMAP 테이블 취약점                                    | [CVE-2010-3959 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3959) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-100](http://technet.microsoft.com/security/bulletin/ms10-100) | 동의 UI 가장 취약점                                            | [CVE-2010-3961 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3961) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-090](http://technet.microsoft.com/security/bulletin/ms10-090) | 초기화되지 않은 메모리 손상 취약점                             | [CVE-2010-3962 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3962) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.** |  
| [MS10-099](http://technet.microsoft.com/security/bulletin/ms10-099) | 커널 NDProxy 버퍼 오버플로 취약점                              | [CVE-2010-3963 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3963) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-104](http://technet.microsoft.com/security/bulletin/ms10-104) | 조작된 요청 코드 실행 취약점                                   | [CVE-2010-3964 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3964) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-094](http://technet.microsoft.com/security/bulletin/ms10-094) | 안전하지 않은 라이브러리 로드 취약점                           | [CVE-2010-3965 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3965) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 공개되었습니다.**                           |  
| [MS10-095](http://technet.microsoft.com/security/bulletin/ms10-095) | BranchCache 안전하지 않은 라이브러리 로드 취약점               | [CVE-2010-3966 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3966) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-093](http://technet.microsoft.com/security/bulletin/ms10-093) | 안전하지 않은 라이브러리 로드 취약점                           | [CVE-2010-3967 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3967) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 공개되었습니다.**                           |  
| [MS10-103](http://technet.microsoft.com/security/bulletin/ms10-103) | Pubconv.dll의 배열에 잘못된 인덱스로 인한 메모리 손상 취약점   | [CVE-2010-2571 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2571) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k Double Free 취약점                                      | [CVE-2010-3941 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3941) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-098](http://technet.microsoft.com/security/bulletin/ms10-098) | Win32k WriteAV 취약점                                          | [CVE-2010-3942 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3942) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | CGM 이미지 변환기 버퍼 오버런 취약점                           | [CVE-2010-3945 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3945) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | PICT 이미지 변환기 정수 오버플로 취약점                        | [CVE-2010-3946 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3946) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | TIFF 이미지 변환기 힙 오버플로 취약점                          | [CVE-2010-3947 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3947) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | TIFF 이미지 변환기 버퍼 오버플로 취약점                        | [CVE-2010-3949 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3949) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | TIFF 이미지 변환기 메모리 손상 취약점                          | [CVE-2010-3950 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3950) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-105](http://technet.microsoft.com/security/bulletin/ms10-105) | FlashPix 이미지 변환기 힙 손상 취약점                          | [CVE-2010-3952 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3952) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-103](http://technet.microsoft.com/security/bulletin/ms10-103) | 배열 인덱싱 메모리 손상 취약점                                 | [CVE-2010-3955 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3955) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-091](http://technet.microsoft.com/security/bulletin/ms10-091) | OpenType 글꼴 인덱스 취약점                                    | [CVE-2010-3956 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3956) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-101](http://technet.microsoft.com/security/bulletin/ms10-101) | Netlogon RPC Null 역참조 DOS 취약점                            | [CVE-2010-2742 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2742) | [**3**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) – 악용 코드 기능 불가능     | 이는 단지 서비스 거부 취약점일 뿐입니다.                  |  
| [MS10-106](http://technet.microsoft.com/security/bulletin/ms10-106) | Exchange Server 무한 루프 취약점                               | [CVE-2010-3937 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3937) | [**3**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) – 악용 코드 기능 불가능     | 이는 단지 서비스 거부 취약점일 뿐입니다.                  |  
| [MS10-103](http://technet.microsoft.com/security/bulletin/ms10-103) | Microsoft Publisher 메모리 손상 취약점                         | [CVE-2010-3954 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3954) | [**3**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) – 악용 코드 기능 불가능     | (없음)                                                    |  
| [MS10-102](http://technet.microsoft.com/security/bulletin/ms10-102) | Hyper-V VMBus 취약점                                           | [CVE-2010-3960 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3960) | [**3**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) – 악용 코드 기능 불가능     | 이는 단지 서비스 거부 취약점일 뿐입니다.                  |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
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
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6031d98a-cd0f-4dd8-80b6-70a7167e9e55&displaylang=ko)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=922a0835-7f69-4e37-a9f7-c64e976e3513&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=a55b8029-9499-4219-99b7-65c30b0b864a&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=cdef3358-ad3e-40a6-9ba5-3be220a56a65&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=46baa431-126c-4fa5-9a7b-525008e2817d&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=fa9a1aac-b9c5-4d4e-9083-a080ad4ccc6f&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=bb9d1657-5beb-4372-b74c-a612a6fff5a8&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=4d0ae558-a4f2-4048-b5fd-ba072ca35e48&displaylang=ko)  
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=5d3a5678-77f8-4ebc-8775-aedd25ef0eb8)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a7c826b0-4aac-41ce-b297-6b6e11105c14)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d5207bf5-7e58-4001-aa8f-f9a4b2c037d8)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=070fef8e-ba09-40f4-abaa-9cebf08983c3)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d&displaylang=ko)  
(중요)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9ce9d62-2eaa-48d8-bb6d-ea137e63d077)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6dabc306-c858-46b1-815c-cd8d011ff62e)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1f277ae4-4f85-4c8a-bfc5-dcdc8afed133)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=238bb885-eae6-464a-bb3d-679025f1cb50)  
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
</tr>
<tr>
<th style="border:1px solid black;" colspan="14">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=4f1f41fb-368a-42e6-8d17-fca83b64f57b&displaylang=ko)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a3b57d26-5551-4785-86cf-41b532d78979&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4f5a3677-0990-4702-bf08-af64cf12cb6c&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9b70334c-490d-446c-988a-a88a75595fd4&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0b2837c-019b-419b-954d-5bdc71a3a332&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8fa2cfa4-a01d-4910-b69f-736aeb585bab&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4aa39f59-2177-459f-9b8a-9543330d48ec&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c87af292-a068-4089-aab8-115c18b4b024&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad843b97-2f6e-4406-a17a-627b7db8a926&displaylang=ko)  
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6a9f56a0-230a-4dde-94da-f051ebf51f47&displaylang=ko)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8b0d2a3a-7fed-4d48-9ec5-8558000e51bb&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1e134e5d-84fb-432b-99b1-593b1be5d5a4&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=08328e82-b012-4ea5-bf89-becb4881084f&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d&displaylang=ko)  
(중요)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4c5cb600-9a39-40a0-be42-1593b1e0b97d&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=17b0b340-73b2-42a7-9d86-1297c63dcc2b&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=bca61d61-d5cf-49a4-ab99-b61e50e8f619&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e17b8878-d065-49cc-bdba-0f24cdf35ea3&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=0b0a06e7-0ae5-41f4-9ff5-d524fc0afbfa&displaylang=ko)  
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7c1cf126-604c-4f70-bbe8-aa4d145eb68f)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=96884bfa-00c8-4263-9936-d7c054919dd3)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=15588d6a-f576-4e3d-95e8-d422af8a94de)  
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
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=9abc8270-f3ac-474d-9ebc-410aaa6262cc)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=04a178cc-1afd-4e47-8cab-05e402e5a568)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=4fce129d-2b4e-4a66-af27-bbbde1e65ba1)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ad896d80-167f-4e8f-a448-cac93516f4d0)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=7c0c2850-e81d-4347-aeb3-47036caa7c1b)  
(중요)
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
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
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
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=897351de-9697-4954-aa7e-169e980b932c&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=bebf0df0-5ebe-44b4-9ace-b3085a993e58&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=2ddb8a06-c9cc-4d33-b6d1-22dbda2d871f&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f10251-34d8-4149-b4b2-bf3ec28f5846&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=55141a02-3ad3-4691-98b9-80dd8ecb14c5&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=e8a57950-43cd-486f-bd97-70b0ad360a0b&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a1c7f1b5-e054-4cd6-857d-2ab0a2fe9f62&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b824d3b9-2ce1-4abc-ae06-68aef1250be9&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=85265a23-5094-4007-8d33-f402cabd1664&displaylang=ko)  
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
Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=171c02f9-f7d2-42f2-ba31-4c819a43784a&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=837b6056-af04-4aed-8afe-cc392770a590&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9a245f3c-ffb6-4ccd-956c-e7d1231fca30&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=099ccc5f-b92f-4d06-bcb5-92e35c49f613&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=5b078136-a492-4a2e-939d-82799f774d82&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=f98c3b96-acb5-49f1-be42-3dd44d316408&displaylang=ko)  
(중요)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=e1054088-f484-4f44-ba0e-5cbd21773c0c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=73624b68-a69d-4517-b971-f0b7d2ccc9d6&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f4c42cfe-b7f2-4436-919e-4bd305a3439a&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=63c7257a-16bf-4108-80b9-9dfe53528348new&displaylang=ko)  
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
<th style="border:1px solid black;" colspan="14">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
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
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f3785f3b-64c6-46a4-8e3a-9b9448124a8f&displaylang=ko)\*\*  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=98183a76-5642-4e19-b488-029eb7ed3942&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=87149ec2-74a8-4dea-b7e3-873558e0103e&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=bdc9564a-4091-4cde-963a-239513db6c17&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=a4ea028f-edfc-4237-8325-7ece11fcf437&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=118f528f-bd05-49c2-a4a4-78314cd00992&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e2f572a-4169-47f2-a872-5466997122ed&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=14e079a8-01a4-47c9-bd47-f5c9a6ca070a&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6793f75b-cdf4-42ef-a53e-a1acb5b662d1&displaylang=ko)\*  
(중요)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4b81aae5-6034-4c83-b5d2-e7e472435284&displaylang=ko)\*\*  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d47b457d-e995-4a7e-9bfa-eebab9b3a729&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=523a47d3-771d-471a-889b-16311c276a00&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=dff39bfe-0799-4912-ae22-392562178ae6&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=f468d2b5-f02c-4691-9fb5-a7f69752f126&displaylang=ko)\*\*  
(중요)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=533d91d8-0291-421e-9701-3bd86d18bc45&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=77e288fb-b51f-4f57-baac-1443d8fbd37b&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=09a4b646-989d-43ef-a3e8-64af8b380a14&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6baf92b7-a336-45f2-a1ba-c00c34dfb76f&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=85add876-ca5a-4a92-984e-188a72e349fc&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8c06bbc-6e84-4cf1-89f0-c0d34cfffaed&displaylang=ko)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8ddafaaf-84a0-4325-b06f-4aac7cd61274)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=959146ee-0e70-4e56-9012-72ed59aeb24b)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=cf341a35-32ea-4ff7-aca9-1a4683c100ee)  
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
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=82f71194-6f1f-4f43-8752-4bf5e5f94a93)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=46522323-837e-4a74-9cf0-45f69343e776)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7a4b23d4-f68e-4d5b-8814-d9247145f164)  
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
<th style="border:1px solid black;" colspan="14">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c288fe87-b113-4615-9b02-5e388bcb5241&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ff590db8-4264-42ba-9e07-88d100e1c4f5&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=cf85cdb6-58c7-4144-82f6-f01a6a4f9c3a&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=75591d37-2cb8-4cdf-acbb-89cd0d1a9290&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=4e8ad5cd-af27-4f00-9378-ad778b8ee7b3&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=aa7de2e4-ba48-4d58-b034-05349f0eb920&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=f7c7d57a-d031-46a3-9613-eae2b9cb6401&displaylang=ko)  
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
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2cf4ac70-88b4-4840-9895-2bcf119312a7&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=4ea4e339-9db2-4b99-b567-80ee55ecdf92&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=0597018d-39f5-4ca9-b437-63d9e68f264d&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=3a0c4dd0-98b4-4e7a-99ed-22b9d9f76cd1&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=35a3e821-b463-411c-858b-d01eb5aed42b&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b21db627-91c2-4ebf-b7c0-38ac58ae5b6c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=e52c36f5-637b-4928-83d0-27514c6cc384&displaylang=ko)  
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
<th style="border:1px solid black;" colspan="14">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://technet.microsoft.com/security/bulletin/ms10-092)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://technet.microsoft.com/security/bulletin/ms10-102)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=99a91ba7-035b-4717-ada5-c1ad6645db64&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=e52f7869-474a-44c8-a102-e766c576fc01&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=28c832fb-4937-4652-8799-eab6c76d05fb&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=f58a765f-cea9-456d-b0ab-bfc70b109cbf&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=9e2c95f6-9381-4484-b11b-814ab9138118&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=d417ebce-7841-4bbb-8abc-b15ef5f4b733&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b823a7aa-0eb9-42dd-bf56-8907d94b314a&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=d7307afd-84a0-434e-9658-bf9f8ae4b938&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=39b7abc7-65a4-4dfd-92ba-c638e3de1118&displaylang=ko)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c26de145-94b8-404a-b946-744988fab83b)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=a21d061a-794a-4012-b3cd-c67445c074f5)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=3ad64d5c-2d81-4ac8-934e-8917b2fcf961)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=13a9f838-ac07-43dc-9aee-a77207998e1e)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=cb4211f3-1082-4245-8f03-7cbac90e9a31)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=7eeac1bb-9f86-4ea5-b30f-980d52be5044)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=66b2506d-80e0-4e32-86e6-0908ef56ae90)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**Windows Server 2008 및 Windows Server 2008 R2 참고 사항**

**\*Server Core 설치가 영향을 받습니다.** 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리 (영문)](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스 (영문)](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

**\*\*Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리 (영문)](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스 (영문)](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

**MS10-093 참고 사항**

<sup>[1]</sup>Windows Movie Maker 2.6은 표시된 운영 체제에 설치할 수 있는 선택적 다운로드입니다.

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
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-103**](http://technet.microsoft.com/security/bulletin/ms10-103)
</td>
<td style="border:1px solid black;">
[**MS10-105**](http://technet.microsoft.com/security/bulletin/ms10-105)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2002 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=f540692c-e404-4383-8937-4d6a36475da5&displaylang=ko)  
(KB2284692)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=724d0ad6-ba5f-4dbf-b280-3fb36335d33b&displaylang=ko)<sup>[1]</sup>
(KB2289162)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=e600de65-3e9d-4e37-8906-8b7091ff523e&displaylang=ko)  
(KB2284695)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=976857e9-77fc-4667-88ca-7637e57536cd&displaylang=ko)<sup>[1]</sup>
(KB2289163)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=79275011-bdc1-446a-8ea6-56fc31bd9c35&displaylang=ko)  
(KB2284697)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=676eeed6-f2b7-4265-afc7-a82ffdbeb290&displaylang=ko)  
(KB2288931)  
(심각도 없음<sup>[1]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2010(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=99e18990-75e9-497e-9b4f-5d7ef8656ab2&displaylang=ko)  
(KB2409055)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=6d644494-b530-4b37-bc37-8a8a7edefe53&displaylang=ko)  
(KB2289078)  
(심각도 없음<sup>[1]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2010(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=9b27ee11-e563-4152-9691-25eec1ee9966&displaylang=ko)  
(KB2409055)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=58e54779-aa8f-41b3-9993-8cec12c49082&displaylang=ko)  
(KB2289078)  
(심각도 없음<sup>[1]</sup>)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
기타 Office 소프트웨어
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-103**](http://technet.microsoft.com/security/bulletin/ms10-103)
</td>
<td style="border:1px solid black;">
[**MS10-105**](http://technet.microsoft.com/security/bulletin/ms10-105)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 변환 팩
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 변환 팩](http://www.microsoft.com/downloads/details.aspx?familyid=dcded2ee-0673-4afe-abe6-04941a2ad306)  
(KB2456849)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=10f6f330-05d8-4b60-9ebb-822a7321ac0f&displaylang=ko)  
(KB2431831)  
(중요)
</td>
</tr>
</table>
 
**MS10-105 참고 사항**

<sup>[1]</sup>표시된 소프트웨어를 사용하는 고객은 MS10-105에서 설명하는 취약점으로부터 보호하기 위해 MS10-087에서 제공하는 Microsoft Office 업데이트도 설치해야 합니다.

<sup>[2]</sup>이 공지에서 설명한 취약점이 이 소프트웨어에 영향을 미치지 않으므로 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 나중에 발생 가능한 새로운 경로를 방지하기 위한 심층적인 보안 대응책으로써 이 소프트웨어를 사용하는 고객은 이 보안 업데이트를 적용하는 것이 좋습니다.

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
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-104**](http://technet.microsoft.com/security/bulletin/ms10-104)
</td>
<td style="border:1px solid black;">
[**MS10-106**](http://technet.microsoft.com/security/bulletin/ms10-106)
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
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 서비스 팩 2(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 서비스 팩 2(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=3c8fb9f9-7920-43ea-b618-e26dc3360c60&displaylang=ko)  
(KB2433089)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 서비스 팩 2(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 서비스 팩 2(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=3db09280-24bd-42e0-9ae3-02c9bf3e8ee3&displaylang=ko)  
(KB2433089)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
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
[**MS10-104**](http://technet.microsoft.com/security/bulletin/ms10-104)
</td>
<td style="border:1px solid black;">
[**MS10-106**](http://technet.microsoft.com/security/bulletin/ms10-106)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 서비스 팩 2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 서비스 팩 2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=7b983156-9e9f-4d29-9e9b-2369747e3b62&displaylang=ko)  
(KB2407132)  
(보통)
</td>
</tr>
</table>
 

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인 (영문)](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)을 참조하십시오.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

**System Center** **Configuration Manager 2007**

Configuration Manager 2007 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. Configuration Manager 2007을 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

Configuration Manager 2007의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. Configuration Manager 2007의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. 관리자가 Configuration Manager 2007을 사용하여 업데이트를 배포하는 방법에 대한 자세한 내용은 [소프트웨어 업데이트 관리](http://www.microsoft.com/systemcenter/ko/kr/configuration-manager/cm-software-update-management.aspx)를 참조하십시오. Configuration Manager에 대한 자세한 내용을 보려면 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/ko/kr/configuration-manager.aspx)를 방문하십시오.

**Systems Management Server 2003**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

**참고** System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 방문하십시오. 현재 다음 릴리스의 SMS, System Center Configuration Manager 2007을 사용할 수 있습니다. 이전 섹션 **SystemCenter Configuration Manager 2007**을 참조하십시오.

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter (영문)](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)를 방문하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트 (영문)](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](http://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS10-090에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Aniway
-   MS10-090에서 설명한 문제점을 보고해 주신 [VUPEN Vulnerability Research Team (영문)](http://www.vupen.com/)의 Nicolas Joly
-   MS10-090에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Stephen Fewer
-   MS10-090에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 [Peter Vreugdenhil (영문)](http://vreugdenhilresearch.nl/)
-   MS10-090에서 설명한 문제점을 해결하기 위해 협력해 주신 [Yosuke Hasegawa (일문)](http://utf-8.jp/)
-   MS10-090에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Jose Antonio Vazquez Gonzalez
-   MS10-091에서 설명한 문제점을 [Opera Security Team (영문)](http://www.opera.com/security/)과 협력하여 보고해 주신 [Red Hat Security Response Team (영문)](https://www.redhat.com/security/team/)의 Marc Schoenefeld
-   MS10-091에서 설명한 문제점을 보고해 주신 [Red Hat Security Response Team (영문)](https://www.redhat.com/security/team/)의 Marc Schoenefeld
-   MS10-091에서 설명한 문제점을 보고해 주신 Paul-Kenji Cahier Furuya
-   MS10-092에서 설명한 문제점을 보고해 주신 [Kaspersky Lab (영문)](http://usa.kaspersky.com/)의 Sergey Golovanov, Alexander Gostev, Maxim Golovkin 및 Alexey Monastyrsky와 [Design and Test Lab (영문)](http://www.dnt-lab.com/)의 Vitaly Kiktenko 및 Alexander Saprykin
-   MS10-092에서 설명한 문제점을 보고해 주신 [Symantec (영문)](http://www.symantec.com/index.jsp)의 Liam O Murchu
-   MS10-092에서 설명한 문제점을 보고해 주신 [ESET (영문)](http://www.eset.com/)의 Alexandr Matrosov, Eugene Rodionov, Juraj Malcho 및 David Harley
-   MS10-095에서 설명한 문제점을 보고해 주신 [Fortinet's FortiGuard Labs (영문)](http://www.fortiguard.com/)의 Haifei Li
-   MS10-096에서 설명한 문제점을 보고해 주신 [ACROS Security (영문)](http://www.acrossecurity.com/)의 Simon Raner
-   MS10-096에서 설명한 문제점을 보고해 주신 [Rapid7 (영문)](http://www.rapid7.com/)의 HD Moore
-   MS10-096에서 설명한 문제점을 보고해 주신 [NGS Software (영문)](http://www.ngssoftware.com/)의 Muhaimin Dzulfakar
-   MS10-097에서 설명한 문제점을 보고해 주신 [NGS Software (영문)](http://www.ngssoftware.com/)의 Muhaimin Dzulfakar
-   MS10-098에서 설명한 문제점을 보고해 주신 [Norman (영문)](http://www.norman.com/)의 Tarjei Mandt
-   MS10-098에서 설명한 문제점을 보고해 주신 [Sysdream (영문)](http://www.sysdream.com/)의 Stéfan Le Berre
-   MS10-099에서 설명한 문제점을 보고해 주신 [Fortinet's FortiGuard Labs (영문)](http://www.fortiguard.com/)의 Honggang Ren
-   MS10-100에서 설명한 문제점을 보고해 주신 [Argeniss (영문)](http://www.argeniss.com/)의 Cesar Cerrudo
-   MS10-101에서 설명한 문제점을 보고해 주신 The Samba Team의 Matthias Dieter Wallnöfer 및 Andrew Bartlett
-   MS10-102에서 설명한 문제점을 보고해 주신 [HP](http://www.hp.com/) 및 [techit (영문)](http://www.techit.de/)
-   MS10-103에서 설명한 다섯 가지 문제점을 보고해 주신 [VUPEN Vulnerability Research Team (영문)](http://www.vupen.com/)의 Chaouki Bekrar
-   MS10-104에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Oleksandr Mirosh
-   MS10-105에서 설명한 두 가지 문제점을 보고해 주신 [Palo Alto Networks (영문)](http://www.paloaltonetworks.com/)의 Yamata Li
-   MS10-105에서 설명한 문제점을 보고해주신 [Secunia Research (영문)](http://secunia.com/)의 Alin Rad Pop
-   MS10-105에서 설명한 세 가지 문제점을 보고해 주신 [Secunia Research (영문)](http://secunia.com/)의 Carsten Eiram
-   MS10-105에서 설명한 두 가지 문제점을 보고해 주신 [Secunia Research (영문)](http://secunia.com/)의 Dyon Balding
-   MS10-106에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Oleksandr Mirosh

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원 (영문)](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2010년 12월 15일): 공지 요약이 게시되었습니다.
-   V1.1(2010년 12월 16일): Microsoft Office XP 및 Microsoft Office 2003의 고객은 MS10-105에서 설명하는 취약점으로부터 보호하기 위해 MS10-087에서 제공하는 업데이트를 적용해야 한다는 설명이 추가되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
