---
layout: default
title: Exercise 2 - Projecting On-the-Fly
nav_order: 10
parent: Exercises
---

## Exercise 2: Projecting on the Fly

*1*{: .circle .circle-blue} From the folder containing the data you downloaded, open the **CAN_lambert** MXD.

Reset the data source if you see the red exclamation point.

Notice the units in the lower right-hand corner of the map. 

*2*{: .circle .circle-blue} Open the properties of the dataset to see what the coordinate system is.

The **Lambert Conformal Conic Projection** has characteristics which make it a good possible choice for maps of Canada.

- most commonly used projection at Statistics Canada
- retains conformality in mid-latitude regions having primarily an east-west direction
- not equal area because distortion increaseas north and south of the standard parallel (line at which there is no distortion in the map projection)

*3*{: .circle .circle-blue} Click on the **Add Data** button.

![addData.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/addData.jpg)

*4*{: .circle .circle-blue} From the window that opens, click on the **Connect to Folder** button and navigate to the Downloads folder where you downloaded the data for this workshop and click **OK**.

![connect.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/connect.jpg)

*5*{: .circle .circle-blue} From the **shapefiles** folder, add the **CAN_WGS1984** shapefile.

You will get a **Geographic Coordinate Systems Warning**.

This is because you are adding data that is in a geographic coordinate system to a map that it is in a projected coordinate system.

You can let ArcMap choose a transformation between these two different kinds of coordinate systems that will project the data you are adding "on-the-fly."

Or, if you have specific knowledge about a more appropriate transformation to use for your area or your data, you can choose the transformation yourself from the dropdown menu.

A **transformation** is a mathematical calculation used to convert coordinates referenced to one datum to coordinates referenced to another datum.

*6*{: .circle .circle-blue} We will let ArcMap handle the transformation for us. Click close.

You can see that these two datasets seem to line up perfectly and the units in the lower right appear as meters.

But projecting on-the-fly does not change the underlying data properties.

*7*{: .circle .circle-blue} Open the properties of the **CAN_WGS1984** to confirm the coordinate system properties.

Taking advantage of on-the-fly projection is okay for visualizing data within the same map.

If you want to do any kind of analysis based on area with your data, you will want to change the projection properties.

We'll go over how to do this in the next exercise.

See additional information on [transformations](https://www.esri.com/arcgis-blog/products/product/mapping/about-geographic-transformations-and-how-to-choose-the-right-one/).
