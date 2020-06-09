# python-api-challenge

![equatorsign](https://github.com/RutgersCodingBootcamp/RU-JER-DATA-PT-01-2020/blob/master/02-Homework/06-Python-APIs/Instructions/Images/equatorsign.png?raw=true)  

We all know that the closer that we get to the equator, the hotter that it gets. But we want to prove this...
In this HW assignment, I used the relatively simple "citipy" library to generate a random sample of over 500 cities to study, along with the OpenWeatherMap API to collect weather data about said cities (the "time" library was imported to make sure that the series of successive calls to the server was not over the limit allowed).  
Four scatter plots were then created (temperature, humidity, cloudiness, wind speed vs. latitude) and briefly analyzed. Linear regression was performed, with the Northern and Souther Hemispheres accounted for, and was analyzed (again, briefly).  
The next part was to use "jupyter-gmaps" and the Google Places API to find the best vacation spots! A heat map showing humidity was created. Next, the DataFrame was filtered down to the cities with the ideal - in my vision - weather conditions. With this table, and with the use of the Google Places API now, I found the first hotel located within 5,000 meters of each vacation city's coordinates. Finally, pins with hotel name, city, and country were plotted on top of the humidity heatmap.  

![Hotel Map](https://github.com/RutgersCodingBootcamp/RU-JER-DATA-PT-01-2020/blob/master/02-Homework/06-Python-APIs/Instructions/Images/hotel_map.png?raw=true)

```
Unit 6 - Python API's Objectives:
- Be able to make GET requests with requests.
- Be able to convert JSON into a Python dictionary.
- Read and apply API documentation.
- Sign up for and use an API key.
- Create applications from scratch using nothing but knowledge of Python and an API documentation.
- Load JSON from API responses into a Pandas DataFrame.
- Be able to use try and except blocks to handle errors.
- Successfully use the Google Maps and Places API to obtain information about geographic areas.
- Understand how to use the Census API wrapper.
- Understand the concept of rate limits and the importance of creating "test cases" prior to running large scripts.
- Have a firmer understanding of how to dissect new API documentation.
```
