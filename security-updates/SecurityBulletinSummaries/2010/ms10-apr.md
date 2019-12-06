---
TOCTitle: 'MS10-APR'
Title: 2010 년 4 월 Microsoft 보안 공지 요약
ms:assetid: 'ms10-apr'
ms:contentKeyID: 61230720
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms10-apr(v=Security.10)'
---


2010 년 4 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2010년 4월 14일 수요일 | 업데이트된 날짜: 2010년 7월 14일 수요일

**버전:** 4.0

이 공지 요약 목록에는 2010년 4월 발표된 보안 공지가 포함되어 있습니다.

2010년 4월 공지 발표와 함께 이 공지 요약이 2010년 4월 8일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2010년 4월 14일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [4월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427721&eventcategory=4&culture=en-us&countrycode=us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](https://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-019">MS10-019</a></td>
<td style="border:1px solid black;"><strong>Windows의 취약점으로 인한 원격 코드 실행 문제점 (981210)</strong><br />
<br />
이 보안 업데이트는 Windows Authenticode Verification의 비공개적으로 보고된 취약점, 즉 원격 코드 실행을 허용할 수 있다는 문제점을 해결합니다. 이 취약점 악용에 성공한 공격자는 영향을 받는 시스템을 완벽히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;"><strong>SMB 클라이언트의 취약점으로 인한 원격 코드 실행 문제점 (980232)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점 1건과 비공개적으로 보고된 여러 취약점을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 SMB 응답을 클라이언트가 시작한 SMB 요청에 보낼 경우 원격 코드 실행이 발생할 수 있습니다. 이 취약점을 악용하려면 공격자는 사용자가 특수하게 조작된 SMB 서버에 SMB 연결을 시작하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-025">MS10-025</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows Media Services의 취약점으로 인한 원격 코드 실행 문제점 (980858)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows 2000 Server에서 실행되는 Windows Media Services의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 전송 정보 패킷을 Windows Media Services를 실행하는 Microsoft Windows 2000 Server 시스템에 보내는 경우 원격 코드 실행이 발생할 수 있습니다. 최선의 방화벽 구성 방법과 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 들어오는 공격으로부터 네트워크를 보호할 수 있습니다. 인터넷과 연결되는 시스템의 경우, 필요한 포트만 최소한으로 열어 두는 것이 안전합니다. Microsoft Windows 2000 Server에서 Windows Media Services는 선택적 구성 요소이며 기본적으로 설치되지 않습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-026">MS10-026</a></td>
<td style="border:1px solid black;"><strong>Microsoft MPEG Layer-3 코덱의 취약점으로 인한 원격 코드 실행 문제점 (977816)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft MPEG Layer-3 오디오 코덱의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 Microsoft MPEG Layer-3 오디오 스트림을 포함하고 있는 특수하게 조작된 AVI 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 사용자가 관리자 권한으로 로그온한 경우, 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-027">MS10-027</a></td>
<td style="border:1px solid black;"><strong>Windows Media Player의 취약점으로 인한 원격 코드 실행 문제점 (979402)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows Media Player의 취약점을 해결합니다. 이 취약점으로 인해 Windows Media Player에서 악의적인 웹 사이트에서 호스팅하는 특수하게 조작된 미디어 콘텐츠를 열 경우 원격 코드 실행이 발생할 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-021">MS10-021</a></td>
<td style="border:1px solid black;"><strong>Windows 커널의 취약점으로 인한 권한 상승 문제점 (979683)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 이 중 가장 위험한 취약점으로 인해 공격자가 시스템에 로컬로 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승을 허용할 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-022">MS10-022</a></td>
<td style="border:1px solid black;"><strong>VBScript의 취약점으로 인한 원격 코드 실행 취약점 (981169)</strong><br />
<br />
이 보안 업데이트는 공개적으로 보고되었으며 Microsoft Windows에서 원격 코드 실행을 허용할 수 있는 VBScript의 취약점을 해결합니다. 이 보안 업데이트의 심각도는 Microsoft Windows 2000, Windows XP 및 Windows Server 2003에 대해 중요입니다. Windows Server 2008, Windows Vista, Windows 7 및 Windows Server 2008 R2에서는 취약한 코드를 악용할 수 없지만 취약한 코드 자체가 존재하기 때문에 이 업데이트가 심층 보안 대응책으로 제공되고 심각도가 적용되지 않습니다.<br />
<br />
이러한 취약점으로 인해 악의적인 웹 사이트에서 특수하게 조작된 대화 상자를 웹 페이지에 표시하고 사용자가 F1 키를 누른 경우 Windows 도움말 시스템이 공격자가 제공한 Windows 도움말 파일로 시작될 수 있습니다. 사용자가 관리자 권한으로 로그온한 경우, 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-023">MS10-023</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Publisher의 취약점으로 인한 원격 코드 실행 문제점 (981160)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 취약점 1건을 해결합니다. 사용자가 특수하게 조작된 Publisher 파일을 열면 이 Microsoft Office Publisher 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-024">MS10-024</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange 및 Windows SMTP 서비스의 취약점으로 인한 서비스 거부 문제점 (981832)</strong><br />
<br />
이 보안 업데이트는 Microsoft Exchange 및 Windows SMTP 서비스의 공개된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 이 중 가장 위험한 취약점으로 인해 공격자가 SMTP 서비스를 실행하는 컴퓨터로 특수하게 조작된 DNS 응답을 전송할 경우 서비스 거부를 허용할 수 있습니다. SMTP 구성 요소는 기본적으로 Windows Server 2003, Windows Server 2003 x64 Edition 또는 Windows XP Professional x64 Edition에 설치되지 않습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Exchange</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-028">MS10-028</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio의 취약점으로 인한 원격 코드 실행 문제점 (980094)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office Visio에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 Visio 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-029">MS10-029</a></td>
<td style="border:1px solid black;"><strong>Windows ISATAP 구성 요소의 취약점으로 인한 스푸핑 허용 문제점 (978338)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점 1건을 해결합니다. 이 보안 업데이트의 심각도는 Windows XP, Windows Server 2003, Windows Vista 및 Windows Server 2008에 대해 보통입니다. Windows 7 및 Windows Server 2008 R2에는 이 보안 업데이트에 의해 배포되는 기능이 포함되어 있지 않으므로 취약하지 않습니다.<br />
<br />
이 취약점으로 인해 공격자가 IPv4 주소를 스푸핑하여 소스 IPv4 주소를 사용하는 필터링 장치를 우회할 수 있습니다. 이 보안 업데이트는 Windows TCP/IP 스택이 터널링된 ISATAP 패킷에서 소스 IPv6 주소를 확인하는 방식을 변경하여 취약점을 해결합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">보통</a><br />
스푸핑</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 악용 가능성 평가 수준 내림차순 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](https://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.

 
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-021">MS10-021</a></td>
<td style="border:1px solid black;">Windows 커널 메모리 할당 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0236">CVE-2010-0236 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-021">MS10-021</a></td>
<td style="border:1px solid black;">Windows 커널 심볼 링크 작성 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0237">CVE-2010-0237 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-028">MS10-028</a></td>
<td style="border:1px solid black;">Visio 특성 유효성 검사 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0254">CVE-2010-0254 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-027">MS10-027</a></td>
<td style="border:1px solid black;">Media Player 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0268">CVE-2010-0268 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-025">MS10-025</a></td>
<td style="border:1px solid black;">Media Services 스택 기반 버퍼 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0478">CVE-2010-0478 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-023">MS10-023</a></td>
<td style="border:1px solid black;">Microsoft Office Publisher 파일 변환 텍스트 상자 처리 버퍼 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0479">CVE-2010-0479 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-026">MS10-026</a></td>
<td style="border:1px solid black;">MPEG Layer-3 오디오 디코더 스택 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0480">CVE-2010-0480 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-022">MS10-022</a></td>
<td style="border:1px solid black;">VBScript 도움말 키 누르기 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0483">CVE-2010-0483 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능<br />
<br />
Windows Server 2008, Windows 7 및 Windows Server 2008 R2:<br />
<a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3 (영문)</strong></a> - 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">이 취약점은 공개되었으며, <a href="https://technet.microsoft.com/security/advisory/981169">Microsoft 보안 권고 981169</a>에 설명되어 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-028">MS10-028</a></td>
<td style="border:1px solid black;">Visio 인덱스 계산 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0256">CVE-2010-0256 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2 (영문)</strong></a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB 클라이언트 트랜잭션 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0270">CVE-2010-0270 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2 (영문)</strong></a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB 클라이언트 응답 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0476">CVE-2010-0476 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2 (영문)</strong></a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-019">MS10-019</a></td>
<td style="border:1px solid black;">WinVerifyTrust 서명 유효성 검사 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0486">CVE-2010-0486 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2 (영문)</strong></a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-019">MS10-019</a></td>
<td style="border:1px solid black;">Cabview 손상 유효성 검사 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0487">CVE-2010-0487 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2 (영문)</strong></a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB 클라이언트 불완전 응답 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3676">CVE-2009-3676 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3 (영문)</strong></a> - 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">이 취약점은 공개되었으며, <a href="https://technet.microsoft.com/security/advisory/977544">Microsoft 보안 권고 977544</a>에 설명되어 있습니다.<br />
<br />
서비스 거부가 발생할 수 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-024">MS10-024</a></td>
<td style="border:1px solid black;">SMTP Server MX 레코드 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0024">CVE-2010-0024 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3 (영문)</strong></a> - 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">서비스 거부가 발생할 수 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB 클라이언트 메모리 할당 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0269">CVE-2010-0269 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3 (영문)</strong></a> - 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB 클라이언트 메시지 크기 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0477">CVE-2010-0477 (영문)</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3 (영문)</strong></a> - 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">서비스 거부가 발생할 수 있습니다.</td>
</tr>
</tbody>
</table>
  
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
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
</td>
</tr>
<tr class="alternateRow">
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
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=d7538166-35ee-4c6b-be8c-e83a1fc6cd77&displaylang=ko)  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 5.1](https://www.microsoft.com/download/details.aspx?familyid=13846177-f25f-4dd4-9fe9-ac43e1d4d73d&displaylang=ko)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=67ccac04-e5c8-4381-9d1a-9b676dd516a6&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=73b3d681-26bb-49c1-849e-1f72484cb978)  
(긴급)
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 코덱](https://www.microsoft.com/download/details.aspx?familyid=f6394fc2-b9d0-46cf-9265-a0d4aeb1448f&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media Player 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=c0b8b362-a321-4ac9-be98-15c71bb7a043&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=c5f4577e-7546-40e9-8bcd-be11c1b260a6&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[VBScript 5.1](https://www.microsoft.com/download/details.aspx?familyid=421be318-f217-4d12-b7a5-833093189073&displaylang=ko)<sup>[1]</sup>
(KB981350)  
(중요)  
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=421be318-f217-4d12-b7a5-833093189073&displaylang=ko)  
(KB981350)  
(중요)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=d5fc47a4-cecb-4817-aafb-45f335061be3&displaylang=ko)  
(KB981349)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=88a0e872-01de-495b-8eec-d105a970daa7)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
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
없음
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
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=2a01ddf0-f3ea-47c8-ada2-e69f6c1b5f96&displaylang=ko)  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=6c3ac102-2107-4726-98be-4fbf6b858bfb)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=dec38c02-3d4a-41c5-8954-e57f56b8fa5b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 코덱](https://www.microsoft.com/download/details.aspx?familyid=b1582a74-4a7b-4540-beb1-7c89c86eae87&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2에 설치된 Windows Media Player 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=5c748c6d-84d1-45a9-8a33-9372eb5504d5&displaylang=ko)  
(긴급)  
[Windows XP 서비스 팩 3에 설치된 Windows Media Player 9 시리즈](https://www.microsoft.com/download/details.aspx?familyid=9e4277b4-2dc5-4163-a6aa-7e07dd32b721&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=142710fd-9cd4-4dd0-aaba-2aace03c008f&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 2의 [VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=aa8ff157-a7b3-4787-80c9-5bc453f0f1c9&displaylang=ko)  
(KB981350)  
(중요)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=cb21d276-65e9-4c8f-96e3-cf6dc36d0133&displaylang=ko)  
(KB981349)  
(중요)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=ba7ef6e5-80ba-4281-a611-6e5be008c1b4&displaylang=ko)  
(KB981332)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=de447b76-ec89-426b-ac54-3ae3855d1159&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=9dc3e1c2-2e9d-4d86-9fce-446c409ad613&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=9bbff00c-f8f4-4a44-98f2-18a868986ae1)  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=e64e487e-2727-4396-b0c9-6eaf000214d2)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c5a21239-a9a3-4ec5-9de8-7d2fc16fc6b8)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 코덱](https://www.microsoft.com/download/details.aspx?familyid=8afca317-a647-44aa-a771-5d85cd5d62ea)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3c0cb02e-3484-4cdf-8c64-c697ad3e2889)  
(중요)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=896c738d-4058-440f-8d4f-16c678610cd1)  
(KB981350)  
(중요)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=d7e8b930-8708-4f0b-b22b-961c2cbc2673)  
(KB981349)  
(중요)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=153fd9c1-0f8e-4492-87d1-f0381e7feb23)  
(KB981332)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4f9a696d-2712-4777-a642-e78a38336e8a)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d872bd77-f491-4706-8ff5-081ac0bf3d6f)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
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
없음
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=0e7e3deb-f078-4953-9642-675ec69267f2&displaylang=ko)  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=7ae9b1d0-0dbe-4abd-b315-10cea4ceccd7)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1189304f-d626-426d-960c-a86dc2d2b528&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 코덱](https://www.microsoft.com/download/details.aspx?familyid=9f89746c-181e-4177-a851-ec1826e78b6d&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0a7ea2d0-61ce-4b68-ad82-d917b1a56f9d&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=28b035b8-d56e-4e93-b811-9a82cf1d4ba9&displaylang=ko)  
(KB981350)  
(중요)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=a142a553-85fc-40e0-9426-8d58f6a4333c&displaylang=ko)  
(KB981349)  
(중요)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=72754e1b-3d09-4b9d-8794-689c45a37f66&displaylang=ko)  
(KB981332)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f781e9e4-87d4-4243-9d44-256424d75fec&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=cd007a6c-04b3-490c-aff4-d5af3e69d477&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=99a3f6da-728f-421c-ab41-c4c4751934a4&displaylang=ko)  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=1709fd4e-d7c6-4cbb-8b71-a96b8d6eee58)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=52e4f66b-b76c-46a1-aeff-74efa21fc743&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 코덱](https://www.microsoft.com/download/details.aspx?familyid=b97e7ea1-a163-4ce4-8cbc-5f933773c4b2&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1fc66f54-260a-4219-a0b4-056ba9dd0abe&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=339ddf48-8949-4857-9ef6-1ddcc7c5f8b8&displaylang=ko)  
(KB981350)  
(중요)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=a489b4e3-78d2-411b-b27c-5987b8fc91d1&displaylang=ko)  
(KB981349)  
(중요)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=72c3013b-f72f-422b-8a89-2246dea4b378&displaylang=ko)  
(KB981332)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=644ff070-237b-4a73-b2e2-9fffdafa3927&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=19cfddfe-e8da-4564-9730-babfae4a3ebb&displaylang=ko)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=06832599-1e9b-4792-8c7b-7b5b3a3d6277)  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=811a2b28-655d-4b5d-821e-5a90d556dba3)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=b2b6d8b1-63cc-459c-b5fa-1355386273c8)  
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
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=8dcb8be8-fb78-4518-aa7e-f8b17f7dfb86)  
(중요)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=9a8bee82-5f7f-490e-a1eb-481f6d4fc4f5)  
(KB981350)  
(중요)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=7d542ac6-8a5b-4dd7-8688-2b5feb563636)  
(KB981349)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=56c8238d-8b04-4aa5-8719-40550cd7325c)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=916f1b09-e79e-4347-9fbc-c0cf07de397d)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
</td>
</tr>
<tr class="alternateRow">
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
없음
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?familyid=a52225a7-6005-4f2b-8291-db20558f23f8&displaylang=ko)  
(KB978601  
(긴급)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=6145e2b2-36fd-4360-bd5b-2bd11890fc52)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=25eeaeb3-c0a3-4a02-9912-acd0342648ba&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 코덱](https://www.microsoft.com/download/details.aspx?familyid=0e7140bb-42d3-48b3-9f4b-d55b17770de8&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista](https://www.microsoft.com/download/details.aspx?familyid=86d7b054-af4f-4d8a-9873-cb5246466374&displaylang=ko)  
(중요)  
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=86d7b054-af4f-4d8a-9873-cb5246466374&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=ee5c42c6-16bb-48bf-95c2-c188bb17d04b&displaylang=ko)  
(KB981349)  
(심각도 없음<sup>[2]</sup>)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=f2a37dbf-4a95-4e8d-a474-ecacd9aee690&displaylang=ko)  
(KB981332)  
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=196055a6-15d1-4da8-b33d-501e69bf5176&displaylang=ko)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?familyid=9ba7468c-23a4-4994-9a5a-22e96ef586f3&displaylang=ko)  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=5b7efa82-0feb-413a-9f8e-212e7432cd99&displaylang=ko)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=394c1caa-97e4-47a3-9aac-a4a88508bd31&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 코덱](https://www.microsoft.com/download/details.aspx?familyid=b885aef4-3a5d-4c3e-bef6-5efef2965752&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=7c84aa24-6331-427a-969c-27f7d39db3d7&displaylang=ko)  
(중요)  
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7c84aa24-6331-427a-969c-27f7d39db3d7&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=ea5c5e9c-0ecd-47bc-912d-5adc00d1aa21&displaylang=ko)  
(KB981349)  
(심각도 없음<sup>[2]</sup>)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=79093796-4ea9-4c6c-92cc-3fd63c5db918&displaylang=ko)  
(KB981332)  
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7c1d1622-1b67-438d-aae4-1a3954974a36&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
</td>
</tr>
<tr class="alternateRow">
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
없음
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?familyid=97ffeec8-8b6d-4a30-97b0-4bff2ba5e91d&displaylang=ko)\*  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=f111735b-68b0-4bcc-9dd8-818a5eca3400)\*  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=51c9c420-4507-4911-a8f5-82331a696882&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 코덱](https://www.microsoft.com/download/details.aspx?familyid=8e9c04c9-898f-4ed2-949d-f4343cc0d9f6&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=25e3ce7f-53a0-4049-a65c-011d2143c4c2&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=dbe89813-0a45-463b-928c-1e58f7bb596a&displaylang=ko)\*\*  
(KB981349)  
(심각도 없음<sup>[2]</sup>)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=527d6376-efc9-436b-835b-219d38bb28f0&displaylang=ko)\*\*  
(KB981332)  
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e29ead69-000a-4982-a25c-f3981eda381a&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=61ece7bc-e9fa-4ede-ba7d-9e5a4c64b9be&displaylang=ko)\*  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?familyid=49f9f740-023a-4291-becf-838a1d282321&displaylang=ko)\*  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=91c08251-0085-44cb-9e9c-9a1a84374caf)\*  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=61c26a1f-c885-4474-9843-204c41628889&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 코덱](https://www.microsoft.com/download/details.aspx?familyid=d6f2e1ae-48d3-4d2c-b329-32cff00afee5&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8b99e54d-955b-4a06-9a04-b2f4596efd72&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=9db62357-557d-40cd-9826-b7baa6c9de65&displaylang=ko)\*\*  
(KB981349)  
(심각도 없음<sup>[2]</sup>)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=0c384dbc-21b7-4cbc-b68f-ced971d9b791&displaylang=ko)\*\*  
(KB981332)  
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8f922e64-e3a6-46fe-9a81-b2813ea6a330&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=72e7c7ea-55ef-457b-a03a-49aa9dea2e84&displaylang=ko)\*  
(보통
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?familyid=bd60779a-8bb1-4107-a344-9b09a50e96ff&displaylang=ko)  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=eb116688-1d6e-4e20-948e-1d347af5d985)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=bcf8b919-08a9-487f-8dfd-3ca24328c4f3)  
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
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b1f9746d-61a2-406f-b707-60646bd5b5bb)  
(보통)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=84c5aaae-9417-42a1-834f-22c1ad46a12f)  
(KB981349)  
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8c48302c-a1d6-41bc-ad24-7ce7332d4842)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
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
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?familyid=8d4a6c65-e171-4570-8f3f-118f06910baf&displaylang=ko)  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?familyid=f0dbac52-0f0e-40bc-9371-17fa594424d5)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=389184c5-9001-497d-bdf4-81f97ecb617f&displaylang=ko)  
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
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=ff58d80c-33ce-4d9e-aaa5-0b1841458931&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=c3f76835-0053-4e53-a451-14255e7a4fc0&displaylang=ko)  
(KB981332)  
(심각도 없음<sup>[2]</sup>)
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
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?familyid=cf8c6721-05c2-4680-93b4-be36f09c6d15&displaylang=ko)  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?familyid=b23efe7d-bca4-4d49-9104-6ae39dc5daa9)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=f3495dae-71f3-421d-a191-d26965f26ad1&displaylang=ko)  
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
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=7f1dc055-2ec9-407a-9e69-da12338587e3&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=998164b7-4b8c-468b-8d39-f242633c8838&displaylang=ko)  
(KB981332)  
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
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
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?familyid=94dfdaae-8464-4de6-a401-7eb70b3bb34f&displaylang=ko)\*  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?familyid=a2979c02-2a80-4b84-bf6c-4798064bdf28)\*  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=cd1a046e-915d-4904-b753-5a24be10c504&displaylang=ko)\*  
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
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=28389c1d-2a12-4bef-a59b-726bb6449c8b&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=c4039d40-a0c7-4183-ab50-04f690d1c5dc&displaylang=ko)\*\*  
(KB981332)  
(심각도 없음<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=eb27cd2b-d514-4405-8650-259a42e35155&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?familyid=40f622d2-48e7-4eb2-9430-bbd218cb5208&displaylang=ko)  
(KB978601)  
(긴급)  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?familyid=5e416d4b-5de7-4688-80c6-245de159e0ce)  
(KB979309)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=541e9e2f-ec1d-42b2-aae5-481c0d435169)  
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
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d4ea3984-5183-47f1-814e-29cb6c90ae06)  
(보통)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=8174463c-5c5e-4095-90c8-fd1e898d4ba5)  
(KB981332)  
(심각도 없음<sup>[2]</sup>)
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

