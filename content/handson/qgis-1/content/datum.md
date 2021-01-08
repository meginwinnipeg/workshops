---
layout: default
title: Datums
nav_order: 2
parent: Coordinate Reference System
---

This is a great video to introduce the topic of datums and how they relate to coordinate reference systems. I recommend you watch it on your own.

[Coordinate System Jargon](https://www.youtube.com/watch?v=Z41Dt7_R180)

## Datums

So just what is a datum?

Remember that the earth is unevenly shaped. 

A datum mathematically defines the shape and size of the earth and it's orientation in space.

Measurements of the surface of the earth in different places collected over time by surveyors are used to define a geodetic datum.

Shifts in the surface of the earth, such as following a major earthquake like occurred in New Zealand in 2016, mean that new measurements have to be taken.

![NZ](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/NZ.jpg)

Another way to think about datums is that they are a reference for a starting point against which to determine other horizontal or vertical measurements.

For example, a datum ensures that engineers, surveyors, planners, and mapmakers are all starting at the same “zero” elevation. 

![surveyor](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/canadianSurveyors.jpg)

### Horizontal and Vertical Datums

A **horizontal** datum measures positions on the surface of the Earth using latitude and longitude.

> A horizontal datum is used to monitor the movement of the Earth's crust, or in other words, to monitor earthquake activity.

> Horizontal datums are also used with geospatial data. All geospatial data should have a defined horizontal datum.

A **vertical** datum defines the height either above or below a nationally defined reference surface (e.g., mean sea level).

> Not all geospatial data needs to have a defined vertical datum, but it makes sense if you are using elevation data in a GIS.

> There was just a new [vertical datum](https://www2.gov.bc.ca/gov/content/data/geographic-data-services/georeferencing/vertical-reference-system) released last year for BC, important for any sea level rise mapping and accuracy.


### A Brief History of Datums

This history varies according to country.

Although Canada and the U.S.A. have different surveying histories, they have used the same datum since 1913 because they are on the same continent, along with Mexico. 

In 1901, the Meades Ranch triangulation station in Kansas (established in 1891) was chosen as the point relative to which all land measurements in the United States were made, in part of because of its geographic centrality to the nation.

![meadesRanch.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/meadesRanch.jpg)

In 1913, both Canada and Mexico decided to adopt this station as the starting point as well. 

As a result, the name of the datum was changed. 

<details>
<summary>Who can guess what that datum and subsequent datums became called?</summary>

North American Datum 1913, North American Datum 1927, and so on.
</details>
<br>

Below is a breakdown of the differences between datums currently in use. 

### North American Datum 1927

- uses the Clarke Ellipsoid of 1866 
- reference point at Meade’s Ranch, Kansas
- many control points calculated from observations in the 1800s
- developed using 26,000 stations

![surveyMon.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/surveyMon.jpg)

### North American Datum 1983

- uses the the Geodetic Reference System (GRS80)
- uses the Earth's center as the reference point rather than a ranch in Kansas
- based on both ground measurements and satellite information
- developed using 250,000 stations
- from 1986 to 2011, this datum has been adjusted four times

### World Geodetic System of 1984 (WGS 1984)

-  developed by U.S. Department of Defense using Doppler observations from the Navy Navigation Satellite System (NNSS)
- assumed to be identical to original NAD 83 in conterminous U.S.
- later iterations in 1996 and 2002 based entirely on GPS observations
- used by military and GPS systems

### Another datum coming down the pike (2022)

- the National Geodetic Survey in the U.S. is currently working on a new datum
- will rely on Global Navigation Satellite Systems (GNSS) and Global Positioning Systems (GPS)
- will use an updated geoid (hypothetical mean sea level) model

### Why Should You Care?

- for starters, you will inevitably encounter errors working with GIS data, and understanding datums and coordinate systems can help you troubleshoot those errors
- coordinates change depending on the datum and spheroid on which they're based, even if they are using the same map projection

For example, the geographic coordinates below are for a single point located within the city of Bellingham, Washington, using 3 different datums:


| DATUM  | X-Coordinate | Y-Coordinate |
| ------------- | ------------- |
| NAD_1927  | -122.466903686523 | 48.7440490722656 |
| NAD_1983  | -122.46818353793 | 48.7438798543649 |
| WGS_1984 | -122.46818353793 | 48.7438798534299 |


While it is unlikely you'll ever encounter data registered to NAD 1913, there are still data you may encounter in NAD 1927, especially if you're working with survey control data. 

In the next section, we'll explore two different kinds of coordinate systems that are used in map making, geographic and projected coordinate systems.

To learn more about Canada's unique history of surveying, check out [100 Years of Geodetic Surveys in Canada](https://www.nrcan.gc.ca/earth-sciences/geomatics/canadian-spatial-reference-system-csrs/100-years-geodetic-surveys-canada/9110).

This section references information and ideas from [What is a datum](https://oceanservice.noaa.gov/facts/datum.html), [NOAA Celebrates 200 Years](https://celebrating200years.noaa.gov/magazine/vertical_datums/welcome.html#network), [Geodetic Datums](https://gisgeography.com/geodetic-datums-nad27-nad83-wgs84/), and  [100 Years of Geodetic Surveys in Canada](https://www.nrcan.gc.ca/earth-sciences/geomatics/canadian-spatial-reference-system-csrs/100-years-geodetic-surveys-canada/9110), and [FAQ: Projection Basics](https://support.esri.com/en/technical-article/000005562).
