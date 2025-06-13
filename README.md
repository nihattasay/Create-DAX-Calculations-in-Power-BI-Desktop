# Create DAX Calculations in Power BI Desktop
# Power BI DAX Calculations Lab

## Overview

This lab is part of the **PL-300 Microsoft Power BI Data Analyst** learning path. The objective is to practice creating calculated tables, columns, and measures using **Data Analysis Expressions (DAX)** in Power BI Desktop.

The lab focuses on building a more robust data model by adding business logic directly in Power BI, allowing for better data analysis and reporting.

---

## Key Tasks

### 1️⃣ Calculated Tables
- Create a `Salesperson` calculated table based on the existing `Salesperson (Performance)` table.
- Define relationships between `Salesperson`, `Sales`, and other tables.

### 2️⃣ Date Table
- Build a full Date table using `CALENDARAUTO(6)`.
- Add fiscal year, quarter, month, and sorting columns.

### 3️⃣ Hierarchies
- Create a Fiscal hierarchy with `Year > Quarter > Month` for easier drill-down in reports.

### 4️⃣ Relationships
- Establish relationships between the Date table and both `Sales` and `Targets` tables.

### 5️⃣ Measures
- Create simple aggregation measures:  
  `Avg Price`, `Median Price`, `Min Price`, `Max Price`, `Orders`, `Order Lines`.
- Apply proper formatting and organize measures into display folders.

### 6️⃣ Advanced Measures
- Build additional business logic measures such as:
  - `Target`
  - `Variance`
  - `Variance Margin`
- Use conditional logic with DAX functions like `HASONEVALUE()`, `DIVIDE()`, and `IF()`.

### 7️⃣ Formatting & Hiding
- Apply formatting to measures.
- Hide columns not needed for report authors to simplify report creation.

---

## Purpose

By completing this lab, users gain hands-on experience with:

- **Data modeling best practices** in Power BI.
- Writing **DAX expressions** for business calculations.
- Creating reusable and well-organized **semantic models**.
- Improving report usability by controlling field visibility, formatting, and structure.

---

## Approximate Duration

⏱ ~45 minutes

---

## Requirements

- Power BI Desktop
- Download lab files from:

https://github.com/MicrosoftLearning/PL-300-Microsoft-Power-BI-Data-Analyst/raw/Main/Allfiles/Labs/04-create-dax-calculations-in-power-bi-desktop/04-intro-dax.zip

