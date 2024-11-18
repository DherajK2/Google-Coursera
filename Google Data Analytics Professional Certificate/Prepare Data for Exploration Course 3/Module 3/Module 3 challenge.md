# Module 3 challenge

### **Question 1:**
**Fill in the blank: Data professionals use data _____ to control their company’s data and make sure data assets are formally managed.**

- **Answer:** `governance`

---

### **Question 2:**
**A data professional at a bank uses metadata to track customer loan applications. They confirm the date and time applications were submitted. What type of metadata are they using?**

- **Answer:** `Administrative`

---

### **Question 3:**
**Which of the following statements accurately describe primary and foreign keys in a relational database? Select all that apply.**

- **Answer:**
  - `Foreign keys are used to connect one table to another.`
  - `A primary key references a column in which each value is unique.`
  - `A table can only have one primary key, but it can have multiple foreign keys.`

---

### **Question 4:**
**A data analyst runs the following query. What do they want to retrieve from the database?**
```sql
SELECT *
FROM ArtDisplays 
WHERE Medium = 'sculpture';

Answer: All fields of the art displays of sculptures
Question 5:
A junior data professional prepares for an analysis project about a very broad and global topic. However, they will only have access to internal data. What are some potential limitations that they should be aware of? Select all that apply.

Answer:
It will be more difficult to confirm the reliability of the data.
The data may not fully represent the facts.
It may be difficult to gather data from multiple departments.
Question 6:
A data professional at a local zoo is sending an email to all donors who give at least $25 to the zoo each year. What spreadsheet tool will enable them to display only donors who meet that condition?

Answer: Filter the data to show only donors who have given more than $25 each year
Question 7:
A data analyst at a retail company uses SQL to explore the data in its customer database. They want to examine the order_date field in the CustomerPurchases table to understand when customers make purchases. What query should they write to return only this information?

Answer:
sql
Copy code
SELECT order_date
FROM CustomerPurchases;
Question 8:
Which SQL statement will return only green cars from the Color column of the Cars database table?

Answer:
sql
Copy code
SELECT *
FROM Cars
WHERE Color = 'Green';
Question 9:
What are the benefits of open data for the public? Select all that apply.

Answer:
Increased public participation and improved decision making.
Improved understanding of government spending and opportunities to contribute to public planning.
Question 10:
You are a database administrator for a hair salon that specializes in hair treatments and styling. The company is growing, and the number of customers the company needs to keep track of has increased. The limitations of the current database design have become more noticeable. There is a lot more repeated data, such as customer names, phone numbers, and email addresses. This redundancy is causing issues with data integrity and making queries slow. In the tables below, what are the primary keys?

Customers Table:

customer_id
first_name
last_name
phone_number
email_address
Services Table:

services_id

service_name

service_price

description

Answer: customer_id and services_id

