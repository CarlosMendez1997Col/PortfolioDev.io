---
title: "Dev: Monitoring water resources using remote sensing"
header:
  image: /assets/images/OfficialLandscape.png
  teaser: /assets/images/OfficialLandscape.png
  og_image: /assets/images/OfficialLandscape.png
categories:
  - Monitoring Water💦
tags:
  - JavaScript
  - Google Earth Engine
---

# Monitoring water resources using Google Earth Engine (GEE) and JavaScript

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

Repository builded in `Google Earth Engine (GEE)` and `Javascript`.

Each section is described below:

- First section, calculate NVDI, MNDWI and AWEI index
  ```html
  <script>
  https://github.com/CarlosMendez1997Col/Monitoring-water-resources-using-Google-Earth-Engine-and-Javascript/tree/main/01.%20Nvdi%2C%20Mndwi%20and%20Awei
  <script>
  ```
- Second section, analyze surface water bodies (watersheds, rivers and lakes)
  ```html
  <script>
  https://github.com/CarlosMendez1997Col/Monitoring-water-resources-using-Google-Earth-Engine-and-Javascript/tree/main/02.%20Surface%20Water
  <script>
  ```
- Third section, analyze precipitation and rainfall in time series (monthly and yearly)
  ```html
  <script>
  https://github.com/CarlosMendez1997Col/Monitoring-water-resources-using-Google-Earth-Engine-and-Javascript/tree/main/03.%20Precipitation%20and%20rainfall
  <script>
  ```
- Fourth section, shows spatial and temporal variations in river levels
  ```html
  <script>
  https://github.com/CarlosMendez1997Col/Monitoring-water-resources-using-Google-Earth-Engine-and-Javascript/tree/main/04.%20Hidrology
  <script>
  ```
- Fifth section, calculate water balance and analyze droughts
  ```html
  <script>
  https://github.com/CarlosMendez1997Col/Monitoring-water-resources-using-Google-Earth-Engine-and-Javascript/tree/main/05.%20Water%20balance%20and%20drought
  <script>
  ```
- Sixth section, analyze reservoir levels and groundwater 
  ```html
  <script>
  https://github.com/CarlosMendez1997Col/Monitoring-water-resources-using-Google-Earth-Engine-and-Javascript/tree/main/06.%20Groundwater
  <script>
  ```
## Versions and releases

Version `1.0`

```html
<script>
https://github.com/CarlosMendez1997Col/Monitoring-water-resources-using-Google-Earth-Engine-and-Javascript/commits/Version1.0
<script>
```
  
## Image collections and datasets

```html
<script>
// 01.NVDI, MNDWI and AWEI index
ee.ImageCollection("COPERNICUS/S2_SR_HARMONIZED")

// 02.Surface Water
ee.ImageCollection("JRC/GSW1_4/YearlyHistory")

// 03.Precipitation and rainfall
ee.ImageCollection('UCSB-CHG/CHIRPS/PENTAD')
ee.ImageCollection('UCSB-CHG/CHIRPS/DAILY')

// 04.Hidrology
ee.ImageCollection('JRC/GSW1_3/YearlyHistory')

// 05.Water balance and drought
ee.ImageCollection('MODIS/006/MOD16A2')
ee.ImageCollection('UCSB-CHG/CHIRPS/PENTAD')

// 06.Groundwater
ee.ImageCollection("NASA/GLDAS/V022/CLSM/G025/DA1D")
ee.ImageCollection('NASA/GRACE/MASS_GRIDS/MASCON_CRI')
<script>
```


## Credits and repository of data

The original code, repositories and scripts used in this project, are available at:

- Google Earth Engine for Water Resources Management (Full Course), Author `Spatial Thoughts`
[Website](https://courses.spatialthoughts.com/gee-water-resources-management.html)

- Aquatic and Hydrological Applications, Author `gee-tutorials` [Website](https://google-earth-engine.com/Aquatic-and-Hydrological-Applications/Water-Balance-and-Drought/) [Github Repository](https://github.com/krishnakafle/gee-tutorials.git)

- Remote Sensing for Water Resources in Earth Engine, Author `Spatial eLearning` [Website](https://courses.spatialelearning.com/p/remote-sensing-for-water-resources-in-google-earth-engine)

- Google Earth Engine for Water Resources, Author `Study Hacks-Institute of GIS & Remote Sensing` [Website](https://www.youtube.com/@gisrsinstitute)

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
