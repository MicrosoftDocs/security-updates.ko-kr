---
TOCTitle: 'MS16-FEB'
Title: 2016년 2월 Microsoft 보안 공지 요약
ms:assetid: 'ms16-feb'
ms:contentKeyID: 72238928
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms16-feb(v=Security.10)'
---

MSRC ppDocument 서식 파일

2016년 2월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2016년 2월 10일 | 업데이트된 날짜: 2016년 2월 25일

**버전:** 3.1

이 공지 요약 목록에는 2016년 2월 발표된 보안 공지가 포함되어 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/ko-kr/security/dd252948.aspx)을 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 절을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향받는 소프트웨어에 대한 자세한 내용은 **영향받는 소프트웨어**라는 다음 절을 참조하십시오.

<table style="width:100%;">
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-009">MS16-009</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3134220)</strong> <br />
이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우, 이 취약성 악용에 성공한 공격자는 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3134814">3134814</a></td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-011">MS16-011</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge용 누적 보안 업데이트(3134225) <br />
</strong>이 보안 업데이트는 Microsoft Edge의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Microsoft Edge를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-012">MS16-012</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Microsoft Windows PDF Library에 대한 보안 업데이트(3138938) <br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 보다 심각한 취약성은 Microsoft Windows PDF Library가 API(응용 프로그래밍 인터페이스) 호출을 부적절하게 처리하는 경우 원격 코드 실행을 허용할 수 있으며, 이로 인해 공격자가 사용자의 시스템에서 임의의 코드를 실행할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다. 하지만 공격자는 강제로 사용자가 악성 PDF 문서를 다운로드하거나 열도록 만들 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-013">MS16-013</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Windows 필기장에 대한 보안 업데이트(3134811)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 사용자가 특수 제작된 필기장 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-014">MS16-014</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Microsoft Windows에 대한 보안 업데이트(3134228)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 공격자가 대상 시스템에 로그온하고 특수 제작된 응용 프로그램을 실행할 수 있는 경우 원격 코드 실행을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3126041">3126041</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3126587">3126587</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3126593">3126593</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-015">MS16-015</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Microsoft Office에 대한 보안 업데이트(3134226)</strong> <br />
이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 Microsoft Office 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office, <br />
Microsoft Office Services 및 Web Apps,<br />
Microsoft Server 소프트웨어 </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-016">MS16-016</a></td>
<td style="border:1px solid black;"><strong>권한 상승을 해결하기 위한 WebDAV에 대한 보안 업데이트(3136041)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 공격자가 Microsoft WebDAV(Web Distributed Authoring and Versioning) 클라이언트를 사용하여 서버에 특수 제작된 입력을 보내는 경우 이 취약성으로 인해 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-017">MS16-017</a></td>
<td style="border:1px solid black;"><strong>권한 상승을 해결하기 위한 원격 데스크톱 디스플레이 드라이버에 대한 보안 업데이트(3134700) </strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 인증된 공격자가 RDP를 사용하여 대상 시스템에 로그온하고 연결을 통해 특수 제작된 데이터를 보내는 경우 이 취약성으로 인해 권한 상승이 허용될 수 있습니다. 기본적으로 RDP는 Windows 운영 체제에서 사용되지 않습니다. RDP가 사용되지 않는 시스템은 취약하지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3134700">3134700</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3126446">3126446</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-018">MS16-018</a></td>
<td style="border:1px solid black;"><strong>권한 상승을 해결하기 위한 Windows 커널 모드 드라이버에 대한 보안 업데이트(3136082)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 공격자가 영향받는 시스템에 로그온한 후 특수 제작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-019">MS16-019</a></td>
<td style="border:1px solid black;"><strong>서비스 거부를 해결하기 위한 .NET Framework에 대한 보안 업데이트(3137893) <br />
</strong>이 보안 업데이트는 Microsoft .NET Framework의 취약성을 해결합니다. 이 중에서 보다 심각한 취약성은 공격자가 특수 제작된 XSLT를 클라이언트 쪽 XML 웹 파트에 삽입하는 경우 서비스 거부를 일으키고, 서버가 재귀적으로 XSLT 변환을 컴파일하게 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
서비스 거부</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-020">MS16-020</a></td>
<td style="border:1px solid black;"><strong>서비스 거부를 해결하기 위한 Active Directory Federation Services에 대한 보안 업데이트(3134222) <br />
</strong>이 보안 업데이트는 ADFS(Active Directory Federation Services)의 취약성을 해결합니다. 공격자가 양식 기반 인증 중에 특정 입력 데이터를 ADFS 서버로 보내는 경우 이 취약성으로 인해 서비스 거부가 허용되고, 해당 서버가 응답하지 않게 될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
서비스 거부</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-021">MS16-021</a></td>
<td style="border:1px solid black;"><strong>서비스 거부를 해결하기 위한 NPS RADIUS 서버에 대한 보안 업데이트(3133043) <br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 공격자가 특수 제작된 사용자 이름 문자열을 NPS(네트워크 정책 서버)에 보내는 경우 이 취약성은 NPS에서 서비스 거부가 발생하게 할 수 있고, 이로 인해 NPS에서 RADIUS 인증이 금지될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
서비스 거부</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-022">MS16-022</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player용 보안 업데이트(3135782) <br />
</strong>이 보안 업데이트는 지원되는 모든 버전의 Windows Server 2012, Windows 8.1, Windows Server 2012 R2, Windows RT 8.1 및 Windows 10에 설치된 Adobe Flash Player의 취약성을 해결합니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

