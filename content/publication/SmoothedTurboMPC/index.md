---
title: "Efficient Learning of Differentiable MPC Policies on the GPU via Smoothed ADMM and First-Order Reinforcement Learning"
authors:
- JianghanZhang
- RolandSchwan
- GabrielBravo
- JohnZhang
- ThomasLew
- admin
date: "2026-10-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: #"In [IEEE Transactions on Robotics](https://www.ieee-ras.org/publications/t-ro/) 2026" 
publication_short: #"In *T-RO* 2026"

abstract: "Differentiable model predictive control (MPC) enables structured, constraint-aware policies to be optimized endto-end. However, learning MPC policies faces two bottlenecks: (1) nonsmooth sensitivities at active-set transitions and (2) expensive policy evaluation, since each requires an optimization solve. We first introduce SmoothedTurboMPC, a GPU-parallel differentiable MPC solver combining sequential quadratic programming (SQP) with a log-barrier-smoothed alternating direction method of multipliers (ADMM) inner solver. Its design enables smooth gradients, exact sensitivities at convergence, and efficient execution on GPUs. Second, to efficiently train MPC policies, we pair our solver with first-order reinforcement learning (FORL) using Short-Horizon Actor-Critic (SHAC), which reuses rollout MPC solutions instead of repeatedly re-evaluating them. Comparisons with state of the art solvers show that the approach achieves up to 4.4× higher end-to-end training throughput. On a vehicle racing task, our method achieves higher returns than MPC PPO with a 46× speedup, training on 3.3 million transitions in only 7 minutes. Finally, we use the framework to train a more reliable MPC racing policy via RL with domain randomization, and validate it on a full-scale race car. We integrate our advances into the open-source TurboMPC solver."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We first introduce SmoothedTurboMPC, a GPU-parallel differentiable MPC solver combining sequential quadratic programming (SQP) with a log-barrier-smoothed alternating direction method of multipliers (ADMM) inner solver. Its design enables smooth gradients, exact sensitivities at convergence, and efficient execution on GPUs. Second, to efficiently train MPC policies, we pair our solver with first-order reinforcement learning (FORL) using Short-Horizon Actor-Critic (SHAC), which reuses rollout MPC solutions instead of repeatedly re-evaluating them. Comparisons with state of the art solvers show that the approach achieves up to 4.4× higher end-to-end training throughput. On a vehicle racing task, our method achieves higher returns than MPC PPO with a 46× speedup, training on 3.3 million transitions in only 7 minutes. Finally, we use the framework to train a more reliable MPC racing policy via RL with domain randomization, and validate it on a full-scale race car. We integrate our advances into the open-source TurboMPC solver."

tags:
- Hardware Acceleration
- Parallel Computing
- GPU
- MPC
- Differentiable
- Reinforcement Learning
- SHAC
featured: false

awards: []

links:
  # - name: "TBD"
  #   url: "TBD"
url_pdf: 'https://arxiv.org/abs/2611.09937'
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

