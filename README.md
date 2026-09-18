<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=280&color=0:0D1117,50:00D9FF,100:00FFB2&text=Harsh%20Raj&fontColor=ffffff&fontSize=65&animation=fadeIn&fontAlignY=40"/>

# Harsh Raj

<img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=700&size=25&pause=1000&color=00D9FF&center=true&vCenter=true&width=900&lines=Software+Engineer;Agentic+AI+%26+LLM+Systems+Builder;Distributed+Systems+Engineer;Full-Stack+Developer;Building+Real+Systems%2C+Not+Demos"/>

### Final Year Computer Science Student @ SRM University AP
### CGPA: 8.93/10.0

<br>

<a href="mailto:hraj15709@gmail.com">
<img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://hxrshraj.github.io">
<img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=vercel&logoColor=00FFB2"/>
</a>

<a href="https://www.linkedin.com/in/harsh-raj-7a26ab314">
<img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00D9FF"/>
</a>

</div>

---

## About Me

I build real, working systems end to end — distributed systems, agentic AI pipelines, low-level performance-critical code, and full-stack products — and I hold every one of them to the same standard: measure whether it actually works before calling it done.

I don't build demos. Every project below is independently designed, built, tested, and (where it makes sense) deployed live, with real benchmarks, real test coverage, and real bugs found and fixed along the way — not assumed to be correct.

### Interests

- Agentic AI Systems & LLM Evaluation
- Distributed Systems & Event Streaming
- Low-Latency Systems & Performance Engineering
- Backend Development & System Design
- MLOps & Cloud Infrastructure
- DevSecOps & Test Automation
- Computer Vision & Machine Learning

Outside technology: cricket, guitar, reading, geopolitics, and fort exploration.

---

## Featured Projects

### 🤖 Sarathi — AI Software-Engineering Copilot
A genuine multi-agent system (Planner, Retriever, Coder, Tester, Debugger, Security, Reviewer) with real tool-calling, hybrid code retrieval (dense + lexical + symbol search via Reciprocal Rank Fusion), and an evaluation harness combining deterministic gates with an LLM judge — because AI output that sounds right isn't the same as AI output that is right.
**Stack:** Python, FastAPI, React (Next.js), TypeScript, LLM APIs, pgvector
**Live:** https://sarathi-web-pumd.vercel.app | **Repo:** https://github.com/HxrshRaj/Sarathi

### 📡 Pravaha — Real-Time Event Streaming & Intelligence Platform
A production-shaped streaming platform on genuine Apache Kafka — partitioning, consumer groups, watermarks, DLQ with retry/replay — verified end to end against 49,000+ real events. Extended with a Spark/Scala batch layer (hourly rollups + cross-event-type correlation) on top of the same real-time data, plus an AI investigator with evidence cross-checking to guard against hallucinated conclusions.
**Stack:** Python, Apache Kafka, Scala, Apache Spark, PostgreSQL, Next.js
**Repo:** https://github.com/HxrshRaj/Pravaha

### 🔍 Nirikshan — AI-Powered Monitoring & Incident Response Platform
A real SRE-style platform: service-health dashboards, statistical anomaly detection (z-score, EWMA, Isolation Forest), and an AI investigator whose hallucination rate is measured and gated in CI — not trusted by default. Validated with 83+ automated tests including Playwright E2E coverage.
**Stack:** Python, FastAPI, React, PostgreSQL, Redis Streams
**Live:** https://nirikshan-web.onrender.com | **Repo:** https://github.com/HxrshRaj/Nirikshan

### 🏗️ Meghdoot — Internal Developer Platform (Kubernetes Deployment Engine)
A genuinely multi-tiered, distributed system: a FastAPI control plane orchestrating a separate Kubernetes-deploying data plane, with rolling, blue-green, and canary deployment strategies, validated across 128 tests and real load testing.
**Stack:** Python, FastAPI, Kubernetes, Redis, PostgreSQL, Docker
**Repo:** https://github.com/HxrshRaj/Meghdoot