악용 가능성 인덱스
------------------

<span id="sectionToggle1"></span>
다음 표에는 이달에 해결된 각 취약성의 악용 가능성 평가가 나와 있습니다. 취약성은 공지 ID 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약성만 포함됩니다.

**이 표를 어떻게 사용합니까?**

이 표를 사용하여 설치해야 할 수 있는 각 보안 업데이트에 대한 보안 공지 발표 후 30일 내 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토하십시오. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/ko-kr/security/cc998259)를 참조하십시오.

아래 열에서 "최신 소프트웨어 릴리스"는 관련 소프트웨어를 나타내며 "이전 소프트웨어 릴리스"는 공지의 "영향받는 소프트웨어" 및 "영향받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 릴리스를 나타냅니다.

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**취약성 제목**

</td>
<td style="border:1px solid black;" colspan="2">
**최신 소프트웨어 릴리스에 대한  
악용 가능성 평가**

</td>
<td style="border:1px solid black;">
**이전 소프트웨어 릴리스에 대한  
악용 가능성 평가**

</td>
<td style="border:1px solid black;">
**서비스 거부  
악용 가능성 평가**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-009: Internet Explorer용 누적 보안 업데이트(3134220)**](https://technet.microsoft.com/ko-kr/library/security/ms16-009)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0041(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0041)

</td>
<td style="border:1px solid black;">
DLL 로드 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0059(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0059)

</td>
<td style="border:1px solid black;">
Internet Explorer 정보 유출 취약성

</td>
<td style="border:1px solid black;" colspan="2">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0060(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0060)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0061(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0061)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0062(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0062)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0063(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0063)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0064(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0064)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0067(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0067)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0068(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0068)

</td>
<td style="border:1px solid black;">
Internet Explorer 권한 상승 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0069(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0069)

</td>
<td style="border:1px solid black;">
Internet Explorer 권한 상승 취약성

</td>
<td style="border:1px solid black;" colspan="2">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0071(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0071)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0072(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0072)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0077(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0077)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 스푸핑 취약성

</td>
<td style="border:1px solid black;" colspan="2">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-011: Microsoft Edge용 누적 보안 업데이트(3134225)**](https://technet.microsoft.com/ko-kr/library/security/ms16-011)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0060(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0060)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0061(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0061)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0062(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0062)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0077(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0077)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 스푸핑 취약성

</td>
<td style="border:1px solid black;" colspan="2">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0080(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0080)

</td>
<td style="border:1px solid black;">
Microsoft Edge ASLR 우회

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0084(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0084)

</td>
<td style="border:1px solid black;">
Microsoft Edge 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-012: 원격 코드 실행을 해결하기 위한 Microsoft Windows PDF Library에 대한 보안 업데이트(3138938)**](https://technet.microsoft.com/ko-kr/library/security/ms16-012)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0046(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0046)

</td>
<td style="border:1px solid black;">
Microsoft Windows 뷰어 취약성

</td>
<td style="border:1px solid black;" colspan="2">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0058(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0058)

</td>
<td style="border:1px solid black;">
Microsoft PDF Library 버퍼 오버플로 취약성

</td>
<td style="border:1px solid black;" colspan="2">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-013: 원격 코드 실행을 해결하기 위한 Windows 필기장에 대한 보안 업데이트(3134811)**](https://technet.microsoft.com/ko-kr/library/security/ms16-013)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0038(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0038)

</td>
<td style="border:1px solid black;">
Windows 필기장 메모리 손상 취약성

</td>
<td style="border:1px solid black;" colspan="2">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-014: 원격 코드 실행을 해결하기 위한 Microsoft Windows에 대한 보안 업데이트(3134228)**](https://technet.microsoft.com/ko-kr/library/security/ms16-014)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0040(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0040)

</td>
<td style="border:1px solid black;">
Windows 권한 상승 취약성

</td>
<td style="border:1px solid black;" colspan="2">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0041(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0041)

</td>
<td style="border:1px solid black;">
DLL 로드 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;" colspan="2">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0042(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0042)

</td>
<td style="border:1px solid black;">
Windows DLL 로드 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0044(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0044)

</td>
<td style="border:1px solid black;">
Windows DLL 로드 서비스 거부 취약성

</td>
<td style="border:1px solid black;" colspan="2">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0049(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0049)

</td>
<td style="border:1px solid black;">
Windows Kerberos 보안 기능 우회

</td>
<td style="border:1px solid black;" colspan="2">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-015: 원격 코드 실행을 해결하기 위한 Microsoft Office에 대한 보안 업데이트(3134226)**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0022(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0022)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0039(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0039)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint XSS 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;" colspan="2">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0052(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0052)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0053(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0053)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0054(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0054)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0055(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0055)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0056(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0056)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-016: 권한 상승을 해결하기 위한 WebDAV에 대한 보안 업데이트(3136041)**](https://technet.microsoft.com/ko-kr/library/security/ms16-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0051(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0051)

</td>
<td style="border:1px solid black;">
WebDAV 권한 상승 취약성

</td>
<td style="border:1px solid black;" colspan="2">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-017: 권한 상승을 해결하기 위한 원격 데스크톱 디스플레이 드라이버에 대한 보안 업데이트(3134700)**](https://technet.microsoft.com/ko-kr/library/security/ms16-017)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0036(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0036)

</td>
<td style="border:1px solid black;">
RDP(원격 데스크톱 프로토콜) 권한 상승 취약성

</td>
<td style="border:1px solid black;" colspan="2">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-018: 권한 상승을 해결하기 위한 Windows 커널 모드 드라이버에 대한 보안 업데이트(3136082)**](https://technet.microsoft.com/ko-kr/library/security/ms16-018)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0048(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0048)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;" colspan="2">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-019: 서비스 거부를 해결하기 위한 .NET Framework에 대한 보안 업데이트(3137893)**](https://technet.microsoft.com/ko-kr/library/security/ms16-019)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0033(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0033)

</td>
<td style="border:1px solid black;">
.NET Framework 스택 오버플로 서비스 거부 취약성

</td>
<td style="border:1px solid black;" colspan="2">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0047(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0047)

</td>
<td style="border:1px solid black;">
Windows Forms 정보 유출 취약성

</td>
<td style="border:1px solid black;" colspan="2">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-020: 서비스 거부를 해결하기 위한 Active Directory Federation Services에 대한 보안 업데이트(3134222)**](https://technet.microsoft.com/ko-kr/library/security/ms16-020)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0037(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0037)

</td>
<td style="border:1px solid black;">
Microsoft Active Directory Federation Services 서비스 거부 취약성

</td>
<td style="border:1px solid black;" colspan="2">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-021: 서비스 거부를 해결하기 위한 NPS RADIUS 서버에 대한 보안 업데이트(3133043)**](https://technet.microsoft.com/ko-kr/library/security/ms16-021)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0050(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0050)

</td>
<td style="border:1px solid black;">
네트워크 정책 서버 RADIUS 구현의 서비스 거부 취약성

</td>
<td style="border:1px solid black;" colspan="2">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-022: Adobe Flash Player용 보안 업데이트(3135782)**](https://technet.microsoft.com/ko-kr/library/security/ms16-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-04](https://helpx.adobe.com/kr/security/products/flash-player/apsb16-04.html)

</td>
<td style="border:1px solid black;">
취약성 심각도 및 업데이트 우선 순위 등급은 [Adobe 보안 공지 APSB16-04](https://helpx.adobe.com/kr/security/products/flash-player/apsb16-04.html)를 참조하십시오.

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 

영향받는 소프트웨어
-------------------

<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.

**참고** 단일 취약성에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 ID로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

 

### Windows 운영 체제 및 구성 요소(표 1/2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/ko-kr/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/ko-kr/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/ko-kr/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/ko-kr/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/ko-kr/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/ko-kr/library/security/ms16-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3115858)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3126587)  
(중요)  
Windows Vista 서비스 팩 2  
(3126593)  
(중요)  
Windows Vista 서비스 팩 2  
(3126041)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3124280)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3115858)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3126587)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(3126593)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(3126041)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3124280)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/ko-kr/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/ko-kr/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/ko-kr/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/ko-kr/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/ko-kr/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/ko-kr/library/security/ms16-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3115858)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3126587)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3126593)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3126041)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3124280)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3115858)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3126587)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3126593)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3126041)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3124280)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3126587)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3126593)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3126041)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/ko-kr/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/ko-kr/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/ko-kr/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/ko-kr/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/ko-kr/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/ko-kr/library/security/ms16-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3115858)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3126587)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3126593)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3124280)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3115858)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3126587)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3126593)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3124280)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/ko-kr/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/ko-kr/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/ko-kr/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/ko-kr/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/ko-kr/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/ko-kr/library/security/ms16-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3115858)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3126587)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3126593)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3124280)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3126587)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3126593)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/ko-kr/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/ko-kr/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/ko-kr/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/ko-kr/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/ko-kr/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/ko-kr/library/security/ms16-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3123294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3115858)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3126587)  
(중요)  
Windows 8.1(32비트 시스템용)  
(3126593)  
(중요)  
Windows 8.1(32비트 시스템용)  
(3126041)  
(중요)  
Windows 8.1(32비트 시스템용)  
(3126434)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3124280)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3123294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3115858)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3126587)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(3126593)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(3126041)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(3126434)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3124280)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/ko-kr/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/ko-kr/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/ko-kr/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/ko-kr/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/ko-kr/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/ko-kr/library/security/ms16-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3134814)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3123294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3115858)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3126587)  
(중요)  
Windows Server 2012  
(3126593)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3124280)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3123294)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3115858)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3126587)  
(중요)  
Windows Server 2012 R2  
(3126593)  
(중요)  
Windows Server 2012 R2  
(3126041)  
(중요)  
Windows Server 2012 R2  
(3126434)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3124280)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/ko-kr/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/ko-kr/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/ko-kr/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/ko-kr/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/ko-kr/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/ko-kr/library/security/ms16-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3126587)  
(중요)  
Windows RT 8.1  
(3126593)  
(중요)  
Windows RT 8.1  
(3126434)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3124280)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/ko-kr/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/ko-kr/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/ko-kr/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/ko-kr/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/ko-kr/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/ko-kr/library/security/ms16-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135174)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135174)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3135174)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3135174)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3135174)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3135174)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135174)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135174)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3135174)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3135174)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3135174)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3135174)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135173)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135173)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3135173)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3135173)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3135173)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135173)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135173)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3135173)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3135173)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3135173)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/ko-kr/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/ko-kr/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/ko-kr/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/ko-kr/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/ko-kr/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/ko-kr/library/security/ms16-016)

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
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3126587)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3126593)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3126041)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3126587)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3126593)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3126041)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3126587)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3126593)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3126587)  
(중요)  
Windows Server 2012(Server Core 설치)  
(3126593)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3123294)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3126587)  
(중요)  
Windows Server 2012 R2(Server Core 설치)  
(3126593)  
(중요)  
Windows Server 2012 R2(Server Core 설치)  
(3126041)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 
 

