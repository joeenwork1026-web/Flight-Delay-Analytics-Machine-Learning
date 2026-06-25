# Flight-Delay-Analytics-Machine-Learning
Author: Joe En Lee  
Email: joeenwork1026@gmail.com  
LinkedIn: https://www.linkedin.com/in/joe-en-lee-94b92b323/  

## Project Overview
This project analyzes historical US flight data (2001–2005) to identify factors contributing to flight delays and diversions. Using Python, R, SQL, and SQLite, an end-to-end analytics pipeline was developed to perform data cleaning, exploratory data analysis, statistical modelling, and machine learning.

The project aims to answer the following questions:
1. What factors contribute most to flight delays?
2. Can flight diversions be predicted using historical flight information?
3. Is there a relationship between aircraft age and arrival delays?
4. Can analytical results be reproduced consistently across Python and R?

## Technologies Used
Python  
R  
SQL  
SQLite  
Pandas  
NumPy  
Scikit-learn  
Matplotlib  
Seaborn  

## Dataset

The dataset consists of historical US flight records from 2001–2005, including information such as:
1. Flight dates
2. Departure and arrival delays
3. Carrier information
4. Origin and destination airports
5. Aircraft details
6. Flight diversion status

## Project Workflow
1. Data Preparation
Imported and integrated flight datasets using SQL and SQLite.
Performed data cleaning, filtering, and transformation.
Handled missing values and prepared datasets for analysis.

2. Exploratory Data Analysis (EDA)
Analyzed delay patterns across years, airlines, and airports.
Identified key factors associated with flight delays and diversions.
Visualized trends using charts and summary statistics.

3. Machine Learning Model
Applied Logistic Regression to predict flight diversion outcomes.
Addressed class imbalance using SMOTE.
Evaluated model performance using:
Accuracy
Recall
ROC-AUC

4. Regression Analysis
Investigated the relationship between aircraft age and arrival delays.
Compared trends across multiple years.
Visualized regression results and interpreted findings.

5. Reproducibility Analysis
Implemented analytical workflows in both Python and R.
Compared outputs to validate consistency and reproducibility of results.

## Key Findings
Several operational factors showed significant relationships with flight delays and diversions.
Logistic Regression provided meaningful predictive insights for diversion classification.
Aircraft age demonstrated measurable relationships with arrival delay patterns.
Results generated in Python and R were largely consistent, supporting analytical reproducibility
