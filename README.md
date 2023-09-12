# sql-challenge
mod 9 challenge

# Background
As a new data engineer at Pewlett Hackard, you are task with doing a research project about people whom the company employed during the 1980s and the 1990s. You have been provided with the remains of the employee database from that period through six CSV files.

For this project, you need to design the tables to hold the data from the CSV files, import the CSV diles into a SQL database, and display the information requested. 

# Data Engineering
Inspect the CSV files and sketch an Entity Relationship Diagram of the tables. The sketch could be reated using the QuickDBD tool.

# Data Engineering
Create a table schema for each of the six CSV files.
  - Remember to specifiy the data types, primary keys, foreign keys, and any other contraints.
  - for primary keys, verify the column is infact unique. Otherwise, a composite key is need to take the two primary keys to uniquely identify a row.
Import each CSV file into it corresponding SQL table.

# Data Analysis
  1. List the employee number, last name, first name, sex, and salary of each employee.
  
  2. List the first name, last name, and hire date for the employees who were hired in 1986.
  
  3, List the manager of each department along with their department number, department name, employee number, last name, and first name.
  
  4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
  
  5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
  
  6. List each employee in the Sales department, including their employee number, last name, and first name.
  
  7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
  
  8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

# Check
- proivde image file of ERD
- create a .sql file of your table schemata
- create a .sql file of your queries
