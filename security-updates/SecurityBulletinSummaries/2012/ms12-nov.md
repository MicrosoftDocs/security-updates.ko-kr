---
TOCTitle: 'MS12-NOV'
Title: 2012년 11월 Microsoft 보안 공지 요약
ms:assetid: 'ms12-nov'
ms:contentKeyID: 61230754
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms12-nov(v=Security.10)'
---


2012년 11월 Microsoft 보안 공지 요약
====================================

게시된 날짜: 2012년 11월 13일 화요일 | 업데이트된 날짜: 2012년 11월 14일 수요일

**버전:** 2.0

이 공지 요약 목록에는 2012년 11월에 발표된 보안 공지가 포함되어 있습니다.

2012년 11월 보안 공지 발표와 함께 이 공지 요약이 2012년 11월 8일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2012년 11월 14일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [11월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522560&culture=ko-kr). 이 날짜 이후 이 웹캐스트는 [주문형](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522560&culture=ko-kr)으로 제공됩니다.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

#### 요약

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향을 받는 소프트웨어 및 다운로드 위치**를 참조하십시오.

 
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268299">MS12-071</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(2761451)<br />
<br />
</strong>이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 3건을 해결합니다. 이 취약점들은 모두 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=260820">MS12-072</a></td>
<td style="border:1px solid black;"><strong>Windows 셸의 취약점으로 인한 원격 코드 실행 문제점(2727528)</strong> <strong><br />
<br />
</strong>이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점으로 인해 사용자가 Windows 탐색기에서 특수하게 조작된 서류 가방을 찾아볼 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 현재 사용자 권한으로 임의 코드를 실행할 수 있습니다. 현재 사용자가 관리자 권한의 사용자 권한으로 로그온한 경우 공격자가 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=255026">MS12-074</a></td>
<td style="border:1px solid black;"><strong>.NET Framework의 취약점으로 인한 원격 코드 실행 문제점(2745030)</strong> <strong><br />
<br />
</strong>이 보안 업데이트는 .NET Framework에서 발견되어 비공개적으로 보고된 취약점 5건을 해결합니다. 이 중 가장 심각한 취약점으로 인해 공격자가 대상 시스템의 사용자로 하여금 악성 프록시 자동 구성 파일을 사용하도록 유도한 다음 현재 실행 중인 응용 프로그램에 코드를 주입할 경우 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=270856">MS12-075</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버의 취약점으로 인한 원격 코드 실행 문제점(2761226)</strong> <strong><br />
<br />
</strong>이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 3건을 해결합니다. 가장 위험한 취약점은 사용자가 특수하게 조작된 문서를 열거나 TrueType 글꼴 파일을 포함하는 악의적인 웹 페이지를 방문할 경우 원격 코드 실행을 허용할 수 있습니다. 공격자는 사용자가 전자 메일 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=260964">MS12-076</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel의 취약점으로 인한 원격 코드 실행 문제점(2720184)</strong> <strong><br />
<br />
</strong>이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 4건을 해결합니다. 이러한 취약점으로 인해 사용자가 영향을 받는 버전의 Microsoft Excel로 특수하게 조작된 Excel 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=258247">MS12-073</a></td>
<td style="border:1px solid black;"><strong>Microsoft IIS(인터넷 정보 서비스)의 취약점으로 인한 정보 유출 문제점(2733829)<br />
<br />
</strong>이 보안 업데이트는 Microsoft IIS(인터넷 정보 서비스)의 일반에 공개된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 가장 심각한 취약점으로 인해 공격자가 서버에 특수하게 조작된 FTP 명령을 보내면 정보 유출이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">보통</a><br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](https://technet.microsoft.com/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.
  
