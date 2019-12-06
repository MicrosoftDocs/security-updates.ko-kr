---
TOCTitle: 'MS14-JUN'
Title: 2014년 6월 Microsoft 보안 공지 요약
ms:assetid: 'ms14-jun'
ms:contentKeyID: 62490237
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms14-jun(v=Security.10)'
---

2014년 6월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2014년 6월 11일 | 업데이트된 날짜: 2014년 6월 18일

**버전:** 1.1

이 공지 요약 목록에는 2014년 6월 발표된 보안 공지가 포함되어 있습니다.

2014년 6월 보안 공지 발표와 함께 이 공지 요약이 2014년 6월 5일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](https://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](https://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2014년 6월 11일 오전 11시(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [6월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572980&culture=en-us).

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향을 받는 소프트웨어**를 참조하십시오.

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >공지 번호</th>
<th style="border:1px solid black;" >공지 제목 및 용약</th>
<th style="border:1px solid black;" >최대 심각도 및 취약점 영향</th>
<th style="border:1px solid black;" >다시 시작 요구 사항</th>
<th style="border:1px solid black;" >영향을 받는 소프트웨어</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(2969262)<br />
<br />
</strong>이 보안 업데이트는 Internet Explorer에서 발견되어 공개적으로 보고된 취약점 2건 및 비공개적으로 보고된 취약점 57건을 해결합니다. 가장 심각한 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics Component의 취약점으로 인한 원격 코드 실행 문제점(2967487)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows, Microsoft Office, Microsoft Lync의 비공개적으로 보고된 취약점 2건을 해결합니다. 사용자가 특수하게 조작된 파일이나 웹 페이지를 열면 이러한 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office, Microsoft Lync</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400971">MS14-034</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word의 취약점으로 인한 원격 코드 실행 문제점(2969261)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 이 취약점으로 인해 영향을 받는 Microsoft Word 버전에서 특수하게 조작된 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=398119">MS14-033</a></td>
<td style="border:1px solid black;"><strong>Microsoft XML Core Services의 취약점으로 인한 정보 유출 문제점(2966061)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 로그온한 사용자가 Internet Explorer를 통해 MSXML(Microsoft XML Core Services)이 실행되도록 특수하게 조작된 웹 사이트를 방문하는 경우 정보가 유출될 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 이러한 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 요청의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400969">MS14-032</a></td>
<td style="border:1px solid black;"><strong>Microsoft Lync Server의 취약점으로 인한 정보 유출 문제점(2969258)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Lync Server의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 모임 URL을 클릭하여 Lync 모임에 참여하려고 시도할 경우 정보 유출이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Lync Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=396824">MS14-031</a></td>
<td style="border:1px solid black;"><strong>TCP 프로토콜의 취약점으로 인한 서비스 거부 문제점(2962478)<br />
</strong><br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점은 공격자가 특수하게 조작된 패킷 시퀀스를 대상 시스템에 전송할 경우 서비스 거부를 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400970">MS14-030</a></td>
<td style="border:1px solid black;"><strong>원격 데스크톱의 취약점으로 인한 변조 문제점(2969259)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점을 악용하면 활성 RDP(원격 데스크톱 프로토콜) 세션 동안 공격자가 대상 시스템과 동일한 네트워크 세그먼트에 대한 액세스 권한을 얻은 다음 특수하게 조작된 RDP 패킷을 대상 시스템으로 전송할 경우 변조할 수 있습니다. 기본적으로 RDP는 모든 Windows 운영 체제에서 사용되도록 설정되지 않습니다. RDP가 사용 가능하지 않는 시스템은 취약하지 않습니다.</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
변조</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
악용 가능성 인덱스  
------------------
  
<span id="sectionToggle1"></span>
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](https://technet.microsoft.com/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.
  
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><strong>취약점 제목</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>최신 소프트웨어 버전에 대한 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>이전 소프트웨어 버전에 대한 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>서비스 거부 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>주요 정보</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400970">MS14-030</a></td>
<td style="border:1px solid black;">RDP MAC 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0296">CVE-2014-0296</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 변조 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=396824">MS14-031</a></td>
<td style="border:1px solid black;">TCP 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1811">CVE-2014-1811</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400969">MS14-032</a></td>
<td style="border:1px solid black;">Lync Server 콘텐츠 삭제 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1823">CVE-2014-1823</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=398119">MS14-033</a></td>
<td style="border:1px solid black;">MSXML 엔터티 URI 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1816">CVE-2014-1816</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400971">MS14-034</a></td>
<td style="border:1px solid black;">포함 글꼴 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2778">CVE-2014-2778</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0282">CVE-2014-0282</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1762">CVE-2014-1762</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1764">CVE-2014-1764</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1766">CVE-2014-1766</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1769">CVE-2014-1769</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1770">CVE-2014-1770</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">TLS 서버 인증서 재협상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1771">CVE-2014-1771</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1772">CVE-2014-1772</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1773">CVE-2014-1773</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1774">CVE-2014-1774</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1775">CVE-2014-1775</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1777">CVE-2014-1777</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1778">CVE-2014-1778</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1779">CVE-2014-1779</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1780">CVE-2014-1780</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1781">CVE-2014-1781</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1782">CVE-2014-1782</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1783">CVE-2014-1783</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1784">CVE-2014-1784</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1785">CVE-2014-1785</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1786">CVE-2014-1786</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1788">CVE-2014-1788</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1789">CVE-2014-1789</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1790">CVE-2014-1790</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1791">CVE-2014-1791</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1792">CVE-2014-1792</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1794">CVE-2014-1794</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1795">CVE-2014-1795</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1796">CVE-2014-1796</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1797">CVE-2014-1797</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1799">CVE-2014-1799</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1800">CVE-2014-1800</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1802">CVE-2014-1802</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1803">CVE-2014-1803</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1804">CVE-2014-1804</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1805">CVE-2014-1805</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2753">CVE-2014-2753</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2754">CVE-2014-2754</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2755">CVE-2014-2755</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2756">CVE-2014-2756</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2757">CVE-2014-2757</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2758">CVE-2014-2758</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2759">CVE-2014-2759</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2760">CVE-2014-2760</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2761">CVE-2014-2761</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2763">CVE-2014-2763</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2764">CVE-2014-2764</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2765">CVE-2014-2765</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2766">CVE-2014-2766</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2767">CVE-2014-2767</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2768">CVE-2014-2768</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2769">CVE-2014-2769</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2770">CVE-2014-2770</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2771">CVE-2014-2771</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2772">CVE-2014-2772</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2773">CVE-2014-2773</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2775">CVE-2014-2775</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2776">CVE-2014-2776</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2777">CVE-2014-2777</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2782">CVE-2014-2782</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Unicode Scripts Processor 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 악용 가능성 평가는 영향을 받는 Microsoft Windows 소프트웨어용입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Unicode Scripts Processor 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 악용 가능성 평가는 영향을 받는 Microsoft Office 소프트웨어용입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Unicode Scripts Processor 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 악용 가능성 평가는 영향을 받는 Microsoft Lync 소프트웨어용입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">GDI+ 이미지 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 악용 가능성 평가는 영향을 받는 Microsoft Windows 소프트웨어용입니다.<br />
<br />
이 취약점은 최신 소프트웨어의 서비스 거부 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">GDI+ 이미지 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 악용 가능성 평가는 영향을 받는 Microsoft Office 소프트웨어용입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">GDI+ 이미지 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 악용 가능성 평가는 영향을 받는 Microsoft Lync 소프트웨어용입니다.</td>
</tr>
</tbody>
</table>
  
영향을 받는 소프트웨어  
----------------------
  
<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
### Windows 운영 체제 및 구성 요소

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**낮음**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2957689)  
(중요)  
Internet Explorer 7  
(2957689)  
(중요)  
Internet Explorer 8  
(2957689)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Server 2003 서비스 팩 2  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(낮음)  
Microsoft XML Core Services 6.0  
(2957482)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2957689)  
(중요)  
Internet Explorer 7  
(2957689)  
(중요)  
Internet Explorer 8  
(2957689)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Server 2003 x64 Edition 서비스 팩 2  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(낮음)  
Microsoft XML Core Services 6.0  
(2957482)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2957689)  
(중요)  
Internet Explorer 7  
(2957689)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(낮음)  
Microsoft XML Core Services 6.0  
(2957482)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2957689)  
(긴급)  
Internet Explorer 8  
(2957689)  
(긴급)  
Internet Explorer 9  
(2957689)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Vista 서비스 팩 2  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2957689)  
(긴급)  
Internet Explorer 8  
(2957689)  
(긴급)  
Internet Explorer 9  
(2957689)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**낮음**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2957689)  
(중요)  
Internet Explorer 8  
(2957689)  
(중요)  
Internet Explorer 9  
(2957689)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2957689)  
(중요)  
Internet Explorer 8  
(2957689)  
(중요)  
Internet Explorer 9  
(2957689)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2957689)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
(긴급)  
Internet Explorer 9  
(2957689)  
(긴급)  
Internet Explorer 10  
(2957689)  
(긴급)  
Internet Explorer 11  
(2957689)  
(긴급)  
Internet Explorer 11  
(2963950)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2965788)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
(긴급)  
Internet Explorer 9  
(2957689)  
(긴급)  
Internet Explorer 10  
(2957689)  
(긴급)  
Internet Explorer 11  
(2957689)  
(긴급)  
Internet Explorer 11  
(2963950)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2965788)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**낮음**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
(중요)  
Internet Explorer 9  
(2957689)  
(중요)  
Internet Explorer 10  
(2957689)  
(중요)  
Internet Explorer 11  
(2957689)  
(중요)  
Internet Explorer 11  
(2963950)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(gdi32)  
(2964736)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2965788)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(gdi32)  
(2964736)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2965788)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
(긴급)  
Internet Explorer 11  
(2963950)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(gdi32)  
(2964736)  
(긴급)  
Windows 8.1(32비트 시스템용)  
(gdi32)  
(2965155)  
(긴급)  
Windows 8.1(32비트 시스템용)  
(DirectWrite)  
(2964718)  
(긴급)  
Windows 8.1(32비트 시스템용)  
(DirectWrite)  
(2965161)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(중요)  
Microsoft XML Core Services 3.0  
(2966631)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2957189)  
(중요)  
Windows 8.1(32비트 시스템용)  
(2961858)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2965788)  
(중요)  
Windows 8.1(32비트 시스템용)  
(2966034)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
(긴급)  
Internet Explorer 11  
(2963950)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(gdi32)  
(2964736)  
(긴급)  
Windows 8.1(x64 기반 시스템용)  
(gdi32)  
(2965155)  
(긴급)  
Windows 8.1(x64 기반 시스템용)  
(DirectWrite)  
(2964718)  
(긴급)  
Windows 8.1(x64 기반 시스템용)  
(DirectWrite)  
(2965161)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(중요)  
Microsoft XML Core Services 3.0  
(2966631)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2957189)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(2961858)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2965788)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(2966034)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**낮음**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(gdi32)  
(2964736)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2965788)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
(중요)  
Internet Explorer 11  
(2963950)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(gdi32)  
(2964736)  
(긴급)  
Windows Server 2012 R2  
(gdi32)  
(2965155)  
(긴급)  
Windows Server 2012 R2  
(DirectWrite)  
(2964718)  
(긴급)  
Windows Server 2012 R2  
(DirectWrite)  
(2965161)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(낮음)  
Microsoft XML Core Services 3.0  
(2966631)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2957189)  
(중요)  
Windows Server 2012 R2  
(2961858)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2965788)  
(중요)  
Windows Server 2012 R2  
(2966034)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(gdi32)  
(2964736)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(gdi32)  
(2964736)  
(긴급)  
Windows RT 8.1  
(DirectWrite)  
(2964718)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**낮음**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)(Windows GDI+)  
(2957503)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(Windows GDI+)  
(2957503)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(usp10)  
(2957509)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 및 Microsoft XML Core Services 6.0  
(2939576)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(gdi32)  
(2964736)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2957189)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2965788)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(gdi32)  
(2964736)  
(긴급)  
Windows Server 2012 R2(Server Core 설치)  
(gdi32)  
(2965155)  
(긴급)  
Windows Server 2012 R2(Server Core 설치)  
(DirectWrite)  
(2964718)  
(긴급)  
Windows Server 2012 R2(Server Core 설치)  
(DirectWrite)  
(2965161)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
(낮음)  
Microsoft XML Core Services 3.0  
(2966631)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(2957189)  
(중요)  
Windows Server 2012 R2(Server Core 설치)  
(2961858)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(2965788)  
(중요)  
Windows Server 2012 R2(Server Core 설치)  
(2966034)  
(중요)

