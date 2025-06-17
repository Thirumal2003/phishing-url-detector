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
nstall dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask app

bash
Copy
Edit
python app.py
Visit http://127.0.0.1:5000 to use the detection interface.

🛠 Usage
Input a URL in the web form.

Click "Check" to get the prediction result (Phishing or Legitimate).

Visualizations and performance metrics are shown on the dashboard.

📊 Dataset
Total URLs: 11,430

50% Legitimate and 50% Phishing

87 extracted features per URL

✅ Results
Model	Accuracy
Logistic Regression	91%
Decision Tree	89%
SVM	84%
Random Forest	80%

Logistic Regression achieved the best results with high precision and recall.

🔭 Future Enhancements
Real-time browser extension for phishing protection

Integration of HTML/content-based features

Deploy as REST API with cloud hosting

Implement LSTM/CNN for deep learning URL analysis

👥 Contributors
Dineshkanna K – kit.25.21bad015@gmail.com

Thirumal P – kit.25.21bad058@gmail.com

Victor Moses M P – kit.25.21bad060@gmail.com





