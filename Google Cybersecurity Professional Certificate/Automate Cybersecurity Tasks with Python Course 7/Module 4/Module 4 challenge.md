# Module 4 challenge


1. **Question 1:**  
   **What is debugging?**

   - **Answer:**  
     The practice of identifying and fixing errors in code.

2. **Question 2:**  
   **The purpose of the following code is to print the numbers from 0 to 9. Run this code, analyze its output, and then debug it.**  
   (If you want to undo your changes to the code, you can click the Reset button.)

   ```python
   count = 0
   while count < 10
       print("number", count)
       count = count + 1

- **Answer:**  
  Add a missing colon (:) after while count < 10.

3. **Question 3:**
   **The purpose of this code is to greet a user by their first name when they log in. Run this code, analyze its output, and debug it.
(If you want to undo your changes to the code, you can click the Reset button.)
How can you fix the error?**

'''python
  def welcome_user(name):
    print("Welcome", name)
first_name = "Charley"
welcome_user("first_name")


- **Answer:**  
 Remove the quotation marks around "first_name" when calling welcome_user() so that it uses the variable first_name instead of the string "first_name".

**Question 4:**  
**You did not define a function before calling it. What type of error is this?**

- **Answer:**  
  Syntax error

**Question 5:**  
**Why might you use print statements when debugging code?**

- **Answer:**  
  To identify which sections of the code are working properly

**Question 6:**  
**What does the following code do?**
  '''python
    with open("logs.txt", "r") as file:

- **Answer:**  
t opens a file called "logs.txt" in read mode and stores it in a variable called file.


**Question 7:**  
**The `logins` variable is a string containing 20 device IDs. The device IDs are separated by spaces. In order to pass it into a function that checks the login count of each device, the string should be divided into a list of separate IDs. How do you convert this string into a list and store it in a `device_ids` variable?**

- **Answer:**  
  `device_ids = logins.split()`

---

**Question 8:**  
**What is parsing?**

- **Answer:**  
  The process of converting data into a more readable format

---

**Question 9:**  
**After you’ve opened a log file as `file`, which line of code will help you read the file into a variable called `text`?**

- **Answer:**  
  `text = file.read()`

---

**Question 10:**  
**You want to check for unusual login activity. Specifically, you want to read a log file that contains information on each login attempt, including whether it failed or was successful. You should then parse the data into a `logins` list, and then you should separate all failed log entries into a separate `failed_logins` list. If you want to automate this through Python, what would be part of your code? Select three answers.**

- **Answer:**  
  - A for loop to iterate through all items in the `logins` list  
  - An if statement to check if a login attempt failed




