#Equator-Analysis

![Weather](cloud.jpg)


Our excersize was to generate a random sampling of 500 cities and test various weather factors to see their relation to the equator.

To start, I generated a list of 1200 pairs of coordinate(lat and long) pairs and ran them against Google's Geocities API. Not all coordinate pairs had a coinciding city, as many of the coordinate pairs were in the world's oceans. When we controlled for these occurences and dropped duplicates, we were left with 545 unique cities. 

In these 545 cities, we ran latitude(distance from the equator) against Wind speed, Temperature, Humidity, and Cloudiness.
