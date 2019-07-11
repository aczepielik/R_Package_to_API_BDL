# bdl 1.0.0

## Overview
'bdl' package is an interface to Local Data Bank (Bank Danych Lokalnych - bdl) 
[API](https://bdl.stat.gov.pl/BDL). It is a set of tools that includes: quick plotting 
and maps generation, with the usage of the data from the data bank. 

The information about how to use this tool is included in the built in R help documentation and on package webpage [https://kaniakrzysztof.github.io/bdl/](https://kaniakrzysztof.github.io/bdl/). 

Try
```{R}
help(p='bdl')
```

More info about the metadata can be found at:
* https://bdl.stat.gov.pl/BDL/start

## Installation
To install this package run these commands:

```{R}
install.packages("remotes", type = "binary")
remotes::install_github("statisticspoland/R_Package_to_API_BDL", upgrade = "always", type = "binary")
```

If installation through remotes didn't work, try installing the package manually by 
downloading source package: https://github.com/statisticspoland/R_Package_to_API_BDL/releases/download/1.0.0/bdl_1.0.0.zip and executing

```{R}
install.packages('path_to_file/bdl_1.0.0.zip', repos = NULL, type="source")
```
