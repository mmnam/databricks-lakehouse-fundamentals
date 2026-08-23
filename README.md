# Databricks Lakehouse Fundamentals

A small portfolio project showing my hands-on practice with **Databricks, PySpark, Spark SQL, and Delta Lake**.

These are polished versions of hands-on learning labs.

## What this project demonstrates

- Creating and querying Spark DataFrames
- Building derived columns with PySpark expressions
- Filtering, grouping, and aggregating data
- Joining transactional and reference datasets
- Using window functions for ranking
- Switching between PySpark and Spark SQL
- Creating and appending to Delta tables
- Updating records with SQL
- Implementing upserts with `MERGE`
- Inspecting Delta transaction history
- Querying previous table versions with time travel

## Notebooks

### 01 - Lakehouse Foundations
Introduces the Databricks environment, compares common data architectures, creates a Delta table, inspects transaction history, and explores catalogs and schemas.

### 02 - PySpark Transformations and Analytics
Uses a retail sales dataset to practice column expressions, filters, aggregations, joins, window functions, and SQL equivalents.

### 03 - Delta Lake Operations
Builds an inventory table and demonstrates append, update, `MERGE`, transaction history, time travel, and schema enforcement.

## Why I built this

I created this project while strengthening my data engineering and analytics foundation in Databricks. My goal was to move beyond isolated exercises and present the work as a clear progression of practical lakehouse skills.

## Next steps

- Add data-quality checks before writes
- Build a Bronze / Silver / Gold medallion pipeline
- Add a Databricks Workflow to orchestrate notebook execution
- Add automated tests for transformation logic
- Build a small dashboard from the curated sales data
