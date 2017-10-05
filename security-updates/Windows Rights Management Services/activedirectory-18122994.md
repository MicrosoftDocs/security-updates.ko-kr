---
TOCTitle: Active Directory 서비스 검색 무시
Title: Active Directory 서비스 검색 무시
ms:assetid: '9d97e7fb-5b05-4853-ad7b-6cc82b9729f0'
ms:contentKeyID: 18122994
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc747614(v=WS.10)'
---

Active Directory 서비스 검색 무시
=================================

RMS 서비스 및 클라이언트는 먼저 로컬 레지스트리를 검색하여 서비스 위치를 발견합니다. 레지스트리의 특정 키에 값이 없다면 RMS 서비스 및 클라이언트는 Active Directory에서 SCP(서비스 연결 지점)를 조회합니다. 즉, 특정 키를 서버 또는 클라이언트 레지스트리에 입력하면 기본 Active Directory 검색 설정을 재정의할 수 있습니다.

| ![](images/Cc747614.note(WS.10).gif)참고                                                                            |
|--------------------------------------------------------------------------------------------------------------------------------------------------|
| SCP가 Active Directory에 게시되지 않도록 RMS 루트 클러스터가 구성된 경우 이러한 키를 사용하여 RMS 클라이언트를 올바른 위치로 지정할 수 있습니다. |

이 섹션에는 레지스트리 항목에 대한 설명과 해당 항목을 만드는 방법에 대한 자세한 내용이 나와 있습니다.

라이센스 전용 클러스터 하위 등록을 위한 서비스 검색 재정의
----------------------------------------------------------

라이센스 전용 클러스터를 구축하는 경우 라이센스 전용 클러스터의 Active Directory 포리스트에 배포된 루트 클러스터가 아닌 다른 루트 클러스터에 하위 등록을 하려면 하위 등록 및 계정 인증 서비스 검색을 모두 재정의해야 합니다.

#### 레지스트리 항목 설명

다음 레지스트리 항목은 하위 등록 및 계정 인증 서비스를 재정의하는 데 사용됩니다.

-   **SubEnrollmentURL**. 이 항목은 해당 서버 사용 허가자 인증서를 요청하는 경우 라이센스 서버에 사용되는 루트 클러스터의 경로를 지정합니다.
-   **GicURL**. 이 항목은 라이센스 전용 클러스터에 대한 계정 인증 서비스의 경로를 지정합니다.

#### 항목 세부 정보

컴퓨터에서 32비트 버전의 Windows Server 2003이 실행되는 경우 라이센스 전용 클러스터 하위 등록을 위한 서비스 검색 항목의 전체 레지스트리 하위 키 경로는 다음과 같습니다.

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0**

컴퓨터에서 64비트 버전의 Windows Server 2003이 실행되는 경우 라이센스 전용 클러스터 하위 등록을 위한 서비스 검색 항목의 레지스트리 하위 키 경로는 다음과 같습니다.

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0**

다음 표에는 서비스 검색을 재정의하기 위해 추가할 수 있는 항목이 나와 있습니다.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >이름</th>
<th style="border:1px solid black;" >유형</th>
<th style="border:1px solid black;" >값</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">SubEnrollmentURL</td>
<td style="border:1px solid black;">문자열</td>
<td style="border:1px solid black;">http(또는 https)://<em>server_name</em>/_wmcs/certification/subenrollservice.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GicURL</td>
<td style="border:1px solid black;">문자열</td>
<td style="border:1px solid black;">http(또는 https)://<em>server_name</em>/_wmcs/certification/certification.asmx</td>
</tr>
</tbody>
</table>
  
게시를 위한 클라이언트 쪽 서비스 검색 재정의  
--------------------------------------------
  
사용자가 자신의 컴퓨터에서 콘텐츠를 게시하는 경우 회사에 사용되는 토폴로지에 따라 게시에 사용되는 서버의 위치를 재정의할 수 있습니다. 게시에 사용되는 서버의 위치는 일반적으로 클라이언트에서 Active Directory를 사용하여 검색합니다. 클라이언트 컴퓨터에 해당 레지스트리 키를 추가하면 클라이언트는 이러한 방법을 무시하고 레지스트리 항목 값에 지정된 URL을 사용합니다.
  
