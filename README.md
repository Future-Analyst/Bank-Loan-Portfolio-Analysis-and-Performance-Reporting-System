# 🏦 Bank Loan Portfolio Analysis & Performance Reporting System

<p align="center">
  <img src="https://img.shields.io/badge/SQL-Analysis-blue?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL Analysis">
  <img src="https://img.shields.io/badge/Tableau-Dashboard-orange?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau Dashboard">
  <img src="https://img.shields.io/badge/Data-Analytics-2ea44f?style=for-the-badge" alt="Data Analytics">
  <img src="https://img.shields.io/badge/Business-Intelligence-purple?style=for-the-badge" alt="Business Intelligence">
</p>

<p align="center">
  <strong>A comprehensive SQL & Tableau solution for analyzing loan portfolio performance, credit risk, borrower characteristics, and lending trends.</strong>
</p>

<p align="center">
  <a href="https://public.tableau.com/app/profile/chigozie.achinike/viz/BankLoanDashboard_17312789293160/Summary?publish=yes">
    <img src="https://img.shields.io/badge/📊%20View%20Interactive%20Dashboard-Tableau%20Public-orange?style=for-the-badge" alt="View Tableau Dashboard">
  </a>
</p>

---

## 📌 Table of Contents

- [🎯 Project Overview](#-project-overview)
- [💡 Project Goal](#-project-goal)
- [❗ Problem Statement](#-problem-statement)
- [🛠️ Technologies Used](#️-technologies-used)
- [📊 Key Metrics](#-key-metrics)
- [🗂️ Data Terminologies](#️-data-terminologies)
- [🧮 SQL Analysis](#-sql-analysis)
- [📈 KPI Analysis](#-kpi-analysis)
- [📊 Dashboard & Visualizations](#-dashboard--visualizations)
- [🔎 Key Insights](#-key-insights)
- [💡 Recommendations](#-recommendations)
- [🚀 Future Enhancements](#-future-enhancements)
- [⚙️ Usage Instructions](#️-usage-instructions)
- [💻 System Requirements](#-system-requirements)
- [🎓 Skills Demonstrated](#-skills-demonstrated)
- [🏁 Conclusion](#-conclusion)

---

# 🎯 Project Overview

The **Bank Loan Portfolio Analysis & Performance Reporting System** is a data analytics project designed to provide a comprehensive view of a bank's lending operations.

The project combines **SQL-based data analysis** with an interactive **Tableau dashboard** to help stakeholders monitor loan portfolio performance, understand borrower characteristics, identify risk patterns, and support data-driven lending decisions.

The analysis covers:

- 💰 Loan applications
- 💵 Funded amounts
- 💳 Amount received
- 📈 Interest rates
- 📊 Debt-to-Income Ratio (DTI)
- 🟢 Good Loans
- 🔴 Bad Loans
- 🏦 Loan status
- 🌎 Regional performance
- ⏳ Loan terms
- 🎯 Loan purposes
- 👨‍💼 Employment length
- 🏠 Home ownership
- 📋 Loan grade and sub-grade

---

# 💡 Project Goal

The primary goal of this project is to create a centralized reporting system that enables stakeholders to:

> **Monitor portfolio health, understand lending performance, identify risk patterns, and make informed data-driven decisions.**

The project uses SQL to extract, transform, aggregate, and analyze loan data before presenting the results through an interactive Tableau dashboard.

---

# ❗ Problem Statement

Financial institutions need reliable and timely insights into their lending portfolios to understand how loans are performing and where potential risks may exist.

This project addresses the need for a reporting system capable of answering questions such as:

- How many loan applications have been received?
- How much has been funded?
- How much has been received from borrowers?
- How is the portfolio performing over time?
- What percentage of loans are classified as Good or Bad?
- Which loan purposes account for the largest portfolio exposure?
- How does loan performance vary across regions?
- How does loan performance vary by loan term?
- What is the average interest rate?
- What is the average Debt-to-Income Ratio?
- How does loan performance differ across grades and sub-grades?
- What borrower characteristics are associated with different portfolio segments?

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| 🗄️ **SQL** | Data extraction, transformation, aggregation and analysis |
| 📊 **Tableau** | Interactive dashboards and data visualization |
| 🧮 **SQL Queries** | KPI and portfolio calculations |
| 📁 **CSV / Dataset** | Source loan data |
| 📈 **Business Intelligence** | Portfolio monitoring and reporting |

---

# 📊 Key Metrics

The project tracks several important financial and portfolio KPIs.

## 💰 Loan Applications

- Total Loan Applications
- Month-to-Date (MTD) Applications
- Previous Month-to-Date (PMTD) Applications

## 💵 Funded Amount

- Total Funded Amount
- MTD Funded Amount
- PMTD Funded Amount

## 💳 Amount Received

- Total Amount Received
- MTD Amount Received
- PMTD Amount Received

## 📈 Interest Rate

- Average Interest Rate
- MTD Average Interest Rate
- PMTD Average Interest Rate

## 📊 Debt-to-Income Ratio

- Average DTI
- MTD Average DTI
- PMTD Average DTI

## 🏦 Loan Status

Loans are categorized into:

| Category | Loan Status |
|----------|-------------|
| 🟢 **Good Loans** | Fully Paid / Current |
| 🔴 **Bad Loans** | Charged Off |

---

# 🗂️ Data Terminologies

## Loan ID

A unique identifier assigned to each loan application.

## Address State

The geographic location associated with the borrower, used for regional analysis.

## Employee Length

The length of time the borrower has been employed.

## Employee Title

The occupation or job title of the borrower.

## Grade & Sub-Grade

Credit-risk classifications associated with each loan.

## Loan Status

The current state of the loan.

Possible values include:

- Fully Paid
- Current
- Charged Off

## Interest Rate

The annual interest rate applied to the loan.

## Debt-to-Income Ratio (DTI)

A ratio used to measure the borrower's debt obligations relative to income.

## Loan Amount

The principal amount associated with the loan.

## Loan Purpose

The reason for borrowing, such as:

- Debt Consolidation
- Education
- Home Improvement
- Credit Card
- Major Purchase
- Small Business

---

# 🧮 SQL Analysis

The project contains SQL queries designed to extract and analyze the loan portfolio.

## 📌 Loan Applications

Calculations include:

- Total Loan Applications
- MTD Loan Applications
- PMTD Loan Applications

## 💰 Funded Amount

Calculations include:

- Total Funded Amount
- MTD Funded Amount
- PMTD Funded Amount

## 💳 Amount Received

Calculations include:

- Total Amount Received
- MTD Amount Received
- PMTD Amount Received

## 📈 Interest Rate

Calculations for:

- Average Interest Rate
- MTD Average Interest Rate
- PMTD Average Interest Rate

## 📊 DTI

Calculations for:

- Average DTI
- MTD Average DTI
- PMTD Average DTI

## 🟢 Good Loan Analysis

Queries calculate:

- Good Loan Applications
- Good Loan Percentage
- Good Loan Funded Amount
- Good Loan Amount Received

## 🔴 Bad Loan Analysis

Queries calculate:

- Bad Loan Applications
- Bad Loan Percentage
- Bad Loan Funded Amount
- Bad Loan Amount Received

## 🏦 Loan Status Analysis

Detailed breakdown of loans by:

- Current
- Fully Paid
- Charged Off

## 🌎 Regional Analysis

Loan portfolio analysis by state, including:

- Application volume
- Funded amount
- Loan performance

## ⏳ Term Analysis

Analysis of loan performance based on loan duration.

## 👨‍💼 Employee Length Analysis

Analysis of loan distribution based on borrower employment length.

## 🏠 Home Ownership Analysis

Analysis of loans based on home ownership categories.

## 🎯 Loan Purpose Analysis

Analysis of portfolio performance based on the purpose of the loan.

---

# 📈 KPI Analysis

## 🟢 Good Loan KPIs

Good loans are categorized as loans that are:

- Fully Paid
- Current

Key metrics include:

- Good Loan Applications
- Good Loan Percentage
- Good Loan Funded Amount
- Good Loan Amount Received

---

## 🔴 Bad Loan KPIs

Bad loans are categorized as loans that have been:

- Charged Off

Key metrics include:

- Bad Loan Applications
- Bad Loan Percentage
- Bad Loan Funded Amount
- Bad Loan Amount Received

---

# 📊 Dashboard & Visualizations

The project includes an interactive Tableau dashboard designed to make the analysis easy to understand.

### 📌 Tableau Public Dashboard

<p align="center">

<a href="https://public.tableau.com/app/profile/chigozie.achinike/viz/BankLoanDashboard_17312789293160/Summary?publish=yes">

<img src="https://img.shields.io/badge/🚀%20OPEN%20INTERACTIVE%20DASHBOARD-Tableau%20Public-orange?style=for-the-badge">

</a>

</p>

---

## 📊 Summary Dashboard

![Summary Dashboard](https://github.com/user-attachments/assets/73cfd59c-12a3-4e30-bf31-f40d33d3e1e9)

The summary dashboard provides an overview of the most important portfolio KPIs.

---

## 🔎 Details Dashboard

![Details Dashboard](https://github.com/user-attachments/assets/490a7e11-0dd6-4ba0-b970-f62bef61683f)

The details dashboard provides deeper analysis of loan characteristics and portfolio segments.

---

## 📈 Overview Dashboard

![Overview Dashboard](https://github.com/user-attachments/assets/a0d299ce-a9be-4784-9975-c990364be69a)

The overview dashboard provides additional visual analysis of portfolio performance.

---

# 📊 Visualization Types

The project uses several visualization techniques.

### 📈 Monthly Trends

Line charts are used to identify changes in:

- Loan applications
- Funded amounts
- Amount received
- Portfolio activity

### 🌎 Regional Analysis

Filled maps visualize loan distribution and performance across states.

### ⏳ Loan Term Analysis

Donut charts display the distribution of loans across different terms.

### 👨‍💼 Employee Length Analysis

Bar charts show loan distribution based on employment length.

### 🎯 Loan Purpose Analysis

Bar charts show the distribution of loans across different purposes.

### 🏠 Home Ownership Analysis

Tree maps visualize the distribution of loans across home ownership categories.

---

# 🔎 Key Insights

The analysis provides several dimensions for understanding the bank's loan portfolio.

## 📈 Trend Analysis

Monthly analysis can reveal changes in:

- Loan applications
- Funded amounts
- Amount received
- Portfolio growth

## 🛡️ Risk Profiling

Good Loan and Bad Loan analysis provides visibility into overall portfolio quality.

## 🌎 Regional Trends

Regional analysis provides insights into differences in loan activity and performance across states.

## ⏳ Term-Based Trends

Loan-term analysis helps identify differences in portfolio composition and repayment performance.

## 🎯 Purpose-Based Trends

Loan-purpose analysis identifies the types of borrowing that make up the largest portions of the portfolio.

## 👥 Borrower Characteristics

Employee length and home ownership provide additional dimensions for understanding the borrower population.

---

# 💡 Recommendations

Based on the analysis, the following recommendations can help improve portfolio monitoring, risk management, data quality, and reporting efficiency.

## 1️⃣ Strengthen Risk-Based Lending

The bank should continue incorporating borrower and loan risk indicators such as:

- Loan Grade
- Loan Sub-Grade
- Interest Rate
- Debt-to-Income Ratio
- Employment Length
- Previous Loan Performance

into credit assessment and portfolio monitoring processes.

Higher-risk applications can receive appropriate additional affordability and creditworthiness assessments in accordance with the bank's lending policies.

---

## 2️⃣ Closely Monitor Bad Loans

Charged-off loans should be monitored as an important portfolio-risk indicator.

The bank can establish early-warning monitoring for accounts showing signs of repayment difficulty so that appropriate interventions can occur before loans deteriorate further.

---

## 3️⃣ Improve Portfolio Segmentation

Portfolio performance should be analyzed across multiple dimensions rather than relying only on overall portfolio averages.

Regular analysis should compare performance by:

- Loan Grade
- Loan Sub-Grade
- Loan Purpose
- Loan Term
- Geographic Location
- Home Ownership
- Employment Length
- Loan Status

---

## 4️⃣ Review Loan Pricing by Risk Level

Interest rates should be evaluated alongside borrower and loan risk characteristics.

Historical portfolio performance can help assess whether loan pricing appropriately reflects differences in credit risk while remaining consistent with applicable lending policies and regulations.

---

## 5️⃣ Monitor Loan Purposes

Loan purposes should be regularly evaluated using:

- Application Volume
- Funded Amount
- Amount Received
- Loan Status
- Charge-Off Rate

Where particular loan-purpose segments demonstrate persistently weaker performance, management can review the relevant underwriting criteria and risk controls.

---

## 6️⃣ Monitor Regional Portfolio Performance

Regional performance should be included in regular portfolio reviews.

Analysis can compare:

- Application Volume
- Funded Amount
- Repayment Performance
- Loan Status

Regional differences should be interpreted alongside borrower and loan characteristics rather than being treated as evidence of borrower risk based solely on geographic location.

---

## 7️⃣ Optimize Loan-Term Management

The relationship between loan term and repayment performance should be continuously evaluated.

Longer-term loans may provide lower periodic payments but extend the period over which repayment risk exists.

Loan-term decisions should therefore be considered alongside:

- Borrower affordability
- Credit risk
- Loan purpose
- Expected repayment performance

---

## 8️⃣ Establish Continuous KPI Monitoring

The Tableau dashboard should be used as an ongoing portfolio-monitoring tool.

Key indicators should be tracked regularly:

- Total Loan Applications
- Funded Amount
- Amount Received
- Good Loan Percentage
- Bad Loan Percentage
- Average Interest Rate
- Average DTI
- Charge-Off Rate
- Portfolio Growth
- Recovery Performance

---

## 9️⃣ Introduce Early-Warning Indicators

The reporting system can be enhanced with early-warning indicators designed to identify potentially deteriorating loans.

Potential indicators include:

- Delinquency Status
- Repayment Behavior
- Payment History
- Loan Age
- DTI
- Changes in borrower financial information
- Historical loan performance

This would move the reporting system toward more proactive portfolio monitoring.

---

## 🔟 Improve Data Quality & Governance

The reporting process should include automated data-quality checks for:

- Missing Values
- Duplicate Loan IDs
- Invalid Dates
- Inconsistent Categories
- Invalid Numerical Values
- Unexpected Changes in Data Structure

A formal data dictionary should also be maintained so that business users have a consistent understanding of metrics and fields.

---

## 1️⃣1️⃣ Automate Report Refreshes

The SQL and Tableau workflow can be improved by introducing an automated data-refresh process.

Automated refreshes would:

- Reduce manual reporting effort
- Improve reporting consistency
- Provide more current portfolio information
- Reduce the risk of outdated dashboards

Data-validation checks should ideally run before each dashboard refresh.

---

## 1️⃣2️⃣ Improve Dashboard Functionality

Future dashboard versions could include additional analytical views such as:

- Delinquency Trends
- Default Trends
- Recovery Rate
- Loss Rate
- Loan Vintage Analysis
- Cohort Analysis
- Portfolio Concentration
- Risk-Adjusted Return
- Expected Loss
- Outstanding Principal
- Average Loan Age
- Performance by Loan Grade
- KPI Drill-Downs

---

# 🚀 Future Enhancements

The current project provides a strong foundation for descriptive loan portfolio analysis.

The following enhancements could transform it into a more comprehensive portfolio-risk management system.

## 🤖 Predictive Credit-Risk Modeling

Machine-learning models could be introduced to estimate the probability of loan default or charge-off using historical loan characteristics.

Potential models include:

- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting

Model performance should be carefully validated before being considered for operational decision-making.

---

## 🔄 Dynamic SQL Reporting

The SQL analysis can be improved by replacing fixed reporting dates with dynamic date parameters.

This would allow queries to automatically calculate:

- Current MTD
- Previous MTD
- Year-to-Date
- Previous Year-to-Date
- Current Reporting Period
- Previous Reporting Period

---

## 🧱 Reusable Analytical Views

Frequently used calculations can be consolidated into reusable database views or an analytical layer.

Benefits include:

- Improved SQL maintainability
- Consistent calculations
- Better reporting performance
- Increased reusability
- Easier Tableau integration

---

## 🔁 Automated Data Pipeline

A future implementation could introduce an automated ETL/ELT architecture:

```text
Source Data
     ↓
Data Validation
     ↓
Data Transformation
     ↓
SQL Database
     ↓
Analytical Layer
     ↓
Tableau Dashboard
     ↓
Business Insights
