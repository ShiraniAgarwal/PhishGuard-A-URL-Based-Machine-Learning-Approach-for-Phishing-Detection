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
│<br>
├── app.py # Flask web app for prediction      <br>
├── main.py # Main ML training and evaluation script      <br>
├── phishing-detection.ipynb # Jupyter notebook with feature extraction & modeling     <br>
├── requirements.txt # Python dependencies     <br>
├── README.md # Project documentation        <br>
├── .gitignore # Files/folders ignored by Git    <br>
└── LICENSE # Project license         <br>

## 🧩 How to Run Locally

### Step 1: Clone the Repository <br>
git clone "(https://github.com/ShiraniAgarwal/PhishGuard-A-URL-Based-Machine-Learning-Approach-for-Phishing-Detection/)"  <br>
Step 2: Navigate to the Project Folder<br>
bash   <br>
  cd PhishGuard-A-URL-Based-Phishing-Detection    <br>
Step 3: Install Dependencies    <br>
bash        <br>
  pip install -r requirements.txt      <br>
Step 4: Run the Flask App      <br>
bash      <br>
  python app.py    <br>

## 🧪 Evaluation Metrics:<br>
    Accuracy<br>
    Precision<br>
    Recall<br>
    F1-Score<br>
    Confusion Matrix<br>


## 🖥️ Technologies Used <br>
    Languages: Python<br>
    Libraries: NumPy, Pandas, Scikit-learn, CatBoost, Flask<br>
    Tools: Jupyter Notebook, VS Code, GitHub<br>


## 👩‍💻 Author <br>
   Shirani Agarwal

## 🌐 GitHub: <br>
(https://github.com/ShiraniAgarwal)
<br>

## 🪪 License <br>

This project is licensed under the MIT License.

