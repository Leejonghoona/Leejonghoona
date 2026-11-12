<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B6BD4,50:3B82F6,100:06B6D4&height=220&section=header&text=Jonghoon%20Lee&fontColor=ffffff&fontSize=44&fontAlignY=38&animation=fadeIn&desc=AI%20Engineer%20%C2%B7%20LLM%20Agents%20%C2%B7%20Evaluation&descAlignY=58&descSize=18" width="100%"/>

### 좋은 숫자일수록 한 번 더 의심하는 AI 엔지니어

현장 업무를 AI로 옮기고, 결과는 평가로 다시 확인합니다.<br>
LLM은 판단을 돕고, 실행은 검증된 규칙이 맡는 구조를 만듭니다.

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ljh11442@gmail.com)
[![Blog](https://img.shields.io/badge/Tistory-000000?style=for-the-badge&logo=tistory&logoColor=white)](https://ddolteng.tistory.com/)

</div>

<br>

## 🧭 About Me

- 🤖 병원 업무를 맡는 **AI 에이전트를 혼자 설계·구현** (WardFlow) — 실행 직전 재검사, 원내 LLM 도입 시험까지
- 🎙️ 아동 음성 그림책 앱 **오또 4인 팀 리드** — Whisper LoRA를 폰에 올려 Google Play 비공개 테스트까지 진행
- 🏆 IBM x Red Hat AX Academy 최종 프로젝트 **DearBaby 최우수상**, 중간 프로젝트 GIUT 최우수상
- 🍖 개발 전에는 족발집을 2년 8개월 운영하며 상권 데이터로 매출을 130%까지 회복시켰습니다
- 🌏 뉴질랜드 유학, 다국적 고객 응대 경험

<br>

## 🛠 Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**AI / ML**
<br>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/Whisper%20LoRA-412991?style=flat-square&logo=openai&logoColor=white"/> <img src="https://img.shields.io/badge/vLLM-30A2FF?style=flat-square"/> <img src="https://img.shields.io/badge/LLM%20Evaluation-6B7280?style=flat-square"/> <img src="https://img.shields.io/badge/RAG-1C3C3C?style=flat-square"/>

**Agent · Data**
<br>
<img src="https://img.shields.io/badge/MCP-111827?style=flat-square&logo=anthropic&logoColor=white"/> <img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white"/> <img src="https://img.shields.io/badge/rdflib%20%C2%B7%20SHACL-0F766E?style=flat-square"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>

</td>
<td valign="top" width="50%">

**Backend · Frontend**
<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white"/>

**Infra · Tools**
<br>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/> <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white"/>

</td>
</tr>
</table>

<br>

## 🚀 Featured Projects

### 🏥 [WardFlow — 병상 준비 AI 에이전트](https://github.com/Leejonghoona/wardflow-bed-agent)
`개인 프로젝트 · 설계·평가·구현 1인 · 2026.11`

퇴원부터 다음 환자 입실까지, 다섯 부서가 전화로 맞추던 병상 준비를 맡는 병원 운영 AI 에이전트입니다. 병상은 점수 규칙이 고르고, LLM은 제안과 기록만 하며, 모든 실행은 게이트웨이가 확정 직전에 다시 검사합니다.

<img src="https://raw.githubusercontent.com/Leejonghoona/wardflow-bed-agent/main/docs/%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98.png" width="100%" alt="WardFlow 시스템 아키텍처"/>

| 실행 안전 위반 | 에이전트 자동 확정 | 입원 1건당 사람 작업 | 원내 LLM 도입 시험 |
|:---:|:---:|:---:|:---:|
| **0 / 766** | **82.3%** | **3.16 → 0.95건** | **4종 중 3종 통과** |

<sub>모두 합성 병원 데이터. 원내 LLM은 H100 1장·vLLM 조건, 대표 Gemma 4 26B</sub>

<br>

### 📚 [오또 OTTO — 아이의 말로 만드는 그림책 앱](https://github.com/ai-project-team3/bootcamp-final-project)
`4인 팀 리드 · 음성 인식·LLM 평가 기준·서버·배포 · 2026.08 ~ 2026.10`

- 아동 발화 3,681개로 평가셋을 만들고 Whisper LoRA를 폰에 탑재 — 3~5세 받아쓰기 오류율 **36.5% → 16.3%** (264MB, 갤럭시 S10 1.69초)
- GPU 동시 접속을 실측해(40명 시 86%가 3초 초과) 받아쓰기를 폰으로 이전
- FastAPI·Docker·GitHub Actions 자동 배포, Google Play 비공개 테스트 12명·14일, 팀 PR 약 260건 리뷰 후 병합

<br>

### 👶 [DearBaby — 영유아 성장 기록 AI 서비스](https://github.com/Leejonghoona/IBM_RedHat_Final_Project_BE)
`5인 팀 · ML·백엔드 담당 · 2026.06 ~ 2026.08` &nbsp;·&nbsp; 🏆 `IBM x Red Hat AX Academy 최우수상`

- 아기 행동 15종 사진 4,500장 데이터셋 구축, ResNet50 분류 정확도 **94.76%**
- 아이 정보 접근 권한(JWT)과 백엔드 API 구현 · [Frontend](https://github.com/Leejonghoona/IBM_RedHat_Final_Project_FE)

<br>

### 💬 [Handover — 인수인계서 RAG 챗봇](https://github.com/Leegijun11/Handover_rag)
`3인 팀 · 프론트엔드 · 원티드 AI Championship 2026`

- 배정된 인수인계서에서 찾은 내용만 근거로 답하는 신입 챗봇과 사수용 적응도 리포트
- React 프론트엔드 전체, 적응도 5개 축 점수 계산 (점수는 규칙, LLM은 조언 문장만)

<br>

<details>
<summary><b>그 밖의 프로젝트</b></summary>

- [GIUT](https://github.com/Leejonghoona/IBM-x-RedHat-Midterm-Project) — 공공데이터 지역 행사 탐색·AI 추천, IBM x Red Hat 중간 프로젝트 최우수상
- 얼음땡 — 아이스브레이킹 웹 서비스, 팀 리드, LLM 중복 호출 6회 → 2회
- 아이 화면 지킴이 — 아이 폰 속 거친 말투를 기기 안에서 순화하는 앱 (진행 중)

</details>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,100:0B6BD4&height=120&section=footer"/>

</div>
