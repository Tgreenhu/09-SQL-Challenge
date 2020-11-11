# 09-SQL-Challenge

In this assignment, we were given 6 CSV files containing data from all employees of a company.

First, to gain a visual picture of what all our data contains, as well as to see which files contain similar columns, I reverse engineered the data into an ERD table.  I did this to better gain a visual of our primary and foregin keys.

From this table, I exported the data as a SQL file so I could import the tables created into pgAdmin.  Using the import function pgAdmin has, I imported each of our given CSVs to fill the tables with the correct data.

Using various JOIN functions, I performed the following queries on our dataset:
    - List the following details of each employee: employee number, last name, first name, sex, and salary.
    - List first name, last name, and hire date for employees who were hired in 1986.
    - List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
    - List the department of each employee with the following information: employee number, last name, first name, and department name.
    - List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
    - List all employees in the Sales department, including their employee number, last name, first name, and department name.
    - List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
    - In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

For Bonus, I imported the SQL database into Jupyter Notebook to perform the following actions using Pandas:
    - Create a histogram to visualize the most common salary ranges for employees.
    - Create a bar chart of average salary by title.