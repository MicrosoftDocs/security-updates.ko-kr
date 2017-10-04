---
TOCTitle: Data Encryption Toolkit for Mobile PCs
Title: Data Encryption Toolkit for Mobile PCs
ms:assetid: '77403c60-81c4-48c4-b2ee-cbf410572bf0'
ms:contentKeyID: 20213898
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc162808(v=TechNet.10)'
---

Data Encryption Toolkit for Mobile PCs 계획 및 구현 가이드
==========================================================

개요

게시 날짜: 2007년 5월 29일

조직에 데이터 암호화를 배포하려면 충분한 검토와 사전 계획이 필요합니다. *Data Encryption Toolkit for Mobile PCs 계획 및 구현 가이드*에서는 모바일 PC의 데이터 보호를 위한 전략으로 Microsoft® BitLocker™ 드라이브 암호화(BitLocker) 및 EFS(파일 시스템 암호화)를 사용할 때 준수해야 하는 계획 및 구현 프로세스를 설명합니다.

##### 이 페이지에서

[](#ehae)[BitLocker에 대한 간략한 개요](#ehae)
[](#egae)[EFS에 대한 간략한 개요](#egae)
[](#efae)[장 요약](#efae)
[](#eeae)[이 가이드를 읽어야 할 사람](#eeae)
[](#edae)[이 가이드에서 사용된 규칙](#edae)
[](#ecae)[지원 및 피드백](#ecae)
[](#ebae)[감사의 말](#ebae)

### BitLocker에 대한 간략한 개요

BitLocker는 컴퓨터의 데이터와 운영 체제를 훌륭하게 보호해 주는 Windows Vista™ 운영 체제의 새로운 중요 보안 기능입니다. BitLocker는 전체 볼륨을 암호화하는 기술로, 설치된 운영 체제가 오프라인 상태일 때 누군가 컴퓨터를 조작하더라도 데이터가 노출되지 않도록 합니다. BitLocker는 호환되는 TPM(신뢰할 수 있는 플랫폼 모듈) 마이크로칩과 BIOS를 사용하여 데이터 보호를 강화하고 초기 부팅 구성 요소의 무결성을 보장하기 때문에 이러한 요소를 갖춘 컴퓨터에서 가장 효과적입니다. BitLocker는 외부 USB 키를 토큰으로 사용하여 시작 키를 저장할 수도 있습니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### EFS에 대한 간략한 개요

EFS를 사용하면 표준에 기반한 고급 암호화 알고리즘을 사용하여 투명하게 파일을 암호화하거나 암호를 해독할 수 있습니다. 적합한 암호화 키가 없는 사용자나 프로그램은 파일이 있는 컴퓨터에 물리적으로 접근할 수는 있더라도 암호화된 데이터의 암호를 해독할 수 없습니다. 컴퓨터 및 파일 시스템에 액세스할 수 있는 권한이 있는 사용자도 암호화된 데이터를 볼 수 없습니다.

EFS는 두 가지 암호화 유형을 결합하여 사용하는데 대칭 암호화는 파일의 데이터를 보호하는 데 사용되고 비대칭 암호화는 대칭 암호화에 사용되는 키를 보호하는 데 사용됩니다.

[Windows 2000 Server Resource Kit](http://go.microsoft.com/fwlink/?linkid=458)의 *Distributed Systems 가이드*에 EFS에 대한 종합적인 개요와 Microsoft Windows® 2000의 EFS에 대한 정보의 모임이 수록되어 있습니다. 이 정보를 온라인으로 찾으려면 Windows 2000 Server Resource Kit 목차에서 *Distributed Systems Guide*로 이동한 다음 **Distributed Security**를 확장하고 **Encrypting File System**을 클릭합니다.

Windows 2000, Windows XP Professional, Windows Server® 2003 및 Windows Vista에서의 EFS는 차이가 있습니다. Windows XP Professional Resource Kit에서는 Windows 2000과 Windows XP Professional에서 EFS를 구현할 경우 차이점에 대해서 설명하고, "[Encrypting File System in Windows XP and Windows Server 2003(Windows XP 및 Windows Server 2003에서의 파일 시스템 암호화)](http://go.microsoft.com/fwlink/?linkid=22413)" 문서에서는 Windows XP 및 Windows Server 2003에서의 차이점에 대해서 설명합니다. Windows XP Professional 및 Windows Vista에 구현된 EFS의 차이점에 대해서는 본 가이드의 [2장: 구성 및 배포 작업](http://www.microsoft.com/a69e5f04-8f25-43a6-86b9-e8279021d108.mspx)에 설명되어 있습니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 장 요약

*계획 및 구현 가이드*의 각 장에서는 다음과 같은 항목에 대해서 설명합니다.

-   [1장: 계획 시 고려 사항](http://www.microsoft.com/54de4f8c-d962-4744-b2da-99f7ad7953df.mspx). 이 장에서는 환경을 평가하고, 보호할 리소스를 결정하고, 가장 적합한 보안 방법을 결정하기 위해 수행해야 하는 계획 단계를 포함하여 Windows Vista BitLocker와 두 가지 유형의 EFS를 배포할 때 계획 시 고려해야 할 사항에 대해서 설명합니다.

-   [2장: 구성 및 배포 작업](http://www.microsoft.com/a69e5f04-8f25-43a6-86b9-e8279021d108.mspx). 이 장에서는 배포 단계에서 수행해야 하는 특정 구성 작업에 대해서 설명합니다. 이러한 구성 작업에는 BitLocker 구성 선택, 디스크 암호화 구성, Active Directory® 디렉터리 서비스 그룹 정책 개체를 설정하여 조직에서 EFS가 사용되는 방식을 제어 및 관리하는 등의 작업이 포함됩니다. 이 장에 설명된 구성 작업은 일반적으로 BitLocker 및 EFS 배포를 위한 환경 준비를 위해 한 번은 수행해야 하는 준비 작업입니다. 또한 이 장에서는 환경에서 BitLocker 및 EFS를 사용할 수 있도록 설정하기 위해 각 컴퓨터에 수행해야 하는 배포 작업에 대해서도 설명합니다. 예를 들어, BitLocker와 함께 작동할 수 있도록 일부 컴퓨터에서는 BIOS를 업데이트해야 할 수 있습니다.

-   [3장: 작업 및 복구 시나리오](http://www.microsoft.com/01754723-3e94-4bec-8284-02e2a4e91593.mspx). 이 장에서는 BitLocker 및 EFS로 보호되는 컴퓨터에서 지속적으로 수행되는 작업에 대해서 설명합니다. 예를 들어, 키 자료나 인증서가 분실되었거나 손상된 경우 조직에서 암호화된 데이터를 복구할 수 있는 방법에 대해서 설명합니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 이 가이드를 읽어야 할 사람

이 가이드는 수십 개에서 수천 개에 이르는 클라이언트 컴퓨터, 그 중에서도 특히 랩톱과 Tablet PC 컴퓨터가 포함된 컴퓨터 네트워크를 설계, 계획 및 구현하는 역할을 담당하는 IT 전문가를 대상으로 합니다. 다음과 같은 업무가 귀하의 업무에 포함되어 있다면 이 가이드를 읽어 보아야 합니다.

-   서버 또는 클라이언트 보안 정책 구현

-   보안 또는 시스템 관리 아키텍처 설계 및 구현

-   보안 기술 평가

-   다른 컴퓨터 관리 정책 도는 기술과의 보안 정책 통합

[](#mainsection)[페이지 위쪽](#mainsection)

### 이 가이드에서 사용된 규칙

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>요소</th>
<th>의미</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>굵게</strong></td>
<td style="border:1px solid black;">명령, 스위치, 파일 이름 등 표시된 대로 정확하게 입력해야 하는 문자를 나타냅니다. 사용자 인터페이스 요소도 굵게 표시됩니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>기울임꼴</em></td>
<td style="border:1px solid black;">저서의 제목 및 기타 중요한 출판물은 <em>기울임꼴</em>로 표시됩니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>&lt;Italic&gt;</em></td>
<td style="border:1px solid black;">각 괄호 안에 기울임꼴로 표시된 자리 표시자(<em>&lt;file name&gt;</em>)는 변수를 나타냅니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><pre><code>고정 폭 글꼴</code></pre></td>
<td style="border:1px solid black;">코드 및 스크립트 예제를 나타냅니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>참고</strong></td>
<td style="border:1px solid black;">독자에게 추가 정보를 알려 줍니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>중요</strong></td>
<td style="border:1px solid black;">독자에게 중요한 추가 정보를 알려 줍니다.</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 지원 및 피드백
  
SA-SC(Solution Accelerators – Security and Compliance) 팀은 본 가이드 및 기타 Solution Accelerator에 대한 여러분의 의견에 감사 드립니다. 여러분의 소중한 의견 및 피드백은 [secwish@microsoft.com](mailto:secwish@microsoft.com?subject=data%20encryption%20toolkit%20for%20mobile%20pcs%20security%20analysis)으로 보내주십시오. 저희는 항상 고객의 의견을 기다립니다.
  
Solution Accelerator는 제품 상호 간 통합을 위한 사전 예방적 지침 및 자동화를 제공합니다. 입증된 도구 및 콘텐츠를 제공하므로 자신 있게 정보 기술을 계획, 구축, 배포 및 운영할 수 있습니다. 광범위한 Solution Accelerator 및 추가 정보를 살펴 보려면 Microsoft TechNet의 [Solution Accelerators](http://go.microsoft.com/fwlink/?linkid=51571) 페이지를 참조하십시오.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 감사의 말
  
SA-SC 팀은 *Data Encryption Toolkit for Mobile PCs 계획 및 구현 가이드*를 제작한 팀에 감사의 뜻을 전하고자 합니다. 다음은 이 가이드의 저작, 개발 및 테스트를 직접적으로 책임졌거나 중요한 공헌을 하신 분들입니다.
  
**개발 책임 담당자**
  
Mike Smith-Lonergan - *Microsoft*
  
David Mowers - *Securitay, Inc.*
  
**프로그램 관리자**
  
Bill Canning - *Microsoft*
  
**콘텐츠 개발자**
  
Roger A. Grimes - *Microsoft*
  
Paul Robichaux - *3Sharp, LLC*
  
**편집자**
  
Steve Wacker - *Wadeware LLC*
  
**검토자**
  
Randy Armknecht - *Calamos Investments*
  
Vijay Bharadwaj - *Microsoft*
  
Marcus Bluestein - *Kraft Kennedy & Lesser, Inc.*
  
Dean Chen - *Waggener Edstrom Worldwide*
  
Tom Daemen - *Microsoft*
  
Mike Danseglio - *Microsoft*
  
Erik Holt - *Microsoft*
  
Russell Humphries - *Microsoft*
  
David Kennedy - *Microsoft*
  
Luca Lorenzini
  
Douglas MacIver - *Microsoft*
  
Sanjay Pandit - *Microsoft*
  
Greg Petersen - *Avanade*
  
Matt Setzer - *Microsoft*
  
Stan Shkolnik - *Deloitte Touche Tohmatsu*
  
Michael Trotman - *United States Postal Service (USPS)*
  
Richard Trusson - *Microsoft*
  
Mike Wolfe - *Microsoft*
  
**제품 관리자**
  
Alain Meeus - *Microsoft*
  
Jim Stuart - *Microsoft*
  
**릴리스 관리자**
  
Karina Larson - *Microsoft*
  
**테스터**
  
Gaurav Singh Bora - *Microsoft*
  
Sumit Ajitkumar Parikh - *Infosys Technologies Ltd.*
  
Swaminathan Viswanathan - *Infosys Technologies Ltd.*
  
Swapna Rangachari Jagannathan - *Infosys Technologies Ltd.*
  
Neethu Thomas - *Infosys Technologies Ltd.*
  
**다운로드**
  
[Data Encryption Toolkit for Mobile PCs 받기](http://go.microsoft.com/fwlink/?linkid=81666)
  
**업데이트 알림**
  
[업데이트 및 새 릴리스에 대해 알아보려면 등록](http://go.microsoft.com/fwlink/?linkid=54982)
  
**사용자 의견**
  
[사용자 의견 및 제안 보내기](mailto:secwish@microsoft.com?subject=data%20encryption%20toolkit%20for%20mobile%20pcs,%20data%20encryption%20toolkit%20계획%20및%20구현%20가이드)
  
[](#mainsection)[페이지 위쪽](#mainsection)
