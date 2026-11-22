<div align="center">

# Ragini Roy

### AI Engineer | Agentic AI Developer | AI Automation | Open Source Contributor

I build, deploy and evaluate AI agents, and connect them to real interfaces and APIs.
Three agents deployed on SmartlyLabs. Google ADK and Gemini agent tooling. n8n + Gemini automation. Flask and Pinecone retrieval at Asvix. Open-source contributor in GSSoC 2026.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=flat-square&logo=google&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

</div>

---

## Highlights

| | |
|---|---|
| **3 deployed AI agents** | Public on SmartlyLabs (GSSoC 2026 Hybrid track). ML Guide Coach is at **v5** with **6 feedback entries** from users. |
| **GSSoC 2026** | **Top 100 global** on the Hybrid track (SmartlyLabs profile: score 782 at last check) <!-- VERIFY then replace with: "Ranked #27 on the Hybrid leaderboard, score 526 (snapshot: DATE, link)" --> |
| **Internship** | AI Full Stack Intern, Asvix Digital LLP. Python, Flask, Gemini, Pinecone. Response evaluation and API docs. |
| **Open source** | Merged feature PR in HerStack-org/website. OpenCV.js feature in sahidawa-india. New agent in iloveAgents. |

---

## Deployed AI Agents (SmartlyLabs)

Agents built, deployed and iterated on SmartlyLabs' agent infrastructure. Profile: [infra.smartlylabs.ai/profile/cmrujnenf002y04lbz7sapym1](https://infra.smartlylabs.ai/profile/cmrujnenf002y04lbz7sapym1) (agent chat pages require a SmartlyLabs sign-in).

