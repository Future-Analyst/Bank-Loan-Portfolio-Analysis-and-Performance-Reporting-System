
# Bank Loan Portfolio Analysis and Performance Reporting System

###    Goal
The Bank Loan Report aims to provide a comprehensive analysis of the bank's lending operations, helping stakeholders to monitor and assess key loan-related metrics. The goal is to facilitate data-driven decision-making, track the health of the loan portfolio, and identify trends that can inform lending strategies. This report includes insights into loan applications, funded amounts, repayment performance, and the risk profiles of the bank's borrowers, categorized by various factors such as loan status, region, term, and purpose.

The project includes detailed SQL queries to extract, aggregate, and analyze loan data, providing valuable insights into Good Loans, Bad Loans, and key performance indicators (KPIs) that support strategic lending decisions.

## Publishing Project to Tableau Public

link: https://public.tableau.com/app/profile/chigozie.achinike/viz/BankLoanDashboard_17312789293160/Summary?publish=yes

![summary dashboad img](https://github.com/user-attachments/assets/73cfd59c-12a3-4e30-bf31-f40d33d3e1e9)


![Details Dashboard img](https://github.com/user-attachments/assets/490a7e11-0dd6-4ba0-b970-f62bef61683f)


![overview dashboard img](https://github.com/user-attachments/assets/a0d299ce-a9be-4784-9975-c990364be69a)



### Problem Statement
In order to effectively monitor and assess the performance of the bank's lending activities, the Bank Loan Report provides insights into the following critical metrics:

####   Loan Applications:   
 Total loan applications, Month-to-Date (MTD), and Previous Month-to-Date (PMTD) loan applications.
Funded Amounts: The total amount of funds disbursed, MTD, and PMTD.

#### Amount Received: 
The total payments received from borrowers, MTD, and PMTD.
Interest Rates and Debt-to-Income Ratio (DTI): Average interest rates and DTIs, MTD, and PMTD.
Loan Status: Breakdown of loans by status (good vs. bad loans).

#### Loan Portfolio Breakdown: 
Analysis by loan term, loan purpose, employee length, and home ownership.
The report will help the bank track key performance indicators (KPIs), assess the quality of loans (good vs. bad), detect regional and term-based trends, and facilitate compliance and strategic planning.

#### Table of Contents
Project Overview

Objective
Key Metrics Tracked
Data Terminologies

Fields Used in Data
Loan ID
Address State
Employee Length
Employee Title
Grade and Sub Grade
Loan Status
Interest Rate
DTI (Debt-to-Income Ratio)
Loan Amount, etc.
SQL Queries

Total Loan Applications
MTD and PMTD Loan Applications
Funded Amounts (Total, MTD, PMTD)
Amounts Received (Total, MTD, PMTD)
Interest Rate and DTI Calculations (Average)
Good Loan Metrics
Bad Loan Metrics
Loan Status Breakdown
Regional Breakdown (State)
Loan Term Breakdown
Home Ownership Breakdown
Employee Length Analysis
Loan Purpose Breakdown
Grade A Filtered Loan Data
KPI Analysis

Good Loan KPIs
Bad Loan KPIs
Risk and Performance Metrics
Portfolio Health
Visualizations

Dashboard Overview
Graphical Representations of Data:
Monthly Trends (Line Charts)
Regional Analysis (Filled Maps)
Loan Term Analysis (Donut Charts)
Employee Length Analysis (Bar Charts)
Loan Purpose Breakdown (Bar Charts)
Home Ownership Analysis (Tree Maps)
Data Insights

Key Findings
Trends and Patterns Identified
Recommendations
Usage Instructions

Database Setup
Running SQL Queries
Interpreting Results
System Requirements

Database Management System (DBMS)
Access Permissions
Required Software (e.g., SQL client)
Conclusion

Summary of Benefits
Next Steps for Implementation
1. Project Overview
Objective
The Bank Loan Report provides a detailed analysis of the bank’s loan portfolio, helping decision-makers monitor and manage lending performance. By aggregating loan data across various dimensions (loan status, region, employee length, etc.), 

the report aims to:

Provide insights into key loan metrics.
Analyze the distribution of loans by different characteristics (loan term, homeownership, purpose, etc.).
Track the health of the loan portfolio and identify opportunities for improvement.
Support strategic decisions regarding lending policies, interest rates, and risk management.
Key Metrics Tracked
The key performance indicators (KPIs) tracked include:

Loan Applications:

 Number of loan applications, MTD and PMTD.
Loan Funded Amount: Total loan amounts disbursed.
Amount Collected: Total payments made by borrowers.
Interest Rate: Average interest rates for loans.
Debt-to-Income Ratio (DTI): Average ratio for loan applicants.

Loan Status:

 Categorization of loans into 'Good' (Fully Paid, Current) and 'Bad' (Charged Off).
Regional, Term, and Purpose-Based Analysis: Distribution of loans by location, loan term, and purpose.

2. Data Terminologies

Fields Used in Data
Loan ID: A unique identifier for each loan application.
Address State: Borrower’s location, used for regional analysis.
Employee Length: Duration of employment, used to assess financial stability.
Employee Title: Occupation of the borrower, useful for assessing income.
Grade and Sub Grade: Risk classification based on creditworthiness.
Loan Status: Categorizes loans as 'Fully Paid', 'Current', or 'Charged Off'.
Interest Rate: The annual cost of the loan, expressed as a percentage.
Debt-to-Income Ratio (DTI): The ratio of debt to income, used to evaluate repayment capacity.
Loan Amount: The principal amount of the loan.
Purpose: The reason for the loan (e.g., debt consolidation, education).

3. SQL Queries

This section contains all SQL queries used for generating the reports and insights within the Bank Loan Report.

Loan Applications: 

Total loan applications, MTD, PMTD.
Funded Amount: Total funded amounts for loans.
Amount Collected: Total payments made by borrowers, MTD, PMTD.
Interest Rate: Calculations of the average interest rates.

DTI: 

Calculations of the average DTI ratios.
Good/Bad Loan Breakdown: Queries to calculate the percentage of good and bad loans.
Loan Status Overview: Detailed loan status breakdowns for risk analysis.
Regional/Term-Based Analysis: Queries for aggregating loan data based on region, term, employee length, and home ownership.

4. KPI Analysis

Good Loan KPIs
Percentage of loans that are fully paid or current.
Total loan applications and funds for good loans.
Amounts received from good loans.
Bad Loan KPIs
Percentage of loans that are charged off.
Total loan applications and funds for bad loans.
Amounts received from bad loans.

5. Visualizations

#### Dashboard Overview

The project includes a variety of charts and visualizations to make it easy to interpret loan data:
Line Charts for monthly trends.
Filled Maps for regional analysis.
Donut Charts for loan term analysis.
Bar Charts for loan purpose and employee length analysis.

Tree Maps for home ownership breakdown.

6. Data Insights
The analysis provides key insights into the performance of the loan portfolio, such as:

Trend analysis: 

Identifying seasonal variations or long-term changes in loan applications and funded amounts.
Risk profiling: Understanding the risk profile of the loan portfolio by analyzing good vs. bad loans.
Regional and term-based trends: Insights into regional differences in loan demand and default rates.

7. Usage Instructions

Database Setup
Ensure that the database is set up with the appropriate tables and data fields.
Use a compatible SQL client (e.g., MySQL Workbench, SQL Server Management Studio) to run the queries.
Running SQL Queries
Execute each query in your SQL client to obtain the desired data.
Results can be exported to CSV or other formats for further analysis or visualization.

8. System Requirements

Database Management System (DBMS): MySQL, PostgreSQL, or another SQL-based DBMS.
SQL Client: A compatible SQL client (e.g., MySQL Workbench, pgAdmin, etc.).
Required Software: No specific software other than the DBMS and SQL client is required.

9. Conclusion

This Bank Loan Report offers a comprehensive view of the bank's loan portfolio and provides detailed insights into key performance metrics. By using this report, the bank can make informed decisions regarding loan approvals, risk management, and portfolio optimization.


