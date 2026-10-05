# Student Database – Part 2

A PostgreSQL and Bash project completed as part of the freeCodeCamp Relational Database curriculum.

## About

This project builds on the Student Database created in Part 1 and focuses on querying relational data using more advanced SQL techniques.

The Bash script executes PostgreSQL queries to retrieve and display information about students, majors, and courses.

## Technologies

- PostgreSQL
- SQL
- Bash

## Concepts Practiced

- SELECT queries
- WHERE clauses
- Comparison and logical operators
- LIKE and ILIKE
- NULL handling
- ORDER BY
- LIMIT
- Aggregate functions
  - MIN()
  - MAX()
  - COUNT()
  - AVG()
- ROUND()
- DISTINCT
- GROUP BY
- HAVING
- Column and table aliases
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL JOIN
- USING()
- Multi-table joins

## Database Relationships

The project works with the following tables:

- `students`
- `majors`
- `courses`
- `majors_courses`

The `majors_courses` table is used to represent the many-to-many relationship between majors and courses.

## Bash Script

The `student_info.sh` script connects to the PostgreSQL database and executes queries to retrieve information such as:

- Students based on GPA
- Courses matching specific patterns
- Average GPA
- Number of students per major
- Majors without students
- Students and their majors
- Courses associated with students
- Courses with only one student enrolled

## What I Learned

This project helped me strengthen my understanding of relational databases and SQL, particularly how to:

- Filter and sort data
- Aggregate and group records
- Filter grouped results with `HAVING`
- Combine related tables using different types of joins
- Work with many-to-many relationships
- Execute PostgreSQL queries from Bash scripts

## Author

Michele De Florio
