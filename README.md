# leaflet-challenge

# Method
Part 1-
Attempted Circle Markers size and color. Could not figure out how to grab the third option after latitude and longitude of coordinates.

function markerSize(mag) {
  return Math.sqrt(mag) * 50;
}
function markerColor(coordinates[2]) {
  var color = "green";
  if (coordinates[2]>10) color = "orange";
  else if (population>50) color = "red";
  return color;
}

# References
Dataset created by the United States Geological Survey. https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php