**\*Server Core 설치가 영향을 받습니다.** 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오

**\*\*Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오

**MS10-022 참고 사항**

<sup>[1]</sup>이 보안 업데이트는 설치된 VBScript 5.1을 VBScript 5.6으로 업그레이드합니다.

<sup>[2]</sup>이 공지에서 설명한 취약점이 이 소프트웨어에 영향을 미치지 않으므로 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 나중에 발생 가능한 새로운 경로를 방지하기 위한 심층적인 보안 대응책으로써 이 소프트웨어를 사용하는 고객은 이 보안 업데이트를 적용하는 것이 좋습니다.

**MS10-024 참고 사항**

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
[**MS10-023**](https://technet.microsoft.com/security/bulletin/ms10-023)
</td>
<td style="border:1px solid black;">
[**MS10-028**](https://technet.microsoft.com/security/bulletin/ms10-028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
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
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=943b3830-70d5-46c5-bffc-1b494434b5f7&displaylang=ko)  
(KB980466)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2002 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2d563cbc-d8f7-486b-8c54-25d168085376&displaylang=ko)  
(KB979364)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=7c2f4610-77bb-4d72-847b-1a06c523b137&displaylang=ko)  
(KB980469)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=803a7ea0-a9da-46dd-9548-0177d3774be7&displaylang=ko)  
(KB979356)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 서비스 팩 1 및 Microsoft Office Publisher 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=10ca2f71-0ab2-4344-b7fd-bbbd6a783a96&displaylang=ko)  
(KB980470)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2007 서비스 팩 1 및 Microsoft Office Visio 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=56fe020f-4444-4a43-aa98-e99a622f6a69&displaylang=ko)  
(KB979365)  
(중요)
</td>
</tr>
</table>
 

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
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2000
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2000 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=e47c90a0-c9c8-43b7-bec7-34107ddde294&displaylang=ko)  
(KB976703)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2003
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=bc8391f8-5335-496b-ad4c-bae38509be4a&displaylang=ko)  
(KB976702)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 서비스 팩 1(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=6a894b4e-12b6-4a91-9555-d813956b6aac&displaylang=ko)  
(KB981407)  
(심각도 없음<sup>[1]</sup>)  
[Microsoft Exchange Server 2007 서비스 팩 2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=b8f7f872-16d5-49d6-9867-adc01351c06f&displaylang=ko)  
(KB981383)  
(심각도 없음<sup>[1]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=7dcf2390-dff7-4e3a-acca-03f4d43fb79a&displaylang=ko)  
(KB981401)  
(심각도 없음<sup>[1]</sup>)
</td>
</tr>
</table>
 
