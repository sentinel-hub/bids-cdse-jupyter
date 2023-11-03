# BiDS Workshop: Jupyter Notebooks on Copernicus Dataspace Ecosystem

Workshop content for using Jupyter Notebooks on the Copernicus Data Space Ecosystem. Workshop held at the Big Data from Space 2023 conference.

This workshop shows streamlined satellite data access using Copernicus Dataspace Ecosystem APIs. It also shows how to get this data into popular python data analysis tools like [Pandas](https://pandas.pydata.org/) and [xarray](https://xarray.dev/).

## Content

The workshop is split up into three notebooks.

### 1: Introduction to Data Access

This notebook introduces you to the Sentinel Hub APIs which allow you streamlined access to satellite data.

#### Covered Concepts:

- [Catalog API](https://documentation.dataspace.copernicus.eu/APIs/SentinelHub/Catalog.html)
- [Evalscripts](https://documentation.dataspace.copernicus.eu/APIs/SentinelHub/Evalscript.html)
- [Processing API](https://documentation.dataspace.copernicus.eu/APIs/SentinelHub/Process.html)

### 2: Pollution Statistics

Using Sentinel 5P data this notebook goes further into depth about data access. It also shows how to easily carry out spatial statistics completely in the cloud. Those spatial statistics are then brought into pandas for further analysis.

#### Covered Concepts:

- Advanced [Evalscripts](https://documentation.dataspace.copernicus.eu/APIs/SentinelHub/Evalscript.html)
- [Statistical API](https://documentation.dataspace.copernicus.eu/APIs/SentinelHub/Statistical.html)
- Basic [Pandas](https://pandas.pydata.org/) tabular analaysis

### 3: Deforestation Time Series

Using Sentinel 2 data this notebook shows how to easily and quickly construct cloud free mosaics. It also shows a simple classification and time series use-case. The analysis is carried out using xarray.

#### Covered Concepts:

- Cloud free mosaics
- Basic multidimensional data handling with [xarray](https://xarray.dev/)
