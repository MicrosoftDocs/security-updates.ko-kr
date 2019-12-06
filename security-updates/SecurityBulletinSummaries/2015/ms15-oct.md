---
TOCTitle: 'MS15-OCT'
Title: 2015년 10월 Microsoft 보안 공지 요약
ms:assetid: 'ms15-oct'
ms:contentKeyID: 70396606
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms15-oct(v=Security.10)'
---

2015년 10월 Microsoft 보안 공지 요약
====================================

게시된 날짜: 2015년 10월 14일 | 업데이트된 날짜: 2015년 10월 28일

**버전:** 2.0

이 공지 요약 목록에는 2015년 10월에 발표된 보안 공지가 포함되어 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://technet.microsoft.com/ko-kr/security/dd252948.aspx)을 참조하십시오.

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3096441)</strong> <br />
이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-107">MS15-107</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge용 누적 보안 업데이트(3096448) <br />
</strong>이 보안 업데이트는 Microsoft Edge의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Microsoft Edge를 사용하여 특수 제작된 웹 페이지를 볼 경우 정보 유출을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-108">MS15-108</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 JScript 및 VBScript에 대한 보안 업데이트(3089659)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 VBScript 및 JScript 스크립팅 엔진의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 공격자가 Internet Explorer를 통해 취약성을 악용하도록 디자인된 특수 제작된 웹 사이트를 호스트(또는 사용자가 제공한 콘텐츠나 광고를 허용하거나 호스트하는 웹 사이트나 공격에 노출된 웹 사이트 이용)한 다음 사용자가 이 웹 사이트를 보도록 유도하는 경우 원격 코드 실행을 허용할 수 있습니다. 또한 공격자는 사용자가 특수 제작된 웹 사이트로 이동하도록 IE 렌더링 엔진을 사용하는 Microsoft Office 문서 또는 응용 프로그램에 &quot;초기화하기 안전&quot;이라고 표시된 ActiveX 컨트롤을 포함시킬 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-109">MS15-109</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Windows Shell에 대한 보안 업데이트(3096443) <br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 사용자가 Windows에서 특수 제작된 도구 모음 개체를 열거나 공격자가 사용자에게 특수 제작된 콘텐츠를 온라인으로 보도록 유도하는 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Microsoft Office에 대한 보안 업데이트(3096440) <br />
</strong>이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 Microsoft Office 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-110">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office, <br />
Microsoft Office Services 및 Web Apps,<br />
Microsoft Server 소프트웨어 </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;"><strong>권한 상승을 해결하기 위한 Windows 커널에 대한 보안 업데이트(3096447) <br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이러한 취약성 중 더 위험한 취약성으로 인해 공격자가 영향받는 시스템에 로그온하여 특수 제작된 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>최신 소프트웨어 릴리스에 대한<br />
악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>이전 소프트웨어 릴리스에 대한<br />
악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>서비스 거부<br />
악용 가능성 평가</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">스크립팅 엔진 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2482">CVE-2015-2482(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6042">CVE-2015-6042(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6044">CVE-2015-6044(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6045">CVE-2015-6045(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6046">CVE-2015-6046(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6047">CVE-2015-6047(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6048">CVE-2015-6048(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6049">CVE-2015-6049(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6050">CVE-2015-6050(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6051">CVE-2015-6051(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">VBScript 및 JScript ASLR 우회</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6052">CVE-2015-6052(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 정보 유출 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6053">CVE-2015-6053(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">스크립팅 엔진 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6055">CVE-2015-6055(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">스크립팅 엔진 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6056">CVE-2015-6056(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">스크립팅 엔진 정보 유출 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6059">CVE-2015-6059(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-107">MS15-107</a></td>
<td style="border:1px solid black;">Microsoft Edge 정보 유출 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6057">CVE-2015-6057(영문)</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-107">MS15-107</a></td>
<td style="border:1px solid black;">Microsoft Edge XSS 필터 우회</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6058">CVE-2015-6058(영문)</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-108">MS15-108</a></td>
<td style="border:1px solid black;">스크립팅 엔진 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2482">CVE-2015-2482(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-108">MS15-108</a></td>
<td style="border:1px solid black;">VBScript 및 JScript ASLR 우회</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6052">CVE-2015-6052(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-108">MS15-108</a></td>
<td style="border:1px solid black;">스크립팅 엔진 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6055">CVE-2015-6055(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-108">MS15-108</a></td>
<td style="border:1px solid black;">스크립팅 엔진 정보 유출 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6059">CVE-2015-6059(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-109">MS15-109</a></td>
<td style="border:1px solid black;">도구 모음 해제 후 사용 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2515">CVE-2015-2515(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-109">MS15-109</a></td>
<td style="border:1px solid black;">Microsoft 태블릿 입력 밴드 해제 후 사용 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2548">CVE-2015-2548(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft Office 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2555">CVE-2015-2555(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft SharePoint 정보 유출 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2556">CVE-2015-2556(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft Office 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2557">CVE-2015-2557(영문)</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft Office 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2558">CVE-2015-2558(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft Office Web Apps XSS 스푸핑 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6037">CVE-2015-6037(영문)</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft SharePoint 보안 기능 우회 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6039">CVE-2015-6039(영문)</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;">Windows 커널 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2549">CVE-2015-2549(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;">Windows 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2550">CVE-2015-2550(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;">신뢰할 수 있는 부팅 보안 기능 우회 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2552">CVE-2015-2552(영문)</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;">Windows 탑재 지점 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2553">CVE-2015-2553(영문)</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;">Windows 개체 참조 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2554">CVE-2015-2554(영문)</a></td>
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
  
### Windows 운영 체제 및 구성 요소

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
[**MS15-106**](https://technet.microsoft.com/ko-kr/library/security/ms15-106)

</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/ko-kr/library/security/ms15-107)

</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/ko-kr/library/security/ms15-108)

</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/ko-kr/library/security/ms15-109)

</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/ko-kr/library/security/ms15-111)

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
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7                                 
(3093983)  
(긴급)  
Internet Explorer 8  
(3093983)  
(긴급)  
Internet Explorer 9  
(3093983)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음                                          

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3094996)  
(긴급)                                               

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3080446)  
(긴급)  
Windows Vista 서비스 팩 2  
(3093513)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3088195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(긴급)  
Internet Explorer 8  
(3093983)  
(긴급)  
Internet Explorer 9  
(3093983)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3094996)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3080446)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(3093513)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3088195)  
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
[**MS15-106**](https://technet.microsoft.com/ko-kr/library/security/ms15-106)

</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/ko-kr/library/security/ms15-107)

</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/ko-kr/library/security/ms15-108)

</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/ko-kr/library/security/ms15-109)

