---
title: "Multiple imputation and direct estimation for qPCR data with non-detects"
authors:
- valeriia_sherina
- Helene R. McMurray
- winslow_powers
- Hartmut Land
- Tanzy M.T. Love
- admin
date: "2017-12-08"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*BMC Bioinformatics*"
publication_short: "*BMC Bioinformatics*"

abstract: "Quantitative real-time PCR (qPCR) is one of the most widely used methods to measure gene expression. An important aspect of qPCR data that has been largely ignored is the presence of non-detects: reactions failing to exceed the quantification threshold and therefore lacking a measurement of expression. While most current software replaces these non-detects with a value representing the limit of detection, this introduces substantial bias in the estimation of both absolute and differential expression. Single imputation procedures, while an improvement on previously used methods, underestimate residual variance, which can lead to anti-conservative inference. We propose to treat non-detects as non-random missing data, model the missing data mechanism, and use this model to impute missing values or obtain direct estimates of model parameters. To account for the uncertainty inherent in the imputation, we propose a multiple imputation procedure, which provides a set of plausible values for each non-detect. We assess the proposed methods via simulation studies and demonstrate the applicability of these methods to three experimental data sets. We compare our methods to mean imputation, single imputation, and a penalized EM algorithm incorporating non-random missingness (PEMM). The developed methods are implemented in the R/Bioconductor package nondetects. The statistical methods introduced here reduce discrepancies in gene expression values derived from qPCR experiments in the presence of non-detects, providing increased confidence in downstream analyses."

# Summary. An optional shortened abstract.
summary: 

tags:
- qPCR
- Missing Data
featured: true

links:
- name: "Paper"
  url: "https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-03807-9"
url_pdf: 'files/bmc_bioinformatics_2020.pdf'
url_code: 'https://bioconductor.org/packages/nondetects/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- qpcr

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

---


