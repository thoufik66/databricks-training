Week 2 — Day 2 — College Management System (Advanced)
Overview

Day 2 of Week 2 continued working with the College Management System (CMS) dataset, focusing on advanced SQL concepts. The practice included window functions, correlated subqueries, department-level analysis, ranking operations, and combined analytical report queries using student and staff data. All queries were practiced on db-fiddle.com.

Schema Used

The College Management System dataset included the following tables:

Department
Staff
Student
Subject
Mark

The dataset was used for advanced analytical SQL queries and reporting operations.

Topics Covered
1. GROUP BY with HAVING and CASE

Practiced grouping records with conditional aggregation.

Concepts Learned
GROUP BY
HAVING
CASE inside aggregate functions
Key Learning

CASE inside aggregates helps perform conditional calculations such as counting passed or failed students.

2. LEFT JOIN for Empty Departments

Learned how to identify departments without matching records.

Examples Practiced
Departments without students
Departments without staff
Key Learning

LEFT JOIN combined with IS NULL helps detect missing relationships.

3. Ranking Functions

Practiced ranking students and staff using window functions.

Functions Used
ROW_NUMBER()
RANK()
DENSE_RANK()
Applications
Ranking students by CGPA
Ranking staff by salary
Key Learning

Different ranking functions handle duplicate values differently.

4. Running Totals using SUM() OVER()

Learned how to calculate cumulative totals across rows.

Examples Practiced
Running total of student marks
Progressive score calculations
Key Learning

Window functions allow cumulative calculations without collapsing rows.

5. Subject-wise Average using AVG() OVER(PARTITION BY)

Practiced calculating averages within groups.

Key Learning

PARTITION BY divides rows into groups while preserving individual rows.

6. LAG() and LEAD()

Learned how to compare current rows with previous and next rows.

Examples Practiced
Comparing exam marks
Tracking score progression
Key Learning

LAG() accesses previous rows and LEAD() accesses upcoming rows.

7. Maximum Marks using MAX() OVER(PARTITION BY)

Practiced finding highest marks within each subject.

Key Learning

Window aggregates help compare rows within groups without using GROUP BY.

8. Cumulative Average using ROWS BETWEEN

Learned how to define custom window frames.

Key Learning

ROWS BETWEEN UNBOUNDED PRECEDING AND CURRENT ROW helps calculate cumulative averages over ordered rows.

9. First Admitted Student and Latest Hired Staff

Used ROW_NUMBER() to identify first or latest records within each department.

Key Learning

Combining PARTITION BY with ORDER BY helps retrieve top records per group.

10. NTILE()

Practiced dividing students into equal CGPA groups.

Example
Quartile ranking using NTILE(4)
Key Learning

NTILE() distributes rows evenly into buckets.

11. PERCENT_RANK()

Learned how to calculate relative ranking percentages.

Key Learning

PERCENT_RANK() shows a row’s position relative to other rows.

12. CUME_DIST()

Practiced cumulative distribution calculations.

Example
Salary distribution among staff
Key Learning

CUME_DIST() measures cumulative percentage distribution.

13. Correlated Subqueries

Practiced department-level comparisons using row-by-row subqueries.

Examples Practiced
Students scoring above department average
Staff earning above department salary average
Key Learning

Correlated subqueries execute once for every row processed by the outer query.

14. Combined Analytical Report Queries

Created advanced reports by combining multiple SQL concepts in a single query.

Concepts Combined
Window functions
Aggregates
Joins
Subqueries
Ranking functions
Key Learning

Real-world SQL analytics often combine multiple advanced concepts together.

Key Learnings
Window functions allow calculations without grouping away rows
Ranking functions handle duplicates differently
PARTITION BY creates grouped analytical windows
Running totals and cumulative averages are easier using window functions
LAG() and LEAD() help compare row values across positions
NTILE(), PERCENT_RANK(), and CUME_DIST() support analytical reporting
Correlated subqueries perform row-level comparisons
Complex reports combine joins, aggregates, subqueries, and window functions
Resources Used
Resource	Purpose
W3Schools SQL Window Functions	Reference for window functions
db-fiddle.com	Practicing and testing SQL queries
YouTube SQL Playlist	SQL advanced concepts and walkthroughs
Files in This Folder
File	Description
Questions.txt	Contains advanced CMS dataset questions
solutions.sql	Contains SQL solutions for all advanced queries
README.md	Summary of Week 2 Day 2 advanced SQL learnings