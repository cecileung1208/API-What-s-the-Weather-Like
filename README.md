# Global Weather Analysis

## Background
![Image](https://cdn.windowsreport.com/wp-content/uploads/2019/08/Storm-Weather-930x620.jpg)

In this project, the objective is to determine the correlation between latitude against factors such as temperature, humidity, cloudiness and windspeed from over 500 cities.  To accomplish this, the global cities weather information is extracted from the Open Weather Map API website.  Then, Jupyter Notebook is written by using programming techniques like Python, Matplotlib, Numpy, Requests, Citypy, Pandas and Scipy to obtain the required outputs.

## Requirements
1. Build a series of scatter plots to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

2. Using the Regression Model, determine the best fit line and plot it against the below scatter plots:
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
5.  Perform an test API call using a for loop through try and except method.
6.  Upon test success, perform the API call and a dataframe on the 500+ cities.
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

**1. Latitude vs Maximum Temperature**

Cities near the equator experience the highest maximum temperature. As the latitude increases , the temperature drops significantly. In general, the Southern Hemisphere have higher temperature than the Northern Hemisphere

<p float="left">
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Latitude_MaxTemp.png" width="250">
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Northern_Hemisphere_MaxTemp.png" width="250"> 
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Southern_Hemisphere_MaxTemp.png" width="250">
</p>

**2. Latitude vs Humidity**

The correlation is almost zero but one noticeable trend is that almost 80% of the cities have a humidity of greater than 60%

<p float="left">
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Latitude_Humidity.png" width="250">
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Northern_Hemisphere_Humidity.png" width="250"> 
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Southern_Hemisphere_Humidity.png" width="250">
</p>


**3. Latitude vs Cloudiness**

The correlation is weak but the graphs do show that the majority of the cities have either 0% or 80-100% cloudiness.

<p float="left">
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Latitude_Cloudiness.png" width="250">
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Northern_Hemisphere_Cloudiness.png" width="250"> 
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Southern_Hemisphere_Cloudiness.png" width="250">
</p>


**4. Latitude vs Wind Speed**

There is no strong relationship between latitude and wind speed as the correlation is only 0.15. However, as the latitude around 60-90 degress, there are numerous cities with wind speed of more than 20 mph.

<p float="left">
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Latitude_WindSpeed.png" width="300">
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Northern_Hemisphere_Windspeed.png" width="300"> 
  <img src="https://github.com/cecileung1208/Global-Weather-Analysis/blob/master/Output%20Files/Southern_Hemisphere_Windspeed.png" width="300">
</p>

