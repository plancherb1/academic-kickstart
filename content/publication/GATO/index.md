---
title: "GATO: GPU-Accelerated and Batched Trajectory Optimization for Scalable Edge Model Predictive Control"
authors:
- AlexDu
- EmreAdabag
- GabrielBravo
- admin
date: "2026-06-01T10:00:01Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-09T10:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2026 International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)*
publication_short: In *ICRA 2026*

abstract: "While Model Predictive Control (MPC) delivers strong performance across robotics applications, solving the underlying (batches of) nonlinear trajectory optimization (TO) problems online remains computationally demanding. Existing GPU-accelerated approaches typically (i) parallelize a single solve to meet real-time deadlines, (ii) scale to very large batches at slower-than-real-time rates, or (iii) achieve speed by restricting model generality (e.g., point-mass dynamics or a single linearization). This leaves a large gap in solver performance for many state-of-the-art MPC applications that require real-time batches of tens to low-hundreds of solves. As such, we present GATO, an open source, GPU-accelerated, batched TO solver co-designed across algorithm, software, and computational hardware to deliver real-time throughput for these moderate batch size regimes. Our approach leverages a combination of block-, warp-, and thread-level parallelism within and across solves for ultra-high performance. We demonstrate the effectiveness of our approach through a combination of: simulated benchmarks showing speedups of 18-21x over CPU baselines and 1.4-16x over GPU baselines as batch size increases; case studies highlighting improved disturbance rejection and convergence behavior; and finally a validation on hardware using an industrial manipulator. We open source GATO to support reproducibility and adoption."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We present GATO, an open source, GPU-accelerated, batched TO solver co-designed across algorithm, software, and computational hardware to deliver real-time throughput for these moderate batch size regimes. Our approach leverages a combination of block-, warp-, and thread-level parallelism within and across solves for ultra-high performance. We demonstrate the effectiveness of our approach through a combination of: simulated benchmarks showing speedups of 18-21x over CPU baselines and 1.4-16x over GPU baselines as batch size increases; case studies highlighting improved disturbance rejection and convergence behavior; and finally a validation on hardware using an industrial manipulator. We open source GATO to support reproducibility and adoption."

tags:
- Model Predictive Control
- Parallel Computing
- GPU
- Linear Systems
- Iterative Methods
- Trajectory Optimization
featured: false

links:
# - name: TBD
#   url: "TBD"
url_pdf: 'https://arxiv.org/abs/2510.07625'
url_code: 'https://github.com/a2r-lab/GATO'
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

