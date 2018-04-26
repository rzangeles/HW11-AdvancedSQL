Surf's Up-AdvancedSQL

Project Scope:

The project scope is to utilize climate data to assist with trip planning.  The data sources are station climate readings.  The end result is to provide climate analysis API for the communit to use.

Libraries Used:

1.  Sqlalchemy
2.  Pandas
3.  Numpy
4.  Matplotlib
5.  DateTime
6.  OS
7.  Flask


Step 1:  Data Engineering

Inspect the data sources and remove the NA values.  Save the cleaned CSV files with the prefix "clean."

File Name - data_engineering_final.ipynb

Step 2:  Database Engineering

1.  Import the clean CSV files
2.  Create declarative bases for Measurement and Station
3.  Establish connection to theh hawaii.sqlite database
4.  Add data to the hawaii.sqlite database (both stations and measurements)

File Name - database_engineering_final.ipynb

Step 3:  Climate Analysis and Exploration

1.  Create a database connection
2.  Start a session
3.  Perform queries and store in tables
4.  Save queries to data frames
5.  Plot the data

File Name - climate_analysis_final.ipynb

A.  Precipitation Anaysis - Precipitation.png

B.  Station Analysis - Histogram_plot.png

C.  Temperature Analysis - TempAvg.png