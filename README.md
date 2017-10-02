# erddap-tsviewer

The goal here is to make a simple JavaScript time series viewer built on ERDDAP. 

1. Use ERDDAP Advanced Search API to find all stations matching a specific time range, lon/lat range and matching a specific standard_name. and display them on a map with clustering, perhaps using Leaflet or OpenLayers3.  Could default to the last week, the continental US and air_temperature for initial display.   The available standard_name list would be displayed on the right side of the map, and if another standard_name was selected, would update the map to only show stations that have that variable.

2. Click on a point and use ERDDAP data API to extract a time series and display as a time series chart, perhaps using Highcharts. 

The idea would be to basically provide a light-weight version of sensors.ioos.us/#map that would work with any ERDDAP endpoint.  
