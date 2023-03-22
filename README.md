## <b>Overview</b> 

Brief description of each pipeline/code. These python scripts are demonstration for some applications in remote sensing and spatial analysis.

 <img src="https://plotly.com/all_static/images/python.png"  width="40" height="40">

All scripts are written in Python 3.9 with necessary packages. Spesific packages are mentioned bellow. Packages such as Numpy and Pandas are now typical defaults in python, and hence are not mentioned.

The common python packages in remote sensing, spatial analysis, and machine learning:

<img src="https://geopandas.org/en/stable/_static/geopandas_logo_web.svg"  width="120" height="40"> <img src="https://developers.google.com/static/earth-engine/images/landing_ee_logo_960.png"  width="85" height="50"><b style="color:darkblue">Earth Engine</b> <img src="https://gdal.org/_static/gdalicon.png"  width="40" height="40"> <b  style="color:red"> Rasterio </b> <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png"  width="70" height="30"> <img src="https://www.gstatic.com/devrel-devsite/prod/v80bae38ba58d74b96b4842131d88ee335fbea404678aa063008110db834e2268/tensorflow/images/lockup.svg"  width="100" height="30"> <img src="https://camo.githubusercontent.com/d7a1f81a2ee7576ab86720d9135ab3c915550e3945a7859f1c0300ab22ac1cec/687474703a2f2f707974686f6e2d76697375616c697a6174696f6e2e6769746875622e696f2f666f6c69756d2f5f696d616765732f666f6c69756d5f6c6f676f2e6a7067"  width="40" height="40"><b style="color:limegreen">Folium</b>
<img src="https://matplotlib.org/_static/images/logo2.svg"  width="120" height="50">

Datapane is optional if you want to publish the results as an interactive map/chart

<img src="https://uploads-ssl.webflow.com/633eb64a2d33ad2e879f0287/633ec6c1fa4724f137e42b89_Logo%20with%20dark%20text.svg"  width="120" height="50">


Detail description for datasets and sources are in respective script.

### <b>01. Large scale deforestation monitoring by Google Earth Engine</b> <br/>


<b>Objective</b> &emsp;: Monitoring deforestion in the tropic<br/>
<b>Spatial data</b> : Time-series Sentinel-2 (5-day temporal resolution), from <i>ee</i> package (cloud processing)<br/>
<b>Packages</b> &emsp;: ee/eaarth engine and geemap<br/>
<b>Method</b> &emsp; &emsp;: Machine learning Random Forest and Decision Tree (supported by <i>ee</i> package)  <br/>

![alt text](https://github.com/siswaphd/My_repo/blob/main/images/1_Monitoring_deforestation.png "Logo Title Text 1")

### <b>02. Quantitave Spatial analysis of AIDS/HIV and Tubercolosis infections in Java Island, Indonesia</b> <br/>

<b>Objective</b> &emsp;: <br/>
<b>Spatial data</b> : Data statistic and demografi (Population) from BPS (<i>Badan Pusat Statistik</i>/Indonesian Statistic Central Agency)<br/>
<b>Packages</b> &emsp;: geopandas, PySAL<br/>
<b>Method</b> &emsp; &emsp;: OLS (Ordinary Least Square), ESDA (Exploratory Spatial Data Analysis), and GWR (Geographic Weighted Regression)  <br/>

![alt text](https://github.com/siswaphd/My_repo/blob/main/images/2_ESDA_a.png "Logo Title Text 1")<br/>
![alt text](https://github.com/siswaphd/My_repo/blob/main/images/2_ESDA_b.png "Logo Title Text 1")

### <b>03. Time series Froecasting by machine learning for Air quality(PM 2.5 concentration in Jakarta, Indonesia)</b> <br/>

<b>Objective</b> &emsp;: <br/>
<b>Spatial data</b> : Time-series of PM 2.5 concentration from US embassy in Jakarta, and climates data (precipitation/rainfal, temperature, etc) ERA5 datasest available in Google earth Engine <br/>
<b>Packages</b> &emsp;: ee/earth engine, tensorflow, sckit-learn, and plotly (optional for interactive plot)<br/>
<b>Method</b> &emsp; &emsp;: machine learning by Long-Short Term Memory (LSTM) Neural Network and Gaussian Process (GP) <br/>
Output as interactive chart is available at [<b>Datapane.com</b>](https://cloud.datapane.com/reports/dA610mk/interactive-chart-machine-learning-lstm-for-forecasting-air-pollution/)<br/>
<br/>
![alt text](https://github.com/siswaphd/My_repo/blob/main/images/3_ML_LSTM_GP.png "Logo Title Text 1")<br/>

### <b>04. Deforestation simulation </b><br/>

<b>Objective</b> &emsp;: <br/>
<b>Spatial data</b> : map of Canopy Height Model (CHM) from SRTM-X DLR (German Space Center) and logging trails/road network derived from very-high resolution aerial images <br/>
<b>Packages</b> &emsp;: GDAL, scikit-learn, scipy<br/>
<b>Method</b> &emsp; &emsp;: machine learning by Randon Forest and OLS <br/>
Output as interactive map is available at [<b>Datapane.com</b>](https://cloud.datapane.com/reports/q34BNqk/deforestation-simulation/)<br/>
<br/>
![alt text](https://github.com/siswaphd/My_repo/blob/main/images/4_deforestation_simulation.gif "Logo Title Text 1")<br/>

### <b>05. Interactive chart </b><br/>

<b>Objective</b> &emsp;: <br/>
<b>Spatial data</b> : Vegetation paramters (daily water uptake and growth from dendrometer data) and environmental/hydro-meterological parameters (watertable depth, rainfall, temperature, humidity, PAR) <br/>
<b>Packages</b> &emsp;: scipy, plotly<br/>
<b>Method</b> &emsp; &emsp;: Time-series analysis and Zero-Growth Approach for dendormeter data<br/>
Output as interactive chart is available at [<b>Datapane.com</b>](https://cloud.datapane.com/reports/E7o5E2A/interactive-chart-tree-physiology/)<br/>

### <b>06. Regional mapping of forest aboveground biomass (AGB) </b><br/>

<b>Objective</b> &emsp;: <br/>
<b>Spatial data</b> : Sentinel-2 and AGB biomass refrence from GEDI NASA mission <br/>
<b>Packages</b> &emsp;: ee/earth engine, scikit-learn<br/>
<b>Method</b> &emsp; &emsp;: machine learning by Random Forest<br/>

![alt text](https://github.com/siswaphd/My_repo/blob/main/images/6_Biomass.png "Logo Title Text 1")<br/>
