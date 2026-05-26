<!--  ╔══════════════════════════════════════════════════╗
      ║   zayzyyazy · GitHub Profile README              ║
      ║   LLM Systems · Automation · Local-First Tools   ║
      ╚══════════════════════════════════════════════════╝  -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Zay&fontSize=72&fontColor=e8e0ff&fontAlignY=52&desc=LLM%20Systems%20%C2%B7%20Automation%20%C2%B7%20Local-First%20Tools&descSize=14&descColor=b0a4d8&descAlignY=74&animation=fadeIn" width="100%" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3500&pause=900&color=9B8EC4&center=true&vCenter=true&width=560&lines=End+of+year+1+%C2%B7+working+in+NLP;building+local-first+AI+tools;LLM+systems+%C2%B7+automation+%C2%B7+workflow+design;Tauri+%C2%B7+Rust+%C2%B7+React+%C2%B7+Python+%C2%B7+SQLite;structured+AI+output+that+actually+persists)](https://git.io/typing-svg)

</div>

<br/>

---

<div align="center">
  <sub>
    B.Sc. Human-Centered Computing + Psychology
        · Universität Duisburg-Essen
        <br/>
    Building local tools where language models do structured work.
  </sub>
</div>

<br/>

---

## Who am I?

I'm Zay — end of year one at university, working at an NLP company.

I build local-first tools where language models do structured work: desktop apps with real UI, real storage, real pipelines. Most of what I make runs on your machine, stores in SQLite, and processes something useful — lecture PDFs into study cards, job listings into scored decisions, codebases into structured explanations.

The direction that's gotten clear over the past year: LLM systems, automation, workflow design, applied NLP. Less focused on classic analytics, more focused on tools that actually transform and organize work.

---

## Snapshot

| 📍 Location | Essen, Germany |
|---|---|
| 🎓 Degree | B.Sc. Human-Centered Computing + Psychology · Universität Duisburg-Essen · Year 1 done |
| 🌍 Languages | German (C1) · English (C1) · French (B1) |
| 🛠️ Stack | Tauri · Rust · React · TypeScript · Electron · Python · FastAPI · Flask · SQLite · OpenAI API · Claude API · Ollama |

---

## What I actually build

The pattern keeps repeating: messy input → structured AI processing → persistent, queryable output. Not a chatbot wrapper, not a demo — tools that do something real with the data.

In practice:

- Import a lecture PDF → generate study cards, quizzes, topic deep dives → stored locally in a course vault
- Pull job listings from Gmail → run structured AI scoring on each → clear signal before applying
- Scan a codebase → send a capped snapshot to Claude → store a structured explanation in SQLite
- Capture context and open loops → run through a decision engine → get one concrete next action

Each of these is something I built for a real problem. The architecture is always the same: local storage, structured LLM calls, real UI.

---

## 📂 Featured Projects

<table>
<tr>
<td>

<h3><a href="https://github.com/zayzyyazy/course-dashboard">Course Dashboard</a></h3>

A local-first desktop study OS for university courses. Import lecture PDFs — the app extracts, profiles, and processes them into structured study material: summaries, key concepts, active recall quizzes, topic deep dives, and a full reading mode with math rendering.

<br/>

<table>
<tr>
<th align="left">What it does</th>
<th align="left">Why I built it</th>
</tr>
<tr>
<td valign="top" width="55%">

- **PDF ingestion** with text extraction and lecture profiling
- AI generates **summary, key concepts, quiz, topic dives** per lecture
- **Active recall quiz** mode with attempt tracking
- **Ask AI** scoped to the current lecture context
- Math rendering (KaTeX) for STEM content
- **Local vault** — all course data on your machine

</td>
<td valign="top" width="45%">

I was spending more time organizing study material than actually studying it. I wanted a tool that takes a lecture PDF and turns it into a proper study resource — real structure, not just a summary. Built it for my own courses, shipped as a desktop app.

</td>
</tr>
</table>

<br/>

`Electron` &nbsp;·&nbsp; `React` &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; `Node.js` &nbsp;·&nbsp; `OpenAI API` &nbsp;·&nbsp; `KaTeX` &nbsp;·&nbsp; `SQLite`

</td>
</tr>
</table>

---

<table>
<tr>
<td>

<h3><a href="https://github.com/zayzyyazy/activity-intelligence">Activity Intelligence</a></h3>

A personal decision engine. Takes your declared focus, captured tasks, and real activity context — runs it through a structured AI call — and outputs ONE concrete next action. Not a to-do list. A system for cutting through noise.

<br/>

<table>
<tr>
<th align="left">What it does</th>
<th align="left">Why I built it</th>
</tr>
<tr>
<td valign="top" width="55%">

- Reads **real activity data** from ActivityWatch
- Structured AI call outputs **ONE clear next action** — not a list
- Format: NEXT\_ACTION / WHY / AFTER
- Captures tasks, ideas, notes, questions in a unified inbox
- **Focus scoring** for matching captured items to declared context
- Actionable: filters, expand, mark done, promote

</td>
<td valign="top" width="45%">

I had many open things and no clear signal on what actually mattered next. I wanted something that looks at what I've been doing, what I've captured, and what I said I care about — and makes a decision, not a list.

</td>
</tr>
</table>

<br/>

`Tauri` &nbsp;·&nbsp; `Rust` &nbsp;·&nbsp; `React` &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; `ActivityWatch API` &nbsp;·&nbsp; `OpenAI` &nbsp;·&nbsp; `SQLite`

