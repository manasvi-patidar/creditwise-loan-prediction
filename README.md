# 💳 CreditWise – Intelligent Loan Approval & Risk Prediction System

A Machine Learning-based classification project that predicts loan approval outcomes by analysing applicants' personal, financial, employment, and credit-related information.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Problem Statement](#-problem-statement)
- [Dataset Description](#-dataset-description)
- [Machine Learning Algorithms](#-machine-learning-algorithms)
- [Model Evaluation](#-model-evaluation)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [Author](#-author)

---

## 📌 Overview

CreditWise is a Supervised Machine Learning project designed to predict whether a loan application should be **Approved or Rejected**.

The system analyses historical loan application data and identifies patterns in applicants' financial backgrounds, credit scores, employment status, income, and other relevant attributes.

The project explores different classification algorithms and evaluates their performance to identify a suitable model for loan approval prediction.

## 🎯 Problem Statement

Traditional loan verification is time-consuming and inconsistent, leading to the rejection of creditworthy applicants and approval of high-risk applicants.

**CreditWise** aims to address this by using Machine Learning to predict loan approval outcomes based on applicants' financial, employment, and credit-related information before final human verification.

## 🗂️ Dataset Description

- **Records:** 1,000
- **Features:** 20 columns
- **Target Variable:** `Loan_Approved`
- **Problem Type:** Binary Classification

## 🤖 Machine Learning Algorithms

The following Supervised Learning classification algorithms were implemented:

| Algorithm                 | Description                             |
| ------------------------- | --------------------------------------- |
| Logistic Regression       | Linear classification algorithm         |
| K-Nearest Neighbors (KNN) | Distance-based classification algorithm |
| Gaussian Naive Bayes      | Probabilistic classification algorithm  |

## 📈 Model Evaluation

Models were evaluated using the following metrics:

- Accuracy: Overall prediction correctness.
- Precision: Correct positive predictions.
- Recall: Actual positives correctly identified.
- F1-Score: Balance between precision and recall.
- Confusion Matrix: Summary of correct and incorrect predictions.

### 📊 Final Model Performance

The following results were obtained after feature engineering:

| Algorithm            | Accuracy | Precision | Recall | F1-Score |
| -------------------- | -------: | --------: | -----: | -------: |
| Logistic Regression  |   88.00% |    78.46% | 83.61% |   80.95% |
| KNN                  |   78.50% |    67.31% | 57.38% |   61.95% |
| Gaussian Naive Bayes |   86.00% |    81.13% | 70.49% |   75.44% |

### 🏆 Best Performing Model

**Gaussian Naive Bayes** achieved the highest Precision (81.13%), while **Logistic Regression** achieved the highest Accuracy (88%) and F1-Score (80.95%).

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

## 📁 Project Structure

```text
CreditWise/
│
├── data/
│   ├── raw/
│   │   └── loan_approval_data.csv
│   └── processed/
│
├── docs/
│   └── DATASET.md
│
├── notebook/
│   └── loan_approval_prediction.ipynb
│
├── .gitignore
├── README.md
└── requirements.txt
```

## 👩‍💻 Author

**Manasvi Patidar**

---
