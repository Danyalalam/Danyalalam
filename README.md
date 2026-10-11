# Danyal Alam

**AI Engineer** · LLM agents, retrieval systems and production Python

I build LLM agents and RAG systems that run in production, mostly for clients in the US, UK and Europe. My work sits at the application layer: agent workflows, retrieval quality, evaluation, and the backend plumbing that makes both reliable.

### What I work on

- **Agents** — multi-step workflows with tool and function calling, guardrails and state handling, built with LangGraph and LangChain
- **Retrieval** — hybrid search combining sparse keyword and dense vector retrieval, citation handling, and evaluation against accuracy and latency rather than vibes
- **MCP** — servers and tool definitions that expose internal systems to LLM agents with scoped permissions
- **Shipping** — FastAPI services, Docker, CI/CD, and tracing with Langfuse so failures are debuggable

### Featured projects

- **[ai_language_agent](https://github.com/Danyalalam/ai_language_agent)** — full-stack pronunciation assessment app. Azure Speech SDK scores the audio, Gemini turns the results into a readable feedback report. FastAPI backend (uv, Python 3.13), React + TypeScript + Vite frontend served through Nginx, multi-stage Docker builds with Compose. Next up: CI/CD and Azure Container Apps
- **Food packaging automation (client project, B2B SaaS MVP)** — LangGraph and LlamaIndex pipeline that extracts packaging data and renders front-panel templates. Hybrid design: LLM extraction, HTML/CSS rendering and a Fabric.js/Konva.js canvas editor, instead of unpredictable pure image generation. Qdrant Cloud (EU) for retrieval, LlamaParse for documents, Langfuse for tracing, FastAPI backend. Private repo, walkthrough on request

### Selected repositories

- **[LLM-from-scratch](https://github.com/Danyalalam/LLM-from-scratch)** — transformer built up component by component, for understanding the layer below the frameworks
- **[Production-Grade-ML-Project](https://github.com/Danyalalam/Production-Grade-ML-Project)** — end-to-end pipeline from ingestion and validation through training to cloud deployment. MongoDB, AWS, Docker, FastAPI, CI/CD
- **[End-To-End-DL-Project-With-MLOPS](https://github.com/Danyalalam/End-To-End-DL-Project-With-MLOPS)** — deep learning project with a full MLOps workflow

### Stack

**LLM & agents** LangGraph · LangChain · LlamaIndex · MCP · Langfuse
**Retrieval** Qdrant · ChromaDB · hybrid sparse and dense search
**Backend** Python · FastAPI · WebSockets · PostgreSQL · MongoDB
**Infra** Docker · Azure · AWS · GitHub Actions
**ML** PyTorch · scikit-learn · Pandas · NumPy

### Contact

danyalalam514@gmail.com · [LinkedIn](https://www.linkedin.com/in/danyal-alam-272593312/)
