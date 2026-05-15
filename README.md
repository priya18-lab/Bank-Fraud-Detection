# Bank Fraud Detection using Machine Learning

## Project Overview

This project is an AI-based Bank Fraud Detection System developed using Machine Learning techniques. The system detects fraudulent banking transactions in real time and helps reduce financial losses caused by fraud activities.

The project uses transaction data and machine learning algorithms such as Logistic Regression, Random Forest, and XGBoost to classify transactions as fraudulent or legitimate.

---

## Features

- Fraud transaction detection
- Real-time prediction system
- Machine Learning model training
- Data preprocessing and feature scaling
- SMOTE for handling imbalanced data
- Model evaluation using confusion matrix and accuracy
- FastAPI deployment support
- Streamlit dashboard support

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SMOTE
- FastAPI
- Streamlit
- Joblib
- SHAP

---

## Dataset

Dataset used:
Credit Card Fraud Detection Dataset from Kaggle

Link:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## Project Structure

```text
Bank_fraud_detection1
│
├── data
│   └── creditcard.csv
│
├── notebooks
│   └── fraud_detection.ipynb
│
├── models
│   └── fraud_model.pkl
│
├── app
│   └── app.py
│
├── requirements.txt
│
├── README.md
│
└── .gitignore
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Bank-Fraud-Detection.git
```

---

### Create Virtual Environment

```bash
python -m venv venv
```

---

### Activate Environment

```bash
venv\Scripts\activate
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Jupyter Notebook

```bash
jupyter notebook
```

---

## Model Training

The model is trained using Logistic Regression and evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Sample Output

Accuracy: 94%

Confusion Matrix:

```text
[[56000   800]
 [  900 55000]]
```

---

## Future Improvements

- Deep Learning integration
- Graph Neural Networks
- Real-time streaming fraud detection
- Federated learning
- Cloud deployment with AWS

---

## Applications

- Banking systems
- Online payment gateways
- E-commerce fraud detection
- Insurance claim fraud detection
- Cryptocurrency transaction monitoring

---

## Conclusion

This project successfully demonstrates how Machine Learning can improve fraud detection accuracy and reduce financial losses in digital banking systems.

---

## Author

Priya C
