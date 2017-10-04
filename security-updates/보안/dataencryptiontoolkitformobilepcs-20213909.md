---
TOCTitle: Data Encryption Toolkit for Mobile PCs 개요
Title: Data Encryption Toolkit for Mobile PCs 개요
ms:assetid: 'abfc4696-a39a-43df-b559-133633e4bd5e'
ms:contentKeyID: 20213909
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc162811(v=TechNet.10)'
---

Data Encryption Toolkit for Mobile PCs - 보안 분석
==================================================

### 개요

게시 날짜: 2007년 4월 4일

불과 몇 년 전만 해도 대부분의 조직에서 랩톱 컴퓨터는 상대적으로 드물었습니다. 랩톱은 출장이 많은 직원과 임원들에게만 지급되곤 했습니다. 오늘날 랩톱은 그 어느 때보다도 강력한 기능을 갖추고 있는 동시에 보편적으로 많이 사용되고 있습니다. 더 이상 일부 선택된 사람들의 전유물이 아니며, 일부 조직에서는 랩톱의 수가 데스크톱의 수를 넘어서고 있습니다. 또한 랩톱의 용량이 증가함에 따라 점차 모든 종류의 중요한 데이터를 저장하는 소중한 저장소로 기능하고 있습니다.

랩톱의 엄청난 증가와 더불어 분실 또는 도난되는 랩톱의 수도 함께 증가하고 있습니다. 중간 규모에서 대규모에 이르는 대개의 조직에서 랩톱 보안은 심각한 문제입니다. Ponemon Institute의 최근 연구인, "[위험에 처한 기밀 데이터(Confidential Data at Risk)](http://www.csoonline.com/read/080106/col_ponemon.html)"에 따르면 "응답자 484명 중 81%가 지난 12개월 동안 중요하거나 기밀인 비즈니스 정보가 들어 있는 랩톱 컴퓨터를 1회 이상 분실 또는 분실한 경험이 있다고 대답했음"이 밝혀졌습니다. 교체 비용도 상당하지만 도난당한 랩톱의 하드 디스크 드라이브에 중요하거나 민감한 데이터가 들어 있을 경우 그에 따르는 보안 위협의 직접 및 간접 비용은 더욱 클 수 있습니다.

어떤 종류의 정보는 연방 또는 자국법에 의해 보호를 받으며, 일부는 주법, 지방법 또는 지역법의 보호를 받고, 일부는 산업 규제의 보호를 받습니다. 랩톱의 수가 늘어날수록 법규의 수, 관할권 및 중요도 분류도 점점 늘어납니다. 랩톱 컴퓨터를 분실하는 경우 사전 예방적 보안 조치에 기울인 노력의 양에 따라 조직은 상당한 벌금 및 민사상 책임을 질 수도 있습니다. 또한 보안 위협에 따르는 직접 및 간접 비용에는 고객 유지의 어려움 및 신뢰와 명성의 손상도 포함될 수 있습니다.

Microsoft는 랩톱 컴퓨터의 보안 문제를 해결할 수 있는 도구를 제공합니다. 랩톱에서 데이터를 적절하게 암호화해 놓으면, 랩톱이 분실 또는 도난당할 경우 중요한 데이터를 검색하는 것이 훨씬 어려워집니다. Microsoft® BitLocker™ 드라이브 암호화(BitLocker) 및 EFS(Encrypting File System)를 적절하게 사용함으로써 많이 사용되는 광범위한 공격 경로로부터 중요한 데이터를 보호할 수 있습니다.

본 가이드인 *Microsoft Data Encryption Toolkit for Mobile PCs 보안 분석*에서는 BitLocker와 EFS를 사용하여 달성할 수 있는 보안 수준에 대한 구체적 내용을 제공합니다. Windows Vista™의 Enterprise 및 Ultimate 버전에서는 이 가이드에서 설명된 보안 기능을 완벽하게 지원하며, Microsoft Windows® XP에서는 중요하고 유용한 일부 기능을 제공합니다. 기능 및 적용된 구성에 따라 여러 수준의 보호 기능을 사용할 수 있습니다. 가장 안전한 구성의 경우, 악의적 공격자는 하드 디스크 드라이브의 데이터를 해독하기 위해 엄청난 양의 리소스를 필요로 합니다.

*보안 분석*을 통해 Windows Vista 및 Windows XP의 기능들이 조직 내에서 특정 보안 위험을 어떻게 완화 또는 감소시킬 수 있는지 이해할 수 있습니다. 이 가이드는 다음과 같은 점에서 도움을 줄 수 있습니다.

-   사용자 환경에서 일반적인 위협 공격 경로 및 위험을 파악합니다.

-   BitLocker와 EFS를 별도로 및 조합하여 사용함으로써 특정 위험 및 위협을 완화할 수 있는 방법을 이해합니다.

