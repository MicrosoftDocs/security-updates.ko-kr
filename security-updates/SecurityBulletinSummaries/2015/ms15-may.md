---
TOCTitle: 'MS15-MAY'
Title: 2015년 5월 Microsoft 보안 공지 요약
ms:assetid: 'ms15-may'
ms:contentKeyID: 65633543
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms15-may(v=Security.10)'
---

2015년 5월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2015년 5월 13일

**버전:** 1.0

이 공지 요약 목록에는 2015년 5월 발표된 보안 공지가 포함되어 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/ko-kr/security/dd252948.aspx)을 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 절을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향받는 소프트웨어에 대한 자세한 내용은 **영향받는 소프트웨어**라는 다음 절을 참조하십시오.

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 ID</strong></td>
<td style="border:1px solid black;"><strong>공지 제목 및 요약</strong></td>
<td style="border:1px solid black;"><strong>최대 심각도<br />
및 취약성 영향</strong></td>
<td style="border:1px solid black;"><strong>다시 시작 요구 사항</strong></td>
<td style="border:1px solid black;"><strong>알려진<br />
문제</strong></td>
<td style="border:1px solid black;"><strong>영향받는 소프트웨어</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3049563)</strong> <br />
이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-044">MS15-044</a></td>
<td style="border:1px solid black;"><strong>Microsoft 글꼴 드라이버의 취약성으로 인한 원격 코드 실행 문제(3057110)</strong><br />
이 보안 업데이트는 Microsoft Windows, Microsoft .NET Framework, Microsoft Office, Microsoft Lync 및 Microsoft Silverlight의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 문서를 열거나 포함된 트루타입 글꼴이 있는 신뢰할 수 없는 웹 페이지를 방문하는 경우 원격 코드 실행을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Office,<br />
Microsoft Lync,<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;"><strong>Windows 필기장의 취약성으로 인한 원격 코드 실행 문제(3046002)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 사용자가 특수 제작된 필기장 파일을 여는 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-046">MS15-046</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office의 취약성으로 인한 원격 코드 실행 문제(3057181)<br />
</strong>이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 Microsoft Office 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-047">MS15-047</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server의 취약성으로 인한 원격 코드 실행 문제(3058083)<br />
</strong>이 보안 업데이트는 Microsoft Office 서버 소프트웨어의 취약성을 해결합니다. 인증된 공격자가 SharePoint 서버에 특수 제작된 페이지를 보내는 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다. 이 취약성 악용에 성공적한 공격자는 대상 SharePoint 사이트의 W3WP 서비스 계정의 보안 컨텍스트에서 임의의 코드를 실행할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Server 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-048">MS15-048</a></td>
<td style="border:1px solid black;"><strong>.NET Framework의 취약성으로 인한 권한 상승 문제(3057134)</strong><br />
이 보안 업데이트는 Microsoft .NET Framework의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 부분 신뢰 응용 프로그램을 설치하는 경우 권한 상승을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-049">MS15-049</a></td>
<td style="border:1px solid black;"><strong>Silverlight의 취약성으로 인한 권한 상승 문제(3058985)</strong><br />
이 보안 업데이트는 Microsoft Silverlight의 취약성을 해결합니다. 영향받는 시스템에서 특수 제작된 Silverlight 응용 프로그램을 실행하면 이 취약성으로 인해 권한 상승이 허용될 수 있습니다. 이 취약성을 악용하기 위해 공격자는 먼저 시스템에 로그온해야 하거나 로그온한 사용자가 특수 제작된 응용 프로그램을 실행하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작할 필요 없음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Siverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-050">MS15-050</a></td>
<td style="border:1px solid black;"><strong>서비스 제어 관리자의 취약성으로 인한 권한 상승 문제(3055642)</strong><br />
이 보안 업데이트는 Windows SCM(서비스 제어 관리자)의 취약성을 해결합니다. 이 취약성은 SCM이 부적절하게 가장 수준을 확인하는 경우 발생합니다. 이 취약성은 공격자가 먼저 시스템에 로그온한 후 권한을 상승시키도록 디자인된 특수 제작된 응용 프로그램을 실행하는 경우 권한 상승을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버의 취약성으로 인한 권한 상승 문제(3057191)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 공격자가 로컬로 로그온하고 커널 모드에서 임의의 코드를 실행하는 경우 권한 상승을 허용할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 공격자는 이 취약성을 이용하기 위해 유효한 로그온 자격 증명이 있어야 하며 로컬로 로그온할 수 있어야 합니다. 이 취약성은 원격으로 또는 익명 사용자가 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-052">MS15-052</a></td>
<td style="border:1px solid black;"><strong>Windows 커널의 취약성으로 인한 보안 기능 우회 문제(3050514)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성은 공격자가 영향받는 시스템에 로그온한 후 특수 제작된 응용 프로그램을 실행하는 경우 보안 기능 우회를 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3050514">3050514</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-053">MS15-053</a></td>
<td style="border:1px solid black;"><strong>JScript 및 VBScript 스크립팅 엔진의 취약성으로 인해 보안 기능 우회 문제(3057263)<br />
</strong>이 보안 업데이트는 Microsoft Windows에서 JScript 및 VBScript 스크립팅 엔진의 ASLR 보안 기능 우회를 해결합니다. 공격자는 대상 시스템에서 임의의 코드를 보다 확실하게 실행하기 위해 원격 코드 실행 취약성 등 다른 취약성과 함께 이러한 ASLR 우회 중 하나를 사용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-054">MS15-054</a></td>
<td style="border:1px solid black;"><strong>Microsoft Management Console 파일 형식의 취약성으로 인한 서비스 거부 문제(3051768)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 인증되지 않은 원격 공격자가 사용자가 특수 제작된 .msc 파일이 포함된 공유를 열도록 유도하는 경우 이 취약성으로 인해 서비스 거부가 허용될 수 있습니다. 하지만 공격자가 강제로 사용자가 이 공유를 방문하거나 해당 파일을 보도록 할 수 있는 방법은 없습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-055">MS15-055</a></td>
<td style="border:1px solid black;"><strong>Schannel의 취약성으로 인한 정보 유출 문제(3061518)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. Schannel(보안 채널)이 암호화된 TLS 세션에서 512비트의 취약한 DFE(Diffie-Hellman ephemeral) 키 길이 사용을 허용하는 경우 이 취약성으로 인해 정보 유출이 허용될 수 있습니다. 512비트 DHE 키를 허용하면 다양한 공격에 DHE 키 교환이 노출되고 취약하게 만듭니다. 공격이 성공하려면 서버에서 512비트 DHE 키 길이를 지원해야 합니다. 기본 구성의 Windows 서버에서 허용되는 최소 DHE 키 길이는 1024비트입니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-KR/library/support.microsoft.com/ko-kr/kb/3061518(v=Security.10)">3061518</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
<span id="sectionToggle1"></span>
다음 표에는 이달에 해결한 각 취약성의 악용 가능성 평가가 나와 있습니다. 취약성은 공지 ID 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약성만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 할 수 있는 각 보안 업데이트에 대한 보안 공지 발표 후 30일 내 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토하십시오. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/ko-kr/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 릴리스"는 관련 소프트웨어를 나타내며 "이전 소프트웨어 릴리스"는 공지의 "영향받는 소프트웨어" 및 "영향받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 릴리스를 나타냅니다.
  
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 ID</strong></td>
<td style="border:1px solid black;"><strong>취약성 제목</strong></td>
<td style="border:1px solid black;"><strong>CVE ID              </strong></td>
<td style="border:1px solid black;"><strong>최신 소프트웨어 릴리스에 대한<br />
악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>이전 소프트웨어 릴리스에 대한<br />
악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>서비스 거부<br />
악용 가능성 평가</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1658">CVE-2015-1658</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">VBScript ASLR 우회</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1684">CVE-2015-1684</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR 우회</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1685">CVE-2015-1685</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">VBScript 및 JScript ASLR 우회</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1686">CVE-2015-1686</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1688">CVE-2015-1688</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1689">CVE-2015-1689</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1691">CVE-2015-1691</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 클립보드 정보 유출 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1692">CVE-2015-1692</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1694">CVE-2015-1694</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1703">CVE-2015-1703</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1704">CVE-2015-1704</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1705">CVE-2015-1705</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1706">CVE-2015-1706</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1708">CVE-2015-1708</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1709">CVE-2015-1709</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1710">CVE-2015-1710</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1711">CVE-2015-1711</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1712">CVE-2015-1712</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1713">CVE-2015-1713</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1714">CVE-2015-1714</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1717">CVE-2015-1717</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-043">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1718">CVE-2015-1718</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-044">MS15-044</a></td>
<td style="border:1px solid black;">OpenType 글꼴 구문 분석 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1670">CVE-2015-1670</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-044">MS15-044</a></td>
<td style="border:1px solid black;">TrueType 글꼴 구문 분석 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1671">CVE-2015-1671</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 필기장 원격 코드 실행 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1675">CVE-2015-1675</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 필기장 원격 코드 실행 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1695">CVE-2015-1695</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 필기장 원격 코드 실행 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1696">CVE-2015-1696</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 필기장 원격 코드 실행 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1697">CVE-2015-1697</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 필기장 원격 코드 실행 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1698">CVE-2015-1698</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-045">MS15-045</a></td>
<td style="border:1px solid black;">Windows 필기장 원격 코드 실행 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1699">CVE-2015-1699</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-046">MS15-046</a></td>
<td style="border:1px solid black;">Microsoft Office 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1682">CVE-2015-1682</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-046">MS15-046</a></td>
<td style="border:1px solid black;">Microsoft Office 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1683">CVE-2015-1683</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-047">MS15-047</a></td>
<td style="border:1px solid black;">Microsoft SharePoint 페이지 콘텐츠 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1700">CVE-2015-1700</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-048">MS15-048</a></td>
<td style="border:1px solid black;">.NET XML 암호 해독 서비스 거부 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1672">CVE-2015-1672</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">영구</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-048">MS15-048</a></td>
<td style="border:1px solid black;">Windows Forms 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1673">CVE-2015-1673</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-049">MS15-049</a></td>
<td style="border:1px solid black;">Microsoft Silverlight의 브라우저 외부에서 실행 응용 프로그램 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1715">CVE-2015-1715</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-050">MS15-050</a></td>
<td style="border:1px solid black;">서비스 제어 관리자 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1702">CVE-2015-1702</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 메모리 공개 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1676">CVE-2015-1676</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 메모리 공개 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1677">CVE-2015-1677</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 메모리 공개 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1678">CVE-2015-1678</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 메모리 공개 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1679">CVE-2015-1679</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 메모리 공개 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1680">CVE-2015-1680</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-051">MS15-051</a></td>
<td style="border:1px solid black;">Win32k 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1701">CVE-2015-1701</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">영구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-052">MS15-052</a></td>
<td style="border:1px solid black;">Windows 커널 보안 기능 우회 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1674">CVE-2015-1674</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-053">MS15-053</a></td>
<td style="border:1px solid black;">VBScript ASLR 우회</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1684">CVE-2015-1684</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-053">MS15-053</a></td>
<td style="border:1px solid black;">VBScript 및 JScript ASLR 우회</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1686">CVE-2015-1686</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-054">MS15-054</a></td>
<td style="border:1px solid black;">Microsoft Management Console 파일 형식의 서비스 거부 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1681">CVE-2015-1681</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">임시</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-055">MS15-055</a></td>
<td style="border:1px solid black;">SChannel 정보 유출 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1716">CVE-2015-1716</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
</tbody>
</table>
  
