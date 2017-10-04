---
TOCTitle: RMS Management Pack 가져오기 및 사용
Title: RMS Management Pack 가져오기 및 사용
ms:assetid: 'd9a73ef0-2f81-48c2-97cc-deb7bf477389'
ms:contentKeyID: 18123088
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc747688(v=WS.10)'
---

RMS Management Pack 가져오기 및 사용
====================================

RMS Management Pack 가져오기 및 사용
------------------------------------

#### RMS Management Pack 가져오기 및 사용

1.  RMS Management Pack(RMS\_MOMPack.akm)을 %ProgramFiles%\\Windows Rights Management Services\\Tools 폴더에서 Microsoft Operations Manager(MOM) 서버로 복사합니다.

2.  MOM 관리자 콘솔을 열고 다음 단계를 사용하여 RMS Management Pack을 가져옵니다.

    1.  MOM 관리자 콘솔의 콘솔 트리에서 **규칙** 항목을 확장한 다음, **처리 규칙 그룹** 항목을 마우스 오른쪽 단추로 클릭합니다.
    2.  바로 가기 키 메뉴에서 **Management Pack 가져오기**를 클릭합니다. **Management Pack 가져오기** 대화 상자가 표시됩니다.
    3.  **찾아보기**를 클릭한 다음, RMS\_MOMPack.akm을 선택합니다.

3.  병합 또는 바꾸기 옵션을 지정합니다. 병합 및 바꾸기 옵션에 대한 자세한 내용은 Microsoft 웹 사이트(http://www.microsoft.com/)에서 "Management Pack 내보내기 및 가져오기"를 참조하십시오.

    **바꾸기**를 클릭합니다. 바꾸기 옵션을 사용하면 가져온 Management Pack이 기존 처리 규칙 그룹을 덮어쓰고 사용자 설명은 보존되지 않습니다. 이 Management Pack을 기존 Management Pack과 병합하려면 테스트 환경에서 수행한 다음, 프로덕션 환경에서 Management Pack을 배포할 때 **바꾸기** 옵션을 사용해야 합니다.

4.  **가져오기**를 클릭하여 Management Pack을 가져옵니다.

5.  **MOM 관리자** 콘솔에서 **구성** 항목을 선택한 다음, **Agent Managers** 폴더를 클릭합니다.

6.  RMS Management Pack을 가져온 서버의 이름을 마우스 오른쪽 단추로 클릭한 다음, **관리되는 컴퓨터 지금 스캔**을 선택합니다.
