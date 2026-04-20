# twitter-sentiment-analysis
End-to-end sentiment analysis system using NLP and machine learning
# Twitter Sentiment Analysis (Advanced)

## 📌 Overview
This project performs sentiment analysis on Twitter data, classifying tweets into Positive, Negative, and Neutral categories using NLP and machine learning techniques.

## 🚀 Features
- Text preprocessing using NLTK
- TF-IDF vectorization with n-grams
- Multi-model comparison (Logistic Regression, Naive Bayes, SVM)
- Model evaluation (Accuracy, Confusion Matrix, ROC Curve)
- WordCloud visualization
- Explainability (important words per sentiment)
- Error analysis
- Real-time sentiment prediction system
- Model saving using pickle

## 🧠 Technologies Used
- Python
- NLTK
- Scikit-learn
- Pandas
- Matplotlib & Seaborn

## 📊 Results
- Achieved strong accuracy across multiple models
- SVM performed best in classification
- Identified key words influencing sentiment

## 🔍 Insights
- Negative sentiment is mostly related to delays and poor service
- Positive sentiment reflects customer satisfaction
- Neutral tweets mainly represent queries or general communication

## ⚙️ How to Run
1. Upload dataset (Tweets.csv)
2. Run the notebook step-by-step
3. Use the prediction function:
```python
predict_sentiment("Your text here")
