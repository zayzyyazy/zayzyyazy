<!-- zayzyyazy · GitHub Profile README -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Zay&fontSize=72&fontColor=e8e0ff&fontAlignY=52&desc=Applied%20AI%20%C2%B7%20Voice%20Agents%20%C2%B7%20Workflow%20Automation&descSize=14&descColor=b0a4d8&descAlignY=74&animation=fadeIn" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono\&size=14\&duration=3500\&pause=900\&color=9B8EC4\&center=true\&vCenter=true\&width=650\&lines=working+on+real-world+voice+agent+behaviour;building+AI-powered+tools+around+everyday+friction;prompts+%C2%B7+APIs+%C2%B7+structured+outputs+%C2%B7+automation;TypeScript+%C2%B7+React+%C2%B7+Python)](https://git.io/typing-svg)

</div>

---

<div align="center">
  <sub>
    B.Sc. Human-Centered Computing + Psychology &nbsp;·&nbsp; Universität Duisburg-Essen<br/>
    Learning how to turn real problems into useful AI-powered tools.
  </sub>
</div>

---

## About me

I'm Zay, a Human-Centered Computing and Psychology student interested in applied AI, automation and AI-powered products.

Alongside university, I work with a company's existing production voice agent. My role is not to build the entire system or its infrastructure. I work closer to the agent's actual behaviour: how it understands callers, follows a conversation, uses available tools and responds when the situation does not match the expected flow.

A lot of my work begins with reviewing real conversations and asking fairly practical questions:

* Why did the agent misunderstand this caller?
* Was the instruction unclear, or is the workflow itself missing something?
* Should the agent handle this case or transfer it to a person?
* Did a lookup or function call return the right information?
* How can the conversation feel clearer without making the prompt more complicated?
* Does the change fix one case while breaking another?

From there, I test scenarios, refine prompts and conversation flows, help identify failure patterns, and work on smaller improvements and integrations around the agent.

Outside of work, I build my own applications to practise the technical side more deeply. Most of my projects combine a normal application with one structured AI step: classify something, extract information, explain a codebase, score an option or turn unstructured input into something usable.

I'm still early in my career and still building stronger foundations in backend development, testing, deployment and system design. I’m most comfortable working with TypeScript, React, Python, APIs and LLM-based features.

---

## What I do in practice

### Voice-agent testing and improvement

My strongest real-world experience so far comes from working with an existing production voice agent.

That includes:

* Reviewing real call transcripts and conversation logs
* Testing expected scenarios, unusual inputs and edge cases
* Finding points where the agent becomes confused, repetitive or too rigid
* Refining prompts, instructions and parts of the conversation flow
* Comparing expected behaviour with what actually happened
* Investigating whether failures come from prompting, workflow logic, missing context or a tool call
* Testing lookups, ticket creation, notifications and other connected functions
* Documenting issues and explaining proposed changes to technical and non-technical colleagues
* Contributing to new agent functionality without claiming ownership of the complete system

This work has made me interested in more than prompt wording. A good response depends on the surrounding workflow: what information the agent has, what actions it is allowed to take, when it should ask another question and when it should involve a human.

### Building small AI applications

In my own projects, I usually work across the whole small application:

* Define the problem and the minimum useful workflow
* Build the interface in React
* Add a small backend or local application layer
* Connect APIs and authentication where needed
* Design prompts and structured outputs
* Store results locally, usually with SQLite
* Test the complete flow and improve whatever feels unclear or unreliable

These are learning projects, not large production platforms. They help me understand how the interface, application logic, AI call and external integrations fit together.

---

## Projects

### [AI Support Panel](https://github.com/zayzyyazy/AI-Support-panel)

A local support console that turns unstructured customer messages into structured tickets.

The app sends an incoming message through an AI classification step and returns a category, priority and escalation recommendation. It can then calculate an SLA deadline and create a ticket through HubSpot or a mock CRM.

I also added rule-based fallback logic so the application is not completely dependent on the model producing the expected result.

**What I worked on:**

* Structured classification for category, urgency and escalation
* Rule-based fallback behaviour
* SLA deadline calculation
* HubSpot ticket creation through the API
* Filtering, escalation badges and ticket resolution
* A local desktop interface for testing the complete workflow

I built it to explore where AI can reduce repetitive support-triage work while still leaving uncertain or important cases to a person.

`React` · `Express` · `Electron` · `OpenAI API` · `HubSpot API`

---

### [Job Pipeline](https://github.com/zayzyyazy/job-pipeline)

A local application that collects job alerts from Gmail and turns them into a searchable application pipeline.

Job-alert emails are often inconsistent: some contain the complete role, others only contain a short preview or several different listings. The application first tries to extract the information with normal parsing logic and can use AI when the format is too messy.

Each role is then scored using defined components and mismatch penalties instead of relying only on a free-form model opinion.

**What I worked on:**

* Gmail OAuth and email synchronization
* Extracting job information from different email formats
* AI fallback for less predictable content
* Structured scoring with explicit criteria
* Basic role classification
* SQLite storage and filtering
* An application-assistance view for selected roles

I built it because I wanted a numeric signal I could filter by before spending time reading and applying—not another paragraph that I would still need to interpret manually.

`Python` · `Flask` · `SQLite` · `Gmail API` · `OpenAI API` · `OAuth`

