
# Capstone Project: RAG System for Rare Disease Knowledge Synthesis

## Project Overview
This project aims to develop a Retrieval-Augmented Generation (RAG) system that synthesizes biomedical knowledge about rare diseases. It integrates structured data from Orphanet and unstructured data from PubMed to answer user queries, summarize disease characteristics, and provide traceable, evidence-based outputs using advanced NLP techniques.

## Core Objectives
* Retrieve and synthesize information about rare diseases.
* Integrate structured data (Orphanet) and unstructured data (PubMed).
* Generate accurate, explainable summaries using Large Language Models (LLMs).
* Provide a user-friendly interface for interaction.

## Minimum Viable Product (MVP) Focus
For the initial MVP, the system will concentrate on the following specific use cases for **Cystic Fibrosis (CF)** and **Huntington's Disease (HD)**:
1.  **Symptoms:** Answering queries like "What are the primary symptoms of [Disease Name]?"
2.  **Associated Genes:** Answering queries like "What genes are associated with [Disease Name]?"

## System Architecture Highlights
The system workflow involves:
1.  User query submission.
2.  Querying Orphanet and PubMed.
3.  Embedding and retrieving relevant documents.
4.  LLM generating a grounded summary.
5.  Displaying the answer, sources, and structured data via the UI.

## Key Technologies
* **Data Sources:** Orphanet (SPARQL), PubMed API
* **Embedding Models:** BioBERT, SciBERT
* **Vector Database:** FAISS, ChromaDB
* **Language Models (LLMs):** GPT-4, BioGPT
* **User Interface:** Streamlit, Gradio

## Folder Structure
-   `/data`: To store extracted and cleaned data from Orphanet and PubMed.
-   `/notebooks`: For initial data exploration, testing scripts, and experimentation.
-   `/src`: For your main Python code files (e.g., data pipeline, RAG logic, UI components).
-   `/ui`: For your Streamlit/Gradio application files.

---
*More detailed documentation and progress updates will be added as the project evolves.*
