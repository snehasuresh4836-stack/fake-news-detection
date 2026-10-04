# 📰 Fake News Detection

An AI-powered fake news detection system that uses machine learning and natural language processing to classify news as **FAKE** or **TRUE**.

The project uses **TF-IDF Vectorization** and **Logistic Regression** to analyze the text of news articles. It also provides confidence-based predictions and can search for recent related news using NewsAPI.

## 📌 Project Overview

Fake news can spread quickly through online platforms and make it difficult for people to identify reliable information.

This project provides a machine learning-based solution that analyzes the title and content of a news article and predicts whether it is **FAKE** or **TRUE**.

## 🎯 Objective

The main objective of this project is to develop a simple and interactive system for detecting potentially fake news using machine learning and natural language processing.

## ✨ Features

- 📰 Fake or True news classification
- 🤖 Machine learning-based prediction
- 📊 Confidence score
- 🧹 Text preprocessing
- 🔤 TF-IDF text vectorization
- 📈 Logistic Regression classification
- 🔎 Recent news search using NewsAPI
- 🖥️ Interactive Gradio interface
- 🛡️ Helpful verification reminder for users

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- TF-IDF
- Logistic Regression
- Gradio
- NewsAPI
- Google Colab

## 🔄 How It Works

1. The user enters a news title and news content.
2. The text is cleaned and preprocessed.
3. Stopwords and unnecessary characters are removed.
4. The title and news content are combined.
5. TF-IDF converts the text into numerical features.
6. Logistic Regression analyzes the features.
7. The system predicts whether the news is **FAKE** or **TRUE**.
8. A confidence score is displayed.
9. The application can also search for recent related news using NewsAPI.

## 🧠 Machine Learning Model

The project uses a pipeline containing:

- **TF-IDF Vectorizer** for converting text into numerical features.
- **Logistic Regression** for classification.

The TF-IDF vectorizer uses up to 50,000 features and considers both single words and two-word combinations (unigrams and bigrams).

## 📊 Model Performance

In the current experiment, the model achieved approximately:

**Accuracy: 98.68%**

The reported test results include precision, recall, F1-score, and a confusion matrix.

> Model performance can vary depending on the dataset and testing conditions.

## 🖥️ User Interface

The application provides three inputs:

- **News Title**
- **News Text**
- **Search Query for Today's News (optional)**

The result displays the predicted classification, confidence score, and available recent news coverage.

## 📸 Screenshot

![Fake News Detection](fake-news-detection.png)

## 📦 Installation

Install the required Python packages:

```bash
pip install pandas numpy scikit-learn gradio nltk requests
