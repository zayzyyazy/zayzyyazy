<!-- zayzyyazy · GitHub Profile README -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Zay&fontSize=72&fontColor=e8e0ff&fontAlignY=52&desc=Applied%20AI%20%C2%B7%20Workflow%20Automation%20%C2%B7%20AI-powered%20Products&descSize=14&descColor=b0a4d8&descAlignY=74&animation=fadeIn" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono\&size=14\&duration=3500\&pause=900\&color=9B8EC4\&center=true\&vCenter=true\&width=700\&lines=understand+the+workflow+%C2%B7+find+the+friction+%C2%B7+build;use+it+%C2%B7+find+what+breaks+%C2%B7+refine+it;AI+where+it+helps%2C+normal+logic+where+it+doesn't;TypeScript+%C2%B7+React+%C2%B7+Python+%C2%B7+APIs)](https://git.io/typing-svg)

</div>

---

<div align="center">
  <sub>
    B.Sc. Human-Centered Computing + Psychology &nbsp;·&nbsp; Universität Duisburg-Essen<br/>
    Interested in the full loop from an inefficient workflow to a tool that improves through real use.
  </sub>
</div>

---

## About me

I'm Zay, a Human-Centered Computing and Psychology student interested in applied AI, workflow automation and AI-powered products.

What interests me most is the process around the technology: understanding how something currently works, finding where it becomes repetitive or unclear, and deciding what could be improved through normal code, AI or a better workflow.

I like building a usable first version, putting it through real scenarios and adapting it based on what I learn. Most of my projects follow that pattern—from turning support messages into structured tickets to converting lecture PDFs into material I can actually study with.

I'm still early in my career and developing stronger foundations in backend engineering, testing, deployment and system design. I'm currently most comfortable with TypeScript, React, Python, APIs and structured LLM features.

---

## What I'm doing right now

Alongside university, I work with a company's existing production voice agent.

I review real conversations, test different scenarios and help investigate why the agent does not always behave as intended. From there, I contribute to improvements in its prompts, conversation flows, tool usage and handling of unexpected situations.

In practice, that includes:

* Reviewing call transcripts and identifying repeated failure patterns
* Testing expected paths, edge cases and unclear caller responses
* Refining instructions and parts of the conversation flow
* Testing lookups, function calls and connected workflows
* Helping decide what the agent should handle and when a person should take over
* Contributing to new functionality and explaining changes to different stakeholders

I did not build or architect the complete system. My work is focused on understanding how the existing agent behaves in real use and helping improve it over time.

This role has also taught me that improving an AI system rarely means changing only a prompt. The surrounding workflow—available information, business rules, integrations, fallbacks and human decisions—matters just as much.

---

## How I work

Most of my work follows the same loop:

<table>
<tr>
<td width="50%" align="center">
<b>1. Understand</b><br/>
<sub>Map the current process and the people, tools and information involved.</sub>
</td>
<td width="50%" align="center">
<b>2. Identify</b><br/>
<sub>Find repetitive work, unclear decisions and points where the workflow breaks.</sub>
</td>
</tr>
<tr>
<td align="center">
<b>3. Build</b><br/>
<sub>Create a small end-to-end version using code, AI and APIs where they are useful.</sub>
</td>
<td align="center">
<b>4. Use & test</b><br/>
<sub>Try real input, edge cases, missing data and unexpected behaviour.</sub>
</td>
</tr>
<tr>
<td align="center">
<b>5. Refine</b><br/>
<sub>Improve the logic, prompts, interface or original workflow based on what happens.</sub>
</td>
<td align="center">
<b>6. Adapt</b><br/>
<sub>Repeat as the requirements, users and system change.</sub>
</td>
</tr>
</table>

I don't try to use AI for every step. I prefer normal logic for predictable behaviour, AI for flexible or unstructured input, and human judgment where automation should stop.

---

## Projects

My projects are working prototypes and learning projects built around real friction I encountered.

### [AI Support Panel](https://github.com/zayzyyazy/AI-Support-panel)

A local support console that turns unstructured customer messages into structured tickets.

It classifies the message, suggests a priority and escalation status, calculates an SLA deadline and creates a ticket through HubSpot or a mock CRM. Rule-based fallbacks handle cases where the model output is uncertain or incomplete.

**Workflow:**
`Incoming message → classify → apply rules → calculate SLA → review → create ticket`

* Structured classification for category, priority and escalation
* Rule-based fallback behaviour
* Automatic SLA deadline calculation
* HubSpot ticket creation through the API
* Filtering, escalation indicators and ticket resolution

`React` · `Express` · `Electron` · `OpenAI API` · `HubSpot API`

---

### [Job Pipeline](https://github.com/zayzyyazy/job-pipeline)

