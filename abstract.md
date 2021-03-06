# The OpenEO R-client: A tool to analyse big earth observation data in R
Earth observation data are images collected by satellites orbiting the earth. The growing amount of new satellites and the continuation of established missions lead to a rapid increase of data. The Copernicus Open Access Hub for example provides access to 10 PB of data. To avoid having to download large amounts of earth observation data, multiple cloud services have been developed independently for storing and processing these data. OpenEO (https://openeo.org/, a Horizon 2020 project) developed a unified API to access these services to foster interoperability and reproducibility across cloud services while reducing complexity for users. 
The openEO R client allows R users to efficiently interact with big earth observation data on cloud platforms from within the R language. The client is available as an R package (https://github.com/Open-EO/openeo-r-client) and integrates the functionalities of openEO into the R environment. R users are enabled to create efficient and scalable workflows that can be processed by different cloud services and access resources that would otherwise be hard to access using R. Additionally, openEO provides user-defined functions as a way to have R or Python functions being evaluated within the cloud platforms, e.g. to run complex time series models on large amounts of high-resolution multispectral earth observation data.
