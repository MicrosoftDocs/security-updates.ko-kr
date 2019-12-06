---
TOCTitle: 'MS11-DEC'
Title: 2011 년 12 월 Microsoft 보안 공지 요약
ms:assetid: 'ms11-dec'
ms:contentKeyID: 61230734
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms11-dec(v=Security.10)'
---


2011 년 12 월 Microsoft 보안 공지 요약
======================================

게시된 날짜: 2011년 12월 13일 화요일 | 업데이트된 날짜: 2012년 2월 23일 목요일

**버전:** 2.1

이 공지 요약 목록에는 2011년 12월 발표된 보안 공지가 포함되어 있습니다.

2011년 12월 보안 공지 발표와 함께 이 공지 요약이 2011년 12월 28일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2011년 12월 14일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [12월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487961). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](https://go.microsoft.com/fwlink/?linkid=217214) 및 웹캐스트를 참조하십시오.

Microsoft는 2010년 12월 29일 오후 1:00(태평양 표준시, 미국 및 캐나다)에 부정기 보안 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [12월 29일 오후 1:00 보안 공지 웹캐스트에 지금 등록하십시오.](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032502798&culture=en-us) 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](https://go.microsoft.com/fwlink/?linkid=217214) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=233008">MS11-087</a></td>
<td style="border:1px solid black;">Windows 커널 모드 드라이버의 취약점으로 인한 원격 코드 실행 문제점(2639417) <br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점을 해결합니다. 이 취약점은 사용자가 특수하게 조작된 문서를 열거나 TrueType 글꼴 파일을 포함하는 악의적인 웹 페이지를 방문할 경우 원격 코드 실행을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232507">MS11-090</a></td>
<td style="border:1px solid black;">ActiveX 킬(Kill) 비트 누적 보안 업데이트(2618451) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft 소프트웨어의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 Internet Explorer에서 특정 바이너리 동작을 사용하는 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 또한 이 업데이트에는 4개의 타사 ActiveX 컨트롤에 대한 킬(Kill) 비트도 포함되어 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232517">MS11-092</a></td>
<td style="border:1px solid black;">Windows Media의 취약점으로 인한 원격 코드 실행 문제점(2648048) <br />
<br />
이 보안 업데이트는 Windows Media Player 및 Windows Media Center에서 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 Microsoft Digital Video Recording(.dvr-ms) 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 공격에 성공하려면 사용자가 파일을 열도록 유도해야 하는데 이 보안 업데이트를 설치하면 모든 경우에 사용자가 파일을 열 수 없게 됩니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=227070">MS11-088</a></td>
<td style="border:1px solid black;">Microsoft Office IME(중국어)의 취약점으로 인한 권한 상승 문제점 (2652016) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office IME(중국어)의 취약점을 해결합니다. 이 취약점은 영향을 받는 중국어 간체용 MSPY(Microsoft Pinyin) IME가 설치된 시스템에서 로그온한 사용자가 특정 동작을 수행할 경우에 권한이 상승되도록 할 수 있습니다. 이 취약점 악용에 성공한 공격자는 커널 모드에서 임의 코드를 실행할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 전체 관리자 권한이 있는 새 계정을 만들 수도 있습니다. Microsoft Pinyin IME 2010 구현만 이 취약점의 영향을 받습니다. 다른 버전의 중국어 간체 IME 및 기타 IME 구현은 영향을 받지 않습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225739">MS11-089</a></td>
<td style="border:1px solid black;">Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점 (2590602) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 Word 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td style="border:1px solid black;">Microsoft Publisher의 취약점으로 인한 원격 코드 실행 문제점 (2607702) <br />
<br />
이 보안 업데이트는 Microsoft Office의 공개된 취약점 1건과 비공개로 보고된 취약점 3건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 특수하게 조작된 Publisher 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약점을 성공적으로 악용한 경우 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232516">MS11-093</a></td>
<td style="border:1px solid black;">OLE의 취약점으로 인한 원격 코드 실행 문제점(2624667) <br />
<br />
이 보안 업데이트는 지원 대상인 모든 Windows XP 및 Windows Server 2003 에디션에서 비공개적으로 보고된 취약점을 해결합니다. 이 보안 업데이트의 심각도는 지원 대상인 모든 Windows XP 및 Windows Server 2003 에디션에 대해 중요입니다. Windows Vista, Windows Server 2008, Windows 7 및 Windows Server 2008 R2는 취약점의 영향을 받지 않습니다.<br />
<br />
이 취약점으로 인해 사용자가 특수하게 조작된 OLE 개체를 포함하는 파일을 열 경우 원격 코드가 실행될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td style="border:1px solid black;">Microsoft PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(2639142) <br />
<br />
이 보안 업데이트는 Microsoft Office에서발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 PowerPoint 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 이러한 취약점 두 가지 중 하나를 성공적으로 악용한 경우 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232666">MS11-095</a></td>
<td style="border:1px solid black;">Windows Active Directory의 취약점으로 인한 원격 코드 실행 문제점(2640045) <br />
<br />
이 보안 업데이트는 Active Directory, ADAM(Active Directory Application Mode) 및 AD LDS(Active Directory Lightweight Directory Service)에서 발견되어 비공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점은 공격자가 Active Directory 도메인에 로그온하여 특수하게 조작된 응용 프로그램을 실행할 경우 원격 코드가 실행되도록 할 수 있습니다. 이 취약점을 악용하려면 공격자는 먼저 Active Directory 도메인에 로그온하기 위한 자격 증명을 획득해야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232696">MS11-096</a></td>
<td style="border:1px solid black;">Microsoft Excel의 취약점으로 인한 원격 코드 실행 문제점(2640241) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 Excel 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 의심되는 파일을 열지 못하도록 Office 파일 유효성 검사(OFV)를 설치하고 구성하면 CVE-2011-3403에 설명된 취약점을 악용하는 공격 경로가 차단됩니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232663">MS11-097</a></td>
<td style="border:1px solid black;">Windows CSRSS(Client/Server Runtime Subsystem)의 취약점으로 인한 권한 상승 문제점 (2620712) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 공격자가 영향을 받는 시스템에 로그온하여 무결성이 높은 프로세스에 장치 이벤트 메시지를 보내도록 특수하게 조작된 응용 프로그램을 실행할 경우 이 취약점을 인해 권한 상승이 발생할 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232424">MS11-098</a></td>
<td style="border:1px solid black;">Windows 커널의 취약점으로 인한 권한 상승 문제점(2633171) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 영향을 받는 시스템에 로그온한 후 이 취약점을 악용하도록 디자인된 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2618444) <br />
<br />
이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 3건을 해결합니다. 가장 심각한 취약점은 사용자가 특수하게 조작된 DLL(동적 연결 라이브러리) 파일과 동일한 디렉터리에 있는 합법적인 HTML(HyperText Markup Language) 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td style="border:1px solid black;">.NET Framework의취약점으로 인한 권한 상승 문제점 (2638420) <br />
<br />
이 보안 업데이트는 Microsoft .NET Framework의 공개된 취약점 1건과 비공개로 보고된 취약점 3건을 해결합니다. 이 중 가장 심각한 취약점이 악용될 경우 인증되지 않은 공격자가 특수하게 조작된 웹 요청을 대상 사이트에 전송하여 권한 상승을 발생시킬 수 있습니다. 이 취약점 악용에 성공한 공격자는 ASP.NET 사이트의 기존 계정 컨텍스트에서 임의 명령 실행을 포함한 모든 작업을 수행할 수 있습니다. 이 취약점을 악용하려면 공격자가 ASP.NET 사이트에 계정을 등록할 수 있어야 하고, 기존 사용자 이름을 알고 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](https://technet.microsoft.com/security/cc998259.aspx)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.
  
| 공지 번호                                                 | 취약점 제목                                            | CVE ID                                                                                 | 최신 소프트웨어 버전에 대한 악용 가능성 평가                                           | 이전 소프트웨어 버전에 대한 악용 가능성 평가                                           | 서비스 거부 악용 가능성 평가 | 주요 정보                                                                                                                                                                          |  
|-----------------------------------------------------------|--------------------------------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS11-087](https://go.microsoft.com/fwlink/?linkid=233008) | TrueType 글꼴 구문 분석 취약점                         | [CVE-2011-3402(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 영구                         | 이 취약점은 공개되었습니다.                                                                                                                                                        |  
| [MS11-088](https://go.microsoft.com/fwlink/?linkid=227070) | Pinyin IME 권한 상승 취약점                            | [CVE-2011-2010(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2010) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 영향 받지 않음                                                                         | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-089](https://go.microsoft.com/fwlink/?linkid=225739) | Word 해제 후 사용 취약점                               | [CVE-2011-1983(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1983) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-090](https://go.microsoft.com/fwlink/?linkid=232507) | Microsoft Time 원격 코드 실행 취약점                   | [CVE-2011-3397(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3397) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-091](https://go.microsoft.com/fwlink/?linkid=235287) | Publisher 범위 초과 배열 인덱스 취약점                 | [CVE-2011-3410(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3410) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-091](https://go.microsoft.com/fwlink/?linkid=235287) | Publisher 잘못된 포인터 취약점                         | [CVE-2011-3411(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3411) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-091](https://go.microsoft.com/fwlink/?linkid=235287) | Publisher 메모리 손상 취약점                           | [CVE-2011-3412(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3412) | 영향 받지 않음                                                                         | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 구축 어려움 | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-092](https://go.microsoft.com/fwlink/?linkid=232517) | Windows Media Player DVR-MS 메모리 손상 취약점         | [CVE-2011-3401(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3401) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-093](https://go.microsoft.com/fwlink/?linkid=232516) | OLE 속성 취약점                                        | [CVE-2011-3400(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3400) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-094](https://go.microsoft.com/fwlink/?linkid=232493) | PowerPoint의 안전하지 않은 라이브러리 로드 취약점      | [CVE-2011-3396(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3396) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | Microsoft PowerPoint 2010은 최신 서비스 팩이 설치되지 않은 경우에만 영향을 받습니다.                                                                                               |  
| [MS11-094](https://go.microsoft.com/fwlink/?linkid=232493) | OfficeArt 도형 RCE 취약점                              | [CVE-2011-3413(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3413) | 영향 받지 않음                                                                         | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 구축 어려움 | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-095](https://go.microsoft.com/fwlink/?linkid=232666) | Active Directory 버퍼 오버플로 취약점                  | [CVE-2011-3406(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3406) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 영구                         | 시스템이 Active Directory, AD LDS, 또는 ADAM을 실행하는 경우에만 영향을 받습니다.                                                                                                  |  
| [MS11-096](https://go.microsoft.com/fwlink/?linkid=232696) | 레코드 메모리 손상 취약점                              | [CVE-2011-3403(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3403) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-097](https://go.microsoft.com/fwlink/?linkid=232663) | CSRSS 로컬 권한 상승 취약점                            | [CVE-2011-3408(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3408) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-098](https://go.microsoft.com/fwlink/?linkid=232424) | Windows 커널 예외 처리기 취약점                        | [CVE-2011-2018(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2018) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 영구                         | (없음)                                                                                                                                                                             |  
| [MS11-099](https://go.microsoft.com/fwlink/?linkid=232505) | XSS 필터 정보 유출 취약점                              | [CVE-2011-1992(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1992) | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 불가능      | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 불가능      | 해당 사항 없음               | 이는 정보 유출 취약점입니다.                                                                                                                                                       |  
| [MS11-099](https://go.microsoft.com/fwlink/?linkid=232505) | Internet Explorer 안전하지 않은 라이브러리 로드 취약점 | [CVE-2011-2019(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2019) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 영향 받지 않음                                                                         | 해당 사항 없음               | (없음)                                                                                                                                                                             |  
| [MS11-100](https://go.microsoft.com/fwlink/?linkid=232432) | 해시 테이블 충돌로 발생하는 Dos 취약점                 | [CVE-2011-3414(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3414) | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 불가능      | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 불가능      | 임시                         | 이 취약점은 서비스 거부에만 해당되며, 일반에 공개되었습니다.[서비스 거부 취약점은 악용 가능성 인덱스 평점이 "3"입니다.](https://technet.microsoft.com/en-us/security/cc998259.aspx) |  
| [MS11-100](https://go.microsoft.com/fwlink/?linkid=232432) | ASP.Net 폼 인증 우회 취약점                            | [CVE-2011-3416(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3416) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | 권한 상승 - 계정 탈취                                                                                                                                                              |  
| [MS11-100](https://go.microsoft.com/fwlink/?linkid=232432) | ASP.NET 폼 인증 티켓 캐싱 취약점                       | [CVE-2011-3417(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3417) | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 구축 어려움 | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 구축 어려움 | 해당 사항 없음               | 권한 상승 - 계정 탈취                                                                                                                                                              |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
참고 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소
  
표 1

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-087](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](https://go.microsoft.com/fwlink/?linkid=232663)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=b01bb041-005c-48c4-a606-66aa264ba0fa)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=21b4b999-2dbf-4921-80bd-cc7ab2cd1190)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=d85091b5-69bb-4d0f-839a-a65cd94e2887)  
(KB2619339)  
(긴급)  
[Windows XP Media Center Edition 2005 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=03bc6446-7cf3-47c4-8ed1-a53a4d53a429)  
(KB2619340)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=73531165-f299-4b62-b738-52fca410eaae)  
(중요)
</td>
<td style="border:1px solid black;">
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=3b816964-d3c3-4f05-94c3-f54a6f54ca73)  
(KB2626416)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=edb594a4-14d2-4ffe-8d1c-2c283689fe8c)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0a872cd2-5f4d-400c-a1c4-a2d194746fb6)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=126e8092-980d-471a-867d-d5939671b7df)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7d1d1e9a-603c-4895-a69f-b61186a75ad5)  
(KB2619339)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a98bb7cf-9939-4927-8d21-ccb3845e7cb7)  
(중요)
</td>
<td style="border:1px solid black;">
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=986f0087-c674-4060-8710-af3496adbfdd)  
(KB2626416)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9e1273e2-7775-40b4-b939-ab530677cd4a)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-087](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](https://go.microsoft.com/fwlink/?linkid=232663)
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
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e84e6964-1580-41ef-9d3e-4d0c3ad4cb69)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dfb948c5-8aee-4bcd-babf-3564b78712dd)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6b555040-1117-4b06-a48c-02f0e1b686d8)  
(중요)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=01caf06f-777d-4ea8-95ca-e11d60a973ad)  
(KB2621146)  
(중요)  
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=6f7c7ccd-22a3-4fbc-bf21-bd0e42ab1da5)  
(KB2626416)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a14057e5-e2c2-4dde-8d26-542a9f162e98)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9d9f3667-3fd6-4948-83db-282783599f41)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2d37a8cb-2316-4db4-980c-11b6dcbdc696)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eb17782c-f754-42ab-905b-6f141df008c3)  
(중요)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=e1ba50cf-fc6b-4668-b71c-e9f75a8ac638)  
(KB2621146)  
(중요)  
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=1b610eb3-456c-4125-94b7-1ead4face8e3)  
(KB2626416)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7f595fd6-bdfd-4075-97e5-70efb7d49dff)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=1ecf72cd-6732-4cf3-aa22-8caf15ea633e)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=7726ddbe-0578-44fb-a40f-49b804a45989)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=4cdde8a9-6d44-41fa-82c0-a25404cdfbb5)  
(중요)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=74099261-60ad-4c68-906c-60e131818955)  
(KB2621146)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=147ec6d3-3401-4aa3-a409-55346bcc7bd7)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-087](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](https://go.microsoft.com/fwlink/?linkid=232663)
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
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7f69ec9d-43ad-4106-90ef-c191e7ec43af)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1dd069a2-fb1a-4f31-88cc-bc031c3e2c80)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e9130fad-de8c-4be0-aea1-62cbaa310b76)  
(KB2619339)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AD LDS(Active Directory Lightweight Directory Service)](https://www.microsoft.com/download/details.aspx?familyid=470da512-2c8b-4ba9-b7bb-b9e6c45cd33f)  
(KB2621146)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=fa6e6d91-4aca-49a6-a6e8-c33ec413097e)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ae1f1f86-6f13-4e1e-9f93-4f70b6c9927e)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=60fd5bf6-e820-44f6-8081-b98c0103acc1)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b7c4bf05-eb2d-48ac-a6df-8afd88e811d8)  
(KB2619339)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AD LDS(Active Directory Lightweight Directory Service)](https://www.microsoft.com/download/details.aspx?familyid=8daf9a49-60cb-4813-ac7a-e9a4bf296889)  
(KB2621146)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c9794756-803d-48ba-86db-350fb577f01b)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-087](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](https://go.microsoft.com/fwlink/?linkid=232663)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c4ba344d-dd0d-4cfb-81d9-d364d7f37e25)\*\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f485d4c3-a4af-4ae6-9404-e79afcbb4f6e)\*\*  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Active Directory 및 Active Directory Lightweight Directory Service(AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=6f9ddcdb-a471-4e00-a697-92a24e4ea8d4)\*  
(KB2621146)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6f934885-b134-400c-a452-50fd4eeedd5e)\*  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=058963f6-9654-41d0-86d2-f25a0c2ad416)\*\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=28598ef6-13fb-44fd-8c76-599af7b0a01d)\*\*  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Active Directory 및 Active Directory Lightweight Directory Service(AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=5253477b-422f-404a-941e-8b69da5a2670)\*  
(KB2621146)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7ade3832-bc20-4fce-8eac-8a3d072d2f1c)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=42cd1c33-11a7-4a29-ae85-f7272a626f91)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5915e19c-b576-453b-b621-5737774f5955)  
(심각도 없음<sup>[1]</sup>)
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
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4bd7a02b-c6d8-4eb5-a46d-e494a1233dc8)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-087](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](https://go.microsoft.com/fwlink/?linkid=232663)
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
Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=0526727a-f2fb-4846-9b04-f1899f52f1f6)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=d112623c-86ce-434a-8fe1-ec3e3e632763)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b6e44069-dec5-48f6-8fc4-8ab375a10b4e)  
(KB2619339)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AD LDS(Active Directory Lightweight Directory Service)](https://www.microsoft.com/download/details.aspx?familyid=d2e87199-6469-4bc0-a721-f43e817e4344)  
(KB2621146)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=0666bdf5-9eed-44c9-84ee-b45f9b3e14b3)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=cfd42c42-1595-419a-bf04-b23b64663629)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=81114ecd-0c73-4ca6-8a66-09c6c636a5db)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=f7997ab8-27e0-4714-845a-d237f4326587)  
(KB2619339)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AD LDS(Active Directory Lightweight Directory Service)](https://www.microsoft.com/download/details.aspx?familyid=ba8d7aa9-8299-49a3-b0c0-b8b5eab48434)  
(KB2621146)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=620f94f9-1f61-45a0-a22e-e7510b56b9b8)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-087](https://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](https://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](https://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](https://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](https://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](https://go.microsoft.com/fwlink/?linkid=232663)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=d64a31ca-cccd-488a-98fd-c059b9e9e1ea)\*\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=bc018647-08cb-431a-8e7c-5dc04980eaa9)\*\*  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Active Directory 및 Active Directory Lightweight Directory Service(AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=a3e0d27c-8b29-4981-bdef-bcd037fd3408)\*  
(KB2621146)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=04878e9a-539a-4549-a5af-11d45add91da)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=b46f6da7-6d24-4262-8e55-3b657db39813)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=9323b9b9-e9b0-4941-afe0-196d22df9ab4)  
(심각도 없음<sup>[1]</sup>)
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
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5b2ebec4-cebb-47b6-864a-12d59a9a3e18)  
(중요)
</td>
</tr>
</table>
 
