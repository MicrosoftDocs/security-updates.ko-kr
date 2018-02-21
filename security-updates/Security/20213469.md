---
TOCTitle: 'IAS(Internet Authentication Service)'
Title: 'IAS(Internet Authentication Service)'
ms:assetid: '36c9382b-b307-4f03-a4b1-7c0c9c306fff'
ms:contentKeyID: 20213469
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Bb643123(v=MSDN.10)'
---

IAS(Internet Authentication Service)
====================================

RADIUS(Remote Authentication Dial-in User Service)의 Microsoft 구현과 마찬가지로 IAS는 무선 및 VPN(가상 사설망) 연결을 비롯한 다양한 네트워크 액세스 권한을 위한 중앙화된 연결 인증, 권한 부여 및 계정을 수행합니다.여기서는 IAS를 통해 회사 네트워크를 더욱 안전하게 유지하는 방법에 대한 정보를 제공합니다.

##### 이 페이지에서

|                                                                                                                                                                                                            |                                                                                  |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| [<img src="images/bb643123.arrow_px_down(ko-kr,TechNet.10).gif" alt="가이드: Windows Server 2003 인증서 서비스를 사용하여 보안 무선 LAN 계획" width="7" height="9" />](#eaa) | [가이드: Windows Server™ 2003 인증서 서비스를 사용하여 보안 무선 LAN 계획](#eaa) |
| [<img src="images/bb643123.arrow_px_down(ko-kr,TechNet.10).gif" alt="가이드: Windows Server 2003 인증서 서비스를 사용하여 보안 무선 LAN 빌드" width="7" height="9" />](#eyb)  | [가이드: Windows Server 2003 인증서 서비스를 사용하여 보안 무선 LAN 빌드](#eyb)  |
| [<img src="images/bb643123.arrow_px_down(ko-kr,TechNet.10).gif" alt="가이드: Windows Server 2003 인증서 서비스를 사용하여 보안 무선 LAN 작동" width="7" height="9" />](#emc)  | [가이드: Windows Server 2003 인증서 서비스를 사용하여 보안 무선 LAN 작동](#emc)  |
| [<img src="images/bb643123.arrow_px_down(ko-kr,TechNet.10).gif" alt="추가 안내" width="7" height="9" />](#eac)                                                                | [추가 안내](#eac)                                                                |
| [<img src="images/bb643123.arrow_px_down(ko-kr,TechNet.10).gif" alt="검사 목록 " width="7" height="9" />](#efd)                                                               | [검사 목록](#efd)                                                                |

------------------------------------------------------------------------

### 가이드: Windows Server™ 2003 인증서 서비스를 사용하여 보안 무선 LAN 계획

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">무선 LAN 계획 보안 가이드 소개</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">보안 무선 네트워킹 전략 결정</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">보안 무선 LAN 솔루션 아키텍처</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">공개 키 인프라 디자인</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">무선 LAN 보안을 위한 RADIUS 디자인</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">802.1X를 사용하여 무선 LAN 보안 디자인</a></td>
</tr>
</tbody>
</table>
  
------------------------------------------------------------------------
  
### 가이드: Windows Server 2003 인증서 서비스를 사용하여 보안 무선 LAN 빌드

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">무선 LAN 빌드 보안 가이드 소개</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">공개 키 인프라 구현</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">무선 LAN 보안을 위한 RADIUS 인프라 구현</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">802.1X를 사용하여 무선 LAN 보안 구현</a></td>
</tr>
</tbody>
</table>
  
------------------------------------------------------------------------
  
### 가이드: Windows Server 2003 인증서 서비스를 사용하여 보안 무선 LAN 작동

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">무선 LAN 작동 보안 가이드 소개</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">공개 키 인프라 관리</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/prodtech/windowsserver2003/pkiwire/swlan.asp">RADIUS 및 무선 LAN 보안 인프라 관리</a></td>
</tr>
</tbody>
</table>
  
------------------------------------------------------------------------
  
### 추가 안내

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/guidance/secmod125.asp">Windows Server 2003 IAS 서버 강화</a></td>
</tr>
</tbody>
</table>
  
------------------------------------------------------------------------
  
### 검사 목록

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li></li>
</ul></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/korea/technet/security/guidance/secmod217.asp">검사 목록: IAS 서버 백업 및 복구</a></td>
</tr>
</tbody>
</table>
  
[<img src="images/bb643123.arrow_px_up(ko-kr,TechNet.10).gif" alt="페이지 위쪽" width="7" height="9" />](#top) [페이지 위쪽](#top)
