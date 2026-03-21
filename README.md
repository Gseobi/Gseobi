<div align="left">

# KIM JISEOP | Java Backend Developer

실서비스 API 운영 경험을 바탕으로, Redis 캐싱 · 메시징 · 외부 연동 · 스케줄링 구조를
설계 중심으로 재구성하는 Java Backend Developer입니다.

단순 CRUD 구현보다 정합성, 장애 복구, 재시도, 상태 관리가 중요한
운영형 백엔드 문제를 구조적으로 풀어내는 데 강점을 가지고 있습니다.

현재는 백엔드 전담 개발자로 근무하며, 앱 서비스 API 서버를 중심으로
충전, 가입자 조회, Mail, 국제 SMS, Push, Daemon, Scheduler 영역의
설계, 개발, 리팩토링, 운영, 유지보수를 수행하고 있습니다.

<br/>

<a href="mailto:wsx2386@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="mailto:wsx2386@naver.com">
  <img src="https://img.shields.io/badge/Naver Mail-03C75A?style=for-the-badge&logo=naver&logoColor=white" />
</a>
<a href="https://github.com/Gseobi">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<p>
  <img src="https://img.shields.io/badge/Java-Main-007396?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-Framework-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Backend-Developer-181717?style=flat-square" />
  <img src="https://img.shields.io/badge/Operations-Focused-4B5563?style=flat-square" />
</p>

</div>

<br/>

## Core Strengths

- Java / Spring 기반 실서비스 API 설계 · 개발 · 운영 경험
- Redis 캐싱, 메시지 처리, 외부 연동, 배치/스케줄링 구조 재구성 경험
- 장애 대응, 재시도, 복구 가능성, 최종 정합성을 고려한 운영형 설계 지향
- 실무 경험을 바탕으로 포트폴리오 프로젝트를 문제 해결 중심으로 재구성

<br/>

## Featured Projects

### 1. [realtime-caching-gateway](https://github.com/Gseobi/realtime-caching-gateway)
기존 DB 중심 메시지 처리 구조에서 발생할 수 있는 조회 지연, cache miss, 최종 정합성 문제를 줄이기 위해,
Redis를 1차 처리 계층으로 두고 PostgreSQL을 fallback / sync 계층으로 분리한 구조를 설계한 프로젝트

- Problem: Redis 유실 상황에서도 복구 가능한 메시지 처리 구조 필요
- Structure: Redis cache/state layer + PostgreSQL fallback + scheduled sync
- Verified: full miss / partial miss recovery, conversation meta recovery, dirty sync

### 2. [provider-integration-gateway](https://github.com/Gseobi/provider-integration-gateway)
다수 Provider / PG 연동 시 분기 로직이 비대해지는 문제를 줄이기 위해,
Provider 전략 분리와 공통 응답 표준화 구조를 설계한 프로젝트

- Problem: Provider별 분기와 응답 처리 로직이 서비스 전반에 흩어질 수 있음
- Structure: provider strategy + common response DTO + extensible routing
- Verified: provider branching, unsupported provider handling, controller 변경 없는 확장

### 3. [ops-scheduler-batch-jobs](https://github.com/Gseobi/ops-scheduler-batch-jobs)
운영형 배치에서 필요한 시간 분산 실행, 중복 실행 방지, 재시도 흐름, 운영 가시성을 구조화한 프로젝트

- Problem: 배치 중복 실행, 실패 재처리, 운영 확인 어려움
- Structure: grouped execution timing + lock + retry flow + ops visibility
- Verified: grouped execution, retry flow, duplicate prevention, result visibility

<br/>

## Tech Stack

### Main
<p>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/MyBatis-BF1E2E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Oracle Database-F80000?style=for-the-badge&logoColor=white" />
</p>

### Production Experience
<p>
  <img src="https://img.shields.io/badge/REST API-005571?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Socket-232F3E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Daemon-4B5563?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Scheduler-0F766E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/AES / SHA-7C3AED?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/jsvc-4B5563?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tomcat-FA7A18?style=for-the-badge&logo=apachetomcat&logoColor=white" />
</p>

### Hands-on Experience
<p>
  <img src="https://img.shields.io/badge/Redis-D82C20?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/QueryDSL-005571?style=for-the-badge" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
</p>

### Collaboration
<p>
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
  <img src="https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
</p>
