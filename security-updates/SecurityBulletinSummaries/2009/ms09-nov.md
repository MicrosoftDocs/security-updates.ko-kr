---
TOCTitle: 'MS09-NOV'
Title: 2009 년 11 월 Microsoft 보안 공지 요약
ms:assetid: 'ms09-nov'
ms:contentKeyID: 61230717
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms09-nov(v=Security.10)'
---


2009 년 11 월 Microsoft 보안 공지 요약
======================================

게시된 날짜: 2009년 11월 11일 수요일 | 업데이트된 날짜: 2009년 11월 25일 수요일

**버전:** 1.1

이 공지 요약 목록에는 2009년 11월 발표된 보안 공지가 포함되어 있습니다.

2009년 11월 공지 발표와 함께 이 공지 요약이 2009년 11월 5일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2009년 11월 11일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [11월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407490&culture=en-us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](https://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

요약
----

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-063">MS09-063</a></td>
<td style="border:1px solid black;"><strong>Web Services on Devices API의 취약점으로 인한 원격 코드 실행 문제점 (973565)</strong><br />
<br />
이 보안 업데이트는 Windows 운영 체제의 WSDAPI(Web Services on Devices 응용 프로그래밍 인터페이스)에서 발견되어 비공개적으로 보고된 취약점 1건을 해결합니다. 영향을 받는 Windows 시스템에서 특수하게 조작된 패킷을 받을 경우 이 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 로컬 서브넷에 있는 공격자만 이 취약점을 악용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-064">MS09-064</a></td>
<td style="border:1px solid black;"><strong>라이센스 로깅 서버의 취약점으로 인한 원격 코드 실행 문제점 (974783)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows 2000에서 발견되어 비공개적으로 보고된 취약점 1건을 해결합니다. 공격자가 특수하게 조작된 네트워크 메시지를 라이센스 로깅 서버를 실행하는 컴퓨터로 전송하면 이 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 최선의 방화벽 구성 방법과 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 들어오는 공격으로부터 네트워크를 보호할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-065">MS09-065</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버의 취약점으로 인한 원격 코드 실행 문제점 (969947)</strong><br />
<br />
이 보안 업데이트는 Windows 커널에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 특수하게 조작된 EOT(Embedded OpenType) 글꼴로 렌더링된 콘텐츠를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 웹을 통한 공격의 경우 공격자는 이 취약점 악용 시도에 사용되는 특수하게 조작된 포함 글꼴을 포함한 웹 사이트를 호스팅해야 합니다. 또한 사용자가 제공한 콘텐츠를 허용하거나 호스팅하는 공격 당한 웹 사이트에는 이 취약점을 악용할 수 있는 특수하게 조작된 콘텐츠가 포함되어 있을 수 있습니다. 공격자는 강제로 사용자가 특수하게 조작된 웹 사이트를 방문하도록 만들 수 없습니다. 대신, 공격자는 사용자가 공격자의 사이트로 이동되는 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하도록 하여 웹 사이트를 방문하도록 만들어야 합니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-066">MS09-066</a></td>
<td style="border:1px solid black;"><strong>Active Directory의 취약점으로 인한 서비스 거부 문제점 (973309)</strong><br />
<br />
이 보안 업데이트는 Active Directory 디렉터리 서비스, ADAM(Active Directory Application Mode) 및 AD LDS(Active Directory Lightweight Directory Service)에서 발견되어 비공개적으로 보고된 취약점 1건을 해결합니다. 특정 유형의 LDAP 또는 LDAPS 요청을 실행하는 동안 스택 공간을 다 써버릴 경우 이 취약점으로 인해 서비스 거부가 발생할 수 있습니다. 이 취약점은 ADAM 또는 AD LDS를 실행하도록 구성된 도메인 컨트롤러와 시스템에만 영향을 줍니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-067">MS09-067</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel의 취약점으로 인한 원격 코드 실행 문제점 (972652)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office Excel에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 사용자가 특수하게 조작된 Excel 파일을 열면 이러한 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-068">MS09-068</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Word의 취약점으로 인한 원격 코드 실행 문제점 (976307)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 취약점 1건을 해결합니다. 사용자가 특수하게 조작된 Word 파일을 열면 이러한 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](https://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 취약점 제목                                        | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                                                     |  
|---------------------------------------------------------------------|----------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|  
| [MS09-063](https://technet.microsoft.com/security/bulletin/ms09-063) | Web Services on Devices API 메모리 손상 취약점     | [CVE-2009-2512 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2512) | [**2 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 경우에 따라 제한적인 서비스 거부 공격이 발생할 수 있습니다.                                   |  
| [MS09-064](https://technet.microsoft.com/security/bulletin/ms09-064) | 라이센스 로깅 서버 힙 오버플로 취약점              | [CVE-2009-2523 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2523) | [**2 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 공격은 악용하기 어려운 경쟁 조건에 의존합니다. 서비스 거부 이외의 모든 악용은 비의존적입니다. |  
| [MS09-065](https://technet.microsoft.com/security/bulletin/ms09-065) | Win32k NULL 포인터 역참조 취약점                   | [CVE-2009-1127new](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1127)     | [**2 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                        |  
| [MS09-065](https://technet.microsoft.com/security/bulletin/ms09-065) | Win32k 불충분한 데이터 유효성 검사 취약점          | [CVE-2009-2513 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2513) | [**1 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |  
| [MS09-065](https://technet.microsoft.com/security/bulletin/ms09-065) | Win32k EOT 구문 분석 취약점                        | [CVE-2009-2514 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2514) | [**1 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |  
| [MS09-066](https://technet.microsoft.com/security/bulletin/ms09-066) | LSASS 재귀 스택 오버플로 취약점                    | [CVE-2009-1928 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1928) | [**3 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 서비스 거부 공격에 대한 조건이 존재합니다.                                                    |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel 캐시 메모리 손상 취약점                      | [CVE-2009-3127 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3127) | [**2 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                        |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel SxView 메모리 손상 취약점                    | [CVE-2009-3128 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3128) | [**2 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                        |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel Featheader 레코드 메모리 손상 취약점         | [CVE-2009-3129 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3129) | [**1 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |  
| [MS09-065](https://technet.microsoft.com/security/bulletin/ms09-065) | Win32k EOT 구문 분석 취약점                        | [CVE-2009-2514 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2514) | [**1 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |  
| [MS09-066](https://technet.microsoft.com/security/bulletin/ms09-066) | LSASS 재귀 스택 오버플로 취약점                    | [CVE-2009-1928 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1928) | [**3 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 서비스 거부 공격에 대한 조건이 존재합니다.                                                    |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel 캐시 메모리 손상 취약점                      | [CVE-2009-3127 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3127) | [**2 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                        |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel SxView 메모리 손상 취약점                    | [CVE-2009-3128 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3128) | [**2 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                        |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel 필드 삭제 취약점                             | [CVE-2009-3134](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3134)        | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능        | (없음)                                                                                        |  
| [MS09-068](https://go.microsoft.com/fwlink/?linkid=165890)           | Microsoft Office Word 파일 정보 메모리 손상 취약점 | [CVE-2009-3135 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3135) | [**1 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
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
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-063**](https://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](https://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](https://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](https://technet.microsoft.com/security/bulletin/ms09-066)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=365a8dff-2383-42f6-b567-e545461fd135&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=45db8bb1-c81b-4d3f-a658-74f5fa445f81&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server 서비스 팩 4의 Active Directory](https://www.microsoft.com/download/details.aspx?familyid=297158cf-374c-45d9-b213-978e1f54d244&displaylang=ko)  
(KB973037)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-063**](https://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](https://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](https://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](https://technet.microsoft.com/security/bulletin/ms09-066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=916abdad-44b7-4f9d-986a-0c3558fb8e06&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=cbe09780-f288-457a-b254-58c9c8744055&displaylang=ko)  
(KB973039)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=1d0464c6-5ed8-4064-887e-618a2db09236)  
(긴급)
</td>
<td style="border:1px solid black;">
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=b65ddf36-a02d-4aa2-9b4f-7416dbf59e2a)  
(KB973039)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-063**](https://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](https://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](https://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](https://technet.microsoft.com/security/bulletin/ms09-066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5cd62750-e269-44ae-8c7c-c335e8545b9a&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=28f1c494-4e16-43b6-93d2-49e15f142ac9&displaylang=ko)  
(KB973037)  
(중요)  
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=44cb9029-4b19-4bad-8fc9-3efe285adb0e&displaylang=ko)  
(KB973039)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=04a7f817-f330-4003-8b25-d3e744905b12&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=509aeec0-112b-44ab-8686-43f381b61940&displaylang=ko)  
(KB973037)  
(중요)  
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=87f2109e-5129-467c-930f-70af31ebf5de&displaylang=ko)  
(KB973039)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=b95daac0-4c99-47a4-b0ca-9429997ea3d9)  
(긴급)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=040e691b-1ef0-4b73-bef7-a1d77b84b0ca)  
(KB973037)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-063**](https://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](https://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](https://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](https://technet.microsoft.com/security/bulletin/ms09-066)
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
없음
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=ebf0c294-cd99-445a-a741-78253e47189f&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=54562103-1d99-42d7-8f7f-c0cbcdce90db&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d9645fc9-f524-43f1-8b8c-94b3b4312158&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=fcb87cc8-6fd7-4f16-93d6-552999462fb1&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-063**](https://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](https://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](https://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](https://technet.microsoft.com/security/bulletin/ms09-066)
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
없음
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=d6a60883-b103-459a-a91b-cd6ed946cefe&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=b97d48de-0f6d-4bca-b990-acf543fdb8b7&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Active Directory 및 AD LDS(Active Directory Lightweight Directory Service)](https://www.microsoft.com/download/details.aspx?familyid=701abf15-7f93-41de-8d09-13404fd79a7e&displaylang=ko)\*  
(KB973037)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3dde1587-42d3-438f-8344-696a5657b9b1&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0e2b8607-10fa-406a-96a5-18290f479c48&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Active Directory 및 AD LDS(Active Directory Lightweight Directory Service)](https://www.microsoft.com/download/details.aspx?familyid=17f5f9e0-5869-41da-9b3b-6e67540af1f0&displaylang=ko)\*  
(KB973037)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=841a027f-22fa-42de-93b3-57a3fe92a1d3)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=28eba3f3-99a5-424c-bc8d-a718c716699e)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**Windows Server 2008 및 Windows Server 2008 R2 참고 사항**

**\*Server Core 설치가 영향을 받습니다.** 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교](https://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오

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
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-067**](https://technet.microsoft.com/security/bulletin/ms09-067)
</td>
<td style="border:1px solid black;">
[**MS09-068**](https://technet.microsoft.com/security/bulletin/ms09-068)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=5672c8fc-8509-4962-ad86-ebc0f2575043&displaylang=ko)  
(KB973471)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=0369fae5-958b-4eba-83a4-9c07e701c273&displaylang=ko)  
(KB973444)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=6a6a0f5d-17dc-4a34-b9a0-0774aa287ba5&displaylang=ko)  
(KB973475)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=6b77bc62-bcbb-4b9a-97d1-a49ca0582e54&displaylang=ko)  
(KB973443)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 서비스 팩 1 및 Microsoft Office Excel 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=322b24ca-aff6-4ca0-acf1-440cae0f9693&displaylang=ko)<sup>[1]</sup>
(KB973593)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-067**](https://technet.microsoft.com/security/bulletin/ms09-067)
</td>
<td style="border:1px solid black;">
[**MS09-068**](https://technet.microsoft.com/security/bulletin/ms09-068)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e)  
(KB976830)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e)  
(KB976830)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=b84fe57d-ddda-451e-9ead-69e10aee7928)  
(KB976828)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=b84fe57d-ddda-451e-9ead-69e10aee7928)  
(KB976828)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6)  
(KB976831)  
(중요)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6)  
(KB976831)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
기타 Microsoft Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-067**](https://technet.microsoft.com/security/bulletin/ms09-067)
</td>
<td style="border:1px solid black;">
[**MS09-068**](https://technet.microsoft.com/security/bulletin/ms09-068)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel Viewer 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=19151e22-5642-456c-bd39-298574369cdb&displaylang=ko)  
(KB973484)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 서비스 팩 1 및 Microsoft Office Excel Viewer 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=fb36df5e-ebef-46bf-9edd-67f2c76dbdb3&displaylang=ko)  
(KB973707)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer 2003
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1&displaylang=ko)  
(KB973866)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer](https://www.microsoft.com/download/details.aspx?familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1&displaylang=ko)  
(KB973866)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=c4c92d2e-e87d-446f-8d3e-8f4be10c70aa&displaylang=ko)  
(KB973704)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**MS09-067 참고 사항**

