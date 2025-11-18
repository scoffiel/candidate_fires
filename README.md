# Candidate Fires data and code
To accompany manuscript "Leveraging additional VIIRS information to improve wildfire tracking in the western US", submitted to Remote Sensing of Environment, November 2025

Input Datasets:
 - VIIRS via LAADS DAAC https://ladsweb.modaps.eosdis.nasa.gov/search/
 - NLCD land cover [https://www.mrlc.gov/data/nlcd-2019-land-cover-conus](https://www.mrlc.gov/data)
 - MASTER 2019 https://daac.ornl.gov/cgi-bin/dsviewer.pl?ds_id=1941
 - NIFC https://ftp.wildfire.gov/
 - FEDS fire perimeters https://doi.org/10.6084/m9.figshare.c.5601537.v1 ; API: [https://nasa-impact.github.io/veda-docs/notebooks/tutorials/mapping-fires.html](https://docs.openveda.cloud/user-guide/notebooks/tutorials/mapping-fires.html)

   
Output dataset: File of 874k known and candidate fire detections from two VIIRS sensors for the 95 large (>25 km2) wildfires in the western US in 2020. Candidate fires denoted as "confidence"="x" and fire_mask < 7. Links to geoparquet and csv files archived via University of Maryland DRUM: [http://hdl.handle.net/1903/34941](http://hdl.handle.net/1903/34941)
