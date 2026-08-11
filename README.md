# Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project analyzes customer demographic and spending behavior to identify meaningful customer segments using **K-Means Clustering**. The analysis explores relationships between age, annual income, spending score, and gender to understand different customer profiles and support targeted marketing strategies.

## 🎯 Objectives

- Perform exploratory data analysis on customer demographics and spending behavior.
- Identify customer groups using K-Means clustering.
- Determine suitable cluster counts using the Elbow Method.
- Perform univariate, bivariate, and multivariate clustering.
- Profile customer segments based on income, spending behavior, age, and gender.
- Generate business insights that can support customer-targeted marketing strategies.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Jupyter Notebook

## 🔍 Analysis Performed

### Exploratory Data Analysis
- Descriptive statistics
- Distribution analysis
- KDE plots
- Box plots
- Gender-wise analysis
- Correlation analysis
- Pairwise relationship analysis

### Customer Segmentation

K-Means clustering was applied at three levels:

1. **Univariate Clustering**
   - Annual Income

2. **Bivariate Clustering**
   - Annual Income
   - Spending Score

3. **Multivariate Clustering**
   - Age
   - Annual Income
   - Spending Score
   - Gender

### Model Selection

The **Elbow Method** was used with K-Means inertia scores to identify an appropriate number of clusters.

Feature scaling was performed using **StandardScaler** before multivariate clustering.
## 📊 Customer Segmentation Visualization

The bivariate K-Means clustering below shows customer segments based on **Annual Income** and **Spending Score**.

![Bivariate Customer Segmentation](./clustering_bivariate.png)

## 📊 Key Insights

The clustering analysis identifies distinct customer groups based on their income and spending behavior, including:

- High-income and high-spending customers
- High-income and low-spending customers
- Lower-income and high-spending customers
- Lower-income and low-spending customers
- Moderate-income and moderate-spending customers

These segments can help businesses develop more targeted marketing and customer engagement strategies.

## 📁 Project Structure

```text
Mall-Customer-Segmentation/
│
├── Mall_Customers.csv
├── Customer_Segmentation.ipynb
├── Clustering.csv
├── clustering_bivariate.png
└── README.md