**MS10-024 참고 사항**

<sup>[1]</sup>이 공지에서 설명한 취약점이 이 소프트웨어에 영향을 미치지 않으므로 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 이 소프트웨어의 고객은 SMTP 서비스에 의해 시작되는 DNS 트랜잭션에 원본 포트 엔트로피를 추가하는 심층 보안 대응책이 포함된 이 업데이트를 적용하는 것이 좋습니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](https://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](https://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](https://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](https://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](https://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**참고** 2009년 8월 1일부터 Microsoft는 Office 업데이트와 Office 업데이트 인벤토리 도구에 대한 지원을 중단합니다. 계속해서 Microsoft Office 제품에 필요한 최신 업데이트를 받으려면 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)를 사용하십시오. 자세한 내용은 [Microsoft Office 업데이트 정보: 자주 제기되는 질문 사항(FAQ)](https://office.microsoft.com/ko-kr/downloads/fx010402221042.aspx)을 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](https://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](https://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](https://go.microsoft.com/fwlink/?linkid=22939)를 참조하십시오. SMS 2.0 사용자는 SUIT(Security Update Inventory Tool)을 사용하여 보안 업데이트 배포를 지원할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](https://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2.0 Administration Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트 (영문)](https://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](https://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](https://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS10-020에서 설명한 문제점을 보고해 주신 [Visuality Systems Ltd. (영문)](https://www.visualitynq.com/)의 Mark Rabinovich
-   MS10-020에서 설명한 세 가지 문제점을 보고해 주신 [stratsec (영문)](https://www.stratsec.net/)의 Laurent Gaffié
-   MS10-021에서 설명한 다섯 가지 문제점을 보고해 주신 [Hispasec (영문)](https://www.hispasec.com/), [Virustotal (영문)](https://www.virustotal.com/)의 Matthew 'j00ru' Jurczyk 및 Gynvael Coldwind
-   MS10-021에서 설명한 두 가지 문제점을 보고해 주신 [Google, Inc.](https://www.google.com/)의 Tavis Ormandy
-   MS10-021에서 설명한 문제점을 보고해 주신 [Obsidium Software (영문)](https://www.obsidium.de/)의 Martin Tofall
-   MS10-023에서 설명한 문제점을 [TippingPoint (영문)](https://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Lionel d'Hauenens
-   MS10-025에서 설명한 문제점을 보고해 주신 [CERT-LEXSI (영문)](https://cert.lexsi.com/)의 Fabien Perigaud
-   MS10-025용 원본 보안 업데이트의 품질 문제에 대한 상세 정보를 제공하고 협력해 주신 [CERT-LEXSI](https://cert.lexsi.com/)의 Fabien Perigaud, [VUPEN Vulnerability Research Team](https://www.vupen.com/) 및 [TELUS Security Labs](https://telussecuritylabs.com/)의 Vulnerability Research Team
-   MS10-026에서 설명한 문제점을 보고해 주신 [Palo Alto Networks (영문)](https://www.paloaltonetworks.com/)의 Yamata Li
-   MS10-027에서 설명한 문제점을 [TippingPoint (영문)](https://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS10-028에서 설명한 두 가지 문제점을 보고해 주신 Fortinet's [FortiGuard Labs (영문)](https://www.fortiguard.com/)의 Bing Liu
-   MS10-029에서 설명한 문제점을 보고해 주신 National EW Research & Simulation Center(Rafael 소재)의 Gabi Nakibly

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](https://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](https://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](https://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2010년 4월 14일): 공지 요약이 게시되었습니다.
-   V1.1(2010년 4월 15일): **요약** 섹션에서 MS10-025의 다시 시작 요구 사항이 수정되었습니다. 또한 Windows Server 2008 및 Windows Server 2008 R2에 대한 Server Core 표시가 수정되었습니다. 이는 MS10-019의 KB978601 업데이트에만 적용됩니다.
-   V2.0(2010년 4월 22일): MS10-025용 원본 보안 업데이트가 이 보안 공지에서 설명한 취약점으로부터 시스템을 보호하지 못함을 고객에게 알리기 위해 개정되었습니다. 고객은 개정된 보안 업데이트가 출시될 때까지 해당 시스템에 미치는 영향을 완화하기 위해 MS10-025에서 설명하는 대안 중 하나를 적용하는 것이 좋습니다.
-   V3.0(2010년 4월 28일): MS10-025에 대한 다시 릴리스된 보안 업데이트를 제공하기 위해 공지가 개정되었습니다.
-   V4.0(2010년 7월 14일): MS10-024의 Windows Server 2008 및 Windows Server 2008 R2에 대한 다시 릴리스된 보안 업데이트를 제공하기 위해 개정되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
