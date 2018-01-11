---
TOCTitle: 'MS10-AUG'
Title: 2010 년 8 월 Microsoft 보안 공지 요약
ms:assetid: 'ms10-aug'
ms:contentKeyID: 61230721
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms10-aug(v=Security.10)'
---


2010 년 8 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2010년 8월 3일 화요일 | 업데이트된 날짜: 2010년 9월 2일 목요일

**버전:** 2.1

이 공지 요약 목록에는 2010년 8월 발표된 보안 공지가 포함되어 있습니다.

2010년 8월 공지 발표와 함께 이 공지 요약이 2010년 8월 5일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2010년 8월 11일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [8월 보안 공지 웹캐스트 (영문)](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454431&eventcategory=4&culture=en-us&countrycode=us)에 지금 등록하십시오. 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

이 보안 공지 요약 버전 1.0에서 처음 발표한 부정기 보안 공지인 [MS10-046](http://technet.microsoft.com/security/bulletin/ms10-046)와 관련하여, Microsoft는 2010년 7월 30일 해당하는 보안 공지 사전 알림을 발표하고 2010년 8월 2일 보안 공지 웹캐스트를 호스팅하였습니다. 이 [2010년 8월 2일 웹캐스트 (영문)](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032456779&culture=en-us)는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-046">MS10-046</a></td>
<td style="border:1px solid black;"><strong>Windows 셸의 취약점으로 인한 원격 코드 실행 문제점(2286198)</strong><br />
<br />
이 보안 업데이트는 Windows 셸의 공개된 취약점을 해결합니다. 특수하게 조작된 바로 가기 아이콘이 표시되는 경우 이 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-049">MS10-049</a></td>
<td style="border:1px solid black;"><strong>SChannel의 취약점으로 인한 원격 코드 실행 문제점(980436)</strong><br />
<br />
이 보안 업데이트는 Windows의 Secure Channel(SChannel) 보안 패키지의 공개된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 인터넷 웹 브라우저를 통해 이 취약점을 악용하도록 설계된 특수하게 조작된 웹 사이트를 방문할 경우 원격 코드 실행이 허용될 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 이러한 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-051">MS10-051</a></td>
<td style="border:1px solid black;"><strong>Microsoft XML Core Services의 취약점으로 인한 원격 코드 실행 문제점(2079403)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft XML Core Services의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 공격자는 강제로 사용자가 이러한 웹 사이트를 방문하도록 할 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-052">MS10-052</a></td>
<td style="border:1px solid black;"><strong>Microsoft MPEG Layer-3 코덱의 취약점으로 인한 원격 코드 실행 문제점(2115168)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft MPEG Layer-3 오디오 코덱의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 미디어 파일을 열거나, 웹 사이트 또는 웹 콘텐츠를 제공하는 응용 프로그램으로부터 특수하게 조작된 스트리밍 콘텐츠를 받을 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-053">MS10-053</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(2183461)</strong><br />
<br />
이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 6건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-054">MS10-054</a></td>
<td style="border:1px solid black;"><strong>SMB 서버의 취약점으로 인한 원격 코드 실행 문제점(982214)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 가장 위험한 취약점으로 인해 공격자가 특수하게 조작된 SMB 패킷을 만들어 영향을 받는 시스템에 보내는 경우 원격 코드 실행이 허용될 수 있습니다. 방화벽 구성 모범 사례와 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 이 취약점을 악용하려는 공격으로부터 네트워크를 보호할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-055">MS10-055</a></td>
<td style="border:1px solid black;"><strong>Cinepak 코덱의 취약점으로 인한 원격 코드 실행 문제점(982665)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Cinepak 코덱의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 미디어 파일을 열거나, 웹 사이트 또는 웹 콘텐츠를 제공하는 응용 프로그램으로부터 특수하게 조작된 스트리밍 콘텐츠를 받을 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-056">MS10-056</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Word의 취약점으로 인한 원격 코드 실행 문제점(2269638)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 4건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 특수하게 조작된 RTF 메일 메시지를 열거나 미리 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-060">MS10-060</a></td>
<td style="border:1px solid black;"><strong>Microsoft .NET 공용 언어 런타임과 Microsoft Silverlight의 취약점으로 인한 원격 코드 실행 문제점(2265906)</strong><br />
<br />
이 보안 업데이트는 Microsoft .NET Framework 및 Microsoft Silverlight에서 비공개적으로 보고된 취약점 2건을 해결합니다. 사용자가 XBAP(XAML 브라우저 응용 프로그램) 또는 Silverlight 응용 프로그램을 실행할 수 있는 웹 브라우저를 사용하여 특수하게 조작된 웹 페이지를 보거나, 공격자가 특수하게 조작한 Microsoft .NET 응용 프로그램을 실행하도록 사용자를 유인하는 데 성공할 경우 이 취약점으로 인해 클라이언트 시스템에서 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 서버에서 ASP.NET 페이지 처리를 허용하고 공격자가 해당 서버에 특수하게 조작한 ASP.NET 페이지를 성공적으로 업로드하여 실행할 경우 이 취약점으로 인해 IIS를 실행하는 서버 시스템에서 원격 코드 실행이 허용될 수 있습니다. 이러한 경우는 웹 호스팅 시나리오에서 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework, Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-047">MS10-047</a></td>
<td style="border:1px solid black;"><strong>Windows 커널의 취약점으로 인한 권한 상승 문제점(981852)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 가장 위험한 취약점으로 인해 공격자가 시스템에 로컬로 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-048">MS10-048</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2160329)</strong><br />
<br />
이 보안 업데이트는 Windows 커널 모드 드라이버의 공개된 취약점 1건과 비공개적으로 보고된 취약점 4건을 해결합니다. 가장 위험한 취약점으로 인해 공격자가 영향을 받는 시스템에 로그온하여 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-050">MS10-050</a></td>
<td style="border:1px solid black;"><strong>Windows Movie Maker의 취약점으로 인한 원격 코드 실행 문제점(981997)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows Movie Maker의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 Movie Maker 프로젝트 파일을 전송하고 특수하게 조작된 파일을 열도록 사용자를 유도한 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-057">MS10-057</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel의 취약점으로 인한 원격 코드 실행 문제점(2269707)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 Excel 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-058">MS10-058</a></td>
<td style="border:1px solid black;"><strong>TCP/IP의 취약점으로 인한 권한 상승 문제점(978886)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 가장 위험한 취약점으로 인해 특정 입력 버퍼 처리 중 발생한 오류로 인한 권한 상승이 허용될 수 있습니다. 대상 시스템에 로그온할 수 있는 공격자는 이 취약점을 악용하여 시스템 수준 권한으로 임의 코드를 실행할 수 있습니다. 이렇게 되면 공격자는 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-059">MS10-059</a></td>
<td style="border:1px solid black;"><strong>서비스 추적 기능의 취약점으로 인한 권한 상승 문제점(982799)</strong><br />
<br />
이 보안 업데이트는 서비스 추적 기능의 공개된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 응용 프로그램을 사용할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 악용 가능성 평가 수준 내림차순 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](http://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 취약점 제목                                                                     | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                                                                                                             |  
|---------------------------------------------------------------------|---------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-060](http://technet.microsoft.com/security/bulletin/ms10-060) | Microsoft Silverlight 메모리 손상 취약점                                        | [CVE-2010-0019 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0019) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-052](http://technet.microsoft.com/security/bulletin/ms10-052) | MPEG Layer-3 오디오 디코더 버퍼 오버플로 취약점                                 | [CVE-2010-1882 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1882) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-047](http://technet.microsoft.com/security/bulletin/ms10-047) | Windows 커널 데이터 초기화 취약점                                               | [CVE-2010-1888 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1888) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-058](http://technet.microsoft.com/security/bulletin/ms10-058) | Windows 네트워킹의 정수 오버플로 취약점                                         | [CVE-2010-1893 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1893) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-048](http://technet.microsoft.com/security/bulletin/ms10-048) | Win32k 예외 처리 취약점                                                         | [CVE-2010-1894 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1894) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 공개되었습니다.**                                                                                                                       |  
| [MS10-048](http://technet.microsoft.com/security/bulletin/ms10-048) | Win32k 풀 오버플로 취약점                                                       | [CVE-2010-1895 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1895) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-048](http://technet.microsoft.com/security/bulletin/ms10-048) | Win32k 사용자 입력 유효성 검사 취약점                                           | [CVE-2010-1896 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1896) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-048](http://technet.microsoft.com/security/bulletin/ms10-048) | Win32k 창 생성 취약점                                                           | [CVE-2010-1897 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1897) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-060](http://technet.microsoft.com/security/bulletin/ms10-060) | Microsoft Silverlight 및 Microsoft .NET Framework CLR 가상 메서드 대리자 취약점 | [CVE-2010-1898 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1898) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-056](http://technet.microsoft.com/security/bulletin/ms10-056) | Word 레코드 구문 분석 취약점                                                    | [CVE-2010-1900 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1900) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-056](http://technet.microsoft.com/security/bulletin/ms10-056) | Word RTF 구문 분석 엔진 메모리 손상 취약점                                      | [CVE-2010-1901 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1901) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-055](http://technet.microsoft.com/security/bulletin/ms10-055) | Cinepak 코덱 압축 해제 취약점                                                   | [CVE-2010-2553 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2553) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-059](http://technet.microsoft.com/security/bulletin/ms10-059) | 추적 메모리 손상 취약점                                                         | [CVE-2010-2555 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2555) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | 초기화되지 않은 메모리 손상 취약점                                              | [CVE-2010-2557 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2557) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점은 완화 요소인 데이터 실행 방지 기능이 없는 Internet Explorer 6에서 악용될 가능성이 더 높습니다.                                             |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | HTML 레이아웃 메모리 손상 취약점                                                | [CVE-2010-2560 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2560) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-057](http://technet.microsoft.com/security/bulletin/ms10-057) | Excel 메모리 손상 취약점                                                        | [CVE-2010-2562 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2562) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-050](http://technet.microsoft.com/security/bulletin/ms10-050) | Movie Maker 메모리 손상 취약점                                                  | [CVE-2010-2564 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2564) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                |  
| [MS10-046](http://technet.microsoft.com/security/bulletin/ms10-046) | 바로 가기 아이콘 로드 취약점                                                    | [CVE-2010-2568 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2568) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.**                                                                                             |  
| [MS10-047](http://technet.microsoft.com/security/bulletin/ms10-047) | Windows 커널 Double Free 취약점                                                 | [CVE-2010-1889 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1889) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                |  
| [MS10-056](http://technet.microsoft.com/security/bulletin/ms10-056) | Word RTF 구문 분석 버퍼 오버플로 취약점                                         | [CVE-2010-1902 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1902) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | Windows Vista 및 Windows 7은 추가 힙 완화 메커니즘으로 인해 악용 가능성이 낮습니다.                                                                   |  
| [MS10-056](http://technet.microsoft.com/security/bulletin/ms10-056) | Word HTML 연결된 개체 메모리 손상 취약점                                        | [CVE-2010-1903 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1903) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                |  
| [MS10-054](http://technet.microsoft.com/security/bulletin/ms10-054) | SMB 풀 오버플로 취약점                                                          | [CVE-2010-2550 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2550) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 대부분의 경우, 취약점을 악용하면 코드 실행보다는 서비스 거부가 발생할 가능성이 높습니다.                                                              |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | 초기화되지 않은 메모리 손상 취약점                                              | [CVE-2010-2556 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2556) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | 경쟁 조건 메모리 손상 취약점                                                    | [CVE-2010-2558 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2558) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | 초기화되지 않은 메모리 손상 취약점                                              | [CVE-2010-2559 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2559) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                |  
| [MS10-051](http://technet.microsoft.com/security/bulletin/ms10-051) | Msxml2.XMLHTTP.3.0 응답 처리 메모리 손상 취약점                                 | [CVE-2010-2561 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2561) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                |  
| [MS10-049](http://technet.microsoft.com/security/bulletin/ms10-049) | SChannel 조작된 형식의 인증서 요청 원격 코드 실행 취약점                        | [CVE-2010-2566 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2566) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 이 취약점을 악용하면 서비스 거부가 발생할 가능성이 높습니다. 원격 코드 실행은 거의 불가능합니다.                                                      |  
| [MS10-049](http://technet.microsoft.com/security/bulletin/ms10-049) | TLS/SSL 재협상 취약점                                                           | [CVE-2009-3555 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3555) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점은 스푸핑 취약점입니다. 이 취약점은 [Microsoft 보안 권고 977377](http://technet.microsoft.com/security/advisory/977377)에 설명되어 있습니다. |  
| [MS10-053](http://technet.microsoft.com/security/bulletin/ms10-053) | 이벤트 처리기 도메인 간 취약점                                                  | [CVE-2010-1258 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1258) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이는 정보 유출 취약점입니다.                                                                                                                          |  
| [MS10-058](http://technet.microsoft.com/security/bulletin/ms10-058) | IPv6 메모리 손상 취약점                                                         | [CVE-2010-1892 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1892) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이것은 서비스 거부 취약점입니다.                                                                                                                      |  
| [MS10-054](http://technet.microsoft.com/security/bulletin/ms10-054) | SMB 변수 유효성 검사 취약점                                                     | [CVE-2010-2551 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2551) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이것은 서비스 거부 취약점입니다.                                                                                                                      |  
| [MS10-054](http://technet.microsoft.com/security/bulletin/ms10-054) | SMB 스택 부족 취약점                                                            | [CVE-2010-2552 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2552) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이것은 서비스 거부 취약점입니다.                                                                                                                      |
  
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
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=12361875-b453-45e8-852b-90f2727894fd&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=ff00381c-e74b-48e5-9dd9-34dbedd906a2&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=dbdbbe5e-2ef9-4704-80c4-27ef28fd95ef&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=08159149-17de-4640-8818-cb7bd4811531&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=bc949915-4e16-4897-a295-2f99102548ab&displaylang=ko)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4b489f8c-ada0-4051-8284-0a941c04d2ed&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1662780f-370a-425b-9917-c601eb54a375&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=6e5e16f8-c140-4a1d-b898-8417a6bfd4d8&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=5ddb5e34-f97a-47c6-96c8-ba2ed06ccb77&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9&displaylang=ko)  
(KB983582)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48&displaylang=ko)  
(KB983583)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=e3574047-5ce5-4461-94aa-4eb3258d5e71&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=deeac521-d3a2-4019-8176-c9228e733cf4&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.1](http://www.microsoft.com/downloads/details.aspx?familyid=b211664b-434d-4626-816f-c77510cfd44d&displaylang=ko)<sup>[1]</sup>
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
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3b44bd67-48e2-497f-9165-42a702e2cc0d)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=eaffa70c-6f2b-4e66-b1bc-64bdbbbcd34f)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4d4e8eeb-a0b2-41c6-9ee4-3f4beb44195e)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b7f28d7a-6b27-4059-865b-5fd55edb6299)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=96b7a562-af16-4f0d-840c-838fb12e7419)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5296fb82-c446-4681-a9a0-0f80a2e248be)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f8ae3978-bad6-4201-8357-2d212ab703ef)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=fd6cc359-e72e-46ec-a08b-763934e3e115)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5cff5d6e-11a5-40ed-92ac-e12d287919e6)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9&displaylang=ko)  
(KB983582)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48&displaylang=ko)  
(KB983583)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d6c5455e-bc31-4842-aef4-ebff92324323)  
(중요)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.1](http://www.microsoft.com/downloads/details.aspx?familyid=decb1fe6-adc8-44f7-89c5-f25767f0cefe)<sup>[1]</sup>
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
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=32fe91ef-5a8d-4095-90ee-2ca216696b09&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f76d68df-97e5-489c-a5f6-0c378c1f62ae&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=31ce233e-4d2d-404b-84a8-683319ba8ef7&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9c2110ec-7e6c-4e73-9785-0a8196095ea0&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b0370e1e-dedf-4fe8-a06c-0e0f0a674205&displaylang=ko)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8753ae27-60a4-475a-b8bc-6a7764480295&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=772e765d-0502-4b0b-bde8-d4f62b96db64&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=230e8559-e6df-49d5-acb5-b0cd4bde0bf4&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9&displaylang=ko)  
(KB983582)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48&displaylang=ko)  
(KB983583)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=59395f00-90f4-4b68-8dd3-03ff611c1bc8&displaylang=ko)  
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
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=923de214-c4fa-41e6-8307-2c5a37f13e8e&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4543bcf0-3505-407b-a5a9-6250ece6fbac&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4d784b57-8564-4e7e-8f61-f897398e7ea5&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=fdfad4ca-37c4-4ac5-bebc-a5ad61299503&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=d92f5e69-43cf-4615-aa3b-41f9f40bb57b&displaylang=ko)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fd3e9d06-1f8b-4ef7-84f6-61e85a1767b8&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=863edf45-0d3b-4408-a47c-258dc4a4fd94&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=03804f59-748e-4832-98e4-2d88564bd10a&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9&displaylang=ko)  
(KB983582)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48&displaylang=ko)  
(KB983583)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9ef1c600-bb93-4800-81b8-8c64b369c194&displaylang=ko)  
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
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=63aa5f8a-fe47-4892-b905-b54e4f3b6580)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=9ef992c3-96e9-4533-b844-07424a6054b3)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=d87ac8b3-41fb-4cdd-b305-181a0024d85c)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=782e2963-4a52-4a1d-b99a-34ba841038a7)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5e730064-8270-4d63-b497-c5ebeddea1fc)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=e4f4f8b3-7a39-4d77-a46b-02c86ad159c3)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9&displaylang=ko)  
(KB983582)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48&displaylang=ko)  
(KB983583)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=f96b8154-9976-41b0-b9d7-d79887fe9364)  
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
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=52748886-6280-4247-8cbd-f64db229ee66&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aca69406-f795-4398-968f-959fe3a74e89&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=bbfaadf8-ab38-456c-956a-ea18c64236c9&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=535c563e-cdac-4e3d-96b0-9947ea22deca&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2062566b-8b81-43c2-875d-9c06d4e3fa82&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9087a3aa-aa55-41f6-8c4c-f322e4aa8681&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=60c81415-b61e-44a4-8dd9-cedec99eb70f&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1&displaylang=ko)  
(KB983587)  
(긴급)  
Windows Vista 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967&displaylang=ko)  
(KB983588)  
(긴급)  
Windows Vista 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104&displaylang=ko)  
(KB983589)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4486f97c-4cf8-4236-bfc3-b50e72e2a5c1&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c9345207-7242-4b71-bf80-b52031e08f8c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Movie Maker 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=8aded9dd-08d6-4b19-955f-0d8414868cf9&displaylang=ko)<sup>[1]</sup>
(중요)  
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=a1d8ed0d-a3b5-416a-ab8b-77501da62132&displaylang=ko)<sup>[2]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4684c4df-0a5c-4dba-82e5-059378737118&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=dfb31aa2-7457-4581-9e28-7984a360edf4&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=37648e95-05c2-4802-9a0f-660200baa229&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e2835ed1-5ca6-4347-8ff1-e694b1ac49ff&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=577131cd-1229-4746-89d7-84d75f29e1f0&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=cd1185e3-ca22-4197-a53b-e7a2806ac352&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=65b04e29-8e39-46de-94e8-b653969b1ffd&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=10c9d5f1-53ed-459b-a663-e69bdb845a6b&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=469b732d-ca62-4a48-bb55-99f2ae4ddcf5&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1&displaylang=ko)  
(KB983587)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967&displaylang=ko)  
(KB983588)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104&displaylang=ko)  
(KB983589)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b547898e-f8a9-49dc-b49d-cffec5a001bc&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1620e7ac-3913-478d-8120-e9f46d98f453&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Movie Maker 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4baff9ae-dd25-4942-b45e-f281d0e1f4ac&displaylang=ko)<sup>[1]</sup>
(중요)  
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=0a226592-8f98-4f67-ac60-1d00cbc56598&displaylang=ko)<sup>[2]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=18152cd4-815f-425f-8694-fbabcbe80609&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=110f932f-d13c-4486-a295-e6068d5d8d7a&displaylang=ko)  
(중요)
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
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3aabd189-7d4c-4c9f-8854-f33127b1c309&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e0253d4-f0c0-4f28-ba08-6907c2fcb339&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=73b5f45c-c9d6-491f-8483-98838b2a7c04&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8239cb9e-bb5a-4157-8038-33d0b329eaee&displaylang=ko)\*\*  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=409b9298-1e7d-48cf-9872-ffbdc56ebe53&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a94e2e38-116a-4b63-9328-6c33e63bbbfe&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008만(32비트 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1&displaylang=ko)\*\*  
(KB983587)  
(긴급)  
Windows Server 2008만(32비트 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967&displaylang=ko)\*\*  
(KB983588)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104&displaylang=ko)\*\*  
(KB983589)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=611765ab-b3f3-45db-92b2-ee040b9cfd27&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a8b1a3f7-7147-494e-bfc0-b1979b9578e6&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=844404be-f2e8-47bc-9650-9e2bbe383814&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4c9b3e60-e166-40c9-8938-3cba0a399c47&displaylang=ko)\*  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=29c6fc2d-d318-4a63-9ab2-82e84272aaf2&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a96891ff-8771-47b3-81bb-8640adb6c098&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=43ece408-4aa7-4819-b3f6-7f0719ed3213&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5ef8abf0-c89e-4911-8d77-42400d9a398f&displaylang=ko)\*\*  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9b869bab-0797-4f83-8c64-23dda9983c8d&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=602dd3f6-0d09-4546-b1db-d7b6b04edb66&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008만(x64 기반 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1&displaylang=ko)\*\*  
(KB983587)  
(긴급)  
Windows Server 2008만(x64 기반 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967&displaylang=ko)\*\*  
(KB983588)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104&displaylang=ko)\*\*  
(KB983589)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=131f3512-1585-462e-a4f1-3f359aac44bd&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c1c25cb7-7e82-4c14-9666-aff52dd308b4&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=08491c73-66b1-4c4c-8740-ea596a730fc1&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=fa84e547-2190-402f-9467-2450deeff565&displaylang=ko)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=cfe227b5-6660-49f8-9d71-a997dd83de0b)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3b16a422-0ee9-4eab-9cfe-e7688ffa0d76)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b6faee94-e821-432d-bfa2-9008664566af)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2f1eee63-2cca-4ec5-b196-36de3c0054cf)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=24d8f0a3-51a9-46c1-b870-a2239bf600e4)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용)만:  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1&displaylang=ko)  
(KB983587)  
(긴급)  
Windows Server 2008(Itanium 기반 시스템용)만:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967&displaylang=ko)  
(KB983588)  
(긴급)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104&displaylang=ko)  
(KB983589)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=972efd3a-ec1e-49b2-835e-76f4b21b5b79)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=45fe5135-aa89-4f60-8cdb-ec0edc9a7e77)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8aa12902-c234-4fd9-bba3-6767eafc38fc)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=84f89dca-108c-4956-9aa2-866e17a872fc)  
(중요)
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
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=22e62b5c-e4c1-47d0-ae4a-8bd2d70d0a0a&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=71716507-7080-4102-991e-6afc7cc377d5&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=31d0f5ac-2cff-42a1-8f18-128bbfc4e57d&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ecaf42e0-a288-40c1-8602-21e967a87408&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=8d58ebc4-a5f9-4318-a6f1-168c1bcdae3c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=2e782ac9-b5d5-490e-a01a-7d4481eab224&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8&displaylang=ko)  
(KB983590)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=a7d60864-5942-47ed-a6f3-1c07b4833a14&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=68bddf4b-b597-477e-80e4-9293d7160496&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=3a5a088e-644a-4a0e-9a09-0370bcd97688&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ce6233f3-2ee5-4329-908d-ba9b28ecc553&displaylang=ko)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=9499f771-c388-4de3-a5c7-8cc8b00b4395&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c457d8ec-83b7-446f-b77c-e47d4187e616&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=a4f6d7c2-b475-4900-82f0-75f5be0b7b63&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ca57a47a-9111-4abe-9356-4962ca2c1d65&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ad1ddf94-d714-4b36-8256-42bf79d03a90&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=24751193-592f-4c44-a8d6-f4112d4f011b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8&displaylang=ko)  
(KB983590)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b00ec47c-402e-4207-a4c9-6c1900f254f8&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=5ff09e03-d662-4b23-ab26-d25ca2ba58df&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=163fe2bd-f999-47c1-9a35-c4fc868bda51&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=146270fa-cd6f-440a-aa3e-e93af0bff447&displaylang=ko)  
(중요)
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
[**MS10-046**](http://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](http://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](http://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](http://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](http://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](http://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](http://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](http://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](http://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](http://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](http://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](http://technet.microsoft.com/security/bulletin/ms10-059)
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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=0d9dd09b-db40-462b-88b0-4dbb8180e81f&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c9aeea25-ca14-4b42-9018-a27c9d8899c4&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=a48cdac5-4d78-49b5-a6d8-ecf6c58cace2&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e7757bbc-3ef0-421d-ab57-0083a302c77b&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=52642a8d-1081-4496-848e-9b03baf3fdac&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8&displaylang=ko)\*  
(KB983590)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c1ad1248-07f1-42d4-baa4-8a20837ec7b4&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=6bbc9cb1-0b59-4473-adf9-2ce2f0f94c0a&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=a1f95600-34e5-44b3-b2cb-b2b2cbf645cb&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=333fb6e4-f867-4dcb-beb3-2d88e428ca2e&displaylang=ko)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ce2bb5d4-f661-44e3-ac28-0b81f7b72670)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b7c2e91f-ca8a-4237-99c8-ca53c91cf73e)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b4d3210e-f3ad-4dbb-9390-6e98eeb99eaa)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7b457d04-03a9-4eb0-ba6a-ab45267e4f74)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=783fb42c-3698-4b1d-a692-3ff319578931)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8&displaylang=ko)  
(KB983590)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=f23dec0f-a33b-4d8c-a86d-0e9368ae7ff5)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=2543191a-09cb-4417-bbb2-aac4d9a2a756)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c3cd7f2f-e198-4fbd-a65d-21a1bf51eb61)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=62034ecb-a6bd-46c5-a03d-9642880bc2d6)  
(중요)
</td>
</tr>
</table>
 
