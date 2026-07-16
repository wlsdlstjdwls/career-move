# 원티드 · 리멤버 이력서 동기화 초안

career-description 기준. 두 플랫폼 다 필드 구조가 비슷(경력/프로젝트/학력/스킬/자기소개 분리형)이라 공통 초안으로 작성. 실제 입력 시 플랫폼별 글자수 제한만 확인.

---

## 자기소개 (자기소개서 / 소개 필드)

```
E-커머스 백엔드 엔지니어로 상품·주문·프로모션·클레임 등 핵심 도메인을 5년 이상 설계·개발·운영했습니다. Java/Spring, Oracle 기반 대규모 백오피스 환경에서 성능 최적화·안정성 확보·CI/CD 자동화를 주도했고, 최근에는 LLM 에이전트 개발(Claude, Gemini, Groq, Ollama)에 집중하고 있습니다.

사내에서는 프로모션 효율성을 AI가 자연어로 분석하는 PoC를 아키텍처 설계부터 분석 엔진까지 담당하고 있고, 개인 프로젝트 'Fitness In Service'는 Claude Code와 함께 기획-설계-개발-배포 전 과정을 진행해 실서비스로 운영 중입니다. 기술 블로그 누적 조회수 70만+.
```

(글자수 제한 있는 플랫폼용 축약본)
```
E-커머스 백엔드 6년차. 상품·주문·프로모션 도메인 설계·개발·운영 경험. 현대백화점 NCP 구축(더현대·투홈 통합) 참여. 최근 LLM 에이전트(Claude/Gemini/Groq) 활용한 사내 AI PoC 및 개인 프로젝트(Fitness In Service) Claude Code 기반 개발 운영 중.
```

---

## 경력사항 (회사별 카드 입력)

### 커머스웨어 | 백엔드 개발자 (주문팀 프론트 API) | 2025.11 — 재직중
```
- 현대백화점 더현대·투홈 플랫폼 통합 고도화(NCP 구축) — 주문상세·고객자산(예치금/H.Point/RSVP/바우처)·사은행사·선물받기 API 개발·운영
- 인수인계 받은 API 영역 안정화, 오픈 직전 변경요청 영향도 분석 및 반영
- 바우처 정책 변경 대응: SUBSTR 파싱 오류 → 정규식 일괄 교체, 전 케이스 검증
- 사내 자체과제: 프로모션 효율성 분석 AI 에이전트 PoC (Python/FastAPI, Claude·Gemini·Groq·Ollama)
```

### 커머스웨어 | 백엔드 개발자 | 2019.01 — 2024.11 (5년 11개월)
```
- 상품/주문/클레임/프로모션 백오피스 개발 및 운영
- 카드즉시할인 프로모션 신규 개발 (다중채널 검증, 구매전환율 상승 기여)
- PC몰 리뉴얼 — 쿼리 튜닝/Spring Cache로 응답속도 3~5초→1~2초 단축
- 기간계 시스템 고도화 — Adobe Flex→ExtJS 전환(AA 역할), CI/CD 파이프라인 구축
- 보이는 ARS — PG 연동 포함 주문/CS 프로세스 설계개발
- 호주 해외법인 홈쇼핑 시스템 구축 — CTI Event-Driven 전환, 현지 상주
```

---

## 프로젝트 (포트폴리오 섹션 — 있는 경우)

### Fitness In Service (실운영중, 2025.10—)
```
헬스장 운영 통합 플랫폼. Spring Boot 멀티모듈(BO/MO/Batch), Claude Code로 기획-설계-개발-배포 전 과정 진행.
- BO: 센터/트레이너/PT세션/급여/GX클래스/대시보드
- MO: 회원 인증, GX 예약, 마이페이지, 장바구니, Toss Payments 결제
- AWS EC2, Docker, Nginx, Redis 세션, JWT, SSE 실시간 알림
링크: beta.fitness-trainer-assistant.ai.kr / github.com/wlsdlstjdwls/fitness-in-service-showcase
```

### 프로모션 효율성 분석 AI 에이전트 PoC (진행중)
```
FastAPI + React/Vite, PostgreSQL, SSE 스트리밍 챗봇. 4계층 클린 아키텍처 설계, Lift/가격탄력성/구매트리거 분석 엔진, 멀티 AI 프로바이더 라우팅(Claude/Gemini/Groq/Ollama), 의도분류 13종 챗봇 오케스트레이션.
```

---

## 학력 / 자격

```
- 도쿄 코코로일본어학교 (6개월)
- JLPT N3 (2025)
- 정보처리기사 (2018)
- Java&Python 기반 응용SW 개발자 양성과정 (2018, 7개월)
```

---

## 스킬 태그

```
Java, Spring Boot, Spring Batch, MyBatis, JPA, QueryDSL, Oracle, PL/SQL, MariaDB, Redis,
AWS EC2, Docker, Nginx, Jenkins, REST API, JWT,
Claude Code, Claude API, Gemini API, Python, FastAPI, React
```

---

## 포트폴리오 / 링크 필드

```
- 경력 상세: https://wlsdlstjdwls.github.io/career-description/
- GitHub: github.com/wlsdlstjdwls
- 기술 블로그: diary-developer.tistory.com (누적 70만+ 조회)
- Fitness In Service: beta.fitness-trainer-assistant.ai.kr
```

---

## 체크사항 (붙여넣기 전)
- [ ] 원티드/리멤버 각 플랫폼 글자수 제한 확인 후 축약본 사용 여부 결정
- [ ] 원티드는 "포지션별 이력서" 복수 작성 가능 — 타겟 회사군(현대백화점 계열 등)에 맞춰 헤드라인 문구 조정 고려
- [ ] 리멤버는 명함 기반 프로필이라 경력 항목 표기가 원티드보다 간결한 편, 위 축약 자기소개 사용 권장
