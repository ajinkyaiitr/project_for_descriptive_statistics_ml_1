# project_for_descriptive_statistics_ml_1

In this project, we shall import a new dataset about cars and try to observe some of the measures. Some of the tasks we shall perform are: calculating mean, median, variance, standard deviation, plotting histograms, density plots, box plots and drawing inferences .

Create a new notebook (Descriptive_Analysis.ipynb) by going to Files > New > Python 3 on CloudXLab. Please keep hold of this jupyter notebook to answer the questions that follow this exercise.

Import the relevant python packages (numpy, pandas, matplotlib).
Hint:

%matplotlib inline
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
Import 'mtcars' data from ggplot.

Hint: from ggplot import mtcars

Get the header data for 'mtcars' and store it in variable 'header_data'. Display the header data using print() command.

These are the columns present in mtcars dataset:

    name - Name of the car; 
mpg - Miles/(US) gallon; 
cyl - Number of cylinders; 
disp - Displacement (cu.in.); 
hp - Gross horsepower; 
drat - Rear axle ratio; 
wt - Weight (lb/1000); 
qsec - 1/4 mile time; 
vs - V/S; 
am - transmission (0 = automatic, 1 = manual); 
gear - Number of forward gears; 
carb - Number of carburetors;
Calculate the mean of each of the columns of mtcars.

Get the mean of each row (car) and store it in variable 'mtcarsMeanCarWise'.

Get the median of each column and store it in variable 'medianCarsFeatures'.

Plot the histograms for each of the columns in mtcars using hist() function with bin-size as 10.

Plot the density curves for each column of mtcars using 'for' loop and plot command.

Plot the correlation for the following attributes: mpg, disp, hp, wt, qsec. You can use the scatter_matrix command present in pandas.plotting library.

We use skewness as a measure of symmetry. If the skewness of is zero then the distribution represented is perfectly symmetric. If the skewness is negative, then the distribution is skewed to the left, while if the skew is positive then the distribution is skewed to the right. Hence, it can also be considered as a measure of normality since normal distributions are symmetric and hence have a zero skew. Calculate the skeweness of each column of 'mtcars' using mtcars.skew()

Use describe and quantile to calculate the Inter-Quantile spread of 'mpg' attribute of mtcars.

Plot the box plot for 'mpg' column of mtcars.

Calculate the mean, standard deviation and variance of the 'mpg' column

Extract cars with automatic transmission and cars with manual transmission into separate variables 'mtCarsAutomatic' and 'mtCarsManual' respectively.

Plot the box plot for 'mpg' (miles per gallons) for each of the subsets of cars grouped by transmission (automatic/ manual).

What can be observed from the box plot? Can you come up with similar box plots to observe how other variables might be significantly impacting Miles/(US) gallon? What are the variables we should track if we need to predict mpg (Miles/ (US) gallon) ?

Please refer the Jupyter notebook to answer the questions that follow this exercise.
