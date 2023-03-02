

# Cryosphere Software, Data and Tools [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

A prototype of a curated list of awesome data sources, models, tools and organizations related to the Cryosphere and its subspheres.




## Contents
- [Cryosphere - across all subspheres](#cryosphere---across-all-subspheres)
    - [Cryo Software](#cryo-software)
    - [Cryo Data](#cryo-data)
- [Frozen Ground/Permafrost](#frozen-groundpermafrost)
    - [FGP Software](#fgp-software)
    - [FGP Data](#fgp-data)
- [Ice Sheets and Glaciers](#ice-sheets-and-glaciers)
    - [ISG Software](#isg-software)
         - [ISG Open Source Models](#isg-open-source-models) 
             - Ice Flow and Mass Balance
             -  (Surface) Mass Balance only
             - Calving/Frontal Ablation
             - Hydrology
             - Sub-/Englacial Hydrology
             - Miscellaneous
         - [ISG Closed/On-Demand Source Models](#isg-closedon---demand-source-models) 
             - Ice Flow and Mass Balance
             - Sub-/Englacial Hydrology
         - [ISG Remote Sensing Software](#isg-remote-sensing-software)
    - [ISG Data](#isg-data)
	    - [ISG Global Data](#isg-global-data) 
	    - [ISG National Data](#isg-local-data)
	        - Switzerland
    - [ISG Visualization Tools](#isg-visualization-tools)
    - [ISG Educational Tools and Data](#isg-educational-tools-and-data)
- [Sea Ice](#sea-ice)
    - [SI Software](#si-software)
    - [SI Data](#si-data)
- [Snow](#snow)
    - [SN Software](#sn-software)
    - [SN Data](#sn-data)
- [Contributing](#contributing)
- [License](#license)

## Cryosphere - across all subspheres
### Cryo Software
- [Antarctic-Plots](https://antarctic-plots.readthedocs.io/en/latest/index.html) - A Python package to help download, process, visualize, and plot Antarctic data.
- [earthspy](https://github.com/AdrienWehrle/earthspy) - Monitor and study any place on Earth and in Near Real-Time (NRT) with satellite data
- [xDEM](https://github.com/GlacioHack/xdem) - A Python module developed by glaciologists for handling DEMs: read/write, coregistration, volume change calculation etc.
### Cryo Data 
- [NSIDC](https://nsidc.org/) - The (US) National Snow and Ice Data Center
- [NSIDC Data Tutorials](https://github.com/nsidc/NSIDC-Data-Tutorials) - Jupyter notebook guides to access, subset, transform, and visualize data products from NSIDC
- [Arctic Data Center](https://arcticdata.io) - Data and software from NSF Arctic research
## Frozen Ground/Permafrost
### FGP Software
#### Data Handling
- [tsp](https://gitlab.com/permafrostnet/teaspoon) - A python library for reading, writing, visualizing and manipulating ground temperature data ([p](https://doi.org/10.21105/joss.04704))
#### Modelling
- [FreeThaw1D](https://github.com/geoframecomponents/FreeThaw1D) A fast 1d heat transfer model with phase change ([p](https://tc.copernicus.org/articles/15/2541/2021/tc-15-2541-2021.html))
### FGP Data
- [PermafrostNet ERDDAP](https://data.permafrostnet.ca/erddap/index.html) - Distributing ground temperature and borehole data using OPeNDAP 
- [PERMOS](http://permos.ch/) - Swiss Permafrost Monitoring Network (PERMOS)
- [PermaSense Matterhorn Data](https://doi.pangaea.de/10.1594/PANGAEA.916193) - Matterhorn Permafrost Observatory data ([p](https://doi.org/10.5194/essd-11-1203-2019))

## Ice Sheets and Glaciers
### ISG Software
####  ISG Open Source Models
##### Ice Flow and Mass Balance
- [ALPGM](https://github.com/JordiBolibar/ALPGM) - ALpine Parameterized Glacier Model. Deep learning-based regional glacier evolution model ([p](https://tc.copernicus.org/articles/14/565/2020/tc-14-565-2020.html))
- [CISM](https://github.com/CISM/cism) - Community Ice Sheet Model ([p](https://doi.org/10.1029/2008JF001015))
- [CFM](https://github.com/UWGlaciology/CommunityFirnModel) - Community Firn Model ([p](https://gmd.copernicus.org/articles/13/4355/2020/gmd-13-4355-2020.html))
- [DEISM ice-sheet-model](https://github.com/cpk26/ice-sheet-model) - DEpth integrated Ice Sheet Model (DEISM)
- [Elmer/Ice](https://github.com/elmercsc/elmerfem) - Open Source Finite Element Software for Ice Sheet, Glaciers and Ice Flow Modelling
- [Fenics Ice](https://github.com/EdiGlacUQ/fenics_ice) - Ice Sheet model with Bayesian Uncertainty Quantification ([p](https://doi.org/10.5194/gmd-2021-90)).
- [flowline-glacier-model](https://github.com/aaschwanden/flowline-glacier-model) - Flowline glacier model by Andy Aschwanden
- [Glacier Energy and Mass Balance (GEMB v1.0)](https://issm.jpl.nasa.gov/) - Energy and Mass Balance Model with focus on firn (part of ISSM) ([p](https://egusphere.copernicus.org/preprints/2022/egusphere-2022-674/egusphere-2022-674.pdf), preprint).
- [glacier-flow-model](https://github.com/munterfinger/glacier-flow-model) - Modelling glacier flow, based on the glaciers mass balance and a digital elevation model
- [icepack](https://github.com/icepack/icepack) - Finite element modeling of glaciers and ice sheets
- [ICESHEET](https://github.com/evangowan/icesheet) - Creates ice sheet reconstructions using a perfectly plastic approximation, using ice margins and basal shear stress as inputs
- [icetools](https://github.com/alexjarosch/icetools) - icetools provides a development environment for numerical ice flow models/simulations
- [ISSM](https://issm.jpl.nasa.gov/)  - Ice Sheet System Model
- [MPAS-Albany Land Ice (MALI)](https://github.com/MPAS-Dev/MPAS-Release/releases) - a variable-resolution ice sheet model for earth system modeling using voronoi grids
- [OGGM](https://oggm.org/) - Open Global Glacier Model: a modular open source model for glacier dynamics ([p](https://doi.org/10.5194/gmd-12-909-2019))
- [PISM](http://www.pism-docs.org/wiki/doku.php) - Parallel Ice Sheet Model ([p](https://doi.org/10.5194/tc-5-715-2011))
- [PyGEM](https://github.com/drounce/PyGEM) - Python Glacier Evolution Model (PyGEM)
- [sia-fluxlim](https://github.com/alexjarosch/sia-fluxlim) - Implementation of a MUSCL-superbee flux limiter to a shallow ice approximation flow code based on finite differences
- [SICOPOLIS](http://www.sicopolis.net/)  - SImulation COde for POLythermal Ice Sheets
- [speceis_flowline](https://github.com/douglas-brinkerhoff/speceis_flowline) - Width-parameterized flowline version of the spectral ice sheet model (SpecEIS)
- [Stochastic Ice-Sheet and Sea-Level System Model (StISSM)](https://issm.jpl.nasa.gov/download) - Stochastic implementation of ISSM ([p](https://egusphere.copernicus.org/preprints/2022/egusphere-2022-699/egusphere-2022-699.pdf), preprint)
- [Úa](https://github.com/GHilmarG/UaSource) - A large-scale ice-flow model
- [UFEMISM](https://github.com/IMAU-paleo/UFEMISM) - The Utrecht FinitE voluMe Ice-Sheet Model ([p](https://doi.org/10.5194/gmd-14-2443-2021))
- [VarGlaS](https://github.com/douglas-brinkerhoff/VarGlaS) - The source code repository for the Variational Glacier Simulator (VarGlaS) code ([p](https://doi.org/10.5194/tc-7-1161-2013))
- [Yelmo](https://github.com/palma-ice/yelmo) - a 3D ice-sheet-shelf model solving for the coupled dynamics and thermodynamics of the ice sheet system ([p](https://doi.org/10.5194/gmd-2019-273))


##### (Surface) Mass Balance only
- [pypdd](https://github.com/juseg/pypdd) - A positive degree day model for glacier surface mass balance ([p](http://doi.org/10.3189/2013JoG13J081))
- [COSIPY](https://github.com/cryotools/cosipy) -  A flexible and user-friendly framework for modeling distributed snow and glacier mass changes ([p](https://doi.org/10.5194/gmd-13-5645-2020))
- [MAR](https://mar.cnrs.fr/) -  A regional climate model for modelling surface mass balance ([p](http://journals.ametsoc.org/doi/abs/10.1175/1520-0493(1994)122%3C0671:DOATDM%3E2.0.CO;2))

##### Calving/Frontal Ablation
- [cryo_calving_2019](https://github.com/bearecinos/cryo_calving_2019) - Experiments with a minimal Frontal ablation model added to OGGM
- [HiDEM](https://github.com/joeatodd/HiDEM) - Helsinki Discrete Element Model, a particle model for simulating elastic behaviour, fracture and calving at marine terminating glaciers ([p](https://doi.org/10.5194/tc-7-1591-2013))
- [SERMeQ](https://github.com/ehultee/sermeq) - Tool to estimate advance, retreat, and sea level contribution of calving glaciers forced by upstream surface mass balance, based on viscoplastic physics ([p](https://doi.org/10.1029/2020GL090213))

##### Hydrology
- [CCHF](https://github.com/thomasmosier/CCHF) - Cryosphere hydrology modeling package written in Matlab ([p](https://doi.org/10.5194/tc-10-2147-2016))
- [DEBAM/DETIM](https://github.com/regine/meltmodel)  - Distributed Energy Balance Model (DEBAM) and Distributed Enhanced Temperature Index Model (DETIM): Two Distributed Glacier Surface Mass-Balance and Discharge Models ([p](https://doi.org/10.3189/S0022143000003087), [p](https://doi.org/10.3189/172756505781829566))

##### Sub-/Englacial Hydrology
- [1Dhydro](https://bitbucket.org/maurow/1dhydro/src/master/) - Example subglacial hydrology model for teaching. Subglacial processes workshop at Centre for Ice and Climate, The Niels Bohr Institute, University of Copenhagen 7-11 th April 2014
- [RchannelODE.jl](https://bitbucket.org/maurow/rchannelode.jl/src/master/) - Solves the 1D steady state R-channel equations
- [SHAKTI]() - Subglacial hydrology and kinetic transient interactions ([p](https://doi.org/10.5194/gmd-11-2955-2018))

##### Miscellaneous
- [bod-marine](https://github.com/bueler/bod-marine) - exact solution to marine ice sheet 1D problem, coming from Bodvardsson (1955)
- [debadvect](https://github.com/awirbel/debadvect) - FEM model for englacial debris transport
- [Glacier initialization](https://github.com/OGGM/initialization) - Method to reconstruct estimated glacier states up to 1850
- [GlacialLakeHazards](https://github.com/drounce/GlacialLakeHazards) - Matlab codes from PhD work on glacial lake outburst flood hazards in the Nepal Himalaya
- [icepack-py](https://github.com/danshapero/icepack-py) - Python bindings and utility scripts for icepack
- [Rounce2014_debristhickness](https://github.com/drounce/Rounce2014_debristhickness) - Codes associated with deriving the debris thickness of debris-covered glaciers from Landsat thermal imagery
- [SELEN](https://github.com/geodynamics/selen) - Calculates glacial isostatic adjustment and the sea level equation
- [sia-fve](https://github.com/bueler/sia-fve) - implicit finite volume element (FVE) method for the shallow ice approximation (SIA) free-boundary problem



#### ISG Closed/On-Demand Source Models

##### Ice Flow and Mass Balance
- [f.ETISh](https://doi.org/10.5194/tc-11-1851-2017) - Fast Elementary Thermomechanical Ice Sheet Model ([p](https://doi.org/10.5194/tc-11-1851-2017))
- [GagliardiniWerder2018](https://doi.org/10.1017/jog.2018.59) - Influence of an increasing surface melt over decadal timescales on land terminating outlet glaciers (paper)
- [GloGEM](https://doi.org/10.3389/feart.2015.00054) - A model for global glacier change and sea-level rise ([p](https://doi.org/10.3389/feart.2015.00054))
- [GloGEMflow](https://doi.org/10.5194/tc-13-1125-2019) - Extended version of the Global Glacier Evolution Model (GloGEM), in which both surface mass balance and ice flow are explicitly accounted for ([p](https://doi.org/10.5194/tc-13-1125-2019))
- [GERM](http://dx.doi.org/10.1002/hyp.8276) - Glacier Evolution and Runoff Model ([p](https://doi.org/10.1002/hyp.7055))
- [PollardDeConto2012](https://doi.org/10.5194/gmd-5-1273-2012) - 3D hybrid ice sheet-shelf model for long-term continental-scale applications ([p](https://doi.org/10.5194/gmd-5-1273-2012))


##### Sub-/Englacial Hydrology
- [Beyeretal2017](https://doi.org/10.5194/tc-12-3931-2018) - A confined–unconfined aquifer model for subglacial hydrology and its application to the north east Greenland ice stream (paper)
- [Brinkerhoffetal2011](https://doi.org/10.1017/aog.2016.3) - Inversion of a glacier hydrology model (paper)
- [BuelervanPelt2015](https://doi.org/10.5194/gmd-8-1613-2015) - Mass-conserving subglacial hydrology in the Parallel Ice Sheet Model version 0.6 (paper)
- [deFleurian2016](https://doi.org/10.1002/2016JF003842) - A modeling study of the effect of runoff variability on the effective pressure beneath Russell Glacier, West Greenland (paper)
- [Hewitt2017](https://doi.org/10.3189/002214311796405951) - Modelling distributed and channelized subglacial drainage: the spacing of channels (paper)
- [HoffmanPrice2014](https://doi.org/10.1002/2013JF002943) - Feedbacks between coupled subglacial
hydrology and glacier dynamics (paper)
- [KesslerAnderson2004](https://doi.org/10.1029/2004GL020622) - Testing a numerical glacial hydrological model using spring speed‐up events and outburst floods (paper)
- [PimentelFlowers2010](https://doi.org/10.1098/rspa.2010.0211) - A numerical study of hydrologically driven glacier dynamics and subglacial flooding (paper)
- [Werderetal2013](https://doi.org/10.1002/jgrf.20146) - Modeling channelized and distributed subglacial drainage in two dimensions (paper)


#### ISG Visualization Tools
- [GLIMS Glacier Viewer](http://www.glims.org/maps/glims) - Global Land Ice Measurememts from Space (GLIMS) / Global Terrestrial Network for Glaciers (GTN-G) Glacier Viewer covering a range of inventories
- [OGGM-edu](http://edu.oggm.org) - Interactive glacier apps for educational purposes
- [WGMS Smartphone App](https://wgms.ch/glacierapp/) - Browsing glaciers worldwide and in your proximity
- [WGMS FoG Browser](https://wgms.ch/fogbrowser/) - Fluctuations of Glaciers Dataset Browser
- [GLAMOS](https://glamos.ch) - Browsing Swiss glaciers on an interactive map
- [iceplotlib](https://github.com/juseg/iceplotlib) - Plotting tools for PISM using matplotlib and netcdf4-python

#### ISG Remote Sensing Software
- [DIC_FFT](https://github.com/bickelmps/DIC_FFT_ETHZ) -  Detect and quantify surface displacements in multi-temporal images ([p](https://www.mdpi.com/2072-4292/10/6/865))
- [glaciersat](https://github.com/jlandmann/glaciersat) -  Tools to observe glaciers from satellite imagery, such as albedo calculation and transient snow line detection
- [icepyx](https://github.com/icesat2py/icepyx) - Python tools for obtaining and working with ICESat-2 laser altimetry data

### ISG Data
#### ISG Global Data
- [FoG](https://wgms.ch/data_databaseversions/) - Fluctuations of Glaciers with point, elevation band and specific mass balance measurements 
- [Glacier Length Fluctuations](https://folk.uio.no/paulwl/length.php)  - Glacier Length Database by Paul Leclercq
- [GlaThiDa](https://www.gtn-g.ch/data_catalogue_glathida/)  - Glacier Thickness Dataset with point, elevation band and specific ice thickness measurements
- [RGI](http://www.glims.org/RGI/index.html) - Randolph Glacier Inventory, a global inventory of glacier outlines ([report an issue](https://github.com/GLIMS-RGI/rgi_issue_tracker))
- [WGI](https://nsidc.org/data/g01130)  - World Glacier Inventory
- [ITS_LIVE](https://its-live.jpl.nasa.gov/) - A NASA MEaSUREs project to provide automated, low latency, global glacier flow and elevation change datasets.

#### ISG National Data
##### Switzerland
- [GLAMOS](https://glamos.ch) - Glacier Monitoring Switzerland: the Swiss glacier data portal]
##### Austria
- [Austrian Glacier Inventory](https://doi.org/10.1594/PANGAEA.844988) - Multi-temporal inventory of Austrian glaciers as a shapefile

### ISG Educational Tools and Data
- [OGGM-edu](http://edu.oggm.org) - Educational material about glaciers, powered by OGGM and MyBinder
- [glacier-graphics](https://github.com/OGGM/glacier-graphics) - A collection of glacier graphics that can be used for education and outreach
- [Ed Bueler's Karthaus material](https://github.com/bueler/karthaus) - Notes and codes for Ed Bueler's numerical lectures at Karthaus (Italy) Summer School on Ice Sheets and Glaciers
- [UW_Geodetic_Mass_Budget_Scripts](https://github.com/ShashankBice/UW_Geodetic_Mass_Budget_Scripts) - no description provided
- [Glaciers Dynamics Lecture](https://github.com/aaschwanden/glaciers617) - Glacier Dynamics lecture by Andy Aschwanden
- [Glacier & Ice Sheet Dynamics at Georgia Tech](https://github.com/nsidc/NSIDC-Data-Tutorials) - Alex Robel's slides, notes, and code demonstrations for grad/undergrad course in glaciology 
- [GRANTSISM](http://homepages.ulb.ac.be/~fpattyn/grantism/)  - GReenland & ANTarctic Ice Sheet Model + Svalbard extension, based on Excel with suggested exercises  ([p](https://doi.org/10.1016/j.cageo.2005.06.020) [p](https://doi.org/10.1080/10899995.2018.1412177))
- [js-ism](https://github.com/mewo2/js-ism) - Reimplementation of GRANTISM in Javascript
- [International Summer School in Glaciology, McCarthy, Alaska](https://glaciers.gi.alaska.edu/courses/summerschool) - bi-annual summer school hosted by University of Alaska in Fairbanks
  - [McCarthy course material](https://glaciers.gi.alaska.edu/content/course-material-0) - Lecture notes on Ice Sheet Modelling, Mass Balance, Glacier Hydrology, Remote Sensing, and so on.
  - [Ed Bueler's material](https://github.com/bueler/mccarthy) - Slides, notes, and codes on numerical glacier and ice sheet modeling
  - [Andy Aschwanden's material](https://github.com/aaschwanden/mccarthy-summerschool) - Lecture notes and exercises on ice flow and thermodynamics
- [Lindsey Nicholson's teaching](https://github.com/linznicholson/teaching) - Materials Lindsey developed for teaching (mainly) about glaciers
- [Physics of Glacier lecture at ETH](http://people.ee.ethz.ch/~luethim/teaching.html) - All the course material for the "Physics of Glaciers" class
- [Subglacial processes workshop material](https://maurow.bitbucket.io/teaching/copenhagen2014.html) - Mauro Werder's material from the subglacial processes workshop Copenhagen
- [Swisseduc Glaciers online](https://www.swisseduc.ch/glaciers/) - A collection of photos and processes of different glaciers


## Sea Ice
### SI Software
- [CICE](https://github.com/CICE-Consortium/CICE) - CICE sea-ice model
- [Icepack](https://github.com/CICE-Consortium/Icepack) - sea-ice column physics
- [SIS2](https://github.com/NOAA-GFDL/SIS2) - NOAA-GFDL's Sea Ice Simulator version 2
- [SI3](https://forge.ipsl.jussieu.fr/nemo/chrome/site/doc/NEMO/guide/html/guide.html) - sea ice model of the NEMO consortium
- [IceNet](https://github.com/tom-andersson/icenet-paper) - code to train a deep learning seasonal Arctic sea ice forecasting model ([paper](https://www.nature.com/articles/s41467-021-25257-4)/[pre-trained networks](https://ramadda.data.bas.ac.uk/repository/entry/show?entryid=71820e7d-c628-4e32-969f-464b7efb187c)/[Jupyter notebook demonstrator](https://the-environmental-ds-book.netlify.app/polar/modelling/polar-modelling-icenet.html))
### SI Data 

## Snow
### SN Software
- [SNOWPACK](https://models.slf.ch/p/snowpack/)  - multi-purpose snow and land-surface model ([p](https://doi.org/10.1016/S0165-232x(02)00073-3))
- [cosipy](https://github.com/cryotools/cosipy) - Coupled snowpack and ice surface energy and mass balance model in Python
- [FSM2](https://github.com/RichardEssery/FSM2) - Flexible Snow Model: a multi-physics energy balance model of accumulation and melt of snow on the ground and in forest canopies ([p](http://www.geosci-model-dev.net/8/3867/2015/))
- [snowtools](https://github.com/dshean/snowtools) - D. Shean's utilities for working with snow data
- [let-it-snow](https://gitlab.orfeo-toolbox.org/remote_modules/let-it-snow/) - Operational snow cover detection from optical multispectral level 2A products ([p](https://www.earth-syst-sci-data.net/11/493/2019/essd-11-493-2019.html))
- [openAMUNDSEN](https://github.com/openamundsen/openamundsen) - Modular snow and hydroclimatological modeling framework
- [TARTES](https://github.com/ghislainp/tartes) - Two-stream radiative transfer in Snow model, also available as a [webapp](http://snowtartes.pythonanywhere.com/)
- [snowoptics](https://github.com/ghislainp/snowoptics) - Functions to compute spectral albedo and extinction of snow on flat and tilted terrains, also available as a [webapp](https://snowslope.pythonanywhere.com/)
- [SMRT](https://github.com/smrt-model/smrt) - Snow Microwave Radiative Transfer model to calculate scattering of microwave radiation in snow ([p](https://doi.org/10.5194/gmd-11-2763-2018))

### SN Data
#### SN Global Data
 - [CommunitySnowObs](http://communitysnowobs.org/) - Community Snow Observations


# Contributing

- Please check for duplicates first.
- Keep an alphabetical order if there is more than one entry in your category
- Keep descriptions short, simple and unbiased.
- Please make an individual commit for each suggestion
- Add a new category if needed.

Thanks for your suggestions!


# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
