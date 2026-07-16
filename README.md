# NeuroFive ML Track
This repository contains my work for the **NeuroFive Solutions Machine Learning Fundamentals Internship**.

## Repository Structure
neurofive-ml-track/
│
├── README.md
│
└── week1/
    ├── train.csv
    ├── Titanic_EDA.ipynb
    └── Titanic_Data_Cleaning_Visualization.ipynb
## Week 1
### Task 1 - Exploratory Data Analysis (EDA)
- Loaded the Titanic dataset using Pandas
- Explored the dataset using `head()`, `info()`, and `describe()`
- Identified missing values
- Distinguished numerical and categorical features
- Summarized key findings

### Task 2 - Data Cleaning & Visualization
- Handled missing values
- Detected outliers using a boxplot
- Created:
  - Histogram
  - Boxplot
  - Bar Chart
  - Correlation Heatmap
- Analyzed the most influential feature for survival

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
Titanic - Machine Learning from Disaster

## Author
**Haider Ali**

           -------------------------------------------------------------------


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
- **Accuracy:** 79.89%

#### Conclusion
The Logistic Regression model achieved approximately **79.89% accuracy** on the test dataset. It correctly classified most passengers and demonstrated the complete machine learning workflow from preprocessing to model evaluation.