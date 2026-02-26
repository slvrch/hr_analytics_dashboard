# Employee Attrition Risk Analysis Dashboard

## About Me
I am a Mathematics graduate with a strong interest in Data Analytics and Business Intelligence. I specialize in transforming raw data into actionable business insights through structured analysis and interactive dashboards. This portfolio project demonstrates my ability to perform end-to-end data analysis aligned with real business challenges.

## Project Overview
Employee attrition is a critical business issue that impacts organizational stability, productivity, and recruiment costs.
This project analyzes workforce data to identify key drivers of employee turnover and builds an interactive dashboard to support HR decision-making.
The goal of this analysis is to transform raw employee data into actionable insights that help reduce attrition risk.

## Portfolio Objective
This project is part of my professional Data Analyst portfolio.

**Target Role:**
- Data Analyst
- Business Intelligence Analyst

**Value Demonstrated:**
- End-to-end data analysis
- KPI development & benchmarking
- Business-oriented dashboard design
- Data storytelling & insight generation

## Business Problem
Jaya Jaya Maju, a multinational company with over 1,000 employees, is experiencing an attrition rate above 10%.

High employee turnover leads to:
- Increased recruitment costs
- Loss of institutional knowledge
- Operational instability

The HR department requires data-driven insights to:
- Identify high-risk employee segments
- Understand key drivers of attrition
- Monitor workforce risk factors effectively

## Dataset Overview
- 1,470 employee records
- 35 features including:
    - Demographics (Age, Gender, Marital Status)
    - Job-related attributes (Department, Job Role, Overtime)
    - Compensation (Monthly Income)
    - Satisfaction metrics (Job Satisfaction, Environment Satisfaction)
    - Tenure metrics (Years at Company, Years in Current Role)

## Data Preparation
Data preparation was performed using Python.

Steps included:
- Handling missing values
- Feature grouping (Age Group, Tenure Categories)
- Creation of calculated KPIs:
     - Total Employee
     - Attrition Rate
     - Total Attrition Count
     - Overtime Percentage
     - Risk Classification
     - Average Monthly Income

Tools used:
- Pandas
- Numpy
- Matplotlib/Seaborn
- Statistical testing (Mann-Whitney U, Chi-Square)

## Analytical Approach
The analysis focused on identifying workforce segments with elevated attrition risk.

**Key Analytical Dimensions:**
- Job Role segmentation
- Tenure-based attrition patterns
- Overtime impact
- Satisfaction metrics correlation
- Marital status segmentation
- Age group distribution

A benchmark attrition rate was used to classify risk levels into:
- High Risk
- Moderate Risk
- Low Risk

## Statistical Validation
To ensure analytical findings are statistically reliable, inferential testing was performed:
- Mann-Whitney U Test for numerical variables
- Chi-Square Test for categorical variables

Key statistically significant factors influencing attrition:
- Age
- Monthly Income
- Years at Company
- Overtime
- Job Role
- Marital Status
- Job Satisfaction
- Environment Satisfaction

All significant variables demonstrated p-values < 0.05, indicating meaningful differences between employees who left and those who stayed.

This statistical validation supports the credibility of segmentation and dashboard insights.

## Key Insights
- Sales Representatives exhibit the highest attrition rate (43%).
- Employees with 0-2 years tenure show significantly elevated turnover.
- Employees working overtime demonstrate substantially higher attrition probability.
- Low environment satisfaction strongly correlates with attrition risk.
- Single employees show higher attrition rates compared to married employees.
  
## Business Recomendations
Based on the analysis, the following strategic actions are recommended:
- Implement early-career retention programs.
- Review workload distribution in Sales department.
- Introduce overtime monitoring and workload balancing policies.
- Improve workplace environment engagement initiatives.
- Develop targeted retention strategies for high-risk employee segments.

## Dashboard Overview
The final dashboard was developed using Tableau and includes:
- Executive KPI summary
- Attrition benchmark comparison
- Segmentation by Job Role, Marital Status, and Age
- Tenure-based risk visualization
- Satisfaction heatmaps
- Interactive filtering and drill-down functionality

Interactive version:
https://public.tableau.com/app/profile/silvia.rachmawati/viz/ExecutiveHROverviewDashboard/RiskSegmentsandKeyDrivers?publish=yes

### Dashboard Preview

<img width="1652" height="806" alt="tableau" src="https://github.com/user-attachments/assets/843fc954-3435-4001-9d8a-f2b48232766b" />


In addition, a secondary dashboard was developed in Metabase to demonstrate BI tool adaptability.

<img width="418" height="848" alt="Metabase-dashboard" src="https://github.com/user-attachments/assets/b7011446-e999-4e95-b611-46d8ca889cba" />


## Tools & Technologies

**Programming & Data Processing**
- Python (Pandas, Numpy)
- Statistical Analysis (SciPy)
- SQLite (for data storage)
  
**Visualization & BI**
- Tableau
- Metabase (secondary dashboard)

## Conclusion
This project demonstrates the ability to:
- Translate business problems into analytical frameworks
- Perform structured data preparation
- Develop KPIs aligned with business objectives
- Deliver interactive dashboard for executive-level decision making


