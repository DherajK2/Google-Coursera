# Module 3 challenge

### Question 1:
**You use VLOOKUP to search for the name “Liza Campbell.” However, the function doesn’t work properly because your spreadsheet has a repeated space between the first and last name. What function should you use to eliminate this space?**

- **Answer:** `TRIM`

---

### Question 2:
**Fill in the blank: The spreadsheet function _____ can be used to tally the number of cells in a range that are not empty.**

- **Answer:** `COUNT`

---

### Question 3:
**A data analyst writes the following formula: =MAX($E$5:$E$500). What are the purposes of the dollar signs ($)? Select all that apply.**

- **Answer:**
  - Create an absolute reference.
  - Ensure rows and columns do not change.
  - Find the maximum value in the range E5 to E500 regardless of whether the formula is copied.

---

### Question 4:
**What will this query return?**
```sql
SELECT *
FROM Inventory_table
LEFT JOIN Scrap_table

Answer: All records in Inventory_table and any matching rows from Scrap_table


Question 5:
In this spreadsheet, which function will search for the surface area of Lake Huron?

A	B	C
Lake	Surface area (sq. miles)	Water type
Caspian Sea	143,000	Saline
Superior	31,700	Freshwater
Victoria	26,590	Freshwater
Huron	23,000	Freshwater
Tanganyika	12,600	Freshwater
Balkhash	6,300	Saline
Athabasca	3,030	Freshwater
Urmia	2,320	Freshwater
Answer: =VLOOKUP("Huron", A2:B10, 2, false)


Question 6:
Fill in the blank: A SQL clause containing HAVING allows you to add a filter to your query when working with _____ functions.

Answer: aggregate


Question 7:
A data professional at a manufacturing company works with a spreadsheet containing inventory management data. To create a chart from the data to share with stakeholders, the analyst uses a function that converts all data to numeric values. What function do they use?

Answer: VALUE



Question 8:
Which query will select all columns from the customer table and alias the table to cust?

Answer:
sql
Copy code
SELECT *
FROM customer AS cust



Question 9:
What are the benefits of using subqueries in SQL? Select all that apply.

Answer:
Subqueries can simplify complex queries.
Subqueries can be used to filter data based on results from another table.
Subqueries can replace complex joins in some cases.
Subqueries can improve code readability.



Question 10:
What does this code do?

sql
Copy code
SELECT account_table.*
   FROM (
       SELECT *
       FROM transaction.sf_model_feature_2014_01
       WHERE day_of_week = 'Monday'
       ) AS account_table
   WHERE account_table.availability = 'NO'
Answer: It selects all columns from the table containing transactions on Monday and filters them to display only the transactions that are unavailable.


Question 11:
What does this code do?

sql
Copy code
SELECT e.employee_id, e.first_name, e.last_name, e.salary
FROM employees e
WHERE e.salary > (
  SELECT AVG(salary)
  FROM employees
  WHERE department_id = e.department_id
);
Answer: It finds employees who earn more than the average salary in their department.

