# RAG Project

This is a Retrieval-Augmented Generation (RAG) system built with [LangChain](https://www.langchain.com/), [ChromaDB](https://www.trychroma.com/), and multiple LLM providers (OpenAI, Anthropic, Google GenAI, LLaMA).  
It allows you to load documents, store embeddings in a vector database, and query them using LLMs.

---

## Features
- Ingest documents into **ChromaDB** with embeddings.
- Query your database using different **LLM providers**.
- Modular design with separate notebooks for **database filling** and **querying**.
- Support for **PDF ingestion** via `pypdf`.
- Easily switch between **OpenAI, Anthropic, Google, and LLaMA** models.

---

## 📂 Project Structure
rag-project/
├── Ask.ipynb          # Notebook to query the vector database (RAG querying)
├── Fill_db.ipynb      # Notebook to ingest documents into ChromaDB
├── requirements.txt   # Python dependencies
├── .gitignore         # Git ignore rules
├── .env.example       # Example environment variables
└── README.md          

