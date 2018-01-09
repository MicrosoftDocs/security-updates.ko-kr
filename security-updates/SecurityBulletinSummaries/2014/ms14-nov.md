---
TOCTitle: 'MS14-NOV'
Title: 2014년 11월 Microsoft 보안 공지 요약
ms:assetid: 'ms14-nov'
ms:contentKeyID: 63355344
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms14-nov(v=Security.10)'
---

2014년 11월 Microsoft 보안 공지 요약
====================================

게시된 날짜: 2014년 11월 11일 | 업데이트된 날짜: 2014년 12월 18일

**Version:** 2.1

이 공지 요약 목록에는 2014년 11월에 발표된 보안 공지가 포함되어 있습니다.

2014년 11월 보안 공지 발표와 함께 이 공지 요약이 2014년 11월 6일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

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
<td style="border:1px solid black;"><strong>공지 제목 및 요약</strong></td>
<td style="border:1px solid black;"><strong>최대 심각도 및 취약점 영향</strong></td>
<td style="border:1px solid black;"><strong>다시 시작 요구 사항</strong></td>
<td style="border:1px solid black;"><strong>영향을 받는 소프트웨어</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518106">MS14-064</a></td>
<td style="border:1px solid black;"><strong>Windows OLE의 취약점으로 인한 원격 코드 실행 문제점 (3011443)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows 개체 연결 및 포함 (OLE)에 대한 취약점 2 건을 해결 합니다. 해당 취약점으로 인해 사용자가 특수하게 조작된 OLE 개체를 포함하는 Microsoft Office 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의로 코드를 실행할 수 있습니다. 현재 사용자가 관리자 권한으로 로그인 한 경우 공격자는 프로그램을 설치하여 데이터 보거나 변경, 삭제, 또는 관리자 권한이 있는 새 계정 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 사용자에 비해서는 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 용 누적 보안 업데이트 (3003057)<br />
<br />
</strong>이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 17건을 해결합니다. 가장 심각한 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518112">MS14-066</a></td>
<td style="border:1px solid black;"><strong>Schannel의 취약점으로 인한 원격 코드 실행 문제점(2992611)<br />
<br />
</strong>이 보안 업데이트는 Windows의 Microsoft 보안 채널 (Schannel) 보안 패키지는 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 공격자가 Windows 서버에 특수하게 조작한 패킷을 보내는 경우 원격 코드 실행이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513100">MS14-067</a></td>
<td style="border:1px solid black;"><strong>XML Core Services의 취약점으로 인한 원격 코드 실행 문제점 (2993958)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점은 로그온한 사용자가 Internet Explorer를 통해 MSXML (Microsoft XML Core Services)이 실행되도록 특수하게 조작된 웹 사이트 방문하는 경우 원격 코드가 실행될 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 이러한 웹 사이트 방문하도록 만들 수 없습니다. 대신 공격자는 전자 메일 메시지 또는 메신저 요청의 사용자가 공격자의 웹 사이트에 있는 링크를 클릭하여 웹 사이트를 방문 하도록 유도 해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518109">MS14-068</a></td>
<td style="border:1px solid black;"><strong>Kerberos의 취약점으로 인한 권한 상승 문제점 (3011780)</strong>
이 보안 업데이트는 공격자가 신뢰할 수 없는 도메인 사용자 계정 권한에서 도메인 관리자 계정 권한으로 권한 상승 시킬수 있는 Microsoft Windows Kerberos KDC 의 비공개적으로 보고 된 취약점 1 건을 해결 합니다. 공격자는 도메인 컨트롤러가 포함 된 도메인에 있는 컴퓨터를 손상시키는데 이러한 권한 상승 취약점을 이용할 수 있습니다. 이 취약점을 악용 하려면 유효한 도메인 자격 증명을 가져야만 합니다. 표준 사용자 계정을 가진 사용자는 영향을 받는 구성요소를 원격으로 사용할 수 있습니다. 이는 로컬 사용자 계정 정보만을 가진 사용자는 해당되지 않습니다. 이 보안 공지가 게시될 때, Microsoft는 이 취약점을 악용하려는 제한적인 공격에 대한 보고를 받았습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518105">MS14-069</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점 (3009710)<br />
<br />
</strong>이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 3건을 해결합니다. 이 취약점으로 인해 영향을 받는 버전의 Microsoft Office 2007에서 특수하게 조작 된 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507675">MS14-070</a></td>
<td style="border:1px solid black;"><strong>TCP/IP의 취약점으로 인한 권한 상승 문제점 (2989935)<br />
<br />
</strong>이 보안 업데이트는 공개적으로 보고된 TCP/IP의 입/출력 제어 (<a href="https://technet.microsoft.com/ko-kr/library/security/dn848375.aspx">IOCTL</a>) 프로세싱에 대한 취약점을 해결합니다.<strong></strong>이 취약점은 공격자가 시스템에 로그온하여 특수하게 조작된 응용 프로그램을 실행하는 경우에 권한 상승이 발생할 수 있습니다.이 취약점 악용에 성공한 공격자는 다른 프로세스의 컨텍스트에서 임의 코드를 실행할 수 있습니다. 이 프로세스가 관리자 권한으로 실행되는 경우 공격자가 프로그램을 설치할 수 있을 뿐만 아니라 보기, 변경, 데이터 삭제 및 모든 사용자 권한으로 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518113">MS14-071</a></td>
<td style="border:1px solid black;"><strong>Windows 오디오 서비스의 취약점으로 인한 권한 상승 문제점 (3005607)<br />
<br />
</strong> 이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점은 응용 프로그램이 Microsoft Windows 오디오 서비스를 사용할 때 권한 상승 취약점이 있습니다. 이 취약점만으로는 임의의 코드 실행을 할 수 없습니다. 그러나 공격자는 이 취약점을 원격 코드 실행을 허용하는 또 다른 취약점과 연결하여 악용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518107">MS14-072</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 취약점으로 인한 권한 상승 문제점 (3005210)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고된 Microsoft.NET Framework의 취약점을 해결합니다. 이 취약점은 공격자가 영향을 받는 워크스테이션 또는.NET Remoting을 사용하여 서버에 특수하게 조작된 데이터를 보내는 경우 권한 상승이 허용될 수 있습니다. .NET remoting 응용 프로그램에서 널리 사용 되지 않습니다. 시스템 취약점을 노출시키는 .NET Remoting은 사용자 지정 응용 프로그램에만 사용하도록 특별히 설계되었습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513105">MS14-073</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Foundation의 취약점으로 인한 권한 상승 (3000431)<br />
<br />
</strong> 이 보안 업데이트는 Microsoft SharePoint Server의 비공개적으로 보고된 취약점을 해결합니다. 이 취약점 악용에 성공한 인증된 공격자는 현재의 SharePoint 사이트의 사용자 컨텍스트에서 임의의 스크립트 실행할 수 있습니다. 웹 기반 공격 시나리오에서 공격자는 이러한 취약점을 악용하도록 설계된 특수하게 조작된 웹 사이트를 호스팅하여 사용자가 이 웹사이트를 보도록 유도할 수 있습니다. 공격자는 사용자가 제공한 콘텐츠나 광고를 허용하거나 호스팅하는 웹 사이트와 공격에 노출된 웹 사이트를 이용할 수도 있습니다. 이러한 웹 사이트에는 취약점을 악용하는 특수하게 조작된 콘텐츠가 포함될 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 공격자 제어 콘텐츠를 보도록 만들 수는 없습니다. 대신 공격자는 일반적으로 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하게 하거나 전자 메일을 통해 보낸 첨부 파일을 열어서 어떤 행동을 수행하도록 유도 해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518111">MS14-074</a></td>
<td style="border:1px solid black;"><strong>원격 데스크톱 프로토콜의 취약점으로 인한 보안 기능 우회 (3003743)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고 된 Microsoft Windows의 취약점을 해결합니다. 이 취약점은 원격 데스크톱 프로토콜 (RDP)이 제대로 감사 이벤트를 기록 하지 못하는 경우 보안 기능을 우회하는 것이 허용될 수 있습니다. RDP는 모든 Windows 운영 체제에서 기본으로 비활성화 되어 있습니다. RDP가 기본으로 활성화되어 있지 않은 시스템은 취약하지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">MS14-075</td>
<td style="border:1px solid black;">추후 릴리즈 예정</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509986">MS14-076</a></td>
<td style="border:1px solid black;"><strong>인터넷 정보 서비스 (IIS)의 취약점으로 인한 보안 기능 우회 (2982998)<br />
<br />
</strong> 이 보안 업데이트는 Microsoft에 비공개적으로 보고된 <a href="https://technet.microsoft.com/en-us/library/security/dn848375.aspx">인터넷 정보 서비스 (IIS)</a>의 &quot;IP 및 도메인 제한&quot; 보안 기능을 우회 할 수 있는 취약점을 해결 합니다. 이 취약점 악용에 성공한 경우에 제한된 도메인 또는 차단된 도메인의 제한된 웹 리소스에 접근 할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518108">MS14-077</a></td>
<td style="border:1px solid black;"><strong>Active Directory Federation Services의 취약점으로 인한 정보 유출 문제점 (3003381)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고된 Active Directory Federation Services(ADFS)의 취약점을 해결합니다. 이 취약점은 사용자가 어플리케이션 로그 오프 후 브라우저를 그대로 열어둔 경우에 공격자는 사용가 로그 오프 후에 즉시 브라우저에서 어플리케이션을 다시 실행시켜 정보 유출을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509952">MS14-078</a></td>
<td style="border:1px solid black;"><strong>Microsoft IME(일본어)의 취약점으로 인한 권한 상승 문제점 (2992719)<br />
<br />
</strong> 이 보안 업데이트는 <a href="https://technet.microsoft.com/en-us/library/security/dn848375.aspx">Microsoft IME</a>(일본어)에서 비공개적으로 보고된 취약점을 해결합니다. 이 취약점은 Microsoft IME(일본어)의 영향을 받는 버전이 설치된 시스템에서 응용 프로그램 샌드박스 정책에 따라 샌드박스 예외 처리를 허용할 수 있습니다. 이 취약점을 성공적으로 악용한 공격자는 취약한 응용 프로그램의 샌드박스를 벗어나 로그인한 사용자 권한으로 영향을 받는 시스템에 액세스할 수 있습니다. 영향을 받은 시스템이 관리자 권한으로 로그인된 경우 공격자는 프로그램을 설치하여 데이터를 보거나 변경하거나 삭제하거나, 모든 관리자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">보통</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518110">MS14-079</a></td>
<td style="border:1px solid black;"><strong>커널 모드 드라이버의 취약점으로 인한 서비스 거부 문제점 (3002885)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 공격자가 네트워크 공유에 특수하게 조작된 TrueType 글꼴을 배치하여 사용자가 Windows 탐색기에서 이를 열어 볼때 서비스 거부 취약점을 허용할 수 있습니다. 웹을 통한 공격의 경우 공격자는 이 취약점 악용 시도할 수 있는 웹페이지를 포함한 웹사이트를 호스팅할 수 있습니다. 또한 사용자가 제공한 콘텐츠나 광고를 허용하거나 호스팅하는 공격 당한 웹 사이트에는 이 취약점을 악용할 수 있는 특수하게 조작된 콘텐츠가 포함되어 있을 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 이러한 웹사이트를 방문하도록 할수는 없습니다. 대신 공격자는 사용자가 이러한 웹사이트를 방문하도록 유도해야 하며, 일반적으로 사용자를 공격자의 웹사이트로 유인하는 전자 메일 메시지 또는 인스턴트 메신저 메세지에 포함된 링크를 클릭하도록 하는 방법을 사용합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">보통</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
악용 가능성 인덱스  
------------------
  
