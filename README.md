# 🚀 Enterprise GenAI Pipeline

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Framework-green.svg)](https://fastapi.tiangolo.com/)
[![LangChain](https://img.shields.io/badge/LangChain-LLM-orange.svg)](https://www.langchain.com/)
[![RAG](https://img.shields.io/badge/RAG-Enabled-red.svg)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)]()

---

## 📌 Overview

Enterprise GenAI Pipeline is a modular AI application framework designed for enterprise-scale document intelligence, Retrieval-Augmented Generation (RAG), and Large Language Model (LLM) workflows.

The system integrates modern AI technologies including FastAPI, LangChain, vector databases, and local/cloud LLMs to provide scalable, secure, and production-ready AI services.

---

## ✨ Features

- RESTful APIs using FastAPI
- Retrieval-Augmented Generation (RAG)
- LangChain orchestration
- Vector database integration
- Local LLM support (Ollama)
- OpenAI-compatible API support
- Document ingestion
- PDF processing
- Semantic search
- Embedding generation
- Enterprise-ready modular architecture
- Configurable AI pipelines
- Logging and monitoring support

---

# 🏗 Architecture

```
                  Enterprise Documents
                           │
                           ▼
                  Document Loader
                           │
                           ▼
                  Text Chunking
                           │
                           ▼
                  Embedding Model
                           │
                           ▼
                  Vector Database
                           │
                           ▼
                   LangChain Pipeline
                           │
          ┌────────────────┴───────────────┐
          │                                │
          ▼                                ▼
      Local LLM                      Cloud LLM
      (Ollama)                    (OpenAI Compatible)
          │                                │
          └──────────────┬─────────────────┘
                         ▼
                  FastAPI REST API
                         ▼
                    Client Application
```

---

# 📂 Project Structure

```
Enterprise-GenAI-Pipeline
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── src
│   ├── embeddings.py
│   ├── retriever.py
│   ├── llm.py
│   ├── vectorstore.py
│   ├── document_loader.py
│   └── utils.py
│
├── assets
│   ├── architecture.png
│   └── demo.gif
│
└── sample_documents
```

---

# ⚙️ Technology Stack

- Python
- FastAPI
- LangChain
- ChromaDB
- Ollama
- OpenAI API
- Sentence Transformers
- Hugging Face
- FAISS (optional)
- Streamlit
- Pydantic
- Uvicorn

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/vamshi-krishna-challa/Enterprise-GenAI-Pipeline.git

cd Enterprise-GenAI-Pipeline
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run FastAPI

```bash
uvicorn app:app --reload
```

---

# ▶️ Example Workflow

1. Upload enterprise documents

2. Generate embeddings

3. Store vectors

4. Retrieve relevant context

5. Send context to LLM

6. Generate grounded responses

---

# 📊 Example Use Cases

- Enterprise Knowledge Assistant
- Internal Document Search
- Policy Question Answering
- Technical Documentation Assistant
- HR Assistant
- IT Helpdesk Assistant
- Compliance Assistant
- Contract Intelligence
- Manufacturing Documentation
- Customer Support AI

---

# 📈 Future Improvements

- Multi-agent workflows
- LangGraph integration
- CrewAI orchestration
- Multi-modal document understanding
- Hybrid search
- PostgreSQL support
- Kubernetes deployment
- Docker support
- Authentication & Authorization
- MLflow integration
- Observability dashboard

---

# 📸 Screenshots

## Home

_Add screenshot here_

## API Documentation

_Add screenshot here_

## Response Example

_Add screenshot here_

---

# 🤝 Contributing

Contributions are welcome.

Please open an issue before submitting a pull request.

---

# 📄 License

MIT License

---

# 👨‍💻 Author

**Vamshi Krishna Challa**

Ph.D. Student  
Computational Analysis and Modeling  
Louisiana Tech University

Research Interests

- Artificial Intelligence
- Large Language Models
- Retrieval-Augmented Generation
- Agentic AI
- Industrial AI
- Time-Series Forecasting
- Deep Learning
- Machine Learning

GitHub

https://github.com/vamshi-krishna-challa

LinkedIn

https://www.linkedin.com/in/vamshikrishnachalla98b306292/

---

⭐ If you find this repository useful, please consider starring it.
