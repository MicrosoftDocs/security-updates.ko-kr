---
TOCTitle: 'MS11-APR'
Title: Microsoft Security Bulletin Summary for 4월 2011
ms:assetid: 'ms11-apr'
ms:contentKeyID: 61230732
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms11-apr(v=Security.10)'
---


Microsoft Security Bulletin Summary for 4월 2011
================================================

게시된 날짜: 2011년 4월 12일 화요일 | 업데이트된 날짜: 2011년 10월 27일 목요일

**버전:** 6.1

이 공지 요약 목록에는 2011년 4월 발표된 보안 공지가 포함되어 있습니다.

2011년 4월 보안 공지 발표와 함께 이 공지 요약이 2011년 4월 7일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2011년 4월 13일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [4월 보안 공지 웹캐스트에 지금 등록하십시오(영문)](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=ko-kr&eventid=1032455070&countrycode=kr). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약(영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. 기타 정보 섹션을 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-018">MS11-018</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2497640) <br />
<br />
이 보안 업데이트는 Internet Explorer에 대해 비공개적으로 보고된 취약점 4건과 공개된 취약점 1건을 해결합니다. 이 보안 업데이트의 심각도는 Windows 클라이언트의 Internet Explorer 6, Internet Explorer 7 및 Internet Explorer 8에 대해서는 긴급이며, Windows 서버의 Internet Explorer 6, Internet Explorer 7 및 Internet Explorer 8에 대해서는 보통입니다. Internet Explorer 9은 이 취약점의 영향을 받지 않습니다.<br />
<br />
가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-019">MS11-019</a></td>
<td style="border:1px solid black;">SMB 클라이언트의 취약점으로 인한 원격 코드 실행 문제점(2511455) <br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 가장 위험한 취약점으로 인해 공격자가 특수하게 조작된 SMB 응답을 클라이언트가 시작한 SMB 요청에 보낼 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자는 사용자가 특수하게 조작된 SMB 서버에 SMB 연결을 시작하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-020">MS11-020</a></td>
<td style="border:1px solid black;">SMB 서버의 취약점으로 인한 원격 코드 실행 문제점(2508429) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 취약점으로 인해 공격자가 특수하게 조작된 SMB 패킷을 만들어 영향을 받는 시스템에 보내는 경우 원격 코드 실행이 허용될 수 있습니다. 방화벽 구성 모범 사례와 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 이 취약점을 악용하려는 공격으로부터 네트워크를 보호할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-027">MS11-027</a></td>
<td style="border:1px solid black;">ActiveX 킬(Kill) 비트 누적 보안 업데이트(2508272) <br />
<br />
이 보안 업데이트는 Microsoft 소프트웨어에 대해 비공개적으로 보고된 취약점 2건과 공개된 취약점 1건을 해결합니다. 이러한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특정 ActiveX 컨트롤을 인스턴스화하는 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 또한 이 업데이트에는 3개의 타사 ActiveX 컨트롤에 대한 킬(Kill) 비트도 포함되어 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-028">MS11-028</a></td>
<td style="border:1px solid black;">.NET Framework의 취약점으로 인한 원격 코드 실행 문제점(2484015) <br />
<br />
이 보안 업데이트는 Microsoft .NET Framework의 공개된 취약점을 해결합니다. 사용자가 XBAP(XAML 브라우저 응용 프로그램)을 실행할 수 있는 웹 브라우저를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 이 취약점으로 인해 클라이언트 시스템에서 원격 코드가 실행될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 서버에서 ASP.NET 페이지 처리를 허용하고 공격자가 해당 서버에 특수하게 조작한 ASP.NET 페이지를 성공적으로 업로드하여 실행할 경우 이 취약점으로 인해 IIS를 실행하는 서버 시스템에서 원격 코드 실행이 허용될 수 있습니다. 이러한 경우는 웹 호스팅 시나리오에서 발생할 수 있습니다. 이 취약점은 CAS(코드 액세스 보안) 제한을 우회하기 위해 Windows .NET 응용 프로그램에서 사용될 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-029">MS11-029</a></td>
<td style="border:1px solid black;">GDI+의 취약점으로 인한 원격 코드 실행 문제점(2489979) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows GDI+의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 영향을 받는 소프트웨어를 사용하여 특수하게 조작된 이미지를 보거나 특수하게 조작된 콘텐츠가 포함된 웹사이트를 탐색할 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-030">MS11-030</a></td>
<td style="border:1px solid black;">DNS 확인 취약점으로 인한 원격 코드 실행 문제점(2509553) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows DNS 확인의 취약점을 해결합니다. 이 취약점을 악용한 공격자가 네트워크에 액세스하고 특수하게 조작된 LLMNR 브로드캐스트 쿼리를 대상 시스템에 보내는 사용자 지정 프로그램을 만들 경우 원격 코드 실행이 허용될 수 있습니다. 최선의 방화벽 구성 방법과 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 들어오는 공격으로부터 네트워크를 보호할 수 있습니다. 인터넷과 연결되는 시스템의 경우, 필요한 포트만 최소한으로 열어 두는 것이 안전합니다. 이런 경우 LLMNR 포트를 인터넷에서 차단해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-031">MS11-031</a></td>
<td style="border:1px solid black;">JScript 및 VBScript 스크 립팅 엔진의 취약점으로 인한 원격 코드 실행 취약점(2514666) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 JScript 및 VBScript 스크립팅 엔진의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 웹 사이트를 방문할 경우 원격 코드 실행이 허용될 수 있습니다. 공격자는 강제로 사용자가 웹 사이트를 방문하도록 할 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-032">MS11-032</a></td>
<td style="border:1px solid black;">OpenType CFF(Compact Font Format) 드라이버의 취약점으로 인한 원격 코드 실행 문제점(2507618) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 OpenType CFF(Compact Font Format) 드라이버의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 CFF 글꼴로 렌더링된 콘텐츠를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 특수하게 조작된 콘텐츠를 보도록 만들 수는 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Microsoft Excel의 취약점으로 인한 원격 코드 실행 문제점(2489279) <br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 9건을 해결합니다. 사용자가 특수하게 조작된 Excel 파일을 열면 이러한 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-022">MS11-022</a></td>
<td style="border:1px solid black;">Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점(2489283) <br />
<br />
이 보안 업데이트는 Microsoft PowerPoint에서 발견되어 비공개적으로 보고된 3건의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 PowerPoint 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. <a href="http://support.microsoft.com/kb/2501584">Microsoft 기술 자료 문서 2501584</a>에서 사용할 수 있는 PowerPoint 2010, &quot;PowerPoint 2010의 제한된 보기에서 편집을 사용하지 않도록 설정&quot;에 대한 Microsoft Fix it 자동화 솔루션은 CVE-2011-0655 및 CVE-2011-0656에 설명된 취약점을 악용하는 공격 경로를 차단합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server 소프트웨어</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-023">MS11-023</a></td>
<td style="border:1px solid black;">Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점(2489293) <br />
<br />
이 보안 업데이트는 Microsoft Office의 공개된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 Office 파일을 열거나 특수하게 조작된 라이브러리 파일과 동일한 네트워크 디렉터리에 있는 합법적인 Office 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-024">MS11-024</a></td>
<td style="border:1px solid black;">Windows 팩스 표지 편집기의 취약점으로 인한 원격 코드 실행 문제점(2527308) <br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 팩스 표지 파일(.cov)을 Windows 팩스 표지 편집기를 사용하여 열 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-025">MS11-025</a></td>
<td style="border:1px solid black;">MFC(Microsoft Foundation Class) 라이브러리의 취약점으로 인한 원격 코드 실행 문제점(2500212) <br />
<br />
이 보안 업데이트는 MFC(Microsoft Foundation Class) 라이브러리를 사용하여 만든 특정 응용 프로그램의 일반에 공개된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 영향을 받는 응용 프로그램과 연결된 합법적인 파일 및 특수하게 조작된 라이브러리 파일과 동일한 네트워크 폴더에 있는 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 공격에 성공하려면, 사용자가 신뢰할 수 없는 원격 파일 시스템 위치 또는 WebDAV 공유를 방문하거나 이러한 위치에서 영향을 받는 응용 프로그램이 로드되는 문서를 열어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft 개발자 도구 및 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-026">MS11-026</a></td>
<td style="border:1px solid black;">MHTML의 취약점으로 인한 정보 유출 문제점(2503658) <br />
<br />
이 보안 업데이트는 일반에 공개된 Microsoft Windows MHTML 프로토콜 처리기의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 웹 사이트를 방문할 경우 정보 유출이 발생할 수 있습니다. 웹 기반의 공격 시나리오에서 웹 사이트는 이 취약점을 악용하는 데 사용되는 특수하게 조작된 링크를 포함하고 있을 수 있습니다. 공격자는 사용자가 웹 사이트를 방문하고 특수하게 조작된 링크를 열도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-033">MS11-033</a></td>
<td style="border:1px solid black;">WordPad 텍스트 변환기의 취약점으로 인한 원격 코드 실행 문제점(2485663) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 보안 업데이트의 심각도는 지원 대상인 모든 Windows XP 및 Windows Server 2003 에디션에 대해 중요입니다. 지원 대상인 모든 Windows Vista, Windows Server 2008, Windows 7 및 Windows Server 2008 R2 에디션은 이 취약점의 영향을 받지 않습니다.<br />
<br />
이러한 취약점으로 인해 사용자가 WordPad를 사용하여 특수하게 조작된 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Windows 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2506223) <br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 30건을 해결합니다. 이 취약점으로 인해 공격자가 시스템에 로컬로 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
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
  
