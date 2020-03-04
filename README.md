# Application of Python + API for weather analysis and vacation destination selection

- See the `output` and `figures` folders for the results of the analysis
- See the `code` folder for the code to perform the following analysis

## Part I - Weather analysis

- Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 
- Used Python library [simple Python library](https://pypi.python.org/pypi/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api)

- Created a series of scatter plots to examine the following relationships and provided interpretation of each.

  * Temperature (F) vs. Latitude
  * Humidity (%) vs. Latitude
  * Cloudiness (%) vs. Latitude
  * Wind Speed (mph) vs. Latitude

- Performed a series of linear regression based on Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude) and provided interpretation of each result.

  * Northern Hemisphere - Temperature (F) vs. Latitude
  * Southern Hemisphere - Temperature (F) vs. Latitude
  * Northern Hemisphere - Humidity (%) vs. Latitude
  * Southern Hemisphere - Humidity (%) vs. Latitude
  * Northern Hemisphere - Cloudiness (%) vs. Latitude
  * Southern Hemisphere - Cloudiness (%) vs. Latitude
  * Northern Hemisphere - Wind Speed (mph) vs. Latitude
  * Southern Hemisphere - Wind Speed (mph) vs. Latitude

### Part II - Vacation destination analysis 

* First created a heat map that displays the humidity for every city from the earlier results.

* Narrow down the DataFrame to find identify cities that meet the desired weather condition, such as:
  * max temperature
  * wind speed
  * level of cloudiness, et.

* Used Google Places API to identify the first hotel for each city located within 5000 meters of the coordinates (of locations that meet the desired weather condition)

* Plotted the hotels identified on top of the humidity heatmap
  * each pin contains information such as the **Hotel Name**, **City**, and **Country**.
