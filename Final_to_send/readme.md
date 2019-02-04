# Movement and Demographics/Rent Leaflet JS Maps
## Ethan Burrell Summer/Fall 2018
* At the top of each HTML, there is a ```<script src="puma-data.js">``` This .js file
holds all of the data for the the pumas in a variable called pumaData. (I just
  copy and paste in a json after var pumaData = {...}). The data in question is
  joined in an GIS software with spatial data, and then you put the .shp files into
  a site like mapshaper.org (shapefiles to geoJson coverter) and it spits out
  all of the data in a geoJson format. You put this in your puma-data.js file
  saved as the variable pumaData
* I documented the code, but generally it has a lot of global varibles with function
calls that are able to change the values of them, this allows easy function calls to be made to
change the values in the maps.
