---
title: Statistical Inference for Spatial Transcriptomics in the Age of Deep Learning

event: Joint Statistical Meetings 2023
event_url: https://ww2.amstat.org/meetings/jsm/2023/

location: Toronto, Ontario, Canada
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Using Graph Convolutional Networks for statistical inference in spatial transcriptomics.
abstract: Single-cell spatial transcriptomics (ST) measures gene expression for individual cells and their positions within a tissue sample. Understanding the gene regulatory networks that govern interactions within and between cells is a central goal of ST experiments, and establishing the conditional independence structure of these networks is an important step towards this goal. We test for conditional independence by comparing the accuracy with which nested subsets of variables predict other gene expressions.   Because cells and genes can relate to each other in complex nonlinear ways, and accurate predictions are essential for testing independence, we make predictions using a graph convolutional network (GCN). This GCN operates on graph-based encodings of ST data. In these graphs, nodes represent cells, spatially proximal cells are connected by weighted edges, and node attributes encode each cell's type and gene expressions. In simulated data, GCNs correctly estimate the true distributions where other methods fail. In real data, GCNs yield the highest likelihoods on held-out data and reveal several gene-pair dependencies.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-08-05'
date_end: '2023-08-10'
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
url_pdf: ''
url_slides: JSM_Slides.pdf
# url_video: 'https://youtube.com'

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
