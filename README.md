# Unit6-WhatsTheWeatherLike-Anuj-Pandya-

# Pre Requisite before executing the code
1. When executing the code please copy the configuration file config_weather.py 
to the folder where the code is being executed. This file contains the api Key from 
openweathermap.
2. I am using the weathermap API that uses City Name(generated from random latitudes and longitudes) to get the weather details. 
However, I noticed that for some cities data is not available from weathermap. Weather map throws a 404 exception. As a solution, I skip 
those cities(I delete those cities from the Pandas Data frame that holds weather info).

# Interpretation of Latitude and Temperature:
Please refer to LatsvsTemp.png. 
It is apparent that the temperatues are the higher as the Latitude approaches zero(Equator). 
Temperatures are the lowest at the extremes ends of the plot. i.e at the poles. This is pretty much in line with what I remember from Middle School science classes.

# Interpretation of Latitude and Humidity:
Please refer to LatsvsHum.png. 
There is no correlation between the two variables Latitude and Humidity.

# Interpretation of Latitude and Wind Speed:
Please refer to WindSpeedvsLatitude.png. 
There is no definitive correaltion between Latitude and Wind Speed , but some outliers indicate that winds speeds tend to get higher at latitudes +60 and -40.

# Interpertation of Cloudiness vs Latitude:
Please refer to CloudsvsLatitude.png.
No corelation.

