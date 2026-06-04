# Student Performance Prediction using Linear Regression

## Project Overview

This project predicts students' final exam scores using Machine Learning techniques. The dataset contains information about study habits, focus levels, sleep patterns, motivation, attendance, and other academic and lifestyle factors.

A Linear Regression model was developed to analyze the relationship between these factors and student performance.

---

## Objectives

* Perform Exploratory Data Analysis (EDA)
* Handle missing values and preprocess data
* Convert categorical variables into numerical format
* Build a Linear Regression model
* Evaluate model performance using regression metrics
* Analyze factors affecting student performance

---

## Dataset Features

The dataset includes features such as:

* Age
* Gender
* Study Hours Per Day
* Deep Work Sessions
* Assignment Completion Rate
* Attendance Percentage
* Social Media Hours
* Sleep Hours
* Motivation Level
* Focus Score
* Physical Activity Hours
* Family Support
* Financial Stress
* Learning Style
* Career Goal
* Consistency Score
* And several other academic and behavioral factors

### Target Variable

* `final_exam_score`

---

## Exploratory Data Analysis (EDA)

The following EDA steps were performed:

1. Dataset overview
2. Missing value analysis
3. Data cleaning
4. Target variable distribution analysis
5. Correlation analysis
6. Scatter plot analysis
7. Outlier detection using boxplots
8. Categorical feature analysis
9. One-Hot Encoding
10. Feature preparation for model training

---

## Data Preprocessing

### Missing Values

Missing values were identified and handled using median imputation.

### Categorical Encoding

Categorical variables were converted into numerical format using One-Hot Encoding.

### Train-Test Split

The dataset was split into:

* Training Set: 80%
* Testing Set: 20%

---

## Model Used

### Linear Regression

Linear Regression was used to predict final exam scores based on multiple student-related features.

---

## Model Evaluation

Evaluation Metrics:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### Results

| Metric                   | Value |
| ------------------------ | ----- |
| Mean Squared Error (MSE) | 35.81 |
| R² Score                 | 0.893 |

### Interpretation

The model achieved an R² score of approximately **89.3%**, indicating that it explains most of the variation in students' final exam scores.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Structure

```text
student-performance-prediction/
│
├── student_performance_dataset.csv
├── project.ipynb
├── README.md
├── requirements.txt
└── screenshots/
```

---

## Key Insights

* Consistency Score showed one of the strongest relationships with exam performance.
* Study Hours Per Day positively influenced exam scores.
* Focus Score and Revision Efficiency contributed significantly to academic performance.
* Students with stronger study habits generally achieved higher scores.

---

## Future Improvements

* Implement advanced regression models such as Random Forest Regressor and XGBoost.
* Deploy the model using Streamlit.
* Perform feature selection and hyperparameter tuning.
* Compare multiple machine learning algorithms.

---

## Author

**Kuldeep Kirit Prajapati**

B.Tech Computer Science Engineering

GitHub: https://github.com/kuldeepin3

LinkedIn: https://www.linkedin.com/in/kuldeep-prajapati-a929a32ab
