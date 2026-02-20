# Beyond Pens, Paper and Ink: Evaluating Council Spending

## Table of Contents
1. Introduction 
    - Rochdale Borough Council 
    - The Purpose Of This Project
2. Data Processing 
    - Importing Data
    - Organising Data
    - Cleaning Data
3. Exploratory Data Analysis 
    - Summary Statistics
    - Expenditure Over Time 
    - Expenditure By Department 
    - Revenue By Department 
4. Outliers and Anomalies 
    - Anomalous Transactions
    - Anomalous Dates 
5. Final Analyses
    - Better Care Fund Pooled Budget Spending - Why So Anomalous?
    - 5 Largest Transactions by Department 
    - Department Expenditure Over Time 
    - Stationary Expenditure
7. Conclusion 
    - So What?
  
# Introduction 
## Rochdale Borough Council
Local councils are the smallest level of government in the UK, and there are four types: borough, district, city, and parish/town councils. A borough is an administrative division, typically a town or district within a larger city that usually has its own governing body. Rochdale Borough Council is an example of this; it is one of ten boroughs forming the Greater Manchester Combined Authority (GMCA) and serves a population of 223,773 (ONS, 2021). The council operates in an area of higher-than-average deprivation, with high demand for social care and public services. Like most local councils, it faces ongoing financial pressures and must balance long-term spending priorities with controlled operational costs.
        
Local councils manage complex budgets and make decisions ranging from major statutory costs, such as adult and children’s social care, to smaller operational spending like stationery and printing. While large expenditures attract attention, small, recurring expenses can quietly add up. Aggregated across departments and time, these routine costs can reveal patterns that are often hidden in headline budget data. Office supplies are a simple, universal, and measurable cost, affecting the council as a whole. In a council such as Rochdale’s, where resources are constrained, analysing these routine costs can reveal trends in departmental behaviour, cost-efficiency, inconsistencies, and procurement practices.

![image.png](attachment:cc3d1db6-e693-46e8-9f00-ed644f727fdc.png)

## The Purpose of This Project 
Beyond Pens, Paper and Ink: Evaluating Council Spending aims to critically examine Rochdale Borough Council’s expenditure between July 2024 and June 2025, assessing efficiency, consistency, and transparency in public spending. While the central question, “How much does a council spend on stationery?” anchors the analysis, the project extends beyond office supplies to explore broader themes of financial accountability and governance. To answer this question effectively, I am taking a structured approach:


Exploratory Data Analysis (EDA):

Aiming to uncover overarching trends in council finances, addressing questions such as:
- How does expenditure vary over time?
- Which departments spend the most?
- Which departments generate the most revenue?

Anomaly Detection:

We identify departments with an unusually high proportion of anomalous transactions, signaling potential inefficiencies or irregularities.

Final Analysis:

The final stage examines:
-  The Better Care Fund Pooled Budget, which exhibited a high anomaly rate, to understand underlying causes.
-  The five largest transactions per department, providing context for financial burdens and operational priorities.
-  Departmental expenditure trends over time.
-  Stationery spending patterns, as a case study of routine costs.


Beyond numbers, this analysis is about accountability and public trust. Local councils manage taxpayers’ money under intense scrutiny, and even minor inefficiencies can erode confidence and raise governance questions. In communities like Rochdale, where demand for services is high, financial transparency is not just a technical requirement; it is a cornerstone of democratic trust. These questions can resonate from local government chambers to national politics, influencing public perception and electoral outcomes. By combining quantitative analysis with contextual interpretation, this project seeks to provide actionable insights into spending patterns, highlight areas of concern, and contribute to the ongoing conversation about responsible public finance management.
