# API-CHALLENGE

## Part 1:
Create a Python script to visualize the weather of over 500 cities of varying distances from the equator using citipy Python library Links to an external site and the OpenWeatherMap API Links to an external site. Create a representative model of weather across cities.

Use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. 

### Requirement 1: 
Create Plots to Showcase the Relationship Between Weather Variables and Latitude using the OpenWeatherMap API to retrieve weather data. Next, you'll create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

### Requirement 2: Compute Linear Regression for Each Relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 
Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values as you can see in the following image

You should create the following plots:

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

## Part 2:
VacationPy  use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

Use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