A local application that turns scattered Gmail job alerts into a structured application pipeline.

It synchronizes emails, extracts job information and scores each role using defined components and mismatch penalties. Normal parsing handles predictable formats, with AI used as a fallback when the content is harder to structure.

**Workflow:**
`Gmail alerts → extract listings → normalize → score → filter → decide whether to apply`

* Gmail synchronization through OAuth
* Extraction across different email formats
* Heuristic parsing with an AI fallback
* Structured scoring and mismatch penalties
* SQLite storage, filtering and application tracking

`Python` · `Flask` · `SQLite` · `Gmail API` · `OpenAI API` · `OAuth`

---

### [Activity Intelligence](https://github.com/zayzyyazy/activity-intelligence)

An experimental desktop application that combines captured tasks, declared priorities and computer-activity context to recommend one next action.

Instead of producing another long productivity list, the application returns one structured recommendation in the format:

`NEXT_ACTION / WHY / AFTER`

**Workflow:**
`Capture tasks → read activity → compare with focus → choose one action → adjust`

* Activity data from ActivityWatch
* Unified inbox for tasks, notes and ideas
* Focus scoring for captured items
* One structured next-action recommendation
* Local storage with completion and promotion flows

`Tauri` · `Rust` · `React` · `TypeScript` · `ActivityWatch API` · `OpenAI API` · `SQLite`

---

### [Course Dashboard](https://github.com/zayzyyazy/course-dashboard)

A local-first desktop application that turns university lecture PDFs into structured study material.

It extracts and organizes lecture content, then creates summaries, key concepts, active-recall questions and focused explanations. AI questions remain scoped to the selected lecture.

**Workflow:**
`Import PDF → extract content → generate study material → practise → revisit topics`

* PDF import and text extraction
* Organization by course and lecture
* Summaries, key concepts and topic explanations
* Active-recall quizzes with attempt tracking
* Lecture-scoped AI questions and local notes

`Electron` · `React` · `TypeScript` · `Node.js` · `OpenAI API` · `KaTeX` · `SQLite`

---

### [Project Explainer](https://github.com/zayzyyazy/project-explainer)

A local desktop application that scans a codebase and creates a structured explanation of the project.

It applies ignore and size rules, prepares a limited snapshot for the Claude API and stores the resulting explanation in a local project library.

**Workflow:**
`Choose project → scan locally → filter files → build snapshot → explain → save`

* Local project-folder import
* File traversal with ignore and size rules
* Capped codebase snapshots
* Structured project explanations
* SQLite library for saved results

`Tauri` · `Rust` · `React` · `TypeScript` · `SQLite` · `Claude API`

---

## Stack

<table>
<tr>
<td width="28%"><b>Applied AI & workflows</b></td>
<td>workflow analysis · prompt and conversation design · structured outputs · function calling · testing and failure diagnosis · human escalation</td>
</tr>
<tr>
<td><b>Languages & frontend</b></td>
<td>TypeScript · React · Python · JavaScript · basic Rust</td>
</tr>
<tr>
<td><b>Applications & backend</b></td>
<td>Electron · Tauri · Express · Flask · SQLite</td>
</tr>
<tr>
<td><b>AI</b></td>
<td>OpenAI API · Claude API · Ollama · context preparation · fallback logic</td>
</tr>
<tr>
<td><b>Integrations</b></td>
<td>Gmail API · HubSpot API · ActivityWatch API · OAuth</td>
</tr>
<tr>
<td><b>Tools</b></td>
<td>Git · Vite · Tailwind CSS · Cursor · Claude Code</td>
</tr>
<tr>
<td><b>Currently improving</b></td>
<td>backend fundamentals · automated testing · deployment · system design</td>
</tr>
</table>

---

## What I'm working toward

I want to become someone who can move between understanding a process and building the technical system that improves it.

I'm looking for a **Werkstudent position** where I can contribute to applied AI, workflow automation, conversational systems, internal tools or AI-powered products. I'm especially interested in work where I can help identify opportunities for automation, build and test solutions, and keep refining them based on real use.

I don't train machine-learning models, and I'm not a backend or infrastructure specialist. My current strength is connecting a practical problem with a technical workflow and building a working version with TypeScript, React, Python, APIs and LLM features.

---

## Contact

**University:** Universität Duisburg-Essen
**Degree:** B.Sc. Human-Centered Computing + Psychology
**Email:** [zaraselim04@gmail.com](mailto:zaraselim04@gmail.com)

*Open to Werkstudent opportunities in applied AI, workflow automation, conversational AI and AI-powered products.*

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,24,12&height=90&section=footer&animation=fadeIn" width="100%" />

<sub>find the friction · build something useful · learn from reality · adapt</sub>

</div>
