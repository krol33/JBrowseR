
<!-- README.md is generated from README.Rmd. Please edit that file -->

# RBrowse

<!-- badges: start -->
<!-- badges: end -->

JBrowseR is an R package that provides a simple and clean interface to
[JBrowse 2](https://jbrowse.org/jb2/) for R users. Using JBrowseR, you
can:

-   Embed the JBrowse 2 genome browser in **R Markdown** documents and
    **Shiny applications**
-   Deploy a genome browser directly from the R console to view your
    data
-   Customize your genome browser to display your own data

With this functionality, you can deploy a first-class genome browser
with your data in just a few lines of R code!

## Installation

You can **soon** install the released version of RBrowse from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("RBrowse")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("elliothershberg/RBrowse")
```

## Example

This line of code can be a used to launch a genome browser from your R
console:

``` r
library(RBrowse)
RBrowse("ViewHg19",
        location = "10:29,838,737..29,838,819")
```

<img src="man/figures/README-example-1.png" width="100%" />

## Getting started

In order to get started with JBrowseR, please refer to the vignette that
best suits your needs:
