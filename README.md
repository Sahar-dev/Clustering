# Clustering Analysis Documentation

## Overview

This documentation delineates the R code implemented for sophisticated clustering analysis. The code employs K-Means clustering and Hierarchical Agglomerative Clustering (CAH) to scrutinize a dataset comprehensively. The analysis encompasses descriptive statistics, visualizations, and a meticulous exploration of optimal cluster configurations.

## Instructions

### 1. Loading the Data

The dataset is ingested from the "data.csv" file utilizing the `read.csv2` function. This foundational step sets the stage for subsequent intricate clustering analysis.

### 2. Descriptive Statistics

Descriptive statistics are systematically computed for each variable in the dataset, offering a nuanced understanding of the data's characteristics. This preliminary exploration informs the subsequent analytical processes.

### 3. K-Means Clustering

K-Means clustering is orchestrated with a meticulous approach, utilizing the `kmeans` function to segment the dataset into three clusters. The ensuing clusters are vividly portrayed through an insightful scatter plot, meticulously crafted using the `fviz_cluster` function.

### 4. Hierarchical Clustering (CAH)

Hierarchical Agglomerative Clustering (CAH) is meticulously applied to the dataset, orchestrating a three-cluster configuration. The visually rich dendrogram produced with `fviz_dend` serves as an illuminating representation of the hierarchical clustering results.

### 5. Inertia Analysis and Elbow Method

A judicious inertia analysis is undertaken to ascertain the optimal number of clusters. The code systematically iterates through a spectrum of cluster numbers, calculating nuanced inertias and producing a visually compelling plot. The elbow method is judiciously applied to discern the pivotal point indicating the optimal cluster count.

### 6. Visualizing Inertia Analysis

The outcomes of the inertia analysis are elegantly visualized through a line plot. Within-cluster, between-cluster, and total inertia are meticulously depicted for each cluster configuration, providing stakeholders with a profound understanding of the clustering dynamics.

### 7. R-Squared Evolution in K-Means Clustering

An intricate exploration of R-squared values is orchestrated, offering a granular perspective on clustering efficacy across various cluster configurations. The visually insightful plot enriches the analysis, aiding in the interpretation of clustering quality.

### 8. Analysis of Variables in Clusters

A sophisticated analysis of variables within clusters is meticulously executed. The code computes the squared correlation ratio (η²) for each variable, substantiating the findings through hypothesis testing.

## Conclusion

This comprehensive clustering analysis aims to unravel intricate patterns and structures embedded within the dataset. The discerning insights garnered facilitate a profound comprehension of the underlying data dynamics.
