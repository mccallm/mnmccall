---
title: Sami Leon added as author of the biclust R package.
date: 2021-06-14
authors:
- sami_leon
---

In recognition of his contributions to the package, Sami Leon was added as an author of the [biclust](https://cran.r-project.org/web/packages/biclust/index.html) R package, which provides several algorithms to find biclusters in two-dimensional data.

<!--more-->

Sami's contribution to the biclust package was to add a projection step after the clustering of the eigenvectors. The data is projected to a small number of eigenvectors, and a final clustering step is performed using k-means. We also added the option of specifying the number of clusters, which allows to incorporate prior knowledge if available.