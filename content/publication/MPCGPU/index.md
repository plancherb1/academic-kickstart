---
title: "MPCGPU: Real-Time Nonlinear Model Predictive Control through Preconditioned Conjugate Gradient on the GPU"
authors:
- EmreAdabag
- MiloniDipakAtal
- WilliamGerard
- admin
date: "2024-05-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2024 IEEE International Conference on Robotics and Automation (ICRA)](http://ieee-icra.org/)*
publication_short: In *ICRA 2024*

abstract: "Nonlinear Model Predictive Control (NMPC) is a state-of-the-art approach for locomotion and manipulation which leverages trajectory optimization at each control step. While the performance of this approach is computationally bounded, implementations of direct trajectory optimization that use iterative methods to solve the underlying moderately-large and sparse linear systems, are a natural fit for parallel hardware acceleration. In this work, we introduce MPCGPU, a GPU-accelerated, real-time NMPC solver that leverages an accelerated preconditioned conjugate gradient (PCG) linear system solver at its core. We show that MPCGPU increases the scalability and real-time performance of NMPC, solving larger problems, at faster rates. In particular, for tracking tasks using the Kuka IIWA manipulator, MPCGPU is able to scale to kilohertz control rates with trajectories as long as 512 knot points. This is driven by a custom PCG solver which outperforms state-of-the-art, CPU-based, linear system solvers by at least 10x for a majority of solves and 3.6x on average."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We introduce MPCGPU, a GPU-accelerated, real-time NMPC solver that leverages an accelerated preconditioned conjugate gradient (PCG) linear system solver at its core. We show that MPCGPU increases the scalability and real-time performance of NMPC, solving larger problems, at faster rates. In particular, for tracking tasks using the Kuka IIWA manipulator, MPCGPU is able to scale to kilohertz control rates with trajectories as long as 512 knot points. This is driven by a custom PCG solver which outperforms state-of-the-art, CPU-based, linear system solvers by at least 10x for a majority of solves and 3.6x on average."

tags:
- Model Predictive Control
- Parallel Computing
- GPU
- Linear Systems
- Iterative Methods
- Trajectory Optimization
featured: true

awards:
- Best Poster Award at the 2024 IEEE TC on Model Based Optimization for Robotics Virtual Poster Session

links:
  # - name: "TBD"
  #   url: "TBD"
url_pdf: 'https://arxiv.org/abs/2309.08079'
url_code: 'https://github.com/a2r-lab/MPCGPU'
url_dataset: ''
url_poster: 'files/2024_MPCGPU_ICRA_Poster_vertical_v2.pdf'
url_project: ''
url_slides: 'files/2024_ICRA_MPCGPU_SymStair_Slides.pdf'
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
projects: [AcceleratingRobotics]
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

