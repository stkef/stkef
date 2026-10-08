# Hi, I'm Pradeep Kase 👋

**SMM / Tech at [Citta AI](#-experience) · AI agents, RAG & retrieval systems · Hyderabad, India**

I build AI agents and LLM applications end to end: multi-step LLM workflows, retrieval-augmented
generation, search and matching systems, and the FastAPI services, tests and evaluation that take them
to production. I like measuring every decision instead of guessing.

🎯 Looking for **AI Engineer** or **Forward Deployed Engineer** roles: building LLM and agent systems
that work reliably on real customer data.

---

## 🔭 Featured projects

| Project | What it is | Highlights |
|---|---|---|
| [**MatchLens**](https://github.com/stkef/matchlens) | Finds the same product across marketplace listings from titles + photos (Shopee, Indonesian/English) | Built as a measured experiment ladder: BM25 → photo hashes → multilingual text & image embeddings (FAISS / Qdrant) → learned fusion → fine-tuned retriever and cross-encoder reranker with hard-negative mining. **F1 0.46 → 0.80 on a held-out test split**, every gain bootstrap-tested |
| [**Multimodal RAG Service**](https://github.com/stkef/Multi-Modal-Rag-System) | Ask questions about 25+ file formats in any language, incl. Telugu, Hindi and code-mixed text | Found why questions in romanised Telugu came back "not found" (an English-only reranker scored them near zero) and fixed it with multilingual hybrid search. Every answer points to its source, and a guardrail removes any sentence the documents don't support before the user sees it. Built to run for real teams: per-customer API keys and spending limits, and an evaluation suite that blocks a release if answers get less accurate |
| [**VectorForge**](https://github.com/stkef/Vector-forge) | A vector database built from first principles on NumPy, Numba and SQLite | Exact, HNSW and IVF-PQ indexes, filtered search with a cost-based planner, crash-safe write-ahead log, HTTP API + Studio, benchmarked against hnswlib, FAISS and Qdrant |
| [**MAUD Smart Revenue System**](https://github.com/stkef/maud-smart-revenue) | Government of Andhra Pradesh hackathon project, **selected and taken into development** | Built the React / TypeScript dashboard for revenue and collection monitoring: charts, summary cards, data tables |
| [**Opsify**](https://github.com/stkef/opsify-ai-assistant) | Conversational AI assistant | LangChain orchestration served through FastAPI to a React / TypeScript chat UI (shadcn/ui, Tailwind) |


---

## 💼 Experience

**SMM / Tech · Citta AI** · *Dec 2025 – present*
Social media and technical execution for an AI products company.
- **AI content pipeline:** a multi-step LLM workflow that turns verified AI/tech news into ready-to-record
  Instagram Reels: sources stories, writes sub-60-second scripts in the creator's style, exports styled
  PDFs and generates ElevenLabs voice direction.
- **AI storyboard generator:** converts scripts into scene-by-scene images and frames, so the video team
  has visual references before shooting.
- **MAUD Smart Revenue System** dashboard (above).

**Founder · Varnev Digital** · *Jan 2023 – present*
Digital agency delivering branding, UI/UX and end-to-end web deployment to early-stage startups, with
automated build-and-deploy pipelines and analytics-driven design.

**UI/UX Developer & Project Coordinator (Intern) · Founders Lab** · *Jun – Aug 2023*
Designed and built responsive interfaces for startup MVPs; coordinated product, design and development
in weekly agile sprints.

---

## 🛠️ Tech stack

**AI agents & LLMs:** LangChain · RAG · multi-step LLM workflows · prompt engineering · structured outputs · LLM evaluation & guardrails · Gemini · OpenAI-compatible APIs · Ollama
**Retrieval & ML:** embeddings · Qdrant · FAISS · ChromaDB · hybrid search (dense + BM25, RRF) · reranking & cross-encoders · fine-tuning · PyTorch · sentence-transformers · scikit-learn · Pandas · NumPy
**Backend:** Python · FastAPI (async, SSE) · Flask · SQLAlchemy · PostgreSQL · SQLite · Node.js
**Frontend:** React · TypeScript · Vite · Tailwind CSS · shadcn/ui · Figma
**Cloud & DevOps:** Docker · GitHub Actions · AWS (EC2, S3, IAM) · Azure · Kubernetes · Terraform · Nginx / Caddy · Prometheus · Grafana · Linux
**Testing & evaluation:** pytest · black-box API tests · Locust · eval harnesses (recall@k, F1, faithfulness, hallucination rate) · bootstrap significance tests

---

## 🎓 Education

**B.Tech, Computer Science & Engineering** · ACE Engineering College, Hyderabad · *2022 – 2026*

---

## 📫 Contact

[LinkedIn](https://linkedin.com/in/pradeep-kase) · [pradeepkase75@gmail.com](mailto:pradeepkase75@gmail.com)
