# 📄 Document Intelligence Agent — Chat with Multiple PDFs

An AI-powered **RAG-based PDF chatbot** that allows users to upload multiple PDF documents and ask questions about their content using **Google Gemini, LangChain, and FAISS**.

## 🚀 Features

* 📚 Upload and process multiple PDF files
* 📝 Extract text from PDF documents
* ✂️ Split documents into optimized text chunks
* 🧠 Generate embeddings using Gemini
* 🔎 Semantic search using FAISS
* 🤖 Answer questions using Gemini
* 💬 Maintains conversational chat history
* 📊 Displays PDF processing status
* ⚡ Interactive Streamlit interface

## 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **LangChain**
* **Google Gemini**
* **FAISS**
* **PyPDF2**
* **Gemini Embeddings**
* **RAG (Retrieval-Augmented Generation)**

## 🔄 Workflow

```text
Multiple PDFs
     ↓
Text Extraction
     ↓
Text Chunking
     ↓
Gemini Embeddings
     ↓
FAISS Vector Store
     ↓
User Question
     ↓
Similarity Search
     ↓
Relevant Context
     ↓
Gemini LLM
     ↓
AI Response
```

## ⚙️ Installation

```bash
git clone <YOUR_REPOSITORY_URL>
cd Document-Intelligence-Agent-Chat-With-Multiple-PDFs
pip install -r requirements.txt
```

Create a `.env` file:

```env
GOOGLE_API_KEY=your_api_key
```

## ▶️ Run

```bash
streamlit run app.py
```

## 📌 Key Concepts

* **RAG:** Retrieves relevant information from uploaded documents before generating an answer.
* **FAISS:** Performs similarity search over document embeddings.
* **Gemini:** Handles embeddings and natural-language responses.
* **LangChain:** Connects document processing, retrieval, prompting, and LLM components.

## 🔮 Future Improvements

* PDF source/page citations
* Document summarization
* Document comparison
* Support for DOCX and TXT
* Improved conversational memory
* Persistent vector database

