---
title: "Discriminating pseudoprogression and true progression in diffuse infiltrating glioma using multi-parametric MRI data through deep learning"

authors:
  - "Joonsang Lee"
  - "Nicholas C. Wang"
  - "Sevcan Turk"
  - admin
  - "Remy Lobo"
  - "John Kim"
  - "Eric Liao"
  - "Sandra Camelo-Piragua"
  - "Michelle M. Kim"
  - "Larry Junck"
  - "Jayapalli R. Bapuraj"
  - "Ashok Srinivasan"
  - "Arvind Rao"

featured: false

# Journal article
publication_types: ["2"]
publication: "*Scientific Reports*, 10, 20331 (2020)"
publication_short: ""

# Use the journal's first-online date
date: 2020-11-23
publishDate: 2020-11-23

tags:
  - "Journal Articles"

# Single link only (DOI)
url_pdf: "https://doi.org/10.1038/s41598-020-77389-0"

---

*Scientific Reports* (2020).

# Abstract:
Differentiating pseudoprogression from true tumor progression has become a significant challenge in follow-up of diffuse infiltrating gliomas, particularly high grade, which leads to a potential treatment delay for patients with early glioma recurrence. In this study, we proposed to use a multiparametric MRI data as a sequence input for the convolutional neural network with the recurrent neural network based deep learning structure to discriminate between pseudoprogression and true tumor progression. In this study, 43 biopsy-proven patient data identified as diffuse infiltrating glioma patients whose disease progressed/recurred were used. The dataset consists of five original MRI sequences; pre-contrast T1-weighted, post-contrast T1-weighted, T2-weighted, FLAIR, and ADC images as well as two engineered sequences; T1post–T1pre and T2–FLAIR. Next, we used three CNN-LSTM models with a different set of sequences as input sequences to pass through CNN-LSTM layers. We performed threefold cross-validation in the training dataset and generated the boxplot, accuracy, and ROC curve, AUC from each trained model with the test dataset to evaluate models. The mean accuracy for VGG16 models ranged from 0.44 to 0.60 and the mean AUC ranged from 0.47 to 0.59. For CNN-LSTM model, the mean accuracy ranged from 0.62 to 0.75 and the mean AUC ranged from 0.64 to 0.81. The performance of the proposed CNN-LSTM with multiparametric sequence data was found to outperform the popular convolutional CNN with a single MRI sequence. In conclusion, incorporating all available MRI sequences into a sequence input for a CNN-LSTM model improved diagnostic performance for discriminating between pseudoprogression and true tumor progression.