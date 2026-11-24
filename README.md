### 🤞 Nice way to meet me
<p>
  <a href="https://ss-o.tistory.com" target="_blank"><img src="https://img.shields.io/badge/Blog-181717?style=flat-square&logo=github&logoColor=white"/></a>
</p>

## KR About Me
- 🎯 Platform/서비스 QA 6년 | 테스트 자동화 하네스 · CI/CD | AI 기반 QA 프로세스
- 🤖 LLM·Claude Code로 요청 접수 → TC 설계 → 자동화 실행 → 리포트까지 QA 흐름 전체를 자동화하고, 필요한 도구는 직접 만듭니다.
- 🧪 pytest·Appium 하네스와 GitHub Actions, Newman+Jenkins 회귀 자동화, JMeter 성능 자동화, 릴리즈 Quality Gate 운영 경험
- 🤝 로그·코드 기반 재현과 트리아지·RCA로 이슈 해결을 리딩하고, 배포 신뢰도를 높여왔습니다.

## US About Me
- 🎯 Platform/Service QA (6 yrs) | Test harnesses & CI/CD | AI-driven QA workflows
- 🤖 Automated the QA flow end to end (request → test design → automated runs → reports) with LLMs and Claude Code, and build my own tools when needed
- 🧪 Built pytest/Appium harnesses on GitHub Actions, regression automation (Newman+Jenkins), performance testing (JMeter), and release quality gates
- 🤝 Lead issue triage/RCA with reproducible evidence from logs and code to improve release confidence

