---
TOCTitle: Microsoft Operations Manager를 사용하여 모니터링
Title: Microsoft Operations Manager를 사용하여 모니터링
ms:assetid: 'ce372598-7421-4f1f-b8eb-f62da26e85d1'
ms:contentKeyID: 18123095
ms:mtpsurl: 'https://technet.microsoft.com/ko-kr/library/Cc747758(v=WS.10)'
---

Microsoft Operations Manager를 사용하여 모니터링
================================================

RMS에는 MOM(Microsoft® Operations Manager)과 함께 사용할 수 있는 Management Pack이 포함되어 있습니다. 다음을 수행하면 MOM을 사용하여 조직에 있는 서버의 작업을 관리할 수 있습니다.

-   RMS가 응용 프로그램 이벤트 로그에 구축하는 이벤트를 모니터링합니다.
-   교정 조치 또는 예방 조치를 신속하게 수행할 수 있도록 서비스 정지 또는 구성 문제를 나타낼 수 있는 이벤트를 강조합니다.
-   서버 사용 허가자 인증서의 만료 또는 웹 서비스의 실패와 같은 경고 및 오류를 알립니다.

RMS Management Pack(RMS\_MOMPack.akm)은 RMS와 함께 %programfiles%\\Windows Rights Management Services\\Tools 폴더에 설치됩니다.

이 Management Pack에는 RMS 관리자가 RMS 서버 배포를 관리하는 데 사용할 수 있는 다음과 같은 규칙 집합이 들어 있습니다.

**RMS MOM Management Pack 규칙**

1.  PMC 측정 - 활성화 프록시 총 실패 수
2.  PMC 측정 - 활성화 프록시 총 시간
3.  PMC 측정 - 활성화 총 처리 시간
4.  PMC 측정 - 활성화 총 요청 수
5.  PMC 측정 - ActivationProxy 총 요청 수
6.  PMC 측정 - AD 캐시(DB 캐시) 적중 횟수
7.  PMC 측정 - AD 캐시(DB 캐시) 누락 횟수
8.  PMC 측정 - 평균 라이센스 처리 시간
9.  이벤트 - 구성 정보 손상
10. PMC 측정 - 끊어진 GC 연결
11. PMC 측정 - 등록 실패 횟수
12. 이벤트 - 일반 오류
13. 이벤트 - 초기화 실패
14. 이벤트 - 사용 허가자 인증서 만료됨
15. 이벤트 - 사용 허가자 인증서 요청 실패
16. 이벤트 - 로깅 서비스 실패
17. PMC 측정 - 사용 가능한 최대 GC 연결 수
18. 이벤트 - 라이센스 취득 지점 생성 플러그인 없음
19. PMC 측정 - 모든 RM 서버의 MSMQ 대기열 길이
20. 이벤트 - 사용 가능한 GC 없음
21. 이벤트 - 플러그인 초기화 실패
22. 이벤트 - 개인 키 보호 암호 변경됨
23. 이벤트 - RM 서버 종료
24. 이벤트 - RM 서버 종료 실패
25. 이벤트 - 서버 시작 실패
26. PMC 측정 - 하위 등록 실패
27. 이벤트 - SuperUser 권한에 있는 무시 기능 호출됨
28. PMC 임계값 - 라이센스 허가 인증서 가져오기 실패 횟수가 너무 많음
29. 이벤트 - 예정된 사용 허가자 인증서 만료 - 한 달
30. 이벤트 - 예정된 사용 허가자 인증서 만료 - 일주일

조직에 MOM 관리 팩 배포 방법에 대한 자세한 내용은 [Microsoft 웹 사이트](http://www.microsoft.com/)(http://www.microsoft.com/)를 참조하십시오.
