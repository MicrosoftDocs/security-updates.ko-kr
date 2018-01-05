---
TOCTitle: 'MS16-JUL'
Title: 2016년 7월 Microsoft 보안 공지 요약
ms:assetid: 'ms16-jul'
ms:contentKeyID: 73201113
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms16-jul(v=Security.10)'
---

MSRC ppDocument 템플릿

2016년 7월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2016년 7월 12일 화요일

**버전:** 1.0

이 공지 요약 목록에는 2016년 7월에 발표된 보안 공지가 포함되어 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 절을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 **영향받는 소프트웨어** 절을 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808143">MS16-084</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3169991)<br />
</strong>이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우 공격자가 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808148">MS16-085</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge용 누적 보안 업데이트(3169999)<br />
</strong>이 보안 업데이트는 Microsoft Edge의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Microsoft Edge를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 고객은 관리자 권한이 있는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808144">MS16-086</a></td>
<td style="border:1px solid black;"><strong>JScript 및 VBScript용 누적 보안 업데이트(3169996)<br />
</strong>이 보안 업데이트는 Microsoft Windows에서 JScript 및 VBScript 스크립팅 엔진의 취약성을 해결합니다. 이 취약성으로 인해 사용자가 특수 제작된 웹 사이트를 방문할 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우, 이 취약성 악용에 성공한 공격자는 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808150">MS16-087</a></td>
<td style="border:1px solid black;"><strong>Windows 인쇄 스풀러 구성 요소용 보안 업데이트(3170005)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이러한 취약성 중 더 위험한 취약성으로 인해 공격자가 워크스테이션이나 인쇄 서버에서 메시지 가로채기(man-in-the-middle) 공격을 실행하거나, 대상 네트워크에서 사기성 인쇄 서버를 설정하는 경우 원격 코드가 실행될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808151">MS16-088</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office용 보안 업데이트(3170008)<br />
</strong>이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 Microsoft Office 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Office Services 및 Web Apps</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808157">MS16-089</a></td>
<td style="border:1px solid black;"><strong>Windows 보안 커널 모드용 보안 업데이트(3170050)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. Windows 보안 커널 모드가 메모리의 개체를 부적절하게 처리하는 경우 이 취약성으로 인해 정보 유출이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808590">MS16-090</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버용 보안 업데이트(3171481)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이러한 취약성 중 더 위험한 취약성으로 인해 공격자가 영향받는 시스템에 로그온하여 취약성을 악용하고 영향받는 시스템을 제어할 수 있는 특수 제작된 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808156">MS16-091</a></td>
<td style="border:1px solid black;"><strong>.NET Framework용 보안 업데이트(3170048)<br />
</strong>이 보안 업데이트는 Microsoft .NET Framework의 취약성을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 XML 파일을 웹 기반 응용 프로그램으로 업로드하면 정보가 공개될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808706">MS16-092</a></td>
<td style="border:1px solid black;"><strong>Windows 커널용 보안 업데이트(3171910)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약점으로 인해 Windows 커널이 낮은 무결성 응용 프로그램에서 특정 개체 관리자 기능을 사용하는 방식을 확인하지 못하는 경우 보안 기능 우회가 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=809010">MS16-093</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player용 보안 업데이트(3174060)<br />
</strong>이 보안 업데이트는 지원되는 모든 버전의 Windows 8.1, Windows Server 2012, Windows RT 8.1, Windows Server 2012 R2 및 Windows 10에 설치된 Adobe Flash Player의 취약성을 해결합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=817339">MS16-094</a></td>
<td style="border:1px solid black;"><strong>보안 부팅용 보안 업데이트(3177404)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 공격자가 대상 장치에 영향을 받는 정책을 설치하는 경우 보안 부팅 보안 기능의 우회가 허용될 수 있습니다. 공격자는 관리자 권한이나 실제 액세스 권한을 통해 정책을 설치하고 보안 부팅을 우회해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
[**MS16-084: Internet Explorer용 누적 보안 업데이트(3169991)**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3204(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3204)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

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
[CVE-2016-3240](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3240)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

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
[CVE-2016-3241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3241)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

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
[CVE-2016-3242](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3242)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

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
[CVE-2016-3243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3243)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

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
[CVE-2016-3245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3245)

</td>
<td style="border:1px solid black;">
Internet Explorer 보안 기능 우회 취약성

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
[CVE-2016-3248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3248)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

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
[CVE-2016-3259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3259)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

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
[CVE-2016-3260](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3260)

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
[CVE-2016-3261](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3261)

</td>
<td style="border:1px solid black;">
Internet Explorer 정보 유출 취약성

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
[CVE-2016-3264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3264)

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
[CVE-2016-3273](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3273)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

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
[CVE-2016-3274](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3274)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 스푸핑 취약성

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
[CVE-2016-3276](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3276)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 스푸핑 취약성

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
[CVE-2016-3277](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3277)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-085: Microsoft Edge용 누적 보안 업데이트(3169999)**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3244(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3244)

</td>
<td style="border:1px solid black;">
Microsoft Edge 보안 기능 우회

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
[CVE-2016-3246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3246)

</td>
<td style="border:1px solid black;">
Microsoft Edge 메모리 손상 취약성

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
[CVE-2016-3248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3248)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

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
[CVE-2016-3259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3259)

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
[CVE-2016-3260](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3260)

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
[CVE-2016-3264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3264)

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
[CVE-2016-3265](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3265)

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
[CVE-2016-3269](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3269)

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
[CVE-2016-3271](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3271)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 정보 유출 취약성

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
[CVE-2016-3273](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3273)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

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
[CVE-2016-3274](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3274)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 스푸핑 취약성

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
[CVE-2016-3276](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3276)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 스푸핑 취약성

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
[CVE-2016-3277](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3277)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

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
[**MS16-086: JScript 및 VBScript용 누적 보안 업데이트(3169996)**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3204(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3204)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

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
[**MS16-087: Microsoft 인쇄 스풀러용 보안 업데이트(3170005)**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3238](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3238)

</td>
<td style="border:1px solid black;">
Windows 인쇄 스풀러 원격 코드 실행 취약성

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
[CVE-2016-3239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3239)

</td>
<td style="border:1px solid black;">
Windows 인쇄 스풀러 권한 상승 취약성

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
[**MS16-088: Microsoft Office용 보안 업데이트(3170008)**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3278(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3278)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

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
[CVE-2016-3279](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3279)

</td>
<td style="border:1px solid black;">
Microsoft 보안 기능 우회 취약성

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
[CVE-2016-3280](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3280)

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
[CVE-2016-3281](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3281)

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
[CVE-2016-3282](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3282)

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
[CVE-2016-3283](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3283)

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
[CVE-2016-3284](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3284)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-089: Windows 보안 커널 모드용 보안 업데이트(3170050)**](http://go.microsoft.com/fwlink/?linkid=808157)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3256](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3256)

</td>
<td style="border:1px solid black;">
Windows 보안 커널 정보 유출 취약성

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
<td style="border:1px solid black;" colspan="5">
[**MS16-090: Windows 커널 모드 드라이버용 보안 업데이트(3171481)**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3249(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3249)

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
[CVE-2016-3250(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3250)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

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
[CVE-2016-3251(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3251)

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
[CVE-2016-3252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3252)

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
[CVE-2016-3254](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3254)

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
[CVE-2016-3286](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3286)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-091: .NET Framework용 보안 업데이트(3170048)**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3255(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3255)

</td>
<td style="border:1px solid black;">
.NET 정보 유출 취약성

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-092: Windows 커널용 보안 업데이트(3171910)**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3258(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3258)

</td>
<td style="border:1px solid black;">
Windows 파일 시스템 보안 기능 우회

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
[CVE-2016-3272](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3272)

</td>
<td style="border:1px solid black;">
Windows 커널 정보 유출 취약성

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
[**MS16-093: Adobe Flash Player용 보안 업데이트(3174060)**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-25](http://helpx.adobe.com/security/products/flash-player/apsb16-25.html)

</td>
<td style="border:1px solid black;">
취약성 심각도 및 업데이트 우선 순위 등급은 [Adobe 보안 공지 APSB16-25](http://helpx.adobe.com/security/products/flash-player/apsb16-25.html)를 참조하십시오.

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
<td style="border:1px solid black;" colspan="5">
[**MS16-094: 보안 부팅용 보안 업데이트(3177404)**](http://go.microsoft.com/fwlink/?linkid=817339)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3287](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3287)

</td>
<td style="border:1px solid black;">
보안 부팅 보안 기능 우회

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

**참고** 단일 취약성에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

 

### Windows 운영 체제 및 구성 요소(표 1/2)

<p> </p>
<table style="border:1px solid black;">
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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)                   

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)                   

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)                   

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 9  
(3170106)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3170455)  
(긴급)

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
Internet Explorer 9  
(3170106)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3170455)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 9  
(3170106)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3170455)  
(긴급)

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
Internet Explorer 9  
(3170106)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3170455)  
(긴급)

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
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3170455)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 11  
(3170106)  
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
(3170455)  
(긴급)

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
Internet Explorer 11  
(3170106)  
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
(3170455)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 11  
(3170106)  
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
(3170455)  
(긴급)

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
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3170455)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3170455)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3170455)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3170106)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3170455)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3170455)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3170455)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 11  
(3163912)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163912)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3163912)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3163912)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163912)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163912)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3163912)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3163912)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3172985)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3172985)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3172985)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3172985)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3172985)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3172985)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3172985)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3172985)  
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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

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
VBScript 5.7  
(3169659)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3170455)  
(긴급)

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
VBScript 5.7  
(3169659)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3170455)  
(긴급)

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
JScript 5.8 및 VBScript 5.8  
(3169658)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3170455)  
(긴급)

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
Windows Server 2012(Server Core 설치)  
(3170455)  
(긴급)

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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3170455)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 
 

