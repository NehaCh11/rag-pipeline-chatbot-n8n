# RAG Pipeline & Chatbot (n8n Workflow)

This repository contains an **n8n workflow** for building a Retrieval-Augmented Generation (RAG) pipeline and chatbot.  
The workflow integrates **Google Drive, OpenAI, Pinecone, and n8n's LangChain nodes** to enable document-based Q&A.

---

## ✨ Features
- Watches a Google Drive folder for new files  
- Downloads documents automatically  
- Generates embeddings using OpenAI  
- Stores embeddings in Pinecone Vector DB  
- Provides chatbot interface via n8n Chat Trigger + AI Agent  
- Supports real-time question answering with context from documents  

---

## ⚙️ Requirements
- [n8n](https://n8n.io) (self-hosted or cloud)  
- Google Drive API credentials  
- OpenAI API key  
- Pinecone API key  
- Git (to sync workflows)  

---

## 🚀 Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/rag-pipeline-chatbot-n8n.git
