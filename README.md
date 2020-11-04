# ncappc

Installation

You need to have R installed.  Download the latest version of R from www.r-project.org. Install ncappc in R using one of the following methods:

* latest stable release -- From CRAN.  Write at the R command line:

```r
install.packages("ncappc")
```

* Latest development version -- from Github. Note that the command below installs the "master" (development) branch; if you want the release branch from Github add `ref="release"` to the `install_github()` call. The `install_github()` approach requires that you build from source, i.e. `make` and compilers must be installed on your system -- see the R FAQ for your operating system; you may also need to install dependencies manually.

```r
devtools::install_github("cacha0227/ncappc",build_vignettes=TRUE)
```

