---
TOCTitle: 'MS09-JUN'
Title: 2009 년 6 월 Microsoft 보안 공지 요약
ms:assetid: 'ms09-jun'
ms:contentKeyID: 61230714
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms09-jun(v=Security.10)'
---


2009 년 6 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2009년 6월 10일 수요일

**버전:** 1.1

이 공지 요약 목록에는 2009년 6월 발표된 보안 공지가 포함되어 있습니다.

2009년 6월 공지 발표와 함께 이 공지 요약이 2008년 6월 4일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2009년 6월 11일 목요일(한국 표준시)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [6월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032395225). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](https://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-018">MS09-018</a></td>
<td style="border:1px solid black;"><strong>Active Directory의 취약점으로 인한 원격 코드 실행 문제점 (971055)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점은 Microsoft Windows 2000 Server 및 Windows Server 2003에 구현된 Active Directory와 Windows XP Professional 및 Windows Server 2003에 설치된 ADAM(Active Directory Application Mode)에서 발견되었습니다. 가장 심각한 취약점은 서비스 거부 조건을 허용할 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 원격으로 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 최선의 방화벽 구성 방법과 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 들어오는 공격으로부터 네트워크를 보호할 수 있습니다. 인터넷과 연결되는 시스템의 경우, 필요한 포트만 최소한으로 열어 두는 것이 안전합니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-022">MS09-022</a></td>
<td style="border:1px solid black;"><strong>Windows 인쇄 스풀러 취약점으로 인한 원격 코드 실행 문제점 (961501)</strong><br />
<br />
이 보안 업데이트는 Windows 인쇄 스풀러에서 이전에 비공개적으로 보고되었던 취약점 3건을 해결합니다. 가장 심각한 취약점은 영향을 받는 서버가 특수하게 조작된 RPC 요청을 받는 경우 원격 코드 실행을 허용할 수 있습니다. 최선의 방화벽 구성 방법과 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 들어오는 공격으로부터 네트워크를 보호할 수 있습니다. 인터넷과 연결되는 시스템의 경우, 필요한 포트만 최소한으로 열어 두는 것이 안전합니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-019">MS09-019</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트 (969897)</strong><br />
<br />
이 보안 업데이트는 Internet Explorer에 대해 비공개적으로 보고된 취약점 7건과 공개된 취약점 1건을 해결합니다. 가장 심각한 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-027">MS09-027</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Word의 취약점으로 인한 원격 코드 실행 문제점 (969514)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 취약점 2건을 해결합니다. 사용자가 특수하게 조작된 Word 파일을 열면 이러한 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 영향을 받는 시스템을 완벽히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-021">MS09-021</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel의 취약점으로 인한 원격 코드 실행 문제점 (969462)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 여러 건의 취약점을 해결합니다. 조작된 레코드 개체를 포함하고 있는 특수하게 조작된 Excel 파일을 사용자가 열면 이 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-024">MS09-024</a></td>
<td style="border:1px solid black;"><strong>Microsoft Works 변환기의 취약점으로 인한 원격 코드 실행 문제점 (957632)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 Works 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-026">MS09-026</a></td>
<td style="border:1px solid black;"><strong>RPC의 취약점으로 인한 권한 상승 문제점 (970238)</strong><br />
<br />
이 보안 업데이트는 RPC 마샬링 엔진이 내부 상태를 적절히 업데이트하지 않는 Windows RPC(원격 프로시저 호출) 기능의 공개된 취약점을 해결합니다. 이 취약점으로 인해 공격자는 영향 받은 시스템에서 임의 코드를 실행하고 시스템을 완전하게 제어할 수 있게 됩니다. 지원되는 Microsoft Windows 에디션에는 이 취약점이 악용될 때 영향을 받는 RPC 서버 또는 클라이언트가 포함되어 있지 않습니다. 기본 구성에서는 이 취약점의 악용되어도 사용자는 공격을 받지 않지만 Microsoft Windows RPC 런타임에 취약점이 있어 타사 RPC 응용 프로그램에 영향을 미칠 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-025">MS09-025</a></td>
<td style="border:1px solid black;"><strong>Windows 커널의 취약점으로 인한 권한 상승 문제점 (968537)</strong><br />
<br />
이 보안 업데이트는 권한 상승을 허용할 수 있는 Windows 커널의 공개된 취약점 2건과 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점 악용에 성공한 공격자는 임의 코드를 실행하여 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-020">MS09-020</a></td>
<td style="border:1px solid black;"><strong>IIS(인터넷 정보 서비스)의 취약점으로 인한 권한 상승 문제점 (970483)</strong><br />
<br />
이 보안 업데이트는 Microsoft IIS(인터넷 정보 서비스)의 일반에 공개된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 이러한 취약점이 있을 때 공격자가 인증을 요구하는 웹 사이트에 특수하게 조작된 HTTP 요청을 보낸 경우 권한이 상승될 수 있습니다. 이 특수하게 조작된 HTTP 요청은 허용되는 인증을 지정하는 IIS 구성을 우회할 수 있지만 지정된 사용자가 파일에 액세스할 수 있는지 여부를 확인하는 파일 시스템 기반 ACL 검사는 우회할 수 없습니다. 이 취약점의 악용에 성공해도 공격자의 권한은 여전히 파일 시스템 ACL 수준의 익명 사용자 계정으로 제한됩니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-023">MS09-023</a></td>
<td style="border:1px solid black;"><strong>Windows 검색의 취약점으로 인한 정보 유출 문제점 (963093)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows 검색의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 파일을 첫 번째 결과로 반환하는 검색을 수행하거나 검색 결과에서 특수하게 조작된 파일을 미리 볼 경우 정보 유출이 발생할 수 있습니다. 기본적으로 Windows 검색 구성 요소는 Microsoft Windows XP 및 Windows Server 2003에 사전 설치되지 않으며 다운로드할 수 있는 선택적 구성 요소입니다. 지원되는 Windows Vista 및 Windows Server 2008 에디션에 설치된 Windows 검색은 이러한 취약점의 영향을 받지 않습니다.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">보통</a><br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내에 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](https://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 공지 제목 | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                                                                                                                                                                           |  
|---------------------------------------------------------------------|-----------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-018](https://technet.microsoft.com/security/bulletin/ms09-018) |           | [CVE-2009-1138 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1138) | [**3 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | **일관적인 악용 코드는 네트워크 상에서 LDAP 혹은 LDAPS 서비스에 노출된 Windows 2008 서버 환경에서 서비스가 거부 될 수 있는 요인입니다. 그러나, 추가 검사 기능으로 인해, 원격 코드 실행 악용 기능은 불가능 합니다.** |  
| [MS09-019](https://technet.microsoft.com/security/bulletin/ms09-019) |           | [CVE-2009-1140 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1140) | [**2 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                              |  
| [MS09-019](https://technet.microsoft.com/security/bulletin/ms09-019) |           | [CVE-2009-1531 (영문)](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1531) | [**3 (영문)**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     |                                                                                                                                                                                                                     |
  
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
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-018**](https://technet.microsoft.com/security/bulletin/ms09-018)
</td>
<td style="border:1px solid black;">
[**MS09-022**](https://technet.microsoft.com/security/bulletin/ms09-022)
</td>
<td style="border:1px solid black;">
[**MS09-019**](https://technet.microsoft.com/security/bulletin/ms09-019)
</td>
<td style="border:1px solid black;">
[**MS09-026**](https://technet.microsoft.com/security/bulletin/ms09-026)
</td>
<td style="border:1px solid black;">
[**MS09-025**](https://technet.microsoft.com/security/bulletin/ms09-025)
</td>
<td style="border:1px solid black;">
[**MS09-020**](https://technet.microsoft.com/security/bulletin/ms09-020)
</td>
<td style="border:1px solid black;">
[**MS09-023**](https://technet.microsoft.com/security/bulletin/ms09-023)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server 서비스 팩 4의 Active Directory](https://www.microsoft.com/download/details.aspx?familyid=bba6e20a-0345-46ae-a6f1-fd27fdee7c21&displaylang=ko)  
(KB969805)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=86378753-db24-44c2-a27d-cc0239f40ab8&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=d645ad82-13c3-4030-808b-834e86ed3298&displaylang=ko)  
(긴급)  
[Microsoft Internet Explorer 6 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=fe8b3796-a407-4f41-89eb-35b4bcc24ff6&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=155a79c1-e5e4-4f62-b4b0-53aca59f20ac&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](https://www.microsoft.com/download/details.aspx?familyid=79b0481d-a3d7-477b-928a-a98cc79374af&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft IIS(인터넷 정보 서비스) 5.0](https://www.microsoft.com/download/details.aspx?familyid=8515a294-4f25-4dc5-860a-e7ad9b6c1c01&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-018**](https://technet.microsoft.com/security/bulletin/ms09-018)
</td>
<td style="border:1px solid black;">
[**MS09-022**](https://technet.microsoft.com/security/bulletin/ms09-022)
</td>
<td style="border:1px solid black;">
[**MS09-019**](https://technet.microsoft.com/security/bulletin/ms09-019)
</td>
<td style="border:1px solid black;">
[**MS09-026**](https://technet.microsoft.com/security/bulletin/ms09-026)
</td>
<td style="border:1px solid black;">
[**MS09-025**](https://technet.microsoft.com/security/bulletin/ms09-025)
</td>
<td style="border:1px solid black;">
[**MS09-020**](https://technet.microsoft.com/security/bulletin/ms09-020)
</td>
<td style="border:1px solid black;">
[**MS09-023**](https://technet.microsoft.com/security/bulletin/ms09-023)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP Professional 서비스 팩 2 및 Windows XP Professional 서비스 팩 3의 ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=cb2c9b76-0c65-4754-9941-d45a7c74a29a&displaylang=ko)  
(KB970437)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=f2119aca-a98e-4810-be52-f38241443baf&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=3d7f63ee-d7c3-48a5-902e-60625405e97d&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=827b735c-660b-4723-b688-3297e107153a&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d9e27ce1-4e7c-437f-9477-e7805a33da08&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=f033fa78-c451-44f8-aa6c-a49622c37f40&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=6349e046-a3f8-4ae5-b8c3-c9879cc99e8f&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft IIS(인터넷 정보 서비스) 5.1](https://www.microsoft.com/download/details.aspx?familyid=97da589f-4534-42f6-9f29-967b5a33c542&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 검색 4.0](https://www.microsoft.com/download/details.aspx?familyid=759f22cb-ea7f-49dd-a200-19cb83fffd8d&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=2ef3aaf0-a2a9-4c17-99ab-a0dc3d3f7e86)  
(KB970437)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=22699d09-1e68-456a-8733-bfad6667ebf5)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=088f70eb-c5c5-426a-880a-18ed386d0b56)  
(긴급)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e5d2c81e-ffab-4e3b-a59a-a55000597213)  
(긴급)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a24aedf0-7a31-4ee8-a9a6-998f1160c700)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=20734b70-37f1-47dd-bc09-d56f93577a55)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3769800e-af93-4a44-8a1e-b30cc54b226f)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft IIS(인터넷 정보 서비스) 6.0](https://www.microsoft.com/download/details.aspx?familyid=8982e6d2-e1f7-4208-88e3-80b159a8e21a)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 검색 4.0](https://www.microsoft.com/download/details.aspx?familyid=50c56dd6-c34d-4632-a779-8bcf8fdb341b)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-018**](https://technet.microsoft.com/security/bulletin/ms09-018)
</td>
<td style="border:1px solid black;">
[**MS09-022**](https://technet.microsoft.com/security/bulletin/ms09-022)
</td>
<td style="border:1px solid black;">
[**MS09-019**](https://technet.microsoft.com/security/bulletin/ms09-019)
</td>
<td style="border:1px solid black;">
[**MS09-026**](https://technet.microsoft.com/security/bulletin/ms09-026)
</td>
<td style="border:1px solid black;">
[**MS09-025**](https://technet.microsoft.com/security/bulletin/ms09-025)
</td>
<td style="border:1px solid black;">
[**MS09-020**](https://technet.microsoft.com/security/bulletin/ms09-020)
</td>
<td style="border:1px solid black;">
[**MS09-023**](https://technet.microsoft.com/security/bulletin/ms09-023)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=d814ce65-a193-4027-a6cd-106d388830a6&displaylang=ko)  
(KB969805)  
(중요)  
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=f6f99957-f74f-4446-8734-a468283eebae&displaylang=ko)  
(KB970437)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=865414f8-3f77-4fee-acc6-6684a3dc0aa4&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=72a23752-86fb-4cc9-ab8e-63ffdfae5bec&displaylang=ko)  
(보통)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a980b867-c67f-4c61-b6db-e55c2ca68dc0&displaylang=ko)  
(보통)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=298143f2-f37a-4a2c-86ac-9804d4ff1dad&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=62bb9e22-4f4b-4ffc-ba76-f626e94c79d5&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=9356404c-d89a-4de0-b9b4-f6e1bdadf745&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft IIS(인터넷 정보 서비스) 6.0](https://www.microsoft.com/download/details.aspx?familyid=2bd4e410-dbd8-431a-b316-e1e2f1825c3a&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 검색 4.0](https://www.microsoft.com/download/details.aspx?familyid=e72ef31f-5161-4fe6-8ed3-6206e02cef31&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=0d1f23c8-06eb-4996-92eb-0eb635fd6a42&displaylang=ko)  
(KB969805)  
(중요)  
[ADAM(Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=1a2badc7-c0a5-4032-a009-73ebe9d76313&displaylang=ko)  
(KB970437)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=197a6cc7-4ba3-4d2e-b621-0ef3da645ef2&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=2a03d3c4-e39d-43a3-8d42-216e9551be96&displaylang=ko)  
(보통)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5e7d6372-9c8c-449d-88fd-afd4f92ad9e6&displaylang=ko)  
(보통)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4a5401d7-ca97-4734-a0e9-d7ffe0777e34&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=888b8dd8-d76c-42f5-a377-1f1750d3cf56&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5a3123af-173d-49eb-9997-14e82e764aee&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft IIS(인터넷 정보 서비스) 6.0](https://www.microsoft.com/download/details.aspx?familyid=ea363223-535d-4142-9aba-3890960c6259&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 검색 4.0](https://www.microsoft.com/download/details.aspx?familyid=7ffc3680-f9bf-423b-96a7-102f4cc9c240&displaylang=ko)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=92e7808b-92ff-449d-bb73-ee8638e9ccd1)  
(KB969805)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=719efd62-fb33-447d-b6dd-2aaafbbad881)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=58efde2c-e0b8-4259-b19e-80564b834882)  
(보통)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a2d2907e-67ae-44a4-a805-8670e659ea57)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=3084f46e-02b9-4d99-a7a1-033817f9bd9f)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](https://www.microsoft.com/download/details.aspx?familyid=13b50993-410f-4e7a-a33a-6d9b48dbb4d1)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft IIS(인터넷 정보 서비스) 6.0](https://www.microsoft.com/download/details.aspx?familyid=e6b806eb-e2c4-4436-8964-720db593055d)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-018**](https://technet.microsoft.com/security/bulletin/ms09-018)
</td>
<td style="border:1px solid black;">
[**MS09-022**](https://technet.microsoft.com/security/bulletin/ms09-022)
</td>
<td style="border:1px solid black;">
[**MS09-019**](https://technet.microsoft.com/security/bulletin/ms09-019)
</td>
<td style="border:1px solid black;">
[**MS09-026**](https://technet.microsoft.com/security/bulletin/ms09-026)
</td>
<td style="border:1px solid black;">
[**MS09-025**](https://technet.microsoft.com/security/bulletin/ms09-025)
</td>
<td style="border:1px solid black;">
[**MS09-020**](https://technet.microsoft.com/security/bulletin/ms09-020)
</td>
<td style="border:1px solid black;">
[**MS09-023**](https://technet.microsoft.com/security/bulletin/ms09-023)
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
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=3ad8f037-2434-4dea-bfc3-9d3b4008b828&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e60215c3-b8b9-4e45-9d9f-b3fb0b47cce1&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6f2730e9-b4fc-4f20-96cf-73f1be63f374&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=5ca227c0-f2dd-429c-a542-e08e93527214&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=c31b36f8-330c-4a0c-9a3d-7cbe9a1ab8c8&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=85c317cd-2a14-4747-9f50-3af3ddd3ae1b&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=88185088-8c2c-4bc6-89b2-87f4d4849cf7&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6f2730e9-b4fc-4f20-96cf-73f1be63f374&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=188adafe-1feb-46ad-b237-a88d35104dcd&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7d70a65f-07ce-4992-8bec-28fefd7587bc&displaylang=ko)  
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
<th style="border:1px solid black;" colspan="8">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-018**](https://technet.microsoft.com/security/bulletin/ms09-018)
</td>
<td style="border:1px solid black;">
[**MS09-022**](https://technet.microsoft.com/security/bulletin/ms09-022)
</td>
<td style="border:1px solid black;">
[**MS09-019**](https://technet.microsoft.com/security/bulletin/ms09-019)
</td>
<td style="border:1px solid black;">
[**MS09-026**](https://technet.microsoft.com/security/bulletin/ms09-026)
</td>
<td style="border:1px solid black;">
[**MS09-025**](https://technet.microsoft.com/security/bulletin/ms09-025)
</td>
<td style="border:1px solid black;">
[**MS09-020**](https://technet.microsoft.com/security/bulletin/ms09-020)
</td>
<td style="border:1px solid black;">
[**MS09-023**](https://technet.microsoft.com/security/bulletin/ms09-023)
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
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=0f18356d-9f09-4d24-8361-970c0d1ccac4&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a0e3f975-57da-43fa-ac12-3d14fd6ce939&displaylang=ko)\*\*  
(보통)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=aaad301c-d232-4733-a0df-8e5d41bbfde8&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=eaa26c6c-5bf7-4099-bb21-1e03de3a25ca&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=98ba52b2-da1a-4939-a10e-d43b3a7e7ed4&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7d0a6e8d-a31d-4f3d-a7d7-e61215bfebed&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=758edce7-2a82-4b2e-bd71-5b7075cc4b17&displaylang=ko)\*\*  
(보통)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=faac92d4-4a2b-4bb5-8bd1-1519a9fa8147&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=447aaa4f-946b-4f23-b151-dcf46ea9f80e&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=dbaa5a72-c267-4907-a207-525c2803d7b9&displaylang=ko)\*  
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
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=bbac3deb-6c93-45aa-832c-02b915ac7f44)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=67d4c189-030d-42eb-98b9-7957ccd92592)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=f33012b9-5d5b-4f72-8d49-a8e1c8bc1337)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=e0e3ad56-a363-44ba-af4d-b7f551c88afd)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**Windows Server 2008 참고 사항**

**\*Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** 지원 대상인 Windows Server 2008 에디션에 대해 이 업데이트의 심각도는 Windows Server 2008에 Server Core 설치 옵션의 사용 여부와 상관없이 동일하게 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

**\*\*Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 Windows Server 2008이 설치된 경우 이 업데이트에서 해결하는 취약점은 지원되는 모든 Windows Server 2008 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

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
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-027**](https://technet.microsoft.com/security/bulletin/ms09-027)
</td>
<td style="border:1px solid black;">
[**MS09-021**](https://technet.microsoft.com/security/bulletin/ms09-021)
</td>
<td style="border:1px solid black;">
[**MS09-024**](https://technet.microsoft.com/security/bulletin/ms09-024)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=3663e9f2-a952-4238-b902-90b5b09feb38&displaylang=ko)  
(KB969600)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=dd16e243-b8e2-4afb-86b6-4d60214598eb&displaylang=ko)  
(KB969683)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=4bf95806-3d32-411b-9779-a81aebad45e9&displaylang=ko)  
(KB957838)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=f1323be1-15f2-491b-abae-c03ba1394398&displaylang=ko)  
(KB969602)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=dd80ce95-0aec-4493-b9d1-c3dad95c3415&displaylang=ko)  
(KB969680)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=b0ba8c9e-75ee-46bd-9e92-d4e6599309ad&displaylang=ko)  
(KB957646)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=7cbc2587-2c8c-49b4-9f40-e4cdccb61ecd&displaylang=ko)  
(KB969603)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=10156044-a5a4-4312-98a7-1b1ced625ddb&displaylang=ko)  
(KB969681)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Works 6–9 파일 변환기가 있는 Microsoft Office Word 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=a7ba3ea7-d06a-4c14-9107-9b92ef68fcae&displaylang=ko)\*\*\*  
(KB968326)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System 서비스 팩 1 및 2007 Microsoft Office System 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 서비스 팩 1 및 Microsoft Office Word 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=7e205108-4c28-4cab-a4d0-4ed3fd696473&displaylang=ko)  
(KB969604)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 서비스 팩 1 및 Microsoft Office Excel 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=2bcd565a-6acb-407d-80da-0398526ddf99&displaylang=ko)\*  
(KB969682)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 서비스 팩 1](https://www.microsoft.com/download/details.aspx?familyid=bd47e1e5-cd2e-4c08-9864-471e97f38ca3&displaylang=ko)  
(KB969559)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-027**](https://technet.microsoft.com/security/bulletin/ms09-027)
</td>
<td style="border:1px solid black;">
[**MS09-021**](https://technet.microsoft.com/security/bulletin/ms09-021)
</td>
<td style="border:1px solid black;">
[**MS09-024**](https://technet.microsoft.com/security/bulletin/ms09-024)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550)  
(KB969661)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550)  
(KB969661)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58)  
(KB971822)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58)  
(KB971822)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6)  
(KB971824)  
(중요)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6)  
(KB971824)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-027**](https://technet.microsoft.com/security/bulletin/ms09-027)
</td>
<td style="border:1px solid black;">
[**MS09-021**](https://technet.microsoft.com/security/bulletin/ms09-021)
</td>
<td style="border:1px solid black;">
[**MS09-024**](https://technet.microsoft.com/security/bulletin/ms09-024)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=20e6933d-85f8-4cec-9534-893789cd053e&displaylang=ko)  
(KB969685)  
(중요)  
[Microsoft Office Excel Viewer](https://www.microsoft.com/download/details.aspx?familyid=ac0530dc-7f63-4ad0-85c1-784ad28156cf&displaylang=ko)  
(KB969686)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=82980a40-f10c-4f02-b06c-3a12d4434a6b&displaylang=ko)  
(KB969614)  
(중요)  
[Microsoft Office Word Viewer](https://www.microsoft.com/download/details.aspx?familyid=82980a40-f10c-4f02-b06c-3a12d4434a6b&displaylang=ko)  
(KB969614)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=63bd8f14-e736-46ce-af66-d30f17461e5a&displaylang=ko)  
(KB969613)  
(중요)
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=a8be8457-b0b6-455e-907e-d13be883adf2&displaylang=ko)  
(KB969679)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 8.5
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](https://www.microsoft.com/download/details.aspx?familyid=628280fe-e035-4274-85f2-393d9bad543c)  
(KB967043)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 9.0
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Works 9.0](https://www.microsoft.com/download/details.aspx?familyid=f6fa110e-45c6-450f-ae47-c89a06e3f762)  
(KB967044)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 서비스 팩 1 및 Microsoft Office SharePoint Server 2007 서비스 팩 2(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=862e6ad1-8124-4060-93b1-2b882ef5ce3d&displaylang=ko)\*\*  
(KB969737)  
(중요)  
[Microsoft Office SharePoint Server 2007 서비스 팩 1 및 Microsoft Office SharePoint Server 2007 서비스 팩 2(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=b7b6e611-2c5d-4639-add9-972055789ecd&displaylang=ko)\*\*  
(KB969737)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**MS09-021 참고 사항**

\*Microsoft Office Excel 2007 서비스 팩 1 및 Microsoft Office Excel 2007 서비스 팩 2를 사용하는 고객은 이 보안 공지에서 설명한 취약점으로부터 보호하기 위해 보안 업데이트 패키지 KB969682와 함께 [Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](https://www.microsoft.com/download/details.aspx?familyid=?...?)(KB969679)에 대한 보안 업데이트를 설치해야 합니다.

\*\*이 업데이트는 Microsoft Office SharePoint Server 2007 Enterprise 및 Microsoft Office SharePoint Server 2007 For Internet Sites와 같이 Excel Services가 설치된 서버에 적용됩니다. Microsoft Office SharePoint Server 2007 Standard에는 Excel Services가 포함되지 않습니다.

**MS09-024 참고 사항**

\*\*\*Microsoft Office Word 2003은 취약한 Works 변환기가 설치된 경우 영향을 받습니다. Works 변환기는 [Microsoft Works 6–9 파일 변환기](https://www.microsoft.com/download/details.aspx?familyid=bf41401e-70fa-465d-ae2e-cf44dbf05297&displaylang=en)에서 다운로드하여 Microsoft Office Word 2003에 사용할 수 있습니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](https://technet.microsoft.com/ko-kr/updatemanagement/default.aspx)를 참조하십시오. [TechNet Security Center](https://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](https://www.microsoft.com/korea/protect/default.mspx)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 및 [Office 업데이트](https://go.microsoft.com/fwlink/?linkid=21135)에서 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](https://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security%20update)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](https://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](https://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 이 달의 보안 업데이트를 위한 검색 및 배포 지침을 제공하였습니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), ESUIT(Extended Security Update Inventory Tool) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](https://support.microsoft.com/kb/910723)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](https://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](https://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](https://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.mspx)를 참조하십시오. SMS 2.0 사용자는 [Software Updates Service Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=33340)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](https://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer와 Microsoft Office 검색 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](https://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack (영문)](https://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit) 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트 (영문)](https://technet.microsoft.com/en-us/wsus/dd573344.aspx)

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](https://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](https://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security%20update)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://technet.microsoft.com/security/bulletin/policy)드립니다.

-   MS09-018에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](https://labs.idefense.com/)의 Joshua J. Drake
-   MS09-019에서 설명한 문제점을 해결하기 위해 협력해 주신 [Google Inc. (영문)](https://www.google.com/)의 David Bloom
-   MS09-019에서 설명한 문제점을 보고해 주신 [Core Security Technologies (영문)](https://www.coresecurity.com/)의 Jorge Luis Alvarez Medina
-   MS09-019에서 설명한 문제점을 보고해 주신 [Fortinet (영문)](https://www.fortinet.com/)의 Haifei Li
-   MS09-019에서 설명한 문제점을 보고해 주신 [Tippingpoint (영문)](https://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)
-   MS09-019에서 설명한 문제점을 [Tippingpoint (영문)](https://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Peter Vreugdenhil
-   MS09-019에서 설명한 두 가지 문제점을 [Tippingpoint (영문)](https://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Wushi
-   MS09-019에서 설명한 문제점을 [Tippingpoint (영문)](https://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Nils
-   MS09-027에서 설명한 문제점을 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 [team509 (영문)](https://www.team509.com/)의 Wushi
-   MS09-027에서 설명한 문제점을 보고해 주신 [VUPEN Security (영문)](https://www.vupen.com/)의 Nicolas Joly
-   MS09-021에서 설명한 세 가지 문제점을 보고해 주신 Fortinet, [FortiGuard Global Security Research Team (영문)](https://www.fortiguardcenter.com/)의 Bing Liu
-   MS09-021에서 설명한 문제점을 보고해 주신 [Secunia (영문)](https://secunia.com/)의 Carsten H. Eiram
-   MS09-021에서 설명한 문제점을 보고해 주신 [Telus (영문)](https://www.telus.com/)의 Ehsan Foroughi
-   MS09-021에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](https://labs.idefense.com/)의 Sean Larsson 및 Joshua Drake
-   MS09-021에서 설명한 문제점을 보고해 주신 [Secunia (영문)](https://secunia.com/)의 Carsten H. Eiram
-   MS09-021에서 설명한 문제점을 보고해 주신 [TippingPoint (영문)](https://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](https://www.zerodayinitiative.com/)
-   MS09-022에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](https://labs.idefense.com/)의 Jun Mao
-   MS09-023에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](https://labs.idefense.com/)
-   MS09-023에서 설명한 문제점을 보고해 주신 [SkyRecon (영문)](https://www.skyrecon.com/)의 Thomas Garnier
-   MS09-024에 설명한 문제점을 보고해 주신 [NGS Software (영문)](https://www.ngssoftware.com/)의 Shaun Colley
-   MS09-025에서 설명한 두 가지 문제점을 보고해 주신 [SkyRecon (영문)](https://www.skyrecon.com/)의 Thomas Garnier
-   MS09-020에서 설명한 문제점을 보고해 주신 [Palo Alto Networks (영문)](https://www.paloaltonetworks.com/)의 Yamata Li
-   MS09-028에서 설명한 문제점을 보고해 주신 [IBM Rational Application Security (영문)](https://www-01.ibm.com/software/rational/offerings/websecurity/webappsecurity.html)의 Yair Amit

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](https://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](https://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](https://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2009년 6월 10일): 공지 요약이 게시되었습니다.
-   V1.1(2009년 6월 11일): 악용 가능성 인덱스에서 CVE-2009-1138 용 키 노트 및 등급이 수정 되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
