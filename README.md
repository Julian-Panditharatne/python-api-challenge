# Python API Challenge

This challenge is broken down to two parts:

1. **WeatherPy**
2. **VacationPy**

## Part 1: WeatherPy

This part of the challenge involves creating a Python script to visualize the weather of over 500 cities of varying distances from the equator, using Jupyter notebooks, citipy Python library, and OpenWeatherMap API.

The challenge is to create visuals in the following manner:

1. Create a series of scatter plots to showcase the relationships between the following weather variables and latitude.
    1. Temperature
    2. Humidity
    3. Cloudiness
    4. Wind Speed
2. Create a similar series of scatter plots that are now seperated into Northern and Southern Hemisphere, compute the linear regression for each relationship, and include the linear regression lines, the models' formulas, and the r values with the plots.

## Part 2: VacationPy

This part of the challenge involves using Jupyter notebooks, geoViews Python library, and Geoapify API to create map visualizations in the following manner:

1. Create a map that displays a point for every city in the DataFrame that will contain all the weather and coordinates data collected in Part 1: WeatherPy; the size of the point should be the humidity in each city.
2. Narrow down the DataFrame to find the following ideal weather conditions:
    1. 21 <= max temperature <= 27.
    2. wind speed < 4.5 m/s.
    3. 0% cloudiness.
3. Create a new DataFrame to store the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of its coordinates, and then store it in the new DataFrame.
5. Add the hotel name and the country as additional information in the hover message for each city on the map.

---

## Repository Files and Folders

Besides this README file and a gitignore file, there are nine other files and two folders:

The folder, which is named *WeatherPy* contains 4 of the 9 files along with the other folder named *output_data*


---

## References

*API reference — pandas 1.4.2 documentation*. (2024, April 10). Pandas Documentation. <https://pandas.pydata.org/pandas-docs/stable/reference/index.html#api>

Geoapify. (n.d.). *Places API | Developer Documentation | Geoapify*. Apidocs.geoapify.com. Retrieved June 1, 2024, from <https://apidocs.geoapify.com/docs/places/#api>

Hunter, J., Dale, D., Firing, E., Droettboom, M., & Matplotlib development team. (n.d.-a). *API reference*. Matplotlib.org. Retrieved May 2024, from <https://matplotlib.org/devdocs/api/index.html>

Hunter, J., Dale, D., Firing, E., Droettboom, M., & Matplotlib development team. (n.d.-b). *Examples*. Matplotlib.org. Retrieved May 2024, from <https://matplotlib.org/stable/gallery/index.html>

OpenWeather. (n.d.). *Current weather data - OpenWeatherMap*. Openweathermap.org. Retrieved June 1, 2024, from <https://openweathermap.org/current>

*User Guide — pandas 2.1.1 documentation*. (2024, April 10). Pandas Documentation. <https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide>
