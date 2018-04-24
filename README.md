# nativeamericanlands
American Indian/Alaska Native/Native Hawaiian Area polygon data was downloaded from the [US Census](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2017&layergroup=American+Indian+Area+Geography)

## Data Conversion
Data was first downloaded as a shapefile. Then:
1) SHP was converted to GEOJSON using mapshaper
2) GEOJSON was simplified using mapshaper
3) simplified GEOJSON was converted to a TOPOJSON

## File sizes
| File name | File Size (kb) |
| ----- | ----- |
| tl_2017_us_aiannh.shp | 22,602 |
| tl_2017_us_aiannh.json | 13,332 |
| tl_2017_us_aiannh_simplify.json | 7,068 |
| tl_2017_us_aiannh_simplify.topojson | 2,231 |
