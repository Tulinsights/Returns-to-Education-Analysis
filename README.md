# Returns-to-Education-Analysis

This project uses OLS regression to analyze the 1976 wage data. I found that each year of education adds approximately $0.54 to hourly earnings.

## Executive Summary: Analysis of Labor Market Returns

### Project Overview
This project investigates the determinants of individual wages using econometric modeling. Specifically, I test the Human Capital Theory, which posits that investments in education and labor market experience significantly increase worker productivity and, consequently, earnings.

##### The Research Question
"Holding experience and job tenure constant, what is the specific financial return to one additional year of education?"

##### Methodology
I utilized the Card (1995) dataset (via the Wooldridge package), which contains labor market data from the 1976 Current Population Survey. The analysis evolved through two stages:

##### Simple Linear Regression:
A baseline model measuring the raw correlation between education and wages.
##### Multiple Linear Regression (OLS): 
An expanded model to control for Omitted Variable Bias. I included variables for experience (total years in the workforce) and tenure (years with the current employer) to isolate the "true" effect of schooling.
##### Key Findings
##### Education: 

Each additional year of schooling is associated with an average increase of approximately $0.60 per hour ($p < 0.01$), confirming that education is a highly significant predictor of earnings.
##### Experience vs. Tenure:
While both contribute to higher wages, total labor market experience showed a stronger correlation with wage growth than specific job tenure in this sample.
##### Model Accuracy:
By moving to a multiple regression model, the R-squared increased from 0.18 to 0.30, meaning our model now explains 30% of the variation in wages—a significant improvement in predictive power.
##### Technical Tools
Language: Python
Libraries: pandas (Data Manipulation), statsmodels (Econometric Modeling), seaborn/matplotlib (Data Visualization).
