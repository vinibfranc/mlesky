
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mlesky : Maximum likelihood phylodynamic inference

This package performs inference of past population size dynamics from a
dated phylogeny using a maximum likelihood approach. The main features
are as follows:

  - Three different phylodynamic models are implemented (skygrid,
    skygrowth and skysigma)
  - A novel cross-validation approach is used for selecting the
    smoothing parameter
  - The resolution of the grid can be selected using AIC or BIC
  - Covariate data can be included into the analysis to quantify
    association
  - Multiple phylogenies can be analysed simultaneously that share the
    same demographic function

For a complete description of the statistical methodology underpinning
this package, see our preprint:
<https://www.biorxiv.org/content/10.1101/2021.01.18.427056v1.full>

## Installation

In R, install the `devtools` package and run

    devtools::install_github('emvolz-phylodynamics/mlesky')

## Documentation

See the vignettes in the R package for examples of how to use mlesky.
