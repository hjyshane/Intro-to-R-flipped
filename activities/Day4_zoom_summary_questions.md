1. [Introduction to R and RStudio] If a command is not complete at the end of a line, R will give a different prompt, by default it is:
a. *
b. –
c. + (correct)
d. /

2. [R Syntax and Data Structure] Which R-object can contain many different types of elements inside it?
a. Vector
b. Functions
c. Matrix
d. Lists (correct)

3. [Data Wrangling: Subsetting Vectors and Factors] What will be the output of the following R code?
r <- 0:10
r[2]
a. 0
b. 1 (correct)
c. 2
d. 3

4. [Data Wrangling: Subsetting Vectors and Factors] We defined x <- c("a", "b", "c", "c", "d", "a"). Which of the following will NOT output the first four elements "a""b""c""c"?
a. x[c(1,2,3,4)]
b. x[-5,-6] (correct)
c. x[1:4]
d. x[-c(5:6)]

5. [Reordering and matching] What is the output of this line of code: 5 %in% c(1,2,9,5,3,6,7,4)?
a. TRUE (correct)
b. FALSE FALSE FALSE TRUE FALSE FALSE FALSE FALSE
c. 4
d. 5

6. [Reordering and matching] What is the output of this line of code: match(5, c(1,2,9,5,3,6,7,4))?
a. TRUE
b. 1
c. 4 (correct)
d. 5

7. [Plotting with the ggplot2 package] In our ggplot2 lesson, if we want all the data points to be color blue, while each genotype plotted with a different shape, what code shall we use?
a. ggplot(new_metadata) +
  geom_point(aes(x = age_in_days, y= samplemeans, color = "blue", shape=genotype)) 
b. ggplot(new_metadata) +
  geom_point(aes(x = age_in_days, y= samplemeans, color = "blue"), shape=genotype) 
c. ggplot(new_metadata) +
  geom_point(aes(x = age_in_days, y= samplemeans, shape=genotype), color = "blue") (correct)
d. ggplot(new_metadata) +
  geom_point(aes(x = age_in_days, y= samplemeans), color = "blue", shape=genotype)

8. [Tidyverse] Which of the following function extracts a subset of rows from a dataframe based on logical conditions?
a. rename
b. filter (correct)
c. select
d. subset

9. [Tidyverse] Which of the following function add new variables/columns through transforming existing variables?
a. mutate (correct)
b. add
c. append
d. arrange
