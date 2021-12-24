# Geospatial-Data-Analysis

Install Postgres+PostGIS on your laptop.
After you install Postgres+PostGIS, you can create a DB, create a table, insert data, query it.
Use the spatial db software to execute the following two spatial queries that you'll write:
• compute the convex hull for your points [a convex hull for a set of 2D points is the smallest convex polygon that contains the point set].
   Use the query's result polygon's coords, to create a polygon in your .kml file (edit the .kml file, add relevant XML to specify the KML polygon's coords). Load this into Google          Earth, visually verify that all your points are on/inside the convex hull, then take a screenshot.
• compute the four nearest neighbors from a location of your choice, say PT. Use the query's results, to create four line segments in your .kml file: line(PT,neighbor1), line(PT,neighbor2), line(PT,neighbor3), line(PT,neighbor4). Verify this looks correct, using Google Earth, take a snapshot.

Using any point of choice as the center, compute (don't/can't use GPS!) a set (sequence) of lat-long (ie. spatial) co-ordinates that lie along a pretty Spirograph curve.
