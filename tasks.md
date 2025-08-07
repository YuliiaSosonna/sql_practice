# SQL Practice tasks

This project includes a collection of SQL tasks designed to analyze employee-related data from a company database. The exercises demonstrate practical use of SQL concepts such as JOINs, aggregation, filtering, and window functions. Each task focuses on extracting useful business insights, supporting decision-making in areas like employee management, salary analysis, and organizational structure.


### Task 1. Join "employees" and "salaries" tables

Display a list of 10 employees, showing their `emp_no`, `first_name`, `last_name`, and their current salary.

> Note: The order of the employees does not matter. The goal is to retrieve the correct table structure.

---
### Task 2. Join "employees" and "titles" tables

Display a list of 10 employees, showing their `emp_no`, `first_name`, `last_name`, and their current job title.

> Note: The order of the employees does not matter. The goal is to retrieve the correct table structure.

---
### Task 3. Join "employees", "dept_emp", and "departments" tables

Display a list of 10 employees, showing their `emp_no`, `first_name`, `last_name`, and the department they are currently working in.

> Note: The order of the employees does not matter. The goal is to retrieve the correct table structure.

---
### Task 4. Count employees per department

The company management seeks a clear understanding of how employees are distributed across different departments. Specifically, you need to:

- Determine the number of unique employees in each department.
- Present this information in a sorted format, starting with the department that has the highest number of employees.

---
### Task 5. Find the highest-paid employee in the Development department

Identify the employee who earns the highest salary in the **Development** department.  
You need to return the following information: their `emp_no`, `first_name`, `last_name`, and `salary`.

---
### Task 6. Identify the department of the highest-paid employee in the company

We want to determine which department the highest-paid employee in the company works in.  
Return their `emp_no`, `first_name`, `last_name`, `salary`, and the department they belong to.

---
### Task 7. Find the employee with the third highest salary

Display the `emp_no`, `first_name`, `last_name`, and `salary` of the employee with the **third highest salary** in the company.  
Only a single row should be returned in the result.

---
### Task 8. Find employees with multiple job titles

Some employees may change their job titles during their time at the company.  
Identify all employees who have held **more than one title** throughout their employment.  
Display their `emp_no`, `first_name`, `last_name`, and a list of all titles they have held.

---
### Task 9. Employee department transfers

Employees sometimes transfer between departments.  
Identify all employees who have worked in **more than one department**.  
Display their `emp_no`, `first_name`, `last_name`, and the names of all departments they have worked in.

---
### Task 10. Current salary of each department manager

For each department, display the department name, the `emp_no` of the **current manager**, their `first_name`, `last_name`, and their **current salary**.  
Make sure to return only the salary of the current manager.


# Task on Using Window Functions

### Task 11. Using ROW_NUMBER to enumerate employees

For the first 10 employees (ordered by `emp_no`), display their `emp_no`, `first_name`, `last_name`,  
and their **row number** in the table using the `ROW_NUMBER()` window function.

---
### Task 12. Display salary history for an employee

Display the `emp_no`, `from_date`, current salary, and the **previous salary** for the employee with `emp_no = 10001`.

---
### Task 14. Rank employees by salary within their department

Display the `emp_no`, `dept_name`, current salary, and the employee's **rank within their department** based on salary.

---
### Task 15. Calculate salary change over the last 2 years

Display the difference between the current salary of the employee with `emp_no = 10001` and their salary 2 years ago.  
The result should include: `emp_no`, `salary_2_years_ago`, current salary, and the difference between the two.

---
### Task 16. Find the employee with the highest salary increase in a year

Identify the employee who received the largest salary increase during the year ending 1 year before the latest date in the `salaries` table (maximum `from_date`).  
The result should include: `emp_no`, salary from the previous year, current salary, and the amount of the salary change.

---
### Task 17. Average salary and earliest hired employee(s) per job title

For each job title, display the title name, the average salary of employees holding that title, the first employee(s) hired for that title (in case multiple employees were hired on the same date), and the corresponding `hire_date`.  
Sort the results by job title and employee name.

---
### Task 18. Using NTILE to group employees by salary

Divide the specified employees into 3 groups based on their current salary.  
Display `emp_no`, `first_name`, `last_name`, salary, and the group number for each employee.

The `emp_no` of the employees to analyze are:  
`419748, 496734, 264134, 209076, 86631, 456171, 16887, 230255, 246465, 420097, 44362, 280370, 479975, 433320, 473949`.
