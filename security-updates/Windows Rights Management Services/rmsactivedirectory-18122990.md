---
TOCTitle: RMS에 대한 Active Directory 지원
Title: RMS에 대한 Active Directory 지원
ms:assetid: '9589127d-19b3-44f1-b7a1-01992e78218a'
ms:contentKeyID: 18122990
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc747604(v=WS.10)'
---

RMS에 대한 Active Directory 지원
================================

RMS는 Active Directory를 다음 용도로 사용합니다.

-   **사용자 인증 제공.** Active Directory는 RMS 사용자를 인증하는 데 사용되는 디렉터리 서비스를 제공합니다. 인증 및 RMS에 대한 자세한 내용은 이 항목 뒷부분의 "[RMS 보안 모델](https://technet.microsoft.com/665db831-366d-4dca-9bb3-cc2912481fe1)"을 참조하십시오.
-   **그룹 구성원 및 개별 사용자 계정 ID 확인.** Active Directory는 게시 라이센스가 개별 사용자 계정이 아닌 그룹에 권한을 부여할 때 RMS로 보호된 콘텐츠에 사용 라이센스를 부여하기 위해 RMS가 사용하는 그룹 구성원에 대한 정보를 제공합니다. Active Directory에 대한 LDAP 쿼리 수를 줄이기 위해 RMS는 중앙 디렉터리 서비스 데이터베이스뿐만 아니라 로컬 캐시에서 얻은 정보를 캐시합니다. 자세한 내용은 이 항목 앞부분의 "[RMS Active Directory 캐시](https://technet.microsoft.com/c721a2eb-2fe9-4346-b426-3cc169b97265)" 및 "[RMS 디렉터리 서비스 데이터베이스](https://technet.microsoft.com/6f6b8586-5d17-4a40-94a3-4dc738195301)"를 참조하십시오.
-   **RMS 서비스 검색 위치 저장.** 요청을 허가하는 웹 서비스의 실행 모듈의 URL로 서비스 요청(예: 사용 라이센스, 게시 라이센스 또는 라이센스 서버의 하위 등록)을 보내야 합니다. 모든 서비스 요청은 서버 웹 서비스(Server.asmx)의 URL에 대한 Active Directory 쿼리로 시작되며 이것은 서비스 요청에 적합한 URL을 제공합니다. 자세한 내용은 이 항목 뒷부분의 "[RMS 서비스 게시 및 검색](https://technet.microsoft.com/336c0d55-fd7f-4aa9-b3e6-bfd6565b1086)"을 참조하십시오.
