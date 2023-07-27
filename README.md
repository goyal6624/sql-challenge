# sql-challenge
This repository contains an Employee Database that includes an Entity-Relationship Diagram (ERD) sketch, a schema, and SQL queries to answer a series of questions related to the employees' information. The database consists of the following tables:

1. ERD Sketch (made with [Quick Database Diagrams](https://www.quickdatabasediagrams.com/):
   - departments
   - dept_emp
   - dept_manager
   - employees
   - salaries
   - titles
[](ERD_sketch.png)

2. Schema:
   The schema for each table is as follows:
   - departments (dept_no, dept_name)
   - dept_emp (emp_no, dept_no, from_date, to_date)
   - dept_manager (dept_no, emp_no, from_date, to_date)
   - employees (emp_no, birth_date, first_name, last_name, gender, hire_date)
   - salaries (emp_no, salary, from_date, to_date)
   - titles (emp_no, title, from_date, to_date)

3. SQL Queries:
   The following SQL queries have been created to answer specific questions about the employees' data:

   1. List the employee number, last name, first name, sex, and salary of each employee.
   2. List the first name, last name, and hire date for the employees who were hired in 1986.
   3. List the manager of each department along with their department number, department name, employee number, last name, and first name.
   4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
   5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
   6. List each employee in the Sales department, including their employee number, last name, and first name.
   7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
   8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

Feel free to explore and use the provided SQL queries to analyze the employee data in the database.
