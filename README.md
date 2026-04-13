<div align="center">

[🇰🇷 한국어](README.ko.md)

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

## About Me

> **Youngjun Ji** — Seoul, Korea 🇰🇷 | Ex-Sydney, Brisbane, Gold Coast, Cleveland, Australia 🇦🇺

Unity/C# Developer with **6+ years** of professional experience in live-service mobile MMORPG development. Contributed to projects generating **₩40B+ annual revenue** (Bluepotion Games, Vanco). Specialized in content development, UI/UX programming, and network protocol implementation for large-scale production environments.

- 🏢 **Current Role** — Content & Systems Developer on a **live-service mobile MMORPG** (6th year)
- 🎲 **Solo Project** — Building [NoMoreRolls](https://github.com/NotNull92), a dice-based roguelike with moral choice mechanics
- 🎯 **Goal** — Achieve financial independence through solo indie game & app development
- 🏋️ When not coding — weight training, anime, ETF investing, and gaming

---

## Professional Experience

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

## Projects

### NoMoreRolls — In Development

<p align="center">
<img src="https://img.shields.io/badge/Engine-Unity-222?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/Genre-Roguelike_(Dice_Based)-FF6B6B?style=for-the-badge" alt="Roguelike" />
<img src="https://img.shields.io/badge/Platform-Steam_(PC)-1B2838?style=for-the-badge&logo=steam&logoColor=white" alt="Steam" />
<img src="https://img.shields.io/badge/Team-Solo_Dev-FFA500?style=for-the-badge" alt="Solo Dev" />
<img src="https://img.shields.io/badge/Status-In_Development-22C55E?style=for-the-badge" alt="In Development" />
</p>

> 🎲 *Undertale's moral combat choices translated into dice poker mechanics — a solo-developed roguelike.*
> Every encounter is a choice: **Fight** or **Talk**. The same dice, the same hands — but divergent meaning.

<details>
<summary><b>⚔️ Core Systems</b></summary>
<br>

- **PedigreeManager** — 10-tier dice hand ranking (HighCard → MonoRoll) + dual damage/empathy calculation
- **TalkManager** — Empathy gauge, per-enemy condition puzzles (7 switch types), dialogue branching
- **BattleManager SubSM** — 11-state turn-based combat FSM (Intro → RouteSelect → Dice → Hand → Resolve → TurnEnd)
- **DiceSlotManager** — 5-slot equip/swap/inventory system (deckbuilding → slot system evolution)
- **CorridorState** — 22-node fixed corridor progression with DOTween scroll/fade direction
- **Fight/Talk Symmetric Routes** — Identical dice-hand loop diverges into attack vs. empathy outcomes

</details>

<details>
<summary><b>🎨 UI & Direction</b></summary>
<br>

- **CombatUIController** — Unified battle HUD (hand selection, reroll, route choice, results)
- **PlayerAttackDirector** — 3-phase attack sequence (popup → icon flight → hit flash)
- **EmotionGaugeUI** — DOTween heart gauge animations
- **DoorSlotUI** — Per-state door sprites + pulse animation + companion display
- **RouteSelectUI** — Fight/Talk selection + enemy dialogue bubbles

</details>

<details>
<summary><b>🔄 Meta Systems & Design</b></summary>
<br>

- **CrossRunSaveManager** — JSON-based cross-run persistence
- **MetaEventSystem** — Per-run title logo/subtitle changes + Dealer typing direction
- **True Ending Route** — Unlocked by achieving both Fight & Talk endings
- **GDD** — 23 sections covering worldview, characters, combat, Talk, gimmicks, encounters, endings
- **Balance Simulation** — 10,000-turn Monte Carlo for hand/damage/empathy tuning
- **9 GimmickTypes** — Trauma translated into gameplay mechanics for 10 unique souls

</details>

<details>
<summary><b>🛠️ Tech Stack</b></summary>
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

## Tech Stack

<table>
<tr>
<th align="center">Core</th>
<th align="center">Libraries</th>
<th align="center">Exploring</th>
<th align="center">Platforms</th>
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

## AI & Tooling

<details>
<summary><b>🔧 AI-Powered Development Workflow</b></summary>
<br>

I leverage AI tools and the **Model Context Protocol (MCP)** ecosystem to supercharge my development workflow:

| Tool | Purpose |
|------|---------|
| **Claude Desktop** | AI-assisted coding, architecture planning, code review |
| **Claude Code CLI** | Terminal-based AI pair programming |
| **Opencode** | Open-source AI coding assistant |
| **OpenClaw** | AI-powered development tools |

**MCP Servers I Use:**
- 📓 **Obsidian MCP** — Knowledge base integration
- 💻 **JetBrains MCP** — IDE-level AI assistance
- 🖥️ **Desktop Commander** — System-level automation
- 🌐 **Playwright MCP** — Browser automation & testing

</details>

---

## GitHub Stats

<div align="center">
<img height="170" src="https://github-readme-streak-stats.herokuapp.com?user=NotNull92&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=30363D&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="GitHub Streak" />
<img height="170" src="https://github-readme-stats.vercel.app/api?username=NotNull92&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=8B949E" alt="GitHub Stats" />
</div>

---

## Beyond Code

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

---

<div align="center">

[![Email](https://img.shields.io/badge/Email-fatiger92@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fatiger92@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-NotNull92-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NotNull92)

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=58A6FF&height=80&section=footer" width="100%" />
</div>
