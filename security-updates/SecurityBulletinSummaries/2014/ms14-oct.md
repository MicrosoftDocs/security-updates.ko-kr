---
TOCTitle: 'MS14-OCT'
Title: 2014년 10월 Microsoft 보안 공지 요약
ms:assetid: 'ms14-oct'
ms:contentKeyID: 63172125
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms14-oct(v=Security.10)'
---

2014년 10월 Microsoft 보안 공지 요약
====================================

게시된 날짜: 2014년 10월 15일

**버전:** 1.0

이 공지 요약 목록에는 2014년 10월에 발표된 보안 공지가 포함되어 있습니다.

2014년 10월 보안 공지 발표와 함께 이 공지 요약이 2014년 10월 9일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2014년 10월 15일 오전 11시(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. 월간 웹캐스트를 보고 추가 보안 공지 웹캐스트에 대한 링크를 확인하려면 [Microsoft 보안 공지 웹캐스트](http://technet.microsoft.com/security/dn756352)를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향을 받는 소프트웨어**를 참조하십시오.

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><strong>공지 제목 및 요약</strong></td>
<td style="border:1px solid black;"><strong>최대 심각도 및 취약점 영향</strong></td>
<td style="border:1px solid black;"><strong>다시 시작 요구 사항</strong></td>
<td style="border:1px solid black;"><strong>영향을 받는 소프트웨어</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(2987107)</strong><br />
<br />
이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 14건을 해결합니다. 가장 심각한 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;"><strong>.NET Framework의 취약점으로 인한 원격 코드 실행 문제점(3000414)<br />
<br />
</strong>이 보안 업데이트는 Microsoft .NET Framework에서 발견되어 비공개적으로 보고된 취약점 3건을 해결합니다. 공격자가 .NET 웹 응용 프로그램에 국제 문자가 포함된 특수하게 조작된 URI 요청을 보낼 경우 가장 심각한 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. .NET 4.0 응용 프로그램에서 취약한 기능(iriParsing)은 기본적으로 비활성화됩니다. 취약점이 악용될 수 있기 때문에 응용 프로그램은 명시적으로 이 기능을 사용합니다. .NET 4.5 응용 프로그램에서 iriParsing은 기본적으로 활성화되어 있으며 비활성화할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></td>
<td style="border:1px solid black;"><strong>커널 모드 드라이버의 취약점으로 인한 원격 코드 실행 문제점(3000061)<br />
<br />
</strong>이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 공격자가 사용자에게 특수하게 조작된 문서를 열도록 유도하거나 포함된 TrueType 글꼴을 포함하는 신뢰할 수 없는 웹 사이트를 방문하도록 유도할 경우 가장 심각한 취약점은 원격 코드 실행을 허용할 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 이러한 작업을 수행하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 메신저 메시지의 링크를 클릭하여 공격자가 파일을 열도록 유도합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507673">MS14-059</a></td>
<td style="border:1px solid black;"><strong>ASP.NET MVC의 취약점으로 인한 보안 기능 우회(2990942)<br />
<br />
</strong>이 보안 업데이트는 ASP.NET MVC의 공개된 취약점을 해결합니다. 이 취약점으로 인해 공격자가 사용자를 특수하게 조작된 링크를 클릭하도록 유도하거나 취약점을 악용하기 위해 설계하여 특수하게 조작된 콘텐츠가 포함된 웹 페이지를 방문하도록 유도하면 보안 기능 우회가 허용될 수 있습니다. 웹 기반 공격의 경우 공격자는 웹 브라우저를 통해 이 취약점을 악용하도록 설계하여 특수하게 조작된 웹 사이트를 호스팅한 다음 사용자가 이 웹 사이트를 보도록 유도할 수 있습니다. 공격자는 사용자가 제공한 콘텐츠가 광고를 허용하거나 호스팅하는 웹 사이트와 공격에 노출된 웹 사이트를 이용할 수도 있습니다. 이러한 웹 사이트에 이 취약점을 악용하는 특수하게 조작된 콘텐츠가 포함될 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 공격자 제어 콘텐츠를 보도록 만들 수는 없습니다. 대신 공격자는 사용자가 공격자의 웹 사이트에 연결되는 전자 메일 메시지나 메신저 메시지에서 링크를 클릭하게 하거나 전자 메일을 통해 보낸 첨부 파일을 열도록 하는 등의 조치를 취하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft 개발자 도구</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513097">MS14-060</a></td>
<td style="border:1px solid black;"><strong>Windows OLE의 취약점으로 인한 원격 코드 실행 문제점(3000869)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 OLE 개체를 포함하는 Microsoft Office 파일을 열 경우 원격 코드가 실행될 수 있습니다. 이 취약점 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의 코드를 실행할 수 있습니다. 현재 사용자가 관리자 권한으로 로그인한 경우 공격자는 프로그램을 설치하여 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513106">MS14-061</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word 및 Office Web Apps의 취약점으로 인한 원격 코드 실행 문제점(3000434)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 공격자가 사용자에게 특수하게 조작된 Microsoft Word 파일을 열도록 유도할 경우 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그인한 경우 공격자는 프로그램을 설치하여 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Office Services,<br />
Microsoft Office Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513107">MS14-062</a></td>
<td style="border:1px solid black;"><strong>Message Queuing 서비스의 취약점으로 인한 권한 상승 문제점(2993254)<br />
<br />
</strong>이 보안 업데이트는 Microsoft Windows의 공개된 취약점을 해결합니다. 공격자가 Message Queuing 서비스에 특수하게 조작된 IOCTL(입출력 제어) 요청을 보낼 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이 취약점의 악용에 성공하면 영향을 받는 시스템에 완전하게 액세스할 수 있습니다. 기본적으로 Message Queuing 구성 요소는 영향을 받는 운영 체제 에디션에 설치되지 않으며, 관리자 권한을 가진 사용자가 직접 설정해야만 사용할 수 있습니다. Message Queuing 구성 요소를 수동으로 설정한 고객만 이 문제에 취약할 가능성이 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513102">MS14-063</a></td>
<td style="border:1px solid black;"><strong>FAT32 디스크 파티션 드라이버의 취약점으로 인한 권한 상승 문제점(2998579)<br />
<br />
</strong>이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 권한 상승 취약점은 Windows FASTFAT 시스템 드라이버가 FAT32 디스크 파티션과 상호 작용하는 방식에 존재합니다. 이 취약점 악용에 성공한 공격자는 상승된 권한을 사용하여 임의 코드를 실행할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
악용 가능성 인덱스  
------------------
  
<span id="sectionToggle1"></span>
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.
  
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><strong>취약점 제목</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>최신 소프트웨어 버전에 대한 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>이전 소프트웨어 버전에 대한 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>서비스 거부 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>주요 정보</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4123">CVE-2014-4123</a></td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 IE 샌드박스 우회를 통한 권한 상승 취약점입니다.
Microsoft는 이 취약점을 악용하려는 제한적인 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4124">CVE-2014-4124</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 권한 상승 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4126">CVE-2014-4126</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4127">CVE-2014-4127</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4128">CVE-2014-4128</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4129">CVE-2014-4129</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4130">CVE-2014-4130</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4132">CVE-2014-4132</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4133">CVE-2014-4133</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4134">CVE-2014-4134</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4137">CVE-2014-4137</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4138">CVE-2014-4138</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR 우회 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4140">CVE-2014-4140</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 보안 기능 우회 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4141">CVE-2014-4141</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;">.NET ClickOnce 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4073">CVE-2014-4073</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 권한 상승 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;">.NET Framework 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4121">CVE-2014-4121</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;">.NET ASLR 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4122">CVE-2014-4122</a></td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 보안 기능 우회 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></td>
<td style="border:1px solid black;">Win32k.sys 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4113">CVE-2014-4113</a></td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 권한 상승 취약점입니다.<br />
<br />
Microsoft는 이 취약점을 악용하려는 제한적인 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></td>
<td style="border:1px solid black;">TrueType 글꼴 구문 분석 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4148">CVE-2014 -4148</a></td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">Microsoft는 이 취약점을 악용하려는 제한적인 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507673">MS14-059</a></td>
<td style="border:1px solid black;">MVC XSS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4075">CVE-2014-4075</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 보안 기능 우회 취약점입니다.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513097">MS14-060</a></td>
<td style="border:1px solid black;">Windows OLE 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4114">CVE-2014-4114</a></td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">Microsoft는 이 취약점을 악용하려는 제한적인 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513106">MS14-061</a></td>
<td style="border:1px solid black;">Microsoft Word 파일 형식 취약점 </td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4117">CVE-2014-4117</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513107">MS14-062</a></td>
<td style="border:1px solid black;">MQAC 임의 쓰기 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4971">CVE-2014-4971</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 권한 상승 취약점입니다.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513102">MS14-063</a></td>
<td style="border:1px solid black;">Microsoft Windows 디스크 파티션 드라이버 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4115">CVE-2014-4115</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 권한 상승 취약점입니다.</td>
</tr>
</tbody>
</table>
  
 
  
영향을 받는 소프트웨어  
----------------------
  
<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2987107)  
(보통)  
Internet Explorer 7  
(2987107)  
(보통)  
Internet Explorer 8  
(2987107)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2972105)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2979574)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2993254)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2998579)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2987107)  
(보통)  
Internet Explorer 7  
(2987107)  
(보통)  
Internet Explorer 8  
(2987107)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2972105)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2979574)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2993254)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2998579)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2987107)  
(보통)  
Internet Explorer 7  
(2987107)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2972105)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2979574)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2993254)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2998579)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(긴급)  
Internet Explorer 8  
(2987107)  
(긴급)  
Internet Explorer 9  
(2987107)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2968292)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2972098)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2979568)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3000869)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2998579)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(긴급)  
Internet Explorer 8  
(2987107)  
(긴급)  
Internet Explorer 9  
(2987107)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2968292)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2972098)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2979568)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3000869)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2998579)  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(보통)  
Internet Explorer 8  
(2987107)  
(보통)  
Internet Explorer 9  
(2987107)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2968292)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2972098)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2979568)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3000869)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2998579)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(보통)  
Internet Explorer 8  
(2987107)  
(보통)  
Internet Explorer 9  
(2987107)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2968292)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2972098)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2979568)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3000869)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2998579)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2968292)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2972098)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2979568)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3000869)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2998579)  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 8  
(2987107)  
(긴급)  
Internet Explorer 9  
(2987107)  
(긴급)  
Internet Explorer 10  
(2987107)  
(긴급)  
Internet Explorer 11  
(2987107)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3000869)  
(중요)

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
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
(긴급)  
Internet Explorer 9  
(2987107)  
(긴급)  
Internet Explorer 10  
(2987107)  
(긴급)  
Internet Explorer 11  
(2987107)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3000869)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 8  
(2987107)  
(보통)  
Internet Explorer 9  
(2987107)  
(보통)  
Internet Explorer 10  
(2987107)  
(보통)  
Internet Explorer 11  
(2987107)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3000869)  
(중요)

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
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3000869)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(중요)  
Microsoft .NET Framework 3.5  
(2972101)  
(긴급)  
Microsoft .NET Framework 3.5  
(2979571)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3000869)  
(중요)

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
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(중요)  
Microsoft .NET Framework 3.5  
(2972101)  
(긴급)  
Microsoft .NET Framework 3.5  
(2979571)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3000869)  
(중요)

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
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(중요)  
Microsoft .NET Framework 3.5  
(2972103)  
(긴급)  
Microsoft .NET Framework 3.5  
(2979573)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(긴급)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3000869)  
(중요)

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
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(중요)  
Microsoft .NET Framework 3.5  
(2972103)  
(긴급)  
Microsoft .NET Framework 3.5  
(2979573)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(긴급)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3000869)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(2987107)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(중요)  
Microsoft .NET Framework 3.5  
(2972101)  
(긴급)  
Microsoft .NET Framework 3.5  
(2979571)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3000869)  
(중요)

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
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(중요)  
Microsoft .NET Framework 3.5  
(2972103)  
(긴급)  
Microsoft .NET Framework 3.5  
(2979573)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(긴급)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3000869)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(3000869)  
(중요)

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
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(긴급)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3000869)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2998579)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3000061)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2998579)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(중요)  
Microsoft .NET Framework 4  
(2972106)  
(긴급)  
Microsoft .NET Framework 4  
(2979575)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3000061)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(중요)  
Microsoft .NET Framework 3.5  
(2972101)  
(긴급)  
Microsoft .NET Framework 3.5  
(2979571)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(긴급)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3000061)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(중요)  
Microsoft .NET Framework 3.5  
(2972103)  
(긴급)  
Microsoft .NET Framework 3.5  
(2979573)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(긴급)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3000061)  
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
</tr>
</table>
 
 

