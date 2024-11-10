|GTIF Capability|**Urban evapotranspiration maps**|
| :- | :- |
|Service Owner and Provider(s)|Sistema (service owner), Contacts: Stefano Natali, Leon Stärker; EOX (provider of hosting platform & support in front end), Contact: Daniel Santillan|
|Abstract Description|Forecast service to provide information about urban open green spaces with particularly good evaporation (demo city is Vienna) |
|Stakeholder(s)|Administrative bodies of cities, Grünstattgrau (GSG)|
|Point of Contact (POC)|Marie-Luise Bruckner, UIV|
|Expectations|ET data created directly from Sentinel-2 observations over a defined period of time (monthly, bi-monthly, seasonal, yearly)|
|Input Data|Data cube containing time-series of Sentinel-2 Level 2A ECOSTRESS data, ESA World-cover (10m) Copernicus Digital Terrain data, In-situ data for calibration/validation of evapotranspiration |
|Pre-processing|Generation of geospatial data cube, conversion into Cloud Optimized GeoTIFF|
|Run-time|Evapotranspiration is estimated at high spatial resolution (10 meters) over the entire region of interest using data fusion/machine learning techniques using data from the Copernicus Sentinel-2 mission and NASA's ECOSTRESS mission. Sentinel-2's capabilities are used as input and those of NASA's ECOSTRESS mission as reference. The aim of the deep learning model is to determine the relationship between the ECOSTRESS thermal infrared (TIR) ​​bands and the 13 VIS-MIR bands of Sentinel-2 and to analyse ET data using additional context layers (e.g. Land cover, digital terrain model). Validation is carried out in the partner project by setting up ET experiments in climate chambers and measuring the ET of different plant communities throughout the year under different weather conditions to verify the accuracy of the product. Algorithm, to be deployed as container on GTIF/EOxHub and elastic cloud|
|Output Information Product|Model to replace the high-resolution ECOSTRESS data with which ET data can be created directly from Sentinel-2 observations. The results are validated and used by those involved in the project (Grünstattgrau, BOKU). In addition, the visualization requirements are collected and tools for data exploration and “narrative stories” are created to show the possibilities of the new data set (SISTEMA, GSG, EOX).|
|GTIF legacy|None |
|Service outlet, API and/or GUI functions|On-demand provision of ET maps for specified locations via GTIF-AT front end (interactive WebGIS).|
|Long-term perspective (governance, sustained operations, funding)|ET-as-a-Service available for customers at any European city|
|Deviations/ Reservations||
|Potential Problems and Identified Solutions|No problems identified yet|

