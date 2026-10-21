# Hi, I'm Mohit Krishna 👋

**Applied AI / Agentic AI Engineer | MS CS @ California State University, Long Beach (Graduating Dec 2026)**
I build GenAI and agentic systems and make them reliable — retrieval, evals, guardrails, and the backends that serve them.
**Two systems live in production**, and I care most about what happens after the demo.

## 💡 About

- 2+ years of production ML experience, now specializing in **GenAI and agentic systems** with eval and guardrail discipline
- **Languages:** Python · SQL · JavaScript
- **GenAI & Agents:** LangChain · LangGraph · OpenAI Agents SDK · MCP / FastMCP · HuggingFace · OpenAI API
- **RAG & Retrieval:** BM25 · RRF · Cross-encoder · FAISS · LanceDB · Sentence Transformers · Pinecone
- **Backend:** FastAPI · Flask · Docker · PostgreSQL · SQLite
- **Cloud & MLOps:** AWS (EC2, S3) · GitHub Actions CI/CD · MLflow · Pytest

## 🏆 Highlights

- **HybridRAG (live):** Production RAG chatbot on AWS EC2 with hybrid search and per-sentence faithfulness checks - cut answer latency **~20s → 2-3s**, **9** pytest tests in CI. → [hybridrag.mohitkrishna.dev](https://hybridrag.mohitkrishna.dev)
- **PipelinePilot (live):** Agent on the OpenAI Agents SDK + a custom **7-tool MCP server**, with a human-approval gate and an output guardrail that blocked **every invented claim across an 8-case eval (0 FP / 0 FN)**. → [pipelinepilot.mohitkrishna.dev](https://pipelinepilot.mohitkrishna.dev)
- **Honeywell (AI Engineer Intern):** Built a maintenance copilot's RAG + LangGraph agent - cut unsupported answers **~40%**, measured **~85%** faithfulness across **~300** engineer questions.
- **Trigent (SWE, Python & ML):** Churn and propensity models scoring **~2M customer profiles weekly** on AWS; lifted churn recall **~15%** over rule-based scoring.
- **ImageQuery:** Semantic image search at **0.98 precision@5** on a 200-image, 10-breed test set.

## 🚀 Featured Work

| Project | Tech | What Stands Out |
|---|---|---|
| [**HybridRAG**](https://github.com/mohitkrishna21/HybridRAG) · 🟢 [live](https://hybridrag.mohitkrishna.dev) | FastAPI · LanceDB · BM25 · Cross-encoder · Groq · Nginx · GitHub Actions | Live on AWS EC2; hybrid BM25 + semantic search (RRF), cross-encoder reranking, per-sentence faithfulness eval. Latency ~20s → 2-3s, 9 CI tests |
| [**PipelinePilot**](https://github.com/mohitkrishna21/PipelinePilot) · 🟢 [live](https://pipelinepilot.mohitkrishna.dev) | OpenAI Agents SDK · FastMCP · FastAPI · SSE · SQLite · Docker | Live; agent + custom 7-tool MCP server, human-approval gate, output guardrail (8-case eval, 0 FP / 0 FN), SSE streaming |
| [**LedgerQuery**](https://github.com/mohitkrishna21/LedgerQuery) | sqlglot · SQLite · Groq · FastAPI · Docker | Natural-language-to-SQL over financial ledgers with validated query generation |
| [**ImageQuery**](https://github.com/mohitkrishna21/ImageQuery) | CLIP · LanceDB · FastAPI | Text-query image search; 0.98 precision@5 on a 200-image set |
| [**MemeSense**](https://github.com/mohitkrishna21/MemeSense) | CLIP · PyTorch · LanceDB · FastAPI | 4 CLIP fusion strategies (early/intermediate/late) vs text-only & image-only baselines - intermediate fusion the only one to beat both. Frozen CLIP + linear probing; BLIP captions as metadata (not fused) |

**More projects:** [DocuQuery](https://github.com/mohitkrishna21/docuquery) · [Prompt Optimizer](https://github.com/mohitkrishna21/prompt-optimizer) · [Document Classifier & Summarizer](https://github.com/mohitkrishna21/document-classifier-summarizer) · [Tokenization Explorer](https://github.com/mohitkrishna21/tokenization-explorer)

## 💼 Experience

**AI Engineer Intern - Honeywell** · May 2026 – Aug 2026
- Built key retrieval components of a maintenance copilot's RAG pipeline (Pinecone, a deployed cross-encoder reranker), lifting top-5 hit rate ~20%.
- Engineered a LangGraph tool-calling agent over manuals, anomaly scores, and work-order history.
- Enforced Pydantic-structured outputs and mandatory citations, cutting unsupported answers ~40%.
- Designed a Pytest + MLflow eval suite, measuring ~85% faithfulness across ~300 engineer questions.

**Software Engineer, Python & ML - Trigent Software** · Jan 2023 – Dec 2024
- Developed churn and propensity models in scikit-learn, lifting churn recall ~15% over rule-based scoring.
- Automated data prep with reusable Python ETL (Pandas, NumPy), cutting refresh time ~40%.
- Served churn and propensity scores to the client's CRM via FastAPI on Docker + AWS.
- Operated weekly batch scoring for ~2M customer profiles on AWS with post-release drift monitoring.

## 📫 Connect

📧 mohitkrishna2024@gmail.com &nbsp;·&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/mohit-krishna21) &nbsp;·&nbsp; 🌐 [mohitkrishna.dev](https://mohitkrishna.dev) &nbsp;·&nbsp; 📍 Long Beach, California

**Work Authorization:** Eligible for 36 months via STEM OPT — no immediate sponsorship required.
