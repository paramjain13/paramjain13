<h1 align="center">PARAM JAIN</h1>

<h3 align="center">AI / ML Engineer · Agentic Systems</h3>

<p align="center">
  <a href="https://paramjain.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Live-4FD1C5?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/paramsachinjain/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="RESUME-LINK"><img src="https://img.shields.io/badge/Resume-View-E8A33D?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Resume"></a>
</p>

<p align="center"><i>I build LLM agents that plan, execute, and correct themselves —<br>and the evaluation harnesses that prove whether they actually work.</i></p>

---

## About

I work on agentic systems: LLM agents that decompose tasks, call tools, and repair their own
failures. Most of my attention goes to the unglamorous half of that problem — **evaluation**.
Measuring which components of an agent graph actually earn their latency and token cost, and
which are decoration.

Before that, production ML (a fraud-detection service on AWS) and systems work in Rust. The
through-line is a preference for things you can measure over things that merely demo well.

**M.S. Computer Science (AI/ML)** — Northeastern University, Boston · *Graduating December 2027*
**B.Tech Computer Science** — Medi-Caps University, Indore

---

## Featured Work

### 01 — [nl2sql-agent](https://github.com/paramjain13/nl2sql-agent)
> **Self-correcting text-to-SQL on LangGraph**

An agent that generates SQL, executes it, and repairs itself from execution errors.
Benchmarked on **BIRD-SQL Mini-Dev (500 questions)**: **64.4% execution accuracy at 1.0 LLM
calls per query** — where leading systems reach ~82% through multi-step pipelines costing many
calls each. Schema-linking node on a cheap model, driver-level read-only SQL guard, correction
loop bounded at 3 attempts.

Also ships a root-cause classifier over all 178 failures: 32.6% projection errors, 25.3% table
selection. Knowing *where* accuracy leaks is what makes the ablation worth running.

**Tools:** LangGraph · Claude API · sqlglot · SQLite · Python

<a href="https://github.com/paramjain13/nl2sql-agent"><img src="https://img.shields.io/badge/View_Code-181717?style=flat-square&logo=github" alt="View Code"></a>

---

### 02 — [ai-content-analyzer-pro](https://github.com/paramjain13/ai-content-analyzer-pro)
> **Multi-document RAG analysis**

Retrieval pipeline over a vector store for analyzing document collections, with a
model-agnostic backend running against both GPT-4 and Gemini.

**Tools:** Python · RAG · Vector Search · GPT-4 · Gemini

<a href="https://github.com/paramjain13/ai-content-analyzer-pro"><img src="https://img.shields.io/badge/View_Code-181717?style=flat-square&logo=github" alt="View Code"></a>

---

### 03 — ELARA
> **Multi-agent retrieval and reasoning**

Multi-agent RAG system orchestrating retrieval, reasoning, and synthesis across a vector store,
with scheduled ingestion pipelines.

**Tools:** LangGraph · GPT-4 · Pinecone · Airflow

<a href="ELARA-REPO-LINK"><img src="https://img.shields.io/badge/View_Code-181717?style=flat-square&logo=github" alt="View Code"></a>

---

## Experience

| Role | Company | Period | Highlights |
| --- | --- | --- | --- |
| **ML Engineering Intern** | Genesis Technologies | Jul — Dec 2024 | End-to-end fraud-detection pipeline over 15+ engineered features across 30K+ users, lifting **F1 from 0.71 to 0.89**. Shipped as a containerized AWS microservice (Lambda, S3, EC2) behind Flask REST APIs — **1,000+ requests/day at 97% uptime**, sub-500ms latency. |
| **AI Engineering Intern** | DevQAExpert | Jan — May 2024 | scikit-learn classifier flagging defect-prone test scenarios across **15,000+ cases**, improving defect prediction by **42%**. Integrated into CI/CD, cutting manual regression effort by **60%**. |

---

## Toolkit

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
</p>

---

## Publications

- **Enhancing Human-Robot Interaction through Advanced NLP** — *International Journal of Scientific Research in Engineering and Management (IJSREM)*, 2024
  <br><sub>BERT + GPT-3 for real-time speech recognition and emotion detection — 86.5% interaction accuracy at sub-500ms response latency.</sub>

---

<p align="center">
  <b>Open to SDE and ML/AI internship and co-op roles</b><br>
  US work authorized · No sponsorship required<br>
  <a href="mailto:paramsachinjain@gmail.com">paramsachinjain@gmail.com</a> · Boston, MA
</p>
