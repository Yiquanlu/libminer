
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->

<!-- badges: end -->

The goal of libminer is to …

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("Yiquanlu/libminer")
```

``` r
# install.packages("pak")
pak::pak("Yiquanlu/libminer")
```

## Example usage

To get a count of installed packages in each of your library locations,
optionally with the total sizes, use the `lib_summary()` function:

``` r
library(libminer)
lib_summary()
#>                                                                                       Library
#> 1                                                     /opt/anaconda3/envs/raukr/lib/R/library
#> 2 /private/var/folders/kg/hgcrwswn5j9cx4mnc5rmgsx00000gn/T/Rtmp39eUUb/temp_libpatha9a86de4909
#>   n_packages
#> 1        334
#> 2          1
```
