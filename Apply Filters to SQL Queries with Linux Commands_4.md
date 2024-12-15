# Portfolio Activity #4: Apply filters to SQL queries files with Linux commands <a name="seven">
- use the content of (https://docs.google.com/document/d/1jRgoPi-qYuspdFpJGn2FEQIySm15KB8xfdCdMEYHs-Y/edit?usp=sharing) and (https://docs.google.com/document/d/1FvBXjHx2e4zscXql4JS-_9aQE0on4mB5znxJghF4nAM/edit?usp=sharing)

# Project Description: Describe the command you can use to check permissions 
- In this scenario, my role is to investigate potential security issues within the organization by analyzing data from two tables, "log_in_attempts" and "employees." Through SQL queries, I aim to retrieve specific data to assess security concerns, such as after-hours login attempts, login attempts on specific dates, unauthorized login attempts from outside Mexico, and details of employees based on their department and location. Retrieve after hours failed login attempts. To investigate potential security incidents that occurred after business hours, I will query the "log_in_attempts" table using SQL filters. Specifically, I will retrieve all records of failed login attempts that occurred after 18:00 (6:00 PM).

# Task
- Your task is to examine the organization’s data in their employees and log_in_attempts tables. You’ll need to use SQL filters to retrieve records from different datasets and investigate the potential security issues.
# Retrieve after hours failed login attempts
```
SQL Query:
SELECT *
FROM log_in_attempts
WHERE success = 0 AND TIME(login_time) > '18:00:00';
```
# Retrieve login attempts on specific dates 
To investigate a specific event, I will query the "log_in_attempts" table to retrieve login attempts that occurred on 2022-05-09 or 2022-05-08.
```
SQL Query:
SELECT *
FROM log_in_attempts
WHERE login_date IN ('2022-05-08', '2022-05-09');
```
# Retrieve login attempts outside of Mexico
To examine suspicious login attempts that occurred outside of Mexico, I will use SQL filters to retrieve records from the "log_in_attempts" table where the country is not Mexico (both "MEX" and "MEXICO" should be considered).
```
SQL Query:
SELECT *
FROM log_in_attempts
WHERE country NOT LIKE 'MEX%';
```
# Retrieve employees in Marketing
To gather information about employees in the Marketing department located in the East building, I will query the "employees" table and apply SQL filters.
```
SQL Query:
SELECT *
FROM employees
WHERE department = 'Marketing' AND office LIKE 'East%';
```
# Retrieve employees in Finance or Sales
To identify employees in the Finance or Sales departments, I will query the "employees" table using SQL filters.
```
SQL Query:
SELECT *
FROM employees
WHERE department IN ('Finance', 'Sales');
```
# Retrieve all employees not in IT
To target all employees not belonging to the IT department, I will query the "employees" table using SQL filters.
```
SQL Query:
SELECT *
FROM employees
WHERE department != 'Information Technology';
```
# Summary
Using SQL queries, I have performed an extensive investigation into potential security concerns, including after-hours login attempts, suspicious logins on specific dates, attempts from outside Mexico, and employee information based on their department and location. These queries help strengthen the organization's security by identifying and mitigating potential vulnerabilities and risks.
