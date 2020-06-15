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

## JavaScript API

### Playground

- [JavaScript Code Editor](https://code.earthengine.google.com/) - The official Google Earth Engine JavaScript Code Editor.

### Tutorials

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

### Repositories

- [jdbcode/Snazzy-EE-TS-GIF](https://github.com/jdbcode/Snazzy-EE-TS-GIF) - Apps for creating Landsat time series animations.
- [fitoprincipe/geetools-code-editor](https://github.com/fitoprincipe/geetools-code-editor) - A set of tools to use in Google Earth Engine JavaScript Code Editor.
- [Fernerkundung/EarthEngine_scripts](https://github.com/Fernerkundung/EarthEngine_scripts) - Scripts and snippets for Google Earth Engine.

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

### Repositories

- [earthengine-py-notebooks](https://github.com/giswqs/earthengine-py-notebooks) - A collection of 360+ Jupyter notebook examples for using Google Earth Engine with interactive mapping.
- [earthengine-py-examples](https://github.com/giswqs/earthengine-py-examples) - A collection of 300+ examples for using Earth Engine and the geemap Python package.
- [ee-tensorflow-notebooks](https://github.com/gee-community/ee-tensorflow-notebooks) - Repository to place example notebooks for Deep Learning applications with TensorFlow and Earth Engine.
- [CoastSat](https://github.com/kvos/CoastSat) - Global shoreline mapping tool from satellite imagery.

## R

### Packages

- [rgee](https://github.com/r-spatial/rgee) - An R package for using Google Earth Engine.
- [earthEngineGrabR](https://github.com/JesJehle/earthEngineGrabR) - Simplify the acquisition of remote sensing data.

### Repositories

- [rgee-examples](https://csaybar.github.io/rgee-examples/) - A collection of 250+ examples for using Google Earth Engine with R.

## QGIS

- Earth Engine QGIS Plugin ([Website](https://gee-community.github.io/qgis-earthengine-plugin/), [GitHub](https://github.com/gee-community/qgis-earthengine-plugin)) - Integrates Google Earth Engine and QGIS using Python API.
- [qgis-earthengine-examples](https://github.com/giswqs/qgis-earthengine-examples) - A collection of 300+ Python examples for using Google Earth Engine in QGIS.

## GitHub Developers

### Community

- [earthengine-api](https://github.com/google/earthengine-api)
- [Google Earth Engine Community](https://github.com/gee-community)

### Individuals

- [Cesar Aybar](https://github.com/csaybar)
- [Justin Braaten](https://github.com/jdbcode)
- [Tirthankar "TC" Chakraborty](https://github.com/TC25)
- [Diego Garcia Diaz](https://twitter.com/mopayyo)
- [Gennadii Donchyts](https://github.com/gena)
- [Ujaval Gandhi](https://github.com/spatialthoughts)
- [Philipp Gärtner](https://github.com/philippgaertner)
- [Kel Markert](https://github.com/KMarkert)
- [Keiko Nomura](https://github.com/nkeikon)
- [Rodrigo E. Principe](https://github.com/fitoprincipe)
- [Samapriya Roy](https://github.com/samapriya)
- [Sabrina Szeto](https://github.com/sabrinaszeto)
- [Qiusheng Wu](https://github.com/giswqs)

## Twitter

### Bots

- [Earth Engine Bot](https://twitter.com/EarthEngineBot)
- [Geospatial Python](https://twitter.com/geospatial_py)

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
- [Kel Markert](https://twitter.com/KelMarkert)
- [Keiko Nomura](https://twitter.com/Keiko_geo)
- [Samapriya Roy](https://twitter.com/samapriyaroy)
- [Sabrina Szeto](https://twitter.com/SabrinaSzeto)
- [Dave Thau](https://twitter.com/davethau)
- [Qiusheng Wu](https://twitter.com/giswqs)

## Apps

- [Earth Engine Apps](https://www.earthengine.app/) - Google
- [An image gallery of almost all publicly available Google Earth Engine Apps](https://philippgaertner.github.io/2020/03/ee-apps/) - Philipp Gärtner

## Presentations

### geemap

- [Using the geemap Python package for interactive mapping with Earth Engine](https://www.researchgate.net/publication/341326008_Using_the_geemap_Python_package_for_interactive_mapping_with_Earth_Engine) - Earth Engine Virtual Meetup on May 8, 2020
- [Cloud computing and interactive mapping with Earth Engine and open-source GIS](https://www.researchgate.net/publication/341722639_Cloud_computing_and_interactive_mapping_with_Earth_Engine_and_open-source_GIS) - GeoInsider webinar on May 28, 2020
- [Mapping Wetland Inundation Dynamics using Google Earth Engine](https://www.researchgate.net/publication/342064888_Mapping_Wetland_Inundation_Dynamics_using_Google_Earth_Engine) - Machine learning and data fusion workshop on June 10, 2020

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

## Datasets

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

- Gorelick, N., Hancher, M., Dixon, M., Ilyushchenko, S., Thau, D., Moore, R., 2017. Google Earth Engine: Planetary-scale geospatial analysis for everyone. _Remote Sens. Environ_. 202, 18–27. <https://doi.org/10.1016/j.rse.2017.06.031>

### Review

- Tamiminia, H., Salehi, B., Mahdianpari, M., Quackenbush, L., Adeli, S., Brisco, B., 2020. Google Earth Engine for geo-big data applications: A meta-analysis and systematic review. _ISPRS J. Photogramm. Remote Sens._ 164, 152–170. <https://doi.org/10.1016/j.isprsjprs.2020.04.001>
- Kumar, L., Mutanga, O., 2018. Google Earth Engine Applications Since Inception: Usage, Trends, and Potential. _Remote Sensing_ 10, 1509. <https://doi.org/10.3390/rs10101509>

### Hydrology

- Pekel, J.-F., Cottam, A., Gorelick, N., Belward, A.S., 2016. High-resolution mapping of global surface water and its long-term changes. _Nature_ 540, 418–422. <https://doi.org/10.1038/nature20584>
- Yamazaki, D., Trigg, M.A., 2016. Hydrology: The dynamics of Earth’s surface water. _Nature_. <https://doi.org/10.1038/nature21100>
- Donchyts, G., Baart, F., Winsemius, H., Gorelick, N., Kwadijk, J., van de Giesen, N., 2016. Earth’s surface water change over the past 30 years. _Nat. Clim. Chang_. 6, 810. <https://doi.org/10.1038/nclimate3111>
- Wu, Q., Lane, C.R., Li, X., Zhao, K., Zhou, Y., Clinton, N., DeVries, B., Golden, H.E., Lang, M.W., 2019. Integrating LiDAR data and multi-temporal aerial imagery to map wetland inundation dynamics using Google Earth Engine. _Remote Sens. Environ_. 228, 1–13. <https://doi.org/10.1016/j.rse.2019.04.015>

### Urban

- Liu, X., Huang, Y., Xu, X., Li, X., Li, X., Ciais, P., Lin, P., Gong, K., Ziegler, A.D., Chen, A., Gong, P., Chen, J., Hu, G., Chen, Y., Wang, S., Wu, Q., Huang, K., Estes, L., Zeng, Z., 2020. High-spatiotemporal-resolution mapping of global urban change from 1985 to 2015. _Nature Sustainability_ 1–7. <https://doi.org/10.1038/s41893-020-0521-x>
- Li, X., Zhou, Y., Zhu, Z., Cao, W., 2020. A national dataset of 30 m annual urban extent dynamics (1985–2015) in the conterminous United States. _Earth System Science Data_ 12, 357. <https://doi.org/10.5194/essd-12-357-2020>

### Vegetation

- Li, X., Zhou, Y., Meng, L., Asrar, G.R., Lu, C., Wu, Q., 2019. A dataset of 30 m annual vegetation phenology indicators (1985–2015) in urban areas of the conterminous United States. _Earth System Science Data_. 11(2), 881-894. <https://doi.org/10.5194/essd-11-881-2019>

### Agriculture

- Xiong, J., Thenkabail, P.S., Tilton, J.C., Gumma, M.K., Teluguntla, P., Oliphant, A., Congalton, R.G., Yadav, K., Gorelick, N., 2017. Nominal 30-m Cropland Extent Map of Continental Africa by Integrating Pixel-Based and Object-Based Algorithms Using Sentinel-2 and Landsat-8 Data on Google Earth Engine. _Remote Sensing_ 9, 1065. <https://doi.org/10.3390/rs9101065>
- Xiong, J., Thenkabail, P.S., Gumma, M.K., Teluguntla, P., Poehnelt, J., Congalton, R.G., Yadav, K., Thau, D., 2017. Automated cropland mapping of continental Africa using Google Earth Engine cloud computing. _ISPRS J. Photogramm. Remote Sens_. 126, 225–244. <https://doi.org/10.1016/j.isprsjprs.2017.01.019>

### Land Cover

- Liu, H., Gong, P., Wang, J., Clinton, N., Bai, Y., Liang, S., 2020. Annual Dynamics of Global Land Cover and its Long-term Changes from 1982 to 2015. _Earth Syst. Sci. Data_. 12, 1217–1243. <https://doi.org/10.5194/essd-12-1217-2020>
- Carrasco, L., O’Neil, A.W., Morton, R.D., Rowland, C.S., 2019. Evaluating Combinations of Temporally Aggregated Sentinel-1, Sentinel-2 and Landsat 8 for Land Cover Mapping with Google Earth Engine. _Remote Sensing_ 11, 288. <https://doi.org/10.3390/rs11030288>

### Disaster Management

- DeVries, B., Huang, C., Armston, J., Huang, W., Jones, J.W., Lang, M.W., 2020. Rapid and robust monitoring of flood events using Sentinel-1 and Landsat data on the Google Earth Engine. _Remote Sens. Environ_. 240, 111664. <https://doi.org/10.1016/j.rse.2020.111664>
- Liu, C.-C., Shieh, M.-C., Ke, M.-S., Wang, K.-H., 2018. Flood Prevention and Emergency Response System Powered by Google Earth Engine. _Remote Sensing_ 10, 1283. <https://doi.org/10.3390/rs10081283>

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Qiusheng Wu has waived all copyright and related or neighboring rights to this work.
