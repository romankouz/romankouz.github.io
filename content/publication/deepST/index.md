---
title: "A Graph Convolutional Network for Spatial Transcriptomics Modelling"
authors:
- admin
- Jackson Loper
- Jeffrey Regier
date: "2023-09-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Single-cell spatial transcriptomics measures gene expression for individual cells and the positions of these cells within a tissue sample.  This data provides a new lens for studying cell-cell communication, but how to most efficiently use this data for inferential purposes is still being investigated. How cells interact with their neighbors can be investigated by comparing models where cells are aware of their neighbors against models where cells are not aware of their neighbors. Posing paired models offers one way to interpret spatial transcriptomics data, but this approach can fail when prediction algorithms are insufficiently flexible, either due to a reliance on fixed-dimensional neighboring expression encodings as model inputs or due to the limited expressivity of the prediction rule that maps neighborhood encodings to predictions. To obtain a sufficiently flexible model, we developed DeepST, a graph convolutional network that learns on graphs defined from spatial transcriptomics data sets.  The contrast between DeepST's predictions and the predictions from a baseline regressor lacking access to cell neighborhood information provides insights into how cells interact. 

# Summary. An optional shortened abstract.
summary: A spatially informed GCN tailored for spatial transcriptomics data. Incorporating expression information from neighboring cells is an open problem and we attempt to leverage deep graph convolutional networks to maximize response expression likelihoods.

tags:
- Spatial Transcriptomics
- GCN
- MLE

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 
url_code: 'https://github.com/prob-ml/spatial'
url_dataset: 'https://datadryad.org/stash/dataset/doi:10.5061/dryad.8t8s248'
url_poster: 'uploads/MSSISS.pdf'
url_project: ''
url_slides: 'uploads/JSM_Slides.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
