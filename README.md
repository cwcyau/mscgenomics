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

## Resources

[tSNE vs. UMAP: Global Structure](https://towardsdatascience.com/tsne-vs-umap-global-structure-4d8045acba17)

[Understanding UMAP](https://pair-code.github.io/understanding-umap/)

[UMAP Dimension Reduction, Main Ideas!!!](https://www.youtube.com/watch?v=eN0wFzBA4Sc&ab_channel=StatQuestwithJoshStarmer)

## References

[The art of using t-SNE for single-cell transcriptomics](https://www.nature.com/articles/s41467-019-13056-x) 

[Dimensionality reduction for visualizing single-cell data using UMAP](https://www.nature.com/articles/nbt.4314)

[Deep generative modeling for single-cell transcriptomics](https://www.nature.com/articles/s41592-018-0229-2)


