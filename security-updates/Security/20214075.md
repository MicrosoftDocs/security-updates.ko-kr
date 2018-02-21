---
TOCTitle: '검사 목록 - Windows Server 2003 도메인 인프라'
Title: '검사 목록 - Windows Server 2003 도메인 인프라'
ms:assetid: '75b38d89-a66f-4aba-a9a8-37707c631167'
ms:contentKeyID: 20214075
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547920(v=TechNet.10)'
---

검사 목록 - Windows Server 2003 도메인 인프라
=============================================

##### 이 페이지에서

[](#xsltsection121121120120)[](#xsltsection121121120120)<span id="XSLTsection121121120120"></span>

다음 검사 목록을 사용하여 Microsoft Windows Server™ 2003 운영 체제 도메인 인프라를 구성하는 모든 보안 설정과 절차가 적절히 구현되었는지 확인하십시오.
### 도메인 정책 구성

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ></th>
<th style="border:1px solid black;" >단계</th>
<th style="border:1px solid black;" >참고:</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">
<img src="images/Dd547920.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
PDC(기본 도메인 컨트롤러)에서 외부 시간 원본을 구성하고 시간을 동기화합니다.</td>
<td style="border:1px solid black;">
w32tm.exe 명령을 사용합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
<img src="images/Dd547920.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
증분 도메인 정책을 만듭니다.</td>
<td style="border:1px solid black;">
예를 들어, 엔터프라이즈 클라이언트 환경의 경우 엔터프라이즈 클라이언트 - 도메인 정책입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
<img src="images/Dd547920.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
새로 만든 GPO(그룹 정책 개체)를 도메인 개체에 연결합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
<img src="images/Dd547920.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
해당 GPO의 우선 순위가 가장 높은지 확인합니다.</td>
<td style="border:1px solid black;">
GPO는 목록 맨 위에 와야 합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">
<img src="images/Dd547920.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
GPO를 무시 안 함으로 구성합니다.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">
<img src="images/Dd547920.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;">
해당 클라이언트 환경의 보안 템플릿을 새로 만든 GPO로 가져옵니다.</td>
<td style="border:1px solid black;">
예를 들어 엔터프라이즈 클라이언트 환경의 경우 Enterprise Client Domain.inf입니다.</td>
</tr>
</tbody>
</table>
 

[](#mainsection)[페이지 위쪽](#mainsection)