**Windows Server 2008 및 Windows Server 2008 R2 참고 사항**

**\*Server Core 설치가 영향을 받습니다.** 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리 (영문)](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스 (영문)](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

**\*\*Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리 (영문)](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스 (영문)](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

**MS10-050 참고 사항**

<sup>[1]</sup>이러한 Windows Movie Maker 버전은 표시된 운영 체제와 함께 제공됩니다.

<sup>[2]</sup>Windows Movie Maker 2.6은 표시된 운영 체제에 설치할 수 있는 선택적 다운로드입니다.

**MS10-060 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

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
Microsoft Office 제품군, 시스템 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-056**](http://technet.microsoft.com/security/bulletin/ms10-056)
</td>
<td style="border:1px solid black;">
[**MS10-057**](http://technet.microsoft.com/security/bulletin/ms10-057)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=978eb887-25b6-4dde-a2ec-d2d1e7f1a434&displaylang=ko)  
(KB2251389)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=032e1530-8736-4e1c-a704-967679227619&displaylang=ko)  
(KB2264397)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=4360bcec-0731-4d4a-89eb-7d28a4607f06&displaylang=ko)  
(KB2251399)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=7cecbce3-bbb7-47d1-bda3-64d7e0f69f62&displaylang=ko)  
(KB2264403)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=0d7210a3-662e-41e7-affc-ae94f9d89388&displaylang=ko)  
(KB2251419)  
(긴급)
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
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-056**](http://technet.microsoft.com/security/bulletin/ms10-056)
</td>
<td style="border:1px solid black;">
[**MS10-057**](http://technet.microsoft.com/security/bulletin/ms10-057)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=d2f44d4a-7cd8-4514-b3ff-1770bc47d595)  
(KB2284171)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=d2f44d4a-7cd8-4514-b3ff-1770bc47d595)  
(KB2284171)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=6ece112f-0ca7-4b1f-ad20-603950edee66)  
(KB2284162)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=6ece112f-0ca7-4b1f-ad20-603950edee66)  
(KB2284162)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=a7b834a3-5a44-42d4-afe9-6ef207333834)  
(KB2284179)  
(중요)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=a7b834a3-5a44-42d4-afe9-6ef207333834)  
(KB2284179)  
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
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-056**](http://technet.microsoft.com/security/bulletin/ms10-056)
</td>
<td style="border:1px solid black;">
[**MS10-057**](http://technet.microsoft.com/security/bulletin/ms10-057)
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
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=39fe2229-9201-4270-bdc1-20bc8e30a766&displaylang=ko)  
(KB2251437)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](http://www.microsoft.com/downloads/details.aspx?familyid=ed5b9671-651d-41f3-aed3-93ee8a28657f&displaylang=ko)  
(KB2277947)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=feb121ad-e5f6-40e2-bf12-045ae5c2a754)  
(KB2092914)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**MS10-056 참고 사항**

