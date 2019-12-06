---
TOCTitle: 'MS16-MAR'
Title: 2016년 3월 Microsoft 보안 공지 요약
ms:assetid: 'ms16-mar'
ms:contentKeyID: 72464137
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms16-mar(v=Security.10)'
---

2016년 3월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2016년 3월 9일 | 업데이트된 날짜: 2016년 3월 26일

**버전:** 3.1

이 공지 요약 목록에는 2016년 3월 발표된 보안 공지가 포함되어 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://technet.microsoft.com/ko-kr/security/dd252948.aspx)을 참조하십시오.

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-023">MS16-023</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3142015)<br />
</strong>이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우, 이 취약성 악용에 성공한 공격자는 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-024">MS16-024</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge용 누적 보안 업데이트(3142019)<br />
</strong>이 보안 업데이트는 Microsoft Edge의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Microsoft Edge를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-025">MS16-025</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Windows 라이브러리 로드에 대한 보안 업데이트(3140709)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. Microsoft Windows가 특정 라이브러리 로드 전에 입력의 유효성을 제대로 검사하지 못하는 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다. 하지만 공격자는 악성 응용 프로그램을 실행할 수 있는 기능과 함께 로컬 시스템에 대한 액세스 권한을 먼저 얻어야 합니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-026">MS16-026</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 그래픽 글꼴에 대한 보안 업데이트(3143148)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 공격자가 사용자에게 특수 제작된 문서를 열거나 특수 제작된 포함된 OpenType 글꼴이 있는 웹 페이지를 방문하도록 유도할 경우 이 중에서 보다 심각한 취약성은 원격 코드 실행을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-027">MS16-027</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Windows Media에 대한 보안 업데이트(3143146)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 사용자가 웹 사이트에서 호스트되는 특수 제작된 미디어 콘텐츠를 여는 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문)<br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-028">MS16-028</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Microsoft Windows PDF Library에 대한 보안 업데이트(3143081)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 사용자가 특수 제작된 .pdf 파일을 여는 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-029">MS16-029</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Microsoft Office에 대한 보안 업데이트(3141806)</strong><br />
이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 Microsoft Office 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Office Services 및 Web Apps,<br />
Microsoft Server 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-030">MS16-030</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Windows OLE에 대한 보안 업데이트(3143136)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. Windows OLE가 제대로 사용자 입력의 유효성을 검사하지 못하는 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다. 공격자는 이러한 취약성을 악용하여 악성 코드를 실행할 수 있습니다. 하지만 공격자는 사용자가 특수 제작된 파일 또는 웹 페이지나 전자 메일 메시지의 프로그램을 열도록 먼저 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-031">MS16-031</a></td>
<td style="border:1px solid black;"><strong>권한 상승을 해결하기 위한 Microsoft Windows에 대한 보안 업데이트(3140410)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 공격자가 대상 시스템에 로그온하고 특수 제작된 응용 프로그램을 실행할 수 있는 경우 이 취약성으로 인해 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-032">MS16-032</a></td>
<td style="border:1px solid black;"><strong>권한 상승을 해결하기 위한 보조 로그온에 대한 보안 업데이트(3143141)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. Windows 보조 로그온 서비스가 메모리의 요청 핸들을 제대로 관리하지 못하는 경우 이 취약성으로 인해 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-033">MS16-033</a></td>
<td style="border:1px solid black;"><strong>권한 상승을 해결하기 위한 Windows USB 대용량 저장소 클래스 드라이버에 대한 보안 업데이트(3143142)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 실제로 액세스할 수 있는 공격자가 시스템에 특수 제작된 USB 장치를 삽입하는 경우 이 취약성으로 인해 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-034">MS16-034</a></td>
<td style="border:1px solid black;"><strong>권한 상승을 해결하기 위한 Windows 커널 모드 드라이버에 대한 보안 업데이트(3143145)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 공격자가 시스템에 로그온하고 특수 제작된 응용 프로그램을 실행할 경우 이 취약성으로 인해 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-035">MS16-035</a></td>
<td style="border:1px solid black;"><strong>보안 기능 우회를 해결하기 위한 .NET Framework에 대한 보안 업데이트(3141780)</strong><br />
이 보안 업데이트는 Microsoft .NET Framework의 취약성을 해결합니다. 서명된 XML 문서의 특성 요소에 대한 유효성을 제대로 검사하지 않는 .NET Framework 구성 요소에 보안 기능 우회가 존재합니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
보안 기능 우회</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3135996">3135996</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3136000">3136000</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3149737">3149737</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3148821">3148821</a></td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-036">MS16-036</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player용 보안 업데이트(3144756)</strong><br />
이 보안 업데이트는 지원되는 모든 버전의 Windows 8.1, Windows Server 2012, Windows Server 2012 R2, Windows RT 8.1 및 Windows 10에 설치된 Adobe Flash Player의 취약성을 해결합니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

