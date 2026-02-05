# WooHyun — Backend Developer

Spring Boot 기반 **실서비스를 운영해온 4년차 백엔드 개발자**입니다.  
라이브 서비스 환경에서의 **안정성, 성능 개선, 유지보수성**을 중요하게 생각합니다.

---

## 👤 About Me
- 4년차 백엔드 개발자 (Java / Spring Boot)
- 앱 API 서버 및 Admin 웹(JSP) 개발·운영 경험
- 라이브 서비스 장애 대응 및 성능 최적화 경험 다수
- AWS 환경에서 EC2 기반 서버 배포 및 운영 경험
- 유지보수 가능한 구조 설계와 공통화에 관심

📎 **GitHub:** https://github.com/swh7j  
📎 **Notion:** https://phrygian-pound-13d.notion.site/WooHyun-024718d0d910435ab962a275306c0aab  
📎 **E-mail:** swh_77@naver.com

---

## 🛠 Tech Stack

### Backend
- Java, Spring Boot, JSP
- MyBatis, Querydsl

### Database
- MySQL, PostgreSQL

### Infra / DevOps
- AWS EC2
- Linux, Nginx, Tomcat

### Tools
- GitHub, GitLab, Bitbucket
- Postman, Mantis

---

## 💼 Experience

### 두댓 / JellyPet (2023.04 ~ 현재)
**Role:** Backend Developer / Server Operation

- Spring Boot 기반 **앱 API 서버 및 Admin 웹 운영**
- AWS EC2, Nginx, Tomcat, Linux 환경 관리
- 홈 화면 API 성능 개선  
  → 평균 응답 시간 **10초 → 2초**
- Admin 페이지 로딩 최적화 및 관리 기능 개선
- 재화(젤리) 자동 차감 로직 구현
  - DB 구조 개선 및 스케줄러 적용
- 라이브 서비스 장애 대응 및 원인 분석

**Troubleshooting**
- 무통장입금 PG Noti 중복 수신  
  → 중복 처리 방지 로직으로 재고 오류 방지
- 스케줄러 동시 실행 문제  
  → 실행 조건 제어로 오류 발생률 감소
- 캐시 기반 User 랭킹 미노출 이슈  
  → 캐시 갱신 로직 개선으로 안정화

---

### HRIntro / SI Projects (2022.03 ~ 2023.04)
**Role:** Backend Developer

- 파주시청 시스템  
  - CRUD 및 대시보드 개발
- JAS 직무분석 시스템  
  - 평가서 생성/확인 기능 개발
  - Admin 페이지 유지보수
- 롯데캐피탈 평가 시스템  
  - 신규 기능 개발 및 평가 부문 담당
- 농협 IT센터 자재유통 시스템  
  - AS-IS → TO-BE 전환 개발
  - 백엔드/프론트 공통 라이브러리 개발

---

## 🏗 Project Skeleton

src/main/java
└── com.example.project
├── config
│ ├── filter # CORS 등 공통 필터
│ ├── interceptor # 인증 / 요청 검증
│ ├── CacheConfig
│ ├── QuerydslConfig
│ └── InterceptorConfig
├── controller # REST API 엔드포인트
├── service # 비즈니스 로직
├── repository # DB 접근 계층
├── dto # 요청 / 응답 DTO
├── exception # 전역 예외 처리
│ ├── ExceptionAdvice
│ ├── ErrorResponse
│ └── Errors
└── util
├── jwt # JWT 인증
├── payment # 결제 / 암호화
├── upload # 파일 업로드 (S3)
└── common


### Structure Principles
- **Controller:** 요청 처리, 비즈니스 로직 최소화
- **Service:** 핵심 도메인 로직 담당
- **Repository:** DB 접근 책임 분리
- **Config:** 공통 설정 및 요청 흐름 제어
- **Exception:** 전역 예외 처리 및 일관된 에러 응답
- **Util:** 인증, 결제, 업로드 등 공통 기능 모듈화

---

## 🎓 Education
- 안산이젠아카데미 웹 개발 과정  
  (Java, JSP, Spring Boot)
- 협성대학교 사회복지학과

---

## ⭐ Etc
- 협성대학교 총학생회장 역임  
  → 협업 및 커뮤니케이션 경험
- 장애 대응과 **서비스 안정성**을 중시
- 단기 구현보다 **유지보수 가능한 설계**를 우선
