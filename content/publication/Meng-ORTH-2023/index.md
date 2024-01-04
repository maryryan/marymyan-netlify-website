---
abstract: Background and objectives - Marginal models with generalized estimating equations (GEE) are usually recommended for analyzing correlated ordinal outcomes which are commonly seen in a longitudinal study or clustered randomized trial (CRT). Within-cluster association is often of interest in longitudinal studies or CRTs, and can be estimated with paired estimating equations. However, the estimators for within-cluster association parameters and variances may be subject to finite-sample biases when the number of clusters is small. The objective of this article is to introduce a newly developed R package ORTH.Ord for analyzing correlated ordinal outcomes using GEE models with finite-sample bias corrections. Methods - The R package ORTH.Ord implements a modified version of alternating logistic regressions with estimation based on orthogonalized residuals (ORTH), which use paired estimating equations to jointly estimate parameters in marginal mean and association models. The within-cluster association between ordinal responses is modeled by global pairwise odds ratios (POR). The R package also provides a finite-sample bias correction to POR parameter estimates based on matrix multiplicative adjusted orthogonalized residuals (MMORTH) for correcting estimating equations, and bias-corrected sandwich estimators with different options for covariance estimation. Results - A simulation study shows that MMORTH provides less biased global POR estimates and coverage of their 95% confidence intervals closer to the nominal level than uncorrected ORTH. An analysis of patient-reported outcomes from an orthognathic surgery clinical trial illustrates features of ORTH.Ord. Conclusions - This article provides an overview of the ORTH method with bias-correction on both estimating equations and sandwich estimators for analyzing correlated ordinal data, describes the features of the ORTH.Ord R package, evaluates the performance of the package using a simulation study, and finally illustrates its application in an analysis of a clinical trial.
#author_notes:
#- Equal contribution
#- Equal contribution
authors:
- Can Meng
- admin
- Paul J. Rathouz
- Elizabeth L. Turner
- John S. Preisser
- Fan Li
date: "2023-07-01T00:00:00Z"
doi: "10.1016/j.cmpb.2023.107567"
featured: false
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false
projects: []
publication: '*Computer Methods and Programs in Biomedicine*'
publication_short: ""
publication_types:
- "2" # journal article
publishDate: "2023-07-01T00:00:00Z"
#slides: example
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
#   ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
tags:
- Computer Methods and Programs in Biomedicine
title: ORTH.Ord - An R package for analyzing correlated ordinal outcomes using alternating logistic regressions with orthogonalized residuals
url_code: ""
url_dataset: ""
url_pdf: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