| 공지 번호                                                 | 취약점 제목                                           | CVE ID                                                                           | 최신 소프트웨어 버전에 대한 악용 가능성 평가                                           | 이전 소프트웨어 버전에 대한 악용 가능성 평가                                           | 서비스 거부 악용 가능성 평가 | 주요 정보                    |  
|-----------------------------------------------------------|-------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|------------------------------|------------------------------|  
| [MS12-071](https://go.microsoft.com/fwlink/?linkid=268299) | CFormElement 해제 후 사용 취약점                      | [CVE-2012-1538](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1538) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                       |  
| [MS12-071](https://go.microsoft.com/fwlink/?linkid=268299) | CTreePos 해제 후 사용 취약점                          | [CVE-2012-1539](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1539) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 임시                         | (없음)                       |  
| [MS12-071](https://go.microsoft.com/fwlink/?linkid=268299) | CTreeNode 해제 후 사용 취약점                         | [CVE-2012-4775](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4775) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                       |  
| [MS12-072](https://go.microsoft.com/fwlink/?linkid=260820) | Windows 서류 가방 정수 언더플로 취약점                | [CVE-2012-1527](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1527) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                       |  
| [MS12-072](https://go.microsoft.com/fwlink/?linkid=260820) | Windows 서류 가방 정수 오버플로 취약점                | [CVE-2012-1528](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1528) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 임시                         | (없음)                       |  
| [MS12-074](https://go.microsoft.com/fwlink/?linkid=255026) | 리플렉션 우회 취약점                                  | [CVE-2012-1895](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1895) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                       |  
| [MS12-074](https://go.microsoft.com/fwlink/?linkid=255026) | 코드 액세스 보안 정보 유출 취약점                     | [CVE-2012-1896](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1896) | 영향 받지 않음                                                                         | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 불가능      | 해당 사항 없음               | 이는 정보 유출 취약점입니다. |  
| [MS12-074](https://go.microsoft.com/fwlink/?linkid=255026) | .NET Framework의 안전하지 않은 라이브러리 로드 취약점 | [CVE-2012-2519](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2519) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                       |  
| [MS12-074](https://go.microsoft.com/fwlink/?linkid=255026) | 웹 프록시 자동 검색 취약점                            | [CVE-2012-4776](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4776) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 영구                         | (없음)                       |  
| [MS12-074](https://go.microsoft.com/fwlink/?linkid=255026) | WPF 리플렉션 최적화 취약점                            | [CVE-2012-4777](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4777) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                       |  
| [MS12-075](https://go.microsoft.com/fwlink/?linkid=270856) | Win32k 해제 후 사용 취약점                            | [CVE-2012-2530](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2530) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 영구                         | (없음)                       |  
| [MS12-075](https://go.microsoft.com/fwlink/?linkid=270856) | Win32k 해제 후 사용 취약점                            | [CVE-2012-2553](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2553) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 영구                         | (없음)                       |  
| [MS12-075](https://go.microsoft.com/fwlink/?linkid=270856) | TrueType 글꼴 구문 분석 취약점                        | [CVE-2012-2897](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2897) | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 구축 어려움 | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 구축 어려움 | 영구                         | (없음)                       |  
| [MS12-076](https://go.microsoft.com/fwlink/?linkid=260964) | Excel SerAuxErrBar 힙 오버플로 취약점                 | [CVE-2012-1885](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1885) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                       |  
| [MS12-076](https://go.microsoft.com/fwlink/?linkid=260964) | Excel 메모리 손상 취약점                              | [CVE-2012-1886](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1886) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                       |  
| [MS12-076](https://go.microsoft.com/fwlink/?linkid=260964) | Excel SST 해제 후 잘못된 길이 사용 취약점             | [CVE-2012-1887](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1887) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                       |  
| [MS12-076](https://go.microsoft.com/fwlink/?linkid=260964) | Excel 스택 오버플로 취약점                            | [CVE-2012-2543](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2543) | 영향 받지 않음                                                                         | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                       |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=fcc633d6-fe18-4220-9b68-ff1479e4dec5)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=f5472e86-2b2f-42bd-abca-6adf84973efa)  
(KB2698035)  
(Media Center Edition 2005 서비스 팩 3 및 Tablet PC Edition 2005 서비스 팩 3만 해당)  
(중요)  
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=31f2c645-b171-4f11-884b-f5056ef57b4f)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a736c3f0-0326-4a0a-9c12-f61bafa537bb)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=828699ac-eb88-4ff8-9110-69c206f5ef54)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0383bdea-53d1-4799-b380-14da1595882a)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=efe0de22-8ca3-474e-acda-7203bf66d0a3)  
(KB2698032)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=73f5dec6-ccda-426d-8d2c-a2db3e59734a)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=615a96fe-88a5-498b-ae20-bbfc43e3b652)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dc9cd62a-c42d-4c54-bc14-7abd34aeb865)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=36962e96-0eaa-45a9-b2d6-6bec3242c73e)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=e4ec19ea-06f2-4164-8e39-84f1d7a47ae7)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=205f1cf3-5431-4740-96c2-eaf019edeeeb)  
(KB2761451)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c19585e3-a358-40b0-80a3-8dbb25ba8557)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c4b3fb44-338d-48be-9981-53fa2cf3094a)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.0용 Microsoft FTP 서비스 7.0](https://www.microsoft.com/download/details.aspx?familyid=e1785af2-a211-467e-a696-d53840581bca)<sup>[1]</sup>
(KB2716513)  
(보통)  
[IIS 7.0용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=b91091d0-176f-4ff9-98d2-74768b747c3a)<sup>[1]</sup>
(KB2716513)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7e7b681c-c580-4671-a515-e5b469002c93)  
(KB2761451)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=31f5ad28-ffe9-4370-b3fc-62eb9fc0c4dd)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7a58e874-f3fc-4db8-8de0-cbfc6ebbf349)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.0용 Microsoft FTP 서비스 7.0](https://www.microsoft.com/download/details.aspx?familyid=2db93767-f364-49c6-9a03-39604173771f)<sup>[1]</sup>
(KB2716513)  
(보통)  
[IIS 7.0용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=0c499445-595f-459f-86cf-b821cbb5fa65)<sup>[1]</sup>
(KB2716513)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=0161baaa-5d7b-4442-a202-41c64a73c9a8)  
(KB2761451)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=258048b5-d992-4821-8836-72262a7b5bb7)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=17b987db-0551-45c3-aab1-0cc11ae60dcc)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.0용 Microsoft FTP 서비스 7.0](https://www.microsoft.com/download/details.aspx?familyid=cb3598ae-b647-4aaa-90fb-b4d8aa1cf211)<sup>[1]</sup>
(KB2716513)  
(보통)  
[IIS 7.0용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=8b135d6f-0f6c-4bd5-bf64-d79ae16ac6a5)<sup>[1]</sup>
(KB2716513)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=52f652bd-edc4-4450-91b4-f19401d2201c)  
(KB2761451)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1c067cb2-71a5-4f8d-9b11-243c9e5318ce)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dd9bd994-41e3-46a1-9dfb-c6d89a3ef883)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.0용 Microsoft FTP 서비스 7.0](https://www.microsoft.com/download/details.aspx?familyid=74d130a4-f42a-48af-87fc-349a1e107529)<sup>[1]</sup>
(KB2716513)  
(보통)  
[IIS 7.0용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=b061a0b0-66e2-49a2-8d20-0c5a6948aecf)<sup>[1]</sup>
(KB2716513)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=fab87b20-398f-4043-9cbe-ffcae8e19ff0)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=279ac887-2420-48d7-bb85-c7cab49f7ff8)  
(KB2761451)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=22ab8987-2506-433f-9f12-0ab60d569949)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=c222943e-9888-4fb9-b9a2-7a035311c887)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.5용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=77a4ae4e-a75c-490a-a0b1-137816ed5c89)  
(KB2716513)  
(보통)  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=fb265aa5-0e09-411a-a0fe-bbb42c409a81)  
(KB2719033)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=279ac887-2420-48d7-bb85-c7cab49f7ff8)  
(KB2761451)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=22ab8987-2506-433f-9f12-0ab60d569949)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=c222943e-9888-4fb9-b9a2-7a035311c887)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.5용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=77a4ae4e-a75c-490a-a0b1-137816ed5c89)  
(KB2716513)  
(보통)  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=fb265aa5-0e09-411a-a0fe-bbb42c409a81)  
(KB2719033)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=eb9babdc-3fac-4ce9-a7ca-85e26a9cb11d)  
(KB2761451)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=fc70708e-9de9-4618-b0ab-d9aa3e2baea0)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=50d7c25f-a67f-4946-b6db-70d9bd4dc178)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.5용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=bda21ea5-f160-4361-8ede-40f6a53a30da)  
(KB2716513)  
(보통)  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=52b6ed39-b7c1-4d49-a6a7-e6208fab24fa)  
(KB2719033)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=eb9babdc-3fac-4ce9-a7ca-85e26a9cb11d)  
(KB2761451)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=fc70708e-9de9-4618-b0ab-d9aa3e2baea0)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=50d7c25f-a67f-4946-b6db-70d9bd4dc178)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.5용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=bda21ea5-f160-4361-8ede-40f6a53a30da)  
(KB2716513)  
(보통)  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=52b6ed39-b7c1-4d49-a6a7-e6208fab24fa)  
(KB2719033)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=3d0a4455-b788-4ad7-be0c-5824f6103694)  
(KB2761451)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=800cd622-d271-41a4-bd21-a76177d2b272)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.5용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(보통)  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=3d0a4455-b788-4ad7-be0c-5824f6103694)  
(KB2761451)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=800cd622-d271-41a4-bd21-a76177d2b272)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.5용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(보통)  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=70447115-957d-48a4-bc27-395abaf22149)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.5용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=92cd0488-03c2-400d-a506-eb2eb8fce7c7)  
(KB2716513)  
(보통)  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=1eea7e7f-83bf-40fc-a978-a4d08af8162a)  
(KB2719033)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=70447115-957d-48a4-bc27-395abaf22149)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
[IIS 7.5용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=92cd0488-03c2-400d-a506-eb2eb8fce7c7)  
(KB2716513)  
(보통)  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=1eea7e7f-83bf-40fc-a978-a4d08af8162a)  
(KB2719033)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 8(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d7c93ade-f7e3-4b6f-b93d-894ca313282f)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b120a7a2-0eff-41d6-981e-60e5ecd55869)<sup>[2]</sup>
(KB2756872)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
[Windows 8(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=24ce3f78-fb25-4f51-8bb0-8cebf19d8843)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 8(64비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=7c4a17b7-bb7f-456c-9cb3-3a355e192734)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=c7a417e6-72e5-4087-bb89-fb8e7f57894c)<sup>[2]</sup>
(KB2756872)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
[Windows 8(64비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=72c49d94-757c-4da4-a895-96d0830bc667)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
**없음**
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=ad6189ae-9341-409b-a53e-486fef094fd0)  
(KB2727528)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=0a7da3d1-a0ac-42a2-9929-b6d831deb9e3)<sup>[2]</sup>
(KB2756872)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=2e69d496-25b4-4f24-97e0-47cb59c178aa)  
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
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
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**없음**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5<sup>[3]</sup>
(KB2737084)  
(중요)  
Microsoft .NET Framework 4.5<sup>[2]</sup><sup>[3]</sup>
(KB2756872)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2761226)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Server Core 설치 옵션
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
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
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](https://go.microsoft.com/fwlink/?linkid=21140)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=17b987db-0551-45c3-aab1-0cc11ae60dcc)(Server Core 설치)  
(KB2761226)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS 7.0용 Microsoft FTP 서비스 7.0](https://www.microsoft.com/download/details.aspx?familyid=cb3598ae-b647-4aaa-90fb-b4d8aa1cf211)<sup>[1]</sup>
(KB2716513)  
(보통)  
[IIS 7.0용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=8b135d6f-0f6c-4bd5-bf64-d79ae16ac6a5)<sup>[1]</sup>
(KB2716513)  
(보통)
</td>
</tr>
<tr class="alternateRow">
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dd9bd994-41e3-46a1-9dfb-c6d89a3ef883)(Server Core 설치)  
(KB2761226)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS 7.0용 Microsoft FTP 서비스 7.0](https://www.microsoft.com/download/details.aspx?familyid=74d130a4-f42a-48af-87fc-349a1e107529)<sup>[1]</sup>
(KB2716513)  
(보통)  
[IIS 7.0용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=b061a0b0-66e2-49a2-8d20-0c5a6948aecf)<sup>[1]</sup>
(KB2716513)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)(Server Core 설치)  
(KB2761226)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS 7.5용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(보통)  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(긴급)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)(Server Core 설치)  
(KB2761226)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS 7.5용 Microsoft FTP 서비스 7.5](https://www.microsoft.com/download/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(보통)  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(보통)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(긴급)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(중요)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=0a7da3d1-a0ac-42a2-9929-b6d831deb9e3)<sup>[2]</sup>
(KB2756872)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=2e69d496-25b4-4f24-97e0-47cb59c178aa)(Server Core 설치)  
(KB2761226)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**MS12-073참고 사항**

