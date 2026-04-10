<div align="center">

<!-- Typing SVG -->
<a href="https://github.com/NotNull92">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=28&duration=4000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=100&lines=Unity+Game+Developer;Indie+Alchemist" alt="Typing SVG" />
</a>

<img src="https://komarev.com/ghpvc/?username=NotNull92&style=for-the-badge&color=58A6FF&label=PROFILE+VIEWS" alt="Profile Views" />

</div>

---

## 🧑‍💻 About Me

> **Youngjun Ji** — Seoul, Korea 🇰🇷 | Ex-Sydney, Ex-Brisbane, Ex-Gold Coast, Ex-Cleveland, Australia 🇦🇺

- 🎮 **Unity/C# Developer** with 6+ years of professional experience
- 🏢 Currently on a **live-service mobile MMORPG** team — content dev, UI programming, network protocol implementation
- 💰 Contributed to projects generating **₩4B+ monthly revenue** (Bluepotion Games, Vanco)
- 🕹️ Building **[NoMoreRolls](https://github.com/NotNull92)** — a dice-based roguelike with moral choice mechanics
- 🎯 **Goal:** Achieve financial independence through solo indie game & app development
- 🏋️ When not coding — weight training, anime, ETF investing, and gaming

---

## ⚔️ Career Highlights

<table>
<tr>
<td width="50%">

### 🏰 Live-Service MMORPG
**6th Year | Content & Systems Developer**

- Content development for large-scale mobile MMORPG
- UI/UX programming & system architecture
- Network protocol design & implementation
- Real-time live operations at scale

</td>
<td width="50%">

### 💎 Revenue Impact
**₩400M+ Monthly Revenue Projects**

- Bluepotion Games — shipped & maintained
- Vanco — shipped & maintained
- Experience with monetization systems and live-ops pipelines
- Cross-functional collaboration in large dev teams

</td>
</tr>
</table>

---

## 🎮 Projects — NoMoreRolls

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

### 🤖 Mental Robo — *Released*

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

- **Rhythm Input** — Timing-window based directional key judgment
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

## 🛠️ Tech Stack

<table>
<tr>
<th align="center">Core</th>
<th align="center">Exploring</th>
<th align="center">Platforms</th>
</tr>
<tr>
<td align="center">

![Unity](https://img.shields.io/badge/Unity-000?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)

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

## 🤖 AI & Tooling

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

## 📊 GitHub Stats

<div align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=NotNull92&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" alt="GitHub Stats" />
<img height="170" src="https://github-readme-streak-stats.herokuapp.com?user=NotNull92&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=30363D&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="GitHub Streak" />
</div>

<div align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=NotNull92&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" alt="Top Languages" />
</div>

---

## 🌍 Beyond Code

```yaml
Location: Seoul, South Korea (ex-Sydney, Ex-Brisbane, Ex-Gold Coast, Ex-Cleveland, Australia)
Languages: Korean (Native) | English (Pre-intermediate)
Hobbies:
  - 🏋️ Weight Training
  - 🎌 Anime & Manga
  - 📈 ETF Investing
  - 🎮 Gaming (obviously)
Motto: "Build the life you want — one commit at a time."
```

---

## 📫 Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-fatiger92@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fatiger92@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-NotNull92-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NotNull92)

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=58A6FF&height=80&section=footer" width="100%" />
</div>
