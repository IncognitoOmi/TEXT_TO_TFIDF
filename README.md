# TF-IDF Sentence Representation

This project demonstrates how to convert textual data into numerical values using the **TF-IDF (Term Frequency-Inverse Document Frequency)** technique. Each sentence is represented as a single numerical score to simplify further analysis.

## 🚀 Features
- Converts text data into TF-IDF scores.
- Aggregates TF-IDF values into a single numerical column per sentence.
- Useful for tasks like text classification, clustering, and feature extraction.

## 📂 Files
- **`tfidf_example.py`**: Python script implementing TF-IDF conversion and aggregation.
- **Sample data**: A small corpus of sentences for demonstration purposes.

## 📖 How It Works
1. **TF-IDF Vectorization**: Converts each word into a numerical score based on its importance in the text corpus.
2. **Aggregation**: Combines word-level TF-IDF scores into a single sentence-level score by calculating the mean.
