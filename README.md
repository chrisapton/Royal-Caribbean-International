# Royal Caribbean International

## Revenue Management Strategy and Analytics – Data Analyst Case Study

This repository contains a complete analysis, presentation, and supporting files for Royal Caribbean's case study focusing on passenger booking “Track” and WTD (Week-To-Date) expectations, as well as SQL-based analytics. The project demonstrates exploratory data analysis (EDA), business reasoning, data wrangling, and visualization. The results were presented to the managers at Royal Caribbean International.

---

## Repository Contents

* **LICENSE**
  Standard repository license file.
* **Christopher Apton - Royal Caribbean Group.pptx**
  The main presentation summarizing the analysis, results, reasoning, SQL code, and business recommendations.
* **testing.ipynb**
  Jupyter notebook used for data analysis, exploratory data analysis (EDA), calculation of WTD expectations, and summary statistics.
* **my\_wtd\_report.csv**
  Output CSV with calculated WTD expectations at sail\_year, sail\_month, and product levels, as requested.
* **Track\_case\_study\_data.xlsx**
  The Excel data file containing the raw and/or cleaned data used for analysis.
* **Track Analyst Case Study.docx**
  Document describing the case study, including instructions, business context, and possibly further discussion or answers in written format.

---

## Project Approach

### 1. WTD (Week-To-Date) Expectations

* **Data Preparation and EDA:**
  Loaded the provided data, cleaned it, and conducted exploratory data analysis (EDA) to understand booking patterns and identify any outliers or abnormalities.
* **Calculation:**
  Used historical booking data to derive daily WTD expectations at the granularity of sail\_year, sail\_month, and product.
* **Output:**
  Results are presented in a tabular format (`my_wtd_report.csv`) matching the requested structure.

### 2. Business Questions & Reasoning

* **Abnormalities:**
  All data anomalies and outliers were identified, documented, and handled with transparent logic, as explained in the presentation and notebook.
* **Implications of WTD Forecast Accuracy:**
  Analysis of the impacts of overestimating or underestimating WTD expectations, and their implications for pricing and revenue management, are included and discussed.
* **Product Comparison:**
  Investigated and explained booking patterns across different products and timeframes using summary statistics and visualizations.

### 3. SQL Analysis

* **SQL Queries:**
  Addressed a series of analytical questions on a star schema using SQL.
  Full code and logic are included in the appendix section of the PowerPoint presentation.

### 4. Presentation

* **Summary Presentation:**
  All steps, findings, visualizations, business reasoning, and code samples are compiled in `Christopher Apton - Royal Caribbean Group.pptx`.

---

## How To Use

1. **Open the Presentation:**
   Start with the PowerPoint file to view the business context, methodology, results, and SQL code.
2. **Explore Data & Code:**

   * Use the notebook (`testing.ipynb`) for code, EDA, and logic behind the analysis.
   * Reference `my_wtd_report.csv` for the resulting WTD expectations.
   * The Excel file contains the underlying data.
   * The Word document contains the original case and/or further explanation.

---

## Notes

* All work, code, and results are fully reproducible and documented.
* The analysis demonstrates both business acumen and technical skill using Python, Excel, and SQL.
* Data used is sample data from cruises and suitable for learning purposes.
