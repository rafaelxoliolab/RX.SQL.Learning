# SQL Server Interview Questions and Answers
By Rafael Xolio


## Description
This is a recopilation of Questions and Answer commonly used for interviews, I hope this can help you as guide for preparation of your interviews and exams.


## QUESTIONS & ANSWERS


**What are INNER JOINS?** \
Inner Join selects only matching records from both tables.

```sql
select * from employee
inner join employeeDepartment
on employee.Id = employeeDepartment.EmployeeId
```

**What are LEFT JOINS?** \
Left Join selects ALL data from the left table and only matching records from right table. The not matching records from the right table will be return as NULL.

```sql
select * from employee
left join employeeDepartment
on employee.Id = employeeDepartment.EmployeeId
```