### Microsoft 개발자 도구 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**ASP.NET MVC**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-059**](http://go.microsoft.com/fwlink/?linkid=507673)

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
ASP.NET MVC 2.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 2.0  
(2993939)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 3.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 3.0  
(2993937)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 4.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 4.0  
(2993928)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 5.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 5.0  
(2992080)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 5.1

</td>
<td style="border:1px solid black;">
ASP.NET MVC 5.1  
(2994397)  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(2883031)  
(중요)  
Microsoft Word 2007 서비스 팩 3  
(2883032)  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
Microsoft Office 2010 서비스 팩 1(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)  
(2883008)  
(중요)  
Microsoft Word 2010 서비스 팩 1(32비트 에디션)  
(2883013)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)  
(2883008)  
(중요)  
Microsoft Word 2010 서비스 팩 2(32비트 에디션)  
(2883013)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)  
(2883008)  
(중요)  
Microsoft Word 2010 서비스 팩 1(64비트 에디션)  
(2883013)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)  
(2883008)  
(중요)  
Microsoft Word 2010 서비스 팩 2(64비트 에디션)  
(2883013)  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3004865)  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
(2883031)  
(중요)

</td>
</tr>
</table>
 
**MS14-061 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
Microsoft SharePoint Server 2010 서비스 팩 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883098)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883098)  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
Microsoft Office Web Apps 2010

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010  
(2889827)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010 서비스 팩 1  
(2889827)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010 서비스 팩 2  
(2889827)  
(중요)

