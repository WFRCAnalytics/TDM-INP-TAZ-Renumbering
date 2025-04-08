# TDM-INP-TAZ-Renumbering

This Python project is used to process and reclassify Traffic Analysis Zones (TAZs) using ArcGIS and spatial data. The workflow includes loading shapefiles, spatial projection, and attribute calculations like binning features based on their geographic extents.

## Features

- Loads TAZ shapefile data from an input folder.
- Projects spatial data to UTM Zone 12N (EPSG:26912).
- Calculates `XMin`, `YMax`, and binned `YMaxBin` for each polygon.
- Prepares data for renumbering or further spatial analysis.
- Organizes intermediate and result outputs in dedicated directories.

## Key Files

- **TAZ_20210520_prenumber.shp**: Original TAZ shapefile to be processed.
- **TAZ.shp**: Processed output saved in the `results` folder.

## Requirements

- Python 3.x
- `pandas`
- `numpy`
- `arcpy` (ArcGIS Pro)
- `arcgis` Python API

