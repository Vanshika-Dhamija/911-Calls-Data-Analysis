# 911 Emergency Calls Data Analysis
# Project Overview
This project analyzes 911 emergency call data from Montgomery County, PA, to uncover patterns in emergency service usage.
By exploring when and why people call 911, this analysis provides actionable insights that can help optimize resource allocation, emergency preparedness, and traffic management.

# Dataset
Source: Kaggle - MontcoAlert 911 Calls Dataset (https://www.kaggle.com/datasets/mchirico/montcoalert)

Key Features of the Data:
Column Name	Description
lat	Latitude of the emergency
lng	Longitude of the emergency
desc	Description of the emergency call
zip	Zipcode of the location
title	Type and category of emergency
timeStamp	Date and time of the call
twp	Township of the incident
addr	Address of the incident
e	Dummy variable (always 1)

# Project Goals
Perform exploratory data analysis (EDA) on 911 call data.
Extract and visualize time-based trends (hour, day of week, month).
Identify the most common reasons for 911 calls: EMS, Fire, Traffic.
Use heatmaps and clustermaps to visualize peak call times.
Provide business insights and potential recommendations for emergency service management.

# Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
