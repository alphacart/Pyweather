 What's the Weather Like?


## WeatherPy

In this example, created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, utilized a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a representative model of weather across world cities.

Objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude



 Notebook contains:

* Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls. 
* Include a print log of each city as it's being processed with the city number, city name, and requested URL.
* Save both a CSV of all data retrieved and png images for each scatter plot.

* Used the Matplotlib and Seaborn libraries.
* Used a written description of three observable trends based on the data. 
* Used proper labeling of your plots, including aspects like: Plot Titles (with date of analysis) and Axes Labels.

Output:
![Image1](https://github.com/alphacart/Pyweather/blob/master/CloudinessInWorldCities.png)
![Image1](https://github.com/alphacart/Pyweather/blob/master/HumidityInWorldCities.png)
![Image1](https://github.com/alphacart/Pyweather/blob/master/TemperatureInWorldCities.png)
![Image1](https://github.com/alphacart/Pyweather/blob/master/WindSpeedInWorldCities.png)
