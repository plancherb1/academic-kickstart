---
title: "HJCD-IK: GPU-Accelerated Inverse Kinematics through Batched Hybrid Jacobian Coordinate Descent"
authors:
- CaelYasutake
- AndrewLiu
- ZacharyKingston
- admin
date: "2026-09-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2026 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)](https://2026.ieee-iros.org/)*
publication_short: In *IROS 2026*

abstract: "Inverse Kinematics (IK) is a core problem in robotics, in which joint configurations are found to achieve a (collision free) desired end-effector pose. Modern IK solvers face a fundamental trade-off: analytical methods are fast but lack generality, while numerical optimization-based methods are broadly applicable but prone to local minima and high computational costs. To overcome this challenge, we introduce HJCD-IK, a GPU-accelerated, sampling-based hybrid solver. By pairing a novel orientation-aware greedy coordinate descent initialization with Jacobian-based polishing and a parallel collision filter, our method achieves up to order-of-magnitude gains in speed and accuracy over state-of-the-art solvers, consistently finding collision-free solutions on the accuracy-latency Pareto frontier, while producing a diverse distribution of high-quality samples. We validate our solver on a physical Franka manipulator and release our code open-source."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We introduce HJCD-IK, a GPU-accelerated, sampling-based hybrid solver. By pairing a novel orientation-aware greedy coordinate descent initialization with Jacobian-based polishing and a parallel collision filter, our method achieves up to order-of-magnitude gains in speed and accuracy over state-of-the-art solvers, consistently finding collision-free solutions on the accuracy-latency Pareto frontier, while producing a diverse distribution of high-quality samples. We validate our solver on a physical Franka manipulator and release our code open-source."

tags:
- Motion Planning
- Parallel Computing
- GPU
- Inverse Kinematics
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

