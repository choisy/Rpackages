<!--- <h1><img src="https://www.r-project.org/logo/Rlogo.png" alt="" style="width:50px;height:43.75px;"> packages</h1> --->

<h1><img src="R.png" alt="" style="width:50px;height:43.26923px;"> packages</h1>

You can install the packages listed below directly from R, provided the `devtools` package is installed. If not, install it:

```R
> install.packages("devtools")
```

With this package installed you can install the packages from [GitHub](https://github.com/choisy) repositories with:

```R
> devtools::install_github("choisy/package_name", build_vignettes = TRUE)
```

and the packages from [Bitbucket](https://bitbucket.org/choisy) repositories with:

```R
> devtools::install_bitbucket("choisy/package_name", build_vignettes = TRUE)
```

## Data packages

| Package | Description | Size | Repo |
|:--------|:------------|-----:|:----:|
| [censusVN2009](https://choisy.github.io/censusVN2009) | Population census of Vietnam by commune, 2009 | 53.0MB | [<img src="Github_small.png" alt="" style="width:30px;height:30px;">](https://github.com/choisy/censusVN2009) |
| [epiVN](https://choisy.github.io/epiVN) | Miscellaneous MoH / WHO EPI's data for Vietnam | 0.1MB | [<img src="Github_small.png" alt="" style="width:30px;height:30px;">](https://github.com/choisy/epiVN) |
| [gadmSEA](https://choisy.github.io/gadmSEA) | Country polygons in southeast Asia | 0.2MB | [<img src="Github_small.png" alt="" style="width:30px;height:30px;">](https://github.com/choisy/gadmSEA) |
| [gadmVN](https://choisy.github.io/gadmVN) | Provinces polygons of Vietnam from 1979 | 22.0MB | [<img src="Github_small.png" alt="" style="width:30px;height:30px;">](https://github.com/choisy/gadmVN) |
| [globcoverVN](https://choisy.github.io/globcoverVN) | Land use of Vietnam per pixel and per province | 8.3MB | [<img src="Github_small.png" alt="" style="width:30px;height:30px;">](https://github.com/choisy/globcoverVN) |
| [imhen](https://choisy.github.io/imhen) | Monthly meteorological data for Vietnam (1960-2015) | 0.7MB | [<img src="Github_small.png" alt="" style="width:30px;height:30px;">](https://github.com/choisy/imhen) |
| [srtmVN](https://choisy.github.io/srtmVN) | Digital Elevation Model (DEM) for Vietnam from SRTM | 108.0MB | [<img src="Bitbucket.png" alt="" style="width:30px;height:30px;">](https://bitbucket.org/choisy/srtmVN) |
| [worldpopVN](https://choisy.github.io/worldpopVN) | Local population density by pixel for Vietnam | 741.0MB | [<img src="Bitbucket.png" alt="" style="width:30px;height:30px;">](https://bitbucket.org/choisy/worldpopVN) |



