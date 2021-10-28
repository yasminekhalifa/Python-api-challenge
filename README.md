# Python-api-challenge

In this project, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this,I utilized a [simple Python library](https://pypi.python.org/pypi/citipy),and the [OpenWeatherMap API](https://openweathermap.org/api).

I created a series of scatter plots to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Secondly, I ran linear regression on each relationship, only this time separating them into Northern Hemisphere and Southern Hemisphere:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
