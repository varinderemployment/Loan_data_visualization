 Loan Data Visualization
Project Overview

This project analyzes loan application data to understand approval trends, applicant profiles, and risk patterns, and presents the findings through an interactive Power BI dashboard.

The analysis uses Excel, Power Query, DAX, Power BI, and SQL to clean, transform, analyze, and visualize the data.

Business Problem

Improve visibility into loan approval trends, customer segments, and risk patterns to support data-driven lending decisions.

Project Objectives
Analyze loan approval and rejection trends.
Understand applicant profiles and segments.
Identify factors associated with loan approval.
Analyze income, loan amount, credit history, education, gender and property area.
Build an interactive dashboard for management reporting.
Dataset

The dataset contains 614 loan applications with the following fields:

Loan_ID – Unique application identifier
Gender, Married, Dependents, Education, Self_Employed – Applicant demographic details
ApplicantIncome, CoapplicantIncome – Income details
LoanAmount, Loan_Amount_Term – Loan details
Credit_History – Applicant's credit history (Good/Bad)
Property_Area – Rural, Semiurban, or Urban
Loan_Status – Approved or Rejected
Tools Used
Power BI
Power Query
DAX
Excel
SQL
Data Cleaning & Transformation
Handled missing values (present across Gender, Married, Dependents, Self_Employed, LoanAmount, Loan_Amount_Term, and Credit_History fields).
Checked and corrected data types.
Removed duplicate records where applicable.
Standardized categorical fields.
Created calculated fields such as:
Total Income
Loan Amount
Loan Term
Loan-to-Income Ratio
Prepared the dataset for visualization.
Dashboard / Analysis

The Power BI dashboard analyzed:

Loan Approval vs Rejection
Credit History vs Loan Status
Loan Status by Property Area
Applicant Income and Assets
Loan Amount and Loan Duration
Applicant segments (Married, Self-Employed, Credit History, Property Area)
Key Results
Analyzed 614 loan applications, with an overall approval rate of 68.7% (422 approved, 192 rejected).
Credit history was the strongest factor in approval outcomes: applicants with a good credit history were approved 79.6% of the time, versus only 7.9% for those with a bad credit history.
Property area influenced approval rates: Semiurban applicants had the highest approval rate (76.8%), followed by Urban (65.8%) and Rural (61.5%).
Applicant income was heavily right-skewed (median ~₹3,813, average ~₹5,403), with a small number of high-income applicants pulling the average well above the typical case.
Loan amounts ranged widely, with a median of ₹128K and 75% of loans under ₹168K.
Identified data quality gaps: Credit_History was missing for 50 applicants (~8%), and LoanAmount was missing for 22 applicants (~3.6%), flagged for improved data collection.
Project Workflow

Raw Data → Data Cleaning → Data Transformation → Exploratory Data Analysis → Data Modeling → DAX Measures → KPI Development → Power BI Dashboard → Business Insights

Key Outcome

Highlighted loan approval trends and customer/risk patterns — particularly the strong link between credit history and approval likelihood, and the variation in approval rates across property areas — to provide clearer, data-driven insights for lending decisions.
