
**HDxBuilder Python Project**

 - Django, Fastapi 비교 기술 검토 진행
 - 사내 Spring 기반의 템플릿을 분석하여 장고 코드 템플릿 및 라이브러리로 개발 진행
    - SSO 로그인 정보 레디스 확인 , 공통 DTO, 예외처리, 로깅 등
 - 사내망에서 pip install 이 원활하게 가능하도록 nexus respository 구성
 - 기존 gitlab runner 환경을 활용한 ci/cd 구성 (Docker 활용)
 - 장고 테스트용 웹사이트를 개발하는 과정을 통해, 기존 AJP 설정  변경 및 개발 가이드 제공
 - 개발 진행 사항 공유를 위한 깃랩 위키 및 프로젝트 대시보드 사용 제안 및 구성

**HDMocean AppStore Project**

- 각 회사별, 직급별 어플리케이션 조회, 신청 권한 설계 및 개발
- 조건별 등록된 어플리케이션 검색 기능 개발
- JPA를 사용하여 기능 개발 후 MyBatis 를 사용하여 한방 쿼리로 API 개선 작업 진행 
- 운영중 발생한  오류 로그 분석을 위한 파이썬 프로그램 개발 및 팀 공유
    - Jmeter 를 사용, 부하 테스트 진행  로그인 로직의  JPA - DBLock 발견 및 수정


**YadrdLif**
 - 사내 개발 플랫폼 HDxBuilder Web 기반 운영 업무
 - 기능 개선 (사내 유투브 리다이렉션,사보 조회 등)
 - 사내 식당 식단 정보 조회 구조 개선
   - 외부 시스템의 DB로 부터 식단 정보를 DB링크를 통해 불러오는 구조에서 발생하는 오류를 해결

**WATCH DOG**
 - SpringBoot Actuator 사용, 서버의 메트릭 값 모니터링 및 메일 알람 전송 기능