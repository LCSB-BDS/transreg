
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/rauschenberger/transreg?svg=true)](https://ci.appveyor.com/project/rauschenberger/transreg)

<!--
[![Travis-CI Build
Status](https://travis-ci.org/rauschenberger/transreg.svg)](https://travis-ci.com/rauschenberger/transreg)
[![Coverage
Status](https://codecov.io/github/rauschenberger/transreg/coverage.svg?branch=master)](https://codecov.io/github/rauschenberger/transreg)
-->

## Penalised regression with multiple sets of prior effects

Improves the predictive performance of ridge and lasso regression exploiting one or more sources of prior information on the importance and direction of effects.

## Installation

Install the current release from
[CRAN](https://CRAN.R-project.org/package=transreg):

``` r
#install.packages("transreg") # not yet released!
```

or the latest development version from [GitHub](https://github.com/lcsb-bds/transreg) or [GitLab](https://gitlab.lcsb.uni.lu/bds/transreg):

``` r
#install.packages("remotes")
remotes::install_github("lcsb-bds/transreg") # upstream
remotes::install_github("rauschenberger/transreg") # fork
remotes::install_gitlab("bds/transreg",host="gitlab.lcsb.uni.lu") # mirror
```

## Reference

Armin Rauschenberger 
[![AR](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0001-6498-4801),
Zied Landoulsi
[![ZL](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0002-2327-3904),
Mark A van de Wiel 
[![MvdW](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0003-4780-8472),
and Enrico Glaab
[![EG](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0003-3977-7469) (2022). 'Penalised regression with multiple sets of prior effects'.
*Manuscript in preparation.*
([arXiv: 2212.08581](https://doi.org/10.48550/arXiv.2212.08581))

<!--
[![CRAN
version](https://www.r-pkg.org/badges/version/transreg)](https://CRAN.R-project.org/package=transreg)
[![CRAN RStudio mirror
downloads](https://cranlogs.r-pkg.org/badges/transreg)](https://CRAN.R-project.org/package=transreg)
[![Total CRAN
downloads](https://cranlogs.r-pkg.org/badges/grand-total/transreg)](https://CRAN.R-project.org/package=transreg)
-->

## Disclaimer

The R package `transreg` implements penalised regression with multiple sources of prior effects (Rauschenberger et al., 2022).

Copyright &copy; 2022 Armin Rauschenberger, University of Luxembourg, Luxembourg Centre for Systems Biomedicine (LCSB), Biomedical Data Science (BDS)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <http://www.gnu.org/licenses/>.
