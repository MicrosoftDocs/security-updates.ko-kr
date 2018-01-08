---
TOCTitle: 'MS16-NOV'
Title: 2016년 11월 Microsoft 보안 공지 요약
ms:assetid: 'ms16-nov'
ms:contentKeyID: 74240672
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms16-nov(v=Security.10)'
---


2016년 11월 Microsoft 보안 공지 요약
====================================

게시된 날짜: 2016년 11월 8일 화요일

**버전:** 1.0

이 공지 요약 목록에는 2016년 11월에 발표된 보안 공지가 포함되어 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 절을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향받는 소프트웨어에 대한 자세한 내용은 **영향받는 소프트웨어**라는 다음 절을 참조하십시오.

<p> </p>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830431">MS16-129</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge용 누적 보안 업데이트(3199057)<br />
</strong>이 보안 업데이트는 Microsoft Edge의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Microsoft Edge를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 고객은 관리자 권한이 있는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833191">MS16-130</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows용 보안 업데이트(3199172)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 로컬에서 인증된 공격자가 특수 제작된 응용 프로그램을 실행하는 경우 원격 코드 실행을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a>  <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833189">MS16-131</a></td>
<td style="border:1px solid black;"><strong>Microsoft 비디오 컨트롤용 보안 업데이트(3199151)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. Microsoft 비디오 컨트롤이 메모리에서 개체를 적절하게 처리하지 못하는 경우 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 하지만 공격자는 사용자가 특수 제작된 파일 또는 웹 페이지나 전자 메일 메시지의 프로그램을 열도록 먼저 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830425">MS16-132</a></td>
<td style="border:1px solid black;"><strong>Microsoft 그래픽 구성 요소용 보안 업데이트(3199120)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 악의적인 웹 페이지를 방문할 때 Windows Animation Manager가 메모리에서 개체를 부적절하게 처리하는 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성의 악용에 성공한 공격자는 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833188">MS16-133</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office용 보안 업데이트(3199168)<br />
</strong>이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 Microsoft Office 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Office Services 및 Web Apps</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=828018">MS16-134</a></td>
<td style="border:1px solid black;"><strong>공용 로그 파일 시스템 드라이버용 보안 업데이트(3193706)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 Windows CLFS(공용 로그 파일 시스템) 드라이버가 메모리에서 개체를 부적절하게 처리하는 경우 권한 상승이 허용될 수 있습니다. 로컬 공격 시나리오에서 공격자는 특수 제작된 응용 프로그램을 실행하여 영향받는 시스템을 완전히 제어함으로써 이러한 취약성을 악용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 관리자 권한 컨텍스트에서 프로세스를 실행할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830428">MS16-135</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버용 보안 업데이트(3199135)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이러한 취약성 중 가장 위험한 취약성으로 인해 공격자가 영향받는 시스템에 로그온하여 취약성을 악용하고 영향받는 시스템을 제어할 수 있는 특수 제작된 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830963">MS16-136</a></td>
<td style="border:1px solid black;"><strong>SQL Server용 보안 업데이트(3199641)<br />
</strong>이 보안 업데이트는 Microsoft SQL Server의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 공격자가 데이터를 보거나 변경하거나 삭제하거나, 새 계정을 만들 수 있는 상승된 권한을 얻도록 허용할 수 있습니다. 이 보안 업데이트는 SQL Server가 포인터 캐스팅을 처리하는 방식을 수정하여 이와 같은 가장 심각한 취약성을 해결합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833192">MS16-137</a></td>
<td style="border:1px solid black;"><strong>Windows 인증 방법용 보안 업데이트(3199173)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 권한 상승을 허용할 수 있습니다. 이 취약성을 악용하려는 공격자는 먼저 유효한 사용자 자격 증명을 사용하여 도메인에 가입된 대상 시스템에 대한 인증을 거쳐야 합니다. 이 취약성을 성공적으로 악용한 공격자는 자신의 권한을 권한 없는 사용자에서 관리자로 상승시킬 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 새 계정을 만들 수 있습니다. 그런 다음 NTLM 암호 변경 요청을 조작하도록 설계된 특수 제작 응용 프로그램을 로컬로 실행하여 권한 상승을 시도할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830965">MS16-138</a></td>
<td style="border:1px solid black;"><strong>Microsoft 가상 하드 디스크 드라이버 보안 업데이트(3199647)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. Windows 가상 하드 디스크 드라이버가 특정 파일에 대한 사용자 액세스를 부적절하게 처리합니다. 공격자는 이 취약성을 악용하여 사용자에게 제공되어서는 안 되는 위치의 파일을 조작할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830965">MS16-139</a></td>
<td style="border:1px solid black;"><strong>Windows 커널용 보안 업데이트(3199720)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 공격자가 특수 제작된 응용 프로그램을 실행하여 중요한 정보에 액세스하면 권한 상승이 허용될 수 있습니다. 로컬에서 인증된 공격자는 특수 제작된 응용 프로그램을 실행하여 이 취약성을 악용하려 시도할 수 있습니다. 공격자는 이 방법을 통해 사용자에게 제공되어서는 안 되는 정보에 액세스할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827857">MS16-140</a></td>
<td style="border:1px solid black;"><strong>부팅 관리자용 보안 업데이트(3193479)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성은 실제로 존재하는 공격자가 영향을 받는 부팅 정책을 설치하는 경우 보안 기능 우회를 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834404">MS16-141</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player용 보안 업데이트(3202790)<br />
</strong>이 보안 업데이트는 지원되는 모든 버전의 Windows 8.1, Windows Server 2012, Windows Server 2012 R2, Windows RT 8.1, Windows 10 및 Windows Server 2016.에 설치된 Adobe Flash Player의 취약성을 해결합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830372">MS16-142</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3198467)<br />
</strong>이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우 공격자가 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
</tbody>
</table>
 

