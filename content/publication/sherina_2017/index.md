---
title: "Statistical Approaches to Decreasing the Discrepancy of Non-detects in qPCR Data"
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
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*bioRxiv*"
publication_short: "*bioRxiv*"

abstract: "Quantitative real-time PCR (qPCR) is one of the most widely used methods to measure gene expression. Despite extensive research in qPCR laboratory protocols, normalization, and statistical analysis, little attention has been given to qPCR non-detects – those reactions failing to produce a minimum amount of signal. While most current software replaces these non-detects with a value representing the limit of detection, recent work suggests that this introduces substantial bias in estimation of both absolute and differential expression. Recently developed single imputation procedures, while better than previously used methods, underestimate residual variance, which can lead to anti-conservative inference. We propose to treat non-detects as non-random missing data, model the missing data mechanism, and use this model to impute missing values or obtain direct estimates of relevant model parameters. To account for the uncertainty inherent in the imputation, we propose a multiple imputation procedure, which provides a set of plausible values for each non-detect. In the proposed modeling framework, there are three sources of uncertainty: parameter estimation, the missing data mechanism, and measurement error. All three sources of variability are incorporated in the multiple imputation and direct estimation algorithms. We demonstrate the applicability of these methods on three real qPCR data sets and perform an extensive simulation study to assess model sensitivity to misspecification of the missing data mechanism, to the number of replicates within the sample, and to the overall size of the data set. The proposed methods result in unbiased estimates of the model parameters; therefore, these approaches may be beneficial when estimating both absolute and differential gene expression. The developed methods are implemented in the R/Bioconductor package nondetects. The statistical methods introduced here reduce discrepancies in gene expression values derived from qPCR experiments, providing more confidence in generating scientific hypotheses and performing downstream analysis."

# Summary. An optional shortened abstract.
summary: 

tags:
- qPCR
- nondetects
featured: true

links:
- name: "Preprint"
  url: "https://www.biorxiv.org/content/10.1101/231621v1"
url_pdf: ''
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