### Windows 운영 체제 및 구성 요소(표 2/2)

<p> </p>
<table style="border:1px solid black;">
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
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista 서비스 팩 2  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3163244)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(중요)  
Microsoft .NET Framework 4.6  
(3164025)  
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
Windows Vista x64 Edition 서비스 팩 2  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3163244)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(중요)  
Microsoft .NET Framework 4.6  
(3164025)  
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
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3163244)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(중요)  
Microsoft .NET Framework 4.6  
(3164025)  
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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3163244)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(중요)  
Microsoft .NET Framework 4.6  
(3164025)  
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
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3163244)  
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
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
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
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3170377)  
(중요)  
Windows 8.1(32비트 시스템용)  
(3169704)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3172727)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3170377)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(3169704)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3172727)  
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
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163246)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163250)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3164023)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3170377)  
(중요)  
Windows Server 2012  
(3169704)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3172727)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3170377)  
(중요)  
Windows Server 2012 R2  
(3169704)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3172727)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3163291)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3170377)  
(중요)  
Windows RT 8.1  
(3169704)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3172727)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3163912)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163912)  
(중요)  
Microsoft .NET Framework 4.6  
(3163912)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3163912)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3163912)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3163912)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163912)  
(중요)  
Microsoft .NET Framework 4.6  
(3163912)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3163912)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3163912)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3172985)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3172985)  
(중요)  
Microsoft .NET Framework 4.6.1  
(3172985)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3172985)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3172985)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3172985)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3172985)  
(중요)  
Microsoft .NET Framework 4.6.1  
(3172985)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3172985)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3172985)  
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
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3168965)  
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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3168965)  
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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
Windows Server 2012  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163246)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163250)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3164023)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3170377)  
(중요)  
Windows Server 2012(Server Core 설치)  
(3169704)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3172727)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3168965)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3170377)  
(중요)  
Windows Server 2012 R2(Server Core 설치)  
(3169704)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3172727)  
(중요)

