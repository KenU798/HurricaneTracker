# Interactive Hurricane/Topical Storm Tracker using Folium

by [Ken Urquhart](https://linkedin.com/in/kenu)

Publicly available data from the National Hurricane Center:

https://www.nhc.noaa.gov/gis/

provides a lot of useful information about tropical storms and hurricanes that you can create yourself instead of waiting for updates from news services.

Find out if you are in the latest predicted path? What the winds might be? Are you in a storm surge area?

This notebook shows you how to:

* Work with files no matter what OS you are running on using `pathlib`
* Work with files (and ZIP'd files) located on Internet servers using `urllib` and `zipfile`
* Work with `shapely` and `KML` geographic data using `geopandas`...
* ...including the (lesser known) tricks for working with `KML` and `KMZ` geographic files
* Create interactive maps or geographic data using `folium` and `folium plugins`
* Work with color maps and tooltips to annotate maps with geographic information
* Build layered maps when you have a lot of information to visualize
* Use of `regular expressions` to clean up data columns in `pandas` and `geopandas`

# >> Artemis 1 and Tropical Storm / Hurricane Ian

As of Sunday September 25, 2022 (initial commit of this notebook), Tropical Storm Ian is threatening to become a hurricane and may pass near the Kennedy Space Center (KSC). Artemis 1 is on Launch Pad 39B and may be returned to the Vehicle Assembly Building to ride out the storm.
I've added a marker for Launch Pad 39B so you can see how close TS/Hurricane Ian may come to the KSC and what kinds of winds are expected.
