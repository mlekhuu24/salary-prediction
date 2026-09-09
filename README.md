# salary-prediction
Salary Prediction Based on Skills and Experience is a machine learning project that predicts an employee's salary based on years of experience, education, job role, and technical and communication skills. The project uses Linear Regression with Python, Pandas, Matplotlib, and Scikit-learn.
# Salary Prediction Based on Skills and Experience

## Project Overview

Salary Prediction Based on Skills and Experience is a machine learning project developed using Python to predict an employee's salary based on their professional experience, education, job role, and skills.

The project analyzes factors such as years of experience, education level, job role, Python skills, SQL skills, cloud skills, and communication skills. A Linear Regression model is used to estimate the expected salary.

This project is intended for educational and academic purposes.

## Objectives

* Analyze employee salary data.
* Study the relationship between experience, skills, and salary.
* Identify factors that influence salary.
* Preprocess employee data.
* Train a machine learning regression model.
* Predict the expected salary of an employee.
* Evaluate the performance of the model.
* Compare actual and predicted salaries.
* Visualize salary-related patterns.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Machine Learning Algorithm

### Linear Regression

The project uses Linear Regression to predict employee salary.

Linear Regression is a supervised machine learning algorithm used to predict continuous numerical values based on one or more input features.

**Input:** Experience, education, job role, and skills

**Output:** Predicted salary

## Dataset

The project uses the following dataset:

`salary_data.csv`

### Dataset Features

| Feature             | Description                                  |
| ------------------- | -------------------------------------------- |
| employee_id         | Unique identification number of the employee |
| years_experience    | Number of years of professional experience   |
| education           | Education level of the employee              |
| job_role            | Job role of the employee                     |
| python_skill        | Python skill rating                          |
| sql_skill           | SQL skill rating                             |
| cloud_skill         | Cloud technology skill rating                |
| communication_skill | Communication skill rating                   |
| salary              | Employee salary                              |

### Target Variable

`salary`

The target variable represents the salary that the machine learning model predicts.

## Project Workflow

The project follows these steps:

1. Load the employee salary dataset.
2. Display the first few records.
3. Check the dataset shape.
4. Check for missing values.
5. Separate input features and target variable.
6. Handle missing numerical values.
7. Handle missing categorical values.
8. Standardize numerical features.
9. Encode categorical features.
10. Split the dataset into training and testing data.
11. Train the Linear Regression model.
12. Generate salary predictions.
13. Evaluate the model.
14. Compare actual and predicted salaries.
15. Predict the salary of a new employee.
16. Analyze important salary-related factors.
17. Generate visualizations.

## Data Preprocessing

The project uses different preprocessing techniques for numerical and categorical features.

### Numerical Features

The numerical features include:

* Years of experience
* Python skill
* SQL skill
* Cloud skill
* Communication skill

Missing numerical values are replaced using the median value.

The numerical features are standardized using `StandardScaler`.

### Categorical Features

The categorical features include:

* Education
* Job role

Missing categorical values are replaced using the most frequent value.

Categorical features are converted into numerical values using One-Hot Encoding.

## Train-Test Split

The dataset is divided into:

* 80% Training Data
* 20% Testing Data

The training data is used to train the Linear Regression model, while the testing data is used to evaluate its performance.

## Model Evaluation

The model is evaluated using the following metrics:

### Mean Absolute Error

MAE measures the average difference between the actual and predicted salaries.

A lower MAE indicates better prediction performance.

### Root Mean Squared Error

RMSE measures the prediction error while giving greater importance to larger errors.

A lower RMSE indicates better performance.

### R² Score

R² Score measures how well the model explains the variation in employee salaries.

A value closer to 1 generally indicates better model performance.

## New Employee Salary Prediction

The project demonstrates how the trained model can predict the salary of a new employee.

Example employee information includes:

* 5 years of experience
* Master's degree
* Software Engineer role
* Python skill rating of 8
* SQL skill rating of 7
* Cloud skill rating of 6
* Communication skill rating of 8

The trained model uses these details to estimate the employee's salary.

## Feature Impact Analysis

The project analyzes the regression coefficients to identify factors that have a greater influence on salary prediction.

Features are ranked according to their absolute coefficient values.

This helps understand which experience, education, job role, or skill-related factors have a stronger relationship with the predicted salary.

## Data Visualization

The project generates three visualizations.

### 1. Experience vs Salary

Shows the relationship between years of experience and employee salary.

Output file:

`experience_vs_salary.png`

### 2. Actual vs Predicted Salaries

Compares actual employee salaries with salaries predicted by the Linear Regression model.

Output file:

`actual_vs_predicted.png`

### 3. Average Salary by Education

Shows the average salary for different education levels.

Output file:

`education_vs_salary.png`

## Project Structure

```text
Salary_Prediction_Based_on_Skills_Experience/
│
├── salary_prediction.py
├── salary_data.csv
├── requirements.txt
└── README.md
```

The visualization files are generated automatically when the program is executed.

## Installation

Make sure Python is installed on your computer.

Install the required libraries using:

```bash
pip install -r requirements.txt
```

Required libraries:

```text
pandas
numpy
matplotlib
scikit-learn
```

## How to Run

Open Command Prompt or Terminal in the project folder.

Run the following command:

```bash
python salary_prediction.py
```

The program will:

* Load the salary dataset.
* Display the dataset information.
* Check for missing values.
* Preprocess the data.
* Train the Linear Regression model.
* Calculate MAE, RMSE, and R² Score.
* Display actual and predicted salaries.
* Predict the salary of a new employee.
* Display important salary-related factors.
* Generate visualization graphs.

## Applications

Salary prediction can be useful for:

* Salary analysis
* Career planning
* Recruitment analysis
* Compensation research
* Employee data analysis
* Human resource analytics
* Understanding the relationship between skills and salary

## Limitations

* The dataset is synthetic.
* The project is intended for educational purposes.
* Actual salaries depend on many factors that may not be included in the dataset.
* Salary structures vary between companies, industries, and locations.
* The model's predictions depend on the quality and size of the training data.

## Future Enhancements

The project can be improved by:

* Using larger real-world salary datasets.
* Comparing multiple regression algorithms.
* Using Random Forest and Gradient Boosting models.
* Adding industry and location information.
* Including additional technical and soft skills.
* Performing feature selection.
* Using cross-validation.
* Developing a web-based salary prediction application.
* Creating an interactive salary analysis dashboard.
* Deploying the model for real-time predictions.

## Project Information

**Project Name:** Salary Prediction Based on Skills and Experience

**Domain:** Machine Learning and Data Science

**Programming Language:** Python

**Machine Learning Type:** Supervised Learning

**Problem Type:** Regression

**Algorithm:** Linear Regression

**Target Variable:** Salary

## Dataset Note

The salary dataset included in this project is synthetic and intended for educational and classroom machine learning practice. It does not contain real employee compensation records.
