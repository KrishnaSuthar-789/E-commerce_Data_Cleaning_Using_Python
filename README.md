# E-commerce_Data_Cleaning_Using_Python
E-commerce Data Cleaning &amp; Preparation Using Python

## Project Overview

This project focuses on cleaning and preparing raw e-commerce dataset using Python. 
The dataset contained several data quality issues such as duplicate records, missing values, inconsistent formats, invalid entries, and incorrect numerical values.

The goal was to improve data accuracy, consistency and reliability so the dataset could be used for further analysis and reporting.

## Tools & Technologies Used

- **Python**
- **Pandas** 
- **NumPy** 
- **Jupyter Notebook** 

## Data Cleaning Process

The project followed a structured data-cleaning workflow:

### 1. Data Inspection
- Explored the dataset structure and column information.
- Identified duplicate records and missing values.
- Examined inconsistent formats and suspicious entries.

### 2. Handling Missing & Duplicate Data
- Identified and handled duplicate records.
- Reviewed missing values across different columns.
- Replaced questionable or invalid values with missing values rather than making unsupported assumptions.

### 3. Standardizing Text Data
- Standardized inconsistent entries in customer gender, city, product category, and payment method.
- Applied string manipulation and conditional replacements to improve consistency.

### 4. Validating Numerical Data
- Checked customer ages, quantities, unit prices, PIN codes, and customer ratings for invalid or out-of-range values.
- Handled negative quantities and prices as invalid entries.
- Corrected inconsistent discount values.
- Adjusted customer ratings to follow the dataset's stated 0–10 rating scale.

### 5. Date & Calculation Corrections
- Converted inconsistent date values into appropriate datetime formats.
- Corrected transaction calculations by recalculating `total_amount` using unit price, quantity, and discount percentage.

### 6. Exporting Cleaned Data
- Converted relevant columns into appropriate data types.
- Exported the cleaned dataset to Excel for further analysis.

## Key Outcomes

- Improved consistency across customer, product, location, and payment-related fields.
- Identified and addressed invalid numerical values and inconsistent date formats.
- Corrected transaction amount calculations.
- Prepared a cleaner dataset suitable for downstream analysis and reporting.

## Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Inspection
- Missing Value Handling
- Duplicate Detection
- Data Standardization
- Data Validation
- Numerical and Date-Time Operations
- Pandas and NumPy

## License

This project is licensed under the [MIT License](LICENSE).
