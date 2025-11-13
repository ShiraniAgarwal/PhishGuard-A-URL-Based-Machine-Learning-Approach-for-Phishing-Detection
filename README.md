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

## 🧩 How to Run Locally

### Step 1: Clone the Repository
git clone "(https://github.com/ShiraniAgarwal/PhishGuard-A-URL-Based-Machine-Learning-Approach-for-Phishing-Detection/)" 
Step 2: Navigate to the Project Folder
bash
  cd PhishGuard-A-URL-Based-Phishing-Detection
Step 3: Install Dependencies
bash
  pip install -r requirements.txt
Step 4: Run the Flask App
bash
  python app.py
Open your browser and go to http://127.0.0.1:5000/ to use the phishing detector.

🧪 Evaluation Metrics
Accuracy

Precision

Recall

F1-Score

Confusion Matrix


🖥️ Technologies Used
Languages: Python

Libraries: NumPy, Pandas, Scikit-learn, CatBoost, Flask

Tools: Jupyter Notebook, VS Code, GitHub


👩‍💻 Author
Shirani Agarwal

🌐 GitHub: (https://github.com/ShiraniAgarwal)

