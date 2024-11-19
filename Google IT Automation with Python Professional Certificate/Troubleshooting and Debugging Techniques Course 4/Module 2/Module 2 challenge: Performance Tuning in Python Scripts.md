# Module 2 challenge: Performance Tuning in Python Scripts

## Question 1:
**What is the primary reason the backup script is taking over 20 hours to complete its operation?**

- **Answer**: The script is I/O-bound.

---

## Question 2:
**What makes rsync (remote sync) distinct from other file transfer methods?**

- **Answer**: rsync uses the delta transfer algorithm, meaning it transfers only the differences between source and destination files.

---

## Question 3:
**In the assessment, 904123904 bytes were written to disk. You found this result using the ______________ function.**

- **Answer**: psutil.disk_io_counters()

---

## Question 4:
**In this example, how was the backup script improved to reduce the backup time significantly?**

- **Answer**: By utilizing multiprocessing

---

## Question 5:
**In the activity, what was the psutil python3 module used for?**

- **Answer**: Checking CPU usage

---

## Question 6:
**What is the following Python script used for?**
```python
import psutil
psutil.cpu_percent()


Answer: CPU utilization
Question 7:
What is the purpose of the Pool class in the multiprocessing Python module as used in the multisync.py script?

Answer: To manage a pool of worker processes
Question 8:
Which of the following are options for the rsync command? Select all that apply.

Answer:
-z
-v
-a
Question 9:
If you want to synchronize files from the directory /home/user/docs to /backup/docs with verbose output, which of the following rsync commands would you use?

Answer: rsync -v /home/user/docs /backup/docs
Question 10:
Which of the following statements best describes the primary purpose of the multiprocessing module in Python?

Answer: It provides support for parallel execution of code using multiple CPU cores.