</td>
</tr>
</table>
 
**MS14-036 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

### Office 제품군 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](https://go.microsoft.com/fwlink/?linkid=400971)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(2878233)  
(중요)  
Microsoft Office 2007 서비스 팩 3  
(2881069)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 서비스 팩 3  
(2880515)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](https://go.microsoft.com/fwlink/?linkid=400971)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)  
(2863942)  
(중요)  
Microsoft Office 2010 서비스 팩 1(32비트 에디션)  
(2767915)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)  
(2863942)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 에디션)  
(2767915)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)  
(2863942)  
(중요)  
Microsoft Office 2010 서비스 팩 1(64비트 에디션)  
(2767915)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)  
(2863942)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 에디션)  
(2767915)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 호환 기능 팩**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](https://go.microsoft.com/fwlink/?linkid=400971)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(2880513)  
(중요)

</td>
</tr>
</table>
 
**MS14-036 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

### Microsoft 통신 플랫폼 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007 콘솔**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](https://go.microsoft.com/fwlink/?linkid=400969)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 콘솔\[

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 콘솔  
(2968966)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](https://go.microsoft.com/fwlink/?linkid=400969)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)  
(2963285)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)  
(2963285)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(사용자 수준 설치)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(사용자 수준 설치)  
(2963282)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)  
(2963284)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2010

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2010  
(Web Components Server)  
(2963286)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](https://go.microsoft.com/fwlink/?linkid=400969)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013(32비트)  
(2881013)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(32비트)  
(2881013)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013(32비트)  
(2881013)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(32비트)  
(2881013)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013(64비트)  
(2881013)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(64비트)  
(2881013)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013(64비트)  
(2881013)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(64비트)  
(2881013)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2013

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Web Components Server)  
(2963288)  
(중요)

