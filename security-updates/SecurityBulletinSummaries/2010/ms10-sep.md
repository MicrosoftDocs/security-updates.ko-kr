---
TOCTitle: 'MS10-SEP'
Title: Microsoft Security Bulletin Summary for 9월 2010
ms:assetid: 'ms10-sep'
ms:contentKeyID: 61230731
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms10-sep(v=Security.10)'
---


Microsoft Security Bulletin Summary for 9월 2010
================================================

게시된 날짜: 2010년 9월 14일 화요일 | 업데이트된 날짜: 2011년 10월 27일 목요일

**버전:** 6.1

이 공지 요약 목록에는 2010년 9월 발표된 보안 공지가 포함되어 있습니다.

2010년 9월 공지 발표와 함께 이 공지 요약이 2010년 9월 9일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2010년 9월 15일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [9월 보안 공지 웹캐스트에 지금 등록하십시오(영문)](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454433&eventcategory=4&culture=en-us&countrycode=us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약(영문)](https://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 2010년 9월 28일 오후 1:00(태평양 표준시, 미국 및 캐나다)에 이 공지 요약의 버전 3.0에 추가된 부정기 보안 공지인 MS10-070에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [9월 28일 오후 1:00 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032464130&culture=en-us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 Microsoft 보안 공지 요약 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. 기타 정보 섹션을 참조하십시오.

### 공지 정보

요약
----

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 영향을 받는 소프트웨어 및 다운로드 위치를 참조하십시오.

 
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-061">MS10-061</a></td>
<td style="border:1px solid black;">인쇄 스풀러 서비스의 취약점으로 인한 원격 코드 실행 문제점(2347290)<br />
<br />
이 보안 업데이트는 일반에 공개된 인쇄 스풀러 서비스의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 RPC를 통해 인쇄 스풀러 인터페이스가 노출된 취약한 시스템으로 특수하게 조작된 인쇄 요청을 보낼 경우 원격 코드 실행이 허용될 수 있습니다. 기본적으로 프린터는 현재 지원되는 어떤 Windows 운영 체제에서도 공유되지 않습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-062">MS10-062</a></td>
<td style="border:1px solid black;">MPEG-4 코덱의 취약점으로 인한 원격 코드 실행 문제점(975558)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 MPEG-4 코덱의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 미디어 파일을 열거나, 웹 사이트 또는 웹 콘텐츠를 제공하는 응용 프로그램으로부터 특수하게 조작된 스트리밍 콘텐츠를 받을 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-063">MS10-063</a></td>
<td style="border:1px solid black;">Unicode Scripts Processor의 취약점으로 인한 원격 코드 실행 문제점(2320113)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Unicode Scripts Processor의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 포함된 OpenType 글꼴을 지원하는 응용 프로그램을 사용하여 특수하게 조작된 문서나 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-064">MS10-064</a></td>
<td style="border:1px solid black;">Microsoft Outlook의 취약점으로 인한 원격 코드 실행 문제점(2315011)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점으로 인해 사용자가 온라인 모드에서 Exchange 서버에 연결된 영향 받는 Microsoft Outlook 버전을 사용하여 특수하게 조작된 전자 메일 메시지를 열거나 미리 볼 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-065">MS10-065</a></td>
<td style="border:1px solid black;">Microsoft IIS(인터넷 정보 서비스)의 취약점으로 인한 원격 코드 실행 문제점(2267960)<br />
<br />
이 보안 업데이트는 IIS(인터넷 정보 서비스)에 대해 비공개적으로 보고된 취약점 2건과 공개된 취약점 1건을 해결합니다. 이 중 가장 심각한 취약점으로 인해 클라이언트가 특수하게 조작된 HTTP 요청을 서버로 전송할 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-066">MS10-066</a></td>
<td style="border:1px solid black;">원격 프로시저 호출의취약점으로 인한 원격 코드 실행 문제점(982802)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 보안 업데이트의 심각도는 지원 대상인 모든 Windows XP 및 Windows Server 2003 에디션에 대해 중요입니다. 지원 대상인 모든 Windows Vista, Windows Server 2008, Windows 7 및 Windows Server 2008 R2 에디션은 이 취약점의 영향을 받지 않습니다.<br />
<br />
이 취약점으로 인해 공격자가 특수하게 조작된 RPC 응답을 클라이언트가 시작한 RPC 요청에 보낼 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 임의 코드를 실행하여 영향을 받는 시스템을 완전히 제어할 수 있습니다. 공격자는 사용자가 공격자에 의해 제어되는 악의적인 서버로의 RPC 연결을 시작하도록 유도해야 합니다. 공격자는 사용자 조작 없이 이 취약점을 원격으로 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-067">MS10-067</a></td>
<td style="border:1px solid black;">WordPad 텍스트 변환기의 취약점으로 인한 원격 코드 실행 문제점(2259922)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 보안 업데이트의 심각도는 지원 대상인 모든 Windows XP 및 Windows Server 2003 에디션에 대해 중요입니다. 지원 대상인 모든 Windows Vista, Windows Server 2008, Windows 7 및 Windows Server 2008 R2 에디션은 이 취약점의 영향을 받지 않습니다.<br />
<br />
이러한 취약점으로 인해 사용자가 WordPad를 사용하여 특수하게 조작된 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-068">MS10-068</a></td>
<td style="border:1px solid black;">로컬 보안 기관 하위 시스템 서비스의 취약점으로 인한 권한 상승 문제점(983539)<br />
<br />
이 보안 업데이트는 Active Directory, ADAM(Active Directory Application Mode) 및 AD LDS(Active Directory Lightweight Directory Service)에서 발견되어 비공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점으로 인해 인증된 공격자가 특수하게 조작된 LDAP(Lightweight Directory Access Protocol) 메시지를 수신하는 LSASS 서버에 보낼 경우 권한 상승이 허용될 수 있습니다. 공격자가 이 취약점을 성공적으로 악용하려면 대상 Windows 도메인 내의 구성원 계정이 있어야 합니다. 그러나 Windows 도메인에 참가한 워크스테이션이 있어야 할 필요는 없습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-069">MS10-069</a></td>
<td style="border:1px solid black;">Windows CSRSS(Client/Server Runtime Subsystem)의 취약점으로 인한 권한 상승 문제점(2121546)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 보안 업데이트의 심각도는 지원 대상인 모든 Windows XP 및 Windows Server 2003 에디션에 대해 중요입니다. 지원 대상인 모든 Windows Vista, Windows Server 2008, Windows 7 및 Windows Server 2008 R2 에디션은 이 취약점의 영향을 받지 않습니다.<br />
<br />
이 취약점으로 인해 공격자가 중국어, 일본어 또는 한국어 시스템 로캘로 구성된 영향 받는 시스템에 로그온할 때 권한 상승이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 프로그램을 설치하거나 데이터를 보고 변경하거나 삭제하고 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-070">MS10-070</a></td>
<td style="border:1px solid black;">ASP.NET의 취약점으로 인한 정보 유출 문제점(2418042)<br />
<br />
이 보안 업데이트는 공개적으로 보고되었으며 정보 유출을 허용할 수 있는 ASP .NET의 취약점을 해결합니다. 이 취약점 악용에 성공한 공격자는 View State와 같이 서버에서 암호화된 데이터를 읽을 수 있습니다. 이 취약점 악용에 성공한 경우 서버에서 암호화된 데이터를 해독 및 변조하는 데 사용할 수 있는 데이터 변조에도 이 취약점을 사용할 수 있습니다. Microsoft .NET Framework 3.5 서비스 팩 1 이전의 Microsoft .NET Framework 버전은 이 취약점의 파일 콘텐츠 노출 부분의 영향을 받지 않습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 악용 가능성 평가 수준 내림차순 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
이 표를어떻게 사용합니까?
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](https://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 취약점 제목                                      | CVE ID                                                                                 | 악용 가능성 인덱스 평가                                                                    | 주요 정보                                                        |  
|---------------------------------------------------------------------|--------------------------------------------------|----------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|------------------------------------------------------------------|  
| [MS10-062](https://technet.microsoft.com/security/bulletin/ms10-062) | MPEG-4 코덱 취약점                               | [CVE-2010-0818(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0818) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | Windows Vista는 추가 힙 완화로 인해 코드 실행 가능성이 낮습니다. |  
| [MS10-068](https://technet.microsoft.com/security/bulletin/ms10-068) | LSASS 힙 오버플로 취약점                         | [CVE-2010-0820(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0820) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                           |  
| [MS10-069](https://technet.microsoft.com/security/bulletin/ms10-069) | CSRSS 로컬 권한 상승 취약점                      | [CVE-2010-1891(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1891) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                           |  
| [MS10-067](https://technet.microsoft.com/security/bulletin/ms10-067) | WordPad Word 97 텍스트 변환기 메모리 손상 취약점 | [CVE-2010-2563(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2563) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                           |  
| [MS10-066](https://technet.microsoft.com/security/bulletin/ms10-066) | RPC 메모리 손상 취약점                           | [CVE-2010-2567(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2567) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                           |  
| [MS10-061](https://technet.microsoft.com/security/bulletin/ms10-061) | 인쇄 스풀러 서비스 가장 취약점                   | [CVE-2010-2729(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2729) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.            |  
| [MS10-070](https://technet.microsoft.com/security/bulletin/ms10-070) | ASP.NET 패딩 오라클 취약점                       | [CVE-2010-3332(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3332) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.            |  
| [MS10-065](https://technet.microsoft.com/security/bulletin/ms10-065) | 디렉터리 인증 우회 취약점                        | [CVE-2010-2731(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2731) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점은 공개되었습니다.                                      |  
| [MS10-063](https://technet.microsoft.com/security/bulletin/ms10-063) | Uniscribe 글꼴 구문 분석 엔진 메모리 손상 취약점 | [CVE-2010-2738(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2738) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                           |  
| [MS10-064](https://technet.microsoft.com/security/bulletin/ms10-064) | Outlook의 힙 기반 버퍼 오버플로 취약점           | [CVE-2010-2728(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2728) | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                           |  
| [MS10-065](https://technet.microsoft.com/security/bulletin/ms10-065) | 요청 헤더 버퍼 오버플로 취약점                   | [CVE-2010-2730(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2730) | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                           |  
| [MS10-065](https://technet.microsoft.com/security/bulletin/ms10-065) | IIS 반복 매개 변수 요청 서비스 거부 취약점       | [CVE-2010-1899(영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1899) | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이는 단지 서비스 거부 취약점일 뿐입니다.                         |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
참고 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-061](https://technet.microsoft.com/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](https://technet.microsoft.com/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](https://technet.microsoft.com/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](https://technet.microsoft.com/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](https://technet.microsoft.com/security/bulletin/ms10-066)
</td>
<td style="border:1px solid black;">
[MS10-067](https://technet.microsoft.com/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](https://technet.microsoft.com/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](https://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](https://technet.microsoft.com/security/bulletin/ms10-069)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=93faba6b-0a85-4acc-b527-a012bbf56b13&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=2084a01c-2a91-4650-8665-7053015f2083&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=a1d47f30-c1fc-4b9d-8829-3bad1224006a&displaylang=ko)  
(KB981322)  
(긴급)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 5.1](https://www.microsoft.com/download/details.aspx?familyid=555864c3-9114-4988-8526-7bf545a27706&displaylang=ko)  
(KB2124261)  
(중요)  
IIS 인증:  
[IIS(인터넷 정보 서비스) 5.1](https://www.microsoft.com/download/details.aspx?familyid=ae55787e-4a5c-48d5-aedf-0abada514938)  
(KB2290570)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=7ad0f2cf-03dc-49a0-a16e-17fed0c01cc6&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=fc4369ec-864a-42ae-a850-b006872241fe&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=6554f98f-4dc5-4784-b92c-b0aae1fa22ca&displaylang=ko)  
(KB982000)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=20091358-7127-4ace-bf96-4319461ad305&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46)  
(KB2418241)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780)  
(KB2416468)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)  
(KB2418240)  
(중요)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9f7f3737-056d-44bd-b644-51093b5b501b)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=284a0e80-fd03-4909-b354-0478f04585a1&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b27f310f-6ecc-4abb-8944-9fc24c66e077)  
(KB981322)  
(긴급)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 6.0](https://www.microsoft.com/download/details.aspx?familyid=0b28bfac-783d-4c89-988b-4123c0343855)  
(KB2124261)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3349b12b-621e-48bc-9c57-489c7a56920d)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7567986a-261d-4def-9fa5-c667994c7844)  
(중요)
</td>
<td style="border:1px solid black;">
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=5bc00f9a-3028-4c9d-be06-f2b78fa444c4)  
(KB982000)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=107eb958-b60f-40ae-a785-5d5b4d13d8c6)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282&displaylang=ko)  
(KB2416447)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46&displaylang=ko)  
(KB2418241)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780&displaylang=ko)  
(KB2416468)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ko)  
(KB2418240)  
(중요)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ko)  
(KB2416473)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ko)<sup>[1]</sup>
(KB2416472)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-061](https://technet.microsoft.com/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](https://technet.microsoft.com/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](https://technet.microsoft.com/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](https://technet.microsoft.com/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](https://technet.microsoft.com/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-067](https://technet.microsoft.com/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](https://technet.microsoft.com/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](https://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](https://technet.microsoft.com/security/bulletin/ms10-070)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3d79680b-c071-462f-9cea-551fbd42edf0&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0a942985-081f-455c-bf9d-4345392c91b0&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7ff7de2f-3e37-4aff-a8e4-5ed21b83575c&displaylang=ko)  
(KB981322)  
(긴급)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 6.0](https://www.microsoft.com/download/details.aspx?familyid=29e6cf4f-446b-461c-82f7-cfa8478cf739&displaylang=ko)  
(KB2124261)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f8b3004b-07db-4638-a9b7-224ff829081c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3290e7ee-1e4a-464c-abfd-17fc4108601e&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=3fe6e78c-c60a-4903-9273-27b37e129f0a&displaylang=ko)  
(KB981550)  
(중요)  
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=c42731f1-6393-42ed-b59f-5310c832fdc4&displaylang=ko)  
(KB982000)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=fd46ba66-8ca1-4aa2-b91b-9e5861a173f7&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=71f0daad-e2df-421c-9818-58e1e40cdb65&displaylang=ko)  
(KB2416451)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46&displaylang=ko)  
(KB2418241)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780&displaylang=ko)  
(KB2416468)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ko)  
(KB2418240)  
(중요)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ko)  
(KB2416473)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ko)<sup>[1]</sup>
(KB2416472)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=073b3305-4a81-4ef8-b6aa-e53b31a936b4&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=284a0e80-fd03-4909-b354-0478f04585a1&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8382c1f2-e16d-475c-a8a0-e378696808f1&displaylang=ko)  
(KB981322)  
(긴급)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 6.0](https://www.microsoft.com/download/details.aspx?familyid=750e4a79-11bf-4726-9eb4-5dd3d029a717&displaylang=ko)  
(KB2124261)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=612b2096-bd82-47ca-8b99-454c2f158d39&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b21570cc-4f90-4ed8-b901-a34584d44a63&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=22412eed-33cd-4dfc-8ef7-b74dcd7c5faf&displaylang=ko)  
(KB981550)  
(중요)  
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=79fb639d-2cc1-4bea-9df6-c67ed95890e3)  
(KB982000)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ff5976e0-579c-4e6e-a225-c0d3913cdc85&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282&displaylang=ko)  
(KB2416447)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46&displaylang=ko)  
(KB2418241)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780&displaylang=ko)  
(KB2416468)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ko)  
(KB2418240)  
(중요)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ko)  
(KB2416473)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ko)<sup>[1]</sup>
(KB2416472)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=ca35a520-c4da-41bb-abcc-d5bc534ff19a)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=be7b3310-ffb7-4528-9c9e-aebe14d264d6)  
(KB981322)  
(긴급)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 6.0](https://www.microsoft.com/download/details.aspx?familyid=f6841057-1745-44e9-a16a-c180dd941ddf)  
(KB2124261)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=1f04f151-330a-4b6c-826e-76def35daa73)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=c9c4427d-54c8-4f3c-9a94-818196cd5180)  
(중요)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=cab75c8a-0d12-4a91-82b2-9f9b70610f67)  
(KB981550)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=e450ca08-1d75-4419-ad9f-c5e5efb55cd5)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46)  
(KB2418241)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780)  
(KB2416468)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)  
(KB2418240)  
(중요)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-061](https://technet.microsoft.com/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](https://technet.microsoft.com/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](https://technet.microsoft.com/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](https://technet.microsoft.com/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](https://technet.microsoft.com/security/bulletin/ms10-066)
</td>
<td style="border:1px solid black;">
[MS10-067](https://technet.microsoft.com/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](https://technet.microsoft.com/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](https://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](https://technet.microsoft.com/security/bulletin/ms10-070)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=028977fd-0f39-42d4-9fee-0d90a2931cfd&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=84629c25-7827-40c1-86fb-7ffa247202a0&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ac1b0260-3802-45d4-985e-ac827d784e4f&displaylang=ko)  
(KB981322)  
(긴급)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 7.0](https://www.microsoft.com/download/details.aspx?familyid=75059175-9c59-45d5-81ce-09b964640e5f&displaylang=ko)  
(KB2124261)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2만 해당:  
[AD LDS(Active Directory Lightweight Directory Service)](https://www.microsoft.com/download/details.aspx?familyid=853a71f3-fb0d-43af-a2b8-45bf8ca1a588&displaylang=ko)  
(KB981550)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)  
(KB2418240)  
(중요)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(중요)  
Windows Vista 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a)  
(KB2416469)  
(중요)  
Windows Vista 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93)  
(KB2416474)  
(중요)  
Windows Vista 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2, Microsoft .NET Framework 3.5 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04)  
(KB2416470)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c68b9337-883d-4e98-ba0a-90b5cad46184&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=36e2a74b-e5c6-47d5-9cd9-b9171be63c7d&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ebfdcd6d-413e-4359-8863-e992327a607f&displaylang=ko)  
(KB981322)  
(긴급)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 7.0](https://www.microsoft.com/download/details.aspx?familyid=9864c590-10a7-4971-a717-924ed0d6cace&displaylang=ko)  
(KB2124261)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2만 해당:  
[AD LDS(Active Directory Lightweight Directory Service)](https://www.microsoft.com/download/details.aspx?familyid=566f468b-22b6-400a-a656-ae64cfcb52df&displaylang=ko)  
(KB981550)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)  
(KB2418240)  
(중요)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(중요)  
Windows Vista x64 Edition 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a)  
(KB2416469)  
(중요)  
Windows Vista x64 Edition 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93)  
(KB2416474)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2, Microsoft .NET Framework 3.5 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04)  
(KB2416470)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-061](https://technet.microsoft.com/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](https://technet.microsoft.com/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](https://technet.microsoft.com/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](https://technet.microsoft.com/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](https://technet.microsoft.com/security/bulletin/ms10-066)
</td>
<td style="border:1px solid black;">
[MS10-067](https://technet.microsoft.com/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](https://technet.microsoft.com/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](https://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](https://technet.microsoft.com/security/bulletin/ms10-070)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e2e788de-8400-4bf6-b96b-a915154aa20a&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=fdfc393e-a54d-44dd-ba45-c2a550ffd2a1&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b679fe0c-5498-4fc5-84c8-0cd24b625907&displaylang=ko)\*  
(KB981322)  
(긴급)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 7.0](https://www.microsoft.com/download/details.aspx?familyid=d798dc8e-ae64-4a1d-abda-f58cf69779d8&displaylang=ko)\*  
(KB2124261)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Active Directory 및 Active Directory Lightweight Directory Service(AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=1452befe-b7b8-4131-b36f-dded2bd16d5e&displaylang=ko)\*  
(KB981550)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)\*\*  
(KB2416447)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)\*\*  
(KB2418240)  
(중요)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)\*\*  
(KB2416473)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)\*\*<sup>[1]</sup>
(KB2416472)  
(중요)  
Windows Server 2008만(32비트 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a)\*\*  
(KB2416469)  
(중요)  
Windows Server 2008만(32비트 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93)\*\*  
(KB2416474)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2, Microsoft .NET Framework 3.5 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04)\*\*  
(KB2416470)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e08d4f49-5a13-4e1d-b0a7-27b314c2edb5&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1b7af424-6286-4a80-827c-c4df4f92fe43&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e1b38b87-24f6-4aaa-afa9-40f4015d6694&displaylang=ko)\*  
(KB981322)  
(긴급)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 7.0](https://www.microsoft.com/download/details.aspx?familyid=e29f01dc-b00d-4c12-a13e-63aa0b09d919&displaylang=ko)\*  
(KB2124261)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Active Directory 및 Active Directory Lightweight Directory Service(AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=38eb875f-1869-401b-b7d3-9f18f4ba4f24&displaylang=ko)\*  
(KB981550)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)\*\*  
(KB2416447)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)\*\*  
(KB2418240)  
(중요)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)\*\*  
(KB2416473)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)\*\*<sup>[1]</sup>
(KB2416472)  
(중요)  
Windows Server 2008만(x64 기반 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a)\*\*  
(KB2416469)  
(중요)  
Windows Server 2008만(x64 기반 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93)\*\*  
(KB2416474)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2, Microsoft .NET Framework 3.5 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04)\*\*  
(KB2416470)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)\*\*  
(KB2418240)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=098537d5-bf6e-4e04-ad33-1cde697e062f)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ceb856e8-f4a6-4229-bd26-b1a763d7d443)  
(KB981322)  
(긴급)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 7.0](https://www.microsoft.com/download/details.aspx?familyid=d595c8d2-90b1-46e4-bb9f-60efd0bf3a02)  
(KB2124261)  
(중요)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(중요)  
[Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용)만:  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a)  
(KB2416469)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용)만:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93)  
(KB2416474)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2, Microsoft .NET Framework 3.5 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04)  
(KB2416470)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-061](https://technet.microsoft.com/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](https://technet.microsoft.com/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](https://technet.microsoft.com/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](https://technet.microsoft.com/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](https://technet.microsoft.com/security/bulletin/ms10-066)
</td>
<td style="border:1px solid black;">
[MS10-067](https://technet.microsoft.com/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](https://technet.microsoft.com/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](https://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](https://technet.microsoft.com/security/bulletin/ms10-070)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=34619e9e-1f00-40e4-be6f-5bbf5e3c801b&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=5b2d42da-4dbc-4fbb-be22-09ca7dec5aa3&displaylang=ko)  
(KB2124261)  
(중요)  
IIS FastCGI:  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=c843afd9-b6f2-48de-91cc-1c0d481c2be4&displaylang=ko)  
(KB2271195)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AD LDS(Active Directory Lightweight Directory Service)](https://www.microsoft.com/download/details.aspx?familyid=454fc025-bfa2-4552-9522-3585f523ecb2&displaylang=ko)  
(KB981550)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7&displaylang=ko)  
(KB2416471)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ko)<sup>[1]</sup>
(KB2416472)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
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
해당 사항 없음
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=dbb747a5-658d-44cf-bd49-425d1700157f)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=66b64374-95e4-4b99-80e6-98dc63cd272b)  
(KB2124261)  
(중요)  
IIS FastCGI:  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=5f0c0454-cbb6-47ed-9227-98aa45b8cbdb)  
(KB2271195)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AD LDS(Active Directory Lightweight Directory Service)](https://www.microsoft.com/download/details.aspx?familyid=b15ad533-3cf1-4dcf-847c-05ebffb84e26)  
(KB981550)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7)  
(KB2416471)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472) (중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
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
해당 사항 없음
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472) (중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-061](https://technet.microsoft.com/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](https://technet.microsoft.com/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](https://technet.microsoft.com/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](https://technet.microsoft.com/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](https://technet.microsoft.com/security/bulletin/ms10-066)
</td>
<td style="border:1px solid black;">
[MS10-067](https://technet.microsoft.com/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](https://technet.microsoft.com/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](https://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](https://technet.microsoft.com/security/bulletin/ms10-070)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=11e20088-1be2-4166-9c97-234b7e9f1c4f&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=21458cce-f67e-4e95-a067-8311afefc261&displaylang=ko)\*  
(KB2124261)  
(중요)  
IIS FastCGI:  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=9578b1de-f2c1-4b37-9d82-69e929cab6f3&displaylang=ko)\*  
(KB2271195)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Active Directory 및 Active Directory Lightweight Directory Service(AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=54f36389-8be4-4a0c-9640-dc32addac9d7&displaylang=ko)\*  
(KB981550)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7)\*  
(KB2416471)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
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
해당 사항 없음
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)\*<sup>[1]</sup>
(KB2416472)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=d8c635f8-8978-44bf-b457-e07368f08ef4)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
IIS ASP:  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=3b8f3fd1-1ef4-4e9f-9bce-0c68f10519d1)  
(KB2124261)  
(중요)  
IIS FastCGI:  
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=21adf80d-267f-47cd-9c03-4b4854ba159f)  
(KB2271195)  
(중요)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7)  
(KB2416471)  
(중요)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(중요)
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
해당 사항 없음
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(중요)
</td>
</tr>
</table>
 
