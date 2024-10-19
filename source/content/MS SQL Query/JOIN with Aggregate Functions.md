
**Name:** Showyeab Ahmed
**Date:** 2024-10-13
**Tags:** #join #aggregatefunctions



## JOIN with Aggregate Functions

### 1. INNER JOIN with COUNT
Retrieve the number of employees in each department.

```sql
SELECT b.DepartmentName, COUNT(a.EmployeeID) AS NumberOfEmployees
FROM Employees a
INNER JOIN Departments b ON a.DepartmentID = b.DepartmentID
GROUP BY b.DepartmentName;
```