### 📦 OrderFlow — Order & Inventory Management
Two genuinely independent Java/Spring Boot microservices (separate databases) with a React frontend. Solved a real concurrency problem (stock overselling) with atomic conditional updates — verified with 40 threads racing for the last unit: exactly 1 succeeds.
**Stack:** Java 21, Spring Boot, React, PostgreSQL, JUnit, Mockito, Testcontainers
**Live:** https://orderflow-web.onrender.com | **Repo:** https://github.com/HxrshRaj/OrderFlow

### ⚡ FastBook — Low-Latency Limit Order Book Engine
A limit order book and matching engine in C++17 with lock-free SPSC concurrency. Profiled with `perf`, found a real bottleneck, and validated a 12.8% latency improvement through rigorous A/B testing — confirmed against 569,265 test assertions.
**Stack:** C++17, Linux
**Live:** https://fastbook-8uym.onrender.com | **Repo:** https://github.com/HxrshRaj/FastBook

### 🎚️ Swara — Real-Time Audio DSP Processor
A real-time DSP engine in C++: a genuine IIR Butterworth filter, an FFT-based spectral noise gate (KissFFT), and a circular-buffer delay line — independently verified against known frequency-domain behavior via a separate library, with real measured latency (mean/p50/p95/p99) across buffer sizes.
**Stack:** C++, React, FastAPI
**Live:** https://swara-7lye.onrender.com | **Repo:** https://github.com/HxrshRaj/Swara

### 🌊 Dhara — Thread-Safe Ring Buffer
A thread-safe circular ring buffer in pure C11 (mutex + condition variables, no busy-waiting) — conceptually similar to a NIC's hardware RX/TX descriptor ring. Stress-tested with 4 producers and 2 consumers across 100,000 packets: 0 corrupted, 0 duplicated, 0 lost across 3 runs, confirmed with ThreadSanitizer showing zero data races.
**Stack:** C11, pthreads
**Repo:** https://github.com/HxrshRaj/dhara-

### 🔬 Parikshan — Equipment Control Simulator & Test Automation Framework
A C#/.NET simulator of semiconductor equipment as an explicit state machine with two independent fault-injection sources, exposed via ASP.NET Core. Built a real test automation framework: 175+ xUnit tests, 97.9% line / 89.4% branch coverage, and 3 real bugs found and fixed with documented root cause.
**Stack:** C#, .NET, ASP.NET Core, xUnit
**Repo:** https://github.com/HxrshRaj/Parikshan

### 🔗 Mudra — Web3 Wallet Authentication & On-Chain Balance Checker
A Sign-In with Ethereum (SIWE) flow with real backend nonce generation and wallet-signature verification, plus live on-chain balance queries against a Polygon testnet via MetaMask.
**Stack:** React, Node.js/Express, ethers.js
**Repo:** https://github.com/HxrshRaj/Mudra

### 🧠 DocuMind — Agentic AI & RAG Data Science Assistant
A RAG pipeline built from scratch — document chunking, embeddings, and vector search via FAISS and LangChain — structured as a 5-stage pipeline to ground LLM responses in real source material rather than trusting an LLM API directly.
**Stack:** Python, LangChain, FAISS, Streamlit
**Live:** https://sj2ihzd75sacteozr264zz.streamlit.app | **Repo:** https://github.com/HxrshRaj/Documind-

### 🛡️ SettleGuard — Merchant Settlement Reconciliation & Triage
A backend service detecting 5 distinct real discrepancy types across two large datasets via SQL joins and aggregations, with an AI-generated triage layer and a dashboard for non-technical stakeholders.
**Stack:** Python, Flask, SQL
**Live:** https://settleguard.onrender.com | **Repo:** https://github.com/HxrshRaj/SettleGuard

### 👨‍💻 CodeArena — Technical Assessment Platform
An interactive coding platform embedding a live code editor with real-time execution results streamed over WebSockets, running arbitrary user code in a hardened, sandboxed environment.
**Stack:** React (Next.js), TypeScript, WebSockets, Docker
**Repo:** https://github.com/HxrshRaj/CodeArena

### ✈️ AeroRoute IQ — AI Analytics & Optimization Platform
An aviation analytics platform applying machine learning (Scikit-learn, XGBoost) for delay prediction alongside real operations research (Google OR-Tools linear programming) for schedule optimization.
**Stack:** Python, Scikit-learn, Pandas, Google OR-Tools, Streamlit
**Live:** https://aeroroute-iq-xfe76fhkz9apk9l6qpv8sw.streamlit.app | **Repo:** https://github.com/HxrshRaj/AeroRoute-IQ

