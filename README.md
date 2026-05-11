# RAGDoc Assistant

![Python](https://img.shields.io/badge/Python-3.10-blue)
![LangChain](https://img.shields.io/badge/LangChain-Framework-green)
![FAISS](https://img.shields.io/badge/FAISS-VectorDB-orange)
![Groq](https://img.shields.io/badge/Groq-LLM-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

# Overview

RAGDoc Assistant is a Retrieval-Augmented Generation (RAG) system designed for intelligent question answering over PDF documents using Large Language Models (LLMs).

The application retrieves contextually relevant document chunks using semantic vector search and generates grounded responses using a Groq-hosted Llama 3.3 model.

The system also includes:
- Source citations with page references
- Prompt-based guardrails to reduce hallucinations
- Context-grounded answer generation
- Semantic document retrieval using FAISS vector database

---

# Features

- PDF-based Question Answering
- Retrieval-Augmented Generation (RAG)
- Semantic Search using Embeddings
- LLM-Powered Response Generation
- Source Citations with Page Numbers
- Prompt-Based Hallucination Guardrails
- FAISS Vector Database Integration
- Groq API + Llama 3.3 Integration

---

# Tech Stack

- Python
- LangChain
- FAISS
- HuggingFace Embeddings
- Groq API
- Llama 3.3 70B Versatile
- PyPDFLoader
- Google Colab

---

# System Architecture

```text
PDF Document
      ↓
Text Chunking
      ↓
Vector Embeddings
      ↓
FAISS Vector Database
      ↓
Semantic Retrieval
      ↓
LLM (Groq-hosted Llama 3.3)
      ↓
Grounded Answer + Citations
```

---

# How It Works

1. Upload PDF document
2. Split document into smaller chunks
3. Convert chunks into vector embeddings
4. Store embeddings inside FAISS vector database
5. Retrieve relevant chunks using semantic similarity
6. Pass retrieved context to the LLM
7. Generate grounded response with citations

---

# Guardrails

The system uses prompt-based guardrails to reduce hallucinations.

If the answer is not present in the retrieved context, the assistant refuses the query instead of generating unsupported information.

Example:

```python
"I could not find the answer in the document."
```

---

# Example Query

```text
What is the Transformer architecture?
```

# Example Output

- Context-aware AI-generated answer
- Retrieved source information
- Page citations
- Hallucination-safe responses

---

# Future Improvements

- Streamlit UI
- Multi-PDF support
- Conversational RAG
- LangSmith observability
- Advanced guardrails

---

# Author

Bani Kaur
