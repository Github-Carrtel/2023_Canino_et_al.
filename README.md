
<!-- README.md is generated from README.Rmd. Please edit that file -->

# 2023_Canino_MBMG

## Overview

In this repository, you will find two tutorials explaining how we processed metabarcoding data (rRNA 16S and 23S) to report on the genetic diversity of phytoplankton in two mock communities used in a study aiming to test the performance of different barcodes and primers to assess freshwater phytoplantkon diversity.

Data analysis was done using R version 4.2.1. This document was compiled with the rmarkdown package version 2.8. This tutorial is licensed under CC BY-NC-ND 4.0, which means you are free to share, copy and redistribute this tutorial in any medium or format under the terms of attribution of appropriate credit, non-commercial purposes and no derivatives.

The data were produced as part of the article:

>Canino A., A. Bouchez, B. Alric, C. Lemonnier, I. Domaizon, C. Laplace-Treyture, F. Rimet. Deciphering the preformance of different barcodes and primers to assess freshwater phtyoplankton diversity, submitted to the journal Metabarcoding & Metagenomics.

## Utilization

We can access the script for 16S rRNA analyzes [here](https://raw.githack.com/Github-Carrtel/2023_Canino_MBMG/Mock_taxonomy_analysis_16S/Mock_taxonomy_analysis_16S.html)
We can access the script for 23S rRNA analyzes [here](https://raw.githack.com/Github-Carrtel/2023_Canino_MBMG/Mock_taxonomy_analysis_23S/Mock_taxonomy_analysis_23S.html)

## Version of packages used to create the web application
```r
sessionInfo()

R version 4.2.1 (2022-06-23 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19044)

Matrix products: default

locale:
[1] LC_COLLATE=French_France.utf8  LC_CTYPE=French_France.utf8    LC_MONETARY=French_France.utf8 LC_NUMERIC=C                  
[5] LC_TIME=French_France.utf8    

attached base packages:
[1] stats4    stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] DESeq2_1.38.3               SummarizedExperiment_1.28.0 Biobase_2.58.0              MatrixGenerics_1.10.0       matrixStats_0.63.0         
 [6] GenomicRanges_1.50.1        GenomeInfoDb_1.34.3         IRanges_2.32.0              S4Vectors_0.36.0            BiocGenerics_0.44.0        
[11] stringr_1.4.1               data.table_1.14.6           dada2_1.26.0                Rcpp_1.0.9                  dplyr_1.0.10               
[16] ggplot2_3.4.0              

loaded via a namespace (and not attached):
 [1] httr_1.4.4               bit64_4.0.5              RcppParallel_5.1.5       latticeExtra_0.6-30      blob_1.2.3              
 [6] GenomeInfoDbData_1.2.9   Rsamtools_2.14.0         yaml_2.3.6               RSQLite_2.3.0            pillar_1.8.1            
[11] lattice_0.20-45          glue_1.6.2               digest_0.6.30            RColorBrewer_1.1-3       XVector_0.38.0          
[16] colorspace_2.0-3         htmltools_0.5.3          Matrix_1.5-3             plyr_1.8.8               XML_3.99-0.12           
[21] pkgconfig_2.0.3          ShortRead_1.56.1         zlibbioc_1.44.0          xtable_1.8-4             scales_1.2.1            
[26] jpeg_0.1-10              BiocParallel_1.32.3      tibble_3.1.8             annotate_1.76.0          KEGGREST_1.38.0         
[31] generics_0.1.3           cachem_1.0.6             withr_2.5.0              cli_3.4.1                magrittr_2.0.3          
[36] crayon_1.5.2             deldir_1.0-6             memoise_2.0.1            evaluate_0.18            fansi_1.0.3             
[41] hwriter_1.3.2.1          tools_4.2.1              lifecycle_1.0.3          interp_1.1-3             locfit_1.5-9.7          
[46] munsell_0.5.0            DelayedArray_0.24.0      AnnotationDbi_1.60.0     Biostrings_2.66.0        compiler_4.2.1          
[51] rlang_1.0.6              grid_4.2.1               RCurl_1.98-1.9           rstudioapi_0.14          bitops_1.0-7            
[56] rmarkdown_2.18           gtable_0.3.1             codetools_0.2-18         DBI_1.1.3                reshape2_1.4.4          
[61] R6_2.5.1                 GenomicAlignments_1.34.0 knitr_1.41               bit_4.0.5                fastmap_1.1.0           
[66] utf8_1.2.2               stringi_1.7.8            parallel_4.2.1           vctrs_0.5.1              geneplotter_1.76.0      
[71] png_0.1-8                tidyselect_1.2.0         xfun_0.35
```