Windows Server 2008 및 Windows Server 2008 R2 참고 사항

\*Server Core 설치가 영향을 받습니다. 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](https://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](https://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](https://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

\*\*Server Core 설치는 영향을 받지 않습니다. Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](https://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](https://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](https://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

MS10-063 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

MS10-070 참고 사항

<sup>[1]</sup>.NET Framework 4.0 Client Profile은 영향을 받지 않습니다. .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4.0 및 .NET Framework 4.0 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4.0 Client Profile은 .NET Framework 4.0의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4.0에만 영향을 주며 .NET Framework 4.0 Client Profile에는 영향을 주지 않습니다. 자세한 내용은 [.NET Framework 설치](https://msdn.microsoft.com/ko-kr/library/5a4x27ek.aspx)를 참조하십시오.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 제품군, 시스템 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS10-063](https://technet.microsoft.com/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-064](https://technet.microsoft.com/security/bulletin/ms10-064)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=0b56f85f-d39b-410a-857a-799a5d714de7&displaylang=ko)  
(KB2288608)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=d5e85841-9dea-4776-9e0e-3cd272066f37&displaylang=ko)  
(KB2293422)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=bb7783b1-b396-4254-b317-f2292b305cfc&displaylang=ko)  
(KB2288613)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=ec8ed81e-05d0-4c20-b5fb-ebc72230a8bd&displaylang=ko)  
(KB2293428)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=44c5bccf-66dd-4796-9089-e6171d8c9785&displaylang=ko)  
(KB2288621)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6009d507-135c-4ce8-a830-925134f214dc&displaylang=ko)  
(KB2288953)  
(중요)
</td>
</tr>
</table>
 
