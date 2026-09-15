<div align="center">

# Lakshya Dharkar

### I don't read about AI. I build it, break it, and rebuild it until it makes sense.

</div>

---

### The short version

CS student in Indore who learns by shipping. Most of what I know about agents, RAG, and LLM infra didn't come from a course — it came from building three real systems, watching them break in production-ish ways, and fixing them. Currently hunting for a Python Developer / AI Engineer role where I can do more of that.

---

## 🛠 What I've Actually Built

**🛡 [AgentPrahari](https://github.com/Httpslakshya/AgentPrahari)** — a pip-installable guardrail layer for AI agents/LLMs, built so integrating real safety checks doesn't mean choosing between "too basic" and "too complex."
Regex + LLM-as-judge detection, a one-line `shield.wrap()` API, FastAPI/Flask middleware, and native LangChain/CrewAI hooks.
**Live on [PyPI](https://pypi.org/project/agentprahari/)** as `agentprahari` — `pip install` gets you a working safety layer, not a demo.

**🏺 [Kiln Studio](https://github.com/Httpslakshya/KILN-Studio)** — a single platform for AI content work instead of stitching together separate RAG, fact-checking, and drafting tools.
PDF RAG (Qdrant) + live multi-domain fact-checking + a 4-agent pipeline (Researcher → Verifier → Writer → Editor) that turns one verified draft into an article, LinkedIn post, carousel, and reel script — guardrails built in via the AgentPrahari console.
Verified working end-to-end: one input, five outputs.

**🎙 [Cosmo](https://github.com/Httpslakshya/COSMO-AI)** — a voice-activated desktop assistant for Windows built around a real multi-agent loop instead of a single scripted flow.
Supervisor → Planner → Executor → Critic/Verifier via LangGraph, hybrid-search memory (Chroma Cloud), sub-250ms Whisper STT via Groq.
Verified working: memory recall, direct tool execution, and multi-step planning with self-verification.
📍 [Meet Cosmo on my portfolio](https://lakshyadharkar.netlify.app/)

---

## ⚙️ How I Build

| Layer | What I reach for |
|---|---|
| **Reasoning & Agents** | Python, LangGraph, Groq, Gemini, OpenRouter |
| **Memory & Retrieval** | Chroma, Qdrant — hybrid dense+sparse search |
| **Serving** | FastAPI, Flask, Node.js, Java |
| **Interfaces** | React, JavaScript, HTML/CSS |
| **Data** | MySQL, MongoDB |
| **Shipping** | Docker, Git/GitHub, Linux |
| **Design** | Figma, Canva |

---

## 🎯 Where This Is Headed

- Sharpening DSA and system design — the stuff that scales beyond a weekend build
- Contributing to open-source agent tooling
- Finding a Python Developer / AI Engineer role where "break it and understand it" is the job, not just the hobby

---

<div align="center">

<a href="https://lakshyadharkar.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-ea8c2a?style=flat-square&logo=googlechrome&logoColor=white" /></a>
<a href="https://linkedin.com/in/lakshya-dharkar"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://dev.to/lakshyadharkar_404"><img src="https://img.shields.io/badge/Dev.to-0A0A0A?style=flat-square&logo=devdotto&logoColor=white" /></a>
<a href="https://leetcode.com/LakshyaDharkar"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" /></a>
<a href="https://huggingface.co/Httpslakshya"><img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" /></a>
<a href="https://pypi.org/project/agentprahari/"><img src="https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi&logoColor=white" /></a>

</div>

<div align="center">

*build it. break it. understand it.*

</div>
