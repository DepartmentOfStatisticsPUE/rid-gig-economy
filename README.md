# The gig economy in Poland -- evidence based on the mobile big data


## Basic info

Data and codes for the paper "The gig economy in Poland -- evidence based on the mobile big data" by:

+ Beręsewicz Maciej -- Poznań University of Economics and Business, Poland; Statistical Office in Poznań, Poland
+ Nikulin Dagmara -- Gdańsk University of Technology, Poland
+ Szymkowiak Marcin -- Poznań University of Economics and Business, Poland; Statistical Office in Poznań, Poland
+ Wilak Kamil -- Poznań University of Economics and Business, Poland; Statistical Office in Poznań, Poland

The structure of the repo is as follows:

+ `data/` -- folder with two datasets: `bael.xlsx` (LFS data) and `selectivv-data-list.rds` (R list)
+ `figures/` -- figures prepared for the paper
+ `paper-calculations.Rmd` -- R notebook with codes to reproduce plots and some tables
+ `paper.pdf` -- the main paper (preliminary and before proofread)

## How to cite

Beręsewicz, Nikulin, Szymkowiak and Wilak, (2021) The gig economy in Poland -- evidence based on the mobile big data, Working paper, URL: https://github.com/DepartmentOfStatisticsPUE/rid-gig-economy

## Acknowledgements

The study was conducted within the research project *Economics in the face of the New Economy* financed within the Regional Initiative for Excellence programme of the Minister of Science and Higher Education of Poland, years 2019-2022, grant no. 004/RID/2018/19, financing 3,000,000 PLN (for Maciej Beręsewicz, Marcin Szymkowiak and Kamil Wilak).

## Session info

```{r}
> sessionInfo()
R version 3.6.1 (2019-07-05)
Platform: x86_64-apple-darwin15.6.0 (64-bit)
Running under: macOS  10.16

Matrix products: default
LAPACK: /Library/Frameworks/R.framework/Versions/3.6/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods  
[7] base     

other attached packages:
 [1] haven_2.4.1      ggh4x_0.1.2.1.9  ggrepel_0.9.1   
 [4] lubridate_1.7.10 xtable_1.8-4     forcats_0.5.1   
 [7] stringr_1.4.0    dplyr_1.0.6      purrr_0.3.4     
[10] readr_1.4.0      tidyr_1.1.3      tibble_3.1.2    
[13] ggplot2_3.3.3    tidyverse_1.3.1  readxl_1.3.1    

loaded via a namespace (and not attached):
 [1] httr_1.4.2         sass_0.4.0         pkgload_1.2.1     
 [4] jsonlite_1.7.2     modelr_0.1.8       bslib_0.2.5.1     
 [7] assertthat_0.2.1   cellranger_1.1.0   yaml_2.2.1        
[10] remotes_2.3.0      sessioninfo_1.1.1  pillar_1.6.1      
[13] backports_1.2.1    glue_1.4.2         digest_0.6.27     
[16] RColorBrewer_1.1-2 rvest_1.0.0        colorspace_2.0-1  
[19] htmltools_0.5.1.1  pkgconfig_2.0.3    devtools_2.4.1    
[22] broom_0.7.6        scales_1.1.1       processx_3.5.2    
[25] farver_2.1.0       generics_0.1.0     usethis_2.0.1     
[28] ellipsis_0.3.2     cachem_1.0.5       withr_2.4.2       
[31] cli_2.5.0          magrittr_2.0.1     crayon_1.4.1      
[34] memoise_2.0.0      evaluate_0.14      ps_1.6.0          
[37] fs_1.5.0           fansi_0.4.2        xml2_1.3.2        
[40] pkgbuild_1.2.0     rsconnect_0.8.17   tools_3.6.1       
[43] prettyunits_1.1.1  hms_1.1.0          lifecycle_1.0.0   
[46] munsell_0.5.0      reprex_2.0.0       callr_3.7.0       
[49] packrat_0.6.0      jquerylib_0.1.4    compiler_3.6.1    
[52] rlang_0.4.11       grid_3.6.1         rstudioapi_0.13   
[55] labeling_0.4.2     rmarkdown_2.8      testthat_3.0.2    
[58] gtable_0.3.0       DBI_1.1.1          curl_4.3.1        
[61] R6_2.5.0           knitr_1.33         fastmap_1.1.0     
[64] utf8_1.2.1         rprojroot_2.0.2    desc_1.3.0        
[67] stringi_1.6.2      Rcpp_1.0.6         vctrs_0.3.8       
[70] dbplyr_2.1.1       tidyselect_1.1.1   xfun_0.23      
```