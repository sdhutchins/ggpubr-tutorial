# ggpubr-tutorial

The goal of ggpubr-tutorial is to introduce [ggpubr](https://rpkgs.datanovia.com/ggpubr/) to graduate students who want to learn how to make publication ready figures.

In this tutorial, I create a ma plot and a box plot using `ggpubr`. The tutorial can be viewed at https://www.shauritahutchins.com/ggpubr-tutorial/. 

Also, the powerpoint slides are available on [Canva](https://www.canva.com/design/DAFTYzLnxME/CvlEpd0wZOqoYSTnXKeOkw/view?utm_content=DAFTYzLnxME&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink).

## Getting Started

### Installing R, RStudio, and the R packages

In order to rerun this code, the below should be installed:

- R v 4.1.1
- R studio
- `ggpubr`
- `tidyverse`

Install the R packages with:

```r
install.packages(c('ggpubr', 'tidyverse'))
```

### Downloading this repository

If you're familiar with git, you can clone this repository using `git clone https://github.com/sdhutchins/ggpubr-tutorial.git`.

However, if you are not comfortable with git, please download the zip archive of this tutorial at https://github.com/sdhutchins/ggpubr-tutorial/archive/refs/heads/main.zip.

## Session Info

```console
R version 4.1.1 (2021-08-10)
Platform: x86_64-apple-darwin17.0 (64-bit)
Running under: macOS 13.0.1

Matrix products: default
LAPACK: /Library/Frameworks/R.framework/Versions/4.1/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] forcats_0.5.2   stringr_1.4.1   dplyr_1.0.10    purrr_0.3.5     readr_2.1.3    
 [6] tidyr_1.2.0     tibble_3.1.8    tidyverse_1.3.2 ggpubr_0.4.0    ggplot2_3.3.6  

loaded via a namespace (and not attached):
 [1] tidyselect_1.1.2    xfun_0.34           haven_2.5.1         gargle_1.2.1       
 [5] carData_3.0-5       colorspace_2.0-3    vctrs_0.4.1         generics_0.1.3     
 [9] htmltools_0.5.3     yaml_2.3.6          utf8_1.2.2          rlang_1.0.6        
[13] pillar_1.8.1        glue_1.6.2          withr_2.5.0         DBI_1.1.3          
[17] dbplyr_2.2.1        readxl_1.4.1        modelr_0.1.9        lifecycle_1.0.3    
[21] munsell_0.5.0       ggsignif_0.6.4      gtable_0.3.1        cellranger_1.1.0   
[25] rvest_1.0.3         evaluate_0.17       knitr_1.40          tzdb_0.3.0         
[29] fastmap_1.1.0       fansi_1.0.3         broom_1.0.1         scales_1.2.1       
[33] backports_1.4.1     googlesheets4_1.0.1 jsonlite_1.8.3      abind_1.4-5        
[37] fs_1.5.2            hms_1.1.2           digest_0.6.30       stringi_1.7.8      
[41] rstatix_0.7.0       grid_4.1.1          cli_3.4.1           tools_4.1.1        
[45] magrittr_2.0.3      crayon_1.5.2        car_3.1-0           pkgconfig_2.0.3    
[49] ellipsis_0.3.2      xml2_1.3.3          reprex_2.0.2        lubridate_1.8.0    
[53] googledrive_2.0.0   httr_1.4.4          assertthat_0.2.1    rmarkdown_2.17     
[57] rstudioapi_0.14     R6_2.5.1            compiler_4.1.1     
```