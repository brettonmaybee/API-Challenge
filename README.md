# API-Challenge
 Data Class Assignment 5

This repository includes two folders, each containing a seperate project. 

The folder "WeatherPy" contains a Python script that generates a list of random cities using a list of random latitude and longitude coordinates. It then uses a weather API to collect weather data on the locations of these cities. The script then uses the weather data to generate a series of scatter plots to analyse the relationship between temperature, humidity, cloudiness and wind speed measurments with their respective latitude coordinates in the north and southern hemispheres. A folder labeled 'output_data' contains the city data in a csv file labeled 'cities_data.csv'. The 'out_put' folder also contains twelve png image files showing the relations between the weather data, and the latitude coordinate were it was measured. The objective of this study was to analyze the relationship between weather and the distance from the equator.     

The folder labeled "VacationPy" contains a Python script that uses the city data from the weather project to plan a vacation. The humudity data is used to add a heatmap layer to a map in relation to the cities on th list. The city list is then filtered based on weather preferences. The coordinated of the cities with the prefered weather conditions are then used to retreive the nearest hotel data from the google API. The hotel data is then added to the heat map as markers, where the name of the hotel, city, and coountry where the hotel is located displayed on the heat map by clicking on the coresponding marker.    
