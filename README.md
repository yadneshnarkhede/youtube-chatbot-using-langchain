# 🎥 YouTube Transcript RAG Chatbot

## 📌 Project Overview

This project is a Retrieval-Augmented Generation (RAG) application built using LangChain. It allows users to ask questions about a YouTube video's transcript. The application retrieves the most relevant transcript chunks using semantic search and generates accurate answers with a Large Language Model (LLM).
*This is my First Gen AI project*

---

## 🚀 Features

* Extracts transcripts from YouTube videos
* Splits transcripts into manageable chunks
* Generates vector embeddings
* Stores embeddings using FAISS
* Retrieves the most relevant transcript sections
* Uses an LLM to answer questions based only on the retrieved context
* Prevents hallucinations by restricting responses to the transcript

---

## 🛠️ Tech Stack

* Python
* LangChain
* FAISS
* Hugging Face / OpenAI Embeddings
* OpenAI / Openrouter API
* YouTube Transcript API

---

## 📂 Project Workflow

YouTube Video URL
⬇️
Transcript Extraction
⬇️
Text Splitting
⬇️
Embedding Generation
⬇️
FAISS Vector Database
⬇️
Retriever
⬇️
Prompt Template
⬇️
LLM
⬇️
Answer

---

## 📦 Installation

```bash
git clone <repository-url>
cd <repository-name>

pip install -r requirements.txt
```

---

## ▶️ Usage

1. Provide a YouTube video ID or URL.
2. Extract the transcript.
3. Generate embeddings and store them in FAISS.
4. Ask questions related to the video.
5. Receive answers generated from the retrieved transcript.

---

## 📁 Project Structure

```
├── app.py
├── notebook.ipynb
├── README.md

```

---

## 🎯 Future Improvements

* Streamlit web interface
* Support for videos without captions using Whisper
* Chat history memory
* Multiple video support
* Source citation for retrieved chunks

---

## 👨‍💻 Author

**Yadnesh Narkhede**

B.Tech Data Science Student | Aspiring Data Engineer | AI & LLM Enthusiast
# youtube-chatbot-using-langchain

## 🙏 Acknowledgements

A special thanks to **CampusX** and **Nitish Sir** for creating high-quality educational content on AI, Machine Learning, and LangChain. Their clear explanations and practical teaching approach helped me understand the concepts behind Retrieval-Augmented Generation (RAG) and successfully build this project.

I sincerely appreciate their efforts in making advanced AI concepts accessible to students and developers.
