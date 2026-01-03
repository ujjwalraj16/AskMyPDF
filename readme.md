# 📄 AskMyPDF – Chat with Multiple PDFs using LLMs

## 🔍 Overview
**AskMyPDF** is a smart web application that allows users to upload **one or multiple PDF documents** and interact with them using **natural language questions**.  
It extracts content from PDFs and provides **accurate, context-aware answers** using **Large Language Models (LLMs)**.

Built using **Python, Streamlit, LangChain**, with support for **OpenAI** and **Hugging Face** models.

---

## 🚀 Features
- 📚 Upload and chat with **multiple PDF files**
- 🧠 Context-aware question answering
- 🔍 Semantic search using vector embeddings
- ⚡ Interactive **Streamlit** interface
- 🔄 Supports **OpenAI** and **Hugging Face** LLMs
- 🧩 Modular and scalable code structure
- 🛡️ Session-based conversation handling

---

## 🛠️ Tech Stack

| Category | Technology |
|--------|------------|
| Language | Python |
| Frontend | Streamlit |
| LLM Framework | LangChain |
| Embeddings | OpenAI / Hugging Face |
| Vector Store | FAISS / Chroma |
| PDF Processing | PyPDF |
| Models | GPT, Hugging Face Transformers |

---

## 🧩 System Architecture

| Step | Description |
|-----|-------------|
| 1 | User uploads PDF documents |
| 2 | PDFs are split into smaller text chunks |
| 3 | Text chunks are converted into embeddings |
| 4 | Embeddings are stored in a vector database |
| 5 | User queries are matched semantically |
| 6 | LLM generates context-based answers |

---


---

## ⚙️ Installation & Setup

```bash
# **Create Virtual Environment**
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows

# **Install Dependencies**
pip install -r requirements.txt

# **Set Environment Variables**
# Create a `.env` file in the project root and add:
echo "OPENAI_API_KEY=your_openai_api_key" >> .env
echo "HUGGINGFACEHUB_API_TOKEN=your_huggingface_token" >> .env

#**Run the application**
streamlit run app.py

