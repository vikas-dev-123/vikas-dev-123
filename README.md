<div align="center">

# Hi, I'm Vikas Dev Pandey 👋

### AI & Automation-Focused Full-Stack Developer

Building production-grade web apps, AI agent systems, and multi-agent automation with React, Node.js, FastAPI, LangChain/LangGraph & LLM orchestration

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vikas-dev-pandey-06869a287/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vikas-dev-123)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/pandeyvikasdev/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vikaspandey0234@gmail.com)

</div>

---

## 🚀 About Me

- 🎓 2026 B.Tech CSE graduate — **AI/ML & Cloud Computing**, United University, Prayagraj (CGPA: 8.6/10)
- 💼 Freelance Full Stack Developer (MERN) — building and shipping client applications end-to-end since Jan 2024
- 🤖 Deep focus on **LLM orchestration, multi-agent systems, RAG pipelines, and voice AI** (LangChain, LangGraph, FAISS, tool-calling)
- 🏗️ I own the full lifecycle: database design → backend → frontend → deployment
- 🏆 IBM Day Hackathon Winner · Meta PyTorch OpenEnv Hackathon Finalist (Top 2.6% of 31,000+ teams)
- 📫 Reach me at **vikaspandey0234@gmail.com**

---

## 🛠️ Tech Stack

**Languages**
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**AI / LLM**
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/-OpenAI%2FGemini-412991?style=flat-square&logo=openai&logoColor=white)
![FAISS](https://img.shields.io/badge/-FAISS%20RAG-4B8BBE?style=flat-square)

**Voice / Telephony**
![Twilio](https://img.shields.io/badge/-Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)
![Deepgram](https://img.shields.io/badge/-Deepgram-13EF93?style=flat-square)
![ElevenLabs](https://img.shields.io/badge/-ElevenLabs-000000?style=flat-square)

**Security / Tooling**
![OWASP ZAP](https://img.shields.io/badge/-OWASP%20ZAP-000000?style=flat-square&logo=owasp&logoColor=white)
![Nmap](https://img.shields.io/badge/-Nmap-4682B4?style=flat-square)

**Frontend**
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/-Express.js-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)

**Databases & Infra**
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS%20EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

---

## 🌟 Featured Projects

### 🛡️ [SentinelAgent — AI Multi-Agent Penetration Testing Engine](https://github.com/vikas-dev-123/sentinel-agent)
`LangGraph` `Claude` `OWASP ZAP` `Nmap` `FastAPI` `Gradio` · [Live Demo ↗](https://sentinel-agent-43sv.onrender.com/)
- 6 specialized LangGraph agents run in parallel, each driving a real security tool (OWASP ZAP, Nmap) — the LLM only interprets and confirms tool output, never fabricates findings
- Dedicated Findings Confirmation agent filters false positives and assigns severity — verified on a live site where it correctly discarded SPA catch-all false positives a naive scanner flagged as HIGH
- Pluggable LLM reasoning backends (Claude, Hugging Face, Ollama, offline heuristic) with automatic fallback and a built-in scope guard that refuses unauthorized targets
- Shipped CLI, REST API, and web UI interfaces with Markdown/PDF reporting, Docker deployment, and a fully offline demo mode

### 📞 [RingOrder — AI Voice Agent for Restaurant Phone Orders](https://github.com/vikas-dev-123/FoodCareAi)
`Node.js` `Claude` `Twilio` `Deepgram` `ElevenLabs` `SQLite`
- End-to-end AI voice agent that answers real restaurant phone calls and takes orders in Hindi/English/Hinglish, live-tested on real inbound Twilio calls
- Real-time pipeline: Twilio Media Streams → Deepgram streaming STT → Claude agentic tool-calling loop → ElevenLabs streaming TTS
- Multi-tenant SQLite backend with automatic per-number restaurant routing, plus a live dashboard (analytics, call logs/recordings, menu CRUD)
- Production-hardening: retry + fallback speech on LLM errors, business-hours enforcement, and auto-hangup after order confirmation

### 🧠 [GenAI Engine — Self-Hosted AI Agent Platform](https://github.com/vikas-dev-123/genai-engine)
`FastAPI` `LangChain` `Gemini` `FAISS` `PostgreSQL` `Redis` `React` `Docker`
- Production-ready self-hosted AI assistant with LangChain agent tool-calling and multi-turn SSE-streamed chat
- RAG pipeline using FAISS vector search over per-user document indexes (PDF/DOCX/TXT)
- Multi-service architecture (FastAPI + React + PostgreSQL + Redis + Nginx) orchestrated via Docker Compose
- Sandboxed agent tools (web search, file I/O, whitelisted shell access) with per-user isolation & Redis rate limiting

### 🏢 [Canvaas — Multi-Tenant SaaS Platform](https://github.com/vikas-dev-123/canvaas)
`Next.js` `Prisma/MySQL` `Clerk` `Stripe` `Tailwind`
- Multi-tenant backend supporting 100+ users with isolated agency/sub-account workflows & RBAC
- CRM, sales pipeline, and funnel-builder modules with real-time analytics dashboards
- Clerk auth + Stripe subscription billing, deployed across 35+ production releases on Vercel
- Cut manual operations by 40%+ through API-driven automation

### 📄 [OfferBoost (ResumeForge AI) — AI Resume Builder SaaS](https://github.com/vikas-dev-123/OfferBoost)
`Next.js` `TypeScript` `Prisma/PostgreSQL` `NextAuth` `Gemini/OpenRouter`
- JD-analysis pipeline extracting ATS keywords, technologies, and role type from job descriptions
- Pluggable AI provider architecture (Gemini, OpenRouter, Ollama) with deterministic fallback
- Custom ATS scoring engine with multi-mode resume rewriting (strict/enhanced/aggressive/creative)
- PDF/DOCX export, version history, shareable links, and cover letter generation

---

## 🏆 Achievements

| 🏅 | Achievement |
|---|---|
| 🥇 | **Winner** — IBM Day Hackathon (AI/ML Track) |
| 🎯 | **Finalist** — Meta PyTorch OpenEnv Hackathon (Top ~2.6% · 800/31,000+ teams, India) |

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=vikas-dev-123&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vikas-dev-123&layout=compact&theme=tokyonight&hide_border=true)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=vikas-dev-123&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

### 💬 Let's Connect

I'm always open to collaborating on AI-powered products, agentic systems, full-stack builds, or freelance work.

📧 **vikaspandey0234@gmail.com** · 📱 **+91 9026358221**

*"Building intelligent systems that work in the real world."*

</div>
