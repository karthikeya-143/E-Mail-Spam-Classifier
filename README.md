# 📧 Email Spam Classifier using Naive Bayes

A simple and effective **Machine Learning project** that detects whether an email is **Spam or Not Spam** using:

* 🧠 Naive Bayes Algorithm
* 🔢 Count Vectorization (Bag of Words)
* 🐍 Python + Scikit-learn

Perfect for beginners in **NLP and ML projects**.

---

## 🚀 Project Overview

Email spam filtering is a classic NLP problem where the goal is to classify emails into:

* ❌ Spam (Promotional, malicious)
* ✅ Ham (Normal email)

This project builds a lightweight and fast spam classifier using **probabilistic learning**.

---

## 🧠 Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* CountVectorizer (BoW)
* Multinomial Naive Bayes

---

## 📌 Machine Learning Pipeline

```
Raw Emails
   ↓
Text Cleaning
   ↓
Count Vectorization
   ↓
Naive Bayes Training
   ↓
Spam Prediction
```

---

## 🔍 Key Concepts

### 🔢 Count Vectorization

Converts text into numerical vectors by counting word occurrences.

Example:

| Email          | free | win | hello |
| -------------- | ---- | --- | ----- |
| free win money | 1    | 1   | 0     |

Creates a **Document-Term Matrix**.

---

### 🧠 Naive Bayes

A probabilistic classifier based on **Bayes Theorem** with an independence assumption.

Formula:

```
P(Class | Text) ∝ P(Class) × Π P(word | Class)
```

Fast and works great for text classification.

---

## 📊 Dataset

You can use:

* SMS Spam Collection Dataset
* Enron Email Dataset
* Custom CSV dataset

Example format:

| label | message          |
| ----- | ---------------- |
| spam  | Win money now!!! |
| ham   | Meeting at 5 PM  |

---


## 🧪 Model Training Steps

1. Load dataset
2. Clean text (lowercase, remove symbols)
3. Convert text → vectors using CountVectorizer
4. Train Multinomial Naive Bayes
5. Evaluate accuracy

---

## 📈 Model Evaluation

Common metrics used:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 📊 Example Output

```
Input: "Congratulations! You won a free iPhone"
Prediction: SPAM 🚨

Input: "Let's meet tomorrow at office"
Prediction: HAM ✅
```

---

## 📂 Project Structure

```
email-spam-classifier/
│
├── data/
│   └── spam.csv
├── notebooks/
│   └── spam_classifier.ipynb
├── src/
│   ├── preprocess.py
│   ├── train.py
│   └── predict.py
├── model/
│   └── spam_model.pkl
├── requirements.txt
└── README.md
```

---

## 🧠 Why Naive Bayes?

* Extremely fast ⚡
* Works well with small datasets
* Great baseline for NLP tasks
* Low computational cost

---

## 👍 Advantages

* Simple implementation
* High performance on text data
* Lightweight model
* Easy deployment

---

## ❌ Limitations

* Assumes feature independence
* Cannot understand context
* Performance drops with complex language

---

## 🔮 Future Improvements

* Use TF-IDF instead of CountVectorizer
* Add deep learning (LSTM/BERT)
* Build web app using Flask/FastAPI
* Deploy with Streamlit
* Add email API integration

---

## 🌐 Real-World Applications

* Gmail spam filters
* SMS spam detection
* Phishing detection
* Customer support filtering

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Commit changes
4. Submit a Pull Request

---

## ⭐ If You Like This Project

* Star ⭐ the repo
* Fork 🍴 and build your own ML version
* Share with friends 🚀

---
