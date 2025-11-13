# 🛡️ PhishGuard: A URL-Based Machine Learning Approach for Phishing Detection

PhishGuard is a **Machine Learning-based project** that detects phishing websites using only their **URL features**.  
The model analyzes various patterns in URLs (like length, special symbols, and domain structure) and predicts whether a website is **Legitimate** or **Phishing**.

---

## 🚀 Features
- Extracts important **URL-based features** automatically.
- Trains and compares multiple **ML algorithms** (Random Forest, SVM, CatBoost, and Stacked Ensemble).
- Achieves **95%+ accuracy** on phishing URL datasets.
- Includes **Flask-based app** for real-time phishing prediction.
- Provides detailed **evaluation metrics and reports**.

---

## 🧠 Machine Learning Models Used
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- CatBoost  
- Stacked Ensemble (final model with highest accuracy)

---

## 📊 Dataset
The dataset contains both **phishing and legitimate URLs**, collected from:
- PhishTank  
- Kaggle  
- UCI Machine Learning Repository  

---

## ⚙️ Project Structure
PhishGuard-A-URL-Based-Machine-Learning-Approach-for-Phishing-Detection/
│
├── app.py # Flask web app for prediction
├── main.py # Main ML training and evaluation script
├── phishing-detection.ipynb # Jupyter notebook with feature extraction & modeling
├── requirements.txt # Python dependencies
├── README.md # Project documentation
├── .gitignore # Files/folders ignored by Git
└── LICENSE # Project license


