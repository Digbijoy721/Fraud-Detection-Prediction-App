# Fraud Detection System

## 📌 Overview

This project is a **Machine Learning-based Fraud Detection System** developed using Python. It predicts whether a financial transaction is **fraudulent or legitimate** based on transaction details such as amount, type, and account balances.

The application also includes a **Streamlit web interface** for real-time prediction.

---

## 🚀 Features

* 🔍 Detects fraudulent transactions using an ML model
* 📊 Real-time prediction through user-friendly UI
* 🧠 Pre-trained machine learning pipeline
* ⚡ Fast and efficient predictions
* 📈 Handles structured transaction data

---

## 🛠️ Tech Stack

* Python
* Pandas
* Scikit-learn
* Joblib
* Streamlit

---

## 📂 Project Structure

```
├── fraud_detection.py              # Main Streamlit app
├── fraud_detection_pipeline.pkl   # Trained ML model
├── dataset.csv                     # Dataset used for training (optional)
├── README.md                       # Project documentation
```

---

## 🧠 Machine Learning Model

* Model trained using classification algorithms (e.g., Random Forest / Logistic Regression)
* Includes:

  * Data preprocessing
  * Feature engineering
  * Model training & evaluation

---

## 📊 Input Features

The model takes the following inputs:

* Transaction Type
* Amount
* Old Balance (Sender)
* New Balance (Sender)
* Old Balance (Receiver)
* New Balance (Receiver)

---

## 🔮 How It Works

1. User enters transaction details in the Streamlit app
2. Input is converted into a structured format (DataFrame)
3. Pre-trained ML model predicts the result
4. Output is displayed as:

   * 🚨 Fraudulent Transaction
   * ✅ Legitimate Transaction

---

## ▶️ How to Run the Project

### 1. Clone the Repository

```
git clone https://github.com/your-username/fraud-detection.git
cd fraud-detection
```

### 2. Install Dependencies

```
pip install -r requirements.txt
```

### 3. Run the Application

```
streamlit run fraud_detection.py
```

---

## 📈 Future Improvements

* Add model comparison
* Improve accuracy using advanced algorithms
* Deploy on cloud (Streamlit Cloud / Render)
* Add API integration (Flask/FastAPI)
* Visual dashboards for insights

---

## 🎯 Use Cases

* Banking fraud detection
* Online payment monitoring
* Financial risk analysis

---

## 👨‍💻 Author

Digbijoy Pandey
B.Tech Student | Python Developer | ML Enthusiast

---

## ⭐ Acknowledgment

Dataset and inspiration taken from real-world financial fraud detection problems.

---
