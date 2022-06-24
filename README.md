# Pewlett-Hackard-Analysis.
# Overview.
The purpose of this analysis is to determine who will be retiring based on the date of birth and date hired, the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. The analysis also helps to generate a list of employees eligible to receive a retirement package and how many job titles will be open after those employees retire. 

# Resources Used.
> Original csv files:
   * [departments.csv](https://github.com/fa7i3/Pewlett-Hackard-Analysis/files/8964452/departments.csv)
   * [dept_emp.csv](https://github.com/fa7i3/Pewlett-Hackard-Analysis/files/8964456/dept_emp.csv)
   * [dept_manager.csv](https://github.com/fa7i3/Pewlett-Hackard-Analysis/files/8964463/dept_manager.csv)
   * [employees.csv](https://github.com/fa7i3/Pewlett-Hackard-Analysis/files/8964476/employees.csv)
   * [salaries.csv](https://github.com/fa7i3/Pewlett-Hackard-Analysis/files/8964480/salaries.csv)
   * [titles.csv](https://github.com/fa7i3/Pewlett-Hackard-Analysis/files/8964481/titles.csv)

> Softwares used:
   * PostgreSQL
   * pgAdmin

> Entity Relationship Diagram (ERD) Tool:
   * Quick Database Diagrams
  
# Pewlett Hackard Employee Database ERD
The Database ERD shows the flow of information between different tables, or CSV files which highlights the primary keys, foreign keys and different data types for each column.

![EmployeeDB](https://user-images.githubusercontent.com/104453593/175185784-b8e02050-19c7-45d1-ae05-0b178ad26cb6.png)

# Results.
* Getting the number of Expected Retirees: According to the analysis, the unique_titles table containing the number of employees (90,398) likely to retire soon was created by joining both the employees and titles tables, filtering the tables by date of birth and date hired, removing duplicates, and arranging the data points by date hired. 
* Total Expected Retirees: 
According to the analysis, 90,398 employees will likely retire soon out of 300,024 employees at the company.
* Titles for Expected Retirees: 
According to the analysis, out of the 90,038 employees likely to retire soon, the majority are Engineers, closely followed by Staff members and the Manager with the least count.

![retiring_titles pic](https://user-images.githubusercontent.com/104453593/175187996-fbbdd2b8-1fb0-4816-9dca-780046ddf6ce.PNG)

* Employees Eligible to participate in the Mentorship Program:
According to the analysis, 1,549 employees are eligible to participate in the Pewlett Hackard's mentorship program.

# Summary.
* How many roles will need to be filled as the "silver tsunami" begins to make an impact? 
According to the analysis, 90,398 employees are likely to retire soon; therefore, the roles that will need to be filled depends on how many employees will actually retire.
* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
According to the analysis, out of 300,024 employees, only 90,398 employees are likely to retire and mentor the next generation of employees. This will give us an average of 58 mentees to 1 mentor. Based on this ratio, the mentees may not get the required knowledge, experience and help needed to excel in the company.
