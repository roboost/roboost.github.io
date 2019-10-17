## BC Geographic Warehouse Web Feature Service Demonstration

### GitHub Pages Example
https://roboost.github.io/index.html

### Description
The index.html file displays a web map of the 2018 Wildfire Perimeters in British Columbia, Canada. This demonstration shows how to generate a JSON file from the BC Geographic Warehouse (BCGW) via a Web Feature Service (WFS). The json file was loaded to github by [geojson.io](http://geojson.io) and the html file was written by Rob Oostlander to reference the json file as a javascript file.

### Web Feature Service Syntax
http://openmaps.gov.bc.ca/geo/pub/WHSE_LAND_AND_NATURAL_RESOURCE.PROT_HISTORICAL_FIRE_POLYS_SP/ows?service=wfs&version=2.0.0&request=getfeature&typename=pub:WHSE_LAND_AND_NATURAL_RESOURCE.PROT_HISTORICAL_FIRE_POLYS_SP&CQL_FILTER=FIRE_YEAR=2018&outputFormat=json&srsName=EPSG:4326

### Web Feature Service Parameters
* Service: WFS
* Version: 2.0.0
* Dataset: [WHSE_LAND_AND_NATURAL_RESOURCE.PROT_HISTORICAL_FIRE_POLYS_SP](https://catalogue.data.gov.bc.ca/dataset/fire-perimeters-historical)
* Query: FIRE_YEAR=2018
* Output Format: json
* Map Projection: [EPSG:4326](https://spatialreference.org/ref/epsg/wgs-84/)

### Web Map Source
https://render.githubusercontent.com/view/geojson?commit=6076eae8ea4d1e49692c68761db4307cc5c5bcea&amp;enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f676973742f726f626f6f73742f38306239633362656237393234346237346462363235666237386637653838642f7261772f363037366561653865613464316534393639326336383736316462343330376363356335626365612f6d61702e67656f6a736f6e&amp;nwo=roboost%2F80b9c3beb79244b74db625fb78f7e88d&amp;path=map.geojson&amp;repository_id=97289045&amp;repository_type=Gist#8d20a62b-4c44-4d89-8a0e-ce83aaa88987\

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
