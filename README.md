<div align="left">

# KIM JISEOP | Backend Developer

단순 기능 구현보다,  
서비스 사용자 경험과 운영자의 관리 편의를 함께 고려하며  
상태 변화, 실패 분기, 복구 가능성을 구조적으로 정리해 문제를 풀어내는 개발자입니다.

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
  실패 가능성을 낮추는 것뿐 아니라, 장애 시에도 제어 가능하고 복구 가능한 흐름을 우선 설계합니다.

- **State Management & Consistency**  
  상태 전이와 최종 정합성을 고려해, 한 번의 요청으로 끝나지 않는 흐름을 구조적으로 설계하는 것을 중요하게 생각합니다.

- **External Integration Design**  
  다수 Provider / 외부 시스템 연동에서 요청·응답 차이, 인증 방식, 실패 분기를 내부 경계에서 흡수하고 표준화하는 구조를 설계해왔습니다.

- **Legacy Analysis & Refactoring**  
  기존 구조를 빠르게 파악하고, 운영 리스크를 줄이는 방향으로 점진적으로 개선해왔습니다.

<br/>

## Featured Projects

### 1. [commerce-orchestration-backend](https://github.com/Gseobi/commerce-orchestration-backend)
주문 이후 payment · settlement · notification · outbox 흐름을  
orchestration, explicit state transition, compensation, admin recovery 관점으로 설계한 프로젝트

`Transaction Flow` · `Explicit State` · `Compensation / Recovery`

### 2. [provider-integration-gateway](https://github.com/Gseobi/provider-integration-gateway)
다수 Provider / PG 연동 환경에서 Provider 선택, 요청 구성, 응답 표준화 책임을  
게이트웨이 계층으로 분리해 확장성과 유지보수성을 높인 프로젝트

`External Integration` · `Strategy Pattern` · `Response Standardization`

### 3. [ops-scheduler-batch-jobs](https://github.com/Gseobi/ops-scheduler-batch-jobs)
중복 실행 제어, 재시도 흐름, 운영 확인 포인트를 구조화한 Scheduler / Batch 프로젝트

`Scheduler` · `Retry Flow` · `Execution Control`

### 4. [realtime-caching-gateway](https://github.com/Gseobi/realtime-caching-gateway)
Redis를 실시간 처리 계층으로, PostgreSQL을 fallback 및 최종 영속 계층으로 분리해  
응답 속도와 복구 가능성을 함께 고려한 프로젝트

`Cache / Data Flow` · `Fallback Recovery` · `Consistency`

### 5. [deferred-deeplink-backend](https://github.com/Gseobi/deferred-deeplink-backend)
광고 클릭 이후 앱 설치 전/후가 분리되는 흐름에서  
서버 기준 추적, 검증, 상태 연결 구조를 설계한 프로젝트

`Server-side Validation` · `Click Tracking` · `State Consistency`

### 6. [java-socket-daemon-springboot](https://github.com/Gseobi/java-socket-daemon-springboot)
DB Polling, 암·복호화, Socket 송수신, 결과 반영 흐름을 분리해  
장기 실행 Provider 연동 구조를 설계한 프로젝트

`Socket Daemon` · `Encryption Flow` · `Timeout / Retry`
