|GTIF Capability|**Energy efficiency of buildings**|
| - | - |
|Service Owner and Provider(s)|OHB Digital Services (owner and provider of algorithm), Contacts: Dietrich Kuhn, Darko Ojdanic; EOX (provider of hosting platform & support in front end), Contact: Daniel Santillan|
|Abstract Description|Service for determination of renovation and retrofitting potential of urban neighbourhoods based on satellite-derived quantification of thermal efficiency of buildings.|
|Stakeholder(s)|City administration, real estate stakeholders|
|Point of Contact (POC)|TBD|
|Expectations|Decision makers need to identify emerging trends in heat emissions from buildings quantifiably assess the effectiveness of heat emission and thermal insulation mitigation strategies; need is amplified by legislative decisions like the German law on municipal heat planning|
|Input Data|TBD Sentinel 3 LST (main – 1km, 1-4 times per day); Sentinel 2 MSI visual (auxiliary for downscaling – 10-20m, every 8 days); Copernicus Global Land Service (CGLS) LST (5km, every 1 hour); Landsat 8/9 LST (30m, every 8 days); Modis LST (1km, 1-4 times per day); Commercial like SatVu LST (3.5m, every 1 hour); Climate/Wheater from ERA5 (28km-45km, every 1 hour)|
|Pre-processing|To enhance granularity in findings, Sentinel 3 LST data will be downscaled|
|Run-time|TBD|
|Output Information Product|Aggregate LST data from several satellites from December to April when the contrast between indoor and outdoor temperatures is most pronounced; compute statistics: min, max, median, mean, …; make trend analysis over years while taking climat. factors into account|
|GTIF legacy|None|
|Service outlet, API and/or GUI functions|API: openEO (access via subscription, paid); WebUI: interactive dashboard (eodash) – public|
|Long-term perspective (governance, sustained operations, funding)|Integration into thematic information service of cities|
|Deviations/ Reservations|None|
|Potential Problems and Identified Solutions|None|

