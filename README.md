Mapsforge Custom for Geopaparazzi
===================================

The mapsforge version used by geopaparazzi and based on the last version of mapsforge that supported also raster tiles.

The revision of this version is mapsforge's svn revision 2013.

Some bugfixes have been backported were applicable since then.

Build instruction
--------------------

To build the library needed for the **GeopaparazziMapsforge** project, just run the comand

{{{
mvn install
}}}

inside this project's folder.

It will create a new library:
{{{
mapsforge-map-0.3.1-SNAPSHOT-jar-with-dependencies.jar
}}}

indside the folder:
{{{
mapsforge-map/target/
}}}

Take that jar file and copy it into the **libs** folder of the **GeopaparazziMapsforge** project.


