# Project 1: Data Cleaning & Preparation

## Overview

This project was completed as part of the DecodeLabs Data Analytics Internship Program.

The objective of this project was to clean and prepare a raw dataset by identifying missing values, checking for duplicate records, validating data formats, and ensuring data integrity before further analysis.

---

## Project Objective

The primary goals of this project were:

* Identify missing or null values
* Handle missing data appropriately
* Check for duplicate records
* Verify that there are no duplicate IDs
* Validate date formats
* Ensure numeric fields are correctly formatted
* Prepare a clean dataset for future analysis

---

## Dataset Information

| Description      | Value                       |
| ---------------- | --------------------------- |
| Total Records    | 1200                        |
| Dataset Type     | E-commerce Transactions     |
| Project Category | Data Cleaning & Preparation |
| Tools Used       | Python, Pandas, Excel       |

---

## Data Cleaning Process

### 1. Missing Value Analysis

The dataset was examined for missing or null values.

#### Findings

* Missing values were found in the **CouponCode** column.

#### Action Taken

* Missing CouponCode values were replaced with **"No Coupon"**.

---

### 2. Duplicate Record Check

The dataset was checked for duplicate rows.

#### Result

* Duplicate Rows Found: **0**

No duplicate records were present in the dataset.

---

### 3. Duplicate ID Validation

The OrderID column was verified to ensure every order had a unique identifier.

#### Result

* Duplicate Order IDs Found: **0**

The dataset satisfies the requirement of having zero duplicate IDs.

---

### 4. Data Format Validation

The following columns were validated:

* Order Date
* Quantity
* Unit Price
* Items In Cart
* Total Price

#### Result

* Incorrect Date Formats Found: **0**
* Numeric fields were correctly formatted.

---

## Final Results

| Validation Check           | Status |
| -------------------------- | ------ |
| Missing Values Identified  | ✅      |
| Missing Values Handled     | ✅      |
| Duplicate Records Checked  | ✅      |
| Duplicate IDs Verified     | ✅      |
| Date Formats Validated     | ✅      |
| Dataset Ready for Analysis | ✅      |

---

## Files Included

```text
Project-1-Data-Cleaning/
│
├── data/
│   ├── raw_dataset.xlsx
│   └── cleaned_dataset.xlsx
│
├── reports/
│   └── Project1_Report.docx
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── screenshots/
│
└── README.md
```

---

## Skills Demonstrated

* Data Cleaning
* Data Validation
* Data Preparation
* Data Quality Assessment
* Python Programming
* Pandas Library
* Excel Data Processing
* GitHub Documentation

---

## Conclusion

The dataset was successfully cleaned and prepared for further analysis. Missing values were handled appropriately, duplicate records were verified, date formats were validated, and overall data quality was improved to ensure reliable analytical results.

---

## Author

Muhammad Hamza Ali

Data Analytics Intern

DecodeLabs
