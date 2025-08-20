# candidate_fires
Code to accompany manuscript "Leveraging additional VIIRS information to improve wildfire tracking in the western US", submitted to Remote Sensing of Environment, August 2025


Input Datasets:
 - VIIRS via LAADS DAAC https://ladsweb.modaps.eosdis.nasa.gov/search/
 - NLCD land cover https://www.mrlc.gov/data/nlcd-2019-land-cover-conus
 - MASTER 2019 https://daac.ornl.gov/cgi-bin/dsviewer.pl?ds_id=1941
 - NIFC https://ftp.wildfire.gov/
 - FEDS fire perimeters https://doi.org/10.6084/m9.figshare.c.5601537.v1 ; API: https://nasa-impact.github.io/veda-docs/notebooks/tutorials/mapping-fires.html

   
Output dataset: File of 874k known and candidate fire detections from two VIIRS sensors. Candidates denoted as "confidence"="x" and fire_mask < 7 for the 95 largest Western US fires in 2020. Links to geoparquet and csv files (can host on Zenodo or other repository for final pub). 
- https://drive.google.com/file/d/1Ud4irm2BtU1r6jyj7EezQJp4923K4IXV/view?usp=sharing (CSV)
- https://drive.google.com/file/d/1roeXOJG6IwqiDKCJbuMIM9R8pX4Ippxu/view?usp=sharing (GeoParquet)
