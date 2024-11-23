# Module 3 challenge
1. **Question 1:**  
   **Which line of code converts the integer 7 to a string?**

   - **Answer:** `str(7)`

2. **Question 2:**  
   **Which line of code returns a copy of the string "HG91AB2" as "hg91ab2"?**

   - **Answer:** `print("HG91AB2".lower())`

3. **Question 3:**  
   **In the string "network", which character has an index of 1?**

   - **Answer:** `"e"`

4. **Question 4:**  
   **You need to take a slice from a device ID. Specifically, you must extract the characters with indices of 8, 9, and 10. Complete the Python code to take this slice and display it.**

   - **Answer:**
     ```python
     device_id = "u899v381w363"
     print(device_id[8:11])
     ```

   - The output will be: `"w36"`

5. **Question 5:**  
   **What is the output of the following code?**
   ```python
   list1  = [1, 2, 3] 
   list2 = ["a", "b", "c"]
   print(list1 + list2)

Answer: [1, 2, 3, "a", "b", "c"]


Question 6:
What is the output of the following code?

python
Copy code
approved_users = ["bmoreno", "elarson", "tshah", "eraab"]
print(approved_users[1])
Answer: "elarson"


Question 7:
Fill in the blank: A(n) _____ is a set of rules to solve a problem.

Answer: algorithm


Question 8:
Which of the following strings would Python return as matches to the regular expression of "\w+"? Select all that apply.

Answer:

"network"
"email123"
"9210"
"email@email.com" would not match, as it contains the @ symbol, which is not a word character (\w matches letters, numbers, and underscores).

Question 9:
What module do you need to import to use regular expressions in Python?

Answer: re


Question 10:
Which method adds input to the end of a list?

Answer: .append()
