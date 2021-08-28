---
title: "Robomorphic Computing: A Design Methodology for Domain-Specific Accelerators Parameterized by Robot Morphology"
authors:
- SabrinaNeuman
- admin
- ThomasBourgeat
- ThierryTambe
- SriniDevadas
- VijayJanapaReddi
date: "2021-04-12T00:00:00Z"
doi: "10.1145/3445814.3446746"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[2021 Architectural Support for Programming Languages and Operating Systems](https://asplos-conference.org/)*
publication_short: In *ASPLOS 2021*

abstract: Robotics applications have hard time constraints and heavy computational burdens that can greatly benefit from domain-specific hardware accelerators. For the latency-critical problem of robot motion planning and control, there exists a performance gap of at least an order of magnitude between joint actuator response rates and state-of-the-art software solutions. Hardware acceleration can close this gap, but it is essential to define automated hardware design flows to keep the design process agile as applications and robot platforms evolve. To address this challenge, we introduce robomorphic computing, a methodology to transform robot morphology into a customized hardware accelerator morphology. We (i) present this design methodology, using robot topology and structure to exploit parallelism and matrix sparsity patterns in accelerator hardware; (ii) use the methodology to generate a parameterized accelerator design for the gradient of rigid body dynamics, a key kernel in motion planning; (iii) evaluate FPGA and synthesized ASIC implementations of this accelerator for an industrial manipulator robot; and (iv) describe how the design can be automatically customized for other robot models. Our FPGA accelerator achieves speedups of 8x and 86x over CPU and GPU when executing a single dynamics gradient computation. It maintains speedups of 1.9x to 2.9x over CPU and GPU, including computation and I/O round-trip latency, when deployed as a coprocessor to a host CPU for processing multiple dynamics gradient computations. ASIC synthesis indicates an additional 7.2x speedup for single computation latency. We describe how this principled approach generalizes to more complex robot platforms, such as quadrupeds and humanoids, as well as to other computational kernels in robotics, outlining a path forward for future robomorphic computing accelerators.

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: We introduce robomorphic computing; a methodology to transform robot morphology into a customized hardware accelerator morphology. In this work, we (i) present this design methodology; (ii) use the methodology to generate a parameterized accelerator design for the gradient of rigid body dynamics; (iii) evaluate FPGA and synthesized ASIC implementations; and (iv) describe how the design can be automatically customized for other robot models. Our FPGA accelerator achieves speedups of 8x and 86x over CPU and GPU latency, and maintains an overall speedup of 1.9x to 2.9x deployed in an end-to-end coprocessor system. ASIC synthesis indicates an additional factor of 7.2x.

tags:
- Hardware Acceleration
- Hardware-Software Co-Design
- FPGA
- Robotics
featured: false

links:
- name: Extended Abstract
  url: 'https://asplos-conference.org/abstracts/asplos21-paper857-extended_abstract.pdf'
url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3445814.3446746'
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

