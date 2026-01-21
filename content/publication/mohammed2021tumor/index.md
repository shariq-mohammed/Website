---
title: "Tumor radiogenomics in gliomas with Bayesian layered variable selection"

authors:
  - admin
  - "Sebastian Kurtek"
  - "Karthik Bharath"
  - "Arvind Rao"
  - "Veerabhadran Baladandayuthapani"

featured: false

# Journal article
publication_types: ["2"]
publication: "*Medical Image Analysis*, 90, 102964 (2023)"
publication_short: ""

# Use the publisher’s first-online date
date: 2023-09-12
publishDate: 2023-09-12

tags:
  - "Journal Articles"

# Single link only (DOI landing)
url_pdf: "https://doi.org/10.1016/j.media.2023.102964"

# Keep your code link
url_code: "https://github.com/shariq-mohammed/marbles"
---

*Medical Image Analysis* (2023).

# Abstract:

We propose a statistical framework to analyze radiological magnetic resonance imaging (MRI) and genomic data to identify the underlying radiogenomic associations in lower grade gliomas (LGG). We devise a novel imaging phenotype by dividing the tumor region into concentric spherical layers that mimics the tumor evolution process. MRI data within each layer is represented by voxel–intensity-based probability density functions which capture the complete information about tumor heterogeneity. Under a Riemannian-geometric framework these densities are mapped to a vector of principal component scores which act as imaging phenotypes. Subsequently, we build Bayesian variable selection models for each layer with the imaging phenotypes as the response and the genomic markers as predictors. Our novel hierarchical prior formulation incorporates the interior-to-exterior structure of the layers, and the correlation between the genomic markers. We employ a computationally-efficient Expectation–Maximization-based strategy for estimation. Simulation studies demonstrate the superior performance of our approach compared to other approaches. With a focus on the cancer driver genes in LGG, we discuss some biologically relevant findings. Genes implicated with survival and oncogenesis are identified as being associated with the spherical layers, which could potentially serve as early-stage diagnostic markers for disease monitoring, prior to routine invasive approaches. We provide a R package that can be used to deploy our framework to identify radiogenomic associations.