<sup>[1]</sup>이 운영 체제의 기본 FTP 서비스가 아님

**MS12-074 참고 사항**

<sup>[1]</sup>**.NET Framework 4 and .NET Framework 4 Client Profile이 영향을 받습니다.** .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4 및 .NET Framework 4 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4 Client Profile은 .NET Framework 4의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4 및 .NET Framework 4 Client Profile에 모두 영향을 줍니다. 자세한 내용은 MSDN 문서, [.NET Framework 설치](https://msdn.microsoft.com/en-us/library/5a4x27ek.aspx)를 참조하십시오.

<sup>[2]</sup>Windows 8, Windows Server 2012 및 Windows RT에서 Microsoft .NET Framework 4.5를 실행하는 고객은 이 문제점의 영향을 받지 않습니다. 2012년 10월 10일에 릴리스된 Windows 8 클라이언트 및 Windows Server 2012 일반 공개 누적 업데이트(KB2756872)에는 추가적인 심층 보안 변경 사항이 있습니다. 이 업데이트를 아직 설치하지 않은 고객은 심층 보안 대응책으로 이 업데이트를 설치하는 것이 좋습니다. 자세한 내용은 [Microsoft 기술 자료 문서 2745030](https://support.microsoft.com/kb/2745030)에서 자세한 정보 섹션을 참조하십시오. 다운로드 링크 및 추가 정보는 [Microsoft 기술 자료 문서 2756872](https://support.microsoft.com/kb/2756872)를 참조하십시오. 이 업데이트에는 보안과 관련 없는 내용이 포함되어 있습니다.

<sup>[3]</sup>Windows RT 보안 업데이트는 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해서만 제공됩니다.

**MS12-075 참고 사항**

<sup>[1]</sup>이 업데이트는 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해서만 제공됩니다.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Office 제품군 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-076**](https://go.microsoft.com/fwlink/?linkid=260964)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=5bb12b2b-a8e2-4324-afee-e4d26dbc658f)  
(KB2687481)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e12aafe1-4445-4047-ad05-3db151a6fa4e)<sup>[1]</sup>
(KB2687307)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=e12aafe1-4445-4047-ad05-3db151a6fa4e)<sup>[1]</sup>
(KB2687307)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 서비스 팩 1(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=37a1074d-bf4f-4b96-b394-1edc581748d0)  
(KB2597126)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 서비스 팩 1(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=5db02eae-966e-41a9-8b64-ddda5f8b2e2a)  
(KB2597126)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-076**](https://go.microsoft.com/fwlink/?linkid=260964)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=d3d801a2-d57f-4b4c-970a-c296bc716521)  
(KB2764048)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=0f4e073f-4fec-440d-a9bf-1e01ee9e92ad)  
(KB2764047)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
기타 Microsoft Office 소프트웨어
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-076**](https://go.microsoft.com/fwlink/?linkid=260964)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer](https://www.microsoft.com/download/details.aspx?familyid=a0917aeb-1e94-4142-bc20-5f1998ac249c)<sup>[2]</sup>
(KB2687313)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 호환 기능 팩 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=79686714-9418-4516-81c3-555fe1ea9e84)  
(KB2687311)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 호환 기능 팩 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=79686714-9418-4516-81c3-555fe1ea9e84)  
(KB2687311)  
(중요)
</td>
</tr>
</table>
 
