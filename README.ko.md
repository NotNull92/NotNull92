<div align="center">

[🇬🇧 English](README.md)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:0D1117&height=120&section=header&text=&fontSize=0" width="100%" />

<a href="https://github.com/NotNull92">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=28&duration=4000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=100&lines=Unity+Game+Developer;Indie+Alchemist" alt="Typing SVG" />
</a>

<img src="https://komarev.com/ghpvc/?username=NotNull92&style=for-the-badge&color=58A6FF&label=PROFILE+VIEWS" alt="Profile Views" />

<br/><br/>

<img src="https://img.shields.io/badge/Experience-6%2B%20Years-58A6FF?style=for-the-badge&logo=unity&logoColor=white" />
<img src="https://img.shields.io/badge/Revenue-%E2%82%A940B%2B%20Annual-22C55E?style=for-the-badge" />
<img src="https://img.shields.io/badge/Domain-Live--Service%20MMORPG-FF6B6B?style=for-the-badge" />

</div>

---

## 소개

> **지영준** — 서울, 대한민국 🇰🇷 | 과거 거주: 시드니, 브리즈번, 골드코스트, 클리블랜드, 호주 🇦🇺

라이브 서비스 모바일 MMORPG 개발 경력 **6년 이상**의 Unity/C# 개발자입니다. **연 매출 400억 원 이상**을 기록한 프로젝트(블루포션 게임즈, 반코)에 기여했습니다. 대규모 프로덕션 환경에서 콘텐츠 개발, UI/UX 프로그래밍 및 네트워크 프로토콜 구현을 전문으로 합니다.

