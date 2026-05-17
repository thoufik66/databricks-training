# 📅 Week 2 — Day 2: Advanced College Management System (CMS)

> **Focus:** Deep diving into advanced window functions, running totals, statistical distributions, partition frames, and producing comprehensive multi-metric analytical reports on the CMS database.

---

## 📝 Overview

Day 2 of Week 2 continued with the College Management System dataset, moving into advanced SQL — window functions applied to student and staff data, subqueries for department-level comparisons, and a final combined report query.

---

## 📚 Topics Covered

- **Conditional Aggregation** — Using `GROUP BY` with `HAVING` and embedding `CASE WHEN` inside aggregate functions
- **Robust Left Joins** — Handling empty departments safely in analytical reports
- **Academic and Financial Ranking** — Utilizing `ROW_NUMBER()`, `RANK()`, and `DENSE_RANK()` on student CGPA and staff salaries
- **Running Totals** — Implementing cumulative sums of student marks using `SUM() OVER()`
- **Partitioned Averages** — Calculating class-wise averages using `AVG() OVER(PARTITION BY)`
- **Temporal Analysis** — Using `LAG()` and `LEAD()` to compare previous and current semester marks
- **Extreme Value Identifiers** — Spotting top subject marks using `MAX() OVER(PARTITION BY)`
- **Cumulative Window Frames** — Computing rolling averages via `ROWS BETWEEN UNBOUNDED PRECEDING AND CURRENT ROW`
- **First/Last Value Identification** — Finding the first admitted student and latest hired staff per department using `ROW_NUMBER()`
- **Quartile & Distribution Metrics:**
  - `NTILE(4)` — Segmenting students into CGPA quartiles
  - `PERCENT_RANK()` — Computing relative percentage ranks
  - `CUME_DIST()` — Calculating cumulative staff salary distributions
- **Advanced Correlated Subqueries** — Handling department average comparative operations
- **Comprehensive Master Report** — Synthesizing multiple window functions into a single cohesive analytical query

---

## 📂 Files in This Folder

| File | Description |
|------|-------------|
| [practice_queries.txt](practice_queries.txt) | Advanced practice questions on the CMS dataset |
| [solution_queries.sql](solution_queries.sql) | Analytical SQL solutions for CMS questions |
| [README.md](README.md) | Summary of Day 2 CMS learnings |