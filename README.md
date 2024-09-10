# NBA-Player-Attributes-Analysis
Here’s a structured README content for your NBA Player Analysis project, which you can use for your GitHub repository.

# Project Overview
The NBA Player Analysis project focuses on analyzing physical characteristics such as height, weight, wingspan, agility, and vertical jump of NBA players to determine how these metrics influence their draft position and potential success in the league.

Dataset: Contains 403 NBA players’ physical attributes from the years 2009 to 2017.
Goal: To provide insights into which physical attributes are critical for success in the NBA draft.
Dashboard: The interactive dashboard visualizes player data to help scouts and analysts make data-driven decisions.

# Data Cleaning & Preparation
Steps Involved:
Missing Values Handling:

Columns like Bench, Sprint, and Agility had missing values, which were filled using the average values.
Formula used: =IF(ISBLANK(Q2), ROUND(AVERAGE($Q$2:$Q$518), 0), Q2)
Power Query in Power BI:

Null values were filtered out during data loading and transformations were applied to ensure clean, usable data.
Data Transformation:

Columns like height and weight were categorized into ranges using the SWITCH() function in DAX.

# Tools & Technologies

->Power BI: Used for building interactive dashboards and generating insights.<br>
->DAX (Data Analysis Expressions): Used for calculating averages, measures, and creating KPIs.<br>
->Excel: Utilized for initial data cleaning and handling missing values.<br>
->SQL: (Optional, if you ran any queries to handle data before importing to Power BI).
# DataSet
<a href="https://github.com/Jai-sanjai/Data-Analysis-Dashboard/blob/main/nba_draft_combine_all_years.csv">Dataset</a>
# Dashboard
<a href="https://github.com/Jai-sanjai/Data-Analysis-Dashboard/blob/main/task_1.png"> Dashboard</a><br>
![task_1](https://github.com/user-attachments/assets/533083af-cfe1-4848-993e-63efb003d160)




