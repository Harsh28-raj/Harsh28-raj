<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00FFFF&center=true&vCenter=true&width=800&lines=Hi%2C+I'm+Harsh+Raj+%F0%9F%91%8B;AI%2FML+Engineer+%7C+Agentic+AI+%26+RAG;Building+systems+that+actually+ship." alt="Typing SVG" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-00FFFF?style=for-the-badge&logo=vercel&logoColor=black)](https://portfolio.harshraj.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/harsh-raj4308g)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/harsh7865)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harshraj4308g@gmail.com)

</div>

---

## About Me

```python
harsh_raj = {
    "role"      : "AI/ML Engineer · B.Tech CSE @ AKGEC (2028)",
    "focus"     : ["Agentic AI", "LangGraph / ReAct", "RAG Systems", "FastAPI backends"],
    "now"       : "AI Agentic Engineering Intern @ AxioraPeople",
    "community" : "Organizer & Mentor @ Machine Learning Centre of Excellence (MLCoE)",
    "open_source": "RAGFlow contributor (infiniflow/ragflow)",
    "available" : "Open to AI/ML & backend internship opportunities",
}
```

I build AI systems end-to-end, from architecture to deployment: autonomous multi-agent backends, real-time data platforms and RAG pipelines. Every project below is live, not just a notebook.

---

## Currently

- 🔧 Taking **AgentOS** from a working multi-agent backend to a production-grade v2
- 🌍 Contributing to open-source RAG / agent infrastructure (**RAGFlow**), working toward bug fixes and tests
- 💼 Building AI-powered hiring features and backend services as an AI Agentic Engineering Intern
- 🧮 Daily DSA practice (450+ problems solved, LeetCode contest rating 1575)

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ AgentOS
**Multi-agent AI backend with human-in-the-loop safety**

LangGraph ReAct agent with a **Supervisor** routing to 3 specialised sub-agents (Research, Coder, Vision), three-tier memory (Postgres checkpointing, ChromaDB RAG, episodic audit logs) and **confirm / reject / edit** approval for risky tool calls. Approval flow verified end to end against a live Gmail account: a real send executed only after explicit approval.

**Stack:** `LangGraph` `FastAPI` `PostgreSQL` `ChromaDB` `Groq` `SSE`

