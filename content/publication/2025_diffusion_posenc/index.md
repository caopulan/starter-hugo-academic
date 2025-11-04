---
title: 'Exploring Position Encoding in Diffusion U-Net for Training-free High-resolution Image Generation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Feng Zhou
  - admin
  - Yiyang Ma
  - Lu Yang
  - Jianqin Yin

# Author notes (optional)
author_notes: []

date: '2025-03-12T00:00:00Z'
doi: '10.48550/arXiv.2503.09830'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-12T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
#publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'arXiv preprint arXiv:2503.09830'
publication_short: 'arXiv:2503.09830'

abstract: Scaling latent resolutions in diffusion U-Nets often produces repetitive artifacts because zero-padding fails to propagate accurate positional cues. Through an analysis of position encoding pathways, this work attributes the degradation to inconsistent positional information and introduces Progressive Boundary Complement, a training-free strategy that synthesizes virtual boundaries to keep features spatially grounded. The method recovers high-resolution fidelity without retraining and consistently improves detail richness across benchmarks.

# Summary. An optional shortened abstract.
summary: Training-free positional encoding fix for high-resolution diffusion generation.
  
tags:
  - Diffusion
  - High-resolution Synthesis

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2503.09830'
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

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
slides: ''
---
