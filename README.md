# World_Weather_Analysis

## BACKGROUND

> Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

### OBJECTIVE

>This new assignment consists of two technical analysis deliverables and a written report to present your results. 
> You will submit the following:

- Deliverable 1: Retrieve Weather Data
- Deliverable 2: Create a Customer Travel Destinations Map
- Deliverable 3: Create a Travel Itinerary Map

---

## DELIVERABLE 1: Retrieve Weather Data

### Retrieve all of the following information from the API call.

- Lat & Long
- Max Temp
- Percent Humidity
- Wind Speed
- Weather descrition

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/weather_data/Weather_data_dataframe.png)

### Export to CSV

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/weather_data/export_weatherdata.png)


## DELIVERABLE 2: Create a Customer Travel Destinations Map

> Input statements are written to prompt the customer for their minimum and maximum temperature preferences.

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/Vacation_Search/set_min_max_temp.png)

> A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped.

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/Vacation_Search/min_max_dataframe.png)

> The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped.

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/Vacation_Search/Hotel_name_dataframe.png)

> The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv.

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/Vacation_Search/hotel_name_csv.png)

> A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information:
- Hotel Name
- City
- Country
- Current weather description with max temp.

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/Vacation_Search/Pop-up_html.png)

> The marker layer map is saved and uploaded to the Vacation_Search folder as WeatherPy_vacation_map.png.

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)


## DELIVERABLE 3: Create a Travel Itinerary Map

> Four DataFrames are created, one for each city on the itinerary.

![This is an image]()

>The latitude and longitude pairs for each of the four cities are retrieved.

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/Vacation_Itinerary/lat_long_pairs.png)

> A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png. 

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

> A DataFrame that contains the four cities on the itinerary is created.

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/Vacation_Itinerary/four_city_datafame.png)

> A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information:

- Hotel Name
- City
- Country
- Current weather description with max temp

![This is an image](https://github.com/jcaraway-na/World_Weather_Analysis/blob/main/Vacation_Itinerary/updated.png)

