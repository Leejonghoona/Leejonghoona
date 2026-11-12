### 이종훈

**좋은 숫자일수록 한 번 더 의심하는 AI 에이전트 개발자**
*AI agent developer who double-checks the good numbers first.*

LLM은 판단을 돕고, 실행은 검증된 규칙이 맡는 구조를 만듭니다.
모델을 고르기 전에 평가 기준과 합격선부터 정하고, 결과가 좋을수록 측정 방법을 다시 확인합니다.

#### 프로젝트

- [**WardFlow**](https://github.com/Leejonghoona/wardflow-bed-agent) · 개인
  퇴원부터 다음 입실까지 병상 준비를 맡는 병원 AI 에이전트. 판단과 실행을 나누고, LLM 판단은 담당자 검증을 거쳐 규칙표로 쌓습니다.
  실행 안전 위반 **0 / 766**, 사람 손 없이 확정 **82.3%** (합성 데이터)

- [**오또 OTTO**](https://github.com/ai-project-team3/bootcamp-final-project) · 4인 팀 리드
  아이의 말로 그림책을 만드는 Android 앱. Google Play 비공개 테스트까지 진행했습니다.
  폰 탑재 Whisper LoRA로 3~5세 받아쓰기 오류율 **36.5% → 16.3%**

- [**DearBaby**](https://github.com/Leejonghoona/IBM_RedHat_Final_Project_BE) · 5인 팀, ML 담당
  아기 사진으로 행동을 분류하는 성장 기록 서비스. IBM x Red Hat AX Academy 최우수상.
  ResNet50 15종 분류 정확도 **94.76%**

- [**Handover**](https://github.com/Leegijun11/Handover_rag) · 3인 팀, 프론트엔드
  인수인계서를 근거로 답하는 신입 온보딩 RAG 챗봇. 원티드 AI Championship 2026 출품.

- **아이 화면 지킴이** · 개인, 진행 중
  아이 폰 속 거친 말투를 기기 안에서 순화하는 앱.

그 밖에 [GIUT](https://github.com/Leejonghoona/IBM-x-RedHat-Midterm-Project)(공공데이터 지역 행사 추천, IBM x Red Hat 중간 프로젝트 최우수상), 얼음땡(아이스브레이킹 웹 서비스, 팀 리드)

<details>
<summary>숫자 더 보기</summary>

- **WardFlow:** 원내 GPU 1장 조건(H100, vLLM)에서 LLM 7종을 사전 등록한 합격선으로 시험해 4종 중 3종 통과, 대표 Gemma 4 26B. 금지 행동 실행 0건
- **오또:** 받아쓰기 3세 오류율 57% → 37%, 판정 LLM 원가 21.6원 → 10.5원, 책 생성 36.9초 → 12.6초

</details>

#### 기술

Python · FastAPI · PyTorch · React · Docker
vLLM · LLM 평가 · RAG · Whisper / LoRA · MCP · OpenTelemetry · rdflib / SHACL · Claude Code

#### 연락

[ljh11442@gmail.com](mailto:ljh11442@gmail.com) · [블로그](https://ddolteng.tistory.com/)