악용 가능성 인덱스
------------------

<span id="sectionToggle1"></span>
다음 표에는 이달에 해결된 각 취약성의 악용 가능성 평가가 나와 있습니다. 취약성은 공지 ID 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약성만 포함됩니다.

**이 표를 어떻게 사용합니까?**

이 표를 사용하여 설치해야 할 수 있는 각 보안 업데이트에 대한 보안 공지 발표 후 30일 내 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토하십시오. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](https://technet.microsoft.com/ko-kr/security/cc998259)를 참조하십시오.

아래 열에서 "최신 소프트웨어 릴리스"는 관련 소프트웨어를 나타내며 "이전 소프트웨어 릴리스"는 공지의 "영향받는 소프트웨어" 및 "영향받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 릴리스를 나타냅니다.

<p> </p>
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
[**MS16-023: Internet Explorer용 누적 보안 업데이트(3142015)**](https://technet.microsoft.com/ko-kr/library/security/ms16-023)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0102(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0102)

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
[CVE-2016-0103(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0103)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

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
[CVE-2016-0104(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0104)

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
[CVE-2016-0105(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0105)

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
[CVE-2016-0106(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0106)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

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
[CVE-2016-0107(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0107)

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
[CVE-2016-0108(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0108)

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
[CVE-2016-0109(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0109)

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
[CVE-2016-0110(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0110)

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
[CVE-2016-0111(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0111)

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
[CVE-2016-0112(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0112)

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
[CVE-2016-0113(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0113)

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
[CVE-2016-0114(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0114)

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
<td style="border:1px solid black;" colspan="6">
[**MS16-024: Microsoft Edge용 누적 보안 업데이트(3142019)**](https://technet.microsoft.com/ko-kr/library/security/ms16-024)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0102(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0102)

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
[CVE-2016-0105(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0105)

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
[CVE-2016-0109(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0109)

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
[CVE-2016-0110(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0110)

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
[CVE-2016-0111(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0111)

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
[CVE-2016-0116(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0116)

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
<td style="border:1px solid black;">
[CVE-2016-0123(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0123)

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
<td style="border:1px solid black;">
[CVE-2016-0124(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0124)

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
<td style="border:1px solid black;">
[CVE-2016-0125(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0125)

</td>
<td style="border:1px solid black;">
Microsoft Edge 정보 유출 취약성

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
[CVE-2016-0129(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0129)

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
<td style="border:1px solid black;">
[CVE-2016-0130(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0130)

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
[**MS16-025: 원격 코드 실행을 해결하기 위한 Windows 라이브러리 로드에 대한 보안 업데이트(3140709)**](https://technet.microsoft.com/ko-kr/library/security/ms16-025)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0100(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0100)

</td>
<td style="border:1px solid black;">
라이브러리 로드 입력 유효성 검사 원격 코드 실행 취약성

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
<td style="border:1px solid black;" colspan="6">
[**MS16-026: 원격 코드 실행을 해결하기 위한 그래픽 글꼴에 대한 보안 업데이트(3143148)**](https://technet.microsoft.com/ko-kr/library/security/ms16-026)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0120(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0120)

</td>
<td style="border:1px solid black;">
OpenType 글꼴 구문 분석 취약성

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
[CVE-2016-0121(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0121)

</td>
<td style="border:1px solid black;">
OpenType 글꼴 구문 분석 취약성

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-027: 원격 코드 실행을 해결하기 위한 Windows Media에 대한 보안 업데이트(3143146)**](https://technet.microsoft.com/ko-kr/library/security/ms16-027)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0098(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0098)

</td>
<td style="border:1px solid black;">
Windows Media 구문 분석 원격 코드 실행 취약성

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
[CVE-2016-0101(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0101)

</td>
<td style="border:1px solid black;">
Windows Media 구문 분석 원격 코드 실행 취약성

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
[**MS16-028: 원격 코드 실행을 해결하기 위한 Microsoft Windows PDF Library에 대한 보안 업데이트(3143081)**](https://technet.microsoft.com/ko-kr/library/security/ms16-028)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0117(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0117)

</td>
<td style="border:1px solid black;">
Windows 원격 코드 실행 취약성

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
[CVE-2016-0118(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0118)

</td>
<td style="border:1px solid black;">
Windows 원격 코드 실행 취약성

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
[**MS16-029: 원격 코드 실행을 해결하기 위한 Microsoft Office에 대한 보안 업데이트(3141806)**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0021(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0021)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

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
[CVE-2016-0057(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0057)

</td>
<td style="border:1px solid black;">
Microsoft Office 보안 기능 우회 취약성

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
[CVE-2016-0134(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0134)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

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
<td style="border:1px solid black;" colspan="6">
[**MS16-030: 원격 코드 실행을 해결하기 위한 Windows OLE에 대한 보안 업데이트(3143136)**](https://technet.microsoft.com/ko-kr/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0091(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0091)

</td>
<td style="border:1px solid black;">
Windows OLE 메모리 원격 코드 실행 취약성

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
[CVE-2016-0092(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0092)

</td>
<td style="border:1px solid black;">
Windows OLE 메모리 원격 코드 실행 취약성

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
[**MS16-031: 권한 상승을 해결하기 위한 Microsoft Windows에 대한 보안 업데이트(3140410)**](https://technet.microsoft.com/ko-kr/library/security/ms16-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0087(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0087)

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
<td style="border:1px solid black;" colspan="6">
[**MS16-032: 권한 상승을 해결하기 위한 보조 로그온에 대한 보안 업데이트(3143141)**](https://technet.microsoft.com/ko-kr/library/security/ms16-032)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0099(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0099)

</td>
<td style="border:1px solid black;">
보조 로그온 권한 상승 취약성

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
[**MS16-033: 권한 상승을 해결하기 위한 Windows USB 대용량 저장소 클래스 드라이버에 대한 보안 업데이트(3143142)**](https://technet.microsoft.com/ko-kr/library/security/ms16-033)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0133(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0133)

</td>
<td style="border:1px solid black;">
USB 대용량 저장소 권한 상승 취약성

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
[**MS16-034: 권한 상승을 해결하기 위한 Windows 커널 모드 드라이버에 대한 보안 업데이트(3143145)**](https://technet.microsoft.com/ko-kr/library/security/ms16-034)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0093(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0093)

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
<td style="border:1px solid black;">
[CVE-2016-0094(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0094)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0095(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0095)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;" colspan="2">
4 - 영향을 받지 않음

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
[CVE-2016-0096(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0096)

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
[**MS16-035: 보안 기능 우회를 해결하기 위한 .NET Framework에 대한 보안 업데이트(3141780)**](https://technet.microsoft.com/ko-kr/library/security/ms16-035)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0132(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0132)

</td>
<td style="border:1px solid black;">
.NET XML 유효성 검사 보안 기능 우회

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
[**MS16-036: Adobe Flash Player용 보안 업데이트(3144756)**](https://technet.microsoft.com/ko-kr/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-08](https://helpx.adobe.com/kr/security/products/flash-player/apsb16-08.html)

</td>
<td style="border:1px solid black;">
취약성 심각도 및 업데이트 우선 순위 등급은 [Adobe 보안 공지 APSB16-08](https://helpx.adobe.com/kr/security/products/flash-player/apsb16-08.html)을 참조하십시오.

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

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/ko-kr/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/ko-kr/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/ko-kr/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/ko-kr/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/ko-kr/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/ko-kr/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/ko-kr/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3140709)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3140735)  
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
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3140709)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3140735)  
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
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/ko-kr/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/ko-kr/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/ko-kr/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/ko-kr/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/ko-kr/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/ko-kr/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/ko-kr/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3140709)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3140709)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3139940)  
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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3140709)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/ko-kr/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/ko-kr/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/ko-kr/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/ko-kr/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/ko-kr/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/ko-kr/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/ko-kr/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
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
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3138910)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3138962)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
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
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3138910)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3138962)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/ko-kr/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/ko-kr/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/ko-kr/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/ko-kr/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/ko-kr/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/ko-kr/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/ko-kr/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
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
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3138910)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3138962)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3139940)  
(중요)

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
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/ko-kr/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/ko-kr/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/ko-kr/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/ko-kr/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/ko-kr/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/ko-kr/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/ko-kr/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
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
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3138910)  
(긴급)  
Windows 8.1(32비트 시스템용)  
(3138962)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3137513)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
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
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3138910)  
(긴급)  
Windows 8.1(x64 기반 시스템용)  
(3138962)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3137513)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/ko-kr/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/ko-kr/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/ko-kr/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/ko-kr/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/ko-kr/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/ko-kr/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/ko-kr/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3139929)  
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
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3138910)  
(긴급)  
Windows Server 2012  
(3138962)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3137513)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
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
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3138910)  
(긴급)  
Windows Server 2012 R2  
(3138962)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3137513)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/ko-kr/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/ko-kr/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/ko-kr/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/ko-kr/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/ko-kr/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/ko-kr/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/ko-kr/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
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
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3138910)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3137513)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3139940)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/ko-kr/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/ko-kr/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/ko-kr/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/ko-kr/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/ko-kr/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/ko-kr/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/ko-kr/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140745)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140745)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3140745)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3140745)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3140745)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3140745)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140745)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140745)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3140745)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3140745)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3140745)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3140745)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140768)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140768)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3140768)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3140768)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3140768)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3140768)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140768)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140768)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3140768)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3140768)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3140768)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3140768)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/ko-kr/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/ko-kr/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/ko-kr/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/ko-kr/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/ko-kr/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/ko-kr/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/ko-kr/library/security/ms16-030)

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
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3140709)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3140735)  
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
(3139940)  
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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3140709)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3140735)  
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
(3139940)  
(중요)

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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3139940)  
(중요)

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
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3139940)  
(중요)

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
(3140735)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3137513)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3139940)  
(중요)

