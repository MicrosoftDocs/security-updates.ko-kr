---
TOCTitle: 'Microsoft 가상 사설망으로 차단 서비스 구현 계획 가이드 - 부록 B'
Title: 'Microsoft 가상 사설망으로 차단 서비스 구현 계획 가이드 - 부록 B'
ms:assetid: '988f3c4d-0801-47ec-9d1d-617fbc83ca26'
ms:contentKeyID: 20214120
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Dd547965(v=TechNet.10)'
---

Microsoft 가상 사설망으로 차단 서비스 구현 계획 가이드
======================================================

### 부록 B - 원격 액세스 임시 차단 서비스 매개 변수

업데이트 날짜: 2005년 5월 24일

원격 액세스 임시 차단 서비스를 설치하면 레지스트리에 항목이 여러 개 만들어지므로 아래 나와 있는 항목을 변경할 수 있습니다.   

**참고:** 레지스트리 편집기를 잘못 사용하면 운영 체제를 다시 설치해야 할 수도 있는 심각한 문제가 발생할 수 있습니다. 레지스트리 편집기를 잘못 사용해서 발생하는 문제는 해결할 수 있다는 보장이 없습니다. 레지스트리 편집기 사용에 대한 위험 부담은 사용자에게 있습니다.

레지스트리 매개 변수를 구성하기 위한 전체 경로는 다음과 같습니다.

HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\rqs

구성할 수 있는 매개 변수는 다음과 같습니다.

-   **AllowedSet**. AllowedSet 매개 변수를 사용하면 원격 액세스 VPN 차단 서버에서 받아들이는 스크립트의 버전을 설정할 수 있습니다.
    
    ```
        AllowedSet, REG_MULTI_SZ
    ```

서비스에서 차단을 제거할 목적으로 받아들이는 문자열 목록은 다음과 같습니다.

-   **Port(REG\_DWORD)**. Port 매개 변수는 RQS 서비스가 수신하는 TCP 포트를 지정합니다. 포트가 지정되지 않은 경우에 7250이 사용됩니다.

-   **Authenticator(REG\_SZ)**. 차단을 제거하기 위해 호출할 모듈을 지정합니다. 기본값은 mprapi.dll입니다.

    사용자 지정 DLL을 만들어 차단 필터 제거 기능을 구현하면 다음과 같은 함수가 표시됩니다.

    
        ```
            DWORD MprAdminConnectionRemoveQuarantine  
            (HANDLE hRasServer,  HANDLE hRasConnection,  BOOL fIsIpAddress)  
        ```

-   **Validator(REG\_SZ)**. 서명 문자열을 보낸 내 RQC가 적합한지 여부를 확인하는 모듈을 지정합니다. 기본적으로 RQS.exe는 AllowedSet 문자열을 비교합니다. 사용자 지정 authenticator dll은 다음과 같은 함수를 표시해야 합니다.

    
        ```
            BOOL ClientAuthenticate(LPCWSTR lpwsString). 
        ```
    인증할 문자열을 포함하는 lpwsString

[](#mainsection)[페이지 위쪽](#mainsection)

##### 다운로드

[Microsoft 가상 사설망으로 차단 서비스 구현 계획 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=41308)

[](#mainsection)[페이지 위쪽](#mainsection)
