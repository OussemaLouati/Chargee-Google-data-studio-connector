# Chargebee Connector for Google data Studio

Deploying this apps script project will give you a new connector on Google data studio, where you can import you Data directly from Chargebee and start building your Dashboards. 

## How to proceed

You should First read the script `chargebee-connector.js.gs` and do the necessary changes so that you can import your data from your own API.

 - Update `function getFields()` (line 35): add the fields that you want to import and choose the right data types for each field. 
 - Update `function fetchDataFromApi(request)`: Add you own API url from where you want to fetch data. 

 ## Deploy Connector

 Deploying the connector is pretty straight forward, please follow this guide: [Here](https://developers.google.com/datastudio/connector/deploy)
