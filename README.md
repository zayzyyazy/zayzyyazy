<!--  ╔══════════════════════════════════════════════════╗
      ║   zayzyyazy · GitHub Profile README              ║
      ║   LLM Systems · Agent Workflows · Local-First    ║
      ╚══════════════════════════════════════════════════╝  -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Zay&fontSize=72&fontColor=e8e0ff&fontAlignY=52&desc=LLM%20Systems%20%C2%B7%20Agent%20Workflows%20%C2%B7%20Local-First%20Tools&descSize=14&descColor=b0a4d8&descAlignY=74&animation=fadeIn" width="100%" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3500&pause=900&color=9B8EC4&center=true&vCenter=true&width=600&lines=building+AI+systems+that+actually+process+information;LLM+pipelines+%C2%B7+structured+outputs+%C2%B7+agent+workflows;document+analysis+%C2%B7+knowledge+extraction+%C2%B7+retrieval;TypeScript+%C2%B7+React+%C2%B7+Python+%C2%B7+Tauri+%C2%B7+SQLite;local-first+by+default%2C+not+by+principle)](https://git.io/typing-svg)

</div>

<br/>

---

<div align="center">
  <sub>
    B.Sc. Human-Centered Computing + Psychology &nbsp;·&nbsp; Universität Duisburg-Essen<br/>
    Building systems where LLMs do real processing work — not just generating text.
  </sub>
</div>

<br/>

---

## Who am I?

I'm Zay. I study Human-Centered Computing and Psychology, and I work at an NLP company.

Before I cared about code, I cared about philosophy — how humans make sense of systems, how meaning gets built and broken, how structure shapes behavior. That lens is probably why I ended up building what I build: not apps that talk, but systems that think. Things that take messy information and make it actually usable.

Over the past year the pattern became clear: I keep building LLM workflows, document pipelines, agent architectures, and automation systems. That's not random anymore — it's a direction.

Most of my work sits at the intersection of **language models, information processing, and human workflows**. I'm less interested in model training or ML research and more focused on building practical systems on top of existing LLMs: structured outputs, retrieval, multi-step pipelines, and early multi-agent designs where different components handle different parts of a problem.

---

## What I actually build

The architecture that keeps showing up across my projects:

```
Raw Input (PDF · email · codebase · notes)
    → Structured extraction
    → LLM processing with prompt design
    → SQLite local storage
    → Queryable, usable output
```

In practice, that looks like:

- Import a lecture PDF → structured study material, quizzes, topic dives → stored locally
- Pull Gmail job alerts → AI scoring with explicit components → filter by actual signal
- Scan a codebase → structured explanation via Claude API → searchable project library
- Feed a document to multiple agents → each analyzes from a different angle → synthesized output

The local-first default isn't a principle — it's usually just the right call for the type of data involved.

---

## 📦 What I'm focused on right now

<table>
<tr>
<td width="50%">

**Multi-agent workflows**

Systems where multiple specialized agents exchange information, critique each other's outputs, or analyze a problem from different perspectives before reaching a conclusion. Moving past single-prompt pipelines.

</td>
<td width="50%">

**Document intelligence**

LLM-powered analysis of PDFs, research papers, and structured documents — not summarization, but extraction, classification, and knowledge structuring with real schemas behind the prompt.

</td>
</tr>
<tr>
<td width="50%">

**AI-assisted review systems**

Workflows that help users process information, surface decisions, and review content — where the LLM handles classification and structuring, not just generation.

</td>
<td width="50%">

**Workflow orchestration**

Designing pipelines where information moves through multiple processing stages. Context management, prompt chaining, structured JSON hand-offs between steps.

</td>
</tr>
</table>

---

## 📂 Featured Projects

<table>
<tr>
<td>

### [activity-intelligence](https://github.com/zayzyyazy/activity-intelligence)

A personal decision engine. Takes declared focus, captured tasks, and real activity context — runs it through a structured AI call — and outputs **one concrete next action**. Not a to-do list. A system for cutting through noise.

<table>
<tr>
<th align="left">What it does</th>
<th align="left">Why I built it</th>
</tr>
<tr>
<td valign="top" width="55%">

- Reads real activity data from ActivityWatch
- Structured AI call: ONE next action — format `NEXT_ACTION / WHY / AFTER`
- Captures tasks, ideas, notes in a unified inbox
- Focus scoring to match captured items to declared context
- Filters, expand, mark done, promote

</td>
<td valign="top" width="45%">

Too many things open, no good way to decide which actually mattered. Wanted something that looks at what I've been doing, what I've captured, and what I declared I cared about — then makes a decision, not a list.

</td>
</tr>
</table>

`Tauri` · `Rust` · `React` · `TypeScript` · `ActivityWatch API` · `OpenAI` · `SQLite`

</td>
</tr>
</table>

---

<table>
<tr>
<td>

### [project-explainer](https://github.com/zayzyyazy/project-explainer)

A local desktop app that scans any codebase and returns a structured explanation — stored in a personal library. Your code never leaves your machine except for the API call.

