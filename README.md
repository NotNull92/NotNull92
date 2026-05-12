<div align="center">

  <!-- Typing SVG -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Victor+%7C+NotNull92;Unity+C%23+%7C+6%2B+Years;Live-Service+MMORPG+Developer;Building+NoMoreRolls+%F0%9F%8E%B2" alt="Typing SVG" />
  </a>

  <br/><br/>

  <!-- Profile Views + Badges -->
  <img src="https://komarev.com/ghpvc/?username=NotNull92&style=for-the-badge&color=58A6FF&label=PROFILE+VIEWS" alt="Profile Views" />
  <br/><br/>
  <img src="https://img.shields.io/badge/Experience-6%2B%20Years-58A6FF?style=for-the-badge&logo=unity&logoColor=white" />
  <img src="https://img.shields.io/badge/Revenue-%E2%82%A940B%2B%20Annual-22C55E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Live--Service%20MMORPG-FF6B6B?style=for-the-badge" />

  <br/><br/>

  <!-- Language Switch -->
  [🇰🇷 한국어](README.ko.md)

</div>

---

<!-- Activity Graph -->
<div align="center">
  <a href="https://github.com/ashutosh00710/github-readme-activity-graph">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=NotNull92&theme=high-contrast&hide_border=true&area=true&area_color=58A6FF" alt="Activity Graph" />
  </a>
</div>

<!-- Stats Row -->
<p align="center">
  <a href="https://github.com/DenverCoder1/github-readme-streak-stats">
    <img height="170" src="https://github-readme-streak-stats.herokuapp.com?user=NotNull92&theme=default&hide_border=true" alt="GitHub Streak" />
  </a>
  <a href="https://github.com/vn7n24fzkq/github-profile-summary-cards">
    <img height="170" src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=NotNull92&theme=github&hide_border=true" alt="GitHub Stats" />
  </a>
</p>

<!-- Languages Row -->
<p align="center">
  <a href="https://github.com/vn7n24fzkq/github-profile-summary-cards">
  <img height="170" src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=NotNull92&theme=github&exclude=JavaScript&hide_border=true" alt="Repos per Language" />
  <img height="170" src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=NotNull92&theme=github&exclude=JavaScript&hide_border=true" alt="Most Commit Language" />
  </a>  
</p>

---

## 👤 About Me

> **Victor** — Seoul, Korea 🇰🇷 | Ex-Sydney, Brisbane, Gold Coast, Cleveland, Australia 🇦🇺

Unity/C# Developer with **6+ years** of professional experience in live-service mobile MMORPG development. Contributed to projects generating **₩40B+ annual revenue** (Bluepotion Games, Vanco). Specialized in content development, UI/UX programming, and network protocol implementation for large-scale production environments.

