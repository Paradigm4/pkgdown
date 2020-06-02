# pkgdown
Forked [R pkgdown library](https://github.com/r-lib/pkgdown)

**Reason of forking**:
The original `pkgdown` package doesn't allow paged data frame rendering.

## Installation

``` r
# Install development version from GitHub
devtools::install_github("Pardigm4/pkgdown")
```

## Usage

Get started with [usethis](http://usethis.r-lib.org/):

``` r
# Run once to configure your package to use pkgdown
usethis::use_pkgdown()
```

Use pkgdown to update your website:

``` r
# Run to build the website
pkgdown::build_site()
```

This generates a `docs/` directory containing a website. Your
`README.md` becomes the homepage, documentation in `man/` generates a
function reference, and vignettes will be rendered into `articles/`.
Read `vignette("pkgdown")` for more details and to learn how to
customise your site.

