# NLP Practice Project

## Project Overview

Comprehensive NLP learning and practice repository covering fundamental to advanced Natural Language Processing techniques.

**Topics Covered:**

- **Text Preprocessing** — Lowercasing, stopwords removal, regex, tokenization, stemming, lemmatization
- **N-Grams** — Unigrams, bigrams, trigrams for sequence analysis
- **Linguistic Analysis** — Parts-of-speech (POS) tagging, Named Entity Recognition (NER)
- **Sentiment Analysis** — Rule-based (TextBlob, VADER) and transformer-based models (BERT, RoBERTa)
- **Text Vectorization** — Bag of Words (BoW), TF-IDF for feature extraction
- **Topic Modeling** — LDA, LSA for unsupervised document understanding
- **Text Classification** — Custom classifiers for spam, sentiment, and fake news detection
- **Practical Exercises** — Real-world datasets (TripAdvisor, BBC News, book reviews, fake news)

## Prerequisites

- Python 3.13.9
- Conda or Miniconda installed

## Setup Instructions

### 1. Create Conda Environment

```bash
conda create -n nlp_practice python=3.13.9
conda activate nlp_practice
```

### 2. Install Required Packages

```bash
conda install -c conda-forge jupyter pandas scikit-learn matplotlib nltk gensim seaborn spacy
pip install textblob vaderSentiment transformers torch
```

### 3. Download Language Models & NLTK Data

```bash
# Spacy English model
python -m spacy download en_core_web_sm

# NLTK data
python -c "import nltk; nltk.download('stopwords'); nltk.download('punkt'); nltk.download('averaged_perceptron_tagger'); nltk.download('maxent_ne_chunker'); nltk.download('wordnet'); nltk.download('words')"
```

### 4. Run Jupyter Notebooks

```bash
jupyter notebook
```

Navigate to desired notebook and execute cells.

## Packages & Usage

| Package            | Purpose                                                                     |
| ------------------ | --------------------------------------------------------------------------- |
| **pandas**         | Data manipulation, CSV handling, data analysis                              |
| **nltk**           | Text preprocessing, tokenization, POS tagging, NER, stemming, lemmatization |
| **spacy**          | Industrial-strength NLP, NER, POS tagging                                   |
| **scikit-learn**   | ML algorithms, TF-IDF vectorization, classification                         |
| **gensim**         | Topic modeling (LDA, LSA), word embeddings                                  |
| **matplotlib**     | Data visualization, plotting results                                        |
| **seaborn**        | Statistical data visualization                                              |
| **textblob**       | Simplified sentiment analysis                                               |
| **vaderSentiment** | Social media sentiment analysis                                             |
| **transformers**   | Pre-trained models (BERT, RoBERTa, DistilBERT)                              |
| **torch**          | Deep learning framework for transformers                                    |
| **jupyter**        | Interactive notebook environment                                            |

## Notebook Structure

### Module 1: Text Preprocessing & Feature Extraction

- **1.1** — Lowercasing text normalization
- **1.2** — Stopwords removal techniques
- **1.3** — Regular expressions for text cleaning
- **1.4** — Tokenizing and segmentation
- **1.5** — Stemming (Porter Stemmer, Snowball)
- **1.6** — Lemmatization with NLTK
- **1.7** — N-grams analysis (unigrams, bigrams, trigrams)
- **1.8** — Practical: TripAdvisor reviews text preprocessing

### Module 2: Linguistic Analysis

- **2.0** — Parts-of-Speech (POS) tagging
- **2.1** — Named Entity Recognition (NER)
- **2.2** — Practical: BBC News articles analysis

### Module 3: Sentiment Analysis

- **3.0** — Rule-based sentiment (TextBlob, VADER)
- **3.1** — Pre-trained transformer models (BERT, RoBERTa)
- **3.2** — Practical: Book reviews sentiment classification

### Module 4: Text Vectorization

- **4.0** — Bag of Words (BoW) representation
- **4.1** — TF-IDF vectorization

### Module 5: Topic Modeling

- **5.0** — Latent Dirichlet Allocation (LDA)
- **5.1** — Latent Semantic Analysis (LSA)

### Module 6: Classification

- **6.0** — Custom text classifiers (Naive Bayes, SVM, Logistic Regression)

### Module 7: Capstone Project

- **7.0** — Practical: Fake news detection & classification

## Key Datasets

| Dataset                           | Size            | Use Case                                     |
| --------------------------------- | --------------- | -------------------------------------------- |
| **bbc-news.csv**                  | ~2,000 articles | News classification, NER                     |
| **tripadvisor_hotel_reviews.csv** | ~20,000 reviews | Sentiment analysis, text preprocessing       |
| **book-reviews-sample.csv**       | Varies          | Sentiment classification, topic modeling     |
| **news-articles.csv**             | Varies          | Fake news detection, document classification |

## Quick Start

```bash
# Activate environment
conda activate nlp_practice

# Launch Jupyter
jupyter notebook

```
