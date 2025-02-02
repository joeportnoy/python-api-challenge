# python-api-challenge

This is Joe Portnoy's submission for the python-api-challenge, part of the DU Data Bootcamp.

## Objective

There are two parts to this challenge:

### WeatherPy
In this challenge, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I did the following:

1. Create Plots to Showcase the Relationship Between Weather Variables and Latitude
    - I retrieved weather data from the generated list of cities and calculated the following:
        - Latitude vs. Temperature
        - Latitude vs. Humidity
        - Latitude vs. Cloudiness
        - Latitude vs. Wind Speed
2. Compute Linear Regression for Each Relationship
    - I separated the data into the Northern and Southern Hemispheres and then computed the linear regression for each relationship. I created the following plots:
        - Northern Hemisphere: Temperature vs. Latitude
        - Southern Hemisphere: Temperature vs. Latitude
        - Northern Hemisphere: Humidity vs. Latitude
        - Southern Hemisphere: Humidity vs. Latitude
        - Northern Hemisphere: Cloudiness vs. Latitude
        - Southern Hemisphere: Cloudiness vs. Latitude
        - Northern Hemisphere: Wind Speed vs. Latitude
        - Southern Hemisphere: Wind Speed vs. Latitude

### VacationPy

Utilizing the city data from the first part of the challenge to plan my vacation.

I mapped all the points making the size of the point based on the humidity in each city.

I narrowed my list of data based on my ideal temperature, wind speed, and cloudiness and compiled the results into a data frame.

Then I used Geoapify to find a hotel within 10,000 meters and mapped the dots with the country and Hotel name.