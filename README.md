# Global Weather Analysis

## Background
![Image](https://cdn.windowsreport.com/wp-content/uploads/2019/08/Storm-Weather-930x620.jpg)

In this project, the objective is to determine the correlation between latitude against factors such as temperature, humidity, cloudiness and windspeed from over 500 cities.  To accomplish this, the global cities weather information is extracted from the Open Weather Map API website.  Then, along with using various programming techniques like Python, Matplotlib, Numpy, Requests, Citypy, Pandas and Scipy ub Jupyter Notebook to obtain the required outputs.

## Requirements
1. Build a series of scatter plots to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

2. Calculate the regression model and plot the best fit line on the scatter plots by the northern and southern hemisphere for the following:
* Temperature (F) vs. Latitude (Northern)
* Temperature (F) vs. Latitude (Southern)
* Humidity (%) vs. Latitude (Northern)
* Humidity (%) vs. Latitude (Southern)
* Cloudiness (%) vs. Latitude (Northern)
* Cloudiness (%) vs. Latitude (Southern)
* Wind Speed (mph) vs. Latitude (Northern)
* Wind Speed (mph) vs. Latitude (Southern)

## Datasets
[Weather Data](https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/weather_data.csv)

## Methods

1.  Go to [openweathermap.org](https://openweathermap.org/) to create an account and obtain an api key.
2.  Produce a text file to define the api key.
3.  In Jupyter Notebook, import dependencies and install libraries as required.
4.  Generate random cities list.
5.  Perform an test API call using the try and except method.
    * Generate a random list of 15 cities/random names to determine if you can successfully call the information.
    * Create record count as 1.
    * Display output of the cityname, record 
6.  Upon test success, perform the API call and a dataframe on the 500+ cities.
    * Create empty list to store information on cityname, maximum temperature, cloudiness, humidity, windspeed, latitude, longitude, date, and country.
    * Create record and set counts as 1.
    * Generate the API call using the try and except method.
    * Append outputs to empty lists.
    * Display output results.
    * Create dataframe from the updated lists.
    * Validate the dataframe by conducting a record count for each column.
    * Save the dataframe as a CSV.
7.  Plot the scatter plot graphs of the following using Matplotlib:
    * Temperature (F) vs. Latitude
    * Humidity (%) vs. Latitude
    * Cloudiness (%) vs. Latitude
    * Wind Speed (mph) vs. Latitude
8.  Calculate the regression model and plot the best fit line of the above scatter plot graphs by northern and southern hemispheres. 
    * Divide the dataframe into the 2 different hemishperes by latitude.
    * Define function for regression model.
    * Define function for best fit line
    * Using these functions, plot the following:
      * Temperature (F) vs. Latitude (Northern)
      * Temperature (F) vs. Latitude (Southern)
      * Humidity (%) vs. Latitude (Northern)
      * Humidity (%) vs. Latitude (Southern)
      * Cloudiness (%) vs. Latitude (Northern)
      * Cloudiness (%) vs. Latitude (Southern)
      * Wind Speed (mph) vs. Latitude (Northern)
      * Wind Speed (mph) vs. Latitude (Southern)

## Scripts

[API Key](https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/api_key.py)<br>
[Weatherpy Notebook](https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/WeatherPy.ipynb)

## Results