Windows Server 2008 및 Windows Server 2008 R2 참고 사항

\*Server Core 설치가 영향을 받습니다. 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](https://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](https://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](https://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

\*\*Server Core 설치는 영향을 받지 않습니다. Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](https://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](https://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](https://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

\*\*\*\*Server Core 설치가 영향을 받습니다. 이 업데이트는 Server Core 설치 옵션을 사용하여 설치할 때 더 낮은 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](https://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](https://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](https://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

MS11-090 참고 사항

<sup>[1]</sup>이 운영 체제는 이 공지에서 설명하는 취약점의 영향을 받지 않습니다. 사용 가능한 업데이트는 타사 컨트롤에 대한 킬(kill) 비트를 설정합니다.

표 2

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="4">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-098](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](https://go.microsoft.com/fwlink/?linkid=232432)
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
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=7a6fcf8d-8c7b-4882-90d3-02db79a75238)  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=caa9360b-2fd8-4f46-99e6-2decf1b60ca7)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=dc6dcd8c-c39f-4c4b-b5b2-b4c18c36973b)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=f3906245-b6f6-464a-84b6-e1b6b195df95)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=2fa77733-70f5-46ff-9cfe-2262d292b870)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a0c55d9b-8529-4d3d-910d-1a822a825be2)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3e60e996-8850-4d25-b994-39646e2cc25e)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-098](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](https://go.microsoft.com/fwlink/?linkid=232432)
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
[낮음](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=281e5bd4-4582-4aa9-af88-518ad3152132)  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=759041cf-fd8b-4e04-b289-d74112bf978b)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b1b4af92-3ff1-4727-9ba3-52764a7b81bb)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=1cbe9469-05f4-4305-bbfd-76b4a04cd598)  
(낮음)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=7538762a-50e9-4f13-a60e-ff99aa8fbbf8)  
(KB2656358)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=5587eca8-86e9-4a63-81cb-81f68178a6c0)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7a87f890-f106-41ab-bc53-4ca44dc99cb1)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a42fa727-482c-4578-9a30-61fdf14ed4da)  
(낮음)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=02d5c057-d551-411b-917b-43d7795111bc)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2fccb214-6c79-4ef6-9d6e-df4f16ef792e)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-098](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](https://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr>
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
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a6c7c960-768d-40d4-8fe5-7d59f48ead1d)  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0adc422f-73f2-46ee-973f-9b7603a76d1e)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4327147b-0481-4172-a835-8786abc50596)  
(중요)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=a0b19b35-1d48-4419-ba3d-66063cc472a7)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=8a3f2351-380b-4566-b186-906dca426d39)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=987f0966-01de-4edf-a0d6-4032d1d72966)  
(중요)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c951044b-4596-462f-bc8f-bdd9d6734297)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-098](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](https://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[낮음](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5a4443f8-fec8-42be-ad67-8475920f1460)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=eaf587f0-9951-4480-a08b-377e61aaf72b)\*\*  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=8f5af52f-dece-4f0c-9fc0-d4973e4f7b1a)\*\*  
(낮음)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c03e65d6-4f92-4bc1-94b5-2f0183d0133e)\*\*  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)\*\*  
(KB2656353)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)\*\*  
(KB2656362)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)\*\*  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*\*<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2f18fc98-984a-4c02-951f-b8438a9e4f6b)\*\*  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=808d26f7-c8fa-446d-9d2f-e8c0babb0c4a)\*\*  
(낮음)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b7a582f3-0a18-4fbf-9b99-21c664bfd979)\*\*  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)\*\*  
(KB2656353)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)\*\*  
(KB2656362)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)\*\*  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*\*<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=fc62df39-7185-448b-b356-25a5a07886ec)  
(심각도 없음<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-098](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](https://go.microsoft.com/fwlink/?linkid=232432)
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
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=eb2bd108-5ef1-45be-9157-e7cbfc8afd2a)  
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=018610bb-e80a-432a-8f32-f50451f71ad9)  
(중요)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=ec2046a6-f069-4f02-9600-7640e57be0a3)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Windows 7(32비트 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=dbe85b05-e252-4029-8e25-f2452db1c017)  
(중요)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=4c773b3d-0ca3-4b9b-af9a-9d6edcd261f7)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Windows 7(x64 기반 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-098](https://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](https://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](https://go.microsoft.com/fwlink/?linkid=232432)
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
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2108b4ef-942f-4727-a1fc-ee7d0abb427c)\*\*  
(낮음)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=72c1654e-526f-4ece-b7ad-767a0710e076)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)\*  
(KB2656355)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)\*  
(KB2656356)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=74614510-e13c-43e8-90e7-d81e63895cf2)  
(낮음)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
</table>
 
