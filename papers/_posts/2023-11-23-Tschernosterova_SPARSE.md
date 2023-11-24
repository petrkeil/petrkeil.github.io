---
layout: paper
title: "SPARSE 1.0 - a template for databases of species inventories, with an open example of Czech birds"
image: /images/papers/sparse.jpg
authors: Tschernosterova K, Travnickova E, Grattarola F, Rosse C, Keil P
year: 2023
ref: Tschernosterova et al 2023 Biodiv Data J
journal: "Biodiversity Data Journal"
pdf: /pdfs/papers/Tschernosterova_2023_BDJ.pdf
doi: 10.3897/BDJ.11.e108731

---

# Abstract

Here, we introduce SPARSE (acronym for "SPecies AcRoss ScalEs"), a simple and portable template for databases that can store data on species composition derived from ecological inventories, surveys and checklists, with emphasis on metadata describing sampling effort and methods. SPARSE can accommodate resurveys and time series and data from different spatial scales, as well as complex sampling designs. SPARSE focuses on inventories that report multiple species for a given site, together with sampling methods and effort, which can be used in statistical models of true probability of occurrence of species. SPARSE is spatially explicit and can accommodate nested spatial structures from multiple spatial scales, including sampling designs where multiple sites within a larger area have been surveyed and the larger area can again be nested in an even larger region. Each site in SPARSE is represented either by a point, line (for transects) or polygon, stored in an ESRI shapefile. SPARSE implements a new combination of our own field definitions with Darwin Core biodiversity data standard and its Humboldt core extension. The use of Humboldt core also makes SPARSE suitable for biodiversity data with temporal replication.

We provide an example use of the SPARSE framework by digitising data on birds from the Czech Republic, from 348 sites and 524 sampling events, with 15,969 unique species-per-event observations of presence, abundance or population density. To facilitate use without the need for a high-level database expertise, the Czech bird example is implemented as MS Access .accdb file, but can be ported to other database engines. The example of Czech birds complements other bird datasets from the Czech Republic, specifically the four gridded national atlases and the breeding bird survey which cover a similar temporal extent, but different locations and spatial scales.
