# Movie Recommendation System 🎬

## Overview
This project implements a **Content-Based Movie Recommendation System** using movie metadata such as genres, keywords, cast, and crew. The system applies **CountVectorizer** for feature extraction and **Cosine Similarity** to recommend similar movies.

## Features
- Data preprocessing with **pandas**
- Feature extraction using **CountVectorizer**
- Similarity computation with **Cosine Similarity**
- Simple and intuitive recommendation function
- Built using **Python** and **scikit-learn**

## How It Works
1. Load movie dataset (TMDB/CSV).
2. Clean and preprocess data (genres, cast, keywords, overview).
3. Convert text features into vectors using **CountVectorizer**.
4. Compute similarity between movies using **Cosine Similarity**.
5. Recommend top N similar movies based on input.

## Example Usage
```python
recommend("Inception")
