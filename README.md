<h1>Employee Database: A Mystery in Two Parts</h1>


<h2><b>Background</b></h2>

It is a beautiful spring day, and it is two weeks since you have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

In this assignment, you will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, you will perform:


Data Modeling
Data Engineering
Data Analysis



<b>Instructions</b>


Data Modeling

Inspect the CSVs and sketch out an ERD of the tables. Feel free to use a tool like http://www.quickdatabasediagrams.com.


Data Engineering


Use the information you have to create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.
Import each CSV file into the corresponding SQL table.



Data Analysis

Once you have a complete database, do the following:

<ul>
<li>List the following details of each employee: employee number, last name, first name, gender, and salary.</li><br/>
<li>List employees who were hired in 1986.</li><br/>
<li>List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name, and start and end employment dates.</li><br/>
<li>List the department of each employee with the following information: employee number, last name, first name, and department name.</li><br/>
<li>List all employees whose first name is "Hercules" and last names begin with "B."</li><br/>
<li>List all employees in the Sales department, including their employee number, last name, first name, and department name.</li><br/>
<li>List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.</li><br/>
<li>In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.</li><br/>
</ul>

<b>Submission</b>


Create an image file of your ERD.<br/>
Create a .sql file of your table schemata.<br/>
Create a .sql file of your queries.<br/>
(Optional) Create a Jupyter Notebook of the bonus analysis.
