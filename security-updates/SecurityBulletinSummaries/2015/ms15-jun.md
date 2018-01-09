---
TOCTitle: 'MS15-JUN'
Title: 2015년 6월 Microsoft 보안 공지 요약
ms:assetid: 'ms15-jun'
ms:contentKeyID: 65883219
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms15-jun(v=Security.10)'
---

2015년 6월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2015년 6월 10일

**버전:** 1.0

이 공지 요약 목록에는 2015년 6월 발표된 보안 공지가 포함되어 있습니다.

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3058515)</strong> <br />
이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-057">MS15-057</a></td>
<td style="border:1px solid black;"><strong>Windows Media Player의 취약성으로 인한 원격 코드 실행 문제(3033890)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 Windows Media Player가 악의적인 웹 사이트에서 호스트되는 특수 제작된 미디어 콘텐츠를 여는 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약성을 악의적으로 이용하는 공격자는 영향받는 시스템을 원격으로 완전히 제어할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-059">MS15-059</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office의 취약성으로 인한 원격 코드 실행 문제(3064949)</strong> <br />
이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 Microsoft Office 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-060">MS15-060</a></td>
<td style="border:1px solid black;"><strong>Microsoft 공용 컨트롤의 취약성으로 인한 원격 코드 실행 문제(3059317)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 사용자가 특수 제작된 링크나 특수 제작된 콘텐츠의 링크를 클릭한 다음 Internet Explorer에서 F12 개발자 도구를 호출하는 경우 이러한 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버의 취약성으로 인한 권한 상승 문제(3057839)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 공격자가 시스템에 로그온하고 특수 제작된 응용 프로그램을 커널 모드로 실행할 경우 권한 상승을 허용할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-062">MS15-062</a></td>
<td style="border:1px solid black;"><strong>Active Directory Federation Services의 취약성으로 인한 권한 상승 문제(3062577)</strong> <br />
이 보안 업데이트는 Microsoft AD FS(Active Directory Federation Services)의 취약성을 해결합니다. 이 취약성으로 인해 공격자가 특수 제작된 URL을 대상 사이트에 제출하는 경우 권한 상승이 허용될 수 있습니다. 특정 상황에서 이 취약성으로 인해, 특수 제작된 스크립트가 적절하게 삭제되지 않으며, 공격자가 제공하는 스크립트가 악성 콘텐츠를 보는 사용자의 보안 컨텍스트에서 실행되는 결과로 이어질 수 있습니다. 이 취약성을 이용한 교차 사이트 스크립팅 공격의 경우 사용자가 손상된 사이트를 방문해야 악의적인 동작이 발생합니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작할 필요 없음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-063">MS15-063</a></td>
<td style="border:1px solid black;"><strong>Windows 커널의 취약성으로 인한 권한 상승 문제(3063858)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성은 공격자가 컴퓨터나 네트워크 공유의 로컬 디렉터리에 악성 .dll 파일을 저장하는 경우 권한 상승을 허용할 수 있습니다. 그런 다음 공격자는 권한 상승이 발생하도록 악성 .dll 파일을 로드할 수 있는 프로그램을 사용자가 실행하기까지 기다려야 합니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 해당 네트워크 공유나 웹 사이트를 방문하도록 만들 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-064">MS15-064</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server의 취약성으로 인한 권한 상승 문제(3062157)</strong> <br />
이 보안 업데이트는 Microsoft Exchange Server의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 인증된 사용자가 특수 제작된 웹 페이지의 링크를 클릭하는 경우 권한 상승을 허용할 수 있습니다. 공격자는 강제로 사용자가 웹 사이트를 방문하도록 할 수 없습니다. 대신 공격자는 일반적으로 전자 메일 또는 인스턴트 메신저 메시지에서 유인물을 이용하여 사용자가 이 링크를 클릭하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작할 필요 없음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1687">CVE-2015-1687(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1730">CVE-2015-1730(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1731">CVE-2015-1731(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1732">CVE-2015-1732(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1735">CVE-2015-1735(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1736">CVE-2015-1736(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1737">CVE-2015-1737(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1739">CVE-2015-1739(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1740">CVE-2015-1740(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1741">CVE-2015-1741(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1742">CVE-2015-1742(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1743">CVE-2015-1743(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1744">CVE-2015-1744(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1745">CVE-2015-1745(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1747">CVE-2015-1747(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1748">CVE-2015-1748(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1750">CVE-2015-1750(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1751">CVE-2015-1751(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1752">CVE-2015-1752(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1753">CVE-2015-1753(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1754">CVE-2015-1754(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1755">CVE-2015-1755(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 정보 유출 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1765">CVE-2015-1765(영문)</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-056">MS15-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1766">CVE-2015-1766(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-057">MS15-057</a></td>
<td style="border:1px solid black;">DataObject를 통한 Windows Media Player RCE 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1728">CVE-2015-1728(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-059">MS15-059</a></td>
<td style="border:1px solid black;">Microsoft Office 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1759">CVE-2015-1759(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-059">MS15-059</a></td>
<td style="border:1px solid black;">Microsoft Office 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1760">CVE-2015-1760(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-059">MS15-059</a></td>
<td style="border:1px solid black;">Microsoft Office 초기화되지 않은 메모리 사용 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1770">CVE-2015-1770(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-060">MS15-060</a></td>
<td style="border:1px solid black;">Microsoft 공용 컨트롤 해제 후 사용 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1756">CVE-2015-1756(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 높음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 정보 유출 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1719">CVE-2015-1719(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">영구</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 해제 후 사용 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1720">CVE-2015-1720(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">영구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;">Win32k Null 포인터 역참조 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1721">CVE-2015-1721(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 비트맵 처리 해제 후 사용 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1722">CVE-2015-1722(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 스테이션 해제 후 사용 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1723">CVE-2015-1723(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 개체 해제 후 사용 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1724">CVE-2015-1724(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;">Win32k 버퍼 오버플로 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1725">CVE-2015-1725(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">영구</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 브러시 개체 해제 후 사용 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1726">CVE-2015-1726(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">영구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;">Win32k 풀 버퍼 오버플로 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1727">CVE-2015-1727(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">영구</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;">Win32k 메모리 손상 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1768">CVE-2015-1768(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">영구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-061">MS15-061</a></td>
<td style="border:1px solid black;">Win32k 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2360">CVE-2015-2360(영문)</a></td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">영구</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-062">MS15-062</a></td>
<td style="border:1px solid black;">ADFS XSS 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1757">CVE-2015-1757(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-063">MS15-063</a></td>
<td style="border:1px solid black;">Windows LoadLibrary EoP 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1758">CVE-2015-1758(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-064">MS15-064</a></td>
<td style="border:1px solid black;">Exchange 서버 쪽 요청 위조 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1764">CVE-2015-1764(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-064">MS15-064</a></td>
<td style="border:1px solid black;">Exchange 교차 사이트 요청 위조 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1771">CVE-2015-1771(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-064">MS15-064</a></td>
<td style="border:1px solid black;">Exchange HTML 삽입 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2359">CVE-2015-2359(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
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
  
### Windows 운영 체제 및 구성 요소

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-056**](https://technet.microsoft.com/ko-kr/library/security/ms15-056)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://technet.microsoft.com/ko-kr/library/security/ms15-057)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://technet.microsoft.com/ko-kr/library/security/ms15-060)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://technet.microsoft.com/ko-kr/library/security/ms15-061)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://technet.microsoft.com/ko-kr/library/security/ms15-062)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://technet.microsoft.com/ko-kr/library/security/ms15-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                             

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                 

</td>
<td style="border:1px solid black;">
**없음**                                 

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                 

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
Windows Server 2003 서비스 팩 2                

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3058515)  
(보통)  
Internet Explorer 7  
(3058515)  
(보통)  
Internet Explorer 8  
(3058515)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Media Player 10  
(3033890)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3057839)  
(중요)  
Windows Server 2003 R2 서비스 팩 2  
(3057839)  
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
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3058515)  
(보통)  
Internet Explorer 7  
(3058515)  
(보통)  
Internet Explorer 8  
(3058515)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Media Player 10  
(3033890)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3057839)  
(중요)  
Windows Server 2003 R2 x64 Edition 서비스 팩 2  
(3057839)  
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
Windows Server 2003 SP2(Itanium 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3058515)  
(보통)  
Internet Explorer 7  
(3058515)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3057839)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-056**](https://technet.microsoft.com/ko-kr/library/security/ms15-056)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://technet.microsoft.com/ko-kr/library/security/ms15-057)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://technet.microsoft.com/ko-kr/library/security/ms15-060)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://technet.microsoft.com/ko-kr/library/security/ms15-061)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://technet.microsoft.com/ko-kr/library/security/ms15-062)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://technet.microsoft.com/ko-kr/library/security/ms15-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
(긴급)  
Internet Explorer 8  
(3058515)  
(긴급)  
Internet Explorer 9  
(3058515)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3063858)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
(긴급)  
Internet Explorer 8  
(3058515)  
(긴급)  
Internet Explorer 9  
(3058515)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3063858)  
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
[**MS15-056**](https://technet.microsoft.com/ko-kr/library/security/ms15-056)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://technet.microsoft.com/ko-kr/library/security/ms15-057)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://technet.microsoft.com/ko-kr/library/security/ms15-060)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://technet.microsoft.com/ko-kr/library/security/ms15-061)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://technet.microsoft.com/ko-kr/library/security/ms15-062)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://technet.microsoft.com/ko-kr/library/security/ms15-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
(보통)  
Internet Explorer 8  
(3058515)  
(보통)  
Internet Explorer 9  
(3058515)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3062577)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3063858)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
(보통)  
Internet Explorer 8  
(3058515)  
(보통)  
Internet Explorer 9  
(3058515)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3062577)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3063858)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3063858)  
(중요)

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
[**MS15-056**](https://technet.microsoft.com/ko-kr/library/security/ms15-056)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://technet.microsoft.com/ko-kr/library/security/ms15-057)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://technet.microsoft.com/ko-kr/library/security/ms15-060)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://technet.microsoft.com/ko-kr/library/security/ms15-061)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://technet.microsoft.com/ko-kr/library/security/ms15-062)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://technet.microsoft.com/ko-kr/library/security/ms15-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
(긴급)  
Internet Explorer 9  
(3058515)  
(긴급)  
Internet Explorer 10  
(3058515)  
(긴급)  
Internet Explorer 11  
(3058515)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(3033890)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3063858)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
(긴급)  
Internet Explorer 9  
(3058515)  
(긴급)  
Internet Explorer 10  
(3058515)  
(긴급)  
Internet Explorer 11  
(3058515)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(3033890)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3063858)  
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
[**MS15-056**](https://technet.microsoft.com/ko-kr/library/security/ms15-056)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://technet.microsoft.com/ko-kr/library/security/ms15-057)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://technet.microsoft.com/ko-kr/library/security/ms15-060)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://technet.microsoft.com/ko-kr/library/security/ms15-061)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://technet.microsoft.com/ko-kr/library/security/ms15-062)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://technet.microsoft.com/ko-kr/library/security/ms15-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
(보통)  
Internet Explorer 9  
(3058515)  
(보통)  
Internet Explorer 10  
(3058515)  
(보통)  
Internet Explorer 11  
(3058515)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(3033890)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.0  
(3062577)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3063858)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3063858)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-056**](https://technet.microsoft.com/ko-kr/library/security/ms15-056)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://technet.microsoft.com/ko-kr/library/security/ms15-057)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://technet.microsoft.com/ko-kr/library/security/ms15-060)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://technet.microsoft.com/ko-kr/library/security/ms15-061)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://technet.microsoft.com/ko-kr/library/security/ms15-062)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://technet.microsoft.com/ko-kr/library/security/ms15-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3058515)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3063858)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3058515)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3063858)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3057839)  
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
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3057839)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-056**](https://technet.microsoft.com/ko-kr/library/security/ms15-056)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://technet.microsoft.com/ko-kr/library/security/ms15-057)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://technet.microsoft.com/ko-kr/library/security/ms15-060)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://technet.microsoft.com/ko-kr/library/security/ms15-061)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://technet.microsoft.com/ko-kr/library/security/ms15-062)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://technet.microsoft.com/ko-kr/library/security/ms15-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3058515)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
Active Directory Federation Services 2.1  
(3062577)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3063858)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3057839)  
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
<td style="border:1px solid black;" colspan="7">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-056**](https://technet.microsoft.com/ko-kr/library/security/ms15-056)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://technet.microsoft.com/ko-kr/library/security/ms15-057)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://technet.microsoft.com/ko-kr/library/security/ms15-060)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://technet.microsoft.com/ko-kr/library/security/ms15-061)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://technet.microsoft.com/ko-kr/library/security/ms15-062)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://technet.microsoft.com/ko-kr/library/security/ms15-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3058515)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(3063858)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3057839)  
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
<td style="border:1px solid black;" colspan="7">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-056**](https://technet.microsoft.com/ko-kr/library/security/ms15-056)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://technet.microsoft.com/ko-kr/library/security/ms15-057)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://technet.microsoft.com/ko-kr/library/security/ms15-060)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://technet.microsoft.com/ko-kr/library/security/ms15-061)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://technet.microsoft.com/ko-kr/library/security/ms15-062)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://technet.microsoft.com/ko-kr/library/security/ms15-063)

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
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3063858)  
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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3063858)  
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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3063858)  
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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3063858)  
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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3059317)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3057839)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 
### Microsoft Server 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-064**](https://technet.microsoft.com/ko-kr/library/security/ms15-064)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 서비스 팩 1  
(3062157)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 8

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 8  
(3062157)  
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
[**MS15-059**](https://technet.microsoft.com/ko-kr/library/security/ms15-059)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(2863812)  
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
[**MS15-059**](https://technet.microsoft.com/ko-kr/library/security/ms15-059)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(2863817)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(2863817)  
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
[**MS15-059**](https://technet.microsoft.com/ko-kr/library/security/ms15-059)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(3039749)  
(중요)  
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(3039782)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)  
(3039749)  
(중요)  
Microsoft Office 2013 서비스 팩 1(64비트 버전)  
(3039782)  
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
[**MS15-059**](https://technet.microsoft.com/ko-kr/library/security/ms15-059)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1  
(3039749)  
(중요)  
Microsoft Office 2013 RT 서비스 팩 1  
(3039782)  
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

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약성 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://technet.microsoft.com/ko-kr/security/dn467918)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

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

-   V1.0(2015년 6월 10일): 공지 요약이 게시되었습니다.

*2015-06-05 16:28Z-07:00에 페이지가 생성되었습니다.*
