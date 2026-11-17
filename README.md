# Python Data Quality Analysis

## Project Overview

This project focuses on identifying and investigating data quality issues in a sales dataset using Python.

The dataset was created with intentional data quality issues to practice data inspection, data cleaning, validation, and outlier detection.

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
