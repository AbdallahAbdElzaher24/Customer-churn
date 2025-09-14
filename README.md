# 📊 Customer Churn Prediction System 2025

## 📌 Overview
This project implements a **Customer Churn Prediction System** using **Artificial Neural Networks (ANN)**.  
The system predicts whether a customer is likely to exit (churn) or stay, helping businesses take proactive measures to improve **customer retention**.  

---

## 📊 Dataset
- Source: [Kaggle – Churn Modelling Dataset](https://www.kaggle.com/datasets/shubh0799/churn-modelling)  
- Records: **10,000+ customer entries**  
- Features: Demographics (Age, Gender, Geography), Banking details (Credit Score, Balance, Estimated Salary, etc.)  
- Target: **Exited (0 = Not Exited, 1 = Exited)**  
- Format: CSV file  

---

## 🛠️ Tech Stack
- **Python**  
- **TensorFlow / Keras**  
- **Scikit-learn**  
- **Pandas & NumPy**  
- **Matplotlib & Seaborn**  

---

## 🧬 Model Architecture
- **ANN Model**: Fully connected layers with Dropout & Batch Normalization  
- **Layers**:  
  - Input: 10 features  
  - Dense(10, activation='relu')  
  - Dropout(0.1) + BatchNormalization  
  - Dense(7, activation='relu')  
  - Dropout(0.1) + BatchNormalization  
  - Dense(1, activation='sigmoid')  

---

## 📈 Results
- **Training Accuracy**: 86%  
- **Validation Accuracy**: 84%  
- **Test Accuracy**: 83%  

Confusion Matrix:  

|                   | Predicted Not Exited | Predicted Exited |
|-------------------|----------------------|------------------|
| **Actual Not Exited** | TN = 2270            | FP = 230          |
| **Actual Exited**     | FN = 280             | TP = 720          |

