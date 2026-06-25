# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Overview

This project focuses on detecting fraudulent credit card transactions using **Machine Learning**. Due to the highly imbalanced nature of fraud detection datasets, **undersampling** was applied to balance the classes before training a **Logistic Regression** model.

The goal is to accurately classify transactions as **legitimate** or **fraudulent**, helping financial institutions identify suspicious activities efficiently.

---

## 🚀 Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Class imbalance handling using **Undersampling**
* Logistic Regression model training
* Model evaluation using accuracy score
* Fraud vs. Legitimate transaction classification

---

## 📂 Dataset

The project uses the **Credit Card Fraud Detection Dataset**, which contains anonymized credit card transactions.

### Dataset Characteristics

* 284,807 transactions
* 30 input features
* Binary classification
* Highly imbalanced dataset

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📊 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Handle Missing Values
5. Analyze Class Distribution
6. Perform Undersampling
7. Split Dataset into Training and Testing Sets
8. Train Logistic Regression Model
9. Evaluate Model Performance

---

## 📈 Model Used

* Logistic Regression

### Evaluation Metric

* Accuracy Score

---

## 📁 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── Credit_Card_Fraud_Detection.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
```

2. Navigate to the project folder

```bash
cd credit-card-fraud-detection
```

3. Install the required libraries

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook

```bash
jupyter notebook
```

5. Run all notebook cells.

---


## 📷 Results

The Logistic Regression model was trained on the balanced dataset obtained through undersampling and evaluated using classification accuracy.

---
