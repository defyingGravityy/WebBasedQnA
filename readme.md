#  Web-based PDF Loader with LangChain + Groq

This notebook demonstrates a minimal RAG (Retrieval-Augmented Generation) workflow using **LangChain** and **Groq's LLaMA3** models. It showcases document upload, chunking, embedding, and context-aware question answering—all from within a Jupyter Notebook.

---

##  What It Does

- Load a text from a web URL
- Use LangChain's `WebBaseLoader` to parse content
- Split text into chunks using `RecursiveCharacterTextSplitter`
- Embed chunks using HuggingFace 
- Store embeddings in Chroma vector store
- Use Groq’s LLaMA3 to answer natural language questions based on retrieved context

---

##  Tools & Libraries

| Purpose               | Library/Service        |
|------------------------|------------------------|
| Document Loading       | LangChain Loaders      |
| Chunking               | LangChain TextSplitter |
| Embeddings             | HuggingFace            |
| Vector Store           | Chroma                 |
| LLM                    | LLaMA3 via (Groq-API)  |
| Notebook Interface     | Jupyter                |



