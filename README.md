# World_Weather_Analysis

## Overview

This project is designed to enable a travel agency, PlanMyTrip to recommend ideal hotels based on clients' weather preferences.

The process involves using the NumPy module to generate over 1,500 random latitudes and longitudes.
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

For Filtering and visualization of the data
- Filtered the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
- Found hotels from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
- Stored names of the hotels in a new DataFrame.
- Added pop-up markers to the map that display information about the city, current weather with maximum temperature, and a hotel in the city.

To Create a travel itinerary map
Used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations.
Created a marker layer map with a pop-up marker for each city on the itinerary.
