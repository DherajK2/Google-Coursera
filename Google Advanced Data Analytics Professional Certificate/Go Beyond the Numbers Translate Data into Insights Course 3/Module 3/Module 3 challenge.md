# Module 3 challenge

### Question 1:
**Fill in the blank: N/A and NaN are terms used to describe _____ data.**

- **Answer:** `missing`

---

### Question 2:
**A data team for an investment banker works on a project related to interest rates. As they familiarize themselves with the datasets, they discover some data is missing. Which of the following strategies can help them solve this problem? Select all that apply.**

- **Answer:**
  - Derive new representative values based on available data.
  - Ask the owner of the data to fill in the missing values.
  - Add in the missing values by taking the average values from the existing data.

---

### Question 3:
**A data professional writes the following code:**

```python
df.merge(df_zip, how='left', 
    on=['date','center_point_geom'])


Which section of the code refers to the dataframe to be merged with df?

Answer: df_zip
Question 4:
What tasks could the pandas function pd.isnull() be used for? Select all that apply.

Answer:
To identify when a value is missing from a data frame.
Question 5:
Fill in the blank: Contextual outliers are normal data points under certain conditions but become _____ under most other conditions.

Answer: anomalies
Question 6:
A data team works for a stereo installation company. To gain insights into what products people are most likely to purchase in the coming year, they review categorical data about 20 of the most popular stereos. Rather than using brand names, they assign a different number to each stereo to make the data simpler to join. What does this scenario describe?

Answer: Label encoding
Question 7:
What type of data visualization shows the concentration of values between two data points by illustrating their magnitude with two colors?

Answer: Heat map
Question 8:
What does the pandas function pd.duplicated() return to indicate that a data value does not have a duplicate value within the same dataset?

Answer: False
Question 9:
Fill in the blank: The pandas function _____ enables data professionals to create a new dataframe with all duplicate rows removed.

Answer: drop_duplicates()
