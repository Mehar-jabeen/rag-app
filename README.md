# RAG PDF QA App

This is a Retrieval-Augmented Generation (RAG) application for querying PDF content (academic, legal, technical) using natural language.

## Features
- Upload and process complex PDFs
- Chunk and embed content (tables, code, citations preserved)
- Vector search + LLM-based QA
- Clean, minimal UI
- Works offline with FAISS + local models

## Requirements
- Python 3.8+
- `pip install -r requirements.txt`

## Run
```bash
python app.py
```

## Offline Mode
Set `OFFLINE=True` in `.env` and install `sentence-transformers`, `faiss-cpu`.