</td>
</tr>
</table>
 
 

### Windows 운영 체제 및 구성 요소(표 2/2)

<p> </p>
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
[**MS16-031**](https://technet.microsoft.com/ko-kr/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/ko-kr/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/ko-kr/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/ko-kr/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/ko-kr/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/ko-kr/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3135982)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(3135987)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(중요)  
Microsoft .NET Framework 4.6  
(3136000)  
(중요)

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
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3135982)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(3135987)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(중요)  
Microsoft .NET Framework 4.6  
(3136000)  
(중요)

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
[**MS16-031**](https://technet.microsoft.com/ko-kr/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/ko-kr/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/ko-kr/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/ko-kr/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/ko-kr/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/ko-kr/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3135982)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(3135987)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(중요)  
Microsoft .NET Framework 4.6  
(3136000)  
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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3135982)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(3135987)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(중요)  
Microsoft .NET Framework 4.6  
(3136000)  
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
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3135982)  
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
[**MS16-031**](https://technet.microsoft.com/ko-kr/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/ko-kr/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/ko-kr/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/ko-kr/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/ko-kr/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/ko-kr/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3135988)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3136000)  
(중요)

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
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3135988)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3136000)  
(중요)

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
[**MS16-031**](https://technet.microsoft.com/ko-kr/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/ko-kr/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/ko-kr/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/ko-kr/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/ko-kr/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/ko-kr/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3135988)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135996)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3136000)  
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
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
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
[**MS16-031**](https://technet.microsoft.com/ko-kr/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/ko-kr/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/ko-kr/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/ko-kr/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/ko-kr/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/ko-kr/library/security/ms16-036)

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
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
(중요)  
Microsoft .NET Framework 3.5  
(3135991)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135994)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
(중요)  
Microsoft .NET Framework 3.5  
(3135991)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135994)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
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
[**MS16-031**](https://technet.microsoft.com/ko-kr/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/ko-kr/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/ko-kr/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/ko-kr/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/ko-kr/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/ko-kr/library/security/ms16-036)

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
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**보통**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135984)  
(중요)  
Microsoft .NET Framework 3.5  
(3135989)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135995)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3135997)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
(중요)  
Microsoft .NET Framework 3.5  
(3135991)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135994)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
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
[**MS16-031**](https://technet.microsoft.com/ko-kr/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/ko-kr/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/ko-kr/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/ko-kr/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/ko-kr/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/ko-kr/library/security/ms16-036)

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
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3135994)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
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
[**MS16-031**](https://technet.microsoft.com/ko-kr/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/ko-kr/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/ko-kr/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/ko-kr/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/ko-kr/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/ko-kr/library/security/ms16-036)

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
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3140745)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3140745)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3140745)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140745)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3140745)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3140745)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3140745)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3140745)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140745)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3140745)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
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
(3140768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3140768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3140768)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140768)  
(중요)  
Microsoft .NET Framework 4.6.1  
(3140768)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
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
(3140768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3140768)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3140768)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140768)  
(중요)  
Microsoft .NET Framework 4.6.1  
(3140768)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
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
[**MS16-031**](https://technet.microsoft.com/ko-kr/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/ko-kr/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/ko-kr/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/ko-kr/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/ko-kr/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/ko-kr/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3139852)  
(중요)

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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3139852)  
(중요)

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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3140410)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
(중요)  
Microsoft .NET Framework 3.5.1  
(3135988)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135996)  
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
Windows Server 2012  
(Server Core 설치)  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135984)  
(중요)  
Microsoft .NET Framework 3.5  
(3135989)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135995)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3135997)  
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
Windows Server 2012 R2  
(Server Core 설치)  
(3139914)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3139398)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3139852)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
(중요)  
Microsoft .NET Framework 3.5  
(3135991)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3135994)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
(중요)

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
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(2956110)  
(중요)  
Microsoft InfoPath 2007 서비스 팩 3  
(3114426)  
(중요)  
Microsoft Outlook 2007 서비스 팩 3  
(2880510)  
(중요)  
Microsoft Word 2007 서비스 팩 3  
(3114901)  
(중요)

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
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(2956063)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3114873)  
(중요)  
Microsoft InfoPath 2010 서비스 팩 2(32비트 버전)  
(3114414)  
(중요)  
Microsoft Outlook 2010 서비스 팩 2(32비트 버전)  
(3114883)  
(중요)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(3114878)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3114873)  
(중요)  
Microsoft InfoPath 2010 서비스 팩 2(64비트 버전)  
(3114414)  
(중요)  
Microsoft Outlook 2010 서비스 팩 2(64비트 버전)  
(3114883)  
(중요)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(3114878)  
(중요)

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
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(3039746)  
(중요)  
Microsoft InfoPath 2013 서비스 팩 1(32비트 버전)  
(3114833)  
(중요)  
Microsoft Outlook 2013 서비스 팩 1(32비트 버전)  
(3114829)  
(중요)  
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(3114824)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft InfoPath 2013 서비스 팩 1(64비트 버전)  
(3114833)  
(중요)  
Microsoft Outlook 2013 서비스 팩 1(64비트 버전)  
(3114829)  
(중요)  
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(3114824)  
(중요)

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
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013 RT 서비스 팩 1  
(3114829)  
(중요)  
Microsoft Word 2013 RT 서비스 팩 1  
(3114824)  
(중요)

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
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016(32비트 버전)  
(3114690)  
(중요)  
Microsoft Outlook 2016(32비트 버전)  
(3114861)  
(중요)  
Microsoft Word 2016(32비트 버전)  
(3114855)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Outlook 2016(64비트 버전)  
(3114861)  
(중요)  
Microsoft Word 2016(64비트 버전)  
(3114855)  
(중요)

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
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3138328)<sup>[1]</sup>
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
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3138327)<sup>[1]</sup>
(중요)

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
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3114900)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114812)  
(중요)

