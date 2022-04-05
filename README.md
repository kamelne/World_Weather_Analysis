# World Weather Analysis
## Overview
An app using Python, OpenWeatherMap api, and the Google Maps api to recommend vacation destinations based on the users preferred temperatures. 

- Latitudes and longitudes are generated randomly then paired using the zip() function
- Nearest city from latitude and longitude pair found using citipy library
- Current weather data for each city is from OpenWeatherMap using their api
- User is then asked for their ideal min and max temperature for a vacation and the city data is filtered based on input
- A hotel for each city is found using the Google Maps places api then placed on a heat map with pins and an info box
- Cities are then chosen and an travel itinerary if produced
