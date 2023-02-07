# Ontario-Gas-Price-Analysis---Data-Visulization-

Regular Unleaded Gasoline Price Analysis

This project is an analysis of the Regular Unleaded Gasoline prices in different cities from 1991 to 2023. 
The data is stored in a CSV file (fueltypesall1991-2023.csv) and is loaded into a Pandas dataframe for manipulation and analysis.

Requirements

This project requires the following packages to be installed: pandas, matplotlib, numpy
You can install these packages using the following command: pip install pandas matplotlib numpy


Analysis

The code in fuelpriceanalysis.py performs the following analysis on the Regular Unleaded Gasoline price data:

Subsets the dataframe to only include columns B-R and rows 0-1726
Calculates the mean of each city (column) in the subsetted dataframe
Plots a bar graph of the average prices of each city
Plots a histogram of the Regular Unleaded Gasoline price in Ottawa for 2022
Plots the ECDF (empirical cumulative distribution function) of the Regular Unleaded Gasoline price in Ottawa for 2022

Running the Analysis


To run the analysis, simply run the following command in your terminal:

python fuelpriceanalysis.py

This will produce the three plots described above, showing the results of the analysis.
