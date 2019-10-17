## BC Geographic Warehouse Web Feature Service Demonstration

### Description
The index.html file displays a web map of the 2018 Wildfire Perimeters in British Columbia, Canada. This demonstration shows how to generate a JSON file from the BC Geographic Warehouse (BCGW) via a Web Feature Service (WFS). The json file was loaded to github by [geojson.io](http://geojson.io) and the html file was written by Rob Oostlander to reference the json file as a javascript file.

### Hyperlink To Web Map Demonstration
https://roboost.github.io/index.html

### Web Feature Service Syntax
http://openmaps.gov.bc.ca/geo/pub/WHSE_LAND_AND_NATURAL_RESOURCE.PROT_HISTORICAL_FIRE_POLYS_SP/ows?service=wfs&version=2.0.0&request=getfeature&typename=pub:WHSE_LAND_AND_NATURAL_RESOURCE.PROT_HISTORICAL_FIRE_POLYS_SP&CQL_FILTER=FIRE_YEAR=2018&outputFormat=json&srsName=EPSG:4326

### Web Feature Service Parameters
* Service: WFS
* Version: 2.0.0
* Dataset: [WHSE_LAND_AND_NATURAL_RESOURCE.PROT_HISTORICAL_FIRE_POLYS_SP](https://catalogue.data.gov.bc.ca/dataset/fire-perimeters-historical)
* Query: FIRE_YEAR=2018
* Output Format: json
* Map Projection: [EPSG:4326](https://spatialreference.org/ref/epsg/wgs-84/)

### License
    Copyright 2019 BC Provincial Government

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
