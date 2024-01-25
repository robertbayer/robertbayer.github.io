---
title: 'TPCx-AI on NVIDIA Jetsons'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jon Voigt Tøttrup
  - Pınar Tözün

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-09-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In TPC-TC
publication_short: In TPC-TC

abstract: |2-
  Despite their resource- and power-constrained nature, edge devices also exhibit an increase in the available compute and memory resources and heterogeneity, similar to the evolution of server hardware in the past decade. For example, NVIDIA Jetson devices have a system- on-chip (SoC) composed of an ARM CPU and an NVIDIA GPU sharing RAM that could be up to 32 GB. Such an SoC setup offers opportunities to push down complex computations closer to the data source rather than performing them on remote servers.

  In this paper, we characterize the performance of two types of NVIDIA Jetson devices for end-to-end machine learning pipelines using the TPCx- AI benchmark. Our results demonstrate that the available memory is the main limitation to performance and scaling up machine learning workloads on edge devices. Despite this limitation, some edge devices show promise when comparing against a desktop hardware in terms of power-efficiency and reduction in data movement. In addition, exploiting the available compute parallelism on these devices can benefit not just model training and inference but also data pre-processing. By parallelizing, we get close to an order of magnitude improvement in pre-processing time for one of the TPCx-AI use cases. Finally, while TPCx-AI is a valuable benchmark, it is designed for server settings; therefore, the community needs an end-to-end machine learning benchmark targeting IoT/edge.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/ContainedBlargh/TPCx-AI-on-Nvidia-Jetsons'

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---