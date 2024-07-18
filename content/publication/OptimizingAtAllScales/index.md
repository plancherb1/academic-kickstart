---
title: "Optimizing at All Scales: Edge (Non)linear Model Predictive Control from MCUs to GPUs"
authors:
- EmreAdabag
- XueyiBu
- KhaiNguyen
- SamSchoedel
- AnoushkaAlavilli
- MiloniDipakAtal
- WilliamGerard
- ElakhyaNedumaran
- ZacharyManchester
- admin
date: "2024-07-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop / Poster; 10 = Magazine Article
publication_types: ["9"]

# Publication name and optional abbreviated publication name.
publication: "In *[Frontiers of Optimization for Robotics](https://sites.google.com/robotics.utias.utoronto.ca/frontiers-optimization-rss24/home)* a Workshop at [Robotics: Sceince and Systems (RSS) 2024](https://roboticsconference.org/)"
publication_short: In *Frontiers of Optimization* at *RSS 2024*

abstract: "Model predictive control (MPC) is a powerful tool for controlling highly dynamic robotic systems subject to complex constraints. However, MPC, and its underlying (nonlinear) optimization algorithms, are often too computationally demanding to meet real-time rates for robotic platforms, both large and small. These problems are exacerbated by the end of Dennard Scaling and Moore's law, which have led to a utilization wall that limits the performance a single CPU chip can deliver. As such, we now need to look to the field of software performance engineering to co-design our solvers for their target hardware architectures. As such, in our recent works, by leveraging a combination of parallelism, approximation, and structure exploitation, we have enabled and accelerated (nonlinear) trajectory optimization solvers for real-time performance on non-standard computational hardware, ranging from microcontrollers (MCUs) to graphical processing units (GPUs). This has led to real-time MPC onboard an MCU powered 27g quadrotor for dynamic obstacle avoidance, as well as simulated whole-body nonlinear MPC at kHz rates for a GPU powered manipulator for high speed trajectory tracking."

# Summary. An optional shortened abstract. Can also be used as a summary for an extended abstract or poster etc.
summary: "In our recent works, by leveraging a combination of parallelism, approximation, and structure exploitation, we have enabled and accelerated (nonlinear) trajectory optimization solvers for real-time performance on non-standard computational hardware, ranging from microcontrollers (MCUs) to graphical processing units (GPUs). This has led to real-time MPC onboard an MCU powered 27g quadrotor for dynamic obstacle avoidance, as well as simulated whole-body nonlinear MPC at kHz rates for a GPU powered manipulator for high speed trajectory tracking."

tags:
- Model Predictive Control
- Parallel Computing
- GPU
- Embedded Systems
- Edge Computing
- MCU
- Linear Systems
- Iterative Methods
- Trajectory Optimization
featured: false

awards: []

links:
  - name: "Workshop Website"
    url: "https://sites.google.com/robotics.utias.utoronto.ca/frontiers-optimization-rss24/home"
  - name: "TinyMPC Website"
    url: "https://tinympc.org/"
  - name: "MPCGPU Website"
    url: "https://a2r-lab.org/publication/mpcgpu/"
url_pdf: 'https://drive.google.com/file/d/11rsDcUR1gz5DniZqbdAB2qbWXg80dHlv/view'
url_code: ''
url_dataset: ''
url_poster: 'files/2024_Optimizing_at_All_Scales_Poster.pdf'
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
projects: [AcceleratingRobotics,Optimization]
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

