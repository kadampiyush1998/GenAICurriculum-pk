# GenAICurriculum-pk

# Applied GenAI Curriculum (Extracted from Screenshots)

## MODULE 1 — Prompt Engineering and API Integration

### Topics
- AI vs ML vs Deep Learning
- Introduction to Generative AI (GenAI)
- Open-source vs Closed-source AI Models
- GenAI Platforms Overview (OpenAI, Anthropic, Mistral, Stable Diffusion, Midjourney)
- Ethics & Responsible AI Usage
- Prompt Anatomy (Role, Instruction, Input, Output)
- Prompting Techniques (Zero-shot, Few-shot, Role-based Prompting)
- Advanced Prompting (CoT, ToT, ReAct, Self-Consistency)
- Handling AI Responses (JSON parsing, streaming, batch outputs, error handling)
- AI Guardrails & Output Validation
- Conversation Memory & Context Management
- Working with OpenAI/Gemini APIs (Chat, Embeddings, Function Calling)
- API Security, Rate Limits & Key Management
- Debugging & Evaluating GenAI Outputs (Accuracy, Relevance, Reliability)

### Tools
- Python
- Hugging Face
- Hugging Face API
- LLM API
- Postman

---

## MODULE 2 — Basics of NLP and Retrieval-Augmented Generation (RAG)

### Topics
- Text Preprocessing & Tokenization
- Text Representation & Feature Engineering
- Named Entity Recognition (NER) & POS Tagging
- Embeddings, Vectorization & Semantic Search
- Chunking Strategies for LLM Applications
- RAG Fundamentals & Architecture
- Retrieval + Generation Workflow in RAG
- Data Handling, Chunking & Indexing
- Vector Databases & Vector Stores
- Dense vs Sparse Retrieval & Hybrid Search
- Working with Text/Image Embeddings in Vector DBs
- Building a Simple RAG Pipeline with LlamaIndex
- Query Rewriting, Multi-hop & Multi-query Retrieval
- Reducing Hallucinations & Context Optimization
- Advanced RAG Techniques (Self-RAG, Corrective RAG, Adaptive RAG, Contextual Retrieval, LOTR)
- Why Basic RAG Fails & Advanced Improvement Strategies
- RAG Evaluation & Fallback Mechanisms
- RAGAS Metrics (Faithfulness, Relevance, Context Recall, etc.)

### Tools
- LangChain
- LlamaIndex
- Hugging Face
- Embeddings
- FAISS
- VectorDB
- Pinecone

---

## MODULE 3 — AI Agents and Multi-Agent Systems

### Topics
- Introduction to AI Agents & Agent Architectures
- Types of AI Agents (Reflex, Goal-based, Utility-based, Tool-based)
- Reactive Agents & Agent Design Patterns
- Tool Calling, Execution Flows & Prompting Strategies
- Multi-Agent Systems (MAS) & Collaborative AI
- Agent Coordination, Negotiation & Consensus Mechanisms
- Popular Agent Frameworks (LangChain, LlamaIndex, AutoGen, CrewAI, LangGraph)
- ReAct Agents & Tool-Using Agents
- LangGraph for Stateful Agent Orchestration
- Framework Comparison: Choosing the Right Agent Stack
- Planning, Reasoning & Tool Orchestration in Agents
- Hierarchical & Collaborative Multi-Agent Patterns
- Goal-Oriented Agent System Design
- Multi-Agent Reinforcement Learning (MARL) Basics
- MCP (Model Context Protocol): Servers, Clients, Tools & Resources
- A2A (Agent-to-Agent) Communication Protocols
- Agentic RAG: Autonomous Retrieval + Reasoning Pipelines
- Single-Agent vs Multi-Agent Agentic RAG
- Agent Debugging, Tracing & Monitoring with LangSmith
- Latency, Performance & Cost Optimization for AI Agents

### Tools
- LangChain
- LangGraph
- AutoGen
- CrewAI
- Hugging Face
- LangSmith
- MCP SDK

---

## MODULE 4 — Deployment and Project Integration