</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/ko-kr/library/security/ms15-111)

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
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(보통)  
Internet Explorer 8  
(3093983)  
(보통)  
Internet Explorer 9  
(3093983)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3094996)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3088195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(보통)  
Internet Explorer 8  
(3093983)  
(보통)  
Internet Explorer 9  
(3093983)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3094996)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3088195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
JScript 5.7 및 VBScript 5.7  
(3094996)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3088195)  
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
[**MS15-106**](https://technet.microsoft.com/ko-kr/library/security/ms15-106)

</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/ko-kr/library/security/ms15-107)

</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/ko-kr/library/security/ms15-108)

</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/ko-kr/library/security/ms15-109)

</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/ko-kr/library/security/ms15-111)

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
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3093983)  
(긴급)  
Internet Explorer 9  
(3093983)  
(긴급)  
Internet Explorer 10  
(3093983)  
(긴급)  
Internet Explorer 11  
(3093983)  
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
(3080446)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3093513)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3088195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3093983)  
(긴급)  
Internet Explorer 9  
(3093983)  
(긴급)  
Internet Explorer 10  
(3093983)  
(긴급)  
Internet Explorer 11  
(3093983)  
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
(3080446)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3093513)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3088195)  
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
[**MS15-106**](https://technet.microsoft.com/ko-kr/library/security/ms15-106)

</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/ko-kr/library/security/ms15-107)

</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/ko-kr/library/security/ms15-108)

</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/ko-kr/library/security/ms15-109)

</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/ko-kr/library/security/ms15-111)

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
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3093983)  
(보통)  
Internet Explorer 9  
(3093983)  
(보통)  
Internet Explorer 10  
(3093983)  
(보통)  
Internet Explorer 11  
(3093983)  
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
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3088195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3093983)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3088195)  
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
[**MS15-106**](https://technet.microsoft.com/ko-kr/library/security/ms15-106)

</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/ko-kr/library/security/ms15-107)

</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/ko-kr/library/security/ms15-108)

</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/ko-kr/library/security/ms15-109)

</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/ko-kr/library/security/ms15-111)

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
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3093983)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3088195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3093983)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3088195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
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
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3088195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
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
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3088195)  
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
[**MS15-106**](https://technet.microsoft.com/ko-kr/library/security/ms15-106)

</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/ko-kr/library/security/ms15-107)

</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/ko-kr/library/security/ms15-108)

</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/ko-kr/library/security/ms15-109)

</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/ko-kr/library/security/ms15-111)

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
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3093983)  
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
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3088195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
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
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3088195)  
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
[**MS15-106**](https://technet.microsoft.com/ko-kr/library/security/ms15-106)

</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/ko-kr/library/security/ms15-107)

</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/ko-kr/library/security/ms15-108)

</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/ko-kr/library/security/ms15-109)

