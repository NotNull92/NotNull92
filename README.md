<div align="center">

  <img src=".github/assets/tagline-en.svg" width="100%" alt="I create games that inspire, resonate deeply, and stay with people long after the final screen fades." />

  <br/>

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

Unity/C# engineer with **6+ years** in live-service mobile MMORPG production. I build gameplay systems, editor tooling, UI flows, and AI-assisted Unity pipelines that are measured inside the real Editor instead of guessed from static code.

- 🏢 **Production** — shipped and maintained live-service systems on revenue-scale MMORPG projects
- 🎲 **Solo Game** — building [NoMoreRolls](https://github.com/NotNull92/NoMoreRolls), a dice-combat roguelike about violence, empathy, and consequence
- 🛠️ **Tooling** — building [hera-agent-unity](https://github.com/NotNull92/hera-agent-unity), a low-token Unity control layer for AI coding agents
- 🎒 **Prototype Lab** — building [Inventoria](https://github.com/NotNull92/Inventoria), a backpack-defense RPG prototype with deterministic simulation

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

**Live-Service Systems**

- Unity/C# gameplay and content implementation
- UI/UX systems for repeated live-operation workflows
- Network protocol implementation and production debugging
- Hotfix-minded development under real service constraints

</td>
<td valign="top">

**Revenue-Scale Production**

- Contributed to titles generating **₩40B+ annual revenue**
- Shipped and maintained work at Bluepotion Games / Banco
- Balanced feature delivery, stability, and live-ops pressure
- Collaborated across design, art, QA, backend, and operations

</td>
<td valign="top">

**Builder Profile**

- Turns game design into maintainable runtime systems
- Uses agent tooling to compress iteration loops
- Prefers observable Editor verification over speculation
- Ships solo projects with production engineering habits

</td>
</tr>
</table>

---

## 🎮 Projects

### [NoMoreRolls](https://github.com/NotNull92/NoMoreRolls) — Solo Game

<p align="center">
<img src="https://img.shields.io/badge/Engine-Unity_6-222?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/Genre-Roguelike_(Dice_Based)-FF6B6B?style=for-the-badge" alt="Roguelike" />
<img src="https://img.shields.io/badge/Platform-Steam_(PC)-1B2838?style=for-the-badge&logo=steam&logoColor=white" alt="Steam" />
<img src="https://img.shields.io/badge/Team-Solo_Dev-FFA500?style=for-the-badge" alt="Solo Dev" />
<img src="https://img.shields.io/badge/Status-Active_Polish-22C55E?style=for-the-badge" alt="Active Polish" />
</p>

> Dice poker combat where the same roll can become violence or empathy.
> Built as a full solo Unity project, with combat logic, UI direction, localization, accessibility, persistence, and editor automation handled end to end.

<details>
<summary><b>⚔️ Core Systems</b></summary>
<br>

- **Dice Combat** — 10-tier hand evaluation, reroll economy, damage/empathy dual resolution, and enemy weakness puzzles
- **Fight / Talk Routes** — one dice loop that branches into attack outcomes or empathy conditions
- **Battle FSM** — intro, route select, dice, hand select, resolve, reward, defeat, and turn-end states split into focused state classes
- **Soul Gimmicks** — handler/factory architecture for Bell, Ember, Gavel, Hollow, Palette, Phonograph, Roulette, Scribe, Seven, and The Dealer
- **Run Structure** — corridor progression, rest/event nodes, memory fragments, cross-run persistence, meta events, and true-ending unlock logic
- **Localization & Accessibility** — KO/EN/JA/RU UI localization, motion reduction, colorblind overlay, visual sound indicator, and font scaling

</details>

<details>
<summary><b>🎨 UI / Game Feel</b></summary>
<br>

- Unified combat HUD with hand selection, reroll controls, route choice, reward panels, and in-battle guides
- Directed attack feedback using popup, icon flight, hit flash, screen overlay, and enemy expression changes
- Tooltip-heavy onboarding for dice hands, reward stats, enemy weakness hints, and gimmick explanations
- Recent polish on reward UI simplification, inventory refresh behavior, icon readability, and dialogue/control friction

</details>

<details>
<summary><b>🔄 Recent Work</b></summary>
<br>

- Simplified battle reward UI and tightened inventory/icon refresh behavior
- Refactored `GameContext` emotion gauge events and dialogue sequencing utilities
- Consolidated ScriptableObject generator helpers and player stat copy flow
- Polished reaction captions, high-dice terminology, pause/dialogue/name-input UX, and reward stat tooltips
- Uses `hera-agent-unity` in the project package manifest for live Editor checks during agent-assisted development

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

### [hera-agent-unity](https://github.com/NotNull92/hera-agent-unity) — Open Source Unity Agent CLI

<p align="center">
<img src="https://img.shields.io/badge/CLI-Go_1.25-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/Unity-2022.3%2B-222?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/Package-C%23_Editor-512BD4?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT" />
<img src="https://img.shields.io/badge/Status-Active-22C55E?style=for-the-badge" alt="Active" />
</p>

> Low-token Unity Editor control for AI coding agents.
> Gives Codex, Claude, Cursor, Copilot, and similar agents a measurable path through the real Unity Editor: status, console, C# execution, Play Mode, scene inspection, UI capture, tests, and screenshots.

<details>
<summary><b>🚀 Release Highlights</b></summary>
<br>

- **Unity Version Coverage** — separately checked on Unity 2022.3 LTS, 2023.2, 6000.3, and 6000.5
- **Token-Saving Protocol** — compact tool list at 93 tokens and object ID handoff around 49-55 tokens in benchmark docs
- **No Server Setup** — one Go binary plus a Unity package; no Python server, no generated MCP config
- **Agent-Facing Commands** — `status`, `doctor`, `list --compact`, `console`, `exec`, `editor play`, `scene info`, `ui_doc`, `test`, `screenshot`, `batch`
- **Ultra Hera** — light checks by default, stricter Unity verification when the task demands it

</details>

<details>
<summary><b>🧱 Engineering</b></summary>
<br>

- Go CLI with Bubble Tea / Lip Gloss TUI pieces, version checks, install/update flows, and cross-platform path handling
- Unity Editor connector with HTTP routing, heartbeat state, command discovery, asset config UI, and tool registration
- Tests around command dispatch, doctor/status/update/install paths, client behavior, polling, asset config, HTML-to-UI conversion, and Unity docs tooling
- Docs emphasize measurable Editor verification, token economy, agent rules, and repeatable benchmark evidence

</details>

---

### [Inventoria](https://github.com/NotNull92/Inventoria) — Backpack Defense RPG Prototype

<p align="center">
<img src="https://img.shields.io/badge/Engine-Unity_6-222?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/Genre-Backpack_Defense-FF6B6B?style=for-the-badge" alt="Backpack Defense" />
<img src="https://img.shields.io/badge/Architecture-asmdef_Modules-512BD4?style=for-the-badge" alt="asmdef Modules" />
<img src="https://img.shields.io/badge/Systems-Grid_%2B_Combat-22C55E?style=for-the-badge" alt="Grid + Combat" />
<img src="https://img.shields.io/badge/Status-Prototype-FFA500?style=for-the-badge" alt="Prototype" />
</p>

> A Unity 6 prototype exploring backpack inventory strategy, tower-defense style combat, and modular simulation code.

<details>
<summary><b>🎒 Gameplay Systems</b></summary>
<br>

- **Grid Inventory** — item placement, flattening, adjacency, simulation input, stat resolution, and synergy evaluation
- **Combat Simulation** — battle simulator, wave director, monster runtime, wall system, buffs, damage pipeline, weapon runtime, boss logic, and mana emblems
- **Loadout Flow** — lobby, gear, loadout, battle, result states with separated panels and controller logic
- **Progression Services** — save service, reward service, growth service, codex service, shop service, recipe service, and catalog/registry layer

</details>

<details>
<summary><b>🧩 Recent Work</b></summary>
<br>

- Shop slots, ad slots, panel isolation, and storage return behavior for the loadout screen
- Grid-inventory behavior for storage with fixes for duplicate drops, z-order, and multi-cell item sizing
- Addressables-oriented turret wiring, item icon wiring, battle FX wiring, and editor-side save tools
- `Game.Core`, `Game.Combat`, `Game.UI`, and `Game.Editor` assembly boundaries for faster iteration

</details>

---

### Current Focus

| Track | What I am building | Why it matters |
|:---|:---|:---|
| **Game** | `NoMoreRolls` combat, rewards, onboarding, and polish | A complete solo game with a distinct mechanical identity |
| **Tooling** | `hera-agent-unity` agent verification and Unity automation | Faster, safer Unity iteration for human + AI workflows |
| **Prototype** | `Inventoria` grid/loadout/combat loop | Rapid design exploration backed by deterministic systems |

---

## 🤖 AI & Tooling

<details>
<summary><b>🔧 Measured AI-Assisted Development</b></summary>
<br>

I use AI agents as execution partners, but the workflow is built around verification:

| Tool | Purpose |
|------|---------|
| **Codex / Claude Code** | implementation, refactoring, debugging, review loops |
| **hera-agent-unity** | live Unity Editor status, console, Play Mode, tests, screenshots |
| **Git / GitHub** | small commits, reproducible diffs, release notes, issue-backed work |
| **Obsidian / Notion** | design notes, production checklists, project memory |

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
Motto: "Measure the system, ship the build."
```

## 🛠️ Tech Stack

[![My Skills](https://skillicons.dev/icons?i=unity,godot,cs,py,go,react,github,git,nodejs,npm,jenkins,md,rider,vscode,notion,obsidian,stackoverflow&theme=dark)](https://skillicons.dev)

---

<div align="center">

[![Email](https://img.shields.io/badge/Email-fatiger92@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fatiger92@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-NotNull92-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NotNull92)

</div>
