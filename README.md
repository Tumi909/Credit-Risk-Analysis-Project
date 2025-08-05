# Credit Risk Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning or Preparation](#data-cleaning-or-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results or Findings](#results-or-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

### Project Overview

This project aimed to analyze credit risk factors and borrower behaviour using a dataset of loan applications. The goal was to identify patterns in default rates, approval trends and income-to-debt relationships in order to support data-driven lending decisions.

### Data Sources

A publicly available credit risk dataset containing borrower demographics, income, loan details, interest rates, employment history and loan status. CSV file imported into SQL and Excel for preprocessing and analysis.

### Tools

- Excel - Data Cleaning
- SQL Server - Data Analysis
- PowerBI - Creating Reports

### Data CLeaning or Preparation

In the initial data preparation phase, we performed the following tasks:
Removed duplicates and irrelevant columns

1. Converted categorical values (e.g. 'Y'/'N' in default column) to binary format (1/0).

2. Handled outliers (e.g. unrealistic employment years).

3. Grouped variables into meaningful bands (e.g. income ranges, DTI levels, employment length).

4. Filled or filtered null values where necessary.

5. Split large dataset in Excel before importing to SQL.

### Exploratory Data Analysis

1. Analyzed distribution of income, loan amounts, credit history and approval rates.

2. Visualized credit behavior across loan purposes, home ownership status and employment history.

3. Identified correlations between income, debt-to-income ratio (DTI) and loan default rates.

### Data Analysis

Key insights calculated using SQL:

- Default rate by income group, loan grade, and loan intent.

- Average loan amount by income group.

- Approval rate by employment length.

- Debt-to-Income (DTI) bands and corresponding risk levels.

- Credit history vs default rate.

- Loan intent vs interest rate.

### Results or Findings

The analysis results are summarised as follows:
1. Higher default rates observed among borrowers with low income, short employment history and high DTI.

2. Loan intent significantly affects risk – personal and medical loans had higher default rates.

3. Interest rates tended to be higher for riskier loan intents.

4. Longer credit history correlated with lower default rates.

5. Approval rates were higher among borrowers with longer employment length.

### Recommendations

Based on the analysis, we recommend the following actions:
- Stricter approval policies for borrowers with low income and high DTI.

- Consider offering alternative loan products for risky loan intents (e.g. personal or medical).

- Adjust interest rates to reflect risk more accurately across borrower segments.

- Encourage longer credit history and stable employment to reduce risk.

### Limitations

1. Dataset did not include credit score or detailed payment history.

2. No unique customer ID, so longitudinal tracking was not possible.

3. Manual steps required to clean and prepare data for import into SQL.

4. Default status was binary without timing, limiting survival or time-to-default analysis.







