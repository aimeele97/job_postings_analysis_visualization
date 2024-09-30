# Indeed job posting analysis - Data scientist

![image.png](img/indeedlogo.png)

## Project Overview

This project analyzes actual data scientist job postings on Indeed in the USA from 23/06/2024 to 11/08/2024. The goal is to examine trends in job postings and salary variations across different states, experience levels, work modes, and companies. Based on this analysis, a predictive model that estimates salaries will be developed, enabling both job seekers and employers to make informed decisions and ensure fair compensation in the job market.

### Data Source
The data used in this project was downloaded from Kaggle.

- Link dataset: [Job posting dataset](https://www.kaggle.com/datasets/yusufolonade/data-science-job-postings-indeed-usa)

### Business Problem

In the competitive data science market, both job seekers and employers struggle with unclear salary expectations and job availability. The lack of comprehensive insights into job posting trends and salary variations across states and experience levels can result in misaligned expectations, affecting recruitment and job satisfaction.

This project seeks to analyze recent job postings and create a predictive model for estimating salaries in data science. By offering data-driven insights, job seekers should negotiate fair compensation while helping employers attract and retain top talent.

### Table of Contents

1. [Data Cleaning](#data-cleaning)
2. [Data Exploratory Analysis (EDA)](#data-exploratory-analysis-eda)
3. [Model Development](#model-development)
   - [Simple Linear Regression (SLR)](#simple-linear-regression-slr)
   - [Multiple Linear Regression (MLR)](#multiple-linear-regression-mlr)
   - [Polynomial Regression](#polynomial-regression)

#### Data cleaning

- Discover each features data to extract useful information to new columns (Working mode, job level, average salary) that help to build the model in the end of this project.
- Handle missing values, remove duplicates, and convert data types.
- Remove columns that are not in use

Raw data
![raw-data](img/raw_data.png)

Clean data
![clean-data](img/clean_data.png)

#### Exploratory data analysis
- Job posting by date
![img.png](img/bydate.png)
- Job distribution by state
![img.png](img/propotion-state.png)
- Salary distribution
![img.png](img/avg-salary.png)
- Salary by job level
![img.png](img/salary-job-level.png)
- Salary by working mode
![img.png](img/salary-working-mode.png)
- Salary by job level and working mode
![img.png](img/salary-joblevel-workingmode.png)
- Top 10 city, state hiring the most
![img.png](img/top-10-city-state.png)
- Top 10 company actively hiring
![img.png](img/top-10-company.png)
- Salary range for entry level positions
![img.png](img//salary-entry-level.png)

#### Model development

Three models were developed to predict salary: 
- Simple Linear Regression (SLR)
![img.png](img/SLR-job-level.png)
- Multiple Linear Regression (MLR)
![img.png](img/mlr.png)
- Polynomial Regression
![img.png](img/polynomial-joblevel.png)
### Conclusion
- The analysis demonstrates that the multiple linear regression (MRL) model is the best choice for salary prediction. With a R-squared value and minimal MSE, this model effectively captures the complexities of various influencing factors. 

- By leveraging multiple relevant predictors, it not only enhances the accuracy of salary forecasts but also provides invaluable insights for both job seekers and employers. Investing in this approach empowers stakeholders to make informed decisions, ultimately leading to a more equitable and efficient job market.

- However, further investigation is needed to refine the model for even greater accuracy.