# Building-GENAI-app-by-using-OpenAI


# 🧠 LangSmith-Powered LLM Retrieval System

This project demonstrates how to build a **retrieval-augmented generation (RAG)** system using **LangChain**, **OpenAI's GPT-4o**, and **LangSmith** for monitoring. It loads web content, transforms it into vector embeddings, stores it in a FAISS vector store, and enables querying via a retrieval chain.

---

## 🔧 Project Features

- Load and scrape documentation from a website
- Preprocess documents into manageable text chunks
- Generate vector embeddings using OpenAI
- Store and retrieve documents using FAISS
- Build a context-aware prompt system
- Retrieve and respond to queries using LLMs
- Monitor and trace execution with LangSmith

---

## 📦 Requirements

- Python 3.8+
- API Keys for:
  - OpenAI
  - LangSmith

Install dependencies:
```bash
pip install langchain openai faiss-cpu python-dotenv
