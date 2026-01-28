# book-genre-classification
Data analysis project (individual)

This project applies natural language processing (NLP) and machine learning techniques to predict the genre of a book based on its textual description.  
It was developed as an end-to-end text classification project, covering data preprocessing, feature engineering, model training, and evaluation.
Tools used: Python, pandas, scikit-learn, spaCy, TF-IDF, langdetect, pyspellchecker, Jupyter Notebook

## Project Highlights
- Built a multi-class text classification model for book genre prediction
- Applied standard NLP preprocessing techniques to noisy real-world text
- Compared multiple machine learning models and evaluated their performance

## Problem Statement
Given a book description or summary, predict its corresponding genre (e.g. fiction, fantasy, mystery, etc.).  
This is a supervised classification problem involving unstructured text data and multiple output classes.

## Dataset
- Text data consists of book descriptions paired with genre labels
- Dataset provided as part of an academic module
- Used strictly for educational and non-commercial purposes

Basic data inspection revealed:
- Noisy text entries
- Inconsistent formatting
- Class imbalance across genres

## Methodology

### 1. Text Preprocessing
- Removal of punctuation and special characters 
- Lowercasing and tokenisation
- Stopword removal
- Lemmatization
- Filtering empty or invalid text entries

### 2. Feature Engineering
- TF-IDF vectorisation to convert text into numerical features
- Vocabulary size control to reduce noise and overfitting

### 3. Models Implemented
- Logistic Regression
- Multinomial Naive Bayes
- Linear Support Vector Classifier (Linear SVC)
- XGBoost

## Model Evaluation
Logistic Regression was used as the final model since it gives the best performace among all models. 

Detailed results and analysis are included in the exported HTML file.

# Files
- Notebook (HTML): bookgenreprediction.html
- Notebook (ipynb): bookgenreprediction.ipynb

