Week 2 — Day 1 — College Management System
Overview

Day 1 of Week 2 focused on practicing SQL using a new real-world style schema — a College Management System (CMS). The dataset included five related tables: Department, Staff, Student, Subject, and Mark. Queries were practiced on db-fiddle.com.

The practice focused on joins, aggregation, filtering, grouping, and subqueries using college-related data.

Schema Used

The College Management System dataset contained the following tables:

Department
Staff
Student
Subject
Mark

The schema was designed to simulate real-world academic data and relationships.

Topics Covered
1. LEFT JOIN Queries

Practiced retrieving all rows from one table even when matching records do not exist in another table.

Examples Practiced
Staff without departments
Students without marks
Key Learning

LEFT JOIN preserves unmatched rows from the left table and fills missing values with NULL.

2. INNER JOIN Queries

Learned how to combine matching records across multiple tables.

Examples Practiced
Students with their departments
Subjects handled by staff
Student marks with subject details
Key Learning

INNER JOIN returns only rows with matching values in both tables.

3. Finding Unmatched Rows

Used:

WHERE column IS NULL

together with LEFT JOIN to identify missing relationships.

Key Learning

This technique is useful for finding incomplete or missing data.

4. GROUP BY with Aggregate Functions

Practiced grouping rows and performing calculations on grouped data.

Aggregate Functions Used
AVG()
COUNT()
SUM()
MAX()
MIN()
Key Learning

GROUP BY helps summarize data category-wise.

5. HAVING Clause

Learned how to filter grouped results after aggregation.

Key Learning

HAVING works on grouped data, while WHERE filters rows before grouping.

6. Subqueries

Practiced writing queries inside other queries for comparisons and filtering.

Examples Practiced
Students scoring above average
Departments with higher than average marks
Key Learning

Subqueries make complex filtering easier and improve query flexibility.

7. Correlated Subqueries

Learned how subqueries can reference the current row from the outer query.

Key Learning

Correlated subqueries execute once for every row processed by the outer query.

8. ORDER BY with CGPA Ranking

Practiced sorting students based on CGPA and marks.

Key Learning

ORDER BY helps rank and organize academic results efficiently.

9. Multiple Condition Filtering

Practiced filtering records using:

AND

with multiple conditions.

Key Learning

Combining conditions helps create more precise queries.

Key Learnings
LEFT JOIN helps find missing relationships
INNER JOIN combines matching data from multiple tables
Aggregate functions summarize grouped data
HAVING filters grouped results after aggregation
Subqueries simplify advanced filtering
Correlated subqueries perform row-by-row comparisons
ORDER BY helps rank students by performance
Multiple conditions improve query accuracy
Resources Used
Resource	Purpose
W3Schools SQL Tutorial	Reference for SQL syntax and queries
db-fiddle.com	Practicing and testing SQL queries
YouTube SQL Playlist	SQL explanations and practice walkthroughs
Files in This Folder
File	Description
Questions.txt	Contains CMS dataset practice questions
solutions.sql	Contains SQL query solutions for the CMS dataset
README.md	Summary of Week 2 Day 1 SQL learnings