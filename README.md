# World_Weather_Analysis

## Data Visualization Week 6 Challenge

### Objectives

The goals for this challenge:

* Use nested try-except blocks.
* Use Pandas methods and attributes on a DataFrame or Series.
* Create a new DataFrame from a new API search with new weather parameters.
* Filter DataFrames based on input and nested decision statements, and logical expressions.
* Create pop-up markers on a Google map from a filtered DataFrame.
* Add a directions layer on a Google map between cities in the filtered DataFrame.

### Resources

* Python 3.7
* Jupyter Notebook
* OpenWeather API
* Google Cloud Platform API

### Results

Used Pandas dataframes, API calls, and json requests to create and filter dataframes of weather conditions, temps, and rain/snowfall.  These dataframes were used to create gmaps with markers and pop-ups that displayed the cities, hotel, and weather info at a snapshot in time (at the time the code is run).  CSV files were also created and stored.  

The code could be refined to validate the user's input to ensure correct datatypes and valid entries are made.  It could also narrow down the list of 4 cities inside the code rather than the programmer choosing the cities.  However, this was outside of the scope of this project.  