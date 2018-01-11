---
TOCTitle: 'MS11-SEP'
Title: Microsoft Security Bulletin Summary for 9월 2011
ms:assetid: 'ms11-sep'
ms:contentKeyID: 61230744
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms11-sep(v=Security.10)'
---


Microsoft Security Bulletin Summary for 9월 2011
================================================

게시된 날짜: 2011년 9월 14일 수요일

**버전:** 1.1

이 공지 요약 목록에는 2011년 9월 발표된 보안 공지가 포함되어 있습니다.

2011년 9월 보안 공지 발표와 함께 이 공지 요약이 2011년 9월 8일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2011년 9월 14일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [9월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487951). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://go.microsoft.com/fwlink/?linkid=217214) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타정보** 섹션을 참조하십시오.

### 공지 정보

요약
----

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향을받는소프트웨어및다운로드위치**를 참조하십시오.

 
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-070">MS11-070</a></td>
<td style="border:1px solid black;"><strong>WINS의취약점으로인한권한상승문제점(2571621)</strong> <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 WINS(Windows Internet Name Service)의 취약점 1건을 해결합니다. 이러한 취약점은 사용자가 WINS 서비스가 실행되는 영향 받은 시스템에서 특수하게 조작된 WINS 복제 패킷을 수신할 경우에 권한이 상승되도록 합니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-071">MS11-071</a></td>
<td style="border:1px solid black;"><strong>Windows Components의취약점으로인한원격코드실행문제점(2570947)</strong> <br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 DLL(동적 연결 라이브러리) 파일과 동일한 네트워크 디렉터리에 있는 합법적인 서식 있는 텍스트 형식 파일(.rtf), 텍스트 파일(.txt) 또는 Word 문서(.doc)를 열 경우 원격 코드가 실행될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-072">MS11-072</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel의취약점으로인한원격코드실행문제점(2587505)</strong> <br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 5건을 해결합니다. 사용자가 특수하게 조작된 Excel 파일을 열면 이러한 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 의심되는 파일을 열지 못하도록 Office 파일 유효성 검사(OFV)를 설치하고 구성하면 CVE-2011-1986 및 CVE-2011-1987에 설명된 취약점을 악용하는 공격 경로가 차단됩니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server 소프트웨어</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-073">MS11-073</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office의취약점으로인한원격코드실행문제점(2587634)</strong> <br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 Office 파일을 열거나 특수하게 조작된 라이브러리 파일과 동일한 네트워크 디렉터리에 있는 합법적인 Office 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-074">MS11-074</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint의취약점으로인한권한상승문제점(2451858)</strong><br />
<br />
이 보안 업데이트는 Microsoft SharePoint 및 Windows SharePoint Services에서 발견되어 공개적으로 보고된 취약점 5건과 비공개적으로 보고된 취약점 1건을 해결합니다. 대부분의 심각한 취약점으로 인해 사용자가 특수하게 조작된 URL을 클릭하거나 특수하게 조작된 웹 사이트를 방문할 경우 권한 상승 문제가 발생할 수 있습니다. 대부분의 심각한 취약점의 경우 인터넷 영역에서 SharePoint 사이트를 검색하는 Internet Explorer 8 및 Internet Explorer 9 사용자는 기본적으로 Internet Explorer 8 및 Internet Explorer 9의 XSS 필터가 인터넷 영역의 공격을 차단하는 데 도움을 주기 때문에 위험이 덜합니다. 그러나 Internet Explorer 8 및 Internet Explorer 9의 XSS 필터는 인트라넷 영역에서는 기본적으로 사용되지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server 소프트웨어</td>
</tr>
</tbody>
</table>
 

악용 가능성 인덱스
------------------

다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.

**이표를어떻게사용합니까?**

이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/security/cc998259.aspx)를 참조하십시오.

