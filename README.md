
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->

[![R-CMD-check](https://github.com/rserran/libminer/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/rserran/libminer/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of libminer is to help you understand your libraries better,
and learn how to develop packages.

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("rserran/libminer")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(libminer)
lib_summary()
#>                                                                                      Library
#> 1                       /Library/Frameworks/R.framework/Versions/4.3-arm64/Resources/library
#> 2 /private/var/folders/_c/g4nn9vsd285_gcjw3nh8c8kr0000gn/T/Rtmpwqcbua/temp_libpathf4680a47b8
#>   n_packages
#> 1        634
#> 2          1

# also can calculate sizes
lib_summary(sizes = TRUE)
#>                                                                                      Library
#> 1                       /Library/Frameworks/R.framework/Versions/4.3-arm64/Resources/library
#> 2 /private/var/folders/_c/g4nn9vsd285_gcjw3nh8c8kr0000gn/T/Rtmpwqcbua/temp_libpathf4680a47b8
#>   n_packages   lib_size
#> 1        634 3426770415
#> 2          1      14393
```
