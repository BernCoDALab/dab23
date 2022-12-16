---
title: "Modelling with open or restricted data? A case study from prehistoric Northern Europe"
authors:
- name: "Giacomo Bilotti"
  affiliation: "University of Kiel"
format: "Standard presentation"
session: "S3: Practical Applications"
weight: 120
---

In this contribution I model population dynamics and past land-use using predictive modelling on some case studies from the South Western Baltic region during the Neolithic and the Bronze Age. Besides the archaeological questions, I will focus on methodology and data availability. By definition, a model is a simplification of the reality that aims to explain observed systems and to predict unknown ones. Therefore, we always need to find a balance between complexity and universality, which can be seen as a sort of mathematical inequality, similar to the well-known Heisenberg uncertainty principle, which asserts the limit in the accuracy of measurement of a particle position and momentum. In our field, this is true in at least to respects:

* The more we try to build a global model the lower our resolution becomes;
* The more data we integrate the less reusable the model becomes in terms of data accessibility and
overcomplexity.

It is possible that in the future we will achieve some sort of Grand Unified Theory – to keep the parallel with physics – allowing the computation of complex and universal models. However, it is likely that the solution is far from being at hand, forcing us to elaborate a different framework. In order to do so, I propose a model dealing with a combination of complexity and simplicity, evaluating the interpretative gain of every additionally included variable and between open and often restricted data.

As a base model I use an oversimplified one, only based on a few and open covariates, notably the EU-DEM from Copernicus (available with 30 m ground resolution) and land use information derived from Open Street Map. As a second step, coarse resolution and open soil maps are introduced, as well as pollen data for environmental reconstructions (e.g. landscape openness) from publicly available repositories such as the European Pollen Database. Finally, I will substitute the low-resolution and open data with High-Resolution DTMs and high-resolution soil maps, which are not always available for every region. In every case I will use a reproducible and transparent workflow, providing the scripts used for the analysis and the necessary requirements.

The comparison between the different models allow an assessment of the interpretational gain in integrating the different covariates and the ideal threshold above which we may be satisfied with the output in terms of uncertainty and predictability. Finally, a cost-efficiency ratio is calculated, comparing the reproducibility and affordability of an open model versus one based on restricted-data, not only in terms of data availability but also computational, time and financial requirements.
