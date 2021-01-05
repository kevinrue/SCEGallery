# The SingleCellExperiment Gallery

The `SingleCellExperiment` is Bioconductor's standard data structure for representing single-cell data.
It builds off the established `SummarizedExperiment` class for compatibility with a wide array of existing Bioconductor pipelines, but also adds a number of single-cell-specific fields to store common objects like dimensionality reduction results.
Over 70 Bioconductor packages rely on the `SingleCellExperiment` format as a "common currency" for interoperable data analysis.

Okay, enough of that boring introduction.
As we all know, single-cell data analysis is _all about_ making pretty plots.
This book aims to survey the options for visualizing data extracted from `SingleCellExperiment` objects using Bioconductor packages, providing functional demonstrations on real single-cell data.
Don't like one visualization? That's okay, just use another option - and here's the code to do it.

The repository holds contents for a [**bookdown**](https://bookdown.org/yihui/bookdown/) book.
Each chapter describes a different aspect of data visualization, e.g., using the `reducedDims()` or the feature assay values.
Each section of the chapter corresponds to the functionality offered by a single Bioconductor package; all functions will usually operate on the same `SingleCellExperiment` object for a like-for-like comparison.

Think you can do better? 
Make a PR on this repository in the relevant chapter (or make your own, if you see a visualization mode that is not covered here).
The only requirements are:

- The relevant packages should be in Bioconductor.
- The functions should accept a `SingleCellExperiment`.

Come and have a go if you think you're hard enough!
