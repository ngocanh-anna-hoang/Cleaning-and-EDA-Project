# Dubai Property Sales ETL & Exploratory Data Analysis

## Overview

This project develops an end-to-end ETL (Extract, Transform, Load) pipeline to clean and prepare a real-world Dubai property sales dataset for analysis. After transforming the raw data, exploratory data analysis (EDA) was conducted to uncover trends in property prices across different property subtypes and geographical areas.

The project demonstrates practical data engineering, data cleaning, and analytical skills using Python and pandas.

---

## Dataset

- **Source:** Dubai Property Sales Dataset (2023)
- **Records:** 81,601 property transactions
- **Features:** 22 variables including transaction details, property characteristics, location, and sale prices.

---

## Objectives

- Build an automated ETL pipeline.
- Assess and improve data quality.
- Clean and transform the dataset for analysis.
- Create derived variables for deeper business insights.
- Explore how property subtype and location influence sale prices.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ETL Pipeline

### Extract

- Imported raw CSV data into Python
- Assessed data quality
- Profiled missing values
- Identified duplicate records
- Reviewed data types
- Detected outliers and inconsistent categorical values

---

### Transform

The data cleaning process included:

- Converting transaction dates to datetime format
- Removing exact duplicate records
- Standardising categorical variables
- Cleaning inconsistent text formatting
- Handling missing values
- Removing highly incomplete columns
- Treating extreme outliers using IQR-based capping
- Creating a new **Price per Square Metre** feature

---

### Load

The cleaned dataset was exported as:

```
dubai_property_sales_cleaned.csv
```

ready for future analysis and dashboard development.

---

## Exploratory Data Analysis

The cleaned dataset was analysed to answer two business questions:

### 1. How does property subtype influence sale price?

The analysis compared:

- Transaction volume
- Median sale price
- Price distributions
- Property subtype performance

### 2. How does location influence property prices?

The analysis explored:

- Transaction concentration across Dubai
- Median property values by area
- Price per square metre
- High-value vs high-volume locations

---

## Key Insights

- Flats represented the largest share of transactions, but not the highest median sale price.
- Commercial and luxury residential properties generally achieved higher sale values.
- Premium locations commanded significantly higher price per square metre.
- Data cleaning substantially improved dataset quality while preserving meaningful market trends.

---

## Repository Structure

```
├── 2003Assignment2.ipynb
├── dubai_property_sales_cleaned.csv
├── README.md
└── figures/
```

---

## Skills Demonstrated

- Data Engineering
- ETL Pipeline Development
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Quality Assessment
- Data Visualisation
- Python Programming

---

## Future Improvements

- Develop an interactive Power BI or Tableau dashboard.
- Automate the ETL workflow using scheduled pipelines.
- Build predictive models for property price estimation.
- Integrate additional years of transaction data for trend analysis.

