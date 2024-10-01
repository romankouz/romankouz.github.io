---
title: Discovering Spatial Differential Expression with Graph Convolutional Networks

event: Machine Learning in Computational Biology (MLCB 2022)
event_url: https://example.org

location: Hugo Blox Builder HQ
address:
  street: 450 Serra Mall
  city: Stanford
  region: CA
  postcode: '94305'
  country: United States

summary: A poster session for our paper on deepST.
abstract: Single-cell spatial transcriptomics measures gene expression for individual cells and pairs these measurements with the positions of cells within a tissue sample.  With spatial transcriptomic data, how neighboring cells interact can be investigated by posing a pair of prediction problems.  The first problem is to predict a gene's expression in each cell using the attributes of the cell.  The second problem is to predict the same responses using the attributes of the cell and its neighbors.  Genes may then be ranked according to difference in predictive performance - genes for which the predictions from the second problem are more accurate than the first may carry important spatial correlates.  Highly ranked genes may warrant further investigation through follow-up experiments. Mixture of Experts for Spatial Signaling genes Identification (MESSI) is one method that adopts this general approach.  However, MESSI is limited to using fixed-dimensional encoding of the attributes of neighboring cells as predictors. MESSI encodes neighboring information as the sum of gene expressions over all neighboring cells, with neighborhood structure determined by Delaunay triangulation.  These encodings ignore the number of neighbors and the interactions among them.  We propose instead to encode neighboring information as a graph, thus avoiding the limitations of fixed-dimensional encodings.   

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-11-22T13:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

url_pdf: uploads/MLCB_Submission.pdf

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---