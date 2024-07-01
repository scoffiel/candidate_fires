# candidate_fires
Code to accompany manuscript "Leveraging additional VIIRS information to improve fire tracking and emissions estimation in the Western US" 2024

WUS_Jun-Nov2020_dets_SNPP_final.csv - output dataset of Suomi-NPP VIIRS known active fire detections + additional candidate detections (denoted as "confidence"="x" and fire_mask < 7) for the 20 largest Western US fires in 2020. 

Input Datasets:
 - VIIRS via LAADS DAAC https://ladsweb.modaps.eosdis.nasa.gov/search/
 - NLCD land cover https://www.mrlc.gov/data/nlcd-2019-land-cover-conus
 - MASTER 2019 https://daac.ornl.gov/cgi-bin/dsviewer.pl?ds_id=1941
 - NIFC https://ftp.wildfire.gov/
 - FEDS fire perimeters https://doi.org/10.6084/m9.figshare.c.5601537.v1 ; API: https://nasa-impact.github.io/veda-docs/notebooks/tutorials/mapping-fires.html
