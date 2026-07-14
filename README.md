# Semantic Movie Search with SBERT

This repository demonstrates semantic search over movie plot summaries using `sentence-transformers` with the SBERT model `all-MiniLM-L6-v2`.

## What it does

- downloads a movie dataset from Kaggle
- loads movie overviews and generates SBERT embeddings
- trains a KNN model on the embedded movie overviews
- performs semantic search for a text query
- visualizes the query and its nearest neighbors in 2D