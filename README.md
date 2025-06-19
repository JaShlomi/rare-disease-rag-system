# rare-disease-rag-system
RAG system synthesizing rare disease knowledge from Orphanet &amp; PubMed.
# Capstone Project: RAG System for Rare Disease Knowledge Synthesis

## Project Overview
[cite_start]This project aims to develop a Retrieval-Augmented Generation (RAG) system that synthesizes biomedical knowledge about rare diseases. [cite_start]It integrates structured data from Orphanet and unstructured data from PubMed to answer user queries, summarize disease characteristics, and provide traceable, evidence-based outputs.

## Core Objectives
* [cite_start]Retrieve and synthesize information about rare diseases.
* [cite_start]Integrate structured data (Orphanet) and unstructured data (PubMed).
* [cite_start]Generate accurate, explainable summaries using Large Language Models (LLMs).
* [cite_start]Provide a user-friendly interface for interaction.

## Minimum Viable Product (MVP) Focus
For the initial MVP, the system will concentrate on the following specific use cases for **Cystic Fibrosis (CF)** and **Huntington's Disease (HD)**:
1.  **Symptoms:** Answering queries like "What are the primary symptoms of [Disease Name]?"
2.  **Associated Genes:** Answering queries like "What genes are associated with [Disease Name]?"

## System Architecture Highlights
The system workflow involves:
1.  [cite_start]User query submission.
2.  [cite_start]Querying Orphanet and PubMed.
3.  [cite_start]Embedding and retrieving relevant documents.
4.  [cite_start]LLM generating a grounded summary.
5.  [cite_start]Displaying the answer, sources, and structured data via the UI.

## Key Technologies
* [cite_start]**Data Sources:** Orphanet (SPARQL), PubMed API 
* [cite_start]**Embedding Models:** BioBERT, SciBERT 
* [cite_start]**Vector Database:** FAISS, ChromaDB 
* [cite_start]**Language Models (LLMs):** GPT-4, BioGPT 
* [cite_start]**User Interface:** Streamlit, Gradio 

## Folder Structure
-   `/data`: To store extracted and cleaned data from Orphanet and PubMed.
-   `/notebooks`: For initial data exploration, testing scripts, and experimentation.
-   `/src`: For your main Python code files (e.g., data pipeline, RAG logic, UI components).
-   `/ui`: For your Streamlit/Gradio application files.

---
*More detailed documentation and progress updates will be added as the project evolves.*
