# IE360-TimeSeries-Project
Time series forecasting project given in the specialization course IE360 at Bogazici University.
Click [here](https://bu-ie-360.github.io/spring22-bthnsrts/) for project report.

Project Introduction:

In this project, main goal is to predict hourly solar power predictions of KIVANC 2 GES (a solar power plant in Mersin) starting from May 25 to June 3, 2022. Past hourly production data ranging from February 1, 2021 to two days before the current date are provided and updated each day. Thus, prediction is made in a very similar setting to the real life dynamics of energy markets. On day d, production up until day d-2 are given, and prediction is provided for day d+1.
In addition to the production data, weather information is provided for 9 different locations. These locations constitute adjacent grid points around the plant and their coordinates range from 36.25 latitude, 33 longtitude to 36.75 latitude, 33.5 longtitude.
For each grid point, past hourly observations of four different weather variables are provided. These variables are;

#### TEMP : Temperature at the provided location.

#### REL_HUMIDITY: Relative humidity at the provided location. Gives information about rainy or cloudy weather.

#### DSWRF: Stands for downward shortwave radiation flux. An estimate of the total amount of shortwave radiation (both direct and diffuse) that reaches the Earth's surface.

#### CLOUD_LOW_LAYER: Total cloud cover data for low-level type of clouds.

