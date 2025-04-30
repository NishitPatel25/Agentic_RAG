# 🤖 Agentic RAG

A **Streamlit** app that powers **Retrieval-Augmented Generation (RAG)** using **Gemini Flash**, **Agno AI Agents**, and **ChromaDB** for persistent document indexing. It supports PDF and Web-based ingestion and intelligently routes queries through document search or web search agents.

---

## 🚀 Features

- 🔎 **Gemini Embeddings** for vectorization of text
- 📄 Upload **PDF documents**
- 🌐 Fetch and process **web URLs**
- 📚 Store and search via **ChromaDB**
- 🧠 Use of **Gemini Flash Agents** for thinking, rewriting, and answering
- 🔄 Smart routing between RAG and live Web Search using **ExaTools**
- 🖼️ **Streamlit UI** with chat-like experience

---

## 🧰 Requirements

- Python 3.9 or above
- A Google API key (for Gemini and Embeddings)
- Exa API key (optional for Web Search Agent)

---

## 📦 Installation

```bash
git clone https://github.com/NishitPatel25/Agentic_RAG.git
cd Agentic_RAG

# Set up virtual environment (Windows)
python -m venv venv
venv\Scripts\activate

# Or on macOS/Linux
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
