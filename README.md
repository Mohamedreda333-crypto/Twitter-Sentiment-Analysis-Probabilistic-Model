# Twitter Sentiment Analysis using Probabilistic Modeling

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![NLP](https://img.shields.io/badge/Field-NLP-green.svg)

## Project Overview
This project aims to analyze and classify the sentiment of tweets into **Positive** or **Negative**. The project demonstrates the full pipeline of an NLP task, from raw data cleaning to building a custom probabilistic model for prediction.

## Tech Stack & Libraries
* **Language:** Python
* **Data Handling:** Pandas, NumPy
* **NLP Tools:** NLTK (Natural Language Toolkit)
* **Modeling:** Custom Probabilistic Implementation
* **Evaluation:** Scikit-learn (Accuracy Score)

## Key Features
- **Custom Preprocessing Pipeline:** - Removing URLs, Hashtags, and Mentions.
    - Tokenization and Stopwords removal.
    - Porter Stemming to reduce words to their root forms.
- **Frequency Dictionary:** Building a word-frequency mapping based on sentiment labels.
- **Probabilistic Model:** Implementing a Naive Bayes-like approach for sentiment classification.
- **Live Prediction:** A dedicated function to test the model with any custom string input.

## Dataset
The model was trained using the **Twitter Sentiment Analysis Dataset**, which contains thousands of labeled tweets. The data is split into:
* `twitter_training.csv` for model building.
* `twitter_validation.csv` for testing and accuracy calculation.

## Accuracy
The model achieved an impressive accuracy of **90.0%** on the validation set.

## How to Use
1. Clone the repository.
2. Ensure you have the datasets in the specified paths.
3. Run the Jupyter Notebook `Sentiment Anaysis.ipynb`.
4. Use the `Sentiment_Analysis("Your text here")` function to test custom statements.

---
Developed as part of an NLP & AI exploration.
