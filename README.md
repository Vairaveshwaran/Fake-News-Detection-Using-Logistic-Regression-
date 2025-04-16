# Fake-News-Detection-Using-Logistic-Regression-
A Machine Learning project that detects fake news articles using Logistic Regression and Count Vectorization. It processes real and fake datasets, trains a binary classifier, and allows testing with custom inputs. Built using Python, pandas, and scikit-learn on Google Colab.
# Fake News Detection using Logistic Regression

## Overview
This project uses machine learning to classify news articles as **Real** or **Fake**. Using **Logistic Regression**, the model learns patterns in text data after converting it to numerical format using **Count Vectorizer**.

## Dataset
Two datasets were used:
- **True.csv** – Real news articles
- **Fake.csv** – Fake news articles  
(Source: [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset))

These were imported using **Google Drive** in Google Colab.

## Features
- Merges and labels real and fake news articles
- Performs text preprocessing
- Uses `CountVectorizer` to transform text
- Applies **Logistic Regression** for classification
- Displays model accuracy and confusion matrix
- Allows input testing with user-defined headlines

## Technologies Used
- **Python**
- **Google Colab**
- **Pandas**
- **Scikit-learn**
- **CountVectorizer**
- **Logistic Regression**

## How to Run
1. Upload `Fake.csv` and `True.csv` to your Google Drive
2. Clone this repo or open `fake_and_real_news_detection.ipynb` in Google Colab
3. Authenticate with Google Drive to access the datasets
4. Run all cells to train and test the model
5. Optionally enter your own news text to classify it as fake or real

## Sample Output
- Training Accuracy  
- Confusion Matrix  
- Input Prediction: *"This news is Fake"* or *"This news is Real"*

## Author
- **Vairaveshwaran** – Developed Count Vectorization, Data Handling, and Model Training.
