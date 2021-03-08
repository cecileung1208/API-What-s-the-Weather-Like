# Global Weather Analysis

## Background
![Image](https://cdn.windowsreport.com/wp-content/uploads/2019/08/Storm-Weather-930x620.jpg)

In this project, the objective is to determine the correlation between latitude against factors such as temperature, humidity, cloudiness and windspeed from over 500 cities.  To accomplish this, the global cities weather information is extracted from the Open Weather Map API.  Then, using programming techniques like Python, Matplotlib, Numpy, Requests, Citypy, Pandas and Scipy in Jupyter Notebook to produce the required outputs.

## Requirements
The objective  is to build a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

## Datasets


## **The Summary of Results have the following outputs:**

### **1.  WeatherPy - Jupyter Notebook**

This [file](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/WeatherPy.ipynb) provides program codes that output the weather infomration and scatterplot graphs for 500+ cities and tables that determine the how the cities' latitude is correlated with the temperature, humidity, cloudiness, and windspeed. 

#### **The output are as follows:**

*  **Analysis of WeatherPy Results**

*  **Generate Cities List**
    * Print Record of City List
    * Dataframe of City Weather Information
    
*  **Plotting the Data - Scatter Plots**
    * Latitude vs. Maximum Temperature (F)
    * Latitude vs. Humidity (%)
    * Latitude vs. Cloudiness (%)
    * Latitude vs. Windspeed (mph)
    
*  **Linear Regression**
    * Northern Hemisphere - Maximum Temperature (F) vs Latitude
    * Southern Hemisphere - Maximum Temperature (F) vs Latitude
    * Northern Hemisphere - Humidity (%) vs Latitude
    * Southern Hemisphere - Humidity (%) vs Latitude
    * Northern Hemisphere - Cloudiness (%) vs. Latitude     
    * Southern Hemisphere - Cloudiness (%) vs. Latitude   
    * Northern Hemisphere - Wind Speed (mph) vs. Latitude
    * Southern Hemisphere - Wind Speed (mph) vs. Latitude
    
### **2.  API Keys - Python File**
This [file](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/api_key.py) is to save the Openweather Map API keys to extract weather information for the various cities.

### **3.  Output Files Folder**
This [folder](https://github.com/cecileung1208/API-What-s-the-Weather-Like/tree/master/Output%20Files) provides a csv and png files from the WeatherPy Jupyter Notebook outputs.

*  **CSV Files**
    * [Dataframe of City Weather Information](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/weather_data.csv)
   
*  **PNG Image Files - Scatter Plots**
    * [Latitude vs. Maximum Temperature (F)](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Latitude_MaxTemp.png)
    * [Latitude vs. Humidity (%)](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Latitude_Humidity.png)
    * [Latitude vs. Cloudiness (%)](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Latitude_Cloudiness.png)
    * [Latitude vs. Windspeed (mph)](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Latitude_WindSpeed.png)
    
*  **PNG Image Files - Linear Regression**

    * [Northern Hemisphere - Maximum Temperature (F) vs Latitude](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Northern_Hemisphere_MaxTemp.png)
    * [Southern Hemisphere - Maximum Temperature (F) vs Latitude](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Southern_Hemisphere_MaxTemp.png)
    * [Northern Hemisphere - Humidity (%) vs Latitude](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Northern_Hemisphere_Humidity.png)
    * [Southern Hemisphere - Humidity (%) vs Latitude](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Southern_Hemisphere_Humidity.png)
    * [Northern Hemisphere - Cloudiness (%) vs. Latitude](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Northern_Hemisphere_Cloudiness.png)     
    * [Southern Hemisphere - Cloudiness (%) vs. Latitude](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Southern_Hemisphere_Cloudiness.png)   
    * [Northern Hemisphere - Wind Speed (mph) vs. Latitude](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Northern_Hemisphere_Windspeed.png)
    * [Southern Hemisphere - Wind Speed (mph) vs. Latitude](https://github.com/cecileung1208/API-What-s-the-Weather-Like/blob/master/Output%20Files/Southern_Hemisphere_Windspeed.png)
