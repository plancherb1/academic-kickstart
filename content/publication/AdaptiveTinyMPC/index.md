---
title: "Robust and Efficient Embedded Convex Optimization through First-Order Adaptive Caching"
authors:
- IshaanMahajan
- admin
date: "2025-06-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
date: "2025-06-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In the *[2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)](https://www.iros25.org/)*"
publication_short: "In *IROS 2025*"

abstract: "Recent advances in Model Predictive Control (MPC) leveraging a combination of first-order methods, such as the Alternating Direction Method of Multipliers (ADMM), and offline precomputation and caching of select operations, have excitingly enabled real-time MPC on microcontrollers. Unfortunately, these approaches require the use of fixed hyperparameters, limiting their adaptability and overall performance. In this work, we introduce First-Order Adaptive Caching, which precomputes not only select matrix operations but also their sensitivities to hyperparameter variations, enabling online hyperparameter updates without full recomputation of the cache. We demonstrate the effectiveness of our approach on a number of dynamic quadrotor tasks, achieving up to a 63.4% reduction in ADMM iterations over the use of optimized fixed hyperparameters and approaching 70% of the performance of a full cache recomputation, while reducing the computational cost from O(n^3) to O(n^2) complexity. This performance enables us to perform figure-eight trajectories on a 27g tiny quadrotor under wind disturbances. We release our implementation open-source for the benefit of the wider robotics community."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "In this work, we introduce First-Order Adaptive Caching, which precomputes not only select matrix operations but also their sensitivities to hyperparameter variations, enabling online hyperparameter updates without full recomputation of the cache. We demonstrate the effectiveness of our approach on a number of dynamic quadrotor tasks, achieving up to a 63.4% reduction in ADMM iterations over the use of optimized fixed hyperparameters and approaching 70% of the performance of a full cache recomputation, while reducing the computational cost from O(n^3) to O(n^2) complexity. This performance enables us to perform figure-eight trajectories on a 27g tiny quadrotor under wind disturbances."

tags:
- Model Predictive Control
- Embedded Systems
- Edge Computing
- Quadrotor
- Adaptive Updates
- Numerical Optimziation

featured: false

awards: []

links:
  - name: "Website"
    url: "https://tinympc.org/"
  - name: "ICRA-25 Workshop Abstract"
    url: "https://aerial-robotics-workshop-icra.com/wp-content/uploads/2025/05/Poster9.pdf"
# url_pdf: 'https://arxiv.org/abs/2403.18149'
url_code: 'https://github.com/tinympc'
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
projects: [TinyRobots]
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

