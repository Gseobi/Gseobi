### Backend Developer KIM JISEOP

## 📌 About Me

중단되지 않는 시스템과 **운영 안정성**을 중심에 두고 개발하는  
**Java Backend Developer**입니다.

실제 서비스 운영 환경에서  
결제(PG) 연동, 장기 실행 Daemon, Scheduler,  
지연 딥링크(Deferred Deep Link) 등  
**운영 민감도가 높은 백엔드 시스템을 직접 설계·구현·운영**해왔습니다.

- Java / Spring 기반 Backend API 설계·개발·운영
- 다수 PG사를 연동하는 **결제 분기 Gateway 구조 설계·개발·운영**
  - 해당 경험을 바탕으로 Wallet 서비스 제공 협력사 대상 결제 연동 기술 지원
- Socket, HTTP/HTTPS, SMTP, FCM Push 기반  
  **장기 실행 Daemon 아키텍처 설계·개발·운영**
  - Pure Java / Spring Boot 기반 모두 개발 가능
- 이중화 환경에서의 Play Store / App Store 리뷰 조회 서버  
  **Scheduler 중복 실행 방지 구조 설계·개발·운영**
- **Deferred Deep Link 백엔드 프로세스 및 아키텍처 전담 설계**
  - Click ID 기반 트래킹
  - 암호화 토큰 기반 위·변조 방지
  - 설치 및 최초 실행 시점 검증 로직 구현
- MVNO 조회·충전 및 PIN(쿠폰/기프티콘) 발급·충전·조회 시스템 연동 경험
- 외부 업체 및 Open API, REST / Socket 기반 시스템 연동 경험 다수

---

## 📌 Development Motto

**“운영 중 장애가 발생하면 즉시 서비스에 영향을 주는 영역”**을 기준으로  
문제 정의 → 구조 설계 → 구현 → 운영 대응까지 책임져 왔습니다.

단순 기능 구현보다 운영 관점에서 아래 항목을 우선 고려합니다.
- 장애 발생 가능성
- 재시도 / 타임아웃 전략
- 로그 가시성 및 추적 용이성
- 운영 환경에서의 안정성과 오류 최소화

---

## 📌 Tech Stack

- **Language** : Java
- **Framework** : Spring, Spring Boot
- **API** : REST API, Socket 기반 통신
- **Daemon** : Socket, HTTP / HTTPS, SMTP, FCM Push 기반 Daemon
- **Data Access** : JDBC, MyBatis, JPA, QueryDSL
- **Auth / Security** : JWT, Authorization, Encrypt·Decrypt (AES, SHA)
- **Infra** : Linux
- **Architecture** : Layered Architecture, Domain-based Design, Strategy / Template Pattern
- **Tooling** : Git, Jira, Confluence, Draw.io, Postman, DBeaver, IntelliJ IDEA, VSCode
- **Environment** : macOS / Windows (혼용 개발 환경)
- **Etc**
  - PG API 연동
  - MVNO 조회·충전 시스템 연동
  - PIN 발급·충전·조회 (쿠폰 / 기프티콘 유형)
  - 데이터 암·복호화 (단방향 / 양방향)

---

## 📌 Portfolio

> 실제 서비스 운영 경험을 바탕으로  
> 보안 및 계약상 제약을 고려하여  
> 핵심 로직은 Mock 및 도메인 재설계 형태로 구성한 포트폴리오입니다.

### 📦 Repositories

**✅ Upload Complete**

- **provider-integration-gateway**
  - 다수 PG사를 분기 처리하는 결제 요청 게이트웨이
  - Strategy Pattern 기반 구조, Mock 연동으로 설계 의도 중심 구현
- **java-socket-daemon-springboot**
  - Spring Boot 기반 장기 실행 Socket Daemon
  - 파일 기반 설정 로딩, 암·복호화, 재시도 / 타임아웃 처리
- **deferred-deeplink-backend**
  - DB Function 기반 Click ID 발급 및 암호화 토큰을 활용한 지연 딥링크 백엔드
  - 서버 검증 중심의 설치·최초 실행 추적 구조 구현
  - 위·변조 방지, 중복 실행 방지, 파라미터 검증 로직 포함
- **ops-scheduler-batch-jobs**
  - 서버 이중화 환경을 고려한 Scheduler 기반 배치 처리
  - 시간 분산 실행, Lock 적용, 재시도(Backoff) 설계
- **spring-boot-jpa-querydsl-api**
  - JPA / QueryDSL 기반 REST API 설계 예제

**⏳ In Progress / Planned**

- **telecom-inquiry-charge-api**
  - MVNO 조회·충전 도메인 추상화 API (Mock 기반)
- **digital-voucher-pin-api**
  - PIN(쿠폰/기프티콘) 발급·충전·조회 도메인 재설계 프로젝트
- **image-synthesis-multi-thread**
  - 비동기 이미지 합성 후 DB 및 CDN 서버 저장 구조 재설계
- **java-daemon-collection**
  - HTTP / HTTPS / SMTP / FCM Push 기반 Daemon 시리즈 (Pure Java & Spring)
- **java-util-collection**
  - 형변환, JSON Build·Parsing, Encrypt·Decrypt, HTTP/HTTPS 통신 유틸 모음

각 Repository에는 **설계 의도, 데이터 흐름, 운영 관점**을 중심으로 한 README를 작성했습니다.

---

## 📌 Contact
- GitHub : https://github.com/Gseobi
- Email : wsx2386@gmail.com / wsx2386@naver.com
