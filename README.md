# Bank-Customer-Churn-Analysis

## Project Overview
Customer churn or customer attrition is the loss of customers and is one of the biggest issues facing the growth-plunged banks. In this project you will gain insight into customer characteristics that impact churn and possible remedial steps in relation to bank customers. Knowledge of such trends will assist the Banks in coming up with ways and means of holding on to important customers and cutting instances of attrition.

## Problem Statement
One of the persistent organizational problems among banks is that of customer attrition. Analytically, this project identifies essentials like credit score, location, age and balance to see which of these affects the decision of a customer to churn. Analyzing these variables, it is our intention to discover patterns valuable for customer retention.

## Dataset
Source: Kaggle
Description: The dataset includes features like credit score, geography, gender, age, tenure, balance, product count, credit card ownership, activity status, and estimated salary. The target variable is whether the customer has churned.

## Project Workflow

#### **1. Importing Libraries**
We utilize key libraries such as:
Pandas and NumPy for data manipulation and analysis.
Matplotlib and Seaborn for data visualization.
Warnings are also filtered to ensure cleaner output.

#### **2. Exploratory Data Analysis (EDA)**
EDA is performed to understand the characteristics of the data, including:
Data Cleaning: Handling missing values and data types.
Feature Analysis: Exploring individual features like age, geography, and balance to understand their distribution.
Correlation Analysis: Identifying relationships between features and churn.

#### **3. Data Preprocessing**
To prepare the data for modeling:
Encoding is applied to categorical features.
Scaling is used for numerical features to ensure uniformity across inputs.
Train-Test Split is performed to enable model evaluation.

#### **4. Model Training and Evaluation**
Several machine learning models are trained to predict customer churn, including:
Logistic Regression
Decision Trees
Random Forests
Gradient Boosting
Each model is evaluated based on accuracy, precision, recall, and F1-score to determine the most effective approach for predicting churn.

#### **5. Results and Insights**
The model performance is analyzed, and insights are provided on the top factors influencing customer churn. Recommendations are offered based on these insights to help reduce churn.

## Getting Started

#### **Prerequisites**
- Python 3.6+
- Jupyter Notebook
- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

#### **Installation**
To install the required libraries, run:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Running the Project

- Clone the repository.
- Open Bank Customer Churn Analysis.ipynb in Jupyter Notebook.
- Run each cell sequentially to replicate the analysis.

## Conclusion
This analysis provides a data-driven approach to understanding customer churn in the banking sector. By identifying key factors that lead to customer attrition, banks can implement targeted strategies to improve customer satisfaction and retention.

## Acknowledgements
The dataset is sourced from Kaggle, and we thank the contributors for making it publicly available.

## License
This project is licensed under the MIT License.
