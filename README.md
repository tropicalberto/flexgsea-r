Flexible Gene Set Enrichment Analysis
=====================================

[![DOI](https://zenodo.org/badge/86062898.svg)](https://zenodo.org/badge/latestdoi/86062898)

flexgsea is a R package to do gene set enrichment analysis [1]. Main advantages:

 - Allows user defined functions.
   So you can use you favorite package for differential expression.
 - Calculates significance by sample permutation.
 - Parallelization using the foreach package.
 - Can calculate normalized enrichment scores (NES) and significance based on that.
 - Implements the weighted KS-like statistic.

The package is not yet on CRAN.
You can install from Github:

``` r
# install.packages("devtools")
devtools::install_github("NKI-CCB/flexgsea-r")
```

Main documentation is on the `flexgsea` function in the package:

``` r
help('flexgsea', 'flexgsea')
```

This package was called ggsea before.

Development branch 
=====================================
This branch is intended to extend the package to allow permutations on paired analysis 

References
----------

[1] Subramanian, Aravind, Pablo Tamayo, Vamsi K. Mootha, Sayan Mukherjee, Benjamin L. Ebert, Michael A. Gillette, Amanda Paulovich, et al. 2005. "Gene Set Enrichment Analysis: A Knowledge-Based Approach for Interpreting Genome-Wide Expression Profiles." Proceedings of the National Academy of Sciences of the United States of America 102 (43): 15545–50. [doi:10.1073/pnas.0506580102](https://dx.doi.org/10.1073/pnas.0506580102).
