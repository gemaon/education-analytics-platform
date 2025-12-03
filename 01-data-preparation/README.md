# Data Preparation

## Overview
Python-based data cleaning and transformation workflow for educational performance data from 11 source CSV files.

## Files

**[education-data-preparation.ipynb](education-data-preparation.ipynb)**
Complete data cleaning workflow: quality assessment, transformation logic, and preparation for Power BI analysis.

**[data-quality-assessment.pdf](data-quality-assessment.pdf)**
Documentation of all data quality issues identified and transformation decisions applied.

**[data-dictionary.pdf](data-dictionary.pdf)**
Reference documentation for all 11 source data tables, including column definitions and data types.

**[sample-dataset-student-enrolments.csv](sample-dataset-student-enrolments.csv)**
Sample anonymised data demonstrating source file structure.

## Key Transformations

- Removed duplicates (25+ records across tables)
- Standardized formats (gender, year levels, class identifiers)
- Handled missing values (1,300+ fields)
- Treated outliers in assessment scores

## Technologies

Python | pandas | NumPy | Jupyter Notebook

---

→ [View Dashboard Documentation](../02-dashboards/)
