---
title: "CLAIRE: clustering evaluation based on item response theory and model agreement"
search: true
categories:
  - Works
tags:
  - Clustering
  - Item Response Theory
  - Evaluation
  - Machine Learning
  - Research
toc: true
excerpt: "CLAIRE is a clustering-evaluation method proposed by Ferreira-Junior and collaborators for comparing models through agreement-based item responses."
last_modified_at: 2025-10-01T00:00:00-03:00
---

[CLAIRE](https://doi.org/10.1007/s10994-025-06911-0) is a method I proposed with collaborators for **global evaluation of clustering models** through pairwise agreement and Item Response Theory. The paper was published in *Machine Learning* (Springer Nature).

## Citation

Ferreira-Junior, M., Lima Neto, E.A., Ferreira, M.R.P., Silva Filho, T.M., Prudencio, R.B.C. **CLAIRE: clustering evaluation based on item response theory and model agreement.** *Machine Learning* 114, 256 (2025). DOI: `10.1007/s10994-025-06911-0`

## Abstract

Clustering evaluation is difficult because external metrics such as Rand Index depend on ground truth, while internal measures such as silhouette, Dunn, and Davies-Bouldin are tied to distance choices and do not compare differently estimated models very well. CLAIRE addresses this by assuming that strong clustering models tend to agree about whether pairs of instances should stay together or apart. From these agreement patterns, the method builds response matrices and applies Item Response Theory to estimate both model ability and instance difficulty. Across diverse datasets, cluster structures, overlap levels, and noisy settings, the paper reports that CLAIRE remains robust even when random partitions are included in the model pool, while still correlating strongly with external clustering-quality measures.

## Why It Matters

- It avoids dependence on labels in truly unsupervised scenarios.
- It compares clustering models through agreement rather than through a single internal distance-based score.
- It connects clustering evaluation to latent-variable modeling, which gives a richer interpretation of model ability and data difficulty.

## Links

- DOI: [10.1007/s10994-025-06911-0](https://doi.org/10.1007/s10994-025-06911-0)
- Journal page: [Machine Learning at Springer Nature](https://link.springer.com/article/10.1007/s10994-025-06911-0)
