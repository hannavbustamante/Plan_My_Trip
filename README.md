# World Weather Analysis
*An API World Weather Analysis*


## Project Overview

PlanMyTrip is an app that looks at the weather around the world and offers insights to travelers who want to book a trip. There are three folders that offer different levels of analysis: weather database, vacation search, and vacation itinerary.

### Weather Database
Using Open Weather Map API, this folder includes the weather data (Max Temp, Cloudiness, Wind Speed, Humidity, weather description) for over 500 cities across the world.

### Vacation Search
In this folder, we create a customer travel destinations map using the information from Weather Database and Google Maps API to find different travel destinations with a hotel at each location. Taking user input, places with a certain range of temperature are shown in the map. For example, this map shows places that have a temperature between 70 and 90 degrees fahrenheit.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/88729583/136297949-bf11c3ac-ac53-443a-ad58-208fca1df07f.PNG)

### Vacation Itinerary
In this folder, we use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. For example, the map shows a 4 stop itinerary in California: from Laguna, CA to Pacifica, CA to Half Moon Bay, CA to Pacific Grove, CA and back to Laguna, CA.

![WeatherPy_travel_map_directions](https://user-images.githubusercontent.com/88729583/136299853-443e3e73-37fa-4ba3-a9ff-e9dd7fd5705a.PNG)

Finally, we created a marker layer map with a pop-up marker for each city on the itinerary (Laguna, CA, Pacifica, CA, Half Moon Bay, CA, Pacific Grove, CA).

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/88729583/136299890-00d9d5e9-ace6-4131-8ac8-6460a8ab6af9.png)

## Resources 

- Software
    -	Jupyter Notebook
- Enviroment
    -	Python 3.7
- Dependencies
    -	Pandas Library
    -	Numpy Library 
    -	CitiPy Module
    -	Python Requests
- APIs
    -	**Open Weather APIs** to retrieve weather data.
    -	**Google Maps API** to create heat maps and retrieve information about hotels around the world.
    -	**Google Directions API** to map the direction between 4 points.

## Techniques used

-	NumPy random module to generate random coordinates.
-	CityPy module to search for city names based on random coordinates.
-	Retrieve and use data from an API "get" request to a server.
-	Retrieve and store values from a JSON array.
-	Use try and except blocks to resolve errors.
-	Create heatmaps, and add markers using the Google Maps API.
-	Create destination layer map using Google Direction API.
-	Pandas to create data frames and clean the data.
-	Take user input and select data base on user input.
-	Python enumerate function.
-	Creating heat maps and pop-up boxes that displays information about hotels and weather.
-	Json traversals.


