# 🧠 Customer Churn Prediction using Artificial Neural Networks (ANN)

Predicting whether a customer will leave a bank — before they actually do — is a powerful tool for improving customer retention and increasing profitability. This project uses a deep learning approach with an ANN to build a predictive model using customer profile data.

---

## 🚀 Project Overview

This project demonstrates how to:

- Preprocess raw customer data using label encoding, one-hot encoding, and feature scaling
- Build a deep learning model with TensorFlow/Keras
- Evaluate and tune the model
- Save and serialize the model and preprocessing tools for future inference
- Visualize training performance using TensorBoard

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**, **NumPy**, **Scikit-learn**
- **TensorFlow / Keras**
- **TensorBoard** (for visualization)
- **Pickle** (for saving model components)
- **Matplotlib / Seaborn** (optional for EDA)
- **Streamlit** (for UI deployment – coming soon!)

---



## 📈 Results

- Training Accuracy: ~87%
- Validation Accuracy: ~86%
- Binary classification (Churn / Not Churn)

---

## 🗃️ Preprocessing & Assets

| Asset | Description |
|-------|-------------|
| `model.h5` | Trained ANN model |
| `scaler.pkl` | StandardScaler used for input normalization |
| `label_encoder_gender.pkl` | LabelEncoder used for gender |
| `onehot_encoder_geo.pkl` | OneHotEncoder used for geography |
| `logs/` | TensorBoard logs for model training |

---

## 📊 Sample Features Used

| Feature              | Description                             |
|----------------------|-----------------------------------------|
| CreditScore          | Customer creditworthiness               |
| Age                  | Customer age                            |
| Balance              | Account balance                         |
| NumOfProducts        | Products held by customer               |
| IsActiveMember       | Whether customer is active              |
| Geography (One-Hot)  | France, Germany, Spain (encoded)        |
| Gender (Label Encoded) | Male/Female                            |

---


