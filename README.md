# 🍕 Local AI Agent – Restaurant Review Q&A

A simple RAG (Retrieval-Augmented Generation) project built with **LangChain** and **Ollama**, using local models to answer questions about restaurant reviews.

---

## 🚀 Features
- Uses **Llama3.2** for local question answering  
- Embeds reviews using **mxbai-embed-large**  
- Stores vectors with **Chroma**  
- Works fully **offline**

---

## 🧠 How It Works
1. `vector.py` reads restaurant reviews from a CSV file  
2. Creates embeddings and saves them in a local vector database  
3. `main.py` loads Llama 3.2 and lets you ask questions interactively  

