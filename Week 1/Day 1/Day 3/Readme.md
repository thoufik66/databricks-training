Week 1 — Day 3 — SQL JOINs Assignment
Overview

Day 3 focused on practicing advanced SQL JOIN operations using a simple online learning platform database containing Students, Courses, Enrollments, and Instructors tables. All queries were written and tested on db-fiddle.com.

Schema Used

The assignment used four related tables:

Students
Courses
Enrollments
Instructors

The schema was designed to practice different JOIN operations and understand relationships between tables.

Topics Covered
1. LEFT JOIN

Practiced retrieving all rows from the left table along with matching rows from the right table.

Key Learning

LEFT JOIN keeps unmatched rows from the left table and fills unmatched columns with NULL.

2. RIGHT JOIN

Learned how to return all rows from the right table with matching rows from the left table.

Key Learning

RIGHT JOIN is the opposite of LEFT JOIN and preserves all rows from the right table.

3. FULL OUTER JOIN

Practiced combining all rows from both tables, including matched and unmatched records.

Key Learning

FULL OUTER JOIN returns:

matched rows
unmatched rows from the left table
unmatched rows from the right table
4. CROSS JOIN

Learned how to generate all possible combinations between two tables.

Key Learning

CROSS JOIN creates a Cartesian product where every row from one table is paired with every row from another table.

5. Finding Unmatched Rows

Used JOINs together with:

WHERE column IS NULL

to identify records without matching relationships.

Examples Practiced
Students without enrollments
Courses without students
Instructors not assigned to courses
6. Multiple JOINs

Practiced chaining multiple JOIN operations in a single query to combine data across several tables.

Key Learning

Complex queries often require joining multiple tables step by step using foreign key relationships.

7. UNION Queries

Learned how to combine results from multiple SELECT statements.

Key Learning
UNION removes duplicates
UNION ALL keeps duplicates
Key Learnings
JOINs help connect related data across tables
LEFT JOIN and RIGHT JOIN preserve unmatched rows
FULL OUTER JOIN combines all matching and non-matching rows
CROSS JOIN creates all possible row combinations
IS NULL is useful for finding missing relationships
Multiple JOINs are commonly used in real-world SQL queries
UNION combines results from multiple queries into one output
Resources Used
Resource	Purpose
W3Schools SQL JOIN Tutorial	Understanding JOIN types
db-fiddle.com	Practicing and testing SQL queries
YouTube SQL Playlist	SQL JOIN explanations and examples
Files in This Folder
File	Description
joins_assignment.txt	Contains all assignment questions
solution_queries.sql	Contains solutions for all JOIN assignment queries
README.md	Summary of Day 3 JOIN assignment learnings