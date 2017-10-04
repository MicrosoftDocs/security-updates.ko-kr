---
TOCTitle: '검사 목록 - Windows Server 2003 방호 호스트'
Title: '검사 목록 - Windows Server 2003 방호 호스트'
ms:assetid: '3eb07107-341f-4006-b079-4ce776e8704c'
ms:contentKeyID: 20214084
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547929(v=TechNet.10)'
---

검사 목록 - Windows Server 2003 방호 호스트
===========================================

##### 이 페이지에서

[](#xsltsection121121120120)[](#xsltsection121121120120)
다음 검사 목록을 사용하여 DNS(Domain Name System) 서버, FTP(File Transfer Protocol) 서버, SMTP(Simple Mail Transport Protocol) 서버 및 NNTP(Network News Transfer Protocol) 서버 등의 Microsoft Windows Server™ 2003 운영 체제 방호 호스트 서버가 적절히 강화되었는지 확인하십시오.

### 방호 호스트 강화 단계:

 
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
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
Windows Server 2003을 설치하고 구성합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
적절한 방호 호스트 서비스를 설치하고 구성합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
필요한 서비스 팩 및/또는 업데이트를 적용합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
바이러스 예방 솔루션을 설치하고 구성합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
적절한 방호 호스트 서비스를 설치하고 구성합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
방호 호스트 보안 템플릿을 수정하여 적절한 방호 호스트 기능에 필요한 서비스를 설정합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
보안 템플릿을 BHLP(방호 호스트의 로컬 정책)로 가져옵니다.</td>
<td style="border:1px solid black;"><br />
보안 및 구성 분석 스냅인을 사용하여 High Security - Bastion Host.inf를 가져옵니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
필요하지 않은 프로토콜과 바인딩을 제거합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
잘 알려진 계정에 보안을 설정합니다.</td>
<td style="border:1px solid black;"><br />
기본 제공 Administrator 계정의 이름을 변경하고 복잡한 암호를 지정합니다. Guest 계정이 해제되어 있는지 확인합니다. 기본 계정 설명을 변경합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
서비스 계정에 보안을 설정합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
BHLP 내의 오류 보고를 해제합니다.</td>
<td style="border:1px solid black;"><br />
DCBP 내의 경로: 컴퓨터 구성\관리 템플릿\시스템\오류 보고</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
IPSec 필터를 구현합니다.</td>
<td style="border:1px solid black;"><br />
PacketFilters-SMTPBastionHost.cmd 파일을 수정하여 적절한 방호 호스트 기능을 설정합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><br />
<img src="images/Dd547929.mnp_checkbox(ko-kr,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><br />
서버를 다시 시작합니다.</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
</tbody>
</table>
 

[](#mainsection)[페이지 위쪽](#mainsection)
