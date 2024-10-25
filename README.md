# creditriskmodelling
Developed a credit risk model for CredX to minimize credit losses by identifying suitable applicants. Used WOE to clean data, built predictive models on demographic and credit bureau data, and created a scorecard to assess default risk. Evaluated the financial benefits by calculating potential credit loss avoided and auto-approval impact.


Project Overview: Credit Risk Analysis for CredX
Objective:
To mitigate credit risk for CredX, a leading credit card provider, by identifying the right customers using predictive modeling. The goal is to reduce credit losses by analyzing past applicant data and establishing effective strategies for customer acquisition.

Project Breakdown:

Business Understanding:
CredX faces increasing credit losses due to poor customer acquisition decisions. The CEO aims to minimize this risk by selecting applicants with a higher likelihood of repayment.

Data Cleaning and Preparation:

A comprehensive master file was created, incorporating relevant variables from the demographic and credit bureau datasets.
Data quality checks and cleaning were performed to ensure reliability.
Employed Weight of Evidence (WOE) analysis to identify important variables and impute missing values. The processed data was stored in a separate file for further analysis.
Model Building:

Demographic Data Model: A predictive model was built using demographic variables (age, gender, income, marital status, etc.) to assess the likelihood of default.
Combined Data Model: A logistic regression model was developed using both demographic and credit bureau data, which includes historical credit behavior metrics like payment history and outstanding balances.
Model Evaluation:
Models were evaluated based on key performance metrics, and the predictive capability was tested on rejected applicants to validate expectations.

Application Scorecard Development:

Created a scorecard with a good-to-bad odds ratio of 10 to 1 at a score of 400, increasing by 20 points for every doubling of odds.
Scoring of rejected applicants was performed, and comparisons with approved candidates were made to derive insights.
Financial Benefit Assessment:

Analyzed the financial implications of model-driven auto-approval and rejection decisions, estimating the number of applicants automatically approved or rejected.
Quantified potential credit losses avoided through the model's implementation, presenting findings to the bank's management.
Discussed key assumptions underpinning the model's construction.
Outcome:
The project aimed to enhance CredX’s decision-making processes by providing a robust framework for evaluating credit risk, ultimately leading to better customer acquisition strategies and reduced credit losses.

