# Contributing

In order of decreasing accuracy, there's 3 main ways of obtaining route data:

1. Obtaining the official route `KML` (from a tracker)
1. Driving the route and pulling a `KML`/`GPX` from your GPS
1. Drawing the route manually

## Drawing the route manually

[Google My Maps](https://www.google.com/mymaps) is a Google Maps service that 
enables users to create custom maps for personal use or sharing. This route 
can be exported as a `KML` file, which can then be ingested by tools to 
generate an elevation profile.

The `KML` file can be converted into a `GPX` file containing elevation data. 
There are existing tools that do so (like 
[GPS Visualizer](http://www.gpsvisualizer.com/elevation)). Elevation profiles 
can also be generated using the Google Maps API.

The easiest way to use Google My Maps is to:

1. Create a new layer with all the landmarks and cities on the route
1. Generate directions from a **Stage Start** to a **Stage Stop**
1. Adjust the directions and drage the route through all the waypoints
1. Go through the turn-by-turn instructions and make sure the route agrees
