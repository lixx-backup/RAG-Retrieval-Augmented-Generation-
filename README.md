# RAG-Retrieval-Augmented-Generation

# RAG Chatbot Project
A comprehensive implementation of Retrieval-Augmented Generation (RAG) techniques for building intelligent document-based chatbots. This project explores various text chunking strategies, vector databases, and hybrid retrieval methods to create an effective question-answering system.

## 🚀 Project Overview
This repository contains two main Jupyter notebooks that demonstrate different aspects of RAG system development:

- Chunking.ipynb - Text chunking strategies comparison
- RAG Chatbot.ipynb - Complete RAG pipeline implementation

### Text Chunking Strategies

- Overlap Chunking: Fixed-size chunks with character overlap
- Recursive Character Splitting: Structure-aware text splitting
- Semantic Chunking: Content-aware chunking using embeddings
- Hierarchical Chunking: Multi-level document organization

### RAG Pipeline Components

- Document Loading: PDF document processing with PyPDFLoader
- Vector Storage: ChromaDB cloud integration for embeddings
- Hybrid Retrieval: Combines semantic search with BM25 keyword search
- Advanced Reranking: ColBERT-based document reranking
- Response Generation: Google Gemini model integration

## 🔑 Required API Keys
Create a `.env` file in the project root with the following variables:

```env
# ChromaDB Configuration
CHROMADB_API_KEY=your_chromadb_api_key
CHROMADB_TENANT=your_tenant_id
CHROMADB_DATABASE=your_database_name

# Google AI (for Gemini model)
GOOGLE_API_KEY=your_google_api_key

