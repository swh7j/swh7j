# WooHyun | Backend Developer

**Spring Boot 기반 실서비스를 개발하고 운영해온 4.5년차 백엔드 개발자입니다.**

서비스의 기능 개발부터 API, Admin, DB, AWS 인프라 운영까지 직접 경험했으며,
실서비스에서 발생하는 **성능 저하, 데이터 정합성 문제, 장애와 운영 이슈를 분석하고 개선해왔습니다.**

단순히 기능을 구현하는 것에 그치지 않고,
**문제의 원인을 분석하고 구조를 개선하여 서비스의 안정성과 성능을 높이는 개발**을 지향합니다.

홈 API 응답시간을 약 **10초 → 3초**, 5천 건 Push 처리시간을 약 **5분 → 10초대**로 단축했으며,
Spring Boot 및 MySQL 메이저 버전 업그레이드와 운영 환경 개선을 통해 AWS 월 운영 비용을
**약 $536 → $323 수준으로 절감**한 경험이 있습니다.

또한 **Ehcache → Redis 캐시 전환, FCM 직접 발송 → Kafka 기반 비동기 처리,
Gemini API 기반 AI 기능, Docker 기반 서비스의 Kubernetes 배포 및 서비스 통신 구성·검증,
Prometheus / Grafana / Alertmanager 기반 모니터링 환경**을 직접 구축·적용하며
실서비스의 개발부터 성능 개선, 자동화, 배포 및 운영까지 폭넓게 경험했습니다.

---

## 💼 Experience

### 🏢 두댓 / JellyPet

**Backend Developer · 2023.04 ~ 현재**

모바일 커머스 플랫폼의 **App API / Admin / DB / Infrastructure** 개발 및 운영

#### 📌 담당 업무

- Spring Boot 기반 App API 및 Admin 개발·운영
- REST API 설계 및 개발
- JPA / QueryDSL / MyBatis 기반 데이터 처리
- MySQL 기반 DB 설계 및 운영
- Redis 기반 캐시 구조 설계 및 운영
- Kafka 기반 비동기 메시지 처리 및 대량 Push 처리
- Spring Security / JWT 기반 인증 구조 유지보수
- AWS EC2 / Linux / Nginx / Tomcat 기반 서비스 운영
- Docker / Docker Compose 기반 운영 환경 구성
- Kubernetes 기반 배포 및 서비스 운영 구조 구성·검증
- AWS S3 기반 파일 업로드 및 저장
- JUnit 5 / Mockito 기반 테스트 코드 작성
- GitHub Actions 기반 CI/CD 및 AWS EC2 자동 배포
- Prometheus / Grafana / Alertmanager 기반 모니터링 구축
- React 기반 Admin 화면 부분 전환
- 기획 / 디자인 요구사항 확인 및 Figma 기반 UI·기능 협업

#### 🚀 주요 성과

- 🏠 홈 API 응답시간 **약 10초 → 3초** 개선
- 📱 5천 건 Push 처리시간 **약 5분 → 10초대** 단축
- ⬆️ Spring Boot **2.3.4 → 2.7.18** 업그레이드
- 🗄️ MySQL **5.7 → 8.0.33 → 8.4.9** 업그레이드 및 데이터 마이그레이션
- 💰 AWS 운영 비용 **월 약 $536 → $323 수준**으로 절감
- ⚡ FCM 직접 발송 구조를 **Kafka 기반 비동기 처리 구조**로 전환
- 🔄 Ehcache 기반 캐시를 **Redis 기반 캐시 구조**로 전환
- 🏆 Scheduler 및 캐시 데이터 흐름을 개선하여 **주간/월간 랭킹 미노출 문제 해결**
- 🔐 PG Noti 중복 처리로 발생하던 **재화 이중 차감 문제 해결**
- ⏰ 동일 시간대에 집중되던 **14개 Scheduler 작업을 분산하여 동시 실행 문제 개선**
- 🤖 Gemini API + Redis 기반 **Admin 고객 문의 요약 기능** 구현
- 📊 Prometheus / Grafana / Alertmanager 기반 **모니터링 및 장애 알림** 구축
- 🚀 GitHub Actions 기반 **CI/CD 및 AWS EC2 자동 배포** 구축
- 🧪 k6 + Prometheus / Grafana 기반 **API 부하테스트 및 성능 지표 검증 환경 구축**
- ☸️ Kubernetes 기반 **배포 및 서비스 운영 구조 구성·검증**
- ⚛️ 기존 JSP Admin의 일부 화면을 React 기반으로 부분 전환