아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >공지 번호</th>
<th style="border:1px solid black;" >취약점 제목</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >최신 소프트웨어 버전에 대한 코드 실행 악용 가능성 평가</th>
<th style="border:1px solid black;" >이전 소프트웨어 버전에 대한 코드 실행 악용 가능성 평가</th>
<th style="border:1px solid black;" >서비스 거부 악용 가능성 평가</th>
<th style="border:1px solid black;" >주요 정보</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-070">MS11-070</a></td>
<td style="border:1px solid black;">WINS 로컬 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1984">CVE-2011-1984 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-071">MS11-071</a></td>
<td style="border:1px solid black;">Windows 구성 요소의 안전하지 않은 라이브러리 로드 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1991">CVE-2011-1991 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-072">MS11-072</a></td>
<td style="border:1px solid black;">무료 WriteAV 후 Excel 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1986">CVE-2011-1986 (영문)</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-072">MS11-072</a></td>
<td style="border:1px solid black;">Excel 범위 초과 배열 인덱싱 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1987">CVE-2011-1987 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-072">MS11-072</a></td>
<td style="border:1px solid black;">Excel 힙 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1988">CVE-2011-1988 (영문)</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">2</a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-072">MS11-072</a></td>
<td style="border:1px solid black;">Excel 조건부 식 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1989">CVE-2011-1989 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-072">MS11-072</a></td>
<td style="border:1px solid black;">Excel 범위 초과 배열 인덱싱 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1990">CVE-2011-1990 (영문)</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-073">MS11-073</a></td>
<td style="border:1px solid black;">Office 구성 요소의 안전하지 않은 라이브러리 로드 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1980">CVE-2011-1980 (영문)</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-073">MS11-073</a></td>
<td style="border:1px solid black;">Office 초기화되지 않은 개체 포인터 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1982">CVE-2011-1982 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-074">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint 일정의 XSS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0653">CVE-2011-0653 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-074">MS11-074</a></td>
<td style="border:1px solid black;">HTML 삭제 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1252">CVE-2011-1252 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">3</a> – 악용 코드 기능 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">3</a> – 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-074">MS11-074</a></td>
<td style="border:1px solid black;">Editform 스크립트 삽입 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1890">CVE-2011-1890 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-074">MS11-074</a></td>
<td style="border:1px solid black;">연락처 정보가 변형된 XSS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1891">CVE-2011-1891 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-074">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint 원격 파일 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1892">CVE-2011-1892 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">3</a> – 악용 코드 기능 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">3</a> – 악용 코드 기능 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms11-074">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint XSS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1893">CVE-2011-1893 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259.aspx">1</a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
</tbody>
</table>
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이표를어떻게사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Windows XP</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 7</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 R2</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP 서비스 팩 3</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Professional x64 Edition 서비스 팩 2</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 서비스 팩 2</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition 서비스 팩 2</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 SP2(Itanium 기반 시스템용)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Vista 서비스 팩 2</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista x64 Edition 서비스 팩 2</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008(32비트 시스템용) 서비스 팩 2</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2008(x64 기반 시스템용) 서비스 팩 2</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1</td>
</tr>
</tbody>
</table>
  
**Windows Server 2008** **및** **Windows Server 2008 R2** **참고사항**
  
**\*Server Core** **설치가영향을받습니다.** 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)(영문) 및 [Server Core 설치 서비스](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)(영문)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.
  
#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Microsoft Office 제품군 및 구성 요소</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office for Mac</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office Groove 및 Microsoft SharePoint Workspace</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">기타 Microsoft Office 소프트웨어</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 2003 서비스 팩 3</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2007 서비스 팩 2</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 2010 및 Microsoft Office 2010 서비스 팩 1(32비트 에디션)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2010 및 Microsoft Office 2010 서비스 팩 1(64비트 에디션)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 2004 for Mac</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2008 for Mac</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office for Mac 2011</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Open XML File Format Converter for Mac</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office Groove 2007 서비스 팩 2</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft SharePoint Workspace 2010 및 Microsoft SharePoint Workspace 2010 서비스 팩 1(32비트 에디션)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft SharePoint Workspace 2010 및 Microsoft SharePoint Workspace 2010 서비스 팩 1(64비트 에디션)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Excel Viewer 서비스 팩 2</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩</td>
</tr>
</tbody>
</table>
  
