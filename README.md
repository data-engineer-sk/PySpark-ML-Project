# README.MD
## PySpark-ML-Project

![ETL Process via API](https://github.com/data-engineer-sk/dataWarehouse-PostgreSQL-1/blob/main/Nasdaq%20API%20-%20ETL%20Processing.png)

### Project Aims
This project aims to apply the PySpark to build a linear regression machine learning model to predict the test score for the Machine Learning Test.

### Machine Learning Process (ML Process)
There are 4 processes in this project
1. Collection of Data from CSV file (no data cleaning in this time)
2. Feature Engineering (Create a new [Independent Value] feature by using [RelectedExperience] and [StudyHour] attributes)
3. Model building and Selection of ML Linear Regression Algorithm
4. Model Evaluation

### How it works
Use Juypter Note to load the **testScore.csv** file for modelling.  Use the standard machine learning technique and apply the **linear regression** model to test the data, then predict the results for by another set of test data. 
** This project has no model deployment at the end.  Will be improved in future

### System Requirement
This system requires the following setting:
- Python 3.10 or above
- PySpark 3.3.1
- Juypter Notebook

### Input File
testScore.csv file will be uploaded for training and testing in the ML processes.

### Output
