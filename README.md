# World Weather Analysis
----
## Purpose
The purpose of this analysis is to create a vacation map that allows users to apply weather criteria to identify potential travel destinations. By utilizing [geoapify](https://www.geoapify.com/), we also provide the user with recommended ideal hotels within there preferred travel destinations.
___

## Overview
In order to create the vacation map, we generated a list of 2,000 random latitudes and longitudes. With the coordinates, we retrieved and compiled a list of the nearest cities using the citipy module. Then, we used the [OpenWeatherMap](https://openweathermap.org/) API to request the current weather data from each unique city on the list. The resulting map provides users with descriptions of the destinations found on our list, including: hotel name, city, country, and current weather.
