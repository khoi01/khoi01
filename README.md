# Hi — I'm khoi01 👋
> 🤖 AI & RAG Engineer | Applied ML Practitioner  
> Building production-ready AI systems with a strong focus on Retrieval-Augmented Generation (RAG), document intelligence, and automation.

Last updated: 2025-12-30

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
- Libraries & Frameworks: LangChain, SentenceTransformers, FastAPI, Quart  
- Vector stores: ChromaDB, FAISS  
- Infrastructure: Docker, Docker Compose (for dev & production-like local stacks)  
- Other: embeddings, retrievers, rerankers, evaluation tooling, metrics, experiment tracking

---

## Example RAG pipeline (high level)
1. Ingest documents (PDF, HTML, DOCX) → structure-aware parsing  
2. Chunk with semantic & layout-aware strategies (keep context for tables, headings, code blocks)  
3. Generate embeddings (SentenceTransformers or OpenAI embeddings) and store in vector DB (Chroma / FAISS)  
4. Retrieve with metadata filters → rerank with cross-encoder / reranker model  
5. Compose prompt with retrieved context → call LLM (local or cloud) with grounding controls  
6. Evaluate: retrieval metrics, factuality checks, attribution scoring, and user-feedback loop

---

## Selected projects
(Replace these with links to your repos or pin them on your profile)
- RAG-Pipeline — production-ready retrieval stack with ingestion, chunking, and evaluation.  
  Repo: https://github.com/khoi01/rag-pipeline
- doc-ingest — PDF & document ingestion toolkit with layout-aware chunking.  
  Repo: https://github.com/khoi01/doc-ingest
- local-llm-deploy — Dockerized local LLM deployment patterns (Ollama + vector DB).  
  Repo: https://github.com/khoi01/local-llm-deploy

---

## How I measure success
- Retrieval: precision@k, recall@k, MRR for reranked candidates  
- Grounding: attribution coverage, hallucination reduction metrics  
- End-to-end: human evaluation, task success rate, latency & cost tradeoffs

---

## Getting in touch
- Email: your.email@example.com
- LinkedIn: https://www.linkedin.com/in/your-linkedin
- Twitter/X: https://twitter.com/your-twitter
- Website / Portfolio: https://your-website.example

(Replace the placeholders above with your preferred contact links.)

---

## GitHub stats
![khoi01's GitHub stats](https://github-readme-stats.vercel.app/api?username=khoi01&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=khoi01&layout=compact&theme=tokyonight)

---

## Collaboration & opportunities
- I’m open to collaboration on RAG/IR-focused projects, integrations between retrieval systems and LLMs, and productionization of document intelligence systems.  
- If you have datasets, evaluation problems, or real-world use cases for RAG, let's connect.

---

## Quick notes for customizing this README
- Pin and link your top repos in the "Selected projects" section.  
- Replace contact placeholders with real links.  
- Add demos, architecture diagrams, or short GIFs to show your systems in action.  
- Consider adding badges (shields.io) for email, deployments, or build status.

---

Thanks for visiting — feel free to open an issue or contact me if you'd like to collaborate!