<table>
<tr>
<th align="left">What it does</th>
<th align="left">Why I built it</th>
</tr>
<tr>
<td valign="top" width="55%">

- Imports any local project folder
- Scans and snapshots the codebase with smart ignore rules
- Sends a capped snapshot to the Claude API
- Stores structured explanations in SQLite
- Browse your full project library from a clean UI

</td>
<td valign="top" width="45%">

I kept reopening old projects just to remember what they were. Wanted something that reads the codebase, sends it to Claude, and keeps the explanation. Local-first wasn't a principle — sending code to a hosted service just made less sense.

</td>
</tr>
</table>

`Rust` · `TypeScript` · `React` · `Tauri` · `SQLite` · `Claude API`

</td>
</tr>
</table>

---

<table>
<tr>
<td>

### [job-pipeline](https://github.com/zayzyyazy/job-pipeline)

A local-first pipeline that pulls Gmail job alerts, extracts the actual posting, and runs structured AI scoring on each one — clear signal before spending time applying.

<table>
<tr>
<th align="left">What it does</th>
<th align="left">Why I built it</th>
</tr>
<tr>
<td valign="top" width="55%">

- Syncs Gmail job alerts via OAuth
- Heuristic extraction with AI fallback for messy formats
- Structured AI scoring with explicit components + mismatch penalties — not free-form LLM text
- Classifies roles (AI workflow vs backend-heavy vs generic)
- All data in SQLite — Apply Assist for fast applications

</td>
<td valign="top" width="45%">

Job alerts come in scattered, descriptions are buried in email snippets. Wanted an actual numeric score on each listing — something I could filter on, not a summary I'd still have to interpret.

</td>
</tr>
</table>

`Python` · `Flask` · `SQLite` · `Gmail API` · `OpenAI` · `OAuth`

</td>
</tr>
</table>

---

<table>
<tr>
<td>

### [course-dashboard](https://github.com/zayzyyazy/course-dashboard)

A local-first desktop study OS. Import lecture PDFs — the app extracts, profiles, and processes them into structured study material: summaries, key concepts, active recall quizzes, topic deep dives.

<table>
<tr>
<th align="left">What it does</th>
<th align="left">Why I built it</th>
</tr>
<tr>
<td valign="top" width="55%">

- PDF ingestion with text extraction and lecture profiling
- AI generates summary, key concepts, quiz, topic dives per lecture
- Active recall quiz mode with attempt tracking
- Ask AI scoped to the current lecture context
- Math rendering (KaTeX) · local vault

</td>
<td valign="top" width="45%">

I kept spending more time organizing lecture notes than actually studying them. Wanted something that takes a PDF and turns it into material I'd actually use.

</td>
</tr>
</table>

`Electron` · `React` · `TypeScript` · `Node.js` · `OpenAI API` · `KaTeX` · `SQLite`

</td>
</tr>
</table>

---

<table>
<tr>
<td>

### [AI-support-panel](https://github.com/zayzyyazy/AI-Support-panel)

A local-first support console that classifies incoming messages with AI, assigns urgency, and creates structured tickets in HubSpot — so support teams stop reading every message by hand.

<table>
<tr>
<th align="left">What it does</th>
<th align="left">Why I built it</th>
</tr>
<tr>
<td valign="top" width="55%">

- AI classifies category, priority, and escalation flag
- Falls back to rule-based logic when the model is unsure
- Calculates SLA deadlines automatically
- Creates tickets in HubSpot (or Mock CRM) via API
- Dashboard with filters, escalation badges, resolve flow

</td>
<td valign="top" width="45%">

Support teams still read every message manually before routing. Repetitive classification doesn't need a human at the front. Wanted something that handles routine decisions and surfaces only what actually needs judgment.

</td>
</tr>
</table>

`React` · `Express` · `Electron` · `OpenAI` · `HubSpot CRM` · `SLA logic`

</td>
</tr>
</table>

---

## 🛠️ Stack

<table>
<tr>
<td width="25%"><b>Desktop</b></td>
<td>Tauri 2 · Rust · React · TypeScript · Electron</td>
</tr>
<tr>
<td><b>Backend / pipelines</b></td>
<td>Python · FastAPI · Flask · SQLite</td>
</tr>
<tr>
<td><b>LLM & AI</b></td>
<td>OpenAI API · Claude API (Anthropic) · Ollama · structured JSON outputs · prompt engineering · context management</td>
</tr>
<tr>
<td><b>Integrations</b></td>
<td>Gmail API · HubSpot · ActivityWatch · OAuth</td>
</tr>
<tr>
<td><b>Tools</b></td>
<td>Cursor · Claude Code · Vite · Tailwind CSS</td>
</tr>
</table>

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

_Open to Werkstudentenstellen in LLM systems, AI automation, or applied NLP._

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,24,12&height=90&section=footer&animation=fadeIn" width="100%" />
<sub>building systems that actually process things · not just generate text</sub>
</div>
