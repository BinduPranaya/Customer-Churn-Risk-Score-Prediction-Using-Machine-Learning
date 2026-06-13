# Customer Churn Risk Score Prediction Using Machine Learning

## Overview

Customer churn is one of the biggest challenges faced by subscription-based and service-oriented businesses. Losing existing customers directly impacts revenue and growth. This project predicts the probability of a customer leaving a company (churn) and assigns a churn risk score using machine learning techniques.

The system analyzes customer demographics, account information, service usage patterns, and contract details to identify customers who are likely to churn. Businesses can use these insights to take proactive retention measures and improve customer satisfaction.

---

## Problem Statement

Acquiring a new customer is significantly more expensive than retaining an existing one. Therefore, companies need an efficient way to identify customers who are at risk of leaving.

The objective of this project is to:

* Predict whether a customer will churn or not.
* Generate a churn risk score.
* Identify important factors contributing to churn.
* Help businesses improve customer retention strategies.

---

## Dataset

The dataset contains customer-related information such as:

* Customer ID
* Gender
* Senior Citizen Status
* Tenure
* Contract Type
* Internet Service
* Monthly Charges
* Total Charges
* Payment Method
* Customer Support Usage
* Churn Status

Target Variable:

* Churn (Yes/No)

---

## Project Workflow

### 1. Data Collection

Customer data is collected from the dataset and loaded into the analysis environment.

### 2. Data Preprocessing

* Handling missing values
* Removing duplicate records
* Encoding categorical variables
* Feature scaling
* Data type conversion

### 3. Exploratory Data Analysis (EDA)

Performed detailed analysis to understand:

* Churn distribution
* Customer demographics
* Service usage patterns
* Correlation between features
* Important churn indicators

### 4. Feature Engineering

Created and transformed features to improve model performance.

### 5. Model Building

Machine learning algorithms used:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost (optional enhancement)

### 6. Model Evaluation

Performance metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

### 7. Risk Score Generation

The model outputs a churn probability which is converted into a risk score ranging from 0 to 100.

Risk Categories:

| Score Range | Risk Level  |
| ----------- | ----------- |
| 0 - 30      | Low Risk    |
| 31 - 70     | Medium Risk |
| 71 - 100    | High Risk   |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Structure

```text
Customer-Churn-Risk-Prediction/
│
├── data/
│   └── customer_data.csv
│
├── notebooks/
│   └── churn_prediction.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── images/
│   └── visualizations
│
├── requirements.txt
├── README.md
└── app.py
```

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project folder:

```bash
cd Customer-Churn-Risk-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python app.py
```

---

## Results

The model successfully predicts customer churn and provides a churn risk score that can help organizations:

* Reduce customer loss
* Improve retention strategies
* Increase customer lifetime value
* Optimize marketing campaigns

---

## Future Enhancements

* Streamlit Web Application
* XGBoost Model Integration
* SHAP Explainability
* Real-Time Predictions
* Cloud Deployment
* Automated Model Retraining

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Machine Learning
* Model Evaluation
* Predictive Analytics
* Business Intelligence

---

## Author

Bindu Mogilicherla

Aspiring AI & ML Engineer passionate about solving real-world business problems using Machine Learning and Data Science.
