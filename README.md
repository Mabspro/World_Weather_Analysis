# World_Weather_Analysis
Analyze City  weather data for different cities to help a travel website

## Overview:
Task: Collect and analyze weather data across cities worldwide.
Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.

### Data
To collect the following data from the JSON file and add it to a DataFrame:
City, country, and date, Latitude and longitude, Maximum temperature, Humidity, Cloudiness, Wind speed.

This assignment consists of three technical analyses as deliverables:

Deliverable 1: Retrieve Weather Data
Deliverable 2: Create a Customer Travel Destinations Map
Deliverable 3: Create a Travel Itinerary Map

### Quick notes of consideration:

The lines of latitude (parallels) and longitude (meridians) make up a geographic grid with intersecting horizontal and vertical lines mapping to specific locations. This will help us map loactions easier.

GCS makes it possible to pinpoint any place on Earth by providing its precise address, which is the intersection of its latitude and longitude lines.

Longitude and latitude lines intersect and form a geographic grid system across the Earth's surface.

## Deliverable 1
### Retrieve Weather Data
Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data you gathered in this module, use your API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.

## Deliverable 2
### Create a Customer Travel Destinations Map.
Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

## Deliverable 3
### Create a Travel Itinerary Map
Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.
