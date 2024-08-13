---
title: "TinyMPC: Model-Predictive Control on Resource-Constrained Microcontrollers"
authors:
- KhaiNguyen
- SamSchoedel
- AnoushkaAlavilli
- admin
- ZacharyManchester
date: "2024-05-13T00:00:00Z"
doi: "10.1109/ICRA57147.2024.10610987"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2024 IEEE International Conference on Robotics and Automation (ICRA)](http://ieee-icra.org/)*
publication_short: In *ICRA 2024*

abstract: "Model-predictive control (MPC) is a powerful tool for controlling highly dynamic robotic systems subject to complex constraints. However, MPC is computationally demanding, and is often impractical to implement on small, resource-constrained robotic platforms. We present TinyMPC, a high-speed MPC solver with a low memory footprint targeting the microcontrollers common on small robots. Our approach is based on the alternating direction method of multipliers (ADMM) and leverages the structure of the MPC problem for efficiency. We demonstrate TinyMPC both by benchmarking against the state-of-the-art solver OSQP, achieving nearly an order of magnitude speed increase, as well as through hardware experiments on a 27 g quadrotor, demonstrating high-speed trajectory tracking and dynamic obstacle avoidance."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "Model-predictive control (MPC) is a powerful tool for controlling highly dynamic robotic systems subject to complex constraints. However, MPC is computationally demanding, and is often impractical to implement on small, resource-constrained robotic platforms. We present TinyMPC, a high-speed MPC solver with a low memory footprint targeting the microcontrollers common on small robots. Our approach is based on the alternating direction method of multipliers (ADMM) and leverages the structure of the MPC problem for efficiency. We demonstrate TinyMPC both by benchmarking against the state-of-the-art solver OSQP, achieving nearly an order of magnitude speed increase, as well as through hardware experiments on a 27 g quadrotor, demonstrating high-speed trajectory tracking and dynamic obstacle avoidance."

tags:
- Model Predictive Control
- Embedded Systems
- Edge Computing
- Quadrotor

featured: true

awards:
- Best Paper in Automation at IEEE ICRA 2024
- Finalist for Best Conference Paper at IEEE ICRA 2024
- Finalist for Best Student Paper at IEEE ICRA 2024

links:
  - name: "Website"
    url: "https://tinympc.org/"
url_pdf: 'https://arxiv.org/abs/2310.16985'
url_code: 'https://github.com/tinympc'
url_dataset: ''
url_poster: 'files/TinyMPC_ICRA_Poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=NKOrRyhcr6w'

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