</td>
</tr>
</table>
 
**MS14-061 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

검색, 배포 도구 및 지침
-----------------------

<span id="sectionToggle3"></span>
관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 존재합니다.

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 구성 오류를 검색할 수 있습니다.

WSUS(Windows Server Update Services), SMS(Systems Management Server), System Center Configuration Manager는 관리자가 보안 업데이트를 배포하는 데 도움이 됩니다.

ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](http://technet.microsoft.com/security/cc297183)를 참조하십시오. 

감사의 말
---------

<span id="sectionToggle4"></span>
고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

**MS14-056**

-   Internet Explorer 권한 상승 취약점(CVE-2014-4123)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw
-   Internet Explorer 권한 상승 취약점(CVE-2014-4124)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4126)을 [VeriSign iDefense Labs](http://labs.idefense.com/)(영문)와 협력하여 보고해 주신 Rohit Mothe
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4127)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4128)을 [VeriSign iDefense Labs](http://labs.idefense.com/)(영문)와 협력하여 보고해 주신 Omair
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4128)을 보고해 주신 Jason Kratzer
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4129)을 보고해 주신 [Adlab of Venustech](http://www.venustech.com.cn/)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4130)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Sky
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4132)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Zhibin Hu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4132)을 [VeriSign iDefense Labs](http://labs.idefense.com/)(영문)와 협력하여 보고해 주신 Yenteasy - Security Research의 José A. Vázquez
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4133)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Zhibin Hu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4134)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Zhibin Hu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4137)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Liu Long
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4138)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 SkyLined
-   Internet Explorer ASLR 우회 취약점(CVE-2014-4140)을 보고해 주신 John Villamil(@day6reak)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4141)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Corelan](http://www.corelangcv.com/)(영문)의 Peter 'corelanc0d3r' Van Eeckhoutte

**MS14-057**

-   .NET ClickOnce 권한 상승 취약점(CVE-2014-4073)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw

**MS14-058**

-   Win32k.sys 권한 상승 취약점(CVE-2014-4113)에 대해 Microsoft와 협력해 주신 [CrowdStrike Intelligence Team](http://www.crowdstrike.com/) (영문)
-   Win32k.sys 권한 상승 취약점(CVE-2014-4113)에 대해 Microsoft와 협력해 주신 [FireEye, Inc.](http://www.fireeye.com/)(영문)
-   TrueType 글꼴 구문 분석 권한 상승 취약점(CVE-2014-4148)에 대해 Microsoft와 협력해 주신 [FireEye, Inc.](http://www.fireeye.com/)(영문)

**MS14-060**

-   Windows OLE 원격 코드 실행 취약점(CVE-2014-4114)을 보고해 주신 [iSIGHT Partners](http://www.isightpartners.com/)(영문)

**MS14-061**

-   Microsoft Word 파일 형식 취약점(CVE-2014-4117)을 [HP의](http://www.hpenterprisesecurity.com/products)(영문) [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 3S Labs

**MS14-063**

-   Windows 디스크 파티션 드라이버 권한 상승 취약점(CVE-2014-4115)을 보고해 주신 [Cisco Talos](http://www.sourcefire.com/solutions/research)(영문)의 Marcin 'Icewall' Noga

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 버전에서 Microsoft는 Windows 업데이트, Microsoft 업데이트, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 발표에서 사용할 수 없습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows 업데이트 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/wsus/bb456965). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드(영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft 업데이트](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows 업데이트를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.

IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617)

Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)

국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 개정 내역

-   V1.0(2014년 10월 15일): 공지 요약이 게시되었습니다.

*2014년 10월 10일 15:47Z-07:00에 페이지가 생성되었습니다.*
