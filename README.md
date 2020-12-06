# World_Weather_Analysis

## Project Overview
The project was carried out for a hypothetical travel company, Plan My Trip, where weather data was collected across cities worldwide which was analyzed then visualized in order to recommend ideal hotels based on clients' weather preferences. Using the Open Weather Map API, the current weather data was requested from each unique city on the list. Then JSON data was parsed from the API request and created a database to include the name of the city, the country, the coordinates (through latitude and longitude), and certain weather data types (such as maximum temperature, humidity, cloudiness, wind speed, and weather description). Exploratory analysis was performed to determine correlations between the coordinates and the various types of weather data. Through the use of Google's Maps, Places API, and its Search Nearby feature, a series of heatmaps with pop-up markers was created to display information on specific cities based on a customer's travel preference. Finally, out of all the potential travel destinations four cities cities were chosen to create an itinerary. With the Google Maps Directions API, travel destinations were plotted on a map with marker indicators to show the driving routes between the four cities.

Below are the snapshots of the customer's vacation search and travel itinerary using the Plan My Trip app.

## Potential travel destinations and nearby hotels
![WeatherPy_vacation_map](https://github.com/Lora-Borja/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)


## The Coastal South African Adventure
![WeatherPy_travel_map](https://github.com/Lora-Borja/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)


![WeatherPy_travel_map_markers](https://github.com/Lora-Borja/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

