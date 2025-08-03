# Automated News Summarizer

## Overview
This project is an automated extractive text summarizer built using Python and NLP techniques. It reads full-length news articles and generates concise summaries by selecting the most relevant sentences using **TF-IDF vectorization** and **cosine similarity**.

## Features
- Cleans and tokenizes raw article text using `spaCy`, `nltk`, and regex
- Filters out short or noisy sentences
- Converts sentence vectors using **TF-IDF**
- Computes similarity scores and selects the most central sentences
- Assembles the top 3 most relevant sentences into a final summary

## Dataset
- Source: [Kaggle – News Articles Dataset](https://www.kaggle.com/datasets/asad1m9a9h6mood/news-articles)
- Contains business and sports articles with headlines, content, and publication dates  
- **Note:** Dataset is not included in this repo due to licensing; please download manually.

## Libraries Used
- `numpy`
- `pandas`
- `nltk`
- `spaCy`
- `scikit-learn`
- `newspaper3k`

