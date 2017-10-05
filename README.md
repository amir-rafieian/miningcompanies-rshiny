#Mining Companies Internal Value

##Introduction
Mining Companies have different mining plots which are graded from 1 to 3 (Grade 1 is the most expensive). The amount and quality of
plots in possession of the mining company are the strong indicator of the internal value of the company. different investors
with different strategies have different opinions of the weights of the grades, one may think level 1 is 10 times more valuable than 
grade 3, others may think grade 1 is only 5 times as valuable. In this R-shiny app, you can specify the weights for each grade. these weights
will then multiplies by the amount of plots and visualized against the Market Capitalization in the scatter plots. This way
we can compare the current value of the company. 

## Purpose
The main aim of this project is to examine  different elements of R shiny:
- Navbar
- Using Icons
- Using slider 
- Render plot using ggplot library to visualize calculated data from sliders
- Using brush to select data points on the graph and display the related entries from dataset 
- Format the columns in datatable
- download data from data table as csv and download plot as png file

##Disclaimer
The dataset in this project is a dummy data and symbols have to relation to the real mining companies