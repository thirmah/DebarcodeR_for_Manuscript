# DebarcodeR_for_Manuscript


# Session Info:
R version 4.2.1 (2022-06-23 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 22621)

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.utf8 
[2] LC_CTYPE=English_United States.utf8   
[3] LC_MONETARY=English_United States.utf8
[4] LC_NUMERIC=C                          
[5] LC_TIME=English_United States.utf8    

attached base packages:
[1] stats     graphics  grDevices utils     datasets 
[6] methods   base     

other attached packages:
 [1] details_0.3.0            mixsmsn_1.1-10          
 [3] mvtnorm_1.1-3            rstatix_0.7.2           
 [5] ggpubr_0.6.0             analyze.stuff_2.1.0     
 [7] readxl_1.4.2             facetscales_0.1.0.9000  
 [9] RColorBrewer_1.1-3       lubridate_1.9.2         
[11] forcats_1.0.0            stringr_1.5.0           
[13] purrr_1.0.1              readr_2.1.4             
[15] tidyr_1.3.0              tibble_3.1.8            
[17] tidyverse_2.0.0          CytobankAPI_2.2.1       
[19] httr_1.4.5               curl_5.0.0              
[21] ggpointdensity_0.1.0     DebarcodeR_1.0.0        
[23] cytotidyr_0.0.1.100      ggcyto_1.24.1           
[25] ncdfFlow_2.42.1          BH_1.81.0-1             
[27] RcppArmadillo_0.12.2.0.0 ggplot2_3.4.2           
[29] dplyr_1.0.10             flowWorkspace_4.8.0     
[31] CytoML_2.8.1             flowCore_2.8.0          

loaded via a namespace (and not attached):
  [1] clipr_0.8.0           utf8_1.2.2           
  [3] tidyselect_1.2.0      htmlwidgets_1.6.2    
  [5] grid_4.2.1            devtools_2.4.5       
  [7] aws.signature_0.6.0   munsell_0.5.0        
  [9] codetools_0.2-18      interp_1.1-3         
 [11] miniUI_0.1.1.1        withr_2.5.0          
 [13] colorspace_2.0-3      Biobase_2.56.0       
 [15] knitr_1.42            rstudioapi_0.14      
 [17] stats4_4.2.1          ggsignif_0.6.4       
 [19] labeling_0.4.2        TeachingDemos_2.12   
 [21] mnormt_2.1.1          polyclip_1.10-4      
 [23] farver_2.1.1          rprojroot_2.0.3      
 [25] vctrs_0.6.2.9000      generics_0.1.3       
 [27] xfun_0.35             timechange_0.2.0     
 [29] R6_2.5.1              doParallel_1.0.17    
 [31] clue_0.3-64           bitops_1.0-7         
 [33] cachem_1.0.6          promises_1.2.0.1     
 [35] scales_1.2.1          gtable_0.3.3         
 [37] processx_3.8.1        RProtoBufLib_2.8.0   
 [39] rlang_1.1.1.9000      GlobalOptions_0.1.2  
 [41] hexbin_1.28.3         earth_5.3.2          
 [43] broom_1.0.4           BiocManager_1.30.20  
 [45] yaml_2.3.7            abind_1.4-5          
 [47] jose_1.2.0            backports_1.4.1      
 [49] httpuv_1.6.9          RBGL_1.72.0          
 [51] usethis_2.1.6         tools_4.2.1          
 [53] ellipsis_0.3.2        gplots_3.1.3         
 [55] proxy_0.4-27          BiocGenerics_0.42.0  
 [57] sessioninfo_1.2.2     Rcpp_1.0.9           
 [59] plyr_1.8.8            base64enc_0.1-3      
 [61] zlibbioc_1.42.0       classInt_0.4-9       
 [63] prettyunits_1.1.1     ps_1.7.5             
 [65] openssl_2.0.6         deldir_1.0-6         
 [67] GetoptLong_1.0.5      viridis_0.6.2        
 [69] urlchecker_1.0.1      S4Vectors_0.34.0     
 [71] cluster_2.1.3         fs_1.6.2             
 [73] magrittr_2.0.3        data.table_1.14.6    
 [75] circlize_0.4.15       ggnewscale_0.4.8     
 [77] matrixStats_0.63.0    pkgload_1.3.2        
 [79] hms_1.1.3             mime_0.12            
 [81] evaluate_0.20         xtable_1.8-4         
 [83] XML_3.99-0.13         jpeg_0.1-10          
 [85] mclust_6.0.0          IRanges_2.30.1       
 [87] gridExtra_2.3         shape_1.4.6          
 [89] compiler_4.2.1        KernSmooth_2.23-20   
 [91] crayon_1.5.2          htmltools_0.5.4.9000 
 [93] later_1.3.0           tzdb_0.3.0           
 [95] Formula_1.2-5         CytoTools_0.1        
 [97] RcppParallel_5.1.5    aws.s3_0.3.21        
 [99] DBI_1.1.3             tweenr_2.0.2         
[101] ComplexHeatmap_2.12.1 MASS_7.3-59          
[103] car_3.1-2             cli_3.4.1            
[105] parallel_4.2.1        pkgconfig_2.0.3      
[107] cytoMEM_1.0.0         sn_2.1.1             
[109] numDeriv_2016.8-1.1   xml2_1.3.3           
[111] foreach_1.5.2         plotmo_3.6.2         
[113] snakecase_0.11.0      callr_3.7.3          
[115] digest_0.6.31         janitor_2.2.0        
[117] graph_1.74.0          rmarkdown_2.21       
[119] cellranger_1.1.0      shiny_1.7.4          
[121] gtools_3.9.4          rjson_0.2.21         
[123] lifecycle_1.0.3       jsonlite_1.8.4       
[125] carData_3.0-5         desc_1.4.2           
[127] viridisLite_0.4.1     askpass_1.1          
[129] fansi_1.0.3           pillar_1.9.0         
[131] lattice_0.20-45       fastmap_1.1.0        
[133] plotrix_3.8-2         pkgbuild_1.4.0       
[135] glue_1.6.2            remotes_2.4.2        
[137] png_0.1-8             iterators_1.0.14     
[139] Rgraphviz_2.40.0      profvis_0.3.7        
[141] ggforce_0.4.1         class_7.3-20         
[143] stringi_1.7.12        latticeExtra_0.6-30  
[145] caTools_1.18.2        memoise_2.0.1        
[147] cytolib_2.8.0         e1071_1.7-13         