[![Live Demo](https://img.shields.io/badge/Live_Demo-00FFFF?style=flat-square&logoColor=black)](https://agentos-core-ivory.vercel.app)&nbsp;[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Harsh28-raj/agentos-core)

</td>
<td width="50%" valign="top">

### 🛰️ SolarSentinel
**Real-time space weather intelligence platform**

Tracks **27,000+ satellites** in real time on live NASA / NOAA APIs, modelling per-satellite damage probability (0–100) via orbital mechanics and NASA SHIELDOSE-2. L1 solar-wind pipeline delivers **45-minute early warnings** for geomagnetic storms with grid heatmaps and automated G1–G5 risk alerts.

**Stack:** `FastAPI` `Python` `NASA DSCOVR` `NOAA GOES` `Skyfield` `NumPy`

[![Live Demo](https://img.shields.io/badge/Live_Demo-00FFFF?style=flat-square&logoColor=black)](https://solar-sentinel-v3.onrender.com)&nbsp;[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Harsh28-raj/solar-sentinel-v3)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 DataMind AI
**Agentic conversational data analyst**

LangGraph agent that turns plain-English questions into SQL / Pandas over DuckDB's OLAP engine, then surfaces hidden data issues with **3-layer anomaly detection** (IQR, Z-Score, Isolation Forest), auto-generated Plotly charts and streamed AI summaries that explain its own reasoning.

**Stack:** `LangGraph` `FastAPI` `DuckDB` `Groq` `Streamlit`

[![Live Demo](https://img.shields.io/badge/Live_Demo-00FFFF?style=flat-square&logoColor=black)](https://datamind-ai-frontend.onrender.com)&nbsp;[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Harsh28-raj/agentic-ai-data-analyst)

</td>
<td width="50%" valign="top">

### 🤖 UNIT-V432 · Kinetic Intelligence
**Autonomous terrain navigation system**

Segmentation model on a Meta AI **DINOv2 ViT-S14** backbone with a custom decoder built from scratch, reaching **98%+ validation accuracy** on a 2GB+ dataset across 10 terrain classes. CLAHE preprocessing lifted low-visibility detection by **30%**.

**Stack:** `PyTorch` `DINOv2` `OpenCV` `Streamlit`

[![Live Demo](https://img.shields.io/badge/Live_Demo-00FFFF?style=flat-square&logoColor=black)](https://kinetic-intelligence-v432.streamlit.app/)&nbsp;[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Harsh28-raj/Kinetic-Intelligence-V432)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏥 AI Healthcare Platform
**RAG-powered multi-service healthcare assistant**

**7 independent FastAPI microservices**: disease prediction, drug-condition classifiers, food / medicine barcode lookup and a FAISS + Groq RAG chatbot (MediMind). Deployed on Render and consumed by a React web app and a Flutter mobile app.

**Stack:** `FastAPI` `FAISS` `LangChain` `MongoDB Atlas`

[![Web App](https://img.shields.io/badge/Web_App-00FFFF?style=flat-square&logoColor=black)](https://healhcare-ai.vercel.app)&nbsp;[![MediMind Bot](https://img.shields.io/badge/MediMind_Bot-00FFFF?style=flat-square&logoColor=black)](https://medimind-bot.streamlit.app)&nbsp;[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Harsh28-raj/Ai_healtcare)

</td>
<td width="50%" valign="top">

### ✍️ BlogForge
**LangGraph multi-agent content pipeline**

Research → Planning → Writing agent workflow with Tavily web search and Groq inference that turns a single topic into a structured, SEO-friendly blog post, fully automated end to end.

**Stack:** `LangGraph` `LangChain` `Groq` `Tavily`

[![Live Demo](https://img.shields.io/badge/Live_Demo-00FFFF?style=flat-square&logoColor=black)](https://blogforge-ai18.streamlit.app/)&nbsp;[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Harsh28-raj/BlogForge)

</td>
</tr>
</table>

---

## How AgentOS Works

```mermaid
flowchart LR
    UI[React UI] -->|SSE stream| API[FastAPI]
    API --> SUP[Supervisor Agent]
    SUP --> RES[Research Agent]
    SUP --> COD[Coder Agent]
    SUP --> VIS[Vision Agent]
    RES --> TOOLS[Tools: web search, code interpreter, Gmail, Calendar, vision]
    COD --> TOOLS
    VIS --> TOOLS
    TOOLS --> RISK{Risky action?}
    RISK -->|yes| HITL[Human approval: confirm / reject / edit]
    HITL --> TOOLS
    API --> PG[(Postgres: checkpoints + episodic logs)]
    API --> CHROMA[(ChromaDB: RAG memory)]
```

Design choices worth noting: Postgres (not Redis) for checkpointing so long-pending approvals survive restarts without TTL risk, SSE instead of WebSockets for one-way streaming of agent events, and a max-step guard that auto-terminates runaway agent loops.

---

## Engineering Highlights

| Area | What I did | Result |
|---|---|---|
| Agent safety | Human-in-the-loop approval (confirm / reject / edit) with full audit trail in Postgres | Risky actions never run unapproved |
| Real-time systems | NASA / NOAA telemetry pipeline with orbital-mechanics damage modelling | 27,000+ satellites, 45-min early warnings |
| Computer vision | DINOv2 ViT backbone + custom decoder + CLAHE preprocessing | 98%+ val. accuracy, +30% low-visibility detection |
| ML engineering | Fixed a Random Forest data leak; built a KNN engine for 144,000 records | +63% real-world accuracy, no more memory crashes |
| MLOps | Automated 3 preprocessing pipelines, containerised deployments | 40% faster deployment, 15% faster processing |

---

## Open Source

| Project | Contribution | Status |
|---|---|---|
| [RAGFlow](https://github.com/infiniflow/ragflow) | [#20548](https://github.com/infiniflow/ragflow/pull/20548): docs update adding a provider to the tested OpenAI-API-compatible model list | ✅ Merged |

Next up: bug fixes and tests in the RAG / agent space.

---

## Experience

- **AI Agentic Engineering Intern**, AxioraPeople (Sep 2026 – Present, Remote): backend architecture, AI-powered hiring features (resume screening, AI video interviews) and containerised deployment
- **Machine Learning Engineer**, AKGEC MLCoE (Aug 2024 – Nov 2024): KNN engine for 144,000 records, Random Forest data-leak fix, pipeline automation
- **Organizer & Mentor**, AKGEC MLCoE (2025 – Present): mentoring juniors in applied ML / AI; led **CONVOLUTE'26**, a datathon with 1,344+ applicants

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

**Agents, LLMs & RAG**

![LangGraph](https://img.shields.io/badge/LangGraph-00FFFF?style=for-the-badge&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**ML & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

**Backend, Data & MLOps**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**Vector Stores:** `FAISS` · `ChromaDB`

---

## Certifications & Achievements

- 🎓 Oracle Agentic AI Certified Foundations Associate · Oracle Cloud Infrastructure Foundations Associate
- 🎓 Google DeepMind AI Research Foundations (Capstone) · Anthropic AI Fluency: Framework & Foundations
- 🎓 IBM SkillsBuild: Unleashing the Power of AI Agents · CampusX: FastAPI, Advanced RAG, Agentic AI Development
- 🏆 **Amazon ML Challenge 2026**: ranked under 700 among 100,000+ registrations (72-hour business entity resolution hackathon)
- 🏆 **DeepThought CultureTech Fellowship**: ranked #1 among shortlisted candidates
- 💻 450+ DSA problems solved · LeetCode contest rating 1575

---

## GitHub Stats

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=Harsh28-raj&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00FFFF&icon_color=00FFFF&text_color=FFFFFF&count_private=true"/>
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Harsh28-raj&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00FFFF&text_color=FFFFFF&hide=jupyter%20notebook"/>

<br/>

![GitHub Streak](https://streak-stats.demolab.com?user=Harsh28-raj&theme=tokyonight&hide_border=true&background=0D1117&ring=00FFFF&fire=00FFFF&currStreakLabel=00FFFF)

</div>

---

<div align="center">

*"I don't build prototypes. I build things that ship."*

</div>
