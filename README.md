# LangChain-Based Multi-Agent Document Q&A System

## 🚀 Project Overview
This project implements an **automated document-based Q&A system** using **LangChain**. It allows users to upload documents, ask questions, and receive AI-generated answers with verification and validation mechanisms.

## 📌 Key Features
- **Document Processing**: Uses LangChain for document ingestion and text chunking.
- **Semantic Retrieval**: Retrieves relevant text chunks using ChromaDB.
- **Multi-Agent Pipeline**: Implements agents for question verification, retrieval, answer generation, and validation.
- **Human Feedback Loop**: Integrates manual review for answer accuracy.
- **Efficient Storage**: Stores processed documents and responses for future use.

## 🏗️ System Workflow
1. **Upload Document**: Users upload a PDF or text document.
2. **Question Verification**: Ensures the question is relevant.
3. **Retrieval Agent**: Extracts top relevant text chunks from ChromaDB.
4. **Answer Generation**: Generates an AI-based response using Llama2.
5. **Validation Agent**: Compares the response with the retrieved text.
6. **Human Feedback Agent**: Collects user feedback and refines responses if necessary.

## 🛠️ Tech Stack
- **LangChain**: Document processing and retrieval
- **ChromaDB**: Vector storage for document embeddings
- **Llama2**: Large language model for answer generation
- **SentenceTransformers**: For semantic similarity search
- **FastAPI / Streamlit**: Web interface (optional for deployment)

## 📦 Installation
```bash
pip install langchain chromadb sentence-transformers llama-cpp-python fastapi streamlit
```

## 🚀 Deployment
- **Local Deployment**: Run the script with a FastAPI/Streamlit UI.
- **Cloud Deployment**: Deploy using **Docker, AWS Lambda, or Google Cloud Run**.

## 🔮 Future Enhancements
- **Fine-tuning Llama2 on domain-specific data**
- **Integrating RAG models for improved retrieval**
- **Adding support for real-time document updates**

---

💡 **Contributions & Feedback** are welcome! Feel free to suggest improvements. 🚀

## Author

Developed by Mahankali N V R Pavan Sai Mohan 🚀
