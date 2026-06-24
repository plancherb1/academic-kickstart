---
title: "TurboMPC: Fast, Scalable, and Differentiable Model Predictive Control on the GPU"
authors:
- GabrielBravo
- JianghanZhang
- ZacharyPestrikov
- admin
- ThomasLew
date: "2026-06-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-06-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: #"In [IEEE Transactions on Robotics](https://www.ieee-ras.org/publications/t-ro/) 2026" 
publication_short: #"In *T-RO* 2026"

abstract: "Robotics increasingly relies on GPUs for parallel simulation, large-scale learning, and neural-network inference. For model predictive control (MPC) to scale with this paradigm, solvers must run efficiently on this hardware while remaining fast, differentiable, and compatible with expressive MPC formulations used in robotics. We present TurboMPC, a differentiable MPC solver that runs entirely on the GPU and supports state and control inequality constraints, implicit integrators, cross-time-coupled costs, and slack variables. TurboMPC combines sequential quadratic programming (SQP), an alternating direction method of multipliers (ADMM) inner solver, implicit differentiation, and a co-designed JAX-CUDA implementation for efficiency and ease of use. In simulation, we validate TurboMPC on constrained planning, humanoid imitation learning, and reinforcement learning with neural-network cost function tasks, achieving up to 15x and 58x speedups over state-of-the-art CPU and GPU differentiable solvers, respectively. We deploy TurboMPC on a full-scale car for minimum-time racing and find that batched, GPU-accelerated tuning of MPC parameters via Bayesian optimization yields significantly faster driving than a hand-tuned baseline. TurboMPC also scales to planning horizons of over 8000 knot points while maintaining control of the vehicle. We open-source TurboMPC at https://github.com/ToyotaResearchInstitute/turbompc."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We present TurboMPC, a differentiable MPC solver that runs entirely on the GPU and supports state and control inequality constraints, implicit integrators, cross-time-coupled costs, and slack variables. TurboMPC combines sequential quadratic programming (SQP), an alternating direction method of multipliers (ADMM) inner solver, implicit differentiation, and a co-designed JAX-CUDA implementation for efficiency and ease of use. In simulation, we achieve up to 15x and 58x speedups over state-of-the-art CPU and GPU differentiable solvers, respectively. We deploy TurboMPC on a full-scale car for minimum-time racing and scale to planning horizons of over 8000 knot points while maintaining control of the vehicle. We open-source TurboMPC at https://github.com/ToyotaResearchInstitute/turbompc"

tags:
- Hardware Acceleration
- Parallel Computing
- GPU
- MPC
- Differentiable
featured: false

awards: []

links:
  - name: "ICRA-26 Workshop Abstract"
    url: "https://openreview.net/pdf?id=u8hZkTX5rs"
  # - name: "ICRA-26 Workshop Website"
  #   url: "https://sites.google.com/robotics.utias.utoronto.ca/icra26-frontiers-optimization/home"
url_pdf: 'https://arxiv.org/abs/2606.24039'
url_code: 'https://github.com/toyotaResearchInstitute/turbompc'
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

