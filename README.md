# python-api-challenge

WeatherPy:
Using Python requests, APIs, and JSON traversals the script evaluates the weather as we approach the equator.  Looking at the weather of over 500 cities of varying distances from the equator, I used openWeatherMap API to retrieve weather data from the cities list.  A series of scatter plots were made to look at the following relationships:  Latitude vs. Temperature, Latitude vs. Humidity, Latitude vs. Cloudiness. Latitude vs. Wind Speed.  Next linear regression was calculated to compare: Northern Hemisphere: Temperature vs. Latitude. Southern Hemisphere: Temperature vs. Latitude, Northern Hemisphere: Humidity vs. Latitude, Southern Hemisphere: Humidity vs. Latitude, Northern Hemisphere: Cloudiness vs. Latitude, Southern Hemisphere: Cloudiness vs. Latitude, Northern Hemisphere: Wind Speed vs. Latitude, and Southern Hemisphere: Wind Speed vs. Latitude.

VacationPy:
From the weather data obtained from WeatherPy, this script used Geoapify API and the geoViews Python library along with Python skills to create map visualizations.  The maps narrowed the selection of cities based on ideal weather conditions based on max temperature, wind speed and cloudiness constraints.  Lastly, hotels in a 10,000 meter radius were retrieved an plotted for each city.
    
