# Database-project-SQL--Student-Registration-System-
20 High level SQL quires are applied to a Database System of Student Registration in a University.

**proj1_tables_script18.pdf** -  This file has the creation and insertion queries.

**Proj1.txt** -This file has 20 high level manipulation quires and their output tables.

The following normalized tables from the Student Registration System (some tables have been simplified) will be used in this project:

Students(B#, first_name, last_name, status, gpa, email, bdate, deptname) 

TAs(B#, ta_level, office)

Courses(dept_code, course#, title) 

Course_credit(course#, credits) 

Classes(classid, dept_code, course#, sect#, year, semester, limit, class_size, room, TA_B#) 

Enrollments(B#, classid, lgrade)

It is assumed that no student takes the same course (including different sections of the same course) more than once.There are 20 statements (see Section below) in this project. The query is taken into consideration that the tuples currently in the database may change. In other words, your query must be correct for any valid state of every table.

