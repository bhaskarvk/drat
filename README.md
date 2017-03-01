My 'drat' Repository
================

[![Project Status: Active – The repository is being actively maintained.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active) [![Last-changedate](https://img.shields.io/badge/last%20change-2017--03--01-green.svg)](/commits/master) [![keybase verified](https://img.shields.io/badge/keybase-verified-brightgreen.svg)](https://gist.github.com/bhaskarvk/46fbf2ba7b5713151d7e)

### What is This?

This is my [drat](https://github.com/eddelbuettel/drat) repository for hosting R packages too big for CRAN.

### Using the Repository

``` r
if(!require("drat")) {
  install.packages("drat")
  library("drat")
}
drat::addRepo("bhaskarvk")
```

For ease of use you should put `drat::addRepo("bhaskarvk")` in you `$HOME/.Rprofile` file. After that use `install.packages`, `update.packages` like you normally do.

### Package List

-   [usgazetteer](https://github.com/bhaskarvk/usgazetteer): US Census Bureau's gazetter data.

### Anything else?

Nope!
