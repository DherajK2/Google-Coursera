# Module 3 challenge

### Question 1:
**What scenarios would prevent you from being able to use a tibble?**

- **Answer:** `You need to create row names`

---

### Question 2:
**A data analyst is working with a large data frame. It contains so many columns that they don’t all fit on the screen at once. The analyst wants a quick list of all of the column names to get a better idea of what is in their data. What function should they use?**

- **Answer:** `colnames()`

---

### Question 3:
**You are working with the ToothGrowth dataset. You want to use the select() function to view all columns except the supp column. Write the code chunk that will give you this view.**

- **Answer:** `select(-supp)`

**How many columns does the resulting data frame contain?**

- **Answer:** `2`

---

### Question 4:
**You have a data frame named employees with a column named last_name. What will the name of the employees column be in the results of the function rename_with(employees, toupper)?**

- **Answer:** `LAST_NAME`

---

### Question 5:
**A data analyst is working with the penguins dataset. The variable island represents the island on which the sample was collected. The analyst wants to create a data frame that excludes records from the island named “Torgersen”. What code chunk will allow them to create this data frame?**

- **Answer:** `penguins %>% filter(island != "Torgersen")`

---

### Question 6:
**You are working with the penguins dataset. You want to use the summarize() and max() functions to find the maximum value for the variable flipper_length_mm. At this point, the following code has already been written into your script:**

```r
penguins %>% 
  drop_na() %>% 
  group_by(species) %>%


Answer: summarize(max_flipper_length = max(flipper_length_mm))
What is the maximum flipper length in mm for the Gentoo species?

Answer: 231
Question 7:
A data analyst is working with a data frame called zoo_records. They want to create a new column named is_large_animal that signifies if an animal has a weight of more than 199 kilograms. What code chunk lets the analyst create the is_large_animal column?

Answer: zoo_records %>% mutate(is_large_animal = weight > 199)
Question 8:
A data analyst is working with a data frame named stores. It has separate columns for city (city) and state (state). The analyst wants to combine the two columns into a single column named location, with the city and state separated by a comma. What code chunk lets the analyst create the location column?

Answer: unite(stores, "location", city, state, sep=",")
Question 9:
In R, which statistical measure can help you understand the spread of values in a dataset and describe how far each value is from the mean?

Answer: Standard deviation
Question 10:
A data analyst wants to find out how much the predicted outcome and the actual outcome of their data model differ. What function can they use to quickly measure this?

Answer: bias()