### 📊 InsightFlow AI — AI Analytics & Predictive Modeling Platform
A modular data pipeline (Pandas, NumPy, Scikit-learn, XGBoost) for automated data processing, feature engineering, and predictive analytics with automated business-insight reporting.
**Stack:** Python, Scikit-learn, XGBoost, Streamlit
**Live:** https://insightflow-ai-stazd6bjfvnu5uyjlvqbmv.streamlit.app | **Repo:** https://github.com/HxrshRaj/InsightFlow-AI

### 🎓 MicroLearn — Gamified Microlearning Platform
A full-stack application (React, Node.js, Express) with a 4-endpoint REST API, empirically load-tested to 3,100+ requests/sec at sub-6ms average latency.
**Stack:** React, Node.js, Express
**Live:** https://microlearn-ivzi.onrender.com | **Repo:** https://github.com/HxrshRaj/microlearn

---

## Research & Publications

📄 **Single-Agent vs. Multi-Agent Architectures for Automated Data Analysis: A Comparative Review of Accuracy, Reliability, and Computational Efficiency** — Zenodo, 2026
[https://doi.org/10.5281/zenodo.22665662](https://doi.org/10.5281/zenodo.22665662)

📄 **Design and Evaluation of Scalable Distributed Web Applications: A Comparative Study of Monolithic, Modular Monolith, and Microservices Architectures** — Zenodo, 2026
[https://doi.org/10.5281/zenodo.22665591](https://doi.org/10.5281/zenodo.22665591)

---

## Technical Arsenal

### Programming Languages

<p>
<img src="https://skillicons.dev/icons?i=java,python,cpp,c,go,typescript,javascript,csharp" />
</p>

### AI / ML & Agentic Systems

<p>
<img src="https://skillicons.dev/icons?i=tensorflow,pytorch" />
</p>

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/RAG-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Agentic_AI-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white"/>

### Backend & Distributed Systems

<p>
<img src="https://skillicons.dev/icons?i=spring,fastapi,nodejs,express,dotnet" />
</p>

<img src="https://img.shields.io/badge/Apache_Kafka-000000?style=for-the-badge&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>

### Frontend

<p>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind" />
</p>

### Cloud, DevOps & Infrastructure

<p>
<img src="https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,githubactions,git" />
</p>

### Databases

<p>
<img src="https://skillicons.dev/icons?i=postgresql,mongodb,redis,mysql" />
</p>

---

## Certifications & Achievements

🏆 Oracle Certified Professional — Java SE 17 Developer

🏆 IBM RAG and Agentic AI Professional Certificate

🏆 Deep Learning Specialization — DeepLearning.AI

🏆 Selected for ABB EngineeredX 2.0 — advanced to the interview round with DocuMind

🏆 Idea published for the micro1 Frontier Engineering Challenge 2026

🏆 200+ Data Structures & Algorithms Problems Solved

---

## Areas of Expertise

🤖 Agentic AI & LLM Evaluation

📡 Distributed Systems & Event Streaming

⚡ Low-Latency Systems & Performance Engineering

⚙️ Software Engineering & System Design

🚀 Backend Development & Microservices

🌐 Full-Stack Development

🔒 Test Automation & DevSecOps

👁️ Computer Vision

---

## Current Focus

- Building agentic AI systems with real, measurable evaluation
- Deepening formal methods and compiler-level systems work
- Engineering distributed, event-driven backends at scale
- Closing skill gaps with real, deployed projects — not just resume lines

---

## GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=HxrshRaj&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117"/>

<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=HxrshRaj&theme=tokyonight&hide_border=true&background=0D1117"/>

</div>

<br>

<div align="center">

<img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=HxrshRaj&theme=tokyo-night&hide_border=true"/>

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=HxrshRaj&theme=tokyonight&no-frame=true&row=1&column=7"/>

</div>

---

## Beyond Code

🏏 Cricket · 🎸 Guitar · 📚 Reading · 🏰 Fort Exploration · 🌍 Geopolitics

---

<div align="center">

### Build it. Break it yourself first. Then ship it.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:0D1117,50:00D9FF,100:00FFB2"/>

</div>
