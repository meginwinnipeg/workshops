---
layout: default
title: Map Projections
nav_order: 5
has_children: true
---

## Map Projections

Let's revisit the main takeaways about projections that we learned from the video at the beginning of class. 

See if you can answer the questions below before you reveal the correct answer by clicking on the arrow.

<details>
<summary>A projection is a mathematical equation to flatten data from a 3D surface onto a ____ plane. </summary>

2D.
</details>
<br>

<details>
<summary>All projections accurately represent the sizes of the continents. True or false. </summary>

False. Every projection is distorted in some way, and some distort the sizes of different land masses a lot.
</details>
<br>

<details>
<summary>Who can identify the projection below and which properties it preserves and distorts?</summary>

The Mercator projection preserves direction and shape. In web maps, it's also good for generating map tiles because it projects the world into a square evenly subdivided across zoom levels, and 90 degree turns appear as right angles. The Mercator projection distorts size, or area. Notice the classic example of comparing the size of Greenland to the continent of Africa in this map.
</details>
<br>

![mercator](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/mercator.jpg)

### Terminology

Remember latitude and longitude? In the context of projections, it may be useful to think of these as lines that have another name to describe them.

Lines of latitude are also called parallels and run east-west parallel to the equator.

Lines of longitude are called meridians and run north-south between the North and South Poles.

![parallels](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/parallels.jpg)

Map projections are typically categorized into three different types, based on the visualization of light shining through through the earth onto a surface, where the surface is a plane, a cylinder, or a cone, respectively.

![lightSource2.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/lightSource2.jpg)

There are also those who [recommend](https://en.wikipedia.org/wiki/Map_projection#Projections_by_surface) dispensing with the three projection categories because they don't account for all projections and can lead to misunderstanding and confusion.

Nevertheless, these three categories can be useful models for illustrating some map projections. 

Projections based on each surface can be used for mapping particular parts of the world.

Where each respective surface touches the earth is also the area of the world portrayed most accurately using one of the three surfaces described below.

### Planar/Azimuthal Projections

![planar.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/planar.jpg)

- area and shape distortion are circular around the point of contact, so these projections accommodate circular regions better than rectangular regions
- point of contact can be anywhere on earth's surface but north and south poles most common point of contact
- longitude lines converge at the north pole and radiate outward
- latitude lines appear as a series of concentric circles
- distances from or through the map center are true
- directions from the map center to any other point are also held true
- any other measure of distance or direction will not be true
- not good for world maps because only show about half of earth at a time

![azimuth.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/azimuth.jpg)

### Cylindrical Projections

![cylindrical](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/cylindrical.jpg)

- Mercator projection is a cylindrical projection with line of tangency at equator
- produce maps with straight, evenly-spaced meridians and straight parallels that intersect meridians at right angles
- touch the globe along a line rather than a point, as with planar
- display true direction along straight lines
- a cylinder wrapped around a globe will cover more of the globe than either a plane or cone can
- tend to be better for world maps but still can't show All of earth's surface

![cylindrical2.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/cylindrical2.jpg)

### Conical Projections

![conic](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/conic.jpg)

- used for midlatitude zones that have an east-to-west orientation (because cone wider than it is tall)
- single cone cannot show the whole globe
- conic maps show only a sector of a complete circle…they don't develop into a complete circle
- produce maps with straight converging longitude lines and concentric circular arcs for latitude lines
- simplest conic projection contacts the globe along a single latitude line, a tangent, called the standard parallel
- distortion increases north and south of the standard parallel

![conic2.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/conic2.jpg)

In the next section, we'll go over choosing the right projection for your data.

This section uses ideas and images from [Wikipedia](https://en.wikipedia.org/wiki/Map_projection#Projections_by_surface), [Projected Coordinate Systems](https://mgimond.github.io/Spatial/coordinate-systems.html#projected-coordinate-systems), [Understanding Map Projections](https://kartoweb.itc.nl/geometrics/Map%20projections/Understanding%20Map%20Projections.pdf), [Light Source Metaphor](https://www.mdpi.com/2220-9964/8/4/162/pdf), and [361 Lectures](http://www.geography.hunter.cuny.edu/~jochen/GTECH361/lectures/), and [Map Projections](https://faculty.kutztown.edu/courtney/blackboard/Physical/05Project/project.html).
