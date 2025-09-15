---
title: "Dev: Modelling and forecast hydropower resources"
header:
  image: /assets/images/PrincipalBanner.gif
  teaser: /assets/images/PrincipalBanner.gif
  og_image: /assets/images/PrincipalBanner.gif
categories:
  - Hydropower🪫
tags:
  - ArcGIS API for Python
  - ArcGIS Pro
  - Python
  - R
  - Scikit-Learn
  - TensorFlow
  - Keras
---

####  Models and forecasts hydrological and energetic resources using ArcGIS API for Python and R [link repository](https://github.com/CarlosMendez1997Col/Model-and-forecasts-hydrological-and-energetic-resources-using-ArcGIS-API-for-Python-and-R.git)

{% include video id="13_A2Tzhoz0Zg2eVDtnOaiZqydnc8duwZ" provider="google-drive" %}

{% include video id="1J93Pi2MxInTkruLSFUyowBFrj8LeR_Al" provider="google-drive" %}


## Use and install this repository

HTTPS
```html
<script>
https://github.com/CarlosMendez1997Col/Model-and-forecasts-hydrological-and-energetic-resources-using-ArcGIS-API-for-Python-and-R.git
<script>
```

GitHub CLI
```html
<script>
gh repo clone CarlosMendez1997Col/Model-and-forecasts-hydrological-and-energetic-resources-using-ArcGIS-API-for-Python-and-R
<script>
```

## Description

Repository builded in `Arcgis for Python` and `R`.

Models: `Neural Network Auto Regression (NNAR)`
        `Long Short Term Memory (LSTM)`
        `Convolutional Neural Network (ResCNN)`

Each section is described below:

1. The first and second sections, forecasting data with `NNAR` and `LSTM`. 
```html
<script>
https://github.com/CarlosMendez1997Col/Model-and-forecasts-hydrological-and-energetic-resources-using-ArcGIS-API-for-Python-and-R/tree/main/1.%20Forecasting%20NNAR%20Neural%20Network
https://github.com/CarlosMendez1997Col/Model-and-forecasts-hydrological-and-energetic-resources-using-ArcGIS-API-for-Python-and-R/tree/main/2.%20Forecasting%20LSTM%20Neural%20Network
<script>
```
2. The third and fourth sections, modeling data with `LSTM` and `ResCNN`.
```html
<script>
https://github.com/CarlosMendez1997Col/Model-and-forecasts-hydrological-and-energetic-resources-using-ArcGIS-API-for-Python-and-R/tree/main/3.%20Modeling%20LSTM%20Neural%20Network
https://github.com/CarlosMendez1997Col/Model-and-forecasts-hydrological-and-energetic-resources-using-ArcGIS-API-for-Python-and-R/tree/main/4.%20Modeling%20ResCNN%20Neural%20Network
<script>
```
3. The fifth and sixth sections, share initial scrips of `NNAR` and `LSTM`
```html
<script>
https://github.com/CarlosMendez1997Col/Model-and-forecasts-hydrological-and-energetic-resources-using-ArcGIS-API-for-Python-and-R/tree/main/5.%20Original%20Data%20NNAR%20Network
https://github.com/CarlosMendez1997Col/Model-and-forecasts-hydrological-and-energetic-resources-using-ArcGIS-API-for-Python-and-R/tree/main/6.%20Original%20Data%20LSTM%20and%20ResCNN%20Networks
<script>
```
## Prerequisites and libraries

### LSTM and ResCNN Neural Networks in ArcGIS API for Python

```python
<script>
import matplotlib.pyplot as plt
import numpy as np
import math
from datetime import datetime as dt
from IPython.display import Image, HTML

#pandas
import pandas as pd
from pandas.plotting import autocorrelation_plot

#sklearn
import sklearn.metrics as metrics
from sklearn.metrics import r2_score
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import MinMaxScaler

#arcgis
from arcgis.gis import GIS
from arcgis.learn import TimeSeriesModel, prepare_tabulardata
from arcgis.features import FeatureLayer, FeatureLayerCollection
<script>
```

### NNAR Neural Networks in R

```R
<script>
library(forecast)
library(timetk)
library(dplyr)
library(tibbletime)
library(cowplot)
library(rsample)
library(keras)
library(tidyverse)
library(tsibble) 
library(modeltime)
library(readxl)
<script>
```

## Versions and releases

Version `1.0`

```HTML
<script>
https://github.com/CarlosMendez1997Col/Model-and-forecasts-hydrological-and-energetic-resources-using-ArcGIS-API-for-Python-and-R/releases
<script>
```


## Data acquisition and download

### The data used for build the time series and the LSTM and ResCNN neural networks, include information about 3 Hydroelectric Power Plants (HPP):

* Data
* Useful Volume
* Useful Volume Percent (%)
* Affluent Flow
* Defluent Flow
* Natural Flow
* Stored Energy 
* Affluent Natural Energy
* Energy Generation

Data processed in time series formats are available at: 

* HPP Capivara: [link](https://arcg.is/1u158D) 
* HPP Chavantes: [link](https://arcg.is/1O1Wq11)
* HPP Jurumirim: [link](https://arcg.is/1WTWX)

### The data used for build the time series and the NNAR neural network, include information of precipitation and potential evapotranspiration. Available in:

Precipitation:[link](https://arcg.is/149qym3)

Potential Evapotranspiration:[link](https://arcg.is/0L9iSy0)

## Credits and repository of data

The data used for forecast precipitation and potential evapotranspiration are from the Nasa Earth re-pository, using the Giovanni (Geospatial Interactive Online Visualization ANd aNalysis Infrastructure). Available online in: [Nasa Giovanni Website](https://giovanni.gsfc.nasa.gov/giovanni/)

## Conflict of Interest.

The author declare that there is no conflict of interest in the publication of this data and have approved it for publication.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate. 

## MIT License

Copyright (c) 2025 Carlos Mendez

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