#### 🧩 주요 개발

- 커뮤니티 / 쿠폰 / Jelly 리뷰 / Jelly 룰렛 기능
- 첫 구매 정책 및 대상자 산정 로직
- 랭킹 정책 및 관련 로직 개선
- Scheduler 기반 주문 상태 변경 및 운영 업무 자동화
- Admin 기능 및 운영 개선
- 파일 업로드 및 AWS S3 기반 파일 저장
- Gemini API + Redis 기반 Admin 고객 문의 요약 및 답변 초안 기능 구현

---

### 🏢 에이치알인트로

**Backend Developer · 2022.03 ~ 2023.04**

공공·금융 분야 **Java / Spring 기반 SI 프로젝트** 개발 및 유지보수

#### 📌 주요 프로젝트

- **롯데캐피탈** — 사내 인사평가 ERP 신규 구축
- **농협 IT센터** — 레거시 시스템 전환
- **파주시청** — 공공 시스템 유지보수
- **JAS** — 직무분석 시스템 유지보수
- 공통 라이브러리 및 MyBatis 기반 업무 로직 개발

---

## 🛠 Tech Stack

### 💻 Backend

☕ **Java** · 🌱 **Spring Boot** · 🔧 **Spring Framework** · 🌐 **REST API**
🔐 **Spring Security** · 🎫 **JWT**

### 🖥 Frontend

⚛️ **React** · 📄 **JSP**

### 🗄 Data Access

🔷 **Spring Data JPA** · 💤 **Hibernate** · 🔍 **QueryDSL** · 🗃️ **MyBatis** · 📝 **Native Query**

### 🗄 Database

🐬 **MySQL** · 🐘 **PostgreSQL** · 🔴 **Oracle**

### ⚡ Cache / Messaging

🔴 **Redis** · 🟠 **Ehcache** · 📨 **Apache Kafka** · 👥 **Consumer Group** · 🔄 **Retry / DLT**

### ☁️ Infrastructure / DevOps

☁️ **AWS EC2 / RDS / S3** · 🐧 **Linux** · 🐳 **Docker / Docker Compose**
☸️ **Kubernetes** · 🌐 **Nginx** · 🐈 **Tomcat**

### 🔄 CI/CD

🚀 **GitHub Actions** · 🐘 **Gradle** · 🔀 **Git**

### 📊 Monitoring

🔥 **Prometheus** · 📈 **Grafana** · 🚨 **Alertmanager** · ❤️ **Spring Boot Actuator**

### 🤖 AI / External API

✨ **Google Gemini API** · 🔗 **RestTemplate**

### 🧪 Testing

🧪 **JUnit 5** · 🎭 **Mockito** · 🌱 **Spring Boot Test** · 📊 **k6**

### 🧰 Tools

🐙 **GitHub / GitLab / Bitbucket** · 📮 **Postman** · 💬 **Slack**
🎨 **Figma** · 🖥️ **Xshell** · 🔧 **Mantis** · 💻 **IntelliJ IDEA / VS Code**

---

## 🔗 Links

- [GitHub](https://github.com/swh7j)
- [Notion Portfolio](https://phrygian-pound-13d.notion.site/WooHyun-024718d0d910435ab962a275306c0aab)
- [Email](mailto:swh_77@naver.com)