</td>
</tr>
</table>
 
 

### Microsoft Office 제품군 및 소프트웨어

<p> </p>
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 서비스 팩 3  
(3115306)  
(중요)  
Microsoft Word 2007 서비스 팩 3  
(3115311)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3115315)  
(긴급)  
Microsoft Excel 2010 서비스 팩 2(32비트 버전)  
(3115322)  
(중요)  
Microsoft Outlook 2010 서비스 팩 2(32비트 버전)  
(3115246)  
(중요)  
Microsoft PowerPoint 2010 서비스 팩 2(32비트 에디션)  
(3115118)  
(중요)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(3115317)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3115315)  
(긴급)  
Microsoft Excel 2010 서비스 팩 2(64비트 버전)  
(3115322)  
(중요)  
Microsoft Outlook 2010 서비스 팩 2(64비트 버전)  
(3115246)  
(중요)  
Microsoft PowerPoint 2010 서비스 팩 2(64비트 에디션)  
(3115118)  
(중요)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(3115317)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 서비스 팩 1(32비트 버전)  
(3115262)  
(중요)  
Microsoft Outlook 2013 서비스 팩 1(32비트 버전)  
(3115259)  
(중요)  
Microsoft PowerPoint 2013 서비스 팩 1(32비트 에디션)  
(3115254)  
(중요)  
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(3115292)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 서비스 팩 1(64비트 버전)  
(3115262)  
(중요)  
Microsoft Outlook 2013 서비스 팩 1(64비트 버전)  
(3115259)  
(중요)  
Microsoft PowerPoint 2013 서비스 팩 1(64비트 에디션)  
(3115254)  
(중요)  
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(3115292)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT 서비스 팩 1  
(3115262)  
(중요)  
Microsoft Outlook 2013 RT 서비스 팩 1  
(3115259)  
(중요)  
Microsoft PowerPoint 2013 RT 서비스 팩 1  
(3115254)  
(중요)  
Microsoft Word 2013 RT 서비스 팩 1  
(3115292)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016(32비트 버전)  
(3115272)  
(중요)  
Microsoft Outlook 2016(32비트 버전)  
(3115279)  
(중요)  
Microsoft Word 2016(32비트 버전)  
(3115301)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016(64비트 버전)  
(3115272)  
(중요)  
Microsoft Outlook 2016(64비트 버전)  
(3115279)  
(중요)  
Microsoft Word 2016(64비트 버전)  
(3115301)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3170463)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3170463)  
(긴급)

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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3170460)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3170460)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3115308)  
(중요)  
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3115309)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3115114)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115393)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115395)  
(긴급)

