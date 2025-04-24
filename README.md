# 🧠 Conversational RAG with PDF Uploads & Chat History

A simple Streamlit app that allows you to upload PDFs and have context-aware conversations with them using Langchain, HuggingFace Embeddings, ChromaDB, and Groq LLM.

---

## 🚀 Features

- Upload multiple PDFs
- Ask questions based on content
- Maintains chat history per session
- Uses Groq's `Gemma-2-9b-it` model
- HuggingFace embeddings + Chroma for vector search

---

## 🛠️ Installation

```bash
git clone https://github.com/niranjana14/LLM-Application-LCEL.git
cd LLM-Application-LCEL
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
