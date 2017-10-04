---
TOCTitle: '검사 목록 - Windows Server 2003 IAS 서버'
Title: '검사 목록 - Windows Server 2003 IAS 서버'
ms:assetid: '8a702a3f-8ae3-4bf1-b908-14a7376609ec'
ms:contentKeyID: 20214082
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547927(v=TechNet.10)'
---

검사 목록 - Windows Server 2003 IAS 서버
========================================

##### 이 페이지에서

[](#xsltsection121121120120)[](#xsltsection121121120120)
다음 검사 목록을 사용하여 Microsoft Windows Server™ 2003 운영 체제 IAS(Internet Authentication Service) 서버를 강화하는 모든 보안 설정과 절차가 적절히 구현되었는지 확인하십시오.

### Microsoft Active Directory IAS 서버 OU 구조 만들기:

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th> </th>
<th>단계</th>
<th>참고:</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
IAS 서버 OU(조직 구성 단위)를 만듭니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
증분 IAS 서버 정책을 만듭니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
GPO를 IAS 서버 OU에 연결합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
해당 클라이언트 환경의 보안 템플릿을 새로 만든 GPO로 가져옵니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
</tbody>
</table>
 

### IAS 서버 강화 단계:

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th> </th>
<th>단계</th>
<th>참고:</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
Windows Server 2003을 설치하고 구성합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
IAS 서비스를 설치하고 구성합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
필요한 서비스 팩 및/또는 업데이트를 적용합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
바이러스 예방 솔루션을 설치하고 구성합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
필요하면 MOM(Microsoft Operations Manager) 에이전트 또는 이와 유사한 모니터링 솔루션을 설치하고 구성합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
서버를 해당 IAS 서버 OU로 이동합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
잘 알려진 계정에 보안을 설정합니다.</td>
<td style="border:1px solid black;"><br />
기본 제공 Administrator 계정의 이름을 변경하고 복잡한 암호를 지정합니다. Guest 계정이 해제되어 있는지 확인합니다. 기본 계정 설명을 변경합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
서비스 계정에 보안을 설정합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
증분 IAS 정책이 도메인 컨트롤러 간에 복제되었는지 확인합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
GPUPDATE.EXE /FORCE를 실행합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
서버를 다시 시작합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547927.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
이벤트 로그에서 오류를 확인합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
</tbody>
</table>
 

[](#mainsection)[페이지 위쪽](#mainsection)
