# ANNE Student Challenge 2022

Set of resources to support participants accessing external data sources.

## Office for National Statistics (ONS)

[ONS Time series explorer](https://www.ons.gov.uk/timeseriestool) contains over 53k time series datasets. The data can be downloaded in common formats, such as csv, which can be used for further data visualisation and analysis.

[00-ons-example.ipynb](exploratory/00-ons-example.ipynb) is a Jupyter notebook that loads two datasets sourced from ONS: Air emissions All greenhouse gases-Total-Thousand tonnes CO2 equivalent and Passenger Air Transport Services and loads necessary libraries, reads data and plots a simple visualisation.

## Met Office

[Met Office](https://www.metoffice.gov.uk/) is the UK’s national meteorological service providing weather services and climate information. [This guide](data/met-office-data-guide.md) describes how to access historic weather station data, the 18 Petabytes CEDA Archive, and how to access the forecast and observation data.

[01-met-office-temp.ipynb](exploratory/01-met-office-temp.ipynb) is a Jupyter notebook that loads mean temperature for North of England and plots it with a fitted trend line.

Found an issue? Please [let me know](https://github.com/PetoMichalak/anne-student-challenge-2022/issues).

## Urban Observatory (UO)

[Urban Observatory](https://urbanobservatory.ac.uk/) presents a large set of publicly available real time urban data in the UK with highest concentration of sensors placed around Newcastle. A [map-based UI](https://newcastle.urbanobservatory.ac.uk/) allows users to browse through the available sensors, filter them by type and show historical measurements.

Access to the raw data is also possible through a [web-based portal](https://newcastle.urbanobservatory.ac.uk/download/raw_data/). Currently there are 1578 sensors with variety of types, such as: CO, PM, PM 4, Humidity, PM2.5, PM10, Temperature, Pressure, NO, NO2, PM1, Particle Count, O3.

UO provides a [REST API](https://newcastle.urbanobservatory.ac.uk/api_docs/) that can be used to download the raw sensor data. [02-uo-api.ipynb](exploratory/02-uo-api.ipynb) is a Jupyter notebook file that shows how to pull a historical data from an UO API for a specific sensor. Data are then plotted. The notebook also queries all the sensors IDs per ['theme'](https://newcastle.urbanobservatory.ac.uk/api_docs/doc/themes-json/) for easier programmatic interaction.

## Department for Environment, Food & Rural Affairs (DEFRA)

[DEFRA](https://www.gov.uk/government/organisations/department-for-environment-food-rural-affairs) is a ministerial department responsible for improving and protecting the environment. It aims to grow a green economy and sustain thriving rural communities. It supports food, farming and fishing industries.

DEFRA maintains an open [API portal](https://environment.data.gov.uk/apiportal) that provides access to data for Asset Management, Bathing Waters, Catchment Data, Ecology and Fish, Flood Monitoring, Hydrology, Public Registers, Rainfall, Rural Payments Agency Land, Tide Gauge, Water Quality Data Archive. In [03-defra-api.ipynb](exploratory/03-defra-api.ipynb) all of the latest measurements from flood monitoring API are queried from the API.