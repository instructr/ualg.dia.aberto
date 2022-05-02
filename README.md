
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ualg.dia.aberto <img src='man/figures/logo.svg' align="right" height="139" />

<!-- badges: start -->
<!-- badges: end -->

The goal of `{ualg.dia.aberto}` is to provide a Bioinformatics
interactive tutorial as a scientific outreach activity for highschoolers
within the UAlg Dia Aberto yearly event.

## Installation

You can install the package `{ualg.dia.aberto}` from
[GitHub](https://github.com/).

Make sure you have the `{remotes}` package installed:

``` r
install.packages('remotes')
```

Now you can install `{ualg.dia.aberto}` from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("instructr/ualg.dia.aberto")
```

## Tutorials

To list the included tutorials in `{ualg.dia.aberto}`:

``` r
learnr::available_tutorials(package = 'ualg.dia.aberto')
#> Available tutorials:
#> * ualg.dia.aberto
#>   - dia_aberto_ualg_2022 : "Dias Abertos UAlg | 3-4 Maio 2022"
```

To run one of the tutorials included in `{ualg.dia.aberto}` use the
command `learnr::run_tutorial()`. For example to run the interactive
tutorial `"dia_aberto_ualg_2022"`:

``` r
learnr::run_tutorial('dia_aberto_ualg_2022', package = 'ualg.dia.aberto')
```
