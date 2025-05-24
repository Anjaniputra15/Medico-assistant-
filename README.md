## 🧠 Multi-Agent Medical Assistant

### 🌟 AI-powered multi-agentic system for medical diagnosis and assistance

<div align="center">

![logo](https://github.com/Anjaniputra15/Medico-assistant-/blob/main/assets/logo_rounded.png)

![Python - Version](https://img.shields.io/badge/PYTHON-3.11+-blue?style=for-the-badge\&logo=python\&logoColor=white)
![LangGraph - Version](https://img.shields.io/badge/LangGraph-0.3+-teal?style=for-the-badge\&logo=langgraph)
![LangChain - Version](https://img.shields.io/badge/LangChain-0.3+-teal?style=for-the-badge\&logo=langchain)
![Qdrant Client - Version](https://img.shields.io/badge/Qdrant-1.13+-red?style=for-the-badge\&logo=qdrant)
![Pydantic - Version](https://img.shields.io/badge/Pydantic-2.10+-red?style=for-the-badge\&logo=pydantic)
![FastAPI - Version](https://img.shields.io/badge/FastAPI-0.115+-teal?style=for-the-badge\&logo=fastapi)
![Docling - Version](https://img.shields.io/badge/Docling-3.1+-orange?style=for-the-badge\&logo=docling)
![License](https://img.shields.io/badge/License-Apache-green?style=for-the-badge)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg?style=for-the-badge)

</div>

---

## 📌 Overview

The **Multi-Agent Medical Assistant** is an **AI-powered chatbot** designed to assist with **medical diagnosis, research, and patient interactions**.

### Key Highlights:

* Integrates **Large Language Models (LLMs)**
* Supports **medical imaging** via computer vision
* **Retrieval-Augmented Generation (RAG)** with vector database
* **Real-time web search** for latest research
* **Human-in-the-loop** validation for medical safety

## 📈 Technical Flow

![Technical Flow Chart](assets/final_medical_assistant_flowchart_light_rounded.png)

## ✨ Features

* Multi-agent architecture for task-specific processing
* Hybrid RAG with Docling, Qdrant, semantic chunking, reranking
* Computer Vision: Chest X-ray, Skin Lesion, Brain Tumor (TBD)
* Real-time research via web scraping agents
* Voice interaction using Eleven Labs
* Confidence scoring and agent handoff to ensure accuracy
* Human-in-the-loop verification and safety guardrails

## 🛠️ Tech Stack

| Component        | Technologies                       |
| ---------------- | ---------------------------------- |
| Backend          | FastAPI                            |
| Agents           | LangGraph, LangChain               |
| Document Parsing | Docling                            |
| Database         | Qdrant Vector DB                   |
| Vision Models    | PyTorch (image classification/seg) |
| Speech API       | Eleven Labs                        |
| Frontend         | HTML, CSS, JavaScript              |
| Deployment       | Docker                             |

## 🚀 Setup

### Docker

```bash
# Clone
git clone https://github.com/Anjaniputra15/Medico-assistant-.git
cd Medico-assistant-

# .env with API keys
# see README for variables needed

# Build & Run
docker build -t medical-assistant .
docker run -d -p 8000:8000 --env-file .env medical-assistant
```

### Manual

```bash
# Create virtual environment
python -m venv env
source env/bin/activate

# Install dependencies
pip install -r requirements.txt

# Add API keys to .env

# Run
python app.py
```

## 🤔 Usage

* Upload images for CV-based diagnosis
* Ask queries for RAG or web-retrieval answers
* Use voice commands via Eleven Labs
* Confirm responses through human validation

## 🤝 Contributions

PRs welcome. Open issues or ideas in the Issues tab.

## ⚖️ License

Apache-2.0 License

## 📅 Citation

```bibtex
@misc{Anjaniputra15_2025,
  Author = {Anjaniputra15},
  Title = {Multi Agent Medical Assistant},
  Year = {2025},
  Publisher = {GitHub},
  Howpublished = {\url{https://github.com/Anjaniputra15/Medico-assistant-}}
}
```

## 📩 Contact

For questions or collaborations, reach out via GitHub: [https://github.com/Anjaniputra15](https://github.com/Anjaniputra15)

<p align="right">
 <a href="#top"><b>🔝 Back to top</b></a>
</p>
