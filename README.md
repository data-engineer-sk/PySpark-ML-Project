# README.MD
## PySpark-ML-Project

![testScore CSV file](https://github.com/data-engineer-sk/PySpark-ML-Project/blob/main/Machine-Learning.png)

### Project Aims
This project aims to apply the PySpark to build a linear regression machine learning model to predict the test score for the Machine Learning Test.

### Machine Learning Process (ML Process)
There are 4 processes in this project
1. Collection of Data from CSV file (no data cleaning in this time)
2. Feature Engineering (Create a new [Independent Variable] feature by using [RelectedExperience] and [StudyHour] attributes)

![Independent Variable](https://github.com/data-engineer-sk/PySpark-ML-Project/blob/main/The%20Independent%20Variable.png)

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
![testScore CSV file](https://github.com/data-engineer-sk/PySpark-ML-Project/blob/main/testScore.file.png)

### Output
![Test Score Results](https://github.com/data-engineer-sk/PySpark-ML-Project/blob/main/ML%20Results.png)

### Conclusion
The result shows that the relationship of the test score is not depend on the new independent variable feature.  To improve the performance may collect more data for ml training and testing in future.
