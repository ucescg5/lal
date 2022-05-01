**crud.js**: This file contains all the implementation of endpoints, specifying the URL of endpoints and the corresponding logic to handle the request. More specfically, logic includes parsing the request paramaters, connect to database and execute the query and return the result if necessary. Availiable endpoints are described in the table below.  
|Feature name|Description|Type|number of missing value|
|:--|:--|:--|:--|
|Date|Date and time when the incident occurred|Datetime|0|
|Primary Type|The description of crime categories defined by Illinois Unifrom Crime Reporting code|Categorical (30)<br>Including: THEFT, BATTERY, BURGLARY etc.|0|
|Domestic|Indicates whether the incident was domestic-related or not|Boolean|0|
|Ward|The ward (City Council district) where the incident occurred|Integer<br>range: 1-50|5|
|Latitude|The latitude of the location where the incident occurred|Float|790|
|Longitude|The Longitude of the location where the incident occurred|Float|790|
