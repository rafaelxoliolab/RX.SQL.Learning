# SQL Server Interview Questions and Answers
By Rafael Xolio


## Description
This is a recopilation of Questions and Answer commonly used for interviews, I hope this can help you as guide for preparation of your interviews and exams.


## QUESTIONS & ANSWERS


**What are INNER JOINS?** \
Inner Join selects only matching records from _both tables_.

```sql
select * from letfTable
inner join rightTable
on letfTable.Id = rightTable.EmployeeId
```

**What are LEFT JOINS?** \
Left Join selects ALL data from the _left table_ and only matching records from _right table_. The not matching records from the right table will be returned as NULL.

```sql
select * from letfTable
left join rightTable
on letfTable.Id = rightTable.EmployeeId
```

**What are RIGHT JOINS?** \
Right Join selects ALL data from the _right table_ and only matching records from _left table_. The not matching records from the right table will be returned as NULL.

```sql
select * from letfTable
right join rightTable
on letfTable.Id = rightTable.EmployeeId
```
