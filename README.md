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
    └── Titanic_Logistic_Regression.ipynb
```

---

## Week 1

### Task 1 - Exploratory Data Analysis (EDA)

- Loaded the Titanic dataset using Pandas
- Explored the dataset using `head()`, `info()`, and `describe()`
- Identified missing values
- Distinguished numerical and categorical features
- Summarized key findings

### Task 2 - Data Cleaning & Visualization

- Handled missing values
- Detected outliers using Box Plot
- Created:
  - Histogram
  - Box Plot
  - Bar Chart
  - Correlation Heatmap
- Analyzed feature relationships with survival

---

## Week 2

### Task 1 - Titanic Survival Prediction using Logistic Regression

In this task, I built my first machine learning classification model using the Titanic dataset.

#### Steps Performed

- Removed unnecessary columns
- Filled missing values
- Encoded categorical features using `pd.get_dummies()`
- Split the dataset into training and testing sets
- Trained a Logistic Regression model
- Predicted passenger survival
- Evaluated the model using Accuracy Score and Confusion Matrix

#### Results

- **Model:** Logistic Regression
- **Accuracy:** **79.89%**

#### Conclusion

The Logistic Regression model achieved **79.89% accuracy** on the test dataset. The model correctly classified most passengers and demonstrated the complete machine learning workflow, including preprocessing, feature engineering, model training, prediction, and evaluation.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Dataset

**Titanic - Machine Learning from Disaster**

---

## Author

**Haider Ali**