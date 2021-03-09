---
title: "Auto-regressive modeling and diagnostics for qPCR amplification"
authors:
- benjamin_hsu
- valeriia_sherina
- admin
date: "2019-06-10"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Bioinformatics*"
publication_short: "*Bioinformatics*"

abstract: "Current methods used to analyze real-time quantitative polymerase chain reaction (qPCR) data exhibit systematic deviations from the assumed model over the progression of the reaction. Slight variations in the amount of the initial target molecule or in early amplifications are likely responsible for these deviations. Commonly used 4- and 5-parameter sigmoidal models appear to be particularly susceptible to this issue, often displaying patterns of autocorrelation in the residuals. The presence of this phenomenon, even for technical replicates, suggests that these parametric models may be misspecified. Specifically, they do not account for the sequential dependent nature of the amplification process that underlies qPCR fluorescence measurements. We demonstrate that a Smooth Transition Autoregressive (STAR) model addresses this limitation by explicitly modeling the dependence between cycles and the gradual transition between amplification regimes. In summary, application of a STAR model to qPCR amplification data improves model fit and reduces autocorrelation in the residuals."

# Summary. An optional shortened abstract.
summary: 

tags:
- qPCR
featured: false

links:
- name: "Paper"
  url: "https://doi.org/10.1093/bioinformatics/btaa1000"
url_pdf: 'files/bioinformatics_2020.pdf'
url_code: 'https://github.com/bhsu4/GAPDH.SO'
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


