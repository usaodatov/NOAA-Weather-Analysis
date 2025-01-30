NOAA Weather Analysis Project
This repository contains the analysis and cleaning of the NOAA Weather Data for JFK Airport, sourced from IBM Developer Data Asset Exchange.

Objective
The primary goal of this project was to clean, analyze, and visualize hourly weather data from JFK Airport, covering key weather parameters such as temperature, humidity, wind speed, and pressure. This analysis was conducted as part of the Data Science course on Coursera.

What has been done
Data Cleaning: Non-numeric values and empty fields were handled, replacing missing values with the closest valid entries.
Exploratory Data Analysis (EDA): Insights were drawn from weather patterns and data distributions.
Visualization: Key weather trends and relationships were visualized using matplotlib and seaborn libraries.
Feature Selection: Columns irrelevant for analysis were removed to keep the dataset simple.
Tools and Libraries Used:
Python: for all data cleaning and processing tasks.
Pandas: for handling data and performing calculations.
Matplotlib and Seaborn: for data visualization.
Data Source
The dataset is available under the CDLA-Sharing 1.0 license, which allows sharing and redistribution of the data. For more details, check the NOAA Weather Data Documentation.

File list:

jfk_weather.csv: the core dataset as obtained from NOAA.
jfk_weather_cleaned.csv: data cleaned for non-numeric data and redundant fields or empty fields. NULLs have been replaced with the closest previous value.
LICENSE.txt: a plaintext version of the CLDA-Sharing license that the dataset is licensed under. (Read License)
clean_data.py: the Python script used to clean the data.
Key Takeaways:
Handling missing data effectively using median and other imputation methods.
Data visualization techniques to highlight important patterns.
Exploratory analysis of key weather features to understand their relationship and behavior.
If you would like to download similar data for a different time range or U.S. geographic weather station location, follow the steps below:

Access the NOAA Local Climatological Data (LCD) tool.
Select a weather station using the Map Tool filters (e.g., "Country", "State", "Zip Code").
Choose a station and view its details.
Select "ADD TO CART" and proceed to checkout.
Choose the "LCD CSV" format and the date range.
Enter an email for NOAA to send you the download link.
Conclusion
This project was an excellent opportunity to work with real-world weather data, perform data cleaning, and apply various analytical techniques. It provided key learning about handling complex datasets, integrating open-source data, and using Python for data manipulation and visualization.