이표를 어떻게 사용합니까?
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >공지 번호</th>
<th style="border:1px solid black;" >취약점 제목</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >악용 가능성 인덱스 평가</th>
<th style="border:1px solid black;" >주요 정보</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-025">MS11-025</a></td>
<td style="border:1px solid black;">MFC의 안전하지 않은 라이브러리 로드 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3190">CVE-2010-3190(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-028">MS11-028</a></td>
<td style="border:1px solid black;">.NET Framework 스택 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3958">CVE-2010-3958(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-032">MS11-032</a></td>
<td style="border:1px solid black;">OpenType 글꼴 스택 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0034">CVE-2011-0034(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-029">MS11-029</a></td>
<td style="border:1px solid black;">GDI+ 정수 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0041">CVE-2011-0041(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-018">MS11-018</a></td>
<td style="border:1px solid black;">레이아웃 처리 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0094">CVE-2011-0094(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">이 취약점은 제한적이며 대상이 일정한 공격에서 악용되고 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel 정수 오버런 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0097">CVE-2011-0097(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel 힙 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0098">CVE-2011-0098(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel 레코드 분석 WriteAV 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0101">CVE-2011-0101(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-023">MS11-023</a></td>
<td style="border:1px solid black;">Office 구성 요소의 안전하지 않은 라이브러리 로드 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0107">CVE-2011-0107(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-018">MS11-018</a></td>
<td style="border:1px solid black;">MSHTML 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0346">CVE-2011-0346(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-019">MS11-019</a></td>
<td style="border:1px solid black;">SMB 클라이언트 응답 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0660">CVE-2011-0660(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-020">MS11-020</a></td>
<td style="border:1px solid black;">SMB 트랜잭션 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0661">CVE-2011-0661(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0662">CVE-2011-0662(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0665">CVE-2011-0665(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0666">CVE-2011-0666(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0667">CVE-2011-0667(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0670">CVE-2011-0670(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0671">CVE-2011-0671(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0672">CVE-2011-0672(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0673">CVE-2011-0673(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0674">CVE-2011-0674(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0675">CVE-2011-0675(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0676">CVE-2011-0676(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0677">CVE-2011-0677(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-022">MS11-022</a></td>
<td style="border:1px solid black;">OfficeArt Atom RCE 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0976">CVE-2011-0976(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel 배열 인덱싱 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0978">CVE-2011-0978(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel 연결된 목록 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0979">CVE-2011-0979(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel 현수 포인터 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0980">CVE-2011-0980(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1225">CVE-2011-1225(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1226">CVE-2011-1226(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1227">CVE-2011-1227(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1228">CVE-2011-1228(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1229">CVE-2011-1229(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1230">CVE-2011-1230(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1231">CVE-2011-1231(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1232">CVE-2011-1232(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1233">CVE-2011-1233(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1235">CVE-2011-1235(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1236">CVE-2011-1236(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1237">CVE-2011-1237(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1239">CVE-2011-1239(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1240">CVE-2011-1240(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1241">CVE-2011-1241(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1242">CVE-2011-1242(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-018">MS11-018</a></td>
<td style="border:1px solid black;">개체 관리 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1345">CVE-2011-1345(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">이 취약점은 제한적이며 대상이 일정한 공격에서 악용되고 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-033">MS11-033</a></td>
<td style="border:1px solid black;">WordPad 변환기 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0028">CVE-2011-0028(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0103">CVE-2011-0103(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel 버퍼 덮어쓰기 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0104">CVE-2011-0104(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel 데이터 초기화 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0105">CVE-2011-0105(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-019">MS11-019</a></td>
<td style="border:1px solid black;">브라우저 풀 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0654">CVE-2011-0654(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-022">MS11-022</a></td>
<td style="border:1px solid black;">부동점 테크노컬러 타임 밴디트 RCE 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0655">CVE-2011-0655(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-022">MS11-022</a></td>
<td style="border:1px solid black;">일정한 디렉터리 RCE 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0656">CVE-2011-0656(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-030">MS11-030</a></td>
<td style="border:1px solid black;">DNS 쿼리 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0657">CVE-2011-0657(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-031">MS11-031</a></td>
<td style="border:1px solid black;">스크립팅 메모리 재할당 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0663">CVE-2011-0663(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-023">MS11-023</a></td>
<td style="border:1px solid black;">Microsoft Office 그래픽 개체 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0977">CVE-2011-0977(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1234">CVE-2011-1234(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212226">MS11-024</a></td>
<td style="border:1px solid black;">팩스 표지 편집기 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3974">CVE-2010-3974(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> – 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-024">MS11-024</a></td>
<td style="border:1px solid black;">팩스 표지 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-4701">CVE-2010-4701(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> – 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-026">MS11-026</a></td>
<td style="border:1px solid black;">MHTML MIME 형식의 요청 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0096">CVE-2011-0096(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> – 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1238">CVE-2011-1238(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> – 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-018">MS11-018</a></td>
<td style="border:1px solid black;">Javascript 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1245">CVE-2011-1245(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> – 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
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
[MS11-018](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-018)
</td>
<td style="border:1px solid black;">
[MS11-019](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-019)
</td>
<td style="border:1px solid black;">
[MS11-020](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-020)
</td>
<td style="border:1px solid black;">
[MS11-027](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-027)
</td>
<td style="border:1px solid black;">
[MS11-028](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-028)
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-030](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-030)
</td>
<td style="border:1px solid black;">
[MS11-031](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-031)
</td>
<td style="border:1px solid black;">
[MS11-032](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-032)
</td>
<td style="border:1px solid black;">
[MS11-024](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-024)
</td>
<td style="border:1px solid black;">
[MS11-026](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-026)
</td>
<td style="border:1px solid black;">
[MS11-033](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-033)
</td>
<td style="border:1px solid black;">
[MS11-034](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034)
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
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6(영문)](https://www.microsoft.com/download/details.aspx?familyid=c3a8cec0-f947-4d4e-a6ae-c7f4f1f311b0)  
(긴급)  
[Internet Explorer 7(영문)](https://www.microsoft.com/download/details.aspx?familyid=0b7d0403-8965-4c62-970c-20b561f66713)  
(긴급)  
[Internet Explorer 8(영문)](https://www.microsoft.com/download/details.aspx?familyid=689c5496-56c4-48a6-9f3d-b5f5aaf3e566)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=f5378e7b-4619-4c42-9d9f-87b209c6d878)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=ccb08a8a-f4d9-4320-8ffb-3fd4fe217987)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=b031a496-aa74-4367-b2ae-24843c061745)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(긴급)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=59266a9d-a319-4309-a046-7f15c6da0136)  
(KB2412687)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=2d433adb-bcaf-4c59-9405-a4892f8ccba3)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.7 및 VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=637f4d4c-de07-4c6a-95f8-3bd0cbfe77b2)  
(KB2510581)  
(긴급)  
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=fbe1e7e3-1d5f-4daf-a4a5-67fe79292963)  
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=9080c5a1-e638-4047-a70a-9367f1acced7)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=50fc3869-f2fc-43c8-8049-aad62f2cb332)   
(KB2491683)  
(중요)  
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=a8220a21-02fc-4ad6-988d-844276b2fd66)   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=7f0a4616-8e3e-4925-9d95-ce6e614e45ae)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=6753ca98-feb4-4c7f-9969-9294038a2bbb)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=39e55bbf-c1c5-4696-bfe7-632e997cd98e)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=986f07ae-0fdc-4be2-8a74-5eb56d4300ef)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ed88f183-dd06-46f6-ae8a-a594a752f248)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6d3433ee-c2e1-433f-a3d9-c049d66e2190)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c01441da-8933-4f60-923b-d9b00db8ba3d)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7ee202da-a711-42ee-bea3-7202a70e4ea0)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eddd2964-9765-461d-9df8-2c05402948e8)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(긴급)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3797009a-b9a4-4e83-8614-e1589c8b5090)  
(KB2412687)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=29ff546e-a232-4f23-a223-c029c71ff1c6)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.6 및 VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=a5586246-2908-4def-9298-c16060098197)  
(KB2510587)  
(긴급)  
[JScript 5.7 및 VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=3a5f65e0-bb00-4e55-b8b5-77751349a3ec)  
(KB2510581)  
(긴급)  
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=57aa7ee2-254d-40b5-9ff0-cba969daf45a)  
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2374e09a-cb3e-4bc3-bb4b-53b611025121)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b93311b4-1b8f-478d-8833-750c5e01e6f8)   
(KB2491683)  
(중요)  
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0f60fc99-cd88-4237-8b31-a4e618502f7e)   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b01fe9a5-66a4-4683-963b-e78aea214579)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3c94bc96-99ea-44a1-9052-e69de5e21f81)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=83771177-284e-4918-86a9-980e8229c7c9)  
(중요)
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
[MS11-018](http://go.microsoft.com/fwlink/?linkid=214126)
</td>
<td style="border:1px solid black;">
[MS11-019](http://go.microsoft.com/fwlink/?linkid=212314)
</td>
<td style="border:1px solid black;">
[MS11-020](http://go.microsoft.com/fwlink/?linkid=212236)
</td>
<td style="border:1px solid black;">
[MS11-027](http://go.microsoft.com/fwlink/?linkid=214005)
</td>
<td style="border:1px solid black;">
[MS11-028](http://go.microsoft.com/fwlink/?linkid=207931)
</td>
<td style="border:1px solid black;">
[MS11-029](http://go.microsoft.com/fwlink/?linkid=208524)
</td>
<td style="border:1px solid black;">
[MS11-030](http://go.microsoft.com/fwlink/?linkid=212595)
</td>
<td style="border:1px solid black;">
[MS11-031](http://go.microsoft.com/fwlink/?linkid=212243)
</td>
<td style="border:1px solid black;">
[MS11-032](http://go.microsoft.com/fwlink/?linkid=212224)
</td>
<td style="border:1px solid black;">
[MS11-024](http://go.microsoft.com/fwlink/?linkid=212226)
</td>
<td style="border:1px solid black;">
[MS11-026](http://go.microsoft.com/fwlink/?linkid=212523)
</td>
<td style="border:1px solid black;">
[MS11-033](http://go.microsoft.com/fwlink/?linkid=208110)
</td>
<td style="border:1px solid black;">
[MS11-034](http://go.microsoft.com/fwlink/?linkid=211826)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
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
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[낮음](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=b902c58a-9e2f-4352-8d2f-fffda5344598)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5c464287-3dab-4342-a38d-a12719d3b158)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=45feb35b-b24e-4160-adb0-d0b7ae530e90)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d46fe0bf-28c2-4696-87bc-dd3c8287fc28)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=64c550d4-c927-4382-91e1-473ed6790819)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=53756404-39e4-43af-81e9-81471536aa66)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(긴급)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=fd284233-e177-4064-9b02-f83dcb727dbe)  
(KB2412687)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=753ed6e3-df2e-4b2d-9e9f-7275cd94d214)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.6 및 VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=e026f2ed-8a20-4268-9b29-04a78bde1999)  
(KB2510587)  
(긴급)  
[JScript 5.7 및 VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=5b0ed0b2-07f9-43da-bb5d-5be5a45969ee)  
(KB2510581)  
(긴급)  
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=01aa2beb-9fc1-40f0-a2a4-bcd3d9cb31f8)  
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5d71d3f5-fd6b-4f3b-8389-37c899748d4b)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=edda8cce-b764-4ef1-afbe-391fbd087362)   
(KB2491683)  
(중요)  
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=bf084b4c-aac9-4cc6-bb30-87fc96ba9430)   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0209a004-f23a-40d9-991f-864046f4605f)  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9fbfc742-6c74-49a2-b3cc-e1d5d8c84b77)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=af320f27-bb3a-4e76-a279-4632267c8761)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=5d8f14d1-85cc-478f-8b50-5c355a331f59)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9d8bbea9-c456-4569-ad96-c2cd0f5fae7e)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=979d2ec5-5114-4ec7-aa97-e9289c590cbb)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ca0fb4d3-7651-4760-83fa-b71c86cbe459)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ef62db94-4f72-4245-ac9f-6391035e2516)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c8d59f49-45ec-4527-b3a8-4925f710bbfd)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(긴급)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d5adaf4e-4cd7-42ea-8202-31b5c856f5e3)  
(KB2412687)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a0192dbc-4d0d-4555-9ef7-3e10209a6389)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.6 및 VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=83ce6c99-a57d-4ed1-972b-a6b6798e6675)  
(KB2510587)  
(긴급)  
[JScript 5.7 및 VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=af791715-77a1-405b-a69e-d63f75dd7ccd)  
(KB2510581)  
(긴급)  
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=bf0a2966-25c4-4717-bcd6-016ce610d220)  
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3a498ff0-21d9-493a-b127-6bc20f1baf95)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f04d939a-da11-4a9f-9e03-b6c3bf3ca58b)   
(KB2491683)  
(중요)  
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=12b01f3a-ccf8-41c1-ac5a-e417a6ddbe95)   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6c287571-54ea-4298-8b7d-b98b2c830cc3)  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=897b97b0-1bab-4b1b-b417-950fab0d4a65)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9c95f81c-9812-4070-88d7-34422c638e42)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=8afe86fc-58b4-4a95-b047-c09138fa4f5e)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f1abfb48-3c8a-4b2d-b739-cc61628b387d)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=87eb8b93-9829-45ec-9528-52787732044e)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=79aeb3cd-7c73-467b-b91e-02c6ea01e911)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=9c784734-f44f-4a3c-8223-6289f7dc2ad8)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(긴급)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=72a513bb-f901-4992-8562-d1afe1afec8a)  
(KB2412687)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=f5ad6963-2d6a-4d59-9e25-4fc088647fcd)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.6 및 VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=b7d36bae-7ca4-4a40-9efb-13f484fa5518)  
(KB2510587)  
(긴급)  
[JScript 5.7 및 VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=3f519013-ed14-41a8-aa45-cf8b095d3152)  
(KB2510581)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=c71f4398-2e3b-4b81-a650-8806e618db7f)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=efb575c7-3259-49b1-b59c-89d9544e37a6)   
(KB2491683)  
(중요)  
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=03a7ee49-7bd6-4215-9779-1b48c10d08b9)   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=3fb450a0-d087-4f36-9301-05ffbf94cc1a)  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=ede38974-4e57-4ea1-8731-b91e96534693)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=f58cf64a-bf31-4496-be75-5775a123338b)  
(중요)
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
[MS11-018](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-018)
</td>
<td style="border:1px solid black;">
[MS11-019](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-019)
</td>
<td style="border:1px solid black;">
[MS11-020](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-020)
</td>
<td style="border:1px solid black;">
[MS11-027](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-027)
</td>
<td style="border:1px solid black;">
[MS11-028](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-028)
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-030](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-030)
</td>
<td style="border:1px solid black;">
[MS11-031](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-031)
</td>
<td style="border:1px solid black;">
[MS11-032](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-032)
</td>
<td style="border:1px solid black;">
[MS11-024](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-024)
</td>
<td style="border:1px solid black;">
[MS11-026](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-026)
</td>
<td style="border:1px solid black;">
[MS11-033](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-033)
</td>
<td style="border:1px solid black;">
[MS11-034](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=00c3c176-feff-4022-ac4c-2d4732ca3d78)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5ea94705-4f76-4b0d-bbbc-afb5e75204bf)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=da8dd55d-6630-484e-836c-9feeab5cc311)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d6eddff4-a242-4dec-9d84-72891db2b754)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=80bf050a-9aff-4cd4-8e2f-196b0a92b1c0)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)  
(KB2449741)  
(긴급)  
Windows Vista 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)  
(KB2449742)  
(긴급)  
Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2:  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4ff2e440-79c2-4045-b225-913d1740fdb9)  
(KB2412687)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2a17e44f-54aa-423d-b3c7-a4f404f7c28b)  
(긴급)
</td>
<td style="border:1px solid black;">
[JScript 5.7 및 VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=719e2c86-30e5-4cd5-94f4-d6de54efee5f)  
(KB2510581)  
(긴급)  
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=21decb84-75ef-4bde-a802-1e661a505e94)<sup>[1]</sup>
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e7c4fc81-d1ef-4378-862b-e955d75fb2de)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=11a8f240-51b3-4e31-a24a-a235179f3396)   
(KB2491683)  
(중요)  
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e6cba040-9d7c-4777-a2f7-e4dd11dfb845)   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c8fce0fb-4c90-479b-8ce9-75e60d52d256)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b4743167-9614-445a-9e91-10efdac505a8)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=79f52733-44e4-47b6-86ca-1395a095b4e7)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=bc63b233-9db0-4fb1-a61c-fa7e9e44ba10)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=040f8b46-f458-4a72-a1b0-ad8a65a1194c)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2878c587-6544-40b4-9288-fc3b3ce1128d)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a81412d0-2516-4bf4-87f7-3e41ebf6b82b)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)  
(KB2449741)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)  
(KB2449742)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2:  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4d826026-e62a-4cec-8682-49fbe7f65cd6)  
(KB2412687)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e708d24f-e348-4c4d-99ed-e78dd1689d01)  
(긴급)
</td>
<td style="border:1px solid black;">
[JScript 5.7 및 VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=89b9d01e-bcbc-4f2c-973b-51051494f406)  
(KB2510581)  
(긴급)  
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=d4ac199e-7bf8-4661-a4e5-c53719b2673a)<sup>[1]</sup>
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8d654a78-0e4f-452c-8874-fbf478813857)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=61db662e-88d7-4454-b4b7-e987728fb137)   
(KB2491683)  
(중요)  
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1c942282-0f80-46c1-aeef-1ef948e105a3)   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7da10b64-d0a9-4e42-aa3a-87c657122a8c)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7e410d5c-b9f7-4a63-8300-36b2d57c6128)  
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
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-018](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-018)
</td>
<td style="border:1px solid black;">
[MS11-019](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-019)
</td>
<td style="border:1px solid black;">
[MS11-020](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-020)
</td>
<td style="border:1px solid black;">
[MS11-027](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-027)
</td>
<td style="border:1px solid black;">
[MS11-028](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-028)
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-030](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-030)
</td>
<td style="border:1px solid black;">
[MS11-031](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-031)

