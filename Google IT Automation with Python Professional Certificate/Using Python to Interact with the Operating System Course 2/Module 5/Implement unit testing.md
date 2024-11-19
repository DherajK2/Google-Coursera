# Implement unit testing


## Question 1:
**What output told you whether a test passed?**

- **Answer**: OK

---

## Question 2:
**When you looked for the script `emails.py` in the scripts directory, what command did you use to navigate to the scripts directory?**

- **Answer**: `cd ~/scripts`

---

## Question 3:
**Which of the following terms describes an individual unit of testing that checks for a specific response to a particular set of inputs?**

- **Answer**: Test case

---

## Question 4:
**If a try clause is executed and an exception occurs, but there is no match for the exception in any of the except clauses, what happens?**

- **Answer**: It's an unhandled exception and the execution stops with an error message.

---

## Question 5:
**Before software can ship, you have been asked to test the software. What specifically should you be testing for?**

- **Answer**: To make sure the software meets the specified requirements

---

## Question 6:
**When referring to unit testing, what are “classes”?**

- **Answer**: Classes bundle data and functionality together.

---

## Question 7:
**The following code will either return an email address for an employee or an error message if there is no employee matching the name entered. What would the error message be?**

```python
if email_dict.get(fullname.lower()):
    return email_dict.get(fullname.lower())
else:
    return "No email"

- **Answer**: “No email”

## Question 8:
**Which of the following is the correct order of blocks in a try/except construct?**

- **Answer**: try, except, finally, raise.


## Question 9:
**The following portion of code will return an error message if a user fails to enter the full name of the employee for a search. What will the error message be?**


```python
def find_email(argv):
 """ Return an email address based on the username given."""
 # Create the username based on the command line input.
 try:
   fullname = str(argv[1] + " " + argv[2])
   # Preprocess the data
   email_dict = populate_dictionary('/home/<username>/data/user_emails.csv')
   # Find and print the email
   return email_dict.get(fullname.lower())
 except IndexError:


- **Answer**: Missing name


## Question 10:
**When writing a try/except clause, how many except clauses can be included?**


- **Answer**: As many except clauses are needed to specify handlers for different exceptions.