악용 가능성 인덱스
------------------

<span id="sectionToggle1"></span>
다음 표에는 이달에 해결된 각 취약성의 악용 가능성 평가가 나와 있습니다. 취약성은 공지 ID, CVE ID 순으로 나열되어 있습니다. 공지에서 심각도 등급이 긴급 또는 중요인 취약성만 포함되어 있습니다.

**이 표를 어떻게 사용합니까?**

이 표를 사용하여 설치해야 할 수 있는 각 보안 업데이트에 대한 보안 공지 발표 후 30일 내 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토하십시오. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/ko-kr/security/cc998259)를 참조하십시오.

아래 열에서 "최신 소프트웨어 릴리스"는 관련 소프트웨어를 나타내며 "이전 소프트웨어 릴리스"는 공지의 "영향받는 소프트웨어" 및 "영향받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 릴리스를 나타냅니다.

<p> </p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**취약성 제목**

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-129: Microsoft Edge용 누적 보안 업데이트(3199057)**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7195(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7195)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7196(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7196)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7198(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7198)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7199(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7199)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

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
[CVE-2016-7200(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7200)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7201(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7201)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7202(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7202)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

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
[CVE-2016-7203(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7203)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7204(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7204)

</td>
<td style="border:1px solid black;">
Microsoft Edge 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

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
[CVE-2016-7208(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7208)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7209(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7209)

</td>
<td style="border:1px solid black;">
Microsoft Edge 스푸핑 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

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
[CVE-2016-7227(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7227)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

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
[CVE-2016-7239(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7239)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7240(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7240)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7241(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7241)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7242(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7242)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7243(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7243)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-130: Microsoft Windows용 보안 업데이트(3199172)**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7212(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7212)

</td>
<td style="border:1px solid black;">
Windows 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7221(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7221)

</td>
<td style="border:1px solid black;">
Windows IME 커널 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7222(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7222)

</td>
<td style="border:1px solid black;">
작업 스케줄러 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-131: Microsoft 비디오 컨트롤용 보안 업데이트(3199151)**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7248(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-cve-2016-7248)

</td>
<td style="border:1px solid black;">
Microsoft 비디오 컨트롤용 보안 업데이트

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-132: Microsoft 그래픽 구성 요소용 보안 업데이트(3199120)**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7205(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7205)

</td>
<td style="border:1px solid black;">
Windows Animation Manager 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7210(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7210)

</td>
<td style="border:1px solid black;">
오픈타입 글꼴 정보 유출 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7217(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7217)

</td>
<td style="border:1px solid black;">
미디어 파운데이션 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7256(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7256)

</td>
<td style="border:1px solid black;">
오픈타입 글꼴 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-133: Microsoft Office용 보안 업데이트(3199168)**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7213(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7213)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7228(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7228)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7229(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7229)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7230(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7230)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7231(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7231)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7232(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7232)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7233(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7233)

</td>
<td style="border:1px solid black;">
Microsoft Office 정보 유출 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7234(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7234)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7235(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7235)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7236(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7236)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7244(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7244)

</td>
<td style="border:1px solid black;">
Microsoft Office 서비스 거부 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

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
[CVE-2016-7245(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7245)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-134: 공용 로그 파일 시스템 드라이버용 보안 업데이트(3193706)**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0026(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0026)

</td>
<td style="border:1px solid black;">
Windows CLFS 커널 권한 상승

</td>
<td style="border:1px solid black;">
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
[CVE-2016-3332(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3332)

</td>
<td style="border:1px solid black;">
Windows 공용 로그 파일 시스템 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-3333(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3333)

</td>
<td style="border:1px solid black;">
Windows 공용 로그 파일 시스템 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-3334(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3334)

</td>
<td style="border:1px solid black;">
Windows 공용 로그 파일 시스템 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-3335(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3335)

</td>
<td style="border:1px solid black;">
Windows 공용 로그 파일 시스템 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-3338(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3338)

</td>
<td style="border:1px solid black;">
Windows 공용 로그 파일 시스템 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-3340(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3340)

</td>
<td style="border:1px solid black;">
Windows 공용 로그 파일 시스템 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-3342(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3342)

</td>
<td style="border:1px solid black;">
Windows 공용 로그 파일 시스템 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-3343(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3343)

</td>
<td style="border:1px solid black;">
Windows 공용 로그 파일 시스템 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7184(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7184)

</td>
<td style="border:1px solid black;">
Windows CLFS 커널 권한 상승

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-135: Windows 커널 모드 드라이버용 보안 업데이트(3199135)**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7214(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7214)

</td>
<td style="border:1px solid black;">
Win32k 정보 유출 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7215(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7215)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
[CVE-2016-7218(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7218)

</td>
<td style="border:1px solid black;">
Bowser.sys 정보 유출 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7246(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7246)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7255(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7255)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-136: SQL Server용 보안 업데이트(3199641)**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7249(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7249)

</td>
<td style="border:1px solid black;">
SQL RDBMS 엔진 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7250(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7250)

</td>
<td style="border:1px solid black;">
SQL RDBMS 엔진 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7251(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7251)

</td>
<td style="border:1px solid black;">
MDS API XSS 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7252(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7252)

</td>
<td style="border:1px solid black;">
SQL Analysis Services 정보 유출 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7253(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7253)

</td>
<td style="border:1px solid black;">
SQL Server 에이전트 권한 상승 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

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
[CVE-2016-7254(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7254)

</td>
<td style="border:1px solid black;">
SQL RDBMS 엔진 EoP 취약성

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-137:Windows 인증 방법용 보안 업데이트(3199173)**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7220(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7220)

</td>
<td style="border:1px solid black;">
가상 보안 모드 정보 유출 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7237(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7237)

</td>
<td style="border:1px solid black;">
로컬 보안 기관 하위 시스템 서비스 서비스 거부 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7238(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7238)

</td>
<td style="border:1px solid black;">
Windows NTLM 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-138: Microsoft 가상 하드 디스크 드라이버 보안 업데이트(3199647)**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7223(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7223)

</td>
<td style="border:1px solid black;">
VHDFS 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7224(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7224)

</td>
<td style="border:1px solid black;">
VHDFS 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7225(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7225)

</td>
<td style="border:1px solid black;">
VHDFS 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7226(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7226)

</td>
<td style="border:1px solid black;">
VHDFS 드라이버 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-139: Windows 커널용 보안 업데이트(3199720)**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7216(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7216)

</td>
<td style="border:1px solid black;">
Windows 커널 권한 상승 취약성

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-140: 부팅 관리자용 보안 업데이트(3193479)**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7247(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7247)

</td>
<td style="border:1px solid black;">
보안 부팅 보안 기능 우회 취약성

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-141: Adobe Flash Player용 보안 업데이트(3202790)**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-37](http://helpx.adobe.com/kr/security/products/flash-player/apsb16-37.html)

</td>
<td style="border:1px solid black;">
취약성 심각도 및 업데이트 우선 순위 등급은 Adobe 보안 공지 [APSB16-37](http://helpx.adobe.com/kr/security/products/flash-player/apsb16-37.html)를 참조하십시오.

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-142: Internet Explorer용 누적 보안 업데이트(3198467)**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7239(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7239)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7227(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7227)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7198(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7198)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7199(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7199)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7195(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7195)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7196(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7196)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
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
[CVE-2016-7241(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7241)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

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

### Windows 운영 체제 및 구성 요소(표 1/3)

<p> </p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3193418)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3198218)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3198195)  
(중요)

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
(3193418)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3198218)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3198195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3193418)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3198195)  
(중요)

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
(3193418)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3198195)  
(중요)

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
(3193418)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3198195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197867)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197867)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197867)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197868)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197868)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197868)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197867)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197867)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197868)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197868)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3197873)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3197873)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3197874)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3197874)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3197873)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3197873)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3197874)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3197874)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197876)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197876)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197877)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197877)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197873)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197873)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197874)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197874)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1<span></span>
(3197874)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1<span></span>
(3197874)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1<span></span>
(3197874)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3198585)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3198585)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3198585)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3198585)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3198585)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3198585)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3198585)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3198585)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3198585)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3198585)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3198586)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3198586)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3198586)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3198586)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3198586)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3198586)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3198586)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3198586)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3198586)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3198586)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(3200970)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(3200970)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(3200970)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(3200970)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(3200970)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3200970)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3200970)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3200970)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)<span></span>
(3200970)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(3200970)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(3200970)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3193418)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3193418)  
(중요)

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
Windows Server 2008(x86비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3193418)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x86비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3193418)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3197867)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3197867)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3197868)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3197868)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3197876)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3197876)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3197877)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3197877)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3197873)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3197873)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3197874)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3197874)  
(긴급)