<span id="sectionToggle1"></span>
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518106">MS14-064</a></td>
<td style="border:1px solid black;">Windows OLE 자동화 배열 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6332">CVE-2014-6332</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518106">MS14-064</a></td>
<td style="border:1px solid black;">Windows OLE 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6352">CVE-2014-6352</a></td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">Microsoft는 이 취약점을 악용 하려는 제한적인 공격을 인지하고 있습니다.<br />
<br />
이 취약점은 보안 권고 <a href="https://technet.microsoft.com/library/security/3010060.aspx">3010060</a> 에서 처음 기술되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4143">CVE-2014-4143</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 클립보드 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6323">CVE-2014-6323</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6337">CVE-2014-6337</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR 우회 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6339">CVE-2014-6339</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 보안 기능 우회 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 도메인 간 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6340">CVE-2014-6340</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6341">CVE-2014-6341</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6342">CVE-2014-6342</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6343">CVE-2014-6343</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6344">CVE-2014-6344</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 도메인 간 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6345">CVE-2014-6345</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 도메인 간 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6346">CVE-2014-6346</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6347">CVE-2014-6347</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6348">CVE-2014-6348</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6349">CVE-2014-6349</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 권한 상승 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6350">CVE-2014-6350</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 권한 상승 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6351">CVE-2014-6351</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6353">CVE-2014-6353</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518112">MS14-066</a></td>
<td style="border:1px solid black;">Microsoft 보안 채널 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6321">CVE-2014-6321</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513100">MS14-067</a></td>
<td style="border:1px solid black;">MSXML 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4118">CVE-2014-4118</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518109">MS14-068</a></td>
<td style="border:1px solid black;">Kerberos Checksum 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6324">CVE-2014-6324</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 권한 상승 취약점입니다.<br />
Microsoft는 이 취약점을 악용하려는 제한적인 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518105">MS14-069</a></td>
<td style="border:1px solid black;">Microsoft Office 이중 삭제 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6333">CVE-2014-6333</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518105">MS14-069</a></td>
<td style="border:1px solid black;">Microsoft Office 배드 인덱스 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6334">CVE-2014-6334</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518105">MS14-069</a></td>
<td style="border:1px solid black;">Microsoft Office 무효 포인터 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6335">CVE-2014-6335</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(해당없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507675">MS14-070</a></td>
<td style="border:1px solid black;">TCP/IP 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4076">CVE-2014-4076</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이것은 권한 상승 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518113">MS14-071</a></td>
<td style="border:1px solid black;">Windows 오디오 서비스 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6322">CVE-2014-6322</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 권한 상승 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518107">MS14-072</a></td>
<td style="border:1px solid black;">TypeFilterLevel 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4149">CVE-2014-4149</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 권한 상승 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513105">MS14-073</a></td>
<td style="border:1px solid black;">SharePoint 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4116">CVE-2014-4116</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 권한 상승 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518111">MS14-074</a></td>
<td style="border:1px solid black;">원격 데스크톱 프로토콜 (RDP) 감사 실패 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6318">CVE-2014-6318</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 보안 기능 우회 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509986">MS14-076</a></td>
<td style="border:1px solid black;">IIS 보안 기능 위회 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4078">CVE-2014-4078</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 보안 기능 우회 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518108">MS14-077</a></td>
<td style="border:1px solid black;">Active Directory Federation Services 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6331">CVE-2014-6331</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509952">MS14-078</a></td>
<td style="border:1px solid black;">Microsoft IME(일본어) 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4077">CVE-2014-4077</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이것은 권한 상승 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=518110">MS14-079</a></td>
<td style="border:1px solid black;">Windows 커널 모드 드라이버의 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6317">CVE-2014-6317</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이것은 서비스 거부 취약점입니다.</td>
</tr>
</tbody>
</table>
  
 
  