### Windows 운영 체제 및 구성 요소(표 2/2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/ko-kr/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/ko-kr/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/ko-kr/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/ko-kr/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/ko-kr/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/ko-kr/library/security/ms16-022)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3122646)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3127219)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(중요)  
Microsoft .NET Framework 4.6  
(3122661)  
(중요)  
Microsoft .NET Framework 4.6  
(3127233)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3122646)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3127219)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(중요)  
Microsoft .NET Framework 4.6  
(3122661)  
(중요)  
Microsoft .NET Framework 4.6  
(3127233)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/ko-kr/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/ko-kr/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/ko-kr/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/ko-kr/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/ko-kr/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/ko-kr/library/security/ms16-022)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3122646)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3127219)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(중요)  
Microsoft .NET Framework 4.6  
(3122661)  
(중요)  
Microsoft .NET Framework 4.6  
(3127233)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3133043)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3122646)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3127219)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(중요)  
Microsoft .NET Framework 4.6  
(3122661)  
(중요)  
Microsoft .NET Framework 4.6  
(3127233)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3133043)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3122646)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(3127219)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/ko-kr/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/ko-kr/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/ko-kr/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/ko-kr/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/ko-kr/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/ko-kr/library/security/ms16-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3126446)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3126446)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/ko-kr/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/ko-kr/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/ko-kr/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/ko-kr/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/ko-kr/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/ko-kr/library/security/ms16-022)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3133043)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/ko-kr/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/ko-kr/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/ko-kr/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/ko-kr/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/ko-kr/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/ko-kr/library/security/ms16-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3126446)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(중요)  
Microsoft .NET Framework 3.5  
(3127222)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3126446)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(중요)  
Microsoft .NET Framework 3.5  
(3127222)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/ko-kr/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/ko-kr/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/ko-kr/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/ko-kr/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/ko-kr/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/ko-kr/library/security/ms16-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3126446)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122649)  
(중요)  
Microsoft .NET Framework 3.5  
(3127221)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122655)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127227)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3122658)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3127230)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3133043)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3126446)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(중요)  
Microsoft .NET Framework 3.5  
(3127222)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(중요)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 3.0  
(3134222)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3133043)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/ko-kr/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/ko-kr/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/ko-kr/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/ko-kr/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/ko-kr/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/ko-kr/library/security/ms16-022)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3122654)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/ko-kr/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/ko-kr/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/ko-kr/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/ko-kr/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/ko-kr/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/ko-kr/library/security/ms16-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3135174)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3135174)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135174)  
(중요)  
Microsoft .NET Framework 4.6  
(3135174)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3135174)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3135174)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135174)  
(중요)  
Microsoft .NET Framework 4.6  
(3135174)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3135173)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135173)  
(중요)  
Microsoft .NET Framework 4.6.1  
(3135173)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3135173)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135173)  
(중요)  
Microsoft .NET Framework 4.6.1  
(3135173)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/ko-kr/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/ko-kr/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/ko-kr/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/ko-kr/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/ko-kr/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/ko-kr/library/security/ms16-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3133043)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3133043)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3133043)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3126446)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122649)  
(중요)  
Microsoft .NET Framework 3.5  
(3127221)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122655)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127227)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3122658)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3127230)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3133043)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3126446)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3134214)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(중요)  
Microsoft .NET Framework 3.5  
(3127222)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(중요)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 3.0  
(3134222)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3133043)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 
 

