--- 
title: "SCE Gallery"
date: "2020-08-26"
site: bookdown::bookdown_site
documentclass: book
bibliography: ref.bib
biblio-style: apalike
link-citations: yes
favicon: "favicon.ico"
cover-image: "https://www.bioconductor.org/images/logo_bioconductor.gif"
---

# Welcome {-}

<a href="https://bioconductor.org"><img src="https://github.com/Bioconductor/BiocStickers/raw/master/Bioconductor/Bioconductor-serial.gif" width="200" alt="Bioconductor Sticker" align="right" style="margin: 0 1em 0 1em" /></a> 

One of the most important parts of single-cell data analysis is visualization.
In fact, it could even be said that this is _the_ most important part of the analysis.
I mean, how else can we make Figure 1 of that _Nature_ paper without some sweet, sweet $t$-SNEs? (Or UMAPs.)

This book will showcase various methods for visualizing single-cell data from the standard `SingleCellExperiment` container.
Each chapter focuses on a particular aspect of data visualization, 
starting with a brief analysis to set up the `SingleCellExperiment` 
before applying plotting functions from different packages.
Readers can then pick and choose their poison in a bake-off between plotting philosophies.

I'll finish with a quote from Keats, for those of us unfortunate to have to study poetry in high school:

> "Beauty is truth, truth beauty,"--that is all Ye know on earth, and all ye need to know.

Pretty much sums up the field.