-   BitLocker 또는 EFS로 해결할 수 없는 보안 위협을 완화할 수 있도록 대비합니다.

-   Windows Vista에서 사용할 수 있는 뛰어난 보안 기능 및 기술을 이해합니다.

이 가이드에서 설명된 보안 기능은 업계에서 수용되는 기술을 사용하여 개발되었습니다. 예를 들어 Microsoft에서 구현한 BitLocker와 EFS에 사용된 암호 기술은 미국 연방 정부의 FIPS(Federal Information Processing Standard) 140-1의 인증을 받았으며 구현된 알고리즘은 충분히 검증되었습니다. 이렇게 업계에서 인정되는 기술을 고수하는 것이 중요한 이유는 일부 주 및 국가의 데이터 개인 정보 보호 법률이 데이터 보안에 있어 최고의 관행을 따르기 위해 충분한 노력을 기울였음을 입증할 수 있는 조직에 대해 감세 또는 감면 혜택을 제공하기 때문입니다.

##### 이 페이지에서

[](#egaa)[이 가이드를 읽어야 할 사람](#egaa)
[](#efaa)[장의 구성](#efaa)
[](#eeaa)[이 가이드에서 사용된 규칙](#eeaa)
[](#edaa)[자세한 정보](#edaa)
[](#ecaa)[지원 및 피드백](#ecaa)
[](#ebaa)[감사의 말](#ebaa)

### 이 가이드를 읽어야 할 사람

이 가이드는 수십 개에서 수천 개의 클라이언트 컴퓨터, 특히 랩톱에 대한 정책과 기술 결정 또는 권장 사항을 책임지는 보안 전문가를 대상으로 합니다. 기술 및 관련 위협은 일반적으로 가정용 사용자나 가정용 네트워크에는 적용되지 않습니다. 다음과 같은 업무가 귀하의 업무에 포함되어 있다면 이 가이드를 읽어 보아야 합니다.

-   보안 정책 및 기술에 대한 의사 결정 또는 권장 사항 제시

-   서버 또는 클라이언트 보안 정책 구현

-   보안 기술 평가

-   다른 컴퓨터 관리 정책 도는 기술과의 보안 정책 통합

이 가이드에서 제공하는 정보는 자세한 고급 정보이며 보안, 암호화, 파일 시스템 또는 보안 및 시스템 관리의 기타 기본적 주제에 대한 기초 자료로 사용할 수 없습니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 장의 구성

본 섹션에서는 이 가이드의 장에 대한 개요를 제공합니다.

[1장: 위험에 대한 설명](http://www.microsoft.com/df2c6d71-98f7-4212-b3b7-b9eb2f501348.mspx)에서는 BitLocker와 EFS로 해결할 수 있는 보안 위협을 소개합니다. 여기에서는 위험 및 이점을 논의하는 데 있어 보다 구체적인 틀을 제공하기 위해 *보안 분석* 전반에서 사용되는 시나리오에 대해서도 설명합니다.

[2장: BitLocker 드라이브 암호화](http://www.microsoft.com/4e6ce820-fcac-495a-9f23-73d65d846638.mspx)는 Windows Vista에서 소개되는 BitLocker 드라이브 암호화 기술을 중점적으로 설명합니다. 여기에서는 BitLocker를 사용하여 1장에서 설명된 특정 보안 위협을 완화할 수 있는 방법을 설명하고, 조직 내에서 안정적인 BitLocker 구현을 개발하는 데 시작점으로 사용할 수 있는 구성 예제를 제공합니다.

[3장: EFS(Encrypting File System)](http://www.microsoft.com/dc2cde72-a84d-4716-9a30-f62b608efda1.mspx)에서는 EFS 작동 방식 및 EFS를 사용하여 사용자 환경에서 특정 위협을 완화할 수 있는 방법을 설명합니다.

[4장: BitLocker 및 EFS](http://www.microsoft.com/80c0d0af-2c2e-45d6-9b29-f850926296bb.mspx)에서는 BitLocker와 EFS를 결합하여 각각의 기술을 별도로 사용할 때보다 더욱 효과적으로 위협을 완화할 수 있는 방법을 설명합니다.

[5장: 올바른 솔루션 선택](http://www.microsoft.com/b77d6369-10e9-4e66-8c67-c9f8cb073ced.mspx)에서는 보안 전문가가 해당 조직에 적합한 기능 및 구성 항목을 적절하게 선택하는 데 도움이 되는 설명 및 도구를 제공합니다.

[](#mainsection)[페이지 위쪽](#mainsection)

### 이 가이드에서 사용된 규칙

이 가이드는 다음 표에서 설명된 규칙을 사용합니다.

 
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
  
### 자세한 정보
  
이 *보안 분석*과 더불어 [Data Encryption Toolkit for Mobile PCs](http://go.microsoft.com/fwlink/?linkid=86127)에도 기타 유용한 문서 및 도구가 포함되어 있습니다.
  
-   *계획 및 구현 가이드*에서는 모바일 PC를 보호하기 위해 BitLocker 및 EFS를 계획하고 구현하는 방법을 설명합니다.
  
-   Microsoft EFS(Encrypting File System) Assistant 도구는 Windows XP 및 Windows Vista가 실행되는 컴퓨터에서 중요한 파일을 검색 및 암호화하는 과정을 자동화하는 데 도움을 줍니다.
  
-   *EFS Assistant 관리자 가이드*에서는 업무 부서 또는 기업 전체에서 일관성 있는 보호 기능을 제공할 수 있도록 도메인이 결합된 컴퓨터에서 관리자가 EFS Assistant를 배포 및 관리하는 방법을 설명합니다.
  
의사 결정권자들이 Microsoft Windows에서의 보안 문제를 보다 폭넓게 또는 보다 깊이 있게 이해하는 데 도움이 되는 많은 유용한 자료가 준비되어 있습니다. Microsoft TechNet의 [보안 가이드](http://www.microsoft.com/technet/security/guidance/default.mspx) 페이지는 좋은 시작점입니다.
  
도메인 관리의 보안 요구 사항을 해결하기 위한 구체적 조언은 [Windows Server Active Directory 설치 보안을 위한 최고의 관행 지침(Best Practice Guide for Securing Windows Server Active Directory Installations)](http://www.microsoft.com/windowsserver2003/techinfo/overview/adsecurity.mspx)을 참조하십시오.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 지원 및 피드백
  
SASC(Solution Accelerators – Security and Compliance) 팀은 본 가이드 및 기타 Solution Accelerator에 대한 여러분의 의견에 감사 드립니다. 여러분의 소중한 의견 및 피드백은 [secwish@microsoft.com](mailto:secwish@microsoft.com?subject=data%20encryption%20toolkit%20for%20mobile%20pcs%20security%20analysis%20on%20technet)으로 보내주십시오. 저희는 항상 고객의 의견을 기다립니다.
  
Solution Accelerator는 제품 상호 간 통합을 위한 사전 예방적 지침 및 자동화를 제공합니다. 입증된 도구 및 콘텐츠를 제공하므로 자신 있게 정보 기술을 계획, 구축, 배포 및 운영할 수 있습니다. 광범위한 Solution Accelerator 및 추가 정보를 살펴 보려면 Microsoft TechNet의 [Solution Accelerators](http://go.microsoft.com/fwlink/?linkid=51571) 페이지를 참조하십시오.
  
[](#mainsection)[페이지 위쪽](#mainsection)
  
### 감사의 말
  
SA-SC(Solution Accelerators - Security and Compliance) 팀에서는 *Data Encryption Toolkit for Mobile PCs 보안 분석*을 만든 팀에 감사의 뜻을 전하고자 합니다. 다음은 이 솔루션의 저작, 개발 및 테스트를 직접적으로 책임졌거나 중요한 공헌을 하신 분들입니다.
  
**개발 책임 담당자**
  
Mike Smith-Lonergan - *Microsoft*
  
David Mowers - *Securitay, Inc.*
  
**프로그램 관리자**
  
Bill Canning - *Microsoft*
  
**콘텐츠 개발자**
  
Paul Flynn - *3Sharp, LLC*
  
Tommy Phillips - *Butternut Software*
  
Paul Robichaux - *3Sharp, LLC*
  
**편집자**
  
Steve Wacker - *Wadeware LLC*
  
**검토자**
  
Vijay Bharadwaj - *Microsoft*
  
Tom Daemen - *Microsoft*
  
Mike Danseglio - *Microsoft*
  
Kurt Dillard - *Microsoft*
  
Jeff Hatfield - *Wireless Ink Inc.*
  
Erik Holt - *Microsoft*
  
Russell Humphries - *Microsoft*
  
David Kennedy - *Microsoft*
  
Douglas MacIver - *Microsoft*
  
Josh Phillips
  
Greg Petersen - *Avanade Inc.*
  
Ben Wilson - *ASG Group*
  
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
  
**참여**
  
[Data Encryption Toolkit 베타 프로그램 등록](https://connect.microsoft.com/invitationuse.aspx?programid=790&invitationid=desa-r7gd-3f73&siteid=14)
  
**업데이트 알림**
  
[업데이트 및 새 릴리스에 대해 알아보려면 등록](http://go.microsoft.com/fwlink/?linkid=54982)
  
**사용자 의견**
  
[사용자 의견 및 제안 보내기](mailto:secwish@microsoft.com?subject=data%20encryption%20toolkit%20for%20mobile%20pcs%20security%20analysis%20on%20technet)
  
[](#mainsection)[페이지 위쪽](#mainsection)
