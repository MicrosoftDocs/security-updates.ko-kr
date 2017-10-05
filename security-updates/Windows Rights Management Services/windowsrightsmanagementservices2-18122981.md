---
TOCTitle: Windows Rights Management Services 서비스 팩 2 릴리스 정보
Title: Windows Rights Management Services 서비스 팩 2 릴리스 정보
ms:assetid: '78067886-681f-49a6-b43d-bfd08a369b69'
ms:contentKeyID: 18122981
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc747637(v=WS.10)'
---

Windows Rights Management Services 서비스 팩 2 릴리스 정보
==========================================================

*릴리스 날짜: 2006년 12월*

시작하기 전에
-------------

Microsoft® Windows® RMS(Rights Management Services) 서비스 팩 2(SP2)를 설치하기 전에 다음 정보를 검토하십시오. 이 릴리스 정보는 RMS SP2에 적용되며 RMS 클라이언트에는 적용되지 않습니다. RMS 클라이언트에 대한 내용은 Rights Management Services([http://go.microsoft.com/fwlink/?LinkId=68637](http://go.microsoft.com/fwlink/?linkid=68637))(영문)를 참조하십시오.

#### 시스템 요구 사항

RMS SP2를 실행하기 위한 하드웨어 요구 사항이 다음 표에 나와 있습니다.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >요구 사항</th>
<th style="border:1px solid black;" >권장 사항</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Pentium III 프로세서(800MHz 이상) 한 개가 장착된 컴퓨터</td>
<td style="border:1px solid black;">Pentium 4 프로세서(1500MHz 이상) 두 개가 장착된 컴퓨터</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">256MB RAM</td>
<td style="border:1px solid black;">512MB RAM</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">20 GB 하드 디스크 공간</td>
<td style="border:1px solid black;">40GB 하드 디스크 공간</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747637.note(WS.10).gif)참고                                          |  
|----------------------------------------------------------------------------------------------------------------|  
| RMS SP2 서버는 32비트 컴퓨터용으로 제작되었습니다. 64비트 컴퓨터에 설치하는 경우 에뮬레이션 모드로 실행됩니다. |
  
RMS SP2를 실행하는 서버에 대한 소프트웨어 요구 사항이 다음 표에 나와 있습니다.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >구성 요소</th>
<th style="border:1px solid black;" >요구 사항</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">운영 체제</td>
<td style="border:1px solid black;">RMS SP2용 Microsoft Windows Server® 2003(Web Edition 제외)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Rights Management Services SP2</td>
<td style="border:1px solid black;">RMS SP2로 업그레이드하려면 먼저 RMS 서비스 팩 1 (SP1)이 설치되어 있어야 합니다. RMS SP2 클라이언트에는 이러한 요구 사항이 해당되지 않습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">파일 시스템</td>
<td style="border:1px solid black;">NTFS 파일 시스템 권장</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">사전 설치 구성 요소</td>
<td style="border:1px solid black;"><ul>
<li>Active Directory® 디렉터리 서비스 통합이 사용된 Mesage Queuing(MSMQ)<br />
<br />
</li>
<li>ASP.NET이 사용된 IIS(인터넷 정보 서비스)<br />
<br />
</li>
<li>Microsoft .NET Framework 1.1<br />
<br />
</li>
</ul></td>
</tr>
</tbody>
</table>
 

| ![](images/Cc747637.note(WS.10).gif)참고                                                                 |
|---------------------------------------------------------------------------------------------------------------------------------------|
| 원격 관리가 가능하도록 RMS SP2를 구성하는 경우, RMS SP2 관리 서비스에 연결되는 컴퓨터는 Internet Explorer 6.0 이상을 사용해야 합니다. |

RMS SP2를 실행하는 서버에 대한 인프라 요구 사항이 다음 표에 나와 있습니다.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >구성 요소</th>
<th style="border:1px solid black;" >요구 사항</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">디렉터리 서비스</td>
<td style="border:1px solid black;">RMS가 설치된 동일 도메인 내에 Windows Server 2000 서비스 팩 3(SP3) 이상을 실행하는 도메인 컨트롤러 상의 Active Directory RMS를 사용하여 라이센스를 가져오고 콘텐츠를 게시하는 모든 사용자와 그룹에는 Active Directory에서 구성된 전자 메일 주소가 있어야 합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">데이터베이스 서버</td>
<td style="border:1px solid black;">RMS SP2에는 작업을 수행하기 위해 데이터베이스와 저장 프로시저가 필요합니다. Microsoft SQL Server™ 2000(SP3a 이상) 또는 Microsoft SQL Server 2005를 사용할 수 있습니다. 테스트 또는 기타 단일 컴퓨터 배포용으로 Microsoft SQL Server Desktop Engine(MSDE 2000) 릴리스 A 또는 Microsoft SQL Server 2005 Express Edition을 사용할 수 있습니다.</td>
</tr>
</tbody>
</table>
  
RMS는 Microsoft SQL Server 2000 및 Microsoft SQL Server 2005를 실행하는 데이터베이스 서버용으로 제작 및 테스트되었습니다. 다음 조건을 만족하는 경우 다른 데이터베이스 서버에서 RMS를 사용할 수 있습니다.
  
-   Microsoft .NET Framework 1.1에서 제공하는 ADO.NET 인터페이스를 지원합니다.  
-   RMS 초기화 스크립트 및 RMS 저장 프로시저가 Microsoft SQL Server가 사용하는 구조화된 쿼리 언어인 Transact-SQL을 사용하기 때문에 Transact-SQL과 호환되어야 합니다.  
-   모든 Microsoft SQL Server 특정 확장을 지원합니다.  
-   .NET Framework의 System.Data.SqlClient 네임스페이스의 메서드 호출에 응답합니다.  
-   System.Data.SqlClient 네임스페이스의 해당 기능을 제공합니다.  
-   Windows 인증 모드를 사용합니다.
  
데이터베이스 서버가 위의 조건을 지원하는지 여부를 확인하려면 해당 데이터베이스 업체에 문의하십시오.
  
다음 표에서는 RMS에서 다른 작업을 수행할 때 필요한 사용자 권한과 사용 권한을 보여줍니다.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >작업</th>
<th style="border:1px solid black;" >계정 요구 사항</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">RMS 설치</td>
<td style="border:1px solid black;">로컬 컴퓨터 관리자 자격 증명이 있는 도메인 사용자</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RMS 루트 클러스터 구축</td>
<td style="border:1px solid black;">로컬 컴퓨터 관리자 자격 증명 및 Active Directory 조회 및 쓰기가 가능한 도메인 사용자</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RMS 라이센스 전용 클러스터 구축</td>
<td style="border:1px solid black;">로컬 컴퓨터 관리자 자격 증명 및 Active Directory 조회가 가능한 도메인 사용자</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">새 구성 데이터베이스를 사용하여 구축</td>
<td style="border:1px solid black;">SQL Server를 실행하는 컴퓨터에서 로컬 컴퓨터 관리자 자격 증명 및 읽기, 쓰기, 작성이 가능한 도메인 사용자</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">기존 구성 데이터베이스를 사용하여 구축</td>
<td style="border:1px solid black;">데이터베이스 서버를 실행하는 컴퓨터에서 로컬 컴퓨터 관리자 자격 증명 및 읽기, 쓰기가 가능한 도메인 사용자</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RMS 관리</td>
<td style="border:1px solid black;">로컬 컴퓨터 관리자 자격 증명이 있는 도메인 사용자</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747637.note(WS.10).gif)참고                                                                                                                                                                  |  
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Windows Server 구성, Active Directory, 메시지 큐, IIS 및 파일 시스템에 대한 자세한 내용은 Windows Server 2003 TechCenter([http://go.microsoft.com/fwlink/?LinkId=78135](http://go.microsoft.com/fwlink/?linkid=78135))를 참조하십시오. |
  
클러스터 배포에서 RMS를 사용하는 경우 다음 표에 나열된 항목을 해결했는지 확인하십시오.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >조건</th>
<th style="border:1px solid black;" >권장 사항</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">RMS를 사용할 다수의 데스크톱</td>
<td style="border:1px solid black;">SMS(Systems Management Server) 또는 그룹 정책을 사용하여 RMS SP2 클라이언트를 설치합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">대규모 클라이언트 요청</td>
<td style="border:1px solid black;">로드 균형 조정 서버, Windows 서버 운영 체제의 네트워크 로드 균형 조정 서비스 또는 하드웨어 로드 균형 조절기를 사용하여 클러스터 전반에 요청을 분산합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">가상 IP 주소 지정을 사용하여 엑스트라넷 및 인트라넷 요청을 서비스하는 네트워크 어댑터 두 개</td>
<td style="border:1px solid black;">엑스트라넷에 가상 IP 주소를 노출하는 DNS(Domain Name System) 등록이 해당 주소를 인트라넷에도 노출했는지 확인합니다.</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747637.Important(WS.10).gif)중요                                                                                                                                                                                                                                                                                             |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 인트라넷에 DNS를 등록하지 않으면 내부 클라이언트 라이센스를 요청할 수 없습니다. DNS 설정을 수정할 수 없는 경우 클러스터 URL이 클러스터의 가상 IP 주소에 매핑되도록 클러스터 내 각 서버의 호스트 테이블을 수정할 수 있습니다. RMS를 구축하기 전에 DNS 등록이 완료되어야 합니다. 이미 서비스를 구축한 경우 서버에서 RMS를 제거하고 구축 프로세스를 다시 진행해야 합니다. |
  
#### 이 릴리스에서 지원하는 클라이언트
  
서비스 팩이 없는 RMS 클라이언트, RMS 클라이언트 SP1 또는 RMS 클라이언트 SP2는 Microsoft Windows 2000, Windows XP 및 Windows Server 2003을 실행하는 컴퓨터라면 어디에든 설치할 수 있습니다. 이전 버전의 Windows 운영 체제는 이 릴리스에서 지원되지 않습니다.
  
| ![](images/Cc747637.Caution(WS.10).gif)주의                                 |  
|----------------------------------------------------------------------------------------------------------|  
| 서비스 팩이 없는 RMS 클라이언트를 사용한다면 RMS 서버 SP 1 이상에 대해 온라인 게시를 사용할 수 없습니다. |
  
기능상의 변경  
-------------
  
RMS SP2에 추가된 새로운 기능은 다음과 같습니다.
  
-   [향상된 포리스트 간 그룹 확장](#bkmk_cif1)  
-   [데이터베이스 로깅 변경](#bkmk_cif2)  
-   [더 커진 서버 일괄 처리 크기](#bkmk_cif3)  
-   [Microsoft SQL Server 2005 호환성](#bkmk_cif4)
  
<span id="BKMK_CIF1"></span>
#### 향상된 포리스트 간 그룹 확장
  
#### 이 기능은 무엇을 수행합니까?
  
RMS에서 포리스트 간 그룹 확장은 두 포리스트 사이에 그룹 구성원이 복제되지 않는 서로 다른 포리스트에서 RMS가 Active Directory Universal 그룹 구성원을 확장할 수 있도록 지원합니다. 한 포리스트의 사용자가 권한으로 보호된 콘텐츠를 다른 포리스트의 사용자에게 보내면 RMS는 검색 기간을 거쳐 그 사용자가 해당 콘텐츠에 대한 액세스 권한이 있는지 확인합니다. 이 검증 프로세스는 한 포리스트에서 다른 포리스트로의 LDAP 쿼리를 사용하여 원격 포리스트의 RMS SCP(서비스 연결 지점)를 찾는 데 사용됩니다. 원격 포리스트의 SCP를 발견하면 RMS 서비스 계정은 그룹 확장 파이프라인으로 요청을 보냅니다. 사용자가 그룹의 구성원이면 요청은 원격 포리스트를 요청합니다.
  
#### 이 기능의 적용 대상은 누구입니까?
  
이 새로운 기능은 포리스트 간에 유니버설 그룹 구성원이 복제되지 않는 복수 포리스트 Active Directory 환경의 RMS 고객을 대상으로 합니다.
  
#### 이러한 변경 사항이 중요한 이유는 무엇입니까?
  
새로운 포리스트 트러스트 확장 프로토콜은 복수 포리스트 Active Directory 환경을 배포하려는 고객들의 안정성을 증대시켜줄 것입니다.
  
#### 이 기능의 차별화 요소는 무엇입니까?
  
RMS SP2 이전에는 .NET 원격 호출을 사용하여 포리스트 간 그룹 확장이 이루어졌습니다. 이 릴리스에서는 포리스트 프로토콜 간 그룹 확장이 포리스트 트러스트 그룹 확장 파이프라인으로의 SOAP/HTTP 요청을 사용하여 ASP.NET 웹 서비스로 변경되었습니다.
  
| ![](images/Cc747637.note(WS.10).gif)참고                                                                                                                                  |  
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 이전 버전과의 호환성을 위해 .NET 원격 호출도 RMS SP2에서 여전히 지원됩니다. 그러나 새로운 포리스트 프로토콜 간 그룹 확장을 최대한 사용하려면 모든 RMS 클러스터에서 적어도 RMS SP2가 실행되어야 합니다. |
  
#### RMS SP2에서 추가 또는 변경된 설정은 무엇입니까?
  
RMS SP2에서는 새로운 RMS 그룹 확장 파이프라인이 가장 안전한 설정으로 기본 구성되어 로컬 RMS 서비스 및 관리자 그룹만이 액세스할 수 있습니다. 계정 액세스를 부여하려면 wwwroot\\\_wmcs\\GroupExpansion\\GroupExpansion.asmx에 있는 그룹 확장 파이프라인의 액세 제어 목록을 변경해야 합니다.
  
| ![](images/Cc747637.Important(WS.10).gif)중요                                                                                                                                                                                                                                                                               |  
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 각 Active Directory 포리스트의 RMS 서비스 계정에 클러스터의 각 RMS 서버에 있는 그룹 확장 파이프라인에 대한 액세스가 있는지 확인합니다. 계정에 액세스 권한이 없는 경우 그룹 확장이 이루어지지 않습니다. 또는 각 포리스트에 동일한 계정을 만들고 각 계정에 동일한 암호를 지정할 수 있습니다. 이 경우 그룹 확장 파이프라인에 하나의 계정만 추가해야 합니다. |
  
새로운 이벤트가 RMS SP2에 추가되어 메시지 큐 서비스에 들어가지 않은 문제 메시지를 알려줍니다. 이 새로운 이벤트 로그에는 메시지에 디지털 서명을 할 수 없거나 메시지를 검증할 수 없을 때마다 사용자에게 알려주는 이벤트가 포함됩니다. 검증 문제의 몇 가지 예로 형식이 잘못된 메시지, 해시나 서명 누락 또는 잘못된 해시나 서명 등이 있습니다.
  
<span id="BKMK_CIF2"></span>
#### 데이터베이스 로깅 변경
  
#### 이 기능은 무엇을 수행합니까?
  
RMS는 메시지 큐를 사용하여 모든 RMS 통신을 로깅 데이터베이스로 보내는 로깅 수신기 서비스를 사용합니다. RMS 클러스터는 메시지 큐 서비스로 메시지를 제출하고 로깅 수신기 서비스는 이 메시지를 메시지 큐의 큐에서 검색하여 로깅 데이터베이스에 기록합니다.
  
#### 이 기능의 적용 대상은 누구입니까?
  
이 기능은 RMS 로깅 수신기 서비스를 사용하고 있는 현재 RMS 사용자 및 RMS 로깅 수신기 서비스 사용을 고려하고 있는 새로운 RMS SP2 사용자에게 적용됩니다.
  
#### 이러한 변경 사항이 중요한 이유는 무엇입니까?
  
RMS 이전 릴리스에서 RMS 로깅 큐는 액세스 제어 목록을 사용하여 보호되었으나 인증은 사용되지 않았습니다. 인증을 사용하지 않으면 악의적인 사용자가 잘못된 메시지를 RMS 로깅 큐에 기록할 가능성이 발생합니다.
  
#### 이 기능의 차별화 요소는 무엇입니까?
  
RMS SP2에서는 메시지 큐를 사용하여 RMS 클러스터가 전송한 메시지에 추가 인증이 제공됩니다. 메시지 큐에 대한 무단 액세스를 방지하는 액세스 제어 목록 뿐만 아니라 메시지 인증 검증 메커니즘을 사용하여 메시지 큐의 큐를 보호합니다. 메시지 큐 서비스로 메시지를 보내면 RMS 파이프라인은 메시지 해시를 생성하고 RMS 클러스터의 개인 키를 사용하여 디지털 서명을 합니다. 로깅 수신기 서비스는 먼저 메시지의 자체 해시를 계산하고 이를 메시지에 포함된 해시와 비교합니다. 해시가 일치하면 로깅 수신기 서비스는 클러스터 공용 키 및 메시지의 해시를 사용하여 서명을 확인합니다. 해시가 일치하고 서명이 확인되면 메시지를 로깅 데이터베이스로 보냅니다. 확인 단계가 성공하지 못하면 메시지는 메시지 큐의 큐에서 영구 삭제되고 이벤트 경고가 이벤트 뷰어의 응용 프로그램 로그에 기록됩니다.
  
#### RMS SP2에서 추가 또는 변경된 설정은 무엇입니까?
  
문제 메시지가 메시지 큐의 큐에 들어가지 못한 경우 이를 표시하도록 설계된 새로운 이벤트가 RMS SP2에 추가되었습니다. 이러한 새로운 이벤트는 응용 프로그램 로그에 기록되고 디지털 서명을 할 수 없는 메시지나 검증할 수 없는 메시지의 디지털 서명이 포함됩니다. 검증 문제의 몇 가지 예로 형식이 잘못된 메시지, 해시나 서명 누락 또는 잘못된 해시나 서명 등이 있습니다.
  
<span id="BKMK_CIF3"></span>
#### 더 커진 서버 일괄 처리 크기
  
#### 이 기능은 무엇을 수행합니까?
  
RMS에서 일괄 처리는 여러 개의 라이센스 요청을 하나의 요청으로 RMS 클러스터로 보낼 수 있으므로 성능을 향상시킵니다. 이는 각 라이센스에 대해 개별적으로 요청하는 것과 대조되는 개념입니다.
  
#### 이 기능의 적용 대상은 누구입니까?
  
더 큰 서버 일괄 처리를 지원함으로써 권한으로 보호되는 콘텐츠에 대해 한 번에 여러 개의 라이센스를 취득해야 하는 RMS 사용 응용 프로그램을 대상으로 합니다.
  
#### 이러한 변경 사항이 중요한 이유는 무엇입니까?
  
RMS 일괄 처리를 통해 AcquireLicense RMS 파이프라인으로 한 번의 요청을 보내 하나 이상의 게시 라이센스에 대해 여러 개의 RAC(Rights Accounts Certificates) 사용 라이센스를 취득할 수 있습니다. 1보다 큰 일괄 처리 크기를 사용하지 않는다면 RMS 사용 응용 프로그램은 모든 사용자에 대해 개별적으로 사용 라이센스를 요청해야 합니다.
  
#### 이 기능의 차별화 요소는 무엇입니까?
  
RMS SP2 이전 버전에서는 RMS 클러스터가 지원하는 최대 일괄 처리 크기가 1이었습니다. 최대 크기를 1보다 큰 수로 설정하면 클러스터가 이를 무시합니다. RMS SP2에서는 일괄 처리 크기를 최대 100까지 설정할 수 있습니다.
  
| ![](images/Cc747637.note(WS.10).gif)참고        |  
|------------------------------------------------------------------------------|  
| AcquireLicense RMS 파이프라인에만 일괄 처리된 요청에 대한 지원이 포함됩니다. |
  
RMS SP2에서는 일괄 처리된 요청에 대한 오류 보고 기능이 개선되었습니다. 예를 들어 10개의 일괄 처리 요청을 보냈는데 두 번째와 세 번째 요청이 실패한 경우 각 실패한 요청에 대해 이벤트가 이벤트 로그에 기록됩니다.
  
<span id="BKMK_CIF4"></span>
#### Microsoft SQL Server 2005 호환성
  
#### 이 기능은 무엇을 수행합니까?
  
RMS SP2에서 Microsoft SQL Server 2005는 추가 구성을 수행하지 않고도 RMS 구성 및 로깅 데이터베이스를 지원하는 데이터베이스 서버로 사용될 수 있습니다.
  
#### 이 기능의 적용 대상은 누구입니까?
  
RMS SP2에서의 Microsoft SQL Server 2005 지원 기능은 RMS 데이터베이스로 Microsoft SQL Server 2005를 사용하려는 RMS 고객을 대상으로 합니다.
  
#### 이러한 변경 사항이 중요한 이유는 무엇입니까?
  
RMS 이전 버전에서는 sysmessages 표에서 사용된 일부 매개 변수의 데이터 유형이 Microsoft SQL Server 2005 형식 사양과 호환되지 않았습니다. 자세한 내용은 Microsoft 기술 자료 문서 913372[(http://go.microsoft.com/fwlink/?LinkId=68638](http://go.microsoft.com/fwlink/?linkid=68638))(영문)를 참조하십시오.
  
#### 이 기능의 차별화 요소는 무엇입니까?
  
RMS SP2 이전 버전에서는 SQL RAISERROR문을 사용하여 RMS 사용자에게 오류가 발생했음을 알려 주었습니다. RAISERROR문은 sysmessages 테이블을 조회하여 이 표에 저장되어 있는 RMS 오류 메시지를 검색합니다. RMS SP2는 다른 기술을 사용하여 SQL 오류를 전파하므로 sysmessages 테이블에 더 이상 의존하지 않습니다.
  
| ![](images/Cc747637.note(WS.10).gif)참고                                                                                                                                                                                  |  
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| RMS SP1에서 RMS SP2로 업그레이드하는 경우 오류 메시지를 찾기 위해 더 이상 sysmessages 테이블을 조회하지는 않지만 오류 메시지 자체는 sysmessages 테이블에 남아 있게 됩니다. RMS SP2를 새로 설치하면 sysmessages 테이블에 새로 추가되는 항목이 없습니다. |
  
알려진 문제  
-----------
  
아래 절은 이 RMS 릴리스의 알려진 문제점을 다룹니다.
  
#### 도움말 파일이 여전히 RMS 서비스 팩 1을 참조합니다.
  
RMS SP2 설치 시 포함되는 도움말 파일이 여전히 RMS SP1을 참조합니다. RMS SP2에 대한 내용은 Rights Management Services([http://go.microsoft.com/fwlink/?LinkId=68637](http://go.microsoft.com/fwlink/?linkid=68637))(영문)를 참조하십시오.
  
#### Windows Update를 통해 x64 기반 또는 Itanium 기반 컴퓨터에 RMS SP2 클라이언트 설치 실패
  
RMS 클라이언트 또는 RMS SP1 클라이언트가 x64 기반 컴퓨터에 설치되어 있고 Windows Update를 사용하여 RMS SP2 클라이언트(x64)로 클라이언트를 업그레이드하려고 하는 경우 설치되지 않습니다. 32비트 시스템용으로 만들어진 이전 RMS 클라이언트가 x64 기반 컴퓨터에서 작동하긴 하지만 RMS SP2 클라이언트(x64)로 업그레이드할 수는 없습니다. 먼저 이전 RMS 클라이언트를 제거한 다음 업데이트를 다시 시작하십시오. Windows Update는 운영 체제 버전을 검색하여 적절한 RMS SP2 클라이언트를 제공합니다. Itanium 기반 컴퓨터에서도 마찬가지입니다.
  
#### 재구축 시 로깅 수신기 서비스 시작 불가
  
클러스터의 구축을 중단하면 로깅 수신기 서비스는 서비스를 중지된 상태로 두는 데 실패합니다. 서비스를 완전히 중단하려면 컴퓨터를 다시 시작해야 합니다.
  
#### 소프트웨어 기반이 아닌 신뢰할 수 있는 게시 도메인 제거 불가
  
소프트웨어 기반이 아닌 개인 키 구현을 통해 신뢰할 수 있는 게시 도메인을 가져온 후에 이를 삭제하는 것이 불가능합니다. Windows Rights Management Services 관리 콘솔에서 소프트웨어 기반이 아닌 개인 키를 가져올 수 없습니다. 개인 키를 내보내고 가져오는 방법에 대한 지침은 해당 하드웨어 업체에 문의하십시오.
  
#### Microsoft .NET Framework 2.0을 RMS 서버에 설치 시 IIS 가상 루트 변경
  
RMS SP2는 .NET Framework 버전 1.1과 함께 포함된 ASP.NET 스크립트 매핑을 사용합니다. 이후 버전에서 제공되는 매핑은 RMS SP2와 호환되지 않습니다. 그러나 두 버전이 다른 독립 응용 프로그램과 간섭을 일으키지 않고 동시에 존재할 수 있습니다. 서버에 .NET Framework 1.1 및 .NET Framework 2.0 이상이 설치되어 있는 경우 RMS SP2의 설치와 구축을 성공적으로 완료한 것처럼 보여도 RMS 클러스터가 제대로 작동하지 않을 수 있습니다. 이 문제점의 원인은 RMS 가상 루트가 ASP.NET 스크립트 맵 버전 2.0이 아닌 버전 1.1에 등록되어야 하기 때문입니다. RMS 가상 루트를 ASP.NET 스크립트 맵 버전 1.1에 등록하려면 명령 프롬프트에서 다음 명령을 실행하십시오.
  
**%windir%\\Microsoft.NET\\Framework\\v1.1.4322&gt;aspnet\_regiis.exe -s W3SVC/1/ROOT/\_wmcs**
  
이 명령을 실행하면 RMS 가상 루트가 제대로 등록되고 RMS SP2을 서버에서 실행할 수 있습니다.
  
#### Active Directory Windows 2000 기본 기능 수준 사용 시 그룹 구성원 유실 가능
  
Active Directory 인프라 수준이 Windows 2000 기본 기능 수준으로 업그레이드된 환경에서 RMS를 배포하는 경우 숨겨져 있는 분배 목록의 그룹 구성원을 확장하려 할 때 RMS가 Active Directory 개체의 memberOf 특성을 읽지 못할 수도 있습니다. RMS에서 memberOf 특성을 읽으려면 RMS 서비스 계정이 Pre-Windows 2000 Compatible Access 그룹의 구성원인 도메인 계정을 사용해야 합니다. 자세한 내용은 Microsoft 기술 자료 문서 812841([http://go.microsoft.com/fwlink/?LinkId=78152](http://go.microsoft.com/fwlink/?linkid=78152))을 참조하십시오.
  
#### 데이터베이스에 액세스할 수 없을 때 로깅 수신기 서비스가 배달 못한 편지 큐로 메시지 큐 메시지를 보냄
  
데이터베이스 중단, 네트워크 연결 문제 등과 같이 로깅 수신기 서비스가 데이터베이스에 도달하지 못하는 경우가 있습니다. 이 경우 메시지를 배달 못한 편지 큐로 보냅니다. 이 메시지를 복구할 수 있는 즉, 로깅 데이터베이스로 보낼 수 있는 유일한 방법은 RMS 관리 도구 키트와 함께 제공되는 RMS 큐 복구 도구를 사용하는 것입니다. RMS 관리 도구 키트를 다운로드하려면 [http://go.microsoft.com/fwlink/?LinkId=33841](http://go.microsoft.com/fwlink/?linkid=33841)을 참조하십시오.
  
| ![](images/Cc747637.note(WS.10).gif)참고                                                                                                           |  
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| LogRecoveryCmd에서 Recover 및 RecoverandPurge가 제거되었습니다. 따라서 모든 메시지는 메시지 큐 서비스를 통해 다시 라우팅되어 로깅 데이터베이스에 보내지기 전에 인증을 받습니다. |
  
#### Microsoft SQL Server 2005를 업그레이드하기 전에 RMS SP2 업그레이드
  
RMS SP2로 업그레이드하는 경우와 Microsoft SQL Server 2000에서 Microsoft SQL Server 2005로 업그레이드 하는 경우 먼저 RMS를 업그레이드해야 합니다. 이렇게 해야 Microsoft SQL Server 업그레이드 시 발생하는 호환성 문제를 방지할 수 있습니다.
  
#### 이름에 아포스트로피(')가 포함된 웹 사이트에서 RMS SP2 구축 불가
  
아포스트로피 문자(')가 이름에 포함된 웹 사이트에 RMS SP2를 구축하려고 시도하면 구축 프로세스가 실패하고 **잘못된 매개 변수** 오류 메시지가 표시됩니다. 웹 사이트에 RMS SP2를 구축하려면 웹 사이트 이름에서 아포스트로피를 제거하십시오.
  
#### 64비트 버전 Windows Server 2003을 실행하는 서버에서 ASP.NET 버전 1.1 사용
  
RMS 도움말의 "시스템 요구 사항" 항목은 IIS(인터넷 정보 서비스) 설치 후 .NET Framework 1.1을 설치하고 ASP.NET 1.1을 사용하는 방법을 자세히 설명합니다. 그러나 IIS를 설치하기 전에 .NET Framework 1.1을 설치하는 경우 ASP.NET 1.1이 웹 서비스 확장에 나열되지 않으므로 문서화된 프로시저를 사용할 수 없습니다. .NET Framework 1.1 설치 후 IIS를 설치한 경우 명령 프롬프트에서 다음 명령을 실행하여 ASP.NET을 사용하십시오.
  
**%SystemRoot%\\Microsoft.NET\\Framework\\v1.1.4322\\aspnet\_regiis.exe -i –enable**
  
.NET Framework 1.1 이후의 버전을 사용하는 경우 기존 IIS 스크립트 맵이 재설정되는 것을 막으려면 이 명령에서 **-i**를 **-ir**로 변경하십시오.
  
#### 원격 포리스트 RMS 서비스 계정을 로컬 groupexpansion 파이프라인에 추가
  
groupexpansion 파이프라인의 ACL에서 BUILTIN\\users를 제거하는 보안 문제가 해결되었습니다. 이는 포리스트 간의 그룹 확장 시나리오를 해제할 수 있습니다. 이 문제를 해결하려면 다음 단계를 수행합니다.
  
**원격 포리스트에 RMS 서비스 계정 추가**  
1.  첫 번째 포리스트의 RMS 루트 클러스트를 나타내는 Forest1에서 inetpub\\wwwroot\\\_wmcs로 이동합니다.
  
2.  마우스 오른쪽 단추로 **GroupExpansion** 폴더를 클릭한 다음 **속성**을 선택합니다.
  
3.  **GroupExpansion 속성** 창에서 **보안** 탭을 클릭하고 *Forest2\\RmsServiceAccount*(여기서 Forest2는 두 번째 포리스트의 RMS 루트 클러스터를 나타냄)의 항목(예: rmil31\\rmsvc)을 추가합니다.
  
4.  **확인**을 클릭합니다.
  
5.  **실행**을 클릭하고 **iisreset**을 입력한 다음**확인**을 클릭합니다.
  
#### .NET Framework 업그레이드 시 데이터 유실 가능
  
RMS를 설치 및 구축한 후 .NET Framework(CLR) 버전 1.1을 업그레이드하는 경우 .NET Framework 버전 2.0을 사용하도록 vroots를 설정합니다. 이 경우 로깅 데이터베이스에 아무런 정보도 로깅되지 않습니다. 이로 인해 데이터가 유실될 수 있습니다. 다음 조치 중 하나를 수행하십시오.
  
-   RMS를 설치 및 구축하기 전에 .NET Framework를 업그레이드합니다.  
-   .NET Framework가 업그레이드된 후에는 1.1을 사용하도록 vroots를 재설정합니다.
  
이 릴리스에서의 설명서 변경 사항  
--------------------------------
  
다음은 이 릴리스에서 변경된 항목입니다.
  
-   Passport 기반 권한 계정 인증서 트러스트([http://go.microsoft.com/fwlink/?LinkId=70369](http://go.microsoft.com/fwlink/?linkid=70369))  
-   RMS 소프트웨어 요구 사항([http://go.microsoft.com/fwlink/?LinkId=70371](http://go.microsoft.com/fwlink/?linkid=70371))  
-   RMS 클라이언트 배포 방법([http://go.microsoft.com/fwlink/?LinkId=70373](http://go.microsoft.com/fwlink/?linkid=70373))  
-   RMS 명령 프롬프트 설치([http://go.microsoft.com/fwlink/?LinkId=70374](http://go.microsoft.com/fwlink/?linkid=70374))  
-   RMS 핵심 구성 데이터베이스 테이블([http://go.microsoft.com/fwlink/?LinkId=70375](http://go.microsoft.com/fwlink/?linkid=70375))  
-   RMS 구성 데이터베이스 인증 테이블([http://go.microsoft.com/fwlink/?LinkId=70376](http://go.microsoft.com/fwlink/?linkid=70376))  
-   RMS 로깅 데이터베이스 테이블([http://go.microsoft.com/fwlink/?LinkId=70377](http://go.microsoft.com/fwlink/?linkid=70377))  
-   확장 요구 사항 평가([http://go.microsoft.com/fwlink/?LinkId=70378](http://go.microsoft.com/fwlink/?linkid=70378))  
-   RMS 배포 보안([http://go.microsoft.com/fwlink/?LinkId=70379](http://go.microsoft.com/fwlink/?linkid=70379))  
-   서비스 해제 서비스 사용([http://go.microsoft.com/fwlink/?LinkId=70380](http://go.microsoft.com/fwlink/?linkid=70380))  
-   외부 RMS 사용자 계획([http://go.microsoft.com/fwlink/?LinkId=70381](http://go.microsoft.com/fwlink/?linkid=70381))  
-   모바일 장치 및 서버 서비스에 RMS 서버 지원 사용([http://go.microsoft.com/fwlink/?LinkId=70382](http://go.microsoft.com/fwlink/?linkid=70382))
  
#### 저작권
  
*이 문서에 포함된 정보는 문서 발행 시에 논의된 문제들에 대한 Microsoft Corporation의 당시 관점을 나타냅니다. Microsoft는 변화하는 시장 상황에 부응해야 하므로 이를 Microsoft측의 공약으로 해석해서는 안 되며 발행일 이후 소개된 어떠한 정보에 대해서도 Microsoft는 그 정확성을 보증하지 않습니다.*
  
*이 설명서는 오직 정보를 제공하기 위한 것입니다. MICROSOFT는 이 문서의 정보에 대해 명시적, 묵시적 또는 법률에 의해 규정된 보증을 하지 않습니다.*
  
*해당 저작권법을 준수하는 것은 사용자의 책임입니다. 저작권에서의 권리와는 별도로, 이 설명서의 어떠한 부분도 Microsoft Corporation의 명시적인 서면 승인 없이는 어떠한 형식이나 수단(전기적, 기계적, 복사기에 의한 복사, 디스크 복사 또는 다른 방법) 또는 목적으로도 복제되거나, 검색 시스템에 저장 또는 도입되거나, 전송될 수 없습니다.*
  
*Microsoft가 이 설명서 본안에 관련된 특허권, 상표권, 저작권 또는 기타 지적 재산권 등을 보유할 수도 있습니다. 서면 사용권 계약에 따라 Microsoft로부터 귀하에게 명시적으로 제공된 권리 이외에, 이 설명서의 제공은 귀하에게 이러한 특허권, 상표권, 저작권 또는 기타 지적 재산권 등에 대한 어떠한 사용권도 허여하지 않습니다.*
  
*다른 설명이 없는 한, 용례에 사용된 회사, 기관, 제품, 사람 및 이벤트 등은 실제 데이터가 아닙니다. 어떠한 실제 회사, 기관, 제품, 도메인 이름, 전자 메일 주소, 로고, 사람, 장소 및 이벤트와도 연관시킬 의도가 없으며 그렇게 유추해서도 안 됩니다.*
  
*© 2006 Microsoft Corporation. All rights reserved.*
  
*Active Directory, Microsoft, MS-DOS, Visual Studio, Windows, Windows Server, SQL Server 및 Windows NT는 미국, 대한민국 및/또는 기타 국가에서의 Microsoft Corporation 등록 상표  또는 상표입니다.*
  
*여기에 인용된 실제 회사와 제품 이름은 해당 소유자의 상표일 수 있습니다.*