영향받는 소프트웨어  
-------------------
  
<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.
  
**참고** 단일 취약성에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 ID로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
### Windows 운영 체제 및 구성 요소(표 1/2)

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/ko-kr/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/ko-kr/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/ko-kr/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/ko-kr/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                             

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx) 

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2                

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
(보통)  
Internet Explorer 7  
(3049563)  
(보통)  
Internet Explorer 8  
(3049563)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(3048073)  
(긴급)  
Microsoft .NET Framework 4  
(3048074)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(3023211)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3023220)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3035488)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(업데이트 없음, 참고 사항 참조)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
(보통)  
Internet Explorer 7  
(3049563)  
(보통)  
Internet Explorer 8  
(3049563)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(3048073)  
(긴급)  
Microsoft .NET Framework 4  
(3048074)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3023220)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3035488)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(업데이트 없음, 참고 사항 참조)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
(보통)  
Internet Explorer 7  
(3049563)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3045171)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3023220)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3035488)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(업데이트 없음, 참고 사항 참조)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/ko-kr/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/ko-kr/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/ko-kr/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/ko-kr/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(긴급)  
Internet Explorer 8  
(3049563)  
(긴급)  
Internet Explorer 9  
(3049563)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(3048068)  
(긴급)  
Microsoft .NET Framework 4  
(3048074)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3023213)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3035485)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(긴급)  
Internet Explorer 8  
(3049563)  
(긴급)  
Internet Explorer 9  
(3049563)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(3048068)  
(긴급)  
Microsoft .NET Framework 4  
(3048074)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3023213)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3035485)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/ko-kr/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/ko-kr/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/ko-kr/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/ko-kr/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(보통)  
Internet Explorer 8  
(3049563)  
(보통)  
Internet Explorer 9  
(3049563)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(3048068)  
(긴급)  
Microsoft .NET Framework 4  
(3048074)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3023213)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3035485)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(보통)  
Internet Explorer 8  
(3049563)  
(보통)  
Internet Explorer 9  
(3049563)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(3048068)  
(긴급)  
Microsoft .NET Framework 4  
(3048074)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3023213)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3035485)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3045171)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3023213)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3035485)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/ko-kr/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/ko-kr/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/ko-kr/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/ko-kr/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
(긴급)  
Internet Explorer 9  
(3049563)  
(긴급)  
Internet Explorer 10  
(3049563)  
(긴급)  
Internet Explorer 11  
(3049563)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
(긴급)  
Internet Explorer 9  
(3049563)  
(긴급)  
Internet Explorer 10  
(3049563)  
(긴급)  
Internet Explorer 11  
(3049563)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/ko-kr/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/ko-kr/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/ko-kr/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/ko-kr/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
(보통)  
Internet Explorer 9  
(3049563)  
(보통)  
Internet Explorer 10  
(3049563)  
(보통)  
Internet Explorer 11  
(3049563)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3045171)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/ko-kr/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/ko-kr/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/ko-kr/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/ko-kr/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5  
(3048071)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(중요)  
Microsoft .NET Framework 3.5  
(3035486)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5  
(3048071)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(중요)  
Microsoft .NET Framework 3.5  
(3035486)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5  
(3048072)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(중요)  
Microsoft .NET Framework 3.5  
(3035487)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5  
(3048072)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(중요)  
Microsoft .NET Framework 3.5  
(3035487)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/ko-kr/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/ko-kr/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/ko-kr/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/ko-kr/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5  
(3048071)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(중요)  
Microsoft .NET Framework 3.5  
(3035486)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5  
(3048072)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(중요)  
Microsoft .NET Framework 3.5  
(3035487)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/ko-kr/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/ko-kr/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/ko-kr/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/ko-kr/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(3045171)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3045171)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046002)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/ko-kr/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/ko-kr/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/ko-kr/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/ko-kr/library/security/ms15-050)

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
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3045171)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3045171)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(중요)  
Microsoft .NET Framework 4  
(3023221)  
(중요)  
Microsoft .NET Framework 4  
(3032662)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5  
(3048071)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(중요)  
Microsoft .NET Framework 3.5  
(3035486)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3055642)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3045171)  
(긴급)  
Microsoft .NET Framework 3.5  
(3048072)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(중요)  
Microsoft .NET Framework 3.5  
(3035487)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3055642)  
(중요)

