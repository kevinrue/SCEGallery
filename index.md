--- 
title: "The SingleCellExperiment Gallery"
date: "2020-09-14"
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
How else can we make Figure 1 of our _Nature_ papers without some sweet, sweet $t$-SNEs? (Or UMAPs.)
We need something to compete with the aesthetic appeal of a "representative" microscope image, after all.

This book will showcase various methods for visualizing single-cell data from a `SingleCellExperiment` object.
Each chapter focuses on a particular aspect of data visualization, 
starting with a brief analysis to set up the `SingleCellExperiment` before applying a range of plotting functions.
Readers can then pick and choose their poison in a bake-off between visualization philosophies.

All of the visualization packages presented here are available from the [Bioconductor project](https://bioconductor.org).
The major players are *[scater](https://bioconductor.org/packages/3.12/scater)*, a trusty old workhorse for working with `SingleCellExperiment` objects;
*[dittoSeq](https://bioconductor.org/packages/3.12/dittoSeq)*, a more recent package focusing on colorblind-friendly visualizations;
and *[scDataviz](https://bioconductor.org/packages/3.12/scDataviz)*, yet another upstart offering plotting capabilities.
If you're a Bioconductor package developer and you think you can do better, bring it. (With a PR.)

I'll finish with a quote from Keats, for those of us unfortunate enough to have study poetry in high school:

> "Beauty is truth, truth beauty,"--that is all Ye know on earth, and all ye need to know.

Pretty much sums up the field.
