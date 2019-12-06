---
TOCTitle: 'MS10-JUN'
Title: Microsoft Security Bulletin Summary for 6월 2010
ms:assetid: 'ms10-jun'
ms:contentKeyID: 61230726
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms10-jun(v=Security.10)'
---


Microsoft Security Bulletin Summary for 6월 2010
================================================

게시된 날짜: 2010년 6월 9일 수요일 | 업데이트된 날짜: 2011년 9월 14일 수요일

**버전:** 2.0

이 공지 요약 목록에는 2010년 6월 발표된 보안 공지가 포함되어 있습니다.

2010년 6월 공지 발표와 함께 이 공지 요약이 2010년 6월 3일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2010년 6월 9일 오전 11시(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [6월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427727&eventcategory=4&culture=en-us&countrycode=us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타정보** 섹션을 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-033">MS10-033</a></td>
<td style="border:1px solid black;"><strong>미디어압축해제의취약점으로인한원격코드실행문제점</strong> <strong>(979902)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 미디어 파일을 열거나, 웹 사이트 또는 웹 콘텐츠를 제공하는 응용 프로그램으로부터 특수하게 조작된 스트리밍 콘텐츠를 받을 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-034">MS10-034</a></td>
<td style="border:1px solid black;"><strong>ActiveX</strong> <strong>킬(Kill)</strong> <strong>비트누적보안업데이트</strong> <strong>(980195)</strong><br />
<br />
이 보안 업데이트는 Microsoft 소프트웨어에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 보안 업데이트의 심각도는 지원 대상인 모든 Microsoft Windows 2000, Windows XP, Windows Vista 및 Windows 7 에디션에 대해 긴급이며, 지원 대상인 모든 Windows Server 2003, Windows Server2008 및 Windows Server 2008 R2 에디션에 대해 보통입니다.<br />
<br />
이러한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특정 ActiveX 컨트롤을 인스턴스화하는 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 또한 이 업데이트에는 4개의 타사 ActiveX 컨트롤에 대한 킬(Kill) 비트도 포함되어 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-035">MS10-035</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer</strong> <strong>누적보안업데이트(982381)</strong><br />
<br />
이 보안 업데이트는 Internet Explorer에 대해 비공개적으로 보고된 취약점 5건과 공개된 취약점 1건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-032">MS10-032</a></td>
<td style="border:1px solid black;"><strong>Windows</strong> <strong>커널모드드라이버의취약점으로인한권한상승문제점</strong> <strong>(979559)</strong><br />
<br />
이 보안 업데이트는 Windows 커널 모드 드라이버의 공개된 취약점 2건과 비공개로 보고된 취약점 1건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 TrueType 글꼴로 렌더링된 콘텐츠를 볼 경우 권한 상승을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-036">MS10-036</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office의</strong> <strong>COM</strong> <strong>유효성검사취약점으로인한원격코드실행문제점</strong> <strong>(983235)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 COM 유효성 검사 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 Excel, Word, Visio, Publisher 또는 PowerPoint 파일을 영향을 받는 Microsoft Office 버전에서 열 경우 원격 코드 실행을 허용할 수 있습니다. 메일을 통해 취약점을 자동으로 악용할 수 없습니다. 메일 메시지를 통한 공격에 성공하려면 메일로 보낸 첨부 파일을 사용자가 열어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-037">MS10-037</a></td>
<td style="border:1px solid black;"><strong>OpenType CFF(Compact Font Format)</strong> <strong>드라이버의취약점으로인한권한상승문제점</strong> <strong>(980218)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows OpenType CFF(Compact Font Format) 드라이버의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 CFF 글꼴로 렌더링된 콘텐츠를 볼 경우 권한 상승을 허용할 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-038">MS10-038</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel의취약점으로인한원격코드실행문제점</strong> <strong>(2027452)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 14건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 특수하게 조작된 Excel 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-039">MS10-039</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint의취약점으로인한권한상승문제점</strong> <strong>(2028554)</strong><br />
<br />
이 보안 업데이트는 Microsoft SharePoint의 공개된 취약점 1건과 비공개로 보고된 취약점 2건을 해결합니다. 가장 위험한 취약점으로 인해 공격자가 대상 SharePoint 사이트의 사용자로 하여금 특수하게 조작한 링크를 클릭하도록 유도한 경우 권한 상승을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft Server 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-040">MS10-040</a></td>
<td style="border:1px solid black;"><strong>IIS(인터넷정보서비스)의취약점으로인한원격코드실행문제점</strong> <strong>(982666)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 IIS(인터넷 정보 서비스)의 취약점 1건을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 HTTP 요청을 받을 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-041">MS10-041</a></td>
<td style="border:1px solid black;"><strong>Microsoft .NET Framework의취약점으로인한변조문제점(981343)</strong><br />
<br />
이 보안 업데이트는 Microsoft .NET Framework의 공개된 취약점을 해결합니다. 이 취약점을 악용하면 서명된 XML 콘텐츠의 데이터를 탐지되지 않는 방식으로 변조할 수 있습니다. 사용자 지정 응용 프로그램에서 보안 영향은 관련 응용 프로그램이 서명된 콘텐츠를 사용하는 방식에 따라 달라집니다. 서명된 XML 메시지가 보안 채널(예: SSL)을 통해 전송되는 시나리오는 이 취약점의 영향을 받지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
변조</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 악용 가능성 평가 수준 내림차순 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이표를어떻게사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](http://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 취약점 제목                                   | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                                                                                |  
|---------------------------------------------------------------------|-----------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|  
| [MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032) | Win32k 창 생성 취약점                         | [CVE-2010-0485 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0485) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039) | Help.aspx XSS 취약점                          | [CVE-2010-0817 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0817) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점은 [Microsoft 보안 권고 983438](http://technet.microsoft.com/security/advisory/983438)에서 처음 보고되었습니다. |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 개체 스택 오버플로 취약점               | [CVE-2010-0822 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0822) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 레코드 메모리 손상 취약점               | [CVE-2010-0824 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0824) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 레코드 메모리 손상 취약점               | [CVE-2010-1245 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1245) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel RTD 메모리 손상 취약점                  | [CVE-2010-1246 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1246) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 메모리 손상 취약점                      | [CVE-2010-1247 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1247) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel HFPicture 메모리 손상 취약점            | [CVE-2010-1248 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1248) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 메모리 손상 취약점                      | [CVE-2010-1249 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1249) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel EDG 메모리 손상 취약점                  | [CVE-2010-1250 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1250) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel ADO 개체 취약점                         | [CVE-2010-1253 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1253) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Mac Office Open XML 사용 권한 취약점          | [CVE-2010-1254 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1254) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035) | 초기화되지 않은 메모리 손상 취약점            | [CVE-2010-1259 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1259) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035) | 메모리 손상 취약점                            | [CVE-2010-1262 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1262) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-036](http://technet.microsoft.com/security/bulletin/ms10-036) | COM 유효성 검사 취약점                        | [CVE-2010-1263 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-033](http://technet.microsoft.com/security/bulletin/ms10-033) | 미디어 압축 해제 취약점                       | [CVE-2010-1879 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1879) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                   |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035) | 도메인 간 정보 유출 취약점 취약점             | [CVE-2010-0255 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0255) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 이 취약점은 [Microsoft 보안 권고 980088](http://technet.microsoft.com/security/advisory/980088)에서 처음 보고되었습니다. |  
| [MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032) | Win32k 부적절한 데이터 유효성 검사 취약점     | [CVE-2010-0484 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0484) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS10-037](http://technet.microsoft.com/security/bulletin/ms10-037) | OpenType CFF 글꼴 드라이버 메모리 손상 취약점 | [CVE-2010-0819 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0819) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 레코드 분석 메모리 손상 취약점          | [CVE-2010-0821 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0821) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 메모리 손상 취약점                      | [CVE-2010-0823 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0823) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 레코드 스택 손상 취약점                 | [CVE-2010-1251 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1251) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 문자열 변수 취약점                      | [CVE-2010-1252 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1252) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032) | Win32k TrueType 글꼴 구문 분석 취약점         | [CVE-2010-1255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1255)        | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS10-040](http://technet.microsoft.com/security/bulletin/ms10-040) | IIS 인증 메모리 손상 취약점                   | [CVE-2010-1256 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1256) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS10-033](http://technet.microsoft.com/security/bulletin/ms10-033) | MJPEG 미디어 압축 해제 취약점                 | [CVE-2010-1880 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1880) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS10-041](http://technet.microsoft.com/security/bulletin/ms10-041) | XML 서명 HMAC 잘림 인증 우회 취약점           | [CVE-2009-0217 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0217) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점은 스푸핑 및 변조 관련 취약점입니다.                                                                            |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035) | toStaticHTML 정보 유출 취약점                 | [CVE-2010-1257 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점은 [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039)에도 영향을 미칩니다.                     |  
| [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039) | toStaticHTML 정보 유출 취약점                 | [CVE-2010-1257 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점은 [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)에도 영향을 미칩니다.                     |  
| [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039) | SharePoint 도움말 페이지 서비스 거부 취약점   | [CVE-2010-1264 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1264) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | (없음)                                                                                                                   |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이표를어떻게사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
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
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지번호**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
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
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=60c8579b-1540-40d8-80a0-956edadd63ce&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)(DirectX 9)](https://www.microsoft.com/download/details.aspx?familyid=a51c53bd-f9c1-4d53-8ed2-034fd57bc75a&displaylang=ko)<sup>[1]</sup>
(KB975562)  
(긴급)  
[Windows Media Format Runtime 9](https://www.microsoft.com/download/details.aspx?familyid=8417c0ac-bb6d-48f1-8237-77a4bdd8ccb2&displaylang=ko)<sup>[2]</sup>
(KB978695)  
(긴급)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf&displaylang=ko)  
(KB979332)  
(중요)  
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=1f929739-08a1-4faf-9ccf-5f1f43c5bb9e&displaylang=ko)  
(KB979482)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=d3955983-0079-476e-a488-99713097259c&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=0a6c09e5-c655-41a0-a133-78d55267a527&displaylang=ko)  
(심각도 없음)<sup>[1]</sup>
[Internet Explorer 6 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=e2f27eeb-54be-40be-a00e-72867090b8e7&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=5d645891-31e9-42c4-b12b-eb351473fd0c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96&displaylang=ko)  
(KB979906)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad&displaylang=ko)  
(KB979909)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지번호**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
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
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=023a777a-3d83-4a4e-8029-da8b095b074b&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=e77d5af8-e8e0-425c-a809-4cf274e17cc5&displaylang=ko)<sup>[1]</sup>
(KB975562)  
(긴급)  
Windows XP 서비스 팩 2만 해당:  
[Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 및 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=bf8b9b46-ba28-4f48-9dac-6a90b7d592d3&displaylang=ko)  
(KB978695)  
(긴급)  
Windows XP 서비스 팩 3만 해당:  
[Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 및 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=ebbccd82-c637-4c88-86ea-d39ae713c085&displaylang=ko)  
(KB978695)  
(긴급)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf&displaylang=ko)  
(KB979332)  
(중요)  
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=55c05cb8-aa6c-460b-9aa7-084842dab280&displaylang=ko)  
(KB979482)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=8c3f2e81-c0ea-494a-a47c-4f8982effb49&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=bfe87761-ed9e-4fec-a393-d7fddb919db4&displaylang=ko)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=fc02fc7e-ee85-4377-b54c-012fa60a8c9c&displaylang=ko)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9cff9aba-7743-4c33-87c7-37d06ed60a21&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=b42a17c5-997e-4504-ba5b-bfa62166b460&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows XP Media Center Edition 2005만 해당:  
[Microsoft .NET Framework 1.0 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394&displaylang=ko)  
(KB979904)  
(중요)  
Windows XP Media Center Edition 2005 및 Windows XP Tablet PC Edition 2005만 해당:  
[Microsoft .NET Framework 1.0 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394&displaylang=ko)  
(KB979904)  
(중요)  
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96&displaylang=ko)  
(KB979906)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9&displaylang=ko)  
(KB982865)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad&displaylang=ko)  
(KB979909)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=8e3aac9d-7747-435f-9678-f621e314e070)  
(중요)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=7914fdae-9a7a-4a10-8ce7-c621eb903452)  
(KB975562)  
(긴급)  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=b56839e3-e7d3-48da-b90c-d403d8dbeed2)  
(KB978695)  
(긴급)  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555)<sup>[3]</sup>
(KB978695)  
(긴급)  
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=d2887448-9d3c-472f-a0bd-ab083a65eafc)  
(KB978695)  
(긴급)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9)  
(KB979332)  
(중요)  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7)  
(KB979332)  
(중요)  
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=c110d26e-9a1e-4e47-9ce2-4068f2733a2f)  
(KB979482)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f3e462fb-df95-4b79-a8bc-5359c2967503)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=7780af61-a206-49aa-a805-a49bdcbb5419)  
(긴급)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6c7cda29-161e-49b4-976a-c718c0aa11a0)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=37cd7533-ddad-4d0d-85c0-1491308e1ff8&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dc835b94-3368-4c1c-8f29-40517c73540e)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)(KB979909)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지번호**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=79a11dcd-5d88-4d83-beae-6580ef6fc2c0&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=fc15c43b-d48f-4872-8f9d-ed973170db9a&displaylang=ko)<sup>[1]</sup>
(KB975562)  
(긴급)  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=bb580e94-8c02-46f1-b7f6-e7d4373cb1c5&displaylang=ko)  
(KB978695)  
(긴급)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf&displaylang=ko)  
(KB979332)  
(중요)  
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=0ddf95ac-dd49-4cb1-b6f6-bd4e987b0f06&displaylang=ko)  
(KB979482)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3c0bd349-aa77-47de-ba1d-1fcc72dcad28&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=bfb9acdb-2d9c-4c22-963c-8b9ce247350f&displaylang=ko)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f0187b69-3ed9-494c-89f1-90a35e22078c&displaylang=ko)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ebab6101-fcf1-4842-b22d-893a20c1c10f&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ca49b5b5-db8e-4ebc-9a3c-b1ace09ac3c0&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 6.0](https://www.microsoft.com/download/details.aspx?familyid=0761c207-5465-4f42-b61f-bd02efcef27d&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=f82e1b73-7f8b-4f4c-8187-4050a11db44c&displaylang=ko)  
(KB979907)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9&displaylang=ko)  
(KB982865)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad&displaylang=ko)  
(KB979909)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f42cc5d4-1bea-4a4a-8a08-b3eb92503588&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=d28ecdf7-9fd4-437e-9db7-c6b579248abe&displaylang=ko)<sup>[1]</sup>
(KB975562)  
(긴급)  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=41faf16f-c7a8-4ce0-b388-a65478576163&displaylang=ko)  
(KB978695)  
(긴급)  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555&displaylang=ko)<sup>[3]</sup>
(KB978695)  
(긴급)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9&displaylang=ko)  
(KB979332)  
(중요)  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7&displaylang=ko)  
(KB979332)  
(중요)  
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=77b1d55c-b015-4863-aab0-6463b90d4bf7&displaylang=ko)  
(KB979482)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=4aa0ec4f-5502-4f2a-9732-975518c34444&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=81644c43-22c0-4c61-b395-3264516516a6&displaylang=ko)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=50b8ee2e-31f8-473d-83d1-822c89c28070&displaylang=ko)  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=87e13912-f861-4985-ab9d-260a5898dfd4&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b0794e7e-c925-4672-b7a5-4bb3f847f045&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 6.0](https://www.microsoft.com/download/details.aspx?familyid=023572ff-ce5d-4428-a96b-1245db6ff312&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96&displaylang=ko)  
(KB979906)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9&displaylang=ko)  
(KB982865)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad&displaylang=ko)  
(KB979909)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=50efb1cf-9d89-4522-929d-f87fd98d6fe8)  
(중요)
</td>
<td style="border:1px solid black;">
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=7f101f4c-dcc8-474c-a844-fe0c45d6697c)  
(KB975562)  
(긴급)  
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=f34bc115-022b-46b0-9517-806bd0fc73c5)  
(KB979482)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=55d9d7f0-f9d9-4833-b5cc-eb87a62da6a8)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=abcdc3bb-4659-4b63-a9bd-e448f8bed90a)  
(보통)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=123bf547-9005-451f-9eba-97a68037304e)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=6e76ebea-bde1-4352-a283-dd71c2cc51a1)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 6.0](https://www.microsoft.com/download/details.aspx?familyid=f1f3e524-8ac6-4210-a3a8-4ffc58a606ea)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(중요)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지번호**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7cb64633-d2a0-4e38-be35-ec32ea655a04&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 1만 해당:  
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=b64107f2-990a-42df-a75a-5bf371709fd6&displaylang=ko)  
(KB975562)  
(긴급)  
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=75e4c9cb-a55a-4e2a-9c97-60a40353cae3&displaylang=ko)  
(KB979482)  
(긴급)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=9fab91da-1528-4df9-a2dd-90e57a3c24cf&displaylang=ko)  
(KB979332)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2ddaa4b3-1a98-4183-94af-ebdae4e7b76a&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=661c9528-917d-4df6-a330-c89f39dc5ce4&displaylang=ko)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=640f9216-3e99-46b6-aac8-cd051eedad3c)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=363b503a-2e1e-4284-a029-9695d2acfcb6&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 7.0](https://www.microsoft.com/download/details.aspx?familyid=01382926-2313-4769-a0a5-262c4f9f18a1&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96&displaylang=ko)  
(KB979906)  
(중요)  
Windows Vista 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778&displaylang=ko)  
(KB979913)  
(중요)  
Windows Vista 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68&displaylang=ko)  
(KB979911)  
(중요)  
Windows Vista 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb&displaylang=ko)(KB979910)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=bbfc4d80-67eb-4deb-9595-cb67942a0df2&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 1만 해당:  
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=0754addb-2f04-45c9-8594-174b8b8b297c&displaylang=ko)<sup>[1]</sup>
(KB975562)  
(긴급)  
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=c9f033f6-f587-494d-b968-1316f1deed06&displaylang=ko)  
(KB979482)  
(긴급)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=63bba49e-6d80-47b3-b109-fa9b2392af4f&displaylang=ko)  
(KB979332)  
(중요)  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=e19aeef8-6bef-45ee-bc9f-3e4b81a58e33&displaylang=ko)  
(KB979332)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ddf55e74-dbaa-45f7-ac5b-ae3da24e0e33&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d9f5feb0-fa1a-40c1-9971-9b8af6f0b4a5&displaylang=ko)  
(긴급)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3076d1ea-7716-4b54-8ec4-660374f14dcb&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3f512b86-3a99-47f7-a90e-1ae9b291385c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 7.0](https://www.microsoft.com/download/details.aspx?familyid=7fb6f2b8-c7a6-4239-99f3-cf3aacf89b0f&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96&displaylang=ko)  
(KB979906)  
(중요)  
Windows Vista x64 Edition 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778&displaylang=ko)  
(KB979913)  
(중요)  
Windows Vista x64 Edition 서비스 팩 1만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68&displaylang=ko)  
(KB979911)  
Windows Vista x64 Edition 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb&displaylang=ko)  
(KB979910)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지번호**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=22d550fe-ba35-4750-a9d6-624858b67c94&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008만(32비트 시스템용):  
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=18fd814b-51f3-470b-a5bd-97be752298d9&displaylang=ko)<sup>[1]</sup>\*\*  
(KB975562)  
(긴급)  
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=5c5e2dfc-0078-4f2a-9c2e-75e45bb7638e&displaylang=ko)\*  
(KB979482)  
(긴급)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=1ce1e47f-b1c3-4480-bafd-74f8b12e2171&displaylang=ko)\*\*  
(KB979332)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=a06b9f42-47ac-4ff2-ac32-e4958cdb611e&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=bed14484-7fc5-455d-b996-3192467543cc&displaylang=ko)\*\*  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=24ed08c7-a474-4458-8269-3b9de5e22385&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e78ad607-d209-48c4-b0f3-ed4c70993174&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 7.0](https://www.microsoft.com/download/details.aspx?familyid=84a54246-5d9e-49e2-8170-af48b43f984d&displaylang=ko)\*<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96&displaylang=ko)\*\*  
(KB979906)  
(중요)  
Windows Server 2008만(32비트 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778&displaylang=ko)\*\*  
(KB979913)  
(중요)  
Windows Server 2008만(32비트 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68&displaylang=ko)\*\*  
(KB979911)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb&displaylang=ko)\*\*  
(KB979910)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=09025626-4116-4a31-8700-215382898ee2&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008만(x64 기반 시스템용):  
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=4e40da51-23ee-44f0-9ea0-99bda8cca731&displaylang=ko)<sup>[1]</sup>\*\*  
(KB975562)  
(긴급)  
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=bfc0b62c-2d79-48dd-896f-d05057c02e8c&displaylang=ko)\*  
(KB979482)  
(긴급)  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=93cc5ace-6382-4a2f-875b-9348b7e198a6&displaylang=ko)\*\*  
(KB979332)  
(중요)  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=d650a7d7-5620-4bb7-a7ad-0848dd28dae3&displaylang=ko)\*\*  
(KB979332)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6d0a3f7c-2617-4bc6-a4c7-cda26c6471e1&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a24554e8-213b-4c24-b062-ec424d64128e&displaylang=ko)\*\*  
(보통)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=cf84469b-ce6d-45e8-8336-7b4501c6cf91&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=85f6fc5d-efd1-4351-b4c0-b9b7080e6173&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 7.0](https://www.microsoft.com/download/details.aspx?familyid=38286e43-89a6-4895-8ff9-69452df38706&displaylang=ko)\*<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96&displaylang=ko)\*\*  
(KB979906)  
(중요)  
Windows Server 2008만(x64 기반 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778&displaylang=ko)\*\*  
(KB979913)  
(중요)  
Windows Server 2008만(x64 기반 시스템용):  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68&displaylang=ko)\*\*  
(KB979911)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb&displaylang=ko)\*\*  
(KB979910)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0035cfe2-d38d-41cd-b704-ec1feda307d8)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용)만:  
[Quartz.dll(DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=120c68f5-4575-4e2a-912a-eed52736c403)  
(KB975562)  
(긴급)  
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=6e5753ab-848d-475f-917d-ba70f70b65f5)  
(KB979482)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=38347fa6-5946-4bb5-9fea-a5b2f4e7c1f2)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=dee5c0c0-b844-490d-8daf-6e6ec8a39e35)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c6f1aae5-e8fd-4121-89b2-b97c571e8223)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 7.0](https://www.microsoft.com/download/details.aspx?familyid=8ad19eba-9821-48b4-a942-4ee4f002f913)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용)만:  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용)만:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2만 해당:  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)  
(KB979910)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지번호**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=3e0ff389-4612-4c92-bbff-bb45b5bdfc6a&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=63567e99-087d-4804-953a-f23bdeba7772&displaylang=ko)  
(KB979482)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=5bce87fe-dcbb-4638-b248-3f0755537b00&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5c835885-9375-4882-a92f-4d4cfcacc005&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=969af8d6-f6da-4dd1-a7d7-2de54a5a8978&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=588167cb-f62a-4fb8-8a18-ac15dc322495&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764&displaylang=ko)  
(KB979916)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=2b1e4aff-605a-4e94-88f9-135ce35f0646&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=6c261dbf-14c6-4071-8523-e8ba8059fa54&displaylang=ko)  
(KB979482)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=ee68ecd0-5b8a-4c1e-bdee-bd8616558d43&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5cfc5776-0c6b-4092-bc98-94df077c60d8&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=b069e5b2-aa2d-452e-b687-8734b5ba0051&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=1c45d0c8-1629-470b-8167-c6bf66054595&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764&displaylang=ko)  
(KB979916)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지번호**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=4272277f-b2dd-4406-8bbd-bc461c9923b8&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=1331f2bc-7479-4be7-a413-52afb488a330&displaylang=ko)\*  
(KB979482)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=901f7c89-02af-4f87-8592-dad318997d77&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7c4ff5ae-eadd-431e-b982-d5f179efb8c0&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=45242c7c-3752-44bf-a766-024ad7d28f53&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=5d9b7705-6280-4d2e-94fa-3160b3ce5cfa&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764&displaylang=ko)\*  
(KB979916)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=7d636f82-e828-468c-ac36-808ff9d37c7f)  
(중요)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll(COM 구성 요소)](https://www.microsoft.com/download/details.aspx?familyid=7a1ee54f-3f73-4557-9071-5af236e70937)  
(KB979482)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=4958b221-2776-43d7-9e1c-1e1cb318a694)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=52c04d85-911f-47be-852e-c9bb4934744d)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=0a271fb5-da5b-4a17-9593-e56b9a843b8f)  
(중요)
</td>
<td style="border:1px solid black;">
[IIS(인터넷 정보 서비스) 7.5](https://www.microsoft.com/download/details.aspx?familyid=869e900a-0063-4d8b-9b7c-7d12f6be12cd)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(중요)
</td>
</tr>
</table>
 
**Windows Server 2008** **및** **Windows Server 2008 R2** **참고사항**

**\*Server Core** **설치가영향을받습니다.** 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오

**\*\*Server Core** **설치는영향을받지않습니다.** Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오

**MS10-033** **참고사항**

<sup>[1]</sup>Quartz.dll(Direct Show)(DirectX 9)용 업데이트는 DirectX 9.0a, DirectX 9.0b 및 DirectX 9.0c에도 적용됩니다.

<sup>[2]</sup>이 업데이트 패키지는 DRM 지원 Media Players의 업데이트(KB891122)가 설치된 Microsoft Windows 2000의 Windows Media Format 9 SDK Runtime에 적용됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 974316](http://support.microsoft.com/kb/974316)을 참조하십시오.

<sup>[3]</sup> Windows Media Format Runtime 9.5 x64 Edition을 설치한 경우, MS10-033에서 설명한 취약점으로부터 완전히 보호받으려면 Windows Media Format Runtime 9.5 및 Windows Media Format Runtime 9.5 x64 Edition 보안 업데이트를 설치해야 합니다.

**MS10-035** **참고사항**

<sup>[1]</sup>이 공지에서 설명한 취약점이 이 소프트웨어에 영향을 미치지 않으므로 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 이 업데이트는 [MS09-054](http://go.microsoft.com/fwlink/?linkid=163979)에서 발생하는 문제를 해결하기 위해 제공됩니다. 자세한 내용은 [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898)를 참조하십시오.

**MS10-040** **참고사항**

<sup>[1]</sup>이 운영 체제는 인증에 대한 확장된 보호가 설치된 경우에만 영향을 받습니다. [Microsoft 기술 자료 문서 973917](http://support.microsoft.com/kb/973917)을 참조하십시오.

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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Office 제품군, 시스템 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지번호**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://technet.microsoft.com/security/bulletin/ms10-036)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://technet.microsoft.com/security/bulletin/ms10-038)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
Microsoft Office XP 서비스 팩 3<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=fec14a92-79a1-4281-8ee2-659b2dfd283f&displaylang=ko)  
(KB982299)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=80fdd134-2a86-4115-aea1-841f19af92e3&displaylang=ko)  
(KB982311)  
(중요)  
[Microsoft Office Excel 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1&displaylang=ko)<sup>[2]</sup>
(KB982133)  
(중요)  
[Microsoft Office PowerPoint 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=6b6204c1-559f-45a5-8f6c-a1e216192efc&displaylang=ko)<sup>[2]</sup>
(KB982157)  
(중요)  
[Microsoft Office Publisher 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=87bac893-81ec-4ede-aca1-a9aa48b92cd4&displaylang=ko)<sup>[2]</sup>
(KB982122)  
(중요)  
[Microsoft Office Visio 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=1595ada3-bb4f-40f6-8137-23eba918bc8a&displaylang=ko)<sup>[2]</sup>
(KB982126)  
(중요)  
[Microsoft Office Word 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=d2c40eb5-1149-4466-840c-84f406f64245&displaylang=ko)<sup>[2]</sup>
(KB982134)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1&displaylang=ko)  
(KB982133)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System 서비스 팩 1 및 2007 Microsoft Office System 서비스 팩 2
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System 서비스 팩 1 및 2007 Microsoft Office System 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6deb4fb0-cbfc-40df-8f62-35fa1db0e167&displaylang=ko)  
(KB982312)  
(중요)  
[Microsoft Office Excel 2007 서비스 팩 1 및 Microsoft Office Excel 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec&displaylang=ko)<sup>[3]</sup>
(KB982308)  
(중요)  
[Microsoft Office PowerPoint 2007 서비스 팩 1 및 Microsoft Office PowerPoint 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=decb834d-3958-45cc-a5ae-4283adb2462a&displaylang=ko)<sup>[3]</sup>
(KB982158)  
(중요)  
[Microsoft Office Publisher 2007 서비스 팩 1 및 Microsoft Office Publisher 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=6a74b986-1e99-4aa1-828f-757a36896f65&displaylang=ko)<sup>[3]</sup>
(KB982124)  
(중요)  
[Microsoft Office Visio 2007 서비스 팩 1 및 Microsoft Office Visio 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d5df052e-1f38-4308-bcca-296cff22729b&displaylang=ko)<sup>[3]</sup>
(KB982127)  
(중요)  
[Microsoft Office Word 2007 서비스 팩 1 및 Microsoft Office Word 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7e9708f0-8cd6-4f0b-8585-bccc54fa2755&displaylang=ko)<sup>[3]</sup>
(KB982135)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 서비스 팩 1 및 Microsoft Office Excel 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec&displaylang=ko)\[4\]  
(KB982308)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지번호**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://technet.microsoft.com/security/bulletin/ms10-036)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://technet.microsoft.com/security/bulletin/ms10-038)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=16c71ab8-9284-407a-856a-93c67995f125)  
(KB2028866)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=d46255bd-6470-4106-9fe2-ea67acd3f1bd)  
(KB2028864)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=b6ca7b05-cf97-43a2-95eb-7b5caf7c1528)  
(KB2078051)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
기타 Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지번호**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://technet.microsoft.com/security/bulletin/ms10-036)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://technet.microsoft.com/security/bulletin/ms10-038)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체심각도**
</td>
<td style="border:1px solid black;">
없음
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
Microsoft Excel Viewer 서비스 팩 1 및 Microsoft Office Excel Viewer 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 서비스 팩 1 및 Microsoft Office Excel Viewer 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=033b3bf3-7826-4064-b001-11e4dce2d91a&displaylang=ko)  
(KB982333)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=7f89a734-cda4-4abb-9a10-f6dfe560e8d0&displaylang=ko)  
(KB982331)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office InfoPath 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=4f79d376-0ea2-4218-9200-3c34c83ba336&displaylang=ko)  
(KB980923)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office InfoPath 2007 서비스 팩 1 및 Microsoft Office InfoPath 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2007 서비스 팩 1 및 Microsoft Office InfoPath 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=bfa8765a-7970-4feb-996c-7c27d71c97c6&displaylang=ko)  
(KB979441)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 서비스 팩 1 및 Microsoft Office SharePoint Server 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 서비스 팩 1(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df&displaylang=ko)  
(KB979445)  
(중요)  
[Microsoft Office SharePoint Server 2007 서비스 팩 2(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df&displaylang=ko)  
(KB979445)  
(중요)  
[Microsoft Office SharePoint Server 2007 서비스 팩 1(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90&displaylang=ko)  
(KB979445)  
(중요)  
[Microsoft Office SharePoint Server 2007 서비스 팩 2(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90&displaylang=ko)  
(KB979445)  
(중요)
</td>
</tr>
</table>
 
**MS10-036** **참고사항**

<sup>[1]</sup>사용 가능한 업데이트가 없습니다. 자세한 내용은 보안 공지를 참조하십시오.

<sup>[2]</sup>고객은 이 공지에서 설명한 취약점으로부터 보호하기 위해 이 업데이트와 함께 Microsoft Office 2003 서비스 팩 3(KB982311) 업데이트를 설치해야 합니다.

<sup>[3]</sup>고객은 이 공지에서 설명한 취약점으로부터 보호하기 위해 이 업데이트와 함께 2007 Microsoft Office System 서비스 팩 1 및 2007 Microsoft Office System 서비스 팩 2(KB982312) 업데이트를 설치해야 합니다.

**MS10-038** **참고사항**

<sup>[1]</sup>고객은 이 공지에서 설명한 취약점으로부터 보호하기 위해 이 업데이트와 함께 Word, Excel 및 PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 서비스 팩 1 및 Word, Excel 및 PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 서비스 팩 2(KB982308)의 보안 업데이트를 설치해야 합니다.

**MS10-039** **참고사항**

<sup>[1]</sup>고객은 이 공지에서 설명한 취약점으로부터 보호하기 위해 지원 대상인 Microsoft Office SharePoint Server 2007 에디션에 보안 업데이트 패키지 KB979445와 함께 Microsoft Windows SharePoint Services 3.0용 보안 업데이트(KB983444)를 설치해야 합니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을받는소프트웨어및다운로드위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Server 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Windows SharePoint Services
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지번호**
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 서비스 팩 1 및 Microsoft Windows SharePoint Services 3.0 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 서비스 팩 1 및 Microsoft Windows SharePoint Services 3.0 서비스 팩 2(32비트 버전)](https://www.microsoft.com/download/details.aspx?familyid=3841ceda-d0af-4e5e-8a1a-7dd954850783&displaylang=ko)  
(KB983444)  
(중요)  
[Microsoft Windows SharePoint Services 3.0 서비스 팩 1 및 Microsoft Windows SharePoint Services 3.0 서비스 팩 2(64비트 버전)](https://www.microsoft.com/download/details.aspx?familyid=94bc76d4-78e4-4bda-8922-36c3a9d3854f&displaylang=ko)  
(KB983444)  
(중요)
</td>
</tr>
</table>
 
**MS10-039** **참고사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을받는소프트웨어및다운로드위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

검색, 배포 도구 및 지침
-----------------------

**보안센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**참고** 2009년 8월 1일부터 Microsoft는 Office 업데이트와 Office 업데이트 인벤토리 도구에 대한 지원을 중단합니다. 계속해서 Microsoft Office 제품에 필요한 최신 업데이트를 받으려면 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)를 사용하십시오. 자세한 내용은 [Microsoft Office 업데이트 정보: 자주 제기되는 질문 사항(FAQ)](http://office.microsoft.com/ko-kr/downloads/fx010402221042.aspx)을 참조하십시오.

**검색및배포지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](http://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://go.microsoft.com/fwlink/?linkid=22939)를 참조하십시오. SMS 2.0 사용자는 SUIT(Security Update Inventory Tool)을 사용하여 보안 업데이트 배포를 지원할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)를 참조하십시오.

**참고**SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2.0 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator)** **및** **ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트 (영문)](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트관리전략**

[업데이트 관리를 위한 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타보안관련업데이트받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT** **전문가보안영역커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS10-032에서 설명한 문제점을 보고해 주신 [VUPEN Vulnerability Research Team (영문)](http://www.vupen.com/)의 Sebastien Renaud
-   MS10-032에서 설명한 문제점을 보고해 주신 [Secunia Research (영문)](http://secunia.com/)
-   MS10-033에서 설명한 두 가지 문제점을 보고해 주신 [Palo Alto Networks (영문)](http://www.paloaltonetworks.com/)의 Yamata Li
-   MS10-034에서 설명한 문제점을 보고해 주신 [NGS Software (영문)](http://www.ngssoftware.com/)의 Shaun Colley
-   MS10-034에서 설명한 문제점을 보고해 주신 Carnegie Mellon University Computing Services의 Chris Ries
-   MS10-035 및 MS10-039에서 설명한 문제점을 보고해 주신 [Casaba Security (영문)](http://www.casabasecurity.com/)의 Chris Weber
-   MS10-035에서 설명한 문제점을 보고해 주신 [Mitsui Bussan Secure Directions, Inc. (영문)](http://www.mbsd.jp/)의 Takeshi Terada
-   MS10-035에서 설명한 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 Michal Zalewski
-   MS10-035에서 설명한 두 가지 문제점을 보고해 주신 [Matasano Security (영문)](http://www.matasano.com/)의 Chris Rohlf
-   MS10-035에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Peter Vreugdenhil
-   MS10-036에 포함된 심층 보안 변경 사항에 대해 협력해 주신 [IBM ISS X-Force (영문)](http://www.iss.net/)의 David Dewey 및 [Accuvant (영문)](http://www.accuvant.com/)(이전 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/))의 Ryan Smith
-   MS10-037에서 설명한 문제점을 [Secunia (영문)](http://secunia.com/)와 협력하여 보고해 주신 Laserforce International의 Chris Carton
-   MS10-038에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS10-038에서 설명한 여덟 가지 문제점을 보고해 주신 [VUPEN Vulnerability Research Team (영문)](http://www.vupen.com/)의 Nicolas Joly
-   MS10-038에서 설명한 문제점을 보고해 주신 [Fortinet's FortiGuard Labs (영문)](http://www.fortiguard.com/)의 Bing Liu
-   MS10-038에서 설명한 두 가지 문제점을 보고해 주신 [Secunia (영문)](http://secunia.com/)의 Carsten Eiram
-   MS10-038에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS10-038에서 설명한 문제점을 보고해 주신 애리조나 주 길버트 소재 Gilbert Public Schools의 Rick Glaspie
-   MS10-039에서 설명한 문제점을 보고해 주신 Dallas County Community College District의 Rik Jones
-   심층 보안 변경 사항을 통해 MS10-041에서 해결된 ASP.NET 요청 유효성 확인의 우회 문제점을 보고해 주신 [WhiteHat Security (영문)](http://www.whitehatsec.com)의 Arian Evans

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2010년 6월 9일): 공지 요약이 게시되었습니다.
-   V1.1(2010년 6월 10일): **영향을받는소프트웨어및다운로드위치** 섹션에서 MS10-033 참고 사항이 수정되었습니다.
-   V2.0(2011년 9월 14일): Microsoft Windows 2000 및 Windows XP의 Internet Explorer에 대한 검색 문제를 해결하는 업데이트를 다시 제공하기 위해 MS10-035 공지를 다시 릴리스하였습니다. 보안 업데이트 파일에 대한 변경 사항은 없습니다. 이미 시스템을 성공적으로 업데이트한 고객은 추가 조치를 취할 필요가 없습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
