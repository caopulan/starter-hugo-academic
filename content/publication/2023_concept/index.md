---
title: 'Concept-centric Personalization with Large-scale Diffusion Priors'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Lu Yang
  - Feng Zhou
  - Tianrui Huang
  - Qing Song

# Author notes (optional)
author_notes:
  - 
  - 
  - 
  - 
  - 'Corresponding author'

date: '2023-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
#publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ArXiv 2023
publication_short: ArXiv 2023

abstract: 'Despite large-scale diffusion models being highly capable of generating diverse open-world content, they still struggle to match the photorealism and fidelity of concept-specific generators. In this work, we present the task of customizing large-scale diffusion priors for specific concepts as concept-centric personalization. Our goal is to generate high-quality concept-centric images while maintaining the versatile controllability inherent to open-world models, enabling applications in diverse tasks such as concept-centric stylization and image translation. Distinct from existing personalization tasks that focus on specific entities, the proposed task requires large-scale training to achieve reasonable results. It brings forth unique challenges: difficult fidelity and controllability balancing and severe unconditional guidance drift in classifier-free guidance. To tackle these challenges, we identify catastrophic forgetting of guidance prediction from diffusion priors as the fundamental issue. Consequently, we develop a guidance-decoupled personalization framework specifically designed to address this task. We propose Generalized Classifier-free Guidance (GCFG) as the foundational theory for our framework. This approach extends Classifier-free Guidance (CFG) to accommodate an arbitrary number of guidances, sourced from a variety of conditions and models.  Employing GCFG enables us to separate conditional guidance into two distinct components: concept guidance for fidelity and control guidance for controllability. This division makes it feasible to train a specialized model for concept guidance, while ensuring both control and unconditional guidance remain intact. We then present a null-text Concept-centric Diffusion Model as a concept-specific generator to learn concept guidance without the need for text annotations. Furthermore, we demonstrate the seamless integration of our framework with existing techniques and underscore the vast potential of GCFG. Our extensive experiments confirm the superior efficacy of our proposed method in achieving concept-centric personalization. Code will be available at https://github.com/PRIV-Creation/Concept-centric-Personalization.'
  
# Summary. An optional shortened abstract.
summary: Customize diffusion model for concept-centric generation with high controllability, fidelity, and diversity.

tags:
  - Diffusion
  - Personalization

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
#- name: Custom Link
#  url: http://example.org

url_pdf: 'https://arxiv.org/abs/2312.08195'
url_code: 'https://github.com/PRIV-Creation/Concept-centric-Personalization'
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
