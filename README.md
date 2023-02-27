# Toronto Fire Incidents Project
![Toronto Fire logo](https://upload.wikimedia.org/wikipedia/en/0/03/Toronto_Fire_Services_Logo.svg)
## Description
### Analysing fire data created by the city of Toronto
Using the [city of Toronto's fire incident data](https://open.toronto.ca/dataset/fire-incidents/) to understand fires in [Toronto's wards](https://open.toronto.ca/dataset/city-wards/). This data with the use of the [fire station location](https://open.toronto.ca/dataset/fire-station-locations/) and [fire hydrant location](https://open.toronto.ca/dataset/fire-hydrants/) is used to improve our understanding of the nature of fire in the city. 

Using JavaScript we created multiple different visulisations from the initial data to answer three primary questions. 


We would like to determine how to best distribute fire stations to minimize damage of fire incidents:
- Heat map of incidents
Null hypothesis: There is no correlation between the number of fire incidents and the number/distance of nearby fire control services
	- Correlate with distance from nearest fire station.
	- Correlate with distance from hydrant
	- Arrival time of fire truck	
- Choropleth map of Dollar damage
Null hypothesis: There is no correlation between the dollar damage and the number/distance of nearby fire control services
	- Correlate with distance from nearest fire station
	- Correlate with distance from hydrant
	- Arrival time of fire truck
- Choropleth map of how quickly fires are put out
Null hypothesis: There is no correlation between the time it takes to put out a fire and the number/distance of nearby fire control services
	- Correlate with distance from nearest fire station
	- Correlate with distance from hydrant
	- Arrival time of fire truck

## DataBase
We created a MongoDB database to store the GeoJSON data keeping mostly in it original state.
The ward data was modified with the addition of the population density of each ward allowing us to determine if the was a correlation between the dollar damage in each ward and the population density. 

## Authors
This data has been collected, aggregated, and visualised by Youssouf Ismael Youssouf, and David Chartrand.
