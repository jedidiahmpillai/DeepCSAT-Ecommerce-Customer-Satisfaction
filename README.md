# DeepCSAT – Ecommerce Customer Satisfaction Prediction

## 📌 Project Overview
This project predicts customer satisfaction (CSAT Score) using ecommerce customer support data.

Due to severe class imbalance in the original 1–5 rating scale, the problem was converted into a binary classification problem:
- 1 → Satisfied (CSAT ≥ 4)
- 0 → Not Satisfied (CSAT < 4)

## 🧠 Machine Learning Approach
- Data Cleaning & Preprocessing
- Handling Missing Values
- One-Hot Encoding of Categorical Variables
- Train-Test Split with Stratification
- Random Forest Classification
- Handling Class Imbalance using class_weight='balanced'

## 📊 Model Performance
- Accuracy: ~86%
- Dataset is highly imbalanced.
- Model struggles to predict minority class due to limited examples.

## 🔍 Key Learning
- Handling imbalanced datasets
- Feature engineering
- Model evaluation beyond accuracy
- Real-world ML challenges

## 🚀 Future Improvements
- Add sentiment analysis using Customer Remarks
- Use SMOTE for oversampling
- Hyperparameter tuning