</td>
<td style="border:1px solid black;">
[MS11-032](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-032)
</td>
<td style="border:1px solid black;">
[MS11-024](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-024)
</td>
<td style="border:1px solid black;">
[MS11-026](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-026)
</td>
<td style="border:1px solid black;">
[MS11-033](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-033)
</td>
<td style="border:1px solid black;">
[MS11-034](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
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
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[낮음](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7d8603b8-bb52-4cf6-be8b-bb3475d30fc5)\*\*  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d5d76e90-1cef-47e8-9d8d-2c5a43f42ba3)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f8c9390a-5ca1-492a-9e35-a516de48deb5)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=31c48ba9-7774-4633-862d-5c27c3703584)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c3247886-76d0-4292-be9d-3e9b0221c46a)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008만(32비트 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)\*\*  
(KB2449741)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)\*\*  
(KB2449742)  
(긴급)  
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2:  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)\*\*<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=fbada866-7d36-4b85-acde-fd856a998737)\*\*\*  
(KB2412687)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9894be38-a582-4c15-ad0e-cc3afab2aebc)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[JScript 5.7 및 VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=d8b33ffd-eff1-4a10-b6fc-3c8f01e0fec5)\*\*  
(KB2510581)  
(긴급)  
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=afd128ff-717f-4d98-b214-f2c28d59623d)\*\*<sup>[1]</sup>
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9105377e-83c7-4010-8fd6-26e42e98c2cc)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=90f56368-776b-4d45-ad68-91afbd316d25)\*\*   
(KB2491683)  
(중요)  
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=fa972742-1166-4a9e-ab64-6a4f968f9c6d)\*   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=036f1285-7484-4e3b-8799-2c6c08166596)\*\*  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c6ac26b8-8cc8-40fe-baab-22bf13df1aa8)\*  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c6d58f64-bdd5-4fe6-96f4-9641b8e7b570)\*\*  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=51203a31-368b-4b47-96a5-9e9e5a55cd76)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b0cfd5e0-6de5-4863-b5e4-b223a0e36d72)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=de843115-cf98-4511-aa93-f620e4572555)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=51521b6b-94a7-4bcf-ad5f-fc304728b10f)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008만(x64 기반 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)\*\*  
(KB2449741)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)\*\*  
(KB2449742)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2:  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)\*\*<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8f4ddfcb-374d-4cad-8c61-2b988b46f628)\*\*\*  
(KB2412687)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2d7d2021-020f-4cc9-a027-258d7e5faec9)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[JScript 5.7 및 VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=6c2e6b87-afcd-461a-8a43-9a2fb277b18a)\*\*  
(KB2510581)  
(긴급)  
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=40e8beca-0b5a-43b0-98f8-b32a82ad65d6)\*\*<sup>[1]</sup>
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=060e8b20-edca-4427-9d60-eb57261eb668)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=22a001fc-5c2e-4539-85c9-0c2054a1777d)\*\*   
(KB2491683)  
(중요)  
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=fc250c8a-ebaf-4264-9393-dc23cc372d9f)\*   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1438cec8-8dab-4510-ad75-dc6959dac0d8)\*\*  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ac49f5d3-5e2f-4916-99be-a3254278da7e)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f6f6f22c-fc7f-4e96-b6b5-be3c1acecf6e)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8eaf51cd-2f6e-4bbc-bc4f-9deed03649ac)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b89b8e28-cd98-4bcc-8729-5e51d52d1e92)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e7c38b0d-7240-420a-88d3-2749a40e386f)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용)만:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)  
(KB2449741)  
(긴급)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)  
(KB2449742)  
(긴급)  
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2:  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2fd71543-0e18-4907-89b9-355d24d7db69)  
(KB2412687)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c0275df0-10ac-4500-ab86-b7e9a34f8e1d)  
(긴급)
</td>
<td style="border:1px solid black;">
[JScript 5.7 및 VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=afb49d24-1913-4e5f-a3ea-c6c9642e2017)  
(KB2510581)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2b8571cb-2dae-4bff-9f13-feb89840044c)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=421024f1-aa86-459e-b6de-53851a3fcba2)   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f35ecdd1-6b5c-40e7-a00b-ca083bdf5cba)  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3b93de4f-01f4-4efd-afc1-31d87b92fad2)  
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
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-018](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-018)
</td>
<td style="border:1px solid black;">
[MS11-019](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-019)
</td>
<td style="border:1px solid black;">
[MS11-020](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-020)
</td>
<td style="border:1px solid black;">
[MS11-027](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-027)
</td>
<td style="border:1px solid black;">
[MS11-028](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-028)
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-030](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-030)
</td>
<td style="border:1px solid black;">
[MS11-031](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-031)
</td>
<td style="border:1px solid black;">
[MS11-032](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-032)
</td>
<td style="border:1px solid black;">
[MS11-024](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-024)
</td>
<td style="border:1px solid black;">
[MS11-026](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-026)
</td>
<td style="border:1px solid black;">
[MS11-033](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-033)
</td>
<td style="border:1px solid black;">
[MS11-034](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=59676b71-8b9d-4230-a9e0-b20db3e3ec7e)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=0dcba089-19f7-46ca-9e52-24eaebad4715)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=d3ef905b-3584-4842-9ec2-cf3856305d49)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=46510959-e4a2-4c21-b33c-fd3d97b3ac3d)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)  
(KB2446709)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)  
(KB2446710)  
(긴급)  
Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1:  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=8fdae09b-d1bb-4ef5-aa45-2a05f2a5e12d)  
(긴급)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=17ebf291-fdae-4e78-9377-871b3103ce16)<sup>[1]</sup>
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=751c45ea-0943-4948-807f-8716c6ff9198)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=bf762b86-b949-4e84-8ca4-93ebe669c1b8)   
(KB2491683)  
(중요)  
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=0f5a122e-dd5e-4b08-881a-f13b38642720)   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=aed201c1-f1fb-4df9-8875-6f57ea0eb15b)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=6e7ff003-ff3f-49bb-8e45-d869885dd8d7)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3a998678-2678-489e-8711-39322663147d)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b7fd356a-56d0-4638-8901-40acfa600f25)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=7ddc943b-6868-4e8f-a869-89b47133c287)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=432555cf-aed8-4329-a74f-526441521082)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)  
(KB2446709)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)  
(KB2446710)  
(긴급)  
Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1:  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=40879dfb-efa4-41ba-8d5c-22e926a55eef)  
(긴급)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=c95ad86d-da58-4d7a-9ffd-8441f92baaa5)<sup>[1]</sup>
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=976c882a-bc07-4128-927f-82a2df46cf45)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a6793ecf-a3f6-4989-8e4c-c5c0005f9ac4)   
(KB2491683)  
(중요)  
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=658301f1-103a-48a2-9b67-61cf8e1dad50)   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1a32bf04-7eed-4d27-a8e4-054b4a5b76cb)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=0c0aef7e-501c-4ca3-ae7f-497a8c169121)  
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
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-018](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-018)
</td>
<td style="border:1px solid black;">
[MS11-019](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-019)
</td>
<td style="border:1px solid black;">
[MS11-020](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-020)
</td>
<td style="border:1px solid black;">
[MS11-027](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-027)
</td>
<td style="border:1px solid black;">
[MS11-028](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-028)
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-030](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-030)
</td>
<td style="border:1px solid black;">
[MS11-031](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-031)
</td>
<td style="border:1px solid black;">
[MS11-032](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-032)
</td>
<td style="border:1px solid black;">
[MS11-024](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-024)
</td>
<td style="border:1px solid black;">
[MS11-026](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-026)
</td>
<td style="border:1px solid black;">
[MS11-033](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-033)
</td>
<td style="border:1px solid black;">
[MS11-034](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-034)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
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
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[낮음](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c7b2482b-44bf-4c01-99d8-f93868659a24)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=27a3847b-695b-4f60-aea5-86b0dbe68945)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=c4352802-9c5a-4c07-8303-3a4b78d3f954)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=e4fa8ed0-acb0-4864-be18-29a27f8501de)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)\*  
(KB2446709)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용)만 해당:  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)\*  
(KB2446710)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)\*<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=2084c726-187e-41f9-9bea-da18f490d29e)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=aecc2c7a-285c-409d-be23-c5b4b5449496)\*\*<sup>[1]</sup>
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=6f2a52cc-4833-448d-becc-2eac1a447410)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=465c0478-6a74-4b00-8608-938cc492549f)\*\*   
(KB2491683)  
(중요)  
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=4c5c3a0f-0672-49d0-bcbd-c7f40e11d092)\*   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=665faa7e-2368-4421-9dd5-ea6df2c79498)\*\*  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=2fc66224-45c6-4e8f-ad00-6a1ec30b4505)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=af6db318-fbec-4286-a3a7-4081620146e5)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1e7d3f21-bdbd-4826-855d-85422aa5f836)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=0005377b-443f-44ca-a890-620b2dcea6f1)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=d7bcf4d7-b697-4c5f-adbc-a2b3700e0ad5)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)  
(KB2446709)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)  
(KB2446710)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1:  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=34d2793e-a2cd-49f6-b524-6598ea86175f)  
(긴급)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=e1bc0ed8-5a93-4d01-b407-919dfd894b5f)<sup>[1]</sup>
(KB2510531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=c6ca0b7c-8151-4d54-aa9b-5ec2b75d8ab6)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1a993f8c-d28a-4a95-a3c6-059f06e75461)   
(KB2506212)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=140ea384-2877-401f-ac3b-f84f6966e970)  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=485ccf96-27a0-499e-9f52-2836b73d26d2)  
(중요)
</td>
</tr>
</table>
 
