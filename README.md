# Term Deposit Marketing Campaign - Data Science Hackathon
## Overview
This project aims to identify potential customers for a term deposit marketing campaign for DB Bank (hypothetical bank) and hence measure the success in terms of the number of customers converted. The project emerged victorious in a data science hackathon conducted at Fractal Analytics by effectively identifying and analyzing key factors influencing campaign success with a predictive model yielding a recall score of whopping 81%.

## Domain
Marketing for Financial Services

## About
DB Bank is a large public sector bank with branches across various cities, offering services such as savings accounts, current accounts, term deposits, personal loans, and home loans. The bank tracks customer personal, social, and economic details, as well as efforts made to achieve campaign success.

Recently, DB Bank conducted a campaign to market their term deposit scheme, primarily through direct phone calls. The campaign's success was determined by whether a client agreed to place a term deposit (target variable: 'yes' or 'no').

## Challenges
The main challenge for bank officials is to target the right individuals for a successful campaign. The marketing team needs to analyze various customer details, such as profession, income, age, education, existing loans, and credit history, to determine their capability to deposit money into the term deposit scheme.

## Project Steps
### 1. Data Preparation and Exploratory Data Analysis (EDA)
**Goals:**
- Assess available data and perform exploratory and descriptive analytics.
- Identify interesting and useful patterns, trends, and insights.

**Tasks:**
- Analyze the percentage turnout of the marketing campaign.
- Determine the right mode to contact customers (telephone or mobile).
- Analyze the number of attempts made to convert a person into a successful depositor.
- Perform personal data analysis on marital status, existing loans, education, profession, etc., and their impact on the campaign’s success.
- Conduct socio-economic analysis of the customers.
- Test for dependencies between attributes using statistical tests (hypothesis testing) and perform feature engineering based on the results.
- Prepare data by handling missing values, outlier analysis, data transformation, and normalization.

### 2. Predictive Analysis
**Goals:**
- Build a robust and generalized predictive model to classify successful and unsuccessful campaigns.
- Compare various predictive models and provide inferences.

**Tasks:**
- Build appropriate predictive models on the data.
- Compare models with regularization and/or hyper-parameter tuning.
- Evaluate model performance and identify the right metric.
- Identify data issues and suggest techniques to overcome them.

### 3. Recommendations
Based on the analysis, recommend approaches for the marketing team to identify the ideal target group to make the campaign successful.

## Data Dictionary
### Bank Client Data
- **custAge**: Age of the customer.
- **profession**: Type of job.
- **marital**: Marital status.
- **schooling**: Educational qualification.
- **default**: Has credit in default?
- **housing**: Has a housing loan?
- **loan**: Has a personal loan?
### Data Related to the Last Contact of the Current Campaign
- **contact**: Contact communication type.
- **month**: Last contact month of the year.
- **day_of_week**: Last contact day of the week.
- **campaign**: Number of contacts performed during this campaign and for - **this** client (includes last contact).
- **pdays**: Number of days that passed since the client was last - **contacted** from a previous campaign (999 means not previously - **contacted**).
- **previous**: Number of contacts performed before this campaign for this - **client**.
- **poutcome**: Outcome of the previous marketing campaign.
### Data Related to Social and Economic Context Attributes
- **emp.var.rate**: Employment variation rate (quarterly indicator).
- **cons.price.idx**: Consumer price index (monthly indicator).
- **cons.conf.idx**: Consumer confidence index (monthly indicator).
- **euribor3m**: Euribor 3-month rate (daily indicator).
- **nr.employed**: Number of employees (quarterly indicator).
### Target Variable
- **responded**: Indicates whether the client subscribed to a term deposit.
## Results and Insights
Results and graphs are backed with appropriate inferences and insights, highlighting key outcomes from the analysis and providing actionable recommendations for future campaigns.