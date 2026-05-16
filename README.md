# 🎓 Student Pass/Fail Prediction using Machine Learning

## 📌 Project Overview

This project is a machine learning-based classification system designed to predict whether a student will **Pass or Fail** based on academic performance indicators such as attendance, internal test scores, assignment marks, and daily study hours.

The goal is to demonstrate how data-driven approaches can be used in education to identify at-risk students and support early intervention strategies.

---

## 📊 Dataset Information

The dataset contains student academic records with the following features:

- Student ID
- Attendance (%)
- Internal Test 1 (out of 40)
- Internal Test 2 (out of 40)
- Assignment Score (out of 10)
- Daily Study Hours
- Final Exam Marks (out of 100)

---

## ⚙️ Workflow / Pipeline

The project follows a complete ML pipeline:

1. Import Libraries
2. Load Dataset
3. Check Missing Values
4. Data Preprocessing
5. Create Target Variable (Pass/Fail)
6. Feature Selection
7. Feature Scaling (Standardization)
8. Train-Test Split (80/20)
9. Model Training
10. Model Evaluation
11. Visualization
12. Feature Importance Analysis
13. Prediction Function
14. Best Model Selection

---

## 🤖 Machine Learning Models Used

The following classification algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

---

## 📈 Model Evaluation Metrics

Each model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- Actual vs Predicted Visualization

---

## 🏆 Best Performing Model

The best performing model was selected based on accuracy comparison across all models.

> ✔ Best Model: Logistic Regression (or update if yours differs)  
> ✔ Reason: Highest accuracy with balanced performance

---

## 📊 Visualizations Included

- Model Accuracy Comparison Bar Chart
- Confusion Matrix for all models
- Actual vs Predicted Graph
- Feature Importance (Decision Tree & Random Forest)
- Logistic Regression Coefficient Analysis

---

## 🔍 Feature Importance Insights

Feature analysis revealed that:

- Attendance (%) is the most influential factor
- Internal test scores strongly affect final performance
- Study hours significantly contribute to prediction accuracy
- Assignments also play a moderate role in performance prediction

---

## 🧠 Key Functional Feature

A unified prediction function was implemented to compare outputs from all models:

- Logistic Regression prediction
- Decision Tree prediction
- KNN prediction
- Random Forest prediction

This allows real-time comparison of model decisions.

---

## 📌 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 How to Run the Project

1. Clone the repository
```bash
git clone https://github.com/your-username/student-pass-fail-ml.git