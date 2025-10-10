---
title: "HJCD-IK: GPU-Accelerated Inverse Kinematics through Batched Hybrid Jacobian Coordinate Descent"
authors:
- CaelYasutake
- ZacharyKingston
- admin
date: "2025-10-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: #In *[2026 International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)*
publication_short: #In *ICRA 2026*

abstract: "Inverse Kinematics (IK) is a core problem in robotics, in which joint configurations are found to achieve a desired end-effector pose. Although analytical solvers are fast and efficient, they are limited to systems with low degrees-of-freedom and specific topological structures. Numerical optimization-based approaches are more general, but suffer from high computational costs and frequent convergence to spurious local minima. Recent efforts have explored the use of GPUs to combine sampling and optimization to enhance both the accuracy and speed of IK solvers. We build on this recent literature and introduce HJCD-IK, a GPU-accelerated, sampling-based hybrid solver that combines an orientation-aware greedy coordinate descent initialization scheme with a Jacobian-based polishing routine. This design enables our solver to improve both convergence speed and overall accuracy as compared to the state-of-the-art, consistently finding solutions along the accuracy-latency Pareto frontier and often achieving order-of-magnitude gains. In addition, our method produces a broad distribution of high-quality samples, yielding the lowest maximum mean discrepancy. We release our code open-source for the benefit of the community."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We introduce HJCD-IK, a GPU-accelerated, sampling-based hybrid Inverse Kinematics (IK) solver that combines an orientation-aware greedy coordinate descent initialization scheme with a Jacobian-based polishing routine. This design enables our solver to improve both convergence speed and overall accuracy as compared to the state-of-the-art, consistently finding solutions along the accuracy-latency Pareto frontier and often achieving order-of-magnitude gains. In addition, our method produces a broad distribution of high-quality samples, yielding the lowest maximum mean discrepancy. We release our code open-source for the benefit of the community."

tags:
- Motion Planning
- Parallel Computing
- GPU
featured: false

links:
# - name: TBD
#   url: "TBD"
url_pdf: 'https://arxiv.org/abs/2510.07514'
url_code: 'https://github.com/a2r-lab/HJCD-IK'
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
projects: [GPUOptimization]
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

