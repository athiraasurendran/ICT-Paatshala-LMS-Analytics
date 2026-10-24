# Project Methodology

> This document summarises the workflow at a high level. It does not disclose source data, company-specific results, screenshots, or internal implementation details.

## 1. Scope and inputs

- **Domain:** Learning Management System (LMS) analytics
- **Input format:** Excel files
- **Period covered:** 2019–2025
- **Environment:** Python in Jupyter Notebook

## 2. Data preparation

Pandas and NumPy were used for data cleaning and manipulation. Data-quality checks should be described in detail only where they reflect work actually performed and can be safely disclosed.

Relevant areas for data-quality review include missing values, duplicate records, data types, date formats, category consistency, invalid values, and field availability. The exact treatment of each issue depends on the data and business rules.

## 3. Exploratory and descriptive analysis

The work included exploratory data analysis (EDA) and descriptive statistics, such as mean, median, and mode where appropriate. These techniques help describe distributions and provide context for comparisons.

## 4. Trend and relationship exploration

Matplotlib, Seaborn, and Plotly were used for visual exploration. Areas examined included:

- Monthly and yearly enrolment patterns.
- Monthly and yearly dropout patterns.
- Monthly and yearly course-completion patterns.
- Observed changes around the COVID-19 period.
- Relationships between selected indicators, including enrolment and completion.

A relationship or change over time does not, by itself, establish causation.

## 5. Programme comparisons

Programme-level enrolment, completion, and dropout indicators were compared to identify relatively higher and lower values for further review. Any rate comparison should use consistent definitions and appropriate denominators.

## 6. Dashboard presentation

A Flask-based dashboard brought selected KPIs and visual views together, including monthly/yearly trends, learner activity, assignment-submission information, learner engagement, and programme performance.

## Technology used

- Python and Jupyter Notebook
- Pandas and NumPy
- Matplotlib, Seaborn, and Plotly
- Flask

## Confidentiality boundary

No exact metric values, programme names, company-specific findings, raw data, screenshots, or internal implementation details are published in this case study.