**MS11-072** **참고사항**
  
<sup>[1]</sup>Microsoft Office Excel 2007 서비스 팩 2를 사용하는 고객의 경우 이 공지에서 설명한 취약점으로부터 보호하기 위해 보안 업데이트 패키지 KB2553073, KB2553089, KB2553090 이외에도 Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 서비스 팩 2용 보안 업데이트(KB2553074)를 설치해야 합니다.
  
동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을받는소프트웨어및다운로드위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.
  
**MS11-074** **참고사항**
  
동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을받는소프트웨어및다운로드위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.
  
#### Microsoft Server 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Microsoft SharePoint Server</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office Forms Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Groove Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows SharePoint Services 및 Microsoft SharePoint Foundation</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office SharePoint Server 2007 서비스 팩 2(32비트 에디션)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office SharePoint Server 2007 서비스 팩 2(64비트 에디션)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office SharePoint Server 2010 및 Microsoft Office SharePoint Server 2010 서비스 팩 1</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office Forms Server 2007 서비스 팩 2(32비트 에디션)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office Forms Server 2007 서비스 팩 2(64비트 에디션)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office Groove Data Bridge Server 2007 서비스 팩 2</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office Groove Management Server 2007 서비스 팩 2</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Groove Server 2010 및 Microsoft Groove Server 2010 서비스 팩 1</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office Web Apps 2010 및 Microsoft Office Web Apps 2010 서비스 팩 1</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지번호</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>전체심각도</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Windows SharePoint Services 2.0</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows SharePoint Services 3.0 서비스 팩 2(32비트 버전)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Windows SharePoint Services 3.0 서비스 팩 2(64비트 버전)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft SharePoint Foundation 2010 및 Microsoft SharePoint Foundation 2010 서비스 팩 1</td>
</tr>
</tbody>
</table>
  
**MS11-072** **참고사항**
  
<sup>[2]</sup>이 업데이트는 Microsoft Office SharePoint Server 2007 Enterprise 및 Microsoft Office SharePoint Server 2007 For Internet Sites와 같이 Excel Services가 설치된 서버에 적용됩니다. Microsoft Office SharePoint Server 2007 Standard에는 Excel Services가 포함되지 않습니다.
  
동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을받는소프트웨어및다운로드위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.
  
**MS11-074** **참고사항**
  
<sup>[1]</sup>지원 대상인 Microsoft Office SharePoint Server 2007 에디션의 경우 고객은 이 공지에 설명된 취약점으로부터 보호하기 위해 Microsoft Office SharePoint 2007용 보안 업데이트 패키지(KB2508964, KB2553001, KB2553002, KB2553003) 외에 Microsoft Windows SharePoint Services 3.0용 보안 업데이트(KB2493987)를 설치해야 합니다.
  
동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을받는소프트웨어및다운로드위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.
  
검색, 배포 도구 및 지침  
-----------------------
  
**보안센터**
  
해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://technet.microsoft.com/ko-kr/security/default.aspx)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.
  
보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
  
Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인 (영문)](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)을 참조하십시오.
  
마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.
  
**검색및배포지침**
  
Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.
  
**Microsoft Baseline Security Analyzer**
  
관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://technet.microsoft.com/ko-kr/security/cc184924.aspx)를 방문하십시오.
  
**Windows Server Update Services**
  
관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.
  
Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services (영문)](http://technet.microsoft.com/en-us/wsus/default.aspx)를 참조하십시오.
  
**System Center Configuration Manager 2007**
  
Configuration Manager 2007 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. Configuration Manager 2007을 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.
  
Configuration Manager 2007의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. Configuration Manager 2007의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. 관리자가 Configuration Manager 2007을 사용하여 업데이트를 배포하는 방법에 대한 자세한 내용은 [소프트웨어 업데이트 관리](http://www.microsoft.com/systemcenter/ko/kr/configuration-manager/cm-software-update-management.aspx)를 참조하십시오. Configuration Manager에 대한 자세한 내용을 보려면 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/ko/kr/configuration-manager.aspx)를 방문하십시오.
  
**Systems Management Server 2003**
  
Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.
  
**참고** System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다(이전 섹션의 **System Center Configuration Manager 2007** 참조).
  
관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter (영문)](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)를 방문하십시오.
  
**참고**SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.
  
**UCE(Update Compatibility Evaluator)** **및** **ACT(Application Compatibility Toolkit)**
  
업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (영문) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.
  
ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.
  
### 기타 정보
  
#### Microsoft Windows 악성 소프트웨어 제거 도구
  
Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.
  
#### MU, WU 및 WSUS의 비보안 업데이트
  
Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.
  
-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199)  
-   : 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.  
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (영문)  
-   . Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.
  
