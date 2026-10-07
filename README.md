🏢 Project Overview

This project is an interactive Power BI executive analytics solution designed to provide management with a consolidated view of a contingent workforce and its associated financial and insurance costs.

The dashboard transforms operational Excel data into a structured analytical model and provides decision-makers with visibility into:

Workforce size and composition
Employee compensation
Monthly payroll trends
Insurance expenditure
Workforce-related financial costs

The objective was not simply to create charts, but to convert raw operational workforce data into a management-oriented decision-support system.

🎯 Business Problem

Organizations managing contingent employees often have workforce information distributed across multiple operational files.

Information such as:

Employee details
Joining dates
Contract dates
Job titles
Nationality
Visa information
Salary
Insurance
Dependents
Invoices
EOSB
Bonuses
Other workforce costs

can exist in separate datasets.

This makes it difficult for management to answer basic but important questions:

How large is our contingent workforce?

What is the workforce demographic profile?

How much are we spending on salaries and insurance?

Which employee groups are driving insurance costs?

Which contracts are approaching expiry?

What workforce risks require attention?

How are workforce costs changing over time?

This project addresses these questions through a centralized Power BI reporting layer.

💡 Solution

I developed an interactive Power BI dashboard that brings together workforce, financial and insurance information into a single analytical environment.

The solution follows an end-to-end analytics workflow:

Raw Excel Data

↓

Data Cleaning & Transformation

↓

Data Modeling

↓

Calculated Columns & DAX Measures

↓

Interactive Visualizations

↓

Executive KPIs

↓

Business Insights & Decision Support

📂 Data Sources

The project was built using Excel-based operational data containing multiple business areas, including:

Workforce Data
Employee ID
Employee name
Designation
Job title
Client
Department/function
Office
Directorate
Joining date
Start date
Employee status
Nationality
Visa
Marital status
Dependents
Compensation Data
Basic salary
Allowances
Gross salary
CTC
Monthly payroll
Salary-related costs
Insurance Data
Employee insurance
Dependent insurance
Relationship
Age
Gender
Nationality
Insurance plan
Premium
Insurance cost
Policy period
Insurance location/emirate
Cost & Invoice Data

The source workbook also contains invoice and financial information covering categories such as:

Salary
Insurance
Bonus
EOSB
AMI
VISA/Other costs
Markup
Invoice amounts
VAT

The workbook includes dedicated sheets for workforce master data, insurance schedules, invoices, CTC, financial summaries, and insurance planning.

🧹 Data Preparation & Transformation

One of the major components of this project was converting operational Excel data into analysis-ready data.

Data Cleaning

I worked on:

Standardizing employee and workforce fields
Structuring employee-level records
Handling missing values
Preparing date fields
Organizing employee/dependent relationships
Creating consistent categorical fields
Structuring insurance and workforce cost data
Preparing data for time-based analysis
Data Transformation

Using Power Query, the data was transformed into a structure suitable for Power BI reporting.

Key transformation areas included:

Date preparation
Age-group categorization
Tenure categorization
Contract-expiry categorization
Workforce status classification
Insurance relationship classification
Cost-category standardization
Monthly reporting structure
🧠 Data Modeling & DAX

The project uses Power BI's data modeling and DAX capabilities to create analytical metrics rather than relying only on raw columns.

Examples of analytical KPIs include:

Workforce KPIs
Total Contingent Workers
Active Contingent Workers
New Joiners YTD
Average Age
Workers with >2 Years Tenure
Average Contract Duration
Exit YTD
Turnover Rate
Renewal / Extension Rate
Workforce Risk KPIs
Contracts Expiring Within 30 Days
Contracts Expiring Within 90 Days
Contract Expiry Profile
Long-tenured Workers
Workforce concentration by nationality
Workforce concentration by directorate
Insurance KPIs
Total Insurance Cost
Average Insurance Cost per Employee
Total Dependents Covered
Average Family Size
Insurance Cost by Age
Insurance Cost by Relationship
Insurance Cost by Emirate
Insurance Cost by Employee/Dependent
Financial KPIs
Total Payroll
Gross Salary Cost
Insurance Cost
EOSB Liability
Salary Distribution
Cost by Category
Monthly Workforce Cost
📊 Dashboard Architecture

