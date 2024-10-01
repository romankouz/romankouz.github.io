---

title: deepST - A Graph Convolutional Autoencoder for Spatial Transcriptomics

event: Michigan Student Symposium for Interdisciplinary Statistical Sciences (MSSISS 2022)
event_url: https://sites.lsa.umich.edu/mssiss/past/mssiss-2022-homepage/

location: University of Michigan


summary: A preliminary display of our probabilistic deep learning model for spatial transcriptomics data.
abstract: Spatial transcriptomics (ST) measures gene expression for individual cells and pairs these measurements with the positions of cells within a tissue sample. This opens the door for statistical methods to explore how neighboring cells interact.  The statistical structure of these interactions can be investigated by posing prediction problems. For example, we can see which subsets of genes in neighboring cells are most predictive of gene expression in target cells.  We can infer conditional independence structures by comparing prediction accuracy obtained from different subsets.   Existing methods pursuing this vision use fixed-dimensional summaries of the attributes of neighboring cells, ignoring the number of neighbors and the interactions among them.  We here propose deepST, a denoising graph convolutional autoencoder that accounts for these subtleties.  For a large MERFISH hypothalamus dataset, deepST imputes missing expression levels for response genes more accurately than other state-of-the-art methods including gradient boosting, attaining a 8.7\% reduction in absolute error.  We also find that gradient boosting itself outperforms existing methods in this domain such as ``Mixture of Experts for Spatial Signaling genes Identification'', attaining a 7.2\% reduction in absolute error.  This error reduction is critical because we are using differences in predictive accuracy to uncover biological structure, and these differences in prediction accuracy due to biological causes are often on the order of 1\%.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-04-02T13:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
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

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_slides: uploads/MSSISS.pdf

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