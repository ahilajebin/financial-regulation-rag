# AI Compliance RAG System

This project builds an AI assistant that analyzes financial regulatory documents using:

- Retrieval Augmented Generation (RAG)
- SEC filings from EDGAR
- vector embeddings
- FastAPI microservice
- Docker deployment
- Google Cloud deployment

## Data Source

SEC EDGAR filings.

## Pipeline

1. Download filings
2. Extract risk sections
3. Chunk documents
4. Generate embeddings
5. Store in vector database
6. Query via RAG API