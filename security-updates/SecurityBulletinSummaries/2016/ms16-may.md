---
TOCTitle: 'MS16-MAY'
Title: 2016년 5월 Microsoft 보안 공지 요약
ms:assetid: 'ms16-may'
ms:contentKeyID: 72963811
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms16-may(v=Security.10)'
---

2016년 5월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2016년 5월 11일 | 업데이트된 날짜: 2016년 5월 26일

**버전:** 2.1

이 공지 요약 목록에는 2016년 5월 발표된 보안 공지가 포함되어 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/ko-kr/security/dd252948.aspx)을 참조하십시오.

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-051">MS16-051</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3155533)<br />
</strong>이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우 공격자가 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-052">MS16-052</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge용 누적 보안 업데이트(3155538)<br />
</strong>이 보안 업데이트는 Microsoft Edge의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Microsoft Edge를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 고객은 관리자 권한이 있는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-053">MS16-053</a></td>
<td style="border:1px solid black;"><strong>JScript 및 VBScript용 누적 보안 업데이트(3156764)<br />
</strong>이 보안 업데이트는 Microsoft Windows에서 JScript 및 VBScript 스크립팅 엔진의 취약성을 해결합니다. 이 취약성으로 인해 사용자가 특수 제작된 웹 사이트를 방문할 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우, 이 취약성 악용에 성공한 공격자는 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-054">MS16-054</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office용 보안 업데이트(3155544)<br />
</strong>이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. 사용자가 특수 제작된 Microsoft Office 파일을 열면 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 고객은 관리자 권한으로 작업하는 고객보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Office Services 및 Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-055">MS16-055</a></td>
<td style="border:1px solid black;"><strong>Microsoft 그래픽 구성 요소용 보안 업데이트(3156754)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 문서를 열거나 특수 제작된 웹 사이트를 방문하는 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-056">MS16-056</a></td>
<td style="border:1px solid black;"><strong>Windows 필기장용 보안 업데이트(3156761)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 사용자가 특수 제작된 필기장 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-057">MS16-057</a></td>
<td style="border:1px solid black;"><strong>Windows Shell용 보안 업데이트(3156987)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 공격자가 사용자 제공 온라인 콘텐츠를 수락하는 특수 제작된 웹 사이트로 이동하거나 특수 제작된 콘텐츠를 열도록 사용자를 유도하는 데 성공하는 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-058">MS16-058</a></td>
<td style="border:1px solid black;"><strong>Windows IIS용 보안 업데이트(3141083)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성은 로컬 시스템에 대한 액세스 권한을 가진 공격자가 악성 응용 프로그램을 실행하는 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-059">MS16-059</a></td>
<td style="border:1px solid black;"><strong>Windows Media Center용 보안 업데이트(3150220)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. Windows Media Center가 악성 코드를 참조하는 특수 제작된 Media Center 링크(.mcl) 파일을 여는 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-060">MS16-060</a></td>
<td style="border:1px solid black;"><strong>Windows 커널용 보안 업데이트(3154846)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 공격자가 영향받는 시스템에 로그온한 후 특수 제작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-061">MS16-061</a></td>
<td style="border:1px solid black;"><strong>Microsoft RPC용 보안 업데이트(3155520)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 인증된 공격자가 영향받는 호스트에 대한 잘못된 형식의 RPC(원격 프로시저 호출) 요청을 만드는 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-062">MS16-062</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버용 보안 업데이트(3158222)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이러한 취약성 중 더 위험한 취약성으로 인해 공격자가 영향받는 시스템에 로그온하여 특수 제작된 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-064">MS16-064</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player용 보안 업데이트(3157993)</strong><br />
이 보안 업데이트는 지원되는 모든 버전의 Windows 8.1, Windows Server 2012, Windows Server 2012 R2, Windows RT 8.1 및 Windows 10에 설치된 Adobe Flash Player의 취약성을 해결합니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-065">MS16-065</a></td>
<td style="border:1px solid black;"><strong>.NET Framework용 보안 업데이트(3156757)<br />
</strong>이 보안 업데이트는 Microsoft .NET Framework의 취약성을 해결합니다. 공격자가 대상 보안 채널에 암호화되지 않은 데이터를 삽입한 다음 대상 지정된 클라이언트와 합법적 서버 간에 MiTM(메시지 가로채기(man-in-the-middle)) 공격을 수행하는 경우 이 취약성으로 인해 정보 유출이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3156757">3156757</a></td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-066">MS16-066</a></td>
<td style="border:1px solid black;"><strong>가상 보안 모드용 보안 업데이트(3155451)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 공격자가 특수 제작된 응용 프로그램을 실행하여 Windows에서 코드 무결성 보호를 우회하는 경우 이 취약성으로 인해 보안 기능 우회가 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
보안 기능 우회</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms16-067">MS16-067</a></td>
<td style="border:1px solid black;"><strong>볼륨 관리자 드라이버용 보안 업데이트(3155784)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. Microsoft RemoteFX를 통해 RDP(원격 데스크톱 프로토콜)로 탑재된 USB 디스크가 탑재 사용자의 세션에 제대로 연결되지 않은 경우 이 취약성으로 인해 정보 유출이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
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
  
