---
title: Cell Morphology
summary: Methods to quantify and analyze changes in cell morphology. 
authors:
- erik_vonkaenel
share: false
comment: false
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: 

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Advances in high-throughput cell imaging techniques provide an opportunity to develop computational methods to jointly model cell morphology and gene expression. We developed a method to identify genes associated with context-dependent alterations in cell morphology (Nassiri and McCall, 2018). Application of this method to molecular perturbation data from the Library of Integrated Network-based Cellular Signatures (LINCS) Project identifid gene sets associated with individual morphological features.

This project seeks to improve the analysis of cell morphology, specifically microglia morphology, by developing statistical methods to quantify images of cells and to use multiple measures to examine differences in broad domains of morphology between experimental conditions. The majority of current image summaries are not based on an explicit statistical model and lack a corresponding measure of uncertainty. Finally, individual quantitative summaries are typically analyzed separately, ignoring
the dependence between different aspects of cell morphology and thereby reducing statistical power. We are developing statistical methods to model cell morphology that fully leverage the wealth of information present in the imaging data and provide interpretable parameter estimates and corresponding measures of uncertainty. 
