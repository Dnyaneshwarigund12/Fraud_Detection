# 🕵️ Fraud Detection Prediction App

This project is a **Machine Learning–based Fraud Detection System** deployed with **Streamlit**.
It predicts whether a financial transaction is **fraudulent or legitimate** using a trained pipeline.

---

## 🚀 Features

* Interactive **Streamlit web app** for real-time fraud detection.
* Accepts transaction details (type, amount, balances) as input.
* Uses a **trained ML pipeline** for predictions.
* Provides clear alerts: ✅ Safe transaction | ❌ Fraudulent transaction.
* Includes **Jupyter Notebook** for model training and analysis.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy** – Data handling
* **Scikit-learn** – Model & pipeline
* **Joblib** – Model persistence
* **Streamlit** – Web app interface
* **Matplotlib, Seaborn** – Visualization (EDA)
* **Jupyter Notebook** – Model training & analysis

---

## 📂 Project Structure

```
fraud_detection_app/
│
├── fraud_detection.py              # Streamlit app for fraud prediction
├── analysis_model.ipynb            # Jupyter Notebook: data analysis & model training
├── fraud_detection_pipeline.pkl    # Trained ML pipeline (saved model)
├── requirements.txt                # Dependencies for running the project
└── README.md                       # Project documentation
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/fraud_detection_app.git
   cd fraud_detection_app
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:

   ```bash
   streamlit run fraud_detection.py
   ```

---

## 🖥️ Usage

1. Enter transaction details:

   * Transaction Type (PAYMENT, TRANSFER, CASH\_OUT, DEPOSIT)
   * Amount
   * Sender & Receiver Balances

2. Click **Predict**.

3. The app displays whether the transaction is likely **Fraudulent** or **Safe**.

---

## 📊 Model Training

The notebook `analysis_model.ipynb` includes:

* Data preprocessing
* Feature engineering
* Model training with Logistic Regression
* Evaluation and performance metrics

---

## 🔮 Future Improvements

* Support for multiple ML models.
* Explainability (SHAP, LIME).
* Cloud deployment (Streamlit Cloud, Heroku, AWS).
* API integration for real-time monitoring.

---

## 👩‍💻 Author

Developed by **\[Dnyaneshwari Gund ]** ✨


