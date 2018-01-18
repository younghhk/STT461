###  HW1: Data manipulation

**Due: Friday, 26, in class**.

**Problem 1**

1.a There is an exciting data set included with the default `R` installation, but I can't remember what it's called. I think it has something to do with chicken. Find it by keyword search and load it into your workspace.
  
1.b Add a new column that gives the weight in kilograms, rather than grams. Make sure the
column has a descriptive name, kg.  
	
1.c Create 2 weight categories, *light* and *heavy*.  If weight is less than 150g, assign *light*.  Otherwise,  *heavy*.  Make sure the
column has a descriptive name, *weightcat*.

1.d Compute the minimum, maximum, mean and median of weight.

1.e Make a box-and-whiskers plot showing the distribution of chicken weight according to feed type. Make sure to label the axes appropriately.


**Problem 2**

2.a Create a numeric vector $x$ of length 60 that ranges from $-\pi$ to $\pi$.

2.b Create a numeric vector $y$ that is the sine of $x$ (in radians).

2.c Create a vector $z$ that is the cosine of $x$.

2.d Plot $y$ vs. $x$ as a series of points joined by lines. 

2.e On the same graph, add red-colored points for $z$ vs. $x$. 

2.f Add a legend.


**Problem 3**

3.a Download the *crab* spreadsheet to your local machine. Now, import the spreadsheet as a data frame into your `R`
workspace, naming the resulting object *crab_dat*. Briefly inspect the data.
 
3.b Confirm that the last three columns are useless, and remove them. Convert the first column to character
type. 

3.c Change the name of the fifth column to *weight1*. Create *weight2* column which has two weight categories.
 if weight is less than the median of *weight1*, assign *light*,  otherwise *heavy*.

3.d Now that you have cleaned up the *clin* object, save it for later use, both as an R object (`clin.rda`)
and also as a CSV file (`clin.csv`).

[Home](https://github.com/younghhk/STT461)
