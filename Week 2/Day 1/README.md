# 📅 Week 2 — Day 1: College Management System (CMS) Foundations

> **Focus:** Transitioning to a College Management System schema to practice intermediate-to-advanced JOINS, aggregations, subqueries, and multi-conditional filtering on relational databases.

---

## 📝 Overview

Day 1 of Week 2 focused on practising SQL on a new schema — a College Management System (CMS). The dataset has 5 tables: `Department`, `Staff`, `Student`, `Subject`, and `Mark`. Practiced joins, aggregations, subqueries, and filtering on real-world style college data.

---

## 📚 Topics Covered

- **Outer Joins** — Using `LEFT JOIN` to locate unmatched records (e.g., identifying staff without department assignments or students without exam marks)
- **Multi-Table Joins** — Performing `INNER JOIN` operations spanning 3+ tables simultaneously
- **Unmatched Data Auditing** — Writing queries using `IS NULL` to find anomalies and missing records
- `GROUP BY` **& Aggregate Functions** — Computing metrics using `AVG()`, `COUNT()`, `SUM()`, `MAX()`, and `MIN()`
- `HAVING` **Clause Filtering** — Restricting grouped and aggregated result sets
- **Scalar Subqueries** — Comparing individual metrics to system averages
- **Correlated Subqueries** — Performing row-by-row comparisons across groups (e.g., student grades vs. class averages)
- **Complex Sorting** — Organizing outputs by academic ranks and CGPA metrics
- **Logical AND/OR Filtering** — Evaluating complex multi-conditioned WHERE criteria

---

## 📂 Files in This Folder

| File | Description |
|------|-------------|
| [practice_queries.txt](practice_queries.txt) | Practice questions on the CMS dataset |
| [solution_queries.sql](solution_queries.sql) | SQL queries solving the College Management System questions |
| [README.md](README.md) | Summary of Day 1 CMS learnings |