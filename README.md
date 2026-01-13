# 🧹 Employee Data Cleaning and Validation in Excel

## 📌 Overview
This Excel file contains an **employee master dataset** used to practice **data cleaning and validation techniques** in Microsoft Excel.  
The dataset includes employee personal and organizational details and intentionally contains inconsistencies and missing values to simulate real-world data quality issues.

The main goal of this task is to **review, clean, and validate the data** so it can be reliably used for reporting and analysis.

---

## 🎯 Task Objective
To analyze the employee dataset and identify common data quality problems such as:
- Missing values
- Invalid or incorrect entries
- Duplicate records
- Inconsistent formatting

---

## 🗂️ Dataset Description
The dataset consists of the following columns:

| Column Name | Description |
|------------|------------|
| ID | Unique employee identifier |
| Name | Employee full name |
| Age | Employee age |
| Email | Employee email address |
| Salary | Annual salary |
| Date of Joining | Employee joining date |
| Department | Assigned department |
| Manager | Reporting manager |

---

## 🔍 Data Issues Addressed
During analysis, the following issues were observed:

- Missing values in **Age**, **Email**, **Manager**, and **Date of Joining**
- Salary values recorded as **0**, indicating invalid or incomplete data
- Duplicate employee names and repeated records
- Incorrect or inconsistent email formats (typos in domain names)
- Blank or incomplete managerial assignments

These issues are typical in raw business datasets and require systematic cleaning.

---

## 🛠️ Excel Terms & Features Used

The following Excel tools and concepts are used or recommended to complete this task:

### 1. **Data Validation**
Used to restrict invalid inputs such as zero or negative salary values.

---

### 2. **IF Function**
Helps identify invalid or missing data.

**Example:**
```excel
=IF(Salary=0,"Invalid","Valid")