</td>
</tr>
</table>
 
**MS16-088 참고 사항**

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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Word Automation Services  
(3115312)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3115285)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft SharePoint Server 2016

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2016  
(3115299)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2  
(3115318)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office Web Apps Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1  
(3115289)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Office Online Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Office Online Server

</td>
<td style="border:1px solid black;">
Office Online Server  
(3115386)  
(중요)

</td>
</tr>
</table>
 
**MS16-088 참고 사항**

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
Microsoft는 신뢰할 수 있는 취약성 공개를 통해 고객을 보호하는 데 도움을 주는 보안 커뮤니티의 공로를 기립니다. 자세한 내용은 [감사의 말](https://technet.microsoft.com/ko-kr/library/security/mt674627.aspx)을 참조하십시오.

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 릴리스에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services 및 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 릴리스에서 제공되지 않습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft Update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/ko-kr/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services용으로 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/ko-kr/wsus/bb456965). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 재출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 모범 사례와 관련한 추가 정보를 제공합니다.

**기타 보안 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 제공됩니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 제공됩니다. "보안 업데이트"라는 키워드 검색을 수행하면 가장 쉽게 찾을 수 있습니다.
-   소비자 플랫폼용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 제공됩니다.
-   이달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 긴급 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/ko-kr/kb/913086)을 참조하십시오.

**IT 전문가 보안 커뮤니티**

[IT 전문가 보안 커뮤니티](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 알아보고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향받는 소프트웨어는 테스트를 거쳐 영향받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간](http://go.microsoft.com/fwlink/?linkid=21742)을 참조하십시오.

IT 전문가용 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/ko-kr/security/bb980617)

Windows 컴퓨터를 바이러스 및 맬웨어로부터 보호: [바이러스 솔루션 및 보안 센터](http://support.microsoft.com/ko-kr/contactus/cu_sc_virsec_master)

지역별 지원 정보: [국가별 지원](http://support.microsoft.com/ko-kr/common/international.aspx)

### 고지 사항

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성과 특정 목적에 대한 적합성의 보증을 포함하여 명시적이거나 묵시적인 모든 보증을 부인합니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation또는그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 수정 내역

-   V1.0(2016년 7월 12일 화요일): 공지 요약이 게시되었습니다.

*2016-07-13 오전 10:05-07:00에 페이지가 생성되었습니다.*
