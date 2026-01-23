# Hi — I'm khoi01 👋
> 🤖 AI & RAG Engineer | Applied ML Practitioner  
> Building production-ready AI systems with a strong focus on Retrieval-Augmented Generation (RAG), document intelligence, and automation.


---

## About
I design and ship production-ready AI systems that tightly integrate retrieval, grounding, and evaluation. My work centers on practical RAG pipelines and robust document intelligence for real-world applications — with an emphasis on reproducibility, observability, and private/hybrid deployments.

Current focus: improving retrieval quality, grounding, and evaluation metrics for real-world RAG systems.

---

## What I work on
- 🧠 RAG pipelines — chunking, embeddings, reranking, evaluation, and end-to-end orchestration  
- 📄 PDF & knowledge ingestion — semantic and structure-aware chunking, layout-aware extraction  
- 🔍 Vector search — metadata-driven retrieval, filter-aware reranking, and hybrid search strategies  
- 🐳 Dockerized AI systems — reproducible deployments for private & hybrid infra  
- ⚙️ Local & cloud LLMs — Ollama, OpenAI, Azure OpenAI (and integrations with other LLM providers)  
- 🔁 Automation & CI — automated testing, deployment pipelines, and reproducible experiments

---

## Tech stack
- Languages: Python  
- Libraries & Frameworks: LangChain, SentenceTransformers, QuartAPI  
- Vector stores: ChromaDB  
- Infrastructure: Docker, Docker Compose (for dev & production-like local stacks)  
- Other: embeddings, retrievers, rerankers, evaluation tooling, metrics, experiment tracking

---

## Example RAG pipeline (high level)
1. Ingest documents (PDF, HTML, DOCX) → structure-aware parsing  
2. Chunk with semantic & layout-aware strategies (keep context for tables, headings, code blocks)  
3. Generate embeddings (SentenceTransformers) and store in vector DB (Chroma)  
4. Retrieve with metadata filters → rerank with cross-encoder / reranker model  
5. Compose prompt with retrieved context → call LLM (local or cloud) with grounding controls  
6. Evaluate: retrieval metrics, factuality checks, attribution scoring, and user-feedback loop

---

## How I measure success
- Retrieval: precision@k, recall@k, MRR for reranked candidates  
- Grounding: attribution coverage, hallucination reduction metrics  
- End-to-end: human evaluation, task success rate, latency & cost tradeoffs

---
