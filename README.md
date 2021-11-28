# PlanMyTrip App using Google APIs
### Purpose
This project designs a system that allows the client to filter possible vacation destinations based off of minimum and maximum temperatures using an input method and gather other various weather data such as current weather condition, humidity, cloudiness, and wind speed. This system generates 2,000 sets of randoms coordinates, locates the nearest city to each set using the citipy module, allows the client to filter based on minimum and maximum temperature, then creates a route between each of the chosen cities using Google Maps APIs. In order to read the created data from other files, the data frames were exported as CSV files in the above folders.

### Closest cities to randomly generated coordinates with a max temperature between 50 and 70 degrees fahrenheit:
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/92493572/143785922-75dffb1a-efef-4cfd-8f19-55d09af340f6.png)

Notice the HTML bubble with relevent destination information that is shown when destinations are clicked on.

### Route created from a starting point that loops through three nearby cities and heads back to the start:
![WeatherPy_travel_map](https://user-images.githubusercontent.com/92493572/143786023-23d0e37c-fe3a-4327-b581-3f8b0fc34d52.png)
