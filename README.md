# RAGForge

A simple Retrieval-Augmented Generation (RAG) pipeline built with Python, LangChain, and ChromaDB.

## Features

- Custom text data ingestion
- Recursive text splitting
- Text embeddings
- ChromaDB vector storage
- Similarity search
- Context retrieval
- LLM-based answer generation

## RAG Pipeline

```text
Text Data
   ↓
Chunking
   ↓
Embeddings
   ↓
ChromaDB
   ↓
Similarity Search
   ↓
Relevant Context
   ↓
LLM
   ↓
Final Answer