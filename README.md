# ♟ 체스 — Chess vs AI

브라우저에서 바로 즐기는 **1인용 / 2인용 체스 게임**입니다. 설치 없이 HTML/CSS/JavaScript 단일 파일([`index.html`](index.html))로 동작합니다.

## ▶ 지금 플레이

### **https://hwoarang0911-hue.github.io/chess/**

> ⚠️ 위 링크는 저장소 **Settings → Pages** 에서 Pages를 한 번 켜야 동작합니다. (아래 [온라인 배포](#-온라인-배포-github-pages) 참고)
> 지금 바로 해보려면 [`index.html`](index.html) 파일을 내려받아 더블클릭하세요.

## ✨ 기능

- **백(플레이어) vs 흑(AI)** — 말을 클릭하면 갈 수 있는 칸이 **노란색**으로 표시됩니다.
- **특수 규칙** — 캐슬링 · 앙파상 · 프로모션(퀸/룩/비숍/나이트 선택) 모두 지원.
- **판정** — 체크 · 체크메이트 · 스테일메이트를 화면 중앙에 표시(위협받는 쪽 색 + 반대 색 외곽선).
- **AI 난이도 4단계**
  - `Easy` — 무작위 수
  - `Middle` — 1수 앞 기물 가치 평가
  - `Hard` — 미니맥스 깊이 3 + 위치 점수
  - `Expert` — 알파베타 가지치기(~깊이 4) + 위치·킹 안전·기동성 종합
- **2인용(사람 vs 사람) 모드**, **기보(이동 기록) 패널**, 잡은 기물·점수 우세 표시, **무르기** 버튼.

## 🎮 조작법

1. 시작 화면에서 **PLAY** → 난이도 선택(또는 2인용) → 대국 시작.
2. 백(아래쪽)이 먼저 둡니다. 말을 클릭 → 노란 칸 클릭으로 이동.
3. **다시 시작** 버튼으로 언제든 처음 화면으로.

## 💻 로컬에서 실행

별도 서버나 설치가 필요 없습니다.

```
# 저장소를 받은 뒤
index.html  ←  파일을 더블클릭하면 브라우저에서 바로 실행
```

## 🌐 온라인 배포 (GitHub Pages)

깔끔한 주소(`https://hwoarang0911-hue.github.io/chess/`)에서 바로 플레이하려면 Pages를 켜세요. **한 번만** 하면 됩니다.

1. 저장소 상단 **Settings** 탭
2. 왼쪽 메뉴 **Pages**
3. **Source** → `Deploy from a branch`
4. **Branch** → `main` / `/(root)` 선택 후 **Save**
5. 1~2분 뒤 접속 → **https://hwoarang0911-hue.github.io/chess/**

이후에는 `main`에 푸시할 때마다 자동으로 갱신됩니다.

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