이 표를 사용하여 설치해야 할 수 있는 각 보안 업데이트에 대한 보안 공지 발표 후 30일 내 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토하십시오. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/ko-kr/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 릴리스"는 관련 소프트웨어를 나타내며 "이전 소프트웨어 릴리스"는 공지의 "영향받는 소프트웨어" 및 "영향받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 릴리스를 나타냅니다.

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

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
[**MS16-051: Internet Explorer용 누적 보안 업데이트(3155533)**](https://technet.microsoft.com/ko-kr/library/security/ms16-051)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0187(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0187)

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
[CVE-2016-0188(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0188)

</td>
<td style="border:1px solid black;">
Internet Explorer 보안 기능 우회

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
[CVE-2016-0189(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0189)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0192(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0192)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

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
[CVE-2016-0194(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0194)

</td>
<td style="border:1px solid black;">
Internet Explorer 정보 유출 취약성

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
[**MS16-052: Microsoft Edge용 누적 보안 업데이트(3155538)**](https://technet.microsoft.com/ko-kr/library/security/ms16-052)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0186(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0186)

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
[CVE-2016-0191(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0191)

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
[CVE-2016-0192(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0192)

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
[CVE-2016-0193(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0193)

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
[**MS16-053: JScript 및 VBScript용 누적 보안 업데이트(3156764)**](https://technet.microsoft.com/ko-kr/library/security/ms16-053)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0187(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0187)

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
[CVE-2016-0189(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0189)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

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
[**MS16-054: Microsoft Office용 보안 업데이트(3155544)**](https://technet.microsoft.com/ko-kr/library/security/ms16-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0126(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0126)

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
[CVE-2016-0140(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0140)

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
[CVE-2016-0183(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0183)

</td>
<td style="border:1px solid black;">
Microsoft Office 그래픽 RCE 취약성

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
[CVE-2016-0198(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0198)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-055: Microsoft 그래픽 구성 요소용 보안 업데이트(3156754)**](https://technet.microsoft.com/ko-kr/library/security/ms16-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0168(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0168)

</td>
<td style="border:1px solid black;">
Windows 그래픽 구성 요소 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
임시

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0169(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0169)

</td>
<td style="border:1px solid black;">
Windows 그래픽 구성 요소 정보 유출 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
임시

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0170(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0170)

</td>
<td style="border:1px solid black;">
Windows 그래픽 구성 요소 RCE 취약성

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
[CVE-2016-0184(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0184)

</td>
<td style="border:1px solid black;">
Direct3D 해제 후 사용 취약성

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
[CVE-2016-0195(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0195)

</td>
<td style="border:1px solid black;">
Windows 이미징 구성 요소 메모리 손상 취약성

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
[**MS16-056: Windows 필기장용 보안 업데이트(3156761)**](https://technet.microsoft.com/ko-kr/library/security/ms16-056)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0182(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0182)

</td>
<td style="border:1px solid black;">
필기장 메모리 손상 취약성

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
<td style="border:1px solid black;" colspan="5">
[**MS16-057: Windows Shell용 보안 업데이트(3156987)**](https://technet.microsoft.com/ko-kr/library/security/ms16-057)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0179(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0179)

</td>
<td style="border:1px solid black;">
Windows Shell 원격 코드 실행 취약성

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
[**MS16-058: Windows IIS용 보안 업데이트(3141083)**](https://technet.microsoft.com/ko-kr/library/security/ms16-058)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0152(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0152)

</td>
<td style="border:1px solid black;">
Windows DLL 로드 원격 코드 실행 취약성

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
[**MS16-059: Windows Media Center용 보안 업데이트(3150220)**](https://technet.microsoft.com/ko-kr/library/security/ms16-059)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0185(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0185)

</td>
<td style="border:1px solid black;">
Windows Media Center 원격 코드 실행 취약성

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
[**MS16-060: Windows 커널용 보안 업데이트(3154846)**](https://technet.microsoft.com/ko-kr/library/security/ms16-060)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0180(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0180)

</td>
<td style="border:1px solid black;">
Windows 커널 권한 상승 취약성

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
[**MS16-061: Microsoft RPC용 보안 업데이트(3155520)**](https://technet.microsoft.com/ko-kr/library/security/ms16-061)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0178(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0178)

</td>
<td style="border:1px solid black;">
RPC 네트워크 데이터 표시 엔진 원격 코드 실행 취약성

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
[**MS16-062: Windows 커널 모드 드라이버용 보안 업데이트(3158222)**](https://technet.microsoft.com/ko-kr/library/security/ms16-062)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0171(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0171)

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
[CVE-2016-0173(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0173)

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
[CVE-2016-0174(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0174)

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
[CVE-2016-0175(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0175)

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
[CVE-2016-0176(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0176)

</td>
<td style="border:1px solid black;">
Microsoft DirectX Graphics 커널 하위 시스템 권한 상승 취약성

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
[CVE-2016-0196(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0196)

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
[CVE-2016-0197(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0197)

</td>
<td style="border:1px solid black;">
Microsoft DirectX Graphics 커널 하위 시스템 권한 상승 취약성

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
<td style="border:1px solid black;" colspan="5">
[**MS16-064: Adobe Flash Player용 보안 업데이트(3157993)**](https://technet.microsoft.com/ko-kr/library/security/ms16-064)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-15](https://helpx.adobe.com/kr/security/products/flash-player/apsb16-15.html)

</td>
<td style="border:1px solid black;">
취약성 심각도 및 업데이트 우선 순위 등급은 [Adobe 보안 공지 APSB16-15](https://helpx.adobe.com/kr/security/products/flash-player/apsb16-15.html)를 참조하십시오.

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
[**MS16-065: .NET Framework용 보안 업데이트(3156757)**](https://technet.microsoft.com/ko-kr/library/security/ms16-065)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0149(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0149)

</td>
<td style="border:1px solid black;">
TLS/SSL 정보 유출 취약성

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
<td style="border:1px solid black;" colspan="5">
[**MS16-066: 가상 보안 모드용 보안 업데이트(3155451)**](https://technet.microsoft.com/ko-kr/library/security/ms16-066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0181(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0181)

</td>
<td style="border:1px solid black;">
하이퍼바이저 코드 무결성 보안 기능 우회

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
<td style="border:1px solid black;" colspan="5">
[**MS16-067: 볼륨 관리자 드라이버용 보안 업데이트(3155784)**](https://technet.microsoft.com/ko-kr/library/security/ms16-067)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0190(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0190)

</td>
<td style="border:1px solid black;">
원격 데스크톱 프로토콜 드라이브 리디렉션 정보 유출 취약성

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
</table>
 

영향받는 소프트웨어
-------------------

<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.

**참고** 단일 취약성에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 ID로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

 

### Windows 운영 체제 및 구성 요소(표 1/2)

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/ko-kr/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/ko-kr/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/ko-kr/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/ko-kr/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/ko-kr/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/ko-kr/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/ko-kr/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/ko-kr/library/security/ms16-059)

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
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3156013)  
(긴급)  
Windows Vista 서비스 팩 2  
(3156016)  
(긴급)  
Windows Vista 서비스 팩 2  
(3156019)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3155178)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3141083)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3150220)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3156013)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(3156016)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(3156019)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3155178)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3141083)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3150220)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/ko-kr/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/ko-kr/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/ko-kr/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/ko-kr/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/ko-kr/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/ko-kr/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/ko-kr/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/ko-kr/library/security/ms16-059)

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
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
Internet Explorer 9  
(3154070)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3156013)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3156016)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3156019)  
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
(3141083)  
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
Internet Explorer 9  
(3154070)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3156013)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3156016)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3156019)  
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
(3141083)  
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
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3156013)  
(긴급)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3156019)  
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
(3141083)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/ko-kr/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/ko-kr/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/ko-kr/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/ko-kr/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/ko-kr/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/ko-kr/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/ko-kr/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/ko-kr/library/security/ms16-059)

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
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3156016)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3156019)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3155178)  
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
(3150220)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3156016)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3156019)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3155178)  
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
(3150220)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/ko-kr/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/ko-kr/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/ko-kr/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/ko-kr/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/ko-kr/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/ko-kr/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/ko-kr/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/ko-kr/library/security/ms16-059)

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
**없음**

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
Internet Explorer 11  
(3154070)  
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
(3156013)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3156016)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3156019)  
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
(3156013)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3156016)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3156019)  
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
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/ko-kr/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/ko-kr/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/ko-kr/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/ko-kr/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/ko-kr/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/ko-kr/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/ko-kr/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/ko-kr/library/security/ms16-059)

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
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(긴급)  
Windows 8.1(32비트 시스템용)  
(3156016)  
(긴급)  
Windows 8.1(32비트 시스템용)  
(3156019)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3155178)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3156059)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3150220)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(긴급)  
Windows 8.1(x64 기반 시스템용)  
(3156016)  
(긴급)  
Windows 8.1(x64 기반 시스템용)  
(3156019)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3155178)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3156059)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3150220)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/ko-kr/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/ko-kr/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/ko-kr/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/ko-kr/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/ko-kr/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/ko-kr/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/ko-kr/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/ko-kr/library/security/ms16-059)

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
**없음**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3154070)  
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
(3156013)  
(긴급)  
Windows Server 2012  
(3156016)  
(긴급)  
Windows Server 2012  
(3156019)  
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
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(긴급)  
Windows Server 2012 R2  
(3156016)  
(긴급)  
Windows Server 2012 R2  
(3156019)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3156059)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/ko-kr/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/ko-kr/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/ko-kr/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/ko-kr/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/ko-kr/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/ko-kr/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/ko-kr/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/ko-kr/library/security/ms16-059)

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
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(긴급)  
Windows RT 8.1  
(3156016)  
(긴급)  
Windows RT 8.1  
(3156019)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3155178)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3156059)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/ko-kr/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/ko-kr/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/ko-kr/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/ko-kr/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/ko-kr/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/ko-kr/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/ko-kr/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/ko-kr/library/security/ms16-059)

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
**없음**

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
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156387)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156387)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3156387)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3156387)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3156387)  
(긴급)

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
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156387)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156387)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3156387)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3156387)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3156387)  
(긴급)

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
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156421)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156421)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3156421)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3156421)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3156421)  
(긴급)

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
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156421)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156421)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3156421)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3156421)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3156421)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/ko-kr/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/ko-kr/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/ko-kr/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/ko-kr/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/ko-kr/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/ko-kr/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/ko-kr/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/ko-kr/library/security/ms16-059)

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
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
VBScript 5.7  
(3158991)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3156013)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3156016)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3156019)  
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
(3141083)  
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
VBScript 5.7  
(3158991)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3156013)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3156016)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3156019)  
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
(3141083)  
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
JScript 5.8 및 VBScript 5.8  
(3155413)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3156013)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3156016)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3156019)  
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
(3156013)  
(긴급)  
Windows Server 2012(Server Core 설치)  
(3156016)  
(긴급)  
Windows Server 2012(Server Core 설치)  
(3156019)  
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
(3156013)  
(긴급)  
Windows Server 2012 R2(Server Core 설치)  
(3156016)  
(긴급)  
Windows Server 2012 R2(Server Core 설치)  
(3156019)  
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
해당 없음