### Microsoft Office 제품군 및 소프트웨어

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(3114742)  
(중요)  
Microsoft Excel 2007 서비스 팩 3  
(3114741)  
(중요)  
Microsoft Word 2007 서비스 팩 3  
(3114748)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3114752)  
(중요)  
Microsoft Excel 2010 서비스 팩 2(32비트 버전)  
(3114759)  
(중요)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(3114755)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3114752)  
(중요)  
Microsoft Excel 2010 서비스 팩 2(64비트 버전)  
(3114759)  
(중요)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(3114755)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 서비스 팩 1(32비트 버전)  
(3114734)  
(중요)  
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(3114724)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 서비스 팩 1(64비트 버전)  
(3114734)  
(중요)  
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(3114724)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT 서비스 팩 1  
(3114734)  
(중요)  
Microsoft Word 2013 RT 서비스 팩 1  
(3114724)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016(32비트 버전)  
(3114698)  
(중요)  
Microsoft Word 2016(32비트 버전)  
(3114702)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016(64비트 버전)  
(3114698)  
(중요)  
Microsoft Word 2016(64비트 버전)  
(3114702)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3137721)  
(중요)  
Microsoft Word for Mac 2011  
(3137721)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3134241)  
(중요)  
Microsoft Word 2016 for Mac  
(3134241)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**기타 Office 소프트웨어**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3114548)  
(중요)  
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3114745)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114747)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114773)  
(중요)

