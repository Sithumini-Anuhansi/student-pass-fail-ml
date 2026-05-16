# 🎓 Student Pass/Fail Prediction using Machine Learning

## 📌 Project Overview

This project applies Machine Learning techniques to predict whether a student will **Pass** or **Fail** based on academic performance indicators such as:

* Attendance Percentage
* Internal Test Scores
* Assignment Marks
* Daily Study Hours

The project was developed as part of an ML task to demonstrate the complete machine learning workflow including preprocessing, model training, evaluation, visualization, cross-validation, and hyperparameter tuning.

---

## 🎯 Objectives

* Build a supervised machine learning classification system
* Compare multiple ML algorithms
* Evaluate model performance using different techniques
* Select the best performing model
* Visualize prediction results
* Improve performance using tuning techniques

---

## 🤖 Machine Learning Models Used

The following classification algorithms were implemented and compared:

1. Logistic Regression
2. Decision Tree
3. K-Nearest Neighbors (KNN)
4. Random Forest

Different models were used to compare various learning approaches:

* Linear learning
* Rule-based learning
* Distance-based learning
* Ensemble learning

---

## ⚙️ Technologies & Libraries

### Languages

* Python

### Libraries

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* Google Colab

---

## 📂 Project Structure

```bash id="1kq2pi"
student-pass-fail-ml/
│
├── data/
│   └── Final_Marks_Data.csv
│
├── notebooks/
│   └── ML_Task.ipynb
│
├── images/
│   ├── model-accuracy-comparison.png
│   ├── confusion-matrix-logistic-regression.png
│   ├── confusion-matrix-decision-tree.png
│   ├── confusion-matrix-knn.png
│   ├── actual-vs-predicted.png
│   └── feature-importance-decision-tree.png
│
├── README.md
└── report.pdf
```

---

## 🔄 Machine Learning Workflow

### 1️⃣ Import Libraries

Imported required libraries for:

* Data processing
* Visualization
* Model building
* Evaluation

### 2️⃣ Upload Dataset

Dataset uploaded dynamically using Google Colab.

### 3️⃣ Data Overview

Performed:

* Dataset inspection
* Data type checking
* Missing value checking

### 4️⃣ Create Target Variable

Created binary classification target:

* Pass = 1
* Fail = 0

### 5️⃣ Feature Selection

Selected relevant academic performance features.

### 6️⃣ Feature Scaling

Used `StandardScaler()` to normalize feature values.

### 7️⃣ Train-Test Split

Dataset divided into:

* 70% Training Data
* 30% Testing Data

### 8️⃣ Model Training

Trained all four machine learning models.

### 9️⃣ Model Evaluation

Evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Actual vs Predicted Graphs

### 🔟 Cross Validation

Applied 5-Fold Cross Validation to verify model stability.

### 1️⃣1️⃣ Hyperparameter Tuning

Used `GridSearchCV` to optimize model parameters and improve performance.

### 1️⃣2️⃣ Feature Importance

Analyzed the influence of features on predictions.

### 1️⃣3️⃣ Best Model Selection

Compared:

* Original Accuracy
* Cross Validation Score
* Tuned Accuracy

Selected the best overall model based on combined performance.

---

## 📊 Final Model Performance

| Model               | Original Accuracy | CV Mean Score | Tuned Accuracy |
| ------------------- | ----------------- | ------------- | -------------- |
| Logistic Regression | ~0.95             | ~0.95         | ~0.95          |
| Decision Tree       | ~0.91             | ~0.91         | ~0.94          |
| KNN                 | ~0.93             | ~0.94         | ~0.94          |
| Random Forest       | ~0.94             | ~0.94         | ~0.95          |

---

## 🏆 Best Model

### ✅ Logistic Regression

Selected because it showed:

* Highest overall accuracy
* Strong cross-validation performance
* Better stability and generalization ability

---

## 📈 Visualizations Included

* Accuracy Comparison Chart
* Confusion Matrices
* Actual vs Predicted Results
* Feature Importance Graphs

---

## 📌 Key Findings

* Attendance and Internal Test Scores were the strongest predictors of student success.
* Cross-validation improved confidence in model reliability.
* Hyperparameter tuning improved model performance and optimization.

---

## 🚀 How to Run the Project

### Clone Repository

```bash id="j12bux"
git clone https://github.com/Sithumini-Anuhansi/student-pass-fail-ml.git
```

### Open Project

```bash id="uvfskm"
cd student-pass-fail-ml
```

### Run Notebook

Open:

```bash id="z7mlgv"
notebooks/ML_Task.ipynb
```

Run all cells in Google Colab or Jupyter Notebook.

---

## 📌 Conclusion

This project successfully demonstrates the practical application of machine learning for predicting student academic outcomes. By comparing multiple models, applying cross-validation, and performing hyperparameter tuning, a reliable and accurate prediction system was developed.

---

## 👩‍💻 Author

### Sithumini Anuhansi

Software Engineering Undergraduate – NIBM Sri Lanka
