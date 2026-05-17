# 📅 Week 1 — Day 4: Window Functions

> **Focus:** Understanding SQL Window Functions for partition-based calculations, ranking, and running totals.

---

## 📝 Overview

Day 4 focused on SQL window functions. Practiced on [db-fiddle.com](https://www.db-fiddle.com/) using a retail sales dataset with employees, customers, and orders.

---

## 📚 Topics Covered

- `ROW_NUMBER()` — Assigns a unique, sequential row number to each row starting at 1
- `RANK()` — Ranks rows within a partition, skipping rank numbers when ties occur
- `DENSE_RANK()` — Ranks rows within a partition without skipping numbers on ties
- `PARTITION BY` — Divides the result set into partitions to apply the window function independently
- **Running Totals** using `SUM() OVER()` across ordered partitions
- **Cumulative Sales** per employee analysis
- `LAG()` — Accesses data from a previous row in the same result set without a self-join
- `LEAD()` — Accesses data from a subsequent row in the same result set
- **Moving Averages** calculation using `ROWS BETWEEN` frames
- `NTILE(N)` — Divides ordered rows in a partition into `N` roughly equal buckets/percentiles

---

## 📂 Files in This Folder

| File | Description |
|------|-------------|
| [practice_queries.txt](practice_queries.txt) | Practice questions on window functions |
| [solution_queries.sql](solution_queries.sql) | SQL solutions utilizing window functions |
| [README.md](README.md) | Summary of Day 4 learnings |
