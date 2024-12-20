# LiveNLP
A collection of learning programs for NLP
# Word2Vec Model Training and Word Similarity Check

This program demonstrates how to train a custom Word2Vec model on a dataset, reduce the dimensionality of word embeddings using PCA, and check for word similarities. It is designed as a class assignment to explore the basics of natural language processing and machine learning.

## Features

- **Dataset Integration:** Load and preprocess a dataset of your choice.
- **Word2Vec Training:** Train a custom Word2Vec model to generate word embeddings.
- **Dimensionality Reduction:** Apply Principal Component Analysis (PCA) to reduce embeddings to 2 dimensions for visualization and analysis.
- **Word Similarity:** Evaluate the similarity between words using the trained Word2Vec model.

## Prerequisites

- Python 3.x
- Required libraries: `gensim`, `numpy`, `scikit-learn`, `matplotlib` (if visualization is needed).

## How to Run

1. **Prepare the Dataset:**
   - Choose any text dataset (e.g., news articles, movie reviews, etc.).
   - Ensure it is in a clean and usable format (plain text or tokenized sentences).

2. **Install Dependencies:**
   ```bash
   pip install gensim numpy scikit-learn matplotlib
