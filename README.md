# Unit2_Project
This project focuses on analyzing education data using Google Sheets. It includes working with three related datasets : students, subjects, and scores - to explore how data can be cleaned, linked, and visualized. See assignment: https://docs.google.com/spreadsheets/d/1n0qTmi6gnysfKMtF_oGLFGCAXb8xrg_med8SFh8w_K8/edit?usp=sharing

## Objective
This assignment will test your ability to apply everything you’ve learned in Unit 2 from
importing and cleaning datasets to linking multiple data sources using relational formulas and
building a summary dashboard.
By the end of this project, you should be able to demonstrate:
• Your understanding of data foundations and relationships.
• Your ability to clean and transform raw datasets.
• The use of Google Sheets formulas to perform real-world data analysis. •
The ability to automate tasks and present insights clearly.

## Overview
You are to choose one of three domains below and complete a full data cleaning and analysis
workflow using the provided datasets.
Each domain includes three related CSV files that you will import into Google Sheets, clean, and
connect using relational formulas.
1️⃣Health Domain
• patients.csv
• visits.csv
• billing.csv

## Instructions
STEP 1 – Import & Explore
1. Open a new Google Sheet and name it Unit 2 Mini Project – [Your Name].
2. Import the three CSVs of your chosen domain.
3. Rename each tab appropriately (e.g., Patients, Visits, Billing).
4. Explore the data and briefly describe what each sheet represents.

STEP 2 – Data Cleaning
Clean each sheet to make the data analysis-ready.
Focus on:
• Removing duplicates.
• Fixing inconsistent text cases using.
• Trimming extra spaces.
• Handling missing values.
• Standardizing dates.
• Replacing errors.
• Document all your cleaning steps in a new sheet titled Data_Cleaning_Log.

STEP 3 – Data Linking (Relational Formulas)
Now connect your datasets using lookup and query functions.
Use at least two of the following relational formulas:
• =VLOOKUP () → Match and retrieve related values (e.g., Patient Name from Patients
sheet).
• =INDEX (MATCH ()) → Flexible lookup for combined keys.
• =QUERY () → Perform SQL-like grouping or filtering.
• =FILTER () → Extract subsets dynamically.
Example:

• In the visits sheet, link the patient’s full name using VLOOKUP from the patient’s sheet. • In
the billing sheet, link the doctor name and patient ID from the visits sheet. • Create one
combined table (using QUERY or {} merge formula) summarizing information from all
three sheets.

STEP 4 – Analysis & Dashboard
Use Google Sheets features to summarize your cleaned data.
1. Pivot Tables:
o Summarize totals, averages, and counts (e.g., total payments per region, average
scores per subject, total transactions per customer).

2. Conditional Formatting:
o Highlight top performers, unpaid bills, or transactions above a threshold.
3. Charts:
o Create at least one bar or pie chart showing key insights (e.g., number of visits per
doctor, pass rate by subject, or spending by category).

4. Dashboard:
o Combine your visuals and pivot tables into one sheet titled Dashboard.

STEP 5 – Automation (Optional for Bonus Marks)
Record a macro to automatically:
• Format your data,
• Highlight missing entries, or
• Update your dashboard.
Try writing a simple Google Apps Script to replace all “N/A” entries with blanks or auto
refresh your summary sheet.
