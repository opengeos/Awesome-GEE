# Awesome Earth Engine [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Google Earth Engine resources. Please visit the [Awesome-GEE](https://github.com/giswqs/Awesome-GEE) GitHub repo if you want to contribute to this project.

## Table of Contents

- [Earth Engine official websites](#earth-engine-official-websites)
- [Get Started](#get-started)
- [Get Help](#get-help)
- [JavaScript API](#javascript-api)
- [Python API](#python-api)
- [R](#r)
- [QGIS](#qgis)
- [GitHub Developers](#github-developers)
- [Twitter](#twitter)
- [Apps](#apps)
- [Free Courses](#free-courses)
- [Presentations](#presentations)
- [Videos](#videos)
- [Projects](#projects)
- [Websites](#websites)
- [Datasets](#datasets)
- [Papers](#papers)
- [Contributing](#contributing)
- [License](#license)

## Earth Engine official websites

- [Official homepage](https://earthengine.google.com/)
- [JavaScript Code Editor](https://code.earthengine.google.com/)
- [API Documentation](https://developers.google.com/earth-engine/)
- [Data Catalog](https://developers.google.com/earth-engine/datasets/)
- [Timelapse](https://earthengine.google.com/timelapse/)
- [Earth Engine Apps](https://www.earthengine.app/)
- [Blog](https://medium.com/google-earth)
- [Sign up](https://earthengine.google.com/signup/)
- [Developer Forum](https://developers.google.com/earth-engine)
- [Issue Tracker](https://issuetracker.google.com/issues?q=componentid:184426&p=1)
- [Earth Engine API on GitHub](https://github.com/google/earthengine-api)
- [Google Earth Engine Community Tutorials](https://github.com/google/earthengine-community)
- [Google Earth Engine Community Developer Resources](https://developers.google.com/earth-engine/tutorials/community/developer-resources)

## Get Started

1. [Sign up](https://earthengine.google.com/signup/) for an Earth Engine account.
2. Read the Earth Engine API documentation - [Get Started with Earth Engine](https://developers.google.com/earth-engine/getstarted).
3. Read another Earth Engine API documentation - [Client vs. Server](https://developers.google.com/earth-engine/client_server). Make sure you have a good understanding of client-side objects vs server-side objects.
4. Try out the [JavaScript API](https://code.earthengine.google.com/) or Python API (e.g., [geemap](https://github.com/giswqs/geemap)).
5. Read [Coding Best Practices](https://developers.google.com/earth-engine/best_practices).

## Get Help

- [Earth Engine Developer Forum](https://groups.google.com/forum/#!forum/google-earth-engine-developers)
- [GIS Stack Exchange](https://gis.stackexchange.com/questions/tagged/google-earth-engine)
- [Report a bug](https://issuetracker.google.com/issues?q=componentid:184406&type:bug)
- [Dataset requests](https://issuetracker.google.com/issues?q=componentid:184426%2B%20status:open)
- [Feature requests](https://issuetracker.google.com/issues?q=componentid:184406%20type:feature_request%20status:open)
- [Slack channel for geemap and Earth Engine](https://gishub.org/geemap-slack)

## JavaScript API

### Playground

- [JavaScript Code Editor](https://code.earthengine.google.com/) - The official Google Earth Engine JavaScript Code Editor.

### Repositories

- [jdbcode/Snazzy-EE-TS-GIF](https://github.com/jdbcode/Snazzy-EE-TS-GIF) - Apps for creating Landsat time series animations.
- [fitoprincipe/geetools-code-editor](https://github.com/fitoprincipe/geetools-code-editor) - A set of tools to use in Google Earth Engine JavaScript Code Editor.
- [Fernerkundung/EarthEngine_scripts](https://github.com/Fernerkundung/EarthEngine_scripts) - Scripts and snippets for Google Earth Engine.
- [Google Earth Engine Toolbox (GEET)](https://github.com/sacridini/GEET) - Library to write small EE apps or big/complex apps with a lot less code.
- [LandTrendr](https://code.earthengine.google.com/?accept_repo=users/emaprlab/public) - Spectral-temporal segmentation algorithm.
- [zecojls/tagee](https://github.com/zecojls/tagee) - Terrain Analysis in Google Earth Engine (TAGEE).
- [ee-palettes](https://github.com/gee-community/ee-palettes) - A module for generating color palettes in Earth Engine to be applied to mapped data.
- [gee-ccdc-tools](https://gee-ccdc-tools.readthedocs.io/en/latest) - A suite of tools designed for continuous land change monitoring in Google Earth Engine.
- [Continuous Degradation Detection (CODED)](https://coded.readthedocs.io/en/latest/) - A system for monitoring forest degradation and deforestation.
- [LT-GEE](https://emapr.github.io/LT-GEE) - Google Earth Engine implementation of the LandTrendr spectral-temporal segmentation algorithm.
- [spectral](https://github.com/awesome-spectral-indices/spectral) - Awesome Spectral Indices for the Google Earth Engine JavaScript API (Code Editor).
- [msslib](https://github.com/gee-community/msslib) - An Earth Engine JavaScript library for working with Landsat MSS image data.
- [geeSharp](https://github.com/aazuspan/geeSharp) - Pan-sharpening in the Earth Engine Code Editor.
- [snazzy](https://github.com/aazuspan/snazzy) - Custom basemap styles in the Earth Engine Code Editor.
- [ee-polyfill](https://github.com/aazuspan/ee-polyfill) - Modern Javascript methods (ES6+) for the Earth Engine Code Editor.
- [gee-blend](https://github.com/jessjaco/gee-blend) - Various blending functions for Google Earth Engine.
- [OpenEarthEngineLibrary](https://www.open-geocomputing.org/OpenEarthEngineLibrary/) - Collection of code goodies for Google Earth Engine (GEE).

### Tutorials

- [Introduction to Google Earth Engine](https://www.google.com/earth/outreach/learn/introduction-to-google-earth-engine/)
- [Introduction to JavaScript for Earth Engine](https://developers.google.com/earth-engine/tutorial_js_01)
- [Introduction to the Earth Engine JavaScript API](https://developers.google.com/earth-engine/tutorial_api_01)
- [Global Forest Change Analysis](https://developers.google.com/earth-engine/tutorial_forest_01)
- [Global Surface Water Change Analysis](https://developers.google.com/earth-engine/tutorial_global_surface_water_01)
- [Beginner's Cookbook](https://developers.google.com/earth-engine/tutorials/community/beginners-cookbook)
- [Combining FeatureCollections](https://developers.google.com/earth-engine/tutorials/community/combining-feature-collections)
- [Customizing Base Map Styles](https://developers.google.com/earth-engine/tutorials/community/customizing-base-map-styles)
- [Forest Cover and Loss Estimation](https://developers.google.com/earth-engine/tutorials/community/forest-cover-loss-estimation)
- [Getting Started with Drawing Tools](https://developers.google.com/earth-engine/tutorials/community/drawing-tools)
- [Identifying Annual First Day of No Snow Cover](https://developers.google.com/earth-engine/tutorials/community/identifying-first-day-no-snow)
- [Interactive Region Reduction App](https://developers.google.com/earth-engine/tutorials/community/drawing-tools-region-reduction)
- [Land Surface Temperature in Uganda](https://developers.google.com/earth-engine/tutorials/community/ph-ug-temp)
- [Landsat ETM+ to OLI Harmonization](https://developers.google.com/earth-engine/tutorials/community/landsat-etm-to-oli-harmonization)
- [MODIS NDVI Times Series Animation](https://developers.google.com/earth-engine/tutorials/community/modis-ndvi-time-series-animation)
- [Non-parametric trend analysis](https://developers.google.com/earth-engine/tutorials/community/nonparametric-trends)
- [GEE 开发 on 知乎 by 无形的风](https://zhuanlan.zhihu.com/c_123993183)
- [Calculating Area in Google Earth Engine](https://spatialthoughts.com/2020/06/19/calculating-area-gee/)
- [Extracting Time Series using Google Earth Engine](https://spatialthoughts.com/2020/04/13/extracting-time-series-ee/)
- [Histogram Matching in Google Earth Engine](https://spatialthoughts.com/2020/07/14/histogram-matching-gee/)
- [Getting Git Right on Google Earth Engine](https://medium.com/@samapriyaroy/getting-git-right-on-google-earth-engine-e853f6551889)
- [AmericaView - Google Earth Engine (GEE) tutorials](https://americaview.org/program-areas/education/google-earth-engine-tutorials/)
- [Earth Lab - Introduction to the Google Earth Engine code editor](https://www.earthdatascience.org/tutorials/intro-google-earth-engine-ide/)
- [Coding Club - Intro to the Google Earth Engine](https://ourcodingclub.github.io/tutorials/earth-engine/)
- [Global Snow Observatory - Google Earth Engine Tutorials](https://sites.google.com/site/globalsnowobservatory/home/Presentations-and-Tutorials)
- [GEARS - Getting started with Google Earth Engine](https://www.geospatialecology.com/intro_rs_lab1/)
- [An Introduction to Remote Sensing for Ecologists Using Google Earth Engine](https://ecology.colostate.edu/google-earth-engine/)
- [An introduction to Google Earth Engine](https://www.paulamoraga.com/tutorial-gee/)

## Python API

### Installation

- [Earth Engine Python API installation](https://developers.google.com/earth-engine/python_install)

### Packages

- [earthengine-api](https://pypi.org/project/earthengine-api/) - The official Google Earth Engine Python API.
- [geemap](https://github.com/giswqs/geemap) - A Python package for interactive mapping with Google Earth Engine, ipyleaflet, and ipywidgets.
- [geeadd](https://github.com/samapriya/gee_asset_manager_addon) - Google Earth Engine Batch Asset Manager with Addons.
- [geeup](https://github.com/samapriya/geeup) - Simple CLI for Google Earth Engine Uploads.
- [cartoee](https://github.com/KMarkert/cartoee) - Publication quality maps using Earth Engine and Cartopy.
- [gee_tools](https://github.com/gee-community/gee_tools) - A set of tools for working with Google Earth Engine Python API.
- [landsat-extract-gee](https://github.com/loicdtx/landsat-extract-gee) - Get Landsat surface reflectance time-series from google earth engine.
- [Ndvi2Gif](https://github.com/Digdgeo/Ndvi2Gif) - Creating seasonal NDVI compositions GIFs.
- [eemont](https://github.com/davemlz/eemont) - A Python package that extends the Google Earth Engine Python API with pre-processing and processing tools.
- [hydra-floods](https://github.com/Servir-Mekong/hydra-floods) - An open source Python application for downloading, processing, and delivering surface water maps derived from remote sensing data.
- [restee](https://github.com/KMarkert/restee) - A package that aims to make plugging Earth Engine computations into downstream Python processing easier.
- [wxee](https://github.com/aazuspan/wxee) - A Python interface between Earth Engine and xarray for processing weather and climate data.
- [taskee](https://github.com/aazuspan/taskee) - Monitor your Earth Engine tasks and get notifications on your phone or computer.
- [geedim](https://github.com/dugalh/geedim) - Search, composite, and download Earth Engine imagery, without size limits.

### Repositories

- [earthengine-py-notebooks](https://github.com/giswqs/earthengine-py-notebooks) - A collection of 360+ Jupyter notebook examples for using Google Earth Engine with interactive mapping.
- [earthengine-py-examples](https://github.com/giswqs/earthengine-py-examples) - A collection of 300+ examples for using Earth Engine and the geemap Python package.
- [ee-tensorflow-notebooks](https://github.com/gee-community/ee-tensorflow-notebooks) - Repository to place example notebooks for Deep Learning applications with TensorFlow and Earth Engine.
- [CoastSat](https://github.com/kvos/CoastSat) - Global shoreline mapping tool from satellite imagery.
- [Google-Earth-Engine-Python-Examples](https://github.com/renelikestacos/Google-Earth-Engine-Python-Examples)
- [csaybar/EEwPython](https://github.com/csaybar/EEwPython)

### Tutorials

- [geemap and Earth Engine Python API tutorials](https://github.com/giswqs/geemap/tree/master/examples)
- [A Quick Introduction to Google Earth Engine](https://towardsdatascience.com/a-quick-introduction-to-google-earth-engine-c6a608c5febe)
- [Google Earth Engine (GEE) and Image Analysis](https://climada-python.readthedocs.io/en/stable/tutorial/climada_util_earth_engine.html)
- [Earth Engine Python API Colab Setup](https://colab.sandbox.google.com/github/google/earthengine-api/blob/master/python/examples/ipynb/ee-api-colab-setup.ipynb)
- [Earth Engine TensorFlow demonstration notebook](https://colab.sandbox.google.com/github/google/earthengine-api/blob/master/python/examples/ipynb/TF_demo1_keras.ipynb)
- [Earth Lab - Calculating the area of polygons in Google Earth Engine](https://www.earthdatascience.org/tutorials/basic-polygon-operations-google-earth-engine/)
- [Semantic Segmentation of GEE High Resolution Imagery](https://gist.github.com/mortcanty/ac4c48e3d10e89676b7fe9b3a6f1ba3a)

## R

### Packages

- [rgee](https://github.com/r-spatial/rgee) - An R package for using Google Earth Engine.
- [earthEngineGrabR](https://github.com/JesJehle/earthEngineGrabR) - Simplify the acquisition of remote sensing data.

### Repositories

- [rgee-examples](https://csaybar.github.io/rgee-examples/) - A collection of 250+ examples for using Google Earth Engine with R.

### Tutorials

- [rgee tutorial #1: Creating global land surface temperature maps](https://csaybar.github.io/blog/2020/06/10/rgee_01_worldmap/)
- [rgee tutorial #2: Satellite image processing](https://csaybar.github.io/blog/2020/06/15/rgee_02_io/)

## QGIS

### Packages

- Earth Engine QGIS Plugin ([Website](https://gee-community.github.io/qgis-earthengine-plugin/), [GitHub](https://github.com/gee-community/qgis-earthengine-plugin)) - Integrates Google Earth Engine and QGIS using Python API.

### Repositories

- [qgis-earthengine-examples](https://github.com/giswqs/qgis-earthengine-examples) - A collection of 300+ Python examples for using Google Earth Engine in QGIS.

### Tutorials

- [Creating Maps with Google Earth Engine](https://spatialthoughts.com/2020/04/04/ndvi-time-series-gee-qgis/)

## GitHub Developers

### Community

- [earthengine-api](https://github.com/google/earthengine-api)
- [Google Earth Engine Community](https://github.com/gee-community)
- [Google Earth Engine Community Tutorials](https://github.com/google/earthengine-community)

### Individuals

- [Cesar Aybar](https://github.com/csaybar)
- [Justin Braaten](https://github.com/jdbcode)
- [Tirthankar "TC" Chakraborty](https://github.com/TC25)
- [Diego Garcia Diaz](https://twitter.com/mopayyo)
- [Gennadii Donchyts](https://github.com/gena)
- [Ujaval Gandhi](https://github.com/spatialthoughts)
- [Philipp Gärtner](https://github.com/philippgaertner)
- [Eduardo Lacerda](https://github.com/sacridini)
- [Kel Markert](https://github.com/KMarkert)
- [Mort Canty](https://gist.github.com/mortcanty)
- [Keiko Nomura](https://github.com/nkeikon)
- [Rodrigo E. Principe](https://github.com/fitoprincipe)
- [Samapriya Roy](https://github.com/samapriya)
- [Sabrina Szeto](https://github.com/sabrinaszeto)
- [Qiusheng Wu](https://github.com/giswqs)

## Twitter

### Bots

- [Earth Engine Bot](https://twitter.com/EarthEngineBot)
- [Geospatial Python](https://twitter.com/geospatial_py)
- [Synthetic Aperture Random](https://twitter.com/ApertureRandom)

### Google affiliated

- [Google Earth](https://twitter.com/googleearth)
- [Google Earth Outreach](https://twitter.com/googleearth)
- [Tyler Erickson](https://twitter.com/tylerickson)
- [Rebecca Moore](https://twitter.com/rebeccatmoore)
- [Kurt Schwehr](https://twitter.com/kurtschwehr)

### Individuals

- [Cesar Aybar](https://twitter.com/csaybar)
- [Justin Braaten](https://twitter.com/jstnbraaten)
- [Tirthankar "TC" Chakraborty](https://twitter.com/Chalkemort)
- [Morgan Crowley](https://twitter.com/morganahcrowley)
- [Diego Garcia Diaz](https://github.com/Digdgeo)
- [Gennadii Donchyts](https://twitter.com/gena_d)
- [Ujaval Gandhi](https://twitter.com/spatialthoughts)
- [Philipp Gärtner](https://twitter.com/gartn001)
- [Belize GEO](https://twitter.com/BZgeo)
- [Mort Canty](https://twitter.com/mort_canty)
- [Kel Markert](https://twitter.com/KelMarkert)
- [Keiko Nomura](https://twitter.com/Keiko_geo)
- [Samapriya Roy](https://twitter.com/samapriyaroy)
- [Sabrina Szeto](https://twitter.com/SabrinaSzeto)
- [Dave Thau](https://twitter.com/davethau)
- [Qiusheng Wu](https://twitter.com/giswqs)

## Apps

- [Earth Engine Apps](https://www.earthengine.app/) - Google
- [An image gallery of almost all publicly available Google Earth Engine Apps](https://philippgaertner.github.io/2020/03/ee-apps/) - Philipp Gärtner
- [A searchable list of all publicly available Google Earth Engine Apps](https://datawrapper.dwcdn.net/4cHkZ/1/)

## Free Courses

- [End-to-End Google Earth Engine](https://courses.spatialthoughts.com/end-to-end-gee.html) - by [Ujaval Gandhi](https://twitter.com/spatialthoughts)
- [Spatial Data Management with Earth Engine](https://www.youtube.com/playlist?list=PLAxJ4-o7ZoPdz9LHIJIxHlZe3t-MRCn61) - by [Qiusheng Wu](https://twitter.com/giswqs)

## Presentations

### geemap

- [Using the geemap Python package for interactive mapping with Earth Engine](https://www.researchgate.net/publication/341326008_Using_the_geemap_Python_package_for_interactive_mapping_with_Earth_Engine) - Earth Engine Virtual Meetup on May 8, 2020
- [Cloud computing and interactive mapping with Earth Engine and open-source GIS](https://www.researchgate.net/publication/341722639_Cloud_computing_and_interactive_mapping_with_Earth_Engine_and_open-source_GIS) - GeoInsider webinar on May 28, 2020
- [Mapping Wetland Inundation Dynamics using Google Earth Engine](https://www.researchgate.net/publication/342064888_Mapping_Wetland_Inundation_Dynamics_using_Google_Earth_Engine) - Machine learning and data fusion workshop on June 10, 2020

### General

- [SERVIR Global - Introduction to Google Earth Engine](https://servirglobal.net/Portals/0/Documents/Articles/ChangeDetectionTraining/Module2_Intro_Google_Earth_Engine_presentation.pdf)

## Videos

### Google

- [Geo For Good 2019 on YouTube](https://www.youtube.com/playlist?list=PLLW-qoCMKQsxxXRmzxEJQhUrdX0kekHhV)
- [Earth Engine Video Tutorials](https://developers.google.com/earth-engine/tutorials#video-tutorials)

### General

- Getting Started with Earth Engine with Sabrina Szeto ([video](https://t.co/AQfGXvGksp?amp=1) - [slides](https://t.co/PM4Rqc604X?amp=1))
- Earth Engine Virtual Meetup on May 6, 2020 ([video](https://t.co/6WdQd7m9ZS?amp=1))

### geemap

- [geemap tutorials on YouTube](https://www.youtube.com/playlist?list=PLAxJ4-o7ZoPccOFv1dCwvGI6TYnirRTg3)
- [geemap tutorials on 哔哩哔哩](https://space.bilibili.com/527404442/channel/detail?cid=132674)
- [geemap tutorials on 西瓜视频](https://www.ixigua.com/home/676923482842317/)
- GeoInsider webinar - Cloud computing and interactive mapping with Earth Engine and open-source GIS ([video](https://www.bilibili.com/video/BV1Ep4y1X7tJ) - [slides](https://gishub.org/geoinsider))
- GeoInsider webinar 2 - Using Google Earth Engine for large-scale geospatial analysis: A case study of automated surface water mapping ([video](https://www.bilibili.com/video/BV15z411v7XE) | [slides](https://docs.google.com/presentation/d/1gkT93KCHNdQmL662FdjMjv1QD8fU2DMl0rIxxFSPEFE))

## Projects

- [Google Earth Engine](https://www.researchgate.net/project/Google-Earth-Engine-4) on Research Gate

## Websites

- [Global Surface Water Explorer](http://global-surface-water.appspot.com/)
- [Global Forest Cover Change](http://earthenginepartners.appspot.com/science-2013-global-forest)
- [Global Forest Watch](https://www.globalforestwatch.org/)
- [Map Of Life](http://species.mol.org/species/map/Perdix_dauurica)
- [Climate Engine](https://clim-engine.appspot.com/climateEngine)
- [Surface Water Mapping Tool](http://surface-water-servir.adpc.net/)
- [Surface water changes (1985-2016)](https://aqua-monitor.appspot.com/)
- [Decision Support Tools](https://servir.adpc.net/tools)
- [Earth Map](https://earthmap.org)
- [CoastSat shoreline change database](http://coastsat.wrl.unsw.edu.au/)

## Datasets

### Community Datasets

- [awesome-gee-community-datasets](https://github.com/samapriya/awesome-gee-community-datasets)

### Landsat

- [Landsat 8 Surface Reflectance](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC08_C01_T1_SR)
- [Landsat 8 TOA Reflectance](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC08_C01_T1_TOA)

### Sentinel

- [Sentinel-1 SAR GRD](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S1_GRD)
- [Sentinel-2 MSI](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2_SR)

### NAIP

- [NAIP: National Agriculture Imagery Program](https://developers.google.com/earth-engine/datasets/catalog/USDA_NAIP_DOQQ)

### Land Cover

- [NLCD: USGS National Land Cover Database](https://developers.google.com/earth-engine/datasets/catalog/USGS_NLCD)

## Papers

### Highlights

- Aybar, C., Wu, Q., Bautista, L., Yali, R., & Barja, A. (2020). rgee: An R package for interacting with Google Earth Engine. _The Journal of Open Source Software_. 5(51), 2272. https://doi.org/10.21105/joss.02272
- Gorelick, N., Hancher, M., Dixon, M., Ilyushchenko, S., Thau, D., Moore, R., 2017. Google Earth Engine: Planetary-scale geospatial analysis for everyone. _Remote Sens. Environ_. 202, 18–27. <https://doi.org/10.1016/j.rse.2017.06.031>
- Wu, Q. (2020). geemap: A Python package for interactive mapping with Google Earth Engine. _The Journal of Open Source Software_. 5(51), 2305. https://doi.org/10.21105/joss.02305

### Journal Special Issues

- _Journal of Remote Sensing_, Remote Sensing for Environmental and Societal Changes Using Google Earth Engine ([Call for Papers](https://spj.sciencemag.org/journal-of-remote-sensing-special-issues/gee/))
- _IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing_, Cloud Computing in Google Earth Engine for Remote Sensing ([Call for Papers](https://www.grss-ieee.org/wp-content/uploads/2019/12/Call_for_Paper_GEE.pdf))
- _Remote Sensing_, Google Earth Engine and Cloud Computing Platforms: Methods and Applications in Big Geo Data Science ([Call for Papers](https://www.mdpi.com/journal/remotesensing/special_issues/GEE_Methods_Applications), [Published Papers](https://www.mdpi.com/journal/remotesensing/special_issues/GEE_Methods_Applications))
- _Remote Sensning_, Google Earth Engine Applications ([Call for Papers](https://www.mdpi.com/journal/remotesensing/special_issues/GEE), [Published Papers](https://www.mdpi.com/journal/remotesensing/special_issues/GEE))
- _Remote Sensing of Environment_, Remote Sensing of Land Change Science with Google Earth Engine ([Call for Papers](https://www.journals.elsevier.com/remote-sensing-of-environment/call-for-papers/-special-issue-remote-sensing-of-land-change-science-with-go), [Published Papers](https://www.sciencedirect.com/journal/remote-sensing-of-environment/special-issue/104TX08KZZW))

### Review

- Amani, M., Ghorbanian, A., Ahmadi, A., Kakooei, M., ..., Wu, Q., & Brisco, B. (2020). Google Earth Engine Cloud Computing Platform for Remote Sensing Big Data Applications: A Comprehensive Review. _IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing_. <https://doi.org/10.1109/JSTARS.2020.3021052>
- Boothroyd, R., Williams, R., Hoey, T., Barrett, B., & Prasojo, O. (2020). Applications of Google Earth Engine in fluvial geomorphology for detecting river channel change. _WIREs Water_. <https://doi.org/10.1002/wat2.1496>
- Kumar, L., Mutanga, O., 2018. Google Earth Engine Applications Since Inception: Usage, Trends, and Potential. _Remote Sensing_ 10, 1509. <https://doi.org/10.3390/rs10101509>
- Tamiminia, H., Salehi, B., Mahdianpari, M., Quackenbush, L., Adeli, S., Brisco, B., 2020. Google Earth Engine for geo-big data applications: A meta-analysis and systematic review. _ISPRS J. Photogramm. Remote Sens._ 164, 152–170. <https://doi.org/10.1016/j.isprsjprs.2020.04.001>
- Wang, L., Diao, C., Xian, G., Yin, D., Lu, Y., Zou, S., & Erickson, T. A. (2020). A summary of the special issue on remote sensing of land change science with Google earth engine. _Remote Sensing of Environment_. <https://doi.org/10.1016/j.rse.2020.112002>
- Yang, L., Driscol, J., Sarigai, S., Wu, Q., Chen, H., & Lippitt, C. D. (2022). Google Earth Engine and Artificial Intelligence (AI): A Comprehensive Review. _Remote Sensing_, 14(14), 3253. <https://doi.org/10.3390/rs14143253>
- Yang, L., Driscol, J., Sarigai, S., Wu, Q., Lippitt, C. D., & Morgan, M. (2022). Towards Synoptic Water Monitoring Systems: A Review of AI Methods for Automating Water Body Detection and Water Quality Monitoring Using Remote Sensing. _Sensors_, 22(6), 2416. <https://doi.org/10.3390/s22062416>

### Hydrology

- Donchyts, G., Baart, F., Winsemius, H., Gorelick, N., Kwadijk, J., van de Giesen, N., 2016. Earth’s surface water change over the past 30 years. _Nat. Clim. Chang_. 6, 810. <https://doi.org/10.1038/nclimate3111>
- Pekel, J.-F., Cottam, A., Gorelick, N., Belward, A.S., 2016. High-resolution mapping of global surface water and its long-term changes. _Nature_ 540, 418–422. <https://doi.org/10.1038/nature20584>
- Wu, Q., Lane, C.R., Li, X., Zhao, K., Zhou, Y., Clinton, N., DeVries, B., Golden, H.E., Lang, M.W., 2019. Integrating LiDAR data and multi-temporal aerial imagery to map wetland inundation dynamics using Google Earth Engine. _Remote Sens. Environ_. 228, 1–13. <https://doi.org/10.1016/j.rse.2019.04.015>
- Yamazaki, D., Trigg, M.A., 2016. Hydrology: The dynamics of Earth’s surface water. _Nature_. <https://doi.org/10.1038/nature21100>

### Urban

- Li, X., Zhou, Y., Zhu, Z., Cao, W., 2020. A national dataset of 30 m annual urban extent dynamics (1985–2015) in the conterminous United States. _Earth System Science Data_ 12, 357. <https://doi.org/10.5194/essd-12-357-2020>
- Liu, X., Hu, G., Chen, Y., Li, X., Xu, X., Li, S., Pei, F., Wang, S., 2018. High-resolution multi-temporal mapping of global urban land using Landsat images based on the Google Earth Engine Platform. _Remote Sens. Environ_. 209, 227–239. <https://doi.org/10.1016/j.rse.2018.02.055>
- Liu, X., Huang, Y., Xu, X., Li, X., Li, X., Ciais, P., Lin, P., Gong, K., Ziegler, A.D., Chen, A., Gong, P., Chen, J., Hu, G., Chen, Y., Wang, S., Wu, Q., Huang, K., Estes, L., Zeng, Z., 2020. High-spatiotemporal-resolution mapping of global urban change from 1985 to 2015. _Nature Sustainability_ 1–7. <https://doi.org/10.1038/s41893-020-0521-x>
- Patel, N.N., Angiuli, E., Gamba, P., Gaughan, A., Lisini, G., Stevens, F.R., Tatem, A.J., Trianni, G., 2015. Multitemporal settlement and population mapping from Landsat using Google Earth Engine. _Int. J. Appl. Earth Obs. Geoinf_. 35, 199–208. <https://doi.org/10.1016/j.jag.2014.09.005>
- Weiss, D.J., Nelson, A., Gibson, H.S., Temperley, W., Peedell, S., Lieber, A., Hancher, M., Poyart, E., Belchior, S., Fullman, N., Mappin, B., Dalrymple, U., Rozier, J., Lucas, T.C.D., Howes, R.E., Tusting, L.S., Kang, S.Y., Cameron, E., Bisanzio, D., Battle, K.E., Bhatt, S., Gething, P.W., 2018. A global map of travel time to cities to assess inequalities in accessibility in 2015. _Nature_ 553, 333–336. <https://doi.org/10.1038/nature25181>

### Vegetation

- Li, X., Zhou, Y., Meng, L., Asrar, G.R., Lu, C., Wu, Q., 2019. A dataset of 30 m annual vegetation phenology indicators (1985–2015) in urban areas of the conterminous United States. _Earth System Science Data_. 11(2), 881-894. <https://doi.org/10.5194/essd-11-881-2019>
- Robinson, N.P., Allred, B.W., Jones, M.O., Moreno, A., Kimball, J.S., Naugle, D.E., Erickson, T.A., Richardson, A.D., 2017. A Dynamic Landsat Derived Normalized Difference Vegetation Index (NDVI) Product for the Conterminous United States. _Remote Sensing_ 9, 863. <https://doi.org/10.3390/rs9080863>
- Xie, Z., Phinn, S.R., Game, E.T., Pannell, D.J., Hobbs, R.J., Briggs, P.R., McDonald-Madden, E., 2019. Using Landsat observations (1988–2017) and Google Earth Engine to detect vegetation cover changes in rangelands - A first step towards identifying degraded lands for conservation. _Remote Sens. Environ_. 232, 111317. <https://doi.org/10.1016/j.rse.2019.111317>

### Agriculture

- Dong, J., Xiao, X., Menarguez, M.A., Zhang, G., Qin, Y., Thau, D., Biradar, C., Moore, B., 3rd, 2016. Mapping paddy rice planting area in northeastern Asia with Landsat 8 images, phenology-based algorithm and Google Earth Engine. _Remote Sens. Environ_. 185, 142–154. <https://doi.org/10.1016/j.rse.2016.02.016>
- Xiong, J., Thenkabail, P.S., Gumma, M.K., Teluguntla, P., Poehnelt, J., Congalton, R.G., Yadav, K., Thau, D., 2017. Automated cropland mapping of continental Africa using Google Earth Engine cloud computing. _ISPRS J. Photogramm. Remote Sens_. 126, 225–244. <https://doi.org/10.1016/j.isprsjprs.2017.01.019>
- Xiong, J., Thenkabail, P.S., Tilton, J.C., Gumma, M.K., Teluguntla, P., Oliphant, A., Congalton, R.G., Yadav, K., Gorelick, N., 2017. Nominal 30-m Cropland Extent Map of Continental Africa by Integrating Pixel-Based and Object-Based Algorithms Using Sentinel-2 and Landsat-8 Data on Google Earth Engine. _Remote Sensing_ 9, 1065. <https://doi.org/10.3390/rs9101065>

### Wetlands

- Amani, M., Mahdavi, S., Afshar, M., Brisco, B., Huang, W., Mohammad Javad Mirzadeh, S., White, L., Banks, S., Montgomery, J., Hopkinson, C., 2019. Canadian Wetland Inventory using Google Earth Engine: The First Map and Preliminary Results. _Remote Sensing_ 11, 842. <https://doi.org/10.3390/rs11070842>
- Chen, B., Xiao, X., Li, X., Pan, L., Doughty, R., Ma, J., Dong, J., Qin, Y., Zhao, B., Wu, Z., Sun, R., Lan, G., Xie, G., Clinton, N., Giri, C., 2017. A mangrove forest map of China in 2015: Analysis of time series Landsat 7/8 and Sentinel-1A imagery in Google Earth Engine cloud computing platform. _ISPRS J. Photogramm. Remote Sens_. 131, 104–120. <https://doi.org/10.1016/j.isprsjprs.2017.07.011>
- Hird, J.N., DeLancey, E.R., McDermid, G.J., Kariyeva, J., 2017. Google Earth Engine, Open-Access Satellite Data, and Machine Learning in Support of Large-Area Probabilistic Wetland Mapping. _Remote Sensing_ 9, 1315. <https://doi.org/10.3390/rs9121315>
- Mahdianpari, M., Brisco, B., Granger, J. E., Mohammadimanesh, F., Salehi, B., Banks, S., ... & Weng, Q. (2020). The Second Generation Canadian Wetland Inventory Map at 10 Meters Resolution Using Google Earth Engine. _Canadian Journal of Remote Sensing_, 46(3), 360-375. <https://doi.org/10.1080/07038992.2020.1802584>
- Mahdianpari, M., Salehi, B., Mohammadimanesh, F., Homayouni, S., Gill, E., 2018. The First Wetland Inventory Map of Newfoundland at a Spatial Resolution of 10 m Using Sentinel-1 and Sentinel-2 Data on the Google Earth Engine Cloud Computing Platform. _Remote Sensing_ 11, 43. <https://doi.org/10.3390/rs11010043>
- Wang, X., Xiao, X., Zou, Z., Chen, B., Ma, J., Dong, J., Doughty, R.B., Zhong, Q., Qin, Y., Dai, S., Li, X., Zhao, B., Li, B., 2020. Tracking annual changes of coastal tidal flats in China during 1986–2016 through analyses of Landsat images with Google Earth Engine. _Remote Sens. Environ_. 238, 110987. <https://doi.org/10.1016/j.rse.2018.11.030>
- Wu, Q., Lane, C.R., Li, X., Zhao, K., Zhou, Y., Clinton, N., DeVries, B., Golden, H.E., Lang, M.W., 2019. Integrating LiDAR data and multi-temporal aerial imagery to map wetland inundation dynamics using Google Earth Engine. _Remote Sens. Environ_. 228, 1–13. <https://doi.org/10.1016/j.rse.2019.04.015>
- Yancho, J. M. M., Jones, T. G., Gandhi, S. R., Ferster, C., Lin, A., & Glass, L. (2020). The Google Earth Engine Mangrove Mapping Methodology (GEEMMM). _Remote Sensing_, 12(22), 3758. <https://doi.org/10.3390/rs12223758>

### Land Cover

- Brown, C. F., Brumby, S. P., Guzder-Williams, B., Birch, T., Hyde, S. B., Mazzariello, J., ... & Tait, A. M. (2022). Dynamic World, Near real-time global 10 m land use land cover mapping. _Scientific Data_, 9(1), 1-17. <https://doi.org/10.1038/s41597-022-01307-4>
- Carrasco, L., O’Neil, A.W., Morton, R.D., Rowland, C.S., 2019. Evaluating Combinations of Temporally Aggregated Sentinel-1, Sentinel-2 and Landsat 8 for Land Cover Mapping with Google Earth Engine. _Remote Sensing_ 11, 288. <https://doi.org/10.3390/rs11030288>
- Hansen, M.C., Potapov, P.V., Moore, R., Hancher, M., Turubanova, S.A., Tyukavina, A., Thau, D., Stehman, S.V., Goetz, S.J., Loveland, T.R., Kommareddy, A., Egorov, A., Chini, L., Justice, C.O., Townshend, J.R.G., 2013. High-resolution global maps of 21st-century forest cover change. _Science_ 342, 850–853. <https://doi.org/10.1126/science.1244693>
- Huang, H., Chen, Y., Clinton, N., Wang, J., Wang, X., Liu, C., Gong, P., Yang, J., Bai, Y., Zheng, Y., Zhu, Z., 2017. Mapping major land cover dynamics in Beijing using all Landsat images in Google Earth Engine. _Remote Sens. Environ_. 202, 166–176. <https://doi.org/10.1016/j.rse.2017.02.021>
- Liu, H., Gong, P., Wang, J., Clinton, N., Bai, Y., Liang, S., 2020. Annual Dynamics of Global Land Cover and its Long-term Changes from 1982 to 2015. _Earth Syst. Sci. Data_. 12, 1217–1243. <https://doi.org/10.5194/essd-12-1217-2020>

### Disaster Management

- DeVries, B., Huang, C., Armston, J., Huang, W., Jones, J.W., Lang, M.W., 2020. Rapid and robust monitoring of flood events using Sentinel-1 and Landsat data on the Google Earth Engine. _Remote Sens. Environ_. 240, 111664. <https://doi.org/10.1016/j.rse.2020.111664>
- Liu, C.-C., Shieh, M.-C., Ke, M.-S., Wang, K.-H., 2018. Flood Prevention and Emergency Response System Powered by Google Earth Engine. _Remote Sensing_ 10, 1283. <https://doi.org/10.3390/rs10081283>
- Tellman, B., Sullivan, J.A., Kuhn, C., Kettner, A.J., Doyle, C.S., Brakenridge, G.R., Erickson, T.A., Slayback, D.A., 2021. Satellite imaging reveals increased proportion of population exposed to floods. _Nature_ 596, 80–86. <https://doi.org/10.1038/s41586-021-03695-w>

### Coastal

- Vos, K., Splinter, K.D., Harley, M.D., Simmons, J.A., Turner, I.L., 2019. CoastSat: A Google Earth Engine-enabled Python toolkit to extract shorelines from publicly available satellite imagery _Environmental Modelling and Software_. 122, 104528. <https://doi.org/10.1016/j.envsoft.2019.104528>

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Qiusheng Wu has waived all copyright and related or neighboring rights to this work.
