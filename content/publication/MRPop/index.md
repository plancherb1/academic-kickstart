---
title: "MR. POP: Multi-Robot Parallel Optimizing Planner for Almost-Surely Asymptotically Optimal Planning"
authors:
- ChihHuang
- RoyXing
- admin
- ZacharyKingston
date: "2026-09-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: "In *[Frontiers of Optimization for Robotics](https://sites.google.com/robotics.utias.utoronto.ca/icra26-frontiers-optimization/home)* a Workshop at [2026 International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)"
# publication_short: In *Frontiers of Optimization* at *ICRA 2026*

abstract: "Finding globally optimal paths remains a fundamental challenge in multi-robot motion planning. Despite acceleration of almost-surely asymptotically optimal (a.s.a.o.) planners via CPU-based parallelism, achieving both probabilistic convergence guarantees and strong computational performance, these algorithms still struggle to scale to multi-robot settings. As such, we introduce MR. POP, a GPU-based a.s.a.o. multi-robot planner based on dRRT and the AO-x meta-algorithm. MR. POP uses large-scale GPU-based SIMT-parallelism to simultaneously run hundreds of roadmap construction and tree search iterations with underlying parallel nearest neighbor search and collision checking operations. We show that this enables MR. POP to become the only planner achieving a 100% solve rate while being faster than state-of-the-art a.s.a.o. planners in multi-robot systems up to 35-DOF. MR. POP also raises the success rate of downstream motion optimizers (e.g., from 4% to 72%), by creating high-quality, diverse seeds that help avoid local minima."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We introduce MR. POP, a GPU-based a.s.a.o. multi-robot planner based on dRRT and the AO-x meta-algorithm. MR. POP uses large-scale GPU-based SIMT-parallelism to simultaneously run hundreds of roadmap construction and tree search iterations with underlying parallel nearest neighbor search and collision checking operations. We show that this enables MR. POP to become the only planner achieving a 100% solve rate while being faster than state-of-the-art a.s.a.o. planners in multi-robot systems up to 35-DOF. MR. POP also raises the success rate of downstream motion optimizers (e.g., from 4% to 72%), by creating high-quality, diverse seeds that help avoid local minima."

tags:
- Motion Planning
- Parallel Computing
- GPU
- AO-x
- a.s.a.o.
featured: false

awards: []

links:
  # - name: "Workshop Website"
  #   url: "https://sites.google.com/robotics.utias.utoronto.ca/icra26-frontiers-optimization/home"
  # - name: "Project Website"
  #   url: "https://commalab.org/papers/pRRTC/"
url_pdf: 'https://arxiv.org/abs/2609.30644'
url_code: 'https://github.com/CoMMALab/MR.POP'
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

