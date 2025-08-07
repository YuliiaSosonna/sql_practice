# SQL Practice: Employee Data Analysis

This repository contains practical SQL tasks focused on analyzing employee data. The goal of the project is to extract meaningful business insights using SQL queries and to practice real-world data analysis scenarios.

---

## 📁 Project Structure

* [`tasks.md`](./tasks.md) — SQL tasks 
* [`insights.md`](./insights.md) — Business insights based on query results
* [`solutions.pdf`](./solutions.pdf) — Full SQL solutions in PDF format (in Ukrainian)

---

## 🧠 Key Analytical Insights

* Salary dynamics over time
* Departmental salary comparison
* Internal job transitions
* Workforce loyalty and employee retention
* Recommendations for reward system and HR optimization

> For full details, see the [`insights.md`](./insights.md) file.

---

## 🗃️ Database Overview

The **Employees** database consists of the following main tables:

| Table Name     | Description                                                                                                      |
| -------------- | ---------------------------------------------------------------------------------------------------------------- |
| `employees`    | Basic employee information such as `emp_no`, `first_name`, `last_name`, `gender`, `hire_date`, and `birth_date`. |
| `salaries`     | Salary records linked to employees, with salary amounts and effective dates (`from_date`, `to_date`).            |
| `titles`       | Job titles held by employees over time with start and end dates.                                                 |
| `departments`  | Departments within the company (`dept_no`, `dept_name`).                                                         |
| `dept_emp`     | Links employees to the departments they have worked in, with dates.                                              |
| `dept_manager` | Records department managers with their respective departments and effective dates.                               |

For full documentation and schema details, see the official MySQL Employees database documentation:
[https://dev.mysql.com/doc/employee/en/](https://dev.mysql.com/doc/employee/en/)

---

## 🚀 Tools Used

* SQL (MySQL)
* PDF for report formatting
* GitHub for version control

---

## 📬 Contact

Created by **Yuliia Sosonna**.
Feel free to connect or give feedback!
