# 📄 LLM-RAG-PDF-Chatbot

An end-to-end **Retrieval-Augmented Generation (RAG)** application built using **LangChain**, **Google Gemini**, **ChromaDB**, and **Hugging Face Embeddings**.

The application enables users to upload a PDF document and ask natural language questions. Instead of relying only on the LLM's pretrained knowledge, it retrieves the most relevant information from the uploaded document and generates accurate, context-aware responses.

---

## 🚀 Project Overview

This project demonstrates how modern AI applications combine Large Language Models (LLMs) with Retrieval-Augmented Generation (RAG) to answer questions from private documents.

The application follows a complete RAG pipeline:

- Upload a PDF
- Extract document text
- Split the document into chunks
- Generate semantic embeddings
- Store embeddings inside a Chroma Vector Database
- Retrieve relevant chunks based on the user's query
- Pass the retrieved context to the LLM
- Generate a context-aware response

---

## 🏗️ RAG Pipeline

```text
                User Uploads PDF
                        │
                        ▼
                PyPDF Document Loader
                        │
                        ▼
            Recursive Text Splitter
                        │
                        ▼
        Hugging Face Embedding Model
                        │
                        ▼
           Chroma Vector Database
                        │
                        ▼
          Similarity Search Retriever
                        │
                        ▼
      Retrieved Context + User Question
                        │
                        ▼
            Google Gemini LLM
                        │
                        ▼
               Final AI Response
```

---

# 🛠️ Technologies Used

| Category | Technology |
|----------|------------|
| Programming Language | Python |
| LLM | Google Gemini |
| Framework | LangChain |
| RAG Pipeline | LangChain Retrieval |
| Embedding Model | Hugging Face (sentence-transformers/all-MiniLM-L6-v2) |
| Vector Database | ChromaDB |
| Document Loader | PyPDFLoader |
| Text Chunking | RecursiveCharacterTextSplitter |
| Semantic Search | Chroma Retriever |
| Environment | Google Colab |

---

# ✨ Features

- 📄 Upload PDF documents
- 🤖 Ask questions in natural language
- 🔍 Semantic document retrieval
- 🧠 Context-aware AI responses
- ⚡ Retrieval-Augmented Generation (RAG)
- 🗄️ Chroma Vector Database integration
- 🔗 LangChain orchestration
- ☁️ Cloud-based execution using Google Colab

---

# 🧠 AI Engineering Concepts Demonstrated

This project demonstrates the following AI engineering concepts:

- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- LangChain Framework
- Vector Databases
- Semantic Search
- Embeddings
- Document Chunking
- Prompt Engineering
- Context Retrieval
- Similarity Search
- LLM Orchestration
- Cloud-based Development
- End-to-End RAG Pipeline

---

# 📂 Project Structure

```
LLM-RAG-PDF-Chatbot/
│
├── LLM_RAG_PDF_Chatbot.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── screenshots/
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/LLM-RAG-PDF-Chatbot.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Generate a free Google Gemini API Key

```
https://aistudio.google.com/app/apikey
```

Run the notebook in Google Colab.

---

# 📸 Demo

### Upload PDF

(Add Screenshot)

---

### Ask Questions

(Add Screenshot)

---

### AI Generated Answer

(Add Screenshot)

---

# 🎯 Learning Outcomes

Through this project, I learned how to:

- Build an end-to-end Retrieval-Augmented Generation (RAG) application
- Integrate Large Language Models with LangChain
- Generate semantic embeddings
- Store and retrieve embeddings using ChromaDB
- Perform similarity search over private documents
- Build context-aware question answering systems
- Connect LLMs with external knowledge sources

---

# 🔮 Future Improvements

- Multiple PDF support
- Chat History
- Streamlit Web Application
- Source Citation
- Conversation Memory
- Hybrid Search
- FAISS Support
- Docker Deployment
- Cloud Deployment (AWS / Azure / GCP)

---

# 📌 Tech Stack

- Python
- LangChain
- Google Gemini
- Hugging Face
- ChromaDB
- PyPDF
- Google Colab

---

## ⭐ If you found this project helpful, consider giving it a star!
