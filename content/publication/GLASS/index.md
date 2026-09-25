---
title: "GLASS: Architecture-Tuned, Composable, Device-Side Linear Algebra for Edge Robotics and Beyond"
authors:
- admin
date: "2026-09-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: "In *[2027 IEEE International Conference on Robotics and Automation (ICRA)](http://ieee-icra.org/)*"
# publication_short: In *ICRA 2027*

abstract: "GPU robotics lacks the reusable numerical infrastructure of mature CPU stacks, instead relying on compiler frameworks that introduce overhead or repeatedly reimplementing numerical libraries. To address this, we introduce GLASS (GPU Linear Algebra Simple Subroutines), a header-only CUDA C++ library that provides thread-, warp-, block-, and NVIDIA-backed implementations of robotics-scale linear algebra and geometric computations under one composable device API. GLASS treats implementation choice, execution scope, and launch packing as architecture-specific placement decisions determined by offline measurement and resolved statically at compile time. This is critical as the best and worst placements differ by a median of 4.9x (max 81x), with 145 of 396 recommended placements changing between a Jetson AGX Orin and an RTX 5090, and 162 of 396 versus an AGX Xavier. These stakes are highest at the edge as GLASS's advantage over the best of PyTorch and JAX is as much as 73x on the Orin versus 12x on the RTX  5090. GLASS is released open source with independent numerical oracles and source-bound local-GPU test attestation. Finally, integrating GLASS with published robotics systems both exposed a pre-existing numerical bug and improved embedded runtimes by up to 1.5x."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We introduce GLASS (GPU Linear Algebra Simple Subroutines), a header-only CUDA C++ library that provides thread-, warp-, block-, and NVIDIA-backed implementations of robotics-scale linear algebra and geometric computations under one composable device API. GLASS treats implementation choice, execution scope, and launch packing as architecture-specific placement decisions determined by offline measurement and resolved statically at compile time. This is critical as the best and worst placements differ by a median of 4.9x (max 81x), with 145 of 396 recommended placements changing between a Jetson AGX Orin and an RTX 5090, and 162 of 396 versus an AGX Xavier. These stakes are highest at the edge as GLASS's advantage over the best of PyTorch and JAX is as much as 73x on the Orin versus 12x on the RTX  5090. GLASS is released open source with independent numerical oracles and source-bound local-GPU test attestation. Finally, integrating GLASS with published robotics systems both exposed a pre-existing numerical bug and improved embedded runtimes by up to 1.5x."

tags:
- Hardware Acceleration
- Parallel Computing
- GPU
- Linear Algebra
- Numerical Software
featured: false

awards: []

links:
  - name: "Website"
    url: "https://a2r-lab.org/GLASS/"
  - name: "pytest-gpu-proof CI library"
    url: "https://a2r-lab.org/pytest-gpu-proof/"
url_pdf: 'https://arxiv.org/abs/2609.28179'
url_code: 'https://github.com/a2r-lab/GLASS'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects: [Accelerators]
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}} -->

<!-- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->