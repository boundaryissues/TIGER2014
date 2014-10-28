openpolygons/TIGER
==================
This project contains GeoJSON formated files built from US Census Bureau
TIGER boundary data. These files currently consist of:

State and County polygons directly converted from TIGER 2014 shapefiles
          into GeoJSON using ogr2ogr.

American Indian Tribal Subdivisions converted to GeoJSON

County Subdivision and Place polygons divided according to the following
          process:
		1) Split the TIGER shapefiles by LSAD (Legal/Statistical
		   Are Description) code. These shapefiles are provided.
		2) Convert the TIGER shapefiles to GeoJSON format files.
		   These GeoJSON files are provided

Future versions may contain additional Feature attributes, possibly
including OpenStreetMap format admin polygon tagging.

The county files have been divided up to conform to the "special sub
regions" of the US as used by the GeoFabrik OpenStreetMap extracts.
The GeoFabrik extracts may be found here: 

[http://download.geofabrik.de/north-america.html](http://download.geofabrik.de/north-america.html)
