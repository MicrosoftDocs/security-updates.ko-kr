---
TOCTitle: '검사 목록 - Windows Server 2003 파일 서버'
Title: '검사 목록 - Windows Server 2003 파일 서버'
ms:assetid: '433fce5f-592c-4638-bb83-a805e400f164'
ms:contentKeyID: 20214079
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547924(v=TechNet.10)'
---

검사 목록 - Windows Server 2003 파일 서버
=========================================

##### 이 페이지에서

[](#xsltsection121121120120)

다음 검사 목록을 사용하여 Microsoft Windows Server™ 2003 운영 체제 시스템 파일 서버를 강화하는 데 필요한 모든 보안 설정과 절차가 적절히 구현되었는지 확인하십시오.

### Microsoft Active Directory 파일 서버 OU 만들기:

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th></th>
<th>단계</th>
<th>참고:</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">파일 서버 OU(조직 구성 단위)를 만듭니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">증분 파일 서버 정책을 만듭니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">GPO를 파일 서버 OU에 연결합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">해당 클라이언트 환경의 보안 템플릿을 새로 만든 GPO로 가져옵니다.</td>
<td style="border:1px solid black;">예를 들어 엔터프라이즈 환경의 경우 Enterprise Client - File Server.inf입니다.</td>
</tr>
</tbody>
</table>
  
### 파일 서버 강화 단계:

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th></th>
<th>단계</th>
<th>참고:</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Windows Server 2003을 설치하고 구성합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">필요한 서비스 팩 및/또는 업데이트를 적용합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">바이러스 예방 솔루션을 설치하고 구성합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">필요하면 MOM(Microsoft Operations Manager) 에이전트 또는 이와 유사한 모니터링 솔루션을 설치하고 구성합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">적절한 서버를 해당 파일 서버 OU로 이동합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">잘 알려진 계정에 보안을 설정합니다.</td>
<td style="border:1px solid black;">기본 제공 Administrator 계정의 이름을 변경하고 복잡한 암호를 지정합니다. Guest 계정이 해제되어 있는지 확인합니다. 기본 계정 설명을 변경합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">서비스 계정에 보안을 설정합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">IPSec(인터넷 프로토콜 보안) 필터 구현을 고려합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">증분 파일 서버 정책이 도메인 컨트롤러 간에 복제되었는지 확인합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">GPUPDATE.EXE /FORCE를 실행합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">서버를 다시 시작합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">이벤트 로그에서 오류를 확인합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547924.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">필요하면 파일 공유를 구성합니다.</td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