- 🏢 **Current Role** — Content & Systems Developer on a **live-service mobile MMORPG** (6th year)
- 🎲 **Solo Project** — Building [NoMoreRolls](https://github.com/NotNull92), a dice-based roguelike with moral choice mechanics
- 🎯 **Goal** — Achieve financial independence through solo indie game & app development
- 🏋️ When not coding — weight training, anime, ETF investing, and gaming

---

## 💼 Professional Experience

<table>
<tr>
<th width="33%" align="center">🏰 Live-Service MMORPG</th>
<th width="33%" align="center">💰 Revenue Impact</th>
<th width="33%" align="center">🚀 Core Competencies</th>
</tr>
<tr>
<td valign="top">

**6th Year | Content & Systems**

- Content development for large-scale mobile MMORPG
- UI/UX programming & system architecture
- Network protocol design & implementation
- Real-time live operations at scale

</td>
<td valign="top">

**₩40B+ Annual Revenue**

- Bluepotion Games — shipped & maintained
- Vanco — shipped & maintained
- Monetization systems & live-ops pipelines
- Cross-functional collaboration in large dev teams

</td>
<td valign="top">

**Production-Grade Skills**

- Unity/C# architecture & optimization
- Live-service operations & hotfix pipelines
- Complex UI systems & state management
- Network protocol implementation

</td>
</tr>
</table>

---

## 🎮 Projects

### NoMoreRolls — In Development

<p align="center">
<img src="https://img.shields.io/badge/Engine-Unity_6-222?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/Genre-Roguelike_(Dice_Based)-FF6B6B?style=for-the-badge" alt="Roguelike" />
<img src="https://img.shields.io/badge/Platform-Steam_(PC)-1B2838?style=for-the-badge&logo=steam&logoColor=white" alt="Steam" />
<img src="https://img.shields.io/badge/Team-Solo_Dev-FFA500?style=for-the-badge" alt="Solo Dev" />
<img src="https://img.shields.io/badge/Status-BIC_2026_Polishing-22C55E?style=for-the-badge" alt="BIC 2026 Polishing" />
</p>

> 🎲 *Undertale's moral combat choices translated into dice poker mechanics — a solo-developed roguelike.*
> Every encounter is a choice: **Fight** or **Talk**. The same dice, the same hands — but divergent meaning.

<details>
<summary><b>⚔️ Core Systems (148 Scripts, ~22K LOC)</b></summary>
<br>

- **PedigreeManager** — 10-tier dice hand ranking (HighCard → MonoRoll) + dual damage/empathy calculation
- **TalkManager** — Empathy gauge, per-enemy condition puzzles (7 switch types), dialogue branching
- **BattleManager SubSM** — 11-state turn-based combat FSM (Intro → RouteSelect → Dice → Hand → Resolve → TurnEnd)
- **DiceSlotManager** — 5-slot equip/swap/inventory system (Basic/Unique/Enhanced 3-tier dice)
- **SoulGimmick System** — 10 unique soul gimmicks via ISoulGimmickHandler interface + Factory pattern (Bell, Ember, Gavel, Hollow, Palette, Phonograph, Roulette, Scribe, Seven, TheDealer)
- **CorridorState** — 22-node fixed corridor progression (Battle/Elite/Boss/Rest/Event/Exit)
- **Fight/Talk Symmetric Routes** — Identical dice-hand loop diverges into attack vs. empathy outcomes
- **EnemyWeakness System** — Visual badge + puzzle-based weakness hints with dynamic bias mechanics
- **MemoryFragment** — Consumable cross-run item system with FragmentEffectHelper
- **EmotionalStateTracker** → BattleAtmosphereController + DynamicUITintController + EnemyExpressionController
- **FlashbackManager** — Micro/short/long 3-tier flashback cinematic sequences
- **CrossRunSaveManager** — JSON-based persistence with meta-event tracking
- **MetaEventManager** — Per-run title logo/subtitle changes + Dealer typing direction
- **True Ending Route** — Unlocked by achieving both Fight & Talk endings
- **LocalizationManager** — KO/EN/JA/RU 4-language support with static UI translation
- **AccessibilityManager** — Motion reduction, colorblind overlay, visual sound indicator, font scaler

</details>

<details>
<summary><b>🎨 UI & Direction</b></summary>
<br>

- **CombatUIController** — Unified battle HUD (hand selection, reroll, route choice, results)
- **PlayerAttackDirector** — 3-phase attack sequence (popup → icon flight → hit flash)
- **EmotionGaugeUI** — DOTween heart gauge animations + empathy label
- **HandGuidePanel** — 2-row scrollable hand reference guide (TAB toggle, dice highlight)
- **DoorSlotUI** — Per-state door sprites + pulse animation + companion display
- **RouteSelectUI** — Fight/Talk selection with description tooltips + enemy dialogue bubbles
- **BattleResultPanelUI** — Victory reward selection with golden effect text
- **ScreenOverlayController** — Damage flash, vignette, chromatic aberration
- **GimmickGuideUI** — In-battle gimmick mechanic explanation panel
- **WeaknessIconUI** — Dynamic weakness hint badge system

</details>

<details>
<summary><b>🔄 Recent Major Updates (2026.04–05)</b></summary>
<br>

- **BIC 2026 Polishing** — 6-phase polishing plan (Code stabilization → Onboarding UX → Combat polish → Build stabilization → Submission)
- **Playtest Feedback Applied** — ESC→Pause menu, Space+Click dialogue, Name input back button, Battle onboarding guide, Reward stat tooltips
- **Seven NumberLock Redesign** — Visual badge system + `seven_reverse` sub-gimmick + dynamic reroll cost
- **Enemy Weakness System** — Full implementation with hint/puzzle mechanics + event/rest reward overhaul
- **Singleton Refactor** — Manager/Controller-only singletons, Inspector-assigned references
- **ParlorScene Hierarchy Cleanup** — Object renaming + structural reorganization
- **Hera Agent Pro Upgrade** — Unity MCP integration for AI-driven development

</details>

<details>
<summary><b>🛠️ Tech Stack</b></summary>
<br>

<p>
<img src="https://img.shields.io/badge/Unity_6-000?style=flat-square&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/DOTween-E84C3D?style=flat-square" alt="DOTween" />
<img src="https://img.shields.io/badge/Odin_Inspector-1E90FF?style=flat-square" alt="Odin Inspector" />
<img src="https://img.shields.io/badge/UniTask-6C5CE7?style=flat-square" alt="UniTask" />
<img src="https://img.shields.io/badge/Hermes_Agent-FF6B6B?style=flat-square&logo=nousresearch&logoColor=white" alt="Hermes Agent" />
<img src="https://img.shields.io/badge/Claude_Code_CLI-CC785C?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code CLI" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square" alt="Obsidian" />
</p>

</details>

---

### Mental Robo — Released

<p align="center">
<img src="https://img.shields.io/badge/Engine-Unity-222?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/Genre-Rhythm_%2B_Talk_Show-FF6B6B?style=for-the-badge" alt="Rhythm + Talk Show" />
<img src="https://img.shields.io/badge/Platform-PC_(Windows)-0078D4?style=for-the-badge" alt="PC" />
<img src="https://img.shields.io/badge/Team-3_People-FFA500?style=for-the-badge" alt="3 People" />
<img src="https://img.shields.io/badge/Status-Released-22C55E?style=for-the-badge" alt="Released" />
</p>

> 🎤 *A comedy robot stand-up game combining rhythm input with a talk show.*
> Read the crowd. Pick the right joke. Nail the timing. Become the greatest comedian robot.
> Built in **48 hours** for **Global Game Jam 2024** — theme: *"Make Me Laugh"*

<details>
<summary><b>⚔️ Systems</b></summary>
<br>

- **Rhythm Input** — Timing window based directional key judgment
- **Joke Topic Branching** — 3 choices: trendy jokes, dad jokes, bathroom humor
- **Audience AI** — Per-topic affinity calculation + real-time score feedback
- **Crowd Reading Puzzle** — Analyze audience profiles ("40-something males", "mostly managers") → strategic topic selection
- **Game Flow** — Stand-up progression → topic selection → rhythm input → scoring

</details>

<details>
<summary><b>🎨 Art & Direction</b></summary>
<br>

- Pixel art robot character + stage background (red curtain, spotlight)
- Audience silhouette + reaction animations
- Joke topic button UI
- Audience profile hint system

</details>

<details>
<summary><b>🔗 Links & Info</b></summary>
<br>

| Info | Detail |
|------|--------|
| **Event** | Global Game Jam 2024 @Seoul (Zempie) |
| **Duration** | 48 hours |
| **Role** | Main developer — all core systems |
| **Tech** | Unity, C#, Git |
| **Repo** | [GitHub](https://github.com/MrBadToast/GGJ2024) |
| **Game Jam Page** | [GGJ 2024](https://globalgamejam.org/games/2024/mental-robo-2) |

</details>

---

### [unity-agent-cli](https://github.com/NotNull92/unity-agent-cli) — Open Source

<p align="center">
<img src="https://img.shields.io/badge/Engine-Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/Connector-C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/Protocol-HTTP-FF6B6B?style=for-the-badge" alt="HTTP" />
<img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT" />
<img src="https://img.shields.io/badge/Status-Released-22C55E?style=for-the-badge" alt="Released" />
</p>

> One binary. Zero dependencies. Direct HTTP bridge to Unity Editor.

An open-source CLI tool that lets AI agents and terminals control Unity Editor directly. A single Go binary communicates with Unity over localhost HTTP, and the Unity-side connector starts automatically when the editor launches.

- **Go CLI** — 20 files, ~800 LOC — command parsing, HTTP client, instance discovery
- **C# Connector** — 22 files, ~2,300 LOC — auto tool registration via `[UnityCliTool]` attribute
- **Core Commands** — `editor play`, `test`, `status`, `exec`, `console`, `update`
- **Architecture** — Stateless single-shot HTTP, zero runtime dependencies, cross-platform (Linux/macOS/Windows)

---

### [unity-agent-cli-pro](https://github.com/NotNull92/unity-agent-cli-pro) — Pro Version

<p align="center">
<img src="https://img.shields.io/badge/Engine-Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/Connector-C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/Protocol-HTTP-FF6B6B?style=for-the-badge" alt="HTTP" />
<img src="https://img.shields.io/badge/License-Commercial-red?style=for-the-badge" alt="Commercial" />
<img src="https://img.shields.io/badge/Status-v0.0.12-22C55E?style=for-the-badge" alt="v0.0.12" />
</p>

> One binary. Zero dependencies. Direct HTTP bridge to Unity Editor.

The pro version of unity-agent-cli. Offers an extended toolset, asset plugin configuration management, self-update system, and improved TUI.

- **Go CLI** — 27 files, ~3,400 LOC — asset config, version check, advanced TUI helpers
- **C# Connector** — 23 files, ~5,100 LOC — `[HeraAgentPro]` attribute, built-in tools schema, test runner
- **Additional Features** — Asset plugin config persistence, periodic update notice (12h), self-update from GitHub releases
- **Release** — Cross-build 5 targets (linux/darwin × amd64/arm64, windows amd64) via GitHub Actions
- **Used in NoMoreRolls Development** — Unity Editor automation, scene control, test execution

<details>
<summary><b>⚙️ Engineering Highlights</b></summary>
<br>

- Harness engineering applied — testable architecture with clean separation of concerns
- Orchestration layer for cross-process state coordination between Go CLI and Unity Editor
- Unity Mono runtime coding guidelines enforced for code correctness
- Cross-platform release pipeline (Linux/macOS/Windows, amd64/arm64)

</details>

---

## 🤖 AI & Tooling

<details>
<summary><b>🔧 AI-Powered Development Workflow</b></summary>
<br>

I leverage AI tools and the **Model Context Protocol (MCP)** ecosystem to supercharge my development workflow:

| Tool | Purpose |
|------|---------|
| **Claude Desktop** | AI-assisted coding, architecture planning, code review |
| **Claude Code CLI** | Terminal-based AI pair programming |
| **[Open-Code](https://github.com/anomalyco/opencode)** | Open-source AI coding assistant |
| **[Hermes Agent](https://github.com/nousresearch/hermes-agent)** | Autonomous AI agent framework by Nous Research |

</details>

---

## 🌐 Beyond Code

```yaml
Location: Seoul, South Korea (ex-Sydney, Brisbane, Gold Coast, Cleveland, Australia)
Languages: Korean (Native) | English (Conversational)
Hobbies:
  - Weight Training
  - Anime & Manga
  - ETF Investing
  - Gaming
Motto: "Build the life you want — one commit at a time."
```

## 🛠️ Tech Stack

[![My Skills](https://skillicons.dev/icons?i=unity,godot,cs,py,go,react,github,git,nodejs,npm,jenkins,md,rider,vscode,notion,obsidian,stackoverflow&theme=dark)](https://skillicons.dev)

---

<div align="center">

[![Email](https://img.shields.io/badge/Email-fatiger92@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fatiger92@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-NotNull92-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NotNull92)

</div>
