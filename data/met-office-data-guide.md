# Met Office – Data

## Intro to Met Office

[Met Office](https://www.metoffice.gov.uk/) is the UK’s national meteorological service providing weather services and climate information. It contains a vast amount of information not only providing a weather forecasts for a specific region, but also in-depth articles on climate change, such as this [introductory piece](https://www.metoffice.gov.uk/weather/climate-change/what-is-climate-change), or a detailed report on [State of the UK Climate 2020](https://rmets.onlinelibrary.wiley.com/doi/10.1002/joc.7285).

## Historic Station Data

The Met Office offers [a historical station data](https://www.metoffice.gov.uk/research/climate/maps-and-data/historic-station-data) for 37 stations dating back as far as 1853 for some stations. The data consists of following records: year, month, temperature max, temperature min, rain, sun hours as well as location of the station.

## UK and regional series

Monthly, seasonal and annual measurements split into 17 regions providing 7 parameters such as: max/mean/min temperature, rainfall or day frost is available using open [UI interface](https://www.metoffice.gov.uk/research/climate/maps-and-data/uk-and-regional-series).

## The CEDA Archive
[The CEDA Archive](https://archive.ceda.ac.uk/) holds data from atmospheric and earth observation with impressive 18 Petabytes archive. The environmental data from [Met Office MIDAS Open dataset](https://catalogue.ceda.ac.uk/uuid/dbd451271eb04662beade68da43546e1) contains 32 datasets, such as UK daily temperature, UK hourly rainfall, wind, solar radiation and others. For example, a user can retrieve a [xls table](https://data.ceda.ac.uk/badc/ukmo-midas-open/data/uk-daily-temperature-obs/dataset-version-202007/tyne-and-wear/00307_newcastle-weather-centre/qc-version-1) with two daily measurements of temperature in Newcastle since 1st October 1974.
A free [registration](https://services.ceda.ac.uk/cedasite/register/info/) is required before accessing the CEDA archive.

## Met Office DataPoint API
Met Office DataPoint API exposes the data produced either through a free tier, limiting the number of data requests to 5000 per day or 100 per minute under its [Fair use policy](https://www.metoffice.gov.uk/services/data/datapoint/terms-and-conditions---datapoint); or using a Paid data plan the download limits are increased to 100,000 data requests per day or 1000 data requests per minute. A [registration](https://register.metoffice.gov.uk/WaveRegistrationClient/public/newaccount.do?service=datapoint) is required before accessing any data, this consists of a short form with an instant response with an API key. Data is available in XML or JSON format. Following data are accessible from the service:
• forecast and observation map layers such as radar and cloud cover for the UK;
• forecast and observed site specific data such as temperature, wind speed and
direction;
• regularly updated text forecasts for mountain weather, national parks and UK
regions.

[This guide](https://www.metoffice.gov.uk/services/data/datapoint/getting-started) is an excellent starting point for accessing the Met Office DataPoint API. It describes the registration process and the use of APIs. The service has a detailed [documentation](https://www.metoffice.gov.uk/services/data/datapoint/datapoint-documentation), [a guide on selecting the right product](https://www.metoffice.gov.uk/services/data/datapoint/datapoint-products) (Forecasts or Observations).