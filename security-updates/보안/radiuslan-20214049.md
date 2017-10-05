---
TOCTitle: '운영 설명서 — RADIUS 및 무선 LAN 보안 인프라 관리'
Title: '운영 설명서 — RADIUS 및 무선 LAN 보안 인프라 관리'
ms:assetid: 'a8801b8d-0c14-418c-865a-7fd8b287a52c'
ms:contentKeyID: 20214049
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547894(v=TechNet.10)'
---

12장: RADIUS 및 무선 LAN 보안 인프라 관리
=========================================

게시 날짜: 2004년 11월 20일 | 업데이트 날짜: 2004년 11월 24일

##### 이 페이지에서

[](#ejaa)[소개](#ejaa)
[](#eiaa)[필수 유지 관리 작업](#eiaa)
[](#ehaa)[운영 설명서의 필요한 기술](#ehaa)
[](#egaa)[RADIUS 및 WLAN 보안 관리 역할](#egaa)
[](#efaa)[운영 사분면 작업](#efaa)
[](#eeaa)[지원 사분면 작업](#eeaa)
[](#edaa)[최적화 사분면 작업](#edaa)
[](#ecaa)[변경 사분면 작업](#ecaa)
[](#ebaa)[구성 표](#ebaa)
[](#eaaa)[추가 정보](#eaaa)

### 소개

이 장에서는 이 *무선* *LAN* *보안* 지침의 일부로 구현된 RADIUS(Remote Authentication Dial-in User Service) 인프라 및 WLAN(무선 LAN) 보안의 관리에 필요한 운영 절차를 설명합니다. 이러한 구조는 10장, "운영 설명서 소개"에서 논의된 MOF(Microsoft Operations Framework) 범주 및 개념을 기반으로 합니다.

이 장에서는 시스템 모니터링과 관리를 시작하기 위한 모든 설정 작업을 포함하여, RADIUS 인프라 및 무선 LAN 보안을 위한 완전한 관리 시스템을 구현하는 방법을 설명합니다. 또한 인프라의 정상적인 작동을 유지하기 위한 일반적인 운영 작업, 사건 지원와 환경 변화를 관리하고 시스템 성능을 최적화하는 데 유용한 절차도 포함합니다.

이 장은 크게 두 부분으로 구성되어 있습니다. 첫 번재 부분은 "필수 유지 관리 작업"과 "RADIUS 및 WLAN 보안 관리 역할"의 두 절로 나누어지는데, 길지 않으므로 완전히 읽어야 합니다. 시스템을 위한 올바른 관리 환경을 설정하는 데 핵심적인 정보를 담고 있습니다. 이 장의 나머지 내용은 주로 참고 자료로 사용되어야 합니다. 시스템을 배포할 때 참고 절의 몇 가지 작업을 수행해야 합니다. 이 작업은 "필수 유지 관리 작업" 절에 나와 있습니다.

참고 자료 절의 모든 세부 사항을 소화할 필요는 없지만 나중에 필요한 항목을 빨리 찾을 수 있도록 내용을 익혀 놓는 것이 좋습니다.

#### 장 전제 조건

10장 "운영 설명서 소개"에서 논의된 MOF 개념을 익히는 것이 좋습니다. MOF를 상세하게 알 필요는 없습니다.

802.11, 802.1X 및 EAP-TLS 개념과 특히 RADIUS 및 Microsoft® IAS(인터넷 인증 서비스) 개념을 이해해야 합니다. 이 기술 항목에 관한 자세한 정보는 계획 설명서의 참고 자료를 참조하십시오.

다음 영역에서 Microsoft Windows® 2000 Server(이상)를 잘 이해해야 합니다.

-   Microsoft Windows Server™ 2003의 기본 운영 및 유지 관리(이벤트 뷰어, 컴퓨터 관리 및 NTBackup과 같은 도구 사용 포함).

-   Active Directory® 디렉터리 서비스 개념 및 작업. 여기에는 Active Directory 구조, 도구, 사용자, 그룹, 기타 Active Directory 개체 관리 및 그룹 정책 사용 등이 포함됩니다.

-   사용자, 그룹, 감사, 액세스 제어 목록 등의 Windows 시스템 보안 개념, 보안 템플릿 사용, 그룹 정책 또는 명령줄 도구를 사용한 보안 템플릿 적용.

-   인터넷 인증 서비스 관리.

-   WSH(Windows Scripting Host) 및 Microsoft Visual Basic® Scripting Edition(VBScript) 언어. 배치 프로그래밍 구문을 이해하면 제공되는 스크립트를 최대한 활용하는 데 도움이 되지만 필수적인 것은 아닙니다.

또한 이 장을 읽기 전에 계획 설명서 및 구축 설명서를 읽고 솔루션 아키텍처와 디자인을 철저하게 이해하는 것이 좋습니다.

#### 장 개요

다음 목록은 이 장 주요 절을 하나씩 설명합니다.

-   **필수유지관리작업.** 관리 시스템을 설치하는 데 필요한 작업 목록 및 시스템을 유지 관리하기 위해 정기적으로 수행해야 하는 작업 목록의 두 가지가 있습니다.

-   **관리역할**. 솔루션에 사용된 관리 역할, 각 역할의 기능 및 역할이 솔루션에 정의된 MOF 역할 클러스터 및 관리 보안 그룹에 매핑되는 방식을 설명합니다.

-   **운영사분면작업**. 정상적인 RADIUS 인프라 유지 관리 및 WLAN 보안과 관련한 모든 작업을 포함합니다. 이 절은 모니터링, 백업 및 디렉터리/보안 작업을 다룹니다.

-   **지원사분면작업**. 시스템 문제 복구에 관한 모든 절차가 있습니다. 이 절은 백업 복원 및 실패한 IAS 서버 처리 작업을 다룹니다.

-   **최적화사분면작업**. 성능 관리 계획 절차를 다룹니다.

-   **변경사분면작업**. IAS 구성 변경 및 변경 내용을 제어 가능한 방법으로 생산 단계에 배포하는 공통 작업을 다룹니다. IAS에 관한 필수 구성 정보를 수집하고 관리하는 데 필요한 절차도 있습니다.

-   **문제해결**. RADIUS 인프라 및 WLAN 보안에서 흔히 발생하는 문제를 해결하는 데 유용한 절차가 들어 있습니다. 또한 유용한 문제 해결 도구와 여러 구성 요소 로깅에 필요한 절차를 설명합니다.

-   **구성표**. 구축 설명서에 사용된 구성 매개 변수의 일부분입니다. 이 값은 절차 설명에 예제로 사용됩니다.

-   **추가정보**. 설명에서 언급되는 다양한 추가 정보 출처 목록입니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 필수 유지 관리 작업

이 절은 RADIUS 인프라 및 WLAN 보안을 성공적으로 작동하기 위해 수행해야 하는 핵심 작업을 설명합니다. 작업은 초기 설정 작업과 지속적인 운영 작업으로 나뉘어 두 개의 표로 정리했습니다. 표에 나오는 작업 이름에 대해서는 문서의 뒷부분에 자세히 설명되어 있습니다. 작업은 MOF 사분면별로 그룹화되어 있으며, 각 작업이 속하는 MOF SMF(서비스 관리 기능)가 각 작업 옆에 표시되어 있어서 필요한 작업을 쉽게 찾을 수 있습니다.

이 절에는 이 장의 절차에 사용되는 도구 및 기술 목록이 있습니다.

#### 초기 설정 작업

다음 표는 RADIUS 인프라 및 WLAN 보안 작업을 실제 프로덕션 환경에서 구현하기 위해 수행해야 하는 작업을 보여 줍니다. 운영 기준과 관행에 따라 작업 모두를 수행할 필요가 없는 경우도 있습니다. 하지만 각 작업의 세부 사항을 검토하고 수행할 필요가 있는지 결정해야 합니다. 이들 작업 중 일부는 일정 시점이 되면 다시 수행해야 할 수도 있습니다. 예를 들어 새 IAS 서버를 설치한 경우 백업 및 모니터링 작업을 구성해야 합니다.

**표** **12.1** **초기설정작업**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >작업 이름</th>
<th style="border:1px solid black;" >서비스 관리 기능</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>운영사분면</strong></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS 서버에 RADIUS 클라이언트 추가</td>
<td style="border:1px solid black;">네트워크 관리</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">컴퓨터에 무선 설정 사용</td>
<td style="border:1px solid black;">디렉터리 서비스 관리</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">원격 액세스 정책 그룹에 컴퓨터 및 사용자 추가</td>
<td style="border:1px solid black;">디렉터리 서비스 관리</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">모니터링 경고 범주화</td>
<td style="border:1px solid black;">서비스 모니터링 및 제어</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS 용량 제한 모니터링</td>
<td style="border:1px solid black;">서비스 모니터링 및 제어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS 구성 내보내기 구성</td>
<td style="border:1px solid black;">저장소 관리</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RADIUS 클라이언트 구성 내보내기</td>
<td style="border:1px solid black;">저장소 관리</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS 데이터 디렉터리의 백업 구성</td>
<td style="border:1px solid black;">저장소 관리</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS 백업 테스트</td>
<td style="border:1px solid black;">저장소 관리</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>최적화사분면</strong></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS 서버의 최대 로드 확인</td>
<td style="border:1px solid black;">성능 관리</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS 서버에 대한 저장소 및 백업 요구 사항 확인</td>
<td style="border:1px solid black;">성능 관리</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>변경사분면</strong></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">운영 체제 업데이트 관리</td>
<td style="border:1px solid black;">변경 관리<br />
릴리스 관리</td>
</tr>
</tbody>
</table>
 

#### 유지 관리 작업

이 표는 RADIUS 인프라 및 WLAN 보안이 올바르게 동작하도록 하기 위해 정기적으로 수행해야 하는 작업을 보여 줍니다. 이 표를 사용하여 보다 쉽게 필요한 리소스 및 시스템 관리 작업 일정을 계획할 수 있습니다.

수행하지 않아도 되는 작업이 있지만 각 작업을 자세히 검토한 후 수행할 필요가 있는지 결정해야 합니다. 또한 어떤 작업은 필요할 때만 수행하고 어떤 작업은 일정에 따라 수행합니다. 예를 들어 IAS 서버에 RADIUS 클라이언트를 추가한 경우 예정에 없어도 서버 구성의 내보내기/백업을 수행해야 합니다. 그런 작업은 빈도 열에 나와 있습니다. 이와 같은 종속 관계에 대해서는 작업 정보에서도 설명합니다.

**표** **12.2** **지속적인유지관리작업**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >작업 이름</th>
<th style="border:1px solid black;" >빈도</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">IAS 서버에 RADIUS 클라이언트 추가</td>
<td style="border:1px solid black;">네트워크에 무선 AP가 추가될 때</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS 서버에서 RADIUS 클라이언트 제거</td>
<td style="border:1px solid black;">무선 AP가 네트워크에서 제거될 때</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">컴퓨터에 무선 설정 사용</td>
<td style="border:1px solid black;">네트워크에 컴퓨터가 추가될 때</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">원격 액세스 정책 그룹에 컴퓨터 및 사용자 추가</td>
<td style="border:1px solid black;">직원에게 WLAN 액세스 권한이 부여될 때</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RADIUS 클라이언트 구성 내보내기</td>
<td style="border:1px solid black;">네트워크에 무선 AP가 추가될 때</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS 백업 테스트</td>
<td style="border:1px solid black;">매월</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS RADIUS 요청 로그에 액세스</td>
<td style="border:1px solid black;">매일 또는 매주<br />
(보안 요구 사항에 따라)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS RADIUS 인증 이벤트 로그 항목 검토</td>
<td style="border:1px solid black;">매일 또는 매주<br />
(보안 요구 사항에 따라)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS RADIUS 로그 항목 보관 및 삭제</td>
<td style="border:1px solid black;">매월</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">운영 체제 업데이트 관리</td>
<td style="border:1px solid black;">매일</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 운영 설명서의 필요한 기술
  
다음 표는 이 장에서 다루는 절차에 사용된 도구 또는 기술을 보여 줍니다.
  
**표** **12.3** **필요한기술**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >항목 이름</th>
<th style="border:1px solid black;" >소스</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Active Directory 사용자 및 컴퓨터 MMC 스냅인</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MSS 스크립트</td>
<td style="border:1px solid black;">솔루션</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">텍스트 편집기</td>
<td style="border:1px solid black;">메모장 — Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 작업 스케줄러 서비스</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SchTasks.exe</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 백업</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">이벤트 뷰어</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">성능 모니터</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Net.exe</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Operational Alert 콘솔</td>
<td style="border:1px solid black;">MOM(Microsoft Operations Manager)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">시스템 외부 저장에 사용할 이동식 미디어</td>
<td style="border:1px solid black;">플로피 디스크, CD–RW 또는 테이프</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS 서버 백업</td>
<td style="border:1px solid black;">네트워크 백업 서비스<br />
또는<br />
로컬 백업 장치</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">그룹 정책 관리 콘솔</td>
<td style="border:1px solid black;">Microsoft.com에서 웹 다운로드</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IASParse</td>
<td style="border:1px solid black;">Windows Server 2003 지원 도구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Access 2002</td>
<td style="border:1px solid black;">Microsoft Office XP</td>
</tr>
</tbody>
</table>
  
**표** **12.4** **권장기술**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >항목 이름</th>
<th style="border:1px solid black;" >소스</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Operational Alert 콘솔</td>
<td style="border:1px solid black;">Microsoft Operations Manager 또는 기타 서비스 모니터링 시스템</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">전자 메일 인프라 – 작업 경고용(MOM의 대안)</td>
<td style="border:1px solid black;">Microsoft Exchange Server 및 Microsoft Outlook® 등의 SMTP/POP3/IMAP 서버 및 클라이언트</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Eventquery.vbs</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">성능 계획 도구</td>
<td style="border:1px solid black;">Microsoft Operations Manager 또는 기타 성능 계획 도구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">보안 업데이트 배포 시스템</td>
<td style="border:1px solid black;">Microsoft Systems Management Server<br />
또는<br />
Microsoft Software Update Services</td>
</tr>
</tbody>
</table>
 

[](#mainsection)[페이지 위쪽](#mainsection)

### RADIUS 및 WLAN 보안 관리 역할

RADIUS 인프라 및 WLAN 보안 관리에는 수많은 역할이 관련되어 있습니다. 다음 두 절에서는 핵심 역할과 이를 지원하는 지원 역할에 대해 설명합니다.

#### RADIUS 및 WLAN 핵심 역할

다음 표의 역할은 RADIUS 인프라 및 WLAN 보안 관리에 핵심적입니다.

**표** **12.5 RADIUS** **및** **WLAN** **핵심보안역할**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >역할 이름</th>
<th style="border:1px solid black;" >범위</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Internet Authentication Service Administrator</td>
<td style="border:1px solid black;">엔터프라이즈</td>
<td style="border:1px solid black;">회사 IAS의 전반적인 관리 및 구성을 담당합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Internet Authentication Service Auditor</td>
<td style="border:1px solid black;">엔터프라이즈</td>
<td style="border:1px solid black;">IAS 서버 컴퓨터에 있는 RADIUS 로그를 검토, 보관 및 삭제하는 작업을 담당합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Internet Authentication Service Backup Operators</td>
<td style="border:1px solid black;">엔터프라이즈</td>
<td style="border:1px solid black;">IAS 구성 상태 및 이력 데이터의 백업 및 복원을 담당합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">WLAN Helpdesk Staff</td>
<td style="border:1px solid black;">엔터프라이즈</td>
<td style="border:1px solid black;">WLAN 문제점 해결을 담당하는 지원 부서의 상급 직원입니다.</td>
</tr>
</tbody>
</table>
  
#### RADIUS 및 WLAN 지원 보안 역할
  
다음 표의 운영 역할은 RADIUS 인프라 및 WLAN 보안 관리에 핵심적이지는 않지만 핵심 역할을 지원합니다.
  
**표** **12.6 RADIUS** **및** **WLAN** **보안역할지원**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >역할 이름</th>
<th style="border:1px solid black;" >범위</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Monitor Operator</td>
<td style="border:1px solid black;">엔터프라이즈</td>
<td style="border:1px solid black;">이벤트 모니터링을 담당합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Capacity Planner</td>
<td style="border:1px solid black;">엔터프라이즈</td>
<td style="border:1px solid black;">향후 성능 요구 사항을 예측하기 위해 성능 및 로드를 분석하는 작업을 담당합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Active Directory Administrator</td>
<td style="border:1px solid black;">엔터프라이즈</td>
<td style="border:1px solid black;">Active Directory 인프라의 구성 및 지원을 담당합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Active Directory Operations</td>
<td style="border:1px solid black;">엔터프라이즈</td>
<td style="border:1px solid black;">보안 그룹 유지 관리, 계정 작성 등 매일 수행하는 디렉터리 유지 관리 작업을 담당합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Desktop Administrator</td>
<td style="border:1px solid black;">엔터프라이즈</td>
<td style="border:1px solid black;">데스크톱 컴퓨터의 구성 및 지원을 담당합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Change Approvals Board</td>
<td style="border:1px solid black;">엔터프라이즈</td>
<td style="border:1px solid black;">인프라 변경을 승인하는 데 필요한 업무 및 기술 대표입니다.</td>
</tr>
</tbody>
</table>
  
#### 역할과 보안 그룹 간 대응 관계
  
아래 표는 이 솔루션을 위해 정의된 보안 그룹을 보여 주며 각 그룹의 기능 또는 사용 권한을 간단히 설명합니다.
  
IAS 서버의 경우 각 역할에 적용할 수 있는 사용 권한을 적용하기 위해 도메인 및 로컬 보안 그룹을 사용합니다. 도메인 계정은 역할 그룹을 채우는 데 사용됩니다. 조직의 보안과 IT 정책에 맞는다면 단일 계정을 여러 역할 그룹의 구성원으로 만들 수 있습니다.
  
**표** **12.7 RADIUS** **및** **WLAN** **보안역할과보안그룹간매핑**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >역할 이름</th>
<th style="border:1px solid black;" >도메인 보안 그룹</th>
<th style="border:1px solid black;" >로컬 보안 그룹</th>
<th style="border:1px solid black;" >권한</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Internet Authentication Service Administrator</td>
<td style="border:1px solid black;">IAS Admins</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">IAS 서비스 시작/중지 및 해당 구성 변경을 비롯하여 IAS 서버에 대한 전체 관리 권한</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Internet Authentication Service Auditors</td>
<td style="border:1px solid black;">IAS Security Auditors</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">로깅 볼륨에 대한 RADIUS 요청 로그 파일을 읽고 삭제하는 기능</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS Backup Operators</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">Backup Operators</td>
<td style="border:1px solid black;">운영 체제 상태 및 IAS 구성 데이터의 전체 백업 및 복원</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">WLAN Helpdesk Staff</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">IAS Administrator와 협력하여 IAS 인증 문제를 해결합니다. (경우에 따라 IAS Security auditor와 동일한 리소스에 읽기 권한을 부여할 수 있음)</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 운영 사분면 작업
  
운영 사분면에는 미리 결정된 매개 변수 내에서 서비스 수준을 확보하고 관리하기 위해 서비스 솔루션에 정기적으로 적용하는 IT 운영 표준, 프로세스 및 절차가 포함됩니다. 운영 사분면의 목표는 일상적인 수동 및 자동 작업을 쉽게 예측할 수 있는 방식으로 수행하는 것입니다.
  
이 절은 다음 SMF와 관련된 정보를 제공합니다.
  
-   네트워크 관리
  
-   디렉터리 서비스 관리
  
-   보안 관리
  
-   저장소 관리
  
-   서비스 모니터링 및 제어
  
-   작업 예약
  
나머지 SMF에 속하는 작업이 없습니다.
  
-   시스템 관리
  
-   네트워크 관리
  
-   인쇄 및 출력 관리
  
    **참고:** 각 작업 설명에는 보안 요구 사항, 빈도 및 기술 요구 사항의 요약 정보가 들어 있습니다.
  
#### 네트워크 관리
  
네트워크 관리 역할은 서비스, 라우터, 스위치 및 방화벽과 같이 조직의 네트워크를 구성하는 실제 구성 요소의 설계 및 유지 관리를 담당합니다. 무선 네트워크의 경우 이 구성 요소에는 무선 액세스 지점(AP) 및 이를 지원하는 RADIUS 서버도 포함됩니다.
  
##### IAS 서버에 RADIUS 클라이언트 추가
  
무선 AP는 IAS 서버와의 인증 및 계정 부여 작업을 수행하기 위해 권한을 부여받아야 합니다. 새 무선 AP를 RADIUS 클라이언트로 사용하는 작업은 배포된 프로덕션 IAS 서버에서 이루어져야 하는 드문 증분 변화 중 하나입니다. 이 작업은 무선 AP에 권한을 부여하여 RADIUS 인증 및 IAS 서버 계정을 받도록 합니다. 새 무선 AP가 배포되고 네트워크 인증에 참여하도록 구성될 때마다 이 작업을 수행하십시오.
  
###### 요약 정보
  
-   **보안구성요소**: IAS Admins 보안 그룹의 구성원 자격
  
-   **빈도**: 네트워크에 새 무선 AP를 추가할 때
  
-   **기술요구사항**:
  
    -   인터넷 인증 서버 MMC 스냅인
  
    -   MSS 스크립트(GenPwd 스크립트 명령용)
  
    -   플로피 디스크 드라이브 또는 기타 쓰기 가능한 이동식 미디어 드라이브
  
    -   플로피 디스크 또는 기타 쓰기 가능한 이동식 미디어
  
###### 작업 정보
  
AP를 각 IAS 서버에 추가할 때 각 무선 AP별로 고유한, 임의로 생성된 암호(비밀)를 사용합니다. 여러 무선 AP에 하나의 RADIUS 암호를 사용하면 공유 암호가 오랫동안 비밀로 유지되지 않을 위험이 커집니다.
  
Windows Server 2003 Enterprise Edition으로 관리자는 전용 RADIUS 클라이언트 서브넷을 추가하고 해당 서브넷의 모든 AP에 공유 암호를 사용하여 무선 AP를 대량으로 IAS에 추가할 수 있습니다. 이 방법은 암호 관리를 단순화하지만 고유한 암호를 사용하는 것에 비해 솔루션 보안이 약해집니다.
  
이 솔루션은 이 설명서에 포함된 GenPwd 스크립트가 암호화 방식에 따라 무작위로 생성한 암호를 구현합니다.
  
**IAS에** **RADIUS** **클라이언트를개별적으로추가하려면다음을수행합니다.**
  
1.  인터넷 인증 서비스 MMC 스냅인에서 **RADIUS** **클라이언트** 폴더를 마우스 오른쪽 단추로 클릭하고 **새** **RADIUS** **클라이언트**를 클릭합니다.
  
2.  무선 AP의 **이름**과 **클라이언트주소(IP** **또는** **DNS)**를 입력합니다. 서버가 시작되면 IAS는 각 RADIUS 클라이언트를 확인하려 하므로 DNS 이름 대신 IP 주소를 사용해야 합니다. 무선 AP가 많은 대규모 사용 환경에서 DNS 이름으로 클라이언트를 확인하면 시작이 지연됩니다. **다음**을 클릭합니다.
  
3.  클라이언트-공급업체 특성으로 **RADIUS** **표준**을 선택하고 해당 특정 무선 AP에 대한 공유 암호를 입력합니다.
  
    **참고**: 다음 단계에서 플로피 디스크 또는 기타 쓰기 가능한 이동식 미디어 사용을 다룹니다. 포맷된 미디어 디스크를 찾아 "*&lt;서버이름&gt;*의 RADIUS 클라이언트"라는 레이블을 부착합니다.
  
4.  이 설명서에 포함된 GenPwd 스크립트를 사용하면 RADIUS 클라이언트로 구성된 각 무선 AP가 개별적으로 사용할 수 있는 강력한 무작위 암호를 생성할 수 있습니다. GenPwd는 암호를 생성한 다음 각 RADIUS 클라이언트에 대한 이름과 해당 암호를 함께 Clients.txt 파일에 저장합니다. 또한 현재 디렉터리의 Clients.txt 파일에 쉼표로 구분한 값 형태로 해당 정보가 자동으로 추가됩니다. 하지만 수준 높은 RADIUS 암호를 생성하는 방법이 있으면 다음 몇몇 단계에서 GenPwd 대신 그 방법을 사용해도 됩니다.
  
    **참고:** GenPwd는 CryptoAPI 함수를 사용하여 암호화 방식으로 base64 인코딩된 무작위 문자열을 만듭니다. VBScript 난수 함수를 사용하지 않습니다.
  
5.  명령 프롬프트를 열고 A:\\ 디렉터리를 현재 디렉터리로 사용합니다. 현재 디렉터리의 Clients.txt 파일에 새 정보가 자동으로 추가되므로 파일 시스템 디렉터리 위치가 중요합니다. Clients.txt 파일이 없으면 자동으로 만들어집니다.
  
6.  다음 명령을 실행합니다. *&lt;client\_name&gt;*을 무선 AP 이름으로 바꾸어야 합니다. 이 이름은 DNS 이름, IP 주소 또는 다른 문자열일 수 있습니다.
  
    cscript //job:GenPwd C:\\MSSScripts\\wl\_tools.wsf /client:client\_name
  
    쉼표로 구분되는 파일을 작성한 후 참조 및 편집을 위해 쉽게 스프레드시트 또는 데이터베이스 응용 프로그램으로 가져올 수 있습니다.
  
    **중요**: 각 IAS 서버 및 무선 AP의 RADIUS 암호는 정기적으로 변경해야 합니다. GenPwd 또는 기타 유틸리티를 사용하여 강력한 암호를 생성하고 새 암호 및 무선 AP 이름을 Clients.txt 파일에 저장하십시오. clients.txt 파일의 데이터는 매우 중요합니다. 이 파일을 서버에 복사하지 마십시오. 금고 같은 안전한 장소에 보관하십시오.
  
7.  인터넷 인증 서비스 MMC 스냅인에서 **공유암호** 및 **공유암호확인** 필드에 RADIUS 공유 암호를 입력합니다. **요청에메시지인증자특성이포함되어야함**을 선택하고 **마침**을 클릭합니다.
  
    **참고**: 일부 RADIUS 클라이언트는 VSA(공급업체별 특성)를 구성해야 올바르게 동작합니다. VSA 요구 사항과 관련된 정보는 공급업체별 설명서를 참조하십시오.
  
##### IAS 서버에서 RADIUS 클라이언트 제거
  
RADIUS 클라이언트로 사용했던 불필요한 무선 AP를 제거하는 것은 배포된 프로덕션 IAS 서버에 수행해야 하는 몇 가지 변경 사항 중 하나입니다. 이 작업은 무선 AP의 RADIUS 인증 및 IAS 서버 계정 등록을 막습니다. 무선 AP가 RADIUS 인증 및 계정 서비스를 사용하지 못하도록 제거할 때마다 이 작업을 수행합니다.
  
###### 요약 정보
  
-   **보안요구사항**: IAS Administrators 그룹의 구성원 자격
  
-   **빈도**: 네트워크에서 무선 AP를 제거할 때
  
-   **기술요구사항**:
  
    -   인터넷 인증 서버 MMC 스냅인
  
    -   Notepad.exe 또는 기타 텍스트 파일 편집기
  
###### 작업 정보
  
IAS에서 각 무선 액세스 지점을 따로 제거합니다. 안전한 곳에 보관해 놓은 RADIUS 클라이언트 플로피 디스크에 있는 Clients.txt 파일의 해당 항목도 삭제해야 합니다. Clients.txt 파일은 "IAS 서버에 RADIUS 클라이언트 추가" 작업의 절차에 따라 생성됩니다.
  
**IAS** **서버에서** **RADIUS** **클라이언트를제거하려면다음을수행합니다.**
  
1.  IAS(인터넷 인증 서버) MMC 스냅인에서 RADIUS 클라이언트 폴더를 선택합니다.
  
2.  오른쪽 창에서 제거할 RADIUS 클라이언트에 해당하는 항목을 선택한 후 **삭제** 키를 누릅니다.
  
3.  확인 메시지가 표시되면 **예**를 클릭합니다.
  
    **참고**: 다음 단계에서는 이전 절에서 만든 "*&lt;서버이름&gt;*의 RADIUS 클라이언트"라는 레이블이 부착된 플로피 디스크 또는 기타 쓰기 가능한 이동식 미디어를 사용합니다. 데이터 손실을 방지하려면 해당 서버에 올바른 디스크를 사용해야 합니다.
  
4.  이 서버의 RADIUS 클라이언트 플로피 디스크를 찾고 메모장을 사용하여 A:\\Clients.txt 파일을 엽니다.
  
5.  사용하지 않을 RADIUS 클라이언트와 관련된 항목을 찾아서 삭제합니다.
  
#### 디렉터리 서비스 관리
  
디렉터리 서비스를 통해 사용자와 응용 프로그램은 네트워크에서 사용자, 서버, 응용 프로그램, 도구, 서비스 및 기타 정보와 같은 네트워크 리소스를 찾을 수 있습니다. 디렉터리 서비스 관리는 엔터프라이즈 디렉터리에 대한 일상적인 작업, 유지 관리 및 지원 업무를 처리합니다. 디렉터리 서비스 관리는 권한이 있는 요청자라면 누구든지 간단하고 체계적인 프로세스를 사용하여 네트워크로 정보를 액세스하도록 합니다.
  
##### 사용자 및 컴퓨터의 WLAN 액세스 사용
  
WLAN을 액세스하려면 세 가지 작업을 별도로 수행해야 합니다. 이 작업은 모두 보안 그룹 구성원 자격으로 제어하기 때문에 VBScript, Jscript 또는 명령(배치) 파일 스크립트를 사용하여 쉽게 자동화할 수 있습니다. 이 작업은 많은 조직에서 WLAN 도입의 여러 단계에서 수행하기 때문에 각각 따로 문서화되어 있습니다.
  
**중요:** 이 솔루션은 사용자 지정 보안 그룹을 사용하여 어떤 사용자 및 컴퓨터가 WLAN 인증서 및 정책 설정을 받는지와 어떤 사용자와 컴퓨터에 IAS를 통한 WLAN 액세스를 허용할 것인지를 제어합니다. 세 가지 항목이 인증서, 정책 설정 및 WLAN 액세스의 단계적인 배포를 허용하도록 별도의 그룹이 사용됩니다. 이렇게 정교한 제어를 원치 않는 경우 모든 항목에 대해 모든 사용자와 컴퓨터를 허용할 수 있습니다. 모든 사용자 및 컴퓨터를 허용하는 가장 쉬운 방법은 도메인 사용자 또는 도메인 컴퓨터를 관련 인증서 등록 그룹, WLAN 그룹 정책 그룹(컴퓨터만) 및 WLAN 액세스 그룹에 추가하는 것입니다.
  
**컴퓨터용** **WLAN** **액세스를사용하려면다음을수행합니다.**
  
1.  "사용자 또는 컴퓨터에 대해 인증서 종류 등록(또는 자동 등록) 사용" 절차에 따라 컴퓨터 계정을 인증서 등록 그룹 **클라이언트인증** **–** **컴퓨터인증서자동등록**에 추가합니다.
  
2.  "컴퓨터에 무선 설정 사용" 절차(이 절 뒷부분)에 따라 현재 네트워크 설정을 컴퓨터에 배포합니다. 컴퓨터 계정을 **무선네트워크정책** **–** **컴퓨터** 정책 그룹에 추가합니다.
  
3.  "원격 액세스 정책 그룹에 컴퓨터 및 사용자 추가" 절차(이 절 뒷부분)에 따라 컴퓨터에 WLAN에 연결할 수 있는 권한을 부여합니다. 컴퓨터 계정을 원격 액세스 보안 그룹 **원격액세스정책** **–** **무선컴퓨터**에 추가합니다.
  
    **중요:** 이 단계는 임의의 순서로 수행할 수 있습니다. 대규모 배포 시 WLAN 하드웨어를 사용하기 훨씬 전에 모든 단계를 수행할 수 있습니다. 컴퓨터는 적어도 한 번 *다시부팅해야* 각 절차에서 지정한 그룹 구성원 자격을 얻을 수 있습니다. 컴퓨터 로그온 토큰은 일정 시간이 지나면 시간 제한에 도달하여 그룹 구성원 자격을 갱신하는데 이 프로세스는 최대 1주일까지 걸릴 수 있습니다.  
    컴퓨터가 초기 인증서 및 초기 무선 설정을 받으려면 *유선네트워크에연결되어있어야* 합니다. 인증서 갱신 및 향후 무선 설정 변경은 WLAN으로 받습니다.
  
**사용자용** **WLAN** **액세스를사용하려면다음을수행합니다.**
  
1.  11장의 "사용자 또는 컴퓨터에 대해 인증서 종류 등록(또는 자동 등록) 사용" 절차에 따라 사용자 계정을 인증서 등록 그룹 **클라이언트인증** **-** **사용자인증서자동등록**에 추가합니다.
  
2.  사용자가 허가 받고 구성된 WLAN 컴퓨터를 사용하여 로그온하도록 합니다(이전 절차에서 설명). 특히 컴퓨터는 정확한 WLAN 정책 설정으로 구성해야 합니다.
  
3.  "원격 액세스 정책 그룹에 컴퓨터 및 사용자 추가" 절차(이 절 뒷부분)에 따라 컴퓨터에 WLAN에 연결할 수 있는 권한을 부여합니다. 컴퓨터 계정을 원격 액세스 보안 그룹 **원격액세스정책** **–** **무선사용자**에 추가합니다.
  
    **중요:** 이 단계는 임의의 순서로 수행할 수 있습니다. 또한 WLAN 하드웨어를 배포하여 사용하기 전이라면 언제든지 수행할 수 있습니다. 사용자는 적어도 한 번 *로그오프했다가다시로그온해야* 각 절차에서 지정한 그룹 구성원 자격을 얻을 수 있습니다. 사용자 로그온 토큰은 일정 시간이 지나면 시간 제한에 도달하여 그룹 구성원 자격을 갱신하는데 이 프로세스는 최대 1주일까지 걸릴 수 있습니다.  
    사용자가 초기 인증서를 받으려면 유선 네트워크에 *연결되어있어야* 합니다. 인증서 갱신은 WLAN으로 받습니다.
  
##### 컴퓨터에 무선 설정 사용
  
클라이언트 컴퓨터의 무선 네트워킹 설정(예: 802.11 및 802.1X 설정)구성은 Active Directory 그룹 정책으로 자동화합니다. 컴퓨터를 보안 그룹에 추가하여 어떤 컴퓨터가 무선 네트워크 설정을 받는지 제어합니다. 보안 그룹으로 그룹 정책 개체(GPO)를 필터링하여 그룹 구성원만 정책 설정을 받도록 합니다. 무선 네트워크를 사용해야 하는 작업 환경에 새 컴퓨터가 추가될 때마다 이 작업을 수행해야 합니다.
  
###### 요약 정보
  
-   **보안요구사항**: Domain Admins 구성원 자격 또는 Active Directory의 무선 네트워크 정책 - Computer 보안 그룹에 사용자를 추가하는 권한
  
-   **빈도**: 네트워크에 모바일 컴퓨터가 추가될 때
  
-   **기술요구사항**: Active Directory 사용자 및 컴퓨터 MMC 스냅인
  
###### 작업 정보
  
무선 네트워크 정책을 구성하고 정책이 작동하면 정책 적용을 제어하는 보안 그룹에 컴퓨터를 추가하는 작업은 간단합니다.
  
**무선네트워킹그룹정책보안그룹에컴퓨터를추가하려면다음을수행합니다.**
  
1.  Active Directory 사용자 및 컴퓨터 MMC 스냅인에서 적용할 무선 네트워크 정책에 해당하는 무선 네트워크 정책 - 컴퓨터 보안 그룹을 찾습니다. 그룹의 구성원 수정 권한이 있는 사용자로 로그온해야 합니다.
  
2.  선택한 보안 그룹에 컴퓨터를 추가합니다.
  
    **참고:** 컴퓨터를 다시 시작해야 새 그룹 구성원 자격을 반영하고 무선 정책을 적용할 수 있습니다. 무선 정책을 처음 적용할 때 컴퓨터가 *유선네트워크에연결되어있어야* 무선 설정을 받을 수 있습니다. 이후의 변경 내용은 WLAN으로 적용할 수 있습니다.
  
##### 원격 액세스 정책 그룹에 컴퓨터 및 사용자 추가
  
원격 액세스 정책 보안 그룹에 컴퓨터와 사용자를 추가하면 해당 컴퓨터와 사용자는 WLAN에 액세스할 수 있습니다. IAS는 원격 액세스 정책 내에서 이 그룹 구성원 자격을 액세스 허가 조건으로 사용합니다. WLAN에 대한 권한을 부여하려면 원격 액세스 정책 그룹에 컴퓨터와 사용자를 추가해야 합니다.
  
###### 요약 정보
  
-   **보안요구사항**: Domain Admins 구성원 자격 또는 Active Directory의 원격 액세스 정책-무선 사용자 및 원격 액세스 정책-무선 컴퓨터 보안 그룹의 구성원을 수정할 수 있는 권한
  
-   **빈도**: 사용자에게 WLAN에 대한 액세스 권한이 부여될 때
  
-   **기술요구사항**: Active Directory 사용자 및 컴퓨터 MMC 스냅인
  
###### 작업 정보
  
원격 액세스 정책 보안 그룹이 만들어지면 WLAN을 제어하는 보안 그룹에 다른 컴퓨터 및 사용자를 추가하는 작업은 간단합니다.
  
**원격액세스정책보안그룹에사용자를추가하려면다음을수행합니다.**
  
1.  Domain Admins 구성원 또는 원격 액세스 정책 - 무선 사용자 보안 그룹의 구성원 자격 수정 권한이 있는 사용자로 관리 컴퓨터에 로그온합니다.
  
2.  Active Directory 사용자 및 컴퓨터 MMC 스냅인에서 무선 LAN 액세스를 제어하는 원격 액세스 정책에 해당하는 원격 액세스 정책 – 무선 사용자 보안 그룹을 찾습니다.
  
3.  선택한 보안 그룹에 사용자를 추가합니다.
  
    **참고:** 사용자는 로그오프한 다음 다시 로그온해야 새 그룹 구성원 자격을 얻어 WLAN에 액세스할 수 있습니다.
  
**원격액세스정책보안그룹에컴퓨터를추가하려면다음을수행합니다.**
  
1.  Domain Admins 구성원 또는 원격 액세스 정책 - 무선 컴퓨터 보안 그룹의 구성원 자격 수정 권한이 있는 사용자로 관리 컴퓨터에 로그온합니다.
  
2.  Active Directory 사용자 및 컴퓨터 MMC 스냅인에서 무선 LAN 액세스를 제어하는 원격 액세스 정책에 해당하는 원격 액세스 정책 – 무선 컴퓨터 보안 그룹을 찾습니다.
  
3.  선택한 보안 그룹에 컴퓨터를 추가합니다.
  
    **참고:** 컴퓨터를 다시 시작해야 새 그룹 구성원 자격을 얻어 WLAN에 액세스할 수 있습니다.
  
#### 서비스 모니터링 및 제어
  
서비스 모니터링을 통해 운영 부서의 직원은 IT 서비스의 상태를 실시간으로 모니터링할 수 있습니다.
  
이 절에서는 사용자가 MOM(Microsoft Operations Manager) 운영 설명서의 지침에 따라 MOM을 배포했다고 간주하고 설명합니다. 그러나 MOM이 반드시 필요한 것은 아니며 한 예로 제시될 뿐입니다. MOM 운영 설명서에 대한 자세한 내용은 이 장 끝에 나오는 "추가 정보" 절을 참조하십시오.
  
##### 모니터링 경고 범주화
  
모니터링 시스템은 가장 중요한 사항만 운영 부서 직원에게 경고해야 합니다. 모든 경미한 오류가 확대되어 사고 경고가 생성되면 운영 직원은 긴급한 문제점과 긴급하지는 않으나 장기적인 조사가 필요한 문제점을 모두 전달 받기 때문에 혼란이 발생합니다.
  
###### 요약 정보
  
-   **보안요구사항**: 없음
  
-   **빈도**: 설치 작업
  
-   **기술요구사항**: Operational alert 콘솔(예: MOM)
  
###### 작업 정보
  
이 문서에 사용된 경고 범주는 다음과 같습니다. 이 중 상위 세 가지만(서비스 사용할 수 없음, 보안 침해 및 중대 오류) 즉시 주의를 주기 위해 운영자 콘솔에 경고를 생성합니다. 오류와 경고는 긴급한 것으로 간주하지 않으며 RADIUS 및 WLAN 운영 지원 담당자에게 보고하여 해결해야 합니다. 이 이벤트 범주는 MOM이 사용하는 기본값이고 이어지는 나머지 작업 설명에서 이를 참조합니다.
  
**표** **12.8** **경고범주**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >경고 범주</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">서비스 사용할 수 없음</td>
<td style="border:1px solid black;">응용 프로그램이나 구성 요소가 100% 사용 불가능한 경우</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">보안 침해</td>
<td style="border:1px solid black;">응용 프로그램이 해킹을 당하거나 손상된 경우</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">중대 오류</td>
<td style="border:1px solid black;">응용 프로그램에 즉각적인 관리 조치(반드시 즉시 수행할 필요는 없음)가 필요한 중대 오류가 발생한 경우 응용 프로그램이나 구성 요소가 저하된 성능으로 실행되지만 대부분의 중요한 작업을 계속해서 수행할 수 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Error</td>
<td style="border:1px solid black;">응용 프로그램에 일시적인 문제가 발생했지만 즉각적인 관리 조치나 해결 방법이 필요하지 않은 경우 응용 프로그램이나 구성 요소가 적절한 수준의 성능으로 실행되며 모든 중요한 작업을 계속해서 수행할 수 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">경고</td>
<td style="border:1px solid black;">응용 프로그램이 즉각적인 관리 조치나 해결 방법이 필요하지 않은 경고 메시지를 생성한 경우 응용 프로그램이나 구성 요소가 적절한 수준의 성능으로 실행되며 모든 중요한 작업을 계속해서 수행할 수 있습니다. 하지만 문제가 지속될 경우 상황이 오류, 심각한 오류 또는 서비스 사용할 수 없음으로 발전할 수 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">정보</td>
<td style="border:1px solid black;">응용 프로그램에서 정보 이벤트를 생성한 경우 응용 프로그램이나 구성 요소가 적절한 수준의 성능으로 실행되며 모든 중요한 작업과 중요하지 않은 작업을 계속해서 수행할 수 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">성공</td>
<td style="border:1px solid black;">응용 프로그램이 성공 이벤트를 생성한 경우 응용 프로그램이나 구성 요소가 적절한 수준의 성능으로 실행되며 모든 중요한 작업과 중요하지 않은 작업을 계속해서 수행할 수 있습니다.</td>
</tr>
</tbody>
</table>
  
##### IAS 용량 제한 모니터링
  
잠재적인 성능 제한을 발견하는 것은 서비스를 최적의 수준으로 유지 관리하는 데 반드시 필요합니다. 하위 시스템이 작동 성능의 한계에 이르면 성능이 급격하게 저하됩니다(보통 비선형으로). 따라서 성능 경향을 모니터링하여 추후 문제가 될만한 경향을 초기에 발견하여 해결하는 것이 중요합니다.
  
###### 요약 정보
  
-   **보안요구사항**: 모니터링 솔루션에 지정된 필요한 권한
  
-   **빈도**: 설치 작업
  
-   **기술요구사항**:
  
    -   성능 모니터
  
    -   성능 카운터 통합자(예: MOM)
  
    -   Operational alert 콘솔(예: MOM)
  
    -   성능 계획 도구
  
###### 작업 정보
  
다음의 성능 카운터는 IAS의 용량 제한을 식별하는 데 가장 유용합니다. 프로세서와 디스크는 IAS가 가장 많이 사용하는 두 리소스이므로 네트워크나 메모리보다 초기 단계에서 문제를 보일 가능성이 큽니다.
  
**표** **12.9 IAS** **성능문제를파악하기위해모니터링해야할항목**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >성능 개체</th>
<th style="border:1px solid black;" >성능 카운터</th>
<th style="border:1px solid black;" >Instance</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">프로세서</td>
<td style="border:1px solid black;">% Processor Time</td>
<td style="border:1px solid black;">_Total</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">실제 디스크</td>
<td style="border:1px solid black;">% Disk Time</td>
<td style="border:1px solid black;">_Total</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">실제 디스크</td>
<td style="border:1px solid black;">Avg. Disk Read Queue Length</td>
<td style="border:1px solid black;">_Total</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">실제 디스크</td>
<td style="border:1px solid black;">Avg. Disk Write Queue Length</td>
<td style="border:1px solid black;">D: (IAS–DATA)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">네트워크 인터페이스</td>
<td style="border:1px solid black;">Bytes Total/sec</td>
<td style="border:1px solid black;">네트워크 어댑터</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">메모리</td>
<td style="border:1px solid black;">% Committed Bytes in use</td>
<td style="border:1px solid black;">---</td>
</tr>
</tbody>
</table>
  
성능 제한 및 관련 성능 카운터에 관한 정보는 이 장 뒷부분에 있는 "추가 정보" 절을 참조하십시오.
  
지원 인프라에 대한 용량 표시기 또한 반드시 모니터링해야 합니다. 주요 항목은 다음과 같습니다.
  
-   **IAS와** **Active Directory의통신**. IAS는 인증 및 일부 권한 부여 서비스를 위해 포괄적으로 Active Directory를 사용합니다.
  
-   **무선** **AP와같은** **RADIUS** **클라이언트**. 무선 AP 같은 RADIUS 클라이언트는 EAP(확장할 수 있는 인증 프로토콜) 및 RADIUS 프로토콜을 사용하여 클라이언트 및 IAS와 모두 통신합니다.
  
-   **Active Directory에대한클라이언트관련통신**. 무선 LAN 클라이언트는 그룹 정책 및 원시 도메인 인증을 위해 Active Directory 도메인 컨트롤러를 사용합니다.
  
#### 저장소 관리
  
저장소 관리에서는 데이터 복원과 기록 보관을 위해 온사이트 및 오프사이트 데이터 저장소를 취급합니다. 저장소 관리 팀은 백업 및 아카이브 데이터에 대해 물리적인 보안이 이루어지도록 해야 합니다. 저장소 관리는 프로덕션 IT 환경의 데이터 및 데이터 리소스를 정의, 추적 및 유지 관리하는 작업입니다.
  
##### IAS 구성 내보내기 구성
  
이 작업은 재해 발생 후 시스템 복원을 돕도록 IAS 구성 상태 일부를 내보내는 야간 작업을 예약합니다. 전체 IAS 구성 상태에는 보안에 중요한 정보인 RADIUS 클라이언트 구성이 포함됩니다. 따라서 구성 상태 중에서 RADIUS 클라이언트 부분을 내보내기 위한 지침은 따로 자세히 설명됩니다. 각 IAS 서버에 대해 전체 생산 서비스의 전체 복원을 수행하려면 두 가지 유형의 백업이 모두 필요합니다.
  
IAS 서버의 전체 백업에는 운영 체제 구성과 IAS 서버가 의존하는 기타 상태 정보가 포함됩니다. 이 작업은 서버가 다시 설치되고, 옵션 IAS 구성 요소가 다시 설치되고, 구성 상태가 복원될 수 있도록 하기 위해 개발되었습니다. 이 작업을 통해 더 이상 알려진 구성 상태에 있지 않아 신뢰할 수 없거나 보안이 침해된 서버의 서비스를 보다 쉽게 복원합니다.
  
###### 요약 정보
  
-   **보안요구사항**: 로컬 Administrators 보안 그룹의 구성원 자격
  
-   **빈도**: 설치 작업
  
-   **기술요구사항**:
  
    -   MSS 스크립트
  
    -   Windows 작업 스케줄러 서비스
  
    -   SchTasks.exe
  
###### 작업 정보
  
이 작업은 예약된 작업을 구성하여 IAS 서버의 야간 구성 상태 백업을 수행합니다. IAS 백업 시 현재 회사 서버의 백업 시스템이 작동되고 있다고 가정됩니다. 즉, 이 절차에 따라 백업을 수행하면 출력이 백업 파일로 보내지며 회사의 백업 시스템은 이 파일을 백업합니다. 주요 백업 시스템은 네트워크 백업, SAN(저장소 영역 네트워크) 백업 또는 로컬 장치 백업일 수 있습니다. 또한 이 솔루션은 서버 백업 시스템이 야간에 실행되어 IAS 서버 디스크를 백업한다는 점을 전제로 합니다.
  
**IAS** **구성백업을구성하려면다음을수행합니다.**
  
1.  다음 명령을 실행하여 백업 작업이 야간에 실행되도록 예약합니다. 이 명령은 작업이 오전 2시에 실행되도록 설정합니다.
  
    SCHTASKS /Create /RU system /SC Daily /TN "IAS Backup" /TR \\"C:\\MSSScripts\\IASExport.bat\\" /ST 02:00
  
    (이 명령은 두 줄 이상으로 표시됩니다. 한 줄로 입력하십시오.)
  
    **참고:** 스크립트 이름 C:\\MSSScripts\\IASExport.bat 어느 한 쪽의 슬래시 및 인용 부호는 경로 이름이나 파일 이름에 공백이 있는 경우에만 필요합니다. 백슬래시는 스크립트 이름을 둘러싼 인용 부호를 "제거하여" schtasks 작업 명령줄 일부로 저장하는 데 사용합니다. 경로 이름에 공백이 없으면 생략할 수 있습니다.
  
2.  D:\\IASConfig 디렉터리의 내용을 이동식 미디어에 매일 밤 백업하도록 서버 백업 시스템을 구성합니다. 가능한 경우 IAS 구성 텍스트 파일이 IASExport.bat 파일에서 만들어진 날짜와 시간이 24시간보다 오래되지 않았는지 확인하도록 전제 조건 스크립트를 설정합니다. 파일에 24시간이 지난 날짜 및 시간 스탬프가 있으면 이전 백업을 실패했거나 아직 백업이 실행 중임을 의미합니다.
  
    **참고**: 제공된 IASExport.bat 스크립트를 이 작업의 시작 지점으로 사용할 수 있습니다. IASExport.bat 스크립트의 논리를 수정하여 스크립트에 사용되는 **netsh** 도구의 오류 이벤트가 운영 담당자가 탐지할 수 있는 이벤트나 알림을 생성하도록 할 수 있습니다.
  
D:\\IASConfig 디렉터리에 대해 Windows 파일 감사를 사용하고 감사 데이터에서 실패한 액세스와 같은 일반적이지 않은 작업을 검토하도록 서버 보안 감사자에게 지시하는 것을 고려해야 합니다. D:\\IASConfig 디렉터리의 정보는 공격자에게 네트워크 액세스 제어를 손상시키는 방법을 알려줄 수 있습니다.
  
##### RADIUS 클라이언트 구성 내보내기
  
IAS 서버에서 RADIUS 클라이언트 구성을 내보내 서버에서 심각한 장애가 발생했을 때 이 정보를 복원할 수 있도록 해야 합니다. RADIUS 클라이언트 정보는 각 서버와 무선 AP 간에 사용되는 RADIUS 암호를 포함하므로 보안에 민감한 사항입니다. 따라서 RADIUS 클라이언트 데이터는 이동식 미디어로 내보내고 이 미디어를 안전한 장소에 보관해야 합니다. 내보낸 RADIUS 클라이언트 구성 데이터는 일반적으로 각 IAS 서버에 고유합니다.
  
IAS 서버 구성을 완전히 복원하려면 이 작업에서 만드는 RADIUS 클라이언트 구성 데이터 및 이전 절차에서 IASExport.bat 스크립트로 만든 IAS 시스템 구성 데이터를 복원해야 합니다.
  
###### 요약 정보
  
-   **보안요구사항**: IAS Admins 보안 그룹의 구성원 자격
  
-   **빈도**: 설치 작업
  
-   **기술요구사항**:
  
    -   MSS 스크립트
  
    -   플로피 디스크 또는 기타 쓰기 가능한 이동식 미디어
  
###### 작업 정보
  
RADIUS 클라이언트 정보는 **netsh** 명령을 사용하여 내보냅니다. 이 솔루션에는 RADIUS 클라이언트 정보를 플로피 디스크 또는 기타 이동식 미디어로 내보내는 배치 파일이 들어 있습니다.
  
**RADIUS** **클라이언트구성을내보내려면다음을수행합니다.**
  
1.  RADIUS 클라이언트 데이터를 저장할 IAS 서버에 로그온하여 명령줄에서 다음 명령을 실행합니다.
  
    C:\\MSSScripts\\IASClientExport.bat
  
2.  발견한 오류 또는 경고를 조사하여 수정합니다. 수정한 후에는 다시 스크립트를 실행합니다.
  
3.  백업 미디어를 적절히 저장합니다. 이 백업 데이터는 회사 WLAN에 액세스하는 데 사용하는 암호가 들어 있으므로 매우 중요합니다. 이 데이터는 IAS 서버를 다룰 때와 같은 보안 수준을 적용하여 다루어야 합니다. IAS 서버와는 물리적으로 다른 장소에 백업 데이터를 저장하는 것이 좋습니다. 그러면 사이트의 모든 컴퓨터 장비가 손상되거나 액세스할 수 없는 경우가 발생할 때 IAS 서버를 복구할 수 있습니다.
  
##### IAS 데이터 디렉터리의 백업 구성
  
이 작업의 목적은 서버에서 심각한 장애가 발생한 후 IAS 구성 상태 및 RADIUS 로그 데이터의 전체 시스템 복구를 위해 어떤 IAS 서버 디렉터리를 백업해야 하는지 설명하는 것입니다. IAS 서버의 전체 백업에는 운영 체제 구성과 IAS 서버가 의존하는 기타 시스템 상태 정보가 포함됩니다.
  
###### 요약 정보
  
-   **보안요구사항**: 로컬 Backup Operators 보안 그룹의 구성원 자격
  
-   **빈도**: 설치 작업
  
-   **기술요구사항**:
  
    -   Windows 백업 또는 엔터프라이즈 백업 시스템
  
    -   Windows 작업 스케줄러 서비스
  
    -   SchTasks.exe
  
###### 작업 정보
  
이 작업은 IAS 구성 상태 및 로그 파일 데이터를 완전히 복원할 수 있도록 백업해야 하는 디렉터리를 소개합니다. 이 작업은 회사의 서버 백업 시스템이 현재 적절히 작동되고 있다는 가정 하에 진행됩니다. 시스템은 네트워크 백업, SAN 백업 또는 로컬 장치 백업일 수 있습니다. 또한 이 솔루션은 회사 서버의 백업 시스템이 IAS 서버의 디스크 백업을 위해 IAS 구성 상태 백업 이후 야간에(오전 2시) 실행된다고 가정합니다.
  
**IAS** **데이터디렉터리백업을구성하려면다음을수행합니다.**
  
1.  IAS 구성 상태 백업이 제대로 계획되고 성공적으로 실행되고 있는지 확인합니다. IAS 구성 상태에 대해 예약된 백업 작업이 수행되면 IAS 구성 상태가 하드 디스크의 파일로 출력됩니다.
  
2.  메모장을 사용하여 D:\\IASLogs 디렉터리에 backuptest.txt 파일을 만듭니다. 이 파일 내에 **Used for backup and restoration verification purposes**를 입력합니다. 파일을 저장하고 메모장을 닫습니다. 이 파일은 나중에 복원 확인 절차에서 사용됩니다.
  
    다음 디렉터리의 전체, 증분 또는 차등 백업을 수행하도록 회사 서버의 백업 시스템을 구성합니다.
  
    -   D:\\IASConfig
  
    -   D:\\IASLogs
  
3.  회사 서버 백업 시스템의 로그 파일을 확인하여 오류나 경고가 발생하지 않았는지 살펴봅니다. 오류나 경고가 발견되면 IAS 구성 내보내기 스크립트를 수동으로 실행하고 두 디렉터리의 전체 백업을 다시 수행하는 것을 고려하십시오.
  
4.  백업 미디어를 적절히 저장합니다. 이 백업 데이터에는 회사 WLAN에 액세스할 수 있는 서버 소프트웨어 구성이 들어 있으므로 중요합니다. IAS 서버를 다룰 때와 같은 수준의 보안으로 다루어야 합니다. IAS 서버와는 물리적으로 다른 장소에 백업 데이터를 저장하는 것이 좋습니다. 그러면 사이트의 모든 컴퓨터 장비가 손상되거나 액세스할 수 없는 경우가 발생할 때 IAS 서버를 복구할 수 있습니다.
  
##### IAS 백업 테스트
  
이 작업의 목적은 테스트 복원을 수행하여 백업 프로세스 및 기술이 올바르게 동작하는지 테스트하는 것입니다. 예비 서버 하드웨어에 있는 백업의 전체 복원을 수행해보면 백업 절차가 제대로 작동될 것임을 확신할 수 있습니다. 그러나 이 절차에 따르면 예비 서버 하드웨어에 액세스할 수 없는 고객은 약간의 위험을 감수하고 실제 프로덕션 하드웨어에서 복원 절차를 테스트해야 합니다. 실제 프로덕션 서버 서버에서 복원 절차를 테스트할 경우 부분 복원 시 서버가 사용 불가능 상태가 될 수 있습니다.
  
백업 테스트를 수행하면 서버에 심각한 장애가 발생할 경우 복원 단계를 잘 알고 있어 진행에 방해가 되는 절차상 또는 기술적 오류를 피할 수 있습니다.
  
IAS 서버 복원 데이터는 다음으로 구성되어 있습니다.
  
-   **IAS** **구성상태내보내기데이터**. D:\\IASConfig 디렉터리에 있습니다. 테이프에서 복원하는 경우 이 정보는 IAS 서버로 구성을 다시 가져오는 데 사용되고 이 장의 "IAS 구성 내보내기 구성" 단계에 따라 생성됩니다.
  
-   **RADIUS** **클라이언트내보내기데이터**. "*&lt;서버이름&gt;*의 RADIUS 클라이언트"라는 레이블이 부착된 플로피 디스크 또는 기타 쓰기 가능한 이동식 미디에서 있습니다. 이 정보는 IAS 서버로 RADIUS 클라이언트 구성을 복원하는 데 사용되고 이 장의 "RADIUS 클라이언트 구성 내보내기" 단계에 따라 생성됩니다.
  
-   **RADIUS** **요청로그데이터**. D:\\IASLogs 디렉터리에 있습니다. 테이프에서 복원할 경우 이 정보에는 IAS 보안 감사자가 사용하는 이력 데이터가 포함됩니다. 이 데이터는 IAS 서비스가 RADIUS 정보를 디스크에 기록할 때 지속적으로 만들어집니다.
  
테스트 복원을 수행하기 전에 IAS 구성 내보내기 데이터 및 RADIUS 클라이언트 내보내기 데이터를 수동으로 내보내야 합니다. 이런 식으로 예약하지 않고 서버 데이터를 특수 테이프에 백업하고 테스트 복원 시 문제가 발생할 때에만 사용하도록 이 백업을 보관합니다. 이렇게 하면 정상적인 백업 중에 불량 테이프 문제 및 알지 못하는 상태로 발생하는 기타 오류로 인해 실제 프로덕션 서버의 부분 복원이 진행되지 않게 되는 위험을 줄일 수 있습니다.
  
###### 요약 정보
  
-   **보안요구사항**: 테스트 컴퓨터의 로컬 관리자 또는 Backup Operator
  
-   **빈도**:
  
    -   IAS 서버 운영을 시작하기 전에
  
    -   매월
  
    -   백업 기술 또는 프로세스가 변경될 때마다 다시 테스트합니다.
  
-   **기술요구사항**:
  
    -   Windows 백업 또는 엔터프라이즈 백업 시스템
  
    -   MSS 스크립트
  
###### 작업 정보
  
이 작업은 IAS 데이터의 복원 및 확인을 자세히 설명합니다. 세 가지 형식의 데이터가 모두 복원되며 복원을 검증하기 위해 특수한 절차가 사용됩니다. 성공적으로 완료된 최근 최근의 전체 백업(앞에서 야간에 수행한 백업)을 사용해야 합니다. 또한 테스트를 시작하기 전에 마지막 백업 이후 대상 서버에 관리 작업(예: 구성 변경)을 수행하지 않도록 해야 합니다.
  
새로 설치된 Windows Server 2003에 복원하려고 하면 8장 "무선 LAN 보안을 위한 RADIUS 인프라 구현"의 서버 빌드 사전 작업 단계를 완수하여 서버 하드웨어 및 소프트웨어가 IAS에 맞게 구성되도록 해야 합니다.
  
**참고**: 복원한 WLAN 원격 액세스 정책 내에 새로 설치한 RAS 및 IAS 서버 인증 인증서를 다시 선택해야 하는 경우가 있습니다.
  
**IAS** **백업을테스트하려면다음을수행합니다.**
  
**참고**: 이 절차의 첫 번째 단계는 옵션으로 테스트 랩 환경에서 프로덕션 서버가 아닌 하드웨어에 사용됩니다. 불안정하고 보안이 침해된 상태에서 서버를 복구할 수 있으면 많은 도움이 될 것입니다.
  
1.  복구가 불가능한 하드웨어 또는 소프트웨어 손상 또는 보안 침해(예: 바이러스 감염)가 발생한 서버를 복원하려면 8장 "RADIUS 인프라 구현"의 지침대로 Windows Server 2003을 다시 설치합니다. 반드시 배포 미디어의 MSS 스크립트를 서버의 C:\\MSSScripts 디렉터리에 복사하십시오.
  
2.  D:\\IASLogs 디렉터리로 이동하여 파일 backuptest.txt를 찾습니다. 파일이 없으면 다음 단계를 진행합니다. backuptest.txt 파일을 찾으면 삭제합니다. backuptest.txt 파일은 "IAS 데이터 디렉터리의 백업 구성" 절차를 수행할 때 만들어집니다. backuptest.txt는 IAS RADIUS 요청 로그와 함께 백업되어 사용자가 RADIUS 로그를 복원하지 않고도 백업에서 데이터를 복원할 수 있는지를 확인할 수 있습니다. 원할 경우 대신 D:\\IASLogs에서 실제 RADIUS 요청 로그 데이터를 복원할 수도 있습니다. 하지만 로그 파일 데이터를 덮어쓰면 복원이 실패할 경우 데이터 손실이 발생할 수 있습니다.
  
3.  3. 인터넷 인증 서비스 MMC 스냅인을 열고 **인터넷인증서비스(로컬)** 개체의 속성을 선택한 후 **일반** 탭을 확인합니다. **서버설명** 필드에 "**(복원테스트)**"를 추가합니다. **확인**을 클릭하여 IAS 속성 대화 상자를 닫습니다. 서버 설명을 변경하면 이전에 백업된 IAS 구성 설정이 복원되었는지 확인할 수 있습니다. 이전 IAS 구성 설정을 복원하면 **서버설명** 문자열은 이전 값이 덮어쓰고 "**(복원테스트)"** 텍스트는 사라집니다.
  
4.  **인터넷인증서비스** MMC 스냅인을 사용하여 **RADIUS** **클라이언트** 폴더를 마우스 오른쪽 단추로 클릭하고 **새** **RADIUS** **클라이언트**를 선택합니다. **이름**으로 **복원테스트**를 입력하고 **클라이언트주소(IP** **또는** **DNS)**로 **127.0.0.1**을 입력합니다. 이 RADIUS 클라이언트에 대한 **공유암호** 및 **공유암호확인** 필드에 암호를 입력한 후 **마침**을 클릭합니다. 복원이 성공하면 RADIUS 클라이언트 정보를 덮어쓰고 새로운 RADIUS는 사라집니다.
  
5.  지난 밤의 예약된 백업 작업 등의 테스트하려는 백업 미디어를 찾아 서버 하드 디스크에 다음 데이터를 복원하는 데 사용합니다.
  
    -   D:\\IASConfig\\\*.\*
  
    -   D:\\IASLogs\\BACKUPTEST.TXT
  
6.  명령 프롬프트에서 다음 명령을 실행하여 이전에 텍스트 파일로 저장했던 IAS 구성을 IAS 데이터베이스로 다시 복원합니다. 스크립트 실행 중 나타나는 모든 오류나 경고를 검토하십시오.
  
    C:\\MSSScripts\\IASImport.bat
  
    **참고:** 다음 단계에서 "&lt;*서버이름*&gt;의 RADIUS 클라이언트"라는 레이블이 부착된 플로피 디스크 또는 기타 쓰기 가능한 이동식 미디어 사용을 다룹니다. 데이터 손실을 방지하기 위해 서버에 맞는 정확한 디스크를 사용합니다.
  
7.  이 서버의 RADIUS 클라이언트 구성 플로피 디스크나 기타 이동식 쓰기 가능 미디어를 찾은 후 서버 드라이브에 넣습니다. 명령 프롬프트에서 다음을 실행합니다. 스크립트 실행 중 나타나는 모든 오류나 경고를 검토하십시오.
  
    C:\\MSSScripts\\IASClientImport.bat
  
8.  **인터넷인증서비스** MMC 스냅인을 닫았다가 다시 연 후 **인터넷인증서비스(로컬)** 개체의 속성을 선택하고 **일반** 탭을 열어 **서버설명** 필드에 더 이상 **(복원테스트)** 텍스트가 나타나지 않는지 확인합니다. **확인**을 클릭하여 **IAS** **속성** 대화 상자를 닫습니다.
  
9.  RADIUS 클라이언트폴더를 선택하고 **복원테스트** RADIUS 클라이언트가 오른쪽 창의 클라이언트 목록에 더 이상 나타나지 않는지 확인합니다.
  
10. **인터넷인증서비스** MMC 스냅인 내의 다른 모든 구성이 복원 테스트 이전의 설정을 나타내야 합니다.
  
11. D:\\IASLogs 디렉터리를 찾아 이동한 후 backuptest.txt 파일이 있는지 확인합니다. 이 절차의 복원 단계가 실제 프로덕션 서버에서 수행되었으면 IAS 보안 감사자는 로그 파일이 손상되지 않았으며 적어도 백업 시점의 상태로 복원되었는지 확인합니다.
  
12. 백업 미디어와 플로피 디스크를 안전한 저장소에 다시 보관해야 합니다.
  
#### 보안 관리
  
보안 관리는 안전한 컴퓨팅 환경을 유지 관리하는 업무를 담당합니다. 보안은 회사 IT 인프라의 중요한 부분입니다. 보안 기반이 취약한 정보 시스템에는 보안상 빈틈이 생기게 됩니다.
  
##### IAS RADIUS 요청 로그에 액세스
  
IAS는 옵션으로 무선 AP RADIUS 요청으로부터 발생한 다양한 이벤트를 서버 하드 디스크에 있는 RADIUS 요청 로그에 기록합니다. RADIUS 로그는 시스템의 잠재적인 공격 및 회사 네트워크에 대한 무단 액세스를 식별하는 등 다양한 용도로 사용할 수 있습니다. 이 작업에서 RADIUS 요청 로그 검사 방법을 설명하지만 RADIUS 요청 로그 분석에 관한 상세한 논의는 이 설명서의 범위를 벗어납니다.
  
RADIUS 요청 로그는 IAS 형식이나 데이터베이스 가져오기 형식으로 저장되므로 다양한 방법으로 분석할 수 있습니다. 본 솔루션은 데이터베이스 가져오기 형식의 로그 파일을 선택했는데 이 형식이 쉼표로 구분된 텍스트 파일 입력을 받는 응용 프로그램에 가져오는 것이 비교적 쉽기 때문입니다. IAS RADIUS 요청 로그를 검토하는 방법은 다음과 같습니다.
  
-   **IASPARSE** **유틸리티로로그파일직접찾기**. 이 도구는 Windows Server 2003 지원 도구에서 구할 수 있는데 성능상의 이유로 보통 IAS 서버에 설치하여 실행합니다. 따라서 원격 데스크톱 연결(또는 기타 원격 실행 방법) 세션이 필요합니다. 기본적으로 이 솔루션은 이러한 방식의 로그 파일 보기를 지원하도록 구성되어 있지 않습니다.
  
-   **원격관리컴퓨터에서** **Microsoft Access 2002으로로그파일가져오기**. 이 방법을 사용하여 관리자는 즉석 쿼리를 위해 또는 체계적인 보고 및 보관 계획의 일부로 Microsoft Access 테이블에 로그를 가져올 수 있습니다. 이 로그 파일 보기 방법은 간단함과 유연성이 잘 조화를 이루기 때문에 이 솔루션에서 사용하는 옵션입니다. 기업 고객 역시 Microsoft SQL Server™ 2000 기반 로깅을 사용하는 다음 옵션을 고려해야 합니다.
  
-   데이터가 각 IAS 서버의 MSDE-2000으로부터 복제되는 대상인 **중앙** **SQL Server 2000** **클러스터를통해로그정보액세스**. 각 IAS 서버는 MSDE의 로컬 인스턴스에 로깅합니다. 이 시나리오에 대한 설정은 비교적 복잡하지만 Microsoft는 이 프로세스에 도움이 되는 백서와 코드를 제작했습니다. 이러한 방식으로 SQL 로깅을 설정하는 방법에 관한 정보는 Microsoft 파트너 업체에 문의하거나 파트너 업체 또는 Microsoft Consulting Services 전문가에게 연결해줄 수 있는 Microsoft 고객 담당자에게 문의하십시오.
  
###### 요약 정보
  
-   **보안요구사항**: IAS Security Auditors 보안 그룹의 구성원 자격
  
-   **빈도**: 보안 요구 사항에 따라 매일 또는 매주
  
-   **기술요구사항**:
  
    -   IASPARSE
  
    -   Microsoft Access
  
    -   Microsoft Excel
  
###### 작업 정보
  
RADIUS 요청 로그는 이 솔루션의 각 서버에서 생성되어 전용 디스크 볼륨에 저장됩니다. 이러한 로그 파일에 액세스하는 단계에는 각 IAS 서버에 대한 네트워크 연결 설정, 로그 파일 검토 및 더 이상 필요하지 않은 로그 파일 삭제 등이 포함됩니다. 이 솔루션의 IAS 서버는 매달 새 RADIUS 요청 로그 파일을 만들도록 구성되어 있지만 각자의 필요에 따라 간격을 변경할 수 있습니다.
  
Access에서 만든 테이블은 각 필드에 포함된 데이터 형식에 따라 서식이 지정됩니다. 이 예제는 새 테이블을 만드는 방법을 보여 주지만 기존 테이블에 로그를 가져올 수도 있습니다.
  
**RADIUS** **요청로그파일을** **Microsoft Access로가져오려면다음을수행합니다.**
  
1.  관리자 워크스테이션에 Active Directory IAS Security Auditors 보안 그룹의 구성원으로 로그온하고 로그를 검토할 IAS 서버에 드라이브 연결을 매핑합니다. 명령 프롬프트에 다음 명령을 입력하여 HQ-IAS-01을 IAS 서버 이름으로 대체합니다.
  
    NET USE X: \\\\HQ-IAS-01\\IASLogs
  
2.  보려는 달에 해당하는 로그 파일을 찾습니다. 로그 파일 이름은 파일이 작성된 날짜를 표시하는 형식을 사용합니다. 로그 파일을 복사하고 복사본 이름을 .txt 파일 이름 확장명으로 바꿉니다.
  
3.  C:\\MSSScripts\\IASAccessPrep.txt 텍스트 파일의 두 줄 전부를 복사된 로그 파일 첫 부분에 추가합니다. 첫째 줄에는 로그에 들어 있는 각 필드의 속성 이름이 포함되며, Access에서는 이 속성 이름을 사용하여 해당 테이블에 필드 이름을 만듭니다. 테이블의 속성 이름을 사용하면 로그 항목을 보다 쉽게 해석할 수 있습니다. Access는 둘째 줄을 사용하여 테이블의 각 열에 대한 데이터 형식을 설정합니다. 로그 파일을 가져온 후에는 Access 테이블에서 해당 항목을 삭제해야 합니다.
  
4.  Access 2002에서 **새데이터베이스**를 클릭합니다. **새데이터베이스파일**에서 파일 이름을 지정한 후 **데이터를입력하여테이블만들기**를 클릭합니다. **파일**을 클릭하고 **외부데이터가져오기**를 클릭한 후 **가져오기**를 클릭합니다.
  
5.  **가져오기**, **파일형식**, **텍스트파일**을 차례로 클릭한 후 IAS 로그 파일을 찾아 선택한 후 **가져오기**를 클릭합니다. **텍스트가져오기마법사**에서 **고급**을 클릭합니다.
  
6.  **가져오기설정**:을 클릭합니다.
  
7.  **파일형식**에서 **구분기호로분리됨**을 클릭합니다.
  
8.  **필드구분기호**에서 **,**(쉼표)를 선택합니다.
  
9.  **텍스트묶음기호**에서 "(따옴표)를 선택합니다.
  
10. **날짜,** **시간,** **숫자**에서 **4자리연도체계**와 **0** **선행날짜**를 선택하고 올바른 **날짜순서**(예: MDY), **날짜구분기호**(예: **/** 또는 **슬래시**), **시간구분기호**(예: **:** 또는 콜론) 및 **소수점기호**(예: . 또는 마침표)를 입력합니다.
  
11. **텍스트가져오기마법사** 대화 상자에서 **다음**을 클릭하여 **첫행에필드이름포함**을 선택하고 **다음**을 클릭합니다. **새테이블**을 선택한 후 **다음**을 클릭합니다.
  
12. **필드옵션**을 기본 설정대로 두고 **다음**을 클릭합니다. **Access에서기본키추가**를 클릭한 후 **다음**을 클릭합니다. **테이블로가져오기**에서 새 테이블의 이름을 입력합니다. **마침**을 클릭합니다.
  
13. **파일명:데이터베이스** 대화 상자에서 데이터베이스의 이름을 입력하고 **열기**를 클릭하여 테이블을 확인합니다.
  
##### IAS RADIUS 인증 이벤트 로그 항목 검토
  
보안 감사자는 이 작업을 주기적으로 사용하여 무선 네트워크에 대한 허가되지 않은 액세스 시도를 확인할 수 있습니다. 내부 보안 정책에 따라 이벤트 로그에서 RADIUS 인증 이벤트를 주기적으로 검토하여 인증 시도나 도난당한 인증서 자격 증명을 사용하는 경우를 탐지할 수 있습니다. 또한 수상한 이벤트가 기록되면 MOM 등의 관리 도구를 사용할 수 있습니다.
  
이 작업은 옵션으로 앞서 설명한 IAS RADIUS 로깅의 대안으로 볼 수 있습니다. 이 작업은 IAS Admins 그룹 또는 서버 로컬 Administrators 그룹의 구성원 자격이 필요합니다.
  
###### 요약 정보
  
-   **보안요구사항**: IAS Admins 그룹 또는 기본 제공 로컬 Administrators 그룹의 구성원 자격
  
-   **빈도**: 보안 요구 사항에 따라 매일 또는 매주
  
-   **기술요구사항**:
  
    -   이벤트 뷰어
  
    -   옵션으로 EventCombMT 또는 Windows Server 2003 Resource Kit의 EventFilter
  
###### 작업 정보
  
이 작업은 IAS Security Auditors 및 IAS 시스템 관리자가 동일한 사람인 IT 환경에 적합합니다. 반면 RADIUS 로그는 서버의 로컬 관리자가 아닌 운영자가 볼 수 있습니다. 이 솔루션은 Security Auditors에 로컬 Administrator 권한을 부여하지 않습니다. 따라서 이 작업을 수행하기 전에 Active Directory의 IAS Admins 보안 그룹에 해당 보안 감사자를 추가해야 합니다.
  
**이벤트뷰어를사용하여이벤트로그에서실패한인증시도를확인하려면다음을수행합니다.**
  
1.  IAS 서버 중 하나에 IAS Admins 보안 그룹의 구성원으로 로그온합니다.
  
2.  **시작**, **모든프로그램**, **관리도구**를 차례로 클릭하여 이벤트 뷰어를 엽니다.
  
3.  **시스템이벤트로그**를 클릭합니다.
  
4.  **보기** 메뉴에서 **필터**를 클릭합니다.
  
5.  **이벤트원본**으로 **IAS**를 선택하고 **Event ID**로 **2**를 선택합니다.
  
6.  잦은 인증 실패 또는 기타 수상한 항목을 조사합니다.
  
    **참고:** 또한 Eventquery 도구(Windows XP 및 Windows Server 2003) 및 Windows Server 2003 Resource Kit의 EventFilter 또는 EventCombMT 도구를 사용하여 IAS 이벤트를 볼 수 있습니다.
  
##### IAS RADIUS 로그 파일 보관 및 삭제
  
IAS에는 로깅 디스크가 꽉 찰 경우 가장 오래된 IAS RADIUS 로그 파일을 삭제하는 기능이 있습니다. 이 자동화 기능을 사용하지 않을 경우 수동으로 IAS RADIUS 요청 로그 파일을 보관하고 삭제하여 IAS 디스크 공간이 부족하지 않도록 해야 합니다. 디스크 공간이 부족하면 IAS가 무선 AP의 인증 및 계정 요청에 대한 서비스를 중단합니다. 또한 스크립트나 자동화된 SQL Server 2000 복제 전략을 사용하여 로그 보관을 자동화할 수 있습니다(이 장 앞부분의 "IAS RADIUS 요청 로그 액세스" 작업에서 설명).
  
**참고:** 이 솔루션은 IAS 기능을 사용하여 디스크가 꽉 찰 경우 자동으로 가장 오래된 로그 파일을 삭제합니다.
  
###### 요약 정보
  
-   **보안요구사항**: IAS Security Auditors Active Directory 보안 그룹의 구성원 자격
  
-   **빈도**: 매월
  
-   **기술요구사항**: 기본 Windows 명령
  
###### 작업 정보
  
RADIUS 인증 및 계정 요청 로그의 다양한 보관 및 삭제 방법이 있습니다. 예를 들어 서버 기반 백업 스크립트는 로그 파일의 백업이 성공적으로 완료되었음을 전자 메일을 통해 IAS 보안 감사자에게 알릴 수 있습니다. 그런 후 보안 감사자는 IAS 서버에 연결한 후 가장 오래된 로그 파일을 삭제합니다. 또는 IAS 보안 감사자가 RADIUS 로그 파일을 관리 컴퓨터에 연결된 테이프 또는 CD–RW 장치에 백업한 다음 IAS 서버에 연결하여 더 이상 사용하지 않는 가장 오래된 로그 파일을 삭제합니다.
  
이 솔루션에서 IAS는 매달 새 로그 파일을 만들도록 구성됩니다.
  
여러 상황에 대비해 네트워크 액세스 정보를 다시 구성할 수 있을 만큼 충분한 데이터를 온라인화할 수 있는 전략을 만들어야 합니다. 예를 들어 3개의 개별 로그 파일에 3달 분량의 데이터를 온라인 상태로 유지하는 경우 보안 이벤트를 추적하기 위해 네트워크 액세스 정보를 다시 생성하는 데 최신 로그 파일 2개만 필요합니다. 따라서 가장 오래된 로그 파일 3개를 보관 및 삭제하고 마지막 2개 파일을 남겨 두어야 합니다.
  
RADIUS 요청 로그 및 기타 IAS 데이터 백업에 대한 정보는 이 장에 자세히 설명되어 있는 "IAS 데이터 디렉터리 백업 구성" 작업에서 찾을 수 있습니다. 이 작업은 관리 스테이션에서 RADIUS 로그를 보관 및 삭제하기 위한 지침을 제공합니다.
  
**RADIUS** **요청로그파일을보관및삭제하려면다음을수행합니다.**
  
1.  IAS Security Auditors 보안 그룹의 구성원으로 관리 워크스테이션에 로그온합니다.
  
2.  다음 명령을 사용하여 드라이브를 로그 파일이 보관된 IAS 서버에 매핑하여 HQ-IAS-01을 IAS 서버 이름으로 바꿉니다.
  
    NET USE X: \\\\HQ-IAS-01\\IASLogs
  
3.  IAS 서버에서 보관 및 삭제할 가장 오래된 로그 파일을 식별합니다. NTBACKUP, **copy** 명령 또는 기타 유틸리티를 사용하여 온라인 공유 위치의 선택한 로그 파일을 보조 미디어에 보관합니다.
  
4.  온라인 공유 위치에서 불필요한 로그 파일을 삭제합니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 지원 사분면 작업
  
지원 사분면의 SMF에 필요한 서비스 수준을 유지하기 위한 사후 대처 및 사전 대비 작업이 모두 있습니다. 사후 대처 기능은 발생한 사건과 문제에 신속하게 대응하고 이를 해결하는 조직의 능력에 의존합니다. 그러나 서비스 수준이 어떠한 영향도 받기 전에 사전 기능을 통해 문제를 식별하고 해결하여 서비스가 중단되지 않도록 하는 것이 더 좋습니다. 이 기능은 서비스 솔루션을 사전에 정의한 임계값과 대조하여 철저하게 모니터링하고 서비스 중단 사태가 발생하기 전에 운영 직원에게 잠재적인 문제에 대처할 충분한 시간을 줍니다. 지원 사분면은 운영 사분면에 기술된 서비스 제어 및 모니터링 SMF와 밀접한 관련이 있습니다. 서비스 제어 및 모니터링은 운영 및 지원 담당자가 문제를 탐지하는 데 필요한 필수 정보를 제공합니다. 이 절에서 다루는 절차는 가장 흔히 발생하는 문제를 해결하고 문제로부터 복구하기 위한 것입니다.
  
이 절에서는 다음 SMF와 관련된 정보를 제공합니다.
  
-   사건 관리
  
나머지 SMF에 속하는 작업이 없습니다.
  
-   문제 관리
  
-   서비스 데스크
  
    **참고:** 각 작업 설명에는 보안 요구 사항, 빈도 및 기술 요구 사항이라는 요약 정보가 들어 있습니다.
  
#### 사건 관리
  
사건 관리는 IT 서비스를 사용하거나 구현하는 과정에서 고객이나 IT 파트너가 보고한 결함과 장애를 관리하고 제어하는 프로세스입니다. 사건 관리의 주요 목표는 가능한 한 빨리 정상적인 서비스 작업을 복원하고 비즈니스 운영에 미치는 부정적인 영향을 최소화하여 최상의 서비스 품질과 가용성을 유지하는 데 있습니다. 여기에서는 정상적인 서비스 작동을 SLA(Service Level Agreement)에서 명시하는 서비스 작동으로 정의합니다.
  
**참고:** 일반적인 Windows XP 무선 클라이언트 문제 해결은 이 장 뒷부분의 "추가 정보"의 참고 자료를 참조하십시오.
  
##### 클라이언트 네트워크 연결 폴더 상태 확인
  
네트워크 연결 폴더 및 Windows XP 알림 아이콘은 WLAN 인증 상태에 대한 정보를 제공합니다. 이 작업을 사용하여 최종 사용자나 지원 부서 직원은 클라이언트 컴퓨터의 무선 연결 상태를 확인할 수 있습니다. 여러 사용자 인증서 중 하나를 선택하는 것 등 인증을 위해 사용자가 추가 정보를 제공해야 하는 경우 내용을 설명하는 텍스트 풍선이 나타납니다. 이 작업은 문제 해결 중에 사용됩니다.
  
###### 요약 정보
  
-   **보안요구사항**: WLAN 설정을 수정하기 위해 로컬 Administrators 보안 그룹의 구성원이어야 함
  
-   **빈도**: 사용자 문제를 해결해야 하는 경우
  
-   **기술요구사항**: Windows XP Professional
  
###### 작업 정보
  
네트워크 연결 폴더 내에서 무선 네트워크 어댑터에 해당하는 연결 이름 아래에 표시되는 텍스트는 인증 상태를 설명합니다.
  
연결 상태를 확인할 때 **일반** 탭에서 신호 강도를, **지원** 탭에서 IP 주소 구성을 확인할 수 있습니다. 무선 어댑터에 APIPA(Automatic Private IP Addressing) 주소(169.254.0.0/16)가 있거나 어댑터의 TCP/IP(Transmission Control Protocol/Internet Protocol) 속성에 대체 IP 주소가 구성되어 있으면 인증은 실패하고 Windows XP 무선 클라이언트는 계속 무선 액세스 지점과 연결 상태를 유지합니다. 인증이 실패하고 연결 상태가 계속 유지되어 있는 경우 Windows는 무선 어댑터 사용을 활성화하고 TCP/IP는 정상적인 구성 프로세스를 수행합니다. 이 예에서는 클라이언트가 WLAN 인증을 받지 못했기 때문에 DHCP(Dynamic Host Configuration Protocol) 서버를 찾을 수 없습니다. 따라서 TCP/IP는 자동으로 APIPA 또는 대체 주소를 구성합니다. 이 경우 IAS 서버에서 WLAN 인증이 실패한 이유를 검토하거나 클라이언트 컴퓨터를 추적하여 확인하는 것이 좋습니다.
  
**네트워크연결폴더의상태를확인하려면다음을수행합니다.**
  
-   **시작**, **실행**을 클릭하고 **ncpa.cpl**을 입력한 다음 **확인**을 클릭합니다.
  
##### 클라이언트 컴퓨터에서 추적 활성화 및 비활성화
  
Windows는 지원 센터 담당자 및 개발자가 소프트웨어 구성 요소 관련 문제를 해결할 수 있도록 자세한 추적 정보를 지원합니다. 추적은 이벤트 로그보다 자세한 수준의 정보를 제공하며 이 정보를 텍스트 로그 파일에 저장합니다.
  
EAP 인증 프로세스에 대한 자세한 정보를 보려면 EAPOL(EAP over LAN) 및 RASTLS(원격 액세스 서비스 - 전송 계층 보안) 구성 요소 추적 기능을 사용해야 합니다.
  
###### 요약 정보
  
-   **보안요구사항**: 로컬 Administrators 보안 그룹의 구성원 자격
  
-   **빈도**: 클라이언트 WLAN 문제 해결 시 필요한 경우
  
-   **기술요구사항**:
  
    -   Windows XP Professional
  
    -   Notepad.exe
  
###### 작업 정보
  
다음 명령을 실행한 후 다시 인증 과정을 시도하고 %SystemRoot%\\Tracing 폴더의 Eapol.log 및 Rastls.log 파일을 봅니다.
  
**클라이언트컴퓨터에서추적을사용하려면다음을수행합니다.**
  
-   다음 명령을 실행합니다.
  
    -   **netsh ras set tracing eapol enabled**
  
    -   **netsh ras set tracing rastls enabled**
  
**클라이언트컴퓨터에서추적을해제하려면다음을수행합니다.**
  
-   다음 명령을 실행합니다.
  
    -   **netsh ras set tracing eapol disabled**
  
    -   **netsh ras set tracing rastls disabled**
  
    **참고:** 추적은 시스템 리소스를 소모하고 크기가 급속도로 늘어나는 로그 파일을 만듭니다. 문제 해결을 완료하면 추적 기능을 해제해야 합니다.
  
##### 클라이언트 컴퓨터에서 도메인 이름 문자열 확인
  
다음 작업은 클라이언트 컴퓨터에 인증서 도메인 이름 확인을 사용하는 경우 유용합니다. 이 설정은 사용자에게 혼란을 야기할 수 있는 WLAN 대화 상자를 만들 수 있기 때문에 이 솔루션에서 사용하지 않습니다. Windows XP Professional SP1에서는 기본적으로 이 옵션이 비활성화되어 있습니다.
  
클라이언트 컴퓨터는 EAP - TLS 상호 인증 중에 인증서 해지 확인을 수행할 수 없습니다. WLAN에 액세스가 허용되기 전에는 CRL(인증서 해지 목록) 위치를 알 수 없기 때문입니다. 하지만 Windows 클라이언트는 IAS 서버가 제공하는 인증서에서 서버 이름 전체 또는 일부를 확인할 수 있습니다. 이 기능은 무선 클라이언트 GPO의 무선 네트워크 정책 설정에서 구성합니다. (이 설정은 클라이언트 컴퓨터의 무선 네트워크 어댑터 속성의 무선 네트워크 속성과 유사한 사용자 인터페이스를 갖습니다.)
  
무선 클라이언트가 서버 인증서를 확인할 때 **서버이름이다음으로끝날때만연결** 필드에 IAS 서버 도메인에 대해 잘못된 값을 입력하면 인증은 실패합니다. **다음서버에연결** 옵션을 활성화하는 경우 클라이언트 인증 문제를 해결할 때 이 작업을 수행해야 합니다.
  
###### 요약 정보
  
-   **보안요구사항**: 로컬 Administrators 보안 그룹의 구성원 자격
  
-   **빈도**: 설정 시 또는 사용자 WLAN 문제 해결 시
  
-   **기술요구사항**: Windows XP Professional
  
###### 작업 정보
  
이 작업으로 클라이언트의 WLAN 네트워크 어댑터 네트워크 연결의**속성** 대화 상자 또는 무선 네트워크 정책 GPO의 도메인 이름 문자열이 정확한지 확인할 수 있습니다.
  
**클라이언트컴퓨터에서도메인이름문자열을확인하려면다음을수행합니다.**
  
1.  **시작**, **실행**을 클릭하고 **ncpa.cpl**을 입력한 다음 **확인**을 클릭합니다.
  
2.  무선 네트워크 연결의 속성을 확인합니다.
  
3.  **무선네트워크** 탭에서 기본 설정 네트워크 중에서 대상 네트워크의 네트워크 SSID(서비스 집합 ID)를 선택하고 해당 속성을 확인합니다.
  
4.  **인증** 탭에서 속성을 확인하고 **서버이름이다음으로끝날때만연결** 문자열이 IAS 서버의 도메인 이름과 같은지 확인합니다.
  
##### 이벤트 로그에서 IAS 인증 이벤트 확인
  
클라이언트 인증 성공 및 실패 이벤트가 IAS 서버의 시스템 이벤트 로그에 기록되어 문제 해결에 사용할 수 있습니다. 기본적으로 인터넷 인증 서비스 MMC 스냅인의 IAS 서버 속성인 **서비스** 탭에서 모든 유형의 IAS 이벤트(거부, 무시 및 성공적인 인증 이벤트)에 대해 이벤트 로깅이 활성화되어 있습니다.
  
이 작업을 사용하여 IAS 관리자는 IAS 서버 이벤트 로그에서 인증 이벤트를 확인하여 컴퓨터 및 사용자 인증 문제 해결 시 지원 부서 직원에게 도움을 줄 수 있습니다.
  
IT 지원 부서 직원이 IAS 시스템 이벤트 로그의 무선 클라이언트 인증 정보에 액세스해야 하는 경우 여러 옵션이 있습니다.
  
-   IAS Admins 보안 그룹의 구성원이므로 IAS 시스템 이벤트 로그 메시지에 액세스할 수 있는 IAS 관리자가 지원할 수 있도록 등록합니다. 이 작업은 이 옵션을 사용합니다.
  
-   MOM 같은 기업 이벤트 로그 관리 시스템을 사용하여 지원 부서 직원이 액세스할 수 있는 위치로 로그를 내보냅니다.
  
-   지원 부서 직원에게 IASLogs 공유 위치와 원본 NTFS D:\\IASLogs 디렉터리에 대한 읽기 권한을 부여합니다. 이 장 "IAS RADIUS 요청 로그 액세스" 작업에 설명된 IASPARSE 같은 도구를 사용하여 로그 파일을 검색하는 방법을 설명합니다. 대부분의 고객은 이 옵션이 최소의 인프라만 필요로 하고 과도한 보안 위험에 노출되지 않기 때문에 이 옵션을 사용하려 합니다.
  
관리자가 아닌 사용자에게 IAS 시스템 이벤트 로그에 대한 액세스 권한을 부여하는 것은 보안 위협이 될 수 있습니다. 특히 IAS와 도메인 컨트롤러 서버 역할을 동시에 하는 서버에 문제가 됩니다.
  
###### 요약 정보
  
-   **보안요구사항**: 로컬 IAS Administrators 보안 그룹 또는 시스템 이벤트 로그에 대해 읽기/저장 액세스 권한이 부여된 그룹의 구성원 자격
  
-   **빈도**: 클라이언트 인증 문제를 해결하는 경우
  
-   **기술요구사항**: 이벤트 뷰어 MMC 스냅인 또는 Windows Server 2003 Resource Kit의 EventCombMT
  
###### 작업 정보
  
시스템 이벤트 로그의 인증 시도를 확인하면 IAS가 거부한 인증 시도의 문제를 해결하는 데 도움이 됩니다. 원격 액세스 정책을 여러 개 구성한 경우 시스템 이벤트 로그를 사용하여 연결 시도를 허가했거나 거부한 원격 액세스 정책의 이름을 확인할 수 있습니다. 이벤트 설명에서 정책-이름을 확인합니다. 또한 인증 이벤트(원본: IAS, 허가의 경우 이벤트 ID 1, 거부의 경우 이벤트 ID 2)는 Windows Server 2003 도움말 및 지원에 나와 있는 이유 코드를 해당 설명과 함께 보여 줍니다.
  
IAS 이벤트 로깅을 활성화하고 시스템 이벤트 로그에 있는 IAS 인증 이벤트 텍스트를 읽으면 실패한 IAS 인증 문제를 가장 쉽게 해결할 수 있습니다.
  
**인증이벤트에대한시스템이벤트로그를확인하려면다음을수행합니다.**
  
1.  **시작**, **실행**을 클릭하고 **Eventvwr**을 입력한 다음 **확인**을 클릭합니다.
  
2.  **시스템이벤트로그**를 선택합니다.
  
3.  **보기** 메뉴에서 **필터**를 선택하고 **이벤트원본**으로 **IAS**를 선택한 후 **확인**을 클릭합니다.
  
##### IAS 서버에서 추적 활성화 및 비활성화
  
Windows는 지원 센터 담당자 및 개발자가 소프트웨어 구성 요소 관련 문제를 해결할 수 있도록 자세한 추적 정보를 지원합니다. 추적은 이벤트 로그보다 자세한 수준의 정보를 제공하며 이 정보를 텍스트 로그 파일에 저장합니다.
  
Microsoft Windows Server 2003에는 특정 구성 요소에 대한 복잡한 문제를 해결하는 데 사용할 수 있는 포괄적인 추적 기능이 있습니다. **netsh** 명령을 사용하여 Windows 2003 Server 구성 요소가 추적 정보를 파일에 기록하도록 할 수 있습니다.
  
###### 요약 정보
  
-   **보안요구사항**: IAS 서버에 있는 로컬 Administrators 보안 그룹의 구성원 자격
  
-   **빈도**: 클라이언트 WLAN 연결 문제를 해결할 때 필요한 경우
  
-   **기술요구사항**:
  
    -   Netsh
  
    -   메모장
  
    -   Regedit
  
###### 작업 정보
  
**netsh** 명령을 사용하여 특정 구성 요소 또는 모든 구성 요소의 추적을 사용 및 해제할 수 있습니다. EAP-TLS 기반 802.1X 인증 문제 추적을 사용하는 데 가장 유용한 구성 요소는 다음과 같습니다.
  
-   **IASSAM(*%systemroot%*\\tracing** **폴더의** **Iassam.log** **파일** **)**. 이 로그는 사용자 이름 암호 해독, DC 연결 및 자격 증명 확인 등의 기능을 설명하기 때문에 가장 많이 사용되는 IAS 문제 추적 파일입니다. 이 파일은 IAS 추적 파일의 "심장"이며 일반적으로 인증 관련 문제를 디버깅하는 데 필요합니다.
  
-   **RASTLS(%*systemroot%*\\tracing** **폴더의** **Rastls.log** **파일)**. 모든 EAP 및 PEAP 관련 인증의 경우 이 로그에 대부분의 핵심 디버깅 정보가 들어 있습니다. 하지만 이 로그 파일은 읽기가 어렵습니다. Microsoft는 이 정보를 보다 쉽게 해독할 수 있는 정보를 작성 중입니다.
  
IAS에 대한 다음 추적 정보는 일반적으로 EAP&\#150;TLS를 사용하는 802.1X 인증 문제 해결에 필요하지 않지만 다른 작업 문제를 해결할 때는 유용할 수도 있습니다.
  
-   **IASRAD(*%systemroot%*\\tracing** **폴더의** **Iasrad.log** **파일)**. 이 로그는 모든 RADIUS 프로토콜 관련 작업을 설명합니다. 서버가 수신 대기하는 포트 등을 설명합니다. 이 로그도 IAS 서버의 디버깅 문제에는 잘 사용되지 않습니다.
  
-   **IASSDO(*%systemroot%*\\tracing** **폴더의** **Iassdo.log** **파일)**. IASSDO 로그는 UI에서 서버 구성 및 사전을 저장하는 MDB 파일까지 트랜잭션을 추적합니다. 이것은 모든 서비스 또는 UI 관련 문제를 디버깅하는 데 사용되는 로그입니다.
  
**IAS** **서버에서추적을사용하려면다음을수행합니다.**
  
-   필요한 추적 정보에 해당하는 **netsh** 명령을 실행합니다. 802.1X를 사용한 EAP-TLS 인증 문제를 해결할 때는 IASSAM 및 RASTLS 로그를 권장합니다.
  
    해당 **netsh** 명령은 다음과 같습니다.
  
    -   **netsh ras set tracing iassam enabled**
  
    -   **netsh ras set tracing rastls enabled**
  
    -   **netsh ras set tracing iasrad enabled**
  
    -   **netsh ras set tracing iassdo enabled**
  
**IAS** **서버에서추적을해제하려면다음을수행합니다.**
  
-   해제할 추적 정보에 해당하는 **netsh** 명령을 실행합니다.
  
    해당 **netsh** 명령은 다음과 같습니다.
  
    -   **netsh ras set tracing iassam disabled**
  
    -   **netsh ras set tracing rastls disabled**
  
    -   **netsh ras set tracing iasrad disabled**
  
    -   **netsh ras set tracing iassdo disabled**
  
        **참고**: 추적은 시스템 리소스를 소모하므로 네트워크 문제를 확인하는 용도로만 사용하는 것이 좋습니다. 추적 내용이 포착되거나 문제가 확인되는 즉시 추적을 비활성화하십시오.
  
IASSAM 추적 로그의 기본값이 1MB뿐이기 때문에 부하가 클 경우 로그 파일의 중요한 정보를 덮어쓸 수 있습니다. 다음 단계를 수행하여 IASSAM 추적 로그를 15MB로 설정합니다. 로그 크기가 15 MB에 도달하면 파일 이름을 IASSAM.old로 바꾸로 새 IASSAM.log를 만듭니다. 이 절차로 서버에 30MB의 데이터를 보관할 수 있습니다.
  
**IASSAM** **추적로그파일을** **15MB로설정하려면다음을수행합니다.**
  
1.  Regedit.exe를 실행합니다.
  
2.  다음 레지스트리 키로 이동합니다. **\\HKLM\\Software\\Microsoft\\Tracing\\**.
  
3.  **IASSAM** 키를 값은 **MaxFileSize**, 형식은 **REG\_DWORD** 및 데이터 값은 **0xF00000**으로 업데이트합니다.
  
##### IAS 서버에서 보안 채널 로깅 활성화
  
보안 채널은 SSL(Secure Sockets Layer) 및 TLS(Transport Level Security) 같은 여러 인터넷 보안 프로토콜을 지원하는 SSP(보안 지원 공급자)입니다.
  
###### 요약 정보
  
-   **보안요구사항**: 로컬 Administrators 보안 그룹의 구성원 자격
  
-   **빈도**: IAS 서버의 클라이언트 연결 문제 해결 시 필요한 경우
  
-   **기술요구사항**:
  
    -   Regedit
  
    -   메모장
  
###### 작업 정보
  
클라이언트 인증 확인 실패에 대한 기록은 보안 채널 이벤트이며 IAS 서버에서 기본적으로 활성화되어 있지 않습니다.
  
**IAS** **서버에** **SChannel** **로깅을사용하려면다음을수행합니다.**
  
다음 레지스트리 키 값을 **1**(**REG\_DWORD** 형식, 데이터 **0x00000001**)에서 **3**(**REG\_DWORD** 형식, 데이터 **0x00000003**)으로 변경하여 추가 보안 채널 이벤트를 활성화합니다.
  
**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\SecurityProviders**  
**\\SCHANNEL\\EventLogging**
  
**경고**: 레지스트리를 잘못 편집하면 시스템에 심각한 손상을 줄 수 있습니다. 레지스트리를 변경하기 전에 컴퓨터의 중요 데이터를 백업해야 합니다.
  
문제 해결 중에는 SChannel 로깅을 사용하지 않도록 합니다. SChannel 로깅이 시스템 리소스를 소모하고 이벤트 로그에 불필요한 항목을 많이 기록하기 때문입니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 최적화 사분면 작업
  
최적화 사분면에는 서비스 수준을 유지 관리하거나 개선하면서 비용을 관리하는 SMF가 포함됩니다. 최적화 사분면에는 작동 중지나 사고 감시, 비용 구조 검사, 직원 평가, 가용성, 성능 분석, 용량 예측이 포함됩니다.
  
이 절에서는 다음 SMF와 관련된 정보를 제공합니다.
  
-   성능 관리
  
나머지 SMF에 속하는 작업이 없습니다.
  
-   서비스 수준 관리
  
-   재무 관리
  
-   가용성 관리
  
-   IT 서비스 연속성 관리
  
-   인력 관리
  
    **참고:** 각 작업 설명에는 보안 요구 사항, 빈도 및 기술 요구 사항이라는 요약 정보가 들어 있습니다.
  
#### 성능 관리
  
성능 관리는 SLA에 명시된 성능 수준 내에서 사용자의 요구 사항을 만족시키는 서비스 솔루션 성능을 계획, 조정 및 제어하는 프로세스입니다. 성능 관리를 위해서는 서비스 솔루션의 사용 시나리오, 패턴, 로드가 가장 많을 때의 특징은 물론 명시된 성능 요구 사항에 대한 정보가 필요합니다.
  
##### IAS 서버의 최대 로드 확인
  
이 절은 IAS 서버의 최대 로드에 대한 정보를 제공합니다.
  
크기가 적당하고 구성에 문제가 없는 IAS RADIUS 서버에서는 성능이 별로 문제가 되지 않습니다. IAS RADIUS 서버는 많은 사용자들이 동시에 로그온하는 아침 시간, 주요 네트워크가 중단된 직후 또는 RADIUS 서버 장애가 발생하여 무선 AP가 백업 서버로 장애 조치될 때 등, 로드가 최대에 도달할 때 가장 심각한 스트레스 상태가 됩니다.
  
###### 요약 정보
  
-   **보안요구사항**: 없음
  
-   **빈도**: 설치 작업
  
-   **기술요구사항**: 없음
  
###### 작업 정보
  
Microsoft의 내부 테스트 결과에 따르면 IAS는 일반 하드웨어에서 최대 로드 수준에 도달할 수 있으며 이는 대부분의 고객 요구를 충족하는 것입니다. IAS가 서비스할 수 있는 인증 횟수는 초당 인증 수를 통해 예측할 수 있습니다. IAS는 Active Directory가 별도의 Intel Pentium 4 2GHz 서버에 있는, Windows Server 2003을 실행하는 Intel Pentium 4 2GHz 서버에서 다음과 같은 성능 수치를 보였습니다.
  
**표** **12.10 IAS** **서버의로드확인**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >인증 유형</th>
<th style="border:1px solid black;" >초당 인증 수</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">새 EAP&amp;#150;TLS 인증</td>
<td style="border:1px solid black;">36</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">오프로드 카드 지원이 포함된 새 EAP&amp;#150;TLS 인증</td>
<td style="border:1px solid black;">50</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">빠른 다시 연결을 사용한 인증</td>
<td style="border:1px solid black;">166</td>
</tr>
</tbody>
</table>
  
**참고**: 이 정보는 정확성을 보장할 수 없으므로 성능을 계획할 때 참조용으로만 사용하고 성능 비교 시에는 사용하지 마십시오.
  
IAS는 여러 가지 RADIUS 요청 정보가 들어 있는 디스크 기반 텍스트 로그를 생성하도록 구성할 수 있습니다. RADIUS 로깅이 RADIUS 서버에 가하는 오버헤드 때문에 RADIUS 로그를 저장하기 위한 고성능 디스크를 계획하는 것이 좋습니다. 디스크 하위 시스템 속도가 느리면 무선 AP에 대한 IAS RADIUS 응답을 지연시켜 프로토콜 시간 제한에 도달하거나 무선 AP가 불필요하게 보조 RADIUS 서버로 장애 조치되는 일이 발생합니다. RADIUS 로깅 옵션에 관한 자세한 정보는 5장 "무선 LAN 보안을 위한 RADIUS 인프라 디자인"을 참조하십시오.
  
앞의 "IAS 서버에서 추적 활성화 및 비활성화"에서 설명한 Windows 2003 Server 소프트웨어 추적 기능도 IAS 서버에 추가로 부하를 가합©©니다. 하지만 네트워크 액세스 문제 해결에 필요한 경우가 있습니다. IAS 서버는 프로덕션 부하를 계속 감당하면서 제한된 시간 동안 추적을 사용하면서 실행할 수 있는 용량을 갖추어야 합니다.
  
##### IAS 서버에 대한 저장소 및 백업 요구 사항 확인
  
이 절은 IAS 저장 매개 변수에 대한 성능 세부 정보를 제공합니다. 이러한 정보는 성능 계획자가 온라인 디스크 및 오프라인 백업 저장소에 대한 추후 저장소 요구 사항을 계산하는 데 도움이 됩니다.
  
###### 요약 정보
  
-   **보안요구사항**: 없음
  
-   **빈도**: 필요한 경우
  
-   **기술요구사항**: 없음
  
###### 작업 정보
  
IAS RADIUS 로그 파일은 저장 계획을 필요로 하는 IAS 서버의 단일 구성 요소입니다. 이 솔루션을 위한 RADIUS 요청 로그는 매월 새 로그를 만들도록 구성되어 있으며 이 솔루션 개발 중에 테스트된 하드웨어에는 18GB의 로그 파일 전용 디스크 볼륨이 있습니다.
  
작업 환경의 IAS 서버의 예상 부하를 계산한 다음 로깅 옵션을 선택하고 랩 환경에서 테스트를 수행하여 프로덕션 무선 클라이언트가 IAS의 인증을 받은 후 로그 데이터를 생성하는 과정을 시뮬레이트해야 합니다. 다음과 같은 논리에 따라 로드를 예상할 수 있습니다.
  
무선 AP당 평균 사용자 수는 25(사용자 또는 컴퓨터)입니다. 각 사용자 또는 컴퓨터는 보안 요구 사항에 따라 10-60분마다 초기 인증 및 재인증을 수행합니다. 각 인증은 1KB의 디스크 로그 정보를 생성하는데 이 로그에는 인증 요청과 감사 요청이 포함되고 임시 요청은 제외됩니다. 파일 크기는 로깅 옵션에 따라 다릅니다. 25개의 클라이언트를 지원할 경우 시간당 무선 AP당 생성되는 디스크 로그 공간 크기를 계산해야 합니다. 그리고 네트워크가 스트레스 상태이거나 서버 장애 조치가 수행되는 중에 주 IAS 서버가 지원하는 무선 AP의 최대 수를 예상하십시오.
  
IAS RADIUS 요청 로그는 높은 비율로 압축됩니다. 압축은 일반적으로는 권장되지 않지만 필요할 경우 RADIUS 요청 로그 파일 폴더에 압축을 사용할 수 있습니다. 데이터 압축이 필요한 IAS 서버의 추가 부하도 예상하는 것이 좋습니다.
  
###### IAS RADIUS 로그 파일의 백업 시간
  
네트워크 백업이 이상적인 조건에서 전용 100Mbps 스위치에서 백업 서버로 수행되고 있다고 가정하면 3GB의 데이터베이스와 500MB의 시스템 상태를 약 15-20분 내에 백업할 수 있습니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 변경 사분면 작업
  
변경 사분면에는 변경 내용을 식별, 승인 및 관리 중인 IT 환경에 통합하는 데 필요한 프로세스와 절차가 들어 있습니다. 변경에는 유/무형의 자산과 특정 프로세스 및 절차와 관련된 변경 내용이 포함됩니다.
  
변경 프로세스의 목적은 역할 및 책임의 변경뿐 아니라 새 기술, 시스템, 응용 프로그램, 하드웨어, 도구 및 프로세스를 IT 환경에 신속하게 도입하고 이로 인한 서비스의 중단을 최소화하는 것입니다.
  
#### 변경 관리
  
변경 관리 SMF는 IT 환경의 변화를 관리합니다. 변경 관리 프로세스의 주요 목표는 특정 변경으로 인해 영향을 받는 모든 당사자가 앞으로 발생할 변경으로 인한 영향을 제대로 인식하도록 하는 데 있습니다. 대부분의 시스템은 서로 밀접하게 관련되어 있으므로 시스템의 한 부분에서 발생한 변경은 다른 부분에도 많은 영향을 미칩니다. 변경 관리는 변경으로 영향을 받는 모든 시스템과 프로세스를 변경 사항 배포 전에 확인하여 부정적인 영향을 줄이거나 제거합니다. 일반적으로 "대상" 환경 또는 관리되는 환경은 프로덕션 환경이지만 핵심적인 통합, 테스트 및 준비 환경도 포함되어야 합니다.
  
RADIUS 인프라 및 WLAN 보안에 대한 모든 변경은 아래에 나오는 표준 MOF 변경 관리 프로세스를 사용해야 합니다.
  
1.  **변경요청**. RFC(변경 요청) 제출을 통해 공식적으로 변경이 시작됩니다.
  
2.  **변경분류**. 변경의 긴급 정도와 인프라나 사용자에게 미치는 영향을 기준으로 변경에 우선 순위와 범주를 할당하는 것입니다. 이렇게 하면 구현 속도와 경로에 영향을 줍니다.
  
3.  **변경허가**. IT 및 비즈니스 담당자가 참여하는 CAB(변경 검토 위원회) 및 변경 관리자가 변경을 검토한 후 승인하거나 거부하는 것입니다.
  
4.  **변경개발**. 변경을 계획하고 개발하는 것으로, 그 범위가 매우 다양하며 중간의 주요 시점에 대한 검토가 포함됩니다.
  
5.  **변경릴리스**. 프로덕션 환경에 변경을 릴리스하고 배포하는 것입니다.
  
6.  **변경검토**. 변경을 통해 사전에 설정된 목표가 달성되었는지 여부를 검토하고, 변경을 그대로 유지할지 아니면 취소할지 여부를 결정하는 구현 후 프로세스입니다.
  
이 절의 절차는 사용자 환경에서 정기적으로 요구되는 주요 변경 중 몇 가지에 대한 변경 개발 절차를 간략하게 보여 줍니다. 각 변경 개발 절차에는 해당 변경을 프로덕션 환경에 배포하는 방법을 설명하는 변경 릴리스 절차가 포함되어 있습니다.
  
##### 운영 체제 업데이트 관리
  
RADIUS 및 WLAN 소프트웨어 구성 요소의 보안 업데이트 관리는 일반 Windows 패치 관리의 일부입니다. 이 주제는 Microsoft의 두 솔루션 설명서에서 다루는데 이 설명서는 Microsoft SMS(Systems Management Server) 또는 Microsoft SUS(Software Update Services)를 사용하여 Windows 운영 체제 업데이트를 설명합니다. 설명서를 구하는 방법에 대해서는 이 장 뒷부분의 "추가 정보" 절을 참조하십시오.
  
패치 관리에는 릴리스 관리 및 구성 관리 구성 요소 그리고 변경 관리 구성 요소가 포함됩니다. 하지만 세 가지 SMF 모두 앞절에서 참조한 설명서에서 다룹니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 구성 표
  
다음 표에는 이 장의 절차에서 사용하는 사이트별 및 솔루션별 구성 정보가 있습니다. 이 표는 8장 "RADIUS 인프라 구현" 및 9장 "무선 LAN 보안 인프라 구현" 계획 구성 표의 일부로 참조용으로만 여기에 소개합니다.
  
#### 사이트별 구성 매개 변수
  
**표** **12.11** **사용자정의구성항목**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >구성 항목</th>
<th style="border:1px solid black;" >설정</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Active Directory 포리스트 루트 도메인의 DNS 이름</td>
<td style="border:1px solid black;">woodgrovebank.com</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">도메인의 NetBIOS(네트워크 기본 입/출력 시스템) 이름</td>
<td style="border:1px solid black;">WOODGROVEBANK</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">주 IAS 서버의 서버 이름</td>
<td style="border:1px solid black;">HQ-IAS-01</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">보조 IAS 서버의 서버 이름</td>
<td style="border:1px solid black;">HQ-IAS-02</td>
</tr>
</tbody>
</table>
  
#### 솔루션 구성 매개 변수
  
**표** **12.12** **솔루션지정구성항목**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >구성 항목</th>
<th style="border:1px solid black;" >설정</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">[계정] IAS의 구성을 제어하는 관리 그룹의 전체 이름</td>
<td style="border:1px solid black;">IAS Admins</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[계정] IAS의 구성을 제어하는 관리 그룹의 Windows 2000 이전 버전 이름</td>
<td style="border:1px solid black;">IAS Admins</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[계정] 보안을 위해 IAS 인증 및 계정 요청 로그를 검토하는 그룹의 전체 이름</td>
<td style="border:1px solid black;">IAS Security Auditors</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[계정] 보안을 위해 IAS 인증 및 계정 요청 로그를 검토하는 그룹의 Windows 2000 이전 이름</td>
<td style="border:1px solid black;">IAS Security Auditors</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[계정] 802.1x 인증서를 필요로 하는 사용자를 포함하는 Active Directory 글로벌 그룹</td>
<td style="border:1px solid black;">클라이언트 인증 - 사용자 인증서 자동 등록</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[계정] 802.1x 인증서를 필요로 하는 컴퓨터를 포함하는 Active Directory 글로벌 그룹</td>
<td style="border:1px solid black;">클라이언트 인증 - 컴퓨터 인증서 자동 등록</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[계정] 802.1x 인증서를 필요로 하는 IAS 서버를 포함하는 Microsoft Active Directory 글로벌 그룹</td>
<td style="border:1px solid black;">RAS 및 IAS 서버 인증 인증서 자동 등록</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[계정] 802.1x 인증서를 필요로 하는 IAS 서버를 포함하는 Microsoft Active Directory 글로벌 그룹의 Windows 2000 이전 버전 이름</td>
<td style="border:1px solid black;">RAS 및 IAS 서버 인증 인증서 자동 등록</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[계정] 무선 네트워크에 액세스할 수 있는 사용자를 포함하는 Active Directory 글로벌 그룹</td>
<td style="border:1px solid black;">원격 액세스 정책 - 무선 사용자</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[계정] 무선 네트워크에 액세스할 수 있는 컴퓨터를 포함하는 Active Directory 글로벌 그룹</td>
<td style="border:1px solid black;">원격 액세스 정책 - 무선 컴퓨터</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[계정] 무선 사용자 그룹과 무선 컴퓨터 그룹을 둘 다 포함하는 Active Directory 유니버설 그룹</td>
<td style="border:1px solid black;">원격 액세스 정책 - 무선 액세스</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[계정] Active Directory 그룹 정책을 통해 무선 네트워크 속성을 구성해야 하는 컴퓨터를 포함하는 Active Directory 글로벌 그룹</td>
<td style="border:1px solid black;">무선 네트워크 정책 - 컴퓨터</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[인증서] 사용자 클라이언트 인증의 인증서를 생성하는 데 사용되는 인증서 템플릿</td>
<td style="border:1px solid black;">클라이언트 인증 - 사용자</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[인증서] 컴퓨터 클라이언트 인증의 인증서를 생성하는 데 사용되는 인증서 템플릿</td>
<td style="border:1px solid black;">클라이언트 인증 - 컴퓨터</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[인증서] IAS에서 사용할 서버 인증 인증서를 생성하는 데 사용되는 인증서 템플릿</td>
<td style="border:1px solid black;">RAS 및 IAS 서버 인증</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[스크립트] 설치 스크립트 경로</td>
<td style="border:1px solid black;">C:\MSSScripts</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[스크립트] IAS 구성 내보내기 배치 파일</td>
<td style="border:1px solid black;">IASExport.bat</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[스크립트] IAS 구성 가져오기 배치 파일</td>
<td style="border:1px solid black;">IASImport.bat</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[스크립트] IAS RADIUS 클라이언트 구성 내보내기 배치 파일</td>
<td style="border:1px solid black;">IASClientExport.bat</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[스크립트] IAS RADIUS 클라이언트 구성 가져오기 배치 파일</td>
<td style="border:1px solid black;">IASClientImport.bat</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[구성] 구성 백업 파일 경로</td>
<td style="border:1px solid black;">D:\IASConfig</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[요청 로그] IAS 인증 및 감사 요청 로그의 위치</td>
<td style="border:1px solid black;">D:\IASLogs</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[요청 로그] RADIUS 요청 로그의 공유 이름</td>
<td style="border:1px solid black;">IASLogs</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[원격 액세스 정책] 정책 이름</td>
<td style="border:1px solid black;">무선 액세스 허용</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[그룹 정책] Microsoft Active Directory 그룹 정책 개체 이름</td>
<td style="border:1px solid black;">무선 네트워크 정책</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[그룹 정책] 그룹 정책 개체의 무선 네트워크 정책</td>
<td style="border:1px solid black;">클라이언트 컴퓨터 무선 구성</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 추가 정보
  
-   MOF 프로세스 모델 및 팀 모델에 관한 자세한 정보는 www.microsoft.com/korea/technet/itsolutions/techguide/mof/default.mspx의 [Microsoft Operations Framework](http://www.microsoft.com/technet/itsolutions/techguide/mof/default.mspx)(영문) 페이지를 참조하십시오.
  
-   용량 제한 및 관련 성능 카운터에 대한 자세한 정보는 http://support.microsoft.com/default.aspx?kbid=146005에서 Microsoft 기술 자료 문서 Q146005 "[Windows NT 성능 최적화](http://support.microsoft.com/default.aspx?kbid=146005)"를 참조하십시오.
  
-   무선 네트워크 문제 해결에 관한 자세한 정보는 다음을 참조하십시오.
  
    -   http://support.microsoft.com/?scid=313242의 Microsoft 기술 자료 문서 Q313242 "[Windows XP에서 무선 네트워크 연결 문제를 해결하는 방법](http://support.microsoft.com/?kbid=313242)"
  
    -   www.microsoft.com/windowsxp/pro/techinfo/administration/networking/troubleshooting.asp의 백서 ["Troubleshooting Windows XP IEEE 802.11 Wireless Access](http://www.microsoft.com/windowsxp/pro/techinfo/administration/networking/troubleshooting.asp)"(영문)
  
-   MOM 배포에 관한 정보는 www.microsoft.com/resources/documentation/mom/2000sp1/all/opsguide/en-us/1\_in781g.mspx의 [*MOM 2000 SP1 Operations Guide*](http://www.microsoft.com/resources/documentation/mom/2000sp1/all/opsguide/en-us/1_in781g.mspx)(영문) 를 참조하십시오.
  
-   Microsoft SMS 2003 패치 관리에 관한 정보는 www.microsoft.com/korea/technet/itsolutions/techguide/msm/swdist/pmsms/2003/pmsms031.mspx의 "[Patch Management Using Microsoft Systems Management Server 2003](http://www.microsoft.com/technet/itsolutions/techguide/msm/swdist/pmsms/2003/pmsms031.mspx)"(영문)을 참조하십시오.
  
-   Microsoft SMS 2.0을 사용한 패치 관리에 관한 정보는 www.microsoft.com/korea/technet/itsolutions/techguide/msm/swdist/pmsms/20/pmsmsin.mspx의 "[Patch Management Using Microsoft Systems Management Server 2.0](http://www.microsoft.com/technet/itsolutions/techguide/msm/swdist/pmsms/20/pmsmsin.mspx)"(영문)을 참조하십시오.
  
-   Microsoft Software Update 서비스를 사용한 패치 관리에 관한 정보는 www.microsoft.com/korea/technet/itsolutions/techguide/msm/swdist/pmsus/pmsus251.mspx의 "[Patch Management Using Microsoft Software Update](http://www.microsoft.com/technet/itsolutions/techguide/msm/swdist/pmsus/pmsus251.mspx)"(영문)를 참조하십시오.
  
-   Microsoft 플랫폼의 보안 패치 관리에 관한 자세한 정보는 http://go.microsoft.com/fwlink/?LinkId=16284의 "[Improve Platform Manageability](http://go.microsoft.com/fwlink/?linkid=16284)"(영문)를 참조하십시오.
  
-   그룹 정책 관리 콘솔(GPMC)을 구하고 사용하는 법에 관한 자세한 정보는 www.microsoft.com/windowsserver2003/gpmc/default.mspx의 "[Enterprise Management with the Group Policy Management Console](http://www.microsoft.com/windowsserver2003/gpmc/default.mspx)"(영문)을 참조하십시오.
  
[](#mainsection)[페이지 위쪽](#mainsection)