</td>
</tr>
</table>
 
**MS15-044 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

또한 [Microsoft 다운로드 센터](http://www.microsoft.com/ko-kr/download/search.aspx?q=security%20update)에서만 제공되는 Microsoft .NET Framework 4.6 RC에 대한 업데이트를 사용할 수 있습니다. 

**MS15-043, MS15-044 및 MS15-045 참고 사항**

Windows Technical Preview 및 Windows Server Technical Preview가 영향을 받습니다. 해당 운영 체제를 실행하는 고객은 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)를 통해 이 업데이트를 적용하는 것이 좋습니다.

**MS15-050 참고 사항**

Windows Server 2003이 영향을 받지만 이에 대한 업데이트는 배포되지 않습니다. 자세한 내용은 공지를 참조하십시오. 

 

### Windows 운영 체제 및 구성 요소(표 2/2)

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/ko-kr/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/ko-kr/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/ko-kr/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/ko-kr/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/ko-kr/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                 

</td>
<td style="border:1px solid black;">
**없음**                                             

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                      

</td>
<td style="border:1px solid black;">
**없음**                                             

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                      

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.6 및 VBScript 5.6  
(3050946)  
(중요)  
JScript 5.7 및 VBScript 5.7  
(3050945)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.6 및 VBScript 5.6  
(3050946)  
(중요)  
JScript 5.7 및 VBScript 5.7  
(3050945)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.6 및 VBScript 5.6  
(3050946)  
(중요)  
JScript 5.7 및 VBScript 5.7  
(3050945)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/ko-kr/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/ko-kr/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/ko-kr/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/ko-kr/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/ko-kr/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3050945)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3050945)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/ko-kr/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/ko-kr/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/ko-kr/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/ko-kr/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/ko-kr/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3050945)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3050945)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3050945)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/ko-kr/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/ko-kr/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/ko-kr/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/ko-kr/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/ko-kr/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/ko-kr/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/ko-kr/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/ko-kr/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/ko-kr/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/ko-kr/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/ko-kr/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/ko-kr/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/ko-kr/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/ko-kr/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/ko-kr/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3050514)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3050514)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3050514)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3050514)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/ko-kr/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/ko-kr/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/ko-kr/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/ko-kr/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/ko-kr/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3050514)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3050514)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/ko-kr/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/ko-kr/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/ko-kr/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/ko-kr/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/ko-kr/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(3050514)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3050514)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/ko-kr/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/ko-kr/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/ko-kr/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/ko-kr/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/ko-kr/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3050945)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3050945)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.8 및 VBScript 5.8  
(3050941)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3050514)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3061518)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3045171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3050514)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3051768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3061518)  
(중요)

