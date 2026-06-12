# AegisNyx 

**AegisNyx**는 다양한 LLM(대규모 언어모델)을 실제 업무에 활용할 수 있도록 지원하는 AI 애플리케이션 플랫폼입니다.

- RAG (Retrieval-Augmented Generation)
- 웹 검색 (Web Search)
- 코드 실행 (Code Execution)
- 파일 생성 (File Creation)
- Deep Research
- AI Agent

또한 기본 제공되는 50개 이상의 커넥터 또는 MCP(Model Context Protocol)를 통해 다양한 시스템과 연동할 수 있습니다.

---

# 주요 기능

## Agentic RAG

AI Agent와 하이브리드 검색을 결합하여 높은 품질의 검색 및 질의응답 기능 제공

### 특징

- 벡터 검색
- 키워드 검색
- AI 기반 정보 검색

---

## Deep Research

다단계 조사 및 분석을 수행하여 심층 보고서 생성

### 특징

- 자동 정보 수집
- 분석 보고서 작성
- 심층 리서치 워크플로우

---

## Custom Agents

사용자 정의 AI 에이전트 생성

### 기능

- 역할 정의
- 전용 지식베이스
- 액션 및 툴 연동

---

## Web Search

실시간 웹 검색 지원

### 지원 엔진

- Google PSE
- Serper
- Brave Search
- SearXNG

### 추가 기능

- 자체 웹 크롤러
- Firecrawl 연동
- Exa 연동

---

## Artifacts

문서 및 결과물 생성

### 예시

- PDF
- 보고서
- 이미지
- 그래프

---

## Actions & MCP

외부 시스템과 AI Agent 연결

### 연동 예시

- Slack
- GitHub
- Jira
- 사내 업무 시스템

---

## Code Execution

격리된 샌드박스 환경에서 코드 실행

### 가능 작업

- 데이터 분석
- 그래프 생성
- 파일 변환
- 자동화 스크립트 실행

---

## Voice Mode

음성 기반 대화 지원

### 기능

- STT (Speech-to-Text)
- TTS (Text-to-Speech)

---

## Image Generation

사용자 프롬프트 기반 이미지 생성

---

# 지원 모델

## 로컬 모델

- Ollama
- LiteLLM
- vLLM

## 상용 모델

- OpenAI
- Anthropic
- Gemini

등 주요 LLM을 모두 지원합니다.

---

# 배포 방식

Onyx는 다양한 환경에서 배포할 수 있습니다.

- Docker
- Kubernetes
- Helm
- Terraform
- AWS
- Azure
- GCP

---

## Onyx Lite

경량 버전

### 특징

- 메모리 1GB 이하
- 빠른 설치
- Agent 기능 지원
- Chat UI 중심

### 추천 대상

- 개인 사용자
- 테스트 환경
- 소규모 팀

---

## Standard Onyx

전체 기능 제공 버전

### 추가 구성 요소

#### RAG 인덱스

- Vector Search
- Keyword Search

#### Background Worker

- 데이터 동기화
- 커넥터 수집 작업

#### AI Inference Server

- 임베딩 생성
- Reranking
- 문서 처리

#### 성능 최적화

- Redis
- MinIO
- 캐시 시스템

### 추천 대상

- 기업
- 대규모 사용자
- 운영 환경

---

# Enterprise 기능

대규모 조직을 위한 기능 제공

## 협업

- Agent 공유
- Chat 공유

## SSO

### 지원 방식

- Google OAuth
- OIDC
- SAML
- SCIM

---

## RBAC

역할 기반 접근 제어

### 예시

- 관리자
- 일반 사용자
- 감사 담당자

---

## Analytics

사용량 분석

### 분석 항목

- 사용자별
- 모델별
- Agent별

---

## Audit

감사 로그 및 질의 기록

### 추적 정보

- 누가
- 언제
- 무엇을 질문했는지

---

## Custom Code

사용자 정의 보안 로직 적용

### 활용 예시

- 개인정보 제거 (PII Masking)
- 민감 질의 차단
- 금융권 규정 준수 검사
- 데이터 유출 방지

---

## White Label

브랜드 변경 가능

### 변경 항목

- 이름
- 로고
- 아이콘
- 배너
- UI 테마

---

# 라이선스

## Community Edition (CE)

### 라이선스

- MIT License

### 포함 기능

- Chat
- RAG
- Agents
- Actions

### 특징

- 무료 사용 가능
- 소스코드 공개

---

## Enterprise Edition (EE)

기업용 추가 기능 제공

### 예시

- 고급 인증
- 고급 분석
- 조직 관리
- 기업 운영 기능

---

# 엔터프라이즈 AI 플랫폼 관점

 단순한 Chat UI가 아니라 다음과 같은 플랫폼으로 활용 가능합니다.

```text
사내 GPT
   +
RAG
   +
Multi-Agent
   +
MCP
   +
보안 분석
   +
감사 로그
```

## 금융권 활용 예시

### AI 보안 분석 플랫폼

- AI Red Team Agent
- Prompt Injection 탐지
- MCP 보안 검증
- Tool Abuse 분석

### 금융권 컴플라이언스

- 전자금융감독규정 검토
- ISMS-P 점검
- CSAP 대응
- NIST 800-171 매핑

### 내부 지식검색

- 보안 정책 검색
- 감사 대응 문서 검색
- 취약점 분석 보고서 검색

---

# 요약

- 오픈소스(MIT)
- RAG 지원
- Multi-Agent 지원
- MCP 지원
- Web Search 지원
- Code Interpreter 지원
- 자체 구축 가능

한 엔터프라이즈급 AI 플랫폼이다.

특히 금융권·공공기관·보안 연구 환경에서 자체 AI Assistant 플랫폼 구축을 위한 기반으로 활용하기 적합하다.
