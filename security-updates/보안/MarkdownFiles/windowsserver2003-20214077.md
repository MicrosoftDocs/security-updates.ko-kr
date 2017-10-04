---
TOCTitle: '검사 목록 - Windows Server 2003 도메인 컨트롤러'
Title: '검사 목록 - Windows Server 2003 도메인 컨트롤러'
ms:assetid: '32a072d9-cd32-4f76-a7a7-a7d2630b4657'
ms:contentKeyID: 20214077
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547922(v=TechNet.10)'
---

검사 목록 - Windows Server 2003 도메인 컨트롤러
===============================================

##### 이 페이지에서

[](#xsltsection121121120120)

다음 검사 목록을 사용하여 Microsoft Windows Server™ 2003 운영 체제 도메인 컨트롤러를 강화하는 모든 보안 설정이 적절히 구현되었는지 확인하십시오.

### Active Directory 도메인 컨트롤러 OU 준비:

 
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
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">DCBP(도메인 컨트롤러 기준 정책)를 만듭니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">DCBP를 도메인 컨트롤러 OU에 연결합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">해당 DCBP의 우선 순위가 가장 높은지 확인합니다.</td>
<td style="border:1px solid black;">GPO는 목록 맨 위에 와야 합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">해당 클라이언트 환경의 보안 템플릿을 새로 만든 GPO로 가져옵니다.</td>
<td style="border:1px solid black;">예를 들어 엔터프라이즈 클라이언트 환경의 경우 Enterprise Client - Domain Controller.inf입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">사용자 권한 할당에 도메인 고유 그룹을 추가합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">DCBP 내의 추가 터미널 서비스 설정을 구성합니다.</td>
<td style="border:1px solid black;">DCBP 내의 경로: 컴퓨터 구성\관리 템플릿\Windows 구성 요소\터미널 서비스\암호화 및 보안</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">DCBP 내의 오류 보고를 해제합니다.</td>
<td style="border:1px solid black;">DCBP 내의 경로: 컴퓨터 구성\관리 템플릿\시스템\오류 보고</td>
</tr>
</tbody>
</table>
  
### 도메인 컨트롤러 강화 단계:

 
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
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Microsoft Active Directory 디렉터리 서비스 데이터베이스 및 로그 파일 위치를 변경합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Active Directory 로그 파일 크기를 조정합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Syskey 구현을 고려합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">DNS 서버를 보호합니다.
<br />
<img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /> 보안 동적 업데이트를 구성합니다.<br />
<img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /> 권한이 있는 시스템으로 영역 전송을 제한합니다.<br />
<img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /> DNS 서비스 로그 크기를 조정합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">잘 알려진 계정에 보안을 설정합니다.</td>
<td style="border:1px solid black;">Administrator 계정 이름을 바꾸고 복잡한 암호를 할당합니다. Guest 계정이 해제되었는지 확인합니다. 기본 계정 설명을 변경합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">서비스 계정에 보안을 설정합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">IPSec 필터 구현을 고려합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">DCBP가 도메인 컨트롤러 간에 복제되었는지 확인합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">GPUPDATE.EXE /FORCE를 실행합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">도메인 컨트롤러를 다시 시작합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><img src="images/Dd547922.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">이벤트 로그에서 오류를 확인합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