</td>
</tr>
</table>
 
**MS15-053 및 MS15-054 참고 사항:**

Windows Technical Preview 및 Windows Server Technical Preview가 영향을 받습니다. 해당 운영 체제를 실행하는 고객은 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)를 통해 이 업데이트를 적용하는 것이 좋습니다.

 

### Microsoft Server 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://technet.microsoft.com/ko-kr/library/security/ms15-047)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 버전)  
(2760412)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 버전)  
(2760412)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://technet.microsoft.com/ko-kr/library/security/ms15-047)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 서비스 팩 2  
(3017815)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 서비스 팩 2  
(3017815)  
(중요)  
Microsoft SharePoint Server 2010 서비스 팩 2  
(2956192)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://technet.microsoft.com/ko-kr/library/security/ms15-047)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1  
(3039736)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 서비스 팩 1  
(3054792)  
(중요)

</td>
</tr>
</table>
 
**MS15-046 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오. 

 

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
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(2883029)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(2965282)  
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
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(2881073)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(2965311)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(2999412)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(2965242)  
(중요)  
Microsoft Excel 2010 서비스 팩 2(32비트 버전)  
(2965240)  
(중요)  
Microsoft PowerPoint 2010 서비스 팩 2(32비트 버전)  
(2999420)  
(중요)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(2965237)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(2881073)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(2965311)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(2999412)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(2965242)  
(중요)  
Microsoft Excel 2010 서비스 팩 2(64비트 버전)  
(2965240)  
(중요)  
Microsoft PowerPoint 2010 서비스 팩 2(64비트 버전)  
(2999420)  
(중요)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(2965237)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

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
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(2975808)  
(중요)  
Microsoft Excel 2013 서비스 팩 1(32비트 버전)  
(2986216)  
(중요)  
Microsoft PowerPoint 2013 서비스 팩 1(32비트 버전)  
(2975816)  
(중요)  
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(2965307)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)  
(2975808)  
(중요)  
Microsoft Excel 2013 서비스 팩 1(64비트 버전)  
(2986216)  
(중요)  
Microsoft PowerPoint 2013 서비스 팩 1(64비트 버전)  
(2975816)  
(중요)  
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(2965307)  
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
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

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
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1  
(2975808)  
(중요)  
Microsoft Excel 2013 RT 서비스 팩 1  
(2986216)  
(중요)  
Microsoft PowerPoint 2013 RT 서비스 팩 1  
(2975816)  
(중요)  
Microsoft Word 2013 RT 서비스 팩 1  
(2965307)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

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
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3062536)  
(중요)  
Microsoft Excel for Mac 2011  
(3062536)  
(중요)  
Microsoft PowerPoint for Mac 2011  
(3062536)  
(중요)  
Microsoft Word for Mac 2011  
(3062536)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**기타 Office 소프트웨어**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

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
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer  
(2956195)  
(중요)

