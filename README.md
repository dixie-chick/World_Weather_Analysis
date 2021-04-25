# World_Weather_Analysis
using APIs in jupyter notebook to plan a holiday based on weather analysis

# Let's Go On Holiday!
With everyone getting vaccinated, planning a trip is back on the agenda. This analysis imports gmaps, citipy, numpy, resources, and utilizes google maps API to retrieve weather data, create a custom travel map, and an itenerary for a warm weather road trip around Brazil's beach cities with accomodation.

## Basic Project Plan

**Task:** Collect and analyze weather data across cities worldwide.
**Purpose:** PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
**Method:** Create a Pandas DataFrame with world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data. Then, perform API calls to retreive weather. Finally, input customer weather preferences and generate an itenerary.


### Step 1: Retreive Weather Data
- uses random() to generate 2000 Lats and Lngs
- retreice nearest city
- perform an API call with OpenWeatherMap to retreive Weather Description

### Step 2: Create a Customer Travel Destinations Map
- use input to retreive customer weather preferences to identify potential travel destinations and nearby hotels
- For this analysis the customer prefers to travel somewhere warm between 75-90 degrees F

![WeatherPy_Vacation_map](https://user-images.githubusercontent.com/79612565/115981023-b6046580-a545-11eb-9fe8-0ddaa85c28d1.png)

### Step 3: Create a Travel Itinerary & Map
- use Google Directions API to create an itenerary that shows the route between four cities and possible travel destinations with hotel accomodations

![weatherpy_travel_map_markers](https://user-images.githubusercontent.com/79612565/115981030-c74d7200-a545-11eb-95c5-76fb53a7c55e.png)
![WeatherPy_travel_map](https://user-images.githubusercontent.com/79612565/115981027-c3b9eb00-a545-11eb-9d1f-06ef72a2c6d0.png)


