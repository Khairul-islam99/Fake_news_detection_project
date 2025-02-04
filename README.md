# Fake News Detection

## Overview

Fake News Detection is a machine learning project aimed at classifying news articles as either **Fake News** or **Real News**. This project uses Natural Language Processing (NLP) techniques and machine learning models to analyze and predict the authenticity of a given news article.

## Features

- Preprocessing of textual data using regular expressions and NLP techniques.
- TF-IDF Vectorization for feature extraction.
- Implementation of multiple machine learning models:
  - Logistic Regression (LR)
  - Decision Tree (DT)
  - Random Forest Classifier (RFC)
  - Gradient Boosting Classifier (GBC)
- Manual testing function for user input.
- Performance evaluation using accuracy scores and confusion matrices.

## Dataset

The dataset consists of labeled news articles where:

- **1** represents real news
- **0** represents fake news

## Installation

To run this project locally, install the required dependencies:

```bash
pip install pandas numpy sklearn nltk re
```

## Usage

1. **Data Preprocessing:**

   - Remove unnecessary punctuation, numbers, and special characters.
   - Convert text to lowercase.
   - Apply TF-IDF Vectorization for text transformation.

2. **Training Machine Learning Models:**

   - Train different models (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting) on the dataset.
   - Evaluate models using accuracy scores.

3. **Testing with Manual Input:**

   - Use `manual_testing(news)` function to classify user-provided news.

## Future Improvements

- Implement deep learning models such as LSTMs and Transformers.
- Improve accuracy by hyperparameter tuning.
- Deploy as a web application using Flask or FastAPI.

## Contributors

- **Md Khairul Islam** *(Data Analyst, Machine Learning Enthusiast)*

