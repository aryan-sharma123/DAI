# DAI
DAI-101 course

# Exploratory Data Analysis (EDA) for Stroke Prediction Dataset

## Introduction
This project performs an in-depth **Exploratory Data Analysis (EDA)** on a dataset related to stroke prediction. It includes **univariate and bivariate analysis**, data visualization, and statistical tests to understand patterns and relationships between variables.

## Dataset Overview
The dataset contains various features such as:
- **Demographic Information** (Age, Gender, Residence Type, etc.)
- **Health Indicators** (Hypertension, Heart Disease, BMI, etc.)
- **Lifestyle Factors** (Smoking Status, Work Type, etc.)
- **Target Variable:** `stroke` (0 = No Stroke, 1 = Stroke)

## EDA Steps Performed
### 1. **Data Preprocessing**
- Loaded the dataset
- Checked for missing values and handled them appropriately
- Converted categorical variables into appropriate formats
- Created **age bins** for analysis

### 2. **Univariate Analysis**
- **Numerical Features:**
  - Histograms and KDE plots to visualize distributions
  - Skewness calculation for each numerical column
- **Categorical Features:**
  - Bar plots and pie charts for feature distributions

### 3. **Bivariate Analysis**
- **Categorical vs Target Variable:**
  - Percentage of stroke cases in **each age group**
  - Stroke occurrence based on **gender**
  - Stroke percentages for different **smoking status**
  - Chi-Square test to check statistical dependence
- **Numerical vs Target Variable:**
  - Boxplots to analyze stroke trends with **age, BMI, and glucose levels**
  - Correlation heatmap

### 4. **Key Insights**
- Stroke risk increases significantly with **age**, especially in the **66+** age group.
- **Smokers** have a higher percentage of stroke cases than non-smokers.
- **Hypertension and heart disease** show a strong correlation with stroke occurrences.

## How to Run the Code
1. Install required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`
2. Run the Jupyter Notebook (`.ipynb` file) step by step
3. Explore visualizations and statistical outputs

## Files Included
- **Untitled.ipynb** → Jupyter Notebook with all EDA code
- **Dataset.csv** → Stroke dataset used for analysis (if applicable)
- **README.md** → This file

## Future Scope
- Perform feature engineering for better insights
- Train machine learning models to predict stroke occurrence
- Implement advanced statistical tests and feature selection

## Author
- **Your Name**

