---
title: "Code Generation for Conic Model-Predictive Control on Microcontrollers with TinyMPC"
authors:
- SamSchoedel
- KhaiNguyen
- ElakhyaNedumaran
- admin
- ZacharyManchester
date: "2024-03-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *[2024 IEEE Conference on Decision and Control (CDC)](https://cdc2024.ieeecss.org/)*
# publication_short: In *CDC 2024*

abstract: "Conic constraints appear in many important control applications like legged locomotion, robotic manipulation, and autonomous rocket landing. However, current solvers for conic optimization problems have relatively heavy computational demands in terms of both floating-point operations and memory footprint, making them impractical for use on small embedded devices. We extend TinyMPC, an open-source, high-speed solver targeting low-power embedded control applications, to handle second-order cone constraints. We also present code-generation software to enable deployment of TinyMPC on a variety of microcontrollers. We benchmark our generated code against state-of-the-art embedded QP and SOCP solvers, demonstrating a two-order-of-magnitude speed increase over ECOS while consuming less memory. Finally, we demonstrate TinyMPC's efficacy on the Crazyflie, a lightweight, resource-constrained quadrotor with fast dynamics. TinyMPC and its code-generation tools are publicly available at [tinympc.org](https://tinympc.org/)."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "We extend TinyMPC, an open-source, high-speed solver targeting low-power embedded control applications, to handle second-order cone constraints. We also present code-generation software to enable deployment of TinyMPC on a variety of microcontrollers. We benchmark our generated code against state-of-the-art embedded QP and SOCP solvers, demonstrating a two-order-of-magnitude speed increase over ECOS while consuming less memory. Finally, we demonstrate TinyMPC's efficacy on the Crazyflie, a lightweight, resource-constrained quadrotor with fast dynamics. TinyMPC and its code-generation tools are publicly available at [tinympc.org](https://tinympc.org/)."

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

