<!-- README.md is generated from README.Rmd. Please edit that file -->

# microperimetr

This package will help you work with microperimetry data.  
It is built for centervue’s maia and compass devices.

## Features

  - Extracting data from MAIA raw (tgz) files becomes as easy as pie.
  - Fully automated comparison of your visual field data with normdata
    from the literature.
  - microperimetr has functions for both location-dependent and
    location-independent visual field analysis. Because the normdata is
    interpolated for location-dependent analysis, any custom grid can be
    used for both types of analysis.
  - microperimetr also includes functions for some more or less common
    visualistaion of visual field data

## Example

This is a basic example which shows you how to import your visual field
data and plot the (estimated) mean deviation for each included
test:

``` r
# save the tgz files from MAIA patient backup into any directory, here "norm_raw", which is a folder in the working directory 
# library(microperimetr)
# testdata <- read_maia(folder = file.path(getwd(), "data-raw"))
# comparedat <- compare_norm(testdata)
```

``` r
# plot_MD(comparedat)
```

## Installation

``` r
# for the development version 
devtools::install_github(tjebo/microperimetr)
```

## Sources

Norm data was used from Jonathan Denniss and Maximilian Pfau.

[Raw data from Denniss et al. has been made available
online](https://www.sciencedirect.com/science/article/pii/S2352340916304978).

Accompanying paper in IOVS:
<http://iovs.arvojournals.org/article.aspx?articleid=2571342>
