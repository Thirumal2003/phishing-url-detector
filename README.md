# 🛡️ Phishing URL Detection using Machine Learning

This project leverages machine learning algorithms to detect phishing attacks based on URL features. It is designed to improve cybersecurity by identifying and classifying phishing websites with high accuracy.

---

## 📘 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)

---

## 🔍 Overview

Phishing attacks are a major cybersecurity threat, deceiving users into revealing sensitive data. Traditional blacklist and rule-based methods are inadequate against new attacks. This project uses ML algorithms like Logistic Regression, Random Forest, SVM, and Decision Tree to classify URLs as **legitimate** or **phishing**.

---

## ✨ Features

- URL-based feature extraction
- Preprocessing with tokenization and stemming
- Model training with Logistic Regression, SVM, Random Forest, Decision Tree
- Flask web interface for real-time prediction
- Confusion matrix, classification report, accuracy metrics

---

## 💻 Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- NLTK
- Joblib

---

## 🚀 Getting Started

1. **Clone the repository**  

git clone https://github.com/your-username/phishing-url-detector.git
cd phishing-url-detector

 ---
 
2. Install dependencies

pip install -r requirements.txt

---

3. Run the Flask app

python app.py

---

4. Open browser

Visit http://127.0.0.1:5000 

## 🛠 Usage

-Enter a URL into the input form

-The model analyzes it and returns either:

✅ Legitimate

🚫 Phishing







