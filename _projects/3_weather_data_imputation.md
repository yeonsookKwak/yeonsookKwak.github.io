---
layout: page
title: korea incomplete weather data imputation 
description: 
img: assets/img/weather_imputation.png
importance: 2
category: methodology & application
---

This is a collaborated work with heedong-yun, in kaware,Inc.

An important outstanding problem in analysis of weather data is collected from Korea Meteorological Administration and some data self quality controlled. Therefore multiple recordings are seperately analyzed and processed depeding on their characteristics. 

#### Imputation API 
- Devise a method for spatially fitting in temperature and humidity, and using variations in wind speed and direction to fit wind speed and direction
    - Convert wind direction to a vector format to work with standardized data
- Bayesian ridge method applied : Forecast imputation using data at times other than the time of the station where the data occurred as the dependent variable and data from nearby stations with the same time as the dependent variable as the independent variable
- Data management : apply a method of loading data as appended when updating the database