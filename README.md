# CodeNova Internship — Task 2: Data Cleaning

## Project Overview
This project focuses on data quality assessment and cleaning using Python and Pandas. The UCI Online Retail dataset is used to identify missing values, duplicate records, invalid data, and statistical outliers.

## Objectives
- Identify missing values and duplicate records.
- Standardize data types and text columns.
- Remove invalid records using documented rules.
- Detect outliers using the Interquartile Range (IQR) method.
- Compare data quality before and after cleaning.

## Tools Used
- Python
- Pandas
- NumPy
- Google Colab

## Dataset
UCI Online Retail Dataset: https://archive.ics.uci.edu/dataset/352/online+retail

## Cleaning Process
1. Inspect missing values, data types, and duplicates.
2. Remove exact duplicate rows.
3. Standardize date, numeric, and text columns.
4. Remove records with invalid dates, non-positive quantities, or non-positive unit prices.
5. Detect outliers using IQR without automatically removing potentially valid transactions.
6. Save the cleaned dataset and data quality reports.

## Deliverables
- `Task2_Data_Cleaning_Report.ipynb` — cleaning workflow and analysis.
- `Task2_Data_Cleaning_Deliverables.zip` — cleaned dataset, comparison metrics, missing-value report, IQR outlier report, and audit report.

## Note
The original dataset is preserved separately. Cleaning decisions and limitations are documented in the audit report.
