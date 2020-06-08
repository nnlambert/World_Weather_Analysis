# Weather Analysis
For the new modifications to the PlanMyTrip app, you are asked to add more data to the database, or cities DataFrame, so that customers know the weather in the cities when they click on a pop-up marker. You’ll also need to add the amount of rainfall or snowfall within the last three hours so that customers can filter the DataFrame using input statements based on the temperature range and whether or not it is raining or snowing. Finally, you’ll need to create a directions layer Google map that shows the directions between multiple cities for travel.

## Resources
- Data Source: https://openweathermap.org/api
- Data Output: Google Maps API
- Software: Python 3.6.1, Jupyter Notebook

## Part 1
## Get the Weather Description and Amount of Precipitation for Each City

Generate a list of 1500 random locations across the globe, and plotted city data using the citypy module. Using openweathermap, plotted:

1) Latitude and longitude
2) Maximum temperature
3) Percent humidity
4) Percent cloudiness
5) Wind speed
6) Weather description (e.g., clouds, fog, light rain, clear sky)
7) if present, amount of rainfall in the last 3 hours
8) if present, amount if snowfall in the last 3 hours

Data saved into weather_data/WeatherPy_chalenge.csv.

## Part 2
## Have Customers Narrow Their Travel Searches Based on Temperature and Precipitation
Import WeatherPy_challenge.csv and allow for user input; Tested using the following criteria
1) Minimum temperature: 70
2) Maximum temperature: 90
3) Rainining? No
4) Snowing? No

Created a map displayng locations of cities with hotels that meet the previous crtieria:
![Vacation Map Zoomed Out](/weather_images/WeatherPy_Vacation_Map.png)

Added Map Layer to display hotel and city info:
![Vacation Map with Markers](/weather_images/WeatherPy_Vacation_popup_map.png)

## Part 3
## Create a Travel Itinerary with a Corresponding Map

Select at least 4 Cities (in close proximity) and create a travel plan between them.

Selected 5 cities in Brazil:

1) "Salinopolis"
2) "Cururupu"
3) "Tutoia"
4) "Itarema"
5) "Aquiraz"

Created a Driving map to go between the 5 cities:
![Vacation Travel Driving Directions](/weather_images/WeatherPy_travel_map.png)

Created Map with Location Markers:
![Vacation Travel MArkers](/weather_images/WeatherPy_travel_map_markers.png)
