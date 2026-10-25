# Customer Churn Prediction & Retention Analysis

## Project Overview

This project focuses on predicting customer churn using machine learning. Customer churn refers to customers discontinuing a subscription or service. By identifying customers who may leave, businesses can take steps to improve customer satisfaction and retention.

The project uses the IBM Telco Customer Churn dataset to analyze customer information, train classification models, and suggest suitable retention strategies.

## Objectives

- Clean and preprocess the customer dataset.
- Perform Exploratory Data Analysis (EDA).
- Identify factors associated with customer churn.
- Build and compare three machine learning classification models.
- Evaluate models using different performance metrics.
- Predict customer churn risk and suggest retention actions.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset

The project uses the IBM Telco Customer Churn dataset, which contains customer demographics, account details, subscribed services, billing information, and churn status.

The target variable is `Churn`:
- `1` – Customer churned
- `0` – Customer did not churn

## Project Workflow

### 1. Data Collection
Load the customer churn dataset into Python using Pandas.

### 2. Data Cleaning
- Remove duplicate records.
- Convert numerical columns to the correct data type.
- Handle missing values.
- Encode the target variable.

### 3. Exploratory Data Analysis
Use charts and summary statistics to understand churn distribution and explore relationships between churn, monthly charges, and contract types.

### 4. Data Preprocessing
Separate the features and target variable, handle missing values, encode categorical columns, scale numerical features, and split the data into training and testing sets.

### 5. Model Training
Train and compare the following classification models:
- Logistic Regression
- Decision Tree
- Random Forest

### 6. Model Evaluation
Evaluate the models using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC score

### 7. Churn Prediction
Estimate the probability of churn for customers and categorize their risk as Low, Medium, or High.

### 8. Retention Recommendations
Suggest actions such as contacting high-risk customers, checking customer satisfaction, offering suitable plans, and providing regular customer support.

## Output Files

The project generates the following files:

- `cleaned_churn_dataset.csv` – Cleaned customer data.
- `model_comparison.csv` – Performance comparison of the models.
- `feature_importance.csv` – Important features identified by the selected model.
- `customer_churn_predictions.csv` – Customer churn predictions and retention recommendations.
- `project_summary.txt` – Summary of the project and model results.

## How to Run the Project

1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Open Jupyter Notebook.
4. Run the project code.
5. Review the charts, model evaluation results, and generated output files.

The dataset must be accessible through the configured download URL or placed in the notebook's working directory.

## Learning Outcomes

Through this project, I gained practical experience in data preprocessing, exploratory data analysis, classification algorithms, model evaluation, feature importance analysis, and applying machine learning to a business problem.

## Conclusion

This project demonstrates how machine learning can help businesses identify customers who may discontinue their services. The results can support targeted retention strategies and better customer relationship management. Model predictions should be evaluated carefully before being used for actual business decisions.

## Internship

**Organization:** Veda Technology  
**Project:** Customer Churn Prediction & Retention Analysis

## Author

Completed as part of a machine learning internship project at Veda Technology.
