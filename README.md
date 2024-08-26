# Employee Attrition Analysis Case Study

This repository contains a comprehensive analysis of employee attrition data for XYZ Company, aimed at identifying the key factors influencing employee resignations and providing actionable recommendations to reduce the attrition rate.
Business Objective

XYZ Company has observed an increase in their attrition rate compared to the previous year. The HR department suspects that there are specific factors driving this trend. The primary objectives of this analysis are to:

  - Identify the causes of attrition.
  - Provide recommendations to address and reduce the high attrition rate.

## Problem Statement

The goal is to analyze the available data to uncover insights and patterns that contribute to employee resignation. This includes both exploratory data analysis (EDA) and predictive modeling to determine the most significant features leading to attrition.
## Data Cleaning

  Handling Missing Values: Columns with 100% null values and non-unique columns were removed.
  Assessing Columns: Columns with a high percentage of null values were dropped.
  Excluding Unnecessary Columns: Columns that did not contribute to the analysis were excluded.

## Exploratory Data Analysis (EDA)

The EDA was conducted to understand the characteristics of the data through the following analyses:
1. Univariate Analysis

    Purpose: Examines each feature individually to understand its distribution and summary statistics (e.g., mean, median, mode).
    Outcome: Provides insights into the general characteristics of the features, helping to identify patterns and anomalies.

2. Segmented Univariate Analysis

    Purpose: Analyzes features within different segments (e.g., region, awards won) to explore distribution variations.
    Outcome: Highlights differences between segments, revealing how feature characteristics influence or are influenced by segment-specific behaviors.

3. Bivariate Analysis

    Purpose: Investigates the relationships between pairs of variables to identify correlations or dependencies.
    Outcome: Provides insights into how changes in one variable might impact another.

## Key Insights from EDA

  Length of Service: Employees with shorter service lengths (0-2 years) are more likely to resign. The likelihood decreases after 5 years.
  Previous Year Rating: Higher-rated employees are more prone to resignation.
  Training Scores: Employees with higher average training scores tend to seek opportunities elsewhere.
  Education: Employees with a Master’s degree or higher are more likely to resign than those with a Bachelor’s degree.
  KPIs Met > 80%: High-performing employees who consistently meet or exceed KPIs are more likely to resign.
  Awards Won: Employees who have won awards are more likely to leave.

## Model Development (Optional Step)
### Feature Engineering and Model Building

Predictive models were developed to validate the findings from the EDA and identify top features contributing to employee resignation. Models used include Logistic Regression and Random Forest Classification, with and without the class_weight parameter.
### Model Insights

  Logistic Regression & Random Forest: Both models identified similar top contributing features.
  Class Weight Adjustment: Incorporating class_weight increased recall but reduced accuracy, illustrating the trade-off between model performance metrics.

## Conclusions: Causes of Attrition

  Department: Higher resignation rates in R&D.
  Region: Specific regions (4, 25, 28) show higher attrition.
  Education: Higher-educated employees are more prone to resign.
  Recruitment Channel: Employees recruited via referrals tend to resign more often.
  Training Opportunities: Fewer training opportunities correlate with higher resignation rates.

## Recommendations to Reduce Attrition

  Enhance Employee Recognition Programs
  Improve Access to Training and Development
  Revise Employee Onboarding and Integration Processes
  Conduct Regular Employee Engagement Surveys
  Develop Tailored Career Development Plans
  Focus on Retaining Newer Employees
    Implement Regional-Specific Strategies
