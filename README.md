# 🤖 ASADI: Intelligent Administrative Assistant (RAG)

> An intelligent chatbot powered by **Django** and **RAG (Retrieval-Augmented Generation)** designed to query administrative and legal documents with precise context management.

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-Framework-green)](https://www.djangoproject.com/)
[![RAG](https://img.shields.io/badge/AI-RAG%20%26%20LLM-orange)]()

## 📄 Project Documentation
For a deep dive into the architecture, the algorithms used, and the detailed results, please refer to our technical report:

👉 **[Read the Full Technical Report (PDF)](./documentation/Rapport.pdf)**

---

## 🚀 About The Project
ASADI is a full-stack application that leverages **Large Language Models (LLMs)** and **ChromaDB** (Vector Database) to assist users in navigating complex documentation.

**Key Features:**
* **RAG Architecture:** Retreives relevant context from indexed documents to ground LLM answers (reducing hallucinations).
* **Workspace Filtering:** Users can create specific workspaces to restrict the AI's search scope to a subset of documents.
* **Dual Version Control:** Synchronized environment bridging legacy SVN workflows with modern GitHub collaboration features.

## 👥 Team & Credits
This project was developed as part of the Computer Science curriculum at **Université Paris Cité**.

- [**Ali Traore**](https://github.com/Taliii7)
- [**Valentin Ponoussamy**](https://github.com/Yvngval)
- [**Thomas Gourmelen**](https://github.com/thmsgo18)
- [**Abdel Malik Djaffer**](https://github.com/malik439)

---
## 🛠 Project Structure

The repository is organized as follows:

```text
ASADI/
├── ASADI/          # Main Django Application logic
├── documents/      # Document ingestion pipeline & storage
├── documentation/  # Technical reports and project deliverables 📄
├── prompts/        # LLM Prompt Engineering & Templates
├── scenario/       # Pedagogical scenario generation logic
├── utilisateurs/   # User management & Authentication
└── workspace/      # Context filtering & Workspace logic
