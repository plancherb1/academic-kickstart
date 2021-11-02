---
title: "A Performance Analysis of Parallel Differential Dynamic Programming on a GPU"
authors:
- admin
- ScottKuindersma
date: "2018-12-11T00:00:00Z"
doi: "10.1007/978-3-030-44051-0_38"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2018 Workshop on the Algorithmic Foundations of Robotics](https://parasol.tamu.edu/wafr/wafr2018/)*
publication_short: In *WAFR 2018*

abstract: Parallelism can be used to significantly increase the throughput of computationally expensive algorithms. With the widespread adoption of parallel computing platforms such as GPUs, it is natural to consider whether these architectures can benefit robotics researchers interested in solving trajectory optimization problems online. Differential Dynamic Programming (DDP) algorithms have been shown to achieve some of the best timing performance in robotics tasks by making use of optimized dynamics methods and CPU multi-threading. This paper aims to analyze the benefits and tradeoffs of higher degrees of parallelization using a multiple-shooting variant of DDP implemented on a GPU. We describe our implementation strategy and present results demonstrating its performance compared to an equivalent multi-threaded CPU implementation using several benchmark control tasks. Our results suggest that GPU-based solvers can offer increased per-iteration computation time and faster convergence in some cases, but in general tradeoffs exist between convergence behavior and degree of algorithm-level parallelism.

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: We analyze the benefits and tradeoffs of higher degrees of parallelization using a multiple-shooting variant of DDP implemented on a GPU. We describe our implementation strategy and present results demonstrating its performance compared to an equivalent multi-threaded CPU implementation using several benchmark control tasks. Our results suggest that GPU-based solvers can offer increased per-iteration computation time and faster convergence in some cases, but in general tradeoffs exist between convergence behavior and degree of algorithm-level parallelism.

tags:
- Model Predictive Control
- Differential Dynamic Programming
- Parallel Computing
- GPU
featured: false

links:
#- name: Publication
#  url: https://link.springer.com/chapter/10.1007/978-3-030-44051-0_38
url_pdf: 'files/GPU_DDP_WAFR_paper.pdf'
url_code: 'http://bitly.com/ParallelDDP'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'files/GPU_DDP_WAFR_presentation.pdf'
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

