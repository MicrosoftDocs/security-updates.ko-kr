---
TOCTitle: Active Directory 캐시 설정 변경
Title: Active Directory 캐시 설정 변경
ms:assetid: '8789a7a5-2065-4fae-9104-e0a70f1f2fb6'
ms:contentKeyID: 18122957
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc747586(v=WS.10)'
---

Active Directory 캐시 설정 변경
===============================

레지스트리의 설정은 Active Directory 캐시에 저장할 항목 수를 지정합니다. 클라이언트 요청에 대한 응답 시간을 향상시키기 위해 이러한 설정을 수정할 수 있습니다. 자세한 내용은 이 항목 앞부분의 "디렉터리 서비스 성능 최적화"를 참조하십시오. 캐시에 저장되는 정보의 유효 기간을 지정할 수도 있습니다.

32비트 버전 Windows Server 2003을 실행하는 컴퓨터에서 다음 레지스트리 키는 캐시 항목의 전체 하위 키 경로입니다.

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0\\DirectoryServices**

64비트 버전 Windows Server 2003을 실행하는 컴퓨터에서 다음 레지스트리 키는 캐시 항목의 전체 하위 키 경로입니다.

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0\\DirectoryServices**

다음 표는 내부 메모리 캐시 동작을 제어하는 항목을 설명합니다.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >이름</th>
<th style="border:1px solid black;" >형식</th>
<th style="border:1px solid black;" >기본값</th>
<th style="border:1px solid black;" >설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">PrincipalCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">캐시에 저장할 수 있는 최대 사용자, 전자 메일 주소 및 SID 수</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PrincipalCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">사용자에 대해 캐시된 정보의 유효 기간</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupIDCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">캐시에 저장할 수 있는 최대 그룹, 전자 메일 주소 및 SID 수</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupIDCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">그룹 구성원에 대해 캐시된 정보의 유효 기간</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupMembershipCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">캐시에 저장할 수 있는 그룹 구성원의 최대 연락처 수</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupMembershipCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">그룹 구성원의 연락처에 대해 캐시된 정보의 유효 기간</td>
</tr>
</tbody>
</table>
  
> [!Caution]  
> 레지스트리를 잘못 편집하면 시스템이 심하게 손상될 수 있습니다. 레지스트리를 변경하기 전에 컴퓨터에 있는 중요한 데이터를 백업해야 합니다. 
  
> [!Note]  
> **PrincipalCacheExpireMinutes**, **GroupIDCacheExpireMinutes**, **GroupMembershipCacheExpireMinutes** 및 **ContactMembersofGroupCacheExpireMinutes** 레지스트리 항목은 데이터베이스 서버의 디렉터리 서비스 데이터베이스에 저장된 로컬 Active Directory 캐시에 있는 캐시 만료도 제어합니다.
