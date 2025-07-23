# 🧠 InsightAI – Chat with Your PDFs using GenAI

InsightAI is a GenAI-powered chatbot that lets you **ask questions about any PDF** — like notes, manuals, resumes, or syllabi — and get intelligent answers grounded in the document content.

Built with **LangChain**, **FAISS**, **Sentence Transformers**, and **OpenAI**, this project demonstrates a complete **Retrieval-Augmented Generation (RAG)** pipeline, deployed using **Streamlit Cloud**, entirely on free tiers.

---

## 🚀 Features

- 📄 Upload any PDF (syllabus, resume, research paper, etc.)
- 🔍 Extracts and indexes content using vector embeddings (FAISS)
- 🤖 Answers your questions with GPT (OpenAI)
- 🧠 Built with LangChain + Sentence Transformers
- 🌐 Deployable on Streamlit Cloud (no credit card needed)

---

## 📦 Tech Stack

| Component         | Tool/Library                        |
|------------------|-------------------------------------|
| Embeddings        | `sentence-transformers` (MiniLM)    |
| Vector Store      | `FAISS` (in-memory, local)          |
| LLM               | `OpenAI GPT-3.5`                    |
| Framework         | `LangChain`                         |
| UI                | `Streamlit`                         |
| Deployment        | `Streamlit Cloud`                   |

