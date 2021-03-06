
# VIBER <img src='man/figures/logo.png' align="right" height="139" />

<!-- badges: start -->

[![R-CMD-check](https://github.com/caravagnalab/VIBER/workflows/R-CMD-check/badge.svg)](https://github.com/caravagnalab/VIBER/actions)
[![pkgdown](https://github.com/caravagnalab/VIBER/actions/workflows/pkgdown.yaml/badge.svg)](https://github.com/caravagnalab/VIBER/actions/workflows/pkgdown.yaml)
[![Lifecycle:
maturing](https://img.shields.io/badge/lifecycle-stable-green.svg)](https://www.tidyverse.org/lifecycle/#stable)

<!-- badges: end -->

`VIBER` is a package that implements a variational Bayesian model to fit
multi-variate Binomial mixtures. The statistical model is
semi-parametric and fit by a variational mean-field approximation to the
model posterior. The components are Binomial distributions which can
model count data; these can be used to model sequencing counts in the
context of cancer, for instance. The package implements methods to fit
and visualize clustering results.

#### Citation

[![](https://img.shields.io/badge/doi-10.1038/s41588--020--0675--5-red.svg)](https://doi.org/10.1038/s41588-020-0675-5)

If you use `VIBER`, please cite:

-   G. Caravagna, T. Heide, M.J. Williams, L. Zapata, D. Nichol, K.
    Chkhaidze, W. Cross, G.D. Cresswell, B. Werner, A. Acar, L. Chesler,
    C.P. Barnes, G. Sanguinetti, T.A. Graham, A. Sottoriva. Subclonal
    reconstruction of tumors by using machine learning and population
    genetics. Nature Genetics 52, 898–907 (2020).

#### Help and support

## [![](https://img.shields.io/badge/GitHub%20Pages-https://caravagnalab.github.io/VIBER/-yellow.svg)](https://caravagnalab.github.io/VIBER)

### Installation

You can install the released version of `VIBER` from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("caravagnalab/VIBER")
```

------------------------------------------------------------------------

#### Copyright and contacts

Giulio Caravagna. Cancer Data Science (CDS) Laboratory.

[![](https://img.shields.io/badge/Email-gcaravagn@gmail.com-steelblue.svg)](mailto:gcaravagn@gmail.com)
[![](https://img.shields.io/badge/CDS%20Lab%20Github-caravagnalab-seagreen.svg)](https://github.com/caravagnalab)
[![](https://img.shields.io/badge/CDS%20Lab%20webpage-https://www.caravagnalab.org/-red.svg)](https://www.caravagnalab.org/)
