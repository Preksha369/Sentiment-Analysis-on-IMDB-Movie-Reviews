# Sentiment Analysis on IMDB Movie Reviews

## Overview

This project performs sentiment analysis on the IMDB movie reviews dataset to classify reviews as **positive** or **negative**.
It demonstrates the complete machine learning workflow including:

* Data loading and preprocessing
* Feature extraction using Count Vectorizer and TF-IDF
* Training and evaluating multiple classifiers: Naive Bayes, Logistic Regression, Decision Tree, Random Forest, and XGBoost
* Comparing model performances based on accuracy

## Dataset

The IMDB dataset contains movie reviews labeled as positive or negative.
For faster experimentation, a subset of 1000 samples (`IMDB_Dataset_1000.csv`) is used, which can be replaced with the full dataset if available.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Preksha369/Sentiment-Analysis-on-IMDB-Movie-Reviews.git
   cd Sentiment-Analysis-on-IMDB-Movie-Reviews
   ```


2. Run the notebook or script to perform sentiment analysis and view results.

## Requirements

* Python 3.7+
* pandas
* numpy
* scikit-learn
* xgboost



## Results

The pipeline evaluates different models with two feature extraction methods and reports accuracy scores.
TF-IDF with Naive Bayes achieves the highest accuracy in this setup (\~83.5%).


