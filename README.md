# twitter-sentiment-analysis
End-to-end sentiment analysis system using NLP and machine learning
# Twitter Sentiment Analysis (Advanced)


## 📌 Overview
This project builds an end-to-end sentiment analysis system that classifies tweets into Positive, Negative, and Neutral categories using Natural Language Processing (NLP) and Machine Learning.

---

## 🎯 Objective
To analyze Twitter data and automatically determine customer sentiment, helping organizations understand public opinion and improve decision-making.

---

## 🚀 Features
- Text preprocessing using NLTK (stopword removal, stemming)
- TF-IDF vectorization with n-grams
- Multi-class sentiment classification (Positive, Negative, Neutral)
- Multiple ML models:
  - Logistic Regression
  - Naive Bayes
  - Support Vector Machine (SVM)
- Model evaluation:
  - Accuracy
  - Classification Report
  - Confusion Matrix
  - ROC Curve
- Data visualization:
  - Sentiment distribution (pie chart)
  - WordCloud (class-wise)
- Explainability:
  - Important words influencing sentiment
- Error analysis for understanding model limitations
- Real-time sentiment prediction system
- Model saving using pickle (deployment-ready)

---

## 🧠 Technologies Used
- Python
- NLTK
- Scikit-learn
- Pandas
- NumPy
- Matplotlib & Seaborn

---

## 📂 Project Structure
- sentiment_analysis.ipynb → Main notebook  
- model.pkl → Trained model  
- vectorizer.pkl → TF-IDF vectorizer  
- Tweets.csv → Dataset  

---

## 📊 Results
- Achieved strong accuracy across multiple models  
- SVM performed best in classification  
- Model successfully identifies key words influencing sentiment  

---

## 🔍 Insights
- Negative sentiment is mostly related to delays and service issues  
- Positive sentiment reflects customer satisfaction and appreciation  
- Neutral tweets mainly represent queries or general communication  

---

## ⚙️ How to Run
1. Upload the dataset (Tweets.csv)  
2. Run the notebook step-by-step  
3. Use the prediction function:

```python
predict_sentiment("I love this airline")
('Positive 😊', 91.23)



Author

Shreya K Reddy
