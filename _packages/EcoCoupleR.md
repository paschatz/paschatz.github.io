---
title: "EcoCoupleR: a computational implementation of ecosystem coupling in R"
excerpt: "<div style='float: left; margin-right: 10px;'><img src='/images/ecocoupler_logo.png' width='150px'></div> An R package that offers functions for calculating ecological coupling. "
collection: packages
---

```EcoCoupleR``` is an R package that provides functions for calculating ecosystem coupling as has been described by [Ochoa-Hueso et
al. (2021)](https://www.sciencedirect.com/science/article/pii/S2590332221003535?via%3Dihub).
This is an ongoing and under construction project. For the time being, the package consists only of one function; `eco_coupling()`. 
In a nutshell, `eco_coupling()` takes as an input a correlation matrix (or a list of many matrices), trims the lower-diagonal, to avoid double
counting, removes self-correlations (the diagonal) and calculates a sinlge ecosystem coupling value. 

For the time being, the package is not available on CRAN, but you can install it from GitHub using devtools.
Although the package is functional and has been tested, it is still under development and more functions will be added in the future.
The first major update will introduce null models and will allow users to calculate the different states of coupling (decoupling, coupling, anticoupling).

To find more, please visit the [GitHub repository](https://github.com/paschatz/EcoCoupleR) of the project.
