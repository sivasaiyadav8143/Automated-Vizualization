# Automated-Vizualization

Author: SivaSai Yadav Mudugandla

Date: 11/06/2020

A simple code that saves most of the data scientists time in visualization.It is a python script that requires  
dataset(csv,excel,etc.) and target column as input.

### The script performs following operations ###
1. Shape of the dataset <br>
2. DataType of columns <br>
3. Problem Type (Classification / Regression)<br>
4. Target Column visualization (Pie & Bar graphs) to check if it has imbalance class.<br>
5. Univariate Analysis (Tells about distribution and presence of outliers if any)<br>
    1. Box Plot
    2. Histogram
    3. Distribution
6. Bivariate Analysis
    1. Density Plot for Classification Problem
       . Tells you whether a feature is poor/weak/good predictor <br>
       ![GitHub Logo](/Screenshots/DensityPlot.PNG)
    2. Scatter Plot for Regression Problem
7. Multivariate Analysis
    1. Correlation Matrix
    2. List of Correlated Features
8. Missing Value Analysis
    1. Missing Table
    2. Missing Bar
    3. Missing Matrix


Automated Vizualization.ipynb: the jupyter notebook containing code.
