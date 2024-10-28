1. Database Creation & Schema Design
• Create a database called `school_management`.
• Create the following tables:
• students: `student_id` (INT, PRIMARY KEY), `first_name`, `last_name`, `dob`, `email`, 
`phone_number`.
• courses: `course_id` (INT, PRIMARY KEY), `course_name`, `course_code`, `credits`.
• enrollments: `enrollment_id` (INT, PRIMARY KEY), `student_id` (INT), `course_id` (INT), 
`enrollment_date`.
• grades: `grade_id` (INT, PRIMARY KEY), `enrollment_id` (INT), `grade`.
2. Alterations and Modifications
• Add a column `address` to the `students` table.
• Modify the `course_name` column in the `courses` table to be of type `VARCHAR(100)`.
• Change the position of the `credits` column to be right after the `course_code` in the `courses` 
table.
• Rename the `dob` column in `students` to `date_of_birth`.
3. Data Insertion
• Insert at least 30 students into the `students` table.
• Insert at least 10 courses into the `courses` table.
• Insert at least 12 records into the `enrollments` table, ensuring that some students are enrolled 
in multiple courses.
• Insert grades for each enrollment in the `grades` table.
4. Complex Queries
• Write a query to retrieve the full names and courses for all students.
• Write a query to find all students who have not yet been assigned a grade.
• Write a query that returns the average grade for each course.
• Create a `CASE` statement to assign letter grades (A, B, C, D, F) based on numerical grades.
• Use subqueries to find students with the highest grades in each course.
5. Using CTEs (Common Table Expressions)
• Write a CTE to list all students with their course names and grades.
• Write a CTE to find students who have taken more than 2 courses.
6. Importing & Exporting Data
• Export the `students` table to a CSV file.
• Import a CSV file (provided or created) containing a list of new courses into the `courses` table.
7. Additional Tasks
• Write a query to count the number of students enrolled in each course.
• Create a report showing the total number of students, courses, and enrollments.
• Use a JOIN to retrieve the names of students and the courses they are not enrolled in.
• Write a query to find students who share the same last name.
