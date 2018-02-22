
<!-- README.md is generated from README.Rmd. Please edit that file -->
did
===

The package contains tools for computing average treatment effect parameters in Difference in Differences models with more than two periods and with variation in treatment timing. The main parameters are group-time average treatment effects which are the average treatment effect for a particular group at a a particular time. These can be aggregated into a fewer number of treatment effect parameters, and the package deals with the cases where there is selective treatment timing, dynamic treatment effects, calendar time effects, or combinations of these. There are also functions for testing the Difference in Differences assumption, and plotting group-time average treatment effects.

Installation
------------

You can install did from github with:

``` r
# install.packages("devtools")
devtools::install_github("bcallaway11/did")
```

Example
-------

This is a basic example which shows you how to solve a common problem:

``` r
## basic example code
```
