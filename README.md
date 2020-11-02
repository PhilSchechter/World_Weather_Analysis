# World_Weather_Analysis
Data analytics class, Module 6
Working with APIs to pull data from:
- Google Maps (maps, directions)
- Openweathermap


And using tools (request, get) to help form URLs for the API pulls and read from the JSON files returned, and the random module. Also used numpy, pandas, matplotlib, requests, time, citypy

## Sections 
### Weather Database
- Generated random combinations of latitude, longitude.
- used citydata to find the nearest city
- used API calls to Openweathermaps to get weather conditions for each city
- generated a CSV file saving this information

## Vaction Search
- filtered potential vacation spots by a user specified temperare range
- mapped out resulting city, with a clickable data layer showing city name, country, weather conditions, and a hotel name.

Can see an impage of the resulting map:

[Cities](Vacation_Search/WeatherPY_vacation_map.png)

## Vacation Itinerary
- picked out 4 cities from the list
- provided a driving map to loop
- saved resulting map

[Itinerary](Vacation_Itinerary/WeatherPy_travel_map.png)

[Itinerary with Markers](Vacation_Itinerary/WeatherPy_travel_map_markers.png)
