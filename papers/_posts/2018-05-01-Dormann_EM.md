---
layout: paper
title: "Model averaging in ecology: a review of Bayesian, information-theoretic, and tactical approaches for predictive inference"
image: /images/papers/Dormann_2018_EM.png
authors: Dormann CF + 24 co-authors (including Keil P)
year: 2018
ref: Shade et al 2018 TREE
journal: "Ecological Monographs 88: 485-504"
pdf: /pdfs/papers/Dormann_2018_EM.pdf
doi: 10.1002/ecm.1309
---

# Abstract

In ecology, the true causal structure for a given problem is often not known, and several plausible models and thus model predictions exist. It has been claimed that using weighted averages of these models can reduce prediction error, as well as better reflect model selection uncertainty. These claims, however, are often demonstrated by isolated examples. Analysts must better understand under which conditions model averaging can improve predictions and their uncertainty estimates. Moreover, a large range of different model averaging methods exists, raising the question of how they differ in their behaviour and performance. 

Here, we review the mathematical foundations of model averaging along with the diversity of approaches available. We explain that the error in model-averaged predictions depends on each model's predictive bias and variance, as well as the covariance in predictions between models, and uncertainty about model weights. We show that model averaging is particularly useful if the predictive error of contributing model predictions is dominated by variance, and if the covariance between models is low. For noisy data, which predominate in ecology, these conditions will often be met. Many different methods to derive averaging weights exist, from Bayesian over information-theoretical to cross-validation optimized and resampling approaches. 

A general recommendation is difficult, because the performance of methods is often context dependent. Importantly, estimating weights creates some additional uncertainty. As a result, estimated model weights may not always outperform arbitrary fixed weights, such as equal weights for all models. When averaging a set of models with many inadequate models, however, estimating model weights will typically be superior to equal weights. We also investigate the quality of the confidence intervals calculated for model-averaged predictions, showing that they differ greatly in behaviour and seldom manage to achieve nominal coverage. Our overall recommendations stress the importance of non-parametric methods such as cross-validation for a reliable uncertainty quantification of model-averaged predictions.
