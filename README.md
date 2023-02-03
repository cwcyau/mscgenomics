# Machine Learning for Oxford MSc Genomics

This is a repository for materials related to the Oxford MSc in Genomics session on *Machine Learning for Single-Cell Transcriptomics*.

The session will consist of the following topics:

1. Dimensionality Reduction (45 mins)

2. Computer Practical - Single cell data visualisation (60 mins)

3. Unsupervised Learning (45 mins)


## Preparation

The computer practical will be using R. 

In advance of the session, students would be advised to pre-install [R](https://www.r-project.org/), [Rstudio/Posit](https://posit.co/) and the following R libraries:

```
# CRAN libraries, use install.packages(...)
library(ggplot2)
library(cowplot)
library(Rtsne)
library(reshape2)
library(umap)
library(igraph)
library(ggheatmap)
library(RColorBrewer)

# Available via Github
devtools::install_github("sctyner/geomnet")
library(geomnet)
```