</td>
</tr>
</table>
 
**MS16-015 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

### Microsoft Office Services 및 Web Apps

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 버전)

</td>
<td style="border:1px solid black;">
Excel Services  
(3114432)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 버전)

</td>
<td style="border:1px solid black;">
Excel Services  
(3114432)  
(중요)

</td>
</tr>
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
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3114401)  
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
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Excel Services  
(3114335)  
(중요)  
Word Automation Services  
(3114481)  
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
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2  
(3114407)  
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
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1  
(3114338)  
(중요)

</td>
</tr>
</table>
 
**MS16-015 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

### Microsoft Server 소프트웨어

 
<table style="border:1px solid black;">
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
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1  
(3039768)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/ko-kr/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**  

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 서비스 팩 1  
(3114733)  
(중요)

</td>
</tr>
</table>
 
**MS16-015 참고 사항**

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
Microsoft는 신뢰할 수 있는 취약성 공개를 통해 고객을 보호하는 데 도움을 주는 보안 커뮤니티의 공로를 기립니다. 자세한 내용은 [감사의 말](https://technet.microsoft.com/ko-kr/library/security/dn903755.aspx)(영문)을 참조하십시오.

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

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약성 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://technet.microsoft.com/ko-kr/security/dn467918)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://technet.microsoft.com/ko-kr/library/bb466251.aspx)(영문)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 모범 사례와 관련한 추가 정보를 제공합니다.

**기타 보안 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 제공됩니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/ko-kr/download/search.aspx?q=security%20update)에서 제공됩니다. "보안 업데이트"라는 키워드 검색을 수행하면 가장 쉽게 찾을 수 있습니다.
-   소비자 플랫폼용 업데이트는 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)에서 제공됩니다.
-   이달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 긴급 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/ko-kr/kb/913086)을 참조하십시오.

