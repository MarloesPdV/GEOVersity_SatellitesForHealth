# GEOVersity_SatellitesForHealth
Materials for the exercise belonging to the lesson: "Satellites for Health" of the GEOVersity MOOC on Planetary Health

The code is based on an exercise developed for the elective course "Satellites for GeoHealth" for 2nd years' MSc students of the ITC faculty of the University of Twente, the Netherlands. Data used in the exercise are HAQAST Sentinel-5P TROPOMI Nitrogen Dioxide (NO2) GLOBAL Monthly Level 3 0.1 x 0.1 Degree Gridded Data Version 2.4 (HAQ_TROPOMI_NO2_GLOBAL_M_L3), downloaded from GES DISC (see: https://disc.gsfc.nasa.gov/datasets/HAQ_TROPOMI_NO2_GLOBAL_M_L3_2.4/summary). A simple python script (MakeTimeseries_HAQ_NO2.ipynb) was used to convert the data from hdf to netCDF and collate the monthly files into yearly files.

The exercise requires the packages xarray, numpy, matplotlib and statsmodels to run; the MakeTimeseries script additionally requires datetime (but not matplotlib or statsmodels).

Enjoy the ride!
Marloes on Friday the 13th of September, 2024
