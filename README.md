![](Images/equatorsign.png)
# What is the Weather Like? :snake:

#### This Python script visualizes the weather of 500+ cities around the world of varying distances from the equator. 

## Part 1 - WeatherPy
#### This script creates a series of scatter plots to showcase the following relationships:
 - Temperature (F) vs. Latitude
 - Humidity (%) vs. Latitude
 - Cloudiness (%) vs. Latitude
 - Wind Speed (mph) vs. Latitude
 - After each plot, add a sentence or two explaining what the code is analyzing.

Next linear regression is performed on each relationship, separating the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). After each pair of plots, I will describe any relationships and other analysis found:
 - Northern Hemisphere - Temperature (F) vs. Latitude
 - Southern Hemisphere - Temperature (F) vs. Latitude
 - Northern Hemisphere - Humidity (%) vs. Latitude
 - Southern Hemisphere - Humidity (%) vs. Latitude
 - Northern Hemisphere - Cloudiness (%) vs. Latitude
 - Southern Hemisphere - Cloudiness (%) vs. Latitude
 - Northern Hemisphere - Wind Speed (mph) vs. Latitude
 - Southern Hemisphere - Wind Speed (mph) vs. Latitude

## Part 2 - VacationPy
#### This script involves working with weather data to plan future vacations using jupyter-gmaps and the Google Places API to search for hotels within 5000 meters and plot markers on a heatmap by doing the following:
 - Create a heat map that displays the humidity for every city from Part I
 - Narrow down the DataFrame to find your ideal weather condition
    - A max temperature lower than 80 degrees but higher than 70.
    - Wind speed less than 10 mph.
    - Zero cloudiness.
    - Drop any rows that don't contain all three conditions. 
 - Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
 - Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
