---
title: 'Spectral Clustering for Discrete Distributions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dong Qiao
  - Jicong Fan

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-01-25T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: Preprint
publication_short: Preprint

abstract: The discrete distribution is often used to describe complex instances in machine learning, such as images, sequences, and documents. Traditionally, clustering of discrete distributions (D2C) has been approached using Wasserstein barycenter methods. These methods operate under the assumption that clusters can be well-represented by barycenters, which is seldom true in many real-world applications. Additionally, these methods are not scalable for large datasets due to the high computational cost of calculating Wasserstein barycenters. In this work, we explore the feasibility of using spectral clustering combined with distribution affinity measures (e.g., maximum mean discrepancy and Wasserstein distance) to cluster discrete distributions. We demonstrate that these methods can be more accurate and efficient than barycenter methods. To further enhance scalability, we propose using linear optimal transport to construct affinity matrices efficiently for large datasets. We provide theoretical guarantees for the success of our methods in clustering distributions. Experiments on both synthetic and real data show that our methods outperform existing baselines.

tags:
  - Clustering
  - Optimal Transport
  - Machine Learning

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2401.13913'
url_code: ''
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
