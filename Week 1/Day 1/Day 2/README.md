Week 1 — Day 2
Overview

Day 2 focused on advancing SQL querying skills by practicing sorting, JOIN operations, subqueries, and multi-clause SQL queries. All queries were written and tested using the Employee–Department–Project schema on db-fiddle.com.

Schema Used

The same three-table schema from Day 1 was used:

Employee
Department
Project

Refer to the Day 1 README for the complete schema structure and sample data.

Topics Covered
7. ORDER BY Queries

Practiced sorting query results using single and multiple columns in ascending and descending order.

Concepts Learned
Sorting rows using ORDER BY
Using ASC and DESC
Sorting by multiple columns
Combining ORDER BY with GROUP BY
Key Learning

When multiple columns are used in ORDER BY, SQL sorts by the first column first, then uses the next column to break ties.

8. JOIN Queries

Learned how to combine records from multiple tables using different JOIN operations.

JOIN Types Practiced
JOIN Type	Purpose
INNER JOIN	Returns matching rows from both tables
LEFT JOIN	Returns all rows from the left table and matched rows from the right
Self JOIN	Joins a table with itself
Concepts Learned
Fetching employee and department details together
Finding unmatched records using LEFT JOIN
Comparing rows within the same table using self joins
Key Learning

Using:

LEFT JOIN ... WHERE right_table.column IS NULL

is a common technique to find records without matches.

9. Nested and Correlated Queries

Practiced writing queries inside other queries using subqueries.

Concepts Learned
Scalar subqueries
Correlated subqueries
Using IN (subquery)
Finding nth highest values using LIMIT and OFFSET
Key Learning

Correlated subqueries execute once for every row of the outer query and can compare values row by row.

10. Combined Moderate Difficulty Queries

Solved more realistic SQL problems by combining multiple SQL clauses in a single query.

Clauses Combined
WHERE
GROUP BY
HAVING
ORDER BY
JOIN
Subqueries
Key Learning

SQL clauses follow a logical execution order:

FROM → JOIN → WHERE → GROUP BY → HAVING → SELECT → ORDER BY → LIMIT

Understanding this order helps in writing correct complex queries.

Key Learnings
ORDER BY can sort using multiple columns
INNER JOIN returns only matching rows
LEFT JOIN preserves unmatched rows from the left table
Self joins help compare rows within the same table
Correlated subqueries reference the outer query
LIMIT 1 OFFSET n-1 helps find nth highest values
HAVING filters grouped data after aggregation
SQL clause execution order is important in complex queries
Resources Used
Resource	Purpose
W3Schools SQL	Reference for JOINs and subqueries
YouTube SQL Playlist	SQL concept explanations and walkthroughs
db-fiddle.com	Practicing and testing SQL queries
Files in This Folder
File	Description
Questions.txt	Contains all 35 SQL practice questions
Solutions.sql	Contains solutions for all 35 SQL queries
README.md	Summary of Day 2 SQL learnings