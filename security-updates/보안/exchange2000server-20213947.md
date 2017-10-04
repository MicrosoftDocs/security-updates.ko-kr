---
TOCTitle: '검사 목록 - 역할을 기초로 한 Exchange 2000 Server 보안'
Title: '검사 목록 - 역할을 기초로 한 Exchange 2000 Server 보안'
ms:assetid: '9f09c527-fc4b-4bfd-88e7-fe192518fcfb'
ms:contentKeyID: 20213947
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd277368(v=TechNet.10)'
---

검사 목록 - 역할을 기초로 한 Exchange 2000 Server 보안
======================================================

##### 이 페이지에서

[](#xsltsection121121120120)[검사 목록 사용법](#xsltsection121121120120)
[](#xsltsection122121120120)[그룹 정책 설정을 사용하여 Exchange 보안 유지](#xsltsection122121120120)
[](#xsltsection124121120120)[Exchange 설치 및 업데이트](#xsltsection124121120120)
[](#xsltsection126121120120)[추가 보안 작업](#xsltsection126121120120)
[](#xsltsection128121120120)[OWA 프런트 엔드 서버의 저장소](#xsltsection128121120120)
[](#xsltsection130121120120)[SMTP 배너](#xsltsection130121120120)
[](#xsltsection132121120120)[Exchange Server 그룹 잠금](#xsltsection132121120120)

검사 목록 사용법
----------------

이 검사 목록은 "역할을 기초로 한 Exchange 2000 Server 보안" 모듈과 함께 제공됩니다. 이 검사 목록은 Exchange 2000 서버의 보안을 유지하는 데 도움을 주며 점검 목록에서 해당 모듈 내용을 빠르게 참조할 수 있습니다. 이 검사 목록은 안전한 Exchange 조직 구현에 도움이 되는 작업 단계를 제공하기 위해 작성되었습니다.

[](#mainsection)[페이지 위쪽](#mainsection)

그룹 정책 설정을 사용하여 Exchange 보안 유지
--------------------------------------------

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>선택</th>
<th>설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">테스트 환경 설정 및 그룹 정책 설정을 철저히 테스트했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">OU(조직 구성 단위) 구조를 모듈에 권장된 대로 수정했으며 서버를 적절한 OU로 이동했습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">이 가이드에 포함된 ExSecurityOps.exe에 들어 있는 보안 템플릿을 다운로드했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">도메인 컨트롤러 OU에서 새 그룹 정책 개체인 &quot;Exchange DC 정책&quot;을 만들었으며 Exchange 도메인 컨트롤러 incremental.inf를 가져왔습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">도메인 컨트롤러 간에 복제를 수행했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
<img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">모든 도메인 컨트롤러에 새 정책이 있습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">도메인 컨트롤러를 순차적으로 다시 시작했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">OWA(Outlook Web Access) 프런트 엔드 서버 OU에서 새 그룹 정책 개체 &quot;OWA 정책&quot;을 만들었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">OWA front-end Incremental.inf를 가져왔습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Exchange 백 엔드 서버 OU에서 새 그룹 정책 개체 &quot;Exchange 백 엔드 정책&quot;을 만들었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Exchange back-end Incremental.inf를 가져왔습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">도메인 컨트롤러 간에 복제를 수행했습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Exchange 서버에서 secedit /refreshpolicy machine_policy /enforce 명령을 사용하여 정책을 다운로드했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">모든 Exchange 서버를 다시 시작했습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">OWA 프런트 엔드 서버와 Exchange 백 엔드 서버에서 지정된 서비스를 비활성화했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Exchange 백 엔드 서버 파일 ACL(액세스 제어 목록)로 변경합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">NNTP(Network News Transport Protocol) 서비스가 사용되지 않을 경우 비활성화합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Exchange 환경이 작동하는 데 필요한 서비스는 다시 활성화했습니다.</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
Exchange 설치 및 업데이트  
-------------------------

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>선택</th>
<th>설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">OWA 프런트 엔드 서버의 시스템 수행자 서비스를 활성화하고 시작했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">모든 Exchange 서버의 분산 트랜잭션 코디네이터 서비스를 활성화하고 시작했습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">모든 Exchange 서버의 NNTP 서비스를 활성화하고 시작했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">모든 Exchange 서버의 Microsoft Windows 운영 체제 Installer 서비스를 활성화하고 시작했습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">OWA 프런트 엔드 서버의 WMI(Windows Management Instrumentation) 서비스를 활성화하고 시작했습니다.</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
추가 보안 작업  
--------------

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>선택</th>
<th>설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">모든 Exchange 서버에서 IIS Lockdown 도구 IISLockd.exe를 설치하고 시작했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Web Service HTTP(Hypertext Transfer Protocol)만 활성화했습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">가상 디렉터리를 제거했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">URLScan을 설치했습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">조직에 맞게 IIS Lockdown 및 URLScan 설정을 수정했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">OWA의 암호 변경 기능을 제거했습니다.</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
OWA 프런트 엔드 서버의 저장소  
-----------------------------

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>선택</th>
<th>설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">시스템 수행자 및 NTLM 보안 지원 공급자 서비스를 시작했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">사서함 저장소를 분리하고 &quot;시작 시 이 저장소 탑재 안 함&quot;을 선택했습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">공용 폴더 저장소를 분리하여 삭제했습니다.</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
SMTP 배너  
---------

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>선택</th>
<th>설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">메타베이스를 편집하여 SMTP 배너를 제거했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">SMTP(Simple Mail Transfer Protocol) 서비스를 다시 시작했습니다.</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
Exchange Server 그룹 잠금  
-------------------------

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>선택</th>
<th>설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd277368.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">EDSLock 스크립트를 실행했습니다.</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