The dashboard is organized into multiple analytical views.

1️⃣ Contingent Workforce Executive Dashboard

The executive dashboard provides a high-level view of workforce size and financial impact.

Key KPIs
Total Workers
Average Gross Salary
Total Monthly Payroll
Total Insurance Cost
Total EOSB Liability
Average Contract Duration
Visual Analysis

The dashboard provides:

Monthly Gross Salary Cost Trend
Insurance Cost Breakdown
Salary Distribution
Age Distribution
Nationality Distribution
Overall Cost Breakdown
Employee-level workforce table
Quick business insights

This page is designed for senior management, allowing decision-makers to understand workforce cost and composition quickly.

👥 2️⃣ Contingent Workforce Demographics

The workforce demographics page focuses on who makes up the workforce.

Key Metrics
Active Contingent Workers
Number of Nationalities
Average Age
New Joiners YTD
Contracts Expiring Within 90 Days
Analysis Includes

Nationality

Understand workforce diversity and nationality concentration.

Age

Identify workforce age distribution and potential workforce planning considerations.

Tenure

Analyze how long contingent workers have been with the organization.

Job Title

Understand workforce distribution across different job roles.

Contract Expiry

Identify employees approaching contract expiry.

Monthly Workforce Trend

Track changes in the contingent workforce over time.

⚠️ 3️⃣ Workforce Risk & Attention

A key focus of the dashboard is moving beyond descriptive reporting into risk-oriented workforce analytics.

The dashboard highlights:

Contract Risk
Contracts expiring within 30 days
Contracts expiring within 90 days
Expired contracts
Workers with longer tenure
Workforce Risk
Workforce concentration
Nationality concentration
Directorate concentration
Workforce turnover
Exit activity
Renewal/extension activity

This allows HR and workforce managers to prioritize areas that require attention instead of manually reviewing employee records.

🛡️ 4️⃣ Insurance Analytics

The insurance dashboard provides a dedicated view of the organization's employee and dependent insurance expenditure.

Executive KPIs
Total Employees
Total Dependents Covered
Total Insurance Cost
Average Cost per Employee
Expired Policies
Policies Expiring Within 30 Days
Average Family Size
Insurance Analysis

The dashboard analyzes insurance costs by:

Age Group
Emirate
Relationship
Employee vs. dependent
Nationality
Policy
Month
💰 Insurance Cost Analysis

One of the major objectives of the project was to understand what is driving insurance expenditure.

The dashboard therefore provides:

Insurance Cost by Age Group

Helps identify which age segments contribute most to insurance expenditure.

Insurance Cost by Emirate

Allows management to compare insurance costs across locations such as:

Abu Dhabi
Dubai
Other/GCC locations
Cost by Relationship

Breaks insurance expenditure between:

Employees
Spouses
Children/dependents
Top Insurance Costs

Highlights the highest insurance-cost records for further investigation.

💵 5️⃣ Workforce Financial Summary

The project also provides a consolidated financial view of workforce-related costs.

The financial summary includes categories such as:

Cost Category
Salary
Insurance
Bonus
EOSB
AMI
VISA / Others
Markup
Grand Total

This enables management to move from:

"How many workers do we have?"

to:

"What is the financial impact of our workforce?"

📈 Key Business Insights

The dashboard was designed to surface insights rather than simply display numbers.

Examples of insights surfaced through the dashboard include:

1. Salary is a major workforce cost driver

The executive dashboard highlights salary as the largest component of overall workforce-related expenditure.

This allows management to focus cost optimization discussions on the areas with the greatest financial impact.

2. Workforce demographics can be monitored interactively

Nationality and age distributions provide visibility into the composition of the contingent workforce and help identify workforce concentration.

3. Contract expiry creates an actionable HR workflow

Instead of manually reviewing employee contracts, management can immediately identify workers whose contracts are approaching expiry.

4. Insurance cost varies across employee groups

Insurance expenditure can be analyzed by age, relationship, location and employee/dependent status, helping identify the major cost drivers.

5. Workforce tenure provides retention and planning visibility

The tenure analysis helps identify the proportion of workers with longer service periods and supports workforce planning discussions.

