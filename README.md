
<!-- README.md is generated from README.Rmd. Please edit that file -->

# airports <a href="https://openintrostat.github.io/airports"><img src="man/figures/logo.png" align="right" alt="Package hex logo" height="120" /></a>

<!-- badges: start -->

[![CRAN
status](https://www.r-pkg.org/badges/version/airports)](https://CRAN.R-project.org/package=airports)
[![R-CMD-check](https://github.com/OpenIntroStat/airports/workflows/R-CMD-check/badge.svg)](https://github.com/OpenIntroStat/airports/actions)
[![Lifecycle:
stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)
[![CRAN RStudio mirror
downloads](http://cranlogs.r-pkg.org/badges/airports)](https://cran.r-project.org/package=airports)
<!-- badges: end -->

This package contains geographic, use, and property related data on
airports.

## Installation

You can install the package from [CRAN](https://CRAN.R-project.org)
with:

``` r
install.packages("airports")
```

Additionally, you can install the development version of airports from
GitHub with:

``` r
#install.packages("devtools")
library(devtools)
install_github("OpenIntroStat/airports")
```

## Usage

The datasets from this package can be used in a teaching context for
data visualization and data manipulation exercises.

## airports and openintro

The datasets from this package are used in
[OpenIntro](https://www.openintro.org/) textbooks and other resources.
These datasets originally lived in the
[**openintro**](http://openintrostat.github.io/openintro/) package, up
until openintro 2.0.0. The motivation for extracting these datasets out
of the openintro package was to create a new package where we can
continue to add more data on airports from all over the world. For those
looking for a seamless experience with OpenIntro resources, note that
the contents of this package will be loaded along with the openintro
package as well, so that you can run `library(openintro)` and use the
datasets from airports.

## Questions, bugs, feature requests

You can file an issue to get help, report a bug, or make a feature
request.

When filing an issue to get help or report a bug, please make a minimal
**repr**oducible **ex**ample using the
[reprex](https://reprex.tidyverse.org/) package. If you haven’t heard of
or used reprex before, you’re in for a treat! See
[here](https://www.tidyverse.org/help/) for additional reprex pointers.

Before opening a new issue, be sure to [search issues and pull
requests](https://github.com/openintrostat/airports/issues) to make sure
the bug hasn’t been reported and/or already fixed in the development
version. By default, the search will be pre-populated with
`is:issue is:open`. You can [edit the
qualifiers](https://help.github.com/articles/searching-issues-and-pull-requests/)
(e.g. `is:pr`, `is:closed`) as needed. For example, you’d simply remove
`is:open` to search *all* issues in the repo, open or closed.

## Code of Conduct

Please note that the airports project is released with a [Contributor
Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
