---
title: "AccelMPC: High-Rate, Low-Power FPGA-Accelerated Model Predictive Control for Tiny Drones"
authors:
- AndreaGrillo
- admin
date: "2026-09-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: "In *[Frontiers of Optimization for Robotics](https://sites.google.com/robotics.utias.utoronto.ca/icra26-frontiers-optimization/home)* a Workshop at [2026 International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)"
# publication_short: In *Frontiers of Optimization* at *ICRA 2026*

abstract: "Unlocking the potential of tiny aerial robots requires order of magnitude improvements in the performance of embedded edge control. In particular, although recent cached model predictive control (MPC) solvers can handle the fast system dynamics and complex constraints required for agile drone flight, their computational demands remain prohibitive for resource-constrained robots, forcing prior implementations to operate at reduced control rates. AccelMPC overcomes this challenge through an end-to-end co-design approach that jointly optimizes the solver algorithm, numerical representation, hardware mapping, and physical integration. AccelMPC pairs a co-designed FPGA-accelerated alternating direction method of multipliers (ADMM)-based MPC solver with a custom 6g PCB, providing high-bandwidth communication for deployment on a 35g Crazyflie. Hardware experiments demonstrate 1 kHz onboard constrained MPC with dynamic obstacles, up to 15.6x faster solve times and 195.4x improvement in energy-delay product over state-of-the-art embedded microcontroller-based solvers, all while scaling to optimization problems with over 20,000 optimization variables and a comparable number of constraints. We release our PCB design files, firmware, and FPGA solver code open source."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "AccelMPC pairs a co-designed FPGA-accelerated alternating direction method of multipliers (ADMM)-based MPC solver with a custom 6g PCB, providing high-bandwidth communication for deployment on a 35g Crazyflie. Hardware experiments demonstrate 1 kHz onboard constrained MPC with dynamic obstacles, up to 15.6x faster solve times and 195.4x improvement in energy-delay product over state-of-the-art embedded microcontroller-based solvers, all while scaling to optimization problems with over 20,000 optimization variables and a comparable number of constraints. We release our PCB design files, firmware, and FPGA solver code open source."

tags:
- Hardware Acceleration
- Parallel Computing
- FPGA
- MPC
featured: false

awards: []

links:
  # - name: "Workshop Website"
  #   url: "https://sites.google.com/robotics.utias.utoronto.ca/icra26-frontiers-optimization/home"
  # - name: "Workshop PDF"
  #   url: "https://openreview.net/pdf?id=rWyuDxXkeE"
url_pdf: 'https://arxiv.org/abs/2609.09380'
url_code: ''
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
projects: [Accelerators, TinyRobots]
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