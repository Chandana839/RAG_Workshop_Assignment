# RAG_Workshop_Assignment
“Retrieval-Augmented Generation project on Machine Learning PDFs.”

# 🎓 RAG Workshop Assignment – Chandana R

## 🧠 Objective
To build a Retrieval-Augmented Generation (RAG) system capable of answering questions about Machine Learning using uploaded PDF research materials.

## 🧩 Models Used
- **LLM:** phi3:mini via Ollama
- **Embeddings:** sentence-transformers/all-MiniLM-L6-v2
- **Vector Store:** ChromaDB
- **Retriever:** Maximum Marginal Relevance (MMR)

## 📚 Data
Five Machine Learning PDFs covering topics such as supervised learning, reinforcement learning, and bias-variance tradeoff.

## ⚙️ Workflow
1. PDF Loading and Text Extraction  
2. Text Chunking (chunk size 1200, overlap 150)  
3. Embedding Creation using MiniLM  
4. Vector Storage using Chroma  
5. Retrieval (MMR strategy)  
6. LLM Integration via Ollama (phi3:mini)  
7. Answer Generation and Validation  

## 💬 Example Question
**Q:** What is supervised learning?  
**A:** “Supervised learning is a method of training models using labeled data…”  
(Source: ML_1.pdf)

## 🧾 Files Included
- `CHANDANA_R_RAG_WORKSHOP.ipynb` — Main Jupyter Notebook  
- `ML_1.pdf` → `ML_5.pdf` — Data sources  

## 🔗 Notes
All models run locally using Ollama. If any file exceeded GitHub’s 100 MB limit, it is shared separately through cloud storage.
