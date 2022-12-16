---
title: "XRONOS: open chronometric data from archive to infrastructure"
authors:
- name: "Joe Roe"
  affiliation: "University of Bern"
  email: "joe@joeroe.io"
- name: "Martin Hinz"
  affiliation: "University of Bern"
  email: "martin.hinz@unibe.ch"
format: "Standard presentation"
session: "S3: Practical Applications"
weight: 180
---

Chronometric data has been one of the principle domains in which open data and open science approaches have been applied over the last ten years.
Comprehensive compilations of radiocarbon dates have become available for many parts of the world in the last decade and, as natural next step, there are now several initiatives to collate this data globally, including the retrieval tool c14bazAAR (Schmid et al. 2019), the IntChron exchange format (Bronk Ramsey et al. 2019), and the synthetic database p3kc14 (Bird et al. 2022).
This move from *archiving* individual datasets to producing a living open data *infrastructure* for archaeological chronologies raises a number of challenges.
Radiocarbon datasets are still sorely lacking for many parts of the world and, even in those regions with good coverage, the *quality* of data is highly uneven and largely undocumented.
There exists no central repository ensuring the long-term sustainability and completeness of these datasets,
and the potential of placing other sources of chronometric information (e.g. dendrochronology, typological dating) in an open data framework has hardly been realised at all.

Here, building on and complementing these initiatives, we present [XRONOS](https://xronos.ch): a new web-based platform for chronometric data from archaeological contexts worldwide, combining an open data repository with tools for importing, curating and analysing chronometric information from diverse sources.
The principal design goals of the software are to:

1. combine all available sources of radiocarbon and other chronometric data in single database;
2. develop robust tools for the continuous ingestion and refinement of this data;
3. disseminate this data within an open and FAIR framework, embedding it in the wider world of Linked Open Data in archaeology and beyond.

This talk outlines the conceptual and technical infrastructure developed to realise these goals in XRONOS' initial phases of development (2019 and 2021–2022), including
a generalised data model for site and radiocarbon information, extendable to other chronometric data;
an R- and Ruby-based pipeline for continuous ingestion of data from a variety of sources;
continuous, semi-automated data cleaning protocols;
a Ruby-on-Rails application providing a web-based frontend to the data and a REST API for programmatic access;
and an R package for interfacing with the API.
We believe the XRONOS framework provides more open, more reliable, and more comprehensive access to chronometric data than previously available, as well as a foundation for its continuous expansion and refinement.

## References

* Bird, Darcy, Lux Miranda, Marc Vander Linden, Erick Robinson, R. Kyle Bocinsky, Chris Nicholson, José M. Capriles, et al. 2022. “p3k14c, a Synthetic Global Database of Archaeological Radiocarbon Dates.” *Scientific Data* 9 (1): 27. https://doi.org/10.1038/s41597-022-01118-7.
* Bronk Ramsey, Christopher, Maarten Blaauw, Rebecca Kearney, and Richard A Staff. 2019. “The Importance of Open Access to Chronological Information: The IntChron Initiative.” *Radiocarbon* 61 (5): 1121–31. https://doi.org/10.  1017/RDC.2019.21.
* Schmid, Clemens, Dirk Seidensticker, and Martin Hinz. 2019. “c14bazAAR: An R Package for Downloading and Preparing C14 Dates from Different Source Databases.” *Journal of Open Source Software* 4 (43): 1914. https://doi.org/10.21105/joss.01914.
