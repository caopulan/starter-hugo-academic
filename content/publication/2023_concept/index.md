---
title: 'Image is All You Need to Empower Large-scale Diffusion Models for In-Domain Generation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Feng Zhou
  - Lu Yang
  - Tianrui Huang
  - Qing Song

# Author notes (optional)
author_notes:
  - 'Authors contribute equally'
  - 'Authors contribute equally'
  - 'Corresponding author'
  - 
  - 

date: '2025-06-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-06-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
#publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: CVPR 2025
publication_short: CVPR 2025

abstract: 'In-domain generation aims to perform a variety of tasks within a specific domain, such as unconditional generation, text-to-image, image editing, 3D generation, and more. Early research typically required training specialized generators for each unique task and domain, often relying on fully-labeled data. Motivated by the powerful generative capabilities and broad applications of diffusion models, we are driven to explore leveraging label-free data to empower these models for in-domain generation.Fine-tuning a pre-trained generative model on domain data is an intuitive but challenging way and often requires complex manual hyper-parameter adjustments since the limited diversity of the training data can easily disrupt the model original generative capabilities.To address this challenge, we propose a guidance-decoupled prior preservation mechanism to achieve high generative quality and controllability by image-only data, inspired by preserving the pre-trained model from a denoising guidance perspective.We decouple domain-related guidance from the conditional guidance used in classifier-free guidance mechanisms to preserve open-world control guidance and unconditional guidance from the pre-trained model. We further propose an efficient domain knowledge learning technique to train an additional text-free UNet copy to predict domain guidance.Besides, we theoretically illustrate a multi-guidance in-domain generation pipeline for a variety of generative tasks, leveraging multiple guidances from distinct diffusion models and conditions. Extensive experiments demonstrate the superiority of our method in domain-specific synthesis and its compatibility with various diffusion-based control methods and applications.'
  
# Summary. An optional shortened abstract.
summary: Empower diffusion model for in-domain generation.

tags:
  - Diffusion

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content/CVPR2025/html/Cao_Image_is_All_You_Need_to_Empower_Large-scale_Diffusion_Models_CVPR_2025_paper.html'
url_code: 'https://github.com/PRIV-Creation/In-domain-Generation-Diffusion'
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
  - Unidiffusion

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
