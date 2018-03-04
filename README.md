# Data Visualization on Map Demo (Taiwan)
by Jack Wu

## Requirements
1. Nodejs (npm)
2. Express
3. mapshaper
4. d3js

# Install
```aidl
npm install
```

# Run
```aidl
npm start
```

## Development Setup
1. Install Nodejs (ask google)
2. Setup a Express project (ask google)
3. Install mapshaper
    ``` 
    npm install -g mapshaper
    ```
4. Download map from opendata.gov.tw and then unzip it
    ```
    https://data.gov.tw/node/7442
    ```
5. Run command (.shp and .dbf files in the same path)
```aidl
mapshaper [COUNTY].shp -o encoding=big5 format=topojson [COUNTY].json
```
6. Put the output file in a reachable path from browser (html file)

## Demo Description
1. /test.html: color varies from population of counties
2. /test2.html: color indication and name showing for a county on hover event

## References:
1. http://blog.infographics.tw/2015/04/visualize-geographics-with-d3js/
2. https://dotblogs.com.tw/explooosion/2017/06/04/020426
3. http://bl.ocks.org/mapsam/6083585