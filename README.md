# chromunity

![chromunity](inst/extdata/chromunity_logo.jpg)

### <font color=black> Discovery of communities in Pore-C concatemers.</font>

## <font color=black> Installations </font>

Install devtools from CRAN


```R
install.packages('devtools')
```

Install dependent packages and latest Bioconductor (if you haven't already)


```R
source('https://bioconductor.org/biocLite.R')
biocLite('GenomicRanges')
```

Install mskilab R dependencies (gUtils)


```R
devtools::install_github(c('mskilab/gUtils','mskilab/gTrack','mskilab/bamUtils','mskilab/gChain','mskilab/skitools'))
```

Install chromunity


```R
devtools::install_github('mskilab/chromunity')
```
Documentation 
------------

[chromunity Tutorial](http://mskilab.com/chromunity/tutorial.html)
