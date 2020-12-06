# Tasks 2020

### Institution: Galway-Mayo Institute of Technology - GMIT
### Course: Higher Diploma in Data Analytics
### Module: Machine Learning and Statistics
### Author: Alexander Pepe

      This is an activity to keep our previous knowledge up the date and improve our skill in Machine Learning and Statistic. 

### First Task ### 

Write a Python function called sqrt2 that calculates and
prints to the screen the square root of 2 to 100 decimal places.


### Second Task ### 

The Chi-squared test for independence is a statistical
hypothesis test like a t-test. It is used to analyse whether two categorical variables
are independent. The Wikipedia article gives the table below as an example,
stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats
to verify this value and calculate the associated p value. You should include a short
note with references justifying your analysis in a markdown cell.

The answer is in Task_2.ipynb

### Third Task ###

The standard deviation of an array of numbers x is
calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) .
However, Microsoft Excel has two different versions of the standard deviation
calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above
calculation but in the STDEV.S calculation the division is by len(x)-1 rather
than len(x) . Research these Excel functions, writing a note in a Markdown cell
about the difference between them. Then use numpy to perform a simulation
demonstrating that the STDEV.S calculation is a better estimate for the standard
deviation of a population when performed on a sample. Note that part of this task
is to figure out the terminology in the previous sentence.


### Fourth Task ###

Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.
