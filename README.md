# Student Depression Prediction Using ML

A machine learning-based predictive analytics project focused on identifying depression risk among students using academic, behavioral, psychological, and lifestyle-related factors. The project applies data preprocessing, exploratory data analysis (EDA), and classification algorithms to analyze depression-related patterns and evaluate predictive model performance.

## Project Overview

Student depression has become a major concern due to increasing academic pressure, financial stress, unhealthy lifestyle habits, and mental health challenges. This project aims to identify important factors associated with student depression and develop predictive machine learning models for early detection.

The system analyzes demographic, academic, behavioral, and psychological data to understand depression-related patterns and compare classification model performance.

## Dataset Information

| Feature         | Details                      |
| --------------- | ---------------------------- |
| Dataset Size    | 27,901 Records               |
| Total Features  | 18                           |
| Target Variable | Depression (0 = No, 1 = Yes) |

## Key Features

* Gender
* Age
* City
* Academic Pressure
* Work Pressure
* Study Satisfaction
* Job Satisfaction
* Sleep Duration
* Dietary Habits
* Work/Study Hours
* Financial Stress
* Suicidal Thoughts
* Family History of Mental Illness

## Project Objectives

* Analyze factors contributing to student depression
* Perform data preprocessing and exploratory data analysis
* Build machine learning classification models
* Compare model performance
* Identify the most effective prediction model

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Data Preprocessing

The dataset was cleaned and transformed before training the models.

### Preprocessing Steps

* Handling missing values
* Encoding categorical variables
* Feature mapping
* Data splitting (80% training, 20% testing)
* Correlation analysis

## Exploratory Data Analysis (EDA)

Several visualizations and statistical analyses were performed to identify important trends and relationships among the variables.

## Important Findings

* Higher academic pressure is strongly associated with depression
* Financial stress significantly affects mental health
* Poor dietary habits increase depression risk
* Lower sleep duration is linked with depression
* Suicidal thoughts show a strong relationship with depression

## Machine Learning Models

### Logistic Regression

### Support Vector Machine (SVM)

## Model Performance

| Model               | Accuracy | Precision | Recall | F1-Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 84.6%    | 85.8%     | 88.5%  | 87.1%    |
| SVM                 | 84.6%    | 85.6%     | 88.5%  | 87.1%    |

## Results Summary

The experimental results demonstrate that machine learning models can effectively identify depression risk patterns among students. Logistic Regression achieved the best overall balance between performance, interpretability, and computational efficiency.

## Repository Structure

```text id="tbv3l5"
├── README.md
├── Project Code.ipynb
├── Project Presentation.pptx
└── Project Report.pdf
```

## Contributors

| Name                 | ID            |
| -------------------- | ------------- |
| Ani Paul             | 2022-3-60-321 |
| Md Moon Rahman Nayem | 2022-3-60-210 |

## Academic Information

* **Course Title:** Statistics for Data Science
* **Course Code:** CSE303
* **Semester:** Spring 2025
* **Department:** Computer Science and Engineering
* **Institution:** East West University

## Supervisor

**Dr. Mohammad Manzurul Islam**
Assistant Professor
Department of Computer Science and Engineering
East West University

## Conclusion

This project successfully demonstrates the practical application of machine learning techniques for predicting student depression using academic, behavioral, and psychological factors. The results highlight how predictive analytics can support early mental health risk identification and assist institutions in taking preventive measures for student well-being.