영향을 받는 소프트웨어  
----------------------
  
<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
### Windows 운영 체제 및 구성 요소

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-064**](http://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](http://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](http://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](http://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](http://go.microsoft.com/fwlink/?linkid=518109)
</td>
<td style="border:1px solid black;">
[**MS14-070**](http://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](http://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](http://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](http://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](http://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](http://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](http://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](http://go.microsoft.com/fwlink/?linkid=518110)

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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3006226)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(보통)  
Internet Explorer 7  
(3003057)  
(보통)  
Internet Explorer 8  
(3003057)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2989935)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2978114)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2978124)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
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
Windows Server 2003 서비스 팩 2  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 에디션 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 에디션 서비스 팩 2  
(3006226)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(보통)  
Internet Explorer 7  
(3003057)  
(보통)  
Internet Explorer 8  
(3003057)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 에디션 서비스 팩 2  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 에디션 서비스 팩 2  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 에디션 서비스 팩 2  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 에디션 서비스 팩 2  
(2989935)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2978124)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
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
Windows Server 2003 x64 에디션 서비스 팩 2  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 에디션 서비스 팩 2  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 기반 시스템 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 기반 시스템 서비스 팩 2  
(3006226)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(보통)  
Internet Explorer 7  
(3003057)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 기반 시스템 서비스 팩 2  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 기반 시스템 서비스 팩 2  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 기반 서비스 팩2  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 기반 시스템 서비스 팩 2  
(2989935)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2978124)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
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
Windows Server 2003 Itanium 기반 시스템 서비스 팩 2  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Itanium 기반 시스템 서비스 팩 2  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-064**](http://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](http://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](http://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](http://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](http://go.microsoft.com/fwlink/?linkid=518109)
</td>
<td style="border:1px solid black;">
[**MS14-070**](http://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](http://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](http://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](http://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](http://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](http://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](http://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](http://go.microsoft.com/fwlink/?linkid=518110)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
없음
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
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3006226)  
(긴급)  
Windows Vista 서비스 팩 2  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(긴급)  
Internet Explorer 8  
(3003057)  
(긴급)  
Internet Explorer 9  
(3003057)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2993958)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3011780)  
(심각도 없음)<sup>[1]</sup>
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2978116)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 에디션 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 에디션 서비스 팩 2  
(3006226)  
(긴급)  
Windows Vista x64 에디션 서비스 팩 2  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(긴급)  
Internet Explorer 8  
(3003057)  
(긴급)  
Internet Explorer 9  
(3003057)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 에디션 서비스 팩 2  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 에디션 서비스 팩 2  
(2993958)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 에디션 서비스 팩 2  
(3011780)  
(심각도 없음)<sup>[1]</sup>
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 에디션 서비스 팩 2  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2978116)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 에디션 서비스 팩 2  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 에디션 서비스 팩 2  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Vista x64 에디션 서비스 팩 2  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-064**](http://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](http://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](http://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](http://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](http://go.microsoft.com/fwlink/?linkid=518109)
</td>
<td style="border:1px solid black;">
[**MS14-070**](http://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](http://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](http://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](http://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](http://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](http://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](http://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](http://go.microsoft.com/fwlink/?linkid=518110)

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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2  
(3006226)  
(긴급)  
Windows Server 2008 32비트 시스템 서비스 팩 2  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(보통)  
Internet Explorer 8  
(3003057)  
(보통)  
Internet Explorer 9  
(3003057)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2978116)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3003381)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2  
(3006226)  
(긴급)  
Windows Server 2008 x64기반 시스템 서비스 팩 2  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(보통)  
Internet Explorer 8  
(3003057)  
(보통)  
Internet Explorer 9  
(3003057)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2978116)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3003381)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Itanium 기반 시스템 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 Itanium 기반 시스템 서비스 팩 2  
(3006226)  
(긴급)  
Windows Server 2008 Itanium 기반 시스템 서비스 팩 2  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Itanium 기반 시스템 서비스 팩 2  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Itanium 기반 시스템 서비스 팩 2  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 tanium 기반 시스템 서비스 팩 2  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 Itanium 기반 시스템 서비스 팩 2  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2978116)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Itanium 기반 시스템 서비스 팩 2  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 Itanium 기반 시스템 서비스 팩 2  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Itanium 기반 시스템 서비스 팩 2  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-064**](http://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](http://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](http://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](http://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](http://go.microsoft.com/fwlink/?linkid=518109)
</td>
<td style="border:1px solid black;">
[**MS14-070**](http://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](http://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](http://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](http://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](http://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](http://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](http://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](http://go.microsoft.com/fwlink/?linkid=518110)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
없음
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
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 32비트 시스템 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows 7 32비트 시스템 서비스 팩 1  
(3006226)  
(긴급)  
Windows 7 32비트 시스템 서비스 팩 1  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(긴급)  
Internet Explorer 9  
(3003057)  
(긴급)  
Internet Explorer 10  
(3003057)  
(긴급)  
Internet Explorer 11  
(3003057)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7 32비트 시스템 서비스 팩 1  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7 32비트 시스템 서비스 팩 1  
(2993958)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7 32비트 시스템 서비스 팩 1  
(3011780)  
(심각도 없음)<sup>[1]</sup>
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 7 32비트 시스템 서비스 팩 1  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7 32비트 시스템 서비스 팩 1  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 7 32비트 시스템 서비스 팩 1  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows 7 32비트 시스템 서비스 팩 1  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64기반 시스템 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows 7 x64기반 시스템 서비스 팩 1  
(3006226)  
(긴급)  
Windows 7 x64기반 시스템 서비스 팩 1  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(긴급)  
Internet Explorer 9  
(3003057)  
(긴급)  
Internet Explorer 10  
(3003057)  
(긴급)  
Internet Explorer 11  
(3003057)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7 x64기반 시스템 서비스 팩 1  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7 x64기반 시스템 서비스 팩 1  
(2993958)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7 x64기반 시스템 서비스 팩 1  
(3011780)  
(심각도 없음)<sup>[1]</sup>
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 7 x64기반 시스템 서비스 팩 1  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7 x64기반 시스템 서비스 팩 1  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 7 x64기반 시스템 서비스 팩 1  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows 7 x64기반 시스템 서비스 팩 1  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-064**](http://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](http://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](http://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](http://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](http://go.microsoft.com/fwlink/?linkid=518109)
</td>
<td style="border:1px solid black;">
[**MS14-070**](http://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](http://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](http://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](http://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](http://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](http://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](http://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](http://go.microsoft.com/fwlink/?linkid=518110)

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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1  
(3006226)  
(긴급)  
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(보통)  
Internet Explorer 9  
(3003057)  
(보통)  
Internet Explorer 10  
(3003057)  
(보통)  
Internet Explorer 11  
(3003057)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3003381)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium 기반 시스템 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium 기반 시스템 서비스 팩 1  
(3006226)  
(긴급)  
Windows Server 2008 R2 Itanium 기반 시스템 서비스 팩 1  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium 기반 시스템 서비스 팩 1  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium 기반 시스템 서비스 팩 1  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium 기반 시스템 서비스 팩 1  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium 기반 시스템 서비스 팩 1  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium 기반 시스템 서비스 팩 1  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium 기반 시스템 서비스 팩 1  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium 기반 시스템 서비스 팩 1  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 8 and Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-064**](http://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](http://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](http://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](http://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](http://go.microsoft.com/fwlink/?linkid=518109)
</td>
<td style="border:1px solid black;">
[**MS14-070**](http://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](http://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](http://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](http://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](http://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](http://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](http://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](http://go.microsoft.com/fwlink/?linkid=518110)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
없음
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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 32 비트 시스템

</td>
<td style="border:1px solid black;">
Windows 8 32 비트 시스템  
(3006226)  
(긴급)  
Windows 8 for 32 비트 시스템  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8 32 비트 시스템  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8 32 비트 시스템  
(2993958)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8 32 비트 시스템  
(3011780)  
(심각도 없음)<sup>[1]</sup>
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 8 32 비트 시스템  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8 32 비트 시스템  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.0  
(2982998)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 8 32 비트 시스템  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 x64 기반 시스템

</td>
<td style="border:1px solid black;">
Windows 8 x64 기반 시스템  
(3006226)  
(긴급)  
Windows 8 x64 기반 시스템  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8 x64 기반 시스템  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8 x64 기반 시스템  
(2993958)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8 x64 기반 시스템  
(3011780)  
(심각도없음)<sup>[1]</sup>
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 8 x64 기반 시스템  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8 x64 기반 시스템  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.0  
(2982998)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 8 x64 기반 시스템  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 32비트 시스템

</td>
<td style="border:1px solid black;">
Windows 8.1 32비트 시스템  
(3006226)  
(긴급)  
Windows 8.1 32비트 시스템  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1 32비트 시스템  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1 32비트 시스템  
(2993958)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1 32비트 시스템  
(3011780)  
(심각도없음)<sup>[1]</sup>
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 8.1 32비트 시스템  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1 32비트 시스템  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.5  
(2982998)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 8.1 32비트 시스템  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 x64 기반 시스템

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 기반 시스템  
(3006226)  
(긴급)  
Windows 8.1 x64 기반 시스템  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 기반 시스템  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 기반 시스템  
(2993958)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64기반 시스템  
(3011780)  
(심각도없음)<sup>[1]</sup>
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 기반 시스템  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 기반 시스템  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.5  
(2982998)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 기반 시스템  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2012 and Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-064**](http://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](http://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](http://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](http://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](http://go.microsoft.com/fwlink/?linkid=518109)
</td>
<td style="border:1px solid black;">
[**MS14-070**](http://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](http://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](http://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](http://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](http://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](http://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](http://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](http://go.microsoft.com/fwlink/?linkid=518110)

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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

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
**없음**

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3006226)  
(긴급)  
Windows Server 2012  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.0  
(2982998)  
(중요)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.1  
(3003381)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3006226)  
(긴급)  
Windows Server 2012 R2  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.5  
(2982998)  
(중요)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 3.0  
(3003381)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows RT and Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-064**](http://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](http://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](http://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](http://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](http://go.microsoft.com/fwlink/?linkid=518109)
</td>
<td style="border:1px solid black;">
[**MS14-070**](http://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](http://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](http://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](http://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](http://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](http://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](http://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](http://go.microsoft.com/fwlink/?linkid=518110)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
없음
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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3006226)  
(긴급)  
Windows RT  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(2993958)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(3003743)  
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
Windows RT  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3006226)  
(긴급)  
Windows RT 8.1  
(3010788)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2993958)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3005607)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3003743)  
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
Windows RT 8.1  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Server Core설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-064**](http://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](http://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](http://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](http://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](http://go.microsoft.com/fwlink/?linkid=518109)
</td>
<td style="border:1px solid black;">
[**MS14-070**](http://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](http://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](http://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](http://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](http://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](http://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](http://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](http://go.microsoft.com/fwlink/?linkid=518110)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2 (Server Core설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2 (Server Core설치)  
(3006226)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2 (Server Core설치)  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2 (Server Core설치)  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2 (Server Core설치)  
(3011780)  
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
Windows Server 2008 32비트 시스템 서비스 팩 2 (Server Core설치)  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2 (Server Core설치)  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 32비트 시스템 서비스 팩 2 (Server Core설치)  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2 (Server Core설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2 (Server Core설치)  
(3006226)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2 (Server Core설치) (2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2 (Server Core설치) (2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2 (Server Core설치)  
(3011780)  
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
Windows Server 2008 x64기반 시스템 서비스 팩 2 (Server Core설치)  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2 (Server Core설치)  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 x64기반 시스템 서비스 팩 2 (Server Core설치)  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1 (Server Core설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1 (Server Core설치)  
(3006226)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1 (Server Core설치)  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1 (Server Core설치)  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1 (Server Core설치)  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(중요)  
Microsoft .NET Framework 4  
(2978125)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1 (Server Core설치)  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1 (Server Core설치)  
(2991963)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 기반 시스템 서비스 팩 1 (Server Core설치)  
(3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core설치)  
(3006226)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core설치)  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core설치) (2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core 설치)  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core설치) (3003743)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core설치)  
(2982998)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core설치) (3002885)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core설치)  
(3006226)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core설치)  
(2992611)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core설치)  
(2993958)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core 설치)  
(3011780)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core설치)  
(3003743)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core설치)  
(2982998)  
(중요)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 3.0  
(3003381)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core설치)  
(3002885)  
(보통)

