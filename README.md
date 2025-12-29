# 🦠 COVID-19 SQL Data Analysis

![COVID-19](https://www.datamanagementblog.com/wp-content/uploads/2020/05/An-open-data-portal-for-the-analysis-of-COVID-19-data.png)

## 📌 Project Overview

This project presents a structured SQL-based analysis of the COVID-19 dataset, focusing on cases, deaths, and population statistics across multiple countries over time.

The analysis is performed using MySQL, and the queries are categorized to demonstrate both SQL fundamentals and analytical thinking, making this project suitable for learning, practice, and portfolio presentation.

## 📊 Dataset Description

- ** The dataset tracks COVID-19 statistics at a country-level, including daily reported cases and deaths along with population details.
- ** Time period: December 2019 – April 2020
- ** Granularity: Daily records per country
- ** Date format: Stored as TEXT (yyyy-mm-dd)

  ## 🗂️ Dataset Structure

| Column Name   | Data Type | Description |
|--------------|----------|-------------|
| date         | TEXT     | Date of record (`yyyy-mm-dd`) |
| day          | INT      | Day of the month |
| month        | INT      | Month number |
| year         | INT      | Year |
| cases        | INT      | Daily confirmed COVID-19 cases |
| deaths       | INT      | Daily reported deaths |
| countries    | TEXT     | Country name |
| geoId        | TEXT     | Geographical identifier |
| countrycodes | TEXT     | ISO country code |
| population   | INT      | Total population |

## 🧠 SQL Query Categories
### 1️⃣ Arithmetic Operations

Queries performing mathematical calculations on numeric columns to derive metrics such as totals, ratios, and comparisons.

### 2️⃣ Logical Operators

Filtering data using:
- ** AND
- ** OR
- ** NOT

### 3️⃣ Special Operators

Queries demonstrating:
- ** IN / NOT IN
- ** BETWEEN / NOT BETWEEN
- ** LIKE / NOT LIKE
- **IS NULL / IS NOT NULL
- ** EXISTS
- ** ANY / ALL
- ** DISTINCT
- ** Column aliasing using AS

### 4️⃣ Aggregate Functions

Analysis using:
- ** COUNT()
- ** SUM()
- ** AVG()
- ** MIN()
- ** MAX()

### 5️⃣ Sorting (ORDER BY)

Sorting results using:
- ** Ascending (ASC)
- ** Descending (DESC)
- ** Multi-column ordering

### 6️⃣ Conditional Logic (CASE)

Classification and grouping of data using:
**`CASE WHEN ... THEN ... ELSE ... END`**.

### 7️⃣ Date Extraction

Working with date components using:
- ** YEAR()
 ** MONTH()
- ** MONTHNAME()
- ** DAY()
- ** DAYNAME()

##🚀 Skills Demonstrated

- ** SQL querying & data manipulation
- ** Data aggregation & filtering
- ** Time-based analysis
- ** Analytical thinking using real-world data
