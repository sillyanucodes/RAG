hi this is rag project.
# LangChain RAG Pipeline with Gemini, Chroma, and WebBaseLoader

This repository demonstrates how to build a **Retrieval-Augmented Generation (RAG) pipeline** using:
- **LangChain**
- **Gemini 1.5 Flash** (via `langchain_google_genai`)
- **Chroma Vector Store**
- **WebBaseLoader for web scraping**

to answer questions using **retrieved context from a web article.**

---

## Features

✅ Loads and scrapes web content  
✅ Splits content into chunks for vector storage  
✅ Generates embeddings using Gemini  
✅ Stores embeddings in Chroma DB  
✅ Uses retrieval for context-based question answering  
✅ Answers questions using Gemini in a concise manner

---

## Requirements

- Python 3.10+
- Install dependencies:

```bash
pip install langchain langchain-google-genai langchain-chroma langchain-community bs4
