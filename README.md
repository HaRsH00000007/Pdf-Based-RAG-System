# Pdf-Based-RAG-System

📄 PDF-Based-RAG System with Chat History (LangChain + Groq + Streamlit)
This is a conversational Retrieval-Augmented Generation (RAG) application that allows users to upload PDF files and interact with their content via a chatbot interface. It maintains chat history for context-aware responses and uses LangChain, ChromaDB, and Groq's Gemma2-9b-It model to provide accurate, context-rich answers.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🔧 Features:

> 📂 Upload and parse multiple PDFs

> 🤖 Ask questions about the uploaded content

> 🧠 Maintains conversation history for contextual understanding

> ⚡ Uses Groq's LLM (Gemma2-9b-It) for fast and intelligent responses

> 🧠 Document embedding with HuggingFace + Chroma

> 🛠️ Built using LangChain + Streamlit
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🧪 Tech Stack:

Streamlit

LangChain

Groq API

HuggingFace Embeddings (all-MiniLM-L6-v2)

Chroma Vector Store

PyPDFLoader
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🚀 How to Use:

Clone the repo

Install requirements

Add your .env file with HF_TOKEN

Run streamlit run app.py

Upload PDFs and start chatting!