#### MAPP(Microsoft Active Protections Program)
  
고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201) (영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.
  
#### 보안 전략 및 커뮤니티
  
**업데이트관리전략**
  
[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.
  
**기타보안관련업데이트받기**
  
기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.
  
-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.  
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.  
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.
  
**IT Pro Security Zone Community(IT** **전문가보안영역커뮤니티)**
  
[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://technet.microsoft.com/ko-kr/security/cc136632.aspx)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.
  
#### 감사의 말
  
고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.
  
-   MS11-070에서 설명한 문제점을 보고해 주신 [Core Security Technologies (영문)](http://www.coresecurity.com/)의 Nicolas Economou  
-   MS11-072에서 설명한 문제점을 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)와 협력하여 보고해 주신 익명 연구자  
-   MS11-072에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Sean Larsson  
-   MS11-072에서 설명한 문제점을 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)와 협력하여 보고해 주신 익명 연구자  
-   MS11-072에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자  
-   MS11-072에서 설명한 문제점을 [TippingPoint(영문)의](http://www.tippingpoint.com/) [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Omair  
-   MS11-073에서 설명한 문제점을 [Secunia Research (영문)](http://secunia.com/)와 협력하여 보고해 주신 Parvez Anwar  
-   MS11-073에서 설명한 문제점을 보고해 주신 [CERT/CC (영문)](http://www.cert.org/)의 David Warren  
-   MS11-074에서 설명한 문제점을 보고해 주신 [Critical Path Training, LLC (영문)](http://www.criticalpathtraining.com/)의 Andrew Connell  
-   MS11-074에서 설명한 문제점을 보고해 주신 [Raytheon (영문)](http://www.raytheon.com/)의 David Feldman  
-   MS11-074에서 설명한 문제점을 보고해 주신 [IBM Rational Application Security (영문)](http://blog.watchfire.com/)의 Adi Cohen  
-   MS11-074에서 설명한 문제점을 해결하기 위해 협력해 주신 [Trend Micro (영문)](http://www.trendmicro.com/)  
-   MS11-074에서 설명한 문제점을 보고해 주신 [ITT (영문)](http://www.itt.com/)의 Pedro Jimenez  
-   MS11-074에서 설명한 문제점을 보고해 주신 [Seeker Automatic Application Security Testing Solution (영문)](http://www.seekersec.com/abouthacktics.html)  
-   MS11-074에서 설명한 문제점을 보고해 주신 [Agarri (불문)](http://www.agarri.fr/)의 Nicolas Grégoire  
-   MS11-074에서 설명한 문제점을 보고해 주신 [LaValley Consulting, LLC (영문)](http://www.lavalley.net/)의 Jim LaValley  
-   MS11-074의 심층 보안 업데이트에 대해 협력해 주신 [Seeker (영문)](http://www.seekersec.com/)의 Irene Abezgauz
  
#### 지원
  
-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.  
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.  
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.
  
#### 부인
  
Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.
  
#### 개정 내역
  
-   V1.0(2011년 9월 14일): 공지 요약이 게시되었습니다.  
-   V1.1(2011년 9월 14일): MS11-074에서는 Microsoft Office SharePoint Server 2010 및 Microsoft Office SharePoint Server 2010 서비스 팩 1(pplwfe)(KB2560890) 업데이트에 대한 업데이트 링크가 추가되었습니다
  
*Built at 2014-04-18T12:27:44Z-07:00*
