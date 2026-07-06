# Employee Attendance Management System using SQL Server

## Project Overview

The Employee Attendance Management System is a SQL Server-based project developed to analyze employee attendance, productivity, leave management, and performance. The project simulates a real-world HR analytics scenario where employee attendance data is transformed into meaningful business insights using SQL queries.

This project demonstrates practical SQL concepts used in the industry, including aggregations, window functions, Common Table Expressions (CTEs), ranking functions, views, stored procedures, and KPI reporting.

---

## Business Problem

Organizations need to monitor employee attendance and productivity to improve workforce efficiency and support informed business decisions.

The objective of this project is to analyze employee attendance records and generate reports that help management answer questions such as:

* How many employees were present, absent, working from home, or on leave?
* Which departments have the highest attendance percentage?
* Which employees are the most productive?
* Which employees consistently arrive late?
* What is the average working hours across departments?
* How is bonus distributed based on employee performance?

---

## Objectives

* Analyze employee attendance trends.
* Calculate attendance-related KPIs.
* Measure employee productivity.
* Evaluate departmental performance.
* Analyze leave utilization.
* Identify top and bottom performers.
* Generate management-ready reports using SQL.

---

## Dataset Information

The dataset contains employee records with attendance and performance information.

### Columns Included

* Employee ID
* Employee Name
* Gender
* Age
* Department
* Designation
* Joining Date
* Salary
* Manager
* Attendance Date
* Check In
* Check Out
* Work Hours
* Attendance Status
* Leave Type
* Leave Status
* Tasks Completed
* Productivity Score
* Performance Rating
* Bonus

---

## Technologies Used

* SQL Server
* SQL Server Management Studio (SSMS)
* Git
* GitHub

---

## SQL Concepts Demonstrated

### Basic SQL

* SELECT
* WHERE
* ORDER BY
* DISTINCT
* TOP
* Aliases

### Aggregate Functions

* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()

### Grouping

* GROUP BY
* HAVING

### Conditional Logic

* CASE WHEN

### Window Functions

* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* NTILE()
* LAG()
* LEAD()

### Common Table Expressions (CTEs)

* Single CTE
* Multiple CTEs

### Views

* Creating Views
* Querying Views

### Stored Procedures

* Parameterized Stored Procedures

### Ranking & Reporting

* Top Performers
* Bottom Performers
* Department-wise Ranking

---

## Key Performance Indicators (KPIs)

* Total Employees
* Present Employees
* Absent Employees
* WFH Employees
* Half-Day Employees
* Attendance Percentage
* Average Working Hours
* Department-wise Attendance
* Productivity Score
* Performance Rating
* Total Bonus Distributed
* Leave Analysis

---

## Business Questions Solved

* Total number of employees.
* Attendance percentage.
* Department-wise attendance summary.
* Employees working more than 9 hours.
* Employees with late check-in.
* Employees working from home.
* Employees on leave.
* Average salary by department.
* Department-wise productivity.
* Top 10 productive employees.
* Bottom-performing employees.
* Highest salary earners.
* Employees receiving the highest bonus.
* Manager-wise team size.
* Employees earning above department average.
* Department-wise employee ranking using RANK().
* Running total of bonus using window functions.

---

## Project Structure

```text
Employee-Attendance-Management-SQL
│
├── Dataset
│   └── Dummy_Employee_Data.csv
│
├── SQL Scripts
│   ├── Create_Database.sql
│   ├── Create_Table.sql
│   ├── Basic_Queries.sql
│   ├── Aggregate_Functions.sql
│   ├── Window_Functions.sql
│   ├── CTE.sql
│   ├── Views.sql
│   ├── Stored_Procedures.sql
│   └── Business_Case_Queries.sql
│
├── Screenshots
│
└── README.md
```

---

## Sample SQL Features Implemented

* Employee attendance reporting
* Department-wise analytics
* Ranking employees using Window Functions
* Leave analysis
* Bonus analysis
* Productivity reporting
* Management KPI dashboard queries

---

## Future Enhancements

* Normalize the database into multiple related tables.
* Create attendance records for multiple months or years.
* Integrate Power BI dashboards.
* Implement triggers for attendance validation.
* Add user authentication and role-based access.
* Build stored procedures for automated reporting.
* Optimize queries using indexes.

---

## Learning Outcomes

Through this project, I strengthened my understanding of:

* SQL Query Writing
* Database Design
* Data Analysis
* HR Analytics
* Window Functions
* Aggregate Functions
* Common Table Expressions
* Views and Stored Procedures
* Business KPI Reporting
* Real-world SQL Problem Solving

---

## Author

**Supriya Pagare**

Data Analyst with experience in Banking Operations and a strong interest in SQL, Power BI, Advanced Excel, and Business Intelligence.

GitHub: https://github.com/Sup0311

LinkedIn: https://www.linkedin.com/in/supriyapagare
