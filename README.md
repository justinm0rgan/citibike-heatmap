# How to make a time lapse heatmap with Folium using NYC Bike Share Data
The following is an exercise in working with monthly bike rideshare data from <a href="https://s3.amazonaws.com/tripdata/index.html" target=blank>Citibike</a> 


- Create function that instantiates a folium Map object to generate a basemap in the correct coordinate reference system for NYC
- Iteratively web scrape the Citibike data server and return the latest month available.
- Create HeatMap with Citibike station ID's to show concentration of Citibike stations. 
- Create HeatMapWithTime (time lapse heat map) by hour for the latest month available.

This will showcase the amount of rides started from each Citibike station, associating brighter colors with higher activity by hour.
