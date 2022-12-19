# SQL statement conventions

SQL commands should be written in uppercase letters.  This convention lets the user identify the keywords
SQL statement keywords and easily parse the statement. The statements can be single line or multiline. If the statement is multiline, format each column or logical statement on a new line,
the statement to identify what is being queried and filtered. SQL keywords should be on their own line and indent the criteria. 

## Examples

Single line

Incorrect

```sql
select e.first-name, e.last-name, s.salary from employees e inner join salary s on e.employeeid=s.employeeid 
```

Correct

```sql
SELECT e.first-name, e.last-name, s.salary FROM employees e INNER JOIN salary s ON e.employeeid=s.employeeid
```

Multiline

Incorrect

```sql
select e.first-name, e.last-name, s.salary from employees e inner join salary s 
on e.employeeid=s.employeeid 
```

Correct

```sql
SELECT
    e.first-name,
    e.last-name,
    s.salary
FROM
    employees e
    INNER JOIN salary s ON e.employeeid=s.employeeid
```
    
