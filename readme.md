# RAG LangChain Example

This project demonstrates a practical implementation of Retrieval-Augmented
Generation (RAG) using LangChain in Python.

## Features

- PDF document loading and processing
- Text splitting and chunking
- Embeddings and vector store with Chroma and FAISS
- Metadata filtering
- Integration with Google Gemini and Ollama

## Setup

1. Install dependencies:

   ```bash
   uv pip install -r requirements.txt
   ```

2. Add your `.env` file with your API keys if needed.

## Usage

Open and run the `main.ipynb` notebook in VS Code or Jupyter.

## Notes

- For FAISS support, make sure to install `faiss-cpu` or `faiss-gpu`.
- For Google Gemini, you need a valid API key.
