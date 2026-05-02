# 📱 SMS Spam Detection System

An end-to-end Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using NLP techniques.

---

## 🚀 Overview
This project demonstrates a complete ML pipeline:
- Text preprocessing
- Feature extraction using TF-IDF
- Model training & evaluation
- Deployment using Streamlit

---

## 🧠 Problem Statement
Spam messages are a common issue in communication systems.  
This project aims to build a model that accurately detects spam messages while minimizing false positives.

---

## ⚙️ Tech Stack
- Python
- Scikit-learn
- NLTK
- Pandas, NumPy
- Streamlit

---

## 🔍 Features
- Text cleaning (lowercase, tokenization, stopword removal, stemming)
- TF-IDF vectorization
- Multiple model comparison:
  - Naive Bayes
  - Logistic Regression
  - SVM
  - Random Forest
- Evaluation using **Accuracy & Precision**
- Real-time prediction via Streamlit UI

---

## 🏆 Best Model
**Multinomial Naive Bayes**
- High precision for spam detection
- Fast and efficient for text classification

---

## 📊 Model Performance
| Model | Accuracy | Precision |
|------|---------|----------|
| Naive Bayes | ⭐ High | ⭐ Very High |
| SVM | High | High |
| Logistic Regression | Good | Good |

---

## 💡 Key Learnings
- TF-IDF is powerful for text-based ML problems  
- Precision is more important than accuracy in spam detection  
- Simple models can outperform complex ones with the right features  

---

## 🚀 Deployment
The model is deployed using Streamlit for real-time predictions.

```bash
streamlit run app.py
