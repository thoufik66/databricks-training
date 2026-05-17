# 📅 Week 1 — Day 5: Window Functions & CTEs

> **Focus:** Advanced window function applications and introducing Common Table Expressions (CTEs) for writing modular, readable, and recursive SQL queries.

---

## 📝 Overview

Day 5 continued window functions and introduced CTEs (Common Table Expressions). Practiced on [db-fiddle.com](https://www.db-fiddle.com/) using a retail sales dataset.

---

## 📚 Topics Covered

- `AVG() OVER(PARTITION BY)` — Computing and displaying department average salaries alongside each individual record
- **Window Function Filtering** — Chaining window function results inside a subquery for advanced row-filtering
- `SUM() OVER(PARTITION BY)` — Calculating aggregate department payrolls
- **Percentage Contributions** — Calculating the percentage contribution of an individual's salary within their department
- `COUNT() OVER()` — Appending total overall row count alongside each individual row
- **CTEs (WITH clause)** — Defining reusable, named temporary result sets to simplify complex nested queries
- **Multiple CTEs** — Writing and chaining multiple CTEs within a single SQL query
- **Recursive CTEs** — Generating sequential numbers and sequences dynamically
- **Hierarchical Traversal** — Using recursive CTEs to traverse employee-manager organizational hierarchies
- **Combining CTEs and Window Functions** — Leveraging both to create highly optimized and readable queries

---

## 📂 Files in This Folder

| File | Description |
|------|-------------|
| [practice_queries.txt](practice_queries.txt) | Practice questions on advanced window functions and CTEs |
| [solution_queries.sql](solution_queries.sql) | SQL solutions for CTE and window function exercises |
| [README.md](README.md) | Summary of Day 5 learnings |
