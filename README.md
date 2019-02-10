# Weather_API_Analysis
This is a python script which randomly generates coordinates for 500 + cities. The geographic information is then used to retrieve data via API from http://api.openweathermap.org. 

The information analyzed here was temperature, humidity, cloudiness, and maximum windspeed. The projected data correspond to the 9th of february 2019.


To run the complete script you will have to create a config file containing your personal api key which you can get for free [http://api.openweathermap.org].
- To review the complete code click here: [weather_analysis.ipynb](weather_analysis.ipynb)
- To load existing data click here: [weather_data.csv](weather_data.csv)

## Results

Figure 1 shows the location of the 500 randomly selected cities.

![](https://github.com/JoannePeel/Weather_API_Analysis/blob/master/Latitude_vs_Longitude_data_points.png) 

Fig. 1. Data points.

Currently the northern hemisphere is experiencing winter conditions, and temperatures range between 0 °C and -30 °C at latitudes higher than 40° (Fig. 2). The highest temperatures can be observed around the equatorial regions. The southern hemisphere is experiencing summer conditions and temperatures are generally higher than 0 °C.

![](https://github.com/JoannePeel/Weather_API_Analysis/blob/master/Latitude_vs_Longitude_temperature.png)

Fig. 2. Temperature around the world

Figure 3 shows the relationship between humidity, latitude and longitude. The lowest humidity values were observed between 20° and 40° latitude on both sides of the equator (0°), which may be associated with the presence of major deserts in this area. 

![](https://github.com/JoannePeel/Weather_API_Analysis/blob/master/Latitude_vs_Longitude_humidity.png)

Fig. 3. Humidity around the world

Figure 4 shows cloud cover related to latitude and longitude. Cloud cover didn’t show any specific latitudinal trend.

![](https://github.com/JoannePeel/Weather_API_Analysis/blob/master/Latitude_vs_Longitude_cloud.png)

Fig. 4. Cloudiness around the world

Figure 5 shows wind speed in relation to latitude and longitude. There was no clear trend observable regarding wind speed and latitude, although winds may be stonger towards the poles, given increased Coriolis forces. However, this was not observable in the analyzed data.


![](https://github.com/JoannePeel/Weather_API_Analysis/blob/master/Latitude_vs_Longitude_wind.png)

Fig. 5. Windspeed around the world

## Conclusions

The temperature gradient shows the northern hemisphere in winter conditions, so temperatures are lower in the northern regions. The highest temperatures may be associated to the presence of major deserts around -30° latitude.
The lowest humidities were also observed around 30° on both sides of the equator, which may also be associated with the presence of desert regions.