</td>
</tr>
</table>

---

<table>
<tr>
<td>

<h3><a href="https://github.com/zayzyyazy/AI-Support-panel">AI Support Operations Console</a></h3>

A local-first support console that classifies incoming messages with AI, assigns urgency, and creates structured tickets in HubSpot — so support teams stop reading every message by hand.

<br/>

<table>
<tr>
<th align="left">What it does</th>
<th align="left">Why I built it</th>
</tr>
<tr>
<td valign="top" width="55%">

- Ingests support messages from a form or operator panel
- **AI classifies** category, priority, and escalation flag
- Falls back to **rule-based logic** when the model is unsure
- Calculates **SLA deadlines** automatically
- Creates tickets in **HubSpot** (or Mock CRM) via API
- Dashboard with filters, escalation badges, resolve flow

</td>
<td valign="top" width="45%">

Support teams still read every message manually and decide what to do with it. It's work that drains people fast and doesn't need a human at the front. I wanted something that handles routine triage and only escalates what actually needs a human — with a real CRM connected, not just a demo.

</td>
</tr>
</table>

<br/>

`React` &nbsp;·&nbsp; `Express` &nbsp;·&nbsp; `Electron` &nbsp;·&nbsp; `OpenAI` &nbsp;·&nbsp; `HubSpot CRM` &nbsp;·&nbsp; `SLA logic`

</td>
</tr>
</table>

---

<table>
<tr>
<td>

<h3><a href="https://github.com/zayzyyazy/job-pipeline">job-pipeline</a></h3>

A local-first pipeline that pulls Gmail job alerts, extracts the actual posting, and runs structured AI scoring on each one — clear signal before you spend time applying.

<br/>

<table>
<tr>
<th align="left">What it does</th>
<th align="left">Why I built it</th>
</tr>
<tr>
<td valign="top" width="55%">

- Syncs **Gmail job alerts** via OAuth
- **Heuristic extraction** with AI fallback for messy formats
- Structured AI scoring with **explicit components + mismatch penalties** — not free-form LLM text
- Classifies roles (AI workflow vs backend-heavy vs generic)
- **Skills breakdown**: Required / Tools / Nice to have
- All data in **SQLite** — Apply Assist for fast applications

</td>
<td valign="top" width="45%">

Job alerts come in scattered, descriptions are buried in snippets, and researching each one by hand is slow. I wanted structured signal early — actual scored decisions, not summaries.

</td>
</tr>
</table>

<br/>

`Python` &nbsp;·&nbsp; `Flask` &nbsp;·&nbsp; `SQLite` &nbsp;·&nbsp; `Gmail API` &nbsp;·&nbsp; `OpenAI` &nbsp;·&nbsp; `OAuth`

</td>
</tr>
</table>

---

<table>
<tr>
<td>

<h3><a href="https://github.com/zayzyyazy/project-explainer">project-explainer</a></h3>

A local desktop app that scans any codebase and returns a structured explanation — stored in a personal library. Your code never leaves your machine except for the API call.

<br/>

<table>
<tr>
<th align="left">What it does</th>
<th align="left">Why I built it</th>
</tr>
<tr>
<td valign="top" width="55%">

- Imports any **local project folder**
- Scans and snapshots the codebase with smart ignore rules
- Sends a capped snapshot to the **Claude API**
- Stores structured explanations in **SQLite**
- Browse your full **project library** from a clean UI

</td>
<td valign="top" width="45%">

Every time I opened an unfamiliar codebase I wasted time just figuring out what it was. I wanted a tool that gives me a clear structured explanation in seconds — and remembers it. Built local-first so nothing gets sent to a server except the API call.

</td>
</tr>
</table>

<br/>

`Rust` &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; `React` &nbsp;·&nbsp; `Tauri` &nbsp;·&nbsp; `SQLite` &nbsp;·&nbsp; `Claude API`

</td>
</tr>
</table>

---

## 🛠️ Stack

**Desktop:** Tauri 2 · Rust · React · TypeScript · Electron  
**Backend / pipelines:** Python · FastAPI · Flask · SQLite  
**AI:** OpenAI API · Claude API (Anthropic) · Ollama (local LLMs)  
**Tools:** Cursor · Claude Code · Vite · Tailwind CSS

---

## 📊 Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=zayzyyazy&show_icons=true&hide_border=true&bg_color=0d1117&title_color=9b8ec4&icon_color=7c6fcd&text_color=c9d1d9&hide=contribs&count_private=true&rank_icon=github" height="150" />
&nbsp;&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com?user=zayzyyazy&hide_border=true&background=0d1117&ring=9b8ec4&fire=c084fc&currStreakLabel=9b8ec4&sideLabels=c9d1d9&currStreakNum=e8e0ff&sideNums=e8e0ff&dates=6e7681" height="150" />

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zayzyyazy&layout=compact&hide_border=true&bg_color=0d1117&title_color=9b8ec4&text_color=c9d1d9&langs_count=4" height="130" />

</div>

---

## 📬 Find me

**University:** Universität Duisburg-Essen — B.Sc. Human-Centered Computing + Psychology  
📧 **Email:** zaraselim04@gmail.com

_Open to Werkstudentenstellen in LLM systems, automation, workflow tooling, or applied NLP._

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,24,12&height=90&section=footer&animation=fadeIn" width="100%" />
<sub>building intentionally · early in the path · moving in a clear direction</sub>
</div>
