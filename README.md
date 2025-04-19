# Bank-churn-analysis
This project analyzes customer data from a bank to understand the factors contributing to customer churn. By applying data cleaning techniques, univariate and bivariate analysis, and visualizations, the project aims to identify trends and patterns that influence whether a customer leaves the bank.

## 📊 Project Objectives

- Understand the distribution and characteristics of customer data
- Identify key factors contributing to customer churn
- Visualize trends and patterns in the data
- Lay the foundation for future predictive modeling (optional extension)

## 🗂️ Dataset Overview

- **Records**: 10,000 customer entries
- **Features**: 14 columns including:
  - Customer ID, Credit Score, Age, Gender, Tenure, Balance, Number of Products, Has Credit Card, Is Active Member, Estimated Salary, Geography, and Churn Status (`Exited`)

## 🔧 Tools and Technologies

- Python (Jupyter Notebook)
- Libraries:
  - `pandas` for data manipulation
  - `numpy` for numerical operations
  - `matplotlib` and `seaborn` for data visualization

## 🧹 Data Cleaning

- Checked for missing values (none found)
- Removed 13 duplicate records
- Verified data types and value ranges

## 📈 Exploratory Data Analysis

### 🔹 Univariate Analysis

- **Credit Score**: Mostly between 600 and 700
- **Age**: Right-skewed distribution; majority between 30–40
- **Balance**: Many customers had zero balance
- **Estimated Salary**: Uniform distribution across customers
- **Geography & Gender**: Majority from France; nearly equal male-female ratio

### 🔹 Churn-Based Insights

- **Balance vs. Churn**: Customers with higher balances tend to churn more
- **Estimated Salary vs. Churn**: No strong correlation observed

## 📌 Key Takeaways

- Age and balance appear to be important indicators of churn
- Uniform salary distribution suggests income alone isn't a strong churn factor
- Future steps could include building a predictive model using logistic regression, decision trees, or other classification algorithms



