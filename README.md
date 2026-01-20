# Multi-Label Movie Genre Classification

Classifying movies into multiple genres using plot synopses

## 📋 Overview

NLP project for multi-label classification of movie genres based on plot descriptions using machine learning techniques.

## 📂 Structure

- **[Data/](Data/)** - Movie plot dataset
- **[Documents/](Documents/)** - Project report and presentation
- **[movie_genre_classification.ipynb](movie_genre_classification.ipynb)** - Implementation notebook

## 📊 Dataset

**Source**: MPST Corpus (IMDB + Wikipedia)
- 14,828 movie plot synopses
- Multiple genre labels per movie

## 🔬 Methodology

### Preprocessing
HTML removal → Accent removal → Punctuation removal → Lowercase → Stemming → Stop word removal

### Features
- **TF-IDF**: Term frequency weighting
- **LDA**: Topic modeling

### Models (One-vs-Rest)
- Naive Bayes
- Logistic Regression on TF-IDF
- Logistic Regression on TF-IDF + LDA

### Metric
**Micro F1 Score** - Global performance across all genres

## 🎯 Applications

- Automated movie categorization
- Content recommendation
- Streaming platform tagging

---

*Multi-label text classification for movie genres*
