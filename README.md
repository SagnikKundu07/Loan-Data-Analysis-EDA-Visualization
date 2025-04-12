![GitHub Banners (1)](https://github.com/user-attachments/assets/cfec18f0-2856-403f-9095-cd87ccb51b4e)


# Exploratory Data Analysis on Loan Dataset

Exploratory Data Analysis (EDA) is a critical step in understanding the structure, patterns, and nuances of a dataset. It forms the foundation for building effective machine learning models. This project documents the EDA process on a **Loan Dataset**, leveraging Python libraries for data transformation and visualization.

---

## Project Highlights

### 1.0 Overview

This notebook aims to:

- Identify categorical and numerical variables in the dataset
- Perform meaningful transformations on columns
- Visualize patterns through charts and graphs
- Handle missing data using appropriate imputation strategies
- Understand correlation between variables
- Handle categorical data for model readiness
- Perform binning and outlier detection
- Enable insights for business decision-making
- Conduct hypothesis testing

---

## 2.0 Column Transformation

- Convert categorical columns to numerical values
- Remove percentage symbols from relevant columns and convert them to numeric format

### Observations
Insights gathered from transformations are documented inline in the notebook.

---

## 3.0 Visualization

- Generate bar charts for all categorical variables to analyze frequency distributions

### Observations
Visual trends and anomalies identified from the charts.

---

## 4.0 Missing Value Imputation

### 4.1 Categorical Variables
- Identify missing columns
- Apply backward fill for imputation

### 4.2 Numerical Variables
- Identify missing columns
- Apply random sample imputation

### Observations
Missing value handling improved dataset quality for analysis and modeling.

---

## 5.0 Correlation Matrix

- Visualize correlation between numerical columns using a heatmap

### Observations
Helps identify highly correlated variables for potential feature selection or engineering.

---

## 6.0 Handling Categorical Data

- Apply One Hot Encoding (OHE) to convert categorical variables into machine-readable binary columns

---

## 7.0 Binning and Binarization

### 7.1 Quantile Binning
- Binning applied on `Debt.To.Income.Ratio` to categorize data into quantiles

### 7.2 Visualization
- Distribution of binned data visualized through plots

### Observations
Helps reduce noise and improve model interpretability.

---

## 8.0 Outlier Detection and Removal

- Analyze statistics: mean, mode, median, IQR
- Detect outliers via histograms
- Apply capping technique to handle outliers

### Observations
Outlier treatment resulted in better data distribution and model stability.

---

## 9.0 Business Decision Making: Visualization

Visualizations were created to uncover business insights from the data:

- States with the highest and lowest loan application counts
- Distribution of loan purposes
- Distribution of requested loan amounts
- Establish elationship between loan interest rate, debt to loan ratio and loan duration

### Observations
These visualizations support strategic decision-making in risk management and customer targeting.

---

## 10.0 Hypothesis Testing

- Understand business problem statement
- Perform hypothesis testing with Z-Test
- Validate result from dataset
- Concluded insights based on significance levels

---

## Final Words

This EDA exercise enables a comprehensive understanding of the loan dataset. It transforms raw data into actionable insights and prepares it for further modeling tasks. The process incorporates data cleaning, transformation, visualization, and statistical techniques to support informed decision-making.

---

**Technologies used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