</td>
</tr>
</table>
 
**MS14-036 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

검색, 배포 도구 및 지침
-----------------------

<span id="sectionToggle3"></span>
관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 존재합니다.

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 구성 오류를 검색할 수 있습니다.

WSUS(Windows Server Update Services), SMS(Systems Management Server), System Center Configuration Manager는 관리자가 보안 업데이트를 배포하는 데 도움이 됩니다.

ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](https://technet.microsoft.com/security/cc297183)를 참조하십시오. 

감사의 말
---------

<span id="sectionToggle4"></span>
고객 보호를 위해 협력해 주신 다음 분들께 [감사](https://go.microsoft.com/fwlink/?linkid=21127)드립니다.

**MS14-030**

-   RDP MAC 취약점(CVE-2014-0296)을 보고해 주신 [Tripwire](https://www.tripwire.com/)의 Andrew Swoboda 및 Tyler Regulyor

     

**MS14-033**

-   MSXML 엔터티 URI 취약점(CVE-2014-1816)을 보고해 주신 Christian Kulenkampff

     

**MS14-034**

-   포함 글꼴 취약점(CVE-2014-2778)을 [VeriSign iDefense Labs](https://labs.idefense.com/)와 협력하여 보고해 주신 s3tm3m

     

**MS14-035**

-   Internet Explorer 메모리 손상 취약점(CVE-2014-0282)을 [HP(영문)](https://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Simon Zuckerbraun
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0282)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Renguang Yuan
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1762)을 보고해 주신 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)의 AbdulAziz Hariri, Matt Molinyawe, Jasiel Spelman
-   Internet Explorer 권한 상승 취약점(CVE-2014-1764)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [VUPEN](https://www.vupen.com/)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1766)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1766)을 [HP(영문)](https://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Andreas Schmidt
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1766)을 [VeriSign iDefense Labs](https://labs.idefense.com/)(영문)와 협력하여 보고해 주신 IronRock
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1766)을 [VeriSign iDefense Labs](https://labs.idefense.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1769)을 보고해 주신 [OUSPG(영문)](https://www.ee.oulu.fi/research/ouspg/)의 Atte Kettunen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1769)을 보고해 주신 [Qihoo 360(중문)](https://www.360.cn/)의 Liu Long
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1769)을 보고해 주신 [Qihoo 360(중문)](https://www.360.cn/)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1769)을 보고해 주신 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)의 AbdulAziz Hariri
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1769)을 보고해 주신 [NSFOCUS Security Team](https://www.nsfocus.com/)의 [Chen Zhang(demi6od)](https://weibo.com/demi6od)(중문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1770)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Corelan](https://www.corelangcv.com/)(영문)의 Peter 'corelanc0d3r' Van Eeckhoutte
-   TLS 서버 인증서 재협상 취약점(CVE-2014-1771)을 보고해 주신 Institut National de Recherche en Informatique et en Automatique (INRIA)의 Prosecco 팀
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1772)을 [VeriSign iDefense Labs(영문)](https://labs.idefense.com/)와 협력하여 보고해 주신 [Omair](https://krash.in/)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1772)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Liu Long
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1772)을 보고해 주신 [Trend Micro](https://www.trendmicro.com/)(영문)의 Jack Tang
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1772)을 보고해 주신 [Venustech Active-Defense Laboratory](https://www.venustech.com.cn/)(중문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1773)을 보고해 주신 John Villamil 및 Sean Larsson
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1773)을 보고해 주신 [NSFOCUS Security Team](https://www.nsfocus.com/)의 [Chen Zhang(demi6od)](https://weibo.com/demi6od)(중문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1774)을 [HP(영문)](https://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 AMol NAik
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1775)을 [HP(영문)](https://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Harmony Security](https://www.harmonysecurity.com/)(영문)의 Stephen Fewer
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1775)을 보고해 주신 [Palo Alto Networks(영문)](https://www.paloaltonetworks.com/)의 Hui Gao
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1775)을 보고해 주신 TELUS Security Labs, Vulnerability Research Team의 Arezou Hosseinzad-Amirkhizi
-   Internet Explorer 정보 유출 취약점(CVE-2014-1777)을 보고해 주신 [Context Information Security(영문)](https://www.contextis.com/)의 James Forshaw
-   Internet Explorer 권한 상승 취약점(CVE-2014-1778)을 보고해 주신 [Context Information Security](https://www.contextis.com/)(영문)의 James Forshaw
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1779)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1780)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Soroush Dalili](https://www.secproject.com/)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1781)을 보고해 주신 [NSFOCUS Security Team](https://www.nsfocus.com/)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1782)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 lokihardt@ASRT
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1782)을 보고해 주신 [Qihoo 360(중문)](https://www.360.cn/)의 Liu Long
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1782)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Zhibin Hu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1782)을 보고해 주신 [Trend Micro](https://www.trendmicro.com/)(영문)의 Yuki Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1782)을 보고해 주신 [knownsec](https://www.knownsec.com/)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1782)을 [iSIGHT Partners GVP Program](https://gvp.isightpartners.com/)(영문)과 협력하여 보고해 주신 35c27308b34d55904da10770e5303503
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1782)을 [VeriSign iDefense Labs](https://labs.idefense.com/)(영문)와 협력하여 보고해 주신 IronRock
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1782)을 [VeriSign iDefense Labs](https://labs.idefense.com/)(영문)와 협력하여 보고해 주신 Sabre
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1783)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1784)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1784)을 보고해 주신 [Palo Alto Networks(영문)](https://www.paloaltonetworks.com/)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1784)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Zhibin Hu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1785)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 SkyLined
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1785)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1785)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1786)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1788)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1789)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1789)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1790)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1791)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1792)을 [VeriSign iDefense Labs(영문)](https://labs.idefense.com/)와 협력하여 보고해 주신 [Corelan](https://www.corelangcv.com/)(영문)의 Peter 'corelanc0d3r' Van Eeckhoutte
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1792)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1794)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1795)을 보고해 주신 [FireEye](https://www.fireeye.com/)(영문)의 Xiaobo Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1796)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Hui Gao
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1797)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative(영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Gareth Heyes
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1799)을 보고해 주신 [Qihoo 360(중문)](https://www.360.cn/)의 Zhibin Hu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1799)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1799)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 0016EECD9D7159A949DAD3BC17E0A939
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1799)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Sweetchip
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1799)을 [VeriSign iDefense Labs](https://labs.idefense.com/)(영문)와 협력하여 보고해 주신 Sabre
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1799)을 보고해 주신 [NCC Group](https://www.nccgroup.com/)(영문)의 Edward Torkington
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1800)을 [HP(영문)](https://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 SkyLined
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1802)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1803)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1804)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Royce Lu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1804)을 보고해 주신 [Trend Micro](https://www.trendmicro.com/)(영문)의 Yuki Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-1805)을 [HP(영문)](https://www.hpenterprisesecurity.com/products)의[Zero Day Initiative(영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 lokihardt@ASRT
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2753)을 보고해 주신 [Qihoo 360(중문)](https://www.360.cn/)의 Liu Long
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2754)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Liu Long
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2755)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Xin Ouyang
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2755)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Zhibin Hu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2756)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2756)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 0016EECD9D7159A949DAD3BC17E0A939
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2757)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative(영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Simon Zuckerbraun
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2758)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2759)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2759)을 [VeriSign iDefense Labs](https://labs.idefense.com/)(영문)와 보고해 주신 Sabre
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2760)을 보고해 주신 [Qihoo 360(중문)](https://www.360.cn/)의 Zhibin Hu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2761)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2761)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 0016EECD9D7159A949DAD3BC17E0A939
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2763)을 보고해 주신 [Qihoo 360](https://www.360.cn/)(중문)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2764)을 보고해 주신 [Qihoo 360(중문)](https://www.360.cn/)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2764)을 보고해 주신 [NSFOCUS Security Team](https://www.nsfocus.com/)(영문)의 [Chen Zhang(demi6od)](https://weibo.com/demi6od)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2764)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2765)을 보고해 주신 [Palo Alto Networks(영문)](https://www.paloaltonetworks.com/)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2766)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2767)을 보고해 주신 [Palo Alto Networks(영문)](https://www.paloaltonetworks.com/)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2768)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2768)을 보고해 주신 [Trend Micro](https://www.trendmicro.com/)(영문)의 Yuki Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2769)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2769)을 보고해 주신 [Venustech Active-Defense Laboratory](https://www.venustech.com.cn/)(중문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2770)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Xin Ouyang
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2771)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Royce Lu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2772)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Harmony Security](https://www.harmonysecurity.com/)(영문)의 Stephen Fewer
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2773)을 보고해 주신 [Keen Team](https://www.k33nteam.org/)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2773)을 보고해 주신 [Palo Alto Networks](https://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2775)을 보고해 주신 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)의 AbdulAziz Hariri
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2776)을 보고해 주신 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)의 AbdulAziz Hariri
-   Internet Explorer 권한 상승 취약점(CVE-2014-2777)을 [HP](https://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](https://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [VUPEN](https://www.vupen.com/)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2782)을 [HP(영문)](https://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative(영문)](https://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   이 공지에 포함된 심층 보안 변경 사항에 대해 Microsoft와 협력해 주신 [Cyber Defense Institute, Inc.](https://www.cyberdefense.jp/)(영문)의 Noriaki Iwasaki

     

**MS14-036**

-   Unicode Scripts Processor 취약점(CVE-2014-1817)을 보고해 주신 [Security-Assessment.com](https://www.security-assessment.com/)(영문)의 Scott Bell
-   GDI+ 이미지 구문 분석 취약점(CVE-2014-1818)을 보고해 주신 [Google Security Team](https://www.google.com/)(영문)의 Mateusz Jurczyk, Ivan Fratric 및 Ben Hawkes

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 버전에서 Microsoft는 Windows 업데이트, Microsoft 업데이트, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 발표에서 사용할 수 없습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows 업데이트 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](https://technet.microsoft.com/wsus/bb456965). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](https://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](https://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft 업데이트](https://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows 업데이트를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](https://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](https://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.

IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](https://technet.microsoft.com/security/bb980617)

Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](https://support.microsoft.com/contactus/cu_sc_virsec_master)

국가별 현지 지원: [국가별 지원](https://support.microsoft.com/common/international.aspx)

### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 개정 내역

-   V1.0(2014년 6월 11일): 공지 요약이 게시되었습니다.
-   V1.1(2014년 6월 18일): MS14-035에는 CVE-2014-2782의 악용 가능성 인덱스에 대한 악용 가능성 평가가 추가되었습니다. 이 변경 사항은 정보에만 해당됩니다.

*2014년 9월 24일 11:25Z-07:00에 페이지가 생성되었습니다.*
