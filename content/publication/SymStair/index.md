---
title: "Symmetric Stair Preconditioning of Linear Systems for Parallel Trajectory Optimization"
authors:
- XueyiBu
- admin
date: "2023-09-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *[2024 IEEE International Conference on Robotics and Automation (ICRA)](http://ieee-icra.org/)*
# publication_short: In *ICRA 2024*

abstract: "There has been a growing interest in parallel strategies for solving trajectory optimization problems. One key step in many algorithmic approaches to trajectory optimization is the solution of moderately-large and sparse linear systems. Iterative methods are particularly well-suited for parallel solves of such systems. However, fast and stable convergence of iterative methods is reliant on the application of a high-quality preconditioner that reduces the spread and increase the clustering of the eigenvalues of the target matrix. To improve the performance of these approaches, we present a new parallel-friendly symmetric stair preconditioner. We prove that our preconditioner has advantageous theoretical properties when used in conjunction with iterative methods for trajectory optimization such as a more clustered eigenvalue spectrum. Numerical experiments with typical trajectory optimization problems reveal that as compared to the best alternative parallel preconditioner from the literature, our symmetric stair preconditioner provides up to a 34% reduction in condition number and up to a 25% reduction in the number of resulting linear system solver iterations."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "In this work we present a new parallel-friendly symmetric stair preconditioner. We prove that our preconditioner has advantageous theoretical properties when used in conjunction with iterative methods for trajectory optimization such as a more clustered eigenvalue spectrum. Numerical experiments with typical trajectory optimization problems reveal that as compared to the best alternative parallel preconditioner from the literature, our symmetric stair preconditioner provides up to a 34% reduction in condition number and up to a 25% reduction in the number of resulting linear system solver iterations."

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
url_pdf: 'https://arxiv.org/abs/2309.06427'
url_code: 'https://github.com/A2R-Lab/SymStair/'
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
projects: [AcceleratingRobotics,RobustTrajopt]
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

