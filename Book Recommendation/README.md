# Book Recommendation System 

## Overview
This project is a content-based book recommendation system built using FAISS for vector search and Ollama's nomic-embed-text model for generating semantic embeddings. The goal is to recommend similar books based on a given book.
Ollama is used to generate text embeddings for each book, I selected this embedding model because it is lightweight and optimized for efficiency, making it ideal for running on my laptop’s hardware. Unlike larger models (e.g., OpenAI embeddings) that requires payments and high-end GPUs.

## Tools Used
- Pandas and Numpy for data manipulation
- Ollama(nomic-embed-text) for text embedding generation
- FAISS for similarity search using vector embeddings
- Jupyter Notebook as the development environment

## Dataset
The dataset [7K Books](https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata) was obtained from kaggle. It contains 7,000 books with metadata such as:
- Title, Authors, Description (summary/blurb)
- Categories (genres/subjects)
- Published Year, Average Rating, Number of Pages
- Additional fields like publisher, language, etc.

## Results
The final output provides a list of book recommendations based on the most semantically similar content, offering personalized and meaningful suggestions to the user.

## Future Improvements
- Integrate a frontend interface using Streamlit or Flask.
- Expand the embedding model with multilingual or larger models (e.g., mxbai-embed-large).
