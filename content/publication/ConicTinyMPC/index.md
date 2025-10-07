---
title: "Code Generation and Conic Constraints for Model-Predictive Control on Microcontrollers with Conic-TinyMPC"
authors:
- IshaanMahajan
- KhaiNguyen
- SamSchoedel
- ElakhyaNedumaran
- MoisesMata
- admin
- ZacharyManchester
date: "2025-10-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *[2026 IEEE International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)*
# publication_short: In *ICRA 2026*

abstract: "Model-predictive control (MPC) is a powerful framework for controlling dynamic systems under constraints, but it remains challenging to deploy on resource-constrained platforms, especially for problems involving conic constraints. To address this, we extend recent work developing fast, structure-exploiting, cached ADMM solvers for embedded applications, to provide support for second-order cones, as well as `C++` code generation from `Python`, `MATLAB`, and `Julia` for easy deployment. Microcontroller benchmarks show that our solver provides up to a two-order-of-magnitude speedup, ranging from 10.6x to 142.7x, over state-of-the-art embedded solvers on QP and SOCP problems, and enables us to fit order-of-magnitude larger problems in memory. We validate our solver's deployed performance through simulation and hardware experiments, including conically-constrained trajectory tracking on a 27g Crazyflie quadrotor. To get started with Conic-TinyMPC, visit our documentation, examples, and the open-source codebase at [tinympc.org](https://tinympc.org/)."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We extend TinyMPC, an open-source, high-speed solver targeting low-power embedded control applications, to provide support for second-order cones, as well as `C++` code generation from `Python`, `MATLAB`, and `Julia` for easy deployment. Microcontroller benchmarks show that our solver provides up to a two-order-of-magnitude speedup, ranging from 10.6x to 142.7x, over state-of-the-art embedded solvers on QP and SOCP problems, and enables us to fit order-of-magnitude larger problems in memory. We validate our solver's deployed performance through simulation and hardware experiments, including conically-constrained trajectory tracking on a 27g Crazyflie quadrotor. To get started with Conic-TinyMPC, visit our documentation, examples, and the open-source codebase at [tinympc.org](https://tinympc.org/)."

tags:
- Model Predictive Control
- Embedded Systems
- Edge Computing
- Quadrotor
- Code Generation
- Conic Constraints

featured: false

awards: []

links:
  - name: "Website"
    url: "https://tinympc.org/"
url_pdf: 'https://arxiv.org/abs/2403.18149'
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