</td>
</tr>
</table>
 
 

### Windows 운영 체제 및 구성 요소(표 2/2)

<p></p> 
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
[**MS16-060**](https://technet.microsoft.com/ko-kr/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/ko-kr/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/ko-kr/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/ko-kr/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/ko-kr/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/ko-kr/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/ko-kr/library/security/ms16-067)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3153199)  
(중요)  
Windows Vista 서비스 팩 2  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3142023)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(중요)  
Microsoft .NET Framework 4.6  
(3142037)  
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
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3153199)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3142023)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(중요)  
Microsoft .NET Framework 4.6  
(3142037)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/ko-kr/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/ko-kr/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/ko-kr/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/ko-kr/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/ko-kr/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/ko-kr/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/ko-kr/library/security/ms16-067)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3153199)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3142023)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(중요)  
Microsoft .NET Framework 4.6  
(3142037)  
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

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3153199)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3142023)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(중요)  
Microsoft .NET Framework 4.6  
(3142037)  
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
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3153199)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(3142023)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/ko-kr/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/ko-kr/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/ko-kr/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/ko-kr/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/ko-kr/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/ko-kr/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/ko-kr/library/security/ms16-067)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3153199)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3153199)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/ko-kr/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/ko-kr/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/ko-kr/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/ko-kr/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/ko-kr/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/ko-kr/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/ko-kr/library/security/ms16-067)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3153199)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3153199)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/ko-kr/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/ko-kr/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/ko-kr/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/ko-kr/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/ko-kr/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/ko-kr/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/ko-kr/library/security/ms16-067)

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
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3153704)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3153199)  
(중요)  
Windows 8.1(32비트 시스템용)  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
Windows 8.1(x64 기반 시스템용)  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3153704)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3153199)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/ko-kr/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/ko-kr/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/ko-kr/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/ko-kr/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/ko-kr/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/ko-kr/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/ko-kr/library/security/ms16-067)

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
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153704)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153199)  
(중요)  
Windows Server 2012  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142025)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142032)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3142035)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3155784)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153704)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153199)  
(중요)  
Windows Server 2012 R2  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3155784)  
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
[**MS16-060**](https://technet.microsoft.com/ko-kr/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/ko-kr/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/ko-kr/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/ko-kr/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/ko-kr/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/ko-kr/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/ko-kr/library/security/ms16-067)

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
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153704)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153199)  
(중요)  
Windows RT 8.1  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3142030)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/ko-kr/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/ko-kr/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/ko-kr/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/ko-kr/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/ko-kr/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/ko-kr/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/ko-kr/library/security/ms16-067)

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
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3156387)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3156387)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3156387)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156387)  
(중요)  
Microsoft .NET Framework 4.6  
(3156387)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3156387)  
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
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3156387)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3156387)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3156387)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156387)  
(중요)  
Microsoft .NET Framework 4.6  
(3156387)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3156387)  
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
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3156421)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3156421)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3156421)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156421)  
(중요)  
Microsoft .NET Framework 4.6.1  
(3156421)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3156421)  
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
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3156421)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3156421)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3156421)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156421)  
(중요)  
Microsoft .NET Framework 4.6.1  
(3156421)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3156421)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

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
[**MS16-060**](https://technet.microsoft.com/ko-kr/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/ko-kr/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/ko-kr/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/ko-kr/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/ko-kr/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/ko-kr/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/ko-kr/library/security/ms16-067)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3153199)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3156017)  
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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3153199)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3156017)  
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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3153199)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
Windows Server 2012  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3153704)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3153199)  
(중요)  
Windows Server 2012  
(Server Core 설치)  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142025)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142032)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3142035)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3155784)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3153171)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3153704)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3153199)  
(중요)  
Windows Server 2012 R2  
(Server Core 설치)  
(3156017)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(중요)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(중요)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3155784)  
(중요)

