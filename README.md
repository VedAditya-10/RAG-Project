# RAG Project

This is a Retrieval-Augmented Generation (RAG) system built with [LangChain](https://www.langchain.com/), [ChromaDB](https://www.trychroma.com/), and multiple LLM providers (OpenAI, Anthropic, Google GenAI, LLaMA).  
I have loaded the syllabus of my college in the data folder.As per the usecase and purpose just modify the knowledge base and queries.
You can load documents, store embeddings in a vector database,ChromaDB in this case. and query them using LLMs.
I have loaded the syllabus of my college in the data folder.

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

