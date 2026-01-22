# Giver RAG Bot – Retrieval-Augmented Generation Chatbot<br/>
Developed a Retrieval Augmented Generation (RAG) Bot with text from 'The Giver' by Lois Lowry.

## Overview
This project implements a Retrieval-Augmented Generation (RAG) chatbot designed to answer user questions using a custom document knowledge base rather than relying solely on a large language model’s pretrained knowledge. The goal of the project is to reduce hallucinations and improve response accuracy by grounding generated answers in retrieved, relevant source documents.

The bot retrieves relevant text chunks from a curated document corpus, then uses those retrieved passages as context when generating responses. This approach demonstrates how generative AI can be combined with information retrieval techniques to support more reliable, context-aware decision support systems.

## How It Works
The RAG pipeline follows four core steps:
1. **Document Ingestion & Chunking** – Source documents are broken into smaller text chunks for efficient retrieval.
2. **Embedding Generation** – Each chunk is converted into a vector embedding using an OpenAI embedding model.
3. **Similarity Search** – User queries are embedded and compared to stored document embeddings to retrieve the most relevant chunks.
4. **Response Generation** – Retrieved context is passed to a language model, which generates a grounded response based only on the supplied information.

## Tools & Technologies
- OpenAI API (embeddings and text generation)
- JavaScript / Google Apps Script
- Google Drive (document storage)
- Google Sheets (lightweight vector index)
- Retrieval-Augmented Generation (RAG) architecture

## Key Features
- Uses a custom knowledge base rather than general internet data
- Reduces hallucinations through retrieval-grounded responses
- Demonstrates end-to-end RAG pipeline implementation
- Designed for explainability and reproducibility

## Learning Outcomes
This project demonstrates practical applications of generative AI in a controlled, business-relevant context. It highlights skills in prompt engineering, embeddings, vector similarity search, and system design, as well as an understanding of how AI systems can be augmented with structured retrieval to improve reliability and decision support.

