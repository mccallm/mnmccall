---
title: "The effect of tissue composition on gene co-expression"
authors:
- yun_zhang
- jonavelle_cuerdo
- Marc K. Halushka
- admin
date: "2019-12-08"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Briefings in Bioinformatics*"
publication_short: "*Briefings in Bioinformatics*"

abstract: "Variable cellular composition of tissue samples represents a significant challenge for the interpretation of genomic profiling studies. Substantial effort has been devoted to modeling and adjusting for compositional differences when estimating differential expression between sample types. However, relatively little attention has been given to the effect of tissue composition on co-expression estimates. In this study, we illustrate the effect of variable cell-type composition on correlation-based network estimation and provide a mathematical decomposition of the tissue-level correlation. We show that a class of deconvolution methods developed to separate tumor and stromal signatures can be applied to two component cell-type mixtures. In simulated and real data, we identify conditions in which a deconvolution approach would be beneficial. Our results suggest that uncorrelated cell-type-specific markers are ideally suited to deconvolute both the expression and co-expression patterns of an individual cell type. We provide a Shiny application for users to interactively explore the effect of cell-type composition on correlation-based co-expression estimation for any cell types of interest."

# Summary. An optional shortened abstract.
summary: 

tags:
- coexpression
- deconvolution
- cell_mixture
featured: true

links:
- name: "Paper"
  url: "https://doi.org/10.1093/bib/bbz135"
url_pdf: 'files/briefings_in_bioinformatics_2021.pdf'
url_code: 'https://github.com/yunzhang813/simDeNet-R-Package-Shiny'
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
- cell_mixture

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

---