</td>
</tr>
</table>
 
### Windows 운영 체제 및 구성 요소(표 2/3)

<p> </p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;" colspan="2">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Vista 서비스 팩 2  
(3181707)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Vista 서비스 팩 2  
(3193418)  
(중요)  
Windows Vista 서비스 팩 2  
(3194371)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Vista 서비스 팩 2  
(3198510)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3198483)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Vista x64 Edition 서비스 팩 2  
(3181707)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Vista x64 Edition 서비스 팩 2  
(3193418)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(3194371)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Vista x64 Edition 서비스 팩 2  
(3198510)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3198483)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;" colspan="2">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3181707)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3193418)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3194371)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3198510)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3198483)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3181707)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3193418)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3194371)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3198510)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3198483)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3181707)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3193418)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3194371)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3198510)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3198483)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;" colspan="2">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;" colspan="2">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;" colspan="2">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;" colspan="2">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;" colspan="2">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;" colspan="2">
Windows 8.1(32비트 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1(32비트 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 8.1(32비트 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1(32비트 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows 8.1(32비트 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1(32비트 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 8.1(32비트 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1(32비트 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;" colspan="2">
Windows 8.1(x64 기반 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1(x64 기반 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 8.1(x64 기반 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1(x64 기반 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows 8.1(x64 기반 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1(x64 기반 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 8.1(x64 기반 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1(x64 기반 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;" colspan="2">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
보안 전용

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012  
(3197876)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197876)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012  
(3197876)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197876)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012  
(3197877)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197877)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012  
(3197877)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197877)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
보안 전용

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;" colspan="2">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows RT 8.1  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows RT 8.1  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows RT 8.1  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;" colspan="2">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10(32비트 시스템용)  
(3198585)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10(32비트 시스템용)  
(3198585)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10(32비트 시스템용)  
(3198585)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10(32비트 시스템용)  
(3198585)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10(x64 기반 시스템용)  
(3198585)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10(x64 기반 시스템용)  
(3198585)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10(x64 기반 시스템용)  
(3198585)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10(x64 기반 시스템용)  
(3198585)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10 버전 1511(32비트 시스템용)  
(3198586)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 버전 1511(32비트 시스템용)  
(3198586)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10 버전 1511(32비트 시스템용)  
(3198586)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 버전 1511(32비트 시스템용)  
(3198586)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10 버전 1511(x64 기반 시스템용)  
(3198586)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 버전 1511(x64 기반 시스템용)  
(3198586)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10 버전 1511(x64 기반 시스템용)  
(3198586)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 버전 1511(x64 기반 시스템용)  
(3198586)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10 버전 1607(32비트 시스템용)  
(3200970)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 버전 1607(32비트 시스템용)  
(3200970)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10 버전 1607(32비트 시스템용)  
(3200970)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 버전 1607(32비트 시스템용)  
(3200970)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10 버전 1607(x64 기반 시스템용)<span></span>
(3200970)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 버전 1607(x64 기반 시스템용)<span></span>
(3200970)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10 버전 1607(x64 기반 시스템용)<span></span>
(3200970)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 버전 1607(x64 기반 시스템용)<span></span>
(3200970)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**공지 ID**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**전체 심각도**

</td>
<td style="border:1px solid black;" colspan="2">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Windows Server 2016(x64 기반 시스템용)

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2016(x64 기반 시스템용)  
(3200970)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2016(x64 기반 시스템용)  
(3200970)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(3200970)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2016(x64 기반 시스템용)  
(3200970)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16**-138](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;" colspan="2">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008(32비트 시스템용) 서비스 팩 2<span></span>(Server Core 설치)  
(3181707)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008(32비트 시스템용) 서비스 팩 2<span></span>(Server Core 설치)  
(3198234)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008(32비트 시스템용) 서비스 팩 2<span></span>(Server Core 설치)  
(3190847)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3196718)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2<span></span>(Server Core 설치)  
(3181707)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2<span></span>(Server Core 설치)  
(3198234)  
(중요)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2<span></span>(Server Core 설치)  
(3190847)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3196718)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1<span></span>(Server Core 설치)  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1<span></span>(Server Core 설치)  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1<span></span>(Server Core 설치)  
(3197867)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1<span></span>(Server Core 설치)  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1<span></span>(Server Core 설치)  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1<span></span>(Server Core 설치)  
(3197868)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012<span></span>(Server Core 설치)  
(3197876)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012<span></span>(Server Core 설치)  
(3197876)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012<span></span>(Server Core 설치)  
(3197876)  
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
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012<span></span>(Server Core 설치)  
(3197877)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012<span></span>(Server Core 설치)  
(3197877)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012<span></span>(Server Core 설치)  
(3197877)  
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
보안 전용

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2<span></span>(Server Core 설치)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2<span></span>(Server Core 설치)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2<span></span>(Server Core 설치)  
(3197873)  
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
월별 롤업

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2<span></span>(Server Core 설치)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
해당 없음

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2<span></span>(Server Core 설치)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2<span></span>(Server Core 설치)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 


### Windows 운영 체제 및 구성 요소(표 3/3)

<p> </p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;" colspan="2">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;" colspan="2">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://catalog.update.microsoft.com/v7/site/search.aspx?q=kb3193418)  
(3193418)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://catalog.update.microsoft.com/v7/site/search.aspx?q=kb3193418)  
(3193418)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://catalog.update.microsoft.com/v7/site/search.aspx?q=kb3193418)  
(3193418)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;" colspan="2">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197867)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197868)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197867)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197868)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;" colspan="2">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197867)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197868)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197873)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197874)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197873)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197874)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
**보통**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197876)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3197876)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197877)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3197877)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197873)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(보통)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197874)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=832634)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3198585)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198585)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3198585)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198585)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3198586)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198586)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3198586)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198586)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(3200970)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3200970)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)<span></span>
(3200970)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3200970)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;" colspan="2">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(3200970)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
**없음**

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
Windows Server 2008(32비트 시스템용) 서비스 팩 2<span></span>(Server Core 설치)  
(3190847)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2<span></span>(Server Core 설치)  
(3190847)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1<span></span>(Server Core 설치)  
(3197867)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1<span></span>(Server Core 설치)  
(3197868)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012<span></span>(Server Core 설치)  
(3197876)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012<span></span>(Server Core 설치)  
(3197877)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2<span></span>(Server Core 설치)  
(3197873)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2<span></span>(Server Core 설치)  
(3197874)  
(중요)

