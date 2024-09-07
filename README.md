# Distributed-Machine-Learning-with-Spark

## Introduction to Distributed Machine Learning with PySpark MLlib
- Simple exposure to machine learning using PySpark
- Dataset used: Singapore Resale flat prices from Jan 2017 (https://data.gov.sg/collections/189/view)

## Breakdown of steps done:
- Data cleaning and transformation 
    - Drop columns that are not necessary 
    - Extract flat's remaining lease in months and use it as a numerical variable when training models
    - Identified numerical variables and categorical variables
- Numerical Variables
    - Use of Imputation estimator for completing missing values, using the mean, median and mode of the columns that have missing values
    - Utilize VectorAssembler to merge numerical columns into a vector column. This allows a larger amount of data to be handled with less memory
    - Standard Scaler as a preprocessing technique to ensure data points have a balanced scale
- Categorical Variables
    - Convert various categorical string columns into numerical indices
    - One hot encoding employed to avoid the problem of ordinality 
- Prediction Model
    - Logistics Regression, more to be done!
- Evaluation Metrics
    - More to be done!


