# 🤖 AI Resume Screener (RAG Architecture)

An automated candidate filtering and resume evaluation application using **Retrieval-Augmented Generation (RAG)**. This project leverages Google's Gemini 3.5 Flash model and a local FAISS vector database to semantically match resumes against job descriptions.

## 🚀 Features
- **PDF Extraction**: Instantly parses and reads resume layout data locally using PyMuPDF.
- **Dynamic Semantic Search**: Chunks documents and indexes them cleanly inside an in-memory FAISS Vector Database.
- **Context Extraction**: Queries vector storage dynamically for semantic overlaps between the candidate text and the job criteria.
- **Automated Grading Engine**: Leverages Gemini 3.5 Flash to extract a structured JSON scorecard highlighting missing skills, matched skills, and an overall fit score.

## 🛠️ Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git)
   cd YOUR_REPO_NAME