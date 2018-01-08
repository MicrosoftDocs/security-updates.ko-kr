---
TOCTitle: 'Microsoft SQL Server 2000 Desktop Engine(MSDE 2000)을 설치하여 RMS에 데이터베이스 지원 제공'
Title: 'Microsoft SQL Server 2000 Desktop Engine(MSDE 2000)을 설치하여 RMS에 데이터베이스 지원 제공'
ms:assetid: 'c9b9cd08-98c4-424f-b3fc-d685f57c002e'
ms:contentKeyID: 18123055
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc747667(v=WS.10)'
---

Microsoft SQL Server 2000 Desktop Engine(MSDE 2000)을 설치하여 RMS에 데이터베이스 지원 제공
===========================================================================================

Microsoft SQL Server 2000 Desktop Engine(MSDE 2000)을 설치하여 RMS에 데이터베이스 지원 제공
-------------------------------------------------------------------------------------------

#### Microsoft SQL Server 2000 Desktop Engine(MSDE 2000)을 설치하여 RMS에 데이터베이스 지원 제공

1.  Microsoft SQL Server Desktop Engine(MSDE 2000)을 설치할 서버에 있는 로컬 관리자 그룹 구성원의 도메인 계정을 사용하여 로그온합니다.

2.  [Microsoft 웹 사이트](http://www.microsoft.com/)(http://www.microsoft.com/)에서 MSDE 2000을 다운로드하여 컴퓨터에 저장합니다.

3.  MSDE2000A.exe 파일을 실행하여 MSDE 2000 설치 패키지를 폴더에 추출합니다. 이 폴더의 이름은 기본적으로 MSDERelA지만 다른 이름을 지정할 수도 있습니다.

4.  명령 프롬프트를 열고 MSDE 2000 설치 파일을 저장한 위치를 찾습니다.

5.  다음 명령을 입력하여 RMS에서 작동할 수 있는 구성으로 Microsoft SQL Server 2000 Desktop Engine 응용 프로그램을 설정하고 *암호*를 강력한 암호로 정하여 바꿉니다.

    **Setup.exe /i setup\\sqlrun10.msi INSTANCENAME=RMS DISABLEAGENTSTARTUP=1 SAPWD**=*password*

    > [!Important]  
    > 설치가 끝나면 MSDE 서비스를 시작해야 합니다. MSDE 서비스는 **제어판**의 **서비스**에서 시작할 수 있습니다. RMS를 실행하는 경우에는 MSDE 데이터베이스를 항상 사용할 수 있도록 서비스가 자동으로 시작되도록 구성하는 것이 좋습니다. 

데이터베이스를 설치하여 RMS 구성 데이터베이스를 지원하기 전에는 서버에 RMS를 구축하지 마십시오.

Microsoft SQL Server Desktop Engine에는 엔터프라이즈 전체 데이터베이스를 완전히 작동하고 지원하는 데 필요한 도구가 없기 때문에 테스트 환경에서만 Microsoft SQL Server Desktop Engine을 사용하여 RMS 데이터베이스를 지원하는 것이 좋습니다. 또한 MSDE는 원격 네트워킹을 지원하지 않기 때문에 RMS와 동일한 서버에 설치해야 하며 RMS 클러스터에 RMS 서버를 더 추가할 수 없습니다. Microsoft SQL Server Desktop Engine의 사용 약관에는 SQL Server 클라이언트 도구를 사용하여 Microsoft SQL Server Desktop Engine 데이터베이스를 조작할 수 없도록 명시되어 있습니다. 이러한 제한 사항 때문에 RMS 구성 데이터베이스를 백업하고 복원할 수 없으며 구성 데이터베이스에 저장된 데이터를 보거나 직접 변경할 수도 없습니다.
