|GTIF Capability|**Short-term forecast solar/photovoltaic potential Austria**|
| - | - |
|Service Owner and Provider(s)|GeoSphere (owner and provider core algorithm), Contact: Stephan Schneider, Marc Olefs; EOX (provider of hosting platform & support in front end), Contact: Daniel Santillan|
|Abstract Description|High-resolution short-term forecast of the solar potential, providing the exact and, above all, daily up to hourly data on solar potential.|
|Stakeholder(s)|Austrian Ministry of Research and Education (BMBWF), operators of energy networks, operators of wind parks, general public (owners of photovoltaic systems and electric cars)|
|Point of Contact (POC)|TBC, BMBWF|
|Expectations|Open Government nowcasting services; Improvement of planning in energy management, grid stability, heat pumps, e-mobility.|
|Input Data|Earth observation derived meteorological forecast data (AROME), VHR-DSM; Solar algorithm is based on the BEAM GRID model calculating ground-level radiation intensity and sunshine duration with 100m spatial resolution. The service integrates a high-resolution digital surface model and considers close-up shading effects. |
|Pre-processing|Wherever offered and useful, preprocessing and feeding of the input data are implemented by calling OpenEO services.|
|Run-time|STRAHLGRID model, integration SNOWGRID & WRF-Chem; Algorithm deployed as container on GTIF/EOxHub and elastic cloud. Infrastructure: Python, Docker, Kubernetes, EOxHub, STAC, eodash, OTC.|
|Output Information Product|<p>Daily forecast time series (NetCDF)</p><p></p>|
|GTIF legacy|None|
|Service outlet, API and/or GUI functions|API: openEO (access via subscription, paid); WebUI: interactive dashboard (eodash) – public|
|Long-term perspective (governance, sustained operations, funding)|TBC: Inclusion in Geosphere Austria’s Performance Agreement (Leistungsvereinbarung) with the responsible Austrian ministerial department (BMBWF) from 2026 onwards to be provided and maintained as operationally funded capability.|
|Deviations/ Reservations|None|
|Potential Problems and Identified Solutions|None|

