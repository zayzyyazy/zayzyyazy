<!--  ╔══════════════════════════════════════════════════╗
      ║   zayzyyazy · GitHub Profile README              ║
      ║   Conversational AI · Agent Workflows · Automation║
      ╚══════════════════════════════════════════════════╝  -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Zay&fontSize=72&fontColor=e8e0ff&fontAlignY=52&desc=Applied%20AI%20%C2%B7%20Business%20Process%20Automation%20%C2%B7%20AI%20Solutions&descSize=14&descColor=b0a4d8&descAlignY=74&animation=fadeIn" width="100%" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3500&pause=900&color=9B8EC4&center=true&vCenter=true&width=650&lines=applied+AI+%C2%B7+turning+messy+processes+into+workflows;analysing+failures%2C+refining+behaviour%2C+improving+systems;strongest+current+example%3A+a+production+voice+agent;LLM+workflows+%C2%B7+API+integrations+%C2%B7+automation;TypeScript+%C2%B7+Python+%C2%B7+React)](https://git.io/typing-svg)

</div>

<br/>

---

<div align="center">
  <sub>
    B.Sc. Human-Centered Computing + Psychology &nbsp;·&nbsp; Universität Duisburg-Essen<br/>
    Turning messy business processes into AI workflows that actually hold up.
  </sub>
</div>

<br/>

---

## Who I am

I'm Zay. I build practical AI solutions that solve real problems — and I get just as much satisfaction from understanding an existing system, finding its weak points, and making it better step by step, as I do from building something new.

Since March, I've been working primarily on a company's production Voice Agent — analyzing real conversations, refining prompting and behavior, and contributing to new features. Parallel to that, I build my own AI projects and keep deepening how I think about LLM applications, automation, and intelligent workflows.

What actually drives me is the process: understand how a system behaves today, find the friction, design a better workflow, build a working version, test it against reality, and iterate.

---

## How I think about problems

I don't start by coding. The process is usually:

1. **Understand the system** — who's involved, what information flows where, where do people get stuck, where does it break down
2. **Find the bottleneck** — repetitive work, unclear workflows, inconsistent behavior, edge cases, places where AI could actually help instead of just being "AI"
3. **Design the workflow** — what should happen first, which decisions are AI's to make vs. a human's, what happens when something goes wrong
4. **Build a working prototype** — not something theoretically perfect, something real that can actually be tested
5. **Test against reality** — deliberately try to break it, ask *why* something failed instead of just patching it
6. **Iterate** — most of the enjoyment is here: making something that already exists cleaner, more reliable, less friction

This is also why the Voice Agent work has held my attention — not because it's "Voice AI," but because it's a constant stream of *why did this call fail*, *should the AI decide this or a human*, *what's actually missing here*. AI is the tool I currently use for that kind of work — not the point in itself.

---

## The project I've been working on: a production Voice Agent

Since March, I've been working primarily on the company's Voice Agent — not something I built from scratch or own end to end, but a system I'm responsible for understanding, testing, and making better. In practice that's meant:

- Testing the agent against real call scenarios and reading through conversation logs to find where it breaks
- Refining prompts, instructions, and conversation flow so it holds up under messy, unscripted real input
- Identifying failure modes and proposing concrete fixes — not just flagging problems
- Wiring up and testing API/tool integrations the agent relies on — lookups, ticket creation, notifications, function calls
- Working across the technical and non-technical side: explaining what changed and why to people who don't read agent configs

It's the strongest, most concrete example of applied AI work I have right now — but it's one project, not my whole identity. I'm comfortable enough with TypeScript, Python, and APIs to build and fix things myself. I'm not a backend or infrastructure engineer, and I don't train models.

---

## Projects

Outside of client work, I build smaller systems that follow a similar pattern: take messy input, run it through a structured AI step, produce something a person can actually use and trust.

<table>
<tr>
<td>

### [AI-support-panel](https://github.com/zayzyyazy/AI-Support-panel)

