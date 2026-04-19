<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00D4FF&center=true&vCenter=true&width=700&lines=AI+%26+ML+Engineer;Federated+Learning+Researcher;AI+Pipeline+Engineer+%40+Cosmic+Tech;Building+Private%2C+Production-Grade+AI)](https://git.io/typing-svg)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:00D4FF,100:0D1117&height=120&section=header&text=Chinmay%20Patil&fontSize=42&fontColor=FFFFFF&fontAlignY=65&animation=fadeIn" width="100%"/>

<p align="center">
  <a href="mailto:patilchinmay100@gmail.com"><img src="https://img.shields.io/badge/Gmail-patilchinmay100-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/chinmay-patil-10xyz"><img src="https://img.shields.io/badge/LinkedIn-chinmay--patil-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/Chinmay-10"><img src="https://img.shields.io/badge/GitHub-Chinmay--10-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=Chinmay-10&style=for-the-badge&color=00D4FF&label=PROFILE+VIEWS"/>
</p>

</div>

---

## 🧠 Who I Am

> **Final-Year B.E. in AI & Data Science** @ New Horizon Institute of Technology & Management, Thane (2022–2026)
> 
> I don't just train models — I **architect production AI systems** that run privately, scale deterministically, and survive real-world edge cases. My work sits at the intersection of **ML systems engineering**, **privacy-preserving AI**, and **GPU-accelerated pipelines**.

Currently building **cinematic AI video generation (SHAMBALA)** at Cosmic Technology Lab — a pipeline that turns static images into 3D-parallax short films using depth estimation, layered compositing, and multi-model orchestration.

---

## 💼 Experience

### 🚀 AI Pipeline Engineer Intern — Cosmic Technology Lab
**Jan 2026 – Present | Mumbai, India**

> *"What does it take to go from a static image to a cinematic vertical video — reliably, reproducibly, at scale?"*

Building **SHAMBALA** — a modular, fault-tolerant AI video generation pipeline for cinematic short-form content:

- 🏗️ **Architected** a deterministic multi-stage pipeline (M2–M8) with manifest-based checkpointing for reproducible outputs and fault-tolerant execution
- 🌊 **Engineered** a 2.5D parallax motion engine using MiDaS depth maps, layered compositing, and camera motion modeling to simulate 3D from static images
- 🔬 **Integrated** SAM2 (segmentation), LaMa (inpainting), and planned AnimateDiff/LivePortrait into a unified production workflow
- ⚡ **Optimized** GPU-aware pipeline stages with sequential VRAM management, graceful fallback, and structured directory contracts
- 🎬 **Delivered** audio-video synchronization via FFmpeg assembly producing final 1080×1920 @ 30FPS vertical video outputs
- 🛡️ **Built** a QC framework using frame-level validation and artifact analysis for motion stability

**Stack:** `Python` `SAM2` `LaMa` `MiDaS` `AnimateDiff` `FFmpeg` `CUDA` `Docker` `CLI Orchestration`

---

## 🔥 Featured Projects

### 🔐 PrivatAI-RAG — Zero-Trust Local RAG System
[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github)](https://github.com/Chinmay-10/privatai-rag)

> **The Problem:** Enterprise teams need document Q&A — but can't afford to send sensitive data to OpenAI or Google. Every query to a cloud LLM is a potential compliance violation.

> **My Solution:** A fully local, zero-trust RAG system where **your documents never leave your machine**.

**What makes it production-grade:**
- 🔑 **JWT-based auth + RBAC** — role-based access control so only the right people read the right documents
- 🧠 **Qdrant vector DB** — semantic search over private document embeddings using locally-hosted models
- 🦙 **Ollama integration** — runs LLMs (Mistral, LLaMA) entirely on local hardware, zero cloud dependency
- 🐳 **Fully Dockerized** — Backend (FastAPI) + Vector DB (Qdrant) + LLM (Ollama) in a single `docker-compose up`

```
[User Upload] → [FastAPI + JWT Auth] → [Qdrant Embeddings] → [Ollama LLM] → [Answer]
      ↑                                                                           ↓
   RBAC Check ←←←←←←←←←←←←←←←←←←←← 100% Local. Zero Cloud. ←←←←←←←←←←←←←←←←
```

**Stack:** `FastAPI` `Qdrant` `Ollama` `React` `Docker` `JWT` `Python`

---

### 🛡️ FedIDS — Federated Intrusion Detection for Cyber-Physical Systems
[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github)](https://github.com/Chinmay-10/FedIDS-CyberPhysicalSystems)

> **The Problem:** Industrial networks (power grids, hospitals, factories) need threat detection — but can't centralize sensitive operational data for training. Standard ML requires a data lake. Federated environments don't have one.

> **My Solution:** A privacy-preserving intrusion detection system that trains across distributed nodes **without ever sharing raw data**.

**Research-grade results:**
- 🎯 **91% accuracy** on NSL-KDD & CICIDS2017 — production-viable threat detection
- 🔏 **Differential Privacy constraints** — mathematically bounded privacy guarantees per training round
- 📊 **Personalized Federated Learning (PFL)** — handles Non-IID data distributions across heterogeneous clients
- 📈 **Significant improvement in worst-case client performance** — no node left behind in the federation

**Stack:** `Python` `PyTorch` `Federated Learning` `Differential Privacy` `NSL-KDD` `CICIDS2017`

---

## 🛠️ Tech Stack

<div align="center">

**Languages & Core**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Databases & Vector Search**

![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**MLOps & Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Chinmay-10&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=00D4FF&icon_color=00D4FF&text_color=FFFFFF&rank_icon=github" width="48%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Chinmay-10&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=00D4FF&text_color=FFFFFF" width="40%"/>
</div>

---

## 🎯 What I'm Looking For

```python
target = {
    "role"     : ["ML Engineer", "AI Systems Engineer", "MLOps Engineer"],
    "location" : "Mumbai (Preferred) | Remote",
    "timeline" : "May 2026",
    "ctc"      : "15 LPA",
    "strengths": ["Production AI Pipelines", "Privacy-Preserving ML",
                  "GPU Systems", "Backend AI Integration"]
}
```

If you're building systems that need **private, reproducible, production-grade AI** — let's talk.

📩 **patilchinmay100@gmail.com**

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:00D4FF,100:0D1117&height=80&section=footer" width="100%"/>

*"The best AI systems are the ones that work reliably at 3am without you."*

</div>
