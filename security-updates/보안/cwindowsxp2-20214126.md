---
TOCTitle: '부록 C: Windows XP 서비스 팩 2 추가 지침'
Title: '부록 C: Windows XP 서비스 팩 2 추가 지침'
ms:assetid: '93bb1c63-1984-4993-862c-5503c5b2410f'
ms:contentKeyID: 20214126
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547971(v=TechNet.10)'
---

Windows XP 보안 가이드
======================

### 부록 C: Windows XP 서비스 팩 2 추가 지침

업데이트 날짜: 2004년 8월 16일

이 부록에서는 Windows XP용 Microsoft Windows XP SP2(서비스 팩 2) 릴리스 보안 가이드에 대한 변경 내용을 설명합니다.

이 부록을 검토하려면 먼저 *Windows XP 보안 가이드* 이전 섹션의 내용을 잘 알고 있어야 합니다. 이 부록에서는 이전 섹션에 대한 보충 정보를 제공하고 SP2에 고유한 구성 변경에 대해서만 설명합니다. 따라서 이 부록을 자체 정보를 포함하는 문서로 생각해서는 안 됩니다.

##### 이 페이지의 내용

[](#efaa)[Windows XP SP2의 개요](#efaa)
[](#eeaa)[보안 설정 변경 내용](#eeaa)
[](#edaa)[관리 템플릿 변경 내용](#edaa)
[](#ecaa)[컴퓨터 구성 설정](#ecaa)
[](#ebaa)[사용자 구성 설정](#ebaa)
[](#eaaa)[요약](#eaaa)

### Windows XP SP2의 개요

Windows XP SP2에는 Windows XP용 최신 업데이트 모음이 들어 있습니다. 이러한 업데이트에는 바이러스 및 웜의 악성 공격으로부터 Windows XP 기반 컴퓨터를 보호해 주는 일련의 보안 기술이 포함되어 있어 운영 체제의 보안을 강화하고 안정성 및 호환성을 향상시킬 수 있습니다. 업데이트에 포함된 기술은 다음과 같습니다.

-   네트워크 보호

-   메모리 보호

-   향상된 전자 메일 보안

-   안전한 검색

-   향상된 컴퓨터 유지 관리

SP2에서는 보안 서비스 관리 효율과 관련된 많은 기능이 향상되었습니다. 이러한 향상된 기능을 사용하여 관리자는 사용자 및 컴퓨터에 특정한 보안 설정을 구현할 수 있습니다.

SP2에서 크게 달라진 점은 기본적으로 보안 기능이 향상되었다는 것입니다. 대부분의 보안 변경 내용이 기본적으로 구현되므로 구성을 변경할 필요가 없습니다. 향상된 기능 중에는 호환성 문제를 일으킬 수 있는 기능이 많지만 전반적인 운영 체제의 향상된 보안을 생각하면 이러한 문제는 크게 중요하지 않습니다.

SP2의 광범위한 변경 내용에 대한 자세한 내용은 "Microsoft Windows XP 서비스 팩 2에서 달라진 기능"(<http://www.microsoft.com/technet/prodtechnol/winxppro/maintain/sp2chngs.mspx>)을 참조하십시오.

[](#mainsection)[페이지 위쪽](#mainsection)

### 보안 설정 변경 내용

Windows XP SP2에서 확장된 정책 및 설정 변경 내용은 주로 그룹 정책의 관리 템플릿에 한정됩니다. 따라서 이 부록에서 제공하는 보안 설정에 대한 권장 변경 내용은 없습니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 관리 템플릿 변경 내용

Windows XP SP 2의 관리 템플릿에는 광범위한 내용이 변경되었습니다. 이 수백 가지의 새로운 설정을 사용하여 관리자의 보안 환경 및 사용자의 상황에 적합한 관리 기능을 구현할 수 있습니다. 이 부록에서는 주로 작업 환경에서 더욱 강력한 보안을 제공할 수 있는 관리 템플릿의 새로운 설정에 대해 자세히 다룹니다.

**참고:** 이 문서를 작성할 당시에는 이 부록에서 설명하는 설정이 Windows XP SP2에만 적용되며, Windows XP 서비스 팩 1 및 이전 운영 체제 버전에는 아무 영향을 주지 않습니다.

#### 새로운 관리 템플릿

관리 템플릿이라고 하는 유니코드 기반 파일에서 추가 보안 설정을 사용할 수 있습니다. 이러한 파일에는 Windows XP 및 해당 구성 요소에 영향을 주는 레지스트리 설정이 들어 있습니다. 새로운 관리 템플릿은 Windows XP SP2에 포함되어 있으며 GPO를 관리하는 경우 Windows XP SP2를 실행하는 컴퓨터를 사용해야 합니다.

이전 버전의 그룹 정책 개체 편집기(Gpedit.exe)에서는 새로운 관리 템플릿을 지원하지 않습니다. 새로운 GPO 또는 기존 GPO를 수정하려면 Windows XP SP2를 실행하는 컴퓨터를 사용해야 합니다. 다른 운영 체제를 사용하여 GPO를 관리하는 방법에 대한 자세한 내용은 Microsoft 기술 자료 문서 842933(<http://support.microsoft.com/?kbid=842933>)을 참조하십시오.

새로운 관리 템플릿의 설정은 Windows XP SP2를 실행하는 컴퓨터에만 적용됩니다. Windows XP SP1 및 이전 운영 체제 버전에서는 새로운 설정을 무시합니다. 따라서 *Windows XP 보안 가이드* 2장에서 설명한 OU 구조로 GPO를 구현하여 작업 환경에서 Windows XP를 실행하는 모든 컴퓨터의 보안을 향상시킬 수 있습니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 컴퓨터 구성 설정

다음 섹션에서는 그룹 정책 개체 편집기의 컴퓨터 구성에 지정된 설정에 대해 설명합니다. 이 설정은 다음 위치에서 구성합니다.

컴퓨터 구성\\관리 템플릿

사용자 환경에서 컴퓨터 계정을 포함하는 OU에 연결된 GPO를 통해 이 설정을 적용합니다. *Windows XP 보안 가이드* 2장에서 설명한 것처럼 GPO의 랩톱 설정은 랩톱 OU에 연결하고 GPO의 데스크톱 설정은 데스크톱 OU에 연결합니다.

#### Internet Explorer

그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.

컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Internet Explorer

##### 크래시 감지 사용 안 함

**표 A.1: 크래시 감지 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**크래시 감지 사용 안 함** 정책 설정을 사용하면 Internet Explorer에서 추가 기능 관리의 크래시 감지 기능을 관리할 수 있습니다. 이 정책 설정을 활성화하면 Internet Explorer가 크래시된 경우 Windows XP Professional 서비스 팩 1 또는 이전 버전에서와 같이 Windows 오류 보고가 시작됩니다. 이 정책 설정을 비활성화하면 추가 기능 관리의 크래시 감지 기능을 사용할 수 있게 됩니다.
  
Internet Explorer 크래시 보고 정보에는 컴퓨터 메모리에서 가져온 중요한 정보가 포함될 수 있으므로 크래시가 자주 반복해서 발생하며 추후 문제 해결을 위해 보고해야 하는 경우가 아닌 이상 이 옵션을 **사용**으로 구성하는 것이 좋습니다. 반면, 크래시가 자주 반복해서 발생하고 추후 문제 해결을 위해 보고해야 하는 경우에는 일시적으로 이 설정을 **사용 안 함**으로 구성할 수 있습니다.
  
##### 사용자가 추가 기능을 사용 또는 사용하지 않도록 허용 안 함
  
**표 A.2: 추가 기능 사용 또는 사용 안 함 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**사용자가 추가 기능을 사용 또는 사용하지 않도록 허용 안 함** 정책 설정을 사용하면 사용자가 추가 기능 관리를 통해 추가 기능 사용을 허용하거나 거부할 수 있는지 관리할 수 있습니다. 이 정책 설정을 **사용**으로 구성하면 사용자가 추가 기능 관리자로 추가 기능을 사용 또는 사용할 수 없도록 설정할 수 없게 됩니다. 사용자가 추가 기능을 관리할 수 있도록 추가 기능이 **추가 기능 목록** 정책 설정에 지정되었으면 예외로 처리됩니다. 이런 경우에는 사용자가 추가 기능 관리자로 추가 기능을 관리할 수 있습니다. 이 정책 설정을 **사용 안 함**으로 구성하면 사용자는 추가 기능을 사용 또는 사용할 수 없도록 설정할 수 있습니다.
  
**참고:** Windows XP SP2에서 Internet Explorer 추가 기능을 관리하는 방법에 대한 자세한 내용은 KB 문서 883256, "Windows XP 서비스 팩 2에서 Internet Explorer 추가 기능을 관리하는 방법"(<http://support.microsoft.com/?kbid=883256>)을 참조하십시오.
  
조직의 보안 정책에서 허용하지 않는 추가 기능을 설치하도록 선택하는 경우가 있습니다. 이러한 추가 기능을 설치하면 네트워크에서 심각한 보안 위험이 초래되고 개인 정보가 노출될 수 있습니다. 따라서 이 정책을 **사용**으로 구성하는 것이 좋습니다.
  
**참고:** Internet Explorer\\보안 기능\\추가 기능 관리의 GPO 설정을 검토하여 허가된 추가 기능 일부는 작업 환경에서 계속 실행될 수 있도록 해야 합니다.
  
##### 인터넷 제어판\\보안 페이지
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Internet Explorer\\인터넷 제어판\\보안 페이지
  
SP2에서는 작업 환경에서 Internet Explorer 영역 구성의 보안을 유지할 수 있는 몇 가지 새로운 정책 설정을 제공합니다. 또한 보안을 향상시키는 이러한 설정을 기본값으로 컴퓨터를 구성합니다. 그러나 사용 편이성 또는 응용 프로그램 호환성을 위해서는 이러한 설정을 검토하여 필요하거나 완화할 정책을 구성할 수 있습니다.
  
예를 들어 SP2에서는 기본적으로 모든 인터넷 영역에 대한 팝업을 차단하도록 Internet Explorer를 구성합니다. 팝업 창을 제거하고 주로 인터넷 웹 사이트에서 생성되는 악의적인 소프트웨어 및 스파이웨어가 설치될 가능성을 줄이기 위해 작업 환경의 모든 컴퓨터에서 이 설정을 적용할 수 있습니다. 반대로 작업 환경에 설치된 특정 응용 프로그램이 실행되기 위해 팝업 창을 사용해야 하는 경우도 있습니다. 이 경우 인트라넷 내의 웹 사이트에 대해 팝업을 허용하도록 이 정책을 구성할 수 있습니다.
  
##### 인터넷 제어판\\고급 페이지
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Internet Explorer\\인터넷 제어판\\고급 페이지
  
###### 소프트웨어의 서명이 올바르지 않더라도 실행 또는 설치하도록 허용
  
**표 A.3: 소프트웨어 실행 허용 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
Microsoft ActiveX 컨트롤 및 파일 다운로드에는 파일의 무결성과 소프트웨어 서명자(작성자)의 신원을 보장하는 디지털 서명이 첨부되어 있는 경우가 많습니다. 이러한 서명은 수정되지 않은 원본 소프트웨어가 다운로드된 것임을 보장하며 서명자를 확인하여 해당 소프트웨어를 실행할 만큼 충분히 신뢰하는 사람인지 결정할 수 있습니다.
  
**소프트웨어의 서명이 올바르지 않더라도 실행 또는 설치하도록 허용** 정책 설정은 서명이 유효하지 않더라도 다운로드한 소프트웨어를 사용자가 설치 또는 실행할 수 있는지 여부를 관리할 수 있습니다. 서명이 유효하지 않으면 누군가가 파일을 무단으로 변경한 것일 수 있습니다. 이 정책 설정을 활성화하면 잘못된 서명을 포함하는 파일을 설치 또는 실행하려고 함을 알려주는 메시지가 표시됩니다. 이 정책 설정을 비활성화하면 잘못된 서명이 포함하는 파일을 실행하거나 설치할 수 없습니다.
  
서명되지 않은 소프트웨어는 보안을 취약하게 만들 수 있으므로 이 설정을 **사용 안 함**으로 구성하여 그러한 소프트웨어를 차단하는 것이 좋습니다.
  
**참고:** 일부 합법적인 소프트웨어 및 컨트롤에 잘못된 서명이 있을 수 있지만 큰 문제는 아닙니다. 이러한 소프트웨어를 조직의 네트워크에서 사용하도록 허용하려면 먼저 별도의 테스트를 거쳐야 합니다.
  
##### 보안 기능\\MK 프로토콜 보안 제한
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Internet Explorer\\보안 기능\\MK 프로토콜 보안 제한
  
###### Internet Explorer 프로세스(MK 프로토콜)
  
**표 A.4: MK 프로토콜 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**MK 프로토콜 보안 제한** 정책 설정은 거의 사용되지 않는 MK 프로토콜을 차단하여 공격 노출 범위를 줄여 줍니다. 오래된 일부 웹 응용 프로그램에서는 MK 프로토콜을 사용하여 압축된 파일에서 정보를 가져옵니다. 이 정책을 **사용**으로 설정하면 Windows 탐색기 및 Internet Explorer에서 MK 프로토콜이 차단되므로 MK 프로토콜을 사용하는 리소스에 오류가 발생합니다. 그러나 이 설정을 비활성화하면 응용 프로그램에서 MK 프로토콜 API를 사용할 수 있습니다.
  
MK 프로토콜이 그리 폭넓게 사용되지는 않으므로 필요하지 않은 경우에는 차단해야 합니다. 작업 환경에서 특별히 필요하지 않는 한 이 설정을 **사용**으로 구성하여 MK 프로토콜을 차단하는 것이 좋습니다.
  
**참고:** 이 설정을 배포할 때 MK 프로토콜을 사용하는 리소스에 오류가 발생하므로 어떤 응용 프로그램에서도 MK 프로토콜이 사용되지 않도록 해야 합니다.
  
##### 보안 기능\\일관성 있는 MIME 핸들링
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Internet Explorer\\보안 기능\\일관성 있는 MIME 핸들링
  
###### Internet Explorer 프로세스(일관성 있는 MIME 핸들링)
  
**표 A.5: 일관성 있는 MIME 핸들링 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
Internet Explorer는 MIME(Multipurpose Internet Mail Extensions) 데이터를 사용하여 웹 서버를 통해 받은 파일의 처리 절차를 결정합니다. **일관성 있는 MIME 핸들링\\Internet Explorer 프로세스** 정책 설정은 웹 서버에서 제공하는 모든 파일 형식 정보가 Internet Explorer에서 일관성을 유지해야 하는지 여부를 결정합니다. 예를 들어 파일의 MIME 형식은 일반 텍스트이지만 MIME 데이터가 해당 파일을 실제로 실행 파일로 지정할 경우 Internet Explorer는 이 실행 파일 상태를 반영하도록 확장명을 변경합니다. 이 기능은 실행 코드가 신뢰할 수 있는 다른 형식의 데이터인 것처럼 가장할 수 없도록 합니다.
  
이 정책 설정을 활성화하면 Internet Explorer에서 수신된 모든 파일을 검토한 후 일관된 MIME 데이터를 적용하고 이 정책 설정을 비활성화하거나 구성하지 않으면 Internet Explorer에서 수신된 모든 파일에 대해 일관된 MIME 데이터를 요구하지 않으며 해당 파일이 제공한 MIME 데이터를 사용합니다.
  
MIME 파일 형식 스푸핑은 조직에 위협이 될 수 있습니다. 이러한 파일이 일관적이며 적절한 레이블이 지정되어 있는지를 확인하면 네트워크에 침투할 수 있는 악의적인 파일의 다운로드를 방지할 수 있습니다. 따라서 이 가이드에 지정된 모든 환경에서 이 정책을 **사용**으로 구성하는 것이 좋습니다.
  
**참고:** 이 설정은 **MIME 검색 안전 기능** 설정과 함께 사용되지만 이 설정을 대신하지는 않습니다.
  
##### 보안 기능\\MIME 검색 안전 기능
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Internet Explorer\\보안 기능\\MIME 검색 안전 기능
  
###### Internet Explorer 프로세스(MIME 검색)
  
**표 A.6: MIME 검색 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
MIME 검색은 MIME 파일이 데이터 파일인지, 실행 파일인지 또는 다른 형식의 파일인지에 상관없이 파일의 내용을 검토하여 해당 컨텍스트를 결정하는 프로세스입니다. 이 정책 설정은 Internet Explorer MIME 검색으로 한 형식의 파일을 더 위험한 파일 형식으로 수준을 올리는 것을 금지할 것인지 결정합니다. 이 정책 설정을 **사용**으로 설정하면MIME 검색으로 인해 한 형식의 파일이 좀 더 위험한 다른 파일 형식으로 수준이 올라갈 수 없습니다. MIME 검색을 비활성화하면 한 형식의 파일을 좀 더 위험한 파일 형식으로 수준을 올리는 MIME 검색을 허용하도록 Internet Explorer 프로세스가 구성됩니다. 예를 들어 텍스트 파일이 실행 파일로 수준이 올라가면 지정된 텍스트 파일의 코드가 실행되므로 위험할 수 있습니다.
  
MIME 파일 형식 스푸핑은 조직에 위협이 될 수 있습니다. 이러한 파일이 일관성 있게 처리되는지를 확인하면 네트워크에 침투할 수 있는 악의적인 파일의 다운로드를 방지할 수 있습니다. 따라서 이 가이드에 지정된 모든 환경에서 이 정책을 **사용**으로 구성하는 것이 좋습니다.
  
**참고:** 이 설정은 **일관성 있는 MIME 핸들링** 설정과 함께 사용되지만 이 설정을 대신하지는 않습니다.
  
##### 보안 기능\\Windows 스크립트 보안 제한
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Internet Explorer\\보안 기능\\Windows 스크립트 보안 제한
  
###### Internet Explorer 프로세스(Window 스크립트 보안 제한)
  
**표 A.7: Window 스크립트 보안 제한 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
Internet Explorer에서는 스크립트가 다양한 유형의 창을 프로그래밍 방식으로 열고 크기를 조정하고 위치를 바꿀 수 있도록 허용합니다. 주로 평판이 좋지 않은 웹 사이트에서 다른 창을 가리거나 악의적인 코드가 들어 있는 창과 강제로 상호 작용이 이루어지도록 창의 크기를 조정합니다.
  
**Window 스크립트 보안 제한** 보안 기능은 팝업 창을 제한하고, 스크립트가 제목 및 상태 표시줄을 사용자에게 표시하지 않거나 다른 창의 제목 및 상태 표시줄을 숨기는 창을 표시하지 못하도록 방지합니다. **Window 스크립트 보안 제한\\Internet Explorer 프로세스** 정책 설정을 활성화하면 팝업 창 및 기타 제한 사항이 Windows 탐색기와 Internet Explorer 프로세스에 적용됩니다. 반면, 이 정책 설정을 비활성화하거나 구성하지 않으면 스크립트가 팝업 창 및 다른 창을 숨기는 창을 계속 만들 수 있습니다.
  
따라서 악의적인 웹 사이트가 Internet Explorer 창을 제어하거나 부주의한 사용자가 잘못된 창을 클릭하는 경우를 방지할 수 있도록 이 설정을 **사용**으로 구성하는 것이 좋습니다.
  
##### 보안 기능\\영역 수준에 따른 보호
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Internet Explorer\\보안 기능\\영역 수준에 따른 보호
  
###### Internet Explorer 프로세스(영역 수준에 따른 보호)
  
**표 A.8: 영역 수준에 따른 보호 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
Internet Explorer에서 열리는 웹 페이지에는 제한 사항이 적용됩니다. 이러한 제한은 웹 페이지의 위치(예: 인터넷 영역, 인트라넷 영역 또는 로컬 컴퓨터 영역)에 따라 다릅니다. 로컬 컴퓨터에 있는 웹 페이지는 로컬 컴퓨터 영역에 있고 최소 보안 제한 사항에 해당하므로 로컬 컴퓨터 보안 영역은 악의적인 공격자의 주된 공격 대상이 됩니다.
  
이 정책 설정을 활성화하면 Internet Explorer 프로세스에서 영역의 수준을 올리지 못하도록 모든 영역을 보호할 수 있습니다. 그러면 한 영역에서 실행되는 콘텐츠가 다른 영역의 수준 높은 권한을 얻지 못합니다. 이 정책 설정을 비활성화하면 어떤 영역도 Internet Explorer 프로세스에 대해 이러한 보호를 받지 못합니다.
  
영역 수준 공격은 심각하고 상대적으로 빈도도 높으므로 모든 환경에서 이 설정을 **사용**으로 구성하는 것이 좋습니다.
  
##### 보안 기능\\ActiveX 설치 제한
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Internet Explorer\\보안 기능\\ActiveX 설치 제한
  
###### Internet Explorer 프로세스(ActiveX 설치 제한)
  
**표 A.9: ActiveX 설치 제한 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
</tr>
</tbody>
</table>
  
**ActiveX 설치 제한\\Internet Explorer 프로세스** 정책 설정을 사용하면 Internet Explorer 프로세스에 대한 ActiveX 컨트롤 설치 확인 메시지를 차단할 수 있습니다.
  
이 정책 설정을 활성화하면 Internet Explorer 프로세스에 대해 ActiveX 컨트롤 설치에 대한 확인 메시지가 차단됩니다. 이 정책 설정을 비활성화하면 ActiveX 컨트롤 설치에 대한 확인 메시지가 차단되지 않습니다.
  
이 경우 사용자는 ActiveX 컨트롤과 같이 회사의 보안 정책에서 허용하지 않는 컨트롤을 설치하도록 선택할 수 있습니다. 이러한 소프트웨어는 네트워크에 심각한 보안 위험을 초래하고 개인 정보를 노출시킬 수 있습니다. 따라서 이 정책을 **사용**으로 구성하는 것이 좋습니다.
  
**참고:** 또한 이 설정은 허가된 ActiveX 컨트롤의 설치를 차단하여 Windows Update와 같은 중요한 시스템 구성 요소를 방해할 수 있습니다. 따라서 이 설정을 활성화할 경우에는 SUS(Software Update Services) 또는 기타 보안 업데이트를 배포하는 대체 방법을 구현해야 합니다.
  
SUS에 대한 자세한 내용은 Software Update Services 페이지(<http://www.microsoft.com/windowsserversystem/sus/default.mspx>)를 참조하십시오. 이 페이지에는 SUS 후속 버전인 Windows Update Services에 대한 내용도 제공되어 있습니다.
  
##### 보안 기능\\파일 다운로드 제한
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Internet Explorer\\보안 기능\\파일 다운로드 제한
  
###### Internet Explorer 프로세스(파일 다운로드 제한)
  
**표 A.10: 파일 다운로드 제한 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
특정 상황에서 웹 사이트에서는 사용자의 상호 작용 없이 파일 다운로드를 확인하는 메시지가 표시될 수 있습니다. 이 기술을 사용하면 사용자가 잘못된 단추를 클릭하여 다운로드를 수락할 경우 사용자의 하드 드라이브에 허가되지 않은 파일이 저장될 수 있도록 합니다.
  
**파일 다운로드 제한\\Internet Explorer 프로세스** 정책 설정을 **사용**으로 구성하면 Internet Explorer 프로세스에 대해 사용자가 시작하지 않은 파일 다운로드 여부를 묻는 메시지가 표시되지 않습니다. 이 정책 설정을 **사용 안 함**으로 구성하면 Internet Explorer 프로세스에 대해 사용자가 시작하지 않은 파일 다운로드 여부를 묻는 메시지가 표시됩니다.
  
**참고**: 공격자가 임의의 코드를 사용자 컴퓨터에 저장하지 못하도록 이 가이드에 지정된 모든 환경에서 이 설정을 **사용**으로 구성하는 것이 좋습니다.
  
##### 보안 기능\\추가 기능 관리
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Internet Explorer\\보안 기능\\추가 기능 관리
  
###### 추가 기능 목록에 지정되지 않은 모든 추가 기능 거부
  
**표 A.11: 지정되지 않은 모든 추가 기능 거부 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
</tr>
</tbody>
</table>
  
이 정책 설정을 **추가 기능 목록** 정책과 함께 사용하면 Internet Explorer 추가 기능을 제어할 수 있습니다. 기본적으로 **추가 기능 목록** 정책 설정은 그룹 정책을 통해 허용 또는 거부할 추가 기능 목록을 정의합니다. **추가 기능 목록에 지정되지 않은 모든 추가 기능 거부** 정책 설정은 **추가 기능 목록** 정책 설정에 구체적으로 나열되지 않은 모든 추가 기능을 거부하는 것으로 간주합니다.
  
이 정책 설정을 활성화하면 Internet Explorer에서 **추가 기능 목록** 정책 설정을 통해 구체적으로 나열(허용)된 추가 기능만 허용합니다. 이 정책 설정을 비활성화하면 사용자는 추가 기능 관리자를 사용하여 추가 기능을 허용하거나 거부할 수 있습니다.
  
작업 환경에 사용될 수 있는 추가 기능을 제어하기 위해서는 **추가 기능 목록에 지정되지 않은 모든 추가 기능 거부** 설정과 **추가 기능 목록** 설정을 모두 사용하는 것이 좋습니다. 이렇게 하면 허가된 추가 기능만 사용될 수 있습니다.
  
###### 추가 기능 목록
  
**표 A.12: 추가 기능 목록 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
</tr>
</tbody>
</table>
  
이 정책 설정을 **추가 기능 목록에 지정되지 않은 모든 추가 기능 거부** 정책과 함께 사용하면 Internet Explorer 추가 기능을 제어할 수 있습니다. 기본적으로 **추가 기능 목록** 정책 설정은 그룹 정책을 통해 허용 또는 거부할 추가 기능 목록을 정의합니다. **추가 기능 목록에 지정되지 않은 모든 추가 기능 거부** 정책 설정은 **추가 기능 목록** 정책 설정에 구체적으로 나열되지 않은 모든 추가 기능을 거부하는 것으로 간주합니다.
  
이 정책 설정을 사용하려면 Internet Explorer에서 허용 또는 거부할 추가 기능 목록을 입력해야 합니다. 목록에 추가해야 하는 각 항목에 대해 다음 정보를 제공해야 합니다.
  
-   **값 이름**. 목록에 추가하려는 추가 기능의 CLSID(클래스 식별자)입니다. CLSID는 {000000000-0000-0000-0000-0000000000000}과 같이 중괄호로 묶어야 합니다. 추가 기능의 CLSID는 추가 기능이 참조된 웹 페이지에서 OBJECT 태그를 읽어 알 수 있습니다.
  
-   **값**. Internet Explorer가 로드될 추가 기능을 거부할지 또는 허용할지 나타내는 숫자입니다. 다음 값을 사용할 수 있습니다.
  
    **표 A.13: 추가 기능 목록 설정 값**

 
    <table style="border:1px solid black;">
    <colgroup>
    <col width="50%" />
    <col width="50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th>값</th>
    <th>설명</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td style="border:1px solid black;">0</td>
    <td style="border:1px solid black;">추가 기능 거부</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;">1</td>
    <td style="border:1px solid black;">추가 기능 허용</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;">2</td>
    <td style="border:1px solid black;">추가 기능을 허용하고 시용자가 추가 기능 관리를 통해 관리하도록 허용</td>
    </tr>
    </tbody>
    </table>
  
이 정책 설정을 비활성화하면 목록이 삭제됩니다.
  
작업 환경에 사용될 수 있는 추가 기능을 제어하기 위해서는 **추가 기능 목록에 지정되지 않은 모든 추가 기능 거부** 설정과 **추가 기능 목록** 설정을 모두 사용하는 것이 좋습니다. 이렇게 하면 허가된 추가 기능만 사용될 수 있습니다.
  
#### 터미널 서비스\\클라이언트
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
관리 템플릿\\Windows 구성 요소\\터미널 서비스\\클라이언트
  
##### 암호를 저장 안 함
  
**표 A.14: 암호를 저장 안 함 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**암호를 저장 안 함** 설정은 암호가 터미널 서비스 클라이언트에 의해 컴퓨터에 저장되지 않도록 합니다. 이 정책 설정을 활성화하면 터미널 서비스 클라이언트의 암호 저장 확인란이 비활성화되어 사용자가 암호를 저장할 수 없게 됩니다. 암호가 저장되면 외부로 누출될 수 있으므로 이 가이드에 정의된 모든 환경에서 이 설정은 **사용**으로 구성됩니다.
  
**참고:** 이 설정이 이전에 **사용 안 함** 또는 **구성되지 않음**으로 구성되면 터미널 서비스 클라이언트와 서버 간의 연결이 처음 끊어질 때 이전에 저장한 암호가 삭제됩니다.
  
#### Windows Update
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
관리 템플릿\\Windows 구성 요소\\Windows Update
  
##### 시스템 종료 대화 상자에 '업데이트 설치 및 시스템 종료' 옵션을 표시하지 않음
  
**표 A.15: 시스템 종료 옵션을 표시하지 않음 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
**시스템 종료 대화 상자에 '업데이트 설치 및 시스템 종료' 옵션을 표시하지 않음** 정책 설정을 사용하면 **업데이트 설치 및 시스템 종료** 옵션을 **시스템 종료** 대화 상자에 표시할지 여부를 관리할 수 있습니다.
  
이 정책 설정을 비활성화하면 사용자가 **시작** 메뉴에서 **시스템 종료** 옵션을 선택하거나 Ctrl+Alt+Delete를 누른 후 표시되는 창에서 **시스템 종료** 단추를 클릭할 때 사용 가능한 업데이트가 있는 경우에만 **시스템 종료** 대화 상자에 **업데이트 설치 및 시스템 종료** 옵션이 표시됩니다. 업데이트 설치는 모든 컴퓨터의 전반적인 보안에 중요하므로 이 가이드에 정의된 모든 환경에서 이 설정은 **사용 안 함**으로 구성됩니다. 이 설정은 다음에 나오는 **Windows 종료 대화 상자의 '업데이트 설치 및 시스템 종료' 기본 옵션을 변경하지 않음** 정책 설정과 함께 사용됩니다.
  
##### Windows 종료 대화 상자의 '업데이트 설치 및 시스템 종료' 기본 옵션을 변경하지 않음
  
**표 A.16: 시스템 종료 기본 옵션을 변경하지 않음 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
**Windows 종료 대화 상자의 '업데이트 설치 및 시스템 종료' 기본 옵션을 변경하지 않음** 정책 설정을 사용하면 **업데이트 설치 및 시스템 종료** 옵션을 **시스템 종료** 대화 상자에 기본 옵션으로 표시할지 여부를 관리할 수 있습니다. 이 정책 설정을 비활성화하면 사용자가 **시작** 메뉴에서 **시스템 종료**를 선택할 때 설치할 수 있는 업데이트가 있는 경우 **업데이트 설치 및 시스템 종료** 옵션이 **시스템 종료** 대화 상자의 기본 옵션이 됩니다.
  
업데이트 설치는 모든 컴퓨터의 전반적인 보안에 중요하므로 이 가이드에 정의된 모든 환경에서 이 설정은 **사용 안 함**으로 구성됩니다.
  
**참고:컴퓨터 구성\\관리 템플릿\\Windows 구성 요소\\Windows Update\\시스템 종료 대화 상자에 '업데이트 설치 및 시스템 종료'옵션을 표시하지 않음**' 정책 설정을 사용하는 경우 이 정책 설정은 아무 효과도 없습니다.
  
#### 시스템
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
컴퓨터 구성\\관리 템플릿\\시스템
  
##### Windows Update 장치 드라이버 검색을 묻지 않음
  
**표 A.17: Windows Update 장치 드라이버 검색 확인 메시지 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**Windows Update 장치 드라이버 검색을 묻지 않음** 설정은 인터넷을 통해 Windows Update에서 장치 드라이버를 검색할지 묻는 메시지의 표시 여부를 제어합니다. 이 설정이 활성화되어 있으면 Windows Update를 검색할지 묻는 메시지가 표시되지 않습니다. 이 설정 및 **Windows Update 장치 드라이버 검색을 묻지 않음**이 사용 안 함 또는 구성되지 않음이면 Windows Update에서 장치 드라이버를 검색하기 전에 동의할지 묻는 메시지가 표시됩니다.
  
인터넷에서 장치 드라이버를 다운로드하면 위험할 수 있으므로 보안 수준이 높은 환경에서는 이 설정을 **사용**으로 구성하고 엔터프라이즈 환경에서는 이 설정을 **사용 안 함**으로 구성하는 것이 좋습니다. 드라이버 다운로드를 이용할 수 있는 공격의 유형은 엔터프라이즈 리소스를 적절히 관리하면 완화시킬 수 있으므로 이러한 권장 사항을 잘 따르도록 합니다.
  
**참고:** 이 설정은 **관리 템플릿/시스템/인터넷 통신 관리/인터넷 통신 설정**의 **Windows Update 장치 드라이버 검색을 묻지 않음**이 사용 안 함 또는 구성되지 않음일 때만 적용됩니다.
  
##### 시스템\\오류 보고
  
*Windows XP 보안 가이드* 4장에서는 몇 가지 오류 보고 구성에 대한 설정을 지정합니다. 이러한 설정은 Windows XP SP2를 실행하는 컴퓨터에 적용되는 것은 동일하지만 설정 중 하나의 이름이 변경되었습니다. 표 4.42에서 설명하는 **오류 보고**는 이제 **오류 보고 구성**으로 표시됩니다. 지정된 설정은 4장에서 설명하는 설정과 같습니다.
  
##### 시스템\\원격 프로시저 호출
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
관리 템플릿\\시스템\\원격 프로시저 호출
  
###### 인증되지 않은 RPC 클라이언트 제한
  
**표 A.18: 인증되지 않은 RPC 클라이언트 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**인증되지 않은 RPC 클라이언트 제한** 설정을 사용하면 RPC 서버의 RPC 런타임이 인증되지 않은 RPC 클라이언트에서 해당 RPC 서버에 연결하는 것을 제한하도록 구성됩니다. 명명된 파이프를 사용하여 서버와 통신하거나 RPC 보안을 사용하는 클라이언트는 인증된 클라이언트로 간주됩니다. 인증되지 않은 클라이언트에서 액세스하도록 특수하게 요청된 RPC 인터페이스는 이 정책의 선택된 값에 따라 이러한 제한에서 제외될 수 있습니다. 이 설정을 사용하도록 구성하는 경우 다음 값을 사용할 수 있습니다.
  
-   **없음**. 이 값은 모든 RPC 클라이언트가 정책이 적용되는 컴퓨터에서 실행되는 RPC 서버에 연결하는 것을 허용합니다.
  
-   **인증됨**. 이 값은 인증된 RPC 클라이언트만 정책이 적용되는 컴퓨터에서 실행되는 RPC 서버에 연결하는 것을 허용합니다. 이 제한에서 제외되도록 요청된 인터페이스에는 예외 권한이 부여됩니다.
  
-   **예외 없이 인증됨**. 이 값은 인증된 RPC 클라이언트만 정책이 적용되는 컴퓨터에서 실행되는 RPC 서버에 연결하는 것을 허용합니다. 예외는 허용되지 않습니다.
  
인증되지 않은 RPC 통신이 이루어지면 보안이 취약해질 수 있으므로 이 가이드에 정의된 모든 환경에서 이 설정을 **사용**으로 구성하고 **인증되지 않은 RPC 런타임 클라이언트 제한 적용** 값은 **인증됨**으로 설정하는 것이 좋습니다.
  
**참고:** 이 구성이 적용되면 요청되지 않은 인바운드 연결 요청을 인증하지 않는 RPC 클라이언트는 제대로 작동하지 않을 수 있습니다. 따라서 이 설정을 배포하기 전에 응용 프로그램을 테스트해야 합니다. 이 설정을 **인증됨**으로 구성한다고 해도 보안이 완전하게 유지되는 것은 아니지만 작업 환경에서 응용 프로그램 호환성을 제공하는 데 도움이 될 수 있습니다.
  
###### RPC 종점 매퍼 클라이언트 인증
  
**표 A.19: 클라이언트 인증 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**RPC 종점 매퍼 클라이언트 인증** 설정을 활성화하면 이 컴퓨터와 통신하는 클라이언트 컴퓨터에서 RPC 통신이 설정되기 전에 인증을 제공해야 합니다.
  
##### 시스템\\인터넷 통신 관리\\인터넷 통신 설정
  
인터넷 통신 설정 그룹에는 몇 가지 구성 설정이 포함되어 있습니다. 컴퓨터 시스템에 있는 데이터의 기밀성을 향상시키기 위해 이러한 설정 대부분을 제한하는 것이 좋습니다. 이런 설정이 제한되지 않으면 공격자가 정보를 가로채 사용할 수 있습니다. 오늘날 이러한 유형의 공격이 실제로 발생하는 경우는 드물지만 이러한 설정을 적절히 구성하면 앞으로의 공격으로부터 환경을 보호하는 데 도움이 됩니다.
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
관리 템플릿\\시스템\\인터넷 통신 관리\\인터넷 통신 설정
  
###### 파일 및 폴더 작업에서 웹에 게시 항목을 사용할 수 없음
  
**표 A.20: 웹에 게시 항목을 사용할 수 없음 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
이 설정은 Windows 폴더의 파일 및 폴더 작업에서 **파일을 웹에 게시**, **폴더를 웹에 게시** 및 **항목을 웹에 게시** 작업을 사용할 수 있는지 여부를 지정합니다. 웹 게시 마법사는 공급자 목록을 다운로드하고 사용자가 콘텐츠를 웹에 게시하도록 도와줍니다. 이 설정을 **사용**으로 구성하면 Windows 폴더의 파일 및 폴더 작업에서 이러한 옵션이 제거됩니다.
  
###### 웹 게시 및 온라인 주문 마법사의 인터넷 다운로드를 사용할 수 없음
  
**표 A.21: 인터넷 다운로드를 사용할 수 없음 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**웹 게시 및 온라인 주문 마법사의 인터넷 다운로드를 사용할 수 없음** 설정은 Windows에서 웹 게시 및 온라인 주문 마법사의 공급자 목록을 다운로드할지를 제어합니다. 이 설정을 활성화하면 Windows에서 공급자를 다운로드할 수 없으며 로컬 레지스트리에 캐시된 서비스 공급자만 표시됩니다.
  
###### Windows Messenger 고객 만족 프로그램 사용 안 함
  
**표 A.22: Windows Messenger 고객 프로그램 사용 안 함 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**Windows Messenger 고객 만족 프로그램 사용 안 함** 설정은 Windows Messenger가 Windows Messenger 소프트웨어 및 서비스 사용 방식에 대한 익명 정보를 수집할 수 있는지를 지정합니다. 이 설정을 **사용**으로 구성하면 Windows Messenger가 사용 정보를 수집하지 않고 사용 정보의 수집을 활성화하는 사용자 설정이 표시되지 않습니다.
  
###### 검색 도우미의 콘텐츠 파일을 업데이트하지 않음
  
**표 A.23: 검색 도우미를 업데이트하지 않음 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**검색 도우미의 콘텐츠 파일을 업데이트하지 않음** 설정은 로컬 및 인터넷 검색 중에 검색 도우미가 콘텐츠 업데이트를 자동으로 다운로드할지를 지정합니다. 이 설정을 **사용**으로 구성하면 검색 도우미가 검색 중에 콘텐츠 업데이트를 다운로드할 수 없습니다.
  
**참고:** 인터넷 검색을 수행할 경우 검색 텍스트 및 검색에 관한 정보가 Microsoft와 검색 서비스 공급자에게 전송됩니다. 이전 버전 검색 기능을 선택하면 검색 도우미 기능을 완전히 사용할 수 없습니다. **시작**, **검색**, **기본 설정 변경**을 차례로 선택한 다음 **인터넷 검색 동작 변경**을 클릭하여 이전 버전 검색을 선택할 수 있습니다.
  
###### HTTP 인쇄 사용 안 함
  
**표 A.24: HTTP 인쇄 사용 안 함 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
이 설정을 사용하면 클라이언트에서 HTTP를 통해 인쇄할 수 없습니다. HTTP 인쇄를 사용하면 클라이언트에서 인트라넷 및 인터넷을 통해 프린터로 인쇄할 수 있습니다. 이 설정을 사용하면 클라이언트에서 HTTP를 통해 인터넷 프린터로 인쇄할 수 없습니다.
  
HTTP를 통해 전송되는 정보는 보호되지 않으므로 악의적인 사용자가 가로챌 수 있습니다. 이러한 이유로 이 설정은 엔터프라이즈 환경 또는 보안 수준이 높은 환경에서는 거의 사용되지 않습니다. 이 기능을 사용하지 않으면 안전하지 않은 인쇄 작업으로 보안을 침해할 수 있는 실수를 방지할 수 있습니다.
  
**참고:** 이 설정은 인터넷 인쇄의 클라이언트쪽에만 영향을 줍니다. 따라서 컴퓨터가 인터넷 인쇄 서버의 역할을 하고 HTTP를 통해 공유 프린터를 사용할 수 있도록 지정하는 것을 방지할 수 없습니다.
  
###### HTTP로 인쇄 드라이버 다운로드 안 함
  
**표 A.25: HTTP로 인쇄 드라이버 다운로드 안 함 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**HTTP로 인쇄 드라이버 다운로드 안 함** 설정은 컴퓨터가 HTTP를 통해 인쇄 드라이버 패키지를 다운로드할 수 있는지를 제어합니다. HTTP 인쇄를 설정하려면 표준 운영 체제 설치에서 사용할 수 없는 프린터 드라이버를 HTTP를 통해 다운로드해야 할 수 있습니다. HTTP를 통해 인쇄 드라이버가 다운로드되지 않도록 하기 위해 이 설정을 **사용**으로 구성하는 것이 좋습니다.
  
**참고:** 이 설정을 사용한다고 해서 클라이언트 컴퓨터가 HTTP를 통해 인트라넷이나 인터넷의 프린터로 인쇄하지 못하는 것은 아니며 아직 로컬로 설치되어 있지 않은 드라이버가 다운로드되지 않을 뿐입니다.
  
###### Windows Update 장치 드라이버 검색 안 함
  
**표 A.26: Windows Update 장치 드라이버 검색 안 함 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**Windows Update 장치 드라이버 검색 안 함** 정책은 장치에 대한 로컬 드라이버가 없을 때 Windows가 Windows Update에서 장치 드라이버를 검색할지를 지정합니다.
  
인터넷에서 장치 드라이버를 다운로드하면 위험할 수 있으므로 보안 수준이 높은 환경에서는 이 설정을 **사용**으로 구성하고 엔터프라이즈 환경에서는 이 설정을 **사용 안 함**으로 구성하는 것이 좋습니다. 드라이버 다운로드를 이용할 수 있는 공격의 유형은 엔터프라이즈 리소스 및 구성을 적절히 관리하면 완화시킬 수 있으므로 이러한 구성이 권장됩니다.
  
**참고:관리 템플릿/시스템**의 **Windows Update 장치 드라이버 검색을 묻지 않음** 설정을 참조하십시오. 이 정책 설정은 장치 드라이버를 로컬로 찾을 수 없을 때 Windows Update에서 검색할지 묻는 확인 메시지를 표시할지를 제어합니다.
  
#### Windows 방화벽\\도메인 프로필
  
이 섹션의 설정은 Windows 방화벽 도메인 프로필을 구성합니다. Windows 방화벽은 컴퓨터가 도메인 환경에 있는지 여부를 동적으로 결정하고, 이러한 결정을 바탕으로 특정 방화벽 구성을 적용할 수 있습니다. 이 기능을 사용하면 컴퓨터 위치에 따라 별도의 방화벽 설정을 배포할 수 있습니다.
  
도메인 환경이 감지되면 도메인 프로필이 사용됩니다. 일반적으로 도메인 환경이 추가적인 보호 계층을 제공하므로 도메인 프로필은 표준 프로필보다 덜 제한적으로 구성할 수 있습니다. 표준 프로필 구성은 이 부록의 뒷부분에서 설명합니다.
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
관리 템플릿\\네트워크\\네트워크 연결\\Windows 방화벽\\도메인 프로필
  
##### Windows 방화벽: 모든 네트워크 연결을 보호(도메인 프로필)
  
**표 A.27: 모든 네트워크 연결을 보호(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: 모든 네트워크 연결을 보호** 설정을 사용하면 Windows XP SP2를 실행하는 모든 컴퓨터에서 인터넷 연결 방화벽 대신 Windows 방화벽을 사용할 수 있습니다. 모든 환경의 컴퓨터에서 모든 네트워크 연결을 보호하도록 이 설정을 **사용**으로 구성하는 것이 좋습니다.
  
이 설정을 **사용 안 함**으로 구성하면 Windows 방화벽이 해제되고 Windows 방화벽에 대한 설정은 모두 무시됩니다.
  
**참고:** 이 정책 설정을 활성화하면 Windows 방화벽이 실행되며 **컴퓨터 구성\\관리 템플릿\\네트워크\\네트워크 연결\\사용자의 DNS 도메인 네트워크에서 인터넷 연결 방화벽의 사용을 금지** 정책 설정은 무시됩니다.
  
##### Windows 방화벽: 예외 허용 안 함(도메인 프로필)
  
**표 A.28: 예외 허용 안 함(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: 예외 허용 안 함** 설정은 Windows 방화벽이 요청되지 않은 들어오는 모든 메시지를 차단하도록 지정합니다. 이 정책 설정은 이러한 메시지를 허용하는 다른 모든 Windows 방화벽 설정보다 우선적으로 적용됩니다. 제어판의 Windows 방화벽 구성 요소에서 이 정책 설정을 활성화하면 **예외 허용 안 함** 확인란이 선택되며 관리자는 선택을 취소할 수 없습니다.
  
많은 작업 환경에는 정상적인 작동 중에 요청되지 않은 인바운드 통신의 수신을 허용해야 하는 응용 프로그램 및 서비스가 포함되어 있습니다. 이 경우 그러한 응용 프로그램 및 서비스가 제대로 실행되도록 이 정책을 **사용 안 함**으로 구성해야 할 수도 있습니다. 그러나 이 정책을 변경하려면 먼저 작업 환경을 테스트하여 허용할 항목과 허용하지 않을 항목을 정확히 결정해야 합니다.
  
**참고**: 이 설정은 외부 공격자를 막는 강력한 방어 장치를 제공하므로 새로운 발생한 네트워크 웜과 같은 외부 공격으로부터 완전히 보호해야 하는 경우에는 이 정책을 **사용**으로 설정해야 합니다. 이 정책 설정을 **사용 안 함**으로 설정하면 Windows 방화벽에서 요청되지 않은 들어오는 메시지를 허용하는 다른 정책 설정을 적용할 수 있습니다.
  
##### Windows 방화벽: 예외 프로그램 정의(도메인 프로필)
  
**표 A.29: 예외 프로그램 정의(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
</tr>
</tbody>
</table>
  
일부 응용 프로그램에서는 Windows 방화벽이 일반적으로 허용하지 않는 네트워크 포트를 열어 사용해야 할 수 있습니다. **Windows 방화벽: 예외 프로그램 정의** 설정은 그룹 정책에 정의된 예외 프로그램 목록을 보고 변경할 수 있도록 합니다.
  
이 정책을 **사용**으로 설정하면 예외 프로그램 목록을 보고 변경할 수 있습니다. 이 목록에 프로그램을 추가하고 해당 상태를 **사용**으로 설정하면 해당 프로그램은 Windows 방화벽에 열도록 요청한 어떠한 포트에서도 요청되지 않은 들어오는 메시지를 수신할 수 있습니다. 해당 포트가 다른 정책 설정에 의해 차단되었는지 여부는 관계가 없습니다.
  
이 정책 설정을 **사용 안 함**으로 구성하면 그룹 정책에 정의된 예외 프로그램 목록이 삭제됩니다.
  
**참고:** 잘못된 정의 문자열을 입력해도 Windows 방화벽은 오류를 검사하지 않고 목록에 그냥 추가합니다. 이와 같이 항목이 검사되지 않으므로 아직 설치되지 않은 프로그램을 추가할 수 있습니다. 또한 서로 충돌하는 범위 또는 상태 값을 지정하여 동일한 프로그램에 대해 여러 예외를 만들 수도 있습니다.
  
##### Windows 방화벽: 예외 로컬 프로그램 허용(도메인 프로필)
  
**표 A.30: 예외 로컬 프로그램 허용(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: 예외 로컬 프로그램 허용** 설정을 사용하면 관리자가 제어판의 Windows 방화벽 구성 요소를 사용하여 예외 로컬 프로그램 목록을 정의할 수 있습니다. 이 정책 설정을 비활성화하면 관리자가 예외 로컬 프로그램 목록을 정의할 수 없으며 그룹 정책에서 가져온 예외 프로그램을 그대로 사용해야 합니다. 이 정책을 **사용**으로 설정하면 로컬 관리자가 제어판을 사용하여 예외 프로그램을 로컬로 정의할 수 있습니다.
  
엔터프라이즈 클라이언트 컴퓨터에서는 클라이언트가 예외 로컬 프로그램을 정의하는 것을 한정하는 조건이 있을 수 있습니다. 이러한 조건에는 조직의 방화벽 정책을 만들 때 분석되지 않은 응용 프로그램이나 비표준 포트 구성을 필요로 하는 새로운 응용 프로그램 등이 포함될 수 있습니다. 이 경우 이 설정을 사용하도록 선택하면 영향 받은 컴퓨터의 공격 노출 범위가 증가할 수 있습니다.
  
##### Windows 방화벽: 원격 관리 허용(도메인 프로필)
  
**표 A.31: 원격 관리 허용(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
많은 조직에서는 일상적인 작업에서 원격 컴퓨터 관리를 활용합니다. 그러나 원격 관리 프로그램에 주로 사용되는 포트가 공격에 이용될 수 있으므로 Windows 방화벽은 이러한 포트를 차단할 수 있습니다. 보다 유연한 원격 관리를 위해 **Windows 방화벽: 원격 관리 허용** 설정을 사용할 수 있습니다.
  
이 설정을 **사용**으로 구성하면 컴퓨터가 TCP 포트 135 및 445에서 원격 관리와 연관된 요청되지 않은 들어오는 메시지를 수신할 수 있습니다. 또한 이 정책 설정을 사용하면 SVCHOST.EXE 및 LSASS.EXE에서 요청되지 않은 들어오는 메시지를 수신할 수 있고 호스팅된 서비스가 동적으로 할당된 추가 포트를 열 수 있습니다. 이 포트의 범위는 일반적으로 1024부터 1034까지이나 1024부터 65535까지의 어떤 번호도 될 수 있습니다. 이 설정을 활성화할 경우 이러한 들어오는 메시지가 허용되는 IP 주소 또는 서브넷을 지정해야 합니다.
  
이 정책 설정을 **사용 안 함**으로 구성하면 Windows 방화벽이 설명된 어떠한 예외도 만들지 않습니다.
  
엔터프라이즈 환경에서는 필요한 경우 이 설정을 사용하고, 보안 수준이 높은 작업 환경에서는 항상 사용하지 않는 것이 좋습니다. 작업 환경의 컴퓨터는 최대한 적은 수의 컴퓨터로부터 원격 관리 요청을 수락해야 합니다. Windows 방화벽에 의한 보호를 최대화하려면 원격 관리에 사용되는 컴퓨터의 필요한 IP 주소 및 서브넷만 지정하도록 합니다.
  
**참고:** 만일 어떠한 정책 설정이 TCP 포트 445를 열면 **Windows 방화벽: ICMP 허용** 정책 설정이 수신 ICMP 에코 요청 메시지(예: PING 유틸리티가 전송하는 메시지)를 차단하려고 해도 Windows 방화벽은 해당 메시지를 허용합니다. TCP 포트 445를 열 수 있는 정책 설정에는 **Windows 방화벽: 파일 및 프린터 공유 허용**, **Windows 방화벽: 원격 관리 허용** 및 **Windows 방화벽: 예외 포트 정의**가 포함됩니다.
  
##### Windows 방화벽: 파일 및 프린터 공유 허용(도메인 프로필)
  
**표 A.32: 파일 및 프린터 공유 허용(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
이 설정은 UDP 포트 137 및 138과 TCP 포트 139 및 445를 열도록 Windows 방화벽을 구성하여 파일 및 프린터 공유를 허용합니다. 이 정책 설정을 활성화하면 Windows 방화벽에서 이러한 포트를 열고 컴퓨터가 인쇄 작업 및 공유 파일 액세스 요청을 받을 수 있습니다. 이러한 들어오는 메시지를 허용하는 IP 주소 또는 서브넷을 지정해야 합니다.
  
이 정책 설정을 비활성화하면 Windows 방화벽이 해당 포트를 닫아 컴퓨터에서 파일 및 프린터를 공유하지 못하도록 합니다.
  
Windows XP를 실행하는 컴퓨터는 일반적으로 파일 및 프린터를 공유하지 않으므로 모든 환경에서 이 설정을 **사용 안 함**으로 구성하는 것이 좋습니다.
  
**참고:** 만일 어떠한 정책 설정이 TCP 포트 445를 열면 **Windows 방화벽: ICMP 허용** 정책 설정이 수신 ICMP 에코 요청 메시지(예: PING 유틸리티가 전송하는 메시지)를 차단하려고 해도 Windows 방화벽은 해당 메시지를 허용합니다. TCP 포트 445를 열 수 있는 정책 설정에는 **Windows 방화벽: 파일 및 프린터 공유 허용**, **Windows 방화벽: 원격 관리 허용** 및 **Windows 방화벽: 예외 포트 정의**가 포함됩니다.
  
##### Windows 방화벽: ICMP 허용(도메인 프로필)
  
**표 A.33: ICMP 허용(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: ICMP 허용** 설정은 Windows 방화벽이 허용하는 ICMP(Internet Control Message Protocol) 메시지 유형 모음을 정의합니다. 유틸리티에서는 ICMP 메시지를 사용하여 다른 컴퓨터의 상태를 확인할 수 있습니다. 예를 들어 PING은 에코 요청 메시지를 사용합니다.
  
이 정책 설정을 **사용**으로 설정하는 경우에는 Windows 방화벽이 해당 컴퓨터에서 주고받을 수 있도록 허용하는 ICMP 메시지 유형을 지정해야 합니다. 이 정책을 **사용 안 함**으로 구성하면 Windows 방화벽이 요청되지 않은 모든 들어오는 ICMP 메시지 유형과 나열된 나가는 ICMP 메시지 유형을 차단합니다. 따라서 차단된 ICMP 메시지를 사용하는 유틸리티에서 컴퓨터와 메시지를 주고받을 수 없게 됩니다.
  
많은 공격자 도구는 ICMP 메시지 유형을 받아들이는 컴퓨터를 이용하며 이러한 메시지를 사용하여 다양한 공격을 수행합니다. 그러나 일부 응용 프로그램은 제대로 작동하기 위해 특정 ICMP 메시지를 요구합니다. 이러한 이유로 가능하면 이 설정을 **사용 안 함**으로 구성하는 것이 좋습니다. 작업 중에 일부 ICMP 메시지가 Windows 방화벽을 통과해야 할 경우 적절한 메시지 유형을 지정하여 이 설정을 구성해야 합니다.
  
**참고:** 만일 어떠한 정책 설정이 TCP 포트 445를 열면 **Windows 방화벽: ICMP 허용** 정책 설정이 수신 ICMP 에코 요청 메시지(예: PING 유틸리티가 전송하는 메시지)를 차단하려고 해도 Windows 방화벽은 해당 메시지를 허용합니다. TCP 포트 445를 열 수 있는 정책 설정에는 **Windows 방화벽: 파일 및 프린터 공유 허용**, **Windows 방화벽: 원격 관리 허용** 및 **Windows 방화벽: 예외 포트 정의**가 포함됩니다.
  
##### Windows 방화벽: 원격 데스크톱 허용(도메인 프로필)
  
**표 A.34: 원격 데스크톱 허용(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
</tr>
</tbody>
</table>
  
많은 조직에서는 정상적인 문제 해결 절차나 작업에서 원격 데스크톱 연결을 사용합니다. 그러나 원격 데스크톱에서 주로 사용되는 포트가 공격에 이용될 수 있습니다. 보다 유연한 원격 관리를 위해 **Windows 방화벽: 원격 데스크톱 허용** 설정을 사용할 수 있습니다.
  
이 설정을 활성화하면 Windows 방화벽에서 인바운드 연결을 위해 TCP 포트 3389를 열도록 구성됩니다. 또한 이러한 들어오는 메시지를 허용하는 IP 주소 또는 서브넷을 지정해야 합니다.
  
이 정책 설정을 비활성화하면 Windows 방화벽은 해당 포트를 차단하고 컴퓨터가 원격 데스크톱 요청을 받아들일 수 없도록 합니다. 즉, 관리자가 예외 로컬 포트 목록에 이 포트를 추가하여 열려고 시도하면 Windows 방화벽에서 포트를 열지 않습니다.
  
열린 포트 3389는 일부 공격에 이용될 수 있으므로 원격 데스크톱이 제공하는 고급 관리 기능을 유지하려면 이 설정을 **사용**으로 구성하고 원격 관리에 사용되는 컴퓨터의 IP 주소 및 서브넷을 지정해야 합니다. 작업 환경의 컴퓨터에서는 최대한 작은 수의 컴퓨터로부터 원격 데스크톱 요청을 수락해야 합니다.
  
##### Windows 방화벽: UPnP 프레임워크 허용(도메인 프로필)
  
**표 A.35: UPnP 프레임워크 허용(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: UPnP 프레임워크 허용** 설정을 사용하면 컴퓨터가 기본 제공 방화벽이 있는 라우터 등의 네트워크 장치에서 전송하는 요청하지 않은 플러그 앤 플레이 메시지를 수신할 수 있습니다. 이러한 메시지를 수신하기 위해 Windows 방화벽은 TCP 포트 2869 및 UDP 포트 1900을 엽니다.
  
이 설정을 활성화하면 Windows 방화벽이 해당 포트를 열어 컴퓨터가 플러그 앤 플레이 메시지를 수신할 수 있습니다. 이러한 들어오는 메시지를 허용하는 IP 주소 또는 서브넷을 지정해야 합니다. 이 정책 설정을 비활성화하면 Windows 방화벽은 해당 포트를 닫아 컴퓨터가 플러그 앤 플레이 메시지를 수신하지 못하도록 합니다.
  
UPnP 네트워크 트래픽을 효과적으로 차단하면 작업 환경의 컴퓨터가 공격에 노출될 가능성이 줄어듭니다. 따라서 네트워크에서 UPnP 장치를 사용하지 않는 한 이 설정을 **사용 안 함**으로 구성하는 것이 좋습니다.
  
##### Windows 방화벽: 알림 금지(도메인 프로필)
  
**표 A.36: 알림 금지(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
</tr>
</tbody>
</table>
  
Windows 방화벽은 특정 프로그램이 예외 프로그램 목록에 프로그램을 추가하도록 요청할 때 알림을 표시할 수 있습니다. 프로그램이 포트를 열려고 하지만 현재의 Windows 방화벽 규칙 때문에 열 수 없을 때 이러한 상황이 발생합니다. **Windows 방화벽: 알림 금지** 설정은 이러한 설정이 사용자에게 표시될지를 결정합니다.
  
이 정책을 **사용**으로 구성하면 Windows 방화벽에서 이러한 알림이 표시되지 않도록 하고 **사용 안 함**으로 설정하면 이러한 알림이 표시되도록 허용합니다.
  
일반적으로 엔터프라이즈 환경 또는 보안 수준이 높은 작업 환경에서는 사용자가 이러한 메시지에 응답하여 응용 프로그램 및 포트를 추가할 수 없습니다. 이 경우 해당 메시지는 사용자가 제어할 수 없는 기능을 사용하려고 한다는 사실을 알려 줍니다. 따라서 이러한 경우에는 이 옵션을 **사용**으로 구성하고, 사용자가 예외를 허용하도록 구성된 다른 환경에서는 이 옵션을 **사용 안 함**으로 구성해야 합니다.
  
##### Windows 방화벽: 멀티캐스트 또는 브로드캐스트 요청에 대한 유니캐스트 응답을 금지(도메인 프로필)
  
**표 A.37: 유니캐스트 응답 금지(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: 멀티캐스트 또는 브로드캐스트 요청에 대한 유니캐스트 응답을 금지** 설정은 컴퓨터가 나가는 멀티캐스트 또는 브로드캐스트 메시지에 대한 유니캐스트 응답을 수신하는 것을 방지합니다. 이 정책을 활성화한 상태에서 컴퓨터가 멀티캐스트 또는 브로드캐스트 메시지를 다른 컴퓨터로 전송하면 Windows 방화벽은 다른 컴퓨터에서 보낸 유니캐스트 응답을 차단합니다. 이 설정을 비활성화한 상태에서 이 컴퓨터가 멀티캐스트 또는 브로드캐스트 메시지를 다른 컴퓨터로 전송하면 Windows 방화벽은 최대 3초까지 다른 컴퓨터의 유니캐스트 응답을 기다렸다가 그 이후의 모든 응답을 차단합니다.
  
일반적으로는 멀티캐스트 또는 브로드캐스트 메시지에 대한 유니캐스트 응답을 수신하지 않으려 할 수 있습니다. 이러한 응답은 DoS(서비스 거부) 공격이나 알려진 컴퓨터를 검색하려는 시도일 수 있습니다. 이 유형의 공격을 방지하기 위해 이 정책 설정을 **사용**으로 구성하는 것이 좋습니다.
  
**참고:** 유니캐스트 메시지가 이 컴퓨터에서 보낸 DHCP(Dynamic Host Configuration Protocol) 브로드캐스트 메시지에 대한 응답일 경우 이 정책 설정은 적용되지 않습니다. Windows 방화벽은 항상 해당 DHCP 유니캐스트 응답을 허용합니다. 그러나 이 정책 설정은 이름 충돌을 감지하는 NetBIOS 메시지를 방해할 수 있습니다.
  
##### Windows 방화벽: 예외 포트 정의(도메인 프로필)
  
**표 A.38: 예외 포트 정의(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
</tr>
</tbody>
</table>
  
Windows 방화벽 예외 포트 목록은 그룹 정책을 통해 정의되며 사용자가 중앙에서 예외 포트를 관리 및 배포할 수 있고 로컬 관리자가 보안이 약한 설정을 만들 수 없습니다. **Windows 방화벽: 예외 포트 정의** 정책 설정을 사용하면 이러한 설정을 중앙에서 관리할 수 있습니다.
  
이 정책 설정을 활성화하면 그룹 정책에 정의된 예외 포트 목록을 보고 변경할 수 있습니다. 예외 포트 목록을 보고 수정하려면 해당 정책 설정을 **사용**으로 설정한 후 **표시** 단추를 클릭합니다. 잘못된 정의 문자열을 입력해도 Windows 방화벽은 오류를 검사하지 않고 목록에 그냥 추가합니다. 따라서 서로 충돌하는 범위 또는 상태 값을 지정하여 동일한 포트에 대해 여러 항목을 만들 수도 있습니다.
  
이 정책 설정을 비활성화하면 그룹 정책에 정의된 예외 포트 목록은 삭제되지만 다른 설정으로 포트를 계속 열거나 차단할 수 있습니다. 또한 예외 로컬 포트 목록이 있어도 **Windows 방화벽: 예외 로컬 포트 허용** 정책 설정을 활성화하지 않으면 무시됩니다.
  
특정 포트를 열도록 요구하는 비표준 응용 프로그램이 설치된 환경에서는 예외 프로그램 배포를 고려해야 합니다. 이 설정을 사용으로 구성하고 예외 프로그램을 정의할 수 없을 때만 예외 포트 목록을 지정하는 것이 좋습니다. 예외 프로그램은 지정된 프로그램이 실행되는 동안에만 Windows 방화벽이 요청되지 않은 네트워크 트래픽을 수락할 수 있으며 예외 포트는 지정된 포트를 항상 열어 둡니다.
  
**참고:** 만일 어떠한 정책 설정이 TCP 포트 445를 열면 **Windows 방화벽: ICMP 허용** 정책 설정이 수신 ICMP 에코 요청 메시지(예: PING 유틸리티가 전송하는 메시지)를 차단하려고 해도 Windows 방화벽은 해당 메시지를 허용합니다. TCP 포트 445를 열 수 있는 정책 설정에는 **Windows 방화벽: 파일 및 프린터 공유 허용**, **Windows 방화벽: 원격 관리 허용** 및 **Windows 방화벽: 예외 포트 정의**가 포함됩니다.
  
##### Windows 방화벽: 예외 로컬 포트 허용(도메인 프로필)
  
**표 A.39: 예외 로컬 포트 허용(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: 예외 로컬 포트 허용** 설정을 사용하면 관리자가 제어판의 Windows 방화벽 구성 요소를 사용하여 예외 로컬 포트 목록을 정의할 수 있습니다. Windows 방화벽에서는 두 개의 예외 포트 목록을 사용할 수 있습니다. 나머지 한 목록은 **Windows 방화벽: 예외 포트 정의** 정책 설정을 통해 정의됩니다.
  
이 정책 설정을 활성화하면 관리자가 제어판의 Windows 방화벽 구성 요소에서 예외 로컬 포트 목록을 정의할 수 있습니다. 이 정책 설정을 비활성화하면 제어판의 Windows 방화벽 구성 요소에서 이러한 목록을 정의할 수 없습니다.
  
일반적으로 엔터프라이즈 환경 또는 보안 수준이 높은 작업 환경에서 로컬 관리자는 조직 정책을 재정의하고 자체의 예외 포트 목록을 설정할 수 있는 권한이 없습니다. 이러한 이유로 이 옵션을 **사용 안 함**으로 구성하는 것이 좋습니다.
  
#### Windows 방화벽\\표준 프로필
  
이 섹션의 설정은 Windows 방화벽 표준 프로필을 구성합니다. Windows 방화벽은 컴퓨터가 도메인 환경에 있는지 여부를 동적으로 결정하고, 이러한 결정을 바탕으로 특정 방화벽 구성을 적용할 수 있습니다. 이 기능을 사용하면 컴퓨터 위치에 따라 별도의 방화벽 설정을 배포할 수 있습니다.
  
도메인이 아닌 환경이 감지되면 표준 프로필이 사용됩니다. 도메인 환경이 기본 수준의 보안을 제공한다고 가정할 경우 일반적으로 이 프로필이 도메인 프로필보다 좀 더 제한적입니다. 표준 프로필은 컴퓨터가 호텔 네트워크나 공용 무선 액세스 지점과 같은 신뢰할 수 없는 네트워크에 연결되어 있을 때 주로 사용됩니다. 이러한 환경에서는 알 수 없는 보안 위협이 발생할 수 있으므로 추가적인 보안 조치가 필요합니다.
  
Windows XP에서 NLA(Network Location Awareness)를 사용하여 연결된 네트워크 종류를 확인하는 방법에 대한 자세한 내용은 "[네트워크 관련 그룹 정책 설정에 대한 네트워크 결정 동작](http://www.microsoft.com/technet/community/columns/cableguy/cg0504.mspx)"(http://www.microsoft.com/technet/community/columns/cableguy/cg0504.mspx)을 참조하십시오.
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
관리 템플릿\\네트워크\\네트워크 연결\\Windows 방화벽\\표준 프로필
  
##### Windows 방화벽: 모든 네트워크 연결을 보호(표준 프로필)
  
**표 A.40: 모든 네트워크 연결을 보호(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: 모든 네트워크 연결을 보호** 설정을 사용하면 Windows XP SP2를 실행하는 모든 컴퓨터에서 인터넷 연결 방화벽 대신 Windows 방화벽을 사용할 수 있습니다. 모든 네트워크 연결은 모든 환경에서 방화벽으로 보호해야 하므로 이 설정은 **사용**으로 구성됩니다.
  
이 설정을 **사용 안 함**으로 구성하면 Windows 방화벽이 해제되고 Windows 방화벽에 대한 설정은 모두 무시됩니다.
  
**참고:** 이 정책 설정을 활성화하면 Windows 방화벽이 실행되며 **컴퓨터 구성\\관리 템플릿\\네트워크\\네트워크 연결\\사용자의 DNS 도메인 네트워크에서 인터넷 연결 방화벽의 사용을 금지** 정책 설정은 무시됩니다.
  
##### Windows 방화벽: 예외 허용 안 함(표준 프로필)
  
**표 A.41: 예외 허용 안 함(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: 예외 허용 안 함** 설정은 Windows 방화벽이 요청되지 않은 들어오는 모든 메시지를 차단하도록 지정합니다. 이 정책 설정은 이러한 메시지를 허용하는 다른 모든 Windows 방화벽 설정보다 우선적으로 적용됩니다. 제어판의 Windows 방화벽 구성 요소에서 이 정책 설정을 활성화하면 **예외 허용 안 함** 확인란이 선택되며 관리자는 선택을 취소할 수 없습니다.
  
**참고:** 이 설정은 외부 공격자를 막는 강력한 방어 장치이므로 다른 정책 설정에서 예외를 만들지 않는 한 **사용**으로 설정해야 합니다. 이 정책 설정을 **사용 안 함**으로 설정하면 Windows 방화벽에서 요청되지 않은 들어오는 메시지를 허용하는 다른 정책 설정을 적용할 수 있습니다.
  
##### Windows 방화벽: 예외 프로그램 정의(표준 프로필)
  
**표 A.42: 예외 프로그램 정의(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
<td style="border:1px solid black;">권장</td>
</tr>
</tbody>
</table>
  
일부 응용 프로그램에서는 Windows 방화벽이 일반적으로 허용하지 않는 네트워크 포트를 열어 사용해야 할 수 있습니다. **Windows 방화벽: 예외 프로그램 정의** 설정은 그룹 정책에 정의된 예외 프로그램 목록을 보고 변경할 수 있도록 합니다.
  
이 정책을 **사용**으로 설정하면 예외 프로그램 목록을 보고 변경할 수 있습니다. 이 목록에 프로그램을 추가하고 해당 상태를 **사용**으로 설정하면 해당 프로그램은 Windows 방화벽에 열도록 요청한 어떠한 포트에서도 요청되지 않은 들어오는 메시지를 수신할 수 있습니다. 해당 포트가 다른 정책 설정에 의해 차단되었는지 여부는 관계가 없습니다.
  
이 정책 설정을 **사용 안 함**으로 구성하면 그룹 정책에 정의된 예외 프로그램 목록이 삭제됩니다.
  
**참고:** 잘못된 정의 문자열을 입력해도 Windows 방화벽은 오류를 검사하지 않고 목록에 그냥 추가합니다. 이 기능을 사용하면 아직 설치하지 않은 프로그램을 추가할 수 있지만 서로 충돌하는 범위 또는 상태 값을 지정하여 동일한 프로그램에 대해 여러 항목을 만들 수도 있습니다.
  
##### Windows 방화벽: 예외 로컬 프로그램 허용(표준 프로필)
  
**표 A.43: 예외 로컬 프로그램 허용(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: 예외 로컬 프로그램 허용** 설정을 사용하면 관리자가 제어판의 Windows 방화벽 구성 요소를 사용하여 예외 로컬 프로그램 목록을 정의할 수 있습니다. 이 정책 설정을 비활성화하면 제어판의 Windows 방화벽 구성 요소에서 이러한 목록을 정의할 수 없으며 그룹 정책에서 가져온 예외 프로그램을 그대로 사용해야 합니다. 이 정책을 **사용**으로 설정하면 로컬 관리자가 제어판을 사용하여 예외 프로그램을 로컬로 정의할 수 있습니다.
  
##### Windows 방화벽: 원격 관리 허용(표준 프로필)
  
**표 A.44: 원격 관리 허용(도메인 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
많은 조직에서는 일상적인 작업에서 원격 컴퓨터 관리를 활용합니다. 그러나 원격 관리 프로그램에서 주로 사용되는 포트가 공격에 이용될 수 있습니다. 이러한 공격에 대비하여 Windows 방화벽에서는 이러한 포트를 차단할 수 있습니다. 보다 유연한 원격 관리를 위해 **Windows 방화벽: 원격 관리 허용** 설정을 사용할 수 있습니다.
  
이 설정을 **사용**으로 구성하면 컴퓨터가 TCP 포트 135 및 445에서 원격 관리와 연관된 요청되지 않은 들어오는 메시지를 수신할 수 있습니다. 또한 이 정책 설정을 사용하면 SVCHOST.EXE 및 LSASS.EXE에서 요청되지 않은 들어오는 메시지를 수신할 수 있고 호스팅된 서비스가 동적으로 할당된 추가 포트를 열 수 있습니다. 이 포트의 범위는 일반적으로 1024부터 1034까지이나 1024부터 65535까지의 어떤 번호도 될 수 있습니다. 이 설정을 활성화할 경우 이러한 들어오는 메시지가 허용되는 IP 주소 또는 서브넷을 지정해야 합니다.
  
이 정책 설정을 **사용 안 함**으로 구성하면 Windows 방화벽이 설명된 어떠한 예외도 만들지 않습니다.
  
따라서 표준 프로필의 모든 컴퓨터에서 이 설정을 사용 안 함으로 구성하여 특히 TCP 포트 135 및 445를 이용하는 알려진 공격을 방지할 수 있습니다.
  
**참고:** 만일 어떠한 정책 설정이 TCP 포트 445를 열면 **Windows 방화벽: ICMP 허용** 정책 설정이 수신 ICMP 에코 요청 메시지(예: PING 유틸리티가 전송하는 메시지)를 차단하려고 해도 Windows 방화벽은 해당 메시지를 허용합니다. TCP 포트 445를 열 수 있는 정책 설정에는 **Windows 방화벽: 파일 및 프린터 공유 허용**, **Windows 방화벽: 원격 관리 허용** 및 **Windows 방화벽: 예외 포트 정의**가 포함됩니다.
  
##### Windows 방화벽: 파일 및 프린터 공유 허용(표준 프로필)
  
**표 A.45: 파일 및 프린터 공유 허용(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
이 설정은 UDP 포트 137 및 138과 TCP 포트 139 및 445를 열도록 Windows 방화벽을 구성하여 파일 및 프린터 공유를 허용합니다. 이 정책 설정을 활성화하면 Windows 방화벽에서 이러한 포트를 열고 컴퓨터가 인쇄 작업 및 공유 파일 액세스 요청을 받을 수 있습니다. 이 경우 이러한 들어오는 메시지를 허용하는 IP 주소 또는 서브넷을 지정해야 합니다.
  
이 정책 설정을 비활성화하면 Windows 방화벽이 해당 포트를 닫아 컴퓨터에서 파일 및 프린터를 공유하지 못하도록 합니다.
  
Windows XP를 실행하는 컴퓨터는 일반적으로 파일 및 프린터를 공유하지 않으므로 모든 환경에서 이 설정을 **사용 안 함**으로 구성하는 것이 좋습니다.
  
**참고:** 만일 어떠한 정책 설정이 TCP 포트 445를 열면 **Windows 방화벽: ICMP 허용** 정책 설정이 수신 ICMP 에코 요청 메시지(예: PING 유틸리티가 전송하는 메시지)를 차단하려고 해도 Windows 방화벽은 해당 메시지를 허용합니다. TCP 포트 445를 열 수 있는 정책 설정에는 **Windows 방화벽: 파일 및 프린터 공유 허용**, **Windows 방화벽: 원격 관리 허용** 및 **Windows 방화벽: 예외 포트 정의**가 포함됩니다.
  
##### Windows 방화벽: ICMP 허용(표준 프로필)
  
**표 A.46: ICMP 허용(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: ICMP 허용** 설정은 Windows 방화벽이 허용하는 ICMP(Internet Control Message Protocol) 메시지 유형 모음을 정의합니다. 유틸리티에서는 ICMP 메시지를 사용하여 다른 컴퓨터의 상태를 확인할 수 있습니다. 예를 들어 Ping 유틸리티는 에코 요청 메시지를 사용합니다.
  
이 정책 설정을 **사용**으로 설정하는 경우에는 Windows 방화벽이 해당 컴퓨터에서 주고받을 수 있도록 허용하는 ICMP 메시지 유형을 지정해야 합니다. 이 정책을 **사용 안 함**으로 구성하면 Windows 방화벽이 요청되지 않은 모든 들어오는 ICMP 메시지 유형과 나열된 나가는 ICMP 메시지 유형을 차단합니다. 따라서 차단된 ICMP 메시지를 사용하는 유틸리티에서 컴퓨터와 메시지를 주고받을 수 없게 됩니다.
  
많은 공격자 도구는 ICMP 메시지 유형을 받아들이는 컴퓨터를 이용하며 이러한 메시지를 사용하여 다양한 공격을 수행합니다. 그러나 일부 응용 프로그램은 제대로 작동하기 위해 특정 ICMP 메시지를 요구합니다. 이러한 이유로 가능하면 이 설정을 **사용 안 함**으로 구성하는 것이 좋습니다. 즉, 컴퓨터가 신뢰할 수 없는 네트워크에 있는 경우에는 이 설정이 항상 **사용 안 함**이어야 합니다.
  
**참고:** 만일 어떠한 정책 설정이 TCP 포트 445를 열면 **Windows 방화벽: ICMP 허용** 정책 설정이 수신 ICMP 에코 요청 메시지(예: PING 유틸리티가 전송하는 메시지)를 차단하려고 해도 Windows 방화벽은 해당 메시지를 허용합니다. TCP 포트 445를 열 수 있는 정책 설정에는 **Windows 방화벽: 파일 및 프린터 공유 허용**, **Windows 방화벽: 원격 관리 허용** 및 **Windows 방화벽: 예외 포트 정의**가 포함됩니다.
  
##### Windows 방화벽: 원격 데스크톱 허용(표준 프로필)
  
**표 A.47: 원격 데스크톱 허용(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
많은 조직에서는 정상적인 문제 해결 절차나 작업에서 원격 데스크톱 연결을 사용합니다. 그러나 원격 데스크톱에서 주로 사용되는 포트가 공격에 이용될 수 있습니다. 보다 유연한 원격 관리를 위해 **Windows 방화벽: 원격 데스크톱 허용** 설정을 사용할 수 있습니다.
  
이 설정을 활성화하면 Windows 방화벽에서 인바운드 연결을 위해 TCP 포트 3389를 열도록 구성됩니다. 또한 이러한 들어오는 메시지를 허용하는 IP 주소 또는 서브넷을 지정해야 합니다.
  
이 정책 설정을 비활성화하면 Windows 방화벽은 해당 포트를 차단하고 컴퓨터가 원격 데스크톱 요청을 받아들일 수 없도록 합니다. 즉, 관리자가 예외 로컬 포트 목록에 이 포트를 추가하여 열려고 시도하면 Windows 방화벽에서 포트를 열지 않습니다.
  
열린 포트 3389는 일부 공격에 이용될 수 있으므로 원격 데스크톱이 제공하는 고급 관리 기능을 유지하려면 이 설정을 **사용**으로 구성하고 원격 관리에 사용되는 컴퓨터의 IP 주소 및 서브넷을 지정해야 합니다. 작업 환경의 컴퓨터에서는 최대한 작은 수의 컴퓨터로부터 원격 데스크톱 요청을 수락해야 합니다.
  
##### Windows 방화벽: UPnP 프레임워크 허용(표준 프로필)
  
**표 A.48: UPnP 프레임워크 허용(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: UPnP 프레임워크 허용** 설정을 사용하면 컴퓨터가 기본 제공 방화벽이 있는 라우터 등의 네트워크 장치에서 전송하는 요청하지 않은 플러그 앤 플레이 메시지를 수신할 수 있습니다. 이러한 메시지를 수신하기 위해 Windows 방화벽은 TCP 포트 2869 및 UDP 포트 1900을 엽니다.
  
이 설정을 활성화하면 Windows 방화벽이 해당 포트를 열어 컴퓨터가 플러그 앤 플레이 메시지를 수신할 수 있습니다. 이 경우 이러한 들어오는 메시지를 허용하는 IP 주소 또는 서브넷을 지정해야 합니다. 이 정책 설정을 비활성화하면 Windows 방화벽은 해당 포트를 닫아 컴퓨터가 플러그 앤 플레이 메시지를 수신하지 못하도록 합니다.
  
UPnP 네트워크 트래픽을 효과적으로 차단하면 컴퓨터가 공격에 노출될 가능성이 줄어듭니다. 신뢰할 수 없는 네트워크에서는 이 설정이 항상 **사용 안 함**이어야 합니다.
  
##### Windows 방화벽: 알림 금지(표준 프로필)
  
**표 A.49: 알림 금지(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
</tr>
</tbody>
</table>
  
Windows 방화벽은 특정 프로그램이 예외 프로그램 목록에 프로그램을 추가하도록 요청할 때 알림을 표시할 수 있습니다. 프로그램이 포트를 열려고 하지만 현재의 Windows 방화벽 규칙 때문에 열 수 없을 때 이러한 상황이 발생합니다. **Windows 방화벽: 알림 금지** 설정은 이러한 설정이 사용자에게 표시될지를 결정합니다.
  
이 정책을 **사용**으로 구성하면 Windows 방화벽에서 이러한 알림이 표시되지 않도록 하고 **사용 안 함**으로 설정하면 이러한 알림이 표시되도록 허용합니다.
  
일반적으로 엔터프라이즈 환경 또는 보안 수준이 높은 작업 환경에서는 사용자가 이러한 메시지에 응답하여 응용 프로그램 및 포트를 추가할 수 없습니다. 이 경우 해당 메시지는 사용자가 제어할 수 없는 기능을 사용하려고 한다는 사실을 알려 줍니다. 따라서 이러한 경우에는 이 옵션을 **사용**으로 구성하고, 사용자가 예외를 허용하도록 구성된 다른 환경에서는 이 옵션을 **사용 안 함**으로 구성해야 합니다.
  
##### Windows 방화벽: 멀티캐스트 또는 브로드캐스트 요청에 대한 유니캐스트 응답을 금지(표준 프로필)
  
**표 A.50: 유니캐스트 응답 금지(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: 멀티캐스트 또는 브로드캐스트 요청에 대한 유니캐스트 응답을 금지** 설정은 컴퓨터가 나가는 멀티캐스트 또는 브로드캐스트 메시지에 대한 유니캐스트 응답을 수신하는 것을 방지합니다. 이 정책을 활성화한 상태에서 컴퓨터가 멀티캐스트 또는 브로드캐스트 메시지를 다른 컴퓨터로 전송하면 Windows 방화벽은 다른 컴퓨터에서 보낸 유니캐스트 응답을 차단합니다. 이 설정을 비활성화한 상태에서 이 컴퓨터가 멀티캐스트 또는 브로드캐스트 메시지를 다른 컴퓨터로 전송하면 Windows 방화벽은 3초 동안 다른 컴퓨터의 유니캐스트 응답을 기다렸다가 그 이후의 모든 응답을 차단합니다.
  
일반적으로는 멀티캐스트 또는 브로드캐스트 메시지에 대한 유니캐스트 응답을 수신하지 않으려 할 수 있습니다. 이러한 응답은 DoS(서비스 거부) 공격이나 알려진 컴퓨터를 검색하려는 시도일 수 있습니다. 이 유형의 공격을 방지하기 위해 이 정책 설정을 **사용**으로 구성하는 것이 좋습니다.
  
**참고:** 유니캐스트 메시지가 이 컴퓨터에서 보낸 DHCP(Dynamic Host Configuration Protocol) 브로드캐스트 메시지에 대한 응답일 경우 이 정책 설정은 적용되지 않습니다. Windows 방화벽은 항상 해당 DHCP 유니캐스트 응답을 허용합니다. 그러나 이 정책 설정은 이름 충돌을 감지하는 NetBIOS 메시지를 방해할 수 있습니다.
  
##### Windows 방화벽: 예외 포트 정의(표준 프로필)
  
**표 A.51: 예외 포트 정의(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
<td style="border:1px solid black;">권장되지 않음</td>
</tr>
</tbody>
</table>
  
Windows 방화벽 예외 포트 목록은 그룹 정책을 통해 정의되며 사용자가 중앙에서 예외 포트를 관리 및 배포할 수 있고 로컬 관리자가 보안이 약한 설정을 만들 수 없습니다. **Windows 방화벽: 예외 포트 정의** 정책 설정을 사용하면 이러한 설정을 중앙에서 관리할 수 있습니다.
  
이 정책 설정을 활성화하면 그룹 정책에 정의된 예외 포트 목록을 보고 변경할 수 있습니다. 예외 포트 목록을 보고 수정하려면 해당 정책 설정을 **사용**으로 설정한 후 **표시** 단추를 클릭합니다. 잘못된 정의 문자열을 입력해도 Windows 방화벽은 오류를 검사하지 않고 목록에 그냥 추가합니다. 따라서 서로 충돌하는 범위 또는 상태 값을 지정하여 동일한 포트에 대해 여러 항목을 만들 수도 있습니다.
  
이 정책 설정을 비활성화하면 그룹 정책에 정의된 예외 포트 목록은 삭제되지만 다른 설정으로 포트를 계속 열거나 차단할 수 있습니다. 또한 예외 로컬 포트 목록이 있어도 **Windows 방화벽: 예외 로컬 포트 허용** 정책 설정을 활성화하지 않으면 무시됩니다.
  
특정 포트를 열도록 요구하는 비표준 응용 프로그램이 설치된 환경에서는 예외 프로그램 배포를 고려해야 합니다. 이 설정을 사용으로 구성하고 예외 프로그램을 정의할 수 없을 때만 예외 포트 목록을 지정하는 것이 좋습니다. 예외 프로그램은 지정된 프로그램이 실행되는 동안에만 Windows 방화벽이 요청되지 않은 네트워크 트래픽을 수락할 수 있으며 예외 포트는 지정된 포트를 항상 열어 둡니다.
  
**참고:** 만일 어떠한 정책 설정이 TCP 포트 445를 열면 **Windows 방화벽: ICMP 허용** 정책 설정이 수신 ICMP 에코 요청 메시지(예: PING 유틸리티가 전송하는 메시지)를 차단하려고 해도 Windows 방화벽은 해당 메시지를 허용합니다. TCP 포트 445를 열 수 있는 정책 설정에는 **Windows 방화벽: 파일 및 프린터 공유 허용**, **Windows 방화벽: 원격 관리 허용** 및 **Windows 방화벽: 예외 포트 정의**가 포함됩니다.
  
##### Windows 방화벽: 예외 로컬 포트 허용(표준 프로필)
  
**표 A.52: 예외 로컬 포트 허용(표준 프로필) 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트 데스크톱</th>
<th>엔터프라이즈 클라이언트 랩톱</th>
<th>고급 보안 데스크톱</th>
<th>고급 보안 랩톱</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
**Windows 방화벽: 예외 로컬 포트 허용** 설정을 사용하면 관리자가 제어판의 Windows 방화벽 구성 요소를 사용하여 예외 로컬 포트 목록을 정의할 수 있습니다. Windows 방화벽에서는 두 개의 예외 포트 목록을 사용할 수 있습니다. 나머지 한 목록은 **Windows 방화벽: 예외 포트 정의** 정책 설정을 통해 정의됩니다.
  
이 정책 설정을 활성화하면 관리자가 제어판의 Windows 방화벽 구성 요소에서 예외 로컬 포트 목록을 정의할 수 있습니다. 이 정책 설정을 비활성화하면 제어판의 Windows 방화벽 구성 요소에서 이러한 목록을 정의할 수 없습니다.
  
일반적으로 엔터프라이즈 환경 또는 보안 수준이 높은 작업 환경에서 로컬 관리자는 조직 정책을 재정의하고 자체의 예외 포트 목록을 설정할 수 있는 권한이 없습니다. 이러한 이유로 이 옵션을 **사용 안 함**으로 구성하는 것이 좋습니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 사용자 구성 설정
  
이 부록의 나머지 섹션에서는 사용자 구성 설정을 설명합니다. 사용자 계정이 포함된 OU에 연결된 GPO를 통해 이러한 설정을 적용합니다.
  
**참고**: 사용자 구성 설정은 사용자가 로그온하는 Microsoft Active Directory 디렉터리 서비스 도메인의 모든 클라이언트에 적용됩니다. 컴퓨터 구성 설정은 클라이언트에 로그온한 사용자에 관계없이 Active Directory의 GPO를 통해 제어되는 모든 클라이언트 컴퓨터에 적용됩니다. 이러한 이유로 이 섹션의 표에서는 이 설명서에 정의된 엔터프라이즈 클라이언트 및 보안 수준이 높은 작업 환경에 권장되는 설정만 보여 줍니다. 이러한 설정에 대해 랩톱 또는 데스크톱에 적용되는 규정은 없습니다.
  
#### 첨부파일 관리자
  
그룹 정책 개체 편집기를 사용하여 적절한 관리 템플릿을 구성합니다. 지정된 설정은 다음 위치에서 확인할 수 있습니다.
  
사용자 구성\\관리 템플릿\\Windows 구성 요소\\첨부파일 관리자
  
##### 첨부 파일에 영역 정보를 보존하지 않음
  
**표 A.53: 영역 정보를 보존하지 않음 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트</th>
<th>고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용 안 함</td>
<td style="border:1px solid black;">사용 안 함</td>
</tr>
</tbody>
</table>
  
**첨부 파일에 영역 정보를 보존하지 않음 정책** 설정으로 Windows가 첨부 파일의 출처(제한 영역, 인터넷, 인트라넷, 로컬)에 대한 정보를 사용하여 파일에 표시하는 것을 관리할 수 있습니다. 이 기능이 올바르게 작동하려면 파일이 NTFS 디스크 파티션으로 다운로드되어야 합니다. 영역 정보를 보존하지 않으면 Windows는 첨부 파일의 출처를 기반으로 위험성 확인을 올바르게 수행할 수 없습니다.
  
이 정책을 **사용**으로 설정하면 첨부 파일에 영역 정보가 표시되지 않습니다. 반면, 이 정책을 **사용 안 함**으로 설정하면 Windows에서 첨부 파일에 영역 정보를 표시합니다. 일반적으로 인터넷 영역과 같은 신뢰할 수 없는 Internet Explorer 영역에서 위험한 첨부 파일이 다운로드되므로 각 파일에 최대한 많은 보안 정보가 포함되도록 이 설정을 **사용 안 함**으로 구성하는 것이 좋습니다.
  
##### 영역 정보를 제거하는 메커니즘 숨기기
  
**표 A.54: 영역 정보를 제거하는 메커니즘 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트</th>
<th>고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
**영역 정보를 제거하는 메커니즘 숨기기** 정책 설정을 사용하면 사용자가 파일의 **속성** 시트에 있는 **차단 해제** 단추를 클릭하거나 **보안 경고** 대화 상자의 확인란을 선택하여 저장된 첨부 파일에서 영역 정보를 수동으로 제거할 수 있는지를 관리할 수 있습니다. 영역 정보를 제거하면 사용자는 Windows에서 차단한 위험성이 있는 첨부 파일을 열 수 있게 됩니다.
  
이 정책 설정이 **사용**인 경우 Windows에서는 해당 확인란과 **차단 해제** 단추를 숨기고, 이 설정이 **사용 안 함**인 경우 구성에는 확인란과 **차단 해제** 단추를 표시합니다. 일반적으로 인터넷 영역과 같은 신뢰할 수 없는 Internet Explorer 영역에서 위험한 첨부 파일이 다운로드되므로 각 파일에 최대한 많은 보안 정보가 포함되도록 이 설정을 **사용**으로 구성하는 것이 좋습니다.
  
**참고:** 파일을 영역 정보와 함께 저장할지를 구성하려면 앞에 나온 **첨부 파일에 영역 정보를 보존하지 않음** 정책 설정을 참조하십시오.
  
##### 첨부 파일을 열 때 바이러스 백신 프로그램 알림
  
**표 A.55: 바이러스 백신 프로그램 알림 설정**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>엔터프라이즈 클라이언트</th>
<th>고급 보안</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">사용</td>
<td style="border:1px solid black;">사용</td>
</tr>
</tbody>
</table>
  
백신 프로그램은 대부분의 환경에서 반드시 필요한 프로그램이며 현재 공격에 대한 강력한 방어 장치입니다. **바이러스 백신 프로그램 알림** 정책 설정을 사용하면 등록된 백신 프로그램 알림 동작을 관리할 수 있습니다.
  
이 정책 설정이 **활성화**되면 Windows에서는 사용자가 첨부 파일을 열 때 등록된 바이러스 백신 프로그램이 해당 파일을 검사하도록 요청합니다. 바이러스 백신 프로그램이 검사에 실패하면 첨부 파일은 열 수 없도록 차단됩니다. 이 정책 설정을 **비활성화**하면 Windows에서는 첨부 파일이 열릴 때 바이러스 백신 프로그램을 호출하지 않습니다.
  
모든 첨부 파일을 열기 전에 바이러스 백신 프로그램으로 검사하도록 모든 환경에서 이 정책 설정을 **사용**으로 구성하는 것이 좋습니다.
  
**참고:** 이 설정이 제대로 작동하려면 업데이트된 바이러스 백신 프로그램을 설치해야 합니다. 업데이트된 많은 바이러스 백신 프로그램이 SP2에 포함되어 있는 새로운 API를 사용합니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 요약
  
Windows XP SP2의 보안 서비스 관리 효율과 관련된 많은 향상된 기능을 사용하여 관리자는 사용자 및 컴퓨터에 특정한 보안 설정을 구현할 수 있습니다. 이 부록에서는 SP2 환경에서 보안 기능을 향상시키는 데 사용해야 하는 가장 중요한 설정들을 보여 주었습니다. 가능한 모든 설정을 설명한 것은 아니지만 지정한 설정은 작업 환경에 직접적이고 많은 영향을 줄 수 있습니다.
  
SP2는 이전 버전의 Windows에 비해 많은 기능이 달라졌기 때문에 작업 환경에서 응용 프로그램 호환성 문제가 발생할 수 있습니다. 따라서 구현하기 전에 모든 권장 설정을 신중하게 테스트해야 합니다. 이러한 설정은 지정된 환경에서 올바르게 작동하도록 철저한 테스트를 거쳤지만 사용자의 특정 환경에 대한 테스트를 대신할 수는 없습니다.
  
[](#mainsection)[페이지 위쪽](#mainsection)
