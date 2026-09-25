## A simple Retrieval-Augmented Generation (RAG) pipeline built with Python, LangChain, and ChromaDB.

## Features

- Custom text data ingestion
- Recursive text splitting
- Text embeddings
- ChromaDB vector storage
- Similarity search
- Context retrieval
- LLM-based answer generation

## Project Structure

```text
RAGForge/
├── notebooks/
│   └── 1.0_RAG_With_Own_Text.ipynb   # Step-by-step RAG tutorial
├── .env.example                       # Environment variables template
├── .gitignore
├── pyproject.toml                     # Dependencies & environment configuration
└── README.md
```

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
```

## Getting Started

1. **Install dependencies:**
   ```bash
   uv sync
   ```

2. **Configure environment:**
   ```bash
   cp .env.example .env
   # Add your GROQ_API_KEY to .env
   ```

3. **Open the notebooks:**
   Open any notebook in `notebooks/` using your preferred Jupyter editor or IDE (select the project `.venv` kernel).
