---
title: "A benchmark for microRNA quantification algorithms using the OpenArray platform"
authors:
- admin
- Alexander S. Baras
- Alexander Crits-Christoph
- Roxann Ingersoll
- Melissa A. McAlexander
- Kenneth W. Witwer
- Marc K. Halushka 
date: "2016-03-22"
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

abstract: "Several techniques have been tailored to the quantification of microRNA expression, including hybridization arrays, quantitative PCR (qPCR), and high-throughput sequencing. Each of these has certain strengths and limitations depending both on the technology itself and the algorithm used to convert raw data into expression estimates. Reliable quantification of microRNA expression is challenging in part due to the relatively low abundance and short length of the miRNAs. While substantial research has been devoted to the development of methods to quantify mRNA expression, relatively little effort has been spent on microRNA expression. In this work, we focus on the Life Technologies Taqman OpenArray system, a qPCR-based platform to measure microRNA expression. Several algorithms currently exist to estimate expression from the raw amplification data produced by qPCR-based technologies. To assess and compare the performance of these methods, we performed a set of dilution/mixture experiments to create a benchmark data set. We also developed a suite of statistical assessments that evaluate many different aspects of performance: accuracy, precision, titration response, number of complete features, limit of detection, and data quality. The benchmark data and software are freely available via two R/Bioconductor packages, miRcomp and miRcompData. Finally, we demonstrate use of our software by comparing two widely used algorithms and providing assessments for four other algorithms. Benchmark data sets and software are crucial tools for the assessment and comparison of competing algorithms. We believe that the miRcomp and miRcompData packages will facilitate the development of new methodology for microRNA expression estimation."

# Summary. An optional shortened abstract.
summary: 

tags:
- microRNA
- qPCR
featured: false

links:
- name: "Paper"
  url: "https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-0987-8"
url_pdf: 'files/bmc_bioinformatics_2016.pdf'
url_code: 'http://bioconductor.org/packages/release/bioc/html/miRcomp.html'
url_dataset: 'https://bioconductor.org/packages/release/data/experiment/html/miRcompData.html'
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
- microrna

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

---


