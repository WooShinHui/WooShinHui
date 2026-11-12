<div align="center">

# 우신희 · WooShinHui

### `AI Engineer` · AI Agent · RAG · MCP

**반복되는 병목**을 찾아 **도구로 해결**하고, **토큰과 시간으로 측정**합니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-PDF-D97757?style=flat-square&logo=readdotcv&logoColor=white)](https://github.com/WooShinHui/WooShinHui/blob/main/asset/AI_Engineer.pdf)
[![Demo](https://img.shields.io/badge/Demo-YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=e7tsqP_GTtQ)

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-000000?style=flat-square&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-5A5A5A?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-5A5A5A?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Phaser](https://img.shields.io/badge/Phaser-211F1F?style=flat-square)
![Python](https://img.shields.io/badge/Python-Learning-3776AB?style=flat-square&logo=python&logoColor=white)

</div>

---

## 🌱 About

```yaml
role: Client Programmer → AI Engineer
focus: [AI Agent, RAG, MCP, Developer Tooling]
approach: 병목 발견 → 도구화 → 측정
learning: Python Backend
```

---

## 🏢 Experience

### 교육 콘텐츠 클라이언트 프로그래머 · 천재교육 `2025.02 ~ 현재`

`TypeScript` `Phaser` `CreateJS` `Canvas 2D` `Android WebView`

<details>
<summary><b>인터랙티브 콘텐츠</b> · <code> 50개+ </code></summary>

- 터치, 색칠, 선 긋기, 드래그앤드롭 등 교육용 인터랙션 개발
- Spine·AnimateCC 애니메이션 연동
- MVC 패턴을 기반으로 피드백 대응에 용이한 설계 구축

</details>

<details>
<summary><b>Canvas MCP</b> · <code> 약 3시간 → 20분 </code></summary>
  
**Code:** [canvas-agent-mcp](https://github.com/WooShinHui/canvas-agent-mcp)

- **문제:** Canvas 내부는 브라우저 도구로 보이지 않아 구현, 사람 확인, 수정이 반복됨
- **해결:** 메인 씬에 접근해 실행, 상태 조회, 클릭·드래그, 타임라인, 스크린샷을 제공하는 도구 8종 구현
- **신뢰성:** MVC와 CLAUDE.md로 수정 범위를 명시해 에이전트 작업 범위 제한

</details>

<details>
<summary><b>Whisper Editor</b> · <code>작업 시간 80%↓</code></summary>

**Code:** [Whisper-Editor](https://github.com/WooShinHui/Whisper-Editor)

- **문제:** 음성에 맞춰 JSON을 수작업으로 고치며 시간 소모와 휴먼 에러 발생
- **해결:** API 끊김을 피하려 Whisper를 로컬에서 구동하고, 원문과 음성 타이밍을 맞추는 GUI 개발
- **결과:** 작업 시간 약 15분 → 3분 (실측), 빌드된 프로젝트의 JSON 수정만으로 양산

</details>

<details>
<summary><b>DrawCall 최적화</b> · <code> 21fps → 61fps </code></summary>

- **문제:** 색칠과 스티커가 쌓일수록 객체별 DrawCall이 누적되어 저사양 기기에서 프레임 저하
- **해결:** 그래픽을 RenderTexture에 그린 뒤 객체를 정리해 DrawCall 누적 차단
- **결과:** DrawCall 감소로 21fps->61fps까지 방어

</details>

<details>
<summary><b>명화퍼즐</b> · <code> 외주 작업 주도 개발 </code></summary>

- **문제:** 색칠되는 영역이 이미지로 대체되어 연속 터치가 많아질수록 레이턴시 증가, 초기 로딩 시간 증가
- **해결:** 색칠 영역을 고유 색상과 매핑하고 알파값을 조절하여 유저들에게는 안 보이게 하였으며 이미지 대체 대신 고유 매핑 색상을 채우는 방식으로 대체
- **결과:** 로딩 속도 5초-> 1초 개선, 레이턴시 대폭 감소

</details>

---

### 개인 프로젝트 · AI Factory

**Code:** [AI Factory](https://github.com/WooShinHui/ai_factory_portfolio)

`RAG` `MCP` `Claude Code` `Codex` `Hooks`

| What | Impact |
|---|---|
| BM25·임베딩·리랭커 검색 도구 | (동일 질문)토큰 **27.9만 → 17.9만** |
| 고정 6개 질문 A/B 테스트 | 총 토큰 **8~47%↓** |
| 협업자와 개발자의 토큰 격차 축소 | **1.63배 → 1.28배** |
| RAG 미호출 추적, Hook으로 호출 강제 | **11/15세션** 발견 |
| 에이전트 환경을 운영해 게임 출시 | **로블록스** |


## 🎬 Demo

<p align="center"><b>🤖 AI Agent 운영 콘솔</b> · <b>🎙️ Whisper Editor</b></p>
<p align="center">
<a href="https://www.youtube.com/watch?v=e7tsqP_GTtQ"><img src="https://i.ytimg.com/vi/e7tsqP_GTtQ/hqdefault.jpg" width="48%" alt="AI Agent 운영 콘솔" /></a>
<a href="https://www.youtube.com/watch?v=M6qNg_z43Ow"><img src="https://i.ytimg.com/vi/M6qNg_z43Ow/hqdefault.jpg" width="48%" alt="Whisper Editor" /></a>
</p>

<p align="center"><b>🎮 로블록스 게임</b> · <b>⚡ DrawCall 최적화</b></p>
<p align="center">
<a href="https://www.youtube.com/shorts/NYDJ5ZEf3Xk"><img src="https://i.ytimg.com/vi/NYDJ5ZEf3Xk/hqdefault.jpg" width="48%" alt="Roblox Game" /></a>
<a href="https://www.youtube.com/watch?v=cBksAnVZQDg"><img src="https://i.ytimg.com/vi/cBksAnVZQDg/hqdefault.jpg" width="48%" alt="DrawCall Optimization" /></a>
</p>


---

## 🗓 History

| 시기 | 내용 |
|---|---|
| `2026.11` | 로블록스 게임 출시 (2종) |
| `2026.10` | 카카오임팩트 AI TOP 100 참가 · 프롬프트 캐싱으로 약 **$140** 절감 |
| `2026.08` | AWS Quick 교육 · 실습 발표 약 30명 중 **1위** |
| `2026.02` | AI-POT 프롬프트 활용능력 1급 · 고득점 베타테스터 · 한국생산성본부(KPC) |
| `2025.12` | 사내 이벤트 게임 라이브 서비스 (약 120명) |
| `2025.02` | 천재교육 입사 |
| `2024.06` | 충북 아카데미 글로벌 게임센터 · 기업연계 프로젝트(곤군게임즈) |

> 🔒 실서비스 게임과 일부 업무 코드는 보안 및 소유권 문제로 비공개입니다.
