# matplotlib-challenge
## Module 5 Challenge

In this project I used Pandas and Jupyter Notebook to analyze a pharmaceutical drug used in an animal study in comparison to other treatment regimens. Click [here](https://github.com/isabellajade/matplotlib-challenge/blob/main/Pymaceuticals/pymaceuticals_starter.ipynb) to view the code.

## Summary of Study Results

- Capomulin and Ramicane are similar in stats (see summary stats table)
- Capomulin and Ramicane had similar amt of timepoints tested (C230, R228)
- 51% male mice tested, 49% female
- Capomulin and Ramicane final tumor vol similar
- Infubinol and Ceftamin final tumor vol much higher
- Capomulin tumor vol v weight positive correlation (more weight = bigger tumor)
- r-squared is 0.71


## Summary Statistics Table
Included in this table are the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

![Summary Statistics Table](Pymaceuticals/images/SummaryStats.PNG)

## Bar Chart
Displayed in this bar chart is the total number of time points tested for all mice for each drug regimen throughout the study.

![Bar Chart](Pymaceuticals/images/BarChart.PNG)

## Pie Chart
This pie chart represents the distribution of female versus male mice over the study for all drug regimens. 

![Pie Chart](Pymaceuticals/images/PieChart.PNG)

## Box Plot
This box plot displays the distribution of the final tumor volume for all of the mice within treatment groups Capomulin, Ramicane, Infubinol, and Ceftamin. Potential outliers are represented by the red dot.

![Box Plot](Pymaceuticals/images/BoxPlot.PNG)

## Line Plot
Below is a line chart representing the tumor volume vs time point for a randomly selected mouse treated with Capomulin.

![Line Plot](Pymaceuticals/images/LinePlot.PNG)

## Scatter Plot
This scatter plot displays the tumor volume vs mouse weight for mice treated with the Capomulin treatment regimen.

![Scatter Plot](Pymaceuticals/images/ScatterPlot.PNG)

## Correlation and Regression
Below is the calculated correlation coefficient and linear regression model for mouse weight and average tumor volume for the Capomulin treatment regimen.

![Correlation and Regression](Pymaceuticals/images/CorrAndRegress.PNG)