💳 Credit Card Fraud Detection using Machine Learning

📌 Project Overview

This project builds a machine learning model to detect fraudulent credit card transactions. Since fraud cases are very rare compared to legitimate transactions, this project focuses on handling an imbalanced dataset and evaluating models using appropriate classification metrics.

---

📊 Dataset

- Dataset: Credit Card Fraud Detection
- Features: 30 input features ("Time", "V1"–"V28", "Amount")
- Target: "Class"
  - "0" = Legitimate Transaction
  - "1" = Fraudulent Transaction

---

🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

📈 Exploratory Data Analysis

- Dataset overview
- Missing value analysis
- Class distribution visualization
- Feature scaling using StandardScaler

---

🤖 Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

📊 Model Performance

Random Forest (Best Model)

- Accuracy: 99.87%
- Precision (Fraud): 0.88
- Recall (Fraud): 0.74
- F1-Score (Fraud): 0.80
- ROC-AUC Score: 0.919

---

📁 Project Files

- "credit_card_fraud_detection.ipynb"
- "random_forest_model.pkl"
- "scaler.pkl"

---

🚀 Future Improvements

- Apply SMOTE and compare performance.
- Tune hyperparameters using GridSearchCV.
- Experiment with XGBoost and LightGBM.
- Build a simple web application for fraud prediction.

---

👨‍💻 Author

Abdul Wahab

Machine Learning Engineer
