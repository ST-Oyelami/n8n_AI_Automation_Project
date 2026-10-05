# 🤖 n8n AI Automation Projects

> Five real-world AI automation projects built from scratch with [n8n](https://n8n.io), covering lead generation, social outreach, content summarization, RAG, and conversational assistants.

![n8n](https://img.shields.io/badge/built%20with-n8n-EA4B71?logo=n8n&logoColor=white)
![AI](https://img.shields.io/badge/focus-AI%20Automation-blueviolet)
![Projects](https://img.shields.io/badge/projects-5-success)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Projects](#-projects)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Repository Structure](#-repository-structure)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📖 Overview

This repository is a hands-on collection of end-to-end automation workflows built with n8n and modern AI tooling. Each project is self-contained, so you can import a single workflow, explore how it works, and adapt it to your own use case.

---

## 🚀 Projects

| # | Project | Description | Key Tools | Folder |
|---|---------|-------------|-----------|--------|
| 1 | **Lead Generation Automation** | Automatically finds and enriches leads | n8n, enrichment APIs | [`/01-lead-generation`](./01-lead-generation) |
| 2 | **LinkedIn Automation** | Automates LinkedIn outreach and engagement | n8n, LinkedIn | [`/02-linkedin-automation`](./02-linkedin-automation) |
| 3 | **AI-Powered News Summarizer** | Collects news and summarizes it using AI | n8n, LLM | [`/03-news-summarizer`](./03-news-summarizer) |
| 4 | **End-to-End RAG Project** | Complete RAG pipeline with vector search | n8n, Pinecone, Hugging Face | [`/04-rag-pipeline`](./04-rag-pipeline) |
| 5 | **Alexa-like Chat Assistant** | Conversational AI assistant with Guardrails | n8n, LLM, Guardrails | [`/05-chat-assistant`](./05-chat-assistant) |

### 1. Lead Generation Automation
Automatically discovers potential leads and enriches them with useful data, so you spend less time on manual research.

### 2. LinkedIn Automation
Streamlines LinkedIn outreach and engagement by automating repetitive tasks.

### 3. AI-Powered News Summarizer
Pulls in news content and uses AI to produce short, readable summaries.

### 4. End-to-End RAG Project
A full Retrieval-Augmented Generation pipeline: documents are embedded with Hugging Face models, stored in Pinecone, and retrieved to give accurate, context-aware answers.

### 5. Alexa-like Chat Assistant
A conversational AI assistant with Guardrails to keep responses safe, on-topic, and reliable.

---

## 🛠 Tech Stack

- **Automation:** [n8n](https://n8n.io)
- **Vector Database:** [Pinecone](https://www.pinecone.io)
- **Models & Embeddings:** [Hugging Face](https://huggingface.co)
- **AI / LLMs:** your preferred provider (e.g., OpenAI, Gemini)

---

## ⚡ Getting Started

### Prerequisites

- An n8n instance ([n8n Cloud](https://n8n.io/cloud) or [self-hosted](https://docs.n8n.io/hosting/))
- API keys for the services each project uses (Pinecone, Hugging Face, LLM provider, etc.)

### Setup

1. **Clone the repository**
```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
```
2. **Open the project folder** you want to try.
3. **Import the workflow** into n8n: *Workflows → Import from File* and select the `.json` file.
4. **Add your credentials** in n8n (API keys, OAuth connections).
5. **Activate or run** the workflow.

> ⚠️ Never commit API keys or credentials. Use n8n's credential manager or environment variables.

---

## 📂 Repository Structure

```
.
├── 01-lead-generation/
├── 02-linkedin-automation/
├── 03-news-summarizer/
├── 04-rag-pipeline/
├── 05-chat-assistant/
└── README.md
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to open an issue or submit a pull request.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for details.