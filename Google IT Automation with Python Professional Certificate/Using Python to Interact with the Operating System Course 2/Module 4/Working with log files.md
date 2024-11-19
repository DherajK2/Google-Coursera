# Working with log files


## Question 1:
**Which term describes a program that provides a text-based interface for typing commands?**

- **Answer**: A terminal

---

## Question 2:
**What is the primary purpose of the `sys` module in Python?**

- **Answer**: Provides functions and variables to interact with the Python interpreter and the runtime environment

---

## Question 3:
**In the lab’s Python script, what is the role of the `error_search` function in relation to processing log files with regular expressions (RegEx)?**

- **Answer**: To interactively receive an error type from the user and use RegEx to find corresponding logs

---

## Question 4:
**What is the role of `fishy.log` in the provided Python script for log file analysis?**

- **Answer**: It is the log file that is being analyzed for specific error patterns.

---

## Question 5:
**What is the step-by-step process of how errors are searched for and processed in the script within the lab?**

- **Answer**: Set the log_file variable, call the `error_search()` function with the log_file parameter to search for errors, and store the matching errors in the returned_errors list.

---

## Question 6:
**You are analyzing a log file. What would happen if you didn’t escape special characters in your regular expression?**

- **Answer**: The regular expression would match the literal character instead of the special meaning.

---

## Question 7:
**In the script's execution process described, what are the main functions called, and in what order?**

- **Answer**: `error_search()` and `file_output()` called in that order

---

## Question 8:
**Which of the following statements about log files is true? Select all that apply.**

- **Answers**: 
  - They can help in identifying and fixing issues.
  - They can be used to monitor system performance.
  - They can be programmed to record specific events.

---

## Question 9:
**You want to pull specific data from a log file. Which Python module should you use?**

- **Answer**: `re`

---

## Question 10:
**Apply what you’ve learned from this lab to answer this question. You are working on the `find_error.py` script to search for specific errors in the `fishy.log` file. If you need to find all instances of a network connection failure, which of the following steps would you take to modify the script accordingly?**

- **Answer**: Modify the user input line to specifically ask for "network connection failure" errors, then process `fishy.log`.
