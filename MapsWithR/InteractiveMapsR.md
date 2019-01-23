Interactive Maps with R
================
Alex Mandel, Nistara Randhawa, Ryan Peek, Mahesh Maskey
January 30, 2019

Goal
----

Give people an dive into how to make interactive plots in R with maps. Focus on maps that allow the user to pan, zoom, query(click).

Core tools
----------

Mapview, Leaflet

Data Types
----------

-   Points, Lines, Polygons, Rasters
-   Vectors include the option for popups from attribute tables
-   sp and sf

Data Examples
-------------

-   Crop Field Boundaries (polygons) with UAS RGB and NDVI rasters (From Taylors presentation last quarter), it could be crop type
-   Getting country/administrative boundaries (polygons) via R and using them in Leaflet. Useful when working with health data or any field project in different countries
-   Climate data

Steps
-----

-   Data Preparation
-   Decide how to derive data
-   Dealing with missing data
-   Compile them at a point wise

Styling
-------

-   Points - circles vs markers, their attributes, using custom icons, etc
-   Lines
-   Polygons
-   Rasters
-   Basemaps
-   Standard - OSM, Bing, Google,
-   XYZ tiles - i.e. Stamen, etc
-   Transparency
-   Labels
-   Attribute pop-ups
-   Toggle different data layers on the map
-   Tools that allow measurement/point extraction (Javascript based but easy to drop code in to play with (Leaflet))

Bonus
-----

Exporting to share with others (HTML or Shiny)

References
----------

-   <https://rstudio.github.io/leaflet/>
-   <https://r-spatial.github.io/mapview/>