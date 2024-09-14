---
title: 'CasOmniMVS: Cascade Omnidirectional Depth Estimation with Dynamic Spherical Sweeping'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Pinzhi Wang
  - Ming Li
  - Jinghao Cao
  - Sidan Du
  - Yang Li

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: Applied Sciences
publication_short: ""

abstract: Estimating 360° depth from multiple cameras has been a challenging problem. However, existing methods often adopt a fixed-step spherical sweeping approach with densely sampled spheres and use numerous 3D convolutions in networks, which limits the speed of algorithms in practice. Additionally, obtaining high-precision depth maps of real scenes poses a challenge for the existing algorithms. In this paper, we design a cascade architecture using a dynamic spherical sweeping method that progressively refines the depth estimation from coarse to fine over multiple stages. The proposed method adaptively adjusts sweeping intervals and ranges based on the predicted depth and the uncertainty from the previous stage, resulting in a more efficient cost aggregation performance. The experimental results demonstrated that our method achieved state-of-the-art accuracy with reduced GPU memory usage and time consumption compared to the other methods. Furthermore, we illustrate that our method achieved satisfactory performance on real-world data, despite being trained on synthetic data, indicating its generalization potential and practical applicability.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.mdpi.com/2076-3417/14/2/517/pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