- 🏢 **현재 직무** — **라이브 서비스 모바일 MMORPG** 콘텐츠 및 시스템 개발 (6년 차)
- 🎲 **개인 프로젝트** — 도덕적 선택 메커니즘이 적용된 주사위 기반 로그라이크 [NoMoreRolls](https://github.com/NotNull92) 개발 중
- 🎯 **목표** — 1인 인디 게임 및 앱 개발로 경제적 자립 달성
- 🏋️ 코딩 외 시간 — 웨이트 트레이닝, 애니메이션, ETF 투자, 게임

---

## 경력

<table>
<tr>
<th width="33%" align="center">🏰 라이브 서비스 MMORPG</th>
<th width="33%" align="center">💰 매출 실적</th>
<th width="33%" align="center">🚀 핵심 역량</th>
</tr>
<tr>
<td valign="top">

**6년 차 | 콘텐츠 & 시스템**

- 대규모 모바일 MMORPG 콘텐츠 개발
- UI/UX 프로그래밍 및 시스템 아키텍처
- 네트워크 프로토콜 설계 및 구현
- 대규모 실시간 라이브 오퍼레이션

</td>
<td valign="top">

**연 매출 400억 원 이상**

- 블루포션 게임즈 — 출시 및 유지보수
- 반코 — 출시 및 유지보수
- 수익화 시스템 및 라이브옵스 파이프라인
- 대규모 개발팀 내 다기능 협업

</td>
<td valign="top">

**프로덕션급 기술력**

- Unity/C# 아키텍처 및 최적화
- 라이브 서비스 운영 및 핫픽스 파이프라인
- 복잡한 UI 시스템 및 상태 관리
- 네트워크 프로토콜 구현

</td>
</tr>
</table>

---

## 프로젝트

### NoMoreRolls — 개발 중

<p align="center">
<img src="https://img.shields.io/badge/Engine-Unity-222?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/Genre-Roguelike_(Dice_Based)-FF6B6B?style=for-the-badge" alt="Roguelike" />
<img src="https://img.shields.io/badge/Platform-Steam_(PC)-1B2838?style=for-the-badge&logo=steam&logoColor=white" alt="Steam" />
<img src="https://img.shields.io/badge/Team-Solo_Dev-FFA500?style=for-the-badge" alt="Solo Dev" />
<img src="https://img.shields.io/badge/Status-In_Development-22C55E?style=for-the-badge" alt="In Development" />
</p>

> 🎲 *언더테일의 도덕적 전투 선택을 다이스 포커 메커니즘으로 구현한 1인 개발 로그라이크.*
> 모든 조우는 하나의 선택: **싸우기(Fight)** 또는 **대화하기(Talk)**. 같은 주사위, 같은 패 — 하지만 다른 의미로 분기합니다.

<details>
<summary><b>⚔️ 핵심 시스템</b></summary>
<br>

- **PedigreeManager** — 10단계 주사위 패 순위(HighCard → MonoRoll) + 이중 피해/공감력 계산
- **TalkManager** — 공감 게이지, 적별 조건 퍼즐(7가지 스위치 타입), 대화 분기
- **BattleManager SubSM** — 11상태 턴제 전투 FSM(Intro → RouteSelect → Dice → Hand → Resolve → TurnEnd)
- **DiceSlotManager** — 5슬롯 장착/교체/인벤토리 시스템(덱빌딩 → 슬롯 시스템 진화)
- **CorridorState** — 22노드 고정 복도 진행 + DOTween 스크롤/페이드 연출
- **Fight/Talk 대칭 루트** — 동일한 다이스-핸드 루프가 공격과 공감 결과로 분기

</details>

<details>
<summary><b>🎨 UI & 연출</b></summary>
<br>

- **CombatUIController** — 통합 전투 HUD(핸드 선택, 리롤, 루트 선택, 결과)
- **PlayerAttackDirector** — 3페이즈 공격 시퀀스(팝업 → 아이콘 비행 → 타격 플래시)
- **EmotionGaugeUI** — DOTween 하트 게이지 애니메이션
- **DoorSlotUI** — 상태별 도어 스프라이트 + 펄스 애니메이션 + 동료 표시
- **RouteSelectUI** — Fight/Talk 선택 + 적 대화 버블

</details>

<details>
<summary><b>🔄 메타 시스템 & 디자인</b></summary>
<br>

- **CrossRunSaveManager** — JSON 기반 런 간 영속성
- **MetaEventSystem** — 런별 타이틀 로고/서브타이틀 변경 + 딜러 타이핑 연출
- **트루 엔딩 루트** — Fight 및 Talk 엔딩 모두 달성 시 해금
- **GDD** — 세계관, 캐릭터, 전투, Talk, 기믹, 조우, 엔딩을 다루는 23개 섹션
- **밸런스 시뮬레이션** — 핸드/피해/공감력 튜닝을 위한 10,000턴 몬테카를로 시뮬레이션
- **9가지 기믹 타입** — 트라우마를 게임플레이 메커니즘으로 변환한 10명의 고유한 영혼

</details>

<details>
<summary><b>🛠️ 기술 스택</b></summary>
<br>

<p>
<img src="https://img.shields.io/badge/Unity-000?style=flat-square&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/DOTween-E84C3D?style=flat-square" alt="DOTween" />
<img src="https://img.shields.io/badge/Odin_Inspector-1E90FF?style=flat-square" alt="Odin Inspector" />
<img src="https://img.shields.io/badge/UniTask-6C5CE7?style=flat-square" alt="UniTask" />
<img src="https://img.shields.io/badge/OpenClaw-22C55E?style=flat-square" alt="OpenClaw" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square" alt="Obsidian" />
</p>

</details>

---

### Mental Robo — 출시 완료

<p align="center">
<img src="https://img.shields.io/badge/Engine-Unity-222?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/Genre-Rhythm_%2B_Talk_Show-FF6B6B?style=for-the-badge" alt="Rhythm + Talk Show" />
<img src="https://img.shields.io/badge/Platform-PC_(Windows)-0078D4?style=for-the-badge" alt="PC" />
<img src="https://img.shields.io/badge/Team-3_People-FFA500?style=for-the-badge" alt="3 People" />
<img src="https://img.shields.io/badge/Status-Released-22C55E?style=for-the-badge" alt="Released" />
</p>

> 🎤 *리듬 입력과 토크쇼를 결합한 코미디 로봇 스탠드업 게임.*
> 관객을 읽고, 올바른 농담을 고르고, 타이밍을 맞추세요. 최고의 코미디언 로봇이 되세요.
> **글로벌 게임잼 2024**를 위해 **48시간** 만에 제작 — 테마: *"Make Me Laugh"*

<details>
<summary><b>⚔️ 시스템</b></summary>
<br>

- **리듬 입력** — 타이밍 윈도우 기반 방향키 판정
- **농담 주제 분기** — 3가지 선택: 트렌드 농담, 아재 개그, 병맛 개그
- **관객 AI** — 주제별 호감도 계산 + 실시간 점수 피드백
- **관객 분석 퍼즐** — 관객 프로필 분석("40대 남성", "주로 관리자") → 전략적 주제 선택
- **게임 흐름** — 스탠드업 진행 → 주제 선택 → 리듬 입력 → 채점

</details>

<details>
<summary><b>🎨 아트 & 연출</b></summary>
<br>

- 픽셀아트 로봇 캐릭터 + 무대 배경(빨간 커튼, 스포트라이트)
- 관객 실루엣 + 리액션 애니메이션
- 농담 주제 버튼 UI
- 관객 프로필 힌트 시스템

</details>

<details>
<summary><b>🔗 링크 & 정보</b></summary>
<br>

| 정보 | 내용 |
|------|------|
| **행사** | 글로벌 게임잼 2024 @서울 (Zempie) |
| **개발 기간** | 48시간 |
| **역할** | 메인 개발자 — 모든 핵심 시스템 |
| **기술** | Unity, C#, Git |
| **저장소** | [GitHub](https://github.com/MrBadToast/GGJ2024) |
| **게임잼 페이지** | [GGJ 2024](https://globalgamejam.org/games/2024/mental-robo-2) |

</details>

---

## 기술 스택

<table>
<tr>
<th align="center">핵심</th>
<th align="center">라이브러리</th>
<th align="center">탐색 중</th>
<th align="center">플랫폼</th>
</tr>
<tr>
<td align="center">

![Unity](https://img.shields.io/badge/Unity-000?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)

</td>
<td align="center">

![DOTween](https://img.shields.io/badge/DOTween-E84C3D?style=for-the-badge)
![Odin](https://img.shields.io/badge/Odin_Inspector-1E90FF?style=for-the-badge)
![UniTask](https://img.shields.io/badge/UniTask-6C5CE7?style=for-the-badge)

</td>
<td align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

</td>
<td align="center">

![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Rider](https://img.shields.io/badge/Rider-000?style=for-the-badge&logo=rider&logoColor=white)

</td>
</tr>
</table>

---

## AI & 툴링

<details>
<summary><b>🔧 AI 기반 개발 워크플로우</b></summary>
<br>

AI 도구와 **Model Context Protocol(MCP)** 생태계를 활용하여 개발 워크플로우를 극대화합니다:

| 도구 | 용도 |
|------|------|
| **Claude Desktop** | AI 보조 코딩, 아키텍처 기획, 코드 리뷰 |
| **Claude Code CLI** | 터미널 기반 AI 페어 프로그래밍 |
| **Opencode** | 오픈소스 AI 코딩 어시스턴트 |
| **OpenClaw** | AI 기반 개발 도구 |

**사용 중인 MCP 서버:**
- 📓 **Obsidian MCP** — 지식 베이스 연동
- 💻 **JetBrains MCP** — IDE 수준 AI 지원
- 🖥️ **Desktop Commander** — 시스템 수준 자동화
- 🌐 **Playwright MCP** — 브라우저 자동화 및 테스트

</details>

---

## GitHub 통계

<div align="center">
<img height="170" src="https://github-readme-streak-stats.herokuapp.com?user=NotNull92&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=30363D&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="GitHub Streak" />
<img height="170" src="https://github-readme-stats.vercel.app/api?username=NotNull92&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=8B949E" alt="GitHub Stats" />
</div>

---

## 코드 외의 삶

```yaml
위치: 서울, 대한민국 (과거 거주: 시드니, 브리즈번, 골드코스트, 클리블랜드, 호주)
언어: 한국어 (원어민) | 영어 (초급)
취미:
  - 웨이트 트레이닝
  - 애니메이션 & 만화
  - ETF 투자
  - 게임
좌우명: "원하는 삶을 만들어라 — 한 번의 커밋씩."
```

---

<div align="center">

[![Email](https://img.shields.io/badge/Email-fatiger92@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fatiger92@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-NotNull92-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NotNull92)

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=58A6FF&height=80&section=footer" width="100%" />
</div>
