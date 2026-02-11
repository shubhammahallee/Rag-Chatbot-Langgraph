# Rag-Chatbot-Langgraph
RAG based chatbot using LangGraph, Ollama and FAISS with tool-calling workflow.
# RAG Chatbot using LangGraph + Ollama

This project implements a Retrieval-Augmented Generation (RAG) chatbot using:

- LangGraph (workflow orchestration)
- LangChain
- Ollama (Local LLM)
- FAISS (Vector Database)
- Streamlit (Frontend)

---

## 🚀 Features

- PDF document ingestion
- Text chunking
- Embeddings using Ollama
- FAISS vector store
- Tool-calling workflow via LangGraph
- Stateful conversation

---

## 🧠 Architecture

PDF → Chunking → Embeddings → FAISS → Retriever Tool → LangGraph → LLM → Response

---

## ⚙️ Installation

```bash
pip install -r requirements.txt

