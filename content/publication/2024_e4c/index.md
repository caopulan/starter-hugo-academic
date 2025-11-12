---
title: 'E4C: Enhance Editability for Text-Based Image Editing by Harnessing Efficient CLIP Guidance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tianrui Huang
  - admin
  - Lu Yang
  - Chun Liu
  - Mengjie Hu
  - Zhiwei Liu
  - Qing Song

# Author notes (optional)
author_notes:
  - 'Authors contribute equally'
  - 'Authors contribute equally'
  - 
  - 
  - 
  - 
  - 'Corresponding author'

date: '2024-03-18T00:39:13Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-18T00:39:13Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
#publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE TCSVT 2025
publication_short: IEEE TCSVT 2025

abstract: Diffusion-based image editing is a composite process of preserving the source image content and generating new content or applying modifications. While current editing approaches have made improvements under text guidance, most of them have only focused on preserving the information of the input image, disregarding the importance of editability and alignment to the target prompt. In this paper, we prioritize the editability by proposing a zero-shot image editing method, named \textbf{E}nhance \textbf{E}ditability for text-based image \textbf{E}diting via \textbf{E}fficient \textbf{C}LIP guidance (\textbf{E4C}), which only requires inference-stage optimization to explicitly enhance the edibility and text alignment. Specifically, we develop a unified dual-branch feature-sharing pipeline that enables the preservation of the structure or texture of the source image while allowing the other to be adapted based on the editing task. We further integrate CLIP guidance into our pipeline by utilizing our novel random-gateway optimization mechanism to efficiently enhance the semantic alignment with the target prompt. Comprehensive quantitative and qualitative experiments demonstrate that our method effectively resolves the text alignment issues prevalent in existing methods while maintaining the fidelity to the source image, and performs well across a wide range of editing tasks.

# Summary. An optional shortened abstract.
summary: Improving editability in text-guided Image editing.
  
tags:
  - Diffusion
  - Editing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10887316'
#url_code: 'https://github.com/caopulan/Domain-Specific_Hybrid_Refinement_Inversion'
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
#projects:
#  - gan_inverter

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
