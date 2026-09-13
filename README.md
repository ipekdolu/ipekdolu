# Hi, I'm Ipek 👋

I'm an applied AI engineer with an M.Sc. background in **Natural Language Processing** (University of Trier) and a B.Sc. in Computer Science & Engineering (Sabancı University). I build AI-powered products end-to-end — from LLM systems and retrieval pipelines to the product decisions that shape how they actually solve a problem for the people using them.

I like sitting at the intersection of engineering and product: understanding what a system needs to do, why, and for whom — then building it well.

---

## What I'm working on

- **LLM-powered applications** — building with the Claude API: structured outputs, function calling, and prompt engineering for production use cases
- **RAG systems** — retrieval pipelines, vector databases, embedding models, and multilingual retrieval
- **Agentic AI** — expanding into agent orchestration and tool-use pipelines (LangGraph)
- **Full-stack AI products** — designing and shipping complete user-facing applications, not just backend pipelines
- **Applied NLP** — transformer-based models for classification, extraction, and generation, grounded in research-level evaluation practices

---

## Background

- 🎓 M.Sc. Natural Language Processing — University of Trier, Germany
- 🎓 B.Sc. Computer Science & Engineering — Sabancı University
- Portfolio of deployed AI products spanning LLM applications, RAG systems, and full-stack development

---

## Tech stack

**Languages:** Python · TypeScript · JavaScript · SQL

**LLM & Agentic AI:** Claude API · Prompt engineering · Structured outputs · RAG · LangGraph · ChromaDB · Neo4j · sentence-transformers

**ML / NLP:** PyTorch · Hugging Face Transformers · scikit-learn · spaCy · NLTK · pandas

**Frontend:** React · Next.js · Tailwind CSS · Vite

**Backend & Data:** FastAPI · Supabase (PostgreSQL) · Drizzle ORM · REST APIs · Power BI

**Testing & Analysis:** Vitest · Excel

**DevOps & Deployment:** Vercel · Render · Git/GitHub · Langfuse

---

## 📌 Projects

### [CareerAI](https://careerai-delta.vercel.app) &nbsp;·&nbsp; [Repo](https://github.com/ipekdolu/careerai)
- FastAPI backend on the Anthropic Claude SDK with task-specific tool lists
- Claude-generated diff-based rewriting with PDF export via ReportLab
- React + Vite frontend with Supabase Google OAuth and a session-based data model
- Deployed full-stack — Vercel (frontend), Render (backend)

### MythCheck &nbsp;·&nbsp; [Repo](https://github.com/ipekdolu/mythcheck)
- Neo4j AuraDB knowledge graph + ChromaDB vector store, built from Wikipedia mythology sources (Greek, Norse, Egyptian)
- Claude API structured extraction (strict tool schema), with entity resolution via alias merging and cross-tradition equivalence detection using embedding similarity
- Claim-routing pipeline — graph traversal for relational claims, vector search + LLM-as-judge for descriptive claims, every verdict citing an actually-retrieved chunk
- Evaluation harness using synthetic claim corruption for gold-label generation — 1.00 precision across all categories (n=50 synthetic, n=15 real hallucinations)
- Langfuse observability end-to-end, FastAPI `/verify` endpoint, Streamlit UI

### [Knack](https://knackde-azure.vercel.app) &nbsp;·&nbsp; [Repo](#)
- Next.js, TypeScript, and React frontend with Supabase and Drizzle ORM
- LLM-based grading pipeline via the Anthropic API, with complexity-based model routing
- Web Speech API integration for spoken exercises
- Spaced repetition system with mastery-state logic

---

> More projects coming soon.
