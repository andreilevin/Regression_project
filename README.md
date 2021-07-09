# NBA Free Agent Salary Predictor

In this project, we predict the salary of NBA free fgents based on a regression model that takes their previous year's salary and stats as features.

## Design and Data

We scraped the last four years of NBA free agent statistics  from http://www.basketball-reference.com and salary data from http://www.hoopshype.com.  Extensive cleaning was performed both before and after the various datasets were combined

## Algorithms

We used ordinary linear regression, feature engineering (including polynomial and fractional features), cross-validation, regularization,  and LASSO regression.

## Tools

* Beautifulsoup for web scraping
* Pandas for data cleaning, filtering and aggregation
* Statsmodels and scikitlearn for EDA and regression modelling
* Matplotlib and Seaborn for plotting 

## Communication

Our best fit was achieved by Ordinary Least Squares, with an average R-squared of 0.74 on the train set and 0.66 on the Test set.  On the test data, mean absolute error was $3.71 million and root mean square error of of $5.21 million.  A scatter plot of predicted vs actual salaries in the test set is show below:

<img  src="https://raw.githubusercontent.com/andreilevin/Regression_project/main/fig_ols.png" 
      title="results_unfiltered" width="400"/>
