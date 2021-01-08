---
layout: default
title: Coordinate Systems
nav_order: 3
parent: Coordinate Reference System
---

## Geographic vs. Projected Coordinate Systems

Most spatial references fall into one of two categories, a geographic or projected coordinate system. 

If you are going to work with geospatial data, you need to understand the difference between the two and when it is appropriate to use one over the other.

### Geographic Coordinate System (GCS)

- a system which spans the entire globe
- uses latitude and longitude
- based on angles measured on a sphere, usually expressed in degrees
- not reliable for calculating distance 

![latLongGrid.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/GCS.jpg)

Latitude and longitude are the typical units used by GCS and are expressed in decimal degrees.

Two of the most common GCS in North America are WGS1984 (used in GPS) and NAD83 (used in surveying and mapping in North America).

You can identify any location in the world using a latitude and longitude.

But these are angular measures, not measures of distance.

In order to more accurately measure distances between places on the surface of the earth or to better represent shapes and sizes in particular areas of the world, we use a projected coordinate system.

### Projected Coordinate System 

- contains a GCS but projects it onto a flat surface
- units are linear, often in meters
- optimized for a particular location to minimize distortion
- consists of lines on a grid at right angles to each other

Difference between a GCS and a PCS.
![pcsGCS.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/pcsGCS.jpg)

Now let's explore the different kinds of map projections.

This section references information, screenshots, and ideas from [Introduction to Spatial References](https://developers.arcgis.com/documentation/core-concepts/spatial-references/), [Coordinate Systems](https://mgimond.github.io/Spatial/coordinate-systems.html#geographic-coordinate-systems), [Earth Lab](https://www.earthdatascience.org/courses/use-data-open-source-python/intro-vector-data-python/spatial-data-vector-shapefiles/geographic-vs-projected-coordinate-reference-systems-python/), [Latitude, Longitude and Coordinate System Grids](https://gisgeography.com/latitude-longitude-coordinates/), [Coordinate Systems: What's the Difference?](https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/coordinate-systems-difference/), [Understanding Map Projections](https://kartoweb.itc.nl/geometrics/Map%20projections/Understanding%20Map%20Projections.pdf), and [Projections and Coordinate Systems](https://courses.washington.edu/gis250/lessons/projection/#coord_systems). 
