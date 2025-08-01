---
title: "Polynomial and Parallelizable Preconditioning for Block Tridiagonal Positive Definite Matrix"
authors:
- ShaohuiYang
- ToshiyukiOhtsuka
- admin
- ColinJones
date: "2025-03-25T00:00:03Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *[Robotics and Automation Letters](https://www.ieee-ras.org/publications/ra-l)* 2025
# publication_short: In *RA-L* 2025

abstract: "The efficient solution of moderately large-scale linear systems arising from the KKT conditions in optimal control problems (OCPs) is a critical challenge in robotics. With the stagnation of Moore’s law, there is growing interest in leveraging GPU-accelerated iterative methods, and corresponding parallel preconditioners, to overcome these computational challenges. To improve the performance of such solvers, we introduce a parallel-friendly, parametrized multi-splitting polynomial preconditioner framework. We first construct and prove the optimal parametrization theoretically in terms of the least amount of distinct eigenvalues and the narrowest spectrum range. We then compare the theoretical time complexity of solving the linear system directly or iteratively. We finally show through numerical experiments how much the preconditioning improves the convergence of OCP linear systems solves."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "The efficient solution of moderately large-scale linear systems arising from the KKT conditions in optimal control problems (OCPs) is a critical challenge in robotics. With the stagnation of Moore’s law, there is growing interest in leveraging GPU-accelerated iterative methods, and corresponding parallel preconditioners, to overcome these computational challenges. To improve the performance of such solvers, we introduce a parallel-friendly, parametrized multi-splitting polynomial preconditioner framework. We first construct and prove the optimal parametrization theoretically in terms of the least amount of distinct eigenvalues and the narrowest spectrum range. We then compare the theoretical time complexity of solving the linear system directly or iteratively. We finally show through numerical experiments how much the preconditioning improves the convergence of OCP linear systems solves."

tags:
- Linear Systems
- Iterative Methods
- Preconditioning
- Trajectory Optimization
featured: false

awards: []

links:
  # - name: "TBD"
  #   url: "TBD"
url_pdf: 'https://arxiv.org/abs/2503.15269'
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

