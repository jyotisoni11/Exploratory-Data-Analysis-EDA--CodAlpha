# 📊 Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project was completed as part of the **CodAlpha Data Analytics Internship**.

The objective of this project is to perform Exploratory Data Analysis (EDA) on an Online Retail dataset to understand business performance, investigate data quality issues, identify sales patterns, and extract meaningful insights from retail transaction data.

Using Python and its data analysis libraries, the project explores revenue trends, product performance, country-wise sales, customer activity, and transaction patterns.

The analysis helps demonstrate how raw business data can be transformed into useful information to support data-driven decision-making.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Understand the structure and characteristics of the retail dataset.
- Identify missing values and duplicate records.
- Detect invalid values and unusual transactions.
- Examine negative quantities and zero unit prices.
- Perform data cleaning and validation.
- Create new analytical features from existing columns.
- Analyze overall sales and revenue performance.
- Identify top-performing countries and products.
- Explore monthly and daily sales trends.
- Discover meaningful business insights.
- Provide recommendations based on the analysis.

---

## 🛠️ Tools and Technologies

The following tools and Python libraries were used:

| Tool / Library | Purpose |
|---|---|
| Python | Programming and data analysis |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis environment |

---

## 🔍 Project Workflow

### 1. Data Loading

- Imported the required Python libraries.
- Loaded the Online Retail Excel dataset using Pandas.
- Examined the first and last few records.
- Checked the dataset dimensions and column names.

### 2. Data Understanding

Performed initial inspection to understand the dataset.

Functions used:

- `head()`
- `tail()`
- `shape`
- `columns`
- `info()`
- `describe()`
- `dtypes`

### 3. Data Quality Assessment

Investigated the quality and reliability of the dataset.

The following checks were performed:

- Missing value analysis.
- Duplicate record detection.
- Data type verification.
- Negative quantity identification.
- Zero unit price identification.
- Cancellation transaction identification.
- Missing product description analysis.

### 4. Data Cleaning and Validation

Performed data quality checks and prepared the data for analysis.

Key activities included:

- Examining missing customer IDs.
- Investigating missing product descriptions.
- Checking duplicate records.
- Identifying negative quantities.
- Examining zero unit prices.
- Reviewing cancellation transactions.
- Validating data types and analytical columns.

**Note:** Negative quantities and cancellation records require business interpretation because they may represent returns or cancelled orders rather than ordinary sales.

### 5. Feature Engineering

Created additional analytical columns to support business analysis.

New features included:

- Revenue
- Year
- Month
- Month Name
- Day Name

Revenue was calculated using:

`Revenue = Quantity × UnitPrice`

These features helped analyze sales performance across different time periods.

### 6. Exploratory Data Analysis

Performed different types of analysis to identify useful patterns.

**Univariate Analysis**
- Distribution of numerical variables.
- Quantity distribution.
- Unit price distribution.
- Revenue distribution.

**Bivariate Analysis**
- Quantity and revenue relationship.
- Unit price and revenue relationship.
- Country-wise revenue analysis.
- Product-wise revenue analysis.

**Time-Based Analysis**
- Monthly revenue trends.
- Daily revenue patterns.
- Weekday versus weekend revenue.
- Highest and lowest revenue months.

**Business Performance Analysis**
- Total revenue.
- Total invoices.
- Total customers.
- Total quantity sold.
- Top revenue-generating countries.
- Top-performing products.

---

## ⚠️ Data Quality Findings

The analysis identified the following data quality issues:

| Data Quality Check | Result |
|---|---:|
| Missing Customer IDs | 135,037 |
| Missing Product Descriptions | 1,454 |
| Exact Duplicate Rows | 0 |
| Negative Quantity Records | 10,587 |
| Zero Unit Price Records | 2,510 |
| Cancellation Transaction Rows | 9,251 |
| Unique Cancelled Invoices | 3,836 |

**Important observations:**

- Missing Customer IDs can limit customer-level analysis.
- Negative quantities may represent returned products.
- Cancellation invoices require separate consideration.
- Zero unit prices should be investigated before revenue interpretation.
- Data quality issues can influence the accuracy of business conclusions.

---

## 💡 Business Recommendations

Based on the findings, the following recommendations can help improve business performance:

**1. Strengthen the UK Market**

The UK generates the largest share of recorded revenue. The business should focus on customer retention, product availability, and customer experience in this market.

**2. Explore International Markets**

Countries such as the Netherlands, Germany, and France show opportunities for further market development.

**3. Improve Inventory Planning**

High-demand products should be monitored to reduce stock shortages and support consistent product availability.

**4. Prepare for Seasonal Demand**

The business should analyze high-revenue periods and plan inventory and promotional campaigns accordingly.

**5. Monitor Returns and Cancellations**

Regular monitoring of negative quantities and cancelled invoices can help identify potential operational issues.

**6. Improve Data Quality**

The business should improve customer information collection and investigate missing or unusual transaction values.

---

## 📚 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning and Data Validation
- Data Manipulation using Pandas
- Numerical Analysis using NumPy
- Feature Engineering
- Missing Value Analysis
- Duplicate Detection
- Outlier and Anomaly Investigation
- Statistical Analysis
- Business Data Analysis
- Data Interpretation
- Analytical Problem-Solving

---

## 🏁 Conclusion

This project demonstrates the use of Python-based Exploratory Data Analysis to investigate real-world retail transaction data.

Through data inspection, quality assessment, feature engineering, and business analysis, meaningful insights were extracted regarding revenue performance, customer activity, product demand, country-wise sales, and transaction patterns.

The project strengthened practical skills in data analysis, data preparation, and business insight generation.

## Conclusion
This project helped identify data quality issues, understand retail sales patterns, and extract business insights using Python-based exploratory data analysis.
