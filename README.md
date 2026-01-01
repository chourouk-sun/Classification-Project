# Sentiment Analysis on IMDB Movie Reviews

## Overview 
This project aims to build a machine learning model that classifies IMDB movie reviews as **positive** or **negative**. It leverages **TF-IDF vectorization** and **Logistic Regression** to analyze textual data and predict sentiment.

## Dataset
* **Source:** [Kaggle IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?utm_source=chatgpt.com)
* **Size:** 50,000 movie reviews
* **Classes:** Balanced dataset with **positive** and **negative** reviews

## Methodology
1. **Data Preprocessing**
   * Text cleaning (removing punctuation, stopwords, lowercase conversion)
   * Tokenization
2. **Feature Extraction**
   * TF-IDF vectorization of movie reviews
3. **Model Training**
   * Logistic Regression classifier
   * Train-test split for evaluation
4. **Evaluation**
   * Accuracy score
   * Classification report
   * Confusion matrix

## Results
* **Accuracy:** ~88-90%
* **Top Positive Words:** amazing, excellent, perfect
* **Top Negative Words:** boring, worst, awful

## Future Improvements
* Experiment with advanced models such as **Random Forest**, **XGBoost**, or **BERT**
* Handle **imbalanced datasets** with techniques like SMOTE
* Perform **hyperparameter tuning** for improved accuracy
* Deploy the model as a **web app** for live predictions


`notebook/sentiment_analysis.ipynb` and run all cells
