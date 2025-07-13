# Diabetes Classification - Statistical Learning Project

This project presents a statistical learning approach to predicting diabetes, using a dataset of Pima Indian women. The main goal is to develop and evaluate classification models capable of identifying diabetic individuals and understanding which medical and demographic features contribute most to diabetes risk.

## 📊 Overview

- **Dataset**: Pima Indians Diabetes Dataset ([Kaggle link](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset))
- **Population**: Females aged 21+ of Pima Indian heritage
- **Observations**: 768 examples, 9 variables
- **Target**: Binary classification (`Outcome`)

## 📈 Methods Used

- Logistic Regression (complete, forward, backward)
- Shrinkage methods: Ridge, Lasso
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- K-Nearest Neighbors (KNN)

## 🧠 Key Findings

- **Top predictors**:
  - Glucose level
  - BMI (Body Mass Index)
  - DiabetesPedigreeFunction (genetic factor)
  - Pregnancies (proxy for age)
- **Best models**:
  - Best accuracy: **KNN (k=28)** – *Accuracy: 0.7912*
  - Best sensitivity: **Ridge Regression** – *Sensitivity: 0.8246*
  - Best balanced model: **LDA**

## 📄 Authors

- Giulio Nebbiai – 2092296  
- Francesco Pio Pittorino – 2090920  
- Statistical Learning Course – 2022/2023

## 🔗 Resources

- Kaggle dataset: [https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)


