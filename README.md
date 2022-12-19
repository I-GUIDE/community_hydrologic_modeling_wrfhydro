# Scalable modeling of hydroclimatic extremes on I-GUIDE Platform - WRF-Hydro

As a use case to support and drive the development of scalable modeling of hydroclimatic extremes, a workflow system for setting up and executing subsets of the [National Water Model (NWM)](https://water.noaa.gov/about/nwm) has been prototyped. The NWM is an implementation of the [Weather Research and Forecasting Model Hydrological modeling system (WRF-Hydro)](https://ral.ucar.edu/projects/wrf_hydro) at the US continental scale. The cyberinfrastructure and workflows needed to set up and configure the data product subsets for a modeling domain of interest are complex, and demand a high level of skill from researchers, thus limiting broad applicability. [I-GUIDE](https://iguide.illinois.edu/) is building on modeling capabilities developed by the [HydroShare](https://www.hydroshare.org/) and [CyberGIS-Compute](https://cybergisxhub.cigi.illinois.edu/knowledge-base/components/cybergis-compute/what-is-cybergis-compute/) projects enabling scalable computing for the research community and integrating data connectors and processors from the [GeoEDF](https://github.com/geoedf) project to deploy easy to use workflows for setting up and running WRF-Hydro configured like the NWM for any watershed specified in the NWM modeling domain. The goal is to make it easy for researchers to identify or select a watershed of interest, set up the inputs for WRF-Hydro configured equivalently to the NWM and run the model to reproduce NWM results. This then serves as a starting point for in-depth evaluation of NWM results in the watershed of interest and research to improve understanding and modeling of the hydrological processes in that watershed that could be fed back into the NWM. It also serves as a starting point for broader collaborations connecting with social and environmental research, one example being the geospatial aspects of perspectives from river-related organizations elicited through surveys and interviews. Our work serves as a prototype of a general methodology enabled by the I-GUIDE Platform that broadens participation in modeling by reducing the needs for software installation and configuration, enabling easy access to high-performance computing, and supporting reproducibility and interoperability. The use of the I-GUIDE Platform that combines cloud and high-performance computing enables scaling up of this modeling workflow to more complex and larger domains than what researchers could address with their own personal computing resources.


This notebook demostrates the setup for a typical WRFHydro model on I-GUIDE platform.


[Open Notebook on I-GUIDE](https://jupyter.iguide.illinois.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FI-GUIDE%2Fcommunity_hydrologic_modeling_wrfhydro&urlpath=lab%2Ftree%2Fcommunity_hydrologic_modeling_wrfhydro%2Figuide_wrfhydro.ipynb+&branch=main)
