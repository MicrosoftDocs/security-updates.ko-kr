---
TOCTitle: '검사 목록 - Windows Server 2003 구성원 서버 기준'
Title: '검사 목록 - Windows Server 2003 구성원 서버 기준'
ms:assetid: 'cfc44b7a-780e-4130-96fd-9d18b1469fff'
ms:contentKeyID: 20214076
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547921(v=TechNet.10)'
---

검사 목록 - Windows Server 2003 구성원 서버 기준
================================================

##### 이 페이지에서

[](#xsltsection121121120120)[](#xsltsection121121120120)<span id="XSLTsection121121120120"></span>

다음 검사 목록을 사용하여 Microsoft Windows Server™ 2003 운영 체제 구성원 서버 기준을 만드는 데 필요한 모든 보안 설정과 절차가 적절히 구현되었는지 확인하십시오.
### 구성원 서버 기준 정책 구성:

 
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
<td style="border:1px solid black;">
<img src="images/Dd547921.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
구성원 서버 OU(조직 구성 단위)를 만듭니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
<img src="images/Dd547921.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
MSBP(구성원 서버 기준 정책)를 만듭니다.</td>
<td style="border:1px solid black;">
예를 들어 엔터프라이즈 클라이언트 환경의 경우 엔터프라이즈 클라이언트 도메인 구성원 서버 기준 정책입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
<img src="images/Dd547921.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
MSBP를 구성원 서버 OU에 연결합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
<img src="images/Dd547921.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
적절한 보안 템플릿을 새로 만든 MSBP로 가져옵니다.</td>
<td style="border:1px solid black;">
예를 들어 엔터프라이즈 클라이언트 환경의 경우 Enterprise Client Domain.inf입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
<img src="images/Dd547921.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
DCBP(도메인 컨트롤러 기준 정책) 내의 추가 터미널 서비스 설정을 구성합니다.</td>
<td style="border:1px solid black;">
MSBP 내의 경로: 컴퓨터 구성\관리 템플릿\Windows 구성 요소\터미널 서비스\암호화 및 보안</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
<img src="images/Dd547921.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
사용자 권한 할당에 도메인 고유 그룹을 추가합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
<img src="images/Dd547921.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
MSBP 내의 오류 보고를 해제합니다.</td>
<td style="border:1px solid black;">
MSBP 내의 경로: 컴퓨터 구성\관리 템플릿\시스템\오류 보고</td>
</tr>
</tbody>
</table>
 

[](#mainsection)[페이지 위쪽](#mainsection)