</td>
</tr>
</table>
 
 

### Microsoft Office 제품군 및 소프트웨어

<p></p> 
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
[**MS16-054**](https://technet.microsoft.com/ko-kr/library/security/ms16-054)

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
(2984938)  
(중요)  
Microsoft Office 2007 서비스 팩 3  
(2984943)  
(중요)  
Microsoft Word 2007 서비스 팩 3  
(3115116)  
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
[**MS16-054**](https://technet.microsoft.com/ko-kr/library/security/ms16-054)

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
(3115121)  
(긴급)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3054984)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3101520)  
(중요)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(3115123)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3115121)  
(긴급)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3054984)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3101520)  
(중요)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(3115123)  
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
[**MS16-054**](https://technet.microsoft.com/ko-kr/library/security/ms16-054)

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
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(3115016)  
(중요)  
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(3115025)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)  
(3115016)  
(중요)  
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(3115025)  
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
[**MS16-054**](https://technet.microsoft.com/ko-kr/library/security/ms16-054)

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
Microsoft Office 2013 RT 서비스 팩 1  
(3115016)  
(중요)  
Microsoft Word 2013 RT 서비스 팩 1  
(3115025)  
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
[**MS16-054**](https://technet.microsoft.com/ko-kr/library/security/ms16-054)

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
Microsoft Office 2016(32비트 버전)  
(3115103)  
(중요)  
Microsoft Word 2016(32비트 버전)  
(3115094)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016(64비트 버전)  
(3115103)  
(중요)  
Microsoft Word 2016(64비트 버전)  
(3115094)  
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
[**MS16-054**](https://technet.microsoft.com/ko-kr/library/security/ms16-054)

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
Microsoft Word for Mac 2011  
(3155776)  
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
[**MS16-054**](https://technet.microsoft.com/ko-kr/library/security/ms16-054)

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
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3155777)  
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
[**MS16-054**](https://technet.microsoft.com/ko-kr/library/security/ms16-054)

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
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3115115)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115132)  
(긴급)

</td>
</tr>
</table>
 
**MS16-054 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

### Microsoft Office Services 및 Web Apps

<p></p> 
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
[**MS16-054**](https://technet.microsoft.com/ko-kr/library/security/ms16-054)

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
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3115117)  
(긴급)

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
[**MS16-054**](https://technet.microsoft.com/ko-kr/library/security/ms16-054)

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
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2  
(3115124)  
(긴급)

</td>
</tr>
</table>
 
**MS16-054 참고 사항**

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
Microsoft는 신뢰할 수 있는 취약성 공개를 통해 고객을 보호하는 데 도움을 주는 보안 커뮤니티의 공로를 기립니다. 자세한 내용은 [감사의 말](https://technet.microsoft.com/ko-kr/library/security/mt674627.aspx)(영문)을 참조하십시오.

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

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약성 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침입 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://technet.microsoft.com/ko-kr/security/dn467918)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

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

-   V1.0(2016년 5월 11일): 공지 요약이 게시되었습니다.
-   V1.1(2016년 5월 12일): MS16-061의 취약성 영향을 권한 상승에서 원격 코드 실행으로 변경하고, CVE 2016-0178 제목을 RPC 네트워크 데이터 표시 엔진 원격 코드 실행 취약성으로 변경하기 위해 공지 요약이 개정되었습니다. 이 변경 사항은 정보 제공용입니다.
-   V1.2(2016년 5월 14일): MS16-067에서는 Windows 8.1 및 Windows RT 8.1에 대한 취약성 심각도를 해당 없음으로 변경하기 위해 공지 요약이 개정되었습니다. 이러한 운영 체제는 이 공지에 설명된 취약성에 의해 영향을 받지 않습니다. 보안 업데이트 3155784를 적용한 고객은 따로 조치를 취할 필요가 없습니다. 이 변경 사항은 정보 제공용입니다.
-   V2.0(2016년 5월 14일 ): MS16-064에서는 Adobe 보안 공지 APSB16-15에 포함된 취약성을 해결하는 업데이트 3163207 릴리스를 알리기 위해 공지 요약이 개정되었습니다. 업데이트 3163207은 MS16-064(업데이트 3157993)에서 이전에 릴리스된 업데이트를 대체합니다. Adobe 보안 공지 APSB16-15에 설명된 취약성으로부터 보호하는 데 도움이 되도록 업데이트 3163207을 설치하는 것이 좋습니다.
-   V2.1(2016년 5월 26일): MS16-065에서는 요약 표에 알려진 문제가 추가되었습니다. Lync Server 2010, Lync Server 2013 또는 비즈니스용 Skype 서버 2015의 프런트 엔드 서버 또는 Standard Edition Server에서 MS16-065에 포함된 보안 업데이트를 설치한 후 여러 회의 형식이 내부 사용자에 대해 더 이상 작동하지 않습니다. 이 알려진 문제의 해결 방법에 대한 자세한 내용은 [Microsoft 기술 자료 문서 3165438](https://support.microsoft.com/ko-kr/kb/3165438)을 참조하십시오.

*2016-05-25 12:52-07:00에 페이지가 생성되었습니다.*
