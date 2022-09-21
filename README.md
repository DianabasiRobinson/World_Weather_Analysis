# World_Weather_Analysis

## Overview

This project is designed to enable a travel agency, PlanMyTrip to recommend ideal hotels based on clients' weather preferences.

The process involves;
1. Using the NumPy module to generate over 1,500 random latitudes and longitudes.
Getting the nearest city to the latitudes and longitudes by using citipy module to compute the list.
Current weather data from each unique city in the list was retrieved by using OpenWeatherMap API request.
Parse the JSON data from the API request.
The enlisted data were collected from th JSON file and added to a dataframe.
- City, country, and date
- Latitude and longitude
- Maximum temperature
- Humidity
- Cloudiness
- Wind speed
2. Exploratory Analysis with Visualization
Create scatter plots of the weather data for the following comparisons:
Latitude versus temperature
Latitude versus humidity
Latitude versus cloudiness
Latitude versus wind speed
Determine the correlations for the following weather data:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
Create a series of heatmaps using the Google Maps and Places API that showcases the following:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed

3. Visualize Travel Data
Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
Create a heatmap for the new DataFrame.
Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
Store the name of the first hotel in the DataFrame.
Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.
