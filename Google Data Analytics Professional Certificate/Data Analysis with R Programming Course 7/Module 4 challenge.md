# Module 4 challenge

### Question 1:
**Which of the following statements about ggplot is true?**

- **Answer:** `ggplot allows analysts to create different types of plots.`

---

### Question 2:
**Which ggplot function is used to define the mappings of variables to visual representations of data?**

- **Answer:** `aes()`

---

### Question 3:
**A data analyst creates a plot using the following code chunk:**

```r
ggplot(data = penguins) + 
   geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g))


Which of the following represents a function in the code chunk? Select all that apply.

Answer:
The aes function
The geom_point function
The ggplot function
Question 4:
A data analyst uses the aes() function to define the connection between their data and the plots in their visualization. What argument is used to refer to matching up a specific variable in your dataset with a specific aesthetic?

Answer: Mapping
Question 5:
A data analyst creates a scatterplot with many data points. The analyst wants to make some points on the plot more transparent than others. What aesthetic should the analyst use?

Answer: Alpha
Question 6:
You are working with the penguins dataset. You create a scatterplot with the following code chunk:

r
Copy code
ggplot(data = penguins) +
    geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g))
You want to highlight the different penguin species on your plot. Add a code chunk to the second line of code to map the aesthetic shape to the variable species.

r
Copy code
geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, shape = species))
Which penguin species does your visualization display?

Answer: Adelie, Chinstrap, Gentoo
Question 7:
A data analyst creates a plot with the following code chunk:

r
Copy code
ggplot(data = penguins) + 
    geom_jitter(mapping = aes(x = flipper_length_mm, y = body_mass_g))
What does the geom_jitter() function do to the points in the plot?

Answer: Adds a small amount of random noise to each point in the plot
Question 8:
You are working with the diamonds dataset. You create a bar chart with the following code:

r
Copy code
ggplot(data = diamonds) +
    geom_bar(mapping = aes(x = color, fill = cut)) +
You want to use the facet_wrap() function to display subsets of your data. Add the code chunk that lets you facet your plot based on the variable cut.

r
Copy code
facet_wrap(~ cut)
How many subplots does your visualization show?

Answer: 5
Question 9:
A data analyst wants to add a large piece of text above the grid area that clearly defines the purpose of a plot. Which ggplot function can they use to achieve this?

Answer: labs()
Question 10:
In R studio, what default options does the Export functionality of the Plots tab give for exporting plots?

Answer: Image