### 1. AI/ML Guide Coach — v5, 6 user feedback entries
**Problem:** Generic AI assistants don't adapt to a learner's level or run realistic ML interview practice.
**How it works:** An intent classifier routes each query into Learning or Interview mode. A modular prompt orchestrator (system, learning and interview prompts) builds the response, and the SmartlyLabs runtime executes it. The workflow uses web search, Telegram and hooks. Interview mode runs Question → Answer → Evaluation → Follow-up → Feedback, with experience-aware study plans.
**Evaluation:** Every response is checked against six criteria: relevance, technical accuracy, adaptiveness, clarity, follow-up quality and educational value.
**Iteration:** Built across multiple versions, with structured user feedback used to tune prompts and behaviour.
**My role:** Designed the agent, prompt modules and evaluation criteria; deployed and iterated it. <!-- VERIFY role wording -->
**Stack:** OpenAI GPT · Prompt engineering · SmartlyLabs runtime · Telegram · hooks · web search
**Repo:** [github.com/Ragini-Roy7/AI-ML-Guide-Coach-Agent](https://github.com/Ragini-Roy7/AI-ML-Guide-Coach-Agent)
**Demos:** [Interview mode video](https://drive.google.com/file/d/1aT9jTqvuScVEFfDuHvelB7BZyQBKhWa1/view?usp=sharing) · [Full demo folder](https://drive.google.com/drive/folders/1ph07UItSgmnK8v4QmBW-lhMVEMaK6Nhc?usp=sharing)

### 2. SystemMind — AI Computer Science Systems Reasoning Agent
Traces a problem through algorithms, memory, operating systems, networks, databases and hardware so learners see how systems work beneath abstractions. Deployed on SmartlyLabs (research category, v1).

### 3. Third deployed agent
<!-- VERIFY: name (DevPilot? ML Interview Coach?), purpose, repo/demo link. Delete this block if no separate third agent. -->

**Agent tuning:** I also contribute accepted tuning work on the SmartlyLabs Intelligence track, for example output JSON reliability and stale-data retrieval in a data-collection step.

---

## Open Source & Community Achievements

**GirlScript Summer of Code 2026 — Hybrid / AI Agents track.** Top 100 global (see highlights above).
<!-- Hacktoberfest: add only once merged PRs are confirmed -->

| Repository | What I contributed | Area | PR | Status |
|---|---|---|---|---|
| RatLoopz/sahidawa-india | OpenCV.js packaging-geometry detection in the barcode scanner: lazy-loaded OpenCV.js, a periodic camera-frame detection hook, tests/fixtures (closes #3857) | Feature (computer vision, frontend) | [#3943](https://github.com/RatLoopz/sahidawa-india/pull/3943) | Merged <!-- VERIFY --> |
| HerStack-org/website | Project-Based Learning Track: beginner→advanced ML project roadmap, homepage ProjectPath section, concept-page "Put It Into Practice" links, nav link (closes #167) | Feature, docs, UI (React) | [#174](https://github.com/HerStack-org/website/pull/174) | **Merged** (Aug 17, 2026) |
| AditthyaSS/iloveAgents | DSA Progress Analyzer agent: turns a pasted practice log into a report of weak/strong topics, mistake patterns, next problems and a weekly action item (closes #780) | New agent | [#788](https://github.com/AditthyaSS/iloveAgents/pull/788) | Merged <!-- VERIFY --> |

---

## Engineering Experience

**AI Full Stack Intern — Asvix Digital LLP** · Sept 2026 – Present
- Work on Aroha and its IDSP AI chatbot: Python/Flask backend, Gemini generation, Pinecone embedding-based retrieval.
- Evaluate agent responses against IDSP source data using structured test cases, and refine prompts from the results.
- Write API documentation for the Aroha backend.

**Virtual EduSkills Internship — TensorFlow / Machine Learning**
- Exposure to TensorFlow, ML and deep learning fundamentals, and ML workflows (learning stage).

---

## More Featured Projects

### AI Issue Triage Agent
**Problem:** Triaging bug reports by hand is slow; an agent can gather evidence before a human looks.
**Approach:** A Google ADK agent using Gemini and tools that fetch GitHub issue context through the GitHub API. An agent that decides which tool to call and analyzes the result, rather than answering from a single prompt. <!-- VERIFY against code; add architecture to repo README -->
**Stack:** Python · Google ADK · Gemini · GitHub API
**Repo:** [github.com/Ragini-Roy7/ai-issue-triage-agent](https://github.com/Ragini-Roy7/ai-issue-triage-agent)

### n8n AI Ticket Automation
**Problem:** Support teams lose time sorting tickets and catching urgent ones.
**Trigger:** A ticket arrives via webhook or an n8n form, normalized to one JSON schema (name, email, subject, message).
**Gemini's role:** Classifies category, priority and sentiment, and writes a summary and recommended action, using a structured output parser.
**Decisions:** An AI agent decides whether to escalate (critical priority, payment/security concerns, or an explicit request for a human) and calls an escalation sub-workflow as a tool.
**Stack:** n8n · Gemini · AI agent · structured outputs · webhooks
**Repo:** [github.com/Ragini-Roy7/n8n-ai-ticket-automation](https://github.com/Ragini-Roy7/n8n-ai-ticket-automation) · **Demo:** [drive.google.com/file/d/1zW_8S4_wXaqwLDbCVjsjNOwx3-RUk-7p](https://drive.google.com/file/d/1zW_8S4_wXaqwLDbCVjsjNOwx3-RUk-7p/view?usp=sharing)

### BrainBridge
Hackathon team project (TypeScript). I led the team and built and tested REST API endpoints with validation, JSON responses and error handling.
**Repo:** [github.com/Ragini-Roy7/BrainBridge](https://github.com/Ragini-Roy7/BrainBridge)

---

## Technical Skills

| Level | Skills |
|---|---|
| **Built and deployed** | Prompt engineering · LLM agents (OpenAI, Gemini) · Google ADK · n8n workflows · Telegram/webhook integrations · evaluation criteria and test cases |
| **Used in projects** | Python · Flask · REST APIs · Pinecone · JavaScript/React · SQL |
| **Working knowledge** | Java · MongoDB · MySQL · scikit-learn · Firebase Auth · JWT |
| **Learning** | TensorFlow · RAG at scale |

---

## GitHub Activity

![Snake animation](https://raw.githubusercontent.com/Ragini-Roy7/Ragini-Roy7/output/github-snake-dark.svg)

![Stats](https://github-readme-stats.vercel.app/api?username=Ragini-Roy7&show_icons=true&theme=tokyonight) ![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Ragini-Roy7&layout=compact&theme=tokyonight)

![Streak](https://streak-stats.demolab.com/?user=Ragini-Roy7&theme=tokyonight)

---

## Coding Profiles & Contact

[LeetCode](https://leetcode.com/u/Ragini_Roy/) · [GeeksforGeeks](https://www.geeksforgeeks.org/profile/raginij1c) · [Kaggle](https://www.kaggle.com/ragini2002) · [HackerRank](https://www.hackerrank.com/profile/raginicodes)

[Email](mailto:raginicodes@gmail.com) · [LinkedIn](https://www.linkedin.com/in/ragini-roy-56231b25a/) · [SmartlyLabs profile](https://infra.smartlylabs.ai/profile/cmrujnenf002y04lbz7sapym1)
