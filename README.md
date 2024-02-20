# Project Brief: Skopje Air Pollution

### Introduction
The city of Skopje faces significant challenges with air pollution, particularly during winter months. Key pollutants include CO, NO2, ozone, and various particulate matter.

Monitoring stations have been strategically placed throughout the city to measure pollutant concentrations.

### Objective
This project aims to analyze air pollution data in Skopje from January 2012 to December 2016. The dataset, compiled from monitoring stations, covers pollutants such as CO, NO2, O3, PM10, and PM25.

### Approach
Data Import and Review:

Import data from CSV files (CO.csv, NO2.csv, O3.csv, PM10.csv, PM25.csv) into separate Pandas dataframes.
Review dataframes to check data types and structure.
Data Cleaning and Restructuring:

Drop irrelevant columns (e.g., mobile monitoring station data).
Rename columns and create additional time and date columns.
Add a column indicating pollutant type to each dataframe and concatenate them.


### Analysis Questions:

a. Question 1: Identify locations with the highest average pollution for each pollutant.
b. Question 2: Determine the time stamps of maximum pollution for each location, annually. Identify peak pollution periods in Skopje.
c. Question 3: Find the months with the highest average pollution for each pollutant.
d. Question 4: Analyze the average pollution levels across locations for each hour of the day.
e. Question 5: Plot the average daily pollution across locations over time for each pollutant.
f. Question 6: Determine the number of days each year where the average PM10 pollution exceeds the moderate range.
g. Question 7: Calculate the number of days each year where PM10 pollution at least one location exceeds the moderate range.
h. Question 8: Create a bar plot showing the average number of days per year with PM10 pollution exceeding the moderate range at least one location.

### Deliverables
Analytical insights and visualizations addressing each question.
A final report summarizing findings and recommendations.
Codebase documenting data processing and analysis steps.

### Stakeholders
Environmental authorities in Skopje.
Local community members affected by air pollution.
Policy makers and government officials.
