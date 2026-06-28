# Credit_Card_Fraud_Detection
## Project Overview

Credit Card Fraud Detection is a machine learning project that identifies fraudulent credit card transactions and distinguishes them from genuine transactions. The model is trained on transaction data and uses classification techniques to detect suspicious activities.

## Objective

The objective of this project is to build a machine learning model that can accurately predict whether a credit card transaction is fraudulent or genuine.

## Dataset

The dataset contains transaction details with the target variable:

- 0 → Genuine Transaction
- 1 → Fraudulent Transaction

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Logistic Regression

## Project Workflow

### 1. Data Collection
- Loaded the credit card transaction dataset.

### 2. Data Preprocessing
- Removed unnecessary columns.
- Handled categorical variables using Label Encoding.
- Checked for missing values.

### 3. Feature Engineering
- Converted categorical data into numerical format.
- Selected relevant features for training.

### 4. Data Splitting
- Split the dataset into:
  - 80% Training Data
  - 20% Testing Data

### 5. Feature Scaling
- Applied StandardScaler to normalize numerical features.

### 6. Model Training
- Trained a Logistic Regression model with balanced class weights to handle class imbalance.

### 7. Model Evaluation
- Evaluated the model using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

### 8. Fraud Prediction
- Predicted whether a transaction is fraudulent or genuine.

## Model Performance

### Accuracy
- 94%

### Fraud Detection Recall
- 78%



| Actual Class | Predicted Genuine | Predicted Fraud |
|-------------|------------------|----------------|
| Genuine (0) | 103723 | 6995 |
| Fraud (1) | 92 | 334 |

### Key Results

- Successfully detected 334 fraudulent transactions.
- Achieved 78% fraud recall.
- Reduced the number of undetected fraud transactions.
