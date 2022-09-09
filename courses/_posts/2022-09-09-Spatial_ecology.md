---
layout: default
title: FZP CZU, winter semester
handle: Spatial ecology and macroecology
image:
category: post
author: ptrkl
---

# Spatial ecology and macroecology (winter semester)

Principal lecturer: *Petr Keil*

Other lecturers: *Florencia Grattarola*, *Francois Leroy*

## Summary 
This is an introduction to geographical patterns of species distributions and biodiversity, and their connections to applied ecological and conservation problems. It focuses on biological phenomena at large geographic resolutions (ca. 1km2 or coarser) or large geographic extents (continents, Earth). It also introduces major theories and models that explain or predict these geographic patterns. Practical parts are done mostly in R, and they aim to introduce data types, and quantitative methods used in macroecology. The course blends elements of biogeography, ecology, and spatial data analysis. Among others, the course is aimed at species distribution modellers, physical geographers, conservationists, and policy makers who will benefit from a „big picture“ perspective not provided by traditional ecology, nor by physical geography.

## Requirements

 Elementary knowledge of R, i.e. participants should be able to turn it on, load data in, and execute basic commands. Prior knowledge of ecology, geography, or statistics is advantageous, but not necessary.

## Form

Ca. 1.5h lecture and 1.5h practical exercise once per week. 


## Contents

1. **Species geographic distributions - where species live?** 
Lecture. Probability of occurrence, abundance, endemism, spatial aggregation. 
Practice (Flo, Petr). Major data sources and data types: GBIF, OBIS, Map of Life, IUCN, BIEN, eBIRD, BBS, important atlas projects. Open vs. closed data, data quality issues, automatic download (e.g. through R packages), licensing and data sharing. 

2. **Drivers of distributions – why are species where they are?**
Lecture. Environmental drivers of distributions, dispersal limits, species abiotic and biotic niche, climatic niche, optima, ecological limits, habitat requirements. 
Practice (Flo, Petr). Species Distribution Models (SDM) in R vol. 1, niche models, predicted vs observed maps, comparison of techniques.

3. **Species range size – what it means to be rare?**
Lecture. Range size, area of occupancy, extent of occurrence, role of spatial scale, fractals, aggregation. Patterns of range size, Rapoport’s rule, range size vs abundance, range size and abundance distributions. 
Practice (Petr, Flo). SDM in R vol. 2 – spatial autocorrelation, or other advanced stuff.

4. **Applied issues around range and its size – which species should we protect?** 
Lecture. Rarity, conservation status, IUCN, endemism, threat. 
Practice (Petr, Flo, Francois). SDM in R vol. 3 – occupancy models, data vs models, Unmarked. Alternatively, we can do this about the topic of the lecture (range size, climate projections, …), or on Red List index. Bottom line: This is open, we will assess the week before.

5. **Simple biodiversity – what is diversity and why does it matter?**
Lecture. Introduction to biodiversity, history, major concepts. Count-based measures – taxonomic, phylogenetic, functional diversity, weighted endemism. Diversity in other disciplines. Why diversity matters, biodiversity-ecosystem functioning (BEF). 
Practice (Francois, Flo). Empirical data I - Geographic ranges and biodiversity in an example large-scale biodiversity database, learning the basics and visualizing things.

6. **Biodiversity and spatial scale – where and how much should we count species?**
Lecture. Biodiversity scaling: Species-area relationship, endemics-area relationship, alpha vs. beta vs. gamma diversity. Species accumulation curves, rarefaction, MoB. 
Practice (Flo, Francois). Empirical data II - Gridding biodiversity data, exploring patterns at different resolutions, making pretty maps. 

7. **Complex biodiversity – it’s not just the counts.** 
Lecture. Species composition, beta diversity, co-occurrences and species associations. Diversity at higher levels: Coenoses and biomes. 
Practice (Petr). Empirical data III - Gridding biodiversity data – mapping beta diversity and species associations, brief mention of ordinations.

8. **Spatial patterns of biodiversity – where are the places with many species?** 
Lecture. Biodiversity patterns: Latitudinal and altitudinal gradients, distance decay of similarity. 
Practice (Francois). Playing with (in R) and interpreting a regression model (or machine learning) explaining biodiversity in a real-world dataset, including spatial autocorrelation.

9.  **Theories and mechanisms I. – why are some places species-rich and other poor?** 
Lecture. Theory of island biogeography, neutral theory, maximum entropy theory, historical drivers of diversity.
Practice (Petr, Francois). Null models and simulations II. Coding and playing (in R) with a simple neutral model.

10.  **Theories and mechanisms II. – is it all about climate?** 
Lecture. All things climate – Rohde‘s hypothesis, metabolic theory, species-energy, endotherms vs ectotherms, habitat heterogeneity. 
Practice (Petr). Null models and simulations I. Playing with a simple range placement model to explore mid-domain effect, the effect of geometric constraints, and the idea of null models

11. **Temporal change – how does nature change in time during anthropocene?** 
Lecture. Range size dynamics – expansions, contractions, extirpations. Biodiversity change, species loss, extinction rates, invasions. Spatial scale and biodiversity change, drivers of biodiversity change, anthropocene. 
Practice (Francois). Exploring major biodiversity change datasets: BioTime, PREDICTS.

12. **Applied issues around biodiversity – which places should we protect?** 
Lecture. What should we protect? Biodiversity, rarity, or function? Habitat loss vs species loss, SLOSS, reserve selection, effects of climate, connectivity, refugia, neorefugia. 
Practice (Petr, Flo). A biodiversity hotspots / conservation prioritization (Zonation, Marxan).

## Literature
- Lomolino et al. (2010) Biogeography. Sinauer.
- Storch et al. (2007) Scaling Biodiversity. Cambridge University Press.
- McGill & Mittlebach (2012) Community Ecology. Oxford University Press.
- Brown J. (1995) Macroecology. University of Chicago Press.
- Smith et al. (2014) Foundations of Macroecology. University of Chicago Press.
- Ladle & Whittaker (2011) Conservation Biogeography. Wiley.

