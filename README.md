openpolygons/TIGER
==================
This project contains GeoJSON formated files built from US Census Bureau
TIGER boundary data. These files currently consist of State and County
Polys directly tranlated from TIGER 2014 shapefiles using ogr2ogr.
Future versions may contain additional Feature attributes, possibly
including OpenStreetMap format admin polygon tagging.

Future files will include reorganized version of TIGER county subdivsion
and places files, restructured in order to be more useful to geocoders
and renderers. For example, statistical areas such as CDPs will be
separated from legal boundaries.

The county files have been divided up to conform to the "special sub
regions" of the US as used by the GeoFabrik OpenStreetMap extracts.
The GeoFabrik extracts may be found here: 

[http://download.geofabrik.de/north-america.html](http://download.geofabrik.de/north-america.html)
