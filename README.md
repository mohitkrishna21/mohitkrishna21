# Hi, I'm Mohit Krishna 👋

**Applied AI / Agentic AI Engineer**
I build GenAI and agentic systems and make them reliable — retrieval, evals, guardrails, and the backends that serve them. **Two systems live in production.**
MS CS @ California State University, Long Beach · Graduating Dec 2026 · Long Beach, CA

---

## 🏆 Highlights

- **HybridRAG** — production RAG chatbot **live on AWS EC2**; cut answer latency ~20s → 2-3s, 9 pytest tests in CI. → [hybridrag.mohitkrishna.dev](https://hybridrag.mohitkrishna.dev)
- **PipelinePilot** — agent on the OpenAI Agents SDK + a custom 7-tool MCP server; output guardrail blocked **every invented claim across an 8-case eval (0 false positives, 0 false negatives)**. → [pipelinepilot.mohitkrishna.dev](https://pipelinepilot.mohitkrishna.dev)
- **Honeywell (AI Engineer Intern)** — built a maintenance copilot's RAG + LangGraph agent; cut unsupported answers ~40%, measured ~85% faithfulness on ~300 engineer questions.
- **Trigent (SWE, Python & ML)** — churn/propensity models scoring **~2M customer profiles weekly** on AWS; lifted churn recall ~15% over rule-based scoring.
- **ImageQuery** — semantic image search at **0.98 precision@5** on a 200-image, 10-breed test set.

---

## 🧠 What I Work On

- 🔍 **RAG** — hybrid retrieval (BM25 + vectors), RRF fusion, cross-encoder reranking, faithfulness evals
- 🤖 **Agents** — LangGraph, OpenAI Agents SDK, MCP tool servers, human-in-the-loop + guardrails
- 🧪 **Multimodal** — CLIP embeddings, image search, fusion experiments
- ⚙️ **Production** — FastAPI backends, Docker, CI/CD, latency and drift monitoring

---

## 🚀 Projects

| Project | What it does | Stack |
|---|---|---|
| [**HybridRAG**](https://github.com/mohitkrishna21/HybridRAG) · 🟢 [live](https://hybridrag.mohitkrishna.dev) | Production RAG chatbot: hybrid BM25 + semantic search (RRF), cross-encoder reranking, per-sentence faithfulness check, and guardrails. Latency ~20s → 2-3s; 9 pytest tests in CI. | FastAPI · LanceDB · BM25 · Cross-encoder · Groq · Nginx · GitHub Actions |
| [**PipelinePilot**](https://github.com/mohitkrishna21/PipelinePilot) · 🟢 [live](https://pipelinepilot.mohitkrishna.dev) | Job-search agent on the OpenAI Agents SDK + a custom 7-tool MCP server, with a human-approval gate and an output guardrail (8-case eval, 0 FP / 0 FN). Streams over SSE. | OpenAI Agents SDK · FastMCP · FastAPI · SSE · SQLite · Docker |
| [**LedgerQuery**](https://github.com/mohitkrishna21/LedgerQuery) | Natural-language-to-SQL query engine over financial ledgers, with validated SQL generation. | sqlglot · SQLite · Groq · FastAPI · Docker |
| [**ImageQuery**](https://github.com/mohitkrishna21/ImageQuery) | Text-query image search over a local collection; 0.98 precision@5 on a 200-image set. | CLIP · LanceDB · FastAPI |
| [**MemeSense**](https://github.com/mohitkrishna21/MemeSense) | Multimodal sarcasm experiment: compares four CLIP fusion strategies (early/intermediate/late) against text-only and image-only baselines — intermediate fusion was the only one to beat both. Frozen CLIP + linear probing; BLIP captions stored as metadata (not fused). | CLIP · PyTorch · LanceDB · FastAPI |

**More projects:** [DocuQuery](https://github.com/mohitkrishna21/docuquery) (RAG PDF Q&A) · [Prompt Optimizer](https://github.com/mohitkrishna21/prompt-optimizer) · [Document Classifier & Summarizer](https://github.com/mohitkrishna21/document-classifier-summarizer) · [Tokenization Explorer](https://github.com/mohitkrishna21/tokenization-explorer)

---

## 💼 Experience

**AI Engineer Intern — Honeywell** · May 2026 – Aug 2026
- Built key retrieval components of a maintenance copilot's RAG pipeline (Pinecone, a deployed cross-encoder reranker), lifting top-5 hit rate ~20%.
- Engineered a LangGraph tool-calling agent over manuals, anomaly scores, and work-order history.
- Enforced Pydantic-structured outputs and mandatory citations, cutting unsupported answers ~40%.
- Designed a Pytest + MLflow eval suite, measuring ~85% faithfulness across ~300 engineer questions.

**Software Engineer, Python & ML — Trigent Software** · Jan 2023 – Dec 2024
- Developed churn and propensity models in scikit-learn, lifting churn recall ~15% over rule-based scoring.
- Automated data prep with reusable Python ETL (Pandas, NumPy), cutting refresh time ~40%.
- Served churn and propensity scores to the client's CRM via FastAPI on Docker + AWS.
- Operated weekly batch scoring for ~2M customer profiles on AWS with post-release drift monitoring.

---

## 🛠️ Stack

**Languages:** Python · SQL · JavaScript
**GenAI & Agents:** LangChain · LangGraph · OpenAI Agents SDK · MCP / FastMCP · HuggingFace · OpenAI API
**RAG & Retrieval:** BM25 · RRF · Cross-encoder · FAISS · LanceDB · Sentence Transformers · Pinecone
**Backend:** FastAPI · Flask · Docker · PostgreSQL · SQLite
**Cloud & MLOps:** AWS (EC2, S3) · GitHub Actions CI/CD · MLflow · Pytest

---

## 📫 Connect

📧 mohitkrishna2024@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/mohit-krishna21) · 🌐 [mohitkrishna.dev](https://mohitkrishna.dev) · 📍 Long Beach, California

**Work Authorization:** Eligible for 36 months via STEM OPT — no immediate sponsorship required.
