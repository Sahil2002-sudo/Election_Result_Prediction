# Election Results Prediction

**Dataset**: Election_Data.xlsx  
**Language**: Python  
**IDE**: Jupyter Notebook  

## Project Overview:
This project aims to predict the political party an individual will vote for based on their responses in an exit poll survey. The goal is to predict election results by analyzing these responses.

## Problem Type:
This is a **binary classification** problem, where we are predicting one of two possible outcomes.

## Steps Taken:

### 1. Data Import and Preparation:
- The data was loaded using Pandas.
- Performed initial data cleanup by checking for missing values and removing duplicates.

### 2. Exploratory Data Analysis (EDA):
- Conducted **univariate**, **bivariate**, and **multivariate** analysis to uncover patterns and insights in the data.

### 3. Data Preprocessing:
- **Outlier detection** and treatment were performed.
- Categorical variables were **encoded** and the data was **scaled** for better model performance.

### 4. Data Splitting:
- Split the data into **training** (70%) and **testing** (30%) sets.

### 5. Model Building:
- Built and trained multiple classification models, including:
  - Logistic Regression
  - LDA (Linear Discriminant Analysis)
  - KNN (K-Nearest Neighbors)
  - Naive Bayes
  - Random Forest
  - Gradient Boosting

### 6. Model Tuning:
- **Hyperparameter tuning** was done using **grid search** to improve the performance of the models.

### 7. Model Evaluation:
- Models were evaluated based on **accuracy** and **ROC AUC score** to determine which one performed best.

### 8. Insights:
- After training the models, we analyzed the results and drew conclusions from the most accurate models.

---

## Requirements:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

---

