# DSCI_410L_Research_Project

This is a project I did for my Data Science 410L Class at the University of Oregon. It is a research project analyzing the affect of temporal and weather variables affect CAHOOTS (local non-profit) call volume.

Here are the instruction walking you through the "Data Cleaning" Jupyter Notebook file:

The code is pretty easy to use. First, ensure that you have 3 data sets sourced from NOAA(Public), the EPA(Public), and CAHOOTS(Private), all as csv files, and saved in the same folder as the "Data Cleaning" file. 
After, just run the code cell in the written order, and you will end up with a "clean_data" csv file
This is done through code which reads in all the csv files, creates the CAHOOTS call volume per hour df, drops unecessary columns, standardizes the Datetime valued column in all df and then merges them on that datetime column (date & hour).

Here are the instruction walking you through the "Data Analysis" Jupyter Notebook file:

