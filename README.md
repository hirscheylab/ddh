# ddh <img src="man/figures/hex_ddh.png" align="right" height="120" />

<!-- badges: start -->
[![Lifecycle: stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)
[![R-CMD-check](https://github.com/matthewhirschey/ddh/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/matthewhirschey/ddh/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

This package contains functions for data analysis and graphing, data sets, and supporting materials for the [ddh web app](https://www.datadrivenhypothesis.com).

## Installation

```{r, eval = FALSE}
# install.packages("devtools")
devtools::install_github("heurekalabsco/ddh")
```

## Usage

```{r, eval = FALSE}
library(ddh)

# Load DDH data from your local directory
ddh::load_ddh_data(app_data_dir = "xxxx") # path to DDH data dir

# And start using DDH functions!
ddh::make_radial(input = list(content = "ROCK1"))
```

## System Requirements

# Hardware Requirements
- ddh requires a standard computer with R programming software and enough RAM to support the program functions.
- No specialized hardware is required.

# OS Requirements
- ddh has been tested on the following systems:
  macOS: Sonoma (14.6.1)
  R version 4.4.3

# Typical Install Time on a 'Normal' Computer
- Less than 5 minutes to install the required R packages.
- Up to 10 minutes if all dependencies need to be installed from scratch.

# Expected Run Time for Demo on a 'Normal' Computer
- For single pathway-pathway associations, approximately 15 minutes

## License
# MIT License
Copyright (c) 2022 ddh authors
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MECHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Citation

Hirschey M. _Making data-driven hypotheses for gene functions by integrating dependency, expression, and literature data_. bioRxiv 2020.07.17.208751; doi: https://doi.org/10.1101/2020.07.17.208751

## Code of Conduct

Please note that the ddh project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.

