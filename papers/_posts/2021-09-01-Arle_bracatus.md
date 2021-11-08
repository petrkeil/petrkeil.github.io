---
layout: paper
title: "bRacatus: A method to estimate the accuracy and biogeographical status of georeferenced biological data"
image: /images/papers/arle.png
authors: Alre E, Zizka A, Keil P, Winter M, Essl F, Knight T, Wiegelt P, Jimenez-Munoz M, Meyer C
year: 2021
ref: Arle et al 2021 Meth Ecol Evol
journal: "Methods in Ecology and Evolution 21: 1759-1771"
pdf: /pdfs/papers/Arle_2021_MEE.pdf
doi: 10.1111/2041-210X.13629
---

# Abstract

**1.** Georeferenced biological data of species distributions, abundances or traits are critical for ecological and evolutionary research. However, the accuracy (true vs. false records) and biogeographical status (native vs. alien) of individual georeferenced records are often unclear, which limits their use in species distribution modelling, analyses of biodiversity change and other applications.

**2.** Here, we introduced bRacatus, a new method and R package to estimate a given georeferenced record's probability of being true or false and of corresponding to a native or an alien occurrence. Our framework avoided artificial thresholds of data filtering and instead implemented a probabilistic framework which allowed propagating uncertainties in subsequent analyses. We trained and tested our method on 400 terrestrial species of amphibians, birds, terrestrial mammals and vascular plants from four continents.

**3.** bRacatus showed good predictive power (mean AUC higher than 0.9; mean RMSE lower than 0.3) for both the accuracy and biogeographical status. Model performance was similar among continents, range sizes and taxa not used in the training. Tests were robust using either range maps or regional checklists of differing levels of data completeness as reference regions.

**4.** bRacatus was implemented as a user-friendly R package that enabled researchers to assess the accuracy and biogeographical status of species occurrences, population abundances, community composition or any other type of georeferenced biodiversity records. We proposed this method as a routine step in addressing the inherent uncertainty of point observations to promote more accurate ecological inference and predictions.
