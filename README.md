# Linear Regression Multivariate: House Prices and Hiring Prediction

<em>These datas and notebook is part of Linear Regression Multivariate: House Prices and Hiring Prediction by [Codebasics Youtube Channel ML Playlist](https://www.youtube.com/watch?v=J_LnPL3Qg70&list=PLeo1K3hjS3uvCeTYTeyfe0-rN5r8zn9rw&index=3)</em>

Sample problem of predicting home price in monroe, new jersey (USA)
Below is the table containing home prices in monroe twp, NJ. Here price depends on area (square feet), bed rooms and age of the home (in years). Given these prices we have to predict prices of new homes based on area, bed rooms and age.

<img src="https://github.com/codebasics/py/blob/master/ML/2_linear_reg_multivariate/homeprices.jpg?raw=true">

Given these home prices find out price of a home that has,

3000 sqr ft area, 3 bedrooms, 40 year old

2500 sqr ft area, 4 bedrooms, 5 year old

We will use regression with multiple variables here. Price can be calculated using following equation,

<img src="https://github.com/codebasics/py/blob/master/ML/2_linear_reg_multivariate/home_equation.jpg?raw=true">


Here area, bedrooms, age are called independant variables or features whereas price is a dependant variable

## Exercise
The `hiring.csv` contains hiring statistics for a firm such as experience of candidate, his written test score and personal interview score. Based on these 3 factors, HR will decide the salary. Given this data, you need to build a machine learning model for HR department that can help them decide salaries for future candidates. Using this predict salaries for following candidates,

<strong>2 yr experience, 9 test score, 6 interview score</strong>

<strong>12 yr experience, 10 test score, 10 interview score</strong>

Is need to install `word2number` package

`pip install word2number`
