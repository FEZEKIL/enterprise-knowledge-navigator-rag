📘 Enterprise Knowledge Navigator · Agentic RAG

Multi-agent Retrieval-Augmented Generation system for enterprise document intelligence with hybrid search (FAISS + BM25) and metadata-aware retrieval.

🚀 Overview

Enterprise Knowledge Navigator is a hybrid AI retrieval system designed to search and reason over large-scale enterprise document collections such as:

Policy documents
Technical manuals
Medical and compliance PDFs
Organizational guidelines

It combines:

Dense vector search (FAISS)
Sparse keyword search (BM25)
LLM reasoning layer (IBM Watsonx / LLaMA 3)
Metadata tagging agent for structured retrieval
🧠 System Architecture
PDF ingestion from cloud storage (IBM COS)
Text extraction using PyPDF
Sentence-level chunking
Embedding generation (SentenceTransformers)
FAISS vector index
BM25 lexical index
Hybrid retrieval engine
LLM-powered answer synthesis
⚙️ Tech Stack
Python
IBM Watsonx AI (LLaMA 3)
FAISS (Vector Search)
BM25Okapi (Keyword Search)
SentenceTransformers
PyPDF
NumPy / Pandas
IBM Cloud Object Storage
🧩 Key Features
Hybrid search (semantic + lexical)
Scalable chunk-based document processing
Metadata tagging agent (department / doc type)
Context-aware LLM response generation
Production-style RAG pipeline design
📊 Example Use Case

Query:

What are symptoms of hypertensive emergency?

System Response:

Retrieves relevant medical chunks
Combines FAISS + BM25 ranking
Sends context to LLM
Generates grounded clinical answer
🏗️ Future Improvements (Phase 2)
Cross-encoder reranker
Multi-agent orchestration layer
FastAPI deployment
Authentication layer
UI dashboard (React / Streamlit)
👨‍💻 Author

Fezekile Gxalaba
AI/ML Engineer · Generative AI · RAG Systems · IBM Certified

⭐ Status

✔ Phase 1 Completed
🚧 Phase 2: Enterprise Production Layer (In Progress)
