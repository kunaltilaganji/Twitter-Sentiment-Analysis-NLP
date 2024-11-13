# Twitter Sentiment Analysis - NLP

This project aims to detect hate speech in tweets, identifying tweets with racist or sexist sentiments. The primary goal is to classify these hateful tweets from non-hateful ones using Natural Language Processing (NLP) techniques.

## Project Overview

The dataset includes 31,962 labeled tweets provided as part of a hackathon problem on Analytics Vidhya. A tweet is labeled as '1' if it is classified as racist or sexist and '0' if it is not. The objective is to build a model to predict these labels for a given test dataset.

**Hackathon Link:** [Practice Problem - Twitter Sentiment Analysis](https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/)

## Dataset Information

- **Total Tweets**: 31,962
- **Labels**:
  - `1` - Racist/Sexist
  - `0` - Not Racist/Sexist
- **Format**: CSV file with columns for tweet ID, label, and tweet text

## Libraries Used

- **pandas**: For data manipulation and preprocessing
- **matplotlib**: For data visualization
- **seaborn**: For enhanced visualizations
- **scikit-learn**: For implementing machine learning models
- **nltk**: For creating applications for statistical

## Algorithms Implemented

This project explores two algorithms in separate Jupyter Notebooks (`.ipynb` files):

1. **Logistic Regression**: A classic machine learning approach for binary classification.
2. **LSTM (Long Short-Term Memory)**: A deep learning model capable of handling sequential data, particularly useful for text analysis.

### Best Model Performance

- **Accuracy**: 95.00%

## File Structure

- `Twitter_Sentiment_Analysis.ipynb`: Notebook implementing Logistic Regression
- `LSTM_Twitter_Sentiment_Analysis.ipynb`: Notebook implementing LSTM model

