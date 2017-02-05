[![Project Status: WIP - Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip)
[![Travis Build Status](https://img.shields.io/travis/prioritizr/prioritizr/master.svg?label=Mac%20OSX%20%26%20Linux)](https://travis-ci.org/prioritizr/prioritizr)
[![AppVeyor Build Status](https://img.shields.io/appveyor/ci/prioritizr/prioritizr/master.svg?label=Windows)](https://ci.appveyor.com/project/prioritizr/prioritizr)
[![Coverage Status](https://codecov.io/github/prioritizr/prioritizr/coverage.svg?branch=master)](https://codecov.io/github/prioritizr/prioritizr?branch=master)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/prioritizr)](https://CRAN.R-project.org/package=prioritizr)

# Conservation Prioritization with Integer Programming in R

`prioritizr` is an R package for solving systematic conservation prioritization problems using the techniques of integer linear programming (ILP). In particular, both the minimum set cover (Marxan-like) and maximum coverage reserve design problems can be solved. The package offers a unified interface to a variety of commercial and open-source ILP solvers. In contrast to heuristic approaches, such as simulated annealing, the ILP algorithms used by `prioritizr` can find exact solutions to optimization problems.

This package consists largely of two layers of functions: those that define a reserve design problem and those that solve a reserve design problem using any one of a variety of solvers. The details of the solvers are intentionally abstracted away so that the user requires minimal knowledge of the specific solvers or ILP in general.


```r
plot(1)
```

![plot of chunk unnamed-chunk-1](inst/vign/readme-figure/unnamed-chunk-1-1.png)

**This package is under development, please check back later.**

