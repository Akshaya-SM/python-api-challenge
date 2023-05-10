# python-api-challenge

# Part 1: WeatherPy
* Using the OpenWeatherMap API to retrieve weather data from the cities list generated. 

* create a series of scatter plots to showcase the following relationships:
    - Latitude vs. Temperature
    - Latitude vs. Humidity
    - Latitude vs. Cloudiness
    - Latitude vs. Wind Speed

* Compute the linear regression for each relationship. Separate the plots into Northern and Southern Hemisphere. To create the linear regression plots.

* Create a series of scatter plots. Include the linear regression line, the model's formula, and the r values.

* You should create the following plots:
    - Northern Hemisphere: Temperature vs. Latitude
    - Southern Hemisphere: Temperature vs. Latitude
    - Northern Hemisphere: Humidity vs. Latitude
    - Southern Hemisphere: Humidity vs. Latitude
    - Northern Hemisphere: Cloudiness vs. Latitude
    - Southern Hemisphere: Cloudiness vs. Latitude
    - Northern Hemisphere: Wind Speed vs. Latitude
    - Southern Hemisphere: Wind Speed vs. Latitude
    
* After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

# Part 2: VacationPy
* Use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

* The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

* Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

* open the VacationPy.ipynb starter code and complete the following steps:

    1. Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.

    2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:
        - A max temperature lower than 27 degrees but higher than 21
        - Wind speed less than 4.5 m/s
        - Zero cloudiness
    3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

    4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

    5. Add the hotel name and the country as additional information in the hover message for each city on the map.