
[![minimal R version](https://img.shields.io/badge/R%3E%3D-3.3.3-6666ff.svg)](https://cran.r-project.org/) [![GitHub (pre-)release](https://img.shields.io/github/release/timtrice/rrricanes/all.svg)](https://github.com/timtrice/rrricanes/tags) [![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/rrricanes)](https://cran.r-project.org/package=rrricanes) [![Build Status](https://img.shields.io/travis/timtrice/rrricanes/feature-47.svg)](https://travis-ci.org/timtrice/rrricanes) [![AppVeyor Build Status](https://img.shields.io/appveyor/ci/timtrice/rrricanes/feature-47.svg)](https://ci.appveyor.com/project/timtrice/rrricanes) [![codecov](https://codecov.io/gh/timtrice/rrricanes/branch/feature-47/graph/badge.svg)](https://codecov.io/gh/timtrice/rrricanes)

rrricanes
=========

`rrricanes` is a R library that extracts information from available archives on past and current tropical cyclones. Currently, archives date back to 1998.

Data can be obtained for cyclones in the north Atlantic (considered the Atlantic Basin) and north-eastern Pacific (the East Pacific Basin from 140°W and eastward, and Central Pacific Basin from 140°W to 180°W).

Getting Started
---------------

Please view the vignette 'Getting Started':

``` r
vignette("getting-started", package = "rrricanes")
```

[Online documentation](https://timtrice.github.io/rrricanes/) is also available.

### Prerequisites

`rrricanes` requires an active internet connection as data is extracted from online sources.

Additionally, to use high resolution tracking maps you must install the `rnaturalearthhires` package:

``` r
install.packages("rnaturalearthhires",
                 repos = "http://packages.ropensci.org",
                 type = "source")
```

### Installing

`rrricanes` is currently only available in GitHub. It can be installed using the `devtools` package:

``` r
devtools::install_github("timtrice/rrricanes@v0.2.0-alpha")
```

Built With
----------

-   [R 3.3.3](https://www.r-project.org/) - The R Project for Statistical Computing

Contributing
------------

Please read [CONTRIBUTING.md](https://github.com/timtrice/rrricanes/blob/master/.github/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

Versioning
----------

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/timtrice/Hurricanes/tags).

Authors
-------

-   **Tim Trice** - *Initial work* - [timtrice](https://github.com/timtrice)

See also the list of [contributors](https://github.com/timtrice/rrricanes/contributors) who participated in this project.

License
-------

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

Acknowledgments
---------------

-   [Molyneux, James](https://github.com/jimmylovestea)
-   [Padgham, Mark](https://github.com/mpadge)
-   [Rudis, Bob](https://github.com/hrbrmstr)
