---
TOCTitle: 'MS10-NOV'
Title: 2010 년 11 월 Microsoft 보안 공지 요약
ms:assetid: 'ms10-nov'
ms:contentKeyID: 61230729
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms10-nov(v=Security.10)'
---


2010 년 11 월 Microsoft 보안 공지 요약
======================================

게시된 날짜: 2010년 11월 10일 수요일 | 업데이트된 날짜: 2011년 4월 14일 목요일

**버전:** 2.1

이 공지 요약 목록에는 2010년 11월 발표된 보안 공지가 포함되어 있습니다.

2010년 11월 공지 발표와 함께 이 공지 요약이 2010년 11월 4일 게시된 공지 사전 알림을 대체합니다. 공지 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2010년 11월 10일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [11월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032454441). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

요약
----

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향을 받는 소프트웨어 및 다운로드 위치**를 참조하십시오.

 
<p></p>
<table style="border:1px solid black;">
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-087">MS10-087</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점(2423930)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office의 공개된 취약점 1건과 비공개로 보고된 취약점 5건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 특수하게 조작된 RTF 메일 메시지를 열거나 미리 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-088">MS10-088</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점(2293386)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 취약점 2건을 해결합니다. 사용자가 특수하게 조작된 PowerPoint 파일을 열면 이러한 Microsoft Office 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 어느 것이든 성공적으로 악용한 경우 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-089">MS10-089</a></td>
<td style="border:1px solid black;"><strong>Forefront UAG(Unified Access Gateway)의 취약점으로 인한 권한 상승 문제점(2316074)</strong><br />
<br />
이 보안 업데이트는 Forefront UAG(Unified Access Gateway)에서 비공개적으로 보고된 취약점 4건을 해결합니다. 이 중 가장 심각한 취약점으로 인해 사용자가 특수하게 조작된 URL을 사용하여 영향 받는 웹 사이트를 방문할 경우 권한 상승이 허용될 수 있습니다. 그러나 공격자는 강제로 사용자가 이러한 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Forefront United Access Gateway</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 악용 가능성 평가 수준 내림차순 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](http://technet.microsoft.com/ko-kr/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                                  | 취약점 제목                                                                               | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                        | 주요 정보                                                                                     |  
|----------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|  
| [MS10-088](http://technet.microsoft.com/security/bulletin/ms10-088)        | PowerPoint 구문 분석 버퍼 오버플로 취약점                                                 | [CVE-2010-2572 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2572) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |  
| [MS10-089](http://technet.microsoft.com/security/bulletin/ms10-089)        | UAG XSS EOP 허용 취약점                                                                   | [CVE-2010-2733 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2733) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |  
| [MS10-089](http://technet.microsoft.com/security/bulletin/ms10-089)        | Forefront Unified Access Gateway의 UAG 모바일 포털 웹 사이트에서 나타나는 XSS 문제 취약점 | [CVE-2010-2734 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2734) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |  
| [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087)        | RTF 스택 버퍼 오버플로 취약점                                                             | [CVE-2010-3333 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3333) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |  
| [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087)        | Office Art 그리기 레코드 취약점                                                           | [CVE-2010-3334 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3334) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |  
| [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087)        | 그리기 예외 처리 취약점                                                                   | [CVE-2010-3335 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3335) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |  
| [MS10-087 (영문)](http://technet.microsoft.com/security/bulletin/ms10-087) | 안전하지 않은 라이브러리 로드 취약점                                                      | [CVE-2010-3337 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3337) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 공개되었습니다.**                                                               |  
| [MS10-089](http://technet.microsoft.com/security/bulletin/ms10-089)        | Signurl.asp의 XSS 취약점                                                                  | [CVE-2010-3936 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3936) | [**1**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                        |  
| [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087)        | PowerPoint 정수 언더플로로 인한 힙 손상 취약점                                            | [CVE-2010-2573 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2573) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | [MS10-088](http://technet.microsoft.com/security/bulletin/ms10-088)도 이 취약점을 해결합니다. |  
| [MS10-088](http://technet.microsoft.com/security/bulletin/ms10-088)        | PowerPoint 정수 언더플로로 인한 힙 손상 취약점                                            | [CVE-2010-2573 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2573) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087)도 이 취약점을 해결합니다. |  
| [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087)        | MSO 대형 SPID 읽기 AV 취약점                                                              | [CVE-2010-3336 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3336) | [**2**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                        |  
| [MS10-089](http://technet.microsoft.com/security/bulletin/ms10-089)        | UAG 리디렉션 스푸핑 취약점                                                                | [CVE-2010-2732 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2732) | [**3**](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점은 단지 스푸핑 취약점입니다.                                                         |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 제품군 및 구성 요소  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-087**](http://technet.microsoft.com/security/bulletin/ms10-087)
</td>
<td style="border:1px solid black;">
[**MS10-088**](http://technet.microsoft.com/security/bulletin/ms10-088)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=f32648e3-2fb5-472c-932f-360e5d3c0931&displaylang=ko)  
(KB2289169)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2002 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=3efbf9f6-734a-46ac-8f92-87b6ec819bfa&displaylang=ko)  
(KB2413272)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=07a6cf76-2cea-4c54-b66d-50e9eed108ac&displaylang=ko)  
(KB2289187)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2003 서비스 팩 3](https://www.microsoft.com/download/details.aspx?familyid=108286d4-fb68-40d6-a7b1-64b3a4eb87ee&displaylang=ko)  
(KB2413304)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=be0c5878-60c0-4700-8836-50d369b51d04&displaylang=ko)  
(KB2289158)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010(32비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=0b308508-0e1e-4e90-b2b8-7e32bfc5dbf4&displaylang=ko)  
(KB2289161)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010(64비트 에디션)](https://www.microsoft.com/download/details.aspx?familyid=534c6a2a-e7c6-4adf-8b81-e009a2b5fff4&displaylang=ko)  
(KB2289161)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-087**](http://technet.microsoft.com/security/bulletin/ms10-087)
</td>
<td style="border:1px solid black;">
[**MS10-088**](http://technet.microsoft.com/security/bulletin/ms10-088)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac<sup>[1]</sup>
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ad1b1984-b2b2-49b3-a1dd-385b77d9248a)  
(KB2476512)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=8bd6ca3b-8004-4e8d-a09d-220dcbbce799)  
(KB2454823)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=b846d255-a7d4-4a2c-a084-d434c29fe676)  
(KB2476511)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
기타 Office 소프트웨어
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-087**](http://technet.microsoft.com/security/bulletin/ms10-087)
</td>
<td style="border:1px solid black;">
[**MS10-088**](http://technet.microsoft.com/security/bulletin/ms10-088)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint Viewer 2007 서비스 팩 2](https://www.microsoft.com/download/details.aspx?familyid=df826b79-7398-45de-943c-6f6f0af1b4e3&displaylang=ko)  
(KB2413381)  
(중요)
</td>
</tr>
</table>
 
**MS10-087 참고 사항**

<sup>[1]</sup>Microsoft Office 2004 for Mac(KB2505924)용 보안 업데이트는 2011년 4월 12일에 발표되었습니다. 자세한 내용은 공지를 참조하십시오.

**MS10-088 참고 사항**

<sup>[1]</sup>Microsoft Office 2004 for Mac(KB2505924)용 보안 업데이트는 2011년 4월 12일에 발표되었습니다. 자세한 내용은 공지를 참조하십시오.

#### Microsoft 원격 액세스 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Forefront Unified Access Gateway
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-089**](http://technet.microsoft.com/security/bulletin/ms10-089)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Unified Access Gateway
</td>
<td style="border:1px solid black;">
[Forefront Unified Access Gateway 2010](https://www.microsoft.com/download/details.aspx?familyid=5f2ee08e-e289-47db-bd3f-7b9cfc1eb985)<sup>[1]</sup>
(KB2433585)  
(중요)  
[Forefront Unified Access Gateway 2010 업데이트 1](https://www.microsoft.com/download/details.aspx?familyid=db0b70c8-1fa5-4d92-9888-3500c7566b19)<sup>[1]</sup>
(KB2433584)  
(중요)  
[Forefront Unified Access Gateway 2010 업데이트 2](https://www.microsoft.com/download/details.aspx?familyid=4e3ee07a-771c-46ee-959f-82389bab67d7)<sup>[1]</sup>
(KB2418933)  
(중요)
</td>
</tr>
</table>
 
**MS10-089 참고 사항**

<sup>[1]</sup>이 업데이트는 Microsoft 다운로드 센터에서만 다운로드할 수 있습니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](http://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://go.microsoft.com/fwlink/?linkid=22939)를 참조하십시오. SMS 2.0 사용자는 SUIT(Security Update Inventory Tool)을 사용하여 보안 업데이트 배포를 지원할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2.0 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트 (영문)](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](http://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS10-087에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS10-087에서 설명한 문제점을 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)와 협력하여 보고해 주신 [team509 (영문)](http://www.team509.com/)
-   MS10-087에서 설명한 문제점을 보고해 주신 [Secunia (영문)](http://secunia.com/)의 Dyon Balding
-   MS10-087에서 설명한 문제점을 보고해 주신 [CERT Coordination Center (영문)](http://www.cert.org/)의 Will Dorman
-   MS10-087에서 설명한 문제점을 보고해 주신 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)
-   MS10-087에서 설명한 문제점을 보고해 주신 [VUPEN Vulnerability Research Team (영문)](http://www.vupen.com/)의 Chaouki Bekrar
-   MS10-087에서 설명한 문제점을 보고해 주신 [Fortinet's FortiGuard Labs (영문)](http://www.fortiguard.com/)의 Haifei Li
-   MS10-087에서 설명한 문제점을 보고해 주신 [ACROS Security (영문)](http://www.acrossecurity.com)의 Simon Raner
-   MS10-088에서 설명한 문제점을 보고해주신 [Secunia Research (영문)](http://secunia.com/)의 Alin Rad Pop
-   MS10-088에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS10-089에서 설명한 문제점을 해결하기 위해 협력해 주신 [BugSec (영문)](http://www.bugsec.com/)의 Eyal Gruner

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2010년 11월 10일): 공지 요약이 게시되었습니다.
-   V1.1(2010년 11월 11일): MS10-088에서 영향을 받는 버전이 "Microsoft PowerPoint Viewer"에서 "Microsoft PowerPoint Viewer 2007 서비스 팩 2"로 수정되었습니다. 이 변경 사항은 정보에만 해당됩니다. 자동 업데이트를 사용하는 고객을 포함하여 이미 시스템을 성공적으로 업데이트한 고객은 추가 조치를 취할 필요가 없습니다. 이전에 이 업데이트를 설치하지 않은 고객은 개정된 영향을 받는 소프트웨어에 따라 시스템에 이 업데이트가 필요한지 다시 평가해야 할 수 있습니다.
-   V1.2(2010년 11월 18일): MS10-087에서 CVE-2010-2573을 이 업데이트에서 해결하는 취약점으로 추가하기 위해 악용 가능성 인덱스가 수정되었습니다. 이 변경 사항은 정보에만 해당됩니다.
-   V2.0(2010년 12월 16일): MS10-087에서 Microsoft Office 2008 for Mac(KB2476512) 및 Open XML File Format Converter for Mac(KB2476511)용 보안 업데이트가 제공됨을 알리기 위해 이 공지 요약을 개정하였습니다. 이러한 소프트웨어의 사용자는 가능한 빨리 이 업데이트를 적용하는 것이 좋습니다.
-   V2.1(2011년 4월 14일): Microsoft Office 2004 for Mac(KB2505924)용 보안 업데이트가 제공됨을 알리기 위해 이 공지 요약을 개정하였습니다. 자세한 내용은 MS10-087 및 MS10-088을 참조하십시오.

*Built at 2014-04-18T12:27:44Z-07:00*