A local-first support console that classifies incoming messages with AI, assigns urgency, and creates structured tickets in HubSpot — so support teams stop reading every message by hand before routing it.

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

Repetitive classification doesn't need a human at the front of the queue. Wanted something that handles the routine decision and surfaces only what actually needs judgment — the same instinct I use when I'm deciding what an agent should handle automatically versus escalate.

</td>
</tr>
</table>

`React` · `Express` · `Electron` · `OpenAI` · `HubSpot CRM` · `SLA logic`

</td>
</tr>
</table>

---

<table>
<tr>
<td>

### [job-pipeline](https://github.com/zayzyyazy/job-pipeline)

A local-first pipeline that pulls Gmail job alerts, extracts the actual posting, and runs structured AI scoring on each one — a numeric signal before spending time applying, not another summary to interpret.

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

Job alerts come in scattered, descriptions buried in email snippets. Wanted a score I could filter on, not text I'd still have to read and judge myself.

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

### [activity-intelligence](https://github.com/zayzyyazy/activity-intelligence)

A personal decision engine. Takes declared focus, captured tasks, and real activity context — runs it through a structured AI call — and outputs one concrete next action. Not a to-do list, a decision.

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
- Filter, expand, mark done, promote

</td>
<td valign="top" width="45%">

Too many things open, no good way to decide which actually mattered. Wanted something that looks at what I've actually been doing, not just what I said I'd do, and makes a call.

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

I was spending more time organizing lecture notes than studying them. Wanted a PDF in, usable material out.

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

### [project-explainer](https://github.com/zayzyyazy/project-explainer)

A local desktop app that scans any codebase and returns a structured explanation, stored in a personal library. Code never leaves your machine except for the API call itself.

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

I kept reopening old projects just to remember what they were. Local-first wasn't a principle here — sending code to a hosted service just made less sense than keeping it on the machine.

</td>
</tr>
</table>

`Rust` · `TypeScript` · `React` · `Tauri` · `SQLite` · `Claude API`

</td>
</tr>
</table>

---

## Stack

<table>
<tr>
<td width="28%"><b>Applied AI / Agent Systems</b></td>
<td>agent behavior design · prompt & conversation design · function calling / tool integrations · production testing & failure diagnosis (strongest example: a production voice agent)</td>
</tr>
<tr>
<td><b>LLM & AI</b></td>
<td>OpenAI API · Claude API (Anthropic) · Ollama · structured JSON outputs · context management</td>
</tr>
<tr>
<td><b>Languages / Frontend</b></td>
<td>TypeScript · React · Python · Tauri · Rust (basic) · Electron</td>
</tr>
<tr>
<td><b>Backend / pipelines</b></td>
<td>Python · FastAPI · Flask · SQLite</td>
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

## Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=zayzyyazy&show_icons=true&hide_border=true&bg_color=0d1117&title_color=9b8ec4&icon_color=7c6fcd&text_color=c9d1d9&hide=contribs&count_private=true&rank_icon=github" height="150" />
&nbsp;&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com?user=zayzyyazy&hide_border=true&background=0d1117&ring=9b8ec4&fire=c084fc&currStreakLabel=9b8ec4&sideLabels=c9d1d9&currStreakNum=e8e0ff&sideNums=e8e0ff&dates=6e7681" height="150" />

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zayzyyazy&layout=compact&hide_border=true&bg_color=0d1117&title_color=9b8ec4&text_color=c9d1d9&langs_count=4" height="130" />

</div>

---

## Find me

**University:** Universität Duisburg-Essen — B.Sc. Human-Centered Computing + Psychology
📧 **Email:** zaraselim04@gmail.com

_Open to Werkstudentenstellen in applied AI, AI process automation, or AI-powered products — conversational AI included._

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,24,12&height=90&section=footer&animation=fadeIn" width="100%" />
<sub>building AI systems that hold up when real people use them</sub>
</div>
