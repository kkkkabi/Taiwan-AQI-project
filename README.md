# Taiwan Air Quality Map – QGIS

## Overview

This project is a QGIS-based visualisation of air quality data across Taiwan. The aim was to create a clear thematic map showing the distribution of air quality information across different areas of Taiwan.

The project was completed as a practical learning exercise using QGIS to develop experience in spatial data processing, spatial interpolation, raster analysis, and map production.

## Data Source

The air quality data was obtained from the **Taiwan Government Open Data Portal**:

https://data.gov.tw/dataset/40448

The data was imported into QGIS and processed to create the final air quality visualisation.

## Project Process

The project involved importing the air quality data into QGIS, joining the data with geographic information, and applying **Inverse Distance Weighting (IDW)** to perform spatial interpolation.

The resulting raster was clipped to the boundary of Taiwan using **Clip Raster by Mask Layer**. Raster rendering and symbology were then adjusted to visually represent the air quality distribution.

![Taiwan Air Quality Map](Images/1.1%20Taiwan%20Air%20Quality.png)

![Taiwan Air Quality Map](Images/1.2%20Taiwan%20Air%20Quality%20-%20join%20table.png)


A QGIS **Print Layout** was created to prepare the final map for presentation. The layout includes a map, legend, scale bar, north arrow, and coordinate grid.
The completed map was exported as an image, and the QGIS project data was saved as a **GeoPackage**.

![Taiwan Air Quality Map](Images/1.3%20Taiwan%20Air%20Quality%20-%20Export%20map%20as%20image%20with%20coordination.png)

## Tools and Technologies

- QGIS
- QuickMapServices
- ESRI Shaded Relief basemap
- CSV data import
- Attribute Join
- Inverse Distance Weighting (IDW)
- Raster clipping
- Raster symbology and rendering
- QGIS Print Layout
- Map legend
- Scale bar
- North arrow
- Coordinate grid
- Map export
- GeoPackage

## Reference

This project was completed as a learning exercise based on the following GeoLab QGIS tutorials:

- [GeoLab – QGIS Air Quality Map Tutorial](https://www.spatialgeolab.com/qgis-tutorial-part2-aqi-map/)
- [GeoLab QGIS Tutorial Series – YouTube](https://www.youtube.com/playlist?list=PL4V0A_6nZ76BzilmJVhb9Fqg0rMsVykgZ)

The project was developed to build practical experience with QGIS, spatial data processing, spatial interpolation, raster analysis, and map production.
