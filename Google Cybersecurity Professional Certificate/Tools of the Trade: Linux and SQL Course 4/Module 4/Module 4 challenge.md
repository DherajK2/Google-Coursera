# Module 4 challenge


### 1. Question 1  
**A security analyst queries a table related to login attempts. How can SQL help this analyst with their work?**  
- The analyst can efficiently find the login data they need.

---

### 2. Question 2  
**What is true about the values in the primary key column? Select all that apply.**  
- They cannot be null (or empty).  
- Each row must have a unique value.

---

### 3. Question 3  
**Which of these SQL statements queries the `log_in_attempts` table? Select all that apply.**  
- `SELECT * FROM log_in_attempts;`  
- `SELECT event_id, username FROM log_in_attempts WHERE event_id < 150;`

---

### 4. Question 4  
**What type of join compares tables and returns only the rows that have a matching value in a specified column?**  
- INNER JOIN

---

### 5. Question 5  
**What does `WHERE department = 'Sales'` indicate in the following SQL query?**

```sql
SELECT * 
FROM employees 
WHERE department = 'Sales';


To only return rows that match the filter


6. Question 6
You work with a table that has one column for name. Some of these names have prefixes. You want to identify all of the doctors. Which query will return every name that starts with the prefix 'Dr.'?

WHERE name LIKE 'Dr.%';


7. Question 7
You need to perform a SQL join. You want to return all the columns with records matching on the device_id column between the employees and machines tables. You also want to return all records from the employees table. Which of the following queries would you use?

SELECT * FROM employees LEFT JOIN machines ON employees.device_id = machines.device_id;


8. Question 8
You are working with the Chinook database. You want to return the company and country columns from the customers table. Replace --??? with the missing information to complete the query.


--??? 
FROM customers;
In what country is JetBrains s.r.o. located?

Czech Republic


9. Question 9
You are working with the Chinook database and are responsible for filtering for invoices with a total that is more than 20. Replace --??? with the missing information to complete the query.

sql
Copy code
SELECT customerid, total 
FROM invoices
--???
How many invoices have a total that is more than 20?

4


10. Question 10
You are working with the Chinook database and are responsible for filtering for the customers that have a value of 'USA' in the country column and have a value of 'Frank' in the firstname column. Replace --??? with the missing information to complete the query.

sql
Copy code
SELECT firstname, lastname, country
FROM customers
--???
How many customers live in the USA and have the name Frank?

1
