# Matplotlib Project - The Power of Plots

## Background

Working with a simulated data set from a pharmaceutical company, this project analyzes the outcomes of a 45-day study of a variety of drug regimens on a sample of 249 mice. Using Matplotlib, the project:

- Checks data for any mouse IDs with duplicate time points and removes any data associated with that mouse ID, using the cleaned data to complete the project.

- Generates a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

- Generates a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot to show the total number of measurements taken for each treatment regimen throughout the course of the study.

- Generates a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

- Calculates the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculates the quartiles and IQR to quantitatively determine if there are any potential outliers across all four treatment regimens.

- Generates a box and whisker plot of the final tumor volume for all four treatment regimens and highlights any potential outliers in the plot by changing their color and style.

- Selects a mouse that was treated with Capomulin and generates a line plot of tumor volume vs. time point for that mouse.

- Generates a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

- Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment and then plots the linear regression model on top of the previous scatter plot.

- Includes three observations that can be made from the data.

- - -
This assignment is from the University of Denver's Data Analytics Boot Camp. 
### Copyright

Trilogy Education Services © 2020. All Rights Reserved.