**IT 전문가 보안 커뮤니티**

[IT 전문가 보안 커뮤니티](http://technet.microsoft.com/ko-kr/security/cc136632.aspx)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 알아보고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향받는 소프트웨어는 테스트를 거쳐 영향받는 버전이 확인되었습니다. 다른 버전은 지원 주기가 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 주기를 확인하려면 [Microsoft 지원 주기](https://support.microsoft.com/ko-kr/lifecycle)를 참조하십시오.

IT 전문가용 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/ko-kr/security/bb980617)

Windows 컴퓨터를 바이러스 및 맬웨어로부터 보호: [바이러스 솔루션 및 보안 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ko)

지역별 지원 정보: [국가별 지원](http://support.microsoft.com/common/international.aspx?ln=ko)

### 고지 사항

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성과 특정 목적에 대한 적합성의 보증을 포함하여 명시적이거나 묵시적인 모든 보증을 부인합니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한이 적용되지 않을 수도 있습니다.

### 수정 내역

-   V1.0(2016년 2월 10일): 공지 요약이 게시되었습니다.
-   V2.0(2016년 2월 11일): MS16-014에서는 Microsoft Windows Vista, Windows Server 2008, Windows Server 2008(Itanium 기반 시스템용), Windows 8.1 및 Windows Server 2012 R2에 대한 업데이트 3126041을 사용할 수 있음을 알리기 위해 보안 공지가 개정되었습니다. 고객은 이 공지에 나오는 취약성으로부터 보호를 받기 위해 해당되는 업데이트를 적용해야 합니다. 대다수의 고객은 자동 업데이트를 사용하고 있기 때문에 따로 조치를 취할 필요가 없습니다. 이 업데이트가 자동으로 다운로드되고 설치됩니다. MS16-021에서는 CVE-2016-0050에 대한 악용 가능성 평가가 수정되었습니다.
-   V3.0(2016년 2월 17일): MS16-015에서는 2016년 2월 17일부터 사용 가능한 Microsoft Office 2016 for Mac에 대한 3134241 업데이트 및 Microsoft Office for Mac 2011에 대한 3137721 업데이트가 추가되었습니다. 자세한 내용은 [Microsoft 기술 자료 문서 3134241](https://support.microsoft.com/ko-kr/kb/3134241) 및 [Microsoft 기술 자료 문서 3137721](https://support.microsoft.com/ko-kr/kb/3137721)을 참조하십시오.
-   V3.1(2016년 2월 25일): MS16-014에 대한 요약 표에 알려진 문제 참조가 추가되었습니다. 자세한 내용은 [Microsoft 기술 자료 문서 3126041](https://support.microsoft.com/ko-kr/kb/3126041)을 참조하십시오. 해결 방법이 포함된 두 번째 알려진 문제가 [Microsoft 기술 자료 문서 3126587](https://support.microsoft.com/ko-kr/kb/3126587)에 추가되었습니다.

*2016-02-24 13:45-08:00에 페이지가 생성되었습니다.*
