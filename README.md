# 📚 Semantic Book Recommender

A lightweight Gradio app that recommends books using **semantic search** over descriptions, with optional **category** and **emotion** filtering.  
Built with **LangChain + Chroma** for retrieval and **OpenAI embeddings** (swap to local models if you prefer).

---

## ✨ Features
- 🔎 **Semantic search** over book descriptions
- 🗂️ **Category filter** (Fiction, Nonfiction, Children’s, …)
- 😊 **Emotion re-ranking** (joy, sadness, fear, anger, surprise)
- 🖼️ **Thumbnail gallery** with captions (title, authors, teaser)
- 🧰 **Data pipeline** for dataset prep, zero-shot classification & emotion scoring
- 🐳 **Docker support** for easy deployment

---

## 🔧 Tech Stack
- Python, Pandas, NumPy  
- Gradio (UI)  
- LangChain, Chroma (vector DB)  
- OpenAI Embeddings (default; can swap to `sentence-transformers`)  
- Transformers (zero-shot category & emotion classifier)  
- KaggleHub (dataset download)  

---

## 🗂️ Project Structure
