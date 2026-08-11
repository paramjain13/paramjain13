# Param Jain

**MS Computer Science (AI/ML) @ Northeastern University · Boston, MA · Graduating December 2027**

I build agentic AI systems and the infrastructure underneath them LLM agents that plan
and self-correct, retrieval pipelines over vector stores, and the evaluation harnesses
that prove whether any of it actually works.

Right now I'm focused on **agent evaluation**: measuring which components of an agent
graph earn their latency and token cost, and which are just decoration.

[LinkedIn](https://www.linkedin.com/in/paramsachinjain/) · [Portfolio](https://paramjain13.https://paramjain.vercel.app) · [Email](mailto:jain.param@northeastern.edu)

---

## Featured Work

### [nl2sql-agent](https://github.com/paramjain13/nl2sql-agent)
`LangGraph` · `Claude API` · `sqlglot` · `SQLite`

A text-to-SQL agent that generates and **self-corrects** SQL over relational databases,
benchmarked on **BIRD-SQL Mini-Dev (500 examples)**. The goal isn't SOTA — it's strong
accuracy at a fraction of the LLM calls, with an ablation study isolating which agent
nodes actually move the number.

**64.4% execution accuracy at 1.0 LLM calls/query** as the single-call baseline.
Schema-linking node, execution validator, and a read-only SQL guard.

### [ai-content-analyzer-pro](https://github.com/paramjain13/ai-content-analyzer-pro)
`Python` · `RAG` · `GPT-4` · `Gemini`

Multi-document RAG pipeline for content analysis — retrieval across a vector store with
a model-agnostic backend supporting both GPT-4 and Gemini.

### [portfolio](https://github.com/paramjain13/portfolio)
`HTML` · `CSS` · `JS`

Personal site and project index.

---

## Toolkit

**Languages** — Python · Rust · SQL · JavaScript

**AI / ML** — LangGraph · RAG · Vector Search (Pinecone, Qdrant) · PyTorch · scikit-learn · Agent Evaluation

**Backend** — Axum · Tokio · Flask · FastAPI

**Infra** — AWS (Lambda, ECS, RDS, S3, SQS, EventBridge) · Docker · Terraform / OpenTofu · CI/CD

---

## Background

- **ML Engineering Intern** — Genesis Technologies · fraud-detection pipeline on AWS
- **Software Engineering Intern** — DevQAExpert · CI/CD automation, ML classifier work
- **2 peer-reviewed publications** — GIJET, IJSREM

Open to **SDE and ML/AI internship and co-op roles**. US work authorized, no sponsorship required.
