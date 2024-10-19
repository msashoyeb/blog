
**Name:** Showyeab Ahmed
**Date:** 2024-10-13
**Tags:** #mssql #join


## SQL JOIN Queries

### 1. INNER JOIN
An `INNER JOIN` returns only the rows where there is a match in both tables.

### Example:
```sql
SELECT a.EmployeeID, a.Name, b.DepartmentName
FROM Employees a
INNER JOIN Departments b ON a.DepartmentID = b.DepartmentID;
```

<center>Or,</center>

We can use `JOIN` instead of `INNER JOIN`.
<p align="justify">Also, there are more types of joins, such as LEFT JOIN (or LEFT OUTER JOIN), RIGHT JOIN (or RIGHT OUTER JOIN), FULL JOIN (or FULL OUTER JOIN), SELF JOIN, and CROSS JOIN (returns the Cartesian product of both tables. Every row from the first table is combined with every row from the second table).
</p>

![[Pasted image 20241013082939.png#center]]
