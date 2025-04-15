---
title: "Towards A Modular End-To-End Machine Learning Benchmarking Framework"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ties Robroek
  - Pınar Tözün

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: "2025-03-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In TDIS
publication_short: In TDIS

abstract: |2-
  Machine learning (ML) benchmarks are crucial for evaluating the performance, efficiency, and scalability of ML systems, especially as the adoption of complex ML pipelines, such as retrieval-augmented generation (RAG), continues to grow. These pipelines introduce intricate execution graphs that require more advanced benchmarking approaches. Additionally, collocating workloads can improve resource efficiency but may introduce contention challenges that must be carefully managed. Detailed insights into resource utilization are necessary for effective collocation and optimized edge deployments. However, existing benchmarking frameworks often fail to capture these critical aspects.

  We introduce a modular end-to-end ML benchmarking framework designed to address these gaps. Our framework emphasizes modularity and reusability by enabling reusable pipeline stages, facilitating flexible benchmarking across diverse ML workflows. It supports complex workloads and measures their end-to-end performance. The workloads can be collocated, with the framework providing insights into resource utilization and contention between the concurrent workloads.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ""
url_code: "https://github.com/itu-rad/collocation-benchmark"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
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
