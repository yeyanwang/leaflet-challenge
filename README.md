# Earthquake Dashboard

## Background 
  The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

  The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. 

## Description 
This is an interative dashboard to explore the ["USGS All Earthquakes from the Past 7 Days" dataset](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson). This dashboard contains a map to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Features
**The Map**

  The map is set to centered at GeoCoordinate [37.6000, -95.6650] (the United States), with a zoom level of 4.5. Each marker on the map indicates an incident of earthquake. The map is zoomable. You can also move the map by click and drag. 
  <img width="959" alt="image" src="https://user-images.githubusercontent.com/120543690/229026806-59a5c463-8957-407b-812c-732f55437c0b.png">

**Markers**

  - The size of the marker scales with the earthquake magnitude level 
  - The color of the marker changes with the depth level
  - Each marker has a tooltip with the Magnitude, the location and depth
  
**Legend**

  - The legend showing the depth and their corresponding color

## Credits
- Leaflet 
- D3
- USGS
- My Instructor: Kevin Lee
