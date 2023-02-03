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

## Lecture Notes

to be uploaded

## Practical 

to be uploaded

## Resources

Due to limited time during the taught sessions it will not be possible to go into the depths of the algorithms and analysis methods presented. However, these example, free online resources cover the details to support your further learning:

[Dimensionality Reduction - Lecture 11 - Deep Learning in Life Sciences ](https://www.youtube.com/watch?v=0byf2OF6AT0&ab_channel=ManolisKellis)

[tSNE vs. UMAP: Global Structure](https://towardsdatascience.com/tsne-vs-umap-global-structure-4d8045acba17)

[Understanding UMAP](https://pair-code.github.io/understanding-umap/)

[UMAP Dimension Reduction, Main Ideas!!!](https://www.youtube.com/watch?v=eN0wFzBA4Sc&ab_channel=StatQuestwithJoshStarmer)

[Deep Generative Networks for single-cell transcriptomics](https://www.youtube.com/watch?v=BMogp-ufJwY&ab_channel=SIB-SwissInstituteofBioinformatics)

## References

You may find these references useful for your reports:

[The art of using t-SNE for single-cell transcriptomics](https://www.nature.com/articles/s41467-019-13056-x) 

[Dimensionality reduction for visualizing single-cell data using UMAP](https://www.nature.com/articles/nbt.4314)

[Deep generative modeling for single-cell transcriptomics](https://www.nature.com/articles/s41592-018-0229-2)

[Integrated analysis of multimodal single-cell data](https://www.cell.com/cell/fulltext/S0092-8674(21)00583-3?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867421005833%3Fshowall%3Dtrue)

[Machine learning for single-cell genomics data analysis](https://www.sciencedirect.com/science/article/abs/pii/S2452310021000172)

[Deep learning shapes single-cell data analysis](https://www.nature.com/articles/s41580-022-00466-x)

[Challenges in unsupervised clustering of single-cell RNA-seq data](https://www.nature.com/articles/s41576-018-0088-9)

