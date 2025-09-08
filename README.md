Chicago Data Analysis
This project utilizes a SQLite database file, FinalDb.db, containing three tables with data related to the city of Chicago. The primary goal of this project is to analyze and visualize the relationships between crime, public school performance, and socioeconomic census data.

Database Schema
The database file contains the following tables:

CHICAGO_CRIME_DATA: Contains detailed information on reported crimes, including crime type, location, date, and arrest status.

CHICAGO_PUBLIC_SCHOOLS: Provides data on Chicago Public Schools, such as school names, addresses, performance scores, and student demographics.

CENSUS_DATA: Includes socioeconomic data for Chicago community areas, such as per capita income and hardship index.

Key Features
Data Integration: The project connects and queries data from all three tables to find correlations and insights.

Analysis of Trends: The analysis focuses on identifying patterns in crime rates across different community areas and correlating them with school performance and socioeconomic factors.

Data Visualization: The results can be used to generate visualizations (e.g., charts, maps) that highlight key findings.

Potential Analysis Questions
How does the HARDSHIP_INDEX of a community area correlate with its crime rates?

Is there a relationship between a school's SAFETY_SCORE and the crime rates in its surrounding area?

How does the PER_CAPITA_INCOME of a community area affect the performance scores of its public schools?

Getting Started
To use this data, you'll need a tool that can interact with SQLite databases, such as Python with the sqlite3 library, or a dedicated database management tool. You can then write SQL queries to extract and analyze the data based on the tables and columns described above.