</td>
<td style="border:1px solid black;" colspan="2">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 
### Microsoft Office 제품군 및 소프트웨어

<p> </p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2007**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 서비스 팩 3  
(3118395)  
(중요)  
Microsoft Word 2007  
(3127949)  
(중요)  
Microsoft Office 2007 서비스 팩 3  
(3118396)  
(중요)  
Microsoft Office 2007 서비스 팩 3  
(2986253)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2010**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3127951)  
(중요)  
Microsoft Excel 2010 서비스 팩 2(32비트 버전)  
(3118390)  
(중요)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(3127953)  
(중요)  
Microsoft PowerPoint 2010 서비스 팩 2(32비트 버전)  
(3118378)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3115120)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3127951)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3127951)  
(중요)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(3127953)  
(중요)  
Microsoft PowerPoint 2010 서비스 팩 2(64비트 버전)  
(3118378)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3115120)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2013**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 서비스 팩 1(32비트 버전)  
(3127921)  
(중요)  
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(3115153)  
(중요)  
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(3127932)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 서비스 팩 1(64비트 버전)  
(3127921)  
(중요)  
Microsoft Office 2013 서비스 팩 1(64비트 버전)  
(3115153)  
(중요)  
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(3127932)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2013 RT**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT 서비스 팩 1  
(3127921)  
(중요)  
Microsoft Office 2013 RT 서비스 팩 1  
(3115153)  
(중요)  
Microsoft Word 2013 RT 서비스 팩 1  
(3127932)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2016**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016(32비트 버전)  
(3127904)  
(중요)  
Microsoft Office 2016(32비트 버전)  
(3115135)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016(64비트 버전)  
(3127904)  
(중요)  
Microsoft Office 2016(64비트 버전)  
(3115135)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office for Mac 2011**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3198807)  
(중요)  
Microsoft Word for Mac 2011  
(3198807)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3198798)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
기타 Office 소프트웨어

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3127889)  
(중요)  
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3127948)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3127893)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer  
(3118382)  
(중요)