</td>
</tr>
</table>
 
**MS15-044 및 MS15-046 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오. 

 

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
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2965233)  
(중요)  
Excel Services  
(2956194)  
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
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3023055)  
(중요)  
Excel Services  
(3039725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2  
(2956140)  
(중요)  
Microsoft Excel Web Apps 2010 서비스 팩 2  
(2956193)  
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
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/ko-kr/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1  
(3039748)  
(중요)

</td>
</tr>
</table>
 
**MS15-046 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

### Microsoft 통신 플랫폼 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 콘솔

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 콘솔  
(3051467)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)  
(3051464)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)  
(3051464)  
(긴급)

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
(3051465)  
(긴급)

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
(3051466)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype)  
(3039779)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype Basic)  
(3039779)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(64비트)  
(비즈니스용 Skype)  
(3039779)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(64비트)  
(비즈니스용 Skype Basic)  
(3039779)  
(긴급)

</td>
</tr>
</table>
 
**MS15-044 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

### Microsoft 개발자 도구 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/ko-kr/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-049**](https://technet.microsoft.com/ko-kr/library/security/ms15-049)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
Mac에 설치된 Microsoft Silverlight 5  
(3056819)  
(긴급)  
Mac에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3056819)  
(긴급)  
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5  
(3056819)  
(긴급)  
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3056819)  
(긴급)  
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5  
(3056819)  
(긴급)  
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3056819)  
(긴급)

