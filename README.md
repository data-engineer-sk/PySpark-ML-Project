# README.MD
## PySpark-ML-Project

![ETL Process via API](https://github.com/data-engineer-sk/dataWarehouse-PostgreSQL-1/blob/main/Nasdaq%20API%20-%20ETL%20Processing.png)

### Project Aims
This project aims to apply the PySpark to build a linear regression machine learning model to predict the test score for the Machine Learning Test.

### Machine Learning Process (ML Process)
There are 4 processes in this project
1. Collection of Data from CSV file (no data cleaning in this time)
2. Feature Engineering
3. Model building and Selection of ML Linear Regression Algorithm
4. Model Evaluation

### How it works
Write a CLI program with python.  Use the API function calls provided by Nasdaq.com to extract csv file.  Use packages such as  Pandas / Numpy to transform the data complie with the user requirement.  Store the results to the PostgreSQL / MysQL Server (Can be stored in local machine or AWS Cloud RDS) which act as a data warehouse.  Use SQL to furthur transform the data into a new data table (**Perform unit test to ensure the data are clearn to use in future.**)
** This project has no model deployment at the end.  Will be improved in future

### System Requirement
This system requires the following setting:
- Python 3.10 or above
- PySpark 
- Juypter Notebook

### Input File
testScore.csv file will be uploaded for training and testing in the ML processes.

### Output
Extract the historical stock data, use the API which were provided by Nasdaq.com for processing.  Use **nasdaqdatalink.ApiConfig.api_key** to establish 