Windows Server 2008 및 Windows Server 2008 R2 참고 사항

\*Server Core 설치가 영향을 받습니다. 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](https://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](https://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](https://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

\*\*Server Core 설치는 영향을 받지 않습니다. Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](https://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](https://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](https://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

MS11-099 참고 사항

<sup>[1]</sup>이 공지에서 설명한 취약점에 대해 알려진 공격 경로가 기본 구성으로 차단되므로 지정된 소프트웨어에 대한 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 심층적인 보안 대응책으로써 이 소프트웨어를 사용하는 고객은 이 보안 업데이트를 적용하는 것이 좋습니다.

MS11-100 참고 사항

<sup>[1]</sup>.NET Framework 4 and .NET Framework 4 Client Profile이 영향을 받습니다. .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4 및 .NET Framework 4 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4 Client Profile은 .NET Framework 4의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4 및 .NET Framework 4 Client Profile에 모두 영향을 줍니다. 자세한 내용은 MSDN 문서, [.NET Framework 설치](https://msdn.microsoft.com/ko-kr/library/5a4x27ek.aspx)를 참조하십시오.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="6">
Microsoft Office 제품군 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-088](https://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[MS11-089](https://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[MS11-091](https://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[MS11-094](https://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[MS11-096](https://go.microsoft.com/fwlink/?linkid=232696)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=13f3e884-37bf-4ed2-b3ed-a0e7fb48e44f)  
(KB2553084)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=5859014f-afc5-4958-82ea-6ba45a5ad4b3)  
(KB2596954)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 2 및 Microsoft Office 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 서비스 팩 2 및 Microsoft Office 2007 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=e924cd85-5764-4056-bd32-b0e57dc25146)  
(KB2596785)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2007 서비스 팩 2 및 Microsoft Publisher 2007 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=2856821e-f1fd-424b-b03c-e443685eea6d)  
(KB2596705)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d0c3156c-c87c-4d3e-aca2-3fab9ff78711)  
(KB2596764)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 및 Microsoft Office 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Pinyin IME 2010(32비트 버전)](https://www.microsoft.com/download/details.aspx?familyid=d812621e-c35a-4cb0-ba26-928363f3422d)  
(KB2596511)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 및 Microsoft Office 2010 서비스 팩 1(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=e47c0694-a9a5-4dd7-bfba-e470d9855c28)  
(KB2589320)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=fd32d083-46e7-4835-ba83-c33332b920bd)  
(KB2553185)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 및 Microsoft Office 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Pinyin IME 2010(64비트 버전)](https://www.microsoft.com/download/details.aspx?familyid=c8d3ac17-5aca-4da3-961f-b753be4a3634)  
(KB2596511)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 및 Microsoft Office 2010 서비스 팩 1(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=6c2d5273-eef9-4ff6-be6f-8d86f417f004)  
(KB2589320)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=f28b8cf6-8946-448a-ae4e-d11f8a76a679)  
(KB2553185)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-088](https://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[MS11-089](https://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[MS11-091](https://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[MS11-094](https://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[MS11-096](https://go.microsoft.com/fwlink/?linkid=232696)
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
Microsoft Office 2004 for Mac
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
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ef3b559c-0bd2-45dd-8049-6946f6431a2a)  
(KB2644358)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
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
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=2c4d0381-f7ab-49ed-a0c0-b381387d1e68)  
(KB2644354)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=3c8017d6-232c-42a6-a133-96efe3ad3385)  
(KB2644347)  
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
<th style="border:1px solid black;" colspan="6">
기타 Microsoft Office 소프트웨어
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS11-088](https://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[MS11-089](https://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[MS11-091](https://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[MS11-094](https://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[MS11-096](https://go.microsoft.com/fwlink/?linkid=232696)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
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
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint Viewer 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4417592a-8db0-4e35-9895-d589bc341077)  
(KB2596912)  
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=e799f654-7e2d-40c7-a3b8-32e44d1aa6ee)  
(KB2596843)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 및 Microsoft Office Pinyin New Experience Style 2010(32비트 버전)
</td>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 및 Microsoft Office Pinyin New Experience Style 2010(32비트 버전)<sup>[1]</sup>
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 및 Microsoft Office Pinyin New Experience Style 2010(64비트 버전)
</td>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 및 Microsoft Office Pinyin New Experience Style 2010(64비트 버전)<sup>[1]</sup>
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
</tr>
</table>
 
