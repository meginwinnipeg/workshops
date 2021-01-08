---
layout: default
title: Choosing the Right Projection
nav_order: 6
parent: Map Projections
---

## How to Select the Right Projection

Keep in mind that all projections either disort or preserve one of the following properties:

-	**Area/Size**
> Size of a feature on the map is the same relative to its size on the earth
-	**Shape/Angle**
> Shapes appear the same on a map as they do on the earth
> Maps that preserve shape are called *conformal*
-	**Distance**
> Line between one point on the map and another is the same distance as it is on the earth
> Equidistant maps preserve the true scale for all straight lines passing through a single location, such as Vancouver
-	**Direction/Azimuth**
> Directions from a central location to all other points on the map will be shown correctly

It is useful to think about projections grouped by the properties they preserve.

**Equal area projections**

- preserve the area of specific features
- distort shape and angle

The British Columbia (BC) **Albers Equal Area Conic** projection is an example of an equal area projection. This is used province wide when mapping land-use data and is used by [BC Environment](https://ibis.geog.ubc.ca/~brian/Course.Notes/bceprojection.html) in part because it represents the whole province on one projection plane.

Albers Equal Area Conic
![albers.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/albers.jpg)

**Conformal projections**

- preserve angles and shape
- distort area
- lat/long lines intersect at 90-degree angles on the map

The **UTM Zone 10N** projection is a good example. This could be used, for example, when mapping the location of invasive plant species in Vancouver parks.
For most GIS analysis work, equal area and conformal map projections are used. 

Lambert Conformal Conic
![lambert.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/lambert.jpg)

**Equidistant projections**

- preserve distances between points by maintaining the scale of a given dataset
- Outside the given dataset, scale becomes more distorted

The **Two-Point Equidistant** projection is one example of this and allows one to arbitrarily choose two points on the map – the straight-line distance between these points is correct and is used by airports.

**True-direction or azimuthal projections**

- preserve direction from one point to all other points by maintaining some of the great circle arcs
- can be combined with equal area, conformal, and equidistant projections

The **Lambert Equal Area Azimuthal** projection and the **Azimuthal Equidistant** projection are examples of azimuthal projections. 

### Characteristics of Map Projections

| Projection Category | Properties | Common Uses |
| :------------- | :-------------: | -------------: |
| Conformal | Preserves local shapes and angles | Topographic maps, navigation charts, weather maps |
| Equal Area | Preserves areas | Dot density maps, thematic maps |
| Equidistant| Preserves distance from one or two specified points to all other points on the map | Maps of airline distances, seismic maps showing distances from an earthquake epicenter | 
| Azimuthal | All directions are true from a single specified point (usually the center) to all other points on the map | Navigation and route planning maps |
| Compromise | No point is completely distortion free; distortion is minimized near the center and along the equator | World maps |

This section borrows ideas, phrases, and images from Sally Hermansen, [GIS Geography](https://gisgeography.com/conic-projection-lambert-albers-polyconic/), [Choosing a Map Projection](http://www.geography.hunter.cuny.edu/~jochen/GTECH361/lectures/lecture04/concepts/12%20-%20Choosing%20a%20map%20projection.html), [Understanding Distortion](http://www.geography.hunter.cuny.edu/~jochen/GTECH361/lectures/lecture04/concepts/11%20-%20Understanding%20distortion.html), and [361 Lectures](http://www.geography.hunter.cuny.edu/~jochen/GTECH361/lectures/).
