---
title: "Parallel Dynamic Programming for Conic Linear Quadratic Control"
authors:
- LuyaoZhang
- GabrielBravo
- admin
- SergioGrammatico
date: "2026-08-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-06-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[23rd International Federation of Automatic Control World Congress (IFAC)](https://www.ifac2026.org/)*
publication_short: In *IFAC 2026*

abstract: Linear Quadratic (LQ) control problems are at the heart of linear control theory and Model Predictive Control (MPC). While performant, standard approaches to solving such problems are inherently serial, limiting real-time scalability despite the parallel computing power available on modern multi-core CPUs. Contributing to addressing this challenge and motivated by "divide and conquer" strategies, we present a parallel-in-time approach that solves computationally demanding conic optimal control problems through the use of the alternating direction method of multipliers (ADMM). In particular, we formulate the inner primal update of ADMM as an LQ problem and split the reformulated problem along the time horizon. This enables us to derive a variant of the Riccati recursion using dynamic programming to solve each subproblem in parallel. Numerical benchmarks on two real-world applications demonstrate as much as a 5x speedup compared to existing related approaches on multi-core CPU hardware.

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: We present a parallel-in-time approach that solves computationally demanding conic optimal control problems through the use of the alternating direction method of multipliers (ADMM). In particular, we formulate the inner primal update of ADMM as an LQ problem and split the reformulated problem along the time horizon. This enables us to derive a variant of the Riccati recursion using dynamic programming to solve each subproblem in parallel. Numerical benchmarks on two real-world applications demonstrate as much as a 5x speedup compared to existing related approaches on multi-core CPU hardware.

tags:
- Differential Dynamic Programming
- Parallel Computing
featured: false

links:
#- name: Publication
#  url: TBD
url_pdf: 'https://arxiv.org/abs/2606.24632'
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