</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/ko-kr/library/security/ms15-111)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3093983)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(3088195)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
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
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3088195)  
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
[**MS15-106**](https://technet.microsoft.com/ko-kr/library/security/ms15-106)

</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/ko-kr/library/security/ms15-107)

</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/ko-kr/library/security/ms15-108)

</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/ko-kr/library/security/ms15-109)

</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/ko-kr/library/security/ms15-111)

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
[**중요**(영문)](https://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3105210)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3097617)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3097617)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3097617)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3105210)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3097617)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3097617)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3097617)  
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
[**MS15-106**](https://technet.microsoft.com/ko-kr/library/security/ms15-106)

</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/ko-kr/library/security/ms15-107)

</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/ko-kr/library/security/ms15-108)

</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/ko-kr/library/security/ms15-109)

</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/ko-kr/library/security/ms15-111)

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
JScript 5.7 및 VBScript 5.7  
(3094996)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3088195)  
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
JScript 5.7 및 VBScript 5.7  
(3094996)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3088195)  
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
JScript 5.8 및 VBScript 5.8  
(3094995)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3088195)  
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
Windows Server 2012  
(Server Core 설치)  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3088195)  
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
Windows Server 2012 R2  
(Server Core 설치)  
(3080446)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3088195)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Microsoft Excel 2007 서비스 팩 3  
(3085615)  
(중요)  
Microsoft Visio 2007 서비스 팩 3  
(3085542)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Microsoft Excel 2010 서비스 팩 2(32비트 버전)  
(3085609)  
(중요)  
Microsoft Visio 2010 서비스 팩 2(32비트 버전)  
(3085514)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 서비스 팩 2(64비트 버전)  
(3085609)  
(중요)  
Microsoft Visio 2010 서비스 팩 2(64비트 버전)  
(3085514)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Microsoft Excel 2013 서비스 팩 1(32비트 버전)  
(3085583)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 서비스 팩 1(64비트 버전)  
(3085583)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Microsoft Excel 2013 RT 서비스 팩 1  
(3085583)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Microsoft Excel 2016(32비트 버전)  
(2920693)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016(64비트 버전)  
(2920693)  
(중요)

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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Microsoft Excel for Mac 2011  
(3097266)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3097264)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3085619)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3085618)  
(중요)

</td>
</tr>
</table>
 
**MS15-110 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오. 

### Microsoft Office Services 및 Web Apps

<p> </p>
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 버전)

</td>
<td style="border:1px solid black;">
Excel Services  
(3054994)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 버전)

</td>
<td style="border:1px solid black;">
Excel Services  
(3054994)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Excel Services  
(3085596)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Excel Services  
(3085568)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
(3085520)  
(중요)  
Microsoft Excel Web App 2010 서비스 팩 2  
(3085595)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
(3085571)  
(중요)

</td>
</tr>
</table>
 
**MS15-110 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

### Microsoft Server 소프트웨어

<p> </p>
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 버전)  
(2596670)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 버전)  
(2596670)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Microsoft SharePoint Server 2010 서비스 팩 2  
(2553405)  
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
[**MS15-110**](https://technet.microsoft.com/ko-kr/library/security/ms15-110)

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
Microsoft SharePoint Server 2013 서비스 팩 1  
(3085567)  
(중요)  
Microsoft SharePoint Foundation 2013 서비스 팩 1  
(3085582)  
(중요)

</td>
</tr>
</table>
 
**MS15-110 참고 사항**

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

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성과 특정 목적에 대한 적합성의 보증을 포함하여 명시적이거나 묵시적인 모든 보증을 부인합니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 수정 내역

-   V1.0(2015년 10월 14일): 공지 요약이 게시되었습니다.
-   V1.1(2015년 10월 15일): 악용 가능성 인덱스에서 CVE-2015-6046의 제목을 수정하기 위해 공지 요약이 개정되었습니다. 이 변경 사항은 정보 제공용입니다.
-   V1.2(2015년 10월 16일): CVE-2015-6046에 대한 악용 가능성 평가를 수정하기 위해 공지 요약이 개정되었습니다. 이 변경 사항은 정보 제공용입니다.
-   V2.0(2015년 10월 28일) MS15-106에서는 추가적인 취약성 CVE-2015-6045를 해결하는 새로운 Windows 10 누적 업데이트(3105210) 릴리스를 알리고 악용 가능성 인덱스에 이 취약성을 추가하기 위해 공지 요약이 개정되었습니다. Windows 10 시스템을 실행하는 고객만 이 새로운 업데이트를 설치해야 합니다. 이전 시스템은 영향을 받지 않거나 2015년 10월 14일 원래 업데이트의 픽스를 받았습니다. 자세한 내용 및 다운로드 링크는 Microsoft 기술 자료 문서 3105210을 참조하십시오.

*2015-10-26 22:41-07:00에 페이지가 생성되었습니다.*