MS11-088 참고 사항

<sup>[1]</sup>이 버전의 Microsoft Office Pinyin은 더 이상 지원되지 않습니다.

검색, 배포 도구 및 지침
-----------------------

보안 센터

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](https://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](https://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](https://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)을 참조하십시오.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](https://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](https://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

검색 및 배포 지침

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](https://support.microsoft.com/kb/961747)을 참조하십시오.

Microsoft Baseline Security Analyzer

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

Windows Server Update Services

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services(영문)](https://technet.microsoft.com/ko-kr/wsus/default.aspx)를 참조하십시오.

System Center Configuration Manager 2007

Configuration Manager 2007 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. Configuration Manager 2007을 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

Configuration Manager 2007의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. Configuration Manager 2007의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. 관리자가 Configuration Manager 2007을 사용하여 업데이트를 배포하는 방법에 대한 자세한 내용은 [소프트웨어 업데이트 관리](https://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)를 참조하십시오. Configuration Manager에 대한 자세한 내용을 보려면 [System Center Configuration Manager(영문)](https://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)를 방문하십시오.

Systems Management Server 2003

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

참고 System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](https://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다(이전 섹션의 System Center Configuration Manager 2007 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](https://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=ko)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](https://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit) (영문)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199) : 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)
-   . Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너(영문)](https://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

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

-   MS11-087에서 설명한 문제점을 해결하기 위해 협력해 주신 Symantec 및 Laboratory of Cryptography and System Security(CrySyS)
-   MS11-088에서 설명한 문제점을 보고해 주신 Yang Yanbei
-   MS11-089에서 설명한 문제점을 [TippingPoint's](https://www.tippingpoint.com/) [Zero Day Initiative(영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Nikita Tarakanov(CISS Research Team) 및 Alexey Sintsov(Digital Security Research Group)
-   MS11-090에서 설명한 문제점을 [VeriSign iDefense Labs(영문)](https://labs.idefense.com)와 협력하여 보고해 주신 익명 연구자
-   MS11-091에서 설명한 문제점을 보고해 주신 [CERT/CC(영문)](https://www.cert.org/)의 Will Dormann
-   MS11-092에서 설명한 문제점을 [VeriSign iDefense Labs(영문)](https://labs.idefense.com)와 협력하여 보고해 주신 익명 연구자
-   MS11-093에서 설명한 문제점을 [VeriSign iDefense Labs(영문)](https://labs.idefense.com)와 협력하여 보고해 주신 익명 연구자
-   MS11-094에서 설명한 문제점을 보고해 주신 [iSIGHT Partners Labs(영문)](https://www.isightpartners.com/)의 Greg MacManus
-   MS11-094에서 설명한 문제점을 [TippingPoint's](https://www.tippingpoint.com/)[Zero Day Initiative(영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS11-096에서 설명한 문제점을 [VeriSign iDefense Labs(영문)](https://labs.idefense.com)와 협력하여 보고해 주신 익명 연구자
-   MS11-097에서 설명한 문제점을 보고해 주신 Winsider Seminars & Solutions Inc.의 Alex Ionescu
-   MS11-098에서 설명한 문제점을 [VeriSign iDefense Labs(영문)](https://labs.idefense.com/)와 협력하여 보고해 주신 Matthew Jurczyk
-   MS11-099에서 설명한 문제점을 보고해 주신 Thomas Stehle
-   MS11-099에서 설명한 문제점을 [Citrix Security Team(영문)](https://www.citrix.com)과 협력하여 보고하여 주신 Andy Cooper
-   MS11-099에서 설명한 문제점을 보고해주신 [Google Inc.](https://www.google.com/)의 [Robert Swiecki(영문)](https://www.swiecki.net/)
-   MS11-099에서 설명한 문제점을 해결하기 위해 협력해 주신 [Yosuke Hasegawa(영문)](https://utf-8.jp/)
-   MS11-099에 포함된 심층 보안 변경 사항에 대해 협력해 주신 [Jan Schejbal(영문)](https://janschejbal.wordpress.com/)
-   MS11-100에서 설명한 문제점을 보고해 주신 [Seeker(영문)](https://www.seekersec.com)의 Irene Abezgauz
-   MS11-100에서 설명된 문제점을 보고해 주신 [SEC Consult(영문)](https://www.sec-consult.com/)의 Kestutis Gudinavicius.
-   MS11-100에서 설명한 문제점을 보고해 주신 [LBi(영문)](https://www.lbi.com/)의 Oliver Dewdney

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](https://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](https://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](https://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2011년 12월 13일): 공지 요약이 게시되었습니다.
-   V1.1(2011년 12월 13일): MS11-099에서 영향을 받는 소프트웨어 표의 심각도 등급이 수정되었습니다. MS11-088에서 악용 가능성 인덱스의 주요 정보가 수정되었습니다. 이 변경 사항은 정보에만 해당됩니다. 보안 업데이트 파일이나 검색 로직에 대한 변경 사항은 없습니다.
-   V2.0(2011년 12월 29일): Microsoft 보안 공지 MS11-100, .NET Framework의 취약점으로 인한 권한 상승 문제점(2638420)이 추가되었습니다. 또한 이 부정기 보안 업데이트에 대한 공지 웹캐스트 링크가 추가되었습니다.
-   V2.1(2012년 2월 23일): MS11-088에서 Microsoft Office Pinyin SimpleFast Style 2010 및 Microsoft Office Pinyin New Experience Style 2010에 대해 제품 지원 상태가 추가되었습니다. Microsoft Office Pinyin의 해당 버전은 더 이상 지원되지 않습니다. 자세한 내용은 보안 공지를 참조하십시오.

*Built at 2014-04-18T12:27:44Z-07:00*
