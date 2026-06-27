# 📄 LLM RAG PDF Chatbot

A Retrieval-Augmented Generation (RAG) chatbot that allows users to upload a PDF and ask questions about its content.

## 🚀 Features

- Upload PDF documents
- Semantic search using embeddings
- Vector storage with ChromaDB
- Question answering using Google Gemini
- Retrieval-Augmented Generation (RAG)

## 🛠️ Tech Stack

- Python
- LangChain
- Google Gemini
- Hugging Face Embeddings
- ChromaDB
- PyPDF

## 📂 Workflow

PDF
↓
PyPDFLoader
↓
Text Splitter
↓
Embeddings
↓
ChromaDB
↓
Retriever
↓
Gemini
↓
Answer

## ▶️ How to Run

1. Install dependencies

```bash
pip install -r requirements.txt
```

2. Add your Gemini API key.

3. Run the notebook in Google Colab.

4. Upload any PDF.

5. Ask questions.

## 📸 Demo

(Add screenshots here)

## 📌 Future Improvements

- Streamlit UI
- Multiple PDF support
- Chat history
- Source citations
- Conversation memory
