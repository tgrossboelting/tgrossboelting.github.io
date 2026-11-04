---
title: "Generic Machine Learning Inference on Heterogeneous Treatment Effects in Regression Discontinuity Designs"
collection: publications
category: wip
permalink: /2026_03_01_ml_hte_in_RDDs
excerpt: ''
# The date is not displayed for work in progress; it only sets the order on
# the research page (newest first).
date: 2026-03-01
coauthors: "Paul Goldsmith-Pinkham"
---
Applied researchers routinely ask whether RD effects differ across individuals and whether these differences are explained by observed covariates. Current practice relies on splitting the sample based on a single covariate and testing for differences in treatment effect estimates across subsamples. In applied studies there are often many potential covariates to split on, which invites multiple testing, and researchers might not have strong priors about which observable characteristics matter. We propose a simple approach that combines machine learning with sample splitting to test for heterogeneous treatment effects in RD designs. The key idea is to use any flexible machine learning method to construct a proxy for the conditional average treatment effect, and then use this proxy to form subgroups that maximize between-group heterogeneity. Because the proxy is estimated on an auxiliary sample, standard nonparametric RD inference applies within each subgroup on the main sample. Using a simulation design from the literature, we find substantial improvements in power over existing methods.
