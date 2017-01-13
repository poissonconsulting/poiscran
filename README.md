
<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Travis-CI Build Status](https://travis-ci.org/poissonconsulting/poiscran.svg?branch=master)](https://travis-ci.org/poissonconsulting/poiscran) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/poissonconsulting/poiscran?branch=master&svg=true)](https://ci.appveyor.com/project/poissonconsulting/poiscran)

poiscran
========

Attaches CRAN and GitHub Packages Used in Poison Consulting analyses.

Installation
------------

To install and load `poiscran` execute the following code at the R terminal:

    # install.packages("devtools")
    devtools::install_github("poissonconsulting/poiscran")
    library(poiscran)

Demonstration
-------------

``` r
search()
#> [1] ".GlobalEnv"        "package:stats"     "package:graphics" 
#> [4] "package:grDevices" "package:utils"     "package:datasets" 
#> [7] "package:methods"   "Autoloads"         "package:base"
library(poiscran)
#> Loading required package: abind
#> Loading required package: assertthat
#> Loading required package: beepr
#> Loading required package: datacheckr
#> Loading required package: devtools
#> Loading required package: ggplot2
#> Loading required package: ggrepel
#> Loading required package: knitr
#> Loading required package: markdown
#> Loading required package: plyr
#> Loading required package: readxl
#> Loading required package: reshape2
#> Loading required package: rmarkdown
#> Loading required package: scales
#> Loading required package: stringr
#> Loading required package: purrr
#> 
#> Attaching package: 'purrr'
#> The following object is masked from 'package:scales':
#> 
#>     discard
#> The following object is masked from 'package:plyr':
#> 
#>     compact
#> Loading required package: readr
#> 
#> Attaching package: 'readr'
#> The following objects are masked from 'package:scales':
#> 
#>     col_factor, col_numeric
#> Loading required package: lubridate
#> 
#> Attaching package: 'lubridate'
#> The following object is masked from 'package:plyr':
#> 
#>     here
#> The following object is masked from 'package:base':
#> 
#>     date
#> Loading required package: tidyr
#> 
#> Attaching package: 'tidyr'
#> The following object is masked from 'package:reshape2':
#> 
#>     smiths
#> Loading required package: magrittr
#> 
#> Attaching package: 'magrittr'
#> The following object is masked from 'package:tidyr':
#> 
#>     extract
#> The following object is masked from 'package:purrr':
#> 
#>     set_names
#> Loading required package: dplyr
#> 
#> Attaching package: 'dplyr'
#> The following objects are masked from 'package:lubridate':
#> 
#>     intersect, setdiff, union
#> The following objects are masked from 'package:purrr':
#> 
#>     contains, order_by
#> The following objects are masked from 'package:plyr':
#> 
#>     arrange, count, desc, failwith, id, mutate, rename, summarise,
#>     summarize
#> The following objects are masked from 'package:stats':
#> 
#>     filter, lag
#> The following objects are masked from 'package:base':
#> 
#>     intersect, setdiff, setequal, union
#> Loading required package: tmbr
#> Loading required package: mbr
#> Loading required package: broom
#> Loading required package: mcmcr
#> Loading required package: coda
#> 
#> Attaching package: 'mcmcr'
#> The following object is masked from 'package:ggplot2':
#> 
#>     derive
#> Loading required package: newdata
#> Loading required package: jmbr
search()
#>  [1] ".GlobalEnv"         "package:poiscran"   "package:jmbr"      
#>  [4] "package:tmbr"       "package:newdata"    "package:mbr"       
#>  [7] "package:mcmcr"      "package:coda"       "package:broom"     
#> [10] "package:dplyr"      "package:magrittr"   "package:tidyr"     
#> [13] "package:lubridate"  "package:readr"      "package:purrr"     
#> [16] "package:stringr"    "package:scales"     "package:rmarkdown" 
#> [19] "package:reshape2"   "package:readxl"     "package:plyr"      
#> [22] "package:markdown"   "package:knitr"      "package:ggrepel"   
#> [25] "package:ggplot2"    "package:devtools"   "package:datacheckr"
#> [28] "package:beepr"      "package:assertthat" "package:abind"     
#> [31] "package:stats"      "package:graphics"   "package:grDevices" 
#> [34] "package:utils"      "package:datasets"   "package:methods"   
#> [37] "Autoloads"          "package:base"
```
