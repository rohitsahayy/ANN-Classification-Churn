# ANN-Classification-Churn

# 🔍 Customer Churn Classification using ANN

This project aims to predict customer churn in a bank using an Artificial Neural Network (ANN). Churn prediction helps businesses retain valuable customers by identifying those likely to leave based on behavioral and demographic factors.

---

## 📂 Project Contents

- `Churn_Modelling.csv` – Dataset containing customer records.
- `1ModelBuilding.ipynb` – Main notebook for data preprocessing, model building, training, and evaluation.
- `2Prediction.ipynb` – Notebook for loading the trained model and making predictions.
- `requirements.txt` – Dependencies for running the project.
- `README.md` – Project overview and instructions.

---

## 🧠 Problem Statement

Predict whether a bank customer will **churn (exit)** or not, based on features like age, balance, number of products, tenure, and more.

- **Target Variable:** `Exited`
- **Type:** Binary Classification

---

## 📊 Dataset Overview

- Source: [`Churn_Modelling.csv`](https://www.kaggle.com/datasets/shubhendra7/customer-churn-prediction)
- 10,000 customer records with 12 features + target
- Key Features:
  - `CreditScore`, `Geography`, `Gender`, `Age`, `Tenure`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`

---

## 🏗️ Model Architecture

Implemented using **TensorFlow (Keras)**:
- **Input Layer**: 12 features
- **Hidden Layers**:
  - Dense Layer (16 units, ReLU)
  - Dense Layer (8 units, ReLU)
- **Output Layer**: 1 unit (Sigmoid)
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam
- **Metrics**: Accuracy

---

## 🚀 Getting Started

### 📌 1. Clone the Repository
```bash
git clone https://github.com/yourusername/churn-ann.git
cd churn-ann
