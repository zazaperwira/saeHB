
<!-- README.md is generated from README.Rmd. Please edit that file -->

# saeHB

<!-- badges: start -->

<!-- badges: end -->

We designed this package to provide several functions for area level of
small area estimation using hierarchical Bayesian (HB) method. This
package provides model using Univariate Normal distribution and
Univariate Beta distribution for variables of interest. This package
also provides a dataset produced by a data generation. The ‘rjags’
package is employed to obtain parameter estimates. Model-based
estimators involves the HB estimators which include the mean and the
variation of mean. For the reference, see Rao and Molina (2015).

## Functions

  - `Beta()` Produces HB estimators, standard error, random effect
    variance, coefficient and plot under beta distribution.
  - `Normal()` Produces HB estimators, standard error, random effect
    variance, coefficient and plot under Normal distribution.

## References

  - Rao, J.N.K & Molina. (2015). Small Area Estimation 2nd Edition. New
    York: John Wiley and Sons, Inc.
