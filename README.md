[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/D94-Q8ry)
# 📈 Stock Market Sentiment Analysis using NLP and Deep Learning

## 📌 Project Summary

This project focuses on predicting the sentiment of stock market news using Natural Language Processing (NLP) and Machine Learning/Deep Learning techniques. Financial news headlines are processed and classified into **Positive**, **Neutral**, or **Negative** sentiments to understand their potential impact on stock market trends.

The project compares two text embedding techniques—**Word2Vec** and **Sentence Transformers (all-MiniLM-L6-v2)**—to generate meaningful text representations. These embeddings are then used to train and evaluate **Random Forest** and **Neural Network** models. The performance of each model is measured using standard evaluation metrics such as Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

This implementation demonstrates the complete NLP pipeline, including data preprocessing, exploratory data analysis (EDA), text embedding generation, model training, evaluation, and comparison to identify the most effective approach for stock market sentiment classification.

# 🔄 Project Workflow

### 1. Dataset Collection
- Load the stock market news dataset.
- The dataset contains news headlines, stock prices, and sentiment labels (Positive, Neutral, Negative).

⬇️

### 2. Data Preprocessing
- Remove missing values.
- Clean the text by converting it to lowercase.
- Remove punctuation, special characters, and extra spaces.
- Tokenize and prepare the text for analysis.

⬇️

### 3. Exploratory Data Analysis (EDA)
- Analyze the dataset structure.
- Visualize sentiment distribution.
- Check class balance and data quality.
- Explore important statistics using charts.

⬇️

### 4. Text Embedding Generation
Convert text into numerical vectors using two different embedding techniques:

- **Word2Vec** – Learns word-level vector representations.
- **Sentence Transformer (all-MiniLM-L6-v2)** – Generates contextual sentence embeddings.

⬇️

### 5. Train-Test Split
- Split the dataset into training and testing sets.
- Train the models using the training data.
- Evaluate performance on unseen test data.

⬇️

### 6. Model Building

#### Machine Learning Model
- Random Forest Classifier

#### Deep Learning Model
- Neural Network (TensorFlow/Keras)

⬇️

### 7. Model Training
- Train both models using Word2Vec embeddings.
- Train both models using Sentence Transformer embeddings.

⬇️

### 8. Model Evaluation
Evaluate each model using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

⬇️

### 9. Performance Comparison
Compare the performance of:
- Word2Vec + Random Forest
- Word2Vec + Neural Network
- Sentence Transformer + Random Forest
- Sentence Transformer + Neural Network

⬇️

### 10. Best Model Selection
- Select the model with the highest performance.
- Use the best model for stock market news sentiment prediction.

---
