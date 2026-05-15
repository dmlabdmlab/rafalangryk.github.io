---
layout: archive
title: "Open Data"
permalink: /open-data/
author_profile: true
---

A core principle of my DMLab's research is open science. The datasets below are 
publicly available and have been used as community benchmarks for space weather 
forecasting, solar image analysis, and machine learning research. All datasets are 
free to use with appropriate citation.

---

## Space Weather & Solar Physics Datasets

### SWAN-SF — Space Weather ANalytics for Solar Flares
A comprehensive multivariate time series (MVTS) benchmark dataset extracted from 
NASA SDO/HMI solar photospheric vector magnetograms, covering 4,098 active regions 
from May 2010 to December 2018 with 51 flare-predictive parameters. Widely used 
as a community testbed for solar flare prediction models.

- 📄 **Paper:** [Angryk et al., *Scientific Data*, 2020](https://doi.org/10.1038/s41597-020-0548-x)
- 💾 **Dataset:** [Harvard Dataverse — doi:10.7910/DVN/EBCFKM](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EBCFKM)

---

### PIL Dataset — Magnetic Polarity Inversion Lines from SDO/HMI
A large-scale publicly available dataset of magnetic polarity inversion lines (PILs) 
covering solar cycle 24 (May 2010–March 2019), including PIL raster masks, region 
of polarity inversion (RoPI), and multivariate time-series metadata extracted from 
4,090 HARP series.

- 📄 **Paper:** [Ji et al., *Astrophysical Journal Supplement Series*, 2023](https://doi.org/10.3847/1538-4365/acb43a)
- 💾 **Dataset:** [Harvard Dataverse — doi:10.7910/DVN/BKP1RH](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/BKP1RH)

---

### Multimodal PIL Dataset — SDO/HMI Magnetic Polarity Inversions for Flare Forecasting
A supervised-format extension of the PIL dataset integrating rasters, convex hulls, 
and multivariate time series with flare class labels (FQ, C, M, X) for May 2010–
January 2019, designed for direct use in machine learning pipelines.

- 💾 **Dataset:** [Harvard Dataverse — doi:10.7910/DVN/4A7ORF](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/4A7ORF)

---

### Large-Scale SDO Image Dataset for Computer Vision
A standardized and curated large-scale dataset of solar events from NASA SDO/AIA 
high-resolution images, compiled to accelerate computer vision research on solar 
image data by reducing data acquisition and curation overhead.

- 📄 **Paper:** [Kucuk, Banda & Angryk, *Scientific Data*, 2017](https://doi.org/10.1038/sdata.2017.96)

---

### Curated Image Parameter Dataset from SDO/AIA
A large image parameter dataset extracted from NASA SDO/AIA instrument covering 
January 2011 onward at 6-minute cadence across nine wavelength channels (~1 TiB/year). 
Includes a public API for programmatic access.

- 📄 **Paper:** [Ahmadzadeh, Kempton & Angryk, *Astrophysical Journal Supplement Series*, 2019](https://iopscience.iop.org/article/10.3847/1538-4365/ab253a)

---

### Large-Scale Solar Event Reports from SDO Feature Recognition Modules
A comprehensive dataset of over 280,000 event reports for seven types of solar 
phenomena collected from automated SDO Feature Finding Team modules and reported 
to the Heliophysics Event Knowledgebase (HEK).

- 📄 **Paper:** [Schuh, Angryk & Martens, *Journal of Space Weather and Space Climate*, 2016](https://doi.org/10.1051/swsc/2016015)

---

## Using These Datasets

All datasets are freely available for research and educational use. If you use 
any of these datasets in your work, please cite the corresponding paper. For 
questions about data access, extensions, or collaboration, please 
[contact us](/contact/).