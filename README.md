<h1 align="center">Saikiran Babu Annangi</h1>

<p align="center">
  <strong>AI Engineer</strong> · Retrieval-Augmented Generation · Compound AI Systems · Agentic Workflows · Applied LLMs
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=1000&color=10EBF7&center=true&width=800&lines=Building+AI+Systems+That+Ship;RAG+%7C+Agents+%7C+Evaluation+%7C+Compound+AI;From+Prototype+to+Production" alt="Typing SVG">
</p>

<p align="center">
  <a href="https://linkedin.com/in/annangisaikiranbabu/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:asaikiranb@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/asaikiranb">
    <img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://saikiranb.com">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
</p>

---

## 👋 About

I build AI systems that actually work in production — not demos, not decks.

My work spans the full stack of applied AI: designing retrieval pipelines with strong recall and precision, chaining LLM components into compound systems with proper evaluation loops, and shipping agentic workflows that handle real-world edge cases without falling apart.

I approach AI engineering the same way I approach any engineering problem — instrument it, stress test it, and don't claim it works until you can show why.

---

## 🏗 What I Build

| 🔍 RAG Systems | 🤖 Compound AI | 🧪 Evaluation | ⚙️ Agentic Workflows |
|---|---|---|---|
| Chunking · Reranking · Hybrid search | Planning · Generation · Checking pipelines | LLM-as-judge · Groundedness · Recall | LangGraph · Tool use · Memory |
| Multimodal retrieval (text, image, audio) | Prompt routing · Guardrails · Fallbacks | Gold dataset construction · Drift detection | ReAct · Self-correction · State machines |
| Qdrant · FAISS · Semantic caching | Feedback loops · Self-improving pipelines | RAGAS · Custom eval harnesses | Multi-agent coordination |

---

## 🛠 Tech Stack

### 💻 Core Languages

<p align="center">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/SQL-07405e?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" />
</p>

### 🤖 AI / LLM Stack

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Anthropic-000000?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white" />
  <img src="https://img.shields.io/badge/Qdrant-FF4081?style=for-the-badge&logo=qdrant&logoColor=white" />
</p>

### 📦 ML & Data Infrastructure

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-d9ead3?style=for-the-badge&logo=mlflow&logoColor=blue" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
</p>

### ☁️ Cloud & Platforms

<p align="center">
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
</p>

---

## 🚀 Shipped Projects

### 🔧 Multimodal RAG for Field Technicians · [Contextual AI Capstone]
Built a multimodal retrieval system for HVAC field technicians delivered over WhatsApp. Combined Faster-Whisper for voice, YOLO + PaddleOCR for image/diagram parsing, and BAAI/bge-m3 embeddings over Qdrant — all orchestrated with LangGraph. The system retrieves grounded, context-aware answers across modalities in real time.

**Stack:** LangGraph · Qdrant · BAAI/bge-m3 · PaddleOCR · YOLO · Faster-Whisper · WhatsApp API

---

### 🛡 LLM Guardrail Auditor · [Open Source POC]
Designed an evaluation framework that stress-tests LLM pipelines against documented failure vectors — hallucination, retrieval misalignment, refusal drift, and prompt injection. Outputs a structured audit report with per-category scores and flagged examples.

**Stack:** Python · Anthropic Claude · Custom eval harness

---

### 💬 RAG-Powered Portfolio Assistant · [saikiranb.com]
Built the "Ask me anything" interface on my portfolio site using local embeddings, semantic chunking, and Groq for low-latency inference — deployed on Next.js. Visitors can query my work history, projects, and writing directly.

**Stack:** Next.js · Local embeddings · Groq · Semantic search

---

### 🔭 VentureScope · Text-to-SQL Agent
Natural language to SQL agent for startup and market data. Uses a planning step to decompose queries, routes to the right schema context, generates SQL, and self-corrects on execution errors before returning structured results.

**Stack:** Python · OpenAI · LangChain · PostgreSQL · FastAPI

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=asaikiranb&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=asaikiranb&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=asaikiranb&theme=tokyo-night&hide_border=true" />
</p>

---

## 📚 Publications

1) **NeuroPredict: A Comprehensive Approach for Alzheimer's Disease Prediction and Development of a Medical Assisting Kit** — IEEE Conference, 2024  
https://ieeexplore.ieee.org/document/10419914  

2) **API Driven Framework for AES Modes of Encryption Enhanced with Machine Learning** — IRJMETS, 2023  
https://www.irjmets.com/uploadedfiles/paper//issue_7_july_2023/43316/final/fin_irjmets1689856261.pdf

---

<p align="center">
  <i>Open to AI Engineering, Applied AI, and Forward Deployed roles</i>
</p>
