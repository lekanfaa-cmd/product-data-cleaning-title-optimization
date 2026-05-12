# Product Data Cleaning & Title Optimization

## Project Overview

This project focuses on cleaning, preparing, and optimizing a raw product dataset for improved usability, consistency, and marketing effectiveness.

Using Excel, the dataset was transformed through a structured data cleaning workflow involving missing value handling, duplicate removal, format standardization, and feature engineering. A new `short_title` feature was also created to improve readability, search optimization, and product presentation.

The project demonstrates practical data preparation techniques commonly used in marketing analytics, e-commerce operations, and business intelligence workflows.

---

# Business Objective

The primary objective of this project was to prepare raw product data for analysis by improving data quality and creating concise, SEO-friendly product titles.

The task focused on:

- Identifying and resolving data quality issues
- Standardizing inconsistent formats
- Removing duplicate entries
- Improving dataset usability
- Creating optimized short product titles for readability and SEO purposes

---

# Dataset Overview

The dataset contains product-level information including:

- Product Titles
- Descriptions
- Bullet Points
- Pricing Information
- Ratings and Product Attributes

Initial exploration revealed several data quality issues including inconsistent formatting, redundant product titles, duplicate records, and missing values.

---

# Data Cleaning Process

The data cleaning process was carried out entirely in Excel.

## Initial Data Exploration

A high-level review of the dataset was conducted to identify structural inconsistencies and data quality issues.

The following checks were performed:

- Review of column naming consistency
- Identification of missing values
- Duplicate detection
- Text formatting inconsistencies
- Validation of critical fields

---

## Handling Missing Values

Missing values were evaluated based on their importance to the dataset.

### Actions Taken
- Rows with missing critical fields such as product titles were removed or excluded
- Non-critical missing values were retained where appropriate to avoid unnecessary data loss

---

## Removing Duplicate Records

Duplicate entries were identified and removed using Excel’s **Remove Duplicates** functionality.

This ensured:
- Improved data accuracy
- Elimination of redundant records
- Better analytical reliability

---

## Standardizing Data Formats

To improve consistency and readability:

- Column names were standardized using lowercase and underscore formatting
- Extra spaces and formatting inconsistencies were removed
- Text fields were cleaned using trimming techniques
- Categorical values were standardized

Examples:
- `SalesAmount` → `sales_amount`
- `Product Title` → `product_title`

---

## Data Accuracy Validation

Critical variables were reviewed for anomalies and unrealistic values.

Validation checks included:
- Negative pricing values
- Invalid ratings
- Inconsistent formatting patterns

This improved the reliability and usability of the final dataset.

---

# Short Title Optimization

## Objective

The objective of the `short_title` feature was to create concise and SEO-friendly product titles while preserving essential product information.

The optimized titles improve:
- Readability
- Search visibility
- Product presentation
- User experience

---

## Optimization Methodology

The following logic was applied during title optimization:

- Identification of key product attributes
- Removal of redundant phrases such as:
  - “includes”
  - “set of”
  - “features”
- Elimination of unnecessary symbols and separators
- Retention of core product identity
- Reduction of title length to approximately 30–50 characters

---

# Examples of Title Optimization

| Original Title | Optimized Short Title |
|---|---|
| Tulip Flowers Blackout Curtain for Door, Window & Room | Tulip Blackout Curtain - 2 PCS |
| [3 Pack] iPhone SE 5S 5 5C Glass Screen Protector | 3 Pack iPhone Glass Screen Protector |
| BOZABOZA 15" Screen Privacy Filter | BOZABOZA MacBook Privacy Screen Filter |

---

# Project Outcomes

Following the cleaning and optimization process, the dataset achieved:

- Improved structural consistency
- Removal of duplicate entries
- Standardized naming conventions
- Cleaner text formatting
- Enhanced dataset usability
- Addition of a value-enhancing feature (`short_title`)

These improvements make the dataset more suitable for reporting, analytics, and marketing applications.

---

# Tools Used

| Tool | Purpose |
|---|---|
| Excel | Data Cleaning & Preparation |
| GitHub | Documentation & Portfolio Hosting |

---

# Repository Structure

```plaintext
product-data-cleaning-title-optimization/

│── README.md
│
├── dataset/
│     └── cleaned_product_dataset.xlsx
│
├── report/
│     └── data_cleaning_title_optimization_report.pdf
│
│
└── original_dataset/
      └── raw_product_dataset.xlsx
```

---

# Key Skills Demonstrated

- Data Cleaning
- Data Preparation
- Data Quality Assessment
- Excel Data Processing
- Feature Engineering
- Documentation & Reporting
- SEO-Oriented Data Optimization

---

# Conclusion

This project demonstrates the importance of data preparation in ensuring reliable analysis and effective business communication.

The implementation of the `short_title` feature highlights practical feature engineering techniques used in real-world e-commerce and marketing workflows to improve readability, usability, and search optimization.

---

# Author

Lekan Ajayi  
Data Analyst | Business Intelligence Enthusiast