<sup>[1]</sup>Microsoft Office Word 2007 서비스 팩 2를 사용하는 고객의 경우 MS10-056에서 설명한 취약점으로부터 보호하기 위해 보안 업데이트 패키지 KB2251419 이외에도 Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 서비스 팩 2용 보안 업데이트(KB2277947)를 설치해야 합니다.

#### Microsoft 개발자 도구 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-060**](http://technet.microsoft.com/security/bulletin/ms10-060)
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
Microsoft Silverlight 2
</td>
<td style="border:1px solid black;">
Mac에 설치된 [Microsoft Silverlight 2 (영문)](http://www.microsoft.com/getsilverlight/get-started/install/default.aspx)<sup>[1]</sup>
(KB982926)  
(긴급)  
모든 Microsoft Windows 클라이언트 릴리스에 설치된 [Microsoft Silverlight 2 (영문)](http://www.microsoft.com/getsilverlight/get-started/install/default.aspx)<sup>[1]</sup>
(KB982926)  
(긴급)  
모든 Microsoft Windows 서버 릴리스에 설치된 [Microsoft Silverlight 2 (영문)](http://www.microsoft.com/getsilverlight/get-started/install/default.aspx)<sup>[1]</sup>\*\*  
(KB982926)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 3
</td>
<td style="border:1px solid black;">
Mac에 설치된 [Microsoft Silverlight 3](http://www.microsoft.com/downloads/details.aspx?familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850)<sup>[2]</sup>
(KB978464)  
(긴급)  
모든 Microsoft Windows 클라이언트 릴리스에 설치된 [Microsoft Silverlight 3](http://www.microsoft.com/downloads/details.aspx?familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850)<sup>[2]</sup>
(KB978464)  
(긴급)  
모든 Microsoft Windows 서버 릴리스에 설치된 [Microsoft Silverlight 3](http://www.microsoft.com/downloads/details.aspx?familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850)<sup>[2]</sup>\*\*  
(KB978464)  
(긴급)
</td>
</tr>
</table>
 
**MS10-060 참고 사항**

**\*\*Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리 (영문)](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스 (영문)](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

<sup>[1]</sup>이 다운로드는 Microsoft Silverlight 2를 이 공지에서 설명한 취약점의 영향을 받지 않는 최신 버전으로 업그레이드합니다.

<sup>[2]</sup>이 업데이트는 Microsoft Silverlight를 이 공지에서 설명한 취약점의 영향을 받지 않는 최신 빌드로 업그레이드합니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**참고** 2009년 8월 1일부터 Microsoft는 Office 업데이트와 Office 업데이트 인벤토리 도구에 대한 지원을 중단합니다. 계속해서 Microsoft Office 제품에 필요한 최신 업데이트를 받으려면 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)를 사용하십시오. 자세한 내용은 [Microsoft Office 업데이트 정보: 자주 제기되는 질문 사항(FAQ)](http://office.microsoft.com/ko-kr/downloads/fx010402221042.aspx)을 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

Windows Server Update Services(WSUS)를 사용하면 정보 기술 관리자가 최신 Microsoft 제품 업데이트를 Windows 운영 체제를 실행하는 컴퓨터에 배포할 수 있습니다. Windows Server Update Services를 사용하여 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 TechNet 문서의 [Windows Server Update Services (영문)](http://technet.microsoft.com/en-us/wsus/default.aspx)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](http://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://go.microsoft.com/fwlink/?linkid=22939)를 참조하십시오. SMS 2.0 사용자는 SUIT(Security Update Inventory Tool)을 사용하여 보안 업데이트 배포를 지원할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2.0 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

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

-   MS10-046에서 설명한 문제점을 보고해 주신 [VirusBlokAda (영문)](http://www.anti-virus.by/)의 Sergey I. Ulasen 및 Oleg Kupreev
-   MS10-046에서 설명한 문제점을 보고해 주신 [AV-Test (영문)](http://www.av-test.org/)의 Andreas Marx 및 Maik Morgenstern
-   MS10-046에서 설명한 문제점을 해결하기 위해 협력해 주신 [CERT/CC (영문)](http://www.cert.org)의 Will Dormann
-   MS10-046에서 설명한 문제점을 해결하기 위해 협력해 주신 Niels Teusink
-   MS10-046에서 설명한 문제점을 해결하기 위해 협력해 주신 Stefan Kanthak
-   MS10-047에서 설명한 세 가지 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 Tavis Ormandy
-   MS10-048에서 설명한 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 Tavis Ormandy
-   MS10-048에서 설명한 두 가지 문제점을 보고해 주신 [MoonSols (영문)](http://moonsols.com/)의 Matthieu Suiche
-   MS10-048에서 해결된 심층 보안 변경을 위해 협력해 주신 [MoonSols (영문)](http://moonsols.com/)의 Matthieu Suiche
-   MS10-048에서 설명한 문제점을 보고해 주신 [Core Security Technologies](http://www.coresecurity.com/)의 Nicolás Economou
-   MS10-049에서 설명한 문제점을 보고해 주신 [PhoneFactor (영문)](http://www.phonefactor.com/)의 Marsh Ray 및 Steve Dispensa
-   MS10-050에서 설명한 문제점을 보고해 주신 [Secunia (영문)](http://secunia.com/)의 Dyon Balding
-   MS10-051에서 설명한 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 SkyLined
-   MS10-052에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 n.runs AG의 Moritz Jodeit
-   MS10-053에서 설명한 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 David Bloom
-   MS10-053에서 설명한 네 가지 문제점을 보고해 주신 [VUPEN Vulnerability Research Team (영문)](http://www.vupen.com)의 Nicolas Joly
-   MS10-053에서 설명한 문제점을 보고해 주신 Gambino ZaDarkSide
-   MS10-054에서 설명한 문제점을 보고해 주신 [stratsec (영문)](http://www.stratsec.net/)의 Laurent Gaffié
-   MS10-054에서 설명한 문제점을 보고해 주신 [Sourcefire VRT (영문)](http://www.sourcefire.com/services/sf_vrt.html)의 Todd Wease 및 Richard Johnson
-   MS10-054에서 설명한 문제점을 보고해 주신 [Codenomicon (영문)](http://www.codenomicon.com/)의 Riku Hietamaki 및 Joshua Morin
-   MS10-055에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS10-056에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 [team509 (영문)](http://www.team509.com/)의 L.W.Z
-   MS10-056에서 설명한 문제점을 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)와 협력하여 보고해 주신 [team509 (영문)](http://www.team509.com/)의 Wushi
-   MS10-056에서 설명한 문제점을 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)와 협력하여 보고해 주신 [team509 (영문)](http://www.team509.com/)
-   MS10-056에서 설명한 문제점을 보고해 주신 [Check Point (영문)](http://www.checkpoint.com/) IPS Research Team의 Rodrigo Rubira Branco
-   MS10-056에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS10-057에서 설명한 문제점을 보고해 주신 [Core Security Technologies (영문)](http://www.coresecurity.com/)의 Damián Frizza
-   MS10-058에서 설명한 문제점을 보고해 주신 [Fourteenforty Research Institute, Inc. (영문)](http://www.fourteenforty.jp/)의 Darren Willis
-   MS10-058에서 설명한 문제점을 보고해 주신 [MoonSols (영문)](http://moonsols.com/)의 Matthieu Suiche
-   MS10-059에서 설명한 두 가지 문제점을 해결하기 위해 협력해 주신 [Argeniss (영문)](http://www.argeniss.com/)의 Cesar Cerrudo
-   MS10-060에서 설명한 문제점을 보고해 주신 의 Carsten Book
-   MS10-060에서 설명한 문제점을 보고해 주신 [Eamon Nerbonne (영문)](http://eamon.nerbonne.org/)

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2010년 8월 3일): 공지 요약이 게시되었습니다.
-   V2.0(2010년 8월 11일): MS10-047 - MS10-060 공지가 추가됨
-   V2.1(2010년 9월 2일): Word 2007을 사용하는 고객에게 보안 업데이트 패키지 KB2251419 이외에도 보안 업데이트 패키지 KB2277947을 설치해야 함을 알리기 위해 MS10-056에 설명이 추가되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