Windows Server 2008 및 Windows Server 2008 R2 참고 사항

\*Server Core 설치가 영향을 받습니다. 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](http://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](http://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

\*\*Server Core 설치는 영향을 받지 않습니다. Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](http://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](http://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

\*\*\*Server Core 설치는 영향을 받지 않습니다. Server Core 설치 옵션을 사용하여 설치한 경우, 시스템에 이 취약점의 영향을 받는 파일이 있는 경우에도 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 그러나 현재 시스템에 있는 파일보다 업데이트 파일이 최신이므로(버전 번호가 높음) 영향을 받는 파일을 가진 사용자에게 이 업데이트가 제공됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](http://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](http://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

MS11-027 참고 사항

<sup>[1]</sup>이 운영 체제는 이 공지에서 설명하는 취약점의 영향을 받지 않습니다. 사용 가능한 업데이트는 타사 컨트롤에 대한 킬(kill) 비트를 설정합니다.

MS11-028 참고 사항

<sup>[1]</sup>.NET Framework 4.0 및 .NET Framework 4.0 Client Profile이 영향을 받습니다. .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4.0 및 .NET Framework 4.0 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4.0 Client Profile은 .NET Framework 4.0의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4.0 및 .NET Framework 4.0 Client Profile에 모두 영향을 줍니다. 자세한 내용은 [.NET Framework 설치](http://msdn.microsoft.com/ko-kr/library/5a4x27ek.aspx)를 참조하십시오.

MS11-029 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

MS11-031 참고 사항

<sup>[1]</sup>Internet Explorer 9가 설치된 시스템은 영향을 받지 않으며 이 업데이트가 필요하지 않습니다. Internet Explorer 9로 업그레이드되지 않은 시스템에는 설치된 JScript 및 VBScript 버전에 맞는 업데이트가 필요합니다. 시스템에서 설치된 JScript 및 VBScript의 버전을 확인하는 방법은 공지를 참조하십시오.

MS11-024 참고 사항

같은 운영 체제에 대해 두 개의 업데이트가 있는 경우 두 업데이트를 모두 설치하십시오.

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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Microsoft Office 제품군 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-021](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021)
</td>
<td style="border:1px solid black;">
[MS11-022](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-022)
</td>
<td style="border:1px solid black;">
[MS11-023](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-023)
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
[Microsoft Office XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=6c87c2a9-3705-4680-8a9b-63b6ec83674d)  
(KB2509461)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=db2c5cfe-588c-4646-b86a-3fb8248f7af4)  
(KB2466169)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=0d215ab6-c9be-4f43-9501-658bb7ef008e)  
(KB2464617)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=6c87c2a9-3705-4680-8a9b-63b6ec83674d)  
(KB2509461)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=916a076d-d754-4092-b23d-c8826db7e397)  
(KB2502786)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=2ce8349f-79b1-41ef-a1c0-cbe40ccf9f20)  
(KB2464588)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=8b68cf68-1606-4649-b860-a64702c6cf33)  
(KB2509503)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5ae34fe0-03bd-48a9-a7ac-de8f7b1aff90)<sup>[1]</sup>
(KB2464583)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6b2526fe-a061-4a17-992e-ac867bef130e)  
(KB2464594)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dbba0cd4-ab72-4e2b-9524-fd6be27f0b02)  
(KB2509488)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010(32비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=a427f0e2-b74d-4ef3-bec4-0a101d09bfa3)  
(KB2466146)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=549ca7f0-44bf-4965-a9d2-aa5e8dac2238)  
(KB2519975)  
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=13dca35d-2209-4c5c-9150-d6db2bb3b496)  
(KB2466146)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=ef62deae-2b07-41c9-a4bf-b746566e59ee)  
(KB2519975)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-021](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021)
</td>
<td style="border:1px solid black;">
[MS11-022](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-022)
</td>
<td style="border:1px solid black;">
[MS11-023](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-023)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Mac용 Microsoft Office 2004](https://www.microsoft.com/download/details.aspx?familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5)  
(KB2505924)  
(중요)
</td>
<td style="border:1px solid black;">
[Mac용 Microsoft Office 2004](https://www.microsoft.com/download/details.aspx?familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5)  
(KB2505924)  
(중요)
</td>
<td style="border:1px solid black;">
[Mac용 Microsoft Office 2004](https://www.microsoft.com/download/details.aspx?familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5)  
(KB2505924)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918)  
(KB2505927)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918)  
(KB2505927)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918)  
(KB2505927)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=ef1e612f-d8e3-4628-9fe4-ad136f0debd3)  
(KB2525412)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=ef1e612f-d8e3-4628-9fe4-ad136f0debd3)  
(KB2525412)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=0c323a12-6385-4666-ad39-a9516a8eda14)  
(KB2505935)  
(중요)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=0c323a12-6385-4666-ad39-a9516a8eda14)  
(KB2505935)  
(중요)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=0c323a12-6385-4666-ad39-a9516a8eda14)  
(KB2505935)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
기타 Office 소프트웨어
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-021](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-021)
</td>
<td style="border:1px solid black;">
[MS11-022](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-022)
</td>
<td style="border:1px solid black;">
[MS11-023](http://technet.microsoft.com/ko-kr/security/bulletin/ms11-023)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2d75786a-2368-4ef2-970b-fa2e57d63ca9)  
(KB2466158)  
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
Microsoft PowerPoint Viewer 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint Viewer 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6e23d3c3-2944-42ea-80b3-0663af60d0f1)  
(KB2464623)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint Viewer](https://www.microsoft.com/download/details.aspx?familyid=44a703f5-b581-4900-bdbb-0f0e8d9bf0e6)  
(KB2519984)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=946cc611-4d75-4728-b9d3-1c8b557b02c2)  
(KB2466156)  
(중요)
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=913efc28-7deb-47b8-8c22-8eb5fc2631e4)  
(KB2464635)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
MS11-029 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

