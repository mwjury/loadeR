What is loadeR?
===============

`loadeR` is an R package for climate data data access and manipulation, including:
 * Reading local and remote (OPeNDAP) climate datasets
 * Creation of catalogs
 * Integration with the User Data Gateway ([UDG](http://www.meteo.unican.es/udg-wiki))
 * Basic data maniputation 

`loadeR` is powered by NetCDF-Java trough the `rJava` package. Thus, a large variety of files can be read, including the most common NetCDF, Grib, HDF, etc. Find out more about this package (including [installation information](https://github.com/SantanderMetGroup/loadeR/wiki/Installation)) in the [loadeR's WIKI](https://github.com/SantanderMetGroup/loadeR/wiki).

# Other packages of the `loadeR` bundle

 * [`loadeR.ECOMS`](https://github.com/SantanderMetGroup/loadeR.ECOMS/) extends `loadeR` by providing homogenized access to ***seasonal and decadal forecast datasets*** from the [ECOMS](http://www.eu-ecoms.eu) initiative. More information in the [ECOMS-UDG web](https://meteo.unican.es/trac/wiki/udg/ecoms). 

 * [`loadeR.2nc`](https://github.com/SantanderMetGroup/loadeR.2nc/) provides support for ***exporting to NetCDF***.

 * [`downscaleR`](https://github.com/SantanderMetGroup/downscaleR) is an R package for ***empirical-statistical downscaling*** of daily data, including bias correction techniques.  

---
**Since November 2015, this package supersedes the data loading capabilities of package [`downscaleR`](https://github.com/SantanderMetGroup/downscaleR).**



