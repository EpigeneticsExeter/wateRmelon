# wateRmelon
 Illumina 450 and EPIC methylation array normalization and metrics

## Software status

| Resource:     | Bioconductor  (Release)      | Bioconductor (Devel)    |
| ------------- | ------------------- | ------------- |
| _Platforms:_  | _Multiple_          | _Multiple_    |
| R CMD check   | <a href="http://bioconductor.org/checkResults/release/bioc-LATEST/wateRmelon/"><img border="0" src="http://bioconductor.org/shields/build/release/bioc/wateRmelon.svg" alt="Build status"></a></br>|<a href="http://bioconductor.org/checkResults/devel/bioc-LATEST/wateRmelon/"><img border="0" src="http://bioconductor.org/shields/build/devel/bioc/wateRmelon.svg" alt="Build status"></a>

## Installation
We are currently updating `wateRmelon` and our wider ecosystem of software including `bigmelon`. We will try to keep the github repo inline with the bioconductor mirror as much as possible. However if you want the latest features before they are committed to bioconductor you can install both `wateRmelon` using the code below. 



```
library(devtools)
devtools::install_git('https://github.com/EpigeneticsExeter/wateRmelon')
```

## Citation
If you use `watermelon` for your analyses, please use citation() within R or cite [the original manuscript describing the methods](https://doi.org/10.1186/1471-2164-14-293) as:

Pidsley R, Y Wong CC, Volta M, Lunnon K, Mill J, Schalkwyk LC. A data-driven approach to preprocessing Illumina 450K methylation array data. BMC Genomics. 2013;14:293. Published 2013 May 1. doi:10.1186/1471-2164-14-293