</td>
</tr>
</table>
 
**MS16-029 참고 사항**

<sup>[1]</sup>2016년 3월 17일부터 Microsoft Office 2016 for Mac용 3138327 업데이트가 제공되며, Microsoft Office for Mac 2011용 3138328 업데이트가 제공됩니다. Microsoft Outlook 2016 for Mac용 3138327 업데이트는 3월 17일 릴리스되지 않았습니다. 이 업데이트가 사용 가능하게 되면 바로 릴리스될 것이며 공지 개정을 통해 사용자에게 알림이 제공됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 3138327](https://support.microsoft.com/ko-kr/kb/3138327) 및 [Microsoft 기술 자료 문서 3138328](https://support.microsoft.com/ko-kr/kb/3138328)을 참조하십시오.

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
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3114866)  
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
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3114814)  
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
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2  
(3114880)  
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
[**MS16-029**](https://technet.microsoft.com/ko-kr/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1  
(3114821)  
(중요)

</td>
</tr>
</table>
 
**MS16-029 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

검색, 배포 도구 및 지침
-----------------------

<span id="sectionToggle3"></span>
관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 있습니다.

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트와 일반적인 보안 구성 오류를 검색할 수 있습니다.

관리자는 WSUS(Windows Server Update Services), SMS(Systems Management Server) 및 System Center Configuration Manager를 통해 보안 업데이트를 배포할 수 있습니다.

ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](https://technet.microsoft.com/ko-kr/security/cc297183)를 참조하십시오. 

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
-   [Windows Server Update Services용으로 지난 몇 달간 배포된 업데이트](https://technet.microsoft.com/ko-kr/windowsserver/bb332157.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 재출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약성 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](https://technet.microsoft.com/ko-kr/security/dn467918)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](https://technet.microsoft.com/ko-kr/library/bb466251.aspx)(영문)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 모범 사례와 관련한 추가 정보를 제공합니다.

**기타 보안 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 제공됩니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://www.microsoft.com/ko-kr/download/search.aspx?q=security%20update)에서 제공됩니다. "보안 업데이트"라는 키워드 검색을 수행하면 가장 쉽게 찾을 수 있습니다.
-   소비자 플랫폼용 업데이트는 [Microsoft Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)에서 제공됩니다.
-   이달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 긴급 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/ko-kr/kb/913086)을 참조하십시오.

**IT 전문가 보안 커뮤니티**

[IT 전문가 보안 커뮤니티](https://technet.microsoft.com/ko-kr/security/cc136632.aspx)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 알아보고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향받는 소프트웨어는 테스트를 거쳐 영향받는 버전이 확인되었습니다. 다른 버전은 지원 주기가 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 주기를 확인하려면 [Microsoft 지원 주기](https://support.microsoft.com/ko-kr/lifecycle)를 참조하십시오.

IT 전문가용 보안 솔루션: [TechNet 보안 문제 해결 및 지원](https://technet.microsoft.com/ko-kr/security/bb980617)

Windows 컴퓨터를 바이러스 및 맬웨어로부터 보호: [바이러스 솔루션 및 보안 센터](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ko)

지역별 지원 정보: [국가별 지원](https://support.microsoft.com/common/international.aspx?ln=ko)

### 고지 사항

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성과 특정 목적에 대한 적합성의 보증을 포함하여 명시적이거나 묵시적인 모든 보증을 부인합니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한이 적용되지 않을 수도 있습니다.

### 수정 내역

-   V1.0(2016년 3월 9일): 공지 요약이 게시되었습니다.
-   V2.0(2016년 3월 11일): MS16-036의 부정기 발표에 대해 설명하기 위해 공지 요약이 개정되었습니다.
-   V2.1(2016년 3월 11일): MS16-035에 대한 요약 표에 알려진 문제 참조가 추가되었습니다. 자세한 내용은 [Microsoft 기술 자료 문서 3148821](https://support.microsoft.com/ko-kr/kb/3148821)을 참조하십시오.
-   V2.2(2016년 3월 16일): MS16-035에 대한 요약 표에 알려진 문제 참조가 추가되었습니다. 자세한 내용은 [Microsoft 기술 자료 문서 3135996](https://support.microsoft.com/ko-kr/kb/3135996), [Microsoft 기술 자료 문서 3136000](https://support.microsoft.com/ko-kr/kb/3136000) 및 [Microsoft 기술 자료 문서 3149737](https://support.microsoft.com/ko-kr/kb/3149737)을 참조하십시오.
-   V3.0(2016년 3월 17일): MS16-029에서는 2016년 3월 17일부터 제공되는 Microsoft Office 2016 for Mac용 3138327 업데이트 및 Microsoft Office for Mac 2011용 3138328 업데이트가 추가되었습니다. Microsoft Outlook 2016 for Mac용 3138327 업데이트는 3월 17일 릴리스되지 않았습니다. 이 업데이트가 사용 가능하게 되면 바로 릴리스될 것이며 공지 개정을 통해 사용자에게 알림이 제공됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 3138327](https://support.microsoft.com/ko-kr/kb/3138327) 및 [Microsoft 기술 자료 문서 3138328](https://support.microsoft.com/ko-kr/kb/3138328)을 참조하십시오.
-   V3.1(2016년 3월 26일): MS16-028에서는 Windows Server 2012(Server Core 설치)가 영향을 받지 않기 때문에 Windows 운영 체제 및 구성 요소(표 1/2)에서 이를 제거했습니다. 이 변경 사항은 정보 제공용입니다.

*2016-03-25 11:32-07:00에 페이지가 생성되었습니다.*
