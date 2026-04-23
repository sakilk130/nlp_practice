# NLP Practice Project

## Project Overview

Comprehensive NLP learning and practice repository covering fundamental to advanced Natural Language Processing techniques.

**Topics Covered:**

- **Text Preprocessing** — Lowercasing, stopwords removal, tokenization, stemming, lemmatization
- **N-Grams** — Sequence analysis and feature extraction
- **Linguistic Analysis** — Parts-of-speech (POS) tagging, Named Entity Recognition (NER)
- **Sentiment Analysis** — Rule-based (TextBlob, VADER) and transformer-based models
- **Text Vectorization** — Bag of Words, TF-IDF
- **Topic Modeling** — LDA, LSA for unsupervised text understanding
- **Practical Exercises** — Real-world datasets (TripAdvisor, BBC News, book reviews)

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
conda install -c conda-forge jupyter pandas scikit-learn matplotlib nltk gensim
pip install textblob vaderSentiment transformers torch
```

### 3. Download NLTK Data

```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('maxent_ne_chunker')
nltk.download('words')
```

### 4. Run Jupyter Notebooks

```bash
jupyter notebook
```

Navigate to desired notebook and execute cells.

## Packages & Usage

| Package            | Purpose                                            |
| ------------------ | -------------------------------------------------- |
| **pandas**         | Data manipulation, CSV handling                    |
| **nltk**           | Text preprocessing, tokenization, POS tagging, NER |
| **scikit-learn**   | TF-IDF vectorization, ML utilities                 |
| **gensim**         | Topic modeling (LDA, LSA)                          |
| **matplotlib**     | Data visualization                                 |
| **textblob**       | Simple sentiment analysis                          |
| **vaderSentiment** | Social media sentiment analysis                    |
| **transformers**   | Pre-trained models (BERT, GPT)                     |
| **torch**          | Deep learning framework for transformers           |
| **jupyter**        | Interactive notebook environment                   |

## Notebook Structure

- **1.1-1.6** — Text preprocessing fundamentals
- **1.7** — N-grams practice
- **1.8** — Practical: TripAdvisor reviews
- **2.0-2.1** — Linguistic analysis (POS, NER)
- **2.2** — Practical: BBC News
- **3.0-3.1** — Sentiment analysis methods
- **3.2** — Practical: Book reviews
- **4.0-4.1** — Text vectorization
- **5.0-5.1** — Topic modeling

## Quick Start

```bash
# Activate environment
conda activate nlp_practice

# Launch Jupyter
jupyter notebook

```