MS11-021 참고 사항

<sup>[1]</sup>Microsoft Excel 2007 서비스 팩 2를 사용하는 고객의 경우 이 공지에서 설명한 취약점으로부터 보호하기 위해 보안 업데이트 패키지 KB2464583 이외에도 Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 서비스 팩 2용 보안 업데이트(KB2466156)를 설치해야 합니다.

MS11-022 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Server 소프트웨어

 
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
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-022](http://go.microsoft.com/fwlink/?linkid=210727)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
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
[Microsoft PowerPoint Web App](https://www.microsoft.com/download/details.aspx?familyid=9847dc05-7d4a-4a64-9e6a-622d3fa171f9)  
(KB2520047)  
(중요)
</td>
</tr>
</table>
 
MS11-022 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

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
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-025](http://go.microsoft.com/fwlink/?linkid=209720)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=e9501082-a651-452b-8c1a-43987ffd3102)  
(KB2465373)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ee64d83b-6c06-4ccf-b12d-99e2a7a7b18d)  
(KB2538218)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=e6a8e024-12ee-43d5-9aae-4c721505d6df)  
(KB2538241)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2010 및 Microsoft Visual Studio 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010](https://www.microsoft.com/download/details.aspx?familyid=7fd643a8-8e05-4d27-8853-33f79f01cb26)  
(KB2542054)  
(중요)  
[Microsoft Visual Studio 2010 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=1a21c9db-dfa3-4a07-a1e0-89a8069b7c17)  
(KB2565057)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2005 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2005 서비스 팩 1 재배포 가능 패키지](https://www.microsoft.com/download/details.aspx?familyid=ae2e1a40-7b45-4fe9-a20f-2ed2923aca62)  
(KB2538242)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual C++ 2008 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2008 서비스 팩 1 재배포 가능 패키지](https://www.microsoft.com/download/details.aspx?familyid=a821847e-4c44-45c0-9128-61c822bb3280)  
(KB2538243)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2010 및 Microsoft Visual C++ 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2010 재배포 가능 패키지](https://www.microsoft.com/download/details.aspx?familyid=fe558aed-9274-415f-8a0f-d9d8622fb35b)  
(KB2467173)  
(중요)  
[Microsoft Visual C++ 2010 재배포 가능 패키지 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=7557d29b-731b-4abb-8815-2b87a4132efb)  
(KB2565063)  
(중요)
</td>
</tr>
</table>
 

검색, 배포 도구 및 지침
-----------------------

보안 센터

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)을 참조하십시오.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

