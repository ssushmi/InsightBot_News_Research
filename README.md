# 📰 InsightBot – AI-Powered News Research Tool 📈

**InsightBot** is a full-stack AI research assistant that leverages **OpenAI LLMs** and **Retrieval-Augmented Generation (RAG)** to analyze news articles, summarize insights, and answer complex questions — all with source attribution.  

This project demonstrates **end-to-end AI/ML application development**, semantic search, and practical use of **LLMs in a business context**.

---

## 🚀 Key Highlights 

- **Built with production-ready tools**: Streamlit, LangChain, FAISS, OpenAI  
- **End-to-end workflow**: Ingest URLs → Chunk content → Generate embeddings → Build vector store → Query with LLM  
- **Real-world business relevance**: Can analyze financial news, tech updates, market reports, or research articles  
- **Demonstrates AI/ML expertise**: RAG, semantic search, embeddings, and source-backed answers  
- **Scalable & maintainable**: Vector store persistence with FAISS + modular LangChain pipeline  

---

## 💡 Business Use Case

Imagine a team needing **quick insights from multiple news sources**:

- **Input**: 3 URLs of financial or tech articles  
- **Processing**: AI reads, splits, embeds, and indexes content  
- **Output**: Accurate, concise answers with sources  
- **Impact**: Saves hours of research, supports decision-making, and reduces human error  

Example questions InsightBot can answer:

- “What are the key trends in AI mentioned across these articles?”  
- “Summarize the financial risks reported in these news sources.”  
- “What strategies did the CEOs discuss?”  

---


**Key Technologies**:

- **Frontend**: Streamlit (interactive dashboard)  
- **LLM Pipeline**: LangChain  
- **Embeddings**: OpenAI Embeddings  
- **Vector Database**: FAISS  
- **Document Loader**: UnstructuredURLLoader  
- **Environment Management**: python-dotenv  

---

## 📦 Quick Start

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/InsightBot.git
cd InsightBot
