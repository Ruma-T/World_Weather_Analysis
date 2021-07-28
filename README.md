# World_Weather_Analysis
## Project Overview
For PlanMyTrip app, we will retrieve weather data, create a customer travel destinations map, and create a travel itinerary map according to maximum and minimum temperature criteria to help the travelers.
# Plan
We will add all the dependencies.
We have to generate a set of 2,000 random latitudes and longitudes using Numpy Module, using the citipy module we’ll retrieve the nearest cities, and perform an API call with the OpenWeatherMap to request the current weather data from each unique city in the list. Then, we'll create a new DataFrame containing the updated weather data and write it in a csv file.

Next, we will read this csv file and run a code to ask the customer to add a minimum and maximum temperature value according to which we’ll create a new dataframe which contains all the cities that meet the temperature criteria. The cities customers want to travel, they will need to find a hotel to stay in the city. We’ll find the cities and hotel names within the mentioned temperature. For visualization, we'll create the gmap with the cities and hotel names.

Finally, we’ll create a travel itinerary map with the driving distance for four cities with starting with one and end at the same city including three stops.

# Results

![WeatherPy_travel_map](https://github.com/Ruma-T/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)



![WeatherPy_travel_map_markers](https://github.com/Ruma-T/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)



![WeatherPy_vacation_map](https://github.com/Ruma-T/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)
