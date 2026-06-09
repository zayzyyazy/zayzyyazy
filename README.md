<!--  ╔══════════════════════════════════════════════════╗
      ║   zayzyyazy · GitHub Profile README              ║
      ║    · Automation · Workflows ·Local-First Tools   ║
      ╚══════════════════════════════════════════════════╝  -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Zay&fontSize=72&fontColor=e8e0ff&fontAlignY=52&desc=LLM%20Systems%20%C2%B7%20Automation%20%C2%B7%20Local-First%20Tools&descSize=14&descColor=b0a4d8&descAlignY=74&animation=fadeIn" width="100%" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3500&pause=900&color=9B8EC4&center=true&vCenter=true&width=560&lines=%C2%B7+werkstudent+at+DKN+working+with+NLP+and+piplines;building+local-first+AI+tools;LLM+systems+%C2%B7+automation+%C2%B7+workflow+design;Tauri+%C2%B7+Rust+%C2%B7+React+%C2%B7+Python+%C2%B7+SQLite;structured+AI+output+that+actually+persists)](https://git.io/typing-svg)

</div>

<br/>

---

<div align="center">
  <sub>
    B.Sc. Human-Centered Computing + Psychology
        · Universität Duisburg-Essen
        <br/>
    Building local tools where language models do the actual processing work.
  </sub>
</div>

<br/>

---

## Who am I?

Hii :)

I’m Zay. End of my first year at university, currently working at an NLP company.

Before code, I was way more pulled toward philosophy, language, interpretation, meaning, and the question of how humans make sense of systems around them. That’s probably why I got interested in language models from the angle of structure, behavior, and information processing, not just “AI that generates text.”

Right now I study Human Centered Computing + Psychology, and most of what I build sits somewhere in that intersection: local-first tools, AI workflows, automation systems, study infrastructure, decision-support tools, and projects that try to make messy information actually usable.

Over the past year I kept building the same kinds of things without even planning to: LLM workflows, local desktop apps, AI-assisted systems, organization tools, research tools, automation pipelines. At some point it stopped feeling random and started feeling like an actual direction.

Most of what’s here was built fast, locally, experimentally, and very hands-on. I like building things that are usable first, then refining them through iteration instead of waiting for some “perfect” version before shipping anything.

---

## Snapshot

| 📍 Location | Essen, Germany |
|---|---|
| 🎓 Degree | B.Sc. Human-Centered Computing + Psychology · Universität Duisburg-Essen · Year 1 done |
| 🌍 Languages | German (C1) · English (C1) · French (B1) |
| 🛠️ Stack | Tauri · Rust · React · TypeScript  · Python · FastAPI · Flask · SQLite · LLM APIs ·|

---

## What I actually build

Most things I've built follow roughly the same shape:  messy input comes in a PDF, a job listing, a codebase, a pile of notes  a language model processes it with some structure behind the prompt, and the output ends up in SQLite where it's actually usable. Local storage by default. Not cloud-dependent.

In practice:

- Import a lecture PDF → structured study cards, quizzes, topic deep dives → stored in a local course vault
- Pull job listings from Gmail → structured AI scoring on each → real signal before you spend time applying
- Scan a codebase → send a capped snapshot to Claude → structured explanation stored in SQLite
- Capture context and open tasks → run through a decision engine → one concrete next action

I built each of these because I actually needed them. The stack converged on roughly the same shape each time: local storage, real prompt design, real UI, and I stopped fighting that convergence.

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

I kept spending more time organizing lecture notes than actually studying them. I wanted something that takes a PDF and turns it into material I'd actually use — structured, queryable, local. Built it for my own courses, kept using it.

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

I had too many things open with no good way to decide which one actually mattered. I wanted something that looks at what I've been doing, what I've captured, and what I said I cared about — and makes a decision, not a list.

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

Support teams still read every message manually before routing it. That kind of repetitive classification doesn't need a human at the front. I wanted something that handles the routine decisions and only surfaces what actually needs judgment — connected to a real CRM, not just a demo concept.

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

Job alerts come in scattered, descriptions are buried in email snippets, and going through them one by one is slow. I wanted an actual score on each listing — something I could filter on, not a summary I'd still have to interpret.

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

I kept reopening old projects just to remember what they were. I wanted something that reads the codebase, sends it to Claude, and keeps the explanation. The local-first part wasn't a principle — sending code to a hosted service just made less sense.

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

_Looking for Werkstudentenstellen in LLM systems, automation, or applied NLP._

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,24,12&height=90&section=footer&animation=fadeIn" width="100%" />
<sub>year 1 done · a lot more to build</sub>
</div>
