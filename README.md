🔍 Project Description: FireDataToolkit
The FireDataToolkit is a reproducible and extensible Python-based toolkit designed for downloading, preprocessing, and formatting urban fire remote sensing data. It supports daily fire risk modeling and consensus decision frameworks such as HOD-CC-CRP, and is tailored for global urban applications across diverse geographical and climatic regions.

This toolkit integrates open-access satellite data (e.g., MODIS, VIIRS, Sentinel, Landsat) and includes:

🔥 Fire hotspot download scripts (NASA FIRMS API)

📍 Urban-level fire aggregation and feature extraction

🛰️ Google Earth Engine templates for visual heatmaps

🌐 GeoJSON region generators for spatially referenced cities

The preprocessing pipeline includes:

Spatiotemporal data fusion of MODIS (1 km) and VIIRS (375 m) fire products,

Feature extraction (e.g., fire frequency, FRP, initial opinion values),

Spatial aggregation to city-level or region-level polygons using shapefiles,

Export of modeling-ready formats such as Excel or CSV.

All code is open-source and includes sample templates to ensure easy adaptation to new cities, regions, and time ranges.