MS10-063 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

검색, 배포 도구 및 지침
-----------------------

보안 센터

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](https://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](https://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](https://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](https://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](https://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

검색 및 배포 지침

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](https://support.microsoft.com/kb/961747)을 참조하십시오.

Microsoft Baseline Security Analyzer

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

Windows Server Update Services

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

Systems Management Server

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007(영문)](https://technet.microsoft.com/ko-kr/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](https://go.microsoft.com/fwlink/?linkid=22939)를 참조하십시오. SMS 2.0 사용자는 SUIT(Security Update Inventory Tool)을 사용하여 보안 업데이트 배포를 지원할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)를 참조하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포(영문)](https://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2.0 Administration Feature Pack(영문)](https://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit) (영문)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199)
-   : 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트(영문)](https://technet.microsoft.com/ko-kr/wsus/bb456965.aspx)
-   . Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너(영문)](https://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

업데이트 관리 전략

[업데이트 관리를 위한 보안 가이드(영문)](https://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

기타 보안 관련 업데이트 받기

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS10-061에서 설명한 문제점을 보고해 주신 [Kaspersky Lab(영문)](https://www.kaspersky.com/)의 Sergey Golovanov, Alexander Gostev, Maxim Golovkin 및 Alexey Monastyrsky와 [Design and Test Lab(영문)](https://www.dnt-lab.com/)의 Vitaly Kiktenko 및 Alexander Saprykin
-   MS10-061에서 설명한 문제점을 보고해 주신 [Symantec(영문)](https://www.symantec.com/index.jsp)의 Liam O Morchu
-   MS10-062에서 설명한 문제점을 보고해 주신 [Sourcefire VRT(영문)T](https://www.sourcefire.com/services/sf_vrt.html)의 Matthew Watchinski
-   MS10-063에서 설명한 문제점을 보고해 주신 의 Carsten Book
-   MS10-063에서 설명한 문제점을 보고해 주신 Red Hat Security Response Team의 Marc Schoenefeld
-   MS10-063의 CVE-2010-2738에 대한 악용 가능성 인덱스의 변경 사항에 대한 정보를 보고해 주신 [Secunia(영문)](https://secunia.com/)의 Carsten H. Eiram
-   MS10-064에서 설명한 문제점을 보고해 주신 [Secunia(영문)](https://secunia.com/)의 Dyon Balding
-   MS10-065에서 설명한 문제점을 보고해 주신 Jinsik Shim
-   MS10-065에서 설명한 문제점을 보고해 주신 Rubicon West의 Travis Raybold
-   MS10-066에서 설명한 문제점을 보고해 주신 [Palo Alto Networks(영문)](https://www.paloaltonetworks.com/)의 Yamata Li
-   MS10-067에서 설명한 문제점을 보고해 주신 [iDefense Labs(영문)](https://labs.idefense.com/)의 S0lute
-   MS10-069에서 설명한 문제점을 보고해 주신 [IBM Japan(영문)](https://www.ibm.com/jp/ja/)

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원(영문)](https://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](https://support.microsoft.com/korea) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](https://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2010년 9월 14일): 공지 요약이 게시되었습니다.
-   V2.0(2010년 9월 22일): CVE-2010-2738에 대한 악용 가능성 인덱스 평가의 심각도가 상향되었으며 CVE-2010-2730에 대한 악용 가능성 인덱스 평가의 심각도가 하향되고, CVE-2010-0818에 대한 악용 가능성 인덱스 주요 정보가 개정되었습니다.
-   V3.0(2010년 9월 28일): Microsoft 보안 공지 MS10-070, ASP.NET의 취약점으로 인한 정보 유출 문제점(2418042)이 추가되었습니다. 또한 이 부정기 보안 업데이트에 대한 공지 웹캐스트 링크가 추가되었습니다.
-   V4.0(2010년 9월 30일): MS10-070용 보안 업데이트가 현재 Windows Update 및 Microsoft Update를 포함한 모든 배포 채널을 통해 제공됨을 알리기 위해 이 공지 요약을 개정하였습니다. 또한 MS10-070용 업데이트 KB2418240, KB2418241, KB2416470 및 KB2416474에 대한 업데이트 설명도 개정되었습니다.
-   V4.1(2010년 11월 3일): MS10-070에서 .NET Framework 4.0 Client Profile이 영향을 받지 않는다는 것을 설명하기 위해 영향을 받는 소프트웨어 표에 참고가 추가되었습니다.
-   V5.0(2010년 12월 14일): MS10-070에서 다른 업데이트 및/또는 제품의 설공적인 설치를 방해할 수 있는 설정 문제점을 수정하는 .NET Framework 4.0에 대한 새 업데이트 패키지(KB2416472)가 제공됨을 알리기 위해 이 공지 요약을 개정하였습니다. 이미 시스템을 성공적으로 업데이트한 고객은 추가 조치를 취할 필요가 없습니다.
-   V6.0(2011년 2월 22일): MS10-070에서 검색 변경 사항은 이제 Windows 7(32비트 시스템용) 서비스 팩 1, Windows 7(x64 기반 시스템용) 서비스 팩 1, Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1 또는 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1을 설치한 후 Microsoft .NET Framework 4.0을 설치한 고객에게 Microsoft .NET Framework 4.0(KB2416472) 업데이트 패키지를 제공합니다. 이미 시스템을 성공적으로 업데이트한 고객은 추가 조치를 취할 필요가 없습니다.
-   V6.1(2011년 10월 27일): MS10-070에서 설명한 Windows Server 2008 R2(x64 기반 시스템용)의 .NET Framework 4에 대한 Server Core 설치 적용 가능성이 수정되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
