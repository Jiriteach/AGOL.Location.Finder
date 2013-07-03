AGOL.locationFinder
===================

A feature rich location finder powered by ArcGIS Online. This location finder uses the latest geocoding services
from AGOL to execute fast and accurate geosearches.

Using the latest version of the ArcGIS API for JavaScript, geosearches are executed against the API and are limited 
to New Zealand.

This location finder has been built with the requirement of embedding the results of a geosearch in mind.

Usage
-----

Example 1:
http://SERVER/Index.html?address=57 Boulcott Street Wellington

Example 2:
http://SERVER/Index.html?xMin=19454281.45514947&yMin=-5055458.88772083&xMax=19457286.38582401&yMax=-5054114.073754403&pX=19455783.92048674&pY=-5054786.480737616&basemap=1&mode=embed

Basemap 1 = Streets
Basemap 2 = Topographic
Basemap 3 = Imagery