<sup>[1]</sup>Microsoft Office Excel 2007 서비스 팩 1 및 Microsoft Office Excel 2007 서비스 팩 2를 사용하는 고객은 이 보안 공지에서 설명한 취약점으로부터 보호하기 위해 보안 업데이트 패키지 KB973593과 함께 [Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=?...?)(KB973704)에 대한 보안 업데이트를 설치해야 합니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](https://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](https://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](https://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](https://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](https://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**참고** 2009년 8월 1일부터 Microsoft는 Office 업데이트와 Office 업데이트 인벤토리 도구에 대한 지원을 중단합니다. 계속해서 Microsoft Office 제품에 필요한 최신 업데이트를 받으려면 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)를 사용하십시오. 자세한 내용은 [Microsoft Office 업데이트 정보: 자주 제기되는 질문 사항(FAQ)](https://office.microsoft.com/ko-kr/downloads/fx010402221042.aspx)을 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](https://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](https://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](https://go.microsoft.com/fwlink/?linkid=22939)를 참조하십시오. SMS 2.0 사용자는 SUIT(Security Update Inventory Tool)을 사용하여 보안 업데이트 배포를 지원할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](https://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트 (영문)](https://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](https://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](https://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS09-063에서 설명한 문제점을 보고해 주신 [Google Inc.](https://www.google.com/)의 Neel Mehta
-   MS09-064에서 설명한 문제점을 보고해 주신 [TippingPoint DVLabs (영문)](https://dvlabs.tippingpoint.com/)의 Cody Pierce
-   MS09-065에서 설명한 문제점을 보고해 주신 Agin Sun
-   MS09-065에서 설명한 문제점을 보고해 주신 [Google Inc.](https://www.google.com/)의 Tavis Ormandy
-   MS09-067에서 설명한 세 가지 문제점을 보고해 주신 [Fortinet's FortiGuard Labs (영문)](https://www.fortiguard.com/)의 Bing Liu
-   MS09-067에서 설명한 문제점을 보고해 주신 [TippingPoint (영문)](https://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)
-   MS09-067에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](https://labs.idefense.com/)의 Sean Larsson
-   MS09-067에서 설명한 문제점을 [TippingPoint](https://www.tippingpoint.com/) 및 [Zero Day Initiative](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS09-067에서 설명한 문제점을 보고해 주신 [VUPEN Security (영문)](https://www.vupen.com/)의 Nicolas Joly
-   MS09-068에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](https://labs.idefense.com/)의 Jun Mao

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](https://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](https://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](https://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2009년 11월 11일): 공지 요약이 게시되었습니다.
-   V1.1(2009년 11월 26일): CVE-2009-2523의 악용 가능성 인덱스에 대한 주요 정보가 추가되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
