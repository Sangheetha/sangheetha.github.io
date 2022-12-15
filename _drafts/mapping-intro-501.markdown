---
layout: post
title:  "Mapping Intro 501"
date:   2022-12-13 02:04:50 -0500
---

[![Areas covered by Intro 501](/assets/images/Intro501.png){:.centered}](/Intro501){:target="_blank"}
Click the image to explore the map. 
{: style="color:gray; font-size: 80%; text-align: center;"}

[Intro 501](https://legistar.council.nyc.gov/LegislationDetail.aspx?ID=5669096&GUID=13B0175F-8FD2-4728-9734-2ACEB6D2DC5C&Options=Advanced&Search=) is a bill in the New York City Council that would allow people to report the obstruction of a bike lane/bus lane/etc by a vehicle, and creates a new civil penalty of a $175 ticket for that offense. However, it would only apply to vehicles within 1320 feet of a school building.

I made an [interactive map](/Intro501) of the relevant areas.

<!--more-->

The map was made using [geopandas](https://geopandas.org). More details are in the [Github repository](https://github.com/Sangheetha/Intro501). School locations were taken from the [2019-2020 data](https://data.cityofnewyork.us/Education/2019-2020-School-Locations/wg9x-4ke6) on the NYC OpenData site, the latest year that I could find.

A few notes:

* The covered area is ~258km<sup>2</sup> (99 square miles), about 32% of NYC's landmass. A follow-up question on my mind is what proportion of NYC streets or even specifically bike lanes are covered.  
* There's a [school](https://en.wikipedia.org/wiki/New_York_Harbor_School) on Governor's Island!
* I certainly didn't have a mental model of the distribution of schools across the city until I worked on this - an initial plan to also display the individual school locations on this map was scuffed because of the sheer noise the highest density areas would have added.

