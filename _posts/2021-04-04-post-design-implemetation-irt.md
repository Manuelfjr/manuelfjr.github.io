---
title:  "Design and Implementation of IRT models for Clustering Evaluation"
search: false
categories: 
  - Works
tags:
  - Item response theory
  - Machine Learning
  - Clustering

toc: true
last_modified_at: 2021-04-04T08:06:00-16:00
---

The item response theory aims to estimate respondents' latent skills based on their responses in tests composed of items with different levels of difficulty. Several models of item response theory have been proposed for different types of problems, such as binary or probabilistic responses, response time, multiple responses, etc. More recently, item response theory has been explored in applications in the field of machine learning, in the contexts of classification and regression. For the grouping task, however, the item response theory has not yet been explored. In this case, the most used measures are the Rand index, which requires labeled data, and the silhouette measure, which is expensive to calculate and depends on the choice of a distance. Another characteristic of these measures is their poor applicability for diffuse and probabilistic groupings. Thus, this work will propose the use of item response theory to evaluate cluster models, eliminating the need for labeled data and choosing a distance, in addition to allowing the evaluation of diffuse and probabilistic models.

*keywords: Item response theory, Machine Learning, Clustering.*