<h1 align="center">Edson Ibarra</h1>
<p align="center"><b>Senior AI Engineer</b> — building secure, production-grade LLM systems</p>
---

### About

I'm a backend engineer who builds AI systems for production. My focus is the part
most AI projects skip: security, reliability, and scale. I've shipped multi-agent
systems, RAG/GraphRAG pipelines, and LLM workflows for teams in fintech, e-commerce, deployed on AWS, GCP, and Azure.

### What I do

- **Multi-agent systems & AI workflows**: orchestration, tool use, evaluation, and
  failure handling for agents in production
- **RAG & GraphRAG**: retrieval pipelines over vector and graph databases, tuned
  for accuracy and latency
- **Secure AI**: prompt-injection defense, guardrails, PII handling, access control,
  and auditability for LLM applications
- **Backend**: APIs, async processing, observability, and cloud deployment

### Highlights

- Built a hybrid search RAG pipeline (BM25 + embeddings + reranker) that raised retrieval recall@10 from 62% to 89% on 200k internal documents
- Cut hallucination rate by 40% in a customer support copilot by adding citation grounding and an LLM-as-judge evaluation step
- Fine-tuned Llama 3 8B with LoRA on 50k domain examples, matching GPT-4o quality on our task at 1/20th the inference cost
- Trained a multilingual intent classifier (Spanish/English) reaching 94% F1 and replacing a rules-based system

### Tech stack

**Languages:** Python, JavaScript (TypeScript)
**AI/LLM:** Google-ADK, LangGraph, LangChain, LlamaIndex, OpenAI / Anthropic APIs, Hugging Face.
**Data:** PostgreSQL + pgvector, Neo4j, Pinecone / Qdrant / Weaviate, Redis
**Backend:** Django, DRF, Flask, FastAPI, Celery, Kafka, Docker, Kubernetes
**Cloud:** AWS, GCP, Azure — Terraform, GitHub Actions

---
