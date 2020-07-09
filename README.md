# Linear Regression: Salary Prediction
Hello there! This is a **supervised machine learning** project completed early in my journey as a data scientist. I wanted to know what the data might reveal about compensation in the field. Can you blame me for being curious? :monkey:

The goal was to construct a **predictive regression model** achieving the highest **R^2** possible. *Spoiler alert:* it does not go very high in this project. But I did get some neat **interpretations** (take a look at page 8 of the [presentation PDF](https://github.com/fw192020/linear_regression/blob/master/linear_regression_presentation.pdf)). 

I used **cross-validation** as my model selection method amongst the various models evaluated:
1. Simple linear regression
2. Ridge regression
3. LASSO
4. Polynomial regression

The dataset is comprised of ~650 observations which includes salary data and metadata that I **web-scraped** with the help of **Beautiful Soup** and **Selenium** from:
* Levels.fyi (for salary data)
* Salary.com (for cost of living data)
* Wikipedia.com (for company data)

The scraped data has been cleaned and pre-processed so ready to go for the purposes of this repo. 

## Jupyter Notebooks for your perusal:
- 1_EDA (exploratory data analysis)

- 2_Linear Regression (modeling)

Thanks for visiting!


