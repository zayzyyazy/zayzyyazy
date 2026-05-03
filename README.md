<!--  ╔══════════════════════════════════════════════════╗
      ║   zayzyyazy · GitHub Profile README              ║
      ║   HCI · Universität Duisburg-Essen               ║
      ╚══════════════════════════════════════════════════╝  -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Zay&fontSize=72&fontColor=e8e0ff&fontAlignY=52&desc=Human-Centered%20Computing%20·%20Builder%20of%20Useful%20Things&descSize=14&descColor=b0a4d8&descAlignY=74&animation=fadeIn" width="100%" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3500&pause=900&color=9B8EC4&center=true&vCenter=true&width=520&lines=HCI+student+%40+Universit%C3%A4t+Duisburg-Essen;building+tools+that+are+useful%2C+not+just+functional;thinking+about+what+technology+does+to+people;early+in+the+journey+%E2%80%94+building+intentionally)](https://git.io/typing-svg)

</div>

<br/>

---

<div align="center">
  <sub>
    B.Sc. Menschzentrierte Informatik &amp; Psychologie
        · Universität Duisburg-Essen
        <br/>
    Interested in how technology shapes people
        and how people should shape technology.
  </sub>
</div>

<br/>

---

## Who am I?

I'm Zay, in my first year studying HCI :)

What I care about is building things that are actually useful: tools that handle information clearly, reduce friction, and don't require the person using them to think harder than necessary. I'm drawn to automation, document processing, personal knowledge systems, and the philosophical side of what technology does to people and society.

I also have a deeper passion exploring the meaning behind things. Be it systems or behaviours, I enjoy in depth analysis and research into topics that directly affect us as human beings.

That answers "Why HCI?": I genuinely enjoy learning technology and psychology, which is exactly what it's all about.

---

## Snapshot

| 📍 Location | Essen, Germany |
|---|---|
| 🎓 Degree | B.Sc. Human-Centered Computing + Psychology (1st year) |
| 🌍 Languages | German (C1) · English (C1) · French (B1) |
| 🛠️ Skills | LLM APIs · Prompting · API integrations · n8n · OAuth · Figma · Cursor · Claude Code |

---

## What I actually care about

I keep circling back to the same things: how people interact with systems, and how those systems quietly shape what they can or can't do. I don't care about tech as hype, I care about what actually works, especially when it removes friction instead of adding more noise.

I'm drawn to building small, practical setups that take messy information and turn it into something usable,so mething that actually helps you think clearer or move faster.

And beyond that, I can't ignore the deeper layer: how technology isnt neutral, how design decisions carry power, bias, and control. That part interests me more than most of the technical side, because it's where things stop being abstract and start affecting real lives, where analysis of what's being built and how it affects humans starts coming to light, often with opinions warning against possible harm to the human psyche and the nature of humanity being ignored.

---

## 📂 Featured Projects

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
- Creates tickets in **HubSpot** (or a Mock CRM) via API
- Dashboard with filters, escalation badges, resolve flow

</td>
<td valign="top" width="45%">

Support teams still read every message manually and decide what to do with it. It's the kind of work that drains people fast and doesn't really need a human at the front. I wanted to see if I could build something that does the routine triage and only hands real edge cases back to a human — with a real CRM connected, not just a demo.

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

A local-first pipeline that pulls Gmail job alerts, extracts the actual posting from the noise, and runs AI analysis on each one — so the inbox stops being a research bottleneck.

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
- Optional: finds the **original posting** on the open web
- AI enrichment for **skills, fit, and source quality**
- Stores everything **locally in SQLite**
- Decision dashboard: Saved / Applied / Ignored

</td>
<td valign="top" width="45%">

I was on the receiving end of this problem. Job alerts come in scattered across email, the actual description is buried in snippets, and researching each one by hand takes forever. I wanted something that turns that noise into structured leads — with the source still traceable so I can tell where the info came from.

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

A local desktop app that imports any codebase, scans it, and returns a structured explanation — stored in a personal library. Your code never leaves your machine.

<br/>

<table>
<tr>
<th align="left">What it does</th>
<th align="left">Why I built it</th>
</tr>
<tr>
<td valign="top" width="55%">

- Imports any **local project folder**
- Scans and snapshots the codebase intelligently
- Sends a capped snapshot to the **Claude API**
- Stores structured explanations in **SQLite**
- Browse your full **project library** from a clean UI

</td>
<td valign="top" width="45%">

Every time I opened an unfamiliar codebase I wasted time just figuring out what it was. I wanted a tool that gives me a clear, structured explanation in seconds — and remembers it. Built local-first so nothing gets sent to a server except the API call.

</td>
</tr>
</table>

<br/>

`Rust` &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; `React` &nbsp;·&nbsp; `Tauri` &nbsp;·&nbsp; `SQLite` &nbsp;·&nbsp; `Claude API`

</td>
</tr>
</table>

---

## 🛠️ Skills

**AI & Automation** — LLM APIs (OpenAI, Claude) · Prompting & structured outputs · API integrations (Mail, CRM) · n8n / automation workflows · OAuth & local data handling

**Product & Workflow Thinking** — Breaking down processes · spotting bottlenecks · designing automation logic · human-in-the-loop decisions · translating problems into inputs & outputs

**Research & Writing** — Researching complex topics · breaking systems down and explaining them · writing clear demos & docs · structured argumentation

**Tools** — Cursor · Claude Code · Figma · Photoshop · Canva · Notion · Excel

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

**University:** Universität Duisburg-Essen — B.Sc. Menschzentrierte Informatik & Psychologie
- 📧 **Email:** zaraselim04@gmail.com
- 🌐 **Portfolio:** coming soon

_I'm open to Werkstudentenstellen and internships in data analysis, research, automation, or anything at the HCI / AI / information systems intersection._

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,24,12&height=90&section=footer&animation=fadeIn" width="100%" />
<sub>building slowly · building intentionally</sub>
</div>
