# SQL Server Interview Questions and Answers
By Rafael Xolio


## Description
This is a recopilation of Questions and Answer commonly used for interviews, I hope this can help you as guide for preparation of your interviews and exams.


## QUESTIONS & ANSWERS


**What are Inner Joins?** \
Inner join selects matching records from both tables.

```sql
select * from employee
inner join employeeDepartment
on employee.Id = employeeDepartment.EmployeeId
```