</td>
</tr>
</table>
 
 

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
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3118381)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3127950)  
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
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3127927)  
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
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2  
(3127954)  
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
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1  
(3127929)  
(중요)

</td>
</tr>
</table>
 
 

### Microsoft SQL Server

<p> </p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012 서비스 팩 2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2012(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012(x64 기반 시스템용) 서비스 팩 2  
(GDR)  
(3194719)  
(중요)  
Microsoft SQL Server 2012(x64 기반 시스템용) 서비스 팩 2  
(3194725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012 서비스 팩 3**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2012(x64 기반 시스템용) 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012(x64 기반 시스템용) 서비스 팩 3  
(GDR)  
(3194721)  
(중요)  
Microsoft SQL Server 2012(x64 기반 시스템용) 서비스 팩 3  
(3194724)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014 서비스 팩 1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2014(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2014 서비스 팩 1(x64 기반 시스템용)  
(GDR)  
(3194720)  
(중요)  
Microsoft SQL Server 2014 서비스 팩 1(x64 기반 시스템용)  
(3194722)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014 서비스 팩 2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2014(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2014 서비스 팩 2(x64 기반 시스템용)  
(3194714)  
(중요)  
Microsoft SQL Server 2014 서비스 팩 2(x64 기반 시스템용)  
(3194718)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2016(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2016(x64 기반 시스템용)  
(GDR)  
(3194716)  
(중요)  
Microsoft SQL Server 2016(x64 기반 시스템용)  
(3194717)  
(중요)

</td>
</tr>
</table>
 

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
Microsoft는 신뢰할 수 있는 취약성 공개를 통해 고객을 보호하는 데 도움을 주는 보안 커뮤니티의 공로를 기립니다. 자세한 내용은 [감사의 말](https://technet.microsoft.com/ko-kr/library/security/mt674627.aspx)(영문)을 참조하십시오.

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 보안 공지에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services 및 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 릴리스에서 제공되지 않습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft Update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/ko-kr/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services용으로 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/ko-kr/wsus/bb456965)(영문). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 재출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 발표하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드(중요)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 모범 사례와 관련한 추가 정보를 제공합니다.

**기타 보안 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 제공됩니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 제공됩니다. "보안 업데이트"라는 키워드 검색을 수행하면 가장 쉽게 찾을 수 있습니다.
-   소비자 플랫폼용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 제공됩니다.
-   이달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 긴급 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/ko-kr/kb/913086)을 참조하십시오.

**IT 전문가 보안 커뮤니티**

[IT 전문가 보안 커뮤니티](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 알아보고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향받는 소프트웨어는 테스트를 거쳐 영향받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 주기](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.

IT 전문가용 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/ko-kr/security/bb980617)

Windows가 실행되는 컴퓨터를 바이러스 및 맬웨어로부터 보호: [바이러스 솔루션 및 보안 센터](http://support.microsoft.com/ko-kr/contactus/cu_sc_virsec_master)

지역별 지원 정보: [국가별 지원](http://support.microsoft.com/ko-kr/common/international.aspx)

### 고지 사항

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성과 특정 목적에 대한 적합성의 보증을 포함하여 명시적이거나 묵시적인 모든 보증을 부인합니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한이 적용되지 않을 수도 있습니다.

### 수정 내역

-   V1.0(2016년 11월 8일): 공지 요약이 게시되었습니다.

*2016-11-07 오후 12:03-08:00에 페이지가 생성되었습니다.*
