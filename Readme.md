# Database Interview Questions

This project contains the database interview questions, the questions belong to random database topics with varying difficulty.

## List of questions-
1. Out of n records the query should return 3 to 8 records from the table?
2. Calculate the number of experience i.e. months, of the employees from the joining date of the employees table?
3. Difference between drop, truncate and delete a table?
4. Write a query to find the highest salary of an employee?
5. Write a query to find the 3rd highest salary of an employee?
6. Write a query to delete duplicate records from the table
7. If there is a table with a primary key would it be possible to create a clustered index on the table? 
8. Explain ACID properties
9. What is normalization and denormalization? Explain the various normalization forms with an example.
10. What are aggregate and scalar functions? Give 1 example of each.
11. Write a query to create an empty table with the same structure as another table?
12. Write a query/queries to backup data of one table into another backup table?
13. What is an indexing works in database?
14. How indexing affects select, insert and delete queries on a table?
15. What is a join? List its different types with an example. Explain Cartisian join.
16. What is a floor and ceil function in database?
17. What is Referential Integrity?
18. What is the difference between procedure and function?
19. Difference between a view and materialized view? Can we modify a view? 
20. Explain difference between a primary key and unique key.
21. How to get the total number of records from the table?
22. What is pivot?
23. Difference between temp table and temp table variable?
24. Write all the basic operations on a table i.e. Add a row, update a row, delete a row, sort the table in an ascending order
25. What are triggers and its types? How it works?
26. What is the difference between having and where clause? or Why we cannot use Where clause with aggregate functions like HAVING?
27. Given a table employees, such as below one, that has e= employee and m= manager values. swap all e and m values with a single update statement.  
Example:-  
|id | name | designation|  
|---|------|------------|  
|1  | P    | e          |  
|2  | Q    | m          |  
|3  | R    | e          |  
|4  | S    | m          |   
28. What is identity column?
29. How to use minus, intersect and union.

### Practice using below 2 tables for SELECT queries
Employees:  
![alt text](https://github.com/Amit460021/database-interview-problems/blob/master/Employees.PNG, "Employees")

Salary:   
![alt text](https://github.com/Amit460021/database-interview-problems/blob/master/Salary.PNG,"Salary")  

* Write a select query to fetch the count of employees working in project P1.
* Write a SQL query to fetch employee names having salary greater than or equal to 5000 and less than or equal to 10000
* Write a SQL query to fetch the project wise count of employees sorted by project's count in descending order.
* Write a query to fetch only the first name ( string before space) from name of Employees table.
* Write a query to fetch employees name and salary records even if salary record doesn't exist in salary table.
* Write a SQL query to fetch all employee records from employees table who have a salary record in Salary table.
* Write a SQL salary to fetch the duplicate records from a table.
* Write a SQL query to fetch only odd rows from a table.
* Write a SQL query to fetch only even rows from a table.
* Write a SQL query to create a new table employees_copy from employees table with  data and structure copied from employees table.
* Write a SQL query to create an empty table employees_copy with the same structure as that of employees table.
* Write a SQL to find current date time.
* Write a  SQL to find all the employees who join in year 2016.
* Write a SQL to fetch top 3 records? 
* Write a SELECT query to find the employee with 3rd highest salary without using TOP/LIMIT keyword.