| ![](images/Cc747614.note(WS.10).gif)참고                                                        |  
|------------------------------------------------------------------------------------------------------------------------------|  
| 이 섹션에 나열된 클라이언트 재정의는 개별 항목이 아닌 키로 생성됩니다. 이러한 키 값은 각 키의 기본 항목에 만들어져야 합니다. |
  
#### 레지스트리 키 설명
  
다음 레지스트리 키는 RMS 클러스터 자동 검색을 재정의하는 데 사용할 수 있습니다.
  
-   **활성화**. 이 레지스트리 키는 시스템 활성화 서비스의 URL을 정의합니다. RMS 클라이언트 서비스 팩 1 이상 버전을 실행하는 경우 이 레지스트리 항목은 더 이상 사용되지 않습니다.  
-   **EnterprisePublishing**. 이 레지스트리 키는 클라이언트가 라이센스 요청에 사용할 RMS 설치 URL을 정의합니다.  
-   **CloudPublishing**. 이 레지스트리 키는 클라이언트에 RMS 설치 권한은 없지만 인터넷 액세스 권한이 있는 경우에 사용할 수 있는 Microsoft 호스팅 라이센스 서비스의 URL을 정의합니다.
  
#### 키 세부 정보
  
게시를 위한 클라이언트 쪽 서비스 검색 항목의 전체 레지스트리 하위 키 경로는 다음과 같습니다.
  
**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\MSDRM\\ServiceLocation\\**
  
다음 표에는 서비스 검색을 재정의하기 위해 RMS 클라이언트 컴퓨터에 추가할 수 있는 레지스트리 키가 나와 있습니다.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >이름</th>
<th style="border:1px solid black;" >유형</th>
<th style="border:1px solid black;" >값</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">활성화</td>
<td style="border:1px solid black;">문자열</td>
<td style="border:1px solid black;">http(또는 https)://<em>RMS_cluster_name</em>/_wmcs/Certification. 여기서 <em>RMS_cluster_name</em>은 RMS 클러스터 이름입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">EnterprisePublishing</td>
<td style="border:1px solid black;">문자열</td>
<td style="border:1px solid black;">http(또는 https)://<em>RMS_cluster_name</em>/_wmcs/Licensing. 여기서 <em>RMS_cluster_name</em>은 RMS 클러스터 이름입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CloudPublishing</td>
<td style="border:1px solid black;">문자열</td>
<td style="border:1px solid black;">http(또는 https)://<em>FQDN_cluster_name</em>/_wmcs/Licensing. 여기서 <em>FQDN_cluster_name</em>은 RMS 클러스터의 정규화된 도메인 이름입니다.</td>
</tr>
</tbody>
</table>
  
이러한 레지스트리 키를 SMS(Systems Management Server) 또는 그룹 정책 중 하나를 사용하여 구현하려면 회사의 모든 클라이언트가 올바른 게시 서버를 사용하는지 확인하는 것이 좋습니다.
  
| ![](images/Cc747614.Caution(WS.10).gif)주의                                                                     |  
|----------------------------------------------------------------------------------------------------------------------------------------------|  
| 레지스트리를 잘못 편집하면 시스템에 심각한 손상을 줄 수 있으므로 레지스트리를 변경하기 전에 컴퓨터의 중요한 데이터를 반드시 백업해야 합니다. |
  
예제 레지스트리 파일(.reg)은 RMS 클러스터에 있는 각 서버에서 적절한 레지스트리 키를 가져오는 데 사용할 수 있습니다.
  
**RMS 클러스터에 있는 각 서버에서 적절한 레지스트리 키를 가져오려면**  
1.  다음 예제 레지스트리 파일을 메모장으로 복사합니다.
  
    `Windows Registry Editor Version 5.00`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation]`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation\Activation]`
  
    `@="http://<RMS_cluster_name>/_wmcs/certification"`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation\EnterprisePublishing]`
  
    `@="http://<RMS_cluster_name>/_wmcs/licensing"`
  
2.  &lt;RMS\_cluster\_name&gt;을 RMS 클러스터 이름으로 바꿉니다.
  
3.  .reg 파일 이름 확장명을 사용하여 파일을 저장합니다.
  
4.  Windows 탐색기에서 파일 이름을 두 번 클릭합니다.
  
5.  **사용자 계정 컨트롤** 대화 상자가 나타나면 대화 상자에서 표시되는 동작이 원하는 동작인지 확인하고 **계속**을 클릭합니다.. 정보를 레지스트리에 추가할지 여부를 묻는 메시지가 나타나면 **예**를 클릭합니다.