**MS12-076 참고 사항**

<sup>[1]</sup>Microsoft Excel 2007을 사용하는 고객의 경우 이 공지에서 설명한 취약점으로부터 보호하기 위해 보안 업데이트 패키지 KB2687307 이외에도 Microsoft Office 호환 기능 팩용 보안 업데이트(KB2687311)를 설치해야 합니다.

<sup>[2]</sup>이 업데이트를 설치하기 전에 Microsoft Excel Viewer를 지원되는 서비스 팩 수준(Excel Viewer 2007 서비스 팩 2 또는 Excel Viewer 2007 서비스 팩 3)으로 업데이트해야 합니다. 지원되는 Office 뷰어에 대한 자세한 내용은 [Microsoft 기술 자료 문서 979860](https://support.microsoft.com/kb/979860)을 참조하십시오.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](https://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security TechCenter](https://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [Microsoft 안전 및 보안 센터](https://go.microsoft.com/fwlink/?linkid=85102)를 방문하거나 "보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)을 참조하십시오.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](https://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS12-001")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](https://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](https://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)를 참조하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](https://technet.microsoft.com/wsus/default)를 참조하십시오.

**SystemCenter Configuration Manager**

System Center Configuration Manager 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. System Center Configuration Manager를 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

System Center Configuration Manager의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. System Center Configuration Manager의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. System Center Configuration Manager에 대한 자세한 내용은 [System Center 기술 리소스](https://technet.microsoft.com/systemcenter/bb980621)를 참조하십시오.

**Systems Management Server 2003**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

**참고** System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](https://go.microsoft.com/fwlink/?linkid=21742) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager를 지금 사용할 수 있습니다(이전 섹션의 **System** Center Configuration Manager 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/systemcenter/bb545936)를 방문하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](https://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971)에 포함된 [UCE(Update Compatibility Evaluator)](https://technet.microsoft.com/library/cc749197) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](https://technet.microsoft.com/wsus/bb456965). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](https://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](https://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS12-071에서 설명한 문제점 2건을 [VeriSign iDefense Labs](https://labs.idefense.com/)와 협력하여 보고해 주신 spa-s3c.blogspot.com의 Jose A. Vazquez
-   MS12-071에서 설명한 문제점을 보고해 주신 [Omair](https://krash.in/)
-   MS12-071에서 설명한 문제점을 보고해 주신 [Trend Micro](https://www.trendmicro.com/)의 Cheng-da Tsai (Orange), Sung-ting Tsai 및 Ming-chieh Pan(Nanika)
-   MS12-072에서 설명한 문제점 2건을 [VeriSign iDefense Labs](https://labs.idefense.com/)와 협력하여 보고해 주신 Tal Zeltzer
-   MS12-073에서 설명한 문제점을 보고해 주신 ProDX의 Justin Royce
-   MS12-074에서 설명한 문제점 4건을 보고해 주신 Context Information Security의 James Forshaw
-   MS12-075에서 설명한 문제점을 보고해 주신 [Google Inc](https://www.google.com)의 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/)
-   MS12-075에서 설명한 문제점을 보고해 주신 [Documill](https://www.documill.com)의 Eetu Luodemaa 및 Joni Vähämäki
-   MS12-076에서 설명한 문제점을 [iDefense VCP](https://labs.idefense.com)와 협력하여 보고해 주신 Sean Larsson
-   MS12-076에서 설명한 문제점을 [iDefense VCP](https://labs.idefense.com)와 협력하여 보고해 주신 익명 연구자
-   MS12-076에서 설명한 문제점을 [iDefense VCP](https://labs.idefense.com)와 협력하여 보고해 주신 익명 연구자
-   MS12-076에서 설명한 문제점을 [HP TippingPoint](https://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](https://technet.microsoft.com/security/bb980617.aspx)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](https://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2012년 11월 13일): 공지 요약이 게시되었습니다.
-   V1.1(2012년 11월 13일): MS12-075에서 CVE-2012-2897에 대한 **악용 가능성 인덱스**의 CVE 제목 및 서비스 거부 악용 가능성 평가가 수정되었습니다.
-   V2.0(2012년 11월 14일): MS12-073에서 Windows Vista 및 Windows Server 2008의 KB2716513 업데이트가 Windows Update 및 Microsoft Update를 포함한 모든 배포 채널을 통해 제공됨을 반영하기 위해 공지 요약이 수정되었습니다. 자세한 내용은 MS12-073 공지를 참조하십시오.

*Built at 2014-04-18T12:27:44Z-07:00*
