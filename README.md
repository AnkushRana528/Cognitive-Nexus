<p align="center">
  <img src="assets/banner.png" alt="CareerForge AI Banner" width="100%">
</p>

# CareerForge AI

### Multi-Agent Career Intelligence System

Built using **LLMs • LangChain • Ollama • AMD AI Compute**

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)

![LangChain](https://img.shields.io/badge/LangChain-AgenticAI-green)

![Ollama](https://img.shields.io/badge/Ollama-Qwen-purple)

![AMD](https://img.shields.io/badge/AMD-AI-red)


## 📖 Overview

**CareerForge AI** is a **Multi-Agent Career Intelligence System** built using **LLMs, LangChain, Ollama (Qwen)** and **AMD AI Compute**.

The system acts as an autonomous AI career mentor by orchestrating multiple specialized AI agents that work together to analyze resumes, identify technical and soft skills, calculate career readiness, detect skill gaps, recommend personalized learning roadmaps, suggest projects and certifications, prepare interview questions, match job roles, and generate a comprehensive career report.

Unlike traditional resume analyzers, CareerForge AI follows an **Agentic AI architecture**, where each agent is responsible for a dedicated task while collaborating with others to deliver intelligent end-to-end career guidance.

# ✨ Key Features

- 📄 Intelligent Resume Parsing
- 🧠 AI-powered Skill Extraction
- 📊 Career Readiness Score
- 🔍 Skill Gap Detection
- 🗺 Personalized Learning Roadmap
- 💡 AI Project Recommendation
- 🎓 Certification Recommendation
- 📝 Resume Improvement Suggestions
- 🎤 Interview Preparation Agent
- 💼 Job Matching Agent
- 📈 Interactive Visualizations
- 📑 Professional PDF Report Generation
- 🤖 Multi-Agent AI Pipeline
- ⚡ Powered by Ollama + Qwen LLM

# 🎯 Problem Statement

Students often struggle to understand how well their resumes align with industry expectations. Existing tools provide ATS scores but fail to offer complete, personalized career guidance.

CareerForge AI addresses this by using a collaborative Multi-Agent AI system that analyzes resumes, identifies skill gaps, recommends projects and certifications, prepares interview questions, and generates a personalized career roadmap.

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| LLM | Qwen |
| Framework | LangChain |
| LLM Runtime | Ollama |
| Notebook Environment | Jupyter Notebook |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Plotly |
| PDF Processing | PDFPlumber, PyPDF |
| Report Generation | FPDF, ReportLab |
| AI Platform | AMD AI Compute |

## 🏗️ System Architecture

```mermaid
flowchart TD
    A[Resume PDF] --> B[Resume Parser Agent]
    B --> C[Skill Extraction Agent]
    C --> D[Career Readiness Agent]
    D --> E[Skill Gap Agent]

    E --> F[Learning Roadmap Agent]
    E --> G[Project Recommendation Agent]
    E --> H[Certification Recommendation Agent]

    F --> I[Resume Improver Agent]
    G --> I
    H --> I

    I --> J[Interview Preparation Agent]
    J --> K[PDF Report Generator]
    J --> L[Interactive Dashboard]
    K --> M[CareerForge AI Chat]
    L --> M
```

# 📸 Project Screenshots

## 🏠 Dashboard

<img src="assets/screenshots/dashboard.png" width="100%"/>

---

## 📄 Resume Analyzer

<img src="assets/screenshots/resume_upload.png" width="100%"/>

---

## 🤖 AI Chat

<img src="assets/screenshots/chat.png" width="100%"/>

---

## 📈 Placement Progress Analytics

<img src="assets/screenshots/Placement Progress Chart.png" width="100%"/>

---

## 🧠 Skills Breakdown

<img src="assets/screenshots/Skills Breakdown Chart.png" width="100%"/>

---

## 💡 AI Suggestions

<img src="assets/screenshots/AI Suggestions.png" width="100%"/>

---

## 📋 Daily Tasks

<img src="assets/screenshots/tasks.png" width="100%"/>

---

## 👤 Profile Dashboard

<img src="assets/screenshots/profile.png" width="100%"/>

---

## 📄 Resume Parsing Agent

<img src="assets/screenshots/resume_parser_output.png" width="100%"/>

---

## ⚙ Backend Running

<img src="assets/screenshots/backend.png" width="100%"/>

---

## 💬 CareerForge AI Conversation

<img src="assets/screenshots/Career_Forge AI Chat Interface.png" width="100%"/>


# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/AnkushRana528/CareerForge_AI.git

cd CareerForge_AI
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Start Ollama

```bash
ollama serve
```

## Pull the Model

```bash
ollama pull qwen3:4b
```

## Launch Jupyter

```bash
jupyter notebook
```

Open

```
notebooks/00_master_pipeline.ipynb
```

Run all cells.

# 👥 Team

## Team Lead

**Ankush Rana**

## Team Members

- Ashish Kumar
- Saransh Arora
- Harmandeep Kaur

Institution:
Maharishi Markandeshwar (Deemed to be University)