---

### [Activity Intelligence](https://github.com/zayzyyazy/activity-intelligence)

An experimental desktop application that combines declared priorities, captured tasks and computer-activity context to suggest one concrete next action.

Instead of generating another long productivity list, the AI response follows a fixed structure:

`NEXT_ACTION / WHY / AFTER`

**What I worked on:**

* Reading activity information from ActivityWatch
* Capturing tasks, ideas and notes in one inbox
* Comparing captured items with a declared focus
* Generating one structured next-action recommendation
* Filtering, completing and promoting captured items
* Connecting a Tauri desktop application to local data

This project is an experiment in using AI for a small decision rather than for open-ended text generation.

`Tauri` · `Rust` · `React` · `TypeScript` · `ActivityWatch API` · `OpenAI API` · `SQLite`

---

### [Course Dashboard](https://github.com/zayzyyazy/course-dashboard)

A local-first desktop study application for university lecture material.

The application imports lecture PDFs, extracts their text and turns the content into several study formats. These include summaries, key concepts, recall questions and focused explanations of individual topics.

**What I worked on:**

* PDF import and text extraction
* Organizing content by course and lecture
* AI-generated summaries, concepts and quizzes
* Active-recall questions with attempt tracking
* Lecture-scoped AI questions
* Notes and local storage
* Mathematical content rendering with KaTeX

I built it because organizing lecture material was taking time away from actually studying it. The goal was a simpler flow from lecture PDF to usable revision material.

`Electron` · `React` · `TypeScript` · `Node.js` · `OpenAI API` · `KaTeX` · `SQLite`

---

### [Project Explainer](https://github.com/zayzyyazy/project-explainer)

A local desktop application that scans a codebase and generates a structured explanation of the project.

It collects a limited snapshot using ignore rules, sends the relevant content to the Claude API and stores the resulting explanation in a local library.

**What I worked on:**

* Importing local project folders
* Traversing files with ignore and size rules
* Building a capped representation of the codebase
* Generating a structured project explanation
* Saving previous results in SQLite
* Browsing explanations through a desktop interface

I built it because I often reopened an older project and had to reconstruct what it did, how it was organized and where I had stopped.

`Tauri` · `Rust` · `React` · `TypeScript` · `SQLite` · `Claude API`

---

## How I currently approach projects

I usually begin with something concrete that is repetitive, unclear or annoying enough to be worth improving.

My process is roughly:

1. **Understand the current workflow**
   What happens now? What information is available? Where does the process become slow or confusing?

2. **Choose a small useful outcome**
   I try to define what the first version should actually help someone do.

3. **Separate normal logic from AI logic**
   Not every decision needs an LLM. I use regular code for predictable steps and AI where the input is harder to structure.

4. **Build the full basic flow**
   I prefer having a small end-to-end version over several disconnected features.

5. **Use it and find the weak points**
   This is usually where I discover that my original assumptions were incomplete.

6. **Improve it incrementally**
   I simplify confusing parts, add fallbacks and make the output more structured.

I am still learning how to do each of these steps well. The projects on this profile show that learning process rather than finished, production-scale products.

---

## Stack and current experience

<table>
<tr>
<td width="28%"><b>Applied AI</b></td>
<td>prompt design · structured outputs · tool/function calling · conversation testing · failure analysis · human escalation flows</td>
</tr>
<tr>
<td><b>Languages</b></td>
<td>TypeScript · Python · JavaScript · basic Rust</td>
</tr>
<tr>
<td><b>Frontend</b></td>
<td>React · Vite · Tailwind CSS</td>
</tr>
<tr>
<td><b>Application development</b></td>
<td>Electron · Tauri · Flask · Express</td>
</tr>
<tr>
<td><b>Data</b></td>
<td>SQLite · JSON · local application storage</td>
</tr>
<tr>
<td><b>AI APIs</b></td>
<td>OpenAI API · Claude API · Ollama</td>
</tr>
<tr>
<td><b>Integrations</b></td>
<td>Gmail API · HubSpot API · ActivityWatch API · OAuth</td>
</tr>
<tr>
<td><b>Currently improving</b></td>
<td>backend fundamentals · automated testing · deployment · system design · debugging larger applications</td>
</tr>
</table>

---

## What I'm looking for

I'm looking for a **Werkstudent position** where I can continue developing practical experience around:

* Applied AI and LLM-powered features
* Conversational or voice agents
* Workflow and process automation
* Internal tools and AI-assisted products
* API integrations
* Testing and improving existing AI systems
* Prototyping ideas and turning them into working applications

I’m especially interested in roles where the work begins with understanding a real process or user problem—not only calling a model API.

I don't train machine-learning models, and I'm not a backend or infrastructure specialist. My current strength is connecting user or business problems with small technical solutions, then testing and improving those solutions while I continue building deeper engineering skills.

---

## Contact

**University:** Universität Duisburg-Essen
**Degree:** B.Sc. Human-Centered Computing + Psychology
**Email:** [zaraselim04@gmail.com](mailto:zaraselim04@gmail.com)

*Open to Werkstudent opportunities in applied AI, conversational AI, workflow automation and AI-powered products.*

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,24,12&height=90&section=footer&animation=fadeIn" width="100%" />

<sub>building useful things, testing them against reality, and learning from what breaks</sub>

</div>
