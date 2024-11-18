# Module 2 graded assessment


### 1. **Question 1**  
**What is a characteristic of a CSV file?**

- **Answer:**  
  - Data in each row is separated by a special character.

---

### 2. **Question 2**  
**What is a primary benefit of using open() to work with files in Python, as opposed to using with open()?**

- **Answer:**  
  - Once opened, you can use the file elsewhere in your code without having to reopen it.

---

### 3. **Question 3**  
**Which of the following statements is TRUE about absolute paths in a file system?**

- **Answer:**  
  - They provide a full path to the resource, starting from the root directory.

---

### 4. **Question 4**  
**Why is the os module useful when working in Python?**

- **Answer:**  
  - It allows you to interact with the operating system using Python, regardless of whether that operating system is Windows, Mac, Linux, or something else.

---

### 5. **Question 5**  
**You have a file called names.txt in your current working directory. The file contains a single line: Richard Acosta. Then, you run the following code:**  
```python
with open('names.txt', 'w') as file:
    file.write('Matteo Rossi')


What does the new file contain?

Answer:
Matteo Rossi


6. Question 6
Imagine you're reading a text file line by line in Python. The file contains data like names, but each name has an extra blank line appended after it. Which of the following modifications to the code would most effectively remove these extra blank lines while keeping the names intact?

Answer:
Add an if statement within the loop to only print lines that are not empty.


7. Question 7
On Linux systems, which of the following commands is used to create a new directory?

Answer:
mkdir directory_name


8. Question 8
What is the primary function of the line reader = csv.DictReader(software.csv)?

Answer:
It creates a dictionary reader object to iterate over rows in the software.csv file, treating each row as a dictionary.


9. Question 9
Why is it useful to verify whether a file exists? Select all that apply.

Answer:
It helps prevent accidentally overwriting an existing file.
It helps avoid getting a “file not found” error if you try to operate on a non-existent file.


10. Question 10
Imagine you have a Python function that processes data from a file and builds a list named employee_list. The code snippet you're provided includes the line return employee_list. What does this line accomplish within the function?

Answer:
It makes the information contained in employee_list available outside the function, allowing other parts of your code to access the processed data.
