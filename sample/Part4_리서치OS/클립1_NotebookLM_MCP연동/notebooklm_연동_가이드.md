# NotebookLM MCP 연동 가이드

## NotebookLM이란?
Google이 제공하는 AI 기반 리서치 도구로, PDF·URL·텍스트 등 다양한 소스를 하나의 "노트북"에 모아 AI가 분석·요약·질의응답할 수 있게 해주는 서비스.

## MCP 연동의 의미
안티그래비티(Claude Code)에서 NotebookLM의 노트북 데이터를 **직접 호출**하여 분석에 활용할 수 있음.

---

## 연동 절차

### Step 1: NotebookLM 계정 준비
- Google 계정으로 notebooklm.google.com 접속
- 새 노트북 생성

### Step 2: 소스 등록
- PDF, URL, 텍스트, CSV 등 소스 업로드
- 소스별 라벨링 (분석 목적 명시)

### Step 3: MCP 서버 설정
```json
{
  "mcpServers": {
    "notebooklm": {
      "command": "npx",
      "args": ["-y", "notebooklm-mcp"],
      "env": {
        "NOTEBOOKLM_API_KEY": "${NOTEBOOKLM_API_KEY}"
      }
    }
  }
}
```

### Step 4: 안티그래비티에서 연동 확인
```
NotebookLM에 등록된 노트북 목록을 보여줘.
```

---

## 실무 팁
- 소스는 **목적별로 그룹화** → 노트북 1개 = 프로젝트 1개
- 소스가 10개 이상이면 **카테고리별로 노트북 분리** 권장
- 정기적으로 소스 업데이트 (시장 데이터는 월 1회 갱신)
