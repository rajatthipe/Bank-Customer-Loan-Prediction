# Bank-Customer-Loan-Prediction (Accuracy of the model = 87%)

## Introduction

Loan default prediction is a crucial task for financial institutions. This project provides a practical implementation of logistic regression for this purpose. By accurately predicting loan defaults, banks can minimize financial risks and make more informed lending decisions.

## Dataset

The dataset used in this project should be described here. Include details such as:

*   **Source:** Where did the data come from (e.g., Kaggle, UCI Machine Learning Repository, internal data)?
*   **Description:** A brief explanation of the data and its features.
*   **Features:** List the features (columns) in the dataset and their descriptions.
*   **Target Variable:** Clearly identify the target variable (the one you're trying to predict), e.g., "loan default" (0 or 1).

**Example:**

The dataset used in this project is a synthetic dataset generated for demonstration purposes. It contains the following features:

*   `age`: Age of the customer.
*   `income`: Annual income of the customer.
*   `loan_amount`: Amount of the loan requested.
*   `credit_score`: Credit score of the customer.
*   `employment_length`: Length of employment in years.
*   `default`: Target variable (1 if the customer defaulted on the loan, 0 otherwise).

## Methodology

The project follows these steps:

1.  **Data Preprocessing:**
    *   Handling missing values.
    *   Encoding categorical features.
    *   Feature scaling.
    *   Handling class imbalance.
2.  **Model Training:** Training a logistic regression model on the preprocessed data.
3.  **Model Evaluation:** Evaluating the model's performance on a held-out test set using metrics like precision, recall, F1-score, and AUC-ROC.

## Requirements

*   Python 3.x
*   Pandas
*   NumPy
*   Scikit-learn
*   Imbalanced-learn 
*   Scipy