검색 및 배포 지침

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

Microsoft Baseline Security Analyzer

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

Windows Server Update Services

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services(영문)](http://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

System Center Configuration Manager 2007

Configuration Manager 2007 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. Configuration Manager 2007을 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

Configuration Manager 2007의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. Configuration Manager 2007의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. 관리자가 Configuration Manager 2007을 사용하여 업데이트를 배포하는 방법에 대한 자세한 내용은 [소프트웨어 업데이트 관리(영문)](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)를 참조하십시오. Configuration Manager에 대한 자세한 내용을 보려면 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)를 방문하십시오.

Systems Management Server 2003

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

참고 System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다(이전 섹션의 System Center Configuration Manager 2007 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)(영문)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator)(영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199)
-   : 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)
-   . Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너(영문)](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

업데이트 관리 전략

[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

기타 보안 관련 업데이트 받기

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS11-018에서 설명한 문제점을 [VeriSign iDefense Labs(영문)](http://labs.idefense.com/)와 협력하여 보고해 주신 익명 연구자
-   MS11-018에서 설명한 문제점을 해결하기 위해 협력해 주신 [MITRE(영문)](http://mitre.org/)
-   MS11-018에서 설명한 문제점을 해결하기 위해 협력해 주신 [Google Inc.](http://www.google.com/)의 Michal Zalewski
-   MS11-018에서 설명한 두 가지 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 David Bloom
-   MS11-018에서 설명한 문제점을 [TippingPoint(영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하며 보고해 주신 [Harmony Security(영문)](http://www.harmonysecurity.com/)의 Stephen Fewer
-   MS11-021에서 설명한 두 가지 문제점을 보고해 주신 [Secunia Research(영문)](http://secunia.com/)의 Alin Rad Pop
-   MS11-021에서 설명한 문제점을 보고해 주신 [Telus Security Labs(영문)](http://www.telussecuritylabs.com)의 Muhammad Junaid Bohio
-   MS11-021에서 설명한 세 가지 문제점을 [TippingPoint's(영문)](http://www.tippingpoint.com/) [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Aniway
-   MS11-021에서 설명한 문제점을 [VeriSign iDefense Labs(영문)](http://labs.idefense.com/)와 협력하여 보고해 주신 익명 연구자
-   ms11-021에서 설명한 문제점을 보고해 주신 VDT([Check Point Vulnerability Discovery Team](http://www.checkpoint.com/)) (영문)의 Rodrigo Rubira Branco
-   ms11-021에서 설명한 문제점을 [TippingPoint(영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   ms11-021에서 설명한 문제점을 [TippingPoint(영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS11-022에서 설명한 세 가지 문제점을 보고해 주신 [TippingPoint(영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)
-   MS11-023에서 설명한 문제점을 보고해 주신 [Fortinet's FortiGuard Labs(영문)](http://www.fortiguard.com/)의 Haifei Li
-   MS11-023에서 설명한 문제점을 [TippingPoint's](http://www.tippingpoint.com/)[Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS11-024에서 설명한 문제점을 해결하기 위해 협력해 주신 [Secunia(영문)](http://secunia.com/)의 Carsten Eiram
-   MS11-026에서 설명한 문제점을 해결하기 위해 협력해 주신 [Google Security Team(영문)](http://www.google.com/)
-   MS11-027에서 설명한 문제점을 보고해 주신 Carnegie Mellon University Information Security Office의 Chris Ries
-   MS11-027에서 설명한 문제점을 [iSIGHT Partners(영문)](http://www.isightpartners.com/) Global Vulnerability Partnership과 협력하여 보고해 주신 RadLSneak
-   MS11-029에서 설명한 문제점을 보고해 주신 [VUPEN Threat Protection Program(영문)](http://www.vupen.com/english/services/tpp-index.php)의 Nicolas Joly와 Chaouki Bekrar
-   MS11-030에서 설명한 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 Neel Mehta
-   MS11-031에서 설명한 문제점을 해결하기 위해 협력해 주신 [Mozilla(영문)](http://www.mozilla.org/)의 [Jesse Ruderman(영문)](http://www.squarefree.com/)
-   MS11-032에서 설명한 문제점을 보고해 주신 [Fontlab Ltd(영문).](http://www.fontlab.com/)의 Adam Twardoch
-   MS11-033에서 설명한 문제점을 보고해 주신 [Secunia(영문)](http://secunia.com/)의 Carsten Eiram
-   MS11-034에서 설명한 30개의 문제점을 보고해 주신 [Norman(영문)](http://www.norman.com/)의 Tarjei Mandt

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/korea) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2011년 4월 12일): 공지 요약이 게시되었습니다.
-   V1.1(2011년 4월 13일): MS11-019의 요약 표에 취약점에 대한 설명이 추가되었습니다.
-   V2.0(2011년 4월 15일): MS11-032에서 CVE-2011-0034에 대한 악용 가능성 인덱스 평가의 심각도가 "1 - 일관적인 악용 코드 가능"으로 상향되었습니다.
-   V3.0(2011년 4월 21일): MS11-025에 대한 다시 릴리스된 보안 업데이트를 제공하기 위해 공지가 개정되었습니다.
-   V3.1(2011년 4월 27일): MS11-024에서 CVE-2010-4701을 이 업데이트에서 해결하는 취약점으로 추가하기 위해 악용 가능성 인덱스가 수정되었습니다. 이 변경 사항은 정보에만 해당됩니다.
-   V4.0(2011년 5월 16일): 지원 대상인 Windows XP 및 Windows Server 2003 에디션의 Internet Explorer 7에 대한 업데이트를 다시 제공하기 위해 MS11-018 공지를 다시 릴리스하였습니다. 이 변경 사항은 검색에만 해당됩니다. 바이너리에 대한 변경 사항은 없습니다. 영향을 받는 고객에게만 업데이트가 제공됩니다. 이 업데이트를 수동으로 설치한 고객과 검색 로직 변경 대상이 아닌 구성을 실행하는 고객은 추가 조치가 필요하지 않습니다.
-   V5.0(2011년 6월 14일): MS11-025에서 Microsoft Visual Studio 2005 서비스 팩 1, Microsoft Visual Studio 2008 서비스 팩 1, Microsoft Visual Studio 2010, Microsoft Visual C++ 2005 서비스 팩 1 재배포 가능 패키지 및 Microsoft Visual C++ 2008 서비스 팩 1 재배포 가능 패키지에 대한 업데이트를 다시 제공했습니다. 이전에 이 업데이트를 설치한 고객은 영향을 받는 시스템에 새 패키지를 설치해야 합니다.
-   V6.0(2011년 8월 9일): MS11-025에서 Microsoft Visual Studio 2010 서비스 팩 1(KB2565057) 및 Microsoft Visual C++ 2010 재배포 가능 패키지 서비스 팩 1(KB2565063)이 영향을 받는 소프트웨어로 추가되었습니다.
-   V6.1(2011년 10월 27일): MS11-028에서 설명한 Windows Server 2008 R2(x64 기반 시스템용)의 .NET Framework 4에 대한 Server Core 설치 적용 가능성이 수정되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
