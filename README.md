# Online Retail Data Cleaning and Quality Audit

## Project Overview
This project focuses on cleaning and improving the quality of the UCI Online Retail dataset using Python. It includes data inspection, duplicate removal, missing value analysis, data type standardization, invalid record handling, and outlier detection.

## Objectives
- Identify missing values and duplicate records.
- Standardize data types for consistent analysis.
- Detect and handle invalid records.
- Identify numerical outliers using the IQR method.
- Compare data quality before and after cleaning.
- Document the cleaning process and results.

## Dataset
The UCI Online Retail dataset contains transaction records from an online retail business.

**Dataset Source:** [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)

## Tools and Technologies
- Python
- Pandas
- NumPy
- Google Colab

## Data Cleaning Process

### 1. Data Inspection
Examined the dataset structure, columns, data types, missing values, and duplicate records.

### 2. Duplicate Removal
Identified and removed duplicate rows to reduce redundant records.

### 3. Missing Value Analysis
Checked missing values in relevant columns and documented the treatment strategy.

### 4. Data Type Standardization
Reviewed and standardized data types where required for reliable analysis.

### 5. Invalid Record Handling
Checked transaction dates, quantities, and unit prices for invalid values and applied the defined cleaning rules.

### 6. Outlier Detection
Used the Interquartile Range (IQR) method to identify potential outliers in numerical columns. Identified outliers were assessed rather than automatically removed.

### 7. Before-and-After Comparison
Compared row counts, missing values, duplicate records, and statistical summaries to evaluate data quality changes.

## Project Files
- `Online_Retail_Data_Cleaning.ipynb` – Notebook containing data inspection, cleaning steps, and quality analysis.
- `Data_Cleaning_Results.zip` – Compressed archive containing the cleaning deliverables and output files.

## Key Learning Outcomes
- Data cleaning and preprocessing
- Missing value and duplicate analysis
- Data type standardization
- Outlier detection using IQR
- Data quality assessment
- Reproducible data preparation

## Conclusion
This project demonstrates the importance of data cleaning and quality assessment in preparing reliable datasets for further analysis.



