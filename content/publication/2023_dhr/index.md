---
title: 'What Decreases Editing Capability? Domain-Specific Hybrid Refinement for Improved GAN Inversion'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Lu Yang
  - Dongxv Liu
  - Xiaoya Yang
  - Tianrui Huang
  - Qing Song

# Author notes (optional)
author_notes:
  - 
  - 
  - 
  - 
  - 
  - 'Corresponding author'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
#publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: WACV 2024
publication_short: WACV 2024

abstract: Recently, inversion methods have been exploring the incorporation of additional high-rate information from pretrained generators (such as weights or intermediate features) to improve the refinement of inversion and editing results from embedded latent codes. While such techniques have shown reasonable improvements in reconstruction, they often lead to a decrease in editing capability, especially when dealing with complex images that contain occlusions, detailed backgrounds, and artifacts. A vital crux is refining inversion results, avoiding editing capability degradation. To address this problem, we propose a novel refinement mechanism called **Domain-Specific Hybrid Refinement** (DHR), which draws on the advantages and disadvantages of two mainstream refinement techniques. We find that the weight modulation can gain favorable editing results but is vulnerable to these complex image areas and feature modulation is efficient at reconstructing. Hence, we divide the image into two domains and process them with these two methods separately. We first propose a Domain-Specific Segmentation module to automatically segment images into in-domain and out-of-domain parts according to their invertibility and editability without additional data annotation, where our hybrid refinement process aims to maintain the editing capability for in-domain areas and improve fidelity for both of them. We achieve this through Hybrid Modulation Refinement, which respectively refines these two domains by weight modulation and feature modulation. Our proposed method is compatible with all latent code embedding methods. Extension experiments demonstrate that our approach achieves state-of-the-art in real image inversion and editing. Code is available at https://github.com/caopulan/Domain-Specific_Hybrid_Refinement_Inversion.

# Summary. An optional shortened abstract.
summary: Editing capability decreases ineivitably in previous refinement methods, (e.g., PTI, HFGI, and SAM). In this work, we explore the idea of "divide and conquer" to address this problem. We combine two mainstream refinement mechanisms (i.e., weight ande feature modulation) and achieve extroadinary inversion and editing results.

tags: [GAN Inversion]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://arxiv.org/abs/2301.12141'
url_code: 'https://github.com/caopulan/Domain-Specific_Hybrid_Refinement_Inversion'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - gan_inverter

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
