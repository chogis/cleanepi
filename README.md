
<!-- README.md is generated from README.Rmd. Please edit that file. -->
<!-- The code to render this README is stored in .github/workflows/render-readme.yaml -->
<!-- Variables marked with double curly braces will be transformed beforehand: -->
<!-- `packagename` is extracted from the DESCRIPTION file -->
<!-- `gh_repo` is extracted via a special environment variable in GitHub Actions -->
<!-- README.md is generated from README.Rmd. Please edit that file -->

# cleanepi

**cleanepi** provides functions to clean epidemiological data provided
in the form of a data frame or other related data type.

<!-- badges: start -->

[![License:
MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![R-CMD-check](https://github.com/epiverse-trace/cleanepi/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/epiverse-trace/cleanepi/actions/workflows/R-CMD-check.yaml)
[![Codecov test
coverage](https://codecov.io/gh/epiverse-trace/cleanepi/branch/main/graph/badge.svg)](https://app.codecov.io/gh/epiverse-trace/cleanepi?branch=main)
[![lifecycle-concept](https://raw.githubusercontent.com/reconverse/reconverse.github.io/master/images/badge-concept.svg)](https://www.reconverse.org/lifecycle.html#concept)
<!-- badges: end -->

## Installation

You can install the development version of cleanepi from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
# remotes::install_github("epiverse-trace/cleanepi", build_vignettes=TRUE)
library(cleanepi)
```

## Manual

``` r
browseVignettes("cleanepi")
#> No vignettes found by browseVignettes("cleanepi")
```

## Description

| function name                                   | description                                                                                                                                                                                                          |
|:------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **cleanepi**                                    | check whether the IDs comply with the expected format. It will check for: mistakes in subject IDs prefix and suffix, subject IDs with incorrect length, number in subject IDs that are out of range or not permitted |
| [check_subject_ids](./doc/check_subject_ids.md) | check whether the IDs comply with the expected format                                                                                                                                                                |
| **standardize_date**                            | convert date column into *%Y-%m-%d*                                                                                                                                                                                  |
| **calculate_age**                               | calculate age from date column. Returned age can be in either *years*, or *months*, or *weeks*, or *days* or a combination of some of these                                                                          |
| **check date sequence**                         | check the sequence of event dates                                                                                                                                                                                    |
| **WIP**                                         | work in progress                                                                                                                                                                                                     |

## Development

### Lifecycle

This package is currently a *concept*, as defined by the [RECON software
lifecycle](https://www.reconverse.org/lifecycle.html). This means that
essential features and mechanisms are still being developed, and the
package is not ready for use outside of the development team.

### Contributions

Contributions are welcome via [pull
requests](https://github.com/%7B%7B%20gh_repo%20%7D%7D/pulls).

Contributors to the project include:

- Karim Mané
- 

### Code of Conduct

Please note that the cleanepi project is released with a [Contributor
Code of
Conduct](https://github.com/epiverse-trace/.github/blob/main/CODE_OF_CONDUCT.md).
By contributing to this project, you agree to abide by its terms.
