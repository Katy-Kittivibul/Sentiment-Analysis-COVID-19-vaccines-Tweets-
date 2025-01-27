# 👩‍💻 Twitter Sentiment Analysis: COVID-19 Vaccines

Welcome to the **Twitter Sentiment Analysis** project! This repository contains the code for a machine learning pipeline that analyzes tweets' sentiment (Positive, Negative, Neutral) and deploys the model using a Flask web application. 🌟

---

## 📖 About the Project
Twitter sentiment analysis is a common natural language processing (NLP) task where tweets are classified into sentiments like **Positive**, **Negative**, or **Neutral**. 
This project:
1. **Processes raw tweets** using NLP techniques.
2. **Trains a Logistic Regression model** using the `TfidfVectorizer`.
3. Deploys the model using a **Flask web app**, where users can input text and see the predicted sentiment.

---

## ⚙️ Features
- ✅ **Preprocessing**: Cleans and tokenizes text data for sentiment classification.
- ✅ **Model Training**: Uses Logistic Regression with `TfidfVectorizer` for sentiment prediction.
- ✅ **Deployment Ready**: Flask app for real-time user interaction.
- ✅ **Scalable**: Can be extended with other ML models (e.g., SVM, Naive Bayes).

---

## 📦 Installation

### Prerequisites:
- Python 3.8 or above 🐍
- Flask
- Jupyter Notebook 

### Clone the Repository:
   ```bash
> git clone https://github.com/your-username/Sentiment-Analysis-COVID-19-vaccines-Tweets-.git
> cd Sentiment-Analysis-COVID-19-vaccines-Tweets-
   ```
---

## 🏆 Results
Logistic regression
- Accuracy: 0.862
The model correctly classified 86.2% of the test data, indicating good overall performance. This suggests that the model is effective at identifying the correct sentiment for the majority of the input data.
- Precision: 0.873
Precision measures the model’s ability to correctly identify positive predictions. With a precision score of 87.3%, the model shows a high likelihood of producing accurate sentiment predictions when it classifies an instance as positive.
- Recall: 0.862
Recall (or sensitivity) assesses how well the model captures all relevant instances of a specific sentiment. A recall score of 86.2% demonstrates that the model effectively identifies most of the true positive cases.
- F1-Score: 0.852
The F1-Score is the harmonic mean of precision and recall, providing a balanced measure of the model's performance. At 85.2%, the F1-Score confirms that the model strikes a reasonable balance between precision and recall.

## 💬 Discussion

The logistic regression model demonstrated strong performance with high accuracy (86.2%), precision (87.3%), recall (86.2%), and a balanced F1-score (85.2%). The model effectively identifies sentiment in the data, with high precision indicating it makes few false positives and balanced recall showing it captures most true positive cases.
However, the slightly lower F1-score suggests a small trade-off between precision and recall. Logistic regression, being a linear model, may have limitations in handling more complex language data. 
To improve performance, further hyperparameter tuning, the exploration of more advanced models (e.g., SVM, deep learning), and enhanced feature engineering could be beneficial. Overall, the model is suitable for practical applications like social media sentiment analysis but requires additional validation for broader use.

---
## 📄 License
This project is licensed under the MIT License. Feel free to use it as you wish. ✨
