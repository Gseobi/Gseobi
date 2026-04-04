<div align="left">

# KIM JISEOP | Java Backend Developer

실서비스 API 운영 경험을 바탕으로,  
외부 연동 · 상태 관리 · 정합성 · 배치/스케줄링 · 운영 안정성이 중요한  
백엔드 문제를 운영 관점에서 설계하고 개선해온 Java Backend Developer입니다.

단순 CRUD 구현보다  
예외 처리, 재시도, 장애 복구, 상태 전이, 최종 정합성이 중요한 문제를  
구조적으로 풀어내는 데 강점을 가지고 있습니다.

<br/>

<a href="mailto:wsx2386@naver.com">
  <img src="https://img.shields.io/badge/Email-03C75A?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/Gseobi/resume">
  <img src="https://img.shields.io/badge/Resume-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://github.com/Gseobi/portfolio">
  <img src="https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://velog.io/@wsx2386/posts">
  <img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge" />
</a>
<a href="https://www.linkedin.com/in/jiseop-kim-3983813b9/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<br/>

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring MVC-6DB33F?style=flat-square&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/Spring WebFlux-6DB33F?style=flat-square&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/MyBatis-BF1E2E?style=flat-square" />
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-D82C20?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />

</div>

<br/>

## Core Strengths

- **Operational Stability**  
  장애 가능성을 낮추고, 실패 시에도 제어 가능한 흐름을 우선적으로 설계합니다.

- **State Management & Consistency**  
  상태 전이와 최종 정합성을 고려한 백엔드 로직 설계를 중요하게 생각합니다.

- **External Integration Design**  
  다수 Provider / 외부 시스템 연동 시 분기 처리, 예외 대응, 응답 표준화 구조를 설계해왔습니다.

- **Legacy Analysis & Refactoring**  
  기존 구조를 빠르게 파악하고 운영 리스크를 줄이는 방향으로 점진적으로 개선해왔습니다.

<br/>

## Featured Projects

### 1. [provider-integration-gateway](https://github.com/Gseobi/provider-integration-gateway)
다수 Provider / PG 연동 환경에서 Provider 선택, 요청 구성, 응답 표준화를 Backend 게이트웨이로 분리해 설계한 프로젝트

`External Integration` · `Strategy Pattern` · `Response Standardization`

### 2. [ops-scheduler-batch-jobs](https://github.com/Gseobi/ops-scheduler-batch-jobs)
운영형 배치에서 중요한 중복 실행 제어, 재시도 흐름, 운영 가시성을 구조화한 Scheduler / Batch 프로젝트

`Scheduler` · `Retry Flow` · `Execution Control`

### 3. [realtime-caching-gateway](https://github.com/Gseobi/realtime-caching-gateway)
Redis를 실시간 처리 및 캐시 계층으로 활용하고, PostgreSQL fallback / synchronization 구조로 성능과 복구 가능성을 함께 고려한 프로젝트

`Redis Cache` · `Fallback Recovery` · `State Consistency`

### 4. [deferred-deeplink-backend](https://github.com/Gseobi/deferred-deeplink-backend)
광고 클릭 이후 앱 설치 전/후가 분리되는 흐름에서 서버 기준 추적, 검증, 상태 연결 구조를 설계한 프로젝트

`Server-side Validation` · `Click Tracking` · `State Consistency`

### 5. [java-socket-daemon-springboot](https://github.com/Gseobi/java-socket-daemon-springboot)
DB 기반 작업 Polling, 암·복호화, Socket 송수신, 결과 반영 흐름을 분리해 장기 실행 Provider 연동 Daemon 구조를 설계한 프로젝트

`Socket Daemon` · `Encryption Flow` · `Timeout / Retry`
