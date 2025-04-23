# Sentiment Analysis on Google Play Store Reviews

## Project Overview
This project applies Natural Language Processing (NLP) techniques to analyze user sentiment from Google Play Store reviews of a productivity app. It classifies sentiments into **Positive**, **Neutral**, and **Negative** categories and extracts meaningful insights to support **product improvement and customer satisfaction**.

## Objectives
- Clean and preprocess unstructured review text data.
- Build a classification model to predict sentiment using TF-IDF + Logistic Regression.
- Visualize commonly used words across sentiment categories.
- Provide **data-driven product recommendations** for app improvement.

## Dataset Overview
- Source: Google Play Store
- Columns used: `reviewId`, `content`, `score`
- Preprocessing:
  - Dropped null/duplicate reviews
  - Labeled sentiments based on review score
  - Cleaned text (lowercase, stopwords removal, lemmatization)

## Tools & Libraries
- **Python**, Jupyter Notebook
- **Pandas, NumPy** for data handling
- **NLTK** for text processing
- **Scikit-learn** for modeling (TF-IDF + Logistic Regression)
- **Matplotlib, Seaborn** for data visualization
- **WordCloud** for visual NLP insights

## Key Insights

| Insight | Observation |
|----------|-------------|
| 1      | Positive reviews dominate (44%) — users love the app’s usefulness. |
| 2      | Most negative reviews complain about **ads**, **sync issues**, and **crashes**. |
| 3      | Neutral reviews mention **features**, **habit-building**, and **notifications**. |

## Model Performance

- **Accuracy**: 70%
- **Algorithm**: Logistic Regression with TF-IDF Vectorization
- **Evaluation**: Precision, Recall, F1-score, Confusion Matrix

## WordCloud Visuals
- Top words by sentiment to understand **user emotions and feature expectations**.

## Business Recommendations

-  **Reduce intrusive ads**
-  **Improve sync functionality**
-  **A/B test updates before rollout**
-  **Prioritize feedback-aligned features**
-  **Incorporate user voice into roadmap planning**

## Future Work

- Train using deep learning (LSTM / BERT)
- Add topic modeling (LDA) for unsupervised feature discovery
- Deploy as a review dashboard for Product & UX teams

