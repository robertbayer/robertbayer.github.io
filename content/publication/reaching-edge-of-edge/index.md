---
title: "Reaching the Edge of the Edge: Image Analysis in Space"
authors:
- admin
- Julian Priest
- Pınar Tözün
date: "2023-06-27T00:00:00Z"
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

abstract: |2-
  Satellites have become more widely available due to the reduction in size and cost of their components. As a result, there has been an advent of smaller organizations having the ability to deploy satellites with a variety of data-intensive applications to run on them. One popular application is image analysis to detect, for example, land, ice, clouds, etc. for Earth observation. However, the resource-constrained nature of the devices deployed in satellites creates additional challenges for this resource-intensive application.

  In this paper, we present our work and lessons-learned on building an Image Processing Unit (IPU) for a satellite. We first investigate the performance of a variety of edge devices (comparing CPU, GPU, TPU, and VPU) for deep-learning-based image processing on satellites. Our goal is to identify devices that can achieve accurate results and are flexible when workload changes while satisfying the power and latency constraints of satellites. Our results demonstrate that hardware accelerators such as ASICs and GPUs are essential for meeting the latency requirements. However, state-of-the-art edge devices with GPUs may draw too much power for deployment on a satellite. Then, we use the findings gained from the performance analysis to guide the development of the IPU module for an upcoming satellite mission. We detail how to integrate such a module into an existing satellite architecture and the software necessary to support various missions utilizing this module.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/abs/2301.04954
url_code: 'https://github.com/Resource-Aware-Data-systems-RAD/DISCO-IPU-Benchmark'

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
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
slides: ""
---
