# Week 6 – Spark Architecture and Efficient Data Processing

## Overview

This assignment focuses on understanding the architecture of Apache Spark and performing efficient data processing using PySpark DataFrames. It covers Spark's execution model, DataFrame transformations, filtering, schema handling, optimized file formats, and performance optimization concepts.

---

## Objective

- Understand Spark Architecture (Driver, Cluster Manager, Executors).
- Learn Spark execution modes (Client Mode and Cluster Mode).
- Understand Lazy Evaluation and Directed Acyclic Graph (DAG).
- Read CSV files with schema inference.
- Perform DataFrame transformations and filtering.
- Rename columns and cast data types.
- Add new calculated columns.
- Understand Transformations and Actions.
- Compare CSV and Parquet file formats.
- Learn Predicate Pushdown optimization.
- Handle null values efficiently.
- Understand Spark best practices for large datasets.

---

## Technologies Used

- Python 3.x
- Apache Spark (PySpark)
- Jupyter Notebook

---

## Dataset

- Sample - Superstore.csv

---

## Assignment Contents

### Practical Implementation

- Created a Spark Session.
- Loaded a CSV dataset.
- Displayed DataFrame schema.
- Previewed sample records.
- Selected required columns.
- Applied filtering conditions.
- Renamed DataFrame columns.
- Demonstrated data type casting.
- Added calculated columns.
- Handled null values.
- Demonstrated writing data into CSV and Parquet formats.
- Read Parquet files.

### Theory Questions

The notebook includes solutions for:

- Spark Architecture
- Driver, Cluster Manager and Executor
- Lazy Evaluation
- DAG (Lineage Graph)
- CSV vs Parquet
- Predicate Pushdown
- Transformations vs Actions
- Client Mode vs Cluster Mode
- DataFrame Operations
- Spark Performance Best Practices

---

## Learning Outcomes

After completing this assignment, I learned:

- Apache Spark Architecture.
- Spark execution flow using Driver and Executors.
- Lazy Evaluation and DAG optimization.
- Reading and processing CSV files using PySpark.
- Applying DataFrame transformations and actions.
- Filtering and selecting records efficiently.
- Renaming and modifying DataFrame columns.
- Working with optimized storage formats such as Parquet.
- Predicate Pushdown optimization.
- Best practices for handling large-scale datasets.

---

## Repository Structure

```
Week6/
│── week_6_assignment.ipynb
│── Sample - Superstore.csv
│── README.md
```

---

## Note

The notebook follows the assignment requirements provided for Week 6. Some file writing operations (CSV/Parquet) may depend on the local Hadoop configuration (`winutils.exe` and Hadoop native libraries) when executed on Windows. The Spark code itself follows the correct PySpark syntax and is suitable for execution in a properly configured Spark environment.
