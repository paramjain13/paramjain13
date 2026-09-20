<div align="center">

# Param Jain

### M.S. CS @ Northeastern · AI / ML & Data Engineering

*I build LLM agents and data systems that you can measure —*
*not just demo.*

[![Portfolio](https://img.shields.io/badge/Portfolio-paramjain.vercel.app-555555?style=flat-square&logo=googlechrome&logoColor=white)](https://paramjain.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-paramsachinjain-555555?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/paramsachinjain)
[![Email](https://img.shields.io/badge/Email-jain.param%40northeastern.edu-555555?style=flat-square&logo=gmail&logoColor=white)](mailto:jain.param@northeastern.edu)
[![Location](https://img.shields.io/badge/Boston%2C%20MA-F--1%20%C2%B7%20CPT%20Authorized-555555?style=flat-square&logo=googlemaps&logoColor=white)]()

</div>

---

## About

I'm a data science graduate student who builds LLM agents that plan, execute, and correct
themselves — plus the evaluation harnesses that prove whether they actually work. Before grad
school I shipped production ML (an identity-verification service on AWS that went from
**30% → 95% accuracy across 30K+ monthly users**) and engineered data pipelines end to end.

The through-line: a preference for things you can measure over things that merely demo well.

**M.S. Computer Science** — Northeastern University, Boston · *Expected Dec 2027*
**B.Tech Computer Science** — Medi-Caps University, Indore

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=paramjain13&show_icons=true&hide_border=true&title_color=555&icon_color=888&text_color=666&bg_color=00000000" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=paramjain13&layout=compact&hide_border=true&title_color=555&text_color=666&bg_color=00000000" />

<img src="https://streak-stats.demolab.com?user=paramjain13&hide_border=true&background=00000000&ring=888888&fire=888888&currStreakLabel=666666&sideLabels=666666&currStreakNum=444444&sideNums=444444&dates=999999" />

</div>

---

## Featured Work

**01 — [NL2SQL Agent](https://github.com/paramjain13/nl2sql-agent)** · *Self-correcting natural-language-to-SQL*
Multi-step LangGraph + Claude API agent that generates SQL, executes it, and repairs its own
failed queries — **64% execution accuracy across 500 BIRD-SQL benchmark questions** on a
1M+ row database. Static verifier using sqlglot AST parsing and foreign-key graph traversal
catches confident-but-wrong queries pre-execution; schema linking + cost-aware model tiering
cut inference cost at steady accuracy.
`LangGraph` `Claude API` `sqlglot` `SQL` `Python`

**02 — Multi-Agent Research Assistant** · *Measured multi-agent orchestration*
Three specialized LangGraph + GPT-4 agents over vector search, SQL, and live web retrieval —
**90%+ retrieval accuracy**, with every agent's output scored independently. Airflow ingestion
of 500+ documents into Pinecone across three chunking strategies, and an evaluation harness
tracking per-agent accuracy, latency, and routing reliability on every change.
`LangGraph` `GPT-4` `Pinecone` `Airflow` `RAG`

**03 — Fleet Telemetry Platform** · *Streaming pipelines with statistical monitoring*
Kafka + PostgreSQL pipeline on Linux ingesting telemetry from **1,000+ simulated vehicles at
10,000+ events/sec**, with completeness and ordering validation before storage. 3-sigma anomaly
detection over the live stream, plus Grafana dashboards over latency, throughput, and error-rate
trends — every metric definition documented.
`Kafka` `PostgreSQL` `Grafana` `Linux` `Anomaly Detection`

**04 — SkillMatchAI** · *LLM-driven semantic job matching*
React / Next.js / TypeScript front end on a Python backend surfacing LLM-driven matches across
**10K+ records** with confidence scores. OpenAI embeddings + Pinecone semantic search reaching
**85%+ relevance**; Selenium scrapers and Airflow DAGs keep sources fresh on a fixed schedule.
`React` `Next.js` `TypeScript` `OpenAI` `Pinecone` `Airflow`

---

## Experience

| Role | Company | Period | Impact |
|---|---|---|---|
| **Software Engineer** | DevQAExpert | May 2024 – Aug 2025 | Python + scikit-learn framework scoring a regression corpus by failure risk — defect prediction **+42%** at the same runtime across 12 release cycles. CI/CD automation via Jenkins & GitHub Actions cut manual effort **−60%**; traced **40+ defects per release** to root cause before production. |
| **Machine Learning Engineer** | Genesis Technologies | Jan 2023 – Dec 2023 | End-to-end identity-verification service (TensorFlow, scikit-learn) — accuracy **30% → 95%** across **30K+ monthly users**. Diagnosed input quality as the real failure driver, engineered 15+ features; deployed containerized on AWS (Lambda, S3, EC2) at **97% uptime, 1,000+ daily requests**; F1 **0.71 → 0.89** via systematic error analysis. |
| **Data Analyst Intern** | Agrawal's 420 | Jan 2022 – Jun 2022 | Consolidated sales, inventory & campaign data from PostgreSQL with SQL + Python — report runtime **−45%**. Replaced manual spreadsheet reporting with scheduled pipelines (**−6 hrs/week**), built data-quality checks and a job-status tracker that cut troubleshooting **2 hrs → 25 min**. |

---

## Toolkit

**AI / Agents** — LangGraph · LangChain · RAG · Multi-Agent Systems · Claude API · OpenAI API · GPT-4 · Prompt Engineering · Pinecone · Semantic Search · sqlglot
**ML / Data Science** — PyTorch · TensorFlow · scikit-learn · Pandas · NumPy · Feature Engineering · Model Evaluation · Anomaly Detection · Statistical Analysis · EDA
**Engineering** — Python · SQL · C++ · Rust · TypeScript · PostgreSQL · MySQL · Kafka · Airflow · ETL · Grafana · FastAPI · Flask · React · Next.js · REST APIs
**Infra** — AWS (S3, Lambda, EC2) · Docker · CI/CD · GitHub Actions · Jenkins · Linux · Git · Observability

---

## Publications & Certifications

**Enhancing Human-Robot Interaction through Advanced NLP** — *IJSREM, 2024*
Fine-tuned BERT + GPT-3 for intent recognition in collaborative robotics — **86.5% classification
accuracy at sub-500ms latency**, evaluated systematically against strong baselines.

**AWS Academy** — Cloud Foundations · Data Engineering · Generative AI Foundations (2026)

---

<div align="center">

**Open to ML/AI, Data Engineering & SDE internships and co-ops**
F-1 student · CPT authorized — no employer sponsorship required

[paramjain.vercel.app](https://paramjain.vercel.app/) · [linkedin.com/in/paramsachinjain](https://linkedin.com/in/paramsachinjain) · jain.param@northeastern.edu

</div>
