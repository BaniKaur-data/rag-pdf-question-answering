#  RAG PDF Question Answering System

![Python](https://img.shields.io/badge/Python-3.10-blue)
![LangChain](https://img.shields.io/badge/LangChain-Framework-green)
![FAISS](https://img.shields.io/badge/FAISS-VectorDB-orange)
![HuggingFace](https://img.shields.io/badge/Embeddings-HuggingFace-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

##  Overview

This project demonstrates a **Retrieval-Augmented Generation (RAG)** pipeline for extracting relevant information from unstructured PDF documents.

---

## Objective

To build a system that can understand documents and retrieve contextually relevant information based on user queries using vector similarity search.

---

## ⚙️ How It Works

1. 📥 Load PDF document  
2. ✂️ Split text into smaller chunks  
3. 🔢 Convert text into embeddings  
4. 🧠 Store embeddings in FAISS vector database  
5. 🔍 Retrieve relevant chunks based on query  

---

## 🛠 Tech Stack

- Python  
- LangChain  
- FAISS (Vector Database)  
- HuggingFace Embeddings  
- Google Colab  

---

## 💡 Key Concept

Instead of sending the entire document to a model, this system retrieves only the most relevant parts using **semantic search (vector similarity)**.

---

## 📌 Example Query

What is the Transformer architecture?

---

## 📈 Output

Returns the most relevant sections from the document related to the query.

---

## 🚀 Features

- Efficient document retrieval  
- Semantic search using embeddings  
- Scalable pipeline for large documents  
- Clean and modular workflow  

---



## 👩‍💻 Author

**Bani Kaur**


