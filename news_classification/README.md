# NLP for News Article Classification and Analysis

## Overview
This project employs NLP techniques to classify news articles into relevant categories. 
It utilizes TF-IDF for text vectorization and compares various classifiers such as Random Forest, KNN, SVM, 
and Logistic Regression to identify the best-performing model.

## Requirements
- pandas
- matplotlib
- scikit-learn
- seaborn

## Dataset
The source data for this project is obtained from Kaggle:
https://www.kaggle.com/datasets/timilsinabimal/newsarticlecategories/data

## Usage
1. Run the Python script `news_article_classification.py`.
2. The script performs the following steps:
   - Reads the dataset from `news-article-categories.csv`.
   - Cleans the text data.
   - Uses TF-IDF vectorization for feature extraction.
   - Encodes category labels.
   - Splits the data into training and testing sets.
   - Trains multiple classifiers and selects the best-performing model based on accuracy.
   - Evaluates the model using a confusion matrix.
   - Provides a function `find_appropriate_category(text)` to predict the appropriate category for a given article.


## Contact
For any inquiries or feedback, feel free to contact me.
email: mariamsaiqodze@gmail.com


