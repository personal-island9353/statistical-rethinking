# statistical-rethinking

Project used to follow along with the Statistical Rethinking book by Richard McElreath

# Setup

First, follow Stan installation instruction at https://github.com/rmcelreath/rethinking?tab=readme-ov-file#installation

Then install the `renv` package if you haven't already:

```r
install.packages("renv")
```

Then run the following R code to install the `rethinking` package, and the other dependencies:

```r
renv::activate()
renv::install(devtools)
library(devtools)
devtools::install_github("rmcelreath/rethinking")
```
