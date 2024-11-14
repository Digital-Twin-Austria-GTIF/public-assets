﻿|GTIF Capability|**Short-term and seasonal water runoff forecast service**|
| - | - |
|Service Owner and Provider(s)|TIWAG (owner and provider core algorithm), Contact: Johannes Schober; EOX (provider of hosting platform & support in front end), Contact: Daniel Santillan|
|Abstract Description|Satellite-augmented, improved forecasts for water runoff in Alpine regions|
|Stakeholder(s)|Hydroelectric power plant operators, environmental monitoring, tourism, water management and disaster protection organizations|
|Point of Contact (POC)|Johannes Schober, TIWAG; Martin Reichhart, Österreich Werbung / Austria Tourism|
|Expectations|In the capability “runoff forecast service”, the snow area and snow water equivalent information provided in the capability “Snow Maps in Alps (Cover, Wetness)” is compared with the corresponding data that the hydrological forecast system has calculated based on meteorological data from GeoSphere Austria. For this purpose, the snow data is provided in 100m resolution in geotiff format and is also visualized in the GTIF platform. This enables a qualitative comparison of the different modelled snow areas with the measured Sentinel snow areas. An algorithm based on confidence tables compares and quantitatively evaluates the simulated snow areas and snow water equivalent distributions in the TIWAG storage catchment areas. This significantly improves the ability to assess the uncertainties of the discharge forecasts. By comparing the different data, new snow distributions can also be derived and form the basis for additional runoff forecast calculations.|
|Input Data|Snow Maps in Alps (Cover, Wetness); hydrological forecasts|
|Pre-processing|Wherever offered and useful, preprocessing and feeding of the input data are implemented by calling OpenEO services.|
|Run-time|Algorithm deployed as container on GTIF/EOxHub and elastic cloud.|
|Output Information Product|TBD|
|GTIF legacy|None|
|Service outlet, API and/or GUI functions|<p>Two access methods are provided to make the results of the snow modelling chain available to customers. Firstly, programmatic access is provided to transfer the data directly into the workflows of stakeholders. The “Process API” offers programming language-independent access to the results of the snow modelling chain, which are stored in the GTIF data storage and made available via the BYOC API. This means that the user process does not have the entire data archive to integrate the results into its workflow but can directly access the data in the area and at the time that interests it. This cloud-focused approach enables rapid iteration and rapid prototyping for hydrological integration Models of the actor. In addition, two options will be available for visualization: Access to snow modelling results via the Copernicus Data Space Ecosystem's OGC-compliant APIs, which enable streaming the data directly into a GIS environment. Access to data in the Copernicus Browser for visualization of snow modelling results in the browser along with open Copernicus data. Through this interface, the interested party can use all the basic analysis tools available in the Copernicus browser (layer comparison, interactive navigation, measurement tools, etc.).</p><p>The public GTIF-AT portal will display: TBD.</p>|
|Long-term perspective (governance, sustained operations, funding)|Information service for short-term and seasonal discharge forecasts to support the applications of water level management in reservoirs, prediction of electricity generation potential, and flood forecasting. The GTIF capabilities should be made technically integrable with the information systems of the users (core processes). In particular, these are: Specialist information systems of the energy supply companies (seasonal runoff forecast for improved storage management), especially that of TIWAG. Flood forecasting systems, especially that of the Tiroler Inn, which is operated jointly by the state of Tyrol and TIWAG. It is intended to develop drafts for subscription plans and license models regarding the availability and scope of services of the GTIF capabilities. The on-demand service shall be promoted to other hydroelectric plant operators, water management or disaster protection organizations as well.|
|Deviations/ Reservations|None|
|Potential Problems and Identified Solutions|None|