### Topics
- Web API Fundamentals (HTTP Methods: GET, POST, PUT, DELETE)
- Building APIs with FastAPI & Pydantic
- API Documentation with Swagger/OpenAPI
- Deploying AI Apps (Render, Railway, Replit, Hugging Face Spaces)
- Dockerization for AI Applications
- CI/CD Pipelines with GitHub Actions
- Kubernetes (K8s) Basics for GenAI Scaling
- GenAI System Architecture Review (Agents, RAG, APIs)
- Designing Modular AI Systems & Microservices
- FastAPI for LLM Orchestration & LangChain Servers
- Frontend Integration with Gradio & Streamlit
- UI/UX Basics for LLM Applications
- API Security, Environment Variables & Rate Limiting
- Introduction to LLMOps & Production AI Workflows
- Prompt Versioning, Tracing & Performance Monitoring
- LLMOps Platforms (Langfuse, MLflow, LangGraph)
- Observability with Prometheus & Grafana
- Live Deployment Demo & Project Showcase

### Tools
- LangChain
- LangGraph
- FastAPI
- Streamlit
- Langfuse
- FAISS
- Docker
- GCP
- Kubernetes

---

## MODULE 5 (Optional) — AI-Assisted Development with Agentic IDEs

### Topics
- Set up and run AI coding agents across Terminal, IDEs, Cloud, and GitHub
- Choose and switch between leading AI models for different tasks
- Optimize performance with Low, Medium, and High reasoning modes
- Control agent permissions with Read-Only, Auto, and Full Access modes
- Master AI-powered terminals, commands, workflows, and planning tools
- Build persistent project memory using AGENTS.md, PLANS.md, and context files
- Connect external tools and services through MCP (Model Context Protocol)
- Create reusable Skills and Subagents for faster development
- Automate coding, testing, code reviews, CI/CD pipelines, and GitHub workflows
- Orchestrate multiple AI agents working together on complex projects
- Extend agents with Hooks, custom tools, and production-ready automations
- Understand AI limitations, hallucinations, security risks, and best practices
- Implement human-in-the-loop review, approval, and quality-control processes
- Deploy reliable, scalable, and secure AI-assisted development workflows

### Tools
- Codex
- Claude Code
- Antigravity
- MCP Server
- GitHub
- CI/CD

---

## MODULE 6 — Foundations of Neural Networks and Transformers

### Topics
- Machine Learning Foundations (Linear & Logistic Regression)
- Perceptrons & Multi-Layer Perceptrons (MLPs)
- Loss Functions & Activation Functions
- Gradient Descent & Backpropagation
- Introduction to Deep Neural Networks
- CNNs for Computer Vision Applications
- RNNs & LSTMs for Sequential Data
- Limitations of RNNs & Rise of Transformers
- Attention Mechanism (Query, Key, Value)
- Transformer Architecture Explained
- Pretraining vs Fine-tuning in LLMs
- Transfer Learning Concepts & Applications
- Introduction to GANs & Diffusion Models
- Foundations of Modern Image Generation Systems (DALL·E, Stable Diffusion, Midjourney)

### Tools
- PyTorch
- TensorFlow
- Keras
- Hugging Face
- BertViz

---

## MODULE 7 — Fine-Tuning LLMs

### Topics
- Introduction to Fine-Tuning & Domain Adaptation
- Fine-Tuning vs RAG: When to Use Each
- Hybrid Workflows: RAG + Fine-Tuning
- SLM vs LLM for Fine-Tuning
- Choosing Models (LLaMA, Mistral, Phi)
- Domain-Adaptive Pre-Training (DAPT)
- Dataset Preparation & Instruction Tuning
- Popular Datasets (Alpaca, DPO, Preference Datasets)
- Data Cleaning, Formatting & Labeling Best Practices
- PEFT Techniques (LoRA, QLoRA)
- Fine-Tuning Pipelines with Hugging Face & PEFT
- Trainer API, Configurations & Training Workflows
- Preference Optimization (DPO, ORPO, KTO)
- Quantization & Efficient Inference
- GGUF, AWQ & Model Compression Techniques
- Serving Models with vLLM & Ollama
- Evaluation Metrics (Accuracy, F1, BLEU, ROUGE)
- Fine-Tuning Performance Comparison & Benchmarking
- Cost Optimization & Resource Estimation for Training / Inference

### Tools
- Hugging Face
- Ollama
- Datasets
- vLLM
- Transformers
