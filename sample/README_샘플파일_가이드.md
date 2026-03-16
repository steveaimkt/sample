# 샘플 파일 가이드 — 초보자용

> 각 파트별로 어떤 파일을 열어서 어떻게 사용하는지 안내합니다.
> 처음이라면 이 가이드를 따라 순서대로 진행하세요.

---

## Part 3: 엔진 세팅 (기초)

| 클립 | 실습 내용 | 사용할 파일 | 하는 법 |
|------|----------|-----------|---------|
| 클립1 | 워크스페이스 구조 이해 | `Part3_엔진세팅/클립1_워크스페이스_권한설정/폴더구조_예시.md` | 읽고 내 프로젝트 폴더를 동일하게 구성 |
| 클립1 | MCP 서버 설정 | `Part3_엔진세팅/클립1_워크스페이스_권한설정/mcp_settings_예시.json` | 내 config/ 폴더에 복사 후 API 키 입력 |
| 클립1 | 환경 변수 관리 | `Part3_엔진세팅/클립1_워크스페이스_권한설정/env_예시.env` | `.env`로 이름 변경 후 실제 키 입력 |
| 클립2 | Manager View 테스트 | `Part3_엔진세팅/클립2_ManagerView_EditorView/manager_view_예시_프롬프트.md` | 프롬프트 복사 → 클로드에 붙여넣기 → 결과 확인 |
| 클립2 | Manager View 데이터 | `Part3_엔진세팅/클립2_ManagerView_EditorView/sample_data.csv` | 16개 상품 광고 성과 데이터 — Manager View 분석 테스트용 |
| 클립2 | Editor View 테스트 | `Part3_엔진세팅/클립2_ManagerView_EditorView/editor_view_예시_프롬프트.md` | 프롬프트 복사 → 클로드에 붙여넣기 → 결과 확인 |
| 클립3 | Workflow 이해 | `Part3_엔진세팅/클립3_Artifacts_Workflow/workflow_예시.md` | 3가지 워크플로 예시 읽고 내 업무에 적용 |
| 클립3 | Workflow 데이터 | `Part3_엔진세팅/클립3_Artifacts_Workflow/월별_매출데이터_3개월.csv` | 6개 카테고리 3개월 매출 데이터 — 워크플로 실습용 |
| 클립4 | Plan Mode 테스트 | `Part3_엔진세팅/클립4_PlanMode/plan_mode_실행_예시.md` | "플랜"이라고 입력 → Plan Mode 진입 확인 |
| 클립4 | Plan Mode 데이터 | `Part3_엔진세팅/클립4_PlanMode/쿠팡_광고_키워드.csv` | 주차별 키워드 광고 성과 — Plan Mode 분석 대상 |
| 클립5 | SKILL.md 작성 | `Part3_엔진세팅/클립5_SKILL_브랜드가이드/SKILL_예시.md` | 내 브랜드에 맞게 수정 → skills/ 폴더에 저장 |

---

## Part 4: 리서치 OS

| 클립 | 실습 내용 | 사용할 파일 | 하는 법 |
|------|----------|-----------|---------|
| 클립1 | NotebookLM 소스 등록 | 📄 `Part4_리서치OS/클립1_NotebookLM_MCP연동/비타민C세럼_시장트렌드_리포트_2025.md` | **PDF로 변환** → NotebookLM에 업로드 |
| 클립1 | NotebookLM 소스 등록 | 📄 `Part4_리서치OS/클립1_NotebookLM_MCP연동/크래프트볼트_제품소개서.md` | **PDF로 변환** → NotebookLM에 업로드 |
| 클립1 | 연동 가이드 참고 | `Part4_리서치OS/클립1_NotebookLM_MCP연동/notebooklm_연동_가이드.md` | 순서대로 따라하기 |
| 클립2 | 페르소나 도출 테스트 | `Part4_리서치OS/클립2_타겟페르소나_시장분석/고객리뷰_500개.csv` | 클로드에 "이 리뷰를 분석해서 타겟 페르소나를 도출해줘" |
| 클립2 | 경쟁사 비교 | `Part4_리서치OS/클립2_타겟페르소나_시장분석/경쟁사_비교데이터.csv` | 클로드에 "경쟁사 비교 분석 리포트 만들어줘" |
| 실습 | 유튜브 댓글 분석 | `Part4_리서치OS/실습_유튜브댓글_인사이트/유튜브_댓글_수집_100개.csv` | 클로드에 "이 댓글 데이터를 분석해서 인사이트 리포트 만들어줘" |

### PDF 변환 방법 (Mac)
1. MD 파일을 VS Code 또는 텍스트 편집기에서 열기
2. `Cmd + P` → 프린트
3. 좌측 하단 "PDF" → "PDF로 저장" 선택
4. 저장된 PDF를 NotebookLM에 업로드

---

## Part 5: Creative OS

| 클립 | 실습 내용 | 사용할 파일 | 하는 법 |
|------|----------|-----------|---------|
| 클립1 | Pain Point 리서치 | `Part5_CreativeOS/클립1_PainPoint_심층리서치/비타민C세럼_상품정보.csv` | 클로드에 "이 상품 정보와 리서치 예시를 참고해 Pain Point 심층 리서치해줘" |
| 클립2 | Agent Debate | 📌 `Part5_CreativeOS/클립2_AgentTeams_Debate/debate_입력_리서치요약.md` | 이 파일 내용을 클로드에 전달 + "마케터 vs 디자이너 토론해줘" |
| 클립3 | JSON 기획안 생성 | `Part5_CreativeOS/클립3_레이아웃플러그인_피그마MCP/기획안_JSON_예시.json` | 참고용으로 읽고, 클로드에 "내 제품 기획안을 이 JSON 형식으로 만들어줘" |
| 클립4 | 전체 실습 | `Part5_CreativeOS/클립4_실습_기획to와이어프레임/실습_가이드.md` | Phase 1~4 순서대로 따라하기 |
| 클립4 | 빈 템플릿 | `Part5_CreativeOS/클립4_실습_기획to와이어프레임/기획_템플릿.json` | 내 제품 정보로 채워 넣기 |

---

## 빠른 시작 (5분 테스트)

가장 빠르게 결과를 볼 수 있는 조합:

### 테스트 1: 리뷰 분석 (2분)
```
sample/Part4_리서치OS/클립2_타겟페르소나_시장분석/고객리뷰_500개.csv를 분석해서
주요 불만 사항 TOP 5와 만족 포인트 TOP 5를 정리해줘.
```

### 테스트 2: 유튜브 댓글 인사이트 (3분)
```
sample/Part4_리서치OS/실습_유튜브댓글_인사이트/유튜브_댓글_수집_100개.csv를 분석해서
감정 분류, 핵심 키워드, 상세페이지 반영 제안까지 리포트로 만들어줘.
```

### 테스트 3: Agent Debate (5분)
```
sample/Part5_CreativeOS/클립2_AgentTeams_Debate/debate_입력_리서치요약.md를 읽고
마케터 에이전트와 디자이너 에이전트가 상세페이지 전략을 토론해줘.
각 섹션마다 합의안을 도출해줘.
```
