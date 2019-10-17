<!DOCTYPE html>

<html lang="en">

<head>
    
    <!-- browser tab title -->
    <title>2018 Wildfires in BC</title>

    <!-- metadata -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="2018 Wildfire Perimeters in British Columbia Canada">
    <meta name="keywords" content="British Columbia,Wildfire,Fires">
    <meta name="author" content="Rob Oostlander" />
    
</head>

<body>

    <!-- header text -->
    <h4><font face="verdana">2018 Wildfire Perimeters in British Columbia Canada</font></h4>

    <!-- load javascript of map -->
    <script src="https://gist.github.com/roboost/80b9c3beb79244b74db625fb78f7e88d.js"></script>
    
    <!-- text and references -->
    <p><font face="verdana" font size="2">Web Feature Service (WFS) from the BC Geographic Warehouse (BCGW) to generate a JSON file of wildfire perimeters, and display only the 2018 wildfire perimeters (via a CQL Filter).</font></p>
    <p><font face="verdana" font size="2">Syntax <br><a href="http://openmaps.gov.bc.ca/geo/pub/WHSE_LAND_AND_NATURAL_RESOURCE.PROT_HISTORICAL_FIRE_POLYS_SP/ows?service=wfs&version=2.0.0&request=getfeature&typename=pub:WHSE_LAND_AND_NATURAL_RESOURCE.PROT_HISTORICAL_FIRE_POLYS_SP&CQL_FILTER=FIRE_YEAR=2018&outputFormat=json&srsName=EPSG:4326">http://openmaps.gov.bc.ca/geo/pub/WHSE_LAND_AND_NATURAL_RESOURCE.PROT_HISTORICAL_FIRE_POLYS_SP/ows?service=wfs&version=2.0.0&request=getfeature&typename=pub:WHSE_LAND_AND_NATURAL_RESOURCE.PROT_HISTORICAL_FIRE_POLYS_SP&CQL_FILTER=FIRE_YEAR=2018&outputFormat=json&srsName=EPSG:4326</a></font></p>
    <p><font face="verdana" font size="2">Map Source <br><a href="https://gist.github.com/roboost/80b9c3beb79244b74db625fb78f7e88d">https://gist.github.com/roboost/80b9c3beb79244b74db625fb78f7e88d</a></font></p>
    <p><font face="verdana" font size="2">Data Source <br><a href="https://catalogue.data.gov.bc.ca/dataset/fire-perimeters-historical">https://catalogue.data.gov.bc.ca/dataset/fire-perimeters-historical</a></font></p>
    <p><font face="verdana" font size="2">Generated using <a href="http://geojson.io">geojson.io</a></font></p>

</body>
  
</html>