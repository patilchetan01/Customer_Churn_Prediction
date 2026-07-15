# Customer_Churn_Prediction

# Customer Churn Prediction using Machine Learning

## Overview

Customer churn is a major challenge for businesses such as telecom companies, banks, and SaaS platforms. Retaining existing customers is often more cost-effective than acquiring new ones. This project builds a machine learning model to predict whether a customer is likely to stop using a service based on historical customer data.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and interpretation of results.

---

## Objectives

* Predict customer churn using machine learning.
* Identify the key factors that influence customer churn.
* Compare the performance of multiple classification algorithms.
* Help businesses make proactive customer retention decisions.

---

## Dataset

**Recommended Dataset:** IBM Telco Customer Churn Dataset

**Source:** Kaggle

Dataset contains information such as:

* Customer demographics
* Account details
* Service subscriptions
* Contract information
* Payment methods
* Monthly charges
* Total charges
* Churn status (Target Variable)

---

## Technologies Used

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## Project Structure

```text
Customer-Churn-Prediction/
│
├── data/
│   └── Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb
│
├── images/
│   ├── churn_distribution.png
│   ├── roc_curve.png
│   ├── feature_importance.png
│   └── confusion_matrix.png
│
├── models/
│   └── trained_model.pkl
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Prediction
10. Business Insights

---

## Exploratory Data Analysis

EDA was performed to identify important churn patterns.

Key findings include:

* Month-to-month contract customers have the highest churn rate.
* Customers with shorter tenure are more likely to leave.
* Higher monthly charges are associated with increased churn.
* Electronic check payment users tend to churn more frequently.
* Fiber optic internet customers show relatively higher churn.

---

## Machine Learning Models

The following classification models were implemented:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

---

## Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

---

## Sample Performance

| Model               |   Accuracy |     Recall |       ROC-AUC |
| ------------------- | ---------: | ---------: | ------------: |
| Logistic Regression |     79–82% |     58–65% |     0.83–0.85 |
| Random Forest       |     80–84% |     60–70% |     0.84–0.87 |
| XGBoost             | **82–86%** | **65–75%** | **0.86–0.90** |

> Results may vary depending on preprocessing, feature engineering, and hyperparameter tuning.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

Navigate to the project folder:

```bash
cd Customer-Churn-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
jupyter
```

Or install directly:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
```

---

## Business Insights

The model can help organizations:

* Identify customers likely to churn.
* Improve customer retention strategies.
* Reduce revenue loss.
* Design personalized offers for high-risk customers.
* Support data-driven business decisions.

---

## Future Improvements

* Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
* Cross-validation for more reliable model evaluation.
* Model deployment using Flask or FastAPI.
* Interactive dashboard using Streamlit.
* Automated retraining pipeline.
* Integration with real-time customer data.


## Acknowledgements

* IBM Telco Customer Churn Dataset
* Kaggle
* Scikit-learn
* XGBoost
* Open-source Python community
