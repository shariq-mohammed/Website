---
authors:
- admin
- Dipak K. Dey
- Yuping Zhang
featured: false
publication: '*Statistical Analysis and Data Mining: The ASA Data Science Journal*'
publishDate: "2020-06-26T00:00:00Z"
publication_short: ""
publication_types:
- "2"
tags:
- Journal Articles
title: Classification of high-dimensional electroencephalography data with location selection using structured spike-and-slab prior
url_code: "https://github.com/shariq-mohammed/stSpikeSlabEEG"
url_dataset: ""
url_pdf: "https://onlinelibrary.wiley.com/doi/abs/10.1002/sam.11477"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

_**Invited for Statistical Analysis and Data Mining Best Paper Session at Joint Statistical Meetings 2022.**_ [JSM 2022 Program](https://ww2.amstat.org/meetings/jsm/2022/onlineprogram/ActivityDetails.cfm?SessionID=221965)

*Statistical Analysis and Data Mining: The ASA Data Science Journal* (2020).


# Abstract:

With the advent of modern technologies, it is increasingly common to deal with data of large dimensions in various scientific fields of study. In this paper, we develop a Bayesian approach for the classification of multi-subject high-dimensional electroencephalography (EEG) data. In this EEG data, we have a matrix of covariates corresponding to each subject from either the alcoholic or control group. The matrix covariates have a natural spatial correlation based on the locations of the brain, and temporal correlation as the measurements are taken over time. We employ a divide and conquer strategy by building multiple local Bayesian models at each time point separately. We incorporate the spatial structure through the structured spike-and-slab prior, which has inherent variable selection properties. The temporal structure is incorporated within the prior by learning from the local model from the previ- ous time point. We pool the information from the local models and use a weighted average to design a prediction method. We perform simulation studies to show the efficiency of our approach and demonstrate the local Bayesian modeling with a case study on EEG data.

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}