# SQL Server Interview Questions and Answers
By Rafael Xolio


## Description
This is a recopilation of Questions and Answer commonly used for interviews, I hope this can help you as guide for preparation of your interviews and exams.


## QUESTIONS & ANSWERS


**What are INNER JOINS?** \
Inner Join selects only matching records from _both tables_.

```sql
select * from employee
inner join employeeDepartment
on employee.Id = employeeDepartment.EmployeeId
```

**What are LEFT JOINS?** \
Left Join selects ALL data from the _left table_ and only matching records from _right table_. The not matching records from the right table will be return as NULL.

```sql
select * from employee
left join employeeDepartment
on employee.Id = employeeDepartment.EmployeeId
```
