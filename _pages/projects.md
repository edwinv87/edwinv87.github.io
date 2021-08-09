---
title: Packages
permalink: /packages/
---

## FEATS

FEATS is a new Python tool for performing clustering on single-cell RNA-sequencing data. FEATS can also estimate the number of clusters, perform outlier detection and batch correction and integration of data from multiple experiments. See [feats](/feats/)

## SingleCell

SingleCell is a Python class available in the singlecelldata package for managing single-cell RNA-seq data. It contains three pandas dataframes; `data` for holding gene expression values (counts/normalized counts), `genedata` for holding more information about the genes e.g., gene names, and `celldata` which contains more information about cells such as cell types, labels etc. See [SingleCellData](/singlecelldata/)

## scplotlib

scplotlib is a python plotting library for the [SingleCell](/singlecelldata/) object. It is built using [Altair](https://altair-viz.github.io/). It can generate various plots for data stored in a SingleCell object such as:

1. Core plots - line plots, bar plots, scatter plots

2. Visualizing high dimensional data - t-SNE plots, PCA plots

3. Specialized plots - heatmaps, silhouette plots, outlier score plots

See [scplotlib](/scplotlib/)
