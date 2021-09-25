# World Weather Analysis

The purpose of the analysis is to provide clients of PlanMyTrip, a travel company, a tool that enables them to determine their travel destination based on weather conditions. The analysis picks >500 cities around the world using Python's random function and citipy module. Then the analysis collects and analyzes weather data of these cities using OpenWeatherMap API. Next PlanMyTrip recommends ideal hotels based on clients' weather preferences and uses Google Maps API to find ideal hotels and plots them on a map. Finally, I created a travel itinerary and driving route between four cities as well as a marker layer map using the Google Maps Directions API.

## Results
Using input statements, customer can provide weather preferences. The traveler can narrow down potential travel destinations and see nearby hotels. The map uses the pop-up markers on the map to display the destination, weather data, and recommended hotels. 

![Vacation_Search](/Vacation_Search/WeatherPy_vacation_map.png)

I provided a sample itinerary of 4 cities and driving direction using Google Directions API.
![Vacation_Itinerary](/Vacation_Itinerary/WeatherPy_travel_map.png)

The sample itinerary of 4 cities has a map that uses the pop-up markers to display the destination, weather data, and recommended hotels. 
![Vacation_Itinerary2](/Vacation_Itinerary/citipyWeatherPy_travel_map_markers.png)
