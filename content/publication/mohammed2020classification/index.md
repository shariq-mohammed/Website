---
title: "Classification of high-dimensional electroencephalography data with location selection using structured spike-and-slab prior"

authors:
  - admin
  - "Dipak K. Dey"
  - "Yuping Zhang"

featured: false

# Journal article
publication_types: ["2"]
publication: "*Statistical Analysis and Data Mining: The ASA Data Science Journal*, 13(5), 465–481 (2020)"
publication_short: ""

# Use the publisher’s first-online date
date: 2020-07-28
publishDate: 2020-07-28

tags:
  - "Journal Articles"

# Single link only (DOI landing)
url_pdf: "https://doi.org/10.1002/sam.11477"

# Extras you provided
url_code: "https://github.com/shariq-mohammed/stSpikeSlabEEG"
---

**Invited for Statistical Analysis and Data Mining Best Paper Session at Joint Statistical Meetings 2022.** ([JSM 2022 Program](https://ww2.amstat.org/meetings/jsm/2022/onlineprogram/ActivityDetails.cfm?SessionID=221965))

*Statistical Analysis and Data Mining: The ASA Data Science Journal* (2020).

# Abstract:

With the advent of modern technologies, it is increasingly common to deal with data of large dimensions in various scientific fields of study. In this paper, we develop a Bayesian approach for the classification of multi-subject high-dimensional electroencephalography (EEG) data. In this EEG data, we have a matrix of covariates corresponding to each subject from either the alcoholic or control group. The matrix covariates have a natural spatial correlation based on the locations of the brain, and temporal correlation as the measurements are taken over time. We employ a divide and conquer strategy by building multiple local Bayesian models at each time point separately. We incorporate the spatial structure through the structured spike-and-slab prior, which has inherent variable selection properties. The temporal structure is incorporated within the prior by learning from the local model from the previous time point. We pool the information from the local models and use a weighted average to design a prediction method. We perform simulation studies to show the efficiency of our approach and demonstrate the local Bayesian modeling with a case study on EEG data.