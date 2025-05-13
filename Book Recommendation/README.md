# Book Recommendation System with Ollama 

## Overview
This project is a content-based book recommendation system built using FAISS for vector search and Ollama's nomic-embed-text model for generating semantic embeddings. The goal is to recommend similar books based on the textual metadata (title, author, description, etc.) of a given book.
Ollama is used to generate text embeddings for each book, I selected this embedding model because it is lightweight and optimized for efficiency, making it ideal for running on my laptop’s hardware. Unlike larger models (e.g., OpenAI embeddings) that requires payments and high-end GPUs.

## Tools Used
- Pandas/Numpy for data manipulation
- Ollama(nomic-embed-text) for text embedding generation
- FAISS for similarity search using vector embeddings
- Jupyter Notebook as the development environment

