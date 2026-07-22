# NeuroFive ML Track

This repository contains my work for the **NeuroFive Solutions Machine Learning Fundamentals Internship**.

---

## Repository Structure

```text
neurofive-ml-track/
│
├── README.md
│
├── week1/
│   ├── train.csv
│   ├── Titanic_EDA.ipynb
│   └── Titanic_Data_Cleaning_Visualization.ipynb
│
└── week2/
    ├── train.csv
    ├── housing.csv
    ├── Titanic_Logistic_Regression.ipynb
    └── House_Price_Prediction_Linear_Regression.ipynb
```

---

# Week 1

## Task 1 - Exploratory Data Analysis (EDA)

- Loaded the Titanic dataset using Pandas
- Explored the dataset using `head()`, `info()`, and `describe()`
- Identified missing values
- Distinguished numerical and categorical features
- Summarized key findings

---

## Task 2 - Data Cleaning & Visualization

- Handled missing values
- Detected outliers using Box Plot
- Created:
  - Histogram
  - Box Plot
  - Bar Chart
  - Correlation Heatmap
- Analyzed feature relationships with survival

---

# Week 2

## Task 1 - Titanic Survival Prediction using Logistic Regression

In this task, I built my first machine learning classification model using the Titanic dataset.

### Steps Performed

- Removed unnecessary columns
- Filled missing values
- Encoded categorical features using `pd.get_dummies()`
- Split the dataset into training and testing sets
- Trained a Logistic Regression model
- Predicted passenger survival
- Evaluated the model using Accuracy Score and Confusion Matrix

### Results

- **Model:** Logistic Regression
- **Accuracy:** **79.89%**

### Conclusion

The Logistic Regression model achieved **79.89% accuracy** on the test dataset. The project demonstrates the complete machine learning classification workflow, including preprocessing, feature engineering, model training, prediction, and evaluation.

---

## Task 2 - House Price Prediction using Linear Regression

In this task, I built my first machine learning regression model using the California Housing dataset.

### Steps Performed

- Loaded the California Housing dataset
- Explored the dataset and identified missing values
- Filled missing values using the median
- Selected five numerical features
- Split the dataset into training and testing sets
- Trained a Linear Regression model
- Predicted house prices
- Evaluated the model using MAE, MSE, RMSE, and R² Score
- Visualized Actual vs Predicted House Prices

### Features Used

- Median Income
- Housing Median Age
- Total Rooms
- Latitude
- Longitude

### Results

- **Model:** Linear Regression
- **MAE:** 54,230.74
- **MSE:** 5,445,421,137.37
- **RMSE:** 73,793.10
- **R² Score:** 0.5844

### Conclusion

The Linear Regression model successfully learned the relationship between the selected housing features and house prices. The model achieved an **R² Score of 0.5844**, explaining approximately **58.44%** of the variation in house prices. This project demonstrates the complete machine learning regression workflow, including preprocessing, feature selection, model training, evaluation, and visualization.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Datasets

- Titanic - Machine Learning from Disaster
- California Housing Dataset

---

# Author

**Haider Ali**