</td>
</tr>
</table>
 
**MS14-064, MS14-065, MS14-067 참고 사항**

Windows Technical Preview 및 Windows Server Technical Preview가 영향을 받습니다. 이러한 운영 체제를 실행하는 고객들은 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공되는 이 업데이트를 적용하는 것이 좋습니다. 

**MS14-068 참고 사항**

Windows Technical Preview 및 Windows Server Technical Preview가 영향을 받습니다. 이러한 운영 체제를 실행하는 고객들은 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공되는 이 업데이트를 적용하는 것이 좋습니다. 

<sup>[1]</sup> 이 운영체제는 이 공지의 취약점에 영향을 받지 않기 때문에 보안 심각도는 없습니다. 이 업데이트는 알려진 보안 취약점에서 해결되지 않는 추가적인 [심층 방어](https://technet.microsoft.com/en-us/library/security/dn848375.aspx)(영문) 기능을 제공 합니다.

**MS14-078 참고 사항**

이 공지는 하나 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오. 

 

### Microsoft Office 제품군 및 소프트웨어

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
[**MS14-069**](http://go.microsoft.com/fwlink/?linkid=518105)

</td>
<td style="border:1px solid black;">
[**MS14-078**](http://go.microsoft.com/fwlink/?linkid=509952)

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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 서비스 팩 3  
(2899527)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 IME (일본어)  
(2889913)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Other Microsoft Office Software**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-069**](http://go.microsoft.com/fwlink/?linkid=518105)

</td>
<td style="border:1px solid black;">
[**MS14-078**](http://go.microsoft.com/fwlink/?linkid=509952)

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
<tr>
<td style="border:1px solid black;">
Microsoft Word 뷰어

</td>
<td style="border:1px solid black;">
Microsoft Word 뷰어  
(2899553)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능팩 서비스 팩 3  
(2899526)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
</table>
 
**MS14-078 참고 사항**

이 공지는 하나 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오. 

 

### Microsoft Server 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-073**](http://go.microsoft.com/fwlink/?linkid=513105)

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
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 서비스 팩 2  
(2889838)  
(중요)

</td>
</tr>
</table>
 
 

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
Microsoft는 책임감 있는 보안 취약점 공개를 통해 우리의 고객들을 보호하는데 도움을 주고 있는 보안 커뮤니티의 노력을 인식하고 있습니다. 자세한 사항은 [감사의 말](https://technet.microsoft.com/library/security/dn820091.aspx)(영문)에서 확인해 주세요.

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

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너(영문)](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드(영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft 업데이트](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows 업데이트를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.

IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617)

Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)

국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 개정 내역

-   V1.0(2014년 11월 12일): 공지 요약이 게시되었습니다.
-   V2.0(2014년 11월 19일): 공지 요약은 부정기 보안 공지 MS14-068에 대한 요약과 개정된 MS14-066 대한 요약을 게시합니다. 개정된 MS14-066에서는 Windows Server 2008 R2 및 Windows Server 2012 용 2992611 업데이트가 다시 발표되었습니다.

*2014-11-10 11:02Z-08:00에 페이지가 생성되었습니다.*
