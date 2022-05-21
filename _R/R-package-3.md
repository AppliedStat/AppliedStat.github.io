---
title: "rQCC"
excerpt: "Robust Quality Control Chart"
collection: R
---
This \"rQCC\" package constructs robust quality control chart based on the median or Hodges-Lehmann estimator (location) and the median absolute deviation (MAD) or Shamos estimator (scale). 
These estimators are all unbiased with a sample of finite size. 
For more details, see  [Park, Kim, and Wang (2022)](https://doi.org/10.1080/03610918.2019.1699114).

In addition, the \"rQCC\" package also provides various conventional attribute control charts such as 
 _p_, _np_, _c_, _u_, _g_, and _h_ charts. 
For more details on _g_ and _h_ charts, 
see [Park and Wang (2022)](https://doi.org/10.1080/03610926.2022.2044492).

This work was partially supported by the National Research Foundation of Korea (NRF) grant funded by the Korea government (NRF-2017R1A2B4004169).

### Links
[![cran](https://cranlogs.r-pkg.org/badges/grand-total/rQCC)](https://cran.r-project.org/web/packages/rQCC/) 
[![rdrr](https://img.shields.io/badge/%20-rdrr.io-yellowgreen.svg)](https://rdrr.io/cran/rQCC/)
[![github](https://img.shields.io/badge/%20-github-lightgrey.svg)](https://github.com/appliedstat/R/tree/master/rQCC)

### Usage
> install.packages(\"rQCC\")  

> news(package=\"rQCC\")      

> vignette(\"rcc\", package=\"rQCC\")  <br/>
> vignette(\"factors.cc\", package=\"rQCC\")  

> library(\"rQCC\")  <br/>
> help(package=\"rQCC\") 
