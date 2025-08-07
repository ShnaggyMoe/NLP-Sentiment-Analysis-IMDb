# NLP for Product Review Sentiment Analysis

## Project Overview
This project presents a complete pipeline for sentiment analysis on the IMDb movie review dataset. The objective was to build a machine learning model capable of classifying a review as either positive or negative. The final Logistic Regression model achieved **88.3% accuracy** on a held-out test set.

## Methodology
1.  **Data Cleaning:** Sanitized raw text by removing HTML tags and punctuation.
2.  **Feature Engineering:** Converted text into numerical vectors using `TfidfVectorizer`.
3.  **Model Training:** Trained a Logistic Regression classifier on the vectorized data.
4.  **Evaluation:** Assessed model performance using accuracy and a classification report.

## How to Run
1.  Clone the repository.
2.  Create and activate a virtual environment.
3.  Install dependencies: `pip install -r requirements.txt`
4.  Run the Jupyter Notebook: `notebooks/sentiment_analysis_pipeline.ipynb`