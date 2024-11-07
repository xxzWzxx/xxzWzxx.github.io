---
title: 'An example conference paper'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jicong Fan

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-11-07T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-06T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Conference on Neural Information Processing Systems
publication_short: NeurIPS

abstract: Graph classification is a challenging problem owing to the difficulty in quantifying the similarity between graphs or representing graphs as vectors, though there have been a few methods using graph kernels or graph neural networks (GNNs). Graph kernels often suffer from computational costs and manual feature engineering, while GNNs commonly utilize global pooling operations, risking the loss of structural or semantic information. This work introduces Graph Reference Distribution Learning (GRDL), an efficient and accurate graph classification method. GRDL treats each graph's latent node embeddings given by GNN layers as a discrete distribution, enabling direct classification without global pooling, based on maximum mean discrepancy to adaptively learned reference distributions. To fully understand this new model (the existing theories do not apply) and guide its configuration (e.g., network architecture, references' sizes, number, and regularization) for practical use, we derive generalization error bounds for GRDL and verify them numerically. More importantly, our theoretical and numerical results both show that GRDL has a stronger generalization ability than GNNs with global pooling operations. Experiments on moderate-scale and large-scale graph datasets show the superiority of GRDL over the state-of-the-art, emphasizing its remarkable efficiency, being at least 10 times faster than leading competitors in both training and inference stages.

tags:
  - Graph
  - Machine Learning

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/jicongfan/GRDL-Graph-Classification'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false
---
