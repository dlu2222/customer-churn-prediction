# 📊 Customer Churn Prediction | Machine Learning

> An end-to-end machine learning project for identifying telecom customers at risk of churn and translating customer data into actionable retention insights.

## 🎯 Business Problem

Customer churn directly impacts recurring revenue and customer acquisition costs in the telecommunications industry.

The objective of this project is to analyze customer behavior and build a machine learning solution capable of identifying customers who are more likely to leave.

The project explores the question:

**Can customer demographics, service usage, contract information, and billing behavior be used to predict customer churn?**

---

## 📌 Project Highlights

- Analyzed **7,032 customer records**
- Explored **20 customer and service-related variables**
- Performed exploratory data analysis and preprocessing
- Built and compared **4 classification models**
- Evaluated models using Accuracy, Precision, Recall, F1-score, and Confusion Matrix
- Achieved a best accuracy of **78.75%**
- Identified **Logistic Regression** as the strongest model based on accuracy

---

## 📂 Dataset

The dataset contains customer-level information from a telecommunications company.

Key feature groups include:

**Customer Profile**
- Gender
- Senior Citizen
- Partner
- Dependents

**Customer Relationship**
- Tenure
- Contract Type

**Services**
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming Services

**Billing**
- Monthly Charges
- Total Charges
- Payment Method
- Paperless Billing

**Target Variable**

`Churn` — indicates whether a customer left the company.

### Class Distribution

- Non-churn customers: **5,163**
- Churn customers: **1,869**

---

## 🔍 Exploratory Data Analysis

Exploratory Data Analysis (EDA) was conducted to understand the structure of the data and investigate patterns associated with customer churn.

The analysis included:

- Churn distribution
- Customer tenure
- Contract characteristics
- Monthly and total charges
- Service subscriptions
- Customer characteristics
- Relationships between customer attributes and churn

Visualizations were created using **Matplotlib** and **Seaborn** to support data-driven interpretation.

---

## ⚙️ Machine Learning Workflow

The project follows an end-to-end machine learning workflow:

**Data → Exploration → Preprocessing → Feature Transformation → Train/Test Split → Model Training → Evaluation → Model Comparison**

The preprocessing stage prepared categorical and numerical variables for machine learning and ensured that the models were trained on structured, usable data.

---

## 🤖 Models Evaluated

Four classification algorithms were implemented and compared:

1. **Logistic Regression**
2. **Decision Tree**
3. **Random Forest**
4. **XGBoost**

Using multiple algorithms allowed the project to compare a simple interpretable baseline with more complex tree-based ensemble methods.

---

## 📈 Model Performance

| Model | Accuracy |
|---|---:|
| **Logistic Regression** | **78.75%** |
| Random Forest | 78.25% |
| XGBoost | 77.40% |
| Decision Tree | 71.07% |

### 🏆 Best Model: Logistic Regression

Logistic Regression achieved the highest overall accuracy at **78.75%**.

An important finding is that the more complex ensemble models did not outperform the simpler Logistic Regression model on this dataset.

This demonstrates an important machine learning principle:

> **Model complexity does not automatically guarantee better predictive performance.**

---

## 📊 Evaluation Strategy

The models were evaluated using multiple classification metrics rather than relying only on model training results.

Evaluation included:

- Accuracy
- Precision
- Recall
- F1-score
- Classification Report
- Confusion Matrix

This provides a more complete understanding of model behavior, particularly because churn prediction involves an imbalanced target distribution.

---

## 💡 Business Value

A churn prediction model can support customer-retention strategies by helping organizations identify customers who may require attention before they leave.

Potential applications include:

- Prioritizing customers for retention campaigns
- Supporting targeted customer offers
- Identifying high-risk customer segments
- Improving customer relationship management
- Reducing preventable customer loss

The model should therefore be viewed as a **decision-support tool** rather than only a classification exercise.

---

## 🛠️ Tech Stack

**Language**
- Python

**Data Analysis**
- Pandas
- NumPy

**Visualization**
- Matplotlib
- Seaborn

**Machine Learning**
- Scikit-learn
- XGBoost

**Environment**
- Google Colab
- Jupyter Notebook

**Version Control**
- Git
- GitHub

---

## 📁 Repository Structure

```text
customer-churn-prediction/
│
├── project.ipynb
│   └── Complete analysis, preprocessing, modeling, and evaluation
│
├── Telco-Customer-Churn.csv
│   └── Original customer churn dataset
│
├── Customer Churn Prediction-Machine Learning1.docx
│   └── Project documentation and report
│
└── README.md
    └── Project overview and results
```

---

## 👩‍💻 Author

**Dalia Alqahtani**  
Data Science | University of Jeddah

Interested in applying data analytics and machine learning to solve real-world business problems.
