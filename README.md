# diffHic Tutorial for BioCAsia2018
Here is all the material for the Bioconductor Hands-on Training Day workshop "Differential analysis of HiC data with diffHic". A bioconductor package created by [Aaron Lun](https://support.bioconductor.org/u/6732/) and [Gordon Smyth](https://support.bioconductor.org/u/179/) to find differential chromatin structure in HiC data. 

Additional resources for the workshop:
* [diffHic](https://bioconductor.org/packages/release/bioc/html/diffHic.html) - DiffHic bioconductor page
* [diffHic paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-015-0683-0) - The diffHic paper
* [workshop data](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE99151) - Raw data for the paper available from here
* [EdgeR](https://bioconductor.org/packages/release/bioc/html/edgeR.html) - EdgeR bioconductor page

Requires R and bioconductor. Packages in R required:
```
library(diffhic)
library(edgeR)
library(csaw)
library(BSgenome.Mmusculus.UCSC.mm10)
```

Files for the tutorial are availabe from:
* [Count data](http://bioinf.wehi.edu.au/edgeR/diffHic_tutorial.RData) - InteractionSet objects
* [CD4T+ T cells](http://bioinf.wehi.edu.au/edgeR/CD4T1chr2_chr11_chr12.h5) - HDF5 for select chromosomes
* [Grans cells](http://bioinf.wehi.edu.au/edgeR/GW1chr2_chr11_chr12.h5) - HDF5 for select chromosomes
* [Mature B cells](http://bioinf.wehi.edu.au/edgeR/MATB1chr2_chr11_chr12.h5) - HDF5 for select chromosomes
