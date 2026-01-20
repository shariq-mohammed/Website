---
title: "Scalable spatio-temporal Bayesian analysis of high-dimensional electroencephalography data"

authors:
  - admin
  - "Dipak K. Dey"

featured: false

# Journal article
publication_types: ["2"]
publication: "*Canadian Journal of Statistics*, 49(1), 107–128 (2021)"
publication_short: ""

# Use the publisher’s first-online date
date: 2021-02-12
publishDate: 2021-02-12

tags:
  - "Journal Articles"

# Single link only (DOI landing)
url_pdf: "https://doi.org/10.1002/cjs.11592"

# Extras
url_code: "https://github.com/shariq-mohammed/scalableBayesEEG"
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

*Canadian Journal of Statistics* (2021).

# Abstract:

We present a scalable Bayesian modeling approach for identifying brain regions that respond to a certain stimulus and use them to classify subjects. We specifically deal with multi-subject electroencephalography (EEG) data with a binary response distinguishing between alcoholic and control groups. The covariates are matrix-variate with measurements taken for each subject at different locations across multiple time points. EEG data has a complex structure with both spatial and temporal attributes to it. We use a divide-and-conquer strategy to build multiple local models, that is, one model at each time point separately. We employ Bayesian variable selection approaches using a structured continuous spike-and-slab prior to identify the locations which respond to a certain stimulus. We incorporate the spatio-temporal structure through a Kronecker product of the spatial and temporal correlation matrices. We develop a highly scalable estimation algorithm using likelihood approximation to deal with large number of parameters in the model. Variable selection is done via clustering of the locations based on their duration of activation. We use scoring rules to evaluate the prediction performance. We perform simulation studies to demonstrate the efficiency of our scalable algorithm in terms of estimation and fast computation. We present results using our scalable approach for a case study on multi-subject EEG data.
