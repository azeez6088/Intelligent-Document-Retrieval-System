# 🧠 Intelligent Document Retrieval System

**Built with LangChain + Vector Databases**

## 🔍 Overview

The Intelligent Document Retrieval System leverages **LangChain** and **Vector Databases** (FAISS) to provide **semantic search** and **context-aware document querying**. This system transforms unstructured documents into embeddings, stores them efficiently, and enables natural language-based retrieval using a large language model (LLM).

---

## 🚀 Features

* ✅ **Semantic Search** using vector similarity
* ✅ **Document Chunking** with configurable chunk size and overlap
* ✅ **Embeddings Generation** via OpenAI
* ✅ **LangChain Integration** for seamless LLM orchestration
* ✅ **Support for Multiple Vector Stores** via FAISS
* ✅ **Custom Prompt Templates** for better query interpretation
* ✅ **Modular Design** for easy extensibility

---

## 🛠️ Tech Stack

* [LangChain](https://www.langchain.com/)
* Vector DB: [FAISS](https://github.com/facebookresearch/faiss) 
* Embedding Models: OpenAI 
* LLM: OpenAI GPT 
* GUI: Streamlit for UI, FastAPI for backend integration

---

## 📂 Project Structure

```
intelligent-doc-retrieval/
│   ├── .gitignore          
│   ├── .env.example        # Tracked on Git
│   ├── .env                # Store secret keys
│   ├── requirements.txt    # List of requirements
|   ├── app.py              # Main application pipeline
│   └── README.md

```

## 🔧 Configuration

Set your environment variables or `.env` file:

```env
OPENAI_API_KEY=your_openai_key
VECTOR_DB_TYPE=faiss  # Options: faiss
```

---

## 🧪 Usage

### 1. Prepare Documents

Prepare your `.pdf` files.

### 2. Run the Pipeline

```bash
streamlit run app.py
```

### 3. Ask Questions!

```bash
> What are the key clauses in the agreement?
```

The system returns the most relevant document snippets with answers synthesized using LLM.

---

## 🧠 Example Use Cases

* Legal document search
* Academic paper retrieval
* Internal knowledge base Q\&A
* Customer support documentation

---

## 📈 Future Improvements

* UI with Streamlit or React
* RAG-based summarization
* Support for multilingual documents
* Document ingestion via API


---

## 📜 License

This project is licensed under the MIT License. See `LICENSE` for details.

---
