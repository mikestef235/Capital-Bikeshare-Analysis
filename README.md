# Capital-Bikeshare-Analysis
This is a repo demonstrating the use of multiple geospatial visualization tools on public Capital Bikeshare trip data.

This analysis focuses on using 2017 Washington, DC "Capital BikeShare" trip data to show the capabilities of three Geospatial tools which are Geopandas, Ipyleaflet, and Kepler. The first two are python packages, while the latter is an open source tool developed by Uber to visualize ride demand over time. This makes it perfect for the time dependent bike ride trip data. Specific objectives are as follows...

__Geopandas:__

1. Importing basemap file
2. Geocoding, aka finding the latitude and longitude, of each station's street address
3. Placing geocoded markers for Bikshare stations

__Ipyleaflet:__

1. Create interactive "Google Maps" style visual
2. Placing customized geocoded markers for each Bikeshare station

__Kepler:__

1. Export data in format friendly for tool
2. Visualize 2017 rides by day
3. Visualize 2017 rides by member type
4. Visualize 2017 rides by duration
5. Export json file of map data and visual
