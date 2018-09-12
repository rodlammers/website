+++
title = "Map-a-Flood: The countyfloods package"
date = 2017-10-30T00:00:00
lastmod = 2017-10-30T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = ["rivers", "floods", "R"]
summary = ""

[header]
image = "headers/hurricanes.jpg"
caption = "Hurricanes Katie, Irma, and Jose. Image Credit: NASA, Public Domain."

# Does this page contain LaTeX math? (true/false)
math = true

[[gallery_item]]
album = "1"
image = "Texas_Gages.gif"
caption = "This is a test."

[[gallery_item]]
album = "1"
image = "Texas_Counties.gif"
caption = ""

[[gallery_item]]
album = "2"
image = "Florida_Gages.gif"
caption = ""

[[gallery_item]]
album = "2"
image = "Puerto_Rico_Gages.gif"
caption = ""
+++
This fall, one hurricane after another battered the U.S. – Harvey in Texas, Irma in Florida, and Maria in Puerto Rico. In addition to the damage from wind and storm surge, heavy rainfall from these storms caused significant flooding. Photographs provided stark visuals of just how extensive this flooding was, but it is also important to quantify their impact. Last year, Dr. Brooke Anderson and I developed an R package – [countyfloods](https://cran.r-project.org/web/packages/countyfloods/index.html) – to analyze flood magnitude using data from stream gages maintained by the US Geological Survey (USGS)[^1].

R is an amazing (and free) software tool for data analysis and visualization. One of the best things about R is that anyone can write and submit “packages” – basically little programs – that are then available to anyone. Our package utilizes available stream flow data to show how big floods are during specific time periods.

For example, I used the package to map flooding in Texas from Hurricane Harvey. Before the hurricane, none of the rivers in Texas were high. As the days progressed, most of the southeastern portion of the state had major or extreme flooding which took over a week to dissipate – and lingered even longer around Houston. In addition to examining the impacts by gage (or by river), the package can also summarize flood impacts for individual counties. Looking at the county level can be useful for emergency responders allocating resources, governors issuing disaster declarations, and researchers looking to assess the impacts of floods.

{{< gallery album = "1" title = "Maps showing flooding in Texas following Hurricane Harvey. Floods are shown by river gage (left) and summarized by county (right)." >}}

This last point was a major motivation for developing this package. Floods can have significant effects on human health, either directly from exposure to contaminated floodwater[^2] or indirectly from the physical and mental strain of weathering these disasters. These types of health impacts have been demonstrated for other weather-related disasters (e.g. extreme heat waves) but flooding has received less attention. Some researchers here at Colorado State are interested in exploring that very question. They are using nationally available health data to see if there are any correlations between major flood events and hospitalizations, reports of mental health distress, and even death. Since all these health data are available by county, it is important to have flood data at that scale as well.

But let’s look back at the recent hurricanes. Flooding in Florida following Hurricane Irma looked similar to what we saw in Texas. Most of the peninsula was hit hard by the storm and saw substantial flooding as a result. The picture in Puerto Rico, however, was much different. You’ll notice that many of the gages disappear after Hurricane Maria struck. This is because flows were so strong that the equipment either malfunctioned, or was destroyed. Still, many of the gages that remained – mostly in the eastern portion of the island – didn’t see much flooding. This is partly because in this mountainous terrain, the floods passed too quickly to be recorded. The package calculates flooding using an average daily river flow rate, so high flows may come and go over the course of several hours while the daily average remains below the flood threshold.

{{< gallery album = "2" title = "Maps showing flooding in Florida following Hurricane Irma (left) and in Puerto Rico following Hurricane Maria (right)." >}}

Floods are important natural processes, but they may be getting more frequent and more destructive as our cities grow and rainfall patterns change. The river flow data collected by the USGS is invaluable to river managers and researchers. Hopefully the countyfloods package will make it just a little easier to analyze this wealth of information.

[^1]: We couldn’t have developed this package without the amazing [dataRetrieval](https://cran.r-project.org/web/packages/dataRetrieval/index.html) package developed by the USGS which makes it easy to access all USGS stream data.

[^2]: This was a concern in Texas as several [toxic waste sites](http://www.chicagotribune.com/g00/news/nationworld/ct-harvey-toxic-superfund-sites-20170902-story.html?i10c.encReferrer=aHR0cDovL3d3dy5lbmdyLmNvbG9zdGF0ZS5lZHUv&i10c.ua=1&i10c.dv=14) were flooded, leaching contamination into the floodwaters.