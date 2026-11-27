=# Telco Customer Churn Prediction

## 1. Project Overview

This project develops a machine learning classification system to predict customer churn in the telecommunications industry.

The objective is to identify customers who are likely to discontinue their services and investigate the characteristics associated with customer churn.

Three classification algorithms are implemented and compared:

- Logistic Regression
- Random Forest
- XGBoost

The project follows a complete machine learning workflow, from data exploration and preprocessing to model evaluation and interpretation.

## 2. Dataset

**Dataset:** Telco Customer Churn

**Source:** IBM Telco Customer Churn Dataset

**Observations:** 7,043 customers

**Original Features:** 20 input and target columns, plus the customer identifier.

The dataset contains information about:

- Customer demographics
- Account information
- Internet and telephone services
- Contract types
- Billing and payment methods
- Customer churn status

**Target Variable:** Churn

- 0 = No Churn
- 1 = Churn

The original dataset contains approximately 73.46% non-churning customers and 26.54% churning customers.

## 3. Technologies and Libraries

The project uses Python and the following libraries:

- NumPy — Numerical computations
- Pandas — Data manipulation and analysis
- Matplotlib — Data visualization
- Seaborn — Statistical visualization
- Scikit-learn — Preprocessing, pipelines, and machine learning
- XGBoost — Gradient boosting classification

## 4. Project Methodology

The analysis follows seven stages:

### Stage 1 — Data Understanding & Initial Inspection
- Dataset structure and dimensions
- Data types and descriptive statistics
- Missing values and unique values

### Stage 2 — Exploratory Data Analysis (EDA)
- Univariate analysis
- Bivariate analysis
- Numerical and categorical distributions
- Correlation analysis
- Data visualization

### Stage 3 — Data Cleaning
- Handling missing values
- Correcting data types
- Removing irrelevant identifiers
- Creating a binary target variable

### Stage 4 — Feature Engineering & Preprocessing
- Numerical and categorical feature identification
- One-Hot Encoding
- Standard Scaling
- Train-test splitting
- ColumnTransformer and Pipeline

### Stage 5 — Model Training
- Logistic Regression
- Random Forest
- XGBoost

### Stage 6 — Model Evaluation
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrices
- Classification reports
- Model comparison

### Stage 7 — Interpretation & Final Project
- Feature importance and model coefficients
- Interpretation of influential predictors
- Business insights and recommendations
- Final conclusions and documentation

## 5. Model Performance

The three classification models were evaluated using the same test dataset.

| Model | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|---|---|---|---|---|---|
| Logistic Regression | To be added | To be added | To be added | To be added | To be added |
| Random Forest | To be added | To be added | To be added | To be added | To be added |
| XGBoost | To be added | To be added | To be added | To be added | To be added |

**Selected Model:** Logistic Regression (highest F1-score in the current evaluation).

## 6. Key Findings

The Logistic Regression coefficients highlighted several influential predictors:

- Customer tenure had the strongest negative coefficient.
- Month-to-month contracts were associated with higher predicted churn odds.
- Two-year contracts were associated with lower predicted churn odds.
- Internet service type contributed to churn predictions.
- Billing-related variables also showed relevant associations.

These findings describe predictive associations rather than causal relationships.

## 7. Business Recommendations

Potential customer retention strategies include:

- Monitoring customers with short tenure.
- Encouraging longer-term contracts.
- Investigating customer satisfaction with fiber optic services.
- Reviewing billing and pricing strategies.
- Improving technical support and customer service.

## 8. Limitations and Future Improvements

Potential future improvements include:

- Hyperparameter optimization.
- Cross-validation.
- Class imbalance handling.
- Classification threshold optimization.
- SHAP-based model interpretation.
- Evaluation using additional and more recent customer data.

## 9. Repository Structure

```text
Project_03_Customer_Churn/
│
├── 01_Customer_Churn_Analysis.ipynb
├── README.md
└── requirements.txt
```

## 10. How to Run the Project

1. Clone the repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Select the appropriate Python environment.
5. Execute the notebook cells sequentially.

Install dependencies using:

```bash
pip install -r requirements.txt
```

## 11. Conclusion

This project demonstrates the application of supervised machine learning techniques to customer churn prediction.

It combines exploratory data analysis, data preprocessing, classification algorithms, model evaluation, and model interpretation to develop a data-driven approach to understanding customer retention.