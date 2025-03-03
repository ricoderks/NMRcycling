
<!-- README.md is generated from README.Rmd. Please edit that file -->

# NMRcycling

<!-- badges: start -->
<!-- badges: end -->

The goal of `NMRcycling` is to provide the R code that is described in
the chapter *NMR based Metabolomics: monitoring physiological response
to physical exercise* in the book *A Practical Guide to Metabolomics
Applications in Health and Disease*. This package contains the script
and the functions to work with the NMR data. The data itself is stored
in a second repository,
[NMRcycling_data](https://github.com/CPM-Metabolomics-Lipidomics/NMRcycling_data).
The data is also in the package in order to build the vignette.

## Installation

You can install `NMRcycling` with and this will install all packages
needed to build the vignette.

``` r
# install.packages("remotes")
remotes::install_github("CPM-Metabolomics-Lipidomics/NMRcycling", 
                        build_vignettes = TRUE,
                        dependencies = c("Imports", "Suggests"),
                        upgrade = "never")
```

Have a look at the vignette with:

``` r
browseVignettes(package = "NMRcycling")
```

## Online version

You can also run the `NMRcycling` notebook on Google Colab. No software
installation necessary, you only need a Google account. Just go to
[NMRcycling Google Colab
site](https://colab.research.google.com/drive/1a71rNVgBCjXN-OeUnPt15IvdPgydXYXz?usp=sharing),
and click “Run all” in the “Runtime” pull down menu.
