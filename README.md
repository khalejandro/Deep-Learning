# **Data Scientist Employee Attrition – Job Change Prediction**

## **Overview**

This project analyzes employee attrition patterns among **Data Science professionals** and predicts whether a candidate is **actively seeking a new job**.  
It is based on a dataset from a company specializing in **Big Data and Data Science training programs**, which aims to identify participants likely to join their workforce after completing training.

By understanding what factors influence a candidate’s job change decision, the company can **optimize recruitment**, **improve training planning**, and **reduce hiring costs**.

## **Problem Statement**

A company conducting data science training wants to determine which participants are likely to **seek new employment opportunities** after completing the course.  

The goal is to:
- Predict the probability that a candidate is **looking for a job change**.
- Identify **key demographic, educational, and experiential factors** influencing that decision.

This analysis supports HR teams in designing better retention and hiring strategies within the data science domain.

## **Dataset Description**

The dataset includes demographic, educational, and employment-related attributes of candidates:

| **Feature** | **Description** |
|--------------|-----------------|
| `enrollee_id` | Unique identifier for each candidate |
| `city` | Encoded city location |
| `city_development_index` | Scaled development index of the candidate’s city |
| `gender` | Candidate’s gender |
| `relevent_experience` | Indicates whether the candidate has relevant experience |
| `enrolled_university` | Type of university course enrolled, if any |
| `education_level` | Candidate’s education level |
| `major_discipline` | Major discipline in education |
| `experience` | Total years of experience |
| `company_size` | Number of employees in the current employer’s company |
| `company_type` | Type of the current employer |
| `last_new_job` | Years since the candidate’s last job change |
| `training_hours` | Number of training hours completed |
| `target` | 0 = Not looking for job change, 1 = Looking for job change |

## **Objective**

The main objectives of this project are:
1. Perform **exploratory data analysis (EDA)** to identify trends in job change behavior.  
2. Build **predictive models** to estimate the probability of job change.  
3. Evaluate and compare model performance using key metrics (accuracy, F1-score, AUC, etc.).  
4. Interpret results to highlight which factors most influence attrition decisions.

## **Methodology**

1. **Data Preprocessing**  
   - Handle missing values, encoding of categorical variables, and scaling of numerical features.  
2. **Exploratory Data Analysis (EDA)**  
   - Study demographic and professional distributions.  
   - Identify correlations between variables and job change intent.  
3. **Model Development**  
   - Train machine learning models (e.g., Logistic Regression, Random Forest, XGBoost).  
   - Optimize hyperparameters and compare results.  
4. **Interpretation & Insights**  
   - Analyze feature importance to understand decision drivers.

## **Repository Structure**

```
Data-Scientist-Attrition/
│
├── data/
│   └── Data.csv
├── notebooks/
│   └── Data_Scientist_Employee_Attrition.ipynb
├── README.md
└── requirements.txt
```

