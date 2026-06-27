<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Aman%20Dinesh%20Gourkhede&fontSize=38&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Machine%20Learning%20Engineer%20%7C%20Generative%20AI%20%7C%20Multi-Agent%20AI%20%7C%20Computer%20Vision&descAlignY=55&descSize=16" width="100%"/>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=6E57F7&center=true&vCenter=true&multiline=true&repeat=true&width=750&height=100&lines=Multi-Agent+AI+%7C+RAG+%7C+LLM+Inference+%7C+Claim+Verification;Built+a+Deep+Research+Engine+from+scratch+%E2%80%94+no+LangChain+%F0%9F%9A%80;IBM+RAG+%26+Agentic+AI+Certified+%7C+RTX+4070+GPU+Local+LLMs)](https://git.io/typing-svg)

</div>

<div align="center">

[![Gmail](https://img.shields.io/badge/amangourkhede03%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:amangourkhede03@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-aman--gourkhede-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aman-gourkhede-029869279)
[![Portfolio](https://img.shields.io/badge/Portfolio-aman--gourkhede.vercel.app-6E57F7?style=flat-square&logo=vercel&logoColor=white)](https://aman-gourkhede-portfolio.vercel.app)
[![Location](https://img.shields.io/badge/Nagpur%2C%20India-🇮🇳-FF9933?style=flat-square)](https://github.com/AmanGourkhede)

</div>

---

## 🧠 About Me

```python
class AmanGourkhede:
    title      = "Machine Learning Engineer | Generative AI | Multi-Agent AI"
    location   = "Nagpur, India"
    education  = "B.Tech CSE — YCCE Nagpur (2025) | CGPA: 7.2"
    certified  = ["IBM RAG & Agentic AI Professional Certificate (Coursera)",
                  "LLMOps — Duke University (Coursera)"]

    expertise  = [
        "Multi-Agent AI Orchestration — built from scratch, no LangChain",
        "Local LLM Inference with GPU (Ollama + RTX 4070, 100% GPU utilized)",
        "Claim Verification Pipelines — fact checking at 65% confidence threshold",
        "RAG, Agentic AI, ChromaDB, Redis, Pydantic, Span-based Observability",
        "Computer Vision (CNN, ResNet50, Transfer Learning, OpenCV)",
        "MLOps (Docker, FastAPI, Flask, AWS, CI/CD, GitHub Actions)",
    ]

    currently  = "Building production-grade AI systems that verify what they say 🔬"
```

---

## 🚀 Featured Projects

### ⭐ Multi-Agent Deep Research Engine — HIGHLIGHT PROJECT
> **7-phase AI research pipeline built entirely from scratch — no LangChain, no paid APIs.**
> Runs 100% locally on RTX 4070 GPU using Ollama. Every fact is verified before it reaches the writer.

[![multi-agent-deep-research](https://github-readme-stats.vercel.app/api/pin/?username=AmanGourkhede&repo=multi-agent-deep-research&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6E57F7&icon_color=6E57F7)](https://github.com/AmanGourkhede/multi-agent-deep-research)

| Phase | What Happens |
|-------|-------------|
| 🌐 **Phase 1 — Scrape** | 4 search queries × 5 pages = 20 web pages fetched via BeautifulSoup |
| 🔍 **Phase 2 — Extract** | Individual factual claims pulled from every page |
| ✅ **Phase 3 — Verify** | Each claim scored by LLM against research evidence — 65% confidence threshold |
| 🎯 **Phase 4 — Judge** | Relevance scoring against original topic — 60% threshold, sorted best-first |
| 📊 **Phase 5 — Diagram** | AI finds numerical data, Plotly renders bar/line/pie charts as PNG |
| ✍️ **Phase 6 — Write** | 7-section 2000+ word article using ONLY verified, relevant facts |
| 🧑‍⚖️ **Phase 7 — Edit** | Senior editor agent reviews, fixes weak sections, improves conclusion |
| 📄 **Export** | Self-contained HTML (base64 charts embedded) + PDF output |

**Key engineering decisions:**
- `format=json_schema` passed to Ollama — model physically cannot generate wrong JSON structure
- JSON boundary extraction with depth counter — handles any nesting level
- 3-attempt retry with error feedback to model — self-correction loop
- Two quality gates before writer: verification (65%) AND relevance (60%)
- Writer never sees raw web content — only verified, relevant facts
- Span-based observability with step-by-step trace replay
- Human-in-the-loop escalation on low confidence tasks
- Redis short-term + ChromaDB long-term memory

`Python` `Ollama` `dolphin-llama3:8b` `ChromaDB` `Redis` `Pydantic v2` `Plotly` `BeautifulSoup` `Streamlit` `Docker` `RTX 4070 GPU`

---

### 🤖 MRDS — Model Regression Detection System

> A production-grade **CI/CD eval pipeline** for LLM-powered classifiers — tests against a **hand-crafted 60-sample golden dataset**, detects quality regressions via moving averages, and alerts the team in real time via Slack.

| Detail | Value |
|--------|-------|
| 📊 Golden Dataset | 60 samples — easy / medium / hard, 4 categories |
| 🔍 Scoring | Category match + LLM-as-judge (1–5) + BGE embedding cosine similarity |
| 📉 Regression Detection | 7-run moving average drift detection |
| 🚨 Alerting | Slack Block Kit alerts with tenacity retry |
| 📈 Dashboard | Live Streamlit UI with Plotly trend charts |
| 🐳 Infra | Docker, GitHub Actions CI, git pre-push hook |

`Python` `Ollama` `Pydantic v2` `SQLite` `Streamlit` `Plotly` `sentence-transformers` `Docker` `GitHub Actions`

---

### 📚 RAG From Scratch — Complete Local Document Q&A System

> **Built a full Retrieval-Augmented Generation pipeline from zero — no LangChain, no frameworks, no paid APIs.**
> Chat with your own PDF/text documents using a completely local, offline AI system.

[![rag-from-scratch](https://github-readme-stats.vercel.app/api/pin/?username=AmanGourkhede&repo=rag-from-scratch-&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6E57F7&icon_color=6E57F7)](https://github.com/AmanGourkhede/rag-from-scratch-)

| Component | What It Does |
|-----------|-------------|
| 📄 **Loader** | Reads PDF and TXT documents from local storage |
| ✂️ **Chunker** | Splits text into overlapping chunks for better context retrieval |
| 🔢 **Embedder** | Converts chunks to vectors using `all-MiniLM-L6-v2` (HuggingFace) |
| 🗄️ **VectorStore** | Stores and indexes vectors in ChromaDB |
| 🔍 **Retriever** | Semantic nearest-neighbour search — finds most relevant chunks |
| 🤖 **Generator** | Feeds retrieved context to Ollama LLM to produce grounded answers |
| 📊 **Evaluator** | RAGAS metrics — faithfulness, answer relevancy, context precision |

**Why build RAG from scratch?**
Most developers use LangChain's `RetrievalQA` and treat it as a black box. Building each component individually — chunker, embedder, retriever, generator — proves you understand what's actually happening inside those abstractions. This is what separates engineers from users.

`Python` `Ollama` `llama3.2:1b` `ChromaDB` `sentence-transformers` `HuggingFace` `RAGAS` `PyMuPDF`

---

### 🔬 Skin Cancer Detection System — B.Tech Mega Project

> Achieved **93.52% accuracy** across 7 lesion categories using **CNN + ResNet50 ensemble** — surpassing single-model baselines by ~8%. Custom Digital Hair Removal pipeline via OpenCV morphological operations.

| Detail | Value |
|--------|-------|
| 🎯 Accuracy | 93.52% across 7 lesion categories |
| 📈 Improvement | +8% over single-model baseline |
| 🗃️ Dataset | HAM10000 + ISIC 2024 |
| 🚀 Live Demo | [🤗 Try it on Hugging Face](https://huggingface.co/spaces/AmanDinesh/skin-cancer-detection) |

`TensorFlow` `Keras` `ResNet50` `OpenCV` `CNN` `Transfer Learning` `HAM10000`

---

### 🧬 Jarvis — Personal AI Agent

> Modular **LangChain + LangGraph** agent with multi-step workflows, RAG via ChromaDB, and persistent long-term memory. Pluggable tool-use framework (web search, file manager, code executor).

`LangChain` `LangGraph` `ChromaDB` `RAG` `Agentic AI` `Vector Databases` `Python`

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**AI / ML & Generative AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

**MLOps & Backend**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-6E57F7?style=for-the-badge&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AmanGourkhede&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6E57F7&icon_color=6E57F7&text_color=ffffff&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AmanGourkhede&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6E57F7&text_color=ffffff&langs_count=6" height="165"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=AmanGourkhede&theme=tokyonight&hide_border=true&background=0D1117&ring=6E57F7&fire=6E57F7&currStreakLabel=6E57F7)](https://git.io/streak-stats)

</div>

---

## 🎓 Certifications & Education

| | |
|---|---|
| 📜 **IBM RAG & Agentic AI Professional Certificate** | Coursera — 10-course: RAG, LangChain, LangGraph, CrewAI, MCP, Vector DBs |
| 📜 **LLMOps Professional Certificate** | Duke University via Coursera |
| 🎓 **B.Tech — Computer Science & Engineering** | YCCE Nagpur · 2022–2025 · CGPA: 7.2/10 |
| 📘 **Diploma — Computer Engineering** | Govt. Polytechnic Nagpur · 2019–2022 · 87% |

---

## 🌱 What I'm Working On

- 🔬 Adding async parallel verification to the deep research engine (5× speed gain)
- 📊 Source credibility scoring — weight .gov/.edu over random blogs
- 📜 Completing IBM RAG & Agentic AI certification

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
