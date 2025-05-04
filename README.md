# 🌍 Multilingual Sentiment Analysis using Logistic Regression

## 🔍 Overview
This project implements a sentiment analysis pipeline for tweets written in multiple languages using traditional machine learning techniques. It classifies tweets into positive, negative, or neutral sentiments and includes a bias analysis across languages.

---

## 📦 Dataset
- **Source**: [HuggingFace – tyqiangz/multilingual-sentiments](https://huggingface.co/datasets/tyqiangz/multilingual-sentiments)
- **Languages**: English, Japanese, Arabic, and others
- **Sentiment Labels**:
  - `0` = Negative
  - `1` = Neutral
  - `2` = Positive

---

## 🧠 Key Features
- ✅ Text preprocessing: URL removal, lowercasing, punctuation stripping
- ✅ Vectorization using TF-IDF
- ✅ Sentiment classification using Logistic Regression
- ✅ Accuracy and classification metrics evaluation
- ✅ Confusion matrix for model evaluation
- ✅ Bias analysis of sentiment distribution across different languages
- ✅ Prediction support for custom input

---

## 📊 Results
- **Model**: Logistic Regression (sklearn)
- **Vectorizer**: TF-IDF with 5,000 features
- **Metrics**: Accuracy, classification report, confusion matrix
- **Bonus**: Language-wise sentiment distribution visualized via bar chart

---

## 🖼️ Visualizations
- Confusion matrix (True vs Predicted)
- Sentiment bias per language (stacked bar chart)

---

## ⚙️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/MPriyadhar/multilingual-sentiment-analysis.git
cd multilingual-sentiment-analysis