## Featured Portfolio
- Regression Pipeline (Postman/Newman/Jenkins → pytest harness + OpenAPI contract + AI scenarios) → 🔗[regression-pipeline-template](https://github.com/sso-jeong/regression-pipeline-template)
- QA Strategy Pack → 🔗[qa-strategy-pack](https://github.com/sso-jeong/qa-strategy-pack)
- Incident & RCA Pack → 🔗[incident-rca-pack](https://github.com/sso-jeong/incident-rca-pack)

## 🛠️ Tech Stack
- **QA / Automation**: Python, pytest, Appium, Postman, Newman, JMeter(non-GUI)
- **CI/CD & Environment**: GitHub Actions(self-hosted runner, matrix), Jenkins, Nexus, Maven, Docker, n8n
- **AI**: Claude Code(skill design), LLM API integration
- **Tooling / Backend**: FastAPI, Next.js, Node.js, Java, Spring Boot, MyBatis, JPA, Kafka
- **Infra / Ops**: AWS(ECR·ECS·S3), Linux(systemd), mitmproxy, log analysis(grep/awk/sed)
- **DB**: PostgreSQL, Oracle, MySQL, DB2

## 💪 Experience
- **Remember & Company — QA Team Manager** (2026.05 ~ Present)  
  - 수동 검수와 UI 자동화를 하나로 잇는 QA 파이프라인 설계·개발 (8개 저장소, 머지 PR **841건**)  
  - **Claude Code 스킬 5종**으로 PR diff·기획서 기반 TC 생성 → 사이클 수행 → 무인 큐 처리까지 자동화  
  - QA 플랫폼 서버 개발(**FastAPI · PostgreSQL · Next.js**): Jira 동기화, 자동화 실행·결과 수집, 커버리지 산출  
  - **pytest + Appium** 하네스(테스트 약 790개)를 GitHub Actions 샤드 matrix로 운영, 체크리스트 자동화 커버리지 **Android 99.4% · iOS 97.1%**  
  - 실기기·에뮬레이터를 self-hosted 러너로 묶은 **디바이스팜**과 웹 대시보드(미러링·원격 조작·빌드 설치) 개발

- **TmaxSoft — Service/Platform QA (SQA)** (2020.12 ~ 2025.06)  
  - Postman 컬렉션 표준화 → **Newman + Jenkins** 회귀 자동화 파이프라인 구축/운영 (리드타임 **30~50% 단축**)  
  - **JMeter non-GUI** 기반 부하/성능 측정 자동화 및 결과 공유 템플릿 정착  
  - 배포 전후 **Quality Gate(스모크/체크리스트/롤백)** 운영으로 릴리즈 안정성 강화  
  - Severity 기반 Triage + RCA 기록으로 재오픈/Hotfix 완화에 기여  
  - Linux/DB(Oracle/H2) 기반 재현 환경 구축 및 운영

- **TmaxSoft — Backend (Distributed Transaction / Saga)** (2025.07 ~ 2026.04)  
  - Saga Manager / Transaction Service 분석·구현·디버깅으로 트랜잭션 리스크(멱등/순서역전/보상 지연) 이해 강화  
  - QA 관점에서 분산 트랜잭션 테스트 아이디어 설계 및 개발 협업 경험

<details>
  <summary>Other</summary>

- 디지털컨버전스 JAVA & Spring 개발자 양성과정 (2020.07 ~ 2020.12)
- (주)지에스티 기술개발본부 인턴 (2019.08 ~ 2020.01)
- LINC+ 프로그램 수료 (2017.08 ~ 2020.02)

</details>

## 💻 Projects (Selected QA Case Studies, anonymized)
- **AI-driven QA Workflow & Automation Platform** (2026 ~ )  
  - 검수 요청 → 자료 수집(PR diff·기획서) → TC 생성 → 사이클 수행을 Claude Code 스킬로 자동화하고, 사람은 판정과 리뷰에 집중  
  - 자동화 실행 트리거(슬랙·허브·야간 cron)를 GitHub Actions 워크플로 하나로 통합, 결과를 허브에 모아 자동 FAIL을 실결함·오탐으로 분류  
  - 테스트 코드 생성·로케이터 자가 복구 초안 PR, 셀렉터 계약 검사로 자동화 유지보수 비용 절감  

- **QA Strategy & Release Quality Gate (Smoke / Checklist / Go-No-Go)** (2022 ~ 2025)  
  - 배포 전후 품질 상태를 종합 판단하기 위한 체크리스트/헬스체크/롤백 절차를 정리하고 운영에 적용  
  - 배포 직후 스모크 자동 실행으로 초기 진단 속도 개선 및 릴리즈 리스크 감소  
  - 🔗 Docs: https://github.com/sso-jeong/qa-strategy-pack

- **Incident 대응 & RCA / Triage 운영** (2021 ~ 2025)  
  - 결함 재현–원인 가설–재검증 루프 운영, Severity/Priority 기준으로 트리아지 정리  
  - RCA 템플릿 기반으로 원인/재발방지 액션을 기록하여 재오픈/Hotfix 완화에 기여  
  - 🔗 Samples: https://github.com/sso-jeong/incident-rca-pack

- **Regression Automation Pipeline** (2022 ~ 2024, v2 2026)  
  - v1: Postman 컬렉션 표준화 → Newman 실행을 Jenkins 파이프라인에 연동하여 회귀 자동화 구축/운영, 반복 검증 리드타임 **30~50% 단축**  
  - v2: pytest 하네스 + **OpenAPI 계약 검증** + **Claude 시나리오 초안 생성**(실행 검증 후 사람 리뷰) + GitHub Actions 샤드 실행  
  - 버그 주입 훈련으로 회귀 탐지력과 AI 시나리오의 커버리지 빈틈까지 확인  
  - 🔗 Template: https://github.com/sso-jeong/regression-pipeline-template

<details>
  <summary>Other (Past personal projects)</summary>

- 오늘의 크보 서비스 개발(back) (2025.06 ~ )
- 개인 프로젝트) 영업자동화 시스템 개발 (2020.09.01 ~ 2020.12.14)
- MES 생산 라인 자동화 시스템 개발 (2019.08 ~ 2020.01)
- 교내 프로젝트) 영어로 읽는 그림책 이야기 어플 개발 (2017.08 ~ 2017.12)
</details>

<details>
  <summary>Other Award</summary>

- 2017 LINC+ 연합 캡스톤 디자인 경진대회 우수상 (2018.01.18)

</details>

## 📌 Certification
- 정보처리기사
