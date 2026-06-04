# 🚀 SpaceX SQL Data Analysis

## Overview

This project demonstrates exploratory data analysis (EDA) using SQL on historical SpaceX Falcon 9 launch data.

The analysis was performed using SQLite and Jupyter Notebook as part of the IBM Data Science Professional Certificate program. The objective was to answer business and operational questions through SQL queries and data exploration techniques.

---

## Objectives

* Load and store SpaceX launch data in SQLite
* Perform exploratory data analysis using SQL
* Analyze launch sites and mission outcomes
* Investigate payload mass distributions
* Explore booster performance
* Extract operational insights from historical launch records

---

## Dataset

The dataset contains Falcon 9 launch information, including:

* Launch Date
* Launch Site
* Booster Version
* Payload Mass
* Customer
* Orbit Type
* Landing Outcome
* Mission Outcome

---

## SQL Analysis Tasks

The project includes analytical SQL queries such as:

* Distinct launch site identification
* Launch site filtering
* Payload mass aggregation
* Average payload calculations
* Successful landing analysis
* Booster performance evaluation
* Mission outcome statistics
* Maximum payload identification
* Monthly launch trend analysis

---

## Technologies

* SQL
* SQLite
* Python
* Pandas
* Jupyter Notebook

---

## Project Structure

```text
spacex-sql-data-analysis/
│
├── README.md
├── requirements.txt
├── notebooks/
│   └── spacex_sql_analysis.ipynb
│
└── src/
    └── sql_queries.sql
```

---

## Sample SQL Query

```sql
SELECT DISTINCT Launch_Site
FROM SPACEXTABLE;
```

---

## Key Learning Outcomes

* SQL data exploration
* Aggregate functions
* Filtering and sorting
* Grouping and summarization
* Subqueries
* Business-oriented data analysis
* Database querying techniques

---

## Results

The project successfully analyzed SpaceX launch records and produced insights related to:

* Launch site activity
* Payload performance
* Booster effectiveness
* Landing success rates
* Mission outcomes

---

## Author

Aliona Vataman

IBM Data Science Professional Certificate

Software Engineering 
