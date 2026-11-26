# WooHyun | Backend Developer

Java · Spring Boot 기반 실서비스를 개발하고 운영해온 백엔드 개발자 신우현입니다.

모바일 커머스 서비스의 App API, Admin, DB부터 AWS 인프라, 배포까지 개발과 운영 전반을 맡고 있습니다. 느린 API, 결제 중복 차감, 새는 비용 같은 문제를 원인부터 찾아 SQL 개선·캐시·비동기 처리 등으로 해결해왔습니다.

## 🚀 Key Achievements

- **API 성능 개선:** 홈 API 응답 시간 9.75초 → 0.73초
- **비동기 처리:** Kafka 기반 Push 발송 약 4,800건 기준 약 10분 → 37초
- **데이터 정합성:** 가상계좌 알림 중복으로 재화·상품 수량이 두 번 빠지던 문제 수정
- **운영 환경 개선:** MySQL 5.7 → 8.0 → 8.4, Spring Boot 1.5/2.3 → 2.7 업그레이드, 월 RDS 비용 약 $536 → $179
- **운영 보안:** 인터넷 전체에 열려 있던 운영 DB 포트를 서비스 중단 없이 차단
- **배포 자동화:** Admin GitHub Actions CI/CD, 테스트 실패 시 배포 중단·배포 뒤 health check

## 🛠 Tech Stack

- **Backend:** Java 8, Spring Boot 2.7, Spring Security, JWT, REST API
- **Data Access:** Spring Data JPA, Hibernate, QueryDSL, MyBatis
- **Database / Cache:** MySQL 8.4 (AWS RDS), Redis, Ehcache
- **Messaging:** Apache Kafka
- **Infrastructure:** AWS EC2 / RDS / S3, Linux, Docker, Docker Compose, Nginx
- **CI/CD / Monitoring:** GitHub Actions, Maven, Gradle, Spring Boot Actuator, Prometheus / Grafana / Alertmanager
- **Testing:** JUnit 5, Mockito, Spring Boot Test, k6
- **Others:** JSP, React, Firebase Cloud Messaging, Google Gemini API

## 💼 Experience

### 두댓 / JellyPet
**Backend Developer · 2023.04 – 현재**

모바일 커머스 서비스의 App API 및 Admin 개발·운영

- REST API 개발 및 홈 API 조회 성능 개선
- Redis·Ehcache 캐시와 Kafka 기반 Push 비동기 발송
- 가상계좌 중복 차감 수정 및 Scheduler 운영
- AWS EC2·RDS, Nginx 운영과 장애 대응, 운영 서버 보안 점검
- JUnit 5 / Mockito 테스트, GitHub Actions 배포 자동화

### 에이치알인트로
**Backend Developer · 2022.03 – 2023.04**

공공·금융 분야 Java / Spring 기반 SI 프로젝트 개발 및 유지보수

- 롯데캐피탈 인사평가 ERP 신규 구축
- 농협 IT센터 자재유통 시스템 레거시 전환
- 파주시청 및 JAS 시스템 유지보수

## 📂 Side Project

### [교회 관리 시스템](https://github.com/swh7j/churchService)
**2026.11 – 현재 · 실제 교회 한 곳에서 운영 중**

기획과 구조 설계는 직접 하고 Claude Code와 함께 개발한 교회 관리 시스템

- 재정·결산보고서, 주보로 예배 PPT 만들기, 앨범, 악보 편집, 백업
- Spring Boot 4, Java 17, React 19, SQLite, GCP, Caddy

## 🔗 Links

- **Portfolio:** [Notion](https://app.notion.com/p/WooHyun-Shin-3cf668db12de8076b424e7e5ba00d683)
- **Email:** [swh_77@naver.com](mailto:swh_77@naver.com)
