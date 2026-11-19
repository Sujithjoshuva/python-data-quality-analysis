# Python Data Quality Analysis

## Project Overview

This project focuses on identifying and investigating data quality issues in a sales dataset using Python.

The dataset was created with intentional data quality issues to practice data inspection, data cleaning, validation, and outlier detection.

## Business Problem

Sales datasets may contain missing values, duplicate records, inconsistent text, invalid numeric values, incorrect data types, and inaccurate sales calculations.

These data-quality issues can affect the accuracy and reliability of business analysis and reporting.

The objective of this project is to use Python, Pandas, NumPy, and Matplotlib to identify, investigate, and visualize data-quality issues in a synthetic sales dataset before further analysis.

## Recommendations

Based on the data-quality checks performed, the following actions are recommended:

- **Handle Missing Values:** Investigate missing values and determine appropriate treatment instead of automatically replacing them.
- **Remove Duplicates:** Identify and remove confirmed duplicate records.
- **Standardize Text:** Apply consistent naming conventions to product, category, region, and payment method values.
- **Validate Numeric Data:** Investigate zero and negative prices and quantities before using them in analysis.
- **Verify Sales Calculations:** Check sales values against the expected Price × Quantity calculation and investigate mismatches.
- **Review Potential Outliers:** Investigate unusually high or low values before deciding whether they are valid or require correction.
- **Maintain Data Quality Checks:** Apply validation rules regularly to improve data reliability.

**Expected Benefit:** Better data consistency, more reliable analysis, and improved confidence in business reporting.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Dataset Information

The dataset contains 1,000 records and 9 columns.

**Columns:**
- Order_ID
- Order_Date
- Product
- Category
- Price
- Quantity
- Region
- Payment_Method
- Sales

## Project Objectives

- Inspect the dataset and understand its structure.
- Identify missing values and duplicate records.
- Detect inconsistent text values.
- Identify invalid numeric values.
- Handle incorrect data types.
- Validate Sales calculations.
- Detect potential outliers using the IQR method.
- Visualize the distribution of product prices using boxplots.

## Project Workflow

1. Data generation and inspection
2. Data quality assessment
3. Duplicate detection and removal
4. Text standardization
5. Data type conversion
6. Missing value investigation
7. Numeric data validation
8. Sales calculation validation
9. Outlier detection using IQR
10. Data visualization using Matplotlib

## Key Data Quality Checks

- Missing values
- Duplicate records
- Inconsistent product, category, and region names
- Zero and negative prices
- Zero and negative quantities
- Invalid dates
- Incorrect Sales calculations
- Potential extreme values

## Visualizations

A boxplot was created using Matplotlib to examine the distribution of product prices and identify potential outliers.

## Repository Structure

```text
python-data-quality-analysis/
│
├── notebooks/
│   ├── python_data_quality_analysis_github.ipynb
│   └── README.md
│
├── visualizations/
│   └── README.md
│
├── reports/
│   └── README.md
│
├── README.md
└── .gitignore
```

## Learning Outcomes

Through this project, I practiced:

- Data inspection using Pandas
- Data cleaning and standardization
- Handling missing and duplicate records
- Numeric and date validation
- Sales calculation checks
- Outlier detection using the IQR method
- Data visualization using Matplotlib

## Project Status

Completed the initial data quality analysis and boxplot visualization. Further improvements and analysis may be added.

## Overall Insights

The analysis demonstrated how data-quality issues can affect the reliability of sales data.

Key observations:

- Identified missing values and duplicate records.
- Detected inconsistent text values and incorrect data types.
- Flagged zero and negative prices and quantities for investigation.
- Validated sales calculations using Price × Quantity.
- Used the IQR method to identify a potential price outlier.
- Created boxplots using Matplotlib to visualize price distribution.

**Conclusion:** Data cleaning, validation, and outlier detection are important steps before performing reliable business analysis. This project provided practical experience in identifying and investigating data-quality issues using Python.
