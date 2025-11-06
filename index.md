## Windspeed and Direction Visualization 
Using data from the Walla Walla Airport weather station, we will create a radial bar graph of windspeed and direction.

### Steps in Creating the Visualization
1. Scraped weather data from the [Walla Walla Airport NWS page](https://www.weather.gov/wrh/timeseries?site=KALW) for the time period Sep 27, 2025 through Oct 27, 2025.
1. Imported into this [colab worksheet](https://colab.research.google.com/drive/11yl4TzDl3MN-dlVS09SljJnpflDeRrhQ?usp=sharing)
   * grouped by wind direction and averaged the wind speeds
   * converted cardinal directions to degrees
1. Built visualization using plotly's [Barpolar()](https://plotly.com/python/reference/barpolar/) function.

#### Prevailing Winds
In this visualization we see clearly that the prevailing winds for this time period were in the south and west.
<!--- static image
![A radial bar plot of avg wind speed by direction for one month Sep 27, 2025 - Oct 27, 2025 at the Walla Walla Airport. Prevailing winds appear to come from the south and west.](prevailing%20winds.png)
--->
<!--- load the live plotly html --->
<iframe src="prevailing.html" width="100%" height="600" style="border:none;">
  <p>Your browser does not support iframes.</p>
</iframe>

