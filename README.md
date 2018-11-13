# admin-boundaries

Geojson files of global admin boundaries, culled from [GADM](https://gadm.org) and transformed from .shp files to geojsons with the [Mapshaper](https://mapshaper.org) CLI. 

Hi-res files have no simplication. 

Lo-res files have been simplified with the Mapshaper CLI using --simplify keep-shapes option. 
Simplification levels used were Admin0: 50%, Admin1: 10%, Admin2: 5%, with lower percentages indicating greater simplification. 

The following hi-res files are not included as they exceed Github's 100MB file size limit:
+ hi-res/Admin1/gadm36_CAN_1.json
+ hi-res/Admin2/gadm36_AUS_2.json
+ hi-res/Admin2/gadm36_CAN_2.json
+ hi-res/Admin2/gadm36_USA_2.json
+ hi-res/Admin3/gadm36_ECU_3.json
+ hi-res/Admin3/gadm36_IDN_3.json
+ hi-res/Admin3/gadm36_POL_3.json
+ hi-res/Admin3/gadm36_PRT_3.json
+ hi-res/Admin3/gadm36_THA_3.json
+ hi-res/Admin4/gadm36_BGD_4.json
+ hi-res/Admin4/gadm36_IND_4.json
+ hi-res/Admin4/gadm36_ZAF_4.json
+ hi-res/Admin4/gadm36_RWA_5.json