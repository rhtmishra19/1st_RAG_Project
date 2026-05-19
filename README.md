# 1st RAG Project

An AI-powered Retrieval-Augmented Generation (RAG) chatbot built using Python and LangChain that allows users to upload PDF documents and ask context-aware questions based on the uploaded content.

---

# Project Overview

This project implements a complete RAG (Retrieval-Augmented Generation) pipeline where:

1. PDF documents are uploaded
2. Documents are loaded and split into chunks
3. Text chunks are converted into vector embeddings
4. Embeddings are stored in a vector database
5. User questions are matched with relevant document chunks
6. Context is sent to the LLM
7. AI generates accurate answers from the uploaded documents

---

# RAG Architecture Flow

## Document Processing Pipeline

```text id="e2hy4w"
PDF Upload
    ↓
Document Loader
    ↓
Text Splitter
    ↓
Chunk Creation
    ↓
Vector Embeddings
    ↓
Vector Database
```

## Question Answering Pipeline

```text id="tjlwmq"
User Question
    ↓
Query Embedding
    ↓
Similarity Search
    ↓
Relevant Chunk Retrieval
    ↓
Context Building
    ↓
LLM Response Generation
```

---

# Features

* Upload and process multiple PDF documents
* Automatic document chunking
* Semantic similarity search
* Vector embedding generation
* Context-aware AI responses
* LangChain integration
* Jupyter Notebook experimentation
* Environment variable support using `.env`

---

# Tech Stack

## Programming Language

* Python

## Libraries & Frameworks

* LangChain
* LangChain Community
* PyPDF
* Python Dotenv

## AI / NLP

* Vector Embeddings
* Retrieval-Augmented Generation (RAG)

## Tools

* VS Code
* Git & GitHub
* Jupyter Notebook
* UV Package Manager

---

# Project Structure

```bash id="mjlwm3"
1st_RAG_Project/
│
├── All_pdf/                 # PDF documents
├── project.ipynb            # Main notebook
├── main.py                  # Python script
├── .env                     # Environment variables
├── .gitignore
├── pyproject.toml
├── uv.lock
├── requirements.txt
└── README.md
```

---

# Installation

## 1. Clone Repository

```bash id="3dbj5u"
git clone https://github.com/rhtmishra19/1st_RAG_Project.git
```

## 2. Move Into Project Directory

```bash id="i1c3z8"
cd 1st_RAG_Project
```

---

# Setup Using UV

## Create Virtual Environment

```bash id="ghjlwm"
uv venv
```

## Activate Environment

### Windows

```bash id="n93xlk"
.venv\Scripts\activate
```

---

# Install Dependencies

```bash id="4vjlwm"
uv sync
```

OR

```bash id="0zwhhu"
uv pip install -r requirements.txt
```

---

# Environment Variables

Create a `.env` file:

```env id="fjlwm9"
API_KEY=your_api_key_here
```

---

# Run Project

## Run Python File

```bash id="efz19z"
uv run main.py
```

## Run Jupyter Notebook

```bash id="tdjlwm"
jupyter notebook
```

---

# Example Workflow

```python id="kgvjlwm"
# Load PDFs
# Split text into chunks
# Create embeddings
# Store vectors
# Ask questions
# Generate AI answers
```

---

# Learning Outcomes

This project helped in understanding:

* RAG Architecture
* Vector Databases
* Embeddings
* Semantic Search
* LangChain Pipelines
* Document Loaders
* Prompt Engineering
* AI Chatbot Development

---

# Future Improvements

* Add Streamlit UI
* Add chat history memory
* Add support for DOCX/TXT files
* Deploy on cloud platform
* Add multiple vector database options
* Add authentication system

---

# Author

Rohit Mishra

GitHub Repository:

[1st_RAG_Project Repository](https://github.com/rhtmishra19/1st_RAG_Project?utm_source=chatgpt.com)

---