</td>
<td style="border:1px solid black;">
Mac에 설치된 Microsoft Silverlight 5  
(3056819)  
(중요)  
Mac에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3056819)  
(중요)  
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5  
(3056819)  
(중요)  
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3056819)  
(중요)  
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5  
(3056819)  
(중요)  
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3056819)  
(중요)

</td>
</tr>
</table>
 
**MS15-044 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

검색, 배포 도구 및 지침
-----------------------

<span id="sectionToggle3"></span>
관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 있습니다.

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트와 일반적인 보안 구성 오류를 검색할 수 있습니다.

관리자는 WSUS(Windows Server Update Services), SMS(Systems Management Server) 및 System Center Configuration Manager를 통해 보안 업데이트를 배포할 수 있습니다.

ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](http://technet.microsoft.com/ko-kr/security/cc297183)를 참조하십시오. 

감사의 말
---------

<span id="sectionToggle4"></span>
Microsoft는 신뢰할 수 있는 취약성 공개를 통해 고객을 보호하는 데 도움을 주는 보안 커뮤니티의 공로를 기립니다. 자세한 내용은 [감사의 말](https://technet.microsoft.com/ko-kr/library/security/dn903755.aspx)을 참조하십시오.

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 릴리스에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services 및 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 릴리스에서 제공되지 않습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft Update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/ko-kr/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services용으로 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/ko-kr/windowsserver/bb332157.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 재출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약성 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침입 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://technet.microsoft.com/ko-kr/security/dn467918)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://technet.microsoft.com/ko-kr/library/bb466251.aspx)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 모범 사례와 관련한 추가 정보를 제공합니다.

**기타 보안 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 제공됩니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/ko-kr/download/search.aspx?q=security%20update)에서 제공됩니다. "보안 업데이트"라는 키워드 검색을 수행하면 가장 쉽게 찾을 수 있습니다.
-   소비자 플랫폼용 업데이트는 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)에서 제공됩니다.
-   이달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 긴급 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/ko-kr/kb/913086)을 참조하십시오.

**IT 전문가 보안 커뮤니티**

[IT 전문가 보안 커뮤니티](http://technet.microsoft.com/ko-kr/security/cc136632.aspx)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 알아보고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향받는 소프트웨어는 테스트를 거쳐 영향받는 버전이 확인되었습니다. 다른 버전은 지원 주기가 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 주기를 확인하려면 [Microsoft 지원 주기](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.

IT 전문가용 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/ko-kr/security/bb980617)

Windows 컴퓨터를 바이러스 및 맬웨어로부터 보호: [바이러스 솔루션 및 보안 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ko)

지역별 지원 정보: [국가별 지원](http://support.microsoft.com/common/international.aspx?ln=ko)

### 고지 사항

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성과 특정 목적에 대한 적합성의 보증을 포함하여 명시적이거나 묵시적인 모든 보증을 부인합니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 수정 내역

-   V1.0(2015년 5월 13일): 공지 요약이 게시되었습니다.

*2015-05-08 14:39Z-07:00에 페이지가 생성되었습니다.*
