# Module 1 

### **Question 1:**
**A data professional at a finance company sorts spreadsheet data. They sort all data by ranking in the Financial Performance column, keeping together all data across rows. What spreadsheet tool are they using?**

- **Answer:** `Sort Sheet`

---

### **Question 2:**
**Fill in the blank: To filter for all items in the Products table that are currently in stock, a data professional uses the _____ clause in SQL.**

- **Answer:** `WHERE`

---

### **Question 3:**
**A data team needs data to build a model to predict ocean surface temperatures. They import data from several different sources into a single database in order to analyze and prepare it for modeling. What phase of analysis is the data team in?**

- **Answer:** `Organize data`

---

### **Question 4:**
**Which of the following statements accurately describe sorting and filtering? Select all that apply.**

- **Answer:**
  - `Sorting can be performed in both spreadsheets and SQL databases.`
  - `Filtering enables data professionals to view the data that is most important.`
  - `Sorting involves arranging data into a meaningful order.`

---

### **Question 5:**
**You’re a data analyst for a sports arena who wants to better understand their customers who attend soccer games. At every event, attendees are asked to fill out a survey. The sports arena keeps the responses in the data table CustomerSurveys. Which query should you use to examine only the data from customers who attended soccer games?**

- **Answer:** `SELECT * FROM CustomerSurveys WHERE event = 'soccer';`

---

### **Question 6:**
**Which query will return a list of all pickup trucks that have fewer than 10,000 miles, in order from the oldest to the most recent year produced?**

- **Answer:** `SELECT * FROM \`CarDealership\` WHERE Type = 'Pickup' AND Mileage < 10000 ORDER BY year_produced ASC`

---

### **Question 7:**
**A data professional in customer service is tasked with identifying customers who are at risk for taking their business to a competitor. In the analyze phase of the data analysis process, what activities might this involve? Select all that apply.**

- **Answer:**
  - `Request input from other customer service data professionals`
  - `Organize a dataset by customer and purchase history`
  - `Format the data to filter for low customer satisfaction scores`

---

### **Question 8:**
**Which function sorts a spreadsheet range between cells K1 and L80 in ascending order by the first column, Column K?**

- **Answer:** `=SORT(K1:L80, 1, TRUE)`

---

### **Question 9:**
**You’re a data analyst working with a team to analyze data. One of your team members shows you a spreadsheet they’ve sorted, but you notice that one of the columns doesn’t seem to be correctly associated with the rest of the dataset. On closer examination, you realize that only that column was sorted, instead of the entire sheet. How can you and your team member sort the entire sheet? Select all that apply.**

- **Answer:**
  - `The Sort range option`
  - `The Sort sheet option`

---

### **Question 10:**
**Which query will return song_title, artist_name, and album_title in alphabetical order by song_title?**

- **Answer:** `SELECT song_title, artist_name, album_title FROM music_db.songs ORDER BY song